# lzx-mieeg-ai4s 讨论资料入口

仓库：https://github.com/oldlady21/lzx-mieeg-ai4s-context
导出时间（UTC）：2026-11-05T13:48:29.048549+00:00
快照身份：`8ad3f9c1f3ce5b7cd23827ec04485fd03d681997fe48490ca7498b2efbc4d2c0`

这是本地已保存文件的公开讨论副本。来源与公开文件 SHA-256、脱敏计数、未公开引用见 [SYNC_MANIFEST.json](SYNC_MANIFEST.json)。
机器字段已机械脱敏；保留原研究身份、冻结边界、预算、证据状态和历史。它不替代本地权威记录，不授予执行/恢复/改协议权限。
合同公开副本可能因脱敏与重排而改变哈希，不能作为可执行冻结合同。源文件字节哈希与合同内的科学规范哈希不是同一种身份。
同一文件中的历史准备、失败和结果段落仍是历史。当前本地运行登记如下；未查询服务器，不保证远端实时状态。

下面只列运行身份摘要，不是完整预算、协议或科学结论。source_path 是本地项目路径；source_public_url 才是公开读取地址。source_in_this_repository=false 仅表示不在本库，不表示未公开。

## 当前本地登记

```json
{
  "dsainet": {
    "source_path": "ai4s/programs/dsainet/research/STATE.yaml",
    "source_sha256": "4ef0f3c4228815d8817087a085c44164036f9a4d3220a7754ad8d2ea4955ceea",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-05T13:09:08.803027+00:00",
    "status": "COMPLETE_MAX_ROUNDS",
    "paused": true,
    "active_run": null,
    "active_operation": null,
    "source_public_parts": [
      "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-001.md",
      "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-002.md",
      "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.parts/part-003.md"
    ]
  },
  "mvcnet": {
    "source_path": "ai4s/programs/mvcnet/research/STATE.yaml",
    "source_sha256": "1a1ad39582bf6b3373c536394aead7e2f4fa9a54d908ed81f5d7cd5b3c71c6d4",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-05T13:35:52.182281+00:00",
    "status": "COMPLETE_MAX_ROUNDS",
    "paused": true,
    "active_run": null,
    "active_operation": null
  },
  "dbconformer": {
    "source_path": "ai4s/programs/dbconformer/research/STATE.yaml",
    "source_sha256": "9b788d809c8b084683e0781dfdbf6679502156266a417230efde60e6494e16f5",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-05T11:39:27.618042+00:00",
    "status": "COMPLETE_MAX_ROUNDS",
    "paused": true,
    "active_run": null,
    "active_operation": null,
    "source_public_parts": [
      "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-001.md",
      "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-002.md",
      "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.parts/part-003.md"
    ]
  },
  "sstdpn": {
    "source_path": "ai4s/programs/sstdpn/research/STATE.yaml",
    "source_sha256": "eb7f498725293661e00f4166d3bf06c2f27ccce44baca925a0abd5232bd011ba",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-05T12:15:39.972563+00:00",
    "status": "COMPLETE_MAX_ROUNDS",
    "paused": true,
    "active_run": null,
    "active_operation": null
  },
  "ota": {
    "source_path": "ai4s/programs/ota/research/STATE.yaml",
    "source_sha256": "c47735370b9d8a57bb1baf005a51fe71ec86cd696a1db20dc9d2458f547506f8",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-10-30T17:05:54.495968+00:00",
    "status": "COMPLETE_MAX_ROUNDS",
    "paused": true,
    "active_run": null,
    "active_operation": null
  }
}
```

## 阅读顺序

1. 本入口与同步清单。
2. PROMPT_INDEX 指定的活动链、对应 Program 当前认识、State 与 Evidence Index（本库提供的范围内）。
3. 根据问题读取决策、论文主线和具体报告。引用不在本库时先查下方对应模型库；仍找不到时再说明未公开，不推断为已核验。

## 模型 State 公开地址

