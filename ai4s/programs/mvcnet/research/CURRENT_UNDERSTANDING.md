# MVCNet 当前研究认识

## 基模设计先验

本节是稳定的来源与事实索引：作者论文陈述、阅读解释、本地实现及本 Program 已有结果分别按下列直接来源理解，不能互相替代。v4.0 的 L3 在“阅读与研究认识入口”链接到本节；本节本身不记录活动状态、权限或当前 Run 结论。
Paper X-Ray §§2–3 与 Note「方法主线」描述作者的训练/分类路径；本地对应以 src/baselines/mvcnet.py:212、augmentation_readout/train.py:28 及本总览 U1 和 next_auxiliary_20261029/CONTEXT_MANIFEST.json 为准。

- **两条分类路径。** 论文 Algorithm 1 对未增强试次做 CNN／Transformer 特征拼接。本地规范 UEP 与 VCN-P1 分类只走 CNN／IFNet 和分类头，Transformer 经训练对比目标影响参数。训练期梯度干预与部署分类修改对应不同对照。（下方本地实现核对、原文算法与已绑定适配器）
- **配套目标的竞争解释。** CVC 与 CMC 会共同影响原生训练；切断一侧 CMC 梯度仍可能经 CVC 跨支影响。保留 CVC 的同配方控制更能识别接收端改动。（下方 U7 及梯度审计）

## 基模来源与认识边界

同一论文的加工材料不作独立证据计数。路径从本文件位置解析：

| 材料 | 用途 |
|---|---|
| [MVCNet-paper.md](../../../../refs/paper-cards/mvcnet/MVCNet-paper.md) | 原文读取材料 |
| [MVCNet-paper-card.md](../../../../refs/paper-cards/mvcnet/MVCNet-paper-card.md) | 贡献与证据边界 |
| [MVCNet-paper-xray.md](../../../../refs/paper-cards/mvcnet/MVCNet-paper-xray.md) | 设计推演 |
| [MVCNet-note.md](../../../../refs/paper-cards/mvcnet/MVCNet-note.md) | 综合理解 |

### 基模设计理解

作者报告：每条 trial 生成 raw 与三种增强视图，经 CNN、Transformer 两分支处理；分类 CE、CVC 跨视图约束和 CMC 跨编码器约束共同训练（Paper X-Ray §2、§3；Note「方法主线」）。阅读解释：CVC 想稳定视图内表示，CMC 想协调两种编码器；CMC 可能也压缩分支独有信息，论文没有直接验证互补性。当前实现须以 `src/baselines/mvcnet.py` 及具体 proposed 文件为准；例如 P1 将四种视图的 BN 状态分开，但仍使用普通 BatchNorm，不能将“视图隔离”推成训练/推理一致性。原文报告仅适用于作者所列数据与协议；本地支持范围见下方 U 证据及其 Evidence ID。关键未决项是完整方法相对强基线的增量、组件归因与适用范围；新证据若无稳定宿主增量，不应将其命名为主创新。

下文是当前可修正综合。作者报告、阅读推断、代码行为、本地观测应按所引来源理解；MVCNet的视图隔离和配套监督不能单凭结构推断互补机制成立。重要结论应能回到原文/源码及Evidence ID，并说明适用范围和何种新证据会改变取舍。历史轮次保留在原报告；其中运行状态只代表记录时点，当前状态以 STATE.yaml 为准。

本地实现核对（2026-10-29，2026-11-12复核）。论文 v4 Algorithm 1 第 25 步对未增强测试试次采用 CNN／Transformer 特征拼接分类。本地规范 UEP baseline 的 `MVCNetAdapter.forward`（`src/baselines/mvcnet.py:212`）和本地留存 native runner（`ai4s/_work/augmentation_readout_source_r1/ai4s/programs/mvcnet/research/augmentation_readout/train.py:28`）均走 CNN/IFNet → 分类头。已核对的 VCN-P1 和 VBR-R1 改动 IFNet 归一化，仍走这一分类路径。Transformer／投影器经训练对比损失影响参数；本地 CVC 沿 batch 轴拼接两种分支表示并包含跨分支负项，切断 CMC 一侧的梯度仍可能保留 CVC 的跨分支影响。其他变体绑定其实际 adapter 和调用路径。[2026-10-29 的来源与源码哈希](next_auxiliary_20261029/CONTEXT_MANIFEST.json)。

## 当前综合与关键缺口

VCN-P1 仍是有范围限制的支架，主创新资格尚未建立。最新固定 VBR 校正未形成稳定支架增量，后续选择应返回主方法证据、强对照与写作缺口；不能默认继续换归一化配方。反例与范围见下方 U2–U5，U5 的原报告保留冻结门与结论。改变此判断需要有实质新依据且符合关闭边界的新设计及合格证据，不能改 seed／日程救援已关闭实例。

以下保留设计时的认识与直接依据；其中“本轮”“选择 VBR”是历史，不是新行动安排。当前运行状态及新工作链只看 State 与 Prompt Index。

## 拟议主线与缺口

拟议主线是：增强视图采用与其统计分布相符的训练归一化，同时保护 raw-only 部署路径。VCN-P1 是有范围限制的支架，不能据此称论文主创新已经成立。主方法的新颖性、规范完整方法比较与适用范围仍有缺口。本轮按用户要求设计辅助方向，其投入理由必须是解决支架的具体局限，而不是再增加一个模块。

## U1：视图间的状态隔离不等于视图内部的训练／推理一致

源码 `src/models/proposed/vcn_p1_mvcnet.py` 中 P1 为 raw/flip/freq/cr 分离 running state 和 affine，但各 bank 仍调用普通 BatchNorm1d。训练使用当前 batch 统计、eval 使用 running 统计是实际实现行为；它在本任务上是否构成有害差异尚未证实。`VCN-P1-S8-SCOPED-2026-08-28` 的角色仅用于继承支架身份和既有支持范围，不用其历史 LOSO 效果选择新配置。`PROGRAM.yaml` 已登记 P1 稳定性 seeds 7..20 为 SATURATED，不再增加同一稳定性重复。

设计后果：允许研究视图内的训练归一化校正，但候选须独立命名；校正关闭恢复 P1，不能把新方法沿称原 P1。相关论文缺口是支架的部署一致性，而非另一个分类器。

## U2：分离增强读出尚未提供稳定的支架增量

`AI4S-MVCNET-mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2`，直接来源 `augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/REPORT.md`。七源开发主比较 P0−S0 +0.675154pp，但两 seed 为 −0.057870/+1.408179pp，仅4/9被试正向，冻结判定 NO_SIGNAL；不能以均值或 CE 改善补偿失败门。控制比较也未建立按增强类型分头的必要性。

该轮当时的运输与标准 intake 差异见 [原分析](augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/REPORT.md)，不由版本激活抹掉；不从该历史快照判断当前运行。

设计后果：关闭 augmentation-readout-separation-v01 精确实例，不改头数、分组、权重或 seed 救援；新方向不以“共享头冲突已证明”为前提。相关缺口是稳定增量与归因。

## U3：源信息可读、CE改善与可转移效用是不同问题

直接 evidence IDs：`AI4S-MVCNET-mvcnet-srtd-d0-diagnostic-lab10-r1`、`AI4S-MVCNET-mvcnet-srtd-t1-diagnostic-lab10-r2`、`AI4S-MVCNET-mvcnet-srtd-c1-diagnostic-lab10-r1`。各自同名 `_decision.yaml` 显示 D0 为 DIAGNOSTIC_SUPPORT，T1/C1 为 INSUFFICIENT_DIAGNOSTIC_SUPPORT；源内读出可拟合不能推出跨源可转移。`AI4S-MVCNET-mvcnet-source-excluded-distillation-screen-lab10-r4` 的 `source_excluded_distillation/analysis_r4/FOLLOW_UP.md` 保留效用门通过、对机制控制的覆盖门失败；`AI4S-MVCNET-mvcnet-source-class-relation-screen-ccmu-r6` 的 `source_class_relation/analysis_r6/REPORT.md` 保留宿主增量不足，弱控制优势不能替代它。

设计后果：本轮不选择 teacher、源路由、类关系或新头；新归一化设计不借这些结果声称机制缺陷已证实。必须同时比较宿主增量和通用归一化改动，防止把一般训练改善称为 VCN 特有互补。

## U4：负结果关闭精确干预，工程失败不否定科学机制

`AI4S-MVCNET-mvcnet-source-head-meta-screen-ccmu-r4` → `source_head_meta/analysis_r4/PRECISE_CLOSURE.json`；`AI4S-MVCNET-mvcnet-source-class-mean-alignment-screen-ccmu-r1` → `source_class_mean_alignment/analysis_r1/REPORT.md`；均维持精确 NO_SIGNAL，不做参数救援。Evidence Index 中 conv-SAM、SED、增强读出的 INVALID 工程条目不并入零效果统计，后续有效轮也不删除原成本与失败。

`VCN-V0-1-PARENT-BOUNDARY-2026-08-21` 的 old_moment_only_route_reentry 禁令仍有效。新候选不是重新用 moments 可分性释放旧路线：保留 P1 已有视图状态/affine布局，只前瞻改变每个 bank 的训练归一化算子。若后续直接合同核对显示与禁闭干预同一，撤销候选，不以更名规避。

## 历史设计取舍（已由 U5 收尾）

选择 [VBR-R1](vbr-r1/research_brief.md)：视图内训练归一化校正的单配置研究设计。它是已知 Batch Renormalization 思路的宿主适配，原创性未建立。若仅得到一般 renorm 收益，不包装成第二创新；若无稳定支架增量，关闭固定实例并回到主方法证据／写作缺口，不默认再换模块。

曝光说明：本次读取了 anchor 中既有 scoped LOSO 摘要及父级 discovery 边界，其已见事实不能擦除。上述数字不用于选择 VBR 超参/阈值；设计主要依据源码行为和 developmental 关闭边界。未来相同被试/数据仍属于已暴露开发范围，新 seed 不提供独立最终确认。正式评价必须另行审计选择历史。

## U5：固定 VBR-R1 校正未建立超越 VCN-P1 的稳定增量

`AI4S-MVCNET-mvcnet-vbr-r1-screen-lab10-r1-repair3`，直接记录 [最终报告](vbr-r1/execution/repair3/analysis_20261029/REPORT.md)及同目录 `PRECISE_CLOSURE.json`。repair3-packfix2 完成72 fresh fits及72 checks；完整远端逐SHA核验、冻结分析、独立复算和核心包本地41,472预测重算一致。按本轮用户新规则，完整约46.83GB保留Lab10，只回拉约27.22MB正式核心产物，明确 `full_payload_local=false`，不是不完整结果被当作全量本地验收。

P0−S0 +0.019290pp；seed69 −0.250772、seed70 +0.289352pp；正向4/9。均值、双seed同向与覆盖三门失败，冻结判定NO_SIGNAL。CE gain +0.012653与0名严重受损通过其各自门，不能补偿主门。P0−B0 +2.015818pp不说明VBR新增价值，因为S0−B0已有约+1.996528pp；本轮也不把N0或交互描述升级为新候选。

判断变化：视图内训练／推理统计差异仍是算子事实，但该固定有界校正未表现出稳定的支架效用；不再以本轮结果支持“这是VCN下一辅助创新”。这不否定所有归一化设计，也不否定既有VCN scoped证据。设计后果：关闭 `vcn-view-batch-renorm-v01`，不通过调日程/限幅/seed或更名救援，返回主方法证据、对照与写作缺口；没有自动新训练授权。State已完成本轮、暂停且无活动Run，原275h累计预算和2026-10-24T04:35:51Z起点、全部工程失败历史保留。

## U6：v3.3下的下一项设计取舍——先区分来源条件与通用标签保护

2026-10-29，仅设计。v3.3已是MVCNet新工作活动链，原VBR工作仍按v3.2关闭；版本升级不更改其门、预算或结果。主方法的强近邻/归因/适用范围证据仍是成文关键缺口，辅助方向不自动变成更高优先级的训练投入。

源码认识更新：原生`_native_objective`调用的`NTXentLoss`按trial组织CVC，通常把其他trial置入负集合；`utils/contrastive_loss.py`同时已有`NTXentLossNeg/NTXentLossClass`草稿，但并非当前原生调用。其存在与SupCon/去偏对比、SCLDGN等先例说明，“普通同类mask”不能包装为新发现；草稿的相似度乘零也不等于数学上从分母删除。这里没有运行或修写上游代码，没有由方法存在推断训练效果。

用户要求继续围绕VCN-P1找辅助点。本轮建议保留一个可被简单对照推翻的问题：[XSN-R1跨来源同类负样本保护](xsn-r1/research_brief.md)。只在保标签的raw↔flip/freq CVC中，停止不同来源同类异trial之间的排斥，不添加同类吸引；CR/CMC、BN、分类头及raw部署保持。它不同于旧同trial跨目标碰撞图删边、固定BRN校正、分头或源类均值对齐，但**尚未证明来源限制有额外价值或有新颖性**。

选择后果：关键对照至少包含S0、XSN、匹配跨源随机删边、通用同类保护。若不能稳定超过S0，关闭固定实例；若与随机/通用保护相当，停止其选择性解释，不自动调mask或转推控制臂。若要声称VCN特异协同，另需B0与B0+XSN的配对交互；本次没有这些结果。保持同源同类排斥可能有害或保留来源捷径，是候选的核心风险。

本次只完成限定构思、直接近邻核对和brief，未调用完整查新/评审、未实现或训练、未分配新预算/Run/Claim。未选构思不登记为负结果；全部候选及实际适配范围见同目录`CANDIDATE_POOL.json`，来源与曝光说明见`CONTEXT_MANIFEST.json`。

### U6后续修正：限定查新与反驳并未支持立即投入

2026-10-29用户后续授权限定查新及独立科研反驳。Grok-4.6-build真实最终意见为查新`PROCEED WITH CAUTION`、科研`HOLD`，不是XSN科学失败。CALDA等已比较来源条件对比集合，普通标签/source对比不是新意；尚未核到完全同式论文，也不据此宣称首次。

P0删跨源同类，N0删所有同类，原P0−N0混入数量/分母质量。现行完整设计增加同类内等量随机保护R0，与S0/P0/C0/N0组成五臂；C0/R0随机化和非退化仍pending。保留同源同类排斥可能有害或保留捷径，不能作为机制事实；SCMA与XSN是相关source×class几何问题上的不同算子，而非完全独立的新问题。原SCMA正式NO_SIGNAL已本地回查，审查者仅见旧brief造成的经验结案pending限定原样保留，没有虚称复审改判。

判断后果：当前不支付完整矩阵，先解决零训练mask/度数可行性；本轮未执行该检查、未训练。五臂约58.677process-h外推，不是独占GPU成本；新预算未分配，原State/Run/275h计时不动。主Agent修订不等于独立接受，HOLD持续。直接报告：[限定查新与反驳](xsn-r1/review_20261029/NOVELTY_AND_REBUTTAL.md)、[对照与成本](xsn-r1/review_20261029/CONTROL_COST_ANALYSIS.md)。

后续用户授权零训练审计后：[144个训练元数据batch的审计](xsn-r1/mask_audit_20261029/REPORT.md)证明C0/R0在该有界样本中可合法匹配且非退化，保存的288控制图独立读取复核通过；R0平均仍与P0重合92.92%，N0比P0平均多删71.389条trial无向边。数量混淆确实存在，可构造性改善不提供效用证据。退化反例、非均匀交换链/未证明混合、未重放生产损失仍限制解释；维持设计HOLD、不直接投入90fit，未训练。加入当前CPU控制构造开销的假设性五臂规划约63.71process-h，4有效并发含假设缓冲约25.9–29.9h，非新GPU报价或预算授权。





## U7：等待XSN时的下一方向设计——CMC的两侧训练职责

2026-10-29，用户仅授权并行设计、不启动新训练。U6中的HOLD/预算描述保留原时点；之后用户选择XSN一次性探索和独立36h预算，精确执行身份见State与`xsn-r1/execution/PROGRESS.md`。本次没有读取其运行中效果，也未改变XSN的授权、合同或预算。

