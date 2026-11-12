# SST-DPN 当前研究总览与接续

## SD-02 closurefix5｜已完成并关闭固定配方

证据 `AI4S-SSTDPN-sd02-three-arm-v0.1-closurefix5`。固定三臂完成 27/27 个科学节点，冻结判定为 **NO_SIGNAL**。四阶 K 对原生 B 和匹配二阶 S 分别为 −25.35 pp 和 −8.29 pp，两项对比的均值、seed 与逐人风险门均未通过。结论限于已曝光开发被试 S02/S05/S08、seed 2/3/4 与本次固定 48 坐标残差配方，正式 Claim 和机制均未建立。该具体实例已关闭，保留原停止条件和曝光边界。未来有不同的可检验结构预测时，按原边界核对新设计及授权。 [冻结结果](sd02-three-arm-v0.1/closeout_20261105/RESULT_SUMMARY.md) · [决策记录](sd02-three-arm-v0.1-closurefix5_decision.yaml)

以下两节保留 2026-11-03 的工程与设计快照。运行状态见 State。

## 2026-11-03：SD-02 模型与判定工程实现（历史，当时未启动实验）

用户进一步授权三臂模型实现、判定接线和必要工程验收，明确不启动实验。代码位于 `research/sd02-three-arm-v0.1/`，共享控制器已增加独立SD02识别/结果绑定/分类分支；[工程验收报告](../../../_work/sstdpn_sd02_assessment_20261103/implementation/REPORT.md)区分已覆盖通路与未验收范围。仅运行CPU合成检查，无科研数据加载或科学拟合。原生初态/BN/eval输出经参考实现核对；按本设计使用functional ISP renorm，训练梯度语义不能声称与reference的`.data`原地投影逐步一致。草稿预测产物显式标记ENGINEERING_ONLY，当前无新执行授权时合同门保持关闭。科学Run、GPU资格、调度/回传和完整生产事务均未验收，Program继续暂停，State/Evidence Index和旧实验判定不变。

## 2026-11-03：SD-02 候选投入判断（设计记录）

同日后续，用户要求具体化三臂比较：详见[三臂设计 brief](../../../_work/sstdpn_sd02_assessment_20261103/research_brief.md)与唯一未冻结的[数值配置](../../../_work/sstdpn_sd02_assessment_20261103/DESIGN_CONFIG.json)。拟定原生完整DPL B／完整48维协方差残差 S／四阶累积量残差 K；S/K同窗、同MLP、同参数与零初始化残差，各新增144240参数。它是原card-v1的明确简化版本，无attention或低秩投影。开发矩阵S02/S05/S08×seeds2/3/4，共27次新科学训练；固定100+30端点配方不等同原生validation-best profile。K−B与K−S各自均值≥1pp、每seed均值>0、每人均值≥−3pp才支持考虑后续投入；不是正式统计确认。新增定义通过[独立增量反驳与处置](../../../_work/sstdpn_sd02_assessment_20261103/review/three_arm_delta/REVIEW_DISPOSITION.md)，模型/判定路径尚未实现，数据载荷与成本未验收，8h执行/12h全轮仅是未批建议上限。当前仍只设计，不安排派发，不改State或Evidence Index。

用户指定 `IF-20261029-02 / IF-20261029-SD-02 / card-v1`，沿已激活的 `sstdpn-transaction-v3.3` 审阅。[本轮 brief](../../../_work/sstdpn_sd02_assessment_20261103/research_brief.md)记录源码/原文对应、相关历史证据、有界一手来源核对及[独立 Grok 反驳和处置](../../../_work/sstdpn_sd02_assessment_20261103/review/REVIEW_DISPOSITION.md)。**值得继续收敛有限判别方案，尚不支持恢复自动运行或作为论文主方法投入。** 这是设计判断更新，无新增经验性证据，不登记新研究或运行对象。

