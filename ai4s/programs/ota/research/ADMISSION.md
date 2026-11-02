# OTA Program 接入记录

- Program：`ota`
- 完成日期：`2026-09-17`
- 用户确认：用户明确授权“接入program并推进OTA实验”，并确认采用以下边界：Lab10；5 个单 epoch 技术 network fits、90 个正式 network fits、162 个 probes；24 小时 `exclude_resource_wait`；最多一次仅接线或运输工程修复；零自动训练重试；在 source-audit 决策后停止。

本记录只确认 Program 接入与首个 bounded campaign 的预算登记。它不创建冻结合同、Run、Bundle、远端任务、执行授权、科研结果或主张。

2026-10-10 v3.1 技术规则补充：共享验收、部署预检、资源调度与工程恢复引用活动 L2 技术门及 `ai4s/prompts/TRANSACTION_RUNTIME.md`。该补充不改变下述预算、零自动训练重试、source-audit 停止点或已有授权。历史工作及冻结 Run 仍按原绑定链和合同处理，不能由本补充升级；新包须记录实际源码身份。
2026-10-11 新普通 Lab10 合同采用实验室宽松容量策略；精确字段和值以 OTA `PROGRAM.yaml` 及新冻结 Transaction 为准，新包的 `RESOURCE_POLICY_SUMMARY.json` 记录实际采用值。画像须与实现、数据、profile、设备、阶段和完整进程证据匹配，不跨 arm 外推。仅未来新合同适用，不改变既有 Run 或授权边界；共享规则见 `ai4s/prompts/TRANSACTION_RUNTIME.md` 的“容量与旧证据”和“包内资源策略摘要”。

OTA 是独立 Program；不接收 DSAINet 或 MVCNet 的 Run、科研状态、预算、执行授权、结果、preflight 或 claim。Lab10 路由为 `ssh -J [REDACTED_MACHINE] [REDACTED_MACHINE]`；Program 已声明对应 `ssh_options`，传输层接线验证单独进行。

2026-10-14 启动命令、最终包离线验收与统一回归入口按活动链 `ai4s/prompts/TRANSACTION_RUNTIME.md` 的“新启动接口的离线验收”执行；具体资源值只读 Program、冻结合同及包内摘要。既有冻结合同、Bundle、Run 与其规则保持不变。
