# SST-DPN 历史证据交接

接入日期：2026-09-19。来源及接入时 SHA-256 见同目录 `EVIDENCE_INDEX.yaml`。本文件用于导航，不替代历史合同、原始分析或正式审查；本次不重做结果审计。

## 基模与中央归档

基模使用 `scripts/run_sstdpn.py` 的 corrected wrapper，参考源码与 wrapper 分别保留身份。两数据集 CO/CV/LOSO 已有完成记录，但中央 `result_registry.csv` 目前只有 BNCI2014001 LOSO 和 BNCI2014004 CO/CV/LOSO 四项。BNCI2014001 CO/CV 的来源是 `experiments/records/sstdpn/2026-07-16_sstdpn_bnci2014001_co_cv_full.md`。

这是待核对并登记已有结果的缺口，不是自动补跑理由。本次接入只登记缺口，不修改共同结果索引。历史预测、可恢复 checkpoint 和 F1 重算限制继续保留；需要复用具体模型时另核验 checkpoint 身份。

## 四条历史研究的边界

| 对象 | 已有判断 | 未来研究必须保留的限制 |
|---|---|---|
| SCID：scale/channel identifiability | 精确诊断关闭，`no_scale_identifiability` | 不能把原生三段直接视为纯短/中/长尺度；未建立用于 prototype 改写的 scale/channel 锚点 |
| SNPD：source-nuisance prototype | 精确诊断关闭，`no_source_nuisance_prototype_anchor` | source identity 可解码不等于 ISP/ICP 稳定占据 nuisance 子空间；不据此恢复 orthogonalization 改法 |
| FCSM：factorial channel/scale mixer | 精确 18-unit 候选 `no_signal`，负边界 | 不重跑同一候选救援；其失败不否定所有通道—尺度结构，新的问题需有独立证据依据 |
| DRPG：direction/radius geometry | 18/18 零训练诊断形成 `isp_icp_geometry_anchor`，支持性证据 | 外审 WARN、artifact-manifest/load-time-hash 缺口和 selection-used 身份保留；不能推断性能损害、改写收益或形成主张 |

四份 `research_cycle.md` 与对应 `_work/decisions/S9_CYCLE_CLOSE_DECISION.md` 均按原路径引用。历史中 `no_go`、`paused`、`supporting_evidence` 等只描述其精确对象，不能映射为本 Program 的状态。DRPG 当时的用户选择暂停及“未授权 child”事实继续有效；本次建立 Program 没有选择该后续实验。

## 待研究问题

可以从多尺度表征、空间—频谱耦合或原型几何中选择新问题，但首个 research 尚未选定。选题时说明它相对上述精确路线的新证据、可归因对象与停止条件；普通探索不预先建立评估计划或 Claim Ledger。
