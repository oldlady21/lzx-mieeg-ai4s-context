---
prompt_id: DBCONFORMER_MI_EEG_PROJECT
version: '3.3'
level: 3
parent: {prompt_id: MIEEG_AI4S_EXECUTION, version: '3.3'}
status: DRAFT
---
# DBConformer 项目适配 v3.3

## 阅读与研究认识入口

研究认识与唯一来源索引见 [研究总览](research/CURRENT_UNDERSTANDING.md)。该总览指向基模阅读材料与本地实现依据；本 L3 不重复列举论文路径。

首次采用基模理解时，重点核对两条压缩路径各保留什么 token、融合与训练配套及本地宿主对应；时间支路仍可含空间信息，EA 不等同类分布对齐。原生与 UEP 实现分别核对。 已有同版本核对可复用，缺口只限制依赖它的判断。

新判定映射要区分完整方法、校准／统计刷新效用和结构归因，并绑定具体宿主与数据角色；FCA／BCU 等旧实例的固定优效与风险门不因新主张改判，也不作为所有新贡献的统一模板。 实际判定路径的对应、接线缺口与最小验证按 [L2 第2节](../../prompts/LEVEL2_EXECUTION_v3.3.md#2-用现有-brief-完成一页决策)执行，共享细则不在本 L3 重复。

仅当 `ai4s/PROMPT_INDEX.yaml` 为 DBConformer 选定兼容的 v3.3 L1/L2/L3 活动链时，本适配才生效。运行状态和证据按索引进入 Program 的 State、Evidence Index 与冻结 Transaction；冻结工作沿其原绑定链、合同、预算和关闭边界处理。本文件只保存稳定项目约束，不复制活动 Run 状态或实验结论。

## 1. 宿主与比较身份

保留 DBConformer 原生实现与 DSAINet 来源 UEP 实现的身份。原生 BNCI2014001、原生 BNCI2014004、UEP BNCI2014001 与 UEP BNCI2014004 分别绑定其实现、数据处理、划分、训练 profile 和 checkpoint 选择；不得共用一个 B0，或把跨数据集、跨 profile 的结果当成精确配对。

- **原生宿主：**使用对应原生训练入口与来源实现，沿其冻结的协议、增强、优化器、划分和选择规则比较。001 与 004 各自核对类别、通道、session、长度和 EA 设置。
- **UEP 宿主：**身份为 `dbconformer-dsainet-uep`，遵循 `mieeg-uep-v1.0` / `tp-dsainet100-v1`。它可按 UEP 的 `eval-compatible` 规则比较；只有合同、数据与 outer split、seed/profile 均满足要求时，才标为 `exact-paired`。不能把这类协议比较写成原论文原生日程或纯架构归因。

新候选先在 brief 中指出声明宿主、实现身份和主比较。增量归因须验证关闭增量恢复该合同绑定的宿主函数。完整方法允许必要训练配方；如果结论要归因于单一模块，需有对应的控制，并处理容量、训练投入和适配外壳等解释。不同宿主之间的完整方法比较不能代替单组件归因。

## 2. 设计时核对

只核对会影响本次设计或解释的路径，稳定事实按需回到下列源码；这些检查是研究设计提示，不是每轮新增门。

- 输入形状、类别数、时空变换、分支和分类头必须与目标数据及被声明的 DBConformer 宿主匹配；增量恢复对照须对应宿主的实际计算路径。
- 指出干预实际进入 forward、loss、gradient 或 checkpoint 选择的位置。分支名称、张量维度或较低表示相似度本身不证明职责互补或机制有效。
- 原生协议共享原生实现的拆分、增强、优化与评估路径；UEP 采用 UEP 独立预处理和 `tp-dsainet100-v1` 设置。二者的运行值、profile 和性能不得互换。
- ACC、Kappa、F1 averaging、统计单位、配对关系和 checkpoint 选择按冻结协议解释。UEP 历史 F1 可能为 weighted；须注明 averaging，不能与 macro F1 直接比较。应使用冻结规则产生的同一评价对象，不能挑选结果后的最佳配置或 seed。
- 若涉及官方预训练权重，记录来源、实际载入和数据接触；下游划分相同不自动证明上游知识或全流程成本公平。

先对齐拟议 Primary Claim 或成文关键缺口，优先收敛 DBConformer 主方法与关键证据；辅助创新须解决其具体局限，不因增加分支或获得一次正收益就转入模块搭配。候选可涉及结构、表征、学习目标、训练机制或有依据的简化；宿主特点可启发问题，无需先额外实验证明宿主缺陷。有限配置和重复按 L1/L2 与实际授权预先界定，不将多个配置事后并作一个机会。

## 3. 当前认识与项目来源

按 L2 第6节在一个稳定研究总览维护拟议主张、关键缺口与当前认识，brief 引用它，原分析保留证据。只更新改变当前选择的结论、反例或未知，标明原生／UEP、001／004、profile、数据角色及来源；整体效用、分支机制和 checkpoint 贡献分开解释。下一轮说明这些认识如何改变主比较、控制或投入，相似方向明确实质差异。正式 Claim 仍按共享评估流程及对应 Claim Ledger 判定；初筛不能自动升级成母项目 Claim。

| 事实 | 直接来源 |
|---|---|
| Program baseline、executor 与实现身份 | `ai4s/programs/dbconformer/PROGRAM.yaml` |
| 活动状态、精确证据和冻结对象 | `ai4s/programs/dbconformer/research/STATE.yaml`、`EVIDENCE_INDEX.yaml` 及索引指向的 Transaction |
| 原生实现与完整性核验 | `src/baselines/dbconformer.py`、`src/models/dbconformer/baseline.py`、`scripts/verify_dbconformer_baseline.py` |
| 原生 protocol loop 的适配接口 | `src/training/dbconformer_protocol.py`；对应入口 `scripts/run_dbconformer_bnci2014001.py`、`scripts/run_dbconformer_bnci2014004.py` |
| DSAINet 来源 UEP loader 与运行协议 | `src/models/dbconformer/dsainet_reference.py`、`scripts/run_dbconformer_bnci2014001_dsainet_protocol.py`、`scripts/run_dbconformer_bnci2014004_dsainet_protocol.py`、`experiments/UNIFIED_EVALUATION_PROTOCOL.md` |
| 数据与实验 profile | `experiments/configs/dbconformer/` 中与冻结合同绑定的配置；运行前核对数据及配置哈希 |

以上路径用于定位稳定来源，不证明当前活动链、checkpoint、数据或 GPU 已验收。动态状态只从指定的权威记录读取。

## 4. 执行与恢复

字段接口按 runtime“字段接口与产物闭环”核验；新 FCA 路径覆盖来源子清单的回传、epoch 标量与 trace 列表、raw 结果与验证上下文、source-data 绑定的真实写入/复用读取。必要派生字段从封存来源唯一重建并核验，不能手工补空值或 PASS；已完成训练优先保留，旧冻结分析器失败与派生修复分别记录。

新 Transaction 合同默认启用 `analysis_v1` 精简回传；冻结前按共享 runtime“新合同冻结前检查”运行 `validate-new`，明确实际分析依赖、包上限和核验超时，缺字段即停止准备并补齐。已有冻结 Run／Bundle 继续原规则，不补写字段或自动迁移。

执行、Bundle、资源策略摘要、验收和恢复使用 L2 与 `ai4s/prompts/TRANSACTION_RUNTIME.md` 的现有入口。只核验本次改变触及的生产路径及必要合法边界和故障反例；可复用仍覆盖当前源码、接口、环境和任务形状的有效检查。

共享验收若读取数值 epoch，仅当值有限、非负、在合同范围内且数学上为整数时规范化（例如 `85.0`）；缺少必需证据、冲突字段或身份错误仍失败。原始产物保留，解析修复不得改写科学标准。DBConformer 的 B0/C0 或某 profile 资源画像不得外推至 P1、其他宿主或数据集；资源数值以适用执行器、冻结合同和包内摘要为准。

旧 Run 的复用、INVALID、失败节点、预算和恢复权限按其原合同处理。本适配不修改 State、Evidence Index、合同或活动绑定，也不因激活 v3.3 而产生新实验授权。