本轮依赖的源码事实已定向核对：wrapper 为 F2=48、池化窗50/100/200；`model.py` 的 `x_chan` 在 Mixer 前保留逐时激活，Mixer 按三组坐标作局部方差并展平。前端 SSA、BN、ELU 使其非线性，不能从方差池化推断整个模型没有高阶信息。SD-02 的统计应在 pre-Mixer 上读，不能从池化输出恢复；参考源码身份与 Program 登记一致，本轮不宣称 wrapper 全文件或全模型复现已验收。

设计后果：优先区分完整二阶与显式四阶在同接口/同外壳/同选择成本下的效用，保留原生完整宿主主比较。累积量 K 是四阶矩 M 与协方差 C 的确定性重参数化；对角峰度、投影混合、有限窗误差、异常峰及融合容量均是竞争解释。初筛不能单独证明双支互补、减 Gaussian 配对项必要或生理机制。只有有价值的净效用证据才支持继续为这些归因付费；若匹配完整二阶复现增量，停止当前高阶特异故事。具体实现、数据角色/曝光、阈值、矩阵、成本与新执行授权仍待明确，当前不安排派发。

原 TEO/FRR 只约束各自冻结探针/读出包，不否定本案联合训练，也不为它背书。Program 保持 `PAUSED_FOR_HUMAN`；State、Evidence Index、旧 FRR/FTA 判定、合同及预算未改。下方“当前没有下一项对照”等均保留其历史日期语义，运行仍以 State 为准。

## 基模来源与认识边界

同一论文的加工材料不作独立证据计数。路径从本文件位置解析：

| 材料 | 用途 |
|---|---|
| [SST-DPN-paper-card.md](../../../../refs/paper-cards/sst-dpn/SST-DPN-paper-card.md) | 贡献与证据边界 |
| [nature-reader/paper.md](../../../../refs/paper-cards/sst-dpn/nature-reader/paper.md) | 已有原文读取材料 |

### 基模设计理解

作者报告：ASSF以空间—频谱通道加权，MVP用多尺度方差池化形成时间汇聚，DPL通过独立/集体原型及类间分离、类内紧致目标约束特征（Paper Card §§6–8）。阅读解释：方差是频谱功率的代理，不等于直接测得神经节律；几何损失的分工是方法假设，需消融与匹配对照归因。本地源定位于外部参考实现 `refs/models/SST-DPN-main/SST-DPN-main`，proposed 适配入口为 `src/models/proposed/fcsm_sstdpn.py`；本次未逐层核验参考实现版本与论文代码一致性，故实现对应仍有限定。作者报告在其公开离线协议成立，不构成本地复现或部署证据。当前未决是各模块独立贡献及本地适用范围；按来源核实实现身份后再更新。

下文是可修正综合，区分作者报告、阅读推断、实现和本地结果，并保留条件、反例及改变判断的证据。历史状态只作当时记录，当前运行状态以 STATE.yaml 为准；暂停和冻结边界不由知识接入改变。

更新：2026-10-25，用户已明确决定暂停 Program。共享控制器登记 `PAUSED_FOR_HUMAN / paused=true`，无活动 Run、operation 或待续接任务。**保留全部实验资产，停止自动推进与新实验，当前不安排下一项对照。**

## 拟议主张

尚无确立的 SST-DPN 论文主创新。保留原生基线、FTA-R1 限定正筛查及各轮精确负结果；不将暂停解释为模型普遍无效或所有研究空间已穷尽。

## 关键缺口

当前缺少值得继续投入的具体新假设与可区分解释的对照。重启须明确相对历史关闭路线的实质差异、依据、合法数据与曝光、正负结果的设计后果，并取得具体新执行授权；不依赖其他模型输赢。HVR 提案继续撤下，旧额度不授权恢复。

## 当前认识与资产保留

[暂停交接报告](pause_20261025/REPORT.md)集中整理主要结论、早期与近期负结果边界、诊断/工程证据区别及重启条件；[资产保留导航](pause_20261025/ASSET_RETENTION_INDEX.json)保留本地入口和历史归档定位。原合同、checkpoint、预测、intake、日志、外审、起点和累计成本保留，不删除或移动资产。外盘载荷未在本次重新验真，按原恢复清单核对后使用。

