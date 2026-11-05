# DBConformer：当前研究理解

## 基模来源与认识边界

同一论文的加工材料不作独立证据计数。路径从本文件位置解析：

| 材料 | 用途 |
|---|---|
| [DBConformer-paper.md](../../../../refs/paper-cards/dbconformer/DBConformer-paper.md) | 原文读取材料 |
| [DBConformer-paper-card.md](../../../../refs/paper-cards/dbconformer/DBConformer-paper-card.md) | 贡献与证据边界 |
| [DBConformer-paper-xray.md](../../../../refs/paper-cards/dbconformer/DBConformer-paper-xray.md) | 设计推演 |
| [DBConformer-note.md](../../../../refs/paper-cards/dbconformer/DBConformer-note.md) | 综合理解 |

### 基模设计理解

作者报告：T-Conformer先混合通道并保留时间patch，S-Conformer按通道提取局部时间特征、沿时间池化后保留通道token；两路Transformer输出拼接分类（X-Ray §1–4；Note §1–3）。阅读解释：关键取舍是保留哪一维作为后续注意力可直接比较的token；时间支路仍含空间混合，空间支路也含时间编码。论文消融支持整条S支路/注意力汇聚在所测设置中的作用，但未证明空间token是唯一增益原因，也未证明两路统计独立。当前实现以 `src/models/dbconformer/baseline.py`、`src/baselines/dbconformer.py` 为核对入口；EA不等同类别分布对齐。独立补充表S1/S6未提供，依赖它们的结论保持未知；本地各方法增量与关闭边界见下方证据记录。

下文区分作者报告、阅读推断、实现和本地实验证据；局部筛查只约束其冻结范围。重要认识附适用条件、直接依据和可能改变判断的新证据。历史轮次链接原报告；运行态只读 STATE.yaml。论文材料提出的问题不限定该Program的全部研究范围。

## 当前综合、反例与未决问题

**2026-11-05 几何R1后下一轮重评（仅设计）**：完整比较三视角六候选并限定核对一手前作，当前仍无论文核心方法；独立Grok原判NO_QUALIFIED_CORE_DIRECTION、备选NONE，主Agent接受。只把“可独立识别的测量迁移能否与神经/任务差异分开”作为有退出条件的资料/理论问题，不接受模板inverse＋loss或低秩/平滑的换名版本。共享模板不观测个体L_s，前向零重建可能代数恒可满足，破坏算子还可能被后层学回；须先关闭识别、非等价控制及真实测量资产缺口。原几何合同仅注册四项EEG/标签/身份/metadata，未注册个体测量识别材料，不据此声称外部不存在。若这些门不能关闭，停止该实例及同信息等价改名扩展，不把L1检索或L2拒判递补核心。原宿主源码另更正T显式radix=1，不把默认radix=2当实际多尺度或性能缺陷。0新训练/前向/EEG特征目标分析/Run/合同/预算/Claim，SGP直接优化和旧几何对象仍停止，State/旧合同与成本不变。审后控制补充是主Agent修订，未伪称外审改判。[选择依据、关键对照与停止条件](reassessment_20261105_post_geometry/research_brief.md)、[原判与处置](reassessment_20261105_post_geometry/review/DISPOSITION.md)。

**2026-11-05 源内识别R1完整收尾**：4次100epoch/3600步、单次attempt全部完成，原SCI封装错误经同Run元数据重放恢复，0重训；远端全量核验、2.89MB精简回传/intake、冻结分析、独立全特征重算与标准决策已完成。INCONCLUSIVE/STOP：16个C均正，但仅11/16观测过噪声相对门、4/8人在两个encoder下均过，不满足冻结全面一致性。正号不是信噪保证，不能选择子组/更佳encoder补救；不支持据此建session关系loss，也不证明整个类别几何家族无效。共享encoder和历史暴露保留，0Claim/后继。State暂停、无活动Run，SGP直接优化继续停。[结果、局限与处置](source_geometry_r1/FINAL_REPORT.md)。下方启动段均为历史快照。