- [dsainet/STATE.yaml](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.yaml)（本库也提供）
- [mvcnet/STATE.yaml](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.yaml)（本库也提供）
- [dbconformer/STATE.yaml](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.yaml)（本库也提供）
- [sstdpn/STATE.yaml](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/STATE.yaml)（本库也提供）
- [ota/STATE.yaml](https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/ota/research/STATE.yaml)（本库也提供）

## 跨 Program 阅读入口

先比较各 Program 的研究认识和上方运行摘要；再按讨论对象读取 State、证据索引、L3及历史边界。无需每轮全文加载所有历史。跨 Program 可共享证据与设计约束，暂停、冻结和实验授权仍各自独立。State较大时先读分段链接；这些是完整脱敏正文的连续片段，不能只读一段就宣称核验了全部State。不把连接的体积限制误判为未公开。

| Program | 研究认识 | 配置 | State | 证据索引 |
|---|---|---|---|---|
| dsainet | [CURRENT_UNDERSTANDING.md](ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/dsainet/PROGRAM.yaml) | [STATE](ai4s/programs/dsainet/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/dsainet/research/STATE.yaml) · [分段1](ai4s/programs/dsainet/research/STATE.parts/part-001.md) · [分段2](ai4s/programs/dsainet/research/STATE.parts/part-002.md) · [分段3](ai4s/programs/dsainet/research/STATE.parts/part-003.md) | [EVIDENCE_INDEX](ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml) |
| mvcnet | [CURRENT_UNDERSTANDING.md](ai4s/programs/mvcnet/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/mvcnet/PROGRAM.yaml) | [STATE](ai4s/programs/mvcnet/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/mvcnet/research/STATE.yaml) | [EVIDENCE_INDEX](ai4s/programs/mvcnet/research/EVIDENCE_INDEX.yaml) |
| dbconformer | [CURRENT_UNDERSTANDING.md](ai4s/programs/dbconformer/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/dbconformer/PROGRAM.yaml) | [STATE](ai4s/programs/dbconformer/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/dbconformer/research/STATE.yaml) · [分段1](ai4s/programs/dbconformer/research/STATE.parts/part-001.md) · [分段2](ai4s/programs/dbconformer/research/STATE.parts/part-002.md) · [分段3](ai4s/programs/dbconformer/research/STATE.parts/part-003.md) | [EVIDENCE_INDEX](ai4s/programs/dbconformer/research/EVIDENCE_INDEX.yaml) |
| sstdpn | [NEXT_RESEARCH.md](ai4s/programs/sstdpn/research/NEXT_RESEARCH.md) | [PROGRAM](ai4s/programs/sstdpn/PROGRAM.yaml) | [STATE](ai4s/programs/sstdpn/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/sstdpn/research/STATE.yaml) | [EVIDENCE_INDEX](ai4s/programs/sstdpn/research/EVIDENCE_INDEX.yaml) |
| ota | [CURRENT_UNDERSTANDING.md](ai4s/programs/ota/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/ota/PROGRAM.yaml) | [STATE](ai4s/programs/ota/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/ota/research/STATE.yaml) | [EVIDENCE_INDEX](ai4s/programs/ota/research/EVIDENCE_INDEX.yaml) |

以下活动链引用仍仅在本地提供，未纳入本次文档公开范围：

- `scripts/ai4s/evaluation.py`（源码，不是公开讨论文档）

## 文档列表