---

## 2026-10-25 自身价值重评快照（历史；暂停建议已获用户确认）

更新：2026-10-25。根据用户明确范围，撤下 HVR 横向比较提案；其他模型 Program 独立推进。仅依据 SST-DPN 自身历史与实际结构，**保留 Program 和原生基线资产，暂停缺乏新依据的局部创新实验**。当前没有值得立即启动的下一轮方法，不作整个模型研究空间已穷尽的结论。

[完整重评及证据链](HOST_REASSESSMENT_20261025.md)，记录 `SSTDPN-HOST-REASSESSMENT-20261025`。结构复核、训练目标调整、风险分配、FTA 稳定性复核及 FRR 分别约束各自配置；不能合并为单一机制否定。FTA 正均值保留，但不救援失败判据。模型有未解问题，尚无证据选中的可行动瓶颈；“尚未尝试”不足以支持继续训练。

下一项对照：目前不安排。重启须有与已关闭路线实质不同、与模型结构相关且有新增依据的可证伪假设，并明确关键对照如何改变设计或停止决定；不依赖其他模型的输赢。State 继续 COMPLETE_MAX_ROUNDS/paused，无活动 Run/operation，无新增执行授权。

---

## 2026-10-24 HVR 提案快照（历史；已按用户范围撤下，不再作为下一步）

更新：2026-10-24；沿sstdpn-transaction-v3.2完成宿主去留重评。**暂停SST-DPN主创新载体上的局部搜索，保留完整DPL原生B参考；尚不能断言它已被其他完整方法淘汰。** [HVR-R1方案](hvr-r01-v0.1/research_brief.md)，设计证据SSTDPN-HVR-R1-DESIGN-20261024。State继续COMPLETE_MAX_ROUNDS/paused，无活动Run/operation，新实验未授权。

## 拟议主张（当前）

尚无成立的SST-DPN论文主方法。不再因Program存在而连续增加模块。HVR仅检验完整管线的相对宿主价值，用于母项目投入选择；不主张新算法、ISP普遍必要、编码器失效或正式benchmark优势。

## 关键缺口（当前）

FRR/FTA/IPR/SGR等有效负结果约束了各自配置，未直接比较SST与合法同任务替代宿主。先核对开发资产兼容性；若确需解决宿主选择，再用固定DBConformer参考作唯一挑战者。条件性矩阵S02–S09×seeds2/3/4，复用24格SST原生B，最多新增24个D科学训练+1个source-only技术训练。7源成员不得混同旧UEP8源；比较只解释完整管线。DB当前另有活动fca_r1，不能插队或转移授权。

## 当前认识与设计后果

**多个作用位置都未形成可持续局部收益。** FRR R−B −5.0347pp且三门失败；FTA-R2正均值未过seed4门；IPR阶段释放、SGR真实组风险、ASG/SFP复核及EFR各有精确负边界。直接证据见HVR brief逐项回链，原结论不改写、不合并统计。投入判断改为暂停局部搜索；尤其IPR已有全程CE-only Z，不把它包装成新实验。

**宿主淘汰仍需相对证据。** FRR固定ridge失败不说明所有读出或表征无效；B相对简化臂的描述性优势也不证明它是最佳宿主。HVR D−S达到预设均值/seed/被试三门才建议优先转向D；反向全部通过只恢复S候选宿主资格；其余维持暂停，不再自动换第三模型。无论哪一支都不复活已关闭配方或自动进入新创新轮。

**保留成本和授权边界。** 旧FRR12h仅用于旧Run收尾；HVR提出新8h执行/12h全轮上限，尚无D适用画像，技术校准与保守成本准入是实施前缺口，不能视为已准入。母项目协调与DB既有Program边界见方案。本轮只完成研究设计、外审及记录，没有模型运行、上传、创建campaign或改变State。

---

## FRR收尾时认识快照（历史；由上文更新）