**2026-11-05 源内识别R1已启动（SGP仍停止）**：用户已明确授权补齐执行并启动4编码器，取代此前“仅设计/预算未分配”阶段限制。24h独立预算、原锚15:00Z计准备；A/B×两拟合会话、seed3/100epoch固定final，4SCI+1零拟合TECH，0重试/后继。真实GPU64样本前向exit0、峰值1217MiB；首次node因published缺transaction_id汇总失败，已保留原件并由原冻结消费者验证唯一父身份的派生补齐，0重执行后恢复同一Run。当前1运行/3待调度/0完成/0失败，无科研结论；4项完整后才核验/intake/冻结分析并停止。SGP直接优化、旧判和旧账保持关闭。[启动与封装恢复](source_geometry_r1/STARTUP_REPORT.md)。

**2026-11-04 下一轮源内识别准备**：冻结meta哈希核验，固定排除subject0后8名source共4608条，16个subject×session单元每类72条；每单元6个实际采集run按排序序号交错成两半，每半每类36条，cue窗不重叠但不宣称独立。旧BPM审计四文件SHA与冻结资产一致，逐run滤波源码和helper身份已回查，未重读波形。提出A/B互斥4人组×拟合会话交换的4编码器草案，查询人两会话均不参与其拟合；融合classifier输入预期80维，当前forward只返回logits，尚未抽取。来源已暴露、共享编码器依赖和普通CE解释仍保留；只有元数据可行性成立，尚无关系复现结果、主方法或执行资格。0拟合/forward/目标效果分析，预算UNASSIGNED，SGP直接优化仍停。[角色、描述量与待冻结判读](reassessment_20261104_post_sgp/source_identification_design/PROTOCOL_DRAFT.md)。

**2026-11-04 用户停止SGP直接优化并重选核心问题**：SGP均值改善、个体风险失败及机制未分离均保留为后续设计约束；不再默认补梯度方向遥测、受限投影、强度/阈值/分组/Adam变体，旧预算不转移。该最新明确停止更新下方历史条件性后继的优先级，不追改科学结果。三视角6候选归为5类后，尚无一项具论文核心方法资格；优先设计“编码器未接触的源会话/源被试上，类别相对关系是否含超出普通分类几何与采样噪声的可迁移信息”。这是有退出条件的源内识别问题，不先指定新loss/训练臂。Grok原判NEEDS_REVISION，主Agent已按训练暴露与RKD/SupCon反驳重写，未再次外审；K=2归一恒定与K≥3近单纯形退化是纸面反例，实际数据未测。0新拟合/forward/数据分析/Run/预算/Claim，State不变。见[下一轮方向与控制](reassessment_20261104_post_sgp/research_brief.md)、[SGP设计约束](reassessment_20261104_post_sgp/SGP_DESIGN_CONSTRAINTS.md)。

**2026-11-04 SGP梯度冲突与风险归因（仅旧证据）**：54任务/621000步全轨迹与合法源metadata、最差配对预测已核对。P/C冲突触发38.70%/36.14%，风险两例并非最大冲突/改变量，且相对改变量与负余弦在非退化对称投影下数学等价，不能作双证据。增强与实际Adam的组别方向、session结构及共享BN替代解释未区分；整体源验证改善也未预警两处目标风险。第一阶段完成但机制INCONCLUSIVE，第二阶段门未满足，0新候选/0训练，保持暂停。用户第三阶段“若唯一新受限候选仍均值改善却失败个体风险则终止方法线扩展”已记录，未假装新实验已发生。[诊断与处置](sgp_r1_budget1/attribution_20261104/REPORT.md)。

**2026-11-04 SGP-R1 budget1 冻结收尾**：54SCI及3旧TECH复用已完成核验/intake/分析/决策；P-B0 +1.2539pp（p=.0234375）、P-C +1.9387pp（p=.00390625），均有平均统计改善，但各1/18配对低于−3pp（subject7 seed3对B0−3.125pp，seed4对C−3.6458pp），冻结判定GROUP_STRUCTURE_UTILITY_NOT_ESTABLISHED_STOP。关闭固定实例，不放宽风险门或事后剔人；不把9人已暴露筛查改称独立确认或已找到可部署适用条件。State COMPLETE_MAX_ROUNDS/paused，无active Run/operation，0后继/Claim。[结果及核验证据](sgp_r1_budget1/FINAL_REPORT.md)，证据AI4S-DBCONFORMER-dbconformer-sgp-r1-budget1。下方运行/等待段为历史快照。

