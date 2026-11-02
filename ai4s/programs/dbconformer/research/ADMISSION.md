# DBConformer 时空表征与分支机制 AI4S Program 接入记录

- Program：`dbconformer`
- 完成日期：`2026-09-19`
- 用户确认：用户在候选分析后明确要求“为DBConformer＋SST-DPN  建立program”。据此建立并激活两个已选 Program；本条仅授权 Program 接入。
- L3：`ai4s/programs/dbconformer/PROJECT_PROMPT_v0.1.md`
- 共享链：L1/L2 v2.1；Transaction v2；正式评估规范版本 1。
- 兼容与差异报告：`ai4s/_work/baseline_program_admission_20260919/REPORT.md`。

## 接入范围

新建 Program、独立 L3、State、Evidence Index 与历史边界导航；仅在唯一 Prompt Index 中新增本模型条目。
两种基模实现与两类协议独立绑定；历史 negative/supporting 范围保留。

历史资料按原路径和本次 SHA-256 引用，verified 范围只是来源文件身份。既有 checkpoint/data 的完整性和可复用性仍按具体研究核对；本次不重判结果、不释放主张。

初始 State 为 READY，表示可接收研究任务。没有 campaign、活动 Run/operation、首个候选或执行授权；预算与轮次均为零。
Lab10 仅按当前共享配置登记为默认能力，实际使用由后续任务确定；本次无远端 probe、训练、上传、启动或GPU验收。

接入前已读历史科学边界，但不继承 cycle/family 状态机、历史运行权限或其他 Program 的研究状态。
普通探索不提前建立 EVALUATION_PLAN 或 CLAIM_LEDGER；正式评估时按活动链按需建立。

## v3.1 技术规则补充（2026-10-10）

2026-10-11 新普通 Lab10 合同采用实验室宽松容量策略；精确字段和值以本 Program 的 `PROGRAM.yaml` 及新冻结 Transaction 为准，新包的 `RESOURCE_POLICY_SUMMARY.json` 记录实际采用值。画像须匹配生产形状和完整进程证据，B0/C0 不外推 P1。该补充只适用于新合同，不回写冻结 Run；细则见 `ai4s/prompts/TRANSACTION_RUNTIME.md` 的“容量与旧证据”和“包内资源策略摘要”。

活动链的部署、字段验收、按改动范围重放和逐任务恢复统一从 `ai4s/prompts/TRANSACTION_RUNTIME.md` 检索；不同 arm 的资源观测不可外推，初筛与充分验证按冻结合同分层解释。该补充不改变本接入记录的历史授权边界；旧 Run 仍按原合同和绑定链恢复，新包须登记实际源码身份。

2026-10-14 启动命令、最终包离线验收与统一回归入口按活动链 `ai4s/prompts/TRANSACTION_RUNTIME.md` 的“新启动接口的离线验收”执行；具体资源值只读 Program、冻结合同及包内摘要。此补充不追改既有冻结合同、Bundle 或 Run。