更新：2026-10-24；活动链`sstdpn-transaction-v3.2`。FRR-R1 repair1b已完整回拉验真并按原三门登记 **NO_SIGNAL**，Program COMPLETE_MAX_ROUNDS/paused，无活动Run或operation。[完整报告](frr-r01-v0.1-repair1b/INTAKE_ANALYSIS_20261024.md)，证据`AI4S-SSTDPN-frr-r01-v0.1-repair1b`。

## 拟议主张与关键缺口（当前）

尚无已确立的SST-DPN论文主方法。FRR固定表征源域ridge替换的投入检验已回答为不支持当前配置；未获支持的FTA配方升级也继续停止。历史探索尚未建立一种稳定优于当前宿主、具有清楚机制控制及合法独立验证的主方法。当前不以继续局部调整代替这个缺口，不新增拟合或实验。

## 当前认识与后续处置

**固定ridge读出未改善当前冻结表征。** `AI4S-SSTDPN-frr-r01-v0.1-repair1b`：B=59.1291%、R=54.0943%，R−B=−5.0347pp；三seed均值全负、8人均值全负、7人低于−3pp，三门均失败。由开放的“更换完整读出包是否值得投入”更新为关闭此固定配置；暂停缺乏新依据的宿主局部改造，不调正则/标准化/截距/seed救援，不把负结果外推为所有读出无效或特征不存在信息。

**效用与机制仍分开。** ridge包与ISP的损失、归一化及截距共同不同，当前结果不定位单一瓶颈。FTA-R2 repair2的seed4门失败保持，FTA-R1限定正筛查与IPR/SGR/ASG/SFP历史精确边界保持；旧工程失败不算科学零效应。S02–S09/seeds2–4均已曝光，仍无正式论文Claim。

**处置是停止此干预并整理证据。** 原生B仍是当前比较宿主；下一项对照未授权、不运行。未来新研究须提供会改变设计选择的新依据和精确新问题，不能由本轮负结果自动派生新读出或完整训练。累计预算按原2026-10-24T04:23:15Z计时，用户仅追加收尾到12h；原日志/失败成本保留，剩余额度不授予新Run。

---

## FRR执行与设计时快照（历史；由上文更新）

运行更新（2026-10-24）：用户明确授权工程修复补跑后，独立修订 `frr-r01-v0.1-repair1b` 已在lab10启动，technical PASS、science RUNNING。原始与repair1两次零任务启动失败均保留；修订补齐通用capacity任务资源元数据，原矩阵/判据和2h执行/6h全轮上限及12:23:15北京时间起点不变。[当前启动报告](frr-r01-v0.1-repair1b/LAUNCH_REPORT.md)。尚无科学结论，不回写FTA负边界。

运行补记（2026-10-24）：用户已授权FRR-R1在lab10按2h/6h启动，唯一Run在scheduler装载capacity前失败，0项拟合/预测；Program暂停，旧失败/成本保留，非科学负结果。[启动报告](frr-r01-v0.1/LAUNCH_REPORT.md)和[工程修复候选](frr-r01-v0.1/execution/repair_candidate/REPAIR_CANDIDATE_REPORT_v2.md)已就绪，零自动修复规则下尚未重投。下文设计时“未授权”保留当时语义，当前运行以State及本补记引用为准。

更新：2026-10-24；活动链 `sstdpn-transaction-v3.2`。FTA-R2 repair2已完整回拉验真并按冻结门登记 **NO_SIGNAL**。State为COMPLETE_MAX_ROUNDS、paused=true，无活动Run/operation。下一步为 [FRR-R1设计](frr-r01-v0.1/research_brief.md)，尚未授权执行；下方2026-10-23内容作为当时认识保留，不能覆盖本次结论。

## 拟议主张（当前）

尚无已确立的SST-DPN论文主方法。停止将FTA固定配方作为待升级强宿主，保留R1限定正筛查。下一项待检验问题收敛为：固定原生编码器及BN后，一个事前固定、只用源域拟合的ridge读出，是否相对同模型ISP产生跨当前开发被试和训练seed的稳定收益。它是读出研究的投入决策，不是原创方法或已成立的ISP瓶颈主张。

