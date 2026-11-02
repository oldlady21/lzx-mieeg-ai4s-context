# lzx-mieeg-ai4s 讨论资料入口

仓库：https://github.com/oldlady21/lzx-mieeg-ai4s-context
导出时间（UTC）：2026-11-02T15:58:47.386494+00:00
快照身份：`1ae372b8823c9010163119d24e4b69e2499b7a7af4fdfa145b535406e25d4e37`

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
    "source_sha256": "b9483b986e4e766041f2f466553879b2d480e2dd0c5aa21b595d4dac1f32f85a",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dsainet/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-02T15:46:48.540867+00:00",
    "status": "WAITING_REMOTE",
    "paused": false,
    "active_run": {
      "round_id": "ds07-r1-science1-readerfix1",
      "dispatch_status": "REMOTE_ACCEPTED"
    },
    "active_operation": null
  },
  "mvcnet": {
    "source_path": "ai4s/programs/mvcnet/research/STATE.yaml",
    "source_sha256": "9a218d0f058e38c3f09b5d4af20aeebc93278ade2a4b67c80b2ab88ec769656a",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/mvcnet/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-02T15:46:35.823536+00:00",
    "status": "WAITING_REMOTE",
    "paused": false,
    "active_run": {
      "round_id": "mvcnet-xsn-r1-screen-lab10-r1-budget480",
      "dispatch_status": "REMOTE_ACCEPTED"
    },
    "active_operation": null
  },
  "dbconformer": {
    "source_path": "ai4s/programs/dbconformer/research/STATE.yaml",
    "source_sha256": "0bb44c059616773d39f3328d56a13aa44b0c899e3a1c26760d114a3261c6826f",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/dbconformer/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-11-02T15:45:04.891432+00:00",
    "status": "WAITING_REMOTE",
    "paused": false,
    "active_run": {
      "round_id": "dbconformer-sgp-r1-budget1",
      "dispatch_status": "REMOTE_ACCEPTED"
    },
    "active_operation": null
  },
  "sstdpn": {
    "source_path": "ai4s/programs/sstdpn/research/STATE.yaml",
    "source_sha256": "113b75edcf6989d280367b730d108a61f5e7118d53a1078f6e4b16c2bcd9c850",
    "source_public_url": "https://github.com/oldlady21/lzx-mieeg-ai4s-context/blob/main/ai4s/programs/sstdpn/research/STATE.yaml",
    "source_in_this_repository": true,
    "source_updated_at": "2026-10-24T16:28:38.028731+00:00",
    "status": "PAUSED_FOR_HUMAN",
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

先比较各 Program 的研究认识和上方运行摘要；再按讨论对象读取 State、证据索引、L3及历史边界。无需每轮全文加载所有历史。跨 Program 可共享证据与设计约束，暂停、冻结和实验授权仍各自独立。State较大时可用raw链接读取正文，不把网页预览失败等同于未公开。

| Program | 研究认识 | 配置 | State | 证据索引 |
|---|---|---|---|---|
| dsainet | [CURRENT_UNDERSTANDING.md](ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/dsainet/PROGRAM.yaml) | [STATE](ai4s/programs/dsainet/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/dsainet/research/STATE.yaml) | [EVIDENCE_INDEX](ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml) |
| mvcnet | [CURRENT_UNDERSTANDING.md](ai4s/programs/mvcnet/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/mvcnet/PROGRAM.yaml) | [STATE](ai4s/programs/mvcnet/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/mvcnet/research/STATE.yaml) | [EVIDENCE_INDEX](ai4s/programs/mvcnet/research/EVIDENCE_INDEX.yaml) |
| dbconformer | [CURRENT_UNDERSTANDING.md](ai4s/programs/dbconformer/research/CURRENT_UNDERSTANDING.md) | [PROGRAM](ai4s/programs/dbconformer/PROGRAM.yaml) | [STATE](ai4s/programs/dbconformer/research/STATE.yaml) · [raw](https://raw.githubusercontent.com/oldlady21/lzx-mieeg-ai4s-context/main/ai4s/programs/dbconformer/research/STATE.yaml) | [EVIDENCE_INDEX](ai4s/programs/dbconformer/research/EVIDENCE_INDEX.yaml) |
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
- [ai4s/programs/dbconformer/research/STATE.yaml](<ai4s/programs/dbconformer/research/STATE.yaml>)
- [ai4s/programs/dsainet/PROGRAM.yaml](<ai4s/programs/dsainet/PROGRAM.yaml>)
- [ai4s/programs/dsainet/PROJECT_PROMPT_v3.3.md](<ai4s/programs/dsainet/PROJECT_PROMPT_v3.3.md>)
- [ai4s/programs/dsainet/research/CLAIM_LEDGER.yaml](<ai4s/programs/dsainet/research/CLAIM_LEDGER.yaml>)
- [ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md](<ai4s/programs/dsainet/research/CURRENT_UNDERSTANDING.md>)
- [ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml](<ai4s/programs/dsainet/research/EVIDENCE_INDEX.yaml>)
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
