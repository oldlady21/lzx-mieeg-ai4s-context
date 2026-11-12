# MI-EEG 当前项目快照

导出时间（UTC）：2026-11-12T05:51:20.925638+00:00
快照 ID：`2dc69c1ebbc9edbc56e4555b8226c51295e6dafa3bb08581ed13214cf03bb246`

## 全局进度

**项目目标与阶段** · [README.md](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/README.md#%E5%BD%93%E5%89%8D%E7%A0%94%E7%A9%B6%E9%98%B6%E6%AE%B5)

- 论文的工作问题是：**在多分支、多尺度 MI-EEG 模型中，结构差异何时形成可利用的增量信息，以及这种信息如何转化为稳定的解码收益？** 这一表述用于收敛论文叙事，尚未冻结为所有 Program 的共同实验假设。
- DBConformer 保留早期主 baseline 定位，DSAINet 是核心匹配对照；MVCNet、SST-DPN 已有各自的研究积累。最终 proposed model、贡献列表和正式评估范围仍待证据收敛，Program 的建立或活跃程度不直接决定论文主模型。
- 目前的论文准备重点是明确主表的数据语义、从已有证据中选择主候选、核验最终入表资产，并同步撰写背景与协议。具体优先级和判断依据见 PAPER.md 第八部分。

**待办摘录** · [TASKS.md](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/TASKS.md#next)

- 按需阅读 `FBATCNet` 或 `DBTSP-Net`，分别补充频带先验与自适应融合的设计证据
- 若卒中 MI 支持线进入正式对照，先为 `CFSPMNet` / `PA-TCNet` 建立不使用目标测试标签选 epoch 的无偏模型选择口径
- 以 `STGMFM` / XW-Stroke 修正版 LOSO 作为 source-only validation 模板，后续统一 CFSPMNet / PA-TCNet 的无偏对照口径

**论文优先事项** · [PAPER.md](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/PAPER.md#8-%E6%88%90%E6%96%87%E6%89%80%E9%9C%80%E7%9A%84%E4%B8%8B%E4%B8%80%E6%AD%A5)

- **先明确主表的数据语义。** 整理 BNCI2014001 窗口问题的实际消费者清单，确定论文如何使用历史输入及是否需要新的独立数据版本。保留旧证据身份，不直接改写 UEP 或正在运行的合同。
- **从已有证据中收敛主候选。** 对可能进入论文的候选，说明它解决的具体问题、与精确负边界的区别、净效用及匹配控制、已有选择暴露和缺失证据。VCN-P1 等支持性基础与当前新模块分别评价，不按活跃轮数选主模型。
- **先补登记与可恢复性核验。** 核对 SST-DPN 001 CO/CV 归档缺口、最终入表模型的预测/checkpoint 和同口径指标来源。无法恢复的内容如实列缺口；不能据“统一 F1”自动重训或补造指标。

[当前有效决策入口](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/DECISIONS.md#%E5%BD%93%E5%89%8D%E6%9C%89%E6%95%88%E5%86%B3%E7%AD%96%E5%85%A5%E5%8F%A3)

## 五个 Program 的本地状态

以下为导出时各 State 的登记。任务与论文摘录按原文顺序选取。活动链以 Prompt Index 为准，具体结论请核对证据索引。

| Program | 状态 | 暂停 | 活动 Run / Operation | 来源 |
|---|---|---|---|---|
| dsainet | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml) · [分段1](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-001.md) · [分段2](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-002.md) · [分段3](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-003.md) |
| mvcnet | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/EVIDENCE_INDEX.yaml) |
| dbconformer | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/EVIDENCE_INDEX.yaml) · [分段1](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-001.md) · [分段2](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-002.md) · [分段3](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-003.md) |
| sstdpn | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/NEXT_RESEARCH.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/EVIDENCE_INDEX.yaml) |
| ota | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/EVIDENCE_INDEX.yaml) |

[活动链索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/PROMPT_INDEX.yaml) · [同步清单与来源哈希](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/SYNC_MANIFEST.json)