## 关键缺口（当前）

历史干预改变了结构、训练目标或整个模型的轨迹平均，尚未直接回答当前24个有效phase2原生端点的固定表征读出可替换性。一次24科学ridge拟合、零编码器重训可利用现有有效模型检验该问题；若失败，暂停当前宿主缺乏新依据的局部改造，整理基线和负结果。若成功，也只支持另立读出损失/约束/截距控制与合法验证方案。S02–S09和seed2–4已曝光，不能当独立验证；S01和BNCI2014004角色未核定的结果不进入选型。

## 当前认识（2026-10-24修订）

**FTA正均值未转化为预设的跨seed稳定支持。** `AI4S-SSTDPN-fta-r02-v0.1-repair2`，[完整分析](fta-r02-v0.1-repair2/INTAKE_ANALYSIS_20261024.md)：A−B/A−N为+1.3310/+1.2587pp，但seed4为−0.1519/−0.4557pp；被试保护门通过仍不能补偿seed门失败。R1的+1.6385/+1.3997pp保留其筛查范围，两批不合并救援。新设计不改平均窗、权重、seed或门槛，也不启动原先以R2通过为前提的跨数据验证。旧两个INVALID属于工程历史，原成本14.5626/16h保留。

**现有证据不能定位为ISP或编码器单一瓶颈。** IPR固定阶段释放、SGR真实源分组CE与ASG/SFP扩展复核各有精确负边界（直接来源见下方既有认识及本轮brief），没有检验冻结同一个表征后重拟合最终读出的效果。FTA里A与E接近也不能证明几何问题。因此FRR只改完整读出包、保持B表征与BN，R胜不解释为某个原型约束被证伪，R败也不解释为所有读出无效。

**历史ridge诊断不能替代本轮跨被试配对比较。** `AI4S-SSTDPN-teo-r01-v0.1-e1`，[报告](teo-r01-v0.1-e1/REPORT.md)：增加有向能量统计未形成稳定源内探针增量，原快照已参与源域训练/选择且没有目标subject评价。FRR不增加时间统计，也不调TEO配方；其问题是固定phase2原生表征的B/R目标域比较。仍属于已曝光开发证据，成功与失败都只约束当前固定包。

**本轮选择可替换性检验而暂缓新完整训练。** [FRR-R1](frr-r01-v0.1/research_brief.md)仅复用repair2全部24个原生B端点，已核对对应磁盘哈希，尚未运行模型。拟议24科学+1技术ridge拟合、48科学视图、0新编码器训练，2h执行/6h全轮；预算与目的地待新的执行指令。完整性、固定正则、三seed/八人门和失败后的投入停止已预先写入。普通探索不建立正式Claim Ledger，当前State与旧冻结合同不变。

---

## 2026-10-23认识快照（历史；已由上文更新）

更新：2026-10-23；活动链 `sstdpn-transaction-v3.2`。FTA-R1已完整回拉验真并完成结果复核，结论SCREEN_POSITIVE / FIXED_TAIL_AVERAGING_DEVELOPMENT_SUPPORT；本轮COMPLETE_MAX_ROUNDS/paused，无活动Run/operation。SGR/IPR原负结论保留。轮次事实以原证据与决策为准。

## 拟议主张

FTA近期研究目标是确认固定尾段平均能否成为稳定的单模型强宿主。已准备 [FTA-R2前瞻方案](fta-r02-v0.1/research_brief.md)：S02–S09 × seed2/3/4，24新训练/96视图，保持R1配方，仅新批次判定；它是已曝光开发范围的训练随机性复核，不解决独立人群验证，也不声称主创新。设计已完成，尚未授权执行。

尚无足以确立论文主方法的候选。SGR 的固定真实源分组 CE 风险适配未提供超出 pooled 宿主和匹配伪分组的开发效用，不能作为主方法推进。Group DRO 是已知方法；本轮只约束该具体适配，不否定所有鲁棒训练。

## 关键缺口