新设计依赖本页上方补充的论文/实现区别：本地CNN承担分类，Transformer为训练辅助；普通BN视图隔离不隔离CMC梯度。结合旧CVC×CMC整项诊断的INSUFFICIENT_DIAGNOSTIC_SUPPORT、VOGR未支持梯度冲突，以及SCVA子空间精确关闭，主Agent暂选[ACM-R1：分类主干为参照的单向CMC](next_auxiliary_20261029/research_brief.md)。这复用原候选池的stop-gradient备选，只改变CMC反向接收端，保留原前向/正负集合和CE/CVC，不改变推理或叠加XSN。

关键反驳为四臂：原双向、只更新辅助分支、只更新CNN、两侧均不反传。P0必须先有S0增量，再区分完全关闭CMC与反向职责；P0/N0首步CNN更新应一致，后续可经原CVC间接分化，因此不能宣称完全隔绝辅助影响。旧VOGR不构成“梯度有害”前提，旧因子实验也不证明删除CMC有利。stop-gradient/非对称学习已有充分一手先例，目前仅是有可辨识对照的开发候选，未建立新颖性或VCN特异互补。

此项依据是静态代码和历史开发证据，不是新科学结果。建议先做限定查新与独立反驳，再决定是否值得72fit；预算未分配，不借用XSN36h或VBR275h权限、不占用新seed、不建Run/Claim。未选备选保留，不登记为实验否定。设计登记ID：`MVCNET-VCN-NEXT-AUX-DESIGN-20261029`。


### U7后续修正：单侧保护已有近邻，先验证可辨识性

2026-10-29用户授权ACM-R1限定查新与独立科研反驳，仍不启动新训练。真实Grok-4.6-build最终结论为查新PROCEED WITH CAUTION（5/10）、科研HOLD_TRAINING；原文及trace见[next_auxiliary审查报告](next_auxiliary_20261029/review_20261029/NOVELTY_AND_REBUTTAL.md)。ADM（ICML2025）已有单侧特征梯度保护，NPL2024已有按部署角色安排不对称训练，故不能把detach或角色分工本身写成新贡献。可能的贡献只在本地CNN分类、训练辅助A经保留CVC耦合的具体发现，尚无效用证据。

P0对完全关闭N0、反向R0均没有实测支持；静态推导P0/N0首步F/C与Adam更新相同，后续可以经CVC分化，不能称全程隔离。旧CCF的CMC增量+0.491898pp未过冻结门，旧VOGR诊断不足；本轮不以它们证明删除有利或梯度有害，也不重开VBR/COC/SCVA/推理桥接融合实例。

设计后果：保持S0/P0/R0/N0四臂窄问题，先看宿主增量，再看关闭与反向的必要性；普通CMC衰减仍是竞争解释。第五固定0.5双侧衰减臂不是精确范数匹配，不自动增加。下一项有价值的是非XSN生产objective的零训练梯度表、S0 parity、P0/N0首步及CVC非退化检查，尚未执行，不记PASS。四臂历史工作量46.942process-h；有效并发4的条件规划20.67–23.60h、并发2为35.34–41.21h，含未实测倍率与6h统筹余量，不是上界或ACM报价。

ACM预算UNASSIGNED，无新seed/Run/Claim。XSN36h与VBR275h原起点/历史保持；未读取XSN中间效果、未probe或变更当前Run。后续即使图资格通过，也只说明设计可比较，仍需比较ACM与补充VCN/XSN证据的投入价值及独立执行预算。登记ID：MVCNET-ACM-R1-NOVELTY-REBUTTAL-20261029。


### U7零训练审计：接收端定义可实现，间接路径在合成实例中非退化

2026-10-29用户授权隔离副本审计、不启动新训练。记录[MVCNET-ACM-R1-GRADIENT-AUDIT-20261029](next_auxiliary_20261029/gradient_audit_20261029/REPORT.md)：53项主检查通过，保存核心张量另脚本复算两个原生实例；S0与原生参考的梯度/参数/Adam精确一致，P0/N0首步F/C及Adam一致。固定F只交换更新后A，CVC→F梯度差范数0.836111/0.428088；固定同一A或断开跨分支耦合后均为0。该计算依赖在所测实例非退化，不是分类效用。

覆盖实际大小模块、合成batch2/4和空Adam首步，未读真实EEG；10个临时副本各一次技术更新、0科学拟合。未验证生产增强、batch64、长期优化或Lab10成本。主Agent将判断从图资格HOLD推进为“有条件值得一次四臂开发探索”，仍不立即派发，预算UNASSIGNED。保持四臂与关闭/反向对照，不增第五臂、不调权救援。前轮Grok原HOLD和5/10查新意见保留，本次没有冒充外审改判。

成本仍采用历史46.942process-h；有效并发4为20.67–23.60h、并发2为35.34–41.21h的条件情景。小batch审计主体59.801秒及CUDA allocator峰值不转成生产报价。XSN当前Run和36h、VBR历史275h及各原起点保持，未访问XSN中间效果或远端。


## U8：XSN-R1未形成VCN-P1支架增量（2026-11-04）

MVCNET-XSN-R1-VERIFIED-NO-SIGNAL-20261104；证据 AI4S-MVCNET-mvcnet-xsn-r1-screen-lab10-r1-budget480。

XSN-R1同Run完成90fit+90check，0失败/0OOM；完整结果留Lab10，核心正式analysis_v1_recovery intake，原始logits两套独立复算一致NO_SIGNAL。P0−S0 −0.192901pp（seed71 −0.135031pp、seed72 −0.250772pp；5/9正向）。P0−C0 +0.096451pp、P0−N0 +0.212191pp未过门；P0−R0 +0.366512pp过门不能替代主门。关闭该固定开发配置，不新增训练或释放Claim。

证据引用 → 判断变化：CE改善0.011905且无≤−5pp被试，不能替代准确率门失败；没有充分依据把来源限制列为VCN-P1的必要辅助模块，不泛化为所有source-aware对比学习无效。来源：[正式结案报告](xsn-r1/execution/budget480/analysis_20261104/REPORT.md)、[精确关闭边界](xsn-r1/execution/budget480/analysis_20261104/PRECISE_CLOSURE.json)。

设计变化或停止 → 下一项对照：关闭此v01实例，不改mask、温度、seed或门救援，不自动改推N0/R0或叠加ACM。ACM零训练资格保留原角色、不继承训练授权；若另选问题，先比较与补齐VCN主方法证据的投入价值，本轮不创建新候选或对照。原480h预算、计时起点和全部失败修复历史保持。


## U9：XSN关闭后，ACM只保留为预算受控的职责检验

2026-11-04；MVCNET-ACM-R1-POST-XSN-REASSESSMENT-20261104。证据→判断：XSN负结果关闭删边v01，并未测试CMC接收端，不为ACM提供正支持。ACM既有53项合成资格和CVC间接作用非退化说明四臂可辨识；CCF/VOGR未建立CMC有害，既有不对称近邻限制仍在。详见[重评依据与关键对照](next_auxiliary_20261029/reassessment_20261104/REPORT.md)。

判断→设计/停止：仅有条件值得一次S0/P0/N0/R0开发探索，先宿主增量，再关闭和反向必要性；任何必要门失败收口固定实例，不调权/加seed/切方向或叠加XSN。四臂不排除一般减权、不证明VCN协同；主方法强近邻/范围证据仍比默认加模块更优先。下一项是将来获准后生产objective绑定与B64/目标机资格、固定判读/成本门，并非本轮执行。

成本→投入：近期XSN原生S0收据×4为37.512192process-h；K4含假设倍率/6h余量约17.72–20.07h，工作量敏感性及旧VBR参照约20.15–23.60h；K2情景29.45–41.21h。36h只是预算商议目标，不是已分配上限或实测可行性。ACM预算UNASSIGNED，XSN480h余款不转用。Program暂停/运行状态保持，本轮无新训练、seed、Run或Claim。


## U10：ACM 固定职责实例已按冻结门关闭（2026-11-05）

历史时点修正：U9 的有条件探索后，用户另授独立42h并完成执行/工程修复。证据 `AI4S-MVCNET-mvcnet-acm-r1-screen-lab10-checkrepair2`；[正式关闭报告](acm-r1/execution/checkrepair2/analysis_20261105/REPORT.md)。72个模型复用、72项check完成/独立logits复算，新增fit0；P0-S0 +0.733025pp主门通过，P0-N0 +0.868056pp通过，但P0-R0在seed74为-0.115741pp，关键逐seed门失败，NO_SIGNAL。保留开发效用线索，不升级为单向机制/论文Claim，不调参救援。原42h及起点/全部失败历史保持；截至既有最终结算累计23.823807h，不转为下一方向预算。

## U11：最小归一化结构已收束，不作新增主创新训练（2026-11-06）

证据 `MVCNET-VCN-MINIMAL-STRUCTURE-READONLY-ZERO-TRAINING-20261106`；[唯一研究brief](normalization_minimal_20261106/research_brief.md)与[结构化决定](normalization_minimal_20261106/DECISION.json)。绑定v3.3，只读设计/隔离CPU零训练，Program State与全部冻结Run/预算不改。

证据→判断：P1/N1已有scoped支持，不重训N1；两个真实IFNet+native CE/CVC/CMC合成实例中，仅合并三个增强running缓冲、保持四affine和raw统计独立，输出/全部已核查梯度/raw预测差均0，完整state_dict不同。共享增强affine具有非同view梯度和梯度求和关系，是活干预，但不能用可辨识性证明性能；固定bank置换只是重命名。B64、长期优化、checkpoint别名和完整gateway动态路径未覆盖，不为已放弃M补资格。

输入/近邻→设计后果：当前生产资产四hash闭合，当前X18条重放匹配trial[0,4)，非cue后[0,4)；历史S8 X字节身份未知，不改旧内部配对/曝光。已找到并核验5hash的既有cue资产候选，不需假设重建数据，但MVCNet协议未绑定，也不产生独立确认。AdvProp/DAJAT/DualBN已覆盖多BN及统计-affine拆分；真实Grok独立反驳STOP_MAIN_INNOVATION_INVESTMENT，原文/主Agent处置完整保留。

最终选择→下一行动：STOP_AS_NEW_MAIN_INNOVATION / HOLD_TRAINING，保留P1既有支架身份；只保留P1对普通raw/aug双BN作为未来论文补证草案，不自动开训、加随机路由臂、救援旧实例或借ACM/XSN预算。12-18h仅是旧100epoch两臂情景假设，非新Lab10报价/授权。下一步先收窄论文贡献与评价对象；cue对齐完整方法净收益是另一明确科学问题，不能冒充本题续跑。此为投入判断而非新科学NO_SIGNAL。


## U12：cue 对齐条件下先检验完整训练方案（2026-11-06）

证据 `MVCNET-CORE-DIRECTION-CUE-ALIGNED-DESIGN-20261106`。既有 P1 scoped、VBR/XSN/ACM 固定实例关闭及最小结构审计共同限制新增支架改动的论文价值。多视角构思初选逐试次参考，经独立科研反驳和限定近邻核对，将 cue 对齐下原生 MVCNet 相对同 IFNet、同增强监督的净增量列为下一设计优先项。P1−B0 另答支架适用范围。主比较成立后再考虑等长度窗口的提示时序依赖，窗口差只能先作条件性证据。

现成 cue 资产有五项哈希核验记录，当前数据 loader 与 role／trial-ID 仍需映射。下一步只读绑定资产、事件、划分、信息与训练预算，核对后决定是否值得配对比较。已暴露九被试限开发；预提示参考保留为次级问题，待因果输入、最近历史对照与独立评价可用性核查。范围及判别见[研究简报](next_core_direction_20261106/research_brief.md)与[决策](next_core_direction_20261106/DIRECTION_DECISION.json)。


### U12 只读绑定结果

证据 `MVCNET-CUE4-READONLY-PROTOCOL-BINDING-20261106`。cue 资产五文件与 18 份 MAT 哈希通过，5,184 条试次身份与旧 MVCNet 输入逐行对应，18 条抽样数组重放确认 500 点窗口偏移。MVCNet 的 18 份七源参考索引在 cue 元数据上闭合，DSAINet 的六源角色保持单独。旧生产入口依赖旧字段、哈希和 VCN-P1，cue 原生 B0 仍需独立生产接线资格。

历史 CVC×CMC 已在旧窗 P1 上比较四视图 CE，联合增量 +0.279707 pp 未过冻结门。当前唯一主比较草案是 cue 窗无 VCN B0 对同 IFNet、同四视图 CE。统一监督与更新步数，计算量单独计量。继续协议准备，暂缓完整训练。数据与角色证明、限制和投入处置见[绑定报告](next_core_direction_20261106/cue_protocol_binding/REPORT.md)。

### U12 两臂隔离零训练验收

证据 `MVCNET-CUE4-TWO-ARM-ZERO-TRAINING-20261106`。源 loader 通过 18 份参考划分闭合、B64 批次与角色拒绝检查。实际四视图匹配原生输入及标签规则，同 IFNet 的共享 CE 梯度一致，B0 的 CVC+CMC 确实进入梯度。两臂源侧 raw 验证共用正确数、平均 CE 和 epoch 的顺序，拒绝越权和不完整验证。真实 EEG 仅用于源批次与增强，模型前向及梯度使用合成输入。

隔离资格通过后，仍暂缓完整训练。仅在论文需要明确检验原生配方相对强增强监督的净增量时，考虑一次两臂开发比较。历史尺度约 19 process-hours。先定义有成文价值的最小差异和个体风险，再核验生产封存链及两臂 Lab10 实际成本。九个已暴露被试只提供开发证据。[验收与投入评估](next_core_direction_20261106/cue_two_arm_zero_training/REPORT.md)

### U12 生产接线、科学门冻结与 Lab10 启动故障

证据 `MVCNET-CUE4-PRODUCTION-QUALIFICATION-20261106`。已接通真实源拟合、raw 选模、全局 36 checkpoint 封存及逐折检查和判读消费者。平均 B0−CE 至少 +1 pp，两 seed 均值各为正，至少 6/9 被试改善，最差被试的两 seed 平均至少 −3 pp，并按 95% 被试配对 bootstrap 区分稳定开发信号和不确定。资格与科学合同身份分离。

Lab10 资格任务 0/4，全部在加载数据和更新前遭遇同一导入路径错误。原包和日志保留，入口修复及无训练的导入重放已完成。冻结的一次任务尝试均已消耗，后继资格须另授一次工程修复。成本仍缺两臂生产形状实测，科学拟合与开发检查均为零。[协议与工程收尾](next_core_direction_20261106/cue_production/REPORT.md)

### U13 sealfix2 后的逐试次参考核查

`sealfix2` 的 [NO_SIGNAL](mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2_decision.yaml) 保留。新零训练核查在名义视觉 cue 下通过参考和任务截止的因果性回放，精确匹配实际派发包的 18 份划分，采集时序共同试次 4,860。严格同角色历史的源验证每折仅 3–10 项。同试次参考相对等长最近历史、等点数三窗替换的全任务窗被试中位距离优势均很小，较短历史时距层方向反转，现有时序无法分离试次身份与时间邻近。按原停止规则结束该方向的训练投入。四视图 CE 继续作为同期强基线，VCN-P1 保留为原历史协议的限定支持证据。[零训练核查与处置](next_core_direction_20261106/PRECUE_ZERO_TRAINING_AUDIT_20261108.md)

### U14 预提示参考关闭与下一候选

依用户指令正式关闭逐试次预提示参考，登记 `MVCNET-PRECUE-ZERO-TRAINING-CLOSE-20261108`。后续只设计一个独立候选，在四视图 CE 的固定一路训练增强上扰动提示起始，以等长错位遮挡和简单晚窗检验真实换提示时的净收益。现成 Supernumerary V3 有同被试双提示，但按日采集，资产触发、时钟和曝光须先验收。当前仅为选题草案，最低下一关为零训练。[候选与停止条件](next_core_direction_20261106/CUE_ONSET_AUGMENTATION_DESIGN_20261108.md)

### U15 提示起始遮挡在 Supernumerary V3 数据关停止