**2026-10-31 SGP-R1 budget1 授权修订并启动**：保留原3TECH资格与成本停止；累计预算72→144h、原起点/账本不变，单并发保守估算112.68h，120hSCI/126hTransaction/6h收尾。原3TECH独立入库与源闭集重新核验，新Run只54fresh SCI，标准控制器已确认远端接收。三臂科学配方/双对照/风险判定不变、无重试/后继。下方原成本停止为历史边界，本次不抹除；科学效用仍待完整SCI与intake。[修订启动记录](sgp_r1_budget1/STARTUP_REPORT.md)。

**2026-10-31 SGP-R1 实际成本停止**：三臂完整GPU TECH已通过并由冻结验证器复核；SCI派发前成本门失败，54SCI预计112.68h超过50h上限，实际SCI为0。当前不是NO_SIGNAL或方法负结果；P-B0与P-C效用及个体风险未检验。标准完整科学回传尚未形成，保留同Run失败，不重试或改预算。[现场核验](sgp_r1/status_check_20261031/REPORT.md)。此前启动段为历史快照。

**2026-10-31 SGP-R1 授权、生产接线与启动更新**：用户现已明确授权本适用条件研究的生产接线、GPU资格、预算设计与科研训练。新72h/57fit（3TECH+54SCI）合同已冻结并派发唯一Run；远端已接收，当前smoke等待GPU容量，GPU资格与科研结果均待真实产物。生产接线、本地正反例及最终包冷导入/parser已过，Grok增量审查READY_WITH_LIMITS，范围和本地补充验收明确分开。下方“预算未授权/生产未接线/仅纸面”段是此前阶段快照，已由本条执行授权更新，不追改原记录。研究仍是共享batch图下分组结构的暴露适用条件筛查，不是成熟原创主方法或独立确认。[启动记录](sgp_r1/STARTUP_REPORT.md)、[冻结合同](dbconformer-sgp-r1.yaml)。运行态只读STATE；真实技术和科学结果未回传前不作效用结论。