已知固定尾段平均在当前SST-DPN开发条件下可改善宿主：A−B +1.6385pp、A−N +1.3997pp，六门全过，见[FTA完整分析](fta-r01-v0.1/analysis_20261023/REPORT.md)。因此后续主方法不能只与较弱原生B比较；FTA应保留为待确认强宿主候选。尚缺合法独立确认及论文主贡献，不把已曝光S02–S09/seed0/1当最终验证，不自动读取S01。本轮已停止，无新候选、窗口、seed或预算授权；E/N仅描述性，不成为自动后继。

## 当前认识

**进一步开发先检验固定配方能否稳定成立。** 本次用户要求继续开发后，将R1“合法独立确认”缺口拆清：seed2–4在ASG/SFP历史中已曝光，只能用于FTA配方的随机性复核；BNCI2014004有历史评价，但没有已核定的FTA开发/最终成员范围。选择一次24-fit有限复核，因为历史正筛查衰减会改变强宿主投入决策，成本可按R1实测估计。R2保持A/B/N/E、固定窗口和风险门，仅seed2/3/4判定，旧结果不救援；通过才设计合法跨数据验证，失败停止配方升级。R1的正结果、停止规则和旧预算保持不变。这不是由旧Run自动补seed，不授予下一Run权限。

**固定尾段平均获得限定开发支持，尚未确立新主方法。** 16条完整100+30轨迹/64个同源视图，固定phase2 epoch21–30参数平均后源域BN校准，A−B +1.6385pp（seed0/1 +1.6059/+1.6710），A−N +1.3997pp（+0.9549/+1.8446），六门全过；S03/S09仍负向，最差被试均值分别−1.3021/−1.6493pp，未越过−3pp保护线。N−B +0.2387pp，E−N +1.6602pp，A−E −0.2604pp仅描述性；不能推出平坦性机制或自动选择E。证据 `AI4S-SSTDPN-fta-r01-v0.1`，[报告](fta-r01-v0.1/analysis_20261023/REPORT.md)，独立64数组重算匹配，Grok结果复核ACCEPT_WITH_LIMITS及真实trace保留。S02–S09/seed0/1已曝光，无S01最终评价或Claim。判断由“是否应先强化宿主未知”更新为“应保留该固定强宿主候选，并先设计合法独立确认/强基线边界”；不再以原生B的弱比较包装主方法，也不直接扩大窗口/seed搜索。平均思想本身不是本项目新颖性。

**当前真实源分组风险 CE 没有净效用。** SGR 八人两 seed 同轮 B/G/P，G−B −2.0508pp、G−P −2.1159pp，两比较的六门全部失败；P−B +0.0651pp 仅描述性。S05 的 G−B +5.1215pp 不能救援 S02/S06/S08/S09 超过3pp的退化。证据 `AI4S-SSTDPN-sgr-r01-v0.1`，见[完整报告](sgr-r01-v0.1/analysis_20261023/REPORT.md)。因此关闭 η=.01、固定100+30、当前分组/估计器/宿主的适配，不调η或删被试救援；不证明来源身份普遍有害，也未建立机制。IPR与SGR干预不同，不能把两个负结果合并为单一机制效应。

**不支持固定阶段释放，不等于ICP普遍必要。** IPR八人两seed、fixed100+30开发实验，R−B −1.2478pp、两seed均负且S05越过−3pp；R−Z平均正差仍未过被试保护门。证据 `AI4S-SSTDPN-ipr-r01-v0.1`，见 [完整报告](ipr-r01-v0.1/analysis_20261022/REPORT.md)。原因未知，B−Z仅描述性。因此当前保持完整DPL，关闭改切换时机/调权重救援；拟议新问题改CE风险分配，不从该负结果推导原型机制。

**梯度/几何诊断不能替代联合训练收益。** PCG-r04-e1仅历史phase1快照的一步反事实，未建立当前PL使CE下降翻转；DRPG历史支持性几何诊断带WARN和selection-used边界。来源 `AI4S-SSTDPN-pcg-r04-v0.1-e1` [报告](pcg-r04-v0.1-e1/REPORT.md)、`SSTDPN-HIST-03` [边界](HISTORY_BOUNDARIES.md)。不将其变成冲突消除或共享方向/半径child的依据；这使下一主问题转向可直接评价的训练风险目标。