40 份 XDF 的 1,600 个左右想象任务窗可定位，未找到两条件的逐试次视觉提示起始标记。XDF 通道头与发行方位置表冲突，去抖显著改变 EEG 时间戳。匹配遮挡的合成控制通过，前向 SOS 与原生 Hilbert 频移在遮挡前处理都会把早段信息带到遮挡外。按原规则 `STOP_CUE_ONSET_UNVERIFIED`，当前资产和管线不进入四臂开发比较。这是数据与辨识性停止，未测模型效用。[实测与处置](next_core_direction_20261106/CUE_ONSET_ZERO_TRAINING_20261108.md)

### U16 提示起始遮挡方向收束

依用户指令关闭 Supernumerary V3 验证路径。限定替代核查未发现同时具有同被试双提示、两种实际起始事件、EEG 时钟和通道映射的公开资产。最接近的 BCIC IV Dataset 1 可由官方标签恢复大多数语音评分边界，仍缺实际呈现事件。DynamicCues 的原始发布未取得。登记 `CLOSED_NO_QUALIFIED_ALTERNATIVE`，提示起始遮挡不进入四臂开发比较。保留 Supernumerary 零训练回执、逐试次参考关闭及 sealfix2 的 `NO_SIGNAL`。[替代核查与收束](next_core_direction_20261106/CUE_ONSET_ALTERNATIVES_CLOSE_20261108.md)

### U17 用已有预测证伪训练配方分歧的错误辨识价值

选题草案。`sealfix2` 两臂准确率接近，已有正式核心包可在同一试次上区分两臂错误重叠和分歧。固定 CE 的预测，比较同 seed B0–CE 分歧与单 CE 置信度、普通 CE 重复分歧和相同两模型的平均概率置信度。最低验证是 CPU 离线等覆盖率错误排序，无新增模型前向、拟合或下载。两重复的源划分也不同，且九人已暴露，只支持开发证伪。两项时间参考/遮挡关闭和 `sealfix2` 判定保持原记录。[候选与对照](next_core_direction_20261106/PAIRED_RECIPE_ERROR_RANKING_DESIGN_20261108.md)

### U18 配对分歧未改善 CE 错误排序

CPU 核查已完成，处置 `STOP_NO_INCREMENTAL_ERROR_RANKING`。固定 CE 输出，每人保留 518/576，配对 JS 比单 CE 最大概率、同对平均置信度的错误率分别高 1.512、1.652 pp，两重复均落后，均为 0/9 人改善。相对普通 CE 重复为 −0.086 pp 改善，重复方向相反、5/9 人改善。匹配预测类别拒绝配额后仍落后主要置信度对照。结束当前路线的独立复核投入，保留所有旧结论。[正式核查](next_core_direction_20261106/PAIRED_RECIPE_ZERO_TRAINING_20261108.md)

### U19 配对分歧正式关闭与固定截止候选

依用户指令关闭 B0–CE 配对分歧方向，登记 `MVCNET-PAIRED-RECIPE-DIRECTION-CLOSE-20261109`，复用原零训练回执。下一候选只做设计，复用现有 2a 连续数据和试次闭集，在名义 cue 后 2 秒、4 秒共享因果主干并保留独立位置读出。最强反证为相同截止独立 CE 或等监督预算短窗 CE。先核前缀因果、训练梯度与缓存等价，再判断是否有资格申请比较。既有三项关闭和 `sealfix2` 的 `NO_SIGNAL` 保留。[设计与停止条件](next_core_direction_20261106/CAUSAL_TWO_DEADLINE_DESIGN_20261109.md)

### U20 双截止 CPU 技术核查通过

18 份 2a MAT、5,184 项嵌套共同试次及 18 个既有划分闭合。每个截止的原始波形扰动与截断回放一致。合成 IFNet 探针通过后缀扰动、完整输入梯度和缓存等价检查，长窗 CE 到共享主干梯度非零。处置 `PASS_ZERO_TRAINING_REVIEW_WORTHY`，仅建议进入独立科研复核，继续保留提示效应和训练预算匹配的反证。未执行外审或开发比较，既有关闭与 `sealfix2` 判定保留。[技术核查与边界](next_core_direction_20261106/CAUSAL_TWO_DEADLINE_ZERO_TRAINING_20261109.md)

### U21 双截止外审与开发派发前置门

Grok 4.6 对原设计独立反驳为 `HOLD_FOR_DESIGN_FIX`。修订后保留同截止独立 CE，加入两个 4 帧头的等监督短窗和 4/8 帧头的等容量短窗对照。匹配两项 CE、处理点数与更新，实测计算和共享梯度。合成 CPU 计时中 2×500 缓存的两次合计中位数下降约 23%，8×125 分块反而更慢。仅建议继续生产形状零训练接线、回放计时与成本资格，当前 `HOLD_BEFORE_DEVELOPMENT_DISPATCH`。早窗仅支持已知提示下的定时四分类。既有关闭和 `sealfix2 NO_SIGNAL` 保留。[外审及本地修订](next_core_direction_20261106/CAUSAL_TWO_DEADLINE_DEVELOPMENT_GATE_20261109.md)

### U22 五臂技术验收通过，含因果前端的合计 p95 未过门

显式候选经实际 adapter/gateway 接通 J/E2/E4/E/P。B64 源侧接线、等监督、J/P 活跃读出容量以及长窗到共享主干梯度均验收，零优化步。分包与前向 SOS 纳入后，2×500 缓存首段和第二段 p95 过门，合计 p95 从 2.2685 降到 2.0775 ms，仅省 8.42%。按原门 `STOP_TOTAL_P95_GATE`，不进入两重复开发或新 Lab10 资格。成本仅更新为历史锚点情景，保留全部旧关闭与 `sealfix2 NO_SIGNAL`。[生产形状资格与停止判断](next_core_direction_20261106/CAUSAL_TWO_DEADLINE_PRODUCTION_QUALIFICATION_20261109.md)

### U23 双截止正式关闭，转向同提示被动观看负对照

依用户指令登记 `MVCNET-CAUSAL-TWO-DEADLINE-DIRECTION-CLOSE-20261109`。五臂零训练资格与原始回执保留。含分包和前向 SOS 的合计 p95 仅下降 8.42%，低于 10% 预设门，关闭双截止开发投入。逐试次预提示参考、提示起始遮挡、B0–CE 配对分歧的关闭结论及 `sealfix2` 的 `NO_SIGNAL` 保留。[资格与停止记录](next_core_direction_20261106/CAUSAL_TWO_DEADLINE_PRODUCTION_QUALIFICATION_20261109.md)

`MVCNET-SAME-CUE-PASSIVE-SPECIFICITY-DESIGN-20261109` 仅登记设计。利用已公开的 HaLT 和 NoMT 记录，问主动训练的左右手解码器在同提示被动观看中是否仍能识别方向。目录可配同人七组，跨日与实际被动方向码和时钟尚待核查。先限定 Subject K 两份原始 MAT 做无拟合数据资格。通过后才核对全组，随后才有理由评审轻量读出。当前无原始波形读取、训练或新 Run。[设计与停止门](next_core_direction_20261106/SAME_CUE_PASSIVE_SPECIFICITY_DESIGN_20261109.md)

### U24 同提示负对照在 Subject K 实际提示资格停止

登记 `MVCNET-SAME-CUE-PASSIVE-K-ZERO-TRAINING-20261109`。HaLT、NoMT 两份原始 MAT 与作者采集脚本均通过发布哈希。两条件同为 200 Hz、相同 19 路 EEG 顺序，各有 163 个左发布码和 159 个右发布码。第 22 列使 322/322 个起点在 ±1 点内唯一复现，MAT 通道名为 X5，与论文 X3 的物理映射未核实。表 5 与发布 eGUI 的 2/3 图标索引冲突，缺逐试次界面源日志。独立硬件结束标记未验出，1 秒共同窗仅按发布 marker 成立。按硬门关闭这条 Kaya 发布资产路径，未扩到其余被试，未训练。保留既有关闭和 `sealfix2` 的 `NO_SIGNAL`。[实测与处置](next_core_direction_20261106/SAME_CUE_PASSIVE_K_ZERO_TRAINING_20261109.md)

### U25 同提示特异性方向因缺合格替代资产收束

登记 `MVCNET-SAME-CUE-PASSIVE-ALTERNATIVES-CLOSE-20261109`。限定核查八个候选，合格数为零。最接近的公开篮球数据同人有纯观察和纯想象。固定发行件实读表明运球事件按任务状态标码，缺可追溯的左右手码与实际显示起止；传球是复合序列。其余候选缺同提示被动条件、仅覆盖单手、改变呈现或当前无公开资产。按原规则收束方向，保留 Subject K 核查、Kaya 路径关闭和 `sealfix2` 的 `NO_SIGNAL`。零拟合，零新 Run。[替代资产核查](next_core_direction_20261106/SAME_CUE_PASSIVE_ALTERNATIVES_CLOSE_20261109.md)

### U26 以独立校准回放检验眼电扰动敏感性

登记 `MVCNET-OCULAR-REPLAY-DESIGN-20261109`。同提示方向关闭后，选择本地 2a 中独立于任务标签的前置眼电校准。对同一 EEG 波形作原波形、真实校准扰动、等能量空间对照三方配对，另以错位校准验证场估计。已查 A01T/E、A04T 的块结构及 seed73-outer0 的被试角色。拟在两名源被试 A03/A04 的 T/E 上做一次 CPU 零训练资格，先验证跨会话混合、等能量和非退化，失败即止。当前设计未执行资格或模型重放。保留同提示关闭、Subject K 核查及 `sealfix2` 的 `NO_SIGNAL`。[设计与停止门](next_core_direction_20261106/OCULAR_REPLAY_DESIGN_20261109.md)

### U27 眼电同步跨会话通过，固定注入因滤波越过试次边界停止

登记 `MVCNET-OCULAR-REPLAY-ZERO-TRAINING-20261109`。A03/A04 的 T/E 四份 MAT、10 个校准块、1,152 条源侧试次身份闭合。E 的 4 秒窗中，同步较错位的归一化平方误差中位优势为 A03 28.76%、A04 14.35%，逐校准块留一方向均为正。按本次固定中央 1 秒注入与 1,651 点连续 FIR，首条 A03T 的理论支撑越过下一试次起点 44 点。`STOP_PAIRED_INPUT_GATE`，尚未生成对照波形或核验等 RMS／拓扑，当前不进入设计复核。保留同提示关闭、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL`。零模型前向、零训练、新 Run 为零。[核查报告](next_core_direction_20261106/OCULAR_REPLAY_ZERO_TRAINING_20261109.md)

### U28 共同位置解决固定试次边界，空间对照未过可辨门

登记 `MVCNET-OCULAR-REPLAY-SHARED-POSITION-20261109`。四条固定试次的共同安全起点为 cue 后 325–331 点，按中点取 328。首条 A03T 实测滤波隔离和等 RMS 通过，真实与分区置换对照的余弦 0.957123 超过既定 0.95，按规则结束固定方案，余下三条只核边界，未进入设计复核。保留上次试次隔离失败、同步通过、同提示关闭、Subject K 和 `sealfix2` 的 `NO_SIGNAL`。无模型前向、训练或新 Run。[补测与关闭记录](next_core_direction_20261106/OCULAR_REPLAY_SHARED_POSITION_20261109.md)

### U29 眼电固定方案正式关闭，登记同窗时间反演设计

依用户指令登记 `MVCNET-OCULAR-REPLAY-DIRECTION-CLOSE-20261109`。同步跨会话通过、原位置试次隔离失败、325–331 点共同安全位置和首条空间对照余弦 0.957123 超过 0.95 均保留。既有各方向关闭、Subject K 核查及 `sealfix2` 的 `NO_SIGNAL` 保留。

`MVCNET-TIME-REVERSAL-ODD-EVIDENCE-DESIGN-20261109` 仅设计。晚窗同试次正放与倒放的功率、实部互谱、零时滞协方差和幅值分布相同，有符号虚部反号。以共同平移、cue 前等长窗和 run 内置换排查伪差，先核其他源被试的 T 对照能否在留出人的 E 上复现。已从固定折元数据计得 403 条源验证左右手试次，未读取信号做效果统计、未拟合或启动 Run。[设计与停止门](next_core_direction_20261106/TIME_REVERSAL_ODD_EVIDENCE_DESIGN_20261109.md)

### U30 晚窗有符号时滞在跨人 T→E 门停止

登记 `MVCNET-TIME-REVERSAL-ODD-ZERO-TRAINING-20261109`。403 条源验证左右手试次及 806 个窗的正放、倒放和共同平移谱不变量通过，391 条进入双类 run 对照。晚窗仅 4/7 人同向，等权晚窗投影 +0.034532 低于置换 P95 +0.190738，晚窗相对 cue 前的增量 +0.189301 低于 P95 +0.360775。三门均未过，固定方案停止于零训练，未进入设计复核。保留眼电回放关闭、Subject K 核查、同提示关闭及 `sealfix2` 的 `NO_SIGNAL`。零模型前向、零训练、零新 Run。[核查与处置](next_core_direction_20261106/TIME_REVERSAL_ODD_ZERO_TRAINING_20261109.md)

### U31 晚窗有符号时滞正式关闭，登记主动未见类拒识设计

依用户指令登记 `MVCNET-TIME-REVERSAL-ODD-DIRECTION-CLOSE-20261109`。保留 403 条、806 窗的谱不变量通过、4/7 人同向及两项置换门失败。保留眼电回放关闭、Subject K 核查、既有关闭与 `sealfix2` 的 `NO_SIGNAL`。

`MVCNET-ACTIVE-UNSUPPORTED-COMMAND-DESIGN-20261109` 仅设计。固定左右手原型读出，比较到两类线段的距离、置信间隔、最近原型和中点距离。在六名源被试 T 定原型、六人 E 的已知手类定阈值，留出人 E 的同 run 双脚和舌只作最后评分。元数据已核对 33 个合格 E run、329 条候选试次。直接近邻已有同类被试内配置，论文投入以严格留人和风险匹配下对简单强对照的实质增量为前提。未做效果统计、拟合或派发。[设计与停止门](next_core_direction_20261106/ACTIVE_UNSUPPORTED_COMMAND_DESIGN_20261109.md)

### U32 主动未见类拒识因接收率不可比且无原型增量停止

登记 `MVCNET-ACTIVE-UNSUPPORTED-COMMAND-ZERO-TRAINING-20261109`。33 个同 run 匹配、329 条留出评分均闭合。其余六人仅以 T 左右手定原型、E 左右手定阈值。线段规则与最近原型和中点的 329 条接收决定完全一致。相对置信间隔，已知接收率相差 12.41 个百分点，超过 5 点门；双脚误放改善 7.82 点，舌 18.28 点，两类各仅 4/7 人改善。按 `STOP_REJECTION_GATE` 停止固定方案，未进入设计复核。保留晚窗时滞、眼电回放关闭、Subject K 核查及 `sealfix2` 的 `NO_SIGNAL`。零模型前向、零训练、零新 Run。[核查与处置](next_core_direction_20261106/ACTIVE_UNSUPPORTED_COMMAND_ZERO_TRAINING_20261109.md)

### U33 主动未见类拒识正式关闭，登记错误序列核查设计

依用户指令登记 `MVCNET-ACTIVE-UNSUPPORTED-COMMAND-DIRECTION-CLOSE-20261109`。保留 33 个匹配 run、329 条试次，线段与最近原型和中点的接收决定全部一致，已知类接收率相差 12.41 个百分点，高于 5 点可比性门。晚窗时滞和眼电回放的关闭、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL` 均保留。[拒识核查](next_core_direction_20261106/ACTIVE_UNSUPPORTED_COMMAND_ZERO_TRAINING_20261109.md)

`MVCNET-ERROR-SEQUENCE-CLUSTERING-DESIGN-20261109` 仅设计。已核对 5,184 条、108 个 run 的时间索引，全部 5,076 对紧邻试次的连续 FIR 输入范围有重叠，全部 4,968 对隔一试次的输入范围分离。拟用两个不重叠子序列及保持真实类别、run 半段错误率和四模型同试次共错的联合置换，判断错误聚集是否值得独立复核。只做了资产和元数据核查，未计算错误序列效果或启动 Run。[设计与停止门](next_core_direction_20261106/ERROR_SEQUENCE_CLUSTERING_DESIGN_20261109.md)