- [AGENTS.md](<AGENTS.md>)
- [DECISIONS.md](<DECISIONS.md>)
- [PAPER.md](<PAPER.md>)
- [README.md](<README.md>)
- [TASKS.md](<TASKS.md>)
- [ai4s/PROMPT_INDEX.yaml](<ai4s/PROMPT_INDEX.yaml>)
- [ai4s/README.md](<ai4s/README.md>)
- [ai4s/programs/dbconformer/PROGRAM.yaml](<ai4s/programs/dbconformer/PROGRAM.yaml>)
- [ai4s/programs/dbconformer/PROJECT_PROMPT_v3.3.md](<ai4s/programs/dbconformer/PROJECT_PROMPT_v3.3.md>)
- [ai4s/programs/dbconformer/research/ADMISSION.md](<ai4s/programs/dbconformer/research/ADMISSION.md>)
- [ai4s/programs/dbconformer/research/CURRENT_UNDERSTANDING.md](<ai4s/programs/dbconformer/research/CURRENT_UNDERSTANDING.md>)
- [ai4s/programs/dbconformer/research/EVIDENCE_INDEX.yaml](<ai4s/programs/dbconformer/research/EVIDENCE_INDEX.yaml>)
- [ai4s/programs/dbconformer/research/HISTORY_BOUNDARIES.md](<ai4s/programs/dbconformer/research/HISTORY_BOUNDARIES.md>)
- [ai4s/programs/dbconformer/research/STATE.parts/part-001.md](<ai4s/programs/dbconformer/research/STATE.parts/part-001.md>)
- [ai4s/programs/dbconformer/research/STATE.parts/part-002.md](<ai4s/programs/dbconformer/research/STATE.parts/part-002.md>)
- [ai4s/programs/dbconformer/research/STATE.parts/part-003.md](<ai4s/programs/dbconformer/research/STATE.parts/part-003.md>)
- [ai4s/programs/dbconformer/research/STATE.yaml](<ai4s/programs/dbconformer/research/STATE.yaml>)
- [ai4s/programs/dsainet/PROGRAM.yaml](<ai4s/programs/dsainet/PROGRAM.yaml>)
- [ai4s/programs/dsainet/PROJECT_PROMPT_v3.3.md](<ai4s/programs/dsainet/PROJECT_PROMPT_v3.3.md>)
- [ai4s/programs/dsainet/research/CLAIM_LEDGER.yaml](<ai4s/programs/dsainet/research/CLAIM_LEDGER.yaml>)
- [ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md](<ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md>)
- [ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml](<ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml>)
- [ai4s/programs/dsainet/research/STATE.parts/part-001.md](<ai4s/programs/dsainet/research/STATE.parts/part-001.md>)
- [ai4s/programs/dsainet/research/STATE.parts/part-002.md](<ai4s/programs/dsainet/research/STATE.parts/part-002.md>)
- [ai4s/programs/dsainet/research/STATE.parts/part-003.md](<ai4s/programs/dsainet/research/STATE.parts/part-003.md>)
- [ai4s/programs/dsainet/research/STATE.yaml](<ai4s/programs/dsainet/research/STATE.yaml>)
- [ai4s/programs/mvcnet/PROGRAM.yaml](<ai4s/programs/mvcnet/PROGRAM.yaml>)
- [ai4s/programs/mvcnet/PROJECT_PROMPT_v3.3.md](<ai4s/programs/mvcnet/PROJECT_PROMPT_v3.3.md>)
- [ai4s/programs/mvcnet/research/CURRENT_UNDERSTANDING.md](<ai4s/programs/mvcnet/research/CURRENT_UNDERSTANDING.md>)
- [ai4s/programs/mvcnet/research/EVIDENCE_INDEX.yaml](<ai4s/programs/mvcnet/research/EVIDENCE_INDEX.yaml>)
- [ai4s/programs/mvcnet/research/STATE.yaml](<ai4s/programs/mvcnet/research/STATE.yaml>)
- [ai4s/programs/ota/PROGRAM.yaml](<ai4s/programs/ota/PROGRAM.yaml>)
- [ai4s/programs/ota/PROJECT_PROMPT_v3.3.md](<ai4s/programs/ota/PROJECT_PROMPT_v3.3.md>)
- [ai4s/programs/ota/research/ADMISSION.md](<ai4s/programs/ota/research/ADMISSION.md>)
- [ai4s/programs/ota/research/CURRENT_UNDERSTANDING.md](<ai4s/programs/ota/research/CURRENT_UNDERSTANDING.md>)
- [ai4s/programs/ota/research/EVIDENCE_INDEX.yaml](<ai4s/programs/ota/research/EVIDENCE_INDEX.yaml>)
- [ai4s/programs/ota/research/STATE.yaml](<ai4s/programs/ota/research/STATE.yaml>)
- [ai4s/programs/sstdpn/PROGRAM.yaml](<ai4s/programs/sstdpn/PROGRAM.yaml>)
- [ai4s/programs/sstdpn/PROJECT_PROMPT_v3.3.md](<ai4s/programs/sstdpn/PROJECT_PROMPT_v3.3.md>)
- [ai4s/programs/sstdpn/research/ADMISSION.md](<ai4s/programs/sstdpn/research/ADMISSION.md>)
- [ai4s/programs/sstdpn/research/EVIDENCE_INDEX.yaml](<ai4s/programs/sstdpn/research/EVIDENCE_INDEX.yaml>)
- [ai4s/programs/sstdpn/research/HISTORY_BOUNDARIES.md](<ai4s/programs/sstdpn/research/HISTORY_BOUNDARIES.md>)
- [ai4s/programs/sstdpn/research/NEXT_RESEARCH.md](<ai4s/programs/sstdpn/research/NEXT_RESEARCH.md>)
- [ai4s/programs/sstdpn/research/STATE.yaml](<ai4s/programs/sstdpn/research/STATE.yaml>)
- [ai4s/prompts/EVALUATION_EVIDENCE.md](<ai4s/prompts/EVALUATION_EVIDENCE.md>)
- [ai4s/prompts/EXTERNAL_REVIEW.md](<ai4s/prompts/EXTERNAL_REVIEW.md>)
- [ai4s/prompts/LEVEL1_RESEARCH_v3.3.md](<ai4s/prompts/LEVEL1_RESEARCH_v3.3.md>)
- [ai4s/prompts/LEVEL2_EXECUTION_v3.3.md](<ai4s/prompts/LEVEL2_EXECUTION_v3.3.md>)
- [ai4s/prompts/MIEEG_AI4S_SKILL_ROUTER.md](<ai4s/prompts/MIEEG_AI4S_SKILL_ROUTER.md>)
- [ai4s/prompts/PROJECT_ADMISSION.md](<ai4s/prompts/PROJECT_ADMISSION.md>)
- [ai4s/prompts/TRANSACTION_RUNTIME.md](<ai4s/prompts/TRANSACTION_RUNTIME.md>)
- [docs/notes/DSAINET_BASELINE_EVIDENCE_MAP_2026-08-26.md](<docs/notes/DSAINET_BASELINE_EVIDENCE_MAP_2026-08-26.md>)
- [docs/notes/MI-EEG_主流数据集规格与实验特性分析_2026-08-13.md](<docs/notes/MI-EEG_主流数据集规格与实验特性分析_2026-08-13.md>)
- [docs/notes/SAFSS_CYCLE_HANDOFF_2026-08-26.md](<docs/notes/SAFSS_CYCLE_HANDOFF_2026-08-26.md>)
- [experiments/UNIFIED_EVALUATION_PROTOCOL.md](<experiments/UNIFIED_EVALUATION_PROTOCOL.md>)
- [refs/paper-cards/dbconformer/DBConformer-note.md](<refs/paper-cards/dbconformer/DBConformer-note.md>)
- [refs/paper-cards/lidsn/LI-DSN-note.md](<refs/paper-cards/lidsn/LI-DSN-note.md>)

## 未公开范围

- 论文PDF、*-paper.md原文读取稿/全文翻译及DOCX继续作为网页项目稳定附件，未纳入公开同步。
- boundary.py有多个同名实例，未确认截图文件身份，未纳入。
- 不自动递归补齐引用；未公开引用见每库SYNC_MANIFEST.json。
- 不上传凭据、SSH配置、数据集、checkpoint、原始预测、机器日志或完整实验目录。

## 在 GPT 项目中使用

讨论当前进度前通过 GitHub 读取本入口与清单，注明版本；读取失败时明确说明，不用历史附件代替当前状态。GitHub 更新不会替换项目附件。