**来源分组ICP失败，未覆盖来源分组CE。** `AI4S-SSTDPN-sdc-r01-v0.1-repair2` [分析](sdc-r01-v0.1-repair2/ANALYSIS_REPORT.md)在精确范围内NO_SIGNAL，不排除所有使用来源身份的方法，也不支持来源身份本身有用。SGR保留单ICP/类，来源身份只进入CE权重，同时用类别/分区/组规模匹配的伪组控制；这是与SDC的实质区别。

**小范围正筛查和弱控制优势不足以确立主方法。** ASG有限筛查PROMISING_INCOMPLETE，八人复核NO_SIGNAL；SFP扩展复核不支持；EFR精确路线NO_SIGNAL。证据 `AI4S-SSTDPN-asg-stability-r01-v0.1` [报告](asg-stability-r01-v0.1/analysis_20261020/REPORT.md)、`AI4S-SSTDPN-sfp-stability-r01-v0.1-repair1`（Evidence Index原记录）、`AI4S-SSTDPN-efr-r01-v0.1` [报告](efr-r01-v0.1/analysis_20261018/REPORT.md)。不归因为单一扩样因素、不复活空间分解。下一轮从八人两seed开始，主比较不能由机制控制救援。

以上都是允许选型的开发/限定诊断认识，不合并为跨轮效应量；工程INVALID不算科学失败，S01与最终评价不进入本设计。本轮训练已结束；后继实验须获得新授权，不继承本轮预算。

---

## 历史接续原文（保留，以下不是当前运行状态）

# SST-DPN 当前接续：SFP-v0.1 当前准备

2026-10-09：最新新工作链 sstdpn-transaction-v3.1 已核验生效。SDC repair2完整18-fit/18-view为NO_SIGNAL；旧v3.0 campaign仍COMPLETE_MAX_ROUNDS/paused，无活动Run或operation。

新方向为SSA后的电极×共享时间滤波器轴因子化融合，四臂具体方案见 sfp-v0.1/research_brief.md 与唯一未冻结 DESIGN_CONFIG.json。真实源码为filter-major/electrode-minor，已修正初版错误并通过19项CPU合成检查。Grok固定快照只读裁决ACCEPT_WITH_LIMITS；尚无完整宿主/GPU/科学效果验收。

本次仅DISCOVER_NEXT/DESIGN_ONLY，科学fit和EEG预测均0。拟议24科学fit、4技术epoch及单轮12小时，未来判据采用与新执行scope仍未确认；不得继承旧SDC授权或余额。State/Evidence Index已登记研究准备，顶层记录D-204。此前历史接续原文保留如下。

---

# SST-DPN 当前接续

JMR repair1已完成：4/4技术检查、24/24科学训练，失败0；完整回拉/manifest核验/intake与冻结分析完成。RMS ACC59.5486%，相对Native+2.0255pp、Joint-0.1736pp、同分母centered RMS+0.0289pp；S02对Native-4.0799pp。三个主门均未通过，同分母支持门也未通过。

证据 AI4S-SSTDPN-jmr-r01-v0.1-repair1；NO_SIGNAL已登记，State为COMPLETE_MAX_ROUNDS。关闭精确RMS候选，不自动调epsilon/换seed/删被试/混合救援；未启动新实验。详见 jmr-r01-v0.1-repair1/ANALYSIS_REPORT.md。原JMR INVALID与原JTN NO_SIGNAL不变。

2026-09-28按用户要求完成机制重归纳：保留归一化接口的条件性结构线索，不等于BN缺陷已证实。新记录 bn-mechanism-synthesis-20260928/MECHANISM_SYNTHESIS.md，含GN48反例、预测冗余和最小source-only统计对照设计。仅既有证据分析，无新Run/训练或候选复活；原NO_SIGNAL不变。