### U34 错误序列聚集在偶数主检验与奇数复核的冻结门停止

登记 `MVCNET-ERROR-SEQUENCE-CLUSTERING-ZERO-TRAINING-20261109`。`sealfix2` 核心包、36 项已封存检查和 5,184 条唯一试次通过身份核验。两组各 2,376 对，分别完成 10,000 次分层联合置换。偶数 CE-73 过 P95，CE-74 和跨重复未过。两次 CE 平均超额 +0.611 个百分点，低于 +1 点门，7/9 人平均超额为正。奇数两次 CE 和跨重复超额均为负。按 `STOP_ERROR_SEQUENCE_CLUSTERING_GATE` 停止固定方向，未进入设计复核。既有关闭结论、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL` 保留。零模型重放、零训练、零新 Run。[核查与处置](next_core_direction_20261106/ERROR_SEQUENCE_CLUSTERING_ZERO_TRAINING_20261109.md)

### U35 错误序列聚集正式关闭，登记 μ 与高 β 时间对齐设计

依用户指令登记 `MVCNET-ERROR-SEQUENCE-CLUSTERING-DIRECTION-CLOSE-20261109`。偶数主检验仅 CE-73 过 P95，两次 CE 平均超额 +0.611 个百分点，7/9 人同向。跨重复未过 P95，奇数复核三项均为负。保留既有关闭结论、Subject K 核查及 `sealfix2` 的 `NO_SIGNAL`。[错误序列核查](next_core_direction_20261106/ERROR_SEQUENCE_CLUSTERING_ZERO_TRAINING_20261109.md)

`MVCNET-MU-HIGH-BETA-ALIGNMENT-DESIGN-20261109` 仅设计。使用两个频带的完整功率轨迹、同维的试次内错位，以及同 run 同类、保留 cue 时钟的跨试次重配，检验同一试次 μ 与高 β 对齐的跨人 T→E 增量。固定折核对七名源被试、812 条 T 左右手和 E 的 20 个匹配 run、129 条。只做了元数据核对，未读取波形计算效应或启动 Run。[新方向与停止门](next_core_direction_20261106/MU_HIGH_BETA_ALIGNMENT_DESIGN_20261109.md)

### U36 μ 与高 β 时间对齐在冻结效果门停止

登记 `MVCNET-MU-HIGH-BETA-ALIGNMENT-ZERO-TRAINING-20261109`。14 份原始 MAT、812 条 T 源侧左右手、20 个 E 匹配 run 的 129 条评分试次和合成对照均通过。候选相对完整功率、同维错位的 AUROC 增量分别为 +0.011905、+0.003720，均低于 +0.03，只有 1/7 人同时改善。候选定向类差 −0.004130，低于 10,000 次同 run 同类重配的 P95 +0.191864。四项效果门均失败，按 `STOP_MU_HIGH_BETA_ALIGNMENT_GATE` 停止，未进入设计复核。保留既有关闭结论、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL`。零模型重放、零训练、零新 Run。[核查与处置](next_core_direction_20261106/MU_HIGH_BETA_ALIGNMENT_ZERO_TRAINING_20261109.md)

### U37 μ 与高 β 时间对齐正式关闭，登记源验证 FIR 支撑隔离设计

依用户指令登记 `MVCNET-MU-HIGH-BETA-ALIGNMENT-DIRECTION-CLOSE-20261109`。保留 14 份 MAT 和合成对照通过、20 个匹配 run 和 129 条试次。两项 AUROC 增量未达 0.03，仅 1/7 人同时改善，定向类差未过重配 P95。既有关闭结论、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL` 均保留。[核查与处置](next_core_direction_20261106/MU_HIGH_BETA_ALIGNMENT_ZERO_TRAINING_20261109.md)

`MVCNET-FIR-SUPPORT-DISJOINT-SELECTION-DESIGN-20261109` 仅设计。18 个冻结折每折有 761–772 条源验证试次与训练窗共享扩展 FIR 支撑，源侧与独立检查被试无同 run 相交。拟固定训练输入和验证身份，只限制验证可读原始采样。A03/A04 T/E 四份文件有 222 条验证，其中 67 条可做单侧相交的等长度反侧对照。仅完成元数据和文件可用性核对，未运行波形探针、复算选模、重放模型或启动训练。[新设计与停止门](next_core_direction_20261106/FIR_SUPPORT_DISJOINT_SELECTION_DESIGN_20261109.md)

### U38 源侧验证 FIR 支撑隔离过零训练门，设计复核暂缓选模比较

登记 `MVCNET-FIR-SUPPORT-DISJOINT-SELECTION-ZERO-TRAINING-20261109`。四份 MAT、222 条冻结验证裁剪及物理支撑通过，8 条实数据脉冲探针的共享响应在隔离验证端归零。67 条配对中，A03T、A03E、A04T、A04E 的隔离改变量中位数分别 8.81%、5.38%、3.97%、4.68%，全部通过 1% 门。进入只读设计复核。冻结 runner 与已验收清单只支持每次拟合的最终选中权重，缺可复用的多 epoch 轨迹，处置 `HOLD_MISSING_REUSABLE_EPOCH_TRAJECTORY`，不推断选模或准确率变化。保留既有关闭结论、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL`。未重放模型、训练或建立 Run。[核查与设计复核](next_core_direction_20261106/FIR_SUPPORT_DISJOINT_SELECTION_ZERO_TRAINING_20261109.md)

### U39 源侧验证 FIR 支撑隔离正式关闭

依用户指令登记 `MVCNET-FIR-SUPPORT-DISJOINT-SELECTION-DIRECTION-CLOSE-20261109`。保留 222 条冻结数组重放、物理支撑与 8 条实数据脉冲核查通过，以及 67 对中四份记录的隔离中位数 8.81%、5.38%、3.97%、4.68%。设计复核确认 `sealfix2` 现有产物缺可复用的多 epoch 轨迹，选模和独立检查准确率的变化仍未检验。保留 Subject K 核查、既有关闭和 `sealfix2` 的 `NO_SIGNAL`。本次关闭不激活新方向。[核查与设计复核](next_core_direction_20261106/FIR_SUPPORT_DISJOINT_SELECTION_ZERO_TRAINING_20261109.md)

### U40 VCN-P1 保留为阶段性创新，登记逐视图 affine 可迁移性判据

`MVCNET-VCN-VIEW-AFFINE-TRANSFER-DESIGN-20261109` 仅设计。历史 P1−B0 和参数匹配 N1 支持仍限原协议。原最小结构结论 `STOP_AS_NEW_MAIN_INNOVATION` 保留。本次筛的是 raw 已独立后，增强 affine 的额外方向是否跨人和记录可复用，能否经共享主干更有利于另一会话的 raw 目标。关键对照为按增强视图分别计算批统计的 raw／增强双 BN、冻结方向后五种同范数错配和三路相同视图。固定折元数据支持七名源被试的 896 条 T 探针与 400 条 E 源验证。单份封存 CE 权重只由历史清单定位，本地精简包无该文件，未验证远端可达性。当前不确立新主线，未执行零训练探针或启动 Run。既有关闭结论与 `sealfix2` 的 `NO_SIGNAL` 均保留。[筛查设计与停止门](next_core_direction_20261106/VCN_VIEW_AFFINE_TRANSFER_DESIGN_20261109.md)

### U41 逐视图 affine 方向在 T 记录互换门停止

登记 `MVCNET-VCN-VIEW-AFFINE-TRANSFER-ZERO-TRAINING-20261109`。Lab10 CPU 就地核验指定封存 CE 权重及源侧索引，技术门通过。896 条 T 试次的两次记录互换分别有 5/7 和 4/7 人过门，同一被试双向通过仅 3/7，低于 5/7。按原规则停止主线筛查，未执行 E raw 梯度门。阶段性 VCN-P1 证据、既有关闭与 `sealfix2` 的 `NO_SIGNAL` 保留。零优化器步，零新 Run。[核查报告](next_core_direction_20261106/VCN_VIEW_AFFINE_TRANSFER_ZERO_TRAINING_20261109.md)

### U42 逐视图 affine 主线关闭，登记固定试次的协议交互设计

依用户指令登记 `MVCNET-VCN-VIEW-AFFINE-TRANSFER-DIRECTION-CLOSE-20261109`。保留 896 条 T 试次技术门通过、两方向 5/7 与 4/7、双向 3/7 和 E raw 未执行。VCN-P1 保留为阶段性创新。

