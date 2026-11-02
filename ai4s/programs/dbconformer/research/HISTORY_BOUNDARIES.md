# DBConformer 历史证据交接

接入日期：2026-09-19。本文件是读取导航和精确边界摘要，来源及接入时 SHA-256 见同目录 `EVIDENCE_INDEX.yaml`。科学判断以对应原始记录、冻结合同和证据为准；本次没有重做结果审计或授予历史续跑权限。

## 已有资产

- 原生 baseline manifest 与统一协议基模副本分别登记。原生锁覆盖 7 项；UEP 副本另有接入快照，不能因名称相同替换。
- UEP 两数据集 CO/CV/LOSO 六项已有登记，各 45 subject-seed 行；CV 另有 225 fold 行。中央 registry 及 integrity summary 不证明全部 checkpoint 当前可恢复。
- 历史结果已暴露；与候选选择有关时逐条登记 selection_used/seen/unknown，不能把新增 seed 当作清除选择历史。

## 精确路线的已知限制

| 路线 | 需继承的科学边界 | 主要来源目录（`experiments/records/` 下） |
|---|---|---|
| CfC、预训练适配及输入因子化探索 | 已有 scoped no-go 或停止记录；概念暂存不等于可执行候选 | `2026-08-09_dbconformer_cfc_reassessment`、`2026-08-09_dbconformer_input_factorization_rebuild`、`2026-08-09_dbconformer_mechanism_reselection` |
| TPCR/SATR event/context 分配 | discovery 和 path-use 观察不等于稳定主性能；后续确认与 SATR 未达冻结门，保留全部选择历史 | `2026-08-13_dbconformer_temporal_phase_complementary_routing`、`2026-08-14_dbconformer_tpcr_v0_2_evidence_continuation`、`2026-08-13_dbconformer_asymmetric_event_context_routing` |
| LCUS/OD-LCUS/TCUS/ACUS | 多个精确输入分解实例未出现可归因净效用；不得改名重跑同一快照 | `2026-08-14_dbconformer_learned_complementary_unmixing`、`2026-08-16_dbconformer_offdiag_complementary_unmixing`、`2026-08-17_dbconformer_temporal_complementary_unmixing`、`2026-08-18_dbconformer_asymmetric_complementary_unmixing` |
| FAGER/IER/FAER | 精确候选均无信号；IER-RIO 的同 checkpoint on/off 贡献不能替代相对独立 B0 的净收益 | `2026-08-18_dbconformer_event_gated_temporal_residual`、`2026-08-18_dbconformer_identity_event_residual`、`2026-08-18_dbconformer_ier_residual_insertion_observation`、`2026-08-19_dbconformer_frozen_anchor_event_residual` |
| ACLT | 精确分类树结构为负边界，不形成主性能或机制 claim | `2026-08-21_dbconformer_anatomy_conditioned_label_tree` |

Evidence Index 对匹配 `*dbconformer*` 的 22 份历史 research_cycle 原文逐一登记，包含上述摘要以外的记录。它们没有可继承的活动实验授权；旧字段保留原文，不映射成新 Program 的运行状态。涉及更早 proposed_v2 等路线时，再从 `PAPER.md` 的相关来源回溯，不把本表视为全部失败的穷尽审计。

## 尚待研究选择

Program 尚未选定首个 research。新问题需解释与相关精确负边界的差异、预期信息和最小对照；既不恢复旧状态机，也不把精确负结果扩大为所有时空交互均无效。