**2026-10-31 适用条件问题具体化（用户选择后）**：已将“真实被试分组的冲突投影是否比同计数随机分组更有价值”具体化为同次forward、真实前缀CE按总batch数加权、35个四对四源被试分组轮换、类内置换伪组、增强梯度原样加入的三臂纸面研究。独立算子的合成CPU检查支持关闭恢复原CE梯度及Adam一步、组计数匹配、无额外BN/RNG状态变动；不代表DBConformer FP32/GPU资格或科学效用。0 EEG读取/0科研拟合/0GPU，生产训练器与三臂判定尚未接线，预算未授权，旧NEEDS_REVISION保留。[具体规则及结果去向](reassessment_20261031_post_sqk/research_brief.md#2026-10-31-用户选择后的适用条件研究具体化)、[记录](reassessment_20261031_post_sqk/APPLICABILITY_RECORD.json)。判断仍是适用条件研究待科学检验，不将其改称已成立主方法。

**2026-10-31 SQK结果与下一方向更新**：SQK-R1已完成2TECH+36SCI的冻结核验与标准intake/决策，B0动态Q/K与Cstatic固定Q/K均值56.7805%/56.4236%，差+0.3569pp、精确被试符号翻转p=.4082，4/18配对低于−3pp。原判`SQK_R1_DYNAMIC_UTILITY_NOT_ESTABLISHED_STOP`；不改称等效或静态简化成功，不推断空间信息无用。[结果](sqk_r1/FINAL_REPORT.md)，证据`AI4S-DBCONFORMER-dbconformer-sqk-r1`。这降低继续扫描Q/K层数、静态图或相近池化配方的投入优先级，没有证明历史失败来自优化冲突。

本轮三视角六候选及限定近邻核对后，只优先继续纸面研究“真实被试分组的冲突投影是否比随机分组更有价值”，保留完整宿主并控制真实/混源增强梯度及同图BN/dropout。Grok独立反驳原判`NEEDS_REVISION`：现方案属于成熟梯度手术的适配，尚不足指定为论文主方法；真实被试分组同时携带session等共变量，三臂不能证明纯来源因果。主Agent已收窄为适用条件/对照研究并明确类内置换控制，未重新外审或获得实验资格。跨源原型、前端共享/秩、可靠拒判和缺通道联合重建均保留为有风险备选；不将未选或未实现记为科学失败。若最终只有常规适配，停止主方法投入并保留DBConformer baseline。当前仍无成熟下一主方法；[方向、依据、关键控制和停止条件](reassessment_20261031_post_sqk/research_brief.md)。此次0拟合/0推理，不改变旧合同、状态或预算。下方10月29日设计段保留当时认识，不能代表SQK之后的优先级。

**2026-10-29 v3.3设计更新（无新实验）**：SBN收尾后已激活L1/L2/L3 v3.3，旧结果和状态不改。三视角六候选比较及Grok独立反驳后，下一方向优先继续设计“空间attention是否需要当前trial驱动的关系”，用完整动态QK与由原位置表驱动的固定QK比较，保留V/O、FFN、LN、残差与两层S编码器。依据是BNS整块删减没有分离动态关系与其他变换，不是BNS证明S无用。源码`MultiHeadAttention:190–216`和`TransformerEncoderBlock:246–265`确认该作用位置；参数形状相同仍不证明优化等价。该方案未实现、未训练，最近邻Synthesizer已有静态attention先例，贡献与最终独立评价仍未建立。若控制不够或只是常规适配，应继续收束。[本轮设计、选择依据与对照](reassessment_v33_20261029/research_brief.md)。

原初“均值＋有符号双段差”方案已降为低优先：同位置SVE失败仍保留，(m,d)与双段拼接线性等价，abs(d)还抹去相对符号，不能称纯时间顺序机制。Grok原判NEEDS_REVISION，最终Q/K细化为主Agent审后设计，未声称外审改判；保护文件变动告警与来源未归因限制见[处置](reassessment_v33_20261029/review/DISPOSITION.md)。默认运行选择仍为暂停与证据收束，这份方向记录不授予训练权限。

当前尚无已具论文主方法资格的新候选。FCA 的均值改善不能覆盖冻结个体风险失败；CGB、BCU、RCS 分别关闭其固定替换、重采样及共有对象假设的精确范围，不否定整个校准或架构家族。直接依据见下方对应结果报告。

SBN-R1已完成正式核心intake与独立复算：仅真实源数据重估BN相对原统计−0.2604pp、相对真实＋增强重估−0.2713pp，两主比较均值及逐seed门失败，前者另有2/18配对低于−3pp。Cmix−B0仅+0.0109pp，不能支持继续投入或把源增强解释为泛化问题的原因。关闭本固定两BN顺序population重估实例，不否定整个BN校准家族，不新增Claim或R2；[直接证据与处置](sbn_r1/closeout_20261029/CLOSEOUT_REPORT.md)。研究问题仍来自实际BN路径与源数据组成，[原设计依据](reassessment_20261029_post_rcs/research_brief.md)保留，不以RCS阴性证明。运行与投入授权仅看State，以下启动及设计段均为历史快照。

## 历史研究判断与来源（保留各时点记录）

更新：2026-10-29，SBN-R1 packfix1三节点/37任务、36科学BN状态/54评分完整通过，兼容回传与标准intake完成，独立复算一致。冻结决策SBN_R1_FIXED_GATE_NOT_MET_STOP；0梯度训练，本次恢复0模型推理，原合同/封存清单/6h起点及旧成本保留。State暂停、活动Run/operation为空，BCU-R2/SBN-R2不启动。[正式收尾](sbn_r1/closeout_20261029/CLOSEOUT_REPORT.md)。



更新：2026-10-29，SBN-R1 packfix1真实源资格、全18原B0重放和成本门均PASS，科学18组合任务已RUNNING；预计科学保守2564.98秒，0梯度训练，未读中间效果，无新Claim，BCU-R2/SBN-R2不启动。[启动与当前阶段](sbn_r1/STARTUP_REPORT.md)。

更新：2026-10-29，用户已批准SBN-R1及新增6h，packfix1正式启动。真实源数据GPU技术资格PASS，峰值1189MiB，18项原B0重放运行中；科学新统计未作效果读取，仍受完整重放与成本门约束。0梯度训练，实际宿主2BN源码更正已记录，原合同/旧结果/预算成本保留，BCU-R2/SBN-R2不启动。[实际启动及门控](sbn_r1/STARTUP_REPORT.md)。

更新：2026-10-29，RCS后新方向仅设计。暂定优先SBN-R1：固定原无对齐B权重，比较原BN统计、真实源数据重估与真实＋增强重估，区分统计刷新和数据组成。该问题由实际训练路径提出，不由RCS阴性证明；已有BN近邻，尚无新效用或原创机制证据。0新梯度训练但需要新源前向/评分，资产、执行预算及专项资格未完成，本轮无实验。共有对象门控与BCU-R2仍关闭。[候选比较及条件方案](reassessment_20261029_post_rcs/research_brief.md)。

更新：2026-10-29，RCS-R1已按2小时授权完成零训练预测分析。90份来源闭合、180会话分数及独立复算通过，18会话中0个满足三配方相对B/D在两seed共12差值均负的原判据。存在局部重复损失，但没有本轮定义的共有受损对象；停止以此为依据启动新方法，不把阴性解释为无风险或随机性已证实，无新Claim。BCU-R2不启动，原活动状态及旧成本保留。[RCS结果与处置](rcs_r1/RESULTS_REPORT.md)。

更新：2026-10-29，BCU后研究重评（仅设计）。当前没有足够依据继续相近训练配方或将DBConformer指定为主创新。优先证据收束；唯一展开的低成本下一轮为RCS-R1：利用已有五臂预测检查受损对象跨seed/配方的会话层一致性。共同模式缺失就停止该方法靶点投入，存在也不等于无标签可识别或因果机制成立。0新训练/模型前向，规划2小时未授权，尚未运行新分析；State/旧判/预算保留。[新方案](reassessment_20261029_post_bcu/research_brief.md)。

更新：2026-10-29，BCU-R1 packfix1正式核心intake、独立全量/核心复算及决策收尾完成。2 TECH+36 SCI、54旧参照均已核验，未重训；原合同/封存清单/全部结果保留。P/E0/C0平均ACC为60.7313/60.3299/60.4275%，P−E0 +0.4015pp、P−C0 +0.3038pp，均低于0.5pp且逐配对风险门失败，四项比较均不通过。决策BCU_R1_FIXED_SCREEN_GATE_NOT_MET_STOP，关闭固定源cal32 bootstrap bank32配方；不外推整个校准家族无效，无新Claim，BCU-R2不启动。State暂停、无活动Run或operation。原48h起点及全部成本不重置。[正式收尾与限定](bcu_r1/closeout_20261029/CLOSEOUT_REPORT.md)。

以下启动、设计与旧研究段保留各自当时状态，以本条正式收尾为本轮最新结论。

更新：2026-10-29。用户已要求启动BCU-R1，48h预算与01:07+08起点已绑定。实际packfix1 Run已在lab-codex接受，两项source-only GPU TECH运行，SCI0/36待TECH与实测成本门。旧54参照和FCA/CGB全部结果、成本及停止边界保留；没有新Claim，不启动任何R2。[实际启动与验收](bcu_r1/STARTUP_REPORT_PACKFIX1.md)。

以下保留先前研究判断及当时的状态；原BCU条件设计的“未授权”现由本轮用户启动指令及48h预算绑定取代。

更新：2026-10-28 22:22。CGB-R1已完成3TECH+27SCI的正式核心intake及独立复算，决策CGB_R1_FIXED_REFERENCE_INSUFFICIENT_STOP；State暂停、活动Run/operation均空，CGB-R2与FCA-R2均不启动。[CGB结果与处置](cgb_r1/RESULTS_REPORT.md)。FCA原FAIL_STOP、原合同、54结果及完整成本保留。

## 拟议主张

2026-10-28 FCA后强对照已完成：固定OAS/源参考切空间/StandardScaler/C1多类LR在B/D/E的ACC为33.746/35.352/41.276%，相对同臂原FCA平均−23.014/−23.199/−19.054pp；全部54个subject/reference-seed配对低于−3pp，冻结三臂保留门失败。由此关闭本固定低成本替换配方，不扫描频带/对齐/C或选最好臂救援；完整管线差距不证明纯架构贡献，也不否定所有几何方法。原FCA校准个体风险失败仍成立。当前无新结构主方法或正式Claim，继续暂停近邻神经模块/选模搜索并收束已有边界。[直接分析及处置](cgb_r1/RESULTS_REPORT.md)，证据AI4S-DBCONFORMER-dbconformer-cgb-r1；旧设计草案仅保留当时决策来源。

当前没有已具备主论文资格的新方法候选。FCA-R1固定完整协方差校准配方已因风险门失败关闭，FCA-R2不启动。固定辅助监督BAS、固定空间编码器删减BNS及固定D6选模实例SVS均已关闭；BAS-R2/BNS-R2/SVS-R2均不启动。建议暂停DBConformer的新模块及近邻选模配方搜索，保留完整2/2宿主baseline及已具来源的鲁棒性辅助分析和限定负结果。已有配置失败不证明整个模型家族没有可行创新。[SVS方案](reassessment_20261023_post_bns/research_brief.md)已完成18条六源训练轨迹，未满足进入完整八源B8比较的冻结前提。

2026-10-24再次重评保持上述主线判断。[FCA-R1方案](reassessment_20261024_post_svs/research_brief.md)在用户接受有限无标签目标会话校准后进入独立任务：完整2/2宿主比较无对齐、对角尺度校准、完整协方差对齐，检验成熟强baseline的价值，不作为结构创新。EA已有明确先例，本地尚无该固定cal32/5%配方效用证据；它不同于SVS选模、CMN缺通道条件归一化及原生EA协议。原方案的DESIGN_ONLY现由本次明确授权取代；旧关闭边界保持，目标访问仅限冻结合同规定的checkpoint选定后每会话最早32项无标签校准，剩余256项仅用于评分。FCA-R1结果现已完成正式验收，具体限定与关闭后果见下文；未释放Claim。

**CGB后的条件性设计（2026-10-28）**：下一项可选问题为BCU-R1源cal32重采样校准训练：部署端仍固定E，比较P与旧E及CovMix-cal32同宿主控制，不增加分支/辅助loss/校准强度扫描。旧SGR的平衡/GroupDRO和SCR同源拼接已失败，不能视为空白。拟36新SCI+最多2source-only TECH、复用旧54参照，48h仅为有条件总预算情景，尚无执行授权；CovMix来源配方、复用、真实TECH/成本未闭合，默认继续收束。外审READY_WITH_LIMITS只允许设计留档；任何新效用或机制主张均待检验。[设计与停止条件](reassessment_20261028_post_cgb/research_brief.md)。

## 关键缺口

BNS静态参数减少42.04%、限定MAC减少14.28%，但个体风险失败，不能作为获准简化方案；实际推理延迟未受控测量，不补测救援。平均保留不是统计非劣效；九名被试反复暴露，新seed不恢复独立评价。原论文已有整分支和深度消融，当前研究没有建立独立方法创新或正式论文Claim。SVS完成真实产物与来源核验，但其固定D6选择配方失败；同轨迹差异不能单独分离验证域组成/密度的作用，也未执行完整八源B8科学比较。新选模结果不会追改旧BAS/BNS失败，正式独立评价范围仍未建立。

## 当前认识

**完整协方差校准有平均收益，但未保住冻结个体风险。** FCA-R1 为已暴露九被试×seeds3/4 的每会话32项无标签校准筛查，54 SCI、3原TECH闭合。B/D/E平均ACC为56.760%/58.550%/60.330%；E-B +3.570pp、E-D +1.780pp，两seed均值均为正，但最差配对 -4.492pp/-8.203pp，低于-3pp分别3/18、5/18。固定cal32/5%完整协方差配方按原规则 FAIL_STOP，FCA-R2不启动，不以均值收益救援风险失败。E-D seed3仅+0.152pp、seed4 +3.407pp，增益稳定性也未建立；本轮不作独立确认或结构创新主张，不外推校准家族无效。证据 `AI4S-DBCONFORMER-dbconformer-fca-r1`；[正式分析与收尾](fca_r1_repair5_packfix80/intake_recovery_v1/CLOSEOUT_REPORT.md)。核心回传及分析接口错误已按精确原身份修复；原包/合同/结果不变、零重训，独立全量/核心复算一致。累计80小时上限未追加，延后回拉与收尾的累计超限按原账本保留。

**固定的未训练源被试验证选模没有改善目标泛化。** SVS-R1 repair2的18项SCI完整完成，1项原TECH无训练导入，54份预测独立NumPy重算与冻结分析一致。R6/D6/F6分别56.5490%/53.2215%/56.0089%；D6−R6 −3.3275pp、D6−F6 −2.7874pp，两个seed均为负，最差配对−13.7153pp/−12.8472pp，低于−3pp分别7/18和6/18，六门均失败。关闭本次两验证被试/抽样/六源训练配方，SVS-R2前提未满足；不换被试、加seed或调epoch窗口救援，不外推全部域泛化/选模无效。证据`AI4S-DBCONFORMER-dbconformer-svs-r1-repair2`，来源[结果报告](svs_r1_repair2/RESULTS_REPORT.md)。该Run实际执行约64分钟，训练在预算内完成；延后回拉收尾按原计时到decision累计14.444h，超过14h约0.444h，保留预算偏差及旧成本。

**删除空间Transformer没有保住预先要求的个体风险。** BNS-R1两臂9被试×seeds3/4，B0 56.7805%、P 57.0698%，P−B0 +0.2894pp；seed3 +0.9259pp、seed4 −0.3472pp，均符合新前瞻保留门。但3/18配对越过−3pp风险线，最差subject7/seed3 −4.5139pp；subject4两seed均越线。参数/MAC门通过不能救援风险失败。Evidence AI4S-DBCONFORMER-dbconformer-bns-r1，完整38项封存分析和独立36份数组重算一致；直接来源[结果报告](bns_r1/RESULTS_REPORT.md)。关闭固定2/0包，BNS-R2前提未满足。不外推空间信息无用或单一attention无用；P保留双前端/位置/池化/融合，C(0/2)没有执行。

**辅助监督正线索未复现。** BGC的P−B0 +1.3696pp但P−A −0.0965pp、必要控制失败；A−B0 seed0 +1.4660pp促成BAS。BAS两新seed平均−1.8036pp、两seed均负、最差−8.8542pp，四门失败，关闭固定A与分配续接。来源AI4S-DBCONFORMER-dbconformer-bgc-r1-repair2和AI4S-DBCONFORMER-dbconformer-bas-r1；[BGC报告](bgc_r1_repair2/RESULTS_REPORT.md)、[BAS报告](bas_r1/RESULTS_REPORT.md)。不调λ/加seed救援，不否定全部辅助监督。

**额外能量/关系实例与缺通道辅助证据各有明确范围。** FSC、BSP、SRT的P−B0分别−3.1829、−0.1736、−2.1412pp，各自必要门失败；其精确边界见对应decision及[历史入口](HISTORY_BOUNDARIES.md)、[v3.2证据表](discover_next_v32_20261020/research_brief.md)。BDA的U0缺通道适配在两backbone seeds获支持，但NNC中U0−RIDGE约−4.9738pp，已撤下独立创新，保留RIDGE强对照及限定鲁棒性来源，见[已有处置](architecture_next_20261005/CLOSEOUT.md)。这些历史不能移作clean改进证据，INVALID不按科学负结果聚合。BNS使用对称独立数据随机流的新训练B0，不能跨profile拿BAS/BGC绝对均值作配对比较。


### 2026-10-27 FCA-R1 repair5 部署续接

已登记累计71小时、SCI3小时/Transaction4小时的repair5。本地53 SCI+3 TECH来源、真实CPU入口、实际启动接口及最终包通过；仅授权补B_s6_seed3。上传时SSH在密钥交换前被远端关闭，未收到上传回执、未发出launch；真实GPU和SCI尚未由本次部署启动。原起点与全部历史成本保留，恢复连接后须先核对同一Run并重过实时预算门。无新增科学结论，FCA-R2不启动。[部署记录](fca_r1_repair5/DEPLOYMENT_STATUS.md)。



