---
prompt_id: SSTDPN_MI_EEG_PROJECT
version: '3.3'
level: 3
parent: {prompt_id: MIEEG_AI4S_EXECUTION, version: '3.3'}
status: ACTIVE
---
# SST-DPN 项目适配 v3.3

## 阅读与研究认识入口

研究认识与唯一来源索引见 [研究总览](research/NEXT_RESEARCH.md)。该总览指向基模阅读材料与本地实现依据；本 L3 不重复列举论文路径。

首次采用基模理解时，重点核对 ASSF、方差池化、多尺度读出与双原型目标的实际作用及 reference／corrected wrapper 对应；不能把目标函数的设计动机当作本地机制证据，原生日程与 UEP profile 分别核对。 已有同版本核对可复用，缺口只限制依赖它的判断。

新判定映射要区分完整编码器训练、冻结表征轻量读出及原型／几何归因，按实际主张选单位与比较；新门不套用其他基模的训练日程或默认双 seed 优效规则，Program 暂停不由知识核对解除。 实际判定路径的对应、接线缺口与最小验证按 [L2 第2节](../../prompts/LEVEL2_EXECUTION_v3.3.md#2-用现有-brief-完成一页决策)执行，共享细则不在本 L3 重复。

仅当 `ai4s/PROMPT_INDEX.yaml` 为 SST-DPN 选定兼容的 v3.3 L1/L2/L3 活动链时，本适配才生效。运行状态和证据按索引进入 Program 的 State、Evidence Index 与冻结 Transaction；冻结工作沿其原绑定链、合同、预算和关闭边界处理。本文件只保存稳定项目约束，不复制活动 Run 状态或实验结论。

## 1. 宿主与方法身份

SST-DPN 研究关注空间—频谱特征、多尺度表征、原型决策与几何约束之间的关系。研究问题可以涉及结构、表示、学习目标、训练机制、完整方法适配或有证据依据的简化；不以调整损失权重代替清楚的结构问题，也不要求先证明宿主存在缺陷。

保留参考实现、项目 corrected wrapper、UEP processed-data、reference-loader 与 raw paper-style 辅助路径各自身份。当前注册 UEP profile 为 `mieeg-uep-v1.0` / `tp-sstdpn-native-v1`，不能套用 DBConformer/DSAINet 的 100 epoch profile。数据集、subject、类别/通道、窗口、数据日程、wrapper 或 checkpoint 阶段改变时，按对应合同核实是否形成新实现或评估身份。

主比较回答完整候选相对合同绑定宿主的效用；机制控制只解释其冻结问题。只有适当控制支持时才将整体差异归因于单个组件。原型初始化、原型与特征参数的优化配套及各阶段作用按完整候选配置、实际梯度路径和 checkpoint 身份解释。

## 2. 设计时核对

仅核对与本轮设计或结果解释有关的实现路径；以下是有针对性的科研事实，不形成新的固定审批门。

- 从实际输入、时间/空间变换、编码器、多尺度表示、ISP/ICP 与分类输出追踪干预作用路径；职责差异、条件收益和交互需由对应比较支持，名称或低相似度不是机制证据。
- 区分特征参数与原型参数的优化器和梯度路径。corrected wrapper 使用 AdamW 优化特征参数、独立 Adam 优化 ISP/ICP；核对所选合同和源码是否仍如此，不从其他历史 run 推定当前配置。
- 按数据集绑定输入、预处理、类数、phase 日程和选择规则。`scripts/run_sstdpn.py` 的默认 phase epoch 因 BNCI2014001/004 而异；新合同的实际值优先。短训仅支持其实际覆盖的阶段，不能证明尚未触及的 phase 有效或无效。
- phase-1 使用验证损失保存 checkpoint；phase-2 从该 checkpoint 恢复并按冻结规则训练。解释结果时记录两阶段实际完成、使用的数据范围和最终 checkpoint，不把“某阶段参与”直接归为候选贡献。
- ACC、Kappa、macro-F1 与统计单位按本 Program 的冻结合同解释。UEP 的 `tp-sstdpn-native-v1` 为独立身份；不能与 DBConformer 的 weighted-F1 或不同数据路径混在同一归因中。
- 合法未排序输入若 X、y 与样本 ID 同步，消费者应一致规范化成员与配对关系并接受；重复 ID、错配、成员篡改或身份不一致应拒绝。规范化不得改变冻结合同规定的科学训练顺序。行序修复的历史验证只在其确切实现与覆盖范围内复用。

候选与行动优先服务拟议 Primary Claim 或成文关键缺口：先收敛 SST-DPN 主方法及关键证据，再考虑解决其具体局限的辅助创新；诊断支持或正筛查不自动表示主创新已成立。候选集合、训练重复、必要控制、主要比较、选择规则、成本和停止条件在结果查看前按 L1/L2、合同与授权确定。ISP/ICP、phase 或初始化诊断仅在可能改变设计或停止判断时安排；历史 DRPG 等支持性诊断不自动决定新方向。

## 3. 当前认识与项目来源

按 L2 第6节在一个稳定研究总览维护拟议主张、关键缺口与当前认识，brief 引用相关条目，原分析保留证据。认识区分参考实现、wrapper、UEP、数据集、phase 和数据角色，支持与反例并列；多因素一起改变时不强行给出单一衰减原因，效用与机制归因分别判断。下一轮说明历史认识实际改变了什么结构、控制或停止选择，仅在判断变化时更新。无效工程运行不作为科学零效应；正式 Claim 由原评估流程及 Claim Ledger 判定。

| 事实 | 直接来源 |
|---|---|
| Program baseline、executor 与配置身份 | `ai4s/programs/sstdpn/PROGRAM.yaml` |
| 活动状态、证据与冻结对象 | `ai4s/programs/sstdpn/research/STATE.yaml`、`EVIDENCE_INDEX.yaml` 及索引指向的 Transaction |
| 参考模型和原始两阶段实现 | `refs/models/SST-DPN-main/SST-DPN-main/model.py`、`train.py`、`load_data.py` |
| corrected wrapper、当前数据映射和训练入口 | `scripts/run_sstdpn.py` |
| UEP 数据、split、指标和报告约束 | `experiments/UNIFIED_EVALUATION_PROTOCOL.md` 及冻结的 `tp-sstdpn-native-v1` 合同 |
| 行序修复的精确测试与科学顺序边界 | `ai4s/programs/sstdpn/research/asg-r01-v0.1-repair1/execution/ROW_ORDER_REPAIR_REPORT.md`，只用于该修复覆盖范围 |
| 历史运行记录 | `experiments/records/sstdpn/` 与 `ai4s/programs/sstdpn/research/EVIDENCE_INDEX.yaml` 精确登记项 |

路径用于定位稳定来源，不替代动态 State，也不证明当前训练、容量或生产验收状态。历史记录只按登记用途和适用范围读取。

## 4. 执行与恢复

普通工程修复、累计成本、有效进展和资格通过后的授权衔接统一按 [L2 工程恢复](../../prompts/LEVEL2_EXECUTION_v3.3.md#5-工程恢复先保留成果再关闭实际缺口)。同步行序、字段及消费者修复保持原配对与科学训练顺序，phase-1／phase-2 checkpoint 资格分别核对；暂停和既有零重试限制不因修补解除。

字段接口按 runtime“字段接口与产物闭环”核验；技术字段与科学字段的生产者、任务阶段和返回结构分清，新增来源复用分支须经过真实小工件消费。既有暂停、阶段顺序和冻结门保持原规则，字段适配不自动恢复训练。

新 Transaction 合同默认启用 `analysis_v1` 精简回传；冻结前按共享 runtime“新合同冻结前检查”运行 `validate-new`，明确实际分析依赖、包上限和核验超时，缺字段即停止准备并补齐。已有冻结 Run／Bundle 继续原规则，不补写字段或自动迁移。

执行、Bundle、资源策略摘要、验收和恢复使用 L2 与 `ai4s/prompts/TRANSACTION_RUNTIME.md` 现有入口。针对本次改变验证受影响的生产路径及必要反例；源码、接口、环境和任务形状仍覆盖时复用既有检查。CPU 合成检查只证明对应的软件路径，不能代替合同要求的 GPU 完整进程资格。

SST-DPN 顺序任务按冻结 phase 和节点收尾需求安排预算；一次超时不自动放宽全部任务时限。GPU 遥测缺失、容量等待、进程失败和产物验收失败分开判断。修复时保留原结果、哈希、INVALID 状态和累计成本；只对符合原合同的任务复用，避免默认整套重训。实际科学行为发生变化或无法证明恢复原行为时，按适用的新计划、合同和授权处理。

资源参数从适用执行器、冻结合同和最终包摘要读取；本 L3 不设统一显存余量、共卡限制或可重试次数。激活此适配不会更新 State、Evidence Index、合同或已有工作的原链绑定，也不授予新实验权限。


