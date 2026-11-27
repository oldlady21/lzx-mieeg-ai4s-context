# MI-EEG 当前项目快照

导出时间（UTC）：2026-11-27T08:08:23.597661+00:00
快照 ID：`952a5db98e19faac99a3d7385e3eb1aab3fc210d54fb92f3857bad35d4b641d8`

## 全局进度

**项目目标与阶段** · [README.md](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/README.md#%E5%BD%93%E5%89%8D%E7%A0%94%E7%A9%B6%E9%98%B6%E6%AE%B5)

- 当前优先在已有模型上找到一项有实验正信号的结构改进。先定位模型在什么条件下表现受限，再用匹配对照检验改动能否解决问题。候选出现可信的正信号后，再考虑收敛成稿。
- DSAINet 是论文首选主线。MVCNet 已在特定比较中取得实质性改进，保留同一优先级。DBConformer、SST-DPN 和 OTA 并行探索，形成有实质收益的改进时按其证据评估，也为 DSAINet 提供可借鉴的诊断、对照和反例。 研究定位
- 科研工作主要由 AI4S 承担，工作流也随实际研究持续调优。DSAINet 和 MVCNet 各自已有明确的探索方向，具体内容按对应 Program 的活动 L3 读取，当前研究任务见工作台。 活动链索引 · 当前工作台

**待办摘录** · [TASKS.md](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/TASKS.md#next)

- 沿 DSAINet 的科学方向核验已授权的对照，按结果确定下一项最能区分解释的结构验证。
- 沿 MVCNet 的科学方向核验已授权的候选比较，判断新改动相对适用宿主的增量与适用范围。
- 从并行探索中整理可改变 DSAINet 设计取舍的结果，注明来源、适用条件和可借鉴的对照。

**论文优先事项** · [PAPER.md](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/PAPER.md#8-%E6%88%90%E6%96%87%E6%89%80%E9%9C%80%E7%9A%84%E4%B8%8B%E4%B8%80%E6%AD%A5)

- 优先在 DSAINet 的既定主线中验证结构改进。用匹配对照检验改动能否解决一个已识别的模型问题，并记录效果及其适用条件。
- 同步推进 MVCNet 的第一优先级探索。保留 VCN-P1 在既定范围内的已验证改进，用相应宿主与匹配控制判断新候选的实际增量。
- 确立可作为论文核心的正信号后，再收敛稿件。把研究问题、结构改动与支持结果连起来，随后确定正式评估范围和拟入表资产。

[当前有效决策入口](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/DECISIONS.md#%E5%BD%93%E5%89%8D%E6%9C%89%E6%95%88%E5%86%B3%E7%AD%96%E5%85%A5%E5%8F%A3)

## 五个 Program 的本地状态

以下为导出时各 State 的登记。任务与论文摘录按原文顺序选取。活动链以 Prompt Index 为准，具体结论请核对证据索引。

| Program | 状态 | 暂停 | 活动 Run / Operation | 来源 |
|---|---|---|---|---|
| dsainet | WAITING_REMOTE | 否 | dsainet-b0-spatial-person-gradient-r1-budget2 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml) · [分段1](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-001.md) · [分段2](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-002.md) · [分段3](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-003.md) |
| mvcnet | WAITING_REMOTE | 否 | mvcnet-pool-antialias-001-development-v1 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/EVIDENCE_INDEX.yaml) · [分段1](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.parts/part-001.md) · [分段2](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.parts/part-002.md) |
| dbconformer | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/EVIDENCE_INDEX.yaml) · [分段1](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-001.md) · [分段2](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-002.md) · [分段3](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-003.md) |
| sstdpn | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/NEXT_RESEARCH.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/EVIDENCE_INDEX.yaml) |
| ota | COMPLETE_MAX_ROUNDS | 是 | 无 / 无 | [State](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/STATE.yaml) · [研究认识](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/CURRENT_UNDERSTANDING.md) · [证据索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/EVIDENCE_INDEX.yaml) |

[活动链索引](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/PROMPT_INDEX.yaml) · [同步清单与来源哈希](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/SYNC_MANIFEST.json)
