---
prompt_id: OTA_MI_EEG_PROJECT
version: '3.4'
level: 3
parent: {prompt_id: MIEEG_AI4S_EXECUTION, version: '3.4'}
status: ACTIVE
---
# OTA 项目适配 v3.4

## 阅读与研究认识入口

研究认识与唯一来源索引见 [研究总览](research/CURRENT_UNDERSTANDING.md)。该总览指向基模阅读材料与本地实现依据；本 L3 不重复列举论文路径。

首次采用基模理解时，以自身研究材料及 model／reference 实现核对软状态占据、有限滞后联合表、log／双中心化和读出接口；联合表不等于条件转移矩阵，不假定 Markov 性，也不把学习型状态称作真实 EEG 脑状态。 已有同版本核对可复用，缺口只限制依赖它的判断。

新判定映射要区分占据／关联信息、匹配初始函数的自由读出及对照用途，不能借用 DSAINet 效用门证明 OTA；首次 Run 技术要求及旧 source-audit 规则继续原绑定，不因本次提示词修补解除。 实际判定路径的对应、接线缺口与最小验证按 [L2 第2节](../../prompts/LEVEL2_EXECUTION_v3.4.md#2-用现有-brief-完成一页决策)执行，共享细则不在本 L3 重复。

新工作按 Prompt Index 选定的兼容活动链处理。历史 OTA v3.1 对象沿精确旧绑定继续。当前状态、预算和执行授权只从 OTA 的 State、Evidence Index 与冻结 Transaction 读取。

## 独立研究边界

OTA 是独立的状态占据—滞后关联双分支 Program，研究问题围绕其自身实现、数据、阈值和 source audit 建立。它不继承任何其他 Program 的 Run、科研状态、预算、执行授权、实验结果或论文主张。跨 Program 证据只能作为待验证的研究启发。State 中的暂停状态始终否决自动续接；新版提示词不解除当前暂停，只有后续明确授权和状态变更才能恢复。

首次科学 Run 必须同时满足本 Program 冻结 Transaction、明确执行授权和同一 Transaction 的生产单 epoch 技术检查。技术预检策略固定为 `in_transaction_production_epoch`，不复用其他 Program 的 preflight。具体任务、数据、seed、阈值和 source-audit 决策写入合同与结果记录，不写入本 L3。

## 稳定事实来源

| 事实 | 来源 | 状态 |
|---|---|---|
| Program 与执行器 | `ai4s/programs/ota/PROGRAM.yaml` | VERIFIED，动态路由仍需索引一致 |
| 当前状态与预算 | `ai4s/programs/ota/research/STATE.yaml` | VERIFIED，动态读取 |
| 证据索引与接入边界 | `ai4s/programs/ota/research/EVIDENCE_INDEX.yaml`、`ADMISSION.md` | VERIFIED |
| OTA 本地实现 | `ai4s/programs/ota/research/ota-v0.1/` | VERIFIED，作为合同输入 |
| OTA-RL 诊断适配器 | `ai4s/programs/ota/research/ota-rl-v0.1/lifecycle.py` | VERIFIED，冻结 source-only readout |

## 研究与评估

研究优先级及 brief 中的结构预测和区分对照按 L1 第1节和 L2 第2节执行。OTA 特有地分别处理 source audit 与生产技术资格、相对 OTA 宿主的效用，以及占据／关联双分支的归因。依据限于本 Program 合法记录。State 的暂停和首次 Run 的生产单 epoch 技术检查仍按原规则。

候选须与 OTA 的实际宿主计算路径及可观察结果对应。新结构问题可涉及局部软状态编码、占据表示、有限滞后联合表或两支读出交互；主比较回答完整候选相对宿主的效用，匹配初始函数的自由读出等控制回答各自限定的替代解释。提示词中的研究优先级不改变 Program 独立性或 State 暂停。正式评价、benchmark 和 Claim 按 ai4s/prompts/EVALUATION_EVIDENCE.md 的适用冻结范围处理。

## 技术执行补充

普通工程修复、累计成本、有效进展和资格通过后的授权衔接统一按 [L2 工程恢复](../../prompts/LEVEL2_EXECUTION_v3.4.md#5-工程恢复先保留成果再关闭实际缺口)。原生产单 epoch 与零自动训练重试依精确冻结规则保留，不泛化为禁止离线修复或原规则允许的产物重放；新技术任务重做须有相应预授权，不绕过首次 Run 资格和暂停。

新 Transaction 合同默认启用 `analysis_v1` 精简回传；冻结前按共享 runtime“新合同冻结前检查”运行 `validate-new`，明确实际分析依赖、包上限和核验超时，缺字段即停止准备并补齐。已有冻结 Run／Bundle 继续原规则，不补写字段或自动迁移。

技术闭环遵循 L2 技术门及 `ai4s/prompts/TRANSACTION_RUNTIME.md` 的部署、容量、最终包验收与资源摘要规则。OTA 保留 `in_transaction_production_epoch` 检查、零自动训练重试、既有预算与 State 暂停门；策略只对符合范围的新合同生效。未知画像按匹配阶段核验，不跨 arm 外推；资源等待、派发失败及遥测缺失分别记录。科学门按冻结合同解释，恢复按合同、哈希与任务身份逐项核验，不默认整套重训或补记 PASS。已有冻结 Run 和旧工作沿原链处理，新链不静默升级旧合同或恢复暂停。