`MVCNET-COMMON-TRIAL-PROTOCOL-INTERACTION-DESIGN-20261109` 仅设计。S8 两套数据的原全测试集 P1 增量在 CO 与 LOSO 间呈相反排序。只读核对了 360 个预测文件的索引和真实标签，两套数据每 seed 分别有 2,592 与 2,840 条共同试次。拟在同一试次计算 P1−B0 的协议差中差，并做基线同对／同错敏感性分析。未读取预测类别或启动训练。既有关闭、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL` 保留。[设计与停止门](next_core_direction_20261106/COMMON_TRIAL_PROTOCOL_INTERACTION_DESIGN_20261109.md)

### U43 共同试次协议交互在稳健性门停止

登记 `MVCNET-COMMON-TRIAL-PROTOCOL-INTERACTION-ZERO-TRAINING-20261109`。360 个冻结预测与历史 ACC 复算通过。共同试次差中差为 001 +1.705 点、004 −1.549 点，方向人数分别 6/9、5/9。B0 同对／同错两层等权后为 −0.067 和 +2.892 点，均未保留原方向。按原门停止该核心候选，未进入设计复核。保留 VCN-P1 历史限定支持、既有关闭、Subject K 核查和 `sealfix2` 的 `NO_SIGNAL`。无模型重放、训练或新 Run。[核查报告](next_core_direction_20261106/COMMON_TRIAL_PROTOCOL_INTERACTION_ZERO_TRAINING_20261109.md)

### U44 MVC-01 的固定观测组合停在合成实用增量门

登记 `MVCNET-MVC01-SYNTHETIC-IDENTIFIABILITY-20261110`。嵌套长窗和重复短窗均未增秩。Hann 权重使秩从 7 升至 14，并打破一个明确的潜在轨迹混叠反例。相对加密矩形短窗，两档脉冲的检出且定位增量为 +0.100 和 +0.675 点，均低于 +5 点预设门。固定观测组停在合成层，未比较 ASSMT、未读真实 EEG、未训练。保留 VCN-P1 历史限定支持、既有关闭与 `sealfix2` 的 `NO_SIGNAL`。[核查报告](next_core_direction_20261106/MVC01_IDENTIFIABILITY_RESULT_20261110.md)

### U45 MVC-04 的同步选组停在真实试次非退化门

登记 `MVCNET-MVC04-PROSPECTIVE-GROUP-SAMPLING-ZERO-TRAINING-20261110`。14 份 MAT、941 条绑定试次与 13,174 项不可见样本扰动检查通过。合成相位控制保持单通道功率与边际选组，改变同步选组。E 源验证的 20 个匹配 run 中，同步和边际规则仅 5/129 条选组不同（3.88%），低于 10% 门，按 `STOP_NONDEGENERACY_GATE` 停止该固定规则。未计算三臂准确率，未进入设计复核。保留既有关闭、Subject K 核查与 `sealfix2` 的 `NO_SIGNAL`。零训练、零模型重放、零新 Run。[核查报告](next_core_direction_20261106/MVC04_ZERO_TRAINING_RESULT_20261110.md)

### U46 MVC-04 当前两段两组选组方案关闭

依用户指令登记 `MVCNET-MVC04-PROSPECTIVE-GROUP-SAMPLING-DIRECTION-CLOSE-20261110`。保留不可见样本扰动通过、同步和单通道规则仅 5/129 条选组不同（3.88%）且未进入三臂效果比较的记录。既有关闭结论与 `sealfix2` 的 `NO_SIGNAL` 均保留。[零训练核查](next_core_direction_20261106/MVC04_ZERO_TRAINING_RESULT_20261110.md)

### U47 MVC-05 固定线性读出停在覆盖门

登记 `MVCNET-MVC05-LINEAR-COMPLETION-ZERO-TRAINING-20261110`。14 份 MAT、129 条 E 评分试次的证书端点和隐藏通道扰动检查通过。两档真实隐藏贡献入集率逐人等权 92.15%，但 A09 仅 16/21（76.19%），低于 80%。总体签发 45/129（34.88%），名义左手 0/5、右手 45/124，左手未过 20% 门。按 `STOP_COVERAGE_GATE` 停止固定方案，未做等接收数效果比较或进入设计复核。保留 MVC-04 关闭、既有关闭及 `sealfix2` 的 `NO_SIGNAL`。零训练、零新 Run。[核查报告](next_core_direction_20261106/MVC05_ZERO_TRAINING_RESULT_20261110.md)

### U48 MVC-05 当前线性证书方案关闭

按用户授权和 v3.4 研究判断登记 `MVCNET-MVC05-LINEAR-COMPLETION-DIRECTION-CLOSE-20261111`。原覆盖门失败足以关闭固定 CP3/CP4 掩码、线性读出和两档半径实例。即使更换阈值，二分类区间证书仍与同半径的归一化间隔排序等价。原核查结果和未执行的等接收数比较按原语义归档，保留 MVC-04 关闭和 `sealfix2` 的 `NO_SIGNAL`。[原始核查](next_core_direction_20261106/MVC05_ZERO_TRAINING_RESULT_20261110.md)

### U49 v3.4 首选结构候选为非相邻片段条件时域卷积

登记 `MVCNET-NONADJACENT-CONTEXT-TEMPORAL-FILTER-DESIGN-20261111`。历史末端融合、分类前残差和池化后乘积的负结果使首选干预转到原生 IFNet 池化前的时域卷积。用同一试次另一非相邻片段决定本段的残差核系数，依次对照原生固定核、同段条件和全试次条件，判断跨段依赖是否值得投入。已有动态卷积是直接近邻。首项拟议检验为隔离 CPU 的反事实输入与作用路径核查。当前为候选设计，独立科研反驳和执行均待定。[研究简报](next_core_direction_20261106/nonadjacent_context_temporal_filter/research_brief.md)

### U50 非相邻片段条件时域卷积通过隔离 CPU 核查

登记 `MVCNET-NONADJACENT-CONTEXT-TEMPORAL-FILTER-ZERO-FIT-20261111`。固定局部卷积输入时，跨段条件只响应指定远段，同段和全试次条件分别呈现预期依赖。关闭及系数置零恢复原生 logits，四视图、raw CE 梯度与严格重载检查通过。完整 stem 的训练态共享 BN 另有跨段路径，归因需固定局部输入并注明所测位置。新增 4,055 参数，单线程 B1 raw 前向 p95 由 3.45 增至 6.42 ms。真实解码效用、目标机成本和独立科研反驳仍待核对。零拟合、零新 Run。[核查报告](next_core_direction_20261106/nonadjacent_context_temporal_filter/ZERO_FIT_RESULT_20261111.md)

### U51 限定查新及独立科研反驳后暂缓配对开发

登记 `MVCNET-NONADJACENT-CONTEXT-TEMPORAL-FILTER-REVIEW-20261111`。动态滤波与 TAdaConv 已覆盖条件调核和逐位置跨时上下文，保留指定远段相对同段与全试次等参数条件的窄检验。共享 BN 和 1,651 点连续 FIR 共同限制机制解释。完成一次 agy 实质审查，实际模型标识未返回。三拟议折的源验证在匹配幅度前均有 807/807 条可做同 run、原始支撑分离的错配。先补源侧片段原始支撑、条件可配对性和目标机成本，拟议 12 fit＋12 check 的矩阵限 9 process-hours（含 20% 余量），尚待测量与冻结。零拟合、零新 Run。[查新、反驳与处置](next_core_direction_20261106/nonadjacent_context_temporal_filter/NOVELTY_AND_DEVELOPMENT_20261111.md)

### U52 开发门已冻结，Lab10 四臂资格等待隔离 GPU

冻结原 Cue4 的离线四臂配对设计及 seed73-outer0/3/6，预先固定 B0、N0、C0 效用差、逐被试风险与错配机制门，矩阵成本限 9 进程小时含 20% 余量。核验 18 份原始 MAT；在同 run、原始支撑分离和四段幅度约束下分别匹配 707、660、679/807 条，均过 80% 门。真实 cue radix=1、63 点原生支路四臂接线的隔离 CPU 检查通过。资格 Run `2026-11-11_mvcnet_context_filter_lab10_qual1` 已在 Lab10 核验不可变包并启动调度，22:39 快照为 4 待、0 运行、0 完成、0 失败，等待 GPU 3 无驻留计算。目标机成本未知，12 次科学拟合尚未派发。[准备及调度记录](next_core_direction_20261106/nonadjacent_context_temporal_filter/DEVELOPMENT_PREPARATION_20261111.md)

### U53 Lab10 四臂资格与成本门通过

原资格 Run 四臂齐套，失败为 0。Lab10 核验四个检查点，本地核验九份核心回执。原 12 次拟合＋12 次检查估算为 6.8594 进程小时，计入 20% 余量为 8.2313 小时，低于 9 小时上限。下一步是完成科学轮正式派发及精简验收判读接线，继续使用冻结四臂三折和全拟合封存规则。科学任务当前尚未派发。[资格验收与成本复算](next_core_direction_20261106/nonadjacent_context_temporal_filter/qualification/QUALIFICATION_CLOSEOUT_20261112.md)

### U54 四臂封存、精简判读与 Lab10 CPU 入口通过验收

容量调度接入四臂全拟合封存，检查在封存后开放，精简包接入专用效应及条件机制判读。合成完整链路覆盖通过与停止分支，目标 Lab10 的 Python 3.9、包哈希、冻结数据和正式入口通过 CPU 验收。原 12＋12 科学轮尚无任务派发，等待共享控制器所需的独立累计执行上限。[派发验收记录](next_core_direction_20261106/nonadjacent_context_temporal_filter/DEPLOYMENT_ACCEPTANCE_20261112.md)

### U55 Lab10 科学轮已启动

用户确认独立累计 12 小时后，Lab10 接收原四臂三折矩阵。23:50:37 核对 12 项拟合中 2 项运行、10 项待运行，完成及失败均为 0。检查按全拟合封存顺序开放。原资格 Run 保留，成本门复算仍为含余量 8.2313 进程小时。[启动记录](next_core_direction_20261106/nonadjacent_context_temporal_filter/DEPLOYMENT_ACCEPTANCE_20261112.md#正式启动核验)

### U56 四臂科学轮效应门停止

12 拟合与 12 检查齐套并通过正式精简 intake。P0 对 B0 与 C0 增量不足，且仅 1/3 人同时优于三臂，登记 `STOP_EFFECT_GATE`。源侧错配未触发。实测 34.250 进程小时，Transaction 执行 7.825 小时，原口径累计至登记 18.134 小时。[收尾记录](next_core_direction_20261106/nonadjacent_context_temporal_filter/SCIENCE_CLOSEOUT_20261114.md)

### U57 VCN-P1 × ACM-R1 析因轮关闭，VCN-P1 优先作为论文主方法候选

36 项拟合、36 项检查经续接闭合。原 Run 归档为 `FAILED`，共享控制器对账为 `COMPLETE_MAX_ROUNDS`，按原起点结算 54.672／57 小时。组合相对原生 +3.144 点通过开发门；VCN-P1 相对原生 +2.411 点，ACM 加到 VCN-P1 上 +0.733 点且区间跨零，交互未过门。原 ACM-R1 的 `NO_SIGNAL` 保留。建议以 VCN-P1 起稿，组合列入开发消融。独立确认优先在未暴露队列中锁定 VCN-P1 对原生和强 raw／增强双 BN 的逐被试增量。若将组合升为主方法，须独立证明 ACM 加到 VCN-P1 后的实际增量。未启动训练或释放新 Claim。 [正式收尾与证据要求](acm-r1/factorial/FINAL_CLOSEOUT_20261116.md)

### U58 v4.0 启用，组合稳定性以 S8 两套 LOSO 的三臂比较推进

MVCNet 新工作切换至 `mvcnet-transaction-v4.0`。001 和 004 的 S8B 各 45 对 B0/S0 通过复用核查。方案只补 P0，分别判读对原生与对 VCN-P1 的增量，事前限定个体退化并核对删去任一 seed 后的增量方向。两套齐过门才建议进入独立确认。当前仍是设计，原 r8 宿主源码复验、Lab10 资格与本轮执行预算待完成。 [v4.0 设计及晋级门](acm-r1/factorial/S8_LOSO_STABILITY_PLAN_20261117.md)

### U59 S8 LOSO 的 P0 技术资格通过

001 和 004 的原 r8 压缩包及源码哈希复验通过。两种输入的零训练检查显示 CMC 的 IFNet 梯度归零，辅助端梯度保留。Lab10 两项 B64 P0 资格各完成五个源侧 epoch，驱动显存峰值分别 7,621 和 6,133 MiB。正式 90 拟合加 90 检查含 25% 余量估计 84.14 进程小时。双任务有效并发下建议累计 48 小时，等待正式轮授权及封存入口验收。正式训练未启动，原 ACM-R1 的 `NO_SIGNAL` 保留。 [技术验收与预算](acm-r1/factorial/S8_LOSO_QUALIFICATION_20261117.md)

### U60 四数据集结案与三臂研究身份冻结

两轮三臂 LOSO 已完成。组合相对原生在 3/4 个数据集通过总效应门，ACM 在 VCN-P1 之上的增量在 0/4 个数据集通过，保留两轮及原 ACM-R1 的 `NO_SIGNAL`。原生 B0、VCN-P1 S0、组合 P0 的身份、各版本源码与配置、核心结果和远程权重位置已集中登记。现有 540 份权重中 450 份已验哈希，001 的 90 份历史 B0/S0 权重保留精确路径与旧清单，CCMU 实际可读性待复核。既有历史结论及执行授权不变。[冻结索引与恢复入口](identity_freeze_20261118/README.md)

### U61 L3 v4.1 激活，双假设零训练筛查停止

登记 `MVCNET-TASK-EVIDENCE-SELECTION-004-ZERO-TRAINING-20261119`。004 本地 18 份 S0 源侧权重、54 个分区指纹和合成对照通过。频移 CVC 真实配对两 seed 的梯度余弦均为正，固定 raw μ 侧化叠加的 AUROC 增量均为负。两诊断均在冻结门停止，本轮转入 VCN-P1 对 raw／增强双 BN 的强对照补证设计。已暴露的四数据集可用于开发，核查范围内尚无合格独立确认队列。共享 L1/L2 留在 v4.0，既有冻结历史及原 ACM-R1 的 `NO_SIGNAL` 保留。零拟合。[诊断收尾](task_evidence_selection_20261119/CLOSEOUT.md) · [双 BN 设计与资产缺口](task_evidence_selection_20261119/DUAL_BN_FOLLOWUP.md)

### U62 双 BN 设计收束到同期开发比较

登记 `MVCNET-VCN-DUAL-BN-DESIGN-20261119`。004 的真实 r8 路径在合成零步检查中，仅共享增强运行缓冲时输出、梯度和 raw eval 逐值相同。D2 共享增强 affine 后聚合三种增强的梯度，保留为唯一新增拟合臂。004 历史 B0／S0 内部配对可追溯到原 CCMU 环境，拟用 D2 的新环境尚未取得严格复用资格。推荐同栈 S0／D2 做 2 seed×9 折开发比较，需要同期原生效用时补 B0。归档与本地资产复核仍无合格独立队列。保留预拟效用、稳定性及逐人风险门，生产模块与判定接线待准备。零科学拟合。[强对照、最小矩阵与成本](task_evidence_selection_20261119/DUAL_BN_FOLLOWUP.md)

### U63 004 两臂生产路径通过 CPU 零步验收

登记 `MVCNET-VCN-DUAL-BN-004-CPU-ZERO-STEP-20261119`。004 已接通同期 S0／D2 的 36 拟合全封存、36 raw 检查和已核验 intake 判定。CPU 验收确认两层 BN 的 1／3 路由、增强 affine 梯度聚合和 raw 重载隔离。合成往返走通精简回传与专用科学门，运行栈不一致和预测篡改被拒绝。下一步为两臂同型号卡的源侧资格及实测成本复算，当前尚未申请额度，零科学拟合和零优化步。[CPU 验收与 Lab10 资格方案](task_evidence_selection_20261119/dual_bn_004/CPU_ACCEPTANCE_AND_LAB10.md)

### U64 004 双 BN 资格通过并派发科学矩阵

登记 `MVCNET-VCN-DUAL-BN-004-LAB10-QUALIFIED-AND-LAUNCHED-20261119`。首个资格包在模型构造时缺动态载入文件，零完整 epoch。补齐原件后，S0／D2 各通过 5 个源侧 epoch 与冷重载，峰值均为 6,133 MiB，含余量外推 14.164 进程小时。正式科学轮为原 36＋36 闭集。首批使用 Lab10 全部 10 张候选卡，其余按容量自然补位，等待全拟合封存后检查。[资格核验与启动](task_evidence_selection_20261119/dual_bn_004/LAUNCH_AND_QUALIFICATION.md)

### U65 004 逐增强 BN 对双 BN 的增量未过开发门

登记 `AI4S-MVCNET-mvcnet-dual-bn-004-development-v1`。36 拟合及 36 检查齐套且 intake 已核验。S0−D2 为 +0.033 pp，seed 0／4 分别为 −0.570／+0.637 pp。效用及 seed 稳定性未过门，个体风险通过。按冻结判决 `NO_SIGNAL / STOP` 关闭该 004 开发比较。本轮未晋级独立确认。[科学收尾](task_evidence_selection_20261119/dual_bn_004/SCIENCE_CLOSEOUT_20261120.md)

### U66 001 三臂开发轮完成资格并启动

历史 001 CCMU S8B 对照与 Lab10 的训练栈不同，旧 Lab10 七源析因使用不同折和训练步数。采用同栈新拟合 B0／D2／S0，同批比较 S0 收益复现、D2 对 B0 的效用和 D2 对 S0 的配对下界及个体风险。CPU 与三臂源侧资格通过，正式 54 拟合及封存后 54 检查已派发，首次核对有 10 项拟合运行。科学证据待同一 Run 回传判定。[复用与冻结科学门](dual_bn_001/RESEARCH_BRIEF.md) · [资格与启动](dual_bn_001/LAUNCH_AND_QUALIFICATION.md)

### U67 001 上 D2 未保住 S0 的收益

54 次拟合与 54 次 raw 检查齐套并核验。S0−B0 为 +2.344 pp，两 seed 同向；D2−B0 为 −0.058 pp；D2−S0 为 −2.402 pp，被试配对 95% 区间 [−3.202, −1.620] pp。个体风险门通过，效用与不劣门未过。登记 `AI4S-MVCNET-mvcnet-dual-bn-001-development-v1`，`NO_SIGNAL / STOP`。001 开发支架保留 S0，独立确认待补。[科学收尾](dual_bn_001/SCIENCE_CLOSEOUT_20261120.md)

### U68 S0 上保留双侧相对功率的增强候选

提出一个待核查的 001 开发问题：当每个电极在训练中经历相同的幅度倍率分布时，左右同源电极使用同步倍率，能否比左右供体错配及原 S0 更好地解码未见被试？首项判别是源训练折中的跨会话幅度轮廓能否复现，以及匹配对照在真实量纲上是否确实不同。本次仅形成设计。已有泛化采集扰动构思、MLEV 以及固定 μ 侧化读出的历史结论见简报。[候选、旧案与最小对照](bilateral_gain_20261120/research_brief.md)

### U69 双侧倍率首版在错配区分度门停止

登记 `MVCNET-BILATERAL-GAIN-001-ZERO-TRAINING-20261120`。001 seed 0／outer 0 的源训练中，幅度轮廓在 T→E 和 E→T 分别为 7/8 和 6/8 人通过。错配后至少两对电极的左右倍率相差 ≥5% 的位置占 23.21%（5,980/25,760），低于 50% 门。停止当前固定倍率及错配对照实例。形状、原 S0 恒等回放和倍率匹配核验通过，零科学拟合、零目标评分。[零训练收尾](bilateral_gain_20261120/ZERO_TRAINING_CLOSEOUT.md)

### U70 S0 上检验 μ 频段相对邻频的局部起伏

首选设计比较同一电极的绝对 μ 功率和扣除邻频背景后的功率。先在 001 已暴露开发折的源训练人群做跨人、跨会话四类读出，判断固定局部频谱形状是否值得送入 S0 的 raw 分类头。后续归因需同时对照原 S0、等参数绝对功率头及可自由组合相同三频带的头。本次只形成候选，源侧门、宿主增量与独立复核均待验。[研究简报](local_spectral_contrast_20261120/research_brief.md)

### U71 局部频谱起伏未达到相对绝对 μ 功率的源侧增量门

登记 `MVCNET-LOCAL-SPECTRAL-CONTRAST-001-ZERO-TRAINING-20261120`。001 seed 0／outer 0 的 3,680 条源训练试次完成跨人、跨会话读出和 9,999 次分层标签置换。T→E 与 E→T 均超过置换 P95，起伏相对绝对 μ 功率分别为 −0.90 和 −1.95 pp，改善人数 4/8 和 5/8，低于事前 +2 pp 和 6/8 人门。停止当前固定频带、电极、窗口及读出实例，保留 S0 作为开发支架。零模型拟合、零外层评分。[零训练收尾](local_spectral_contrast_20261120/ZERO_TRAINING_CLOSEOUT.md)

### U72 用同一组片段检验跨人搭配的训练价值

提出在 S0 的 raw 分类损失中交换末两个池化位置。两名源被试各贡献 T、E 同类试次，同人交换和跨人交换使用相同四条试次，两者均跨会话、保持逐段边际和组内平均 logits。以原 S0 与同人交换判别跨人搭配是否改善完整未见被试试次的分类。首项核查为源训练批次的配对覆盖和零步作用路径。本次仅设计。[候选与对照](cross_subject_block_exchange_20261120/research_brief.md)

### U73 跨人晚段交换通过本地 CPU 零步验收

登记 `MVCNET-CROSS-SUBJECT-BLOCK-EXCHANGE-001-CPU-ZERO-STEP-20261120`。001 seed 0／outer 0 的本地首轮原采样覆盖 1,556/3,680 条源训练试次，四类为 40.87%–44.35%，均达到 20% 门。真实首批的两种映射产生不同的 raw 分类梯度，恒等供体、供受梯度路径、组均值和 raw 推理均通过核对。原 Lab10 使用不同 PyTorch 版本，生产栈采样和批次元数据接口待验。零拟合、零外层评分。[零步收尾](cross_subject_block_exchange_20261120/ZERO_STEP_CLOSEOUT.md)

### U74 跨人晚段交换生产入口通过本地 CPU 验收

登记 `MVCNET-CROSS-SUBJECT-BLOCK-EXCHANGE-001-PRODUCTION-ENTRY-CPU-20261120`。独立源码快照内的统一 runner 传递源试次身份，实际 MVCNet gateway 只替换 raw CE 的晚段特征。生产 loader 与本地原型的 58 批顺序和配对计数一致，四类覆盖门通过。恒等梯度、增量梯度、增强及对比路径、BN 和 raw 推理均通过。Lab10 对应版本 CPU 资格包已在本地生成，目标环境待验。零拟合、零外层评分。[生产入口验收](cross_subject_block_exchange_20261120/PRODUCTION_CPU_CLOSEOUT.md)

### U75 跨人晚段交换通过 Lab10 资格，正式轮待共享控制器接线

Lab10 CPU 复验重现 58 批顺序与四类覆盖。S0、W0、X0 各完成五个源侧 B64 FP32 epoch 与严格冷重载，显存峰值均为 7,619 MiB，三臂精简回传已核验。按自动预算授权登记累计 24 小时，正式 54 次拟合和 54 次封存检查的实测外推含余量为 27.75 进程小时。正式合同和候选判定器已冻结，现有共享控制器的单对照校验拒绝本轮合同，新增精确路由待授权。零科学拟合、零外层评分。[资格与停点](cross_subject_block_exchange_20261120/LAB10_QUALIFICATION_CLOSEOUT.md)

### U76 跨人晚段交换登记并启动正式三臂轮

2026-11-21 用户授权运行，平台准许接入本轮精确控制器分支。GPU 资格正式入库，科学 Run `2026-11-20_mvcnet_block_exchange_001_lab10-full-w1` 经控制器登记、上传和启动，同 Run probe 确认为 `RUNNING`。首批调度 10 拟合运行、44 待调度、0 失败。完成并封存全部 54 项拟合后进入 54 项 raw 检查。[派发核验](cross_subject_block_exchange_20261120/LAB10_QUALIFICATION_CLOSEOUT.md)

### U77 跨人晚段交换的两项均值增量未过冻结门

Run 的 54 拟合及 54 raw 检查齐套、零失败，精简回传已核验，登记 `NO_SIGNAL / STOP`。跨人 X0 相对 S0 提升 0.858 pp、相对同人 W0 提升 0.280 pp，分别低于 +1.0、+0.5 的预设门。两项 seed 方向和相对 S0 逐人风险均通过。同人相对 S0 的描述性差值为 +0.579 pp。关闭当前 001 交换方案，保留 S0 支架。[科学收尾](cross_subject_block_exchange_20261120/SCIENCE_CLOSEOUT_20261121.md)

### U78 跨人交换的晚段特异性未过源侧机制门

登记 `MVCNET-CSBE-001-SOURCE-MECHANISM-CHECK-20261121`。54 份封存权重的源侧零训练回放齐套。在完整输入上 X0 的 NLL 略优于 W0，两 seed 同向。整块晚段移除使 X0 的优势扩大，等幅度晚段干预使优势反转。晚段相对相邻参照的选择性为 −0.09532 与 +0.01717 nats，分别为 0/9 与 9/9 人同向，未通过事前合取门。保留开发轮 `NO_SIGNAL / STOP`，当前证据限于源侧模型读出。零拟合、零外层评分。[机制收尾](cross_subject_block_exchange_20261120/MECHANISM_CLOSEOUT_20261121.md)

### U79 跨人晚段交换收束，下一候选检查 β 高值时段的长度分布

依用户决定收束跨人晚段交换，保留 S0 开发支架。开发效用和机制判定分别沿用 U77、U78。下一问题是，给定一次试次中 β 高值的总时长和段数，长短分布更不均或更均匀，是否仍有可跨人复用的类别信息。首选对照是在相同功率、段数、包络平滑度上，分别增加等幅的有符号偏差和绝对偏差。拟在 001 源训练八人中做双向跨会话留人判读，过门才考虑接入 S0。状态为设计，零新拟合，零新效果评分。[研究简报与关键对照](beta_episode_duration_20261121/research_brief.md)

### U80 β 段长有符号偏差在双向源侧效果门停止

登记 `MVCNET-BETA-EPISODE-DURATION-001-ZERO-TRAINING-20261121`。冻结后用 001 的 3,680 条源训练试次完成八人双向跨会话留人比较。两会话覆盖均为 8/8。T→E、E→T 的有符号偏差相对常规统计分别为 −0.714、−0.265 pp，相对等幅对照分别为 −1.213、−0.589 pp，每方向均只有 2/8 人同时改善。按事前判定 `STOP_SOURCE_GATE` 关闭当前固定读出。保留 S0 开发支架，零网络拟合、零外层评分。[零训练收尾](beta_episode_duration_20261121/ZERO_TRAINING_CLOSEOUT.md)

### U81 β 段长分布方向收束，下一候选检验 S0 特征通道的逐人贡献

依用户决定收束 β 段长分布，保留 S0。拟比较按真实源被试的低端贡献、七人均值、伪被试低端贡献三种规则减弱同样数量的 IFNet 通道，并用完整 S0 判定实际效用。归档内九份 seed 51 原生 S0 权重及其分区已核验。每折留出的源检查人从未参与该模型拟合或选点，可用于一次已暴露开发协议内的零训练回放。仅登记设计，未读取本候选效果，未启动训练。[研究简报、关键对照和拟议门](source_channel_utility_20261121/research_brief.md)

### U82 S0 通道逐人贡献核查在效用与等幅对照门停止

登记 `MVCNET-S0-SOURCE-CHANNEL-UTILITY-001-SEED51-ZERO-TRAINING-20261121`。九折参考名单全封存后完成 5,184 条源检查。真实分组减弱读出比完整 S0、七人均值和伪分组分别低 3.627、4.032 和 1.640 pp，0/9 人同时优于两个分组对照。等幅后真实分组的负对数似然分别比均值及伪组高 0.020744 和 0.014083 nats。判定 `STOP_EFFECT_GATE`，当前固定方案收尾，保留 S0。零新拟合、零外层目标评分。[零训练收尾](source_channel_utility_20261121/ZERO_TRAINING_CLOSEOUT.md)

### U83 收束特征通道逐人贡献，下一候选只翻转电极平均波形

依用户决定收束 S0 特征通道逐人贡献方向，保留 S0 作为开发支架。U82 的原强度与等幅结果沿用原判定。下一候选在单条 raw 试次上保持每一对电极的电位差，平均原始输入与仅将 22 枚电极平均波形反号后的两次 S0 分类分数。关键比较是完整 S0、直接采用平均参考、整条 EEG 反号平均及固定其他空间方向反号平均。只有在留出被试上胜过平均参考，保留平均波形对称响应的第二次推理才有开发依据。拟用旧七源协议的九份 seed 51 S0，先验对照可辨度、原强度效用及配平后 NLL 均须分别判断。本轮仅登记方案，零新效果评分与拟合。[关键对照和最小核查方案](common_waveform_sign_20261121/research_brief.md)

### U84 电极平均波形反号在源侧效用门停止

登记 `MVCNET-COMMON-WAVEFORM-SIGN-001-SEED51-ZERO-TRAINING-20261121`。九折无标签资格均过门，封存后完成 5,184 条留出人检查。候选准确率 55.999%，相对完整 S0、直接平均参考、全局反号和伪方向反号分别为 −2.122、−1.196、+2.643、−1.292 pp。仅 1/9 人同时优于完整 S0 和 CAR。与三项机制对照逐试次分别等幅后，候选 NLL 差值为 +0.005392、−0.036126、−0.026119 nats，仍输给 CAR。原强度与机制两门均未通过，按冻结规则记 `STOP_EFFECT_GATE`，停止此固定读出并保留 S0。零拟合、零外层目标评分。[零训练收尾](common_waveform_sign_20261121/ZERO_TRAINING_CLOSEOUT.md)

### U85 电极平均波形反号收束，下一候选检验源近邻的预测误差能否跨人复用

依用户决定收束电极平均波形反号方向，保留完整 S0 开发支架。沿用 U84 的原强度与等幅判定。新的问题是，在另一名被试的试次上，能否用相似源试次的标签频率与 S0 平均预测之差纠正四类分数。关键对照为完整 S0、同一批源近邻直接投票、只用预测偏移、按四类分数找近邻后取残差。拟用 001 seed 51 九份封存 S0，按原七源验证行建库，在每折未参与拟合与选模的人上判定实际效用，并与三个机制对照分别配平输出变化。当前仅完成设计，零新效果评分与拟合。[关键对照与最小核查方案](source_neighbor_residual_20261121/research_brief.md)

### U86 源近邻预测偏差在效用与等幅对照门停止

登记 `MVCNET-SOURCE-NEIGHBOR-RESIDUAL-001-SEED51-ZERO-TRAINING-20261121`。三个对照在九折均通过区分度门，九库封存后完成 5,184 条留人检查。候选准确率 58.449%，相对完整 S0、直接投票、无标签偏移及分数近邻修正分别为 +0.328、+0.077、+0.617、+0.502 pp。仅 3/9 人同时优于 S0 与直接投票。三对逐试次等幅 NLL 差值分别为 +0.027511、−0.021123、+0.001027 nats。直接投票及分数近邻的机制对照未通过，按冻结规则记 `STOP_EFFECT_GATE`，停止当前固定读出并保留 S0。零拟合、零外层评分。[零训练收尾](source_neighbor_residual_20261121/ZERO_TRAINING_CLOSEOUT.md)

### U87 源近邻预测偏差收束，下一候选检验 μ 与高 β 的同侧空间对应

依用户决定收束源近邻预测偏差，完整 S0 继续作为开发支架。U86 的直接投票和等幅读数支持结束当前修正规则，普通投票作为后续同协议开发对照。拟用 001 原八源训练行做双向跨会话留人核查，检验同侧两频带的电极对相关模式能否在各频带功率、相关与对侧配对之外提供四类判别增量，并以等幅与同类异试次重配检验空间对应的解释。本轮只登记设计，零新效果评分与拟合。[关键对照与最小核查方案](cross_band_spatial_pattern_20261121/research_brief.md)

### U88 同侧 μ／高 β 空间对应停止于幅度覆盖门

登记 `MVCNET-CROSS-BAND-SPATIAL-PATTERN-001-ZERO-TRAINING-20261121`。原八源 3,680 条试次中，同侧与对侧的数值区分度在两会话均为 8/8 人通过。四组中心化三边范数同时超过 0.05 的比例，每人最高仅为 T 会话 65.38%、E 会话 69.91%，低于冻结的 80% 门，两会话合计资格各 0/8 人。按事前规则记 `STOP_NONDEGENERACY_GATE`，停止当前固定读出，保留 S0。此次结果限定于幅度覆盖，分类、等幅效果及异试次重配均未评分。零网络前向、零拟合、零外层评分。[零训练收尾](cross_band_spatial_pattern_20261121/ZERO_TRAINING_CLOSEOUT.md)

### U89 同侧 μ／高 β 空间对应收束，转向原分类头没有使用的类别线索

依用户决定收束 U88 的六电极、两秒窗固定方向，保留完整 S0 作为开发支架。上轮止于幅度覆盖，类别效用未评分。下一候选在 001 的九份封存 S0 中，用七名参考人的四类模板读取对原四类分数差没有贡献的特征方向，再将补充分数加回原分类头。完整 S0、全特征模板、仅凭原分数重建的校正和历史直接投票共同决定是否有跨人增量，完整模板与分数重建另做逐试次等幅比较。本轮只登记方向与建议门槛，零新候选评分、零训练。[关键对照与最小零训练核查方案](head_orthogonal_class_template_20261121/research_brief.md)

### U90 分类头未使用方向的类别模板在原强度效用门停止

登记 `MVCNET-HEAD-ORTHOGONAL-CLASS-TEMPLATE-001-SEED51-ZERO-TRAINING-20261121`。三项可区分性对照均为 9/9 折通过。九折封存后评分 5,184 条历史留人检查，正交部分模板准确率 56.906%，相对 S0、全特征模板、分数重建、历史投票各低 1.215、0.077、1.177、1.466 pp，2/9 人同时胜过 S0 和全特征模板。逐试次等幅后，相对全特征模板、分数重建的 NLL 分别低 0.000911、0.002070 nats。两项方向门通过，原强度效用门全部失败，判为 `STOP_EFFECT_GATE`，停止当前固定模板读出并保留 S0。零新网络前向、训练及外层评分。[零训练收尾](head_orthogonal_class_template_20261121/ZERO_TRAINING_CLOSEOUT.md)

### U91 收束分类头未使用方向的类别模板，下一候选只用电极镜像判断左右手

依用户决定收束 U90 的固定模板读出，保留 S0 作为开发支架。下一候选以原试次和左右镜像的两次冻结 raw 推理估计左右手条件概率，保留原 S0 的手类总概率、脚和舌概率。完整 S0、四类镜像平均、只改置信度而沿用原左右排序、错配左右电极为关键对照。拟用 001 seed 51 九份封存 S0，按人检查四分类增量和手内换边得失。此次仅登记设计与建议门槛，零新效果评分、零训练。[关键对照与最小零训练核查](hand_conditional_reflection_20261122/research_brief.md)

### U92 手内镜像读出止于置信度对照的区分度门

登记 `MVCNET-HAND-CONDITIONAL-REFLECTION-001-SEED51-ZERO-TRAINING-20261122`。001 seed 51 九份 S0 的 504 条原参考验证试次完成资格。候选相对完整 S0、四类镜像平均、错配电极均为 9/9 折通过。与只改置信度对照相比，每折仅 2–8 条的概率 L1 差超过 0.01，达到至少 6/56 条的折数为 3/9，低于冻结要求的 6/9。按 `STOP_NONDEGENERACY_GATE` 停止本次固定读出，保留 S0。四分类、左右手召回和等幅机制均未进入留人评分。零训练、零外层评分。[零训练收尾](hand_conditional_reflection_20261122/ZERO_TRAINING_CLOSEOUT.md)

### U93 手内镜像方向收束，进入自主源侧核查

依用户决定收束手内镜像，沿用 U92 的资格结论，保留 S0。首轮检验同试次宽带空间协方差参照相对简单 μ 空间统计、共享参照和错试次参照是否有跨人增量。[首轮设计](trial_covariance_reference_20261122/research_brief.md)

### U94 同试次宽带参照未过双向留人门

八名源训练人的 3,680 条逐试次判别已经独立复算。T→E、E→T 的四类宏召回分别为 28.914%、27.464%，相对同人同 run 的错配参照为 −6.836、−6.459 pp，相对无参照为 −1.365、−3.925 pp。同时超过二者的人数为 0/8、1/8。关闭当前六电极逐试次宽带白化实例。下一轮检验源人节律峰差能否在另一会话预报类别频谱偏移。[逐试次证据](trial_covariance_reference_20261122/REAL_PREDICTIONS.csv) · [下一轮设计](source_peak_transport_20261122/research_brief.md)

### U95 源人峰差的方向效果未在两会话复现

主 Agent 复算了两个方向共 112 对发送人和接收人。E 估峰、T 评分通过四对照和人数门。反向相对固定、反号、等剂量错配和零移频的余弦仅增加 0.0060、0.0153、0.0160、0.0076，均低于 0.02，3/8 人同时胜过固定和错配。停止该固定频移方案，保留 S0。下一轮核查同一源人不同试次间能否抵消类别偏移。[配对结果](source_peak_transport_20261122/PAIRS.csv) · [下一轮设计](within_person_conditional_loss_20261122/research_brief.md)

### U96 源人偏移校正与同人条件损失均未过门

九份模型的七源验证库中，本人偏移校正相对完整分数的 NLL 改善在 T→E 为 +0.000014、E→T 为 −0.002445 nats。跨人减同人条件损失分别为 T −0.020070、E −0.033209 nats，两会话各 0/9 份模型支持同人配对。独立复核了 126 行校正和 4,536 行条件损失。关闭同人条件损失方案。下一轮检查原生 flip BN 的反号教师是否能补足 raw 的类别次序。[冻结结果](within_person_conditional_loss_20261122/ZERO_TRAINING_RESULT.json) · [下一轮设计](native_flip_teacher_20261122/research_brief.md)

### U97 正确 flip 路由教师的集成增量不足

5,184 条封存留人行经独立复算。候选 58.179%、S0 58.121%，4/9 人净纠错为正。等幅三类 NLL 优于错误 BN 路由，原强度下输给只改置信度的对照 0.000284 nats。关闭本次教师设计。下一项比较保留或打散节律包络的两种等能量训练增强。[教师结果](native_flip_teacher_20261122/ZERO_TRAINING_RESULT.json) · [下一轮设计](envelope_preserving_rotation_20261122/research_brief.md)

### U98 等扰动能量下，保留的时间变化在两方向均可跨人读取

冻结的七电极物理读出在 T→E、E→T 均过门。保留和打散相位对应的宏召回分别为 30.661% 对 23.916%、31.572% 对 23.961%，7/8 与 8/8 人改善。原 flip、原始波形和同向旋转的包络预测逐条相同，符合算子恒等性质。首次进入受控训练准备，比较原 S0、逐频与共用旋转的单条 raw 分类准确率。[冻结诊断](envelope_preserving_rotation_20261122/ZERO_TRAINING_RESULT.json) · [预算与处置](envelope_preserving_rotation_20261122/EXECUTION_AUTHORITY.md)
### U99 包络保持旋转通过工程资格，001 三臂已在 Lab10 拟合

本机与 Lab10 CPU、三臂源侧 GPU 资格和成本门均已通过。北京时间 01:31:59 同 Run 拟合快照显示 9 项运行、45 项等待、0 项失败。S0 保留为开发支架，C0 的留人 raw 收益待本轮完整数据判定。[派发记录](envelope_preserving_rotation_20261122/LAUNCH_AND_QUALIFICATION.md)

### U100 保留包络的相位旋转未达到 001 留人训练门

同一 Run 的 54 次拟合和 54 次 raw 检查全部完成。精简回传、清单哈希和封存顺序已核验，并从全部单条预测独立重算。S0、I0、C0 的平均准确率分别为 58.468%、58.816%、58.507%。C0 对 S0 平均 +0.039 pp，两个种子均为正，低于 +1.0 pp 门；对等能量逐频旋转 I0 平均 −0.309 pp，种子 0、4 分别为 −1.177 和 +0.559 pp，平均增量和种子一致性均未过门。C0 相对 S0 无人下降达到 5 pp，最大下降 3.385 pp。

冻结判定为 `NO_SIGNAL`。保留 S0 作为开发支架，结束该固定增强方案的开发轮。七电极包络在源侧可读的证据仍成立，本次三臂比较显示该信号未转化为 001 单条 raw 的预定收益。[冻结判定](mvcnet-envelope-rotation-001-development-v1_decision.yaml)

### U101 C0 正式收束，S0 梯度同向筛选未支持训练投入

按用户决定关闭本次 C0 包络保持旋转，保留 S0 开发支架。后继问题从物理线索可读性转入 S0 实际分类损失。用九份封存 S0 比较六人同向筛选能否更准确地预测第七人的跨会话 raw 纠错梯度。126 项比较独立复算，T→E、E→T 的候选余弦分别为 0.01848、0.01663，三项等范数对照在两个方向均更高。候选同时胜过全部对照分别为 2/9、0/9 模型，未达到冻结的 6/9。关闭固定筛选方案。现有资产和反例下未留下能改变训练决定的下一项零训练核查，自主轮收尾。[简报](source_gradient_consensus_20261122/research_brief.md) · [核查收尾](source_gradient_consensus_20261122/ZERO_TRAINING_CLOSEOUT.md)

### U102 自主轮依用户纠正继续，时段协方差读出关闭

停止点改为首个通过资格的有限训练 Run 派发及同 Run 状态核验。用 001 九份 seed51 S0、7,263 个源验证行次及 5,184 条历史留源检查，复制原角色，候选四类分数来自同试次双频带前后窗对数协方差差分。相对单窗和对数功率差，各增 0.656、0.733 pp，等幅 NLL 也优于两项。相对 S0 降低 1.312 pp，只有 2/9 人同时胜过三个对照，最大下降 5.903 pp，判定 `STOP_SOURCE_GATE`。保留 S0，关闭这个固定加分读出。[冻结方案](relative_spatial_covariance_20261122/ZERO_TRAINING_PROTOCOL.json) · [结果](relative_spatial_covariance_20261122/ZERO_TRAINING_RESULT.json)

### U103 单试次整体增益收缩未形成分类增量

使用同九份封存 S0。源锚点先封存，各检查折原生 raw 前向与历史分数逐条核验。向源锚点收缩输入幅值再与原分数平均，相对 S0、等剂量反向、正反对称分别 −0.347、−0.193、−0.135 pp，4/9 人同时改善。等幅 NLL 相对两控制改善，准确率门未过，判定 `STOP_SOURCE_GATE`。关闭固定增益读出。下一轮限定到提示后单个电极丢失，检验同试次可靠前缀的校准价值。[结果](trial_gain_canonicalization_20261122/ZERO_TRAINING_RESULT.json) · [下一轮简报](within_trial_sensor_repair_20261122/research_brief.md)

### U104 单点电极丢失可用普通空间插值，逐试次校准额外收益不足

C3、C4 提示后单点置零使 S0 分别降 17.323、14.217 pp。真实前缀校准相对置零改善 15.365 pp，相对等邻及源群系数只改善 0.087 和 0.029 pp，2/9 人同时优于全部对照。相对 L2 为 0.17689、0.18234、0.17826。按冻结门关闭该固定校准，采用普通空间插值作为后续故障比较的强基线。[结果](within_trial_sensor_repair_20261122/ZERO_TRAINING_RESULT.json)

### U105 三电极缺失下的固定位置表未对插值建立双侧增量

两侧同源三个电极全窗失效时，普通空间插值相对 clean 为 −5.652、−4.938 pp。正确位置残差表相对普通、合并表和错表分别为 +0.395、+0.270 和 +3.897 pp，等幅 NLL 更好，左侧相对普通及合并仍为负。冻结门停止本表。该观察支持比较可见输入侧的表示校正，也限定了把错配表当唯一对照的价值。[结果](missing_strip_conditioning_20261122/ZERO_TRAINING_RESULT.json)

### U106 空间 BN 的缺失位置统计有平均效用，个体门未过

原插值、混合统计和错侧统计的增量分别为 +1.447、+1.051 和 +9.221 pp，两侧均值为正。候选同时优于三对照仅 4/9 人，最差对原插值 −5.903 pp。原冻结一致性及风险门失败，关闭固定空间 BN 缺失统计替换。Astra High 定向复核认为应区分固定校正与同试次教师配对，零训练需验证其他源人的可见故障特征是否能预测有用修正。[结果](missing_strip_spatial_bn_20261122/ZERO_TRAINING_RESULT.json) · [后继核查](matched_complete_teacher_20261122/research_brief.md)

### U107 源侧邻域修正有效，未验证同试次教师必要性

依定向外审所提强对照，在真类及完整教师第一类相同的供体内，按置信顺序错配完整目标，同一组学生侧输入和教师侧目标分布不变。126 项源人对比、最低可置换覆盖 88.50%。正确配对相对插值提升 4.584 pp，但相对条件错配仅 +0.115 pp，右侧 −0.394 pp，未过门。关闭固定同试次教师。[冻结结果](matched_complete_teacher_20261122/ZERO_TRAINING_RESULT.json)

### U108 非配对源类模板的特征近邻没有稳健留人增量

九折留出源人的两故障共 10,368 次成对评分。相对普通插值、分数邻居和直接投票分别 +0.154、+0.077、+0.106 pp，只有 3/9 人同时胜过全部控制。等幅对比分数读出 NLL 改善 0.00274，但右侧准确率差 −0.174 pp。停止该固定故障修正，回到完整通道，转查单次原输入长固定截止的滤波边界及模型敏感性。[结果](unpaired_fault_prototypes_20261122/ZERO_TRAINING_RESULT.json) · [新轮设计](deadline_boundary_consistency_20261122/research_brief.md)

### U109 固定截止的偶反射输入已接近原 S0，双补全探针未过门

核对 18 份原 MAT、全部 5,184 条留源检查和原始支持复算。访问真实未来的原 S0 为 58.121%，固定截止偶反射 58.005%，常数 56.443%，双边界 logits 平均 57.215%。7/9 人有至少 10% 试次预测分歧，平均探针相对两边界均值 −0.010 pp，只有 3/9 人改善。关闭原边界一致性设计，偶反射作为后续单截止对照。该结果仍用了真实试次前历史。[结果](deadline_boundary_consistency_20261122/ZERO_TRAINING_RESULT.json)

### U110 手对／非手对监督未见跨会话的方向稳定性

T 与 E 的固定组内错误比例分别为 27.307%、40.174%，两种交叉组合分别为 38.229%/34.464% 与 32.353%/27.473%。T→E、E→T 候选均未过与等幅重权及交叉组的科学门，梯度同时改善覆盖为 2/9、1/9 模型。结束固定分组监督。独立下一问为在单次截止时去除试次前的真实连续历史。[结果](anatomical_pair_supervision_20261122/ZERO_TRAINING_RESULT.json) · [后一方向简报](stateless_trial_edge_20261122/research_brief.md)

### U111 隔离试次偶反射无需新增边缘训练

固定决策时刻，可见左历史、纯试次偶反射、左端常数三臂为 58.005%、57.909%、57.813%，所有九人均在风险线内，无人达到 5% 预测改动和 2% 可恢复错误覆盖。不投入边缘训练，登记四秒状态自由偶反射为开发参照。[结果](stateless_trial_edge_20261122/ZERO_TRAINING_RESULT.json)

### U112 两份独立 S0 的同试次平均未建立超越错配的优势

同试次平均二种子 S0 准确率 58.931%，两个单模型 58.526%、58.410%。等类别与邻近置信度错配为 59.028%，配对未过增量门。结束这个基于逐试次教师身份的压缩设计。[结果](s0_paired_seed_consensus_20261122/ZERO_TRAINING_RESULT.json)

### U113 固定截止的两秒截短未保住 S0 的完整表现

隔离 FIR 分别对匹配原始 500 点处理，晚窗 46.316%，跨提示中窗 50.656%，提示前 25.096%，完整输入 57.909%。晚窗比完整少 11.593 pp，按门停止缩短信号时长。[结果](postcue_compact_readout_20261122/ZERO_TRAINING_RESULT.json)

### U114 保留全窗的 125 Hz 方案通过零训练门

重采样回升后，九份 S0 相对完整 250 Hz 平均 −0.019 pp，最差 −0.174 pp，9/9 人逐条预测一致率达 95%，波形相对 RMS 0.00707 对相邻点均值恢复的 0.14714。该证据支持保留全信号时长并测试原生 125 Hz，而实际低率网络效用与半秒边界机制待三臂开发验证。[冻结核查](physical_time_pooling_125hz_20261122/ZERO_TRAINING_RESULT.json) · [执行边界](physical_time_pooling_125hz_20261122/EXECUTION_AUTHORITY.md)

### U115 原生 125 Hz 三臂开发轮在 Lab10 开始拟合

本机、目标 CPU 及三臂 GPU 工程资格通过。实测总成本含余量 22.86 个 GPU 进程小时，登记累计 12 小时。2026-11-22 北京时间 17:29:34 核验同 Run 已拟合，9 项运行、45 项待调度、0 项失败。按用户要求在同 Run 状态核验后交接。[派发、门与预算](physical_time_pooling_125hz_20261122/LAUNCH_AND_QUALIFICATION.md)

### U116 T125 通过 250 Hz 非劣与逐人风险门，未通过池化优效门

54 项拟合和 54 项 raw 检查全部完成，精简回传验收和逐条预测独立复算齐套。T125 对 S0 为 +0.299 pp，seed 0/4 为 +1.235/−0.637 pp，均达到 −1.0 pp 非劣界限。两档个体风险均 0/9 人，最差 −2.517 pp。T125 对普通 A125 池化只增 0.096 pp，seed 0/4 为 +0.733/−0.540 pp，优效幅度和种子门均失败。登记 `NO_SIGNAL / STOP`，关闭该固定物理边界池化实例的晋级，保留 S0 支架。[科学收尾](physical_time_pooling_125hz_20261122/SCIENCE_CLOSEOUT.md)

### U117 T125 方向收束，低采样率非劣记录为效率证据

依用户决定关闭 T125 物理半秒池化，保留 250 Hz S0 作为开发支架。T125 的同协议非劣、逐人风险和源侧资格成本共同提供 001 开发效率证据，整体判定仍为 `NO_SIGNAL / STOP`。训练资格的进程耗时和显存与独立部署时延分开理解。下一项将 250 Hz S0 的分类与推理完整保留，仅检查训练辅助分支能否用低采样覆盖完整试次。以同样 500 点的提示后短窗作为匹配对照。[效率边界](physical_time_pooling_125hz_20261122/SCIENCE_CLOSEOUT.md) · [下一轮简报](asymmetric_auxiliary_rate_20261122/research_brief.md)

### U118 全窗低率辅助通过冻结源侧关系门与生产 CPU 资格

两份封存 S0 各取八源人 64 条原验证试次。全窗低率往返在八个 CVC/CMC 相似度块的最大平均漂移为 0.000366，等 500 点晚窗为 0.100779–0.130229。全窗侧同试次 margin 的最大下降约 0.000076，冻结门全过。三臂实际 B64／B32 梯度、raw 分类逐值及严格重载已在本机与 Lab10 CPU 验证。有限训练的待决点为 F125 能否以更少训练成本维持 S0 的 raw 泛化，同时超过等容量晚窗 L500。[冻结零训练](asymmetric_auxiliary_rate_20261122/ZERO_TRAINING_RESULT.json) · [生产资格](asymmetric_auxiliary_rate_20261122/PRODUCTION_CPU_CLOSEOUT.md)

### U119 F125 未通过工程速度门，转查训练辅助的电极空间维数

同一资格 Run 的三臂精简包已核验。F125 的稳态中位时间为 14.412 秒，S0 为 15.855 秒，比例 0.909 超过冻结的 0.90。收束这一具体时间压缩设计，零科学拟合。后继 P8 保留完整 250 Hz 时程，在训练辅助端使用只从源训练试次估计的八维空间基。J8 用相同秩和权重谱错配电极坐标，检验空间对应是否提供增量。[资格收尾](asymmetric_auxiliary_rate_20261122/GPU_GATE_CLOSEOUT.md) · [P8 冻结简报](spatial_auxiliary_basis_20261122/research_brief.md)

### U120 八维源侧空间基通过对比关系保持门

两份冻结 S0 的八个 CVC／CMC 块全部通过。P8 对原关系的平均绝对漂移为 0.01360–0.01684，J8 为 0.05110–0.06419。逐块相对错配的最大比例为 0.275，同试次 margin 最大下降 0.00285。两个种子的基底子样本八维能量占比分别约 99.05% 和 99.04%。冻结权重的复原探针没有更新模型或评分外层，支持检验八维训练输入，效用仍需同期三臂验证。[冻结回执](spatial_auxiliary_basis_20261122/FREEZE_RECEIPT.json) · [核查结果](spatial_auxiliary_basis_20261122/ZERO_TRAINING_RESULT.json)

### U121 P8 三臂有限开发轮已在 Lab10 开始拟合

本机和 Lab10 的生产零步验收及三臂源侧 GPU 资格通过，P8／S0 稳态耗时比例 0.86322。登记 14 小时累计上限，正式矩阵估计 30.59 个 GPU 进程小时，含 25% 余量。北京时间 23:28:11 核验同一科学 Run 进入拟合，3 运行、51 候调度、0 失败，raw 尚未开始。按用户授权停在同 Run 远端核验。[派发、冻结门与预算](spatial_auxiliary_basis_20261122/LAUNCH_AND_QUALIFICATION.md)

### U122 P8 通过非劣与逐人风险，真实空间对应未过等容量优效门

54 项拟合与 54 项 raw 检查闭合，精简包验收、18 个配对坐标和逐条预测独立复算全部通过。P8 对 S0 平均 +0.810 pp，两个 seed 分别 +0.791/+0.829 pp，9 人中无人下降达 5 pp。P8 对 J8 平均 +0.241 pp，两种子虽同向，幅度低于 +0.5 pp。J8 同样较 S0 增加 +0.569 pp，零训练关系保持不能替代真实空间对应的训练增量检验。按 `NO_SIGNAL / STOP` 收束固定 P8 的开发晋级，保留 250 Hz S0 支架，保留 P8 的限定开发与工程证据。[科学收尾](spatial_auxiliary_basis_20261122/SCIENCE_CLOSEOUT.md)

### U123 P8 宽带能量保留掩盖了部分手内类别信息损失

在 18 个配对坐标的冻结源验证中，完整波形 C3/C4 左右手 AUROC 为 0.677／0.588，P8 重构为 0.651／0.559，J8 为 0.598／0.501。P8 虽在源侧优于 J8，正式 raw 预测中两种子、两会话的左右手互判均更多，两会话共同改善仅 2/9 人。诊断为 `LIMITED_LEAD_ONLY`。固定 P8 保持原 `NO_SIGNAL / STOP`。若以后提出不同的空间基，优先验证同秩压缩能否在源侧跨人跨会话保住实际类别信息，再看原跨视图关系。零训练、零重新推理。[定向诊断](spatial_auxiliary_basis_20261122/MOTOR_DIAGNOSTIC_REPORT.md)

### U124 等幅奇模转动保住原对比关系，未修复左右手判别损失

依用户决定收束原 P8，保留 250 Hz S0。八源人双向留人的等秩 M8 对同折 P8 分别 +0.00156/+0.00032 AUROC，对等幅反向 W8 为 +0.00128/−0.00022，双向共同胜两对照仅 1/8。E→T 同时未过相对完整波形的非劣界。64/64 冻结 S0 跨视图关系门通过，按 `STOP_SOURCE_GATE` 停止固定转动，不启动训练。保留任务信息与对比关系应分别设门的设计约束。[零训练收尾](lateral_auxiliary_basis_20261123/ZERO_TRAINING_CLOSEOUT.md)

### U125 正式收束 M8，改查原生反射 CVC 是否尊重手类变化

依用户决定关闭 M8 同秩修复方向，保留 250 Hz S0。原 P8／M8 的对比关系和类别效用分离，U92 的推理镜像及 U110 的手对 CE 遗留负例约束新问题。首轮核查原生手类 CR 中四类 CE 已交换左右手标签时，是否值得只在 raw–CR CVC 对里对齐分类轴。用同一球面上的等幅错向和原 S0 作控制，要求真实同试次关系及与手类 CE 的梯度方向均有增量。[冻结构思](cvc_reflection_axis_20261123/research_brief.md)

### U126 手类反射 CVC 对齐通过真实源侧门及生产零步资格

H0 在 T/E 的同手类真配对边际对 S0 增益为 0.00365／0.00481，对 K0 为 0.01562／0.01752。联合手类 CE 梯度余弦对 S0 增益为 0.08848／0.07180，两会话同一 7/8 人通过方向检查。Astra 定向复核确认应保留独立 S0 门，等幅控制不能排除一般对比优化难度解释。生产端保持 CE、CMC 和 raw 路径，同场三臂实际 B64/B32 梯度与严格冷重载在本机及 Lab10 CPU 验收通过。[源侧闭合](cvc_reflection_axis_20261123/SOURCE_GATE_CLOSEOUT.md) · [生产验收](cvc_reflection_axis_20261123/PRODUCTION_CPU_CLOSEOUT.md)

### U127 H0 原生反射 CVC 三臂有限开发轮已派发

三臂源侧五轮 GPU 资格精简包通过核验，进程峰值均为 7,619 MiB。按测得的 32.61 个含余量 GPU 进程小时登记 15 小时累计上限。北京时间 2026-11-23 10:54:09 核验同 Run 已拟合，3 运行、51 待调度、0 失败。raw 检查等全拟合封存。按用户授权停在同 Run 状态核验。[派发、冻结门与预算](cvc_reflection_axis_20261123/LAUNCH_AND_QUALIFICATION.md)

### U128 H0 恢复闭合，互判减少但总体优效未过门

原 GPU0 两次 OOM 后，严格单卡任务准入的恢复轮保留 23 项拟合、仅新跑 31 项，然后完成 54 个 raw 检查。收尾字段错误用原封存产物在独立目录重放，零重复拟合及 raw 推理。精简入库和逐条复算通过。H0 对 S0 平均 +0.058 pp，seed 0／4 为 +0.965／−0.849 pp。相对 K0 平均 +0.405 pp，两种子 +0.926／−0.116 pp。通过逐人风险和左右手互判门，两个优效及相应种子门均未过。按 `NO_SIGNAL / STOP` 收束该固定开发候选，保留 250 Hz S0 支架。[科学与恢复收尾](cvc_reflection_axis_20261123/repair1/SCIENCE_CLOSEOUT.md)

### U129 H0 收束，连续 FIR 批内重叠止于覆盖门

依用户指令收束 H0，保留 250 Hz S0。U33／U38 的支持重叠事实没有改变。以 001 精确生产划分计算，随机 B64 内同 run 重叠边对源试次覆盖的上界在 seed 0／4 分别为 2.657%／2.658%，均低于冻结 5% 门。停止保持原随机采样的固定实例。此次不读 EEG，未计算负例困难度。后续改查训练时 CMC 中同试次 raw 与极性反号的信息是否适合共享一个跨支分支参照。[冻结与上界](contrast_fir_20261123/research_brief.md) · [结果](contrast_fir_20261123/ZERO_TRAINING_RESULT.json)

### U130 CMC 同试次极性等权合并未过源侧门

八名源人两会话和八份逐人排除的冻结 S0。E0 对等规模 3:1 控制的类别余弦边际增量约 0.00014，低于 0.001 门。会话内真配对边际对 S0 下降 0.00663／0.00606，均超出 0.005 容许值。两次跨会话比较的类边际使用双分支对称余弦，相互为转置，实为同一对比的重复，并非独立复核。即使只用单一方向，配对保留门仍失败。收束等权与 3:1 固定实例，保留独立视图配对。[冻结简报](cmc_even_polarity_20261123/research_brief.md) · [结果](cmc_even_polarity_20261123/ZERO_TRAINING_RESULT.json)

### U131 CVC 编码器分组保留更多负项权重，未过真配对门

封存 S0 八源人双会话表明，异试次跨编码器负项占 softmax 权重约 20%–22%，8/8 人在两会话的保标签真分组保留权重均高于混合分组。但 raw–flip／freq 的同试次取回率相对等量混合组差 −3.52 至 −6.84 pp，未过 −2 pp 门，原配方不改。COC 旧案只删直接碰撞边，当前两个分组都删掉该边；当前实测与旧历史不作配对。后续关注编码器看到完整时程后，最厚的投影层需要哪些时序维度。[冻结简报](cvc_encoder_partition_20261123/research_brief.md) · [结果](cvc_encoder_partition_20261123/ZERO_TRAINING_RESULT.json)

### U132 编码后全窗时间模态窄头未过几何门

固定源侧 D384 对四类及手类跨会话边际与同试次边际均满足保留界，但两会话平均余弦漂移为 0.06837／0.06610，均高于 0.035，且未取得相对等秩 J384 的 20% 改善，只有 4/8 人的共同方向为正。关闭这个固定编码后时间投影。类别边际与表示几何受到的影响再次分离。下一轮转查分类头的相邻时段权重共享。[冻结简报](encoded_temporal_modes_20261123/research_brief.md) · [结果](encoded_temporal_modes_20261123/ZERO_TRAINING_RESULT.json)

### U133 相邻硬共享胜过首尾共享，但相对完整分类头损失明显

八名排除源人、两会话全 3,680 条原训练试次。L4 对同秩 R4 的四类宏召回 +10.26／+8.00 pp，7/8 人共同为正。相对完整 250 Hz S0 −4.41／−5.71 pp，手类 −3.86／−6.93 pp，逐人风险也未过，关闭硬共享。保留时序配对有结构性差异、半秒间通道权重差不可固定归零的证据。下一轮在独立拟合重复下检查等范数微扰，区分邻近关系与一般减权，准备全容量软约束。[冻结简报](local_time_readout_20261123/research_brief.md) · [结果](local_time_readout_20261123/ZERO_TRAINING_RESULT.json)

### U134 相邻软约束在等范数首尾对照门停止

P8 同期另一拟合重复的八份封存权重，原冻结源角色的全样本。相邻方向对 S0 四类宏召回 −0.150／−0.522 pp，均在容许界内。相对等范数首尾方向，两会话 NLL 分别多 0.002800／0.005249 nats，未过两会话需改善门。关闭本次全容量软约束，保留 U133 硬共享结果的原边界。下一轮改查原 CVC 接入的特征 dropout 是否让两视图比较不同坐标。[冻结简报](temporal_readout_prior_20261123/research_brief.md) · [结果](temporal_readout_prior_20261123/ZERO_TRAINING_RESULT.json)

### U135 CVC 批级共享掩码通过冻结零步门

D0 的八源真配对边际绝对误差为 0.01124–0.01176，原生 S0 为 0.13915–0.20398，等规模独立掩码 I0 为 0.13796–0.20310。各门通过，8/8 人两会话两视图同向、异试次类别边际保持。Astra 定向复核同意一次三臂有限开发，并指出 softmax 跨分支负项权重和梯度尺度仍是竞争解释。仅支持检验训练后 raw 效用，记录真实分母质量和梯度后进入生产资格。[冻结简报](cvc_shared_dropout_20261123/research_brief.md) · [结果](cvc_shared_dropout_20261123/ZERO_TRAINING_RESULT.json) · [复核](cvc_shared_dropout_20261123/TARGETED_REVIEW.md)

### U136 D0 同一正式 Run 已核验进入拟合

本机与 Lab10 CPU 零步及 Lab10 三臂五轮源侧资格入库通过。累计预算 16 小时，含余量进程小时 36.09。正式 001 科学 Run 经独立远端核验的快照为三拟合运行、51 待调度、零失败，raw 检查在全局拟合封存后进入。下一判断须等全部 54 拟合与 54 raw 检查完成，按原冻结科学门处理，不读取中间效应。本次授权在派发和同 Run 核验完成处结束。[派发与预算](cvc_shared_dropout_20261123/LAUNCH_AND_QUALIFICATION.md)

### U137 D0 的配对保真度未转化为 raw 分类收益

第二次恢复复用 47 项、补齐 7 项，全部 54 项拟合封存后完成 54 项 raw 检查。已核验精简包和 31,104 条预测。D0 对 S0 平均 −0.463 pp，对 I0 −0.299 pp，两项比较的两个种子均不同向。逐人风险门通过。按冻结科学门登记 `NO_SIGNAL / STOP`，收束此共享掩码实例，保留 250 Hz S0。源侧配对结果保留其原有限解释。本次未启动新训练。[收尾与结果](cvc_shared_dropout_20261123/repair2/SCIENCE_CLOSEOUT.md)

### U138 精确对侧电极的任务图对应未在两会话方向复现

扣除粗略侧化后，八名源人的真实六点配对相对同侧分区错位的余弦差在 T→E 为 +0.092，E→T 为 −0.426，两个方向共同胜出者仅 1/8。收束按该依据给 raw 空间核绑定同源对侧权重的候选。此核查未检验联合学习效用。运动想象研究已有同人左右手 CSP 镜像相关性及镜像对比训练的先例，两者都不能代替本轮的跨人检验。[源侧协议与结果](mirror_spatial_filters_20261126/SOURCE_RESULT.json) · [CSP 对照原文](https://pmc.ncbi.nlm.nih.gov/articles/PMC4823701/) · [镜像对比原文](https://arxiv.org/abs/2409.00130)

### U139 提示边界的类别谱形变化没有胜过错位时段

两个会话方向上，三电极 μ/β 类别图按提示前后取差的跨人余弦分别为 +0.060 和 +0.016，按错位时段取差为 +0.261 和 +0.423。只有 1/8 人在两个方向都支持提示边界。收束按此谱形依据分配两个时间核的候选。Neon 请求的审查回应指出该指标只覆盖粗谱形，两种时段划分的接缝数也不同；已有开发证据足以停止投入。[源侧检验](cue_temporal_banks_20261126/SOURCE_RESULT.json) · [交叉意见](cue_temporal_banks_20261126/NEON_REVIEW.json)

### U140 逐电极剂量相同的两种中央排扰动首次获得本轮有限训练资格

G0 和 J0 在同一试次使用相同方向符号时，C1、C2 的取样方向相反，其余三列相同。八名源人两个会话的全部 3,680 条源训练试次均达到组合差异门，逐试次双方向能量误差为零。C3/C4 的线索在两种处理下相同，手类 AUROC 对干净波形的逐人平均绝对变化 T/E 为 0.0072/0.0089。保留的判断是可以做同剂量、不同联合方向的训练对照。若开发结果仅胜过 J0，仍须考虑对照破坏局部平滑的解释。类似传感器旋转增强在既有 MI 对照中未显示稳定优势，不能据空间扰动本身主张原创或有效。下一判断取决于实际 S0/J0/G0 同期拟合。[源侧结果](central_row_augmentation_20261126/SOURCE_RESULT.json) · [科研反驳](central_row_augmentation_20261126/NEON_REVIEW.json) · [相关原始研究](https://cedricrommel.github.io/assets/pdfs/systematic_comparison.pdf)

### U141 中央排候选进入三臂配对开发比较

S0、J0、G0 的 Lab10 源侧五轮资格均通过，实测整进程峰值为 7,619–7,627 MiB。正式 Run `2026-11-26_mvcnet_centralrow_001_lab10-full-w1` 已核实，11 月 26 日 17:08 北京时间有 10/54 个拟合任务运行，失败数为零。科学判断仍以全部拟合封存后的干净 raw 配对检查为准。本轮同步保留镜像空间核与提示时段时间核的两项负结果。[本轮选案与派发](central_row_augmentation_20261126/SELECTION_AND_DISPATCH.md) · [调度快照](central_row_augmentation_20261126/FIT_PHASE_PROBE.json)

### U142 中央排同向扰动未达到干净试次增益门

在 BNCI2014001 已暴露开发协议上，54 项拟合和 54 项干净试次检查完整核验。G0 相对 S0 为 +0.087 个百分点，相对剂量匹配的 J0 为 +0.231 个百分点。两项平均差均低于冻结门，Seed 0 分别持平和下降。逐被试退化门通过，两项被试 bootstrap 区间均跨零。源侧保真和联合波形差异足以支持做训练对照，现有结果不足以支持这项同向扰动带来稳定、具实际幅度的增益。登记 `NO_SIGNAL / STOP`，收束该设计。[科学收尾](central_row_augmentation_20261126/SCIENCE_CLOSEOUT.md) · [控制器判定](mvcnet-centralrow-001-development-v1_decision.yaml)

### U143 相邻时段乘积的类别方向未跨两会话复现

保留完整 S0 线性头，候选预测 IFNet 相邻半秒有超出单段类别均值的联合信息。八份分别排除一名源人的历史 S0 在其各自坐标中回放全 3,680 条源训练试次。T 会话相邻对远距的余弦中位数为 +0.01112 对 +0.00848，7/8 人相邻为正。E 为 −0.01066 对 −0.00147，仅 2/8 人为正，按事前门关闭这一固定相邻读出。转查源监督中同类关系跨人是否有独立作用。[候选关闭](serial_selection_20261127/ADJACENT_CLOSEOUT.md)

### U144 固定来源的跨人同类正对止于批内覆盖上界

第一个必要折的 100 轮 B64 生产批次中，允许重复使用受体并忽略配平时，同时拥有同人与固定异人跨会话同类正对的比例也仅为 37.58%–41.81%。八个类别×会话层都低于事前 50% 门，在本机及 Lab10 原生产栈复算一致。关闭此固定配对和现有采样的联合实例。零波形读取、前向与训练。[候选关闭](serial_selection_20261127/MATCHED_PAIR_CLOSEOUT.md)

### U145 抽取前三角核的源侧折叠分量通过必要性门

在一个固定 S0 的 3,680 条原源训练试次上，8/8 人同时通过预先冻结的三门。原池化的 >1 Hz 贡献 RMS 为去均值参考的 31.9%–37.1%。前滤波相对零频曲率匹配的后滤波，高频分量 RMS 比为 0.500–0.544。两臂完整激活的差 RMS 为参考的 17.6%–21.6%。说明有可干预的原激活分量，保留候选进入一次有限三臂比较。收益及边界仍由独立拟合后的干净试次判断。[冻结简报](ifnet_pool_antialias_20261127/research_brief.md) · [源侧结果](serial_selection_20261127/POOL_ALIAS_SOURCE_RESULT.json)

### U146 IFNet 抽取前抗混叠进入 Lab10 三臂开发比较

三臂生产 CPU 验收和 Lab10 真五轮资格通过。一次正式 Run `2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1` 已启动，11 月 27 日 15:09 北京时间为 7 项拟合运行、47 项待执行、0 项失败。仅在全部 54 拟合封存后做干净试次比较。本轮三臂为原池化、抽取后平滑、抽取前滤波，保留事前优效与个体风险门。科学结果待封存。[资格及派发记录](ifnet_pool_antialias_20261127/SELECTION_AND_DISPATCH.md)
