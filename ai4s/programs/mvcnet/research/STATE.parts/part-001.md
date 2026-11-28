# State 阅读分段 1

完整脱敏文件：`ai4s/programs/mvcnet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`feb7cd87e1a257f71a3858e0f98467a7da5f287f9d54ab9f4b174fb0f1e9d7f0`。UTF-8 字节范围：[0, 500000) / 1075674。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
{
  "acm_r1_checkrepair2_closeout": {
    "analysis_result": {
      "path": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/analysis_20261105/RESULT.json",
      "sha256": "17b9576b8da9aa564995a11f5e70095531be27547cd99173bd51131fbd84526c"
    },
    "checks": 72,
    "claim_release": "none",
    "cumulative_spent_hours": 23.823807198007902,
    "decision": "NO_SIGNAL",
    "evidence_id": "AI4S-MVCNET-mvcnet-acm-r1-screen-lab10-checkrepair2",
    "failed_checks": 0,
    "final_cost": {
      "path": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/analysis_20261105/FINAL_COST.json",
      "sha256": "018d5d811dd99a24f6733321911551a402df492ce4ca7d65f8a1c5ad050df6a0"
    },
    "full_payload_local": false,
    "further_training_authorized": false,
    "new_fits": 0,
    "original_anchor_preserved": true,
    "precise_closure": {
      "path": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/analysis_20261105/PRECISE_CLOSURE.json",
      "sha256": "de866a7dd7e7673aa58c1bf7f0237a148bc8621ba18ecfe0a4308518d55b25c0"
    },
    "report": {
      "path": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/analysis_20261105/REPORT.md",
      "sha256": "b24ce1c1830a9c2d77e5309bcac98528115d04e172be3bbe24da7cabc8e53a38"
    },
    "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
    "status": "CLOSED_NO_SIGNAL_EXACT_CONFIGURATION",
    "total_budget_hours": 42
  },
  "active_round": null,
  "active_run": null,
  "active_run_history": [
    {
      "bundle_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-bundle",
      "dispatch_status": "REMOTE_ACCEPTED",
      "estimated_training_hours": 11.639,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 108,
      "recorded_at": "2026-11-23T02:53:06.620753+00:00",
      "round_id": "mvcnet-reflectcvc-001-development-v1",
      "run_prefix": "2026-11-23_mvcnet_reflectcvc_001_lab10",
      "scientific_intake": false,
      "terminal_engineering_status": "FAILED",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-11-23T02:53:37.782715+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-11-23T02:53:41.651587+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-23T02:53:52.074146+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "be191c0a80f5299d49b73a6099dd695ff66ecb300603c60209f30f2ab6fa0df2",
              "execution_seconds": 7.616241931915283,
              "queue_seconds": 1.7761497497558594,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1",
              "transaction_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-tx",
              "waiting_for_resources": false,
              "wall_seconds": 9.392391681671143
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-23T06:21:19.760153+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "be191c0a80f5299d49b73a6099dd695ff66ecb300603c60209f30f2ab6fa0df2",
              "execution_seconds": 9615.973244667053,
              "queue_seconds": 1.7761497497558594,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1",
              "transaction_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-tx",
              "waiting_for_resources": false,
              "wall_seconds": 9617.749394416809
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-bundle",
      "dispatch_status": "REMOTE_ACCEPTED",
      "estimated_training_hours": 12.27,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 108,
      "recorded_at": "2026-11-23T13:34:17.052258+00:00",
      "round_id": "mvcnet-cvcdropout-001-development-v1",
      "run_prefix": "2026-11-23_mvcnet_cvcdropout_001_lab10",
      "scientific_intake": false,
      "terminal_engineering_status": "FAILED",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-11-23T13:35:01.303663+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-11-23T13:35:04.214639+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-23T13:35:34.393137+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "12578c24b50b29c67bd65ac860da7b591ec64c6c4bf32133b92e7dc81acc6066",
              "execution_seconds": 27.27709937095642,
              "queue_seconds": 1.8278789520263672,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-tx",
              "waiting_for_resources": false,
              "wall_seconds": 29.104978322982788
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-24T01:12:36.314480+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "12578c24b50b29c67bd65ac860da7b591ec64c6c4bf32133b92e7dc81acc6066",
              "execution_seconds": 13019.206773042679,
              "queue_seconds": 1.8278789520263672,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-tx",
              "waiting_for_resources": false,
              "wall_seconds": 13021.034651994705
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-bundle",
      "contract": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/repair1/transaction_contract.yaml",
      "contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
      "dispatch_status": "REMOTE_ACCEPTED",
      "dispatch_units": 80,
      "estimated_training_hours": 8.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 108,
      "recorded_at": "2026-11-24T01:15:03.583553+00:00",
      "round_id": "mvcnet-cvcdropout-001-development-v1",
      "run_prefix": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1",
      "scientific_intake": false,
      "terminal_engineering_status": "FAILED",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-11-24T01:15:30.953943+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-11-24T01:15:34.696044+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-24T01:15:56.653405+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
              "execution_seconds": 20.099177598953247,
              "queue_seconds": 0.0,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 20.099177598953247
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-24T01:19:29.847561+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
              "execution_seconds": 178.94854950904846,
              "queue_seconds": 54.339439153671265,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-tx",
              "waiting_for_resources": true,
              "wall_seconds": 233.28798866271973
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-24T04:58:39.569635+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
              "execution_seconds": 268.5701367855072,
              "queue_seconds": 13114.757668495178,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-tx",
              "waiting_for_resources": true,
              "wall_seconds": 13383.327805280685
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-11-24T12:27:15.806540+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "science",
            "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
              "execution_seconds": 10152.82060432434,
              "queue_seconds": 16361.61447429657,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 26514.43507862091
            }
          }
        }
      ]
    }
  ],
  "anchor": {
    "card": "ai4s/archive/programs/mvcnet/research/VCN_P1_ANCHOR.md",
    "module_id": "VCN-P1-v0.1",
    "status": "scoped_supporting_evidence"
  },
  "archived_campaigns": [
    {
      "campaign_id": "pre-campaign-ai4s-exploration",
      "closed_at": "2026-08-31T16:04:41.300962+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-r01-vcn-p1-new-seed-stability-v0.1"
      },
      "closing_round": "mvcnet-r01-vcn-p1-new-seed-stability-v0.1",
      "closing_run": {
        "intake_path": "results/logs/remote/2026-08-30_ai4s_mvcnet_r01_seed56_b0p1b-full-w1",
        "run_id": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1b-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-08-30T16:59:12.6084289+00:00"
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "user_authorized_three_lab10_rounds_after_verified_B0_and_P1_preflight_fixed_1024MiB_reserve"
    },
    {
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "closed_at": "2026-09-02T18:30:57.258415+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l7-seed1920-fixed1024-v1.0"
      },
      "closing_round": "mvcnet-lab10-l7-seed1920-fixed1024-v1.0",
      "closing_run": {
        "intake_path": "results/logs/remote/2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_fixed1024_r1-full-w1",
        "run_id": "2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_fixed1024_r1-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-02T12:11:52.232415+00:00"
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "用户于2026-09-03授权：以SCVA-CVC为首个模块，最多三轮、总预算30小时；仅完成verified intake后的SCREEN_POSITIVE可继续同模块，完成verified intake后的NO_SIGNAL可在剩余轮次内转入一个独立候选模块；INVALID、BLOCKED_INTAKE、REVIEW_UNAVAILABLE或未完成验收不得转向或重投。VCN-P1的stem、BN路由、raw-only推理和种子饱和边界冻结。"
    },
    {
      "campaign_id": "mvcnet-scva-autonomous-3r-20260903",
      "closed_at": "2026-09-05T16:51:33.679615+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2"
      },
      "closing_round": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
      "closing_run": {
        "intake_path": "results/logs/remote/2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
        "run_id": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-03T11:34:40.725862+00:00"
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "用户2026-09-06明确授权建立TAPR首轮campaign，预算10小时，本地小规模smoke并准备Lab10手动上传脚本和命令；不授权代理远端上传或启动；保留历史关闭边界与seed累计。"
    },
    {
      "campaign_id": "mvcnet-tapr-v0.1-20260906",
      "closed_at": "2026-09-07T06:07:39.490626+00:00",
      "closing_decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "mvcnet-tapr-v0.1-screen-lab10-r1"
      },
      "closing_round": "mvcnet-tapr-v0.1-screen-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "c7fab3f9dc8f664e0a3d7f7b2ceee0798932a28d1f08ffc62cc5a7bd27d5d065",
        "contract_sha256": "87d7eecf49066a5d37be3fb2ec895c86c549941977d8599c05679fd825233253",
        "intake_path": "results/logs/remote/2026-09-07_mvcnet_tapr_lab10_r5-full-w1",
        "pointer_corrected_at": "2026-09-07T06:12:49.977039+00:00",
        "run_id": "2026-09-07_mvcnet_tapr_lab10_r5-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-tapr-tx-20260907-r5",
        "verification_record": "ai4s/programs/mvcnet/research/tapr_r4_r5_analysis/r5_verified_intake.json",
        "verified": true
      },
      "closing_run_before_pointer_correction": {
        "intake_path": "results/logs/remote/2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
        "run_id": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-03T11:34:40.725862+00:00"
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "用户明确选择TCRD新假设并授权1阶段10小时排除资源排队、Lab10排除GPU2、准备上传启动回拉分析；保留TAPR恢复证据与provisional审查限制，不救援lag或rank"
    },
    {
      "campaign_id": "mvcnet-tcrd-v0.1-20260907",
      "closed_at": "2026-09-07T11:02:52.900877+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-tcrd-v0.1-screen-lab10-r1"
      },
      "closing_round": "mvcnet-tcrd-v0.1-screen-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "90c1e2033153cf73f41e66d4c67751c50b5e9f90bd20aaaa57346e3d6441b26b",
        "contract_sha256": "15d17098581c7ebfd4d2e34a47978d52ce94b1734d223a674d1b4530d6e00b6a",
        "intake_path": "results/logs/remote/2026-09-07_mvcnet_tcrd_lab10_r1-full-w1",
        "run_id": "2026-09-07_mvcnet_tcrd_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-tcrd-tx-20260907-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户确认VOGR新campaign一科学阶段十小时排除纯资源排队，Lab10 GPU0-9，授权准备上传启动回拉分析；首阶段源数据梯度诊断，保留TCRD关闭边界"
    },
    {
      "campaign_id": "mvcnet-vogr-d0-20260907",
      "closed_at": "2026-09-07T17:55:28.269548+00:00",
      "closing_decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "source-only diagnostic observation; no performance screen or paper claim",
        "round_id": "mvcnet-vogr-d0-diagnostic-lab10-r1"
      },
      "closing_round": "mvcnet-vogr-d0-diagnostic-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "8b4fc3ea2862e25ebf7b4e40811ee590997a43dfa78d48d8bcdfdf6b231caa7d",
        "contract_sha256": "467c69f711dbec9b55b39eab316c720a17f43b1a42b6ab6f1e6fcf5e7b60ef9a",
        "intake_path": "results/logs/remote/2026-09-07_mvcnet_vogr_lab10_r3-full-w1",
        "run_id": "2026-09-07_mvcnet_vogr_lab10_r3-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-vogr-tx-20260907-r3",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized starting uploaded OCST r1; one stage, exclude pure resource queue, Lab10 excludes GPU2, preserve frozen 90+5 tasks and one technical recovery"
    },
    {
      "campaign_id": "mvcnet-ocst-v0.1-20260908",
      "closed_at": "2026-09-09T06:39:20.206498+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1-repair2"
      },
      "closing_round": "mvcnet-ocst-v0.1-screen-lab10-r1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "9e5cb2619ce77e060ce6c33c0b92782d38885c58915bfd265ba420f7a9cfed18",
        "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
        "intake_path": "results/logs/remote/2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
        "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-ocst-tx-20260908-r3",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized WCR-D0 upload then start; one source-only stage, 10 actual hours excluding pure resource wait, 108 readout fits, no backbone training"
    },
    {
      "campaign_id": "mvcnet-wcr-d0-20260909",
      "closed_at": "2026-09-09T10:12:15.299667+00:00",
      "closing_decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "source-only readout diagnosis; no performance screen or paper claim",
        "round_id": "mvcnet-wcr-d0-diagnostic-lab10-r1"
      },
      "closing_round": "mvcnet-wcr-d0-diagnostic-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "0250b3d6566a2c42b85447a6ac7e2aca76fa0737aa48ad18a46aed9ba922ea9a",
        "contract_sha256": "ca069ca67ab77643722a7b2af2d9bb8305b56cd48fb285a7b6afe093d8d20ca6",
        "intake_path": "results/logs/remote/2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
        "run_id": "2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-wcr-d0-tx-20260909-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized SRTD-D0 preparation upload launch fetch intake analysis; one diagnostic stage; resource waiting excluded"
    },
    {
      "campaign_id": "mvcnet-srtd-d0-20260909",
      "closed_at": "2026-09-09T16:11:22.944187+00:00",
      "closing_decision": {
        "decision": "DIAGNOSTIC_SUPPORT",
        "reason": "source-only readout transfer diagnosis; no outer-target evaluation or paper claim",
        "round_id": "mvcnet-srtd-d0-diagnostic-lab10-r1"
      },
      "closing_round": "mvcnet-srtd-d0-diagnostic-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "dd60d9ebd8ec772ce292f914e051cb5105424470dd05cc7e8fe6185e10daec97",
        "contract_sha256": "fda94a78401b1bfb2b9c2c0738569ce51d2762ddd987728d1cf2589482c63014",
        "intake_path": "results/logs/remote/2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
        "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-srtd-d0-tx-20260909-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized SRTD-T1 fixed donor calibration transfer, preparation upload launch fetch intake analysis; one stage, no training or fitting"
    },
    {
      "campaign_id": "mvcnet-srtd-t1-20260910",
      "closed_at": "2026-09-09T18:35:13.783152+00:00",
      "closing_decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "frozen calibration transfer diagnosis; target evaluation only, no backbone training or paper claim",
        "round_id": "mvcnet-srtd-t1-diagnostic-lab10-r2"
      },
      "closing_round": "mvcnet-srtd-t1-diagnostic-lab10-r2",
      "closing_run": {
        "artifact_manifest_sha256": "965850cd247cd4fcbc773e23c1e7c8af2b93fd4eb82ea7c21b7bac48939be516",
        "contract_sha256": "83df4a6ee95a9e2089e93a22b4e80f9e1d24fa88db5823d2dd7dfc20e3594915",
        "intake_path": "results/logs/remote/2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
        "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-srtd-t1-tx-20260910-r2",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized SRTD-C1 preparation upload launch fetch intake analysis; one source-only diagnostic stage, zero backbone training; resource wait excluded"
    },
    {
      "campaign_id": "mvcnet-srtd-c1-20260910",
      "closed_at": "2026-09-10T05:07:32.746436+00:00",
      "closing_decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "source-only conditional readout diagnosis; no backbone training or paper claim",
        "round_id": "mvcnet-srtd-c1-diagnostic-lab10-r1"
      },
      "closing_round": "mvcnet-srtd-c1-diagnostic-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "ca8c4d1f6b9fc62d0a19d15673d9e69b8806fd256427389d76f7d9034abfae4b",
        "contract_sha256": "ae511d3a9a1a64a73aa5f26ae758bc45821dc292b42621e692cf1cfb9d0cf865",
        "intake_path": "results/logs/remote/2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
        "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-srtd-c1-tx-20260910-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized 54-unit source factorized head screen, prepare upload launch fetch intake analysis; exclude resource wait; Lab10 direct GPU0-9 shared; maximum two engineering repairs"
    },
    {
      "campaign_id": "mvcnet-source-factorized-head-20260910",
      "closed_at": "2026-09-10T13:50:04.516087+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "frozen S0/P0/N0 screen did not pass all paired gates; no_paper_claim",
        "round_id": "mvcnet-source-factorized-head-screen-lab10-r2"
      },
      "closing_round": "mvcnet-source-factorized-head-screen-lab10-r2",
      "closing_run": {
        "artifact_manifest_sha256": "70c09f03f9ac9fce4900727b176e5dbe61016fbed2900d7107ba7bb64e507973",
        "contract_sha256": "706d2021dd66ebb9477b144b39aa09ccddf4788f878bf6921110da72428ee556",
        "intake_path": "results/logs/remote/2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
        "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-sfh-tx-20260910-r2",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized energy complementarity S0/C0/P0 54 units one stage ten execution hours excluding resource wait; all Lab10 GPUs memory-only admission; prepare upload launch fetch analyze; SFH exact instance closed"
    },
    {
      "campaign_id": "mvcnet-energy-complementarity-20260910",
      "closed_at": "2026-09-11T14:48:29.561306+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "frozen S0/C0/P0 screen did not pass all main gates; C0-S0 cannot promote; no_paper_claim",
        "round_id": "mvcnet-energy-complementarity-screen-lab10-r3"
      },
      "closing_round": "mvcnet-energy-complementarity-screen-lab10-r3",
      "closing_run": {
        "artifact_manifest_sha256": "0e012778c1cf7b518239b69820aab3020a928f039835ed37232852713c1a2547",
        "contract_sha256": "8e682f3e2cb6e6beea2a4436cb3e04fe425ce05984c8cc28908d09334f2b7d57",
        "intake_path": "results/logs/remote/2026-09-11_mvcnet_energy_lab10_r3-full-w1",
        "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-energy-tx-20260911-r3",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested upload after reviewing 18-trajectory six-source D0 proposal; preparation and upload only; launch not authorized; QEP remains closed"
    },
    {
      "campaign_id": "mvcnet-source-selection-transfer-d0-20260911",
      "closed_at": "2026-09-14T16:57:47.228229+00:00",
      "closing_decision": {
        "aggregate": {
          "endpoint": {
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -2.8564453125,
              -2.63671875,
              -2.8483072916666665,
              -2.5553385416666665,
              -2.6204427083333335,
              -2.7506510416666665,
              -1.7496744791666667,
              -2.8483072916666665,
              -2.5065104166666665
            ],
            "minimum_direction_seed_gain_pp": -14.84375,
            "overall_accuracy_gain_pp": -2.5969328703703702,
            "overall_ce_gain": 0.031767697118924555,
            "per_subject_seed": [
              {
                "accuracy_gain_pp": -2.4739583333333335,
                "ce_gain": -0.0566773529876311,
                "seed": 35,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 1.4322916666666667,
                "ce_gain": -0.051770274722436005,
                "seed": 36,
                "subject": 0
              },
              {
                "accuracy_gain_pp": -1.8229166666666667,
                "ce_gain": -0.01549290209133436,
                "seed": 35,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -2.734375,
                "ce_gain": -0.018711175718011175,
                "seed": 36,
                "subject": 1
              },
              {
                "accuracy_gain_pp": 2.0833333333333335,
                "ce_gain": 0.0062713582933244805,
                "seed": 35,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -3.2552083333333335,
                "ce_gain": -0.04760968196452925,
                "seed": 36,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -2.34375,
                "ce_gain": -0.061895373116734875,
                "seed": 35,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -3.515625,
                "ce_gain": -0.08657977209028889,
                "seed": 36,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -1.5625,
                "ce_gain": 0.08233542751600209,
                "seed": 35,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -3.255208333333333,
                "ce_gain": 0.15575661280014652,
                "seed": 36,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -0.26041666666666663,
                "ce_gain": 0.19841027621884,
                "seed": 35,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -2.4739583333333335,
                "ce_gain": 0.6814662109295778,
                "seed": 36,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -8.59375,
                "ce_gain": -0.11005384412237029,
                "seed": 35,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -10.15625,
                "ce_gain": -0.1287578805091555,
                "seed": 36,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -1.5625,
                "ce_gain": -0.047869942814525335,
                "seed": 35,
                "subject": 7
              },
              {
                "accuracy_gain_pp": 0.390625,
                "ce_gain": -0.0008152742957301395,
                "seed": 36,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -5.989583333333334,
                "ce_gain": 0.06703536613211669,
                "seed": 35,
                "subject": 8
              },
              {
                "accuracy_gain_pp": -0.6510416666666666,
                "ce_gain": 0.006776770683381339,
                "seed": 36,
                "subject": 8
              }
            ],
            "seed_accuracy_gains_pp": [
              -2.5028935185185186,
              -2.6909722222222223
            ],
            "subject_accuracy_gains_pp": [
              -0.5208333333333334,
              -2.2786458333333335,
              -0.5859375,
              -2.9296875,
              -2.4088541666666665,
              -1.3671875,
              -9.375,
              -0.5859375,
              -3.3203125000000004
            ]
          },
          "independent_subjects": 9,
          "main": {
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -2.490234375,
              -2.5390625,
              -2.44140625,
              -2.1321614583333335,
              -2.0589192708333335,
              -2.2542317708333335,
              -1.2858072916666665,
              -2.5309244791666665,
              -2.189127604166667
            ],
            "minimum_direction_seed_gain_pp": -15.364583333333334,
            "overall_accuracy_gain_pp": -2.2135416666666665,
            "overall_ce_gain": 0.027291237006719364,
            "per_subject_seed": [
              {
                "accuracy_gain_pp": -0.3906249999999998,
                "ce_gain": -0.05784724225998211,
                "seed": 35,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 0.390625,
                "ce_gain": -0.0744819784500308,
                "seed": 36,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 2.213541666666667,
                "ce_gain": 0.02560500809365429,
                "seed": 35,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -1.4322916666666665,
                "ce_gain": -0.008694865536459817,
                "seed": 36,
                "subject": 1
              },
              {
                "accuracy_gain_pp": 4.036458333333334,
                "ce_gain": 0.03445243622826405,
                "seed": 35,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -4.817708333333333,
                "ce_gain": -0.058271770671954604,
                "seed": 36,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -2.213541666666667,
                "ce_gain": -0.06575526526334619,
                "seed": 35,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -3.515625,
                "ce_gain": -0.07629402657446471,
                "seed": 36,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -4.947916666666667,
                "ce_gain": 0.020132503937581925,
                "seed": 35,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -1.953125,
                "ce_gain": 0.0822841426944112,
                "seed": 36,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -2.2135416666666665,
                "ce_gain": 0.20098646829851807,
                "seed": 35,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -1.5625,
                "ce_gain": 0.6605150736566773,
                "seed": 36,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -8.854166666666668,
                "ce_gain": -0.11617185294917892,
                "seed": 35,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -10.416666666666668,
                "ce_gain": -0.13661241910160143,
                "seed": 36,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -0.5208333333333333,
                "ce_gain": -0.03819831634220677,
                "seed": 35,
                "subject": 7
              },
              {
                "accuracy_gain_pp": 1.171875,
                "ce_gain": 0.0033758646611127263,
                "seed": 36,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -4.817708333333333,
                "ce_gain": 0.09116168057992502,
                "seed": 35,
                "subject": 8
              },
              {
                "accuracy_gain_pp": 0.0,
                "ce_gain": 0.005056825120029362,
                "seed": 36,
                "subject": 8
              }
            ],
            "seed_accuracy_gains_pp": [
              -1.9675925925925926,
              -2.459490740740741
            ],
            "subject_accuracy_gains_pp": [
              1.1102230246251565e-16,
              0.3906250000000002,
              -0.39062499999999956,
              -2.8645833333333335,
              -3.4505208333333335,
              -1.8880208333333333,
              -9.635416666666668,
              0.32552083333333337,
              -2.4088541666666665
            ]
          },
          "seen_vs_last100": {
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -0.36621093749999994,
              -0.09765625000000001,
              -0.40690104166666663,
              -0.4231770833333333,
              -0.5615234375,
              -0.4964192708333333,
              -0.4638671875,
              -0.31738281249999994,
              -0.31738281249999994
            ],
            "minimum_direction_seed_gain_pp": -5.46875,
            "overall_accuracy_gain_pp": -0.38339120370370366,
            "overall_ce_gain": 0.004476460112205193,
            "per_subject_seed": [
              {
                "accuracy_gain_pp": -2.0833333333333335,
                "ce_gain": 0.0011698892723510101,
                "seed": 35,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 1.0416666666666667,
                "ce_gain": 0.02271170372759479,
                "seed": 36,
                "subject": 0
              },
              {
                "accuracy_gain_pp": -4.036458333333333,
                "ce_gain": -0.04109791018498865,
                "seed": 35,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -1.3020833333333333,
                "ce_gain": -0.010016310181551358,
                "seed": 36,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -1.953125,
                "ce_gain": -0.02818107793493957,
                "seed": 35,
                "subject": 2
              },
              {
                "accuracy_gain_pp": 1.5625,
                "ce_gain": 0.010662088707425355,
                "seed": 36,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -0.13020833333333334,
                "ce_gain": 0.00385989214661131,
                "seed": 35,
                "subject": 3
              },
              {
                "accuracy_gain_pp": 0.0,
                "ce_gain": -0.010285745515824174,
                "seed": 36,
                "subject": 3
              },
              {
                "accuracy_gain_pp": 3.385416666666667,
                "ce_gain": 0.062202923578420166,
                "seed": 35,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -1.3020833333333335,
                "ce_gain": 0.07347247010573532,
                "seed": 36,
                "subject": 4
              },
              {
                "accuracy_gain_pp": 1.953125,
                "ce_gain": -0.0025761920796780746,
                "seed": 35,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -0.9114583333333334,
                "ce_gain": 0.020951137272900544,
                "seed": 36,
                "subject": 5
              },
              {
                "accuracy_gain_pp": 0.26041666666666674,
                "ce_gain": 0.00611800882680863,
                "seed": 35,
                "subject": 6
              },
              {
                "accuracy_gain_pp": 0.26041666666666663,
                "ce_gain": 0.007854538592445948,
                "seed": 36,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -1.0416666666666667,
                "ce_gain": -0.009671626472318562,
                "seed": 35,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -0.78125,
                "ce_gain": -0.004191138956842866,
                "seed": 36,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -1.171875,
                "ce_gain": -0.024126314447808328,
                "seed": 35,
                "subject": 8
              },
              {
                "accuracy_gain_pp": -0.6510416666666667,
                "ce_gain": 0.0017199455633519767,
                "seed": 36,
                "subject": 8
              }
            ],
            "seed_accuracy_gains_pp": [
              -0.5353009259259259,
              -0.2314814814814815
            ],
            "subject_accuracy_gains_pp": [
              -0.5208333333333334,
              -2.669270833333333,
              -0.1953125,
              -0.06510416666666667,
              1.0416666666666667,
              0.5208333333333333,
              0.2604166666666667,
              -0.9114583333333334,
              -0.9114583333333334
            ]
          }
        },
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "complete frozen six-source selection-transfer diagnostic did not pass the fixed main gate",
        "round_id": "mvcnet-source-selection-transfer-d0-lab10-r8"
      },
      "closing_round": "mvcnet-source-selection-transfer-d0-lab10-r8",
      "closing_run": {
        "artifact_manifest_sha256": "80e5ed7587fd7bca995fe3d3153af73ca56bcc47debe85d712abb5383a18cee9",
        "contract_sha256": "ed8a7c71def64770486b2027a1af12d08b74f1c9fe3cf48d4d5911f16fdff21e",
        "intake_path": "results/logs/remote/2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
        "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-sstd0-tx-20260914-r8",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized shared-subnetwork 54 units, one stage, 10h excluding resource wait; prepare upload launch fetch analyze"
    },
    {
      "campaign_id": "mvcnet-shared-subnetwork-20260915",
      "closed_at": "2026-09-15T12:55:54.810129+00:00",
      "closing_decision": {
        "aggregate": {
          "N0-S0": {
            "gates_passed": false,
            "loo_gains_pp": [
              0.6944444444444444,
              0.7269965277777778,
              0.4014756944444444,
              0.5967881944444444,
              0.3255208333333333,
              0.7052951388888888,
              0.6510416666666666,
              0.11935763888888891,
              1.1610243055555556
            ],
            "mean_accuracy_gain_pp": 0.5979938271604939,
            "mean_ce_gain": 0.03157671338227008,
            "minimum_pair_gain_pp": -8.159722222222221,
            "seed_gains_pp": [
              0.0,
              1.1959876543209877
            ],
            "subject_gains_pp": [
              -0.17361111111111116,
              -0.4340277777777779,
              2.170138888888889,
              0.607638888888889,
              2.7777777777777777,
              -0.2604166666666665,
              0.17361111111111094,
              4.427083333333333,
              -3.9062499999999996
            ]
          },
          "P0-N0": {
            "gates_passed": false,
            "loo_gains_pp": [
              -1.07421875,
              -1.0416666666666665,
              -0.9982638888888888,
              -0.9982638888888888,
              -0.9006076388888888,
              -1.1935763888888888,
              -1.1610243055555556,
              -0.6293402777777777,
              -1.3780381944444444
            ],
            "mean_accuracy_gain_pp": -1.0416666666666667,
            "mean_ce_gain": -0.0011569742718150046,
            "minimum_pair_gain_pp": -5.381944444444445,
            "seed_gains_pp": [
              -0.7523148148148149,
              -1.3310185185185186
            ],
            "subject_gains_pp": [
              -0.7812499999999999,
              -1.0416666666666667,
              -1.3888888888888888,
              -1.3888888888888888,
              -2.170138888888889,
              0.17361111111111105,
              -0.08680555555555558,
              -4.340277777777778,
              1.6493055555555558
            ]
          },
          "P0-S0": {
            "gates_passed": false,
            "loo_gains_pp": [
              -0.3797743055555556,
              -0.31467013888888895,
              -0.5967881944444444,
              -0.4014756944444445,
              -0.5750868055555556,
              -0.48828125000000006,
              -0.509982638888889,
              -0.509982638888889,
              -0.2170138888888889
            ],
            "mean_accuracy_gain_pp": -0.44367283950617287,
            "mean_ce_gain": 0.030419739110455077,
            "minimum_pair_gain_pp": -5.902777777777778,
            "seed_gains_pp": [
              -0.7523148148148149,
              -0.13503086419753085
            ],
            "subject_gains_pp": [
              -0.9548611111111112,
              -1.4756944444444444,
              0.78125,
              -0.7812500000000001,
              0.6076388888888888,
              -0.08680555555555547,
              0.08680555555555558,
              0.08680555555555558,
              -2.2569444444444446
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "round_id": "mvcnet-shared-subnetwork-screen-lab10-r3"
      },
      "closing_round": "mvcnet-shared-subnetwork-screen-lab10-r3",
      "closing_run": {
        "artifact_manifest_sha256": "58c08e4b6ec5f40ee3f4aff8dd1745467282bb675ea62b730a123892c51cd8d2",
        "contract_sha256": "4a390b9306d39bf8aa5021cfa4e0f812ec866a2f05bb3e96f96f13d19d79d303",
        "intake_path": "results/logs/remote/2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
        "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-shared-subnetwork-tx-20260915-r3",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized 72 paired factorial training +72 checks; fixed CVC CMC on-off contribution diagnostic; queues and verified failure downtime excluded"
    },
    {
      "campaign_id": "mvcnet-contrastive-factorial-20260915",
      "closed_at": "2026-09-17T05:12:24.079124+00:00",
      "closing_decision": {
        "aggregate": {
          "D01-D00": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.7426697530864198,
              0.7040895061728395
            ],
            "bootstrap_ce_gain_ci": [
              -0.017615773511917152,
              0.094077370563808
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": true,
            "ci_level": 95.0,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.02170138888888886,
              -0.17361111111111113,
              0.0759548611111111,
              -3.469446951953614e-17,
              -0.17361111111111113,
              -0.3363715277777778,
              -0.09765625000000003,
              0.043402777777777755,
              0.11935763888888887
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": -0.05787037037037039,
            "mean_ce_gain": 0.026108075162186925,
            "minimum_pair_gain_pp": -1.7361111111111112,
            "seed_accuracy_gains_pp": [
              -0.5594135802469136,
              0.4436728395061728
            ],
            "subject_accuracy_gains_pp": [
              -0.6944444444444444,
              0.8680555555555555,
              -1.1284722222222223,
              -0.5208333333333333,
              0.8680555555555555,
              2.170138888888889,
              0.2604166666666667,
              -0.8680555555555556,
              -1.4756944444444444
            ]
          },
          "D10-D00": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.935570987654321,
              0.6462191358024693
            ],
            "bootstrap_ce_gain_ci": [
              -0.03842189869068714,
              0.015229840241639519
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": false,
            "ci_level": 95.0,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -0.2061631944444444,
              -0.16276041666666663,
              -0.21701388888888884,
              -0.5642361111111112,
              -0.3255208333333333,
              -0.21701388888888884,
              5.204170427930421e-17,
              -0.07595486111111108,
              -0.14105902777777773
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": -0.21219135802469133,
            "mean_ce_gain": -0.010222560427125334,
            "minimum_pair_gain_pp": -3.8194444444444446,
            "seed_accuracy_gains_pp": [
              -0.1350308641975308,
              -0.28935185185185186
            ],
            "subject_accuracy_gains_pp": [
              -0.2604166666666667,
              -0.6076388888888888,
              -0.17361111111111116,
              2.604166666666667,
              0.6944444444444445,
              -0.17361111111111113,
              -1.9097222222222223,
              -1.3020833333333333,
              -0.78125
            ]
          },
          "D11-D00": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.1091820987654322,
              1.4371141975308641
            ],
            "bootstrap_ce_gain_ci": [
              -0.07475953884083085,
              0.0677195831730413
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": false,
            "ci_level": 98.33333333333333,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.10850694444444448,
              0.0759548611111111,
              0.6076388888888888,
              0.1736111111111111,
              0.24956597222222224,
              0.09765625,
              0.4014756944444444,
              0.1736111111111111,
              0.6293402777777778
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.2797067901234568,
            "mean_ce_gain": 0.00027058503454198873,
            "minimum_pair_gain_pp": -6.25,
            "seed_accuracy_gains_pp": [
              0.38580246913580246,
              0.17361111111111116
            ],
            "subject_accuracy_gains_pp": [
              1.6493055555555554,
              1.9097222222222223,
              -2.34375,
              1.1284722222222223,
              0.5208333333333333,
              1.7361111111111112,
              -0.6944444444444444,
              1.1284722222222223,
              -2.517361111111111
            ]
          },
          "D11-D01": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.6688046553497943,
              1.4018293467078236
            ],
            "bootstrap_ce_gain_ci": [
              -0.08021215276526114,
              0.017450475300456826
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": true,
            "ci_level": 98.33333333333333,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.08680555555555551,
              0.2495659722222222,
              0.5316840277777777,
              0.1736111111111111,
              0.42317708333333326,
              0.43402777777777773,
              0.4991319444444444,
              0.13020833333333331,
              0.5099826388888888
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.33757716049382713,
            "mean_ce_gain": -0.025837490127644937,
            "minimum_pair_gain_pp": -4.861111111111111,
            "seed_accuracy_gains_pp": [
              0.945216049382716,
              -0.2700617283950617
            ],
            "subject_accuracy_gains_pp": [
              2.34375,
              1.0416666666666665,
              -1.2152777777777777,
              1.6493055555555554,
              -0.3472222222222221,
              -0.4340277777777778,
              -0.9548611111111112,
              1.9965277777777777,
              -1.0416666666666667
            ]
          },
          "D11-D10": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.954861111111111,
              1.7939814814814816
            ],
            "bootstrap_ce_gain_ci": [
              -0.035860211079001586,
              0.05702133568372893
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": false,
            "ci_level": 98.33333333333333,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.31467013888888895,
              0.23871527777777785,
              0.8246527777777779,
              0.7378472222222223,
              0.5750868055555556,
              0.31467013888888895,
              0.40147569444444453,
              0.24956597222222232,
              0.7703993055555556
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.4918981481481482,
            "mean_ce_gain": 0.010493145461667321,
            "minimum_pair_gain_pp": -5.208333333333333,
            "seed_accuracy_gains_pp": [
              0.5208333333333334,
              0.462962962962963
            ],
            "subject_accuracy_gains_pp": [
              1.9097222222222223,
              2.517361111111111,
              -2.170138888888889,
              -1.4756944444444442,
              -0.17361111111111094,
              1.9097222222222223,
              1.215277777777778,
              2.4305555555555554,
              -1.7361111111111112
            ]
          },
          "interaction": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.42438271604938266,
              1.6010802469135803
            ],
            "bootstrap_ce_gain_ci": [
              -0.05828274247145702,
              0.0210623603943979
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": true,
            "ci_level": 95.0,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.29296875,
              0.4123263888888889,
              0.7486979166666666,
              0.7378472222222222,
              0.7486979166666666,
              0.6510416666666666,
              0.4991319444444444,
              0.20616319444444442,
              0.6510416666666666
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.5497685185185185,
            "mean_ce_gain": -0.01561492970051961,
            "minimum_pair_gain_pp": -5.034722222222222,
            "seed_accuracy_gains_pp": [
              1.0802469135802468,
              0.01929012345679014
            ],
            "subject_accuracy_gains_pp": [
              2.6041666666666665,
              1.6493055555555554,
              -1.0416666666666665,
              -0.9548611111111109,
              -1.0416666666666667,
              -0.2604166666666667,
              0.9548611111111112,
              3.298611111111111,
              -0.2604166666666667
            ]
          }
        },
        "contribution_map": {
          "D01-D00": "none",
          "D10-D00": "none",
          "D11-D00": "none",
          "D11-D01": "none",
          "D11-D10": "none",
          "interaction": "none"
        },
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "round_id": "mvcnet-contrastive-factorial-diagnostic-lab10-r3"
      },
      "closing_round": "mvcnet-contrastive-factorial-diagnostic-lab10-r3",
      "closing_run": {
        "artifact_manifest_sha256": "eca0c136bdea92106a1ec58189c561fb429e1da27e85a79dad32588d34cf4126",
        "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
        "intake_path": "results/logs/remote/2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
        "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User confirmed one 12h stage of direct cross-objective collision screening; 54 fresh paired training units and 54 sealed checks, all Lab10 GPUs memory-only, prepare upload launch fetch intake analyze; queue excluded; prior factorial insufficient result preserved."
    },
    {
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "closed_at": "2026-09-20T09:27:09.255542+00:00",
      "closing_decision": {
        "aggregate": {
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -3.423996913580247,
              0.14467592592592593
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260917,
            "ce_gain_nonnegative": false,
            "ci_level": 95.0,
            "direction": "descriptive",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -1.26953125,
              -1.3780381944444444,
              -1.5082465277777777,
              -1.3020833333333333,
              -1.3237847222222223,
              -1.2261284722222223,
              -1.4865451388888888,
              -1.3888888888888888,
              -0.22786458333333331
            ],
            "mean_accuracy_gain_pp": -1.2345679012345678,
            "mean_ce_gain": -0.021747564294052793,
            "seed_accuracy_gains_pp": [
              -1.7939814814814816,
              -0.6751543209876544
            ],
            "subject_accuracy_gains_pp": [
              -0.954861111111111,
              -0.08680555555555558,
              0.954861111111111,
              -0.6944444444444444,
              -0.5208333333333333,
              -1.3020833333333333,
              0.78125,
              0.0,
              -9.288194444444445
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.6847993827160493,
              3.607253086419753
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260917,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              1.0308159722222223,
              1.4539930555555556,
              1.0633680555555556,
              1.0308159722222223,
              0.9765625,
              1.2369791666666667,
              1.1827256944444444,
              1.2478298611111112,
              0.06510416666666671
            ],
            "mean_accuracy_gain_pp": 1.0320216049382716,
            "mean_ce_gain": -0.030486518824137967,
            "seed_accuracy_gains_pp": [
              1.6396604938271604,
              0.42438271604938277
            ],
            "subject_accuracy_gains_pp": [
              1.0416666666666667,
              -2.34375,
              0.78125,
              1.0416666666666667,
              1.4756944444444444,
              -0.6076388888888888,
              -0.17361111111111094,
              -0.6944444444444444,
              8.76736111111111
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.1670524691358024,
              0.6944444444444445
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260917,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.23871527777777773,
              0.07595486111111113,
              -0.4448784722222222,
              -0.27126736111111105,
              -0.3472222222222222,
              0.010850694444444503,
              -0.3038194444444444,
              -0.14105902777777773,
              -0.16276041666666663
            ],
            "mean_accuracy_gain_pp": -0.20254629629629625,
            "mean_ce_gain": -0.052234083118190756,
            "seed_accuracy_gains_pp": [
              -0.15432098765432098,
              -0.2507716049382716
            ],
            "subject_accuracy_gains_pp": [
              0.08680555555555558,
              -2.4305555555555554,
              1.7361111111111112,
              0.3472222222222223,
              0.9548611111111112,
              -1.9097222222222223,
              0.6076388888888888,
              -0.6944444444444444,
              -0.5208333333333333
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "interpretation_boundary": "selection-used discovery only; no default protocol or paper claim",
        "round_id": "mvcnet-cross-objective-collision-screen-lab10-r8"
      },
      "closing_round": "mvcnet-cross-objective-collision-screen-lab10-r8",
      "closing_run": {
        "artifact_manifest_sha256": "09361ad755c752f77b130b07c0f9fb8c9cc495eed88b62939b44dabd9116e995",
        "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
        "intake_path": "results/logs/remote/2026-09-17_mvcnet_coc_lab10_r8-full-w1",
        "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户2026-09-20选择Foundry MV-03并自动授权预算及启动；独立1阶段72train72check，24h加一次必要8h恢复上限，见dual_atom/AUTHORIZATION.md"
    },
    {
      "campaign_id": "mvcnet-dual-atom-20260920",
      "closed_at": "2026-09-24T13:27:06.643899+00:00",
      "closing_decision": {
        "aggregate": {
          "C0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.8584104938271605,
              1.707175925925926
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.4231770833333333,
              0.5750868055555556,
              0.7703993055555556,
              0.4123263888888889,
              0.3146701388888889,
              0.5099826388888888,
              0.14105902777777773,
              0.8138020833333334,
              0.20616319444444442
            ],
            "mean_accuracy_gain_pp": 0.46296296296296297,
            "mean_ce_gain": 0.011149484206088764,
            "seed_accuracy_gains_pp": [
              0.9645061728395061,
              -0.03858024691358023
            ],
            "subject_accuracy_gains_pp": [
              0.78125,
              -0.43402777777777773,
              -1.996527777777778,
              0.8680555555555556,
              1.6493055555555554,
              0.08680555555555547,
              3.0381944444444446,
              -2.34375,
              2.517361111111111
            ]
          },
          "N0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.4564043209876543,
              0.5883487654320987
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.4448784722222222,
              -0.6510416666666666,
              -0.4774305555555555,
              -0.4774305555555555,
              -0.010850694444444461,
              -0.3797743055555555,
              -0.2712673611111111,
              -0.43402777777777773,
              -0.23871527777777773
            ],
            "mean_accuracy_gain_pp": -0.3761574074074074,
            "mean_ce_gain": -0.015178489716008757,
            "seed_accuracy_gains_pp": [
              -1.2924382716049383,
              0.5401234567901234
            ],
            "subject_accuracy_gains_pp": [
              0.1736111111111111,
              1.8229166666666665,
              0.4340277777777778,
              0.4340277777777777,
              -3.2986111111111107,
              -0.3472222222222222,
              -1.2152777777777777,
              0.08680555555555552,
              -1.4756944444444444
            ]
          },
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.0321421682098766,
              1.089891975308642
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.021701388888888964,
              -0.07595486111111117,
              0.29296874999999994,
              -0.06510416666666673,
              0.3038194444444444,
              0.13020833333333326,
              -0.13020833333333343,
              0.3797743055555555,
              -0.032552083333333384
            ],
            "mean_accuracy_gain_pp": 0.0868055555555555,
            "mean_ce_gain": -0.004029005509919994,
            "seed_accuracy_gains_pp": [
              -0.32793209876543217,
              0.5015432098765432
            ],
            "subject_accuracy_gains_pp": [
              0.9548611111111112,
              1.3888888888888888,
              -1.5625,
              1.3020833333333333,
              -1.6493055555555558,
              -0.26041666666666663,
              1.8229166666666667,
              -2.2569444444444446,
              1.0416666666666665
            ]
          },
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.9483024691358024,
              1.7169415509259331
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.05425347222222221,
              -0.04340277777777776,
              -0.7161458333333334,
              -0.35807291666666663,
              0.22786458333333337,
              -0.4991319444444444,
              0.18446180555555558,
              -0.4448784722222222,
              0.054253472222222265
            ],
            "mean_accuracy_gain_pp": -0.18325617283950615,
            "mean_ce_gain": -0.04262437858586407,
            "seed_accuracy_gains_pp": [
              0.17361111111111108,
              -0.5401234567901234
            ],
            "subject_accuracy_gains_pp": [
              -1.2152777777777777,
              -1.3020833333333333,
              4.079861111111112,
              1.2152777777777777,
              -3.4722222222222223,
              2.34375,
              -3.125,
              1.909722222222222,
              -2.0833333333333335
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.3213734567901234,
              1.7746913580246912
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.390625,
              0.6076388888888888,
              -0.23871527777777776,
              0.11935763888888887,
              0.23871527777777776,
              -0.11935763888888892,
              0.45572916666666663,
              -0.010850694444444475,
              0.29296875
            ],
            "mean_accuracy_gain_pp": 0.1929012345679012,
            "mean_ce_gain": -0.027445888869855314,
            "seed_accuracy_gains_pp": [
              1.4660493827160495,
              -1.0802469135802468
            ],
            "subject_accuracy_gains_pp": [
              -1.3888888888888888,
              -3.125,
              3.645833333333333,
              0.78125,
              -0.17361111111111116,
              2.6909722222222223,
              -1.9097222222222223,
              1.8229166666666667,
              -0.6076388888888888
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.8294753086419753,
              1.417824074074074
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.368923611111111,
              0.5316840277777777,
              0.05425347222222214,
              0.05425347222222214,
              0.5425347222222221,
              0.01085069444444435,
              0.3255208333333332,
              0.368923611111111,
              0.2604166666666666
            ],
            "mean_accuracy_gain_pp": 0.2797067901234567,
            "mean_ce_gain": -0.03147489437977531,
            "seed_accuracy_gains_pp": [
              1.1381172839506173,
              -0.5787037037037037
            ],
            "subject_accuracy_gains_pp": [
              -0.4340277777777778,
              -1.7361111111111112,
              2.083333333333333,
              2.083333333333333,
              -1.8229166666666667,
              2.4305555555555554,
              -0.08680555555555558,
              -0.4340277777777777,
              0.4340277777777777
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "N0-S0",
          "C0-S0",
          "N0-C0"
        ],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "round_id": "mvcnet-dual-atom-screen-lab10-r4"
      },
      "closing_round": "mvcnet-dual-atom-screen-lab10-r4",
      "closing_run": {
        "artifact_manifest_sha256": "417737db7572bb6279f224ef1cfe9aa442342c587b4c62536392d1034930fe8f",
        "contract_sha256": "00283c8161394537060b277a1abdc92d37884528fd80ec4bcb3d3617b3debe81",
        "intake_path": "results/logs/remote/2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
        "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-dual-atom-tx-20260924-r4",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized automatic new direction and 16h one-stage Lab10 execution including recovery upload launch fetch analysis; pure resource wait excluded; MV03 fixed instance remains closed."
    },
    {
      "campaign_id": "mvcnet-source-risk-20260924",
      "closed_at": "2026-09-25T02:42:18.035593+00:00",
      "closing_decision": {
        "aggregate": {
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.81030574845679,
              0.5304783950617284
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260924,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.0217013888888889,
              -0.10850694444444445,
              -0.23871527777777776,
              -0.13020833333333331,
              -0.10850694444444445,
              -0.16276041666666666,
              -0.1736111111111111,
              -0.2495659722222222,
              -0.4123263888888889
            ],
            "mean_accuracy_gain_pp": -0.1736111111111111,
            "mean_ce_gain": 0.010962313023067272,
            "seed_accuracy_gains_pp": [
              -0.05787037037037037,
              -0.28935185185185186
            ],
            "subject_accuracy_gains_pp": [
              -1.7361111111111112,
              -0.6944444444444444,
              0.3472222222222222,
              -0.5208333333333334,
              -0.6944444444444444,
              -0.26041666666666663,
              -0.17361111111111113,
              0.4340277777777778,
              1.7361111111111112
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.54320987654321,
              3.115354938271605
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260924,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.5208333333333333,
              0.2821180555555555,
              0.35807291666666663,
              0.7161458333333333,
              0.48828124999999994,
              -0.6944444444444445,
              0.19531249999999994,
              0.44487847222222215,
              0.7269965277777778
            ],
            "mean_accuracy_gain_pp": 0.33757716049382713,
            "mean_ce_gain": 0.09419447174788062,
            "seed_accuracy_gains_pp": [
              -0.03858024691358022,
              0.7137345679012346
            ],
            "subject_accuracy_gains_pp": [
              -1.1284722222222223,
              0.78125,
              0.17361111111111116,
              -2.6909722222222223,
              -0.8680555555555555,
              8.59375,
              1.4756944444444444,
              -0.5208333333333333,
              -2.777777777777778
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.7746913580246912,
              2.903163580246914
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260924,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.5425347222222223,
              0.17361111111111124,
              0.119357638888889,
              0.5859375000000001,
              0.3797743055555557,
              -0.857204861111111,
              0.02170138888888902,
              0.1953125000000001,
              0.314670138888889
            ],
            "mean_accuracy_gain_pp": 0.16396604938271617,
            "mean_ce_gain": 0.10515678477094789,
            "seed_accuracy_gains_pp": [
              -0.0964506172839506,
              0.4243827160493827
            ],
            "subject_accuracy_gains_pp": [
              -2.864583333333333,
              0.08680555555555555,
              0.5208333333333334,
              -3.2118055555555554,
              -1.5625,
              8.333333333333334,
              1.3020833333333333,
              -0.08680555555555555,
              -1.0416666666666667
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "N0-S0"
        ],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0"
        ],
        "round_id": "mvcnet-source-risk-screen-lab10-r1"
      },
      "closing_round": "mvcnet-source-risk-screen-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "334f78071f8e9203bcdd887c3655be7da0dc7baca456288bafc293430d1dbb40",
        "contract_sha256": "228d6d2c448996df946c88d03b0be401a71ebe8a46e630a1ca8e5e145d9373a6",
        "intake_path": "results/logs/remote/2026-09-24_mvcnet_source_risk_lab10_r1-full-w1",
        "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-source-risk-tx-20260924-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested AI4S v3.0 automatic next research; apply Program default 10h one stage; prior source-risk verified NO_SIGNAL retained"
    },
    {
      "campaign_id": "mvcnet-channel-bilinear-20260925",
      "closed_at": "2026-09-25T09:33:22.335671+00:00",
      "closing_decision": {
        "aggregate": {
          "C0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -6.25,
              -1.6203703703703705
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260925,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 3,
            "loo_accuracy_gains_pp": [
              -3.9605034722222223,
              -4.448784722222222,
              -3.396267361111111,
              -4.58984375,
              -3.851996527777778,
              -4.134114583333334,
              -3.80859375,
              -3.9388020833333335,
              -3.3745659722222223
            ],
            "mean_accuracy_gain_pp": -3.9448302469135803,
            "mean_ce_gain": -0.3637385992613175,
            "seed_accuracy_gains_pp": [
              -4.417438271604938,
              -3.4722222222222223
            ],
            "subject_accuracy_gains_pp": [
              -3.8194444444444446,
              0.08680555555555558,
              -8.333333333333334,
              1.2152777777777777,
              -4.6875,
              -2.4305555555555554,
              -5.034722222222222,
              -3.993055555555556,
              -8.506944444444445
            ]
          },
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.6397810570987654,
              3.9544753086419755
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260925,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              1.2152777777777777,
              0.8246527777777778,
              1.1827256944444444,
              1.2044270833333335,
              0.021701388888888895,
              0.44487847222222227,
              0.7378472222222223,
              1.3888888888888888,
              1.66015625
            ],
            "mean_accuracy_gain_pp": 0.9645061728395062,
            "mean_ce_gain": -0.8560617309298628,
            "seed_accuracy_gains_pp": [
              1.871141975308642,
              0.05787037037037038
            ],
            "subject_accuracy_gains_pp": [
              -1.0416666666666665,
              2.0833333333333335,
              -0.78125,
              -0.9548611111111112,
              8.506944444444445,
              5.121527777777778,
              2.7777777777777777,
              -2.4305555555555554,
              -4.600694444444445
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -7.1856915509259265,
              0.8680555555555554
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260925,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 3,
            "loo_accuracy_gains_pp": [
              -2.7452256944444446,
              -3.6241319444444446,
              -2.213541666666667,
              -3.3854166666666665,
              -3.830295138888889,
              -3.689236111111111,
              -3.0707465277777777,
              -2.549913194444444,
              -1.714409722222222
            ],
            "mean_accuracy_gain_pp": -2.980324074074074,
            "mean_ce_gain": -1.2198003301911804,
            "seed_accuracy_gains_pp": [
              -2.5462962962962963,
              -3.414351851851852
            ],
            "subject_accuracy_gains_pp": [
              -4.861111111111111,
              2.170138888888889,
              -9.114583333333332,
              0.2604166666666667,
              3.819444444444444,
              2.690972222222222,
              -2.2569444444444446,
              -6.423611111111112,
              -13.10763888888889
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "C0-S0"
        ],
        "primary_contrasts": [
          "P0-S0",
          "P0-C0"
        ],
        "round_id": "mvcnet-channel-bilinear-screen-lab10-r1"
      },
      "closing_round": "mvcnet-channel-bilinear-screen-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "11f32ef434896e08eb6802eac58e18751f66fa35cfa51a703ab23733c01e60e5",
        "contract_sha256": "6b20b45d9b9e58df44a0b42261a6c13a54e31a357d8c68da4b60b273cba60d56",
        "intake_path": "results/logs/remote/2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
        "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-channel-bilinear-tx-20260925-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested next research after verified channel-bilinear NO_SIGNAL; apply Program default10h one stage to ordered-lowpass pooling screen"
    },
    {
      "campaign_id": "mvcnet-ordered-pool-20260925",
      "closed_at": "2026-09-26T08:50:37.844720+00:00",
      "closing_decision": {
        "aggregate": {
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -3.8001543209876543,
              -0.9452160493827162
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260925,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 1,
            "loo_accuracy_gains_pp": [
              -2.3871527777777777,
              -2.430555555555556,
              -2.235243055555556,
              -2.6475694444444446,
              -2.0941840277777777,
              -2.7018229166666665,
              -1.877170138888889,
              -2.235243055555556,
              -2.3980034722222223
            ],
            "mean_accuracy_gain_pp": -2.334104938271605,
            "mean_ce_gain": -0.05590393767796447,
            "seed_accuracy_gains_pp": [
              -0.925925925925926,
              -3.742283950617284
            ],
            "subject_accuracy_gains_pp": [
              -1.9097222222222223,
              -1.5625,
              -3.125,
              0.17361111111111105,
              -4.253472222222222,
              0.6076388888888884,
              -5.989583333333333,
              -3.125,
              -1.8229166666666667
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.12550636574074073,
              2.662037037037037
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260925,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "positive",
            "gates_passed": true,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              1.1827256944444444,
              1.3997395833333333,
              1.07421875,
              1.8229166666666667,
              1.3563368055555556,
              0.954861111111111,
              1.3888888888888888,
              1.46484375,
              1.2478298611111112
            ],
            "mean_accuracy_gain_pp": 1.3213734567901234,
            "mean_ce_gain": -0.018296136960193457,
            "seed_accuracy_gains_pp": [
              1.1766975308641976,
              1.4660493827160495
            ],
            "subject_accuracy_gains_pp": [
              2.4305555555555554,
              0.6944444444444444,
              3.298611111111111,
              -2.6909722222222223,
              1.0416666666666667,
              4.253472222222222,
              0.7812499999999999,
              0.17361111111111116,
              1.9097222222222223
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -2.912808641975309,
              1.128472222222222
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260925,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 1,
            "loo_accuracy_gains_pp": [
              -1.2044270833333335,
              -1.0308159722222223,
              -1.1610243055555558,
              -0.8246527777777779,
              -0.7378472222222224,
              -1.7469618055555558,
              -0.4882812500000001,
              -0.7703993055555557,
              -1.1501736111111114
            ],
            "mean_accuracy_gain_pp": -1.0127314814814816,
            "mean_ce_gain": -0.07420007463815792,
            "seed_accuracy_gains_pp": [
              0.25077160493827155,
              -2.2762345679012346
            ],
            "subject_accuracy_gains_pp": [
              0.5208333333333333,
              -0.8680555555555556,
              0.17361111111111094,
              -2.517361111111111,
              -3.2118055555555554,
              4.861111111111111,
              -5.208333333333334,
              -2.9513888888888893,
              0.08680555555555558
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "N0-S0"
        ],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0"
        ],
        "round_id": "mvcnet-ordered-pool-screen-lab10-r2"
      },
      "closing_round": "mvcnet-ordered-pool-screen-lab10-r2",
      "closing_run": {
        "artifact_manifest_sha256": "863cb239feaa8cfab694035de70b54ef7043b19210e63bb4a0be7186d42e4694",
        "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
        "intake_path": "results/logs/remote/2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
        "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested next research round under existing automatic design and execution authorization; instantiate temporal-tied-head-v0.1 only, Program default10h one stage, previous ordered-pool verified NO_SIGNAL preserved"
    },
    {
      "campaign_id": "mvcnet-temporal-tied-head-20260926",
      "closed_at": "2026-09-27T02:46:42.299081+00:00",
      "closing_decision": {
        "aggregate": {
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -5.835262345679013,
              -1.5142746913580247
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260926,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 4,
            "loo_accuracy_gains_pp": [
              -3.407118055555556,
              -3.884548611111111,
              -3.2769097222222223,
              -4.1015625,
              -3.493923611111111,
              -4.025607638888889,
              -4.210069444444445,
              -3.125,
              -3.5481770833333335
            ],
            "mean_accuracy_gain_pp": -3.6747685185185186,
            "mean_ce_gain": 0.02273842374535158,
            "seed_accuracy_gains_pp": [
              -3.858024691358025,
              -3.4915123456790127
            ],
            "subject_accuracy_gains_pp": [
              -5.815972222222222,
              -1.996527777777778,
              -6.857638888888889,
              -0.2604166666666665,
              -5.121527777777778,
              -0.8680555555555556,
              0.6076388888888888,
              -8.072916666666668,
              -4.6875
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -21.171031057098762,
              -10.532286844135795
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260926,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 9,
            "loo_accuracy_gains_pp": [
              -14.637586805555555,
              -17.01388888888889,
              -15.11501736111111,
              -16.03732638888889,
              -16.72092013888889,
              -17.13324652777778,
              -14.854600694444445,
              -15.15842013888889,
              -16.297743055555554
            ],
            "mean_accuracy_gain_pp": -15.885416666666666,
            "mean_ce_gain": -0.20233032485590857,
            "seed_accuracy_gains_pp": [
              -15.64429012345679,
              -16.126543209876544
            ],
            "subject_accuracy_gains_pp": [
              -25.868055555555557,
              -6.857638888888889,
              -22.04861111111111,
              -14.67013888888889,
              -9.20138888888889,
              -5.902777777777778,
              -24.131944444444443,
              -21.701388888888886,
              -12.586805555555557
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -25.964506172839506,
              -13.213734567901236
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260926,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 9,
            "loo_accuracy_gains_pp": [
              -18.04470486111111,
              -20.8984375,
              -18.391927083333336,
              -20.13888888888889,
              -20.21484375,
              -21.158854166666668,
              -19.06467013888889,
              -18.28342013888889,
              -19.84592013888889
            ],
            "mean_accuracy_gain_pp": -19.560185185185187,
            "mean_ce_gain": -0.17959190111055698,
            "seed_accuracy_gains_pp": [
              -19.502314814814813,
              -19.618055555555557
            ],
            "subject_accuracy_gains_pp": [
              -31.68402777777778,
              -8.854166666666666,
              -28.90625,
              -14.930555555555555,
              -14.322916666666668,
              -6.770833333333334,
              -23.524305555555557,
              -29.774305555555557,
              -17.274305555555557
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "N0-S0"
        ],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0"
        ],
        "round_id": "mvcnet-temporal-tied-head-screen-lab10-r1"
      },
      "closing_round": "mvcnet-temporal-tied-head-screen-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "a98d53fe4083c943ae7ec899345aa2319bcbcbdc814a5a075b13bfac38fa3644",
        "contract_sha256": "430920fb1d3bef31e1ee6eae99770140e2ddcdf666045304f95c55c70ca66049",
        "intake_path": "results/logs/remote/2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1",
        "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-temporal-tied-head-tx-20260926-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested next round under existing automatic design and execution authorization; instantiate spatial-locality-v0.1 with Program default10h one stage; previous temporal-tied-head verified NO_SIGNAL remains closed"
    },
    {
      "campaign_id": "mvcnet-spatial-locality-20260927",
      "closed_at": "2026-09-27T08:33:16.525878+00:00",
      "closing_decision": {
        "aggregate": {
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -3.433641975308642,
              -0.3665123456790123
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 1,
            "loo_accuracy_gains_pp": [
              -1.66015625,
              -1.9748263888888888,
              -2.224392361111111,
              -2.2026909722222223,
              -1.6710069444444444,
              -1.909722222222222,
              -1.3671875,
              -1.7795138888888888,
              -1.8771701388888888
            ],
            "mean_accuracy_gain_pp": -1.8518518518518519,
            "mean_ce_gain": -0.004176504884942577,
            "seed_accuracy_gains_pp": [
              -0.7137345679012346,
              -2.989969135802469
            ],
            "subject_accuracy_gains_pp": [
              -3.3854166666666665,
              -0.8680555555555556,
              1.1284722222222223,
              0.9548611111111112,
              -3.298611111111111,
              -1.388888888888889,
              -5.729166666666667,
              -2.4305555555555554,
              -1.6493055555555554
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.9675925925925926,
              0.5690586419753086
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -1.0416666666666667,
              -0.5750868055555556,
              -0.24956597222222224,
              -0.48828125,
              -0.6944444444444444,
              -0.5750868055555556,
              -0.8138020833333333,
              -0.7921006944444444,
              -0.7595486111111112
            ],
            "mean_accuracy_gain_pp": -0.6655092592592593,
            "mean_ce_gain": -0.07789039829585352,
            "seed_accuracy_gains_pp": [
              -1.1188271604938271,
              -0.2121913580246913
            ],
            "subject_accuracy_gains_pp": [
              2.34375,
              -1.3888888888888888,
              -3.9930555555555554,
              -2.0833333333333335,
              -0.4340277777777778,
              -1.3888888888888888,
              0.5208333333333333,
              0.3472222222222222,
              0.08680555555555558
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -3.510923032407407,
              -1.6493055555555556
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 1,
            "loo_accuracy_gains_pp": [
              -2.7018229166666665,
              -2.549913194444444,
              -2.473958333333333,
              -2.6909722222222223,
              -2.365451388888889,
              -2.4848090277777777,
              -2.180989583333333,
              -2.571614583333333,
              -2.63671875
            ],
            "mean_accuracy_gain_pp": -2.517361111111111,
            "mean_ce_gain": -0.0820669031807961,
            "seed_accuracy_gains_pp": [
              -1.8325617283950617,
              -3.2021604938271606
            ],
            "subject_accuracy_gains_pp": [
              -1.0416666666666667,
              -2.2569444444444446,
              -2.864583333333333,
              -1.128472222222222,
              -3.732638888888889,
              -2.7777777777777777,
              -5.208333333333333,
              -2.083333333333333,
              -1.5625
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "N0-S0"
        ],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0"
        ],
        "round_id": "mvcnet-spatial-locality-screen-lab10-r1"
      },
      "closing_round": "mvcnet-spatial-locality-screen-lab10-r1",
      "closing_run": {
        "artifact_manifest_sha256": "4ce1566129b22178f3613dab0d38051fc1f15471ad1de17c6f13db49353457c8",
        "contract_sha256": "57b87dd86d7e08e520824988b48ea42af383c5e65594fc52d08c92e568c79f5d",
        "intake_path": "results/logs/remote/2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1",
        "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-spatial-locality-tx-20260927-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested next research after spatial-locality NO_SIGNAL; continuing standing autonomous design/execution authorization with Program default 10h, one new cosine-readout stage, no carryover or automatic extension."
    },
    {
      "campaign_id": "mvcnet-cosine-readout-20260927",
      "closed_at": "2026-09-27T15:39:03.106573+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.6944444444444444,
              0.6076388888888888
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.043402777777777804,
              0.11935763888888885,
              0.054253472222222196,
              -0.17361111111111113,
              -0.09765625000000001,
              0.021701388888888853,
              0.04340277777777775,
              -0.22786458333333337,
              -0.13020833333333337
            ],
            "mean_accuracy_gain_pp": -0.048225308641975335,
            "mean_ce_gain": -0.011768186896412272,
            "seed_accuracy_gains_pp": [
              -0.308641975308642,
              0.21219135802469133
            ],
            "subject_accuracy_gains_pp": [
              -0.08680555555555558,
              -1.3888888888888888,
              -0.8680555555555556,
              0.954861111111111,
              0.3472222222222221,
              -0.6076388888888888,
              -0.78125,
              1.3888888888888888,
              0.6076388888888888
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.369598765432099,
              1.6782407407407407
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.021701388888888867,
              0.5750868055555556,
              0.18446180555555555,
              0.45572916666666663,
              0.2170138888888889,
              0.06510416666666666,
              0.7269965277777778,
              -0.06510416666666671,
              0.07595486111111113
            ],
            "mean_accuracy_gain_pp": 0.2507716049382716,
            "mean_ce_gain": -0.03775216894831704,
            "seed_accuracy_gains_pp": [
              -0.2314814814814815,
              0.7330246913580247
            ],
            "subject_accuracy_gains_pp": [
              2.0833333333333335,
              -2.34375,
              0.78125,
              -1.3888888888888888,
              0.5208333333333333,
              1.7361111111111112,
              -3.559027777777778,
              2.777777777777778,
              1.6493055555555554
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [],
        "primary_contrasts": [
          "P0-S0",
          "P0-C0"
        ],
        "round_id": "mvcnet-cosine-readout-screen-lab10-r2"
      },
      "closing_round": "mvcnet-cosine-readout-screen-lab10-r2",
      "closing_run": {
        "artifact_manifest_sha256": "f56f1350b4d2a49a9d02f40a8ae6126f55398c59289eed6cbc41382ec9efbfed",
        "contract_sha256": "21d14cbd7b5fd6b9b3154d8613de3125116372b534035652042a51f3df7f403f",
        "intake_path": "results/logs/remote/2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
        "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-cosine-readout-tx-20260927-r2",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户继续下一轮研究；cosine-readout已NO_SIGNAL收口，新问题为共享卷积参数敏感性，原生分类头与损失保留，固定SAM方向及随机等幅扰动三臂，Program默认10小时实际预算，不自动追加"
    },
    {
      "campaign_id": "mvcnet-conv-sam-20260927",
      "closed_at": "2026-09-29T16:22:20.478374+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -5.131172839506173,
              3.8676697530864197
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 1,
            "loo_accuracy_gains_pp": [
              -0.390625,
              -0.15190972222222227,
              -0.04340277777777779,
              0.1736111111111111,
              -1.0308159722222223,
              -0.4448784722222222,
              -0.1736111111111111,
              1.9422743055555556,
              0.20616319444444442
            ],
            "mean_accuracy_gain_pp": 0.009645061728395053,
            "mean_ce_gain": 0.03130651560503249,
            "seed_accuracy_gains_pp": [
              3.240740740740741,
              -3.2214506172839505
            ],
            "subject_accuracy_gains_pp": [
              3.2118055555555554,
              1.3020833333333335,
              0.4340277777777778,
              -1.3020833333333333,
              8.333333333333334,
              3.645833333333333,
              1.4756944444444444,
              -15.45138888888889,
              -1.5625
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -6.095679012345679,
              2.006172839506173
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260927,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 2,
            "loo_accuracy_gains_pp": [
              -1.4865451388888886,
              -1.5842013888888886,
              -1.7469618055555554,
              -1.5082465277777775,
              -1.399739583333333,
              -1.985677083333333,
              -1.9639756944444442,
              0.39062500000000017,
              -0.7812499999999998
            ],
            "mean_accuracy_gain_pp": -1.3406635802469133,
            "mean_ce_gain": 0.015391526851142565,
            "seed_accuracy_gains_pp": [
              0.9452160493827162,
              -3.626543209876543
            ],
            "subject_accuracy_gains_pp": [
              -0.17361111111111105,
              0.607638888888889,
              1.9097222222222223,
              0.0,
              -0.8680555555555556,
              3.8194444444444446,
              3.6458333333333335,
              -15.190972222222221,
              -5.815972222222221
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0"
        ],
        "round_id": "mvcnet-conv-sam-screen-lab10-r7"
      },
      "closing_round": "mvcnet-conv-sam-screen-lab10-r7",
      "closing_run": {
        "artifact_manifest_sha256": "1dd2952e772da44d040790abbbfffcd91db2c8b5e3193be7ea807236770717f3",
        "contract_sha256": "9602f44fcb743179f53887d9ec1252bfcdda90776e9873b86f8fe3553b60ffbf",
        "intake_path": "results/logs/remote/2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
        "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-conv-sam-tx-20260927-r7",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested upload and launch the concretely proposed SED 90-training/54-check,16h design; source_excluded_distillation/AUTHORIZATION.md"
    },
    {
      "campaign_id": "mvcnet-source-excluded-distillation-20260930",
      "closed_at": "2026-10-05T11:48:50.420769+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.617283950617284,
              1.2924382716049383
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260930,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.4014756944444444,
              0.22786458333333331,
              0.4014756944444444,
              0.3472222222222222,
              0.6727430555555556,
              0.2495659722222222,
              0.3472222222222222,
              0.4231770833333333,
              0.05425347222222218
            ],
            "mean_accuracy_gain_pp": 0.3472222222222222,
            "mean_ce_gain": 0.018498086267047457,
            "seed_accuracy_gains_pp": [
              0.42438271604938266,
              0.27006172839506176
            ],
            "subject_accuracy_gains_pp": [
              -0.08680555555555558,
              1.3020833333333333,
              -0.08680555555555547,
              0.3472222222222222,
              -2.2569444444444446,
              1.128472222222222,
              0.3472222222222222,
              -0.26041666666666663,
              2.6909722222222223
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.3182870370370369,
              1.8518518518518519
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260930,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "positive",
            "gates_passed": true,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.8246527777777779,
              0.6727430555555556,
              1.0091145833333335,
              0.7486979166666667,
              1.2261284722222223,
              0.7703993055555556,
              0.8246527777777778,
              0.9114583333333334,
              0.5642361111111112
            ],
            "mean_accuracy_gain_pp": 0.8391203703703705,
            "mean_ce_gain": 0.04588296347194248,
            "seed_accuracy_gains_pp": [
              1.4467592592592593,
              0.23148148148148148
            ],
            "subject_accuracy_gains_pp": [
              0.954861111111111,
              2.170138888888889,
              -0.5208333333333333,
              1.5625,
              -2.256944444444444,
              1.3888888888888888,
              0.9548611111111112,
              0.26041666666666674,
              3.0381944444444446
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [],
        "primary_contrasts": [
          "P0-S0",
          "P0-N0"
        ],
        "round_id": "mvcnet-source-excluded-distillation-screen-lab10-r4"
      },
      "closing_round": "mvcnet-source-excluded-distillation-screen-lab10-r4",
      "closing_run": {
        "artifact_manifest_sha256": "849ac59d2c34ddd26d0549d1a81bbabc6c0903039f1aed7cab6cb6e069cb18c7",
        "contract_sha256": "5762262e18c88c87faf0b16d29fdaecc627d1a5b6f60749fd17cbed980211974",
        "intake_path": "results/logs/remote/2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
        "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-source-excluded-distillation-tx-20260930-r4",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User2026-10-05: 24h full execution; both CCMU GPUs; ai4s/programs/mvcnet/research/source_class_relation/AUTHORIZATION.md"
    },
    {
      "campaign_id": "mvcnet-source-class-relation-20261005",
      "closed_at": "2026-10-06T11:59:00.884510+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.5113088348765431,
              1.234567901234568
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261005,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.13020833333333334,
              0.10850694444444445,
              0.17361111111111113,
              0.390625,
              0.4991319444444445,
              0.4991319444444444,
              0.4448784722222222,
              0.27126736111111116,
              0.4340277777777778
            ],
            "mean_accuracy_gain_pp": 0.3279320987654321,
            "mean_ce_gain": 8.528292784821318e-05,
            "seed_accuracy_gains_pp": [
              0.0,
              0.6558641975308642
            ],
            "subject_accuracy_gains_pp": [
              1.9097222222222223,
              2.0833333333333335,
              1.5625,
              -0.17361111111111116,
              -1.0416666666666667,
              -1.0416666666666665,
              -0.6076388888888888,
              0.78125,
              -0.5208333333333335
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              0.2121913580246913,
              2.1122685185185186
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261005,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "positive",
            "gates_passed": true,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              1.26953125,
              1.1067708333333335,
              1.3997395833333335,
              1.0850694444444444,
              1.1501736111111112,
              1.3454861111111112,
              1.605902777777778,
              1.1501736111111112,
              1.171875
            ],
            "mean_accuracy_gain_pp": 1.253858024691358,
            "mean_ce_gain": 0.01640850993471127,
            "seed_accuracy_gains_pp": [
              1.1381172839506173,
              1.3695987654320987
            ],
            "subject_accuracy_gains_pp": [
              1.128472222222222,
              2.4305555555555554,
              0.08680555555555536,
              2.604166666666667,
              2.0833333333333335,
              0.5208333333333334,
              -1.5625,
              2.0833333333333335,
              1.9097222222222223
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.7746913580246912,
              1.8326822916666738
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261005,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.11935763888888895,
              0.043402777777777846,
              0.2495659722222223,
              0.46657986111111116,
              -0.46657986111111105,
              -0.10850694444444436,
              -0.2278645833333333,
              0.46657986111111116,
              -0.28211805555555547
            ],
            "mean_accuracy_gain_pp": 0.028935185185185244,
            "mean_ce_gain": 0.08077698988710223,
            "seed_accuracy_gains_pp": [
              -0.48225308641975295,
              0.5401234567901234
            ],
            "subject_accuracy_gains_pp": [
              -0.6944444444444444,
              -0.08680555555555558,
              -1.7361111111111112,
              -3.472222222222222,
              3.993055555555556,
              1.128472222222222,
              2.0833333333333335,
              -3.4722222222222223,
              2.517361111111111
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "interpretation_boundary": "A positive result is limited to this seven-source class-relation screen; it is not ordinary eight-source LOSO or a novelty claim.",
        "primary_contrasts": [
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "research_stage": "source_class_relation_screen",
        "round_id": "mvcnet-source-class-relation-screen-ccmu-r6"
      },
      "closing_round": "mvcnet-source-class-relation-screen-ccmu-r6",
      "closing_run": {
        "artifact_manifest_sha256": "aee5c5b85e08ed2d31204f53e9ec3cf51119bc855248c185d3b8edabe13aebba",
        "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
        "intake_path": "results/logs/remote/2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
        "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User 2026-10-06 requested launch/upload of the just-delivered SCMA proposal (24h, one stage); authority ai4s/programs/mvcnet/research/source_class_mean_alignment/AUTHORIZATION.md"
    },
    {
      "campaign_id": "mvcnet-source-class-mean-alignment-20261006",
      "closed_at": "2026-10-07T17:01:58.100404+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -2.054398148148148,
              0.655984760802476
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261006,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.7921006944444444,
              -0.46657986111111116,
              -0.6293402777777778,
              -1.0091145833333333,
              -0.7378472222222222,
              -0.6401909722222222,
              -0.9548611111111112,
              -1.2369791666666665,
              -0.5642361111111112
            ],
            "mean_accuracy_gain_pp": -0.78125,
            "mean_ce_gain": 0.00897816327055909,
            "seed_accuracy_gains_pp": [
              -2.199074074074074,
              0.6365740740740741
            ],
            "subject_accuracy_gains_pp": [
              -0.6944444444444444,
              -3.2986111111111107,
              -1.9965277777777777,
              1.0416666666666667,
              -1.1284722222222223,
              -1.9097222222222223,
              0.6076388888888888,
              2.864583333333333,
              -2.517361111111111
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.7457561728395063,
              2.3631606867284023
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261006,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.05425347222222229,
              0.6944444444444444,
              0.5533854166666666,
              0.14105902777777773,
              -0.3906250000000001,
              0.4340277777777777,
              0.03255208333333329,
              0.15190972222222218,
              0.6944444444444444
            ],
            "mean_accuracy_gain_pp": 0.25077160493827155,
            "mean_ce_gain": 0.011741459551392731,
            "seed_accuracy_gains_pp": [
              -1.4660493827160495,
              1.9675925925925926
            ],
            "subject_accuracy_gains_pp": [
              2.6909722222222223,
              -3.298611111111111,
              -2.170138888888889,
              1.128472222222222,
              5.381944444444445,
              -1.2152777777777777,
              1.9965277777777777,
              1.0416666666666665,
              -3.2986111111111116
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -3.6363088348765435,
              -0.33757716049382713
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261006,
            "ce_non_degradation": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 1,
            "loo_accuracy_gains_pp": [
              -2.615017361111111,
              -1.85546875,
              -1.8120659722222223,
              -2.2569444444444446,
              -1.6710069444444444,
              -1.974826388888889,
              -2.126736111111111,
              -2.3546006944444446,
              -1.996527777777778
            ],
            "mean_accuracy_gain_pp": -2.0736882716049383,
            "mean_ce_gain": -0.03033287403582141,
            "seed_accuracy_gains_pp": [
              -2.3341049382716053,
              -1.8132716049382716
            ],
            "subject_accuracy_gains_pp": [
              2.2569444444444446,
              -3.8194444444444446,
              -4.166666666666667,
              -0.6076388888888888,
              -5.295138888888889,
              -2.8645833333333335,
              -1.6493055555555556,
              0.17361111111111113,
              -2.6909722222222223
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "interpretation_boundary": "A positive result is limited to this seven-source developmental SCMA screen; it is not ordinary eight-source LOSO, a novelty claim, or an independent confirmation.",
        "primary_contrasts": [
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "research_stage": "source_class_mean_alignment_screen",
        "round_id": "mvcnet-source-class-mean-alignment-screen-ccmu-r1"
      },
      "closing_round": "mvcnet-source-class-mean-alignment-screen-ccmu-r1",
      "closing_run": {
        "artifact_manifest_sha256": "4515dd6c3d19082183ddf347a90888678e9a1552cb9bd2ab63668dff5d613fbb",
        "contract_sha256": "0f153a10f061916eb6d41c67cb31dd7b5e5fba5f7fa8a0698bf0c10be04580c7",
        "intake_path": "results/logs/remote/2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
        "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-source-class-mean-alignment-tx-20261006-r1",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized 30 hours and full CCMU dual-GPU execution after strict qualification; SCMA closed; no rescue or scope expansion"
    },
    {
      "campaign_id": "mvcnet-source-head-meta-20261008",
      "closed_at": "2026-10-09T06:26:54.015683+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.4467592592592593,
              -0.1446759259259259
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261008,
            "ce_non_degradation": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -1.0525173611111112,
              -0.8463541666666666,
              -0.9331597222222222,
              -0.7378472222222222,
              -0.661892361111111,
              -0.8355034722222222,
              -0.759548611111111,
              -0.78125,
              -0.857204861111111
            ],
            "mean_accuracy_gain_pp": -0.8294753086419753,
            "mean_ce_gain": -0.007879819981730226,
            "seed_accuracy_gains_pp": [
              -1.253858024691358,
              -0.4050925925925926
            ],
            "subject_accuracy_gains_pp": [
              0.9548611111111112,
              -0.6944444444444444,
              0.0,
              -1.5625,
              -2.170138888888889,
              -0.78125,
              -1.3888888888888888,
              -1.2152777777777777,
              -0.6076388888888888
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.7040895061728395,
              0.8969907407407407
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261008,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.043402777777777804,
              -0.1410590277777778,
              0.16276041666666663,
              -0.2170138888888889,
              0.11935763888888885,
              0.13020833333333331,
              0.01085069444444442,
              0.13020833333333331,
              0.19531249999999994
            ],
            "mean_accuracy_gain_pp": 0.038580246913580224,
            "mean_ce_gain": 0.028569499766371315,
            "seed_accuracy_gains_pp": [
              -0.8101851851851852,
              0.8873456790123457
            ],
            "subject_accuracy_gains_pp": [
              0.6944444444444444,
              1.4756944444444444,
              -0.954861111111111,
              2.083333333333333,
              -0.6076388888888888,
              -0.6944444444444444,
              0.26041666666666663,
              -0.6944444444444445,
              -1.2152777777777777
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.5432098765432098,
              0.9355709876543209
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261008,
            "ce_non_degradation": true,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.1410590277777778,
              -0.48828125000000006,
              -0.34722222222222227,
              -0.6293402777777778,
              -0.15190972222222227,
              -0.19531250000000006,
              -0.5967881944444444,
              0.02170138888888888,
              -0.3363715277777778
            ],
            "mean_accuracy_gain_pp": -0.3182870370370371,
            "mean_ce_gain": 0.017274167921039092,
            "seed_accuracy_gains_pp": [
              -0.7908950617283951,
              0.15432098765432098
            ],
            "subject_accuracy_gains_pp": [
              -1.7361111111111112,
              1.0416666666666667,
              -0.08680555555555558,
              2.170138888888889,
              -1.6493055555555554,
              -1.3020833333333333,
              1.9097222222222219,
              -3.0381944444444446,
              -0.17361111111111105
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "interpretation_boundary": "A positive result is limited to this seven-source developmental source head meta screen; it is not ordinary eight-source LOSO, a novelty claim, or an independent confirmation.",
        "primary_contrasts": [
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "research_stage": "source_disjoint_head_meta_screen",
        "round_id": "mvcnet-source-head-meta-screen-ccmu-r4"
      },
      "closing_round": "mvcnet-source-head-meta-screen-ccmu-r4",
      "closing_run": {
        "artifact_manifest_sha256": "6b45cc01797cefa88ade5f7fa25cc4c5844523054573c0bf4e3d511a1cb90e8a",
        "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
        "intake_path": "results/logs/remote/2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
        "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User2026-10-09: 在lab10上运行，四臂新设计30h单阶段"
    },
    {
      "campaign_id": "mvcnet-augmentation-readout-lab10-20261009-r1",
      "closed_at": "2026-10-24T10:29:06.696909+00:00",
      "closing_decision": {
        "aggregate": {
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.4243827160493827,
              1.5335648148148149
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261009,
            "ce_non_degradation": true,
            "ci_level": 95,
            "gates_passed": null,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.6618923611111112,
              0.3580729166666667,
              0.802951388888889,
              0.7269965277777778,
              0.5967881944444444,
              0.4557291666666667,
              0.3038194444444445,
              0.6401909722222222,
              0.22786458333333337
            ],
            "mean_accuracy_gain_pp": 0.5304783950617284,
            "mean_ce_gain": 0.023201175214278266,
            "role": "descriptive_attribution",
            "seed_accuracy_gains_pp": [
              0.21219135802469138,
              0.8487654320987654
            ],
            "subject_accuracy_gains_pp": [
              -0.5208333333333334,
              1.9097222222222223,
              -1.6493055555555556,
              -1.0416666666666665,
              0.0,
              1.1284722222222223,
              2.34375,
              -0.3472222222222222,
              2.951388888888889
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.18325617283950615,
              1.408179012345679
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261009,
            "ce_non_degradation": true,
            "ci_level": 95,
            "gates_passed": null,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.7052951388888888,
              0.4557291666666667,
              0.7378472222222222,
              0.5208333333333334,
              0.7161458333333334,
              0.6618923611111112,
              0.3580729166666667,
              0.7161458333333334,
              0.3363715277777778
            ],
            "mean_accuracy_gain_pp": 0.5787037037037037,
            "mean_ce_gain": 0.03647215510544317,
            "role": "descriptive_attribution",
            "seed_accuracy_gains_pp": [
              0.2700617283950618,
              0.8873456790123456
            ],
            "subject_accuracy_gains_pp": [
              -0.4340277777777777,
              1.5625,
              -0.6944444444444444,
              1.0416666666666665,
              -0.5208333333333333,
              -0.08680555555555558,
              2.34375,
              -0.5208333333333334,
              2.517361111111111
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.9741512345679012,
              2.459490740740741
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20261009,
            "ce_non_degradation": true,
            "ci_level": 95,
            "gates_passed": false,
            "harm_below_or_equal_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.9331597222222223,
              0.08680555555555558,
              0.9331597222222222,
              0.5533854166666667,
              0.8572048611111112,
              0.35807291666666674,
              0.32552083333333337,
              1.0308159722222223,
              0.998263888888889
            ],
            "mean_accuracy_gain_pp": 0.6751543209876544,
            "mean_ce_gain": 0.02818820664966222,
            "role": "primary_gate",
            "seed_accuracy_gains_pp": [
              -0.057870370370370385,
              1.408179012345679
            ],
            "subject_accuracy_gains_pp": [
              -1.3888888888888888,
              5.381944444444445,
              -1.3888888888888886,
              1.6493055555555556,
              -0.78125,
              3.2118055555555554,
              3.4722222222222223,
              -2.170138888888889,
              -1.9097222222222223
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "descriptive_contrasts": [
          "P0-N0",
          "P0-C0"
        ],
        "interpretation_boundary": "A positive result supports only this seven-source developmental augmentation-readout screen; attribution contrasts and bootstrap/LOO intervals are descriptive, with no novelty or independent-confirmation claim.",
        "primary_contrasts": [
          "P0-S0"
        ],
        "research_stage": "augmentation_readout_screen",
        "round_id": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2"
      },
      "closing_round": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "22ed7b9b61f5514c2178e88cef65b6d137f4604ad4de62c34ab829294fb7e9f3",
        "contract_sha256": "7e6ba57cf52614bb92d2678a83b8d33bfa260a4fda6b516ca6e6e57f4d885c6a",
        "intake_path": "results/logs/remote/2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
        "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-augmentation-readout-tx-20261018-r1-resume69-repair2",
        "verified": true,
        "verified_at": "2026-10-24T10:12:37.854380+00:00"
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User2026-10-24 reaffirmed200h and Lab10 VBR-R1 after old standard closeout; include preparation from04:35:51UTC; no scientific retry or budget reset"
    },
    {
      "campaign_id": "mvcnet-vbr-r1-lab10-20261024",
      "closed_at": "2026-10-29T14:07:24.178201+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "harm_subjects": 0,
        "interpretation_boundary": "Seven-source developmental screen; no formal claim.",
        "mean_accuracy_gain_pp": 0.019290123456790105,
        "mean_ce_gain": 0.012652577901765197,
        "positive_subjects": 4,
        "research_stage": "vbr_screen",
        "round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair3",
        "seed_means_pp": {
          "69": -0.2507716049382716,
          "70": 0.2893518518518518
        }
      },
      "closing_round": "mvcnet-vbr-r1-screen-lab10-r1-repair3",
      "closing_run": {
        "addendum_sha256": "191e86ebf84071b7c06a52c09888734bb91949315d4f438038d1d7c0e46cf6a9",
        "artifact_manifest_sha256": "206ac78625979fe528c4061543e8158f3a41a5595451ff724a95bf543116812f",
        "bundle_manifest_sha256": "8ed6eb37ce031dc04af05fd31695670e9acb082d8fe55f50415bdfbb4337d946",
        "complete_remote": true,
        "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
        "core_manifest_sha256": "8f23d0cf6a3c85870189581f8bb578816bcc4cb10bb4cd2778aa461adba0a516",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
        "intake_scope": "analysis_v1_recovery",
        "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
        "run_status": "complete",
        "support_sha256": "44326a309be05f654410a5c92c8742185cc2000a6ad61c01aceb5151eca1ffed",
        "transaction_id": "mvcnet-vbr-r1-tx-20261028-r1-repair3-packfix2",
        "transfer_bytes": 27222739,
        "verified": true,
        "verified_at": null,
        "verified_at_utc": "2026-10-28T18:21:05.601717+00:00"
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized one-shot XSN-R1 exploration and independent 36h cap; preserve prior VBR 275h history and 13:20 UTC preparation anchor; one scientific stage only"
    },
    {
      "campaign_id": "mvcnet-xsn-r1-lab10-20261029",
      "closed_at": "2026-11-04T14:56:23.318302+00:00",
      "closing_decision": {
        "all_interpretive_gates_pass": false,
        "claim_release": "none",
        "decision": "NO_SIGNAL",
        "failure_disposition": "stop this exact configuration; no rescue search",
        "interpretation": "control advantages never substitute for the P0-S0 utility gate",
        "interpretive_gates": {
          "P0-C0": false,
          "P0-N0": false,
          "P0-R0": true
        },
        "primary_P0_minus_S0_pass": false,
        "reason": "a frozen XSN utility or interpretive gate failed; stop this configuration",
        "research_stage": "xsn_screen",
        "round_id": "mvcnet-xsn-r1-screen-lab10-r1-budget480",
        "status": "frozen_rule_applied"
      },
      "closing_round": "mvcnet-xsn-r1-screen-lab10-r1-budget480",
      "closing_run": {
        "analysis_receipt_sha256": "8e90ad02bcc9e445b3978a363e10360c595348af85eccebe7786640c5356bccc",
        "artifact_manifest_sha256": "0644f17901c81030a03c080bdafdbf09818e5f7ed2fcd6651c6b5242104b26d5",
        "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
        "intake_scope": "analysis_v1_recovery",
        "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
        "transfer_bytes": 31464578,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户授权ACM-R1一次性探索，独立42小时，准备计时起点2026-11-04T13:54:00Z；资格与成本门通过才四臂完整训练，不调参救援，保留XSN关闭及全部历史。",
      "full_prior_campaign_snapshot": {
        "campaign": {
          "allowed_transitions": [
            "SCREEN_NEW"
          ],
          "authorization_reason": "User authorized one-shot XSN-R1 exploration and independent 36h cap; preserve prior VBR 275h history and 13:20 UTC preparation anchor; one scientific stage only",
          "budget_extensions": [
            {
              "accounting_started_at": "2026-10-29T13:20:00+00:00",
              "authorization": {
                "path": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/AUTHORIZATION.json",
                "sha256": "7f9927c168131b7cb13a5072efc72b563a4a10c6958f077ef25e240d5b677909"
              },
              "increase_hours": 444,
              "new_total_hours": 480,
              "previous_total_hours": 36,
              "recorded_at": "2026-10-30T20:32:02.230180+00:00",
              "reset": false
            }
          ],
          "budget_policy": {
            "authorization_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/AUTHORIZATION.json",
            "exclude_verified_stopped_seconds": true
          },
          "campaign_id": "mvcnet-xsn-r1-lab10-20261029",
          "completed_at": "2026-11-04T13:06:08.408292+00:00",
          "continuation_policy_version": "evidence_to_design_v1",
          "decision_policy": "stop_at_positive",
          "execution_authorization": {
            "allowed_operations": [
              "upload",
              "launch",
              "probe",
              "fetch",
              "intake"
            ],
            "allowed_transitions": [
              "SCREEN_NEW"
            ],
            "authorization_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/AUTHORIZATION.json",
            "campaign_id": "mvcnet-xsn-r1-lab10-20261029",
            "executor_id": "lab10",
            "recorded_at": "2026-10-29T14:07:32.759938+00:00",
            "research_scope": {
              "allow_new_module": true,
              "allowed_module_ids": [
                "src.models.ai4s.mvcnet.xsn_r1"
              ],
              "allowed_stages": [
                "xsn_screen"
              ],
              "data_scope_id": "xsn-seven-source-developmental-seeds71-72-v1",
              "question_id": "vcn-cross-source-same-class-negative-selection"
            },
            "source_sha256": "57ab6321b850aa98f0123bc4be9ffa2f3782b07ca89a7087a8730e2467aa7fc1"
          },
          "final_accounting": {
            "accounting_started_at": "2026-10-29T13:20:00+00:00",
            "budget_reset": false,
            "check_process_hours": 1.4906911111111114,
            "closed_at": "2026-11-04T13:06:08.408292+00:00",
            "cumulative_charged_hours": 12.02165241743252,
            "elapsed_wall_hours": 143.76900230333334,
            "excluded_resource_queue_hours": 103.11574117322763,
            "excluded_verified_stopped_hours": 28.631608712673188,
            "new_terminal_stopped_hours": 16.492168576783605,
            "no_remaining_training_authorization": true,
            "record": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/FINAL_COST.json",
            "record_sha256": "8ee531f98eccc7f46d5d7edea9bb7a861163e726057a6e01d294fb4b29cf2cf0",
            "remaining_budget_hours": 467.9783475825675,
            "status": "FINAL_ACCOUNTING_AT_CLOSEOUT",
            "time_settlement": {
              "path": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/STOPPED_TIME_SETTLEMENT.json",
              "sha256": "005c5e2d2325ba0063ada5467959c91580f38a677fef12d1a7626b6aacf35f2a"
            },
            "total_budget_hours": 480,
            "training_process_hours": 55.126532222222195,
            "transaction_actual_execution_hours": 8.476120514472326,
            "transaction_forecast_hours": 419.25888487456865,
            "transaction_resource_queue_hours": 86.61061554597484,
            "units_note": "elapsed preparation/execution/intake/analysis, not summed parallel process hours. All time after first status check conservatively charged; no extra idle-gap exclusions."
          },
          "governance_chain_id": "mvcnet-transaction-v3.3",
          "invalid_behavior": "fail_closed_without_advancing",
          "positive_signal_behavior": "pause_for_human_review",
          "purpose": "user-authorized bounded AI4S campaign",
          "queue_accounting": {
            "2026-10-29_mvcnet_xsn_r1_lab10_r1-full-w1": {
              "contract_sha256": "a345fc22ba362196f342c74f5c91f0a7bfb2c9a92931f512dcb28f3761a36035",
              "queue_seconds": 13711.903646469116,
              "run_id": "2026-10-29_mvcnet_xsn_r1_lab10_r1-full-w1",
              "transaction_id": "mvcnet-xsn-r1-tx-20261029-r1"
            },
            "2026-10-30_mvcnet_xsn_r1_lab10_r1_repair1-full-w1": {
              "contract_sha256": "434a50bf6a957497bac049bbc7c424df6416210f2f07f9adcece832aa68943af",
              "queue_seconds": 45706.54861164093,
              "run_id": "2026-10-30_mvcnet_xsn_r1_lab10_r1_repair1-full-w1",
              "transaction_id": "mvcnet-xsn-r1-tx-20261030-r1-repair1"
            },
            "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1": {
              "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
              "queue_seconds": 311798.2159655094,
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480"
            }
          },
          "round_decisions": [
            {
              "decision": "NO_SIGNAL",
              "decision_record": "ai4s/programs/mvcnet/research/mvcnet-xsn-r1-screen-lab10-r1-budget480_decision.yaml",
              "evidence_id": "AI4S-MVCNET-mvcnet-xsn-r1-screen-lab10-r1-budget480",
              "recorded_at": "2026-11-04T13:00:30.633280+00:00",
              "round_id": "mvcnet-xsn-r1-screen-lab10-r1-budget480"
            }
          ],
          "started_at": "2026-10-29T14:07:24.178201+00:00",
          "stopped_accounting": [
            {
              "authorization_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/repair1/AUTHORIZATION.json",
              "end": 1793331454.339,
              "evidence_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/repair1/STOPPED_TIME_SETTLEMENT.json",
              "source_run_id": "2026-10-29_mvcnet_xsn_r1_lab10_r1-full-w1",
              "start": 1793297121.270935
            },
            {
              "authorization_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/AUTHORIZATION.json",
              "end": 1793391626.898,
              "evidence_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/STOPPED_TIME_SETTLEMENT.json",
              "source_run_id": "2026-10-30_mvcnet_xsn_r1_lab10_r1_repair1-full-w1",
              "start": 1793382257.9815757
            },
            {
              "authorization_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/CLOSEOUT_AUTHORIZATION.json",
              "end": 1793795410.6048026,
              "evidence_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/STOPPED_TIME_SETTLEMENT.json",
              "source_run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "start": 1793736038.7979262
            }
          ]
        },
        "final_accounting": null,
        "run_control": {
          "accounting_anchor_basis": "XSN-R1 AUTHORIZATION.json; preparation included; no reset",
          "continuation_policy_version": "evidence_to_design_v1",
          "continue_after_positive": false,
          "max_rounds": 1,
          "monitor": "blocking",
          "night_budget_hours": 480.0,
          "preparation_included": true,
          "queue_time_policy": "exclude_resource_wait",
          "round_index": 1,
          "started_at": "2026-10-29T13:20:00+00:00"
        },
        "xsn_r1_closeout": {
          "decision": "NO_SIGNAL",
          "evidence_id": "AI4S-MVCNET-mvcnet-xsn-r1-screen-lab10-r1-budget480",
          "final_cost": {
            "path": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/FINAL_COST.json",
            "sha256": "8ee531f98eccc7f46d5d7edea9bb7a861163e726057a6e01d294fb4b29cf2cf0"
          },
          "new_training_authorized": false,
          "precise_closure": {
            "path": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/PRECISE_CLOSURE.json",
            "sha256": "12220f30e8a993c7c3748c9bb8940235628e26f2473ba316c5b604a0f4355c6d"
          },
          "report": {
            "path": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/REPORT.md",
            "sha256": "c3a9f81f7f6bd436483fc48904b249669dc3d6fa78ef79ac5953b88132898a7a"
          }
        }
      },
      "full_prior_campaign_snapshot_sha256": "ede4221e22eafe9fe9fcff760d1fc2ab4ddd572cb2e98929322de374304484a3"
    },
    {
      "campaign_id": "mvcnet-acm-r1-lab10-20261104",
      "closed_at": "2026-11-06T04:59:00+00:00",
      "closing_decision": {
        "all_interpretive_gates_pass": false,
        "claim_release": "none",
        "decision": "NO_SIGNAL",
        "interpretive_gates": {
          "P0-N0": true,
          "P0-R0": false
        },
        "primary_P0_minus_S0_pass": true,
        "research_stage": "acm_screen",
        "round_id": "mvcnet-acm-r1-screen-lab10-checkrepair2",
        "status": "frozen_rule_applied"
      },
      "closing_round": "mvcnet-acm-r1-screen-lab10-checkrepair2",
      "closing_run": {
        "analysis_receipt_sha256": "510b47660658f3dd969953cfea81a8f0f06e7240a9235bdb7dfad690ec6ff1c1",
        "artifact_manifest_sha256": "33535de00eadda737f59f7011965b57e042fb9485db6c80a054e1bb41a35808c",
        "contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-acm-r1-tx-20261105-checkrepair2",
        "transfer_bytes": 22225398,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized one cue4 B0/CE paired full comparison under independent 20h cap; exact protocol and full launch gated by acceptance."
    },
    {
      "campaign_id": "mvcnet-cue-aligned-two-arm-20261106",
      "closed_at": "2026-11-12T15:48:00.175401+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2"
      },
      "closing_round": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2",
      "closing_run": {
        "analysis_receipt_sha256": "8d1162a88ab3e42e674558e18d234462404bb2af3c0f5bf1658d3342dd385277",
        "artifact_manifest_sha256": "eccf1daa200552ee68f3546fa09e40f000bd4afe1dd49f70252c8059d1069f47",
        "contract_sha256": "df5a3476a80c807f4b81a0344683cd987b7977c9741516fc06d184f2a308ea57",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-cue-aligned-two-arm-tx-20261106-r1-py39fix1-sealfix2",
        "transfer_bytes": 5309246,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户确认独立累计12小时，Transaction最多9小时，另留3小时准备与收尾，纯资源排队不计，原四臂12拟合加12检查仅一次。"
    },
    {
      "campaign_id": "mvcnet-nonadjacent-context-filter-development-20261112",
      "closed_at": "2026-11-13T20:44:27.392779+00:00",
      "closing_decision": {
        "check_count": 12,
        "claim_status": "no_paper_claim",
        "decision": "STOP_EFFECT_GATE",
        "effect": {
          "by_fold_pp": {
            "seed73-outer0": {
              "B0": -0.6944444444444444,
              "C0": 1.0416666666666667,
              "N0": 3.298611111111111
            },
            "seed73-outer3": {
              "B0": 0.8680555555555556,
              "C0": 1.5625,
              "N0": 1.0416666666666667
            },
            "seed73-outer6": {
              "B0": 3.298611111111111,
              "C0": -1.3888888888888888,
              "N0": 1.5625
            }
          },
          "gates_passed": {
            "individual_risk": true,
            "mean_B0": false,
            "mean_C0": false,
            "mean_N0": true,
            "paired_coverage": false
          },
          "gates_sha256": "a044618a47fd51facc9000e2cdebd7df0e388d9eb132a8a785111aa92bdd76cb",
          "mean_pp": {
            "B0": 1.1574074074074074,
            "C0": 0.4050925925925926,
            "N0": 1.9675925925925926
          },
          "positive_subjects_on_all_three": 1,
          "status": "STOP_EFFECT_GATE"
        },
        "fit_count": 12,
        "mechanism": null,
        "next_training_authorized": false,
        "round_id": "mvcnet-nonadjacent-context-filter-development",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-nonadjacent-context-filter-development",
      "closing_run": {
        "analysis_receipt_sha256": "5aeb23d303b9ea5e35d5baec393455f3da1a30b0fa560a3d6220f609261b1a30",
        "artifact_manifest_sha256": "5546c584176bd04dc6eb98a052c8eccc38de1fcc9f1dc38225738dd16350d513",
        "contract_sha256": "86c240553fdc85c3f0976ed7a9397ff5acf802bc63fddbcd534d6df8473e0679",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-12_mvcnet_context_filter_lab10_development-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-12_mvcnet_context_filter_lab10_development-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-12_mvcnet_context_filter_lab10_development-tx",
        "transfer_bytes": 1696098,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User delegated autonomous execution of one exact matrix. Selected 34h cap from measured shared-load process estimate."
    },
    {
      "campaign_id": "mvcnet-acm-factorial-development-20261114",
      "closed_at": "2026-11-17T11:50:15.203575+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "SCREEN_POSITIVE",
        "factorial_gates": {
          "combined_gate_pass": true,
          "interaction_gate_pass": false,
          "mutual_promotion_gate_pass": false
        },
        "next_training_authorized": false,
        "prior_acm_decision": "NO_SIGNAL",
        "round_id": "mvcnet-acm-factorial-development",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-acm-factorial-development",
      "closing_run": {
        "contract_sha256": "319ed6901d80740804e782c889a427fbb5047983c78f08771e5abd89f0600a8c",
        "core_archive_sha256": "8a6c2cb5b6bf4d817a121a15ecf7adc9f92b14132b60d86870c4b53437f4b4c5",
        "core_bytes": 1886337,
        "core_files": 78,
        "core_manifest_sha256": "940cda90be97bd9a0a679b8282f8b95c682b0aa71390dce49875b891d6623ad0",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/acm-r1/factorial/CHECKFINISH2_CORE",
        "intake_scope": "verified_factorial_continuation_core",
        "normal_original_run_intake": false,
        "run_id": "2026-11-16_mvcnet_acm_factorial_checkfinish2",
        "source_run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
        "verified": true
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved exact P0-only S8B v4.0 matrix; original accounting anchor 2026-11-17T11:28:27+00:00."
    },
    {
      "campaign_id": "mvcnet-acm-s8-loso-stability-20261117",
      "closed_at": "2026-11-18T01:39:16.155182+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "reason": "the frozen promotion gates require both datasets to pass; at least one S8 dataset failed",
        "round_id": "mvcnet-acm-s8-loso-stability",
        "run_action": "STOP",
        "s8_dataset_gates": {
          "001": {
            "increment": false,
            "risk": true,
            "seed_stability": true,
            "total": true
          },
          "004": {
            "increment": false,
            "risk": true,
            "seed_stability": false,
            "total": false
          }
        }
      },
      "closing_round": "mvcnet-acm-s8-loso-stability",
      "closing_run": {
        "analysis_receipt_sha256": "d0b5350b73c9fa1fc67ddfa47cbbf41f98c61ed799d9bcf830a11a78abf38db0",
        "artifact_manifest_sha256": "4eaf489cb547c5179dfe693623a35d11ac246dc31f0c6b7e3453b4645ca59124",
        "contract_sha256": "2f67bb81cbe745c52cc0b9d1d5c1efce687f7022ce36a652e2f74f2e9f92cfad",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-tx",
        "transfer_bytes": 2142655,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved the independent 42-hour Zhou2016 and BNCI2014002 exact paired S8 LOSO extension after six completed Lab10 qualification tasks."
    },
    {
      "campaign_id": "mvcnet-acm-s8-loso-extension-20261118",
      "closed_at": "2026-11-19T14:51:12.841027+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "contract_sha256": "0d46c75539dd242e5a97fe3122d3b8d53b3c7297ef4fc92489377ea35e99cfdb",
        "decision": "NO_SIGNAL",
        "eligible_for_independent_confirmation": false,
        "intake_verified": true,
        "matrix_complete": true,
        "next_training_authorized": false,
        "prior_acm_r1_decision": "NO_SIGNAL",
        "reason": "at least one additional dataset fails the frozen promotion gates; retain the ACM-R1 NO_SIGNAL boundary",
        "round_id": "mvcnet-acm-s8-loso-extension-gpu10-pack1-checkfix1",
        "run_action": "STOP",
        "s8_extension_analysis": {
          "datasets": {
            "BNCI2014002": {
              "acc_percent": {
                "B0": 67.26785714285714,
                "P0": 69.85714285714286,
                "S0": 69.1875
              },
              "acm_increment": {
                "ci95_pp": [
                  -0.07142857142857124,
                  1.4375
                ],
                "harmed_subjects": 0,
                "leave_one_seed_out_pp": [
                  0.8035714285714283,
                  0.6473214285714288,
                  0.6919642857142856,
                  0.7142857142857143,
                  0.49107142857142866
                ],
                "mean_pp": 0.6696428571428571,
                "per_seed_pp": [
                  0.13392857142857245,
                  0.7589285714285704,
                  0.5803571428571433,
                  0.49107142857142855,
                  1.383928571428571
                ],
                "per_subject_pp": [
                  0.0,
                  -1.25,
                  3.5,
                  1.0,
                  -1.8749999999999987,
                  1.625,
                  1.125,
                  1.3750000000000029,
                  -0.75,
                  3.125,
                  0.0,
                  0.875,
                  -4.263256414560601e-15,
                  0.625
                ],
                "positive_subjects": 8,
                "worst_subject_pp": -1.8749999999999987
              },
              "combined": {
                "ci95_pp": [
                  0.2767857142857138,
                  5.071651785714266
                ],
                "harmed_subjects": 1,
                "leave_one_seed_out_pp": [
                  2.444196428571428,
                  2.5111607142857144,
                  3.0580357142857135,
                  2.7790178571428563,
                  2.1540178571428568
                ],
                "mean_pp": 2.5892857142857144,
                "per_seed_pp": [
                  3.1696428571428577,
                  2.9017857142857113,
                  0.7142857142857159,
                  1.830357142857144,
                  4.3303571428571415
                ],
                "per_subject_pp": [
                  -2.1250000000000013,
                  -1.25,
                  10.25,
                  12.0,
                  -5.875000000000002,
                  3.875,
                  0.0,
                  3.2499999999999987,
                  7.125,
                  1.1250000000000013,
                  3.375,
                  2.125,
                  0.375,
                  1.9999999999999987
                ],
                "positive_subjects": 10,
                "worst_subject_pp": -5.875000000000002
              },
              "gates": {
                "increment": false,
                "risk": true,
                "seed_stability": true,
                "total": true
              }
            },
            "Zhou2016": {
              "acc_percent": {
                "B0": 80.58888888888889,
                "P0": 82.5514939309057,
                "S0": 82.02474323062559
              },
              "acm_increment": {
                "ci95_pp": [
                  -0.08991596638655466,
                  0.9201680672268907
                ],
                "harmed_subjects": 0,
                "leave_one_seed_out_pp": [
                  0.6636321195144719,
                  0.502626050420167,
                  0.5047852474323067,
                  0.5907446311858076,
                  0.3719654528478058
                ],
                "mean_pp": 0.5267507002801117,
                "per_seed_pp": [
                  -0.020774976657328637,
                  0.6232492997198911,
                  0.6146125116713321,
                  0.27077497665732864,
                  1.1458916900093357
                ],
                "per_subject_pp": [
                  0.8403361344537814,
                  1.0,
                  -0.4,
                  0.6666666666666657
                ],
                "positive_subjects": 3,
                "worst_subject_pp": -0.4
              },
              "combined": {
                "ci95_pp": [
                  0.20000000000000143,
                  4.637815126050417
                ],
                "harmed_subjects": 0,
                "leave_one_seed_out_pp": [
                  2.249241363211951,
                  1.8672969187675053,
                  1.7930672268907566,
                  1.6203314659197012,
                  2.2830882352941178
                ],
                "mean_pp": 1.9626050420168062,
                "per_seed_pp": [
                  0.8160597572362285,
                  2.3438375350140106,
                  2.6407563025210052,
                  3.3316993464052267,
                  0.6806722689075606
                ],
                "per_subject_pp": [
                  6.050420168067222,
                  0.4,
                  1.4,
                  2.842170943040401e-15
                ],
                "positive_subjects": 4,
                "worst_subject_pp": 2.842170943040401e-15
              },
              "gates": {
                "increment": false,
                "risk": true,
                "seed_stability": true,
                "total": true
              }
            }
          },
          "extension_gates_all_pass": false,
          "metric_unit": "accuracy_pp",
          "prior_acm_r1": "NO_SIGNAL",
          "prior_s8_001_004_increment_gate": "NOT_PASSED",
          "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1"
        },
        "s8_extension_dataset_gates": {
          "BNCI2014002": {
            "increment": false,
            "risk": true,
            "seed_stability": true,
            "total": true
          },
          "Zhou2016": {
            "increment": false,
            "risk": true,
            "seed_stability": true,
            "total": true
          }
        },
        "supplemental_predictions": {
          "path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/checkfix1/supplemental_core/predictions.npz",
          "sha256": "25af664d2f6f8d0579a939c1a7f6305362c0e2616a5fd70cfd0280d54714c693"
        }
      },
      "closing_round": "mvcnet-acm-s8-loso-extension-gpu10-pack1-checkfix1",
      "closing_run": {
        "analysis_receipt_sha256": "03cacc13a31d84d3bfcc3981a4c938003fa7f107ad2e9a8691dacf58fe9d5047",
        "artifact_manifest_sha256": "5c2ed567e98cb13c346241bb22bd5abdf2a100e232c4de19590977b5e9abb8a8",
        "contract_sha256": "0d46c75539dd242e5a97fe3122d3b8d53b3c7297ef4fc92489377ea35e99cfdb",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-tx",
        "transfer_bytes": 2879694,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved proceeding with 004 S0 and D2, Lab10 capacity admission with no fixed card count"
    },
    {
      "campaign_id": "mvcnet-dual-bn-004-development-20261119",
      "closed_at": "2026-11-19T16:31:23.661248+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "d2_analysis": {
          "ci95_pp": [
            -0.6296976801362768,
            0.694860705003248
          ],
          "gates": {
            "effect": false,
            "risk": true,
            "seed_stability": false
          },
          "harmed_at_least_10pp": 0,
          "harmed_at_least_5pp": 0,
          "mean_pp": 0.033330544166457476,
          "paired_seed_count": 2,
          "per_seed_pp": [
            -0.5701896426870627,
            0.6368507310199777
          ],
          "per_subject_pp": [
            -1.6666666666666667,
            0.14705882352941177,
            0.9722222222222222,
            -0.40540540540540543,
            -1.2837837837837838,
            -0.20833333333333334,
            1.875,
            0.5921052631578947,
            0.2777777777777778
          ],
          "subject_count": 9
        },
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "reason": "D2 development screen failed at least one effect, seed, or risk gate",
        "round_id": "mvcnet-dual-bn-004-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-dual-bn-004-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "a1e424b56ccc43ea68a2cdffa90d706f262cea1a4196c1474304821b0b01f1d5",
        "artifact_manifest_sha256": "a27630b7749ac37ab532f0f20fb1ffffb1e695ca4d0ceb182a1ca3b75ae2bc11",
        "contract_sha256": "30329075e7b0c8530966aff6da5a842fb21d9c75d5753d2c80a58de7a408086a",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-19_mvcnet_dual_bn_004_lab10-tx",
        "transfer_bytes": 893085,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User-authorized 001 B0/D2/S0 paired LOSO development; 24 cumulative hours confirmed on 2026-11-20"
    },
    {
      "campaign_id": "mvcnet-dual-bn-001-development-20261120",
      "closed_at": "2026-11-20T15:49:44.574231+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "d2_analysis": {
          "contrasts": {
            "anchor": {
              "ci95_pp": [
                0.6462191358024691,
                3.9158950617283943
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 2.34375,
              "per_seed_pp": [
                1.9290123456790123,
                2.7584876543209877
              ],
              "per_subject_pp": [
                3.732638888888889,
                4.166666666666667,
                1.3020833333333333,
                2.7777777777777777,
                -2.6041666666666665,
                3.5590277777777777,
                6.423611111111111,
                -0.1736111111111111,
                1.9097222222222223
              ]
            },
            "noninferiority": {
              "ci95_pp": [
                -3.2021604938271606,
                -1.6203703703703702
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -2.4016203703703702,
              "per_seed_pp": [
                -2.0833333333333335,
                -2.7199074074074074
              ],
              "per_subject_pp": [
                -3.0381944444444446,
                -3.732638888888889,
                -2.4305555555555554,
                -1.1284722222222223,
                -0.9548611111111112,
                -3.4722222222222223,
                -4.340277777777778,
                -1.2152777777777777,
                -1.3020833333333333
              ]
            },
            "utility": {
              "ci95_pp": [
                -1.1863425925925926,
                0.925925925925926
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.05787037037037037,
              "per_seed_pp": [
                -0.15432098765432098,
                0.038580246913580245
              ],
              "per_subject_pp": [
                0.6944444444444444,
                0.4340277777777778,
                -1.1284722222222223,
                1.6493055555555556,
                -3.5590277777777777,
                0.08680555555555555,
                2.0833333333333335,
                -1.3888888888888888,
                0.6076388888888888
              ]
            }
          },
          "gates": {
            "anchor": true,
            "noninferiority_interval": false,
            "noninferiority_point": false,
            "risk": true,
            "utility": false
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-dual-bn-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-dual-bn-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "2a9c3aa26d12d0eed0c1dbda793496ea4736ba7256bb57a29db88fe77613a811",
        "artifact_manifest_sha256": "7e7d6d77e261adc208935ec7aba2de6efe8da8eaedb4c894a5f2bed43d5d8d0c",
        "contract_sha256": "2f61a543d54eb1293078ca94296c4fa7eed3997fc97f6aea673a95adf7a8c2ec",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-20_mvcnet_dual_bn_001_lab10-tx",
        "transfer_bytes": 1498314,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "2026-11-20 user authorized experiment and automatic budget; S0 W0 X0 001 development"
    },
    {
      "campaign_id": "mvcnet-cross-subject-block-exchange-001-20261120",
      "closed_at": "2026-11-21T17:18:41.965538+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "csbe_analysis": {
          "contrasts": {
            "W0_minus_S0": {
              "ci95_pp": [
                -0.2218364197530864,
                1.408179012345679
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.5787037037037037,
              "per_seed_pp": [
                0.5401234567901234,
                0.6172839506172839
              ],
              "per_subject_pp": [
                0.08680555555555555,
                -1.3020833333333333,
                2.34375,
                1.8229166666666667,
                2.34375,
                -0.5208333333333334,
                0.8680555555555556,
                0.0,
                -0.4340277777777778
              ]
            },
            "X0_minus_S0": {
              "ci95_pp": [
                0.2797067901234568,
                1.5625
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.8584104938271605,
              "per_seed_pp": [
                1.0223765432098766,
                0.6944444444444444
              ],
              "per_subject_pp": [
                0.2604166666666667,
                0.0,
                1.0416666666666667,
                1.1284722222222223,
                3.125,
                0.78125,
                1.5625,
                -0.3472222222222222,
                0.1736111111111111
              ]
            },
            "X0_minus_W0": {
              "ci95_pp": [
                -0.28935185185185186,
                0.8101851851851851
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.2797067901234568,
              "per_seed_pp": [
                0.48225308641975306,
                0.07716049382716049
              ],
              "per_subject_pp": [
                0.1736111111111111,
                1.3020833333333333,
                -1.3020833333333333,
                -0.6944444444444444,
                0.78125,
                1.3020833333333333,
                0.6944444444444444,
                -0.3472222222222222,
                0.6076388888888888
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.57638888888889,
              "arm": "W0",
              "correct": 395,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 66.14583333333333,
              "arm": "X0",
              "correct": 381,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.40277777777778,
              "arm": "W0",
              "correct": 250,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "X0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 82.29166666666667,
              "arm": "W0",
              "correct": 474,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 80.20833333333333,
              "arm": "X0",
              "correct": 462,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 51.736111111111114,
              "arm": "W0",
              "correct": 298,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 53.81944444444444,
              "arm": "X0",
              "correct": 310,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 43.229166666666664,
              "arm": "W0",
              "correct": 249,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "X0",
              "correct": 254,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 43.40277777777778,
              "arm": "W0",
              "correct": 250,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 44.96527777777778,
              "arm": "X0",
              "correct": 259,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 59.895833333333336,
              "arm": "W0",
              "correct": 345,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 62.15277777777778,
              "arm": "X0",
              "correct": 358,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 71.18055555555556,
              "arm": "W0",
              "correct": 410,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 70.65972222222223,
              "arm": "X0",
              "correct": 407,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 67.88194444444444,
              "arm": "W0",
              "correct": 391,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 69.79166666666667,
              "arm": "X0",
              "correct": 402,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 65.27777777777777,
              "arm": "W0",
              "correct": 376,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 68.05555555555556,
              "arm": "X0",
              "correct": 392,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 42.1875,
              "arm": "W0",
              "correct": 243,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "X0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 80.55555555555556,
              "arm": "W0",
              "correct": 464,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "X0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 53.125,
              "arm": "W0",
              "correct": 306,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.65277777777778,
              "arm": "X0",
              "correct": 286,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.61805555555556,
              "arm": "W0",
              "correct": 257,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 45.3125,
              "arm": "X0",
              "correct": 261,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 42.53472222222222,
              "arm": "W0",
              "correct": 245,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 43.576388888888886,
              "arm": "X0",
              "correct": 251,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "W0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 60.416666666666664,
              "arm": "X0",
              "correct": 348,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 73.4375,
              "arm": "W0",
              "correct": 423,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 73.26388888888889,
              "arm": "X0",
              "correct": 422,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 68.22916666666667,
              "arm": "W0",
              "correct": 393,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "X0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "x0_vs_s0_both_seeds_positive": true,
            "x0_vs_s0_mean_at_least_1pp": false,
            "x0_vs_s0_subject_risk": true,
            "x0_vs_w0_both_seeds_positive": true,
            "x0_vs_w0_mean_at_least_0_5pp": false
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-cross-subject-block-exchange-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-cross-subject-block-exchange-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "c49791a7abf934b0b053e65c0bf2dc40a9a247f42ce557b9a4334fef0673b5b8",
        "artifact_manifest_sha256": "525e72557a712d36c449c7f2bdbf4fc91e6a7956bda2c42e4fc68614f36cc04b",
        "contract_sha256": "603cff7167906e833f841880dcff172c46e3478d3784f72275e939597d78ec56",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-20_mvcnet_block_exchange_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-20_mvcnet_block_exchange_001_lab10-tx",
        "transfer_bytes": 1509898,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "Source gate verified. User authorized exactly one eligible development run with measured cost. Initial cumulative engineering allowance includes prior source screens from 00:30 CST."
    },
    {
      "campaign_id": "mvcnet-envelope-rotation-001-20261122",
      "closed_at": "2026-11-22T09:21:44.161264+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "envr_analysis": {
          "contrasts": {
            "C0_minus_I0": {
              "ci95_pp": [
                -2.179783950617284,
                1.7845775462962752
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.30864197530864196,
              "per_seed_pp": [
                -1.1766975308641976,
                0.5594135802469136
              ],
              "per_subject_pp": [
                -0.6076388888888888,
                -3.6458333333333335,
                -1.0416666666666667,
                -0.3472222222222222,
                -2.4305555555555554,
                0.0,
                -4.340277777777778,
                4.253472222222222,
                5.381944444444445
              ]
            },
            "C0_minus_S0": {
              "ci95_pp": [
                -0.9452160493827161,
                0.7908950617283951
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.038580246913580245,
              "per_seed_pp": [
                0.05787037037037037,
                0.019290123456790122
              ],
              "per_subject_pp": [
                0.08680555555555555,
                -3.3854166666666665,
                0.9548611111111112,
                0.3472222222222222,
                0.1736111111111111,
                -0.5208333333333334,
                0.6076388888888888,
                1.8229166666666667,
                0.2604166666666667
              ]
            },
            "I0_minus_S0": {
              "ci95_pp": [
                -1.5046296296296295,
                2.0736882716049383
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 1,
              "mean_pp": 0.3472222222222222,
              "per_seed_pp": [
                1.2345679012345678,
                -0.5401234567901234
              ],
              "per_subject_pp": [
                0.6944444444444444,
                0.2604166666666667,
                1.9965277777777777,
                0.6944444444444444,
                2.6041666666666665,
                -0.5208333333333334,
                4.947916666666667,
                -2.4305555555555554,
                -5.121527777777778
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.57638888888889,
              "arm": "I0",
              "correct": 395,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "C0",
              "correct": 389,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 44.791666666666664,
              "arm": "I0",
              "correct": 258,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 40.625,
              "arm": "C0",
              "correct": 234,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 82.8125,
              "arm": "I0",
              "correct": 477,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 81.59722222222223,
              "arm": "C0",
              "correct": 470,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 52.77777777777778,
              "arm": "I0",
              "correct": 304,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 52.43055555555556,
              "arm": "C0",
              "correct": 302,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 45.65972222222222,
              "arm": "I0",
              "correct": 263,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 38.71527777777778,
              "arm": "C0",
              "correct": 223,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 43.75,
              "arm": "I0",
              "correct": 252,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 43.75,
              "arm": "C0",
              "correct": 252,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 63.19444444444444,
              "arm": "I0",
              "correct": 364,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 58.68055555555556,
              "arm": "C0",
              "correct": 338,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 70.48611111111111,
              "arm": "I0",
              "correct": 406,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 74.82638888888889,
              "arm": "C0",
              "correct": 431,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 65.79861111111111,
              "arm": "I0",
              "correct": 379,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 69.09722222222223,
              "arm": "C0",
              "correct": 398,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 66.49305555555556,
              "arm": "I0",
              "correct": 383,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 66.31944444444444,
              "arm": "C0",
              "correct": 382,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 43.923611111111114,
              "arm": "I0",
              "correct": 253,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 40.798611111111114,
              "arm": "C0",
              "correct": 235,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 79.34027777777777,
              "arm": "I0",
              "correct": 457,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 78.47222222222223,
              "arm": "C0",
              "correct": 452,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.826388888888886,
              "arm": "I0",
              "correct": 287,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.479166666666664,
              "arm": "C0",
              "correct": 285,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 42.708333333333336,
              "arm": "I0",
              "correct": 246,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.791666666666664,
              "arm": "C0",
              "correct": 258,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 42.1875,
              "arm": "I0",
              "correct": 243,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 42.1875,
              "arm": "C0",
              "correct": 243,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 66.14583333333333,
              "arm": "I0",
              "correct": 381,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 61.979166666666664,
              "arm": "C0",
              "correct": 357,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 69.27083333333333,
              "arm": "I0",
              "correct": 399,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 73.4375,
              "arm": "C0",
              "correct": 423,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 60.9375,
              "arm": "I0",
              "correct": 351,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 68.40277777777777,
              "arm": "C0",
              "correct": 394,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "c0_vs_i0_both_seeds_positive": false,
            "c0_vs_i0_mean_at_least_0_5pp": false,
            "c0_vs_s0_both_seeds_positive": true,
            "c0_vs_s0_mean_at_least_1pp": false,
            "c0_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-envelope-rotation-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-envelope-rotation-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "805ea5f744b764ee0aa1f9dae5ff2eefe1f79ad55f91de89121043b540a99c9d",
        "artifact_manifest_sha256": "9b3addfe80bdfef92bc8521d8955db13a15c8fe18412d8f0e1a2e729a711037e",
        "contract_sha256": "b2580fa756600f1d63b875b0d87f32f796c102c17d20d508e181b432430d96e8",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-tx",
        "transfer_bytes": 1513051,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User-authorized first eligible candidate. CPU and source GPU qualification only under interim budget; cumulative accounting includes screening from 16:41 CST."
    },
    {
      "campaign_id": "mvcnet-rate125-001-20261122",
      "closed_at": "2026-11-22T15:02:17.510347+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "envr_analysis": {
          "contrasts": {
            "A125_minus_S0": {
              "ci95_pp": [
                -0.9452160493827161,
                1.4467592592592593
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.2025462962962963,
              "per_seed_pp": [
                0.5015432098765432,
                -0.09645061728395062
              ],
              "per_subject_pp": [
                0.1736111111111111,
                -1.9097222222222223,
                1.0416666666666667,
                1.5625,
                3.90625,
                -1.3888888888888888,
                1.1284722222222223,
                -2.0833333333333335,
                -0.6076388888888888
              ]
            },
            "T125_minus_A125": {
              "ci95_pp": [
                -1.0995370370370372,
                1.1574074074074074
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.09645061728395062,
              "per_seed_pp": [
                0.7330246913580247,
                -0.5401234567901234
              ],
              "per_subject_pp": [
                0.9548611111111112,
                0.6944444444444444,
                0.1736111111111111,
                -0.8680555555555556,
                -1.3888888888888888,
                2.7777777777777777,
                -3.6458333333333335,
                1.0416666666666667,
                1.1284722222222223
              ]
            },
            "T125_minus_S0": {
              "ci95_pp": [
                -0.7137345679012346,
                1.215277777777778
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.29899691358024694,
              "per_seed_pp": [
                1.2345679012345678,
                -0.6365740740740741
              ],
              "per_subject_pp": [
                1.1284722222222223,
                -1.2152777777777777,
                1.2152777777777777,
                0.6944444444444444,
                2.517361111111111,
                1.3888888888888888,
                -2.517361111111111,
                -1.0416666666666667,
                0.5208333333333334
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "A125",
              "correct": 389,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.05555555555556,
              "arm": "T125",
              "correct": 392,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.229166666666664,
              "arm": "A125",
              "correct": 249,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 40.97222222222222,
              "arm": "T125",
              "correct": 236,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "A125",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 81.94444444444444,
              "arm": "T125",
              "correct": 472,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 55.38194444444444,
              "arm": "A125",
              "correct": 319,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 53.298611111111114,
              "arm": "T125",
              "correct": 307,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 44.270833333333336,
              "arm": "A125",
              "correct": 255,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 44.270833333333336,
              "arm": "T125",
              "correct": 255,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 44.61805555555556,
              "arm": "A125",
              "correct": 257,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 47.74305555555556,
              "arm": "T125",
              "correct": 275,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "A125",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 59.548611111111114,
              "arm": "T125",
              "correct": 343,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 70.83333333333333,
              "arm": "A125",
              "correct": 408,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 72.56944444444444,
              "arm": "T125",
              "correct": 418,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 65.97222222222223,
              "arm": "A125",
              "correct": 380,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "T125",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 66.49305555555556,
              "arm": "A125",
              "correct": 383,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 67.88194444444444,
              "arm": "T125",
              "correct": 391,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 41.145833333333336,
              "arm": "A125",
              "correct": 237,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 44.791666666666664,
              "arm": "T125",
              "correct": 258,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 82.11805555555556,
              "arm": "A125",
              "correct": 473,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 78.64583333333333,
              "arm": "T125",
              "correct": 453,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 48.958333333333336,
              "arm": "A125",
              "correct": 282,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.30555555555556,
              "arm": "T125",
              "correct": 284,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 46.701388888888886,
              "arm": "A125",
              "correct": 269,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 43.923611111111114,
              "arm": "T125",
              "correct": 253,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 39.583333333333336,
              "arm": "A125",
              "correct": 228,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 42.013888888888886,
              "arm": "T125",
              "correct": 242,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 60.416666666666664,
              "arm": "A125",
              "correct": 348,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 54.861111111111114,
              "arm": "T125",
              "correct": 316,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 69.61805555555556,
              "arm": "A125",
              "correct": 401,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 69.96527777777777,
              "arm": "T125",
              "correct": 403,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 69.79166666666667,
              "arm": "A125",
              "correct": 402,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 68.57638888888889,
              "arm": "T125",
              "correct": 395,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "t125_vs_a125_both_seeds_positive": false,
            "t125_vs_a125_mean_at_least_0_5pp": false,
            "t125_vs_s0_both_seeds_noninferior": true,
            "t125_vs_s0_mean_at_least_minus_1pp": true,
            "t125_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-rate125-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-rate125-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "b966ce08e419120d40a3a587cc4dd56e0f2d81494f1c87ba6e2096e1e3af0c1a",
        "artifact_manifest_sha256": "4bef95abf1155ca4cb979bcc1e271d8f097b2f95b916bd1cb3c6fb92b774bce2",
        "contract_sha256": "146dae04f6ca68f5c0d47995f37d18a3862081918d3ff6c7d3b8dd095cd035fd",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-22_mvcnet_rate125_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_rate125_001_lab10-tx",
        "transfer_bytes": 1506970,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "First qualified user-authorized candidate, source-only qualification interim; cumulative accounting since 22:55 CST."
    },
    {
      "campaign_id": "mvcnet-auxrate-001-20261122",
      "closed_at": "2026-11-23T02:39:17.911907+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "envr_analysis": {
          "contrasts": {
            "J8_minus_S0": {
              "ci95_pp": [
                -0.2700617283950617,
                1.3503086419753088
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.5690586419753086,
              "per_seed_pp": [
                0.5208333333333334,
                0.6172839506172839
              ],
              "per_subject_pp": [
                1.8229166666666667,
                0.6076388888888888,
                1.9965277777777777,
                0.6076388888888888,
                1.7361111111111112,
                -0.4340277777777778,
                1.4756944444444444,
                -1.2152777777777777,
                -1.4756944444444444
              ]
            },
            "P8_minus_J8": {
              "ci95_pp": [
                -0.49189814814814814,
                0.9162808641975307
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.24112654320987653,
              "per_seed_pp": [
                0.2700617283950617,
                0.21219135802469136
              ],
              "per_subject_pp": [
                1.3888888888888888,
                0.6944444444444444,
                0.2604166666666667,
                0.3472222222222222,
                -1.9965277777777777,
                -0.2604166666666667,
                0.6944444444444444,
                1.8229166666666667,
                -0.78125
              ]
            },
            "P8_minus_S0": {
              "ci95_pp": [
                -0.2700617283950618,
                1.8229166666666667
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.8101851851851852,
              "per_seed_pp": [
                0.7908950617283951,
                0.8294753086419753
              ],
              "per_subject_pp": [
                3.2118055555555554,
                1.3020833333333333,
                2.2569444444444446,
                0.9548611111111112,
                -0.2604166666666667,
                -0.6944444444444444,
                2.170138888888889,
                0.6076388888888888,
                -2.2569444444444446
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.92361111111111,
              "arm": "J8",
              "correct": 397,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 69.09722222222223,
              "arm": "P8",
              "correct": 398,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.229166666666664,
              "arm": "J8",
              "correct": 249,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 44.791666666666664,
              "arm": "P8",
              "correct": 258,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 82.29166666666667,
              "arm": "J8",
              "correct": 474,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 81.59722222222223,
              "arm": "P8",
              "correct": 470,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 51.736111111111114,
              "arm": "J8",
              "correct": 298,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 52.604166666666664,
              "arm": "P8",
              "correct": 303,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 40.625,
              "arm": "J8",
              "correct": 234,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 40.27777777777778,
              "arm": "P8",
              "correct": 232,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 43.05555555555556,
              "arm": "J8",
              "correct": 248,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "P8",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 60.763888888888886,
              "arm": "J8",
              "correct": 350,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "P8",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 70.83333333333333,
              "arm": "J8",
              "correct": 408,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 73.4375,
              "arm": "P8",
              "correct": 423,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 69.96527777777777,
              "arm": "J8",
              "correct": 403,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "P8",
              "correct": 384,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 68.40277777777777,
              "arm": "J8",
              "correct": 394,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 71.00694444444444,
              "arm": "P8",
              "correct": 409,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 46.18055555555556,
              "arm": "J8",
              "correct": 266,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 46.00694444444444,
              "arm": "P8",
              "correct": 265,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 79.86111111111111,
              "arm": "J8",
              "correct": 460,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 81.07638888888889,
              "arm": "P8",
              "correct": 467,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 50.69444444444444,
              "arm": "J8",
              "correct": 292,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 50.520833333333336,
              "arm": "P8",
              "correct": 291,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 46.00694444444444,
              "arm": "J8",
              "correct": 265,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 42.361111111111114,
              "arm": "P8",
              "correct": 244,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 43.05555555555556,
              "arm": "J8",
              "correct": 248,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 41.49305555555556,
              "arm": "P8",
              "correct": 239,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 61.63194444444444,
              "arm": "J8",
              "correct": 355,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 62.5,
              "arm": "P8",
              "correct": 360,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 71.35416666666667,
              "arm": "J8",
              "correct": 411,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "P8",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 64.0625,
              "arm": "J8",
              "correct": 369,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 65.79861111111111,
              "arm": "P8",
              "correct": 379,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "p8_vs_j8_both_seeds_positive": true,
            "p8_vs_j8_mean_at_least_0_5pp": false,
            "p8_vs_s0_both_seeds_noninferior": true,
            "p8_vs_s0_mean_at_least_minus_1pp": true,
            "p8_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-auxspace-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-auxspace-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "0cf7cafe2ac2b1b2e9c547a22a109d5e97cbca69118531267ba58c8b061d31f7",
        "artifact_manifest_sha256": "15afa3a81e3c11bd8f98687dda0e6b5bd0aada5a35083ab319e4d9f1788a41d5",
        "contract_sha256": "1c09b99b026ff56392fd91b12aa3332650fdbe5e488813502ba2c53f69069bc1",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_auxspace_001_lab10-tx",
        "transfer_bytes": 1505553,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "New user-authorized bounded MVCNet campaign with one qualifying scientific run; 3h engineering envelope, auto size from source qualification."
    },
    {
      "campaign_id": "mvcnet-reflectcvc-001-20261123",
      "closed_at": "2026-11-23T13:12:25.635158+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "envr_analysis": {
          "contrasts": {
            "H0_minus_K0": {
              "ci95_pp": [
                -0.028935185185185182,
                0.9837962962962963
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.4050925925925926,
              "per_seed_pp": [
                0.9259259259259259,
                -0.11574074074074074
              ],
              "per_subject_pp": [
                0.6076388888888888,
                -0.5208333333333334,
                0.2604166666666667,
                0.08680555555555555,
                0.4340277777777778,
                0.0,
                0.5208333333333334,
                2.4305555555555554,
                -0.1736111111111111
              ]
            },
            "H0_minus_S0": {
              "ci95_pp": [
                -0.8584104938271605,
                0.916280864197531
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.05787037037037037,
              "per_seed_pp": [
                0.9645061728395061,
                -0.8487654320987654
              ],
              "per_subject_pp": [
                1.1284722222222223,
                -1.5625,
                1.3020833333333333,
                -2.170138888888889,
                1.8229166666666667,
                -0.6076388888888888,
                1.0416666666666667,
                0.6076388888888888,
                -1.0416666666666667
              ]
            },
            "K0_minus_S0": {
              "ci95_pp": [
                -1.1381172839506173,
                0.4340277777777778
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.3472222222222222,
              "per_seed_pp": [
                0.038580246913580245,
                -0.7330246913580247
              ],
              "per_subject_pp": [
                0.5208333333333334,
                -1.0416666666666667,
                1.0416666666666667,
                -2.2569444444444446,
                1.3888888888888888,
                -0.6076388888888888,
                0.5208333333333334,
                -1.8229166666666667,
                -0.8680555555555556
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 67.1875,
              "arm": "K0",
              "correct": 387,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 69.09722222222223,
              "arm": "H0",
              "correct": 398,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.40277777777778,
              "arm": "K0",
              "correct": 250,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "H0",
              "correct": 247,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 79.86111111111111,
              "arm": "K0",
              "correct": 460,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 81.77083333333333,
              "arm": "H0",
              "correct": 471,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 50.86805555555556,
              "arm": "K0",
              "correct": 293,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 52.43055555555556,
              "arm": "H0",
              "correct": 302,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 41.145833333333336,
              "arm": "K0",
              "correct": 237,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 43.40277777777778,
              "arm": "H0",
              "correct": 250,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 42.013888888888886,
              "arm": "K0",
              "correct": 242,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 44.96527777777778,
              "arm": "H0",
              "correct": 259,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 61.458333333333336,
              "arm": "K0",
              "correct": 354,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 60.763888888888886,
              "arm": "H0",
              "correct": 350,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 71.875,
              "arm": "K0",
              "correct": 414,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 71.875,
              "arm": "H0",
              "correct": 414,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 69.27083333333333,
              "arm": "K0",
              "correct": 399,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 68.22916666666667,
              "arm": "H0",
              "correct": 393,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "K0",
              "correct": 389,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 66.84027777777777,
              "arm": "H0",
              "correct": 385,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 42.708333333333336,
              "arm": "K0",
              "correct": 246,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 42.1875,
              "arm": "H0",
              "correct": 243,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 80.38194444444444,
              "arm": "K0",
              "correct": 463,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 78.99305555555556,
              "arm": "H0",
              "correct": 455,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 45.833333333333336,
              "arm": "K0",
              "correct": 264,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 44.44444444444444,
              "arm": "H0",
              "correct": 256,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.791666666666664,
              "arm": "K0",
              "correct": 258,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 43.40277777777778,
              "arm": "H0",
              "correct": 250,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 43.75,
              "arm": "K0",
              "correct": 252,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 40.798611111111114,
              "arm": "H0",
              "correct": 235,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 59.02777777777778,
              "arm": "K0",
              "correct": 340,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 60.763888888888886,
              "arm": "H0",
              "correct": 350,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 69.09722222222223,
              "arm": "K0",
              "correct": 398,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 73.95833333333333,
              "arm": "H0",
              "correct": 426,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 65.97222222222223,
              "arm": "K0",
              "correct": 380,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "H0",
              "correct": 384,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "h0_vs_k0_both_seeds_positive": false,
            "h0_vs_k0_mean_at_least_0_5pp": false,
            "h0_vs_s0_both_seeds_positive": false,
            "h0_vs_s0_cross_hand_errors_each_seed": true,
            "h0_vs_s0_mean_at_least_1pp": false,
            "h0_vs_s0_subject_risk": true
          },
          "hand_confusions_by_seed": {
            "0": {
              "H0": 263,
              "K0": 288,
              "S0": 283
            },
            "4": {
              "H0": 295,
              "K0": 290,
              "S0": 308
            }
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-reflectcvc-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-reflectcvc-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "4c748749159007dc45b41fb7b47d2116e08e80c9582e67859a01ec8884a239d6",
        "artifact_manifest_sha256": "e53b9f36983c397b8a7d8a7652ac0ef894221d4dd3fd3004b642d8109dc4ec6c",
        "contract_sha256": "5203100406b966ec7c6c0b4d4eeaa8f7b306ca6d7ec0d8594230aaa82ffd9ae5",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-tx",
        "transfer_bytes": 1438267,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized sequential screening, measured cost sizing and dispatch of the first qualified 001 development Run."
    },
    {
      "campaign_id": "mvcnet-cvcdropout-001-20261123",
      "closed_at": "2026-11-26T08:25:19.357423+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "envr_analysis": {
          "contrasts": {
            "D0_minus_I0": {
              "ci95_pp": [
                -1.369598765432099,
                0.646219135802469
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.29899691358024694,
              "per_seed_pp": [
                0.38580246913580246,
                -0.9837962962962963
              ],
              "per_subject_pp": [
                1.4756944444444444,
                -1.7361111111111112,
                -0.08680555555555555,
                1.2152777777777777,
                1.2152777777777777,
                -3.298611111111111,
                -1.7361111111111112,
                0.08680555555555555,
                0.1736111111111111
              ]
            },
            "D0_minus_S0": {
              "ci95_pp": [
                -1.4274691358024691,
                0.4340277777777778
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.46296296296296297,
              "per_seed_pp": [
                0.1736111111111111,
                -1.099537037037037
              ],
              "per_subject_pp": [
                0.78125,
                -2.6909722222222223,
                0.08680555555555555,
                1.0416666666666667,
                1.3888888888888888,
                -2.6909722222222223,
                -0.6076388888888888,
                -0.08680555555555555,
                -1.3888888888888888
              ]
            },
            "I0_minus_S0": {
              "ci95_pp": [
                -0.6655092592592593,
                0.3375771604938272
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.16396604938271606,
              "per_seed_pp": [
                -0.21219135802469136,
                -0.11574074074074074
              ],
              "per_subject_pp": [
                -0.6944444444444444,
                -0.9548611111111112,
                0.1736111111111111,
                -0.1736111111111111,
                0.1736111111111111,
                0.6076388888888888,
                1.1284722222222223,
                -0.1736111111111111,
                -1.5625
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 67.36111111111111,
              "arm": "I0",
              "correct": 388,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 70.3125,
              "arm": "D0",
              "correct": 405,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 42.361111111111114,
              "arm": "I0",
              "correct": 244,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "D0",
              "correct": 241,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 80.20833333333333,
              "arm": "I0",
              "correct": 462,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 78.99305555555556,
              "arm": "D0",
              "correct": 455,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 50.520833333333336,
              "arm": "I0",
              "correct": 291,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 53.125,
              "arm": "D0",
              "correct": 306,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 40.625,
              "arm": "I0",
              "correct": 234,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "D0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "I0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 40.97222222222222,
              "arm": "D0",
              "correct": 236,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 62.326388888888886,
              "arm": "I0",
              "correct": 359,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 61.458333333333336,
              "arm": "D0",
              "correct": 354,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 71.35416666666667,
              "arm": "I0",
              "correct": 411,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 72.56944444444444,
              "arm": "D0",
              "correct": 418,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 65.97222222222223,
              "arm": "I0",
              "correct": 380,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 67.70833333333333,
              "arm": "D0",
              "correct": 390,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 64.93055555555556,
              "arm": "I0",
              "correct": 374,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 64.93055555555556,
              "arm": "D0",
              "correct": 374,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 43.923611111111114,
              "arm": "I0",
              "correct": 253,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 40.97222222222222,
              "arm": "D0",
              "correct": 236,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 78.29861111111111,
              "arm": "I0",
              "correct": 451,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 79.34027777777777,
              "arm": "D0",
              "correct": 457,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 50.34722222222222,
              "arm": "I0",
              "correct": 290,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 50.173611111111114,
              "arm": "D0",
              "correct": 289,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "I0",
              "correct": 247,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.61805555555556,
              "arm": "D0",
              "correct": 257,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "I0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 40.625,
              "arm": "D0",
              "correct": 234,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 59.375,
              "arm": "I0",
              "correct": 342,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 56.770833333333336,
              "arm": "D0",
              "correct": 327,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 72.91666666666667,
              "arm": "I0",
              "correct": 420,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 71.875,
              "arm": "D0",
              "correct": 414,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 67.88194444444444,
              "arm": "I0",
              "correct": 391,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 66.49305555555556,
              "arm": "D0",
              "correct": 383,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "d0_vs_i0_both_seeds_positive": false,
            "d0_vs_i0_mean_at_least_0_5pp": false,
            "d0_vs_s0_both_seeds_positive": false,
            "d0_vs_s0_mean_at_least_1pp": false,
            "d0_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-cvcdropout-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-cvcdropout-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "55c2492b55087166d9e8f997adc1e0d657761d77130b70811c4481e6d8799796",
        "artifact_manifest_sha256": "2bdf2655fa887c696444fd5924d941dbf48ad50fe364ac4e6e41b9992109ce85",
        "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
        "transfer_bytes": 1416234,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested sequential MVCNet v4.1 screening and original measured-cost Lab10 dispatch for the first eligible candidate. G0 passes the prospective source gate; prior campaign closed. Accounting includes screening from 2026-11-26T08:03:23Z."
    },
    {
      "campaign_id": "mvcnet-centralrow-001-20261126",
      "closed_at": "2026-11-27T06:55:37.532806+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "envr_analysis": {
          "contrasts": {
            "G0_minus_J0": {
              "ci95_pp": [
                -0.4340277777777778,
                0.9066358024691357
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.23148148148148148,
              "per_seed_pp": [
                -0.23148148148148148,
                0.6944444444444444
              ],
              "per_subject_pp": [
                -0.2604166666666667,
                1.6493055555555556,
                -0.9548611111111112,
                -0.2604166666666667,
                -1.3020833333333333,
                0.1736111111111111,
                0.08680555555555555,
                1.3020833333333333,
                1.6493055555555556
              ]
            },
            "G0_minus_S0": {
              "ci95_pp": [
                -0.45331790123456783,
                0.5979938271604938
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.08680555555555555,
              "per_seed_pp": [
                0.0,
                0.1736111111111111
              ],
              "per_subject_pp": [
                0.08680555555555555,
                -0.3472222222222222,
                0.6944444444444444,
                0.6076388888888888,
                0.0,
                -1.4756944444444444,
                1.3888888888888888,
                0.5208333333333334,
                -0.6944444444444444
              ]
            },
            "J0_minus_S0": {
              "ci95_pp": [
                -1.128472222222222,
                0.80054012345679
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.14467592592592593,
              "per_seed_pp": [
                0.23148148148148148,
                -0.5208333333333334
              ],
              "per_subject_pp": [
                0.3472222222222222,
                -1.9965277777777777,
                1.6493055555555556,
                0.8680555555555556,
                1.3020833333333333,
                -1.6493055555555556,
                1.3020833333333333,
                -0.78125,
                -2.34375
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.75,
              "arm": "J0",
              "correct": 396,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 66.84027777777777,
              "arm": "G0",
              "correct": 385,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 42.53472222222222,
              "arm": "J0",
              "correct": 245,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.05555555555556,
              "arm": "G0",
              "correct": 248,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 81.07638888888889,
              "arm": "J0",
              "correct": 467,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 79.86111111111111,
              "arm": "G0",
              "correct": 460,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 53.99305555555556,
              "arm": "J0",
              "correct": 311,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 51.90972222222222,
              "arm": "G0",
              "correct": 299,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 43.05555555555556,
              "arm": "J0",
              "correct": 248,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 39.583333333333336,
              "arm": "G0",
              "correct": 228,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 42.53472222222222,
              "arm": "J0",
              "correct": 245,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 42.361111111111114,
              "arm": "G0",
              "correct": 244,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 59.548611111111114,
              "arm": "J0",
              "correct": 343,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 60.9375,
              "arm": "G0",
              "correct": 351,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 70.83333333333333,
              "arm": "J0",
              "correct": 408,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 74.13194444444444,
              "arm": "G0",
              "correct": 427,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.49305555555556,
              "arm": "J0",
              "correct": 383,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 68.05555555555556,
              "arm": "G0",
              "correct": 392,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 65.625,
              "arm": "J0",
              "correct": 378,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "G0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 41.666666666666664,
              "arm": "J0",
              "correct": 240,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 44.44444444444444,
              "arm": "G0",
              "correct": 256,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 80.38194444444444,
              "arm": "J0",
              "correct": 463,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 79.6875,
              "arm": "G0",
              "correct": 459,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 48.958333333333336,
              "arm": "J0",
              "correct": 282,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 50.520833333333336,
              "arm": "G0",
              "correct": 291,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 42.708333333333336,
              "arm": "J0",
              "correct": 246,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 43.576388888888886,
              "arm": "G0",
              "correct": 251,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 41.145833333333336,
              "arm": "J0",
              "correct": 237,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 41.666666666666664,
              "arm": "G0",
              "correct": 240,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 62.5,
              "arm": "J0",
              "correct": 360,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "G0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "J0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 71.52777777777777,
              "arm": "G0",
              "correct": 412,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 65.79861111111111,
              "arm": "J0",
              "correct": 379,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "G0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "g0_vs_j0_both_seeds_positive": false,
            "g0_vs_j0_mean_at_least_0_5pp": false,
            "g0_vs_s0_both_seeds_positive": false,
            "g0_vs_s0_mean_at_least_1pp": false,
            "g0_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-centralrow-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-centralrow-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "c85dbadd5157178e81f729685241e84fd38e360a9ccce287a8d72290b57b79c1",
        "artifact_manifest_sha256": "f50edaf790c666635eb4276d6968f91393488a73365351cb9ef4de3d9cc21158",
        "contract_sha256": "83e76e54b73dc2ab298cecc85342c600359e31daa4724646fa87d3bc1670528f",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-26_mvcnet_centralrow_001_lab10-tx",
        "transfer_bytes": 1507428,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested a serial v4.1 screen, early stop on first qualified candidate and same-Run Lab10 dispatch. IFNet anti-alias source gate passed after two prior stops. Three hours from task start for work through engineering qualification."
    },
    {
      "campaign_id": "mvcnet-pool-antialias-001-20261127",
      "closed_at": "2026-11-27T14:20:04.937335+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "pool_antialias_analysis": {
          "contrasts": {
            "G0_minus_J0": {
              "ci95_pp": [
                -1.4467592592592593,
                1.2538580246913582
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.19290123456790123,
              "per_seed_pp": [
                -0.19290123456790123,
                -0.19290123456790123
              ],
              "per_subject_pp": [
                3.90625,
                -1.3020833333333333,
                -0.1736111111111111,
                2.517361111111111,
                0.6944444444444444,
                -2.6041666666666665,
                -1.2152777777777777,
                -2.2569444444444446,
                -1.3020833333333333
              ]
            },
            "G0_minus_S0": {
              "ci95_pp": [
                -1.552854938271605,
                0.6269290123456791
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.5111882716049383,
              "per_seed_pp": [
                -0.07716049382716049,
                -0.9452160493827161
              ],
              "per_subject_pp": [
                2.7777777777777777,
                -1.8229166666666667,
                0.3472222222222222,
                1.0416666666666667,
                0.5208333333333334,
                -2.6041666666666665,
                -1.7361111111111112,
                -1.6493055555555556,
                -1.4756944444444444
              ]
            },
            "J0_minus_S0": {
              "ci95_pp": [
                -0.7523148148148149,
                0.09645061728395062
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.31828703703703703,
              "per_seed_pp": [
                0.11574074074074074,
                -0.7523148148148148
              ],
              "per_subject_pp": [
                -1.1284722222222223,
                -0.5208333333333334,
                0.5208333333333334,
                -1.4756944444444444,
                -0.1736111111111111,
                0.0,
                -0.5208333333333334,
                0.6076388888888888,
                -0.1736111111111111
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "J0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 70.13888888888889,
              "arm": "G0",
              "correct": 404,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.75,
              "arm": "J0",
              "correct": 252,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.229166666666664,
              "arm": "G0",
              "correct": 249,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 79.34027777777777,
              "arm": "J0",
              "correct": 457,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 79.6875,
              "arm": "G0",
              "correct": 459,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 48.958333333333336,
              "arm": "J0",
              "correct": 282,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 51.388888888888886,
              "arm": "G0",
              "correct": 296,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 40.27777777777778,
              "arm": "J0",
              "correct": 232,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "G0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 46.354166666666664,
              "arm": "J0",
              "correct": 267,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 41.145833333333336,
              "arm": "G0",
              "correct": 237,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 59.201388888888886,
              "arm": "J0",
              "correct": 341,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 58.50694444444444,
              "arm": "G0",
              "correct": 337,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 74.13194444444444,
              "arm": "J0",
              "correct": 427,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "G0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 68.75,
              "arm": "J0",
              "correct": 396,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 68.40277777777777,
              "arm": "G0",
              "correct": 394,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 64.40972222222223,
              "arm": "J0",
              "correct": 371,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 69.09722222222223,
              "arm": "G0",
              "correct": 398,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 43.40277777777778,
              "arm": "J0",
              "correct": 250,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "G0",
              "correct": 238,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 79.86111111111111,
              "arm": "J0",
              "correct": 460,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 79.16666666666667,
              "arm": "G0",
              "correct": 456,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.30555555555556,
              "arm": "J0",
              "correct": 284,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 51.90972222222222,
              "arm": "G0",
              "correct": 299,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 42.53472222222222,
              "arm": "J0",
              "correct": 245,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "G0",
              "correct": 247,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 40.625,
              "arm": "J0",
              "correct": 234,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 40.625,
              "arm": "G0",
              "correct": 234,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 59.201388888888886,
              "arm": "J0",
              "correct": 341,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 57.46527777777778,
              "arm": "G0",
              "correct": 331,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 71.70138888888889,
              "arm": "J0",
              "correct": 413,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 69.09722222222223,
              "arm": "G0",
              "correct": 398,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 67.88194444444444,
              "arm": "J0",
              "correct": 391,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 65.625,
              "arm": "G0",
              "correct": 378,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "g0_vs_j0_both_seeds_positive": false,
            "g0_vs_j0_mean_at_least_0_5pp": false,
            "g0_vs_s0_both_seeds_positive": false,
            "g0_vs_s0_mean_at_least_1pp": false,
            "g0_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        },
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-pool-antialias-001-development-v1",
        "run_action": "STOP"
      },
      "closing_round": "mvcnet-pool-antialias-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "38a1085f9cdf32fddce8fc3cd98384c3e652bf6855cda2f287d62f7e9088dcd1",
        "artifact_manifest_sha256": "b78a11588d1687d5399306792dd9ba04344052f39e2790a7e41a7c90b80e6830",
        "contract_sha256": "1fc9a9961bbd63ed7d9ba32d3b383c78fe252593007c606b2bd2765deda64f6f",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-tx",
        "transfer_bytes": 1512328,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "First qualified candidate of the user-authorized serial v4.1 search: raw/flip CE dose. Three hours for technical preparation from 21:45:15 CST."
    },
    {
      "campaign_id": "mvcnet-view-ce-balance-001-20261127",
      "closed_at": "2026-11-27T17:52:10.385679+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "SCREEN_POSITIVE",
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATES_PASS",
        "round_id": "mvcnet-view-ce-balance-001-development-v1",
        "run_action": "STOP",
        "view_ce_balance_analysis": {
          "contrasts": {
            "G0_minus_J0": {
              "ci95_pp": [
                0.16396604938271608,
                2.3823302469135803
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 1.253858024691358,
              "per_seed_pp": [
                1.5046296296296295,
                1.0030864197530864
              ],
              "per_subject_pp": [
                0.1736111111111111,
                2.6041666666666665,
                -1.2152777777777777,
                2.6041666666666665,
                1.4756944444444444,
                1.5625,
                4.427083333333333,
                0.5208333333333334,
                -0.8680555555555556
              ]
            },
            "G0_minus_S0": {
              "ci95_pp": [
                0.29899691358024694,
                2.26658950617284
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 1.2345679012345678,
              "per_seed_pp": [
                1.4467592592592593,
                1.0223765432098766
              ],
              "per_subject_pp": [
                1.4756944444444444,
                -0.3472222222222222,
                0.2604166666666667,
                2.6041666666666665,
                2.517361111111111,
                -0.3472222222222222,
                4.253472222222222,
                -0.2604166666666667,
                0.9548611111111112
              ]
            },
            "J0_minus_S0": {
              "ci95_pp": [
                -1.0706018518518519,
                0.925925925925926
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.019290123456790122,
              "per_seed_pp": [
                -0.05787037037037037,
                0.019290123456790122
              ],
              "per_subject_pp": [
                1.3020833333333333,
                -2.951388888888889,
                1.4756944444444444,
                0.0,
                1.0416666666666667,
                -1.9097222222222223,
                -0.1736111111111111,
                -0.78125,
                1.8229166666666667
              ]
            }
          },
          "coordinate_schema": [
            "seed",
            "outer",
            "arm"
          ],
          "coordinates": [
            {
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.40277777777777,
              "arm": "J0",
              "correct": 394,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 70.3125,
              "arm": "G0",
              "correct": 405,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 40.625,
              "arm": "J0",
              "correct": 234,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 43.576388888888886,
              "arm": "G0",
              "correct": 251,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 78.125,
              "arm": "S0",
              "correct": 450,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 78.81944444444444,
              "arm": "J0",
              "correct": 454,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 79.6875,
              "arm": "G0",
              "correct": 459,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 52.951388888888886,
              "arm": "S0",
              "correct": 305,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 51.90972222222222,
              "arm": "J0",
              "correct": 299,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 51.5625,
              "arm": "G0",
              "correct": 297,
              "count": 576,
              "outer": 3,
              "seed": 0
            },
            {
              "accuracy_pp": 41.84027777777778,
              "arm": "S0",
              "correct": 241,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 40.97222222222222,
              "arm": "J0",
              "correct": 236,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 43.05555555555556,
              "arm": "G0",
              "correct": 248,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "S0",
              "correct": 247,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 43.229166666666664,
              "arm": "J0",
              "correct": 249,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "G0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 58.15972222222222,
              "arm": "S0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 58.68055555555556,
              "arm": "J0",
              "correct": 338,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 64.23611111111111,
              "arm": "G0",
              "correct": 370,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 72.22222222222223,
              "arm": "S0",
              "correct": 416,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 72.56944444444444,
              "arm": "J0",
              "correct": 418,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 72.56944444444444,
              "arm": "G0",
              "correct": 418,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 69.44444444444444,
              "arm": "S0",
              "correct": 400,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 71.00694444444444,
              "arm": "J0",
              "correct": 409,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 70.65972222222223,
              "arm": "G0",
              "correct": 407,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 66.66666666666667,
              "arm": "S0",
              "correct": 384,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 67.88194444444444,
              "arm": "J0",
              "correct": 391,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 66.31944444444444,
              "arm": "G0",
              "correct": 382,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 41.666666666666664,
              "arm": "J0",
              "correct": 240,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 43.923611111111114,
              "arm": "G0",
              "correct": 253,
              "count": 576,
              "outer": 1,
              "seed": 4
            },
            {
              "accuracy_pp": 80.03472222222223,
              "arm": "S0",
              "correct": 461,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 82.29166666666667,
              "arm": "J0",
              "correct": 474,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 78.99305555555556,
              "arm": "G0",
              "correct": 455,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 48.263888888888886,
              "arm": "S0",
              "correct": 278,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.30555555555556,
              "arm": "J0",
              "correct": 284,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 54.861111111111114,
              "arm": "G0",
              "correct": 316,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 41.31944444444444,
              "arm": "S0",
              "correct": 238,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.270833333333336,
              "arm": "J0",
              "correct": 255,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 45.138888888888886,
              "arm": "G0",
              "correct": 260,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.09722222222222,
              "arm": "S0",
              "correct": 254,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 39.93055555555556,
              "arm": "J0",
              "correct": 230,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 42.1875,
              "arm": "G0",
              "correct": 243,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 61.28472222222222,
              "arm": "S0",
              "correct": 353,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 60.416666666666664,
              "arm": "J0",
              "correct": 348,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 63.71527777777778,
              "arm": "G0",
              "correct": 367,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "S0",
              "correct": 417,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 70.48611111111111,
              "arm": "J0",
              "correct": 406,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 71.52777777777777,
              "arm": "G0",
              "correct": 412,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 67.53472222222223,
              "arm": "S0",
              "correct": 389,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 69.61805555555556,
              "arm": "J0",
              "correct": 401,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 68.22916666666667,
              "arm": "G0",
              "correct": 393,
              "count": 576,
              "outer": 8,
              "seed": 4
            }
          ],
          "gates": {
            "g0_vs_j0_both_seeds_positive": true,
            "g0_vs_j0_mean_at_least_0_5pp": true,
            "g0_vs_s0_both_seeds_positive": true,
            "g0_vs_s0_mean_at_least_1pp": true,
            "g0_vs_s0_subject_risk": true
          },
          "paired_seed_count": 2,
          "subject_count": 9
        }
      },
      "closing_round": "mvcnet-view-ce-balance-001-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "b3683f9e18107eafac4134b69beb5b64da2baf25301462545370e8cdcd1e6a06",
        "artifact_manifest_sha256": "f42dad6a0d86f46162d6953b2090a87ebfa34494252a277390b2ce4a97f284c1",
        "contract_sha256": "c770189c413e9aabb8b23fd745995d01fa197979f8af666caf0fc6efa98d0088",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-27_mvcnet_view_ce_balance_001_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-tx",
        "transfer_bytes": 1513679,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized one four-dataset developmental follow-up. Verified 001 reused and same-seed contemporary 004/002/Zhou matrix. Three hours preflight; resource-based cap before scientific dispatch."
    },
    {
      "campaign_id": "mvcnet-view-ce-balance-xdataset-20261128",
      "closed_at": "2026-11-28T03:51:22.420179+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "dataset_dispositions": {
          "BNCI2014002": "NO_SIGNAL",
          "BNCI2014004": "NO_SIGNAL",
          "Zhou2016": "NO_SIGNAL"
        },
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "reason": "NO_NEW_DATASET_PASSED_FROZEN_GATES",
        "round_id": "mvcnet-view-ce-balance-xdataset-development-v1",
        "run_action": "STOP",
        "view_ce_balance_xdataset_analysis": {
          "cross_dataset_aggregate": null,
          "datasets": {
            "BNCI2014002": {
              "allowed_g0_vs_s0_harmed_subjects": 1,
              "contrasts": {
                "G0_minus_J0": {
                  "ci95_pp": [
                    -0.26785714285714285,
                    2.3660714285714284
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 1.0491071428571428,
                  "per_seed_pp": [
                    1.4732142857142858,
                    0.625
                  ],
                  "per_subject_pp": [
                    0.0,
                    -1.25,
                    5.3125,
                    2.1875,
                    1.875,
                    -1.5625,
                    3.75,
                    -2.8125,
                    -2.8125,
                    2.1875,
                    0.0,
                    3.4375,
                    0.3125,
                    4.0625
                  ]
                },
                "G0_minus_S0": {
                  "ci95_pp": [
                    -0.8705357142857143,
                    1.1160714285714286
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 0.17857142857142858,
                  "per_seed_pp": [
                    -0.35714285714285715,
                    0.7142857142857143
                  ],
                  "per_subject_pp": [
                    0.3125,
                    -0.625,
                    0.0,
                    -0.9375,
                    0.9375,
                    -4.375,
                    1.875,
                    1.25,
                    -2.5,
                    1.25,
                    2.1875,
                    2.5,
                    -1.5625,
                    2.1875
                  ]
                },
                "J0_minus_S0": {
                  "ci95_pp": [
                    -2.03125,
                    0.33482142857142855
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 1,
                  "mean_pp": -0.8705357142857143,
                  "per_seed_pp": [
                    -1.8303571428571428,
                    0.08928571428571429
                  ],
                  "per_subject_pp": [
                    0.3125,
                    0.625,
                    -5.3125,
                    -3.125,
                    -0.9375,
                    -2.8125,
                    -1.875,
                    4.0625,
                    0.3125,
                    -0.9375,
                    2.1875,
                    -0.9375,
                    -1.875,
                    -1.875
                  ]
                }
              },
              "coordinate_schema": [
                "seed",
                "outer",
                "arm"
              ],
              "coordinates": [
                {
                  "accuracy_pp": 48.75,
                  "arm": "S0",
                  "correct": 78,
                  "count": 160,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 49.375,
                  "arm": "J0",
                  "correct": 79,
                  "count": 160,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 49.375,
                  "arm": "G0",
                  "correct": 79,
                  "count": 160,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 81.875,
                  "arm": "S0",
                  "correct": 131,
                  "count": 160,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 82.5,
                  "arm": "J0",
                  "correct": 132,
                  "count": 160,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 83.75,
                  "arm": "G0",
                  "correct": 134,
                  "count": 160,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 88.75,
                  "arm": "S0",
                  "correct": 142,
                  "count": 160,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 81.25,
                  "arm": "J0",
                  "correct": 130,
                  "count": 160,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 91.25,
                  "arm": "G0",
                  "correct": 146,
                  "count": 160,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 86.25,
                  "arm": "S0",
                  "correct": 138,
                  "count": 160,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 83.125,
                  "arm": "J0",
                  "correct": 133,
                  "count": 160,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 83.75,
                  "arm": "G0",
                  "correct": 134,
                  "count": 160,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 63.75,
                  "arm": "S0",
                  "correct": 102,
                  "count": 160,
                  "outer": 4,
                  "seed": 0
                },
                {
                  "accuracy_pp": 60.625,
                  "arm": "J0",
                  "correct": 97,
                  "count": 160,
                  "outer": 4,
                  "seed": 0
                },
                {
                  "accuracy_pp": 60.625,
                  "arm": "G0",
                  "correct": 97,
                  "count": 160,
                  "outer": 4,
                  "seed": 0
                },
                {
                  "accuracy_pp": 77.5,
                  "arm": "S0",
                  "correct": 124,
                  "count": 160,
                  "outer": 5,
                  "seed": 0
                },
                {
                  "accuracy_pp": 76.25,
                  "arm": "J0",
                  "correct": 122,
                  "count": 160,
                  "outer": 5,
                  "seed": 0
                },
                {
                  "accuracy_pp": 74.375,
                  "arm": "G0",
                  "correct": 119,
                  "count": 160,
                  "outer": 5,
                  "seed": 0
                },
                {
                  "accuracy_pp": 91.875,
                  "arm": "S0",
                  "correct": 147,
                  "count": 160,
                  "outer": 6,
                  "seed": 0
                },
                {
                  "accuracy_pp": 91.25,
                  "arm": "J0",
                  "correct": 146,
                  "count": 160,
                  "outer": 6,
                  "seed": 0
                },
                {
                  "accuracy_pp": 93.125,
                  "arm": "G0",
                  "correct": 149,
                  "count": 160,
                  "outer": 6,
                  "seed": 0
                },
                {
                  "accuracy_pp": 54.375,
                  "arm": "S0",
                  "correct": 87,
                  "count": 160,
                  "outer": 7,
                  "seed": 0
                },
                {
                  "accuracy_pp": 59.375,
                  "arm": "J0",
                  "correct": 95,
                  "count": 160,
                  "outer": 7,
                  "seed": 0
                },
                {
                  "accuracy_pp": 56.875,
                  "arm": "G0",
                  "correct": 91,
                  "count": 160,
                  "outer": 7,
                  "seed": 0
                },
                {
                  "accuracy_pp": 86.875,
                  "arm": "S0",
                  "correct": 139,
                  "count": 160,
                  "outer": 8,
                  "seed": 0
                },
                {
                  "accuracy_pp": 83.125,
                  "arm": "J0",
                  "correct": 133,
                  "count": 160,
                  "outer": 8,
                  "seed": 0
                },
                {
                  "accuracy_pp": 82.5,
                  "arm": "G0",
                  "correct": 132,
                  "count": 160,
                  "outer": 8,
                  "seed": 0
                },
                {
                  "accuracy_pp": 61.25,
                  "arm": "S0",
                  "correct": 98,
                  "count": 160,
                  "outer": 9,
                  "seed": 0
                },
                {
                  "accuracy_pp": 59.375,
                  "arm": "J0",
                  "correct": 95,
                  "count": 160,
                  "outer": 9,
                  "seed": 0
                },
                {
                  "accuracy_pp": 60.625,
                  "arm": "G0",
                  "correct": 97,
                  "count": 160,
                  "outer": 9,
                  "seed": 0
                },
                {
                  "accuracy_pp": 74.375,
                  "arm": "S0",
                  "correct": 119,
                  "count": 160,
                  "outer": 10,
                  "seed": 0
                },
                {
                  "accuracy_pp": 71.875,
                  "arm": "J0",
                  "correct": 115,
                  "count": 160,
                  "outer": 10,
                  "seed": 0
                },
                {
                  "accuracy_pp": 71.25,
                  "arm": "G0",
                  "correct": 114,
                  "count": 160,
                  "outer": 10,
                  "seed": 0
                },
                {
                  "accuracy_pp": 65.0,
                  "arm": "S0",
                  "correct": 104,
                  "count": 160,
                  "outer": 11,
                  "seed": 0
                },
                {
                  "accuracy_pp": 60.0,
                  "arm": "J0",
                  "correct": 96,
                  "count": 160,
                  "outer": 11,
                  "seed": 0
                },
                {
                  "accuracy_pp": 66.25,
                  "arm": "G0",
                  "correct": 106,
                  "count": 160,
                  "outer": 11,
                  "seed": 0
                },
                {
                  "accuracy_pp": 56.875,
                  "arm": "S0",
                  "correct": 91,
                  "count": 160,
                  "outer": 12,
                  "seed": 0
                },
                {
                  "accuracy_pp": 55.0,
                  "arm": "J0",
                  "correct": 88,
                  "count": 160,
                  "outer": 12,
                  "seed": 0
                },
                {
                  "accuracy_pp": 54.375,
                  "arm": "G0",
                  "correct": 87,
                  "count": 160,
                  "outer": 12,
                  "seed": 0
                },
                {
                  "accuracy_pp": 45.0,
                  "arm": "S0",
                  "correct": 72,
                  "count": 160,
                  "outer": 13,
                  "seed": 0
                },
                {
                  "accuracy_pp": 43.75,
                  "arm": "J0",
                  "correct": 70,
                  "count": 160,
                  "outer": 13,
                  "seed": 0
                },
                {
                  "accuracy_pp": 49.375,
                  "arm": "G0",
                  "correct": 79,
                  "count": 160,
                  "outer": 13,
                  "seed": 0
                },
                {
                  "accuracy_pp": 49.375,
                  "arm": "S0",
                  "correct": 79,
                  "count": 160,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 49.375,
                  "arm": "J0",
                  "correct": 79,
                  "count": 160,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 49.375,
                  "arm": "G0",
                  "correct": 79,
                  "count": 160,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 82.5,
                  "arm": "S0",
                  "correct": 132,
                  "count": 160,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 83.125,
                  "arm": "J0",
                  "correct": 133,
                  "count": 160,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 79.375,
                  "arm": "G0",
                  "correct": 127,
                  "count": 160,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 83.125,
                  "arm": "S0",
                  "correct": 133,
                  "count": 160,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 80.0,
                  "arm": "J0",
                  "correct": 128,
                  "count": 160,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 80.625,
                  "arm": "G0",
                  "correct": 129,
                  "count": 160,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 90.625,
                  "arm": "S0",
                  "correct": 145,
                  "count": 160,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 87.5,
                  "arm": "J0",
                  "correct": 140,
                  "count": 160,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 91.25,
                  "arm": "G0",
                  "correct": 146,
                  "count": 160,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 65.0,
                  "arm": "S0",
                  "correct": 104,
                  "count": 160,
                  "outer": 4,
                  "seed": 4
                },
                {
                  "accuracy_pp": 66.25,
                  "arm": "J0",
                  "correct": 106,
                  "count": 160,
                  "outer": 4,
                  "seed": 4
                },
                {
                  "accuracy_pp": 70.0,
                  "arm": "G0",
                  "correct": 112,
                  "count": 160,
                  "outer": 4,
                  "seed": 4
                },
                {
                  "accuracy_pp": 76.875,
                  "arm": "S0",
                  "correct": 123,
                  "count": 160,
                  "outer": 5,
                  "seed": 4
                },
                {
                  "accuracy_pp": 72.5,
                  "arm": "J0",
                  "correct": 116,
                  "count": 160,
                  "outer": 5,
                  "seed": 4
                },
                {
                  "accuracy_pp": 71.25,
                  "arm": "G0",
                  "correct": 114,
                  "count": 160,
                  "outer": 5,
                  "seed": 4
                },
                {
                  "accuracy_pp": 89.375,
                  "arm": "S0",
                  "correct": 143,
                  "count": 160,
                  "outer": 6,
                  "seed": 4
                },
                {
                  "accuracy_pp": 86.25,
                  "arm": "J0",
                  "correct": 138,
                  "count": 160,
                  "outer": 6,
                  "seed": 4
                },
                {
                  "accuracy_pp": 91.875,
                  "arm": "G0",
                  "correct": 147,
                  "count": 160,
                  "outer": 6,
                  "seed": 4
                },
                {
                  "accuracy_pp": 57.5,
                  "arm": "S0",
                  "correct": 92,
                  "count": 160,
                  "outer": 7,
                  "seed": 4
                },
                {
                  "accuracy_pp": 60.625,
                  "arm": "J0",
                  "correct": 97,
                  "count": 160,
                  "outer": 7,
                  "seed": 4
                },
                {
                  "accuracy_pp": 57.5,
                  "arm": "G0",
                  "correct": 92,
                  "count": 160,
                  "outer": 7,
                  "seed": 4
                },
                {
                  "accuracy_pp": 74.375,
                  "arm": "S0",
                  "correct": 119,
                  "count": 160,
                  "outer": 8,
                  "seed": 4
                },
                {
                  "accuracy_pp": 78.75,
                  "arm": "J0",
                  "correct": 126,
                  "count": 160,
                  "outer": 8,
                  "seed": 4
                },
                {
                  "accuracy_pp": 73.75,
                  "arm": "G0",
                  "correct": 118,
                  "count": 160,
                  "outer": 8,
                  "seed": 4
                },
                {
                  "accuracy_pp": 61.25,
                  "arm": "S0",
                  "correct": 98,
                  "count": 160,
                  "outer": 9,
                  "seed": 4
                },
                {
                  "accuracy_pp": 61.25,
                  "arm": "J0",
                  "correct": 98,
                  "count": 160,
                  "outer": 9,
                  "seed": 4
                },
                {
                  "accuracy_pp": 64.375,
                  "arm": "G0",
                  "correct": 103,
                  "count": 160,
                  "outer": 9,
                  "seed": 4
                },
                {
                  "accuracy_pp": 69.375,
                  "arm": "S0",
                  "correct": 111,
                  "count": 160,
                  "outer": 10,
                  "seed": 4
                },
                {
                  "accuracy_pp": 76.25,
                  "arm": "J0",
                  "correct": 122,
                  "count": 160,
                  "outer": 10,
                  "seed": 4
                },
                {
                  "accuracy_pp": 76.875,
                  "arm": "G0",
                  "correct": 123,
                  "count": 160,
                  "outer": 10,
                  "seed": 4
                },
                {
                  "accuracy_pp": 58.75,
                  "arm": "S0",
                  "correct": 94,
                  "count": 160,
                  "outer": 11,
                  "seed": 4
                },
                {
                  "accuracy_pp": 61.875,
                  "arm": "J0",
                  "correct": 99,
                  "count": 160,
                  "outer": 11,
                  "seed": 4
                },
                {
                  "accuracy_pp": 62.5,
                  "arm": "G0",
                  "correct": 100,
                  "count": 160,
                  "outer": 11,
                  "seed": 4
                },
                {
                  "accuracy_pp": 58.75,
                  "arm": "S0",
                  "correct": 94,
                  "count": 160,
                  "outer": 12,
                  "seed": 4
                },
                {
                  "accuracy_pp": 56.875,
                  "arm": "J0",
                  "correct": 91,
                  "count": 160,
                  "outer": 12,
                  "seed": 4
                },
                {
                  "accuracy_pp": 58.125,
                  "arm": "G0",
                  "correct": 93,
                  "count": 160,
                  "outer": 12,
                  "seed": 4
                },
                {
                  "accuracy_pp": 46.25,
                  "arm": "S0",
                  "correct": 74,
                  "count": 160,
                  "outer": 13,
                  "seed": 4
                },
                {
                  "accuracy_pp": 43.75,
                  "arm": "J0",
                  "correct": 70,
                  "count": 160,
                  "outer": 13,
                  "seed": 4
                },
                {
                  "accuracy_pp": 46.25,
                  "arm": "G0",
                  "correct": 74,
                  "count": 160,
                  "outer": 13,
                  "seed": 4
                }
              ],
              "disposition": "NO_SIGNAL",
              "gates": {
                "g0_vs_j0_both_seeds_positive": true,
                "g0_vs_j0_mean_at_least_0_5pp": true,
                "g0_vs_s0_both_seeds_positive": false,
                "g0_vs_s0_mean_at_least_1pp": false,
                "g0_vs_s0_subject_risk": true
              },
              "paired_seed_count": 2,
              "subject_count": 14
            },
            "BNCI2014004": {
              "allowed_g0_vs_s0_harmed_subjects": 1,
              "contrasts": {
                "G0_minus_J0": {
                  "ci95_pp": [
                    -0.43989164603199693,
                    0.7626348613835712
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 0.19870037736394805,
                  "per_seed_pp": [
                    -0.07466961285330738,
                    0.4720703675812035
                  ],
                  "per_subject_pp": [
                    0.06944444444444445,
                    1.3235294117647058,
                    -0.9722222222222222,
                    -1.6216216216216217,
                    0.8108108108108109,
                    -0.06944444444444445,
                    1.1805555555555556,
                    0.7894736842105263,
                    0.2777777777777778
                  ]
                },
                "G0_minus_S0": {
                  "ci95_pp": [
                    -0.23005724700448643,
                    0.7501151661207119
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 0.29230856243240144,
                  "per_seed_pp": [
                    0.4578430339524251,
                    0.12677409091237782
                  ],
                  "per_subject_pp": [
                    -0.06944444444444445,
                    0.8088235294117647,
                    0.20833333333333334,
                    -1.2837837837837838,
                    1.3513513513513513,
                    0.4166666666666667,
                    0.6944444444444444,
                    0.9210526315789473,
                    -0.4166666666666667
                  ]
                },
                "J0_minus_S0": {
                  "ci95_pp": [
                    -0.2705549977221804,
                    0.4794106542042559
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 0.09360818506845339,
                  "per_seed_pp": [
                    0.5325126468057325,
                    -0.3452962766688257
                  ],
                  "per_subject_pp": [
                    -0.1388888888888889,
                    -0.5147058823529411,
                    1.1805555555555556,
                    0.33783783783783783,
                    0.5405405405405406,
                    0.4861111111111111,
                    -0.4861111111111111,
                    0.13157894736842105,
                    -0.6944444444444444
                  ]
                }
              },
              "coordinate_schema": [
                "seed",
                "outer",
                "arm"
              ],
              "coordinates": [
                {
                  "accuracy_pp": 62.77777777777778,
                  "arm": "S0",
                  "correct": 452,
                  "count": 720,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 62.22222222222222,
                  "arm": "J0",
                  "correct": 448,
                  "count": 720,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 62.916666666666664,
                  "arm": "G0",
                  "correct": 453,
                  "count": 720,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 66.61764705882354,
                  "arm": "S0",
                  "correct": 453,
                  "count": 680,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 66.32352941176471,
                  "arm": "J0",
                  "correct": 451,
                  "count": 680,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 67.3529411764706,
                  "arm": "G0",
                  "correct": 458,
                  "count": 680,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 57.5,
                  "arm": "S0",
                  "correct": 414,
                  "count": 720,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 59.583333333333336,
                  "arm": "J0",
                  "correct": 429,
                  "count": 720,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 59.44444444444444,
                  "arm": "G0",
                  "correct": 428,
                  "count": 720,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 76.35135135135135,
                  "arm": "S0",
                  "correct": 565,
                  "count": 740,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 77.83783783783784,
                  "arm": "J0",
                  "correct": 576,
                  "count": 740,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 74.72972972972973,
                  "arm": "G0",
                  "correct": 553,
                  "count": 740,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 82.43243243243244,
                  "arm": "S0",
                  "correct": 610,
                  "count": 740,
                  "outer": 4,
                  "seed": 0
                },
                {
                  "accuracy_pp": 82.29729729729729,
                  "arm": "J0",
                  "correct": 609,
                  "count": 740,
                  "outer": 4,
                  "seed": 0
                },
                {
                  "accuracy_pp": 82.97297297297297,
                  "arm": "G0",
                  "correct": 614,
                  "count": 740,
                  "outer": 4,
                  "seed": 0
                },
                {
                  "accuracy_pp": 68.88888888888889,
                  "arm": "S0",
                  "correct": 496,
                  "count": 720,
                  "outer": 5,
                  "seed": 0
                },
                {
                  "accuracy_pp": 70.41666666666667,
                  "arm": "J0",
                  "correct": 507,
                  "count": 720,
                  "outer": 5,
                  "seed": 0
                },
                {
                  "accuracy_pp": 69.44444444444444,
                  "arm": "G0",
                  "correct": 500,
                  "count": 720,
                  "outer": 5,
                  "seed": 0
                },
                {
                  "accuracy_pp": 84.58333333333333,
                  "arm": "S0",
                  "correct": 609,
                  "count": 720,
                  "outer": 6,
                  "seed": 0
                },
                {
                  "accuracy_pp": 84.86111111111111,
                  "arm": "J0",
                  "correct": 611,
                  "count": 720,
                  "outer": 6,
                  "seed": 0
                },
                {
                  "accuracy_pp": 85.55555555555556,
                  "arm": "G0",
                  "correct": 616,
                  "count": 720,
                  "outer": 6,
                  "seed": 0
                },
                {
                  "accuracy_pp": 73.55263157894737,
                  "arm": "S0",
                  "correct": 559,
                  "count": 760,
                  "outer": 7,
                  "seed": 0
                },
                {
                  "accuracy_pp": 73.8157894736842,
                  "arm": "J0",
                  "correct": 561,
                  "count": 760,
                  "outer": 7,
                  "seed": 0
                },
                {
                  "accuracy_pp": 75.65789473684211,
                  "arm": "G0",
                  "correct": 575,
                  "count": 760,
                  "outer": 7,
                  "seed": 0
                },
                {
                  "accuracy_pp": 63.47222222222222,
                  "arm": "S0",
                  "correct": 457,
                  "count": 720,
                  "outer": 8,
                  "seed": 0
                },
                {
                  "accuracy_pp": 63.611111111111114,
                  "arm": "J0",
                  "correct": 458,
                  "count": 720,
                  "outer": 8,
                  "seed": 0
                },
                {
                  "accuracy_pp": 62.22222222222222,
                  "arm": "G0",
                  "correct": 448,
                  "count": 720,
                  "outer": 8,
                  "seed": 0
                },
                {
                  "accuracy_pp": 60.97222222222222,
                  "arm": "S0",
                  "correct": 439,
                  "count": 720,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 61.25,
                  "arm": "J0",
                  "correct": 441,
                  "count": 720,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 60.69444444444444,
                  "arm": "G0",
                  "correct": 437,
                  "count": 720,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 67.3529411764706,
                  "arm": "S0",
                  "correct": 458,
                  "count": 680,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 66.61764705882354,
                  "arm": "J0",
                  "correct": 453,
                  "count": 680,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 68.23529411764706,
                  "arm": "G0",
                  "correct": 464,
                  "count": 680,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 61.94444444444444,
                  "arm": "S0",
                  "correct": 446,
                  "count": 720,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 62.22222222222222,
                  "arm": "J0",
                  "correct": 448,
                  "count": 720,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 60.416666666666664,
                  "arm": "G0",
                  "correct": 435,
                  "count": 720,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 77.29729729729729,
                  "arm": "S0",
                  "correct": 572,
                  "count": 740,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 76.48648648648648,
                  "arm": "J0",
                  "correct": 566,
                  "count": 740,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 76.35135135135135,
                  "arm": "G0",
                  "correct": 565,
                  "count": 740,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 81.08108108108108,
                  "arm": "S0",
                  "correct": 600,
                  "count": 740,
                  "outer": 4,
                  "seed": 4
                },
                {
                  "accuracy_pp": 82.29729729729729,
                  "arm": "J0",
                  "correct": 609,
                  "count": 740,
                  "outer": 4,
                  "seed": 4
                },
                {
                  "accuracy_pp": 83.24324324324324,
                  "arm": "G0",
                  "correct": 616,
                  "count": 740,
                  "outer": 4,
                  "seed": 4
                },
                {
                  "accuracy_pp": 70.55555555555556,
                  "arm": "S0",
                  "correct": 508,
                  "count": 720,
                  "outer": 5,
                  "seed": 4
                },
                {
                  "accuracy_pp": 70.0,
                  "arm": "J0",
                  "correct": 504,
                  "count": 720,
                  "outer": 5,
                  "seed": 4
                },
                {
                  "accuracy_pp": 70.83333333333333,
                  "arm": "G0",
                  "correct": 510,
                  "count": 720,
                  "outer": 5,
                  "seed": 4
                },
                {
                  "accuracy_pp": 85.0,
                  "arm": "S0",
                  "correct": 612,
                  "count": 720,
                  "outer": 6,
                  "seed": 4
                },
                {
                  "accuracy_pp": 83.75,
                  "arm": "J0",
                  "correct": 603,
                  "count": 720,
                  "outer": 6,
                  "seed": 4
                },
                {
                  "accuracy_pp": 85.41666666666667,
                  "arm": "G0",
                  "correct": 615,
                  "count": 720,
                  "outer": 6,
                  "seed": 4
                },
                {
                  "accuracy_pp": 75.26315789473684,
                  "arm": "S0",
                  "correct": 572,
                  "count": 760,
                  "outer": 7,
                  "seed": 4
                },
                {
                  "accuracy_pp": 75.26315789473684,
                  "arm": "J0",
                  "correct": 572,
                  "count": 760,
                  "outer": 7,
                  "seed": 4
                },
                {
                  "accuracy_pp": 75.0,
                  "arm": "G0",
                  "correct": 570,
                  "count": 760,
                  "outer": 7,
                  "seed": 4
                },
                {
                  "accuracy_pp": 63.888888888888886,
                  "arm": "S0",
                  "correct": 460,
                  "count": 720,
                  "outer": 8,
                  "seed": 4
                },
                {
                  "accuracy_pp": 62.361111111111114,
                  "arm": "J0",
                  "correct": 449,
                  "count": 720,
                  "outer": 8,
                  "seed": 4
                },
                {
                  "accuracy_pp": 64.30555555555556,
                  "arm": "G0",
                  "correct": 463,
                  "count": 720,
                  "outer": 8,
                  "seed": 4
                }
              ],
              "disposition": "NO_SIGNAL",
              "gates": {
                "g0_vs_j0_both_seeds_positive": false,
                "g0_vs_j0_mean_at_least_0_5pp": false,
                "g0_vs_s0_both_seeds_positive": true,
                "g0_vs_s0_mean_at_least_1pp": false,
                "g0_vs_s0_subject_risk": true
              },
              "paired_seed_count": 2,
              "subject_count": 9
            },
            "Zhou2016": {
              "allowed_g0_vs_s0_harmed_subjects": 0,
              "contrasts": {
                "G0_minus_J0": {
                  "ci95_pp": [
                    -1.1858076563958917,
                    0.4722222222222222
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": -0.46790382819794585,
                  "per_seed_pp": [
                    -0.1580298786181139,
                    -0.7777777777777778
                  ],
                  "per_subject_pp": [
                    -1.2605042016806722,
                    1.0,
                    -0.5,
                    -1.1111111111111112
                  ]
                },
                "G0_minus_S0": {
                  "ci95_pp": [
                    -0.2916666666666667,
                    0.7552521008403362
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 0.3211951447245565,
                  "per_seed_pp": [
                    -0.027777777777777776,
                    0.6701680672268907
                  ],
                  "per_subject_pp": [
                    0.8403361344537815,
                    0.5,
                    0.5,
                    -0.5555555555555556
                  ]
                },
                "J0_minus_S0": {
                  "ci95_pp": [
                    -0.125,
                    1.7145191409897294
                  ],
                  "harmed_at_least_10pp": 0,
                  "harmed_at_least_5pp": 0,
                  "mean_pp": 0.7890989729225023,
                  "per_seed_pp": [
                    0.13025210084033614,
                    1.4479458450046685
                  ],
                  "per_subject_pp": [
                    2.100840336134454,
                    -0.5,
                    1.0,
                    0.5555555555555556
                  ]
                }
              },
              "coordinate_schema": [
                "seed",
                "outer",
                "arm"
              ],
              "coordinates": [
                {
                  "accuracy_pp": 84.87394957983193,
                  "arm": "S0",
                  "correct": 101,
                  "count": 119,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 87.39495798319328,
                  "arm": "J0",
                  "correct": 104,
                  "count": 119,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 84.87394957983193,
                  "arm": "G0",
                  "correct": 101,
                  "count": 119,
                  "outer": 0,
                  "seed": 0
                },
                {
                  "accuracy_pp": 78.0,
                  "arm": "S0",
                  "correct": 78,
                  "count": 100,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 75.0,
                  "arm": "J0",
                  "correct": 75,
                  "count": 100,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 78.0,
                  "arm": "G0",
                  "correct": 78,
                  "count": 100,
                  "outer": 1,
                  "seed": 0
                },
                {
                  "accuracy_pp": 86.0,
                  "arm": "S0",
                  "correct": 86,
                  "count": 100,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 87.0,
                  "arm": "J0",
                  "correct": 87,
                  "count": 100,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 87.0,
                  "arm": "G0",
                  "correct": 87,
                  "count": 100,
                  "outer": 2,
                  "seed": 0
                },
                {
                  "accuracy_pp": 84.44444444444444,
                  "arm": "S0",
                  "correct": 76,
                  "count": 90,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 84.44444444444444,
                  "arm": "J0",
                  "correct": 76,
                  "count": 90,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 83.33333333333333,
                  "arm": "G0",
                  "correct": 75,
                  "count": 90,
                  "outer": 3,
                  "seed": 0
                },
                {
                  "accuracy_pp": 82.3529411764706,
                  "arm": "S0",
                  "correct": 98,
                  "count": 119,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 84.03361344537815,
                  "arm": "J0",
                  "correct": 100,
                  "count": 119,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 84.03361344537815,
                  "arm": "G0",
                  "correct": 100,
                  "count": 119,
                  "outer": 0,
                  "seed": 4
                },
                {
                  "accuracy_pp": 74.0,
                  "arm": "S0",
                  "correct": 74,
                  "count": 100,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 76.0,
                  "arm": "J0",
                  "correct": 76,
                  "count": 100,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 75.0,
                  "arm": "G0",
                  "correct": 75,
                  "count": 100,
                  "outer": 1,
                  "seed": 4
                },
                {
                  "accuracy_pp": 88.0,
                  "arm": "S0",
                  "correct": 88,
                  "count": 100,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 89.0,
                  "arm": "J0",
                  "correct": 89,
                  "count": 100,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 88.0,
                  "arm": "G0",
                  "correct": 88,
                  "count": 100,
                  "outer": 2,
                  "seed": 4
                },
                {
                  "accuracy_pp": 80.0,
                  "arm": "S0",
                  "correct": 72,
                  "count": 90,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 81.11111111111111,
                  "arm": "J0",
                  "correct": 73,
                  "count": 90,
                  "outer": 3,
                  "seed": 4
                },
                {
                  "accuracy_pp": 80.0,
                  "arm": "G0",
                  "correct": 72,
                  "count": 90,
                  "outer": 3,
                  "seed": 4
                }
              ],
              "disposition": "NO_SIGNAL",
              "gates": {
                "g0_vs_j0_both_seeds_positive": false,
                "g0_vs_j0_mean_at_least_0_5pp": false,
                "g0_vs_s0_both_seeds_positive": false,
                "g0_vs_s0_mean_at_least_1pp": false,
                "g0_vs_s0_subject_risk": true
              },
              "paired_seed_count": 2,
              "subject_count": 4
            }
          },
          "decision_scope": "independent dataset dispositions; no pooled rescue and no Claim",
          "disposition_by_dataset": {
            "BNCI2014002": "NO_SIGNAL",
            "BNCI2014004": "NO_SIGNAL",
            "Zhou2016": "NO_SIGNAL"
          },
          "matrix": {
            "check_count": 162,
            "dataset_fit_counts": {
              "BNCI2014002": 84,
              "BNCI2014004": 54,
              "Zhou2016": 24
            },
            "fit_count": 162,
            "fit_seal_sha256": "d4dfc106a1a7a4a1cf5a8e021cab1a80d150584346d12a19439efa854d8cdd53"
          }
        }
      },
      "closing_round": "mvcnet-view-ce-balance-xdataset-development-v1",
      "closing_run": {
        "analysis_receipt_sha256": "41774d2c0d5d238ce4c06632b9fc76791139c0ca5ad3ff9742b042fa7e77e279",
        "artifact_manifest_sha256": "ecfd490c5525eb3e94ce061c65a036bfe637d548ba36b2238d0233cd005bf45e",
        "contract_sha256": "bfd0092145cc3bfd64df7cf878cf0a34b40eabef9a6386db57b036bef2381473",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-tx",
        "transfer_bytes": 4664238,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized serial search. First 001 reference-rank-one source-qualified candidate. Initial technical budget under the original Lab10 sizing rule."
    }
  ],
  "campaign": {
    "allowed_transitions": [
      "SCREEN_NEW"
    ],
    "authorization_reason": "User authorized serial search. First 001 reference-rank-one source-qualified candidate. Initial technical budget under the original Lab10 sizing rule.",
    "campaign_id": "mvcnet-ifnet-reference-rank1-001-20261128",
    "continuation_policy_version": "evidence_to_design_v1",
    "decision_policy": "stop_at_positive",
    "execution_authorization": {
      "allowed_operations": [
        "upload",
        "launch",
        "probe",
        "fetch",
        "intake"
      ],
      "allowed_transitions": [
        "SCREEN_NEW"
      ],
      "authorization_ref": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/EXECUTION_AUTHORITY.md",
      "campaign_id": "mvcnet-ifnet-reference-rank1-001-20261128",
      "executor_id": "lab10",
      "recorded_at": "2026-11-28T03:51:24.853782+00:00",
      "research_scope": {
        "allow_new_module": false,
        "allowed_module_ids": [
          "src.models.ai4s.mvcnet.ifnet_reference_rank1"
        ],
        "allowed_stages": [
          "full"
        ],
        "data_scope_id": "s8b-r8-001-exposed-loso",
        "question_id": "mvcnet-ifnet-reference-rank1-001-development-v1"
      },
      "source_sha256": "7374de5b68e85c1a575fdf345f7daa85b5d78b5ba684973c9eabb0e8586756a7"
    },
    "extensions": [
      {
        "additional_hours": 15.0,
        "authorized_at": "2026-11-28T05:59:12.699952+00:00",
        "budget_argument_semantics": "night_budget_hours is the new cumulative campaign total, not an increment",
        "new_max_rounds": 1,
        "new_night_budget_hours": 18.0,
        "previous_max_rounds": 1,
        "previous_night_budget_hours": 3.0,
        "reason": "Original budget formula applied to verified source-only three-arm Lab10 measurements under the memory-only admission authorized by the user."
      }
    ],
    "governance_chain_id": "mvcnet-transaction-v4.1",
    "invalid_behavior": "fail_closed_without_advancing",
    "positive_signal_behavior": "pause_for_human_review",
    "purpose": "user-authorized bounded AI4S campaign",
    "queue_accounting": {
      "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1": {
        "contract_sha256": "e0d2e6281771ed4c075ed88e0a15b23c74e93d08a3929c472d59a23cac9b961c",
        "queue_seconds": 3.274580240249634,
        "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
        "transaction_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-tx"
      }
    },
    "round_decisions": [
      {
        "decision": "NO_SIGNAL",
        "decision_record": "ai4s/programs/mvcnet/research/mvcnet-ifnet-reference-rank1-001-development-v1_decision.yaml",
        "evidence_id": "AI4S-MVCNET-mvcnet-ifnet-reference-rank1-001-development-v1",
        "recorded_at": "2026-11-28T11:07:15.985509+00:00",
        "round_id": "mvcnet-ifnet-reference-rank1-001-development-v1"
      }
    ],
    "started_at": "2026-11-28T03:51:22.420179+00:00"
  },
  "capacity_rollover_history": [
    {
      "budget_settlement_sha256": "37e031bed599a289971c210a481e1df6cbe70fdcf31d4df91619b3f61c218a73",
      "check_dispatch_count": 270,
      "kind": "verified_gpu10_operational_rollover",
      "parent_proof_path": "_work\\s8_loso_extension_20261118\\gpu10\\parent_drain.json",
      "parent_proof_sha256": "d17ed03163af590acfba53d81042b8078ec6c291ac9ed86ce754ea4875e4475a",
      "parent_round_id": "mvcnet-acm-s8-loso-extension",
      "parent_run": {
        "bundle_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-bundle",
        "dispatch_status": "PENDING_UPLOAD",
        "estimated_training_hours": 38.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 540,
        "recorded_at": "2026-11-18T01:40:06.100887+00:00",
        "round_id": "mvcnet-acm-s8-loso-extension",
        "run_prefix": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-18T01:40:22.754995+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-18T01:40:25.399837+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-full-w1"
            }
          }
        ]
      },
      "parent_run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-full-w1",
      "recorded_at": "2026-11-18T02:34:31.123085+00:00",
      "reused_fit_count": 22,
      "terminal_ledger_sha256": "a6eec4b365437c7364e1382d67c551379c722368b40e2a8e757eddc91a83e1ec",
      "unstarted_fit_count": 248
    },
    {
      "budget_settlement_sha256": "04cfa06dc08ee24d32507e85f6f2999a4be38a6932d1199c44f548d82bd1ba80",
      "check_dispatch_count": 270,
      "kind": "verified_gpu10_operational_rollover",
      "parent_proof_path": "_work\\s8_loso_extension_20261118\\gpu10\\parent_drain.json",
      "parent_proof_sha256": "d17ed03163af590acfba53d81042b8078ec6c291ac9ed86ce754ea4875e4475a",
      "parent_round_id": "mvcnet-acm-s8-loso-extension-gpu10",
      "parent_run": {
        "bundle_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-bundle",
        "capacity_rollover_of": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-full-w1",
        "dispatch_status": "PENDING_UPLOAD",
        "dispatch_units": 518,
        "estimated_training_hours": 37.582,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 540,
        "recorded_at": "2026-11-18T02:34:31.123085+00:00",
        "round_id": "mvcnet-acm-s8-loso-extension-gpu10",
        "run_prefix": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-18T02:34:41.114743+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-18T02:34:44.473669+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-full-w1"
            }
          }
        ]
      },
      "parent_run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-full-w1",
      "recorded_at": "2026-11-18T02:40:48.348463+00:00",
      "reused_fit_count": 22,
      "terminal_ledger_sha256": "a6eec4b365437c7364e1382d67c551379c722368b40e2a8e757eddc91a83e1ec",
      "unstarted_fit_count": 248
    },
    {
      "check_dispatch_count": 270,
      "kind": "verified_s8_gpu10_pack_rollover",
      "max_active_tasks": 10,
      "parent_run": {
        "bundle_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-bundle",
        "capacity_rollover_of": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-full-w1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 518,
        "estimated_training_hours": 37.582,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 540,
        "recorded_at": "2026-11-18T02:40:48.348463+00:00",
        "round_id": "mvcnet-acm-s8-loso-extension-gpu10-importfix1",
        "run_prefix": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-18T02:40:53.174657+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-18T02:40:55.871849+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-18T02:42:03.293670+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "95c0195f1c6acf7ff000e9ca5384ea610b9ad5931a6e5da3a7733655b935f424",
                "execution_seconds": 64.52348971366882,
                "queue_seconds": 1.4207758903503418,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-full-w1",
                "transaction_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 65.94426560401917
              }
            }
          }
        ]
      },
      "parent_run_ids": [
        "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-full-w1",
        "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-full-w1"
      ],
      "recorded_at": "2026-11-18T05:08:39.702448+00:00",
      "reused_fit_count": 89,
      "settlement_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/budget_settlement.json",
      "settlement_sha256": "d82bcd707f2e8d0d2f7dfc337114338f63402b881f6eb32ddd922eff15cda84b",
      "sources": [
        {
          "contract_path": "ai4s/programs/mvcnet/research/mvcnet-acm-s8-loso-extension.yaml",
          "ledger_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/transaction_status.json",
          "ledger_sha256": "a6eec4b365437c7364e1382d67c551379c722368b40e2a8e757eddc91a83e1ec",
          "proof_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/parent_drain.json",
          "proof_sha256": "d17ed03163af590acfba53d81042b8078ec6c291ac9ed86ce754ea4875e4475a",
          "queue_clock_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/science.queue_clock.json",
          "queue_clock_sha256": "963ab9bfd7bb776ea1d7d5106490691f94afec1ea651d50f78c5e3a938039358",
          "scheduler_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/parent_drain_scheduler.json",
          "scheduler_sha256": "50e6fec754d46cb1ccb37281cd91dfa98ca1e220609278849ed9096d24f02611"
        },
        {
          "contract_path": "ai4s/programs/mvcnet/research/mvcnet-acm-s8-loso-extension-gpu10-importfix1.yaml",
          "ledger_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/transaction_status.json",
          "ledger_sha256": "21a778e1a7a56cf7e9befd830b53775ab6361f5dc08c381f25b25cdc95af8349",
          "proof_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/parent_drain.json",
          "proof_sha256": "1bd5df1edce2e446492493d1405b555a092c86ad453d2c7c159fda50da4b10cb",
          "queue_clock_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/science.queue_clock.json",
          "queue_clock_sha256": "7d1dc01817313b23e75774e4bccea87c1234099247a2efea1f5dc28d3a23bb1b",
          "scheduler_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/parent_drain_scheduler.json",
          "scheduler_sha256": "e931d842f8124561559606a73096f5607ee1bb54990905151bd1d84dc663a852"
        }
      ],
      "unstarted_fit_count": 181
    },
    {
      "check_dispatch_count": 270,
      "checkfinish": {
        "check_dispatch_count": 270,
        "fit_dispatch_count": 0,
        "fit_scheduler_metrics_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/checkfix1/scheduler_metrics.json",
        "fit_scheduler_metrics_sha256": "c817c4c36ae83019bf0579f31ed2b55963673a3ead89b28bea7db4d2c458eb22",
        "fit_seal_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/checkfix1/fit_seal.json",
        "fit_seal_sha256": "0ef765a2fa3c9ee523c8dfcfe8085338f2d7a32138736152877188cee5f2b77e",
        "parent_bundle_root": "[REDACTED_MACHINE]",
        "parent_check_dispatch_count": 0,
        "parent_contract_path": "ai4s/programs/mvcnet/research/mvcnet-acm-s8-loso-extension-gpu10-pack1.yaml",
        "parent_contract_sha256": "a42a2d04baa175076ff3a36209d198136c7e1076a7b7ee0469ffb461dc249cbe",
        "parent_failure_log_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/checkfix1/science.log",
        "parent_failure_log_sha256": "75135e2ddb36643dc4e18580c5a0169c3677b290976fe49694af94a7543d606e",
        "parent_ledger_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/checkfix1/transaction_status.json",
        "parent_ledger_sha256": "340a6a176336e375c379ec78cfe726410acbd626c18c4b5617577f417424bd77",
        "parent_run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1",
        "settlement_path": "ai4s/_work/s8_loso_extension_20261118/gpu10/pack1/checkfix1/budget_settlement.json",
        "settlement_sha256": "32d19127d61c8529c2938b3bcea876d0383091808caaa8f38edb93ccc33be392"
      },
      "fit_dispatch_count": 0,
      "kind": "verified_s8_checks_only_repair",
      "parent_run": {
        "bundle_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-bundle",
        "capacity_rollover_of": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-importfix1-full-w1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 451,
        "estimated_training_hours": 35.178,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 540,
        "recorded_at": "2026-11-18T05:08:39.702448+00:00",
        "round_id": "mvcnet-acm-s8-loso-extension-gpu10-pack1",
        "run_prefix": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-18T05:08:54.246392+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-18T05:09:36.276303+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-18T05:11:56.146394+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a42a2d04baa175076ff3a36209d198136c7e1076a7b7ee0469ffb461dc249cbe",
                "execution_seconds": 138.22561049461365,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1",
                "transaction_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 138.22561049461365
              }
            }
          }
        ]
      },
      "parent_run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1",
      "recorded_at": "2026-11-18T08:39:07.605625+00:00",
      "reused_fit_count": 270
    }
  ],
  "completed_rounds": [
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-r01-vcn-p1-new-seed-stability-v0.1"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-r01-vcn-p1-new-seed-stability-v0.1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-r01-vcn-p1-new-seed-stability-v0.1",
      "round_id": "mvcnet-r01-vcn-p1-new-seed-stability-v0.1",
      "run": {
        "bundle_id": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1_bundle_r1b",
        "estimated_training_hours": 7.407,
        "planned_units": 36,
        "recorded_at": "2026-08-30T05:40:20.694905+00:00",
        "retry_of": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1-check",
        "round_id": "mvcnet-r01-vcn-p1-new-seed-stability-v0.1",
        "run_prefix": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1b"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l1-seed78-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l1-seed78-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l1-seed78-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l1-seed78-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_bundle_fixed1024_r1b",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-08-31T17:18:35.803010+00:00",
        "retry_of": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_fixed1024-full-w1",
        "round_id": "mvcnet-lab10-l1-seed78-fixed1024-v1.0",
        "run_prefix": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_fixed1024_r1b"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l2-seed910-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l2-seed910-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l2-seed910-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l2-seed910-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l2_seed910_bundle_fixed1024_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-01T04:25:58.876917+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-01_ai4s_mvcnet_lab10_l2_seed910_fixed1024_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_reconciled_at": "2026-09-01T04:17:58.835128+00:00",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-01T03:28:33.011537+00:00",
        "round_id": "mvcnet-lab10-l2-seed910-fixed1024-v1.0",
        "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l2_seed910_fixed1024_r1"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l3-seed1112-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l3-seed1112-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l3-seed1112-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l3-seed1112-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l3_seed1112_bundle_fixed1024_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-01T12:14:35.300277+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-01_ai4s_mvcnet_lab10_l3_seed1112_fixed1024_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-01T12:13:26.525251+00:00",
        "round_id": "mvcnet-lab10-l3-seed1112-fixed1024-v1.0",
        "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l3_seed1112_fixed1024_r1"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l4-seed1314-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l4-seed1314-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l4-seed1314-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l4-seed1314-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l4_seed1314_bundle_fixed1024_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-01T16:10:06.848920+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-01_ai4s_mvcnet_lab10_l4_seed1314_fixed1024_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-01T16:09:04.732950+00:00",
        "round_id": "mvcnet-lab10-l4-seed1314-fixed1024-v1.0",
        "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l4_seed1314_fixed1024_r1"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l5-seed1516-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l5-seed1516-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l5-seed1516-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l5-seed1516-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l5_seed1516_bundle_fixed1024_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-02T00:14:07.139536+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-01_ai4s_mvcnet_lab10_l5_seed1516_fixed1024_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-01T22:11:00.611170+00:00",
        "round_id": "mvcnet-lab10-l5-seed1516-fixed1024-v1.0",
        "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l5_seed1516_fixed1024_r1"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l6-seed1718-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l6-seed1718-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l6-seed1718-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l6-seed1718-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-09-02_ai4s_mvcnet_lab10_l6_seed1718_bundle_fixed1024_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-02T04:17:09.881936+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-02_ai4s_mvcnet_lab10_l6_seed1718_fixed1024_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-02T04:16:01.581269+00:00",
        "round_id": "mvcnet-lab10-l6-seed1718-fixed1024-v1.0",
        "run_prefix": "2026-09-02_ai4s_mvcnet_lab10_l6_seed1718_fixed1024_r1"
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "mvcnet-lab10-l7-seed1920-fixed1024-v1.0"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l7-seed1920-fixed1024-v1.0_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-lab10-l7-seed1920-fixed1024-v1.0",
      "round_id": "mvcnet-lab10-l7-seed1920-fixed1024-v1.0",
      "run": {
        "bundle_id": "2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_bundle_fixed1024_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-02T08:16:55.428470+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_fixed1024_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-02T08:15:38.984875+00:00",
        "round_id": "mvcnet-lab10-l7-seed1920-fixed1024-v1.0",
        "run_prefix": "2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_fixed1024_r1"
      }
    },
    {
      "decision": {
        "decision": "INVALID",
        "reason": "matrix is incomplete",
        "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.1"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-scva-cvc-s0p0-screen-lab10-v0.1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-scva-cvc-s0p0-screen-lab10-v0.1",
      "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.1",
      "run": {
        "bundle_id": "2026-09-03_ai4s_mvcnet_scva_s0p0_bundle_lab10_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-02T20:16:38.898524+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r1-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-02T20:10:46.694057+00:00",
        "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.1",
        "run_prefix": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r1"
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2"
      },
      "decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-scva-cvc-s0p0-screen-lab10-v0.2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
      "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
      "run": {
        "bundle_id": "2026-09-03_ai4s_mvcnet_scva_s0p0_bundle_lab10_r2",
        "dispatch_receipt": {
          "observed_at": "2026-09-03T01:13:15.239712+00:00",
          "path": "ai4s/archive/programs/mvcnet/research/dispatch_receipts/2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1/run_status.json",
          "remote_status": "running"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.407,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-03T01:08:21.537253+00:00",
        "round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
        "run_prefix": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2"
      }
    },
    {
      "decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "mvcnet-tapr-v0.1-screen-lab10-r1"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-tapr-v0.1-screen-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-tapr-v0.1-screen-lab10-r1",
      "round_id": "mvcnet-tapr-v0.1-screen-lab10-r1",
      "run": {
        "bundle_id": "2026-09-07_mvcnet_tapr_lab10_bundle_r5",
        "dispatch_receipt": {
          "observed_at": "2026-09-07T03:04:07.182786+00:00",
          "path": "ai4s\\_work\\tapr_20260906\\remote_r5_launch\\transaction_status.json",
          "sha256": "77fe797e8493d9d1940b2899860e1b7fb2138e082993b4b573b692171f61444e",
          "type": "transaction_ledger"
        },
        "dispatch_status": "REMOTE_COMPLETE_FETCHED_VERIFIED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 9,
        "queue_time_policy": "exclude_resource_wait",
        "recorded_at": "2026-09-06T10:27:20.342317+00:00",
        "recovery_analysis": {
          "analysis_sha256": "ffd39280c1487f61cfa33a77bf352045039abc7dc9e2a33817ede1885a6c11ee",
          "device_association_review": "UNRESOLVED",
          "formal_decision_registered": false,
          "frozen_rule_result": "NO_SIGNAL",
          "independent_review": "BACKEND_UNAVAILABLE",
          "path": "ai4s/programs/mvcnet/research/tapr_r4_r5_analysis/REPORT.md",
          "r5_manifest_verified": true,
          "retained_r4_task_hashes_verified": true,
          "task_count": 45
        },
        "repair_record": "ai4s/programs/mvcnet/research/TAPR_COMPAT_REPAIR_20260906.md",
        "retained_task_units": 37,
        "retry_of": "2026-09-07_mvcnet_tapr_lab10_r4-full-w1",
        "round_id": "mvcnet-tapr-v0.1-screen-lab10-r1",
        "run_prefix": "2026-09-07_mvcnet_tapr_lab10_r5",
        "ssh_alias": "[REDACTED_MACHINE]",
        "transaction_timeout_seconds": 14400,
        "transport_authorization": "用户：直接从本机通过新增的ssh [REDACTED_MACHINE]-via-ccmu链路推送实验"
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-tcrd-v0.1-screen-lab10-r1"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-tcrd-v0.1-screen-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-tcrd-v0.1-screen-lab10-r1",
      "round_id": "mvcnet-tcrd-v0.1-screen-lab10-r1",
      "run": {
        "bundle_id": "2026-09-07_mvcnet_tcrd_lab10_bundle_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-07T06:12:49.975982+00:00",
          "path": "ai4s/_work/tcrd_20260907/remote_launch/transaction_status.json",
          "sha256": "f5c9b4d9ad3f275cfef5cd975cf89fc6b4a0d415744db05b8c2a4ad75a120ec2",
          "type": "transaction_ledger"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 9.877,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 48,
        "recorded_at": "2026-09-07T06:10:55.172653+00:00",
        "round_id": "mvcnet-tcrd-v0.1-screen-lab10-r1",
        "run_prefix": "2026-09-07_mvcnet_tcrd_lab10_r1",
        "ssh_alias": "[REDACTED_MACHINE]"
      }
    },
    {
      "decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "source-only diagnostic observation; no performance screen or paper claim",
        "round_id": "mvcnet-vogr-d0-diagnostic-lab10-r1"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-vogr-d0-diagnostic-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-vogr-d0-diagnostic-lab10-r1",
      "round_id": "mvcnet-vogr-d0-diagnostic-lab10-r1",
      "run": {
        "bundle_id": "2026-09-07_mvcnet_vogr_lab10_bundle_r3",
        "dispatch_receipt": {
          "observed_at": "2026-09-07T14:00:29.987326+00:00",
          "path": "ai4s\\_work\\vogr_20260907\\remote_r3_launch\\transaction_status.json",
          "sha256": "e86120d72e756178a16cb94ac92515895d12a405d6329ab42cae14db49d422c4",
          "type": "transaction_ledger"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 8,
        "recorded_at": "2026-09-07T11:13:47.375902+00:00",
        "retained_task_units": 11,
        "retry_of": "2026-09-07_mvcnet_vogr_lab10_r2-full-w1",
        "round_id": "mvcnet-vogr-d0-diagnostic-lab10-r1",
        "run_prefix": "2026-09-07_mvcnet_vogr_lab10_r3",
        "ssh_alias": "[REDACTED_MACHINE]",
        "transaction_timeout_seconds": 14400,
        "transport_authorization": "VOGR_AUTHORIZATION.md: user confirmed one-stage 10h GPU0-9 execution"
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1-repair2"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-ocst-v0.1-screen-lab10-r1-repair2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-ocst-v0.1-screen-lab10-r1-repair2",
      "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1-repair2",
      "run": {
        "bundle_id": "2026-09-08_mvcnet_ocst_lab10_bundle_r3",
        "dispatch_receipt": {
          "observed_at": "2026-09-08T04:50:22.231840+00:00",
          "path": "ai4s/_work/ocst_20260908/r3_launch/transaction_status.json",
          "sha256": "2f137b78b8310f2e45fd3b3807170f468dc4cf959eeb9321b8e2ac18b6168872"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 12.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "new_fit_units": 61,
        "planned_units": 95,
        "recorded_at": "2026-09-08T04:46:53.855070+00:00",
        "retry_of": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1",
        "reused_scientific_units": 34,
        "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1-repair2",
        "run_prefix": "2026-09-08_mvcnet_ocst_lab10_r3",
        "ssh_alias": "[REDACTED_MACHINE]",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-08T04:50:22.231840+00:00",
            "result": {
              "action": "UPLOADED_VERIFIED",
              "receipt": "ai4s/programs/mvcnet/research/OCST_R3_UPLOAD_RECEIPT_20260908.json"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-08T04:50:22.231840+00:00",
            "result": {
              "action": "REMOTE_ACCEPTED",
              "pid": "[REDACTED_MACHINE]"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T04:51:20.344270+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 105.12116718292236,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": false,
                "wall_seconds": 105.12116718292236
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T13:37:16.569957+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 21410.546359539032,
                "queue_seconds": 10248.405418634415,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": false,
                "wall_seconds": 31658.951778173447
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T14:19:59.685481+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 23974.25834965706,
                "queue_seconds": 10248.405418634415,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": false,
                "wall_seconds": 34222.66376829147
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T16:02:43.425536+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 30138.163298606873,
                "queue_seconds": 10248.405418634415,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": false,
                "wall_seconds": 40386.56871724129
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T16:45:24.809343+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32586.01293683052,
                "queue_seconds": 10361.357925653458,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 42947.37086248398
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T17:00:00.891825+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32586.013247966766,
                "queue_seconds": 11238.1125934124,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 43824.125841379166
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T17:10:21.413919+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32586.01286959648,
                "queue_seconds": 11858.016333341599,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 44444.02920293808
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T17:19:34.123862+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32586.0128633976,
                "queue_seconds": 12410.658194303513,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 44996.67105770111
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T18:40:23.153590+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32595.588133573532,
                "queue_seconds": 17250.404087543488,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 49845.99222111702
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T19:31:12.068529+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32597.57228255272,
                "queue_seconds": 20297.505122184753,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 52895.07740473747
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T20:27:45.907260+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 32795.941015958786,
                "queue_seconds": 23493.72462296486,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": true,
                "wall_seconds": 56289.665638923645
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T02:21:44.363570+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "bee4cac0704cd8c4ea7bd1873f482b70b8ce32db3fa94d7750853dadb84ee342",
                "execution_seconds": 34795.36248779297,
                "queue_seconds": 40996.55089712143,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r3-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r3",
                "waiting_for_resources": false,
                "wall_seconds": 75791.9133849144
              }
            },
            "transport_host": "[REDACTED_MACHINE]"
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "source-only readout diagnosis; no performance screen or paper claim",
        "round_id": "mvcnet-wcr-d0-diagnostic-lab10-r1"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-wcr-d0-diagnostic-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-wcr-d0-diagnostic-lab10-r1",
      "round_id": "mvcnet-wcr-d0-diagnostic-lab10-r1",
      "run": {
        "bundle_id": "2026-09-09_mvcnet_wcr_d0_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.583,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-09T06:46:02.361025+00:00",
        "round_id": "mvcnet-wcr-d0-diagnostic-lab10-r1",
        "run_prefix": "2026-09-09_mvcnet_wcr_d0_lab10_r1",
        "transaction_operations": [
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T06:58:14.138556+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ca069ca67ab77643722a7b2af2d9bb8305b56cd48fb285a7b6afe093d8d20ca6",
                "execution_seconds": 153.77106404304504,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
                "transaction_id": "mvcnet-wcr-d0-tx-20260909-r1",
                "waiting_for_resources": false,
                "wall_seconds": 153.77106404304504
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T09:33:06.035236+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "ca069ca67ab77643722a7b2af2d9bb8305b56cd48fb285a7b6afe093d8d20ca6",
                "execution_seconds": 8467.830948114395,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
                "transaction_id": "mvcnet-wcr-d0-tx-20260909-r1",
                "waiting_for_resources": false,
                "wall_seconds": 8467.830948114395
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T09:35:13.485775+00:00",
            "result": {
              "artifact_manifest_sha256": "0250b3d6566a2c42b85447a6ac7e2aca76fa0737aa48ad18a46aed9ba922ea9a",
              "contract_sha256": "ca069ca67ab77643722a7b2af2d9bb8305b56cd48fb285a7b6afe093d8d20ca6",
              "run_id": "2026-09-09_mvcnet_wcr_d0_lab10_r1-full-w1",
              "transaction_id": "mvcnet-wcr-d0-tx-20260909-r1",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "DIAGNOSTIC_SUPPORT",
        "reason": "source-only readout transfer diagnosis; no outer-target evaluation or paper claim",
        "round_id": "mvcnet-srtd-d0-diagnostic-lab10-r1"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-srtd-d0-diagnostic-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-srtd-d0-diagnostic-lab10-r1",
      "round_id": "mvcnet-srtd-d0-diagnostic-lab10-r1",
      "run": {
        "bundle_id": "2026-09-09_mvcnet_srtd_d0_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.583,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-09T10:24:06.754991+00:00",
        "round_id": "mvcnet-srtd-d0-diagnostic-lab10-r1",
        "run_prefix": "2026-09-09_mvcnet_srtd_d0_lab10_r1",
        "transaction_operations": [
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T10:29:09.739314+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "fda94a78401b1bfb2b9c2c0738569ce51d2762ddd987728d1cf2589482c63014",
                "execution_seconds": 42.35027050971985,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
                "transaction_id": "mvcnet-srtd-d0-tx-20260909-r1",
                "waiting_for_resources": false,
                "wall_seconds": 42.35027050971985
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T12:56:55.507240+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "fda94a78401b1bfb2b9c2c0738569ce51d2762ddd987728d1cf2589482c63014",
                "execution_seconds": 8907.362440347672,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
                "transaction_id": "mvcnet-srtd-d0-tx-20260909-r1",
                "waiting_for_resources": false,
                "wall_seconds": 8907.362440347672
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T15:19:52.958539+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "fda94a78401b1bfb2b9c2c0738569ce51d2762ddd987728d1cf2589482c63014",
                "execution_seconds": 14847.843437671661,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
                "transaction_id": "mvcnet-srtd-d0-tx-20260909-r1",
                "waiting_for_resources": false,
                "wall_seconds": 14847.843437671661
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T15:20:03.969838+00:00",
            "result": {
              "artifact_manifest_sha256": "dd60d9ebd8ec772ce292f914e051cb5105424470dd05cc7e8fe6185e10daec97",
              "contract_sha256": "fda94a78401b1bfb2b9c2c0738569ce51d2762ddd987728d1cf2589482c63014",
              "run_id": "2026-09-09_mvcnet_srtd_d0_lab10_r1-full-w1",
              "transaction_id": "mvcnet-srtd-d0-tx-20260909-r1",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "frozen calibration transfer diagnosis; target evaluation only, no backbone training or paper claim",
        "round_id": "mvcnet-srtd-t1-diagnostic-lab10-r2"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-srtd-t1-diagnostic-lab10-r2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-srtd-t1-diagnostic-lab10-r2",
      "round_id": "mvcnet-srtd-t1-diagnostic-lab10-r2",
      "run": {
        "bundle_id": "2026-09-10_mvcnet_srtd_t1_lab10_bundle_r2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.583,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-09T16:31:15.320402+00:00",
        "round_id": "mvcnet-srtd-t1-diagnostic-lab10-r2",
        "run_prefix": "2026-09-10_mvcnet_srtd_t1_lab10_r2",
        "transaction_operations": [
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T16:32:47.080602+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "83df4a6ee95a9e2089e93a22b4e80f9e1d24fa88db5823d2dd7dfc20e3594915",
                "execution_seconds": 44.15142750740051,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
                "transaction_id": "mvcnet-srtd-t1-tx-20260910-r2",
                "waiting_for_resources": false,
                "wall_seconds": 44.15142750740051
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T16:33:33.244523+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "83df4a6ee95a9e2089e93a22b4e80f9e1d24fa88db5823d2dd7dfc20e3594915",
                "execution_seconds": 90.32332062721252,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
                "transaction_id": "mvcnet-srtd-t1-tx-20260910-r2",
                "waiting_for_resources": false,
                "wall_seconds": 90.32332062721252
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T17:10:28.891610+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "83df4a6ee95a9e2089e93a22b4e80f9e1d24fa88db5823d2dd7dfc20e3594915",
                "execution_seconds": 1377.7600412368774,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
                "transaction_id": "mvcnet-srtd-t1-tx-20260910-r2",
                "waiting_for_resources": false,
                "wall_seconds": 1377.7600412368774
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T17:10:57.138986+00:00",
            "result": {
              "artifact_manifest_sha256": "965850cd247cd4fcbc773e23c1e7c8af2b93fd4eb82ea7c21b7bac48939be516",
              "contract_sha256": "83df4a6ee95a9e2089e93a22b4e80f9e1d24fa88db5823d2dd7dfc20e3594915",
              "run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r2-full-w1",
              "transaction_id": "mvcnet-srtd-t1-tx-20260910-r2",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "source-only conditional readout diagnosis; no backbone training or paper claim",
        "round_id": "mvcnet-srtd-c1-diagnostic-lab10-r1"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-srtd-c1-diagnostic-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-srtd-c1-diagnostic-lab10-r1",
      "round_id": "mvcnet-srtd-c1-diagnostic-lab10-r1",
      "run": {
        "bundle_id": "2026-09-10_mvcnet_srtd_c1_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.583,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-09T18:46:30.767717+00:00",
        "round_id": "mvcnet-srtd-c1-diagnostic-lab10-r1",
        "run_prefix": "2026-09-10_mvcnet_srtd_c1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T18:47:24.960853+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ae511d3a9a1a64a73aa5f26ae758bc45821dc292b42621e692cf1cfb9d0cf865",
                "execution_seconds": 9.782309532165527,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
                "transaction_id": "mvcnet-srtd-c1-tx-20260910-r1",
                "waiting_for_resources": false,
                "wall_seconds": 9.782309532165527
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T18:48:32.775335+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ae511d3a9a1a64a73aa5f26ae758bc45821dc292b42621e692cf1cfb9d0cf865",
                "execution_seconds": 77.58704662322998,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
                "transaction_id": "mvcnet-srtd-c1-tx-20260910-r1",
                "waiting_for_resources": false,
                "wall_seconds": 77.58704662322998
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T04:12:32.849376+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "ae511d3a9a1a64a73aa5f26ae758bc45821dc292b42621e692cf1cfb9d0cf865",
                "execution_seconds": 376.78810119628906,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
                "transaction_id": "mvcnet-srtd-c1-tx-20260910-r1",
                "waiting_for_resources": false,
                "wall_seconds": 376.78810119628906
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-10T04:12:51.193665+00:00",
            "result": {
              "artifact_manifest_sha256": "ca8c4d1f6b9fc62d0a19d15673d9e69b8806fd256427389d76f7d9034abfae4b",
              "contract_sha256": "ae511d3a9a1a64a73aa5f26ae758bc45821dc292b42621e692cf1cfb9d0cf865",
              "run_id": "2026-09-10_mvcnet_srtd_c1_lab10_r1-full-w1",
              "transaction_id": "mvcnet-srtd-c1-tx-20260910-r1",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "frozen S0/P0/N0 screen did not pass all paired gates; no_paper_claim",
        "round_id": "mvcnet-source-factorized-head-screen-lab10-r2"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-factorized-head-screen-lab10-r2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-factorized-head-screen-lab10-r2",
      "round_id": "mvcnet-source-factorized-head-screen-lab10-r2",
      "run": {
        "bundle_id": "2026-09-10_mvcnet_sfh_lab10_bundle_r2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.75,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-10T07:34:27.292111+00:00",
        "recovery_of": "2026-09-10_mvcnet_sfh_lab10_r1-full-w1",
        "round_id": "mvcnet-source-factorized-head-screen-lab10-r2",
        "run_prefix": "2026-09-10_mvcnet_sfh_lab10_r2",
        "transaction_operations": [
          {
            "operation": "launch",
            "recorded_at": "2026-09-10T07:45:41.281413+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T07:46:33.115174+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "706d2021dd66ebb9477b144b39aa09ccddf4788f878bf6921110da72428ee556",
                "execution_seconds": 11.236568212509155,
                "queue_seconds": 38.85790419578552,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
                "transaction_id": "mvcnet-sfh-tx-20260910-r2",
                "waiting_for_resources": true,
                "wall_seconds": 50.09447240829468
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T13:06:50.148921+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "706d2021dd66ebb9477b144b39aa09ccddf4788f878bf6921110da72428ee556",
                "execution_seconds": 8992.07553267479,
                "queue_seconds": 75.22376537322998,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
                "transaction_id": "mvcnet-sfh-tx-20260910-r2",
                "waiting_for_resources": false,
                "wall_seconds": 9067.29929804802
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-10T13:07:42.194223+00:00",
            "result": {
              "artifact_manifest_sha256": "70c09f03f9ac9fce4900727b176e5dbe61016fbed2900d7107ba7bb64e507973",
              "contract_sha256": "706d2021dd66ebb9477b144b39aa09ccddf4788f878bf6921110da72428ee556",
              "run_id": "2026-09-10_mvcnet_sfh_lab10_r2-full-w1",
              "transaction_id": "mvcnet-sfh-tx-20260910-r2",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "frozen S0/C0/P0 screen did not pass all main gates; C0-S0 cannot promote; no_paper_claim",
        "round_id": "mvcnet-energy-complementarity-screen-lab10-r3"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-energy-complementarity-screen-lab10-r3_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-energy-complementarity-screen-lab10-r3",
      "round_id": "mvcnet-energy-complementarity-screen-lab10-r3",
      "run": {
        "bundle_id": "2026-09-11_mvcnet_energy_lab10_bundle_r3",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 10,
        "estimated_training_hours": 0.833,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-11T09:10:36.901187+00:00",
        "recovery_of": "2026-09-11_mvcnet_energy_lab10_r2-full-w1",
        "round_id": "mvcnet-energy-complementarity-screen-lab10-r3",
        "run_prefix": "2026-09-11_mvcnet_energy_lab10_r3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-11T09:12:23.211665+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-11T09:13:35.753891+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-11T09:14:01.471254+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8e682f3e2cb6e6beea2a4436cb3e04fe425ce05984c8cc28908d09334f2b7d57",
                "execution_seconds": 22.393019914627075,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
                "transaction_id": "mvcnet-energy-tx-20260911-r3",
                "waiting_for_resources": false,
                "wall_seconds": 22.393019914627075
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-11T09:15:25.222193+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8e682f3e2cb6e6beea2a4436cb3e04fe425ce05984c8cc28908d09334f2b7d57",
                "execution_seconds": 106.14168882369995,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
                "transaction_id": "mvcnet-energy-tx-20260911-r3",
                "waiting_for_resources": false,
                "wall_seconds": 106.14168882369995
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-11T11:11:04.583373+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "8e682f3e2cb6e6beea2a4436cb3e04fe425ce05984c8cc28908d09334f2b7d57",
                "execution_seconds": 3284.867282152176,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
                "transaction_id": "mvcnet-energy-tx-20260911-r3",
                "waiting_for_resources": false,
                "wall_seconds": 3284.867282152176
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-11T11:11:54.846236+00:00",
            "result": {
              "artifact_manifest_sha256": "0e012778c1cf7b518239b69820aab3020a928f039835ed37232852713c1a2547",
              "contract_sha256": "8e682f3e2cb6e6beea2a4436cb3e04fe425ce05984c8cc28908d09334f2b7d57",
              "run_id": "2026-09-11_mvcnet_energy_lab10_r3-full-w1",
              "transaction_id": "mvcnet-energy-tx-20260911-r3",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "aggregate": {
          "endpoint": {
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -2.8564453125,
              -2.63671875,
              -2.8483072916666665,
              -2.5553385416666665,
              -2.6204427083333335,
              -2.7506510416666665,
              -1.7496744791666667,
              -2.8483072916666665,
              -2.5065104166666665
            ],
            "minimum_direction_seed_gain_pp": -14.84375,
            "overall_accuracy_gain_pp": -2.5969328703703702,
            "overall_ce_gain": 0.031767697118924555,
            "per_subject_seed": [
              {
                "accuracy_gain_pp": -2.4739583333333335,
                "ce_gain": -0.0566773529876311,
                "seed": 35,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 1.4322916666666667,
                "ce_gain": -0.051770274722436005,
                "seed": 36,
                "subject": 0
              },
              {
                "accuracy_gain_pp": -1.8229166666666667,
                "ce_gain": -0.01549290209133436,
                "seed": 35,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -2.734375,
                "ce_gain": -0.018711175718011175,
                "seed": 36,
                "subject": 1
              },
              {
                "accuracy_gain_pp": 2.0833333333333335,
                "ce_gain": 0.0062713582933244805,
                "seed": 35,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -3.2552083333333335,
                "ce_gain": -0.04760968196452925,
                "seed": 36,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -2.34375,
                "ce_gain": -0.061895373116734875,
                "seed": 35,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -3.515625,
                "ce_gain": -0.08657977209028889,
                "seed": 36,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -1.5625,
                "ce_gain": 0.08233542751600209,
                "seed": 35,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -3.255208333333333,
                "ce_gain": 0.15575661280014652,
                "seed": 36,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -0.26041666666666663,
                "ce_gain": 0.19841027621884,
                "seed": 35,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -2.4739583333333335,
                "ce_gain": 0.6814662109295778,
                "seed": 36,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -8.59375,
                "ce_gain": -0.11005384412237029,
                "seed": 35,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -10.15625,
                "ce_gain": -0.1287578805091555,
                "seed": 36,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -1.5625,
                "ce_gain": -0.047869942814525335,
                "seed": 35,
                "subject": 7
              },
              {
                "accuracy_gain_pp": 0.390625,
                "ce_gain": -0.0008152742957301395,
                "seed": 36,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -5.989583333333334,
                "ce_gain": 0.06703536613211669,
                "seed": 35,
                "subject": 8
              },
              {
                "accuracy_gain_pp": -0.6510416666666666,
                "ce_gain": 0.006776770683381339,
                "seed": 36,
                "subject": 8
              }
            ],
            "seed_accuracy_gains_pp": [
              -2.5028935185185186,
              -2.6909722222222223
            ],
            "subject_accuracy_gains_pp": [
              -0.5208333333333334,
              -2.2786458333333335,
              -0.5859375,
              -2.9296875,
              -2.4088541666666665,
              -1.3671875,
              -9.375,
              -0.5859375,
              -3.3203125000000004
            ]
          },
          "independent_subjects": 9,
          "main": {
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -2.490234375,
              -2.5390625,
              -2.44140625,
              -2.1321614583333335,
              -2.0589192708333335,
              -2.2542317708333335,
              -1.2858072916666665,
              -2.5309244791666665,
              -2.189127604166667
            ],
            "minimum_direction_seed_gain_pp": -15.364583333333334,
            "overall_accuracy_gain_pp": -2.2135416666666665,
            "overall_ce_gain": 0.027291237006719364,
            "per_subject_seed": [
              {
                "accuracy_gain_pp": -0.3906249999999998,
                "ce_gain": -0.05784724225998211,
                "seed": 35,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 0.390625,
                "ce_gain": -0.0744819784500308,
                "seed": 36,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 2.213541666666667,
                "ce_gain": 0.02560500809365429,
                "seed": 35,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -1.4322916666666665,
                "ce_gain": -0.008694865536459817,
                "seed": 36,
                "subject": 1
              },
              {
                "accuracy_gain_pp": 4.036458333333334,
                "ce_gain": 0.03445243622826405,
                "seed": 35,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -4.817708333333333,
                "ce_gain": -0.058271770671954604,
                "seed": 36,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -2.213541666666667,
                "ce_gain": -0.06575526526334619,
                "seed": 35,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -3.515625,
                "ce_gain": -0.07629402657446471,
                "seed": 36,
                "subject": 3
              },
              {
                "accuracy_gain_pp": -4.947916666666667,
                "ce_gain": 0.020132503937581925,
                "seed": 35,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -1.953125,
                "ce_gain": 0.0822841426944112,
                "seed": 36,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -2.2135416666666665,
                "ce_gain": 0.20098646829851807,
                "seed": 35,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -1.5625,
                "ce_gain": 0.6605150736566773,
                "seed": 36,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -8.854166666666668,
                "ce_gain": -0.11617185294917892,
                "seed": 35,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -10.416666666666668,
                "ce_gain": -0.13661241910160143,
                "seed": 36,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -0.5208333333333333,
                "ce_gain": -0.03819831634220677,
                "seed": 35,
                "subject": 7
              },
              {
                "accuracy_gain_pp": 1.171875,
                "ce_gain": 0.0033758646611127263,
                "seed": 36,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -4.817708333333333,
                "ce_gain": 0.09116168057992502,
                "seed": 35,
                "subject": 8
              },
              {
                "accuracy_gain_pp": 0.0,
                "ce_gain": 0.005056825120029362,
                "seed": 36,
                "subject": 8
              }
            ],
            "seed_accuracy_gains_pp": [
              -1.9675925925925926,
              -2.459490740740741
            ],
            "subject_accuracy_gains_pp": [
              1.1102230246251565e-16,
              0.3906250000000002,
              -0.39062499999999956,
              -2.8645833333333335,
              -3.4505208333333335,
              -1.8880208333333333,
              -9.635416666666668,
              0.32552083333333337,
              -2.4088541666666665
            ]
          },
          "seen_vs_last100": {
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -0.36621093749999994,
              -0.09765625000000001,
              -0.40690104166666663,
              -0.4231770833333333,
              -0.5615234375,
              -0.4964192708333333,
              -0.4638671875,
              -0.31738281249999994,
              -0.31738281249999994
            ],
            "minimum_direction_seed_gain_pp": -5.46875,
            "overall_accuracy_gain_pp": -0.38339120370370366,
            "overall_ce_gain": 0.004476460112205193,
            "per_subject_seed": [
              {
                "accuracy_gain_pp": -2.0833333333333335,
                "ce_gain": 0.0011698892723510101,
                "seed": 35,
                "subject": 0
              },
              {
                "accuracy_gain_pp": 1.0416666666666667,
                "ce_gain": 0.02271170372759479,
                "seed": 36,
                "subject": 0
              },
              {
                "accuracy_gain_pp": -4.036458333333333,
                "ce_gain": -0.04109791018498865,
                "seed": 35,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -1.3020833333333333,
                "ce_gain": -0.010016310181551358,
                "seed": 36,
                "subject": 1
              },
              {
                "accuracy_gain_pp": -1.953125,
                "ce_gain": -0.02818107793493957,
                "seed": 35,
                "subject": 2
              },
              {
                "accuracy_gain_pp": 1.5625,
                "ce_gain": 0.010662088707425355,
                "seed": 36,
                "subject": 2
              },
              {
                "accuracy_gain_pp": -0.13020833333333334,
                "ce_gain": 0.00385989214661131,
                "seed": 35,
                "subject": 3
              },
              {
                "accuracy_gain_pp": 0.0,
                "ce_gain": -0.010285745515824174,
                "seed": 36,
                "subject": 3
              },
              {
                "accuracy_gain_pp": 3.385416666666667,
                "ce_gain": 0.062202923578420166,
                "seed": 35,
                "subject": 4
              },
              {
                "accuracy_gain_pp": -1.3020833333333335,
                "ce_gain": 0.07347247010573532,
                "seed": 36,
                "subject": 4
              },
              {
                "accuracy_gain_pp": 1.953125,
                "ce_gain": -0.0025761920796780746,
                "seed": 35,
                "subject": 5
              },
              {
                "accuracy_gain_pp": -0.9114583333333334,
                "ce_gain": 0.020951137272900544,
                "seed": 36,
                "subject": 5
              },
              {
                "accuracy_gain_pp": 0.26041666666666674,
                "ce_gain": 0.00611800882680863,
                "seed": 35,
                "subject": 6
              },
              {
                "accuracy_gain_pp": 0.26041666666666663,
                "ce_gain": 0.007854538592445948,
                "seed": 36,
                "subject": 6
              },
              {
                "accuracy_gain_pp": -1.0416666666666667,
                "ce_gain": -0.009671626472318562,
                "seed": 35,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -0.78125,
                "ce_gain": -0.004191138956842866,
                "seed": 36,
                "subject": 7
              },
              {
                "accuracy_gain_pp": -1.171875,
                "ce_gain": -0.024126314447808328,
                "seed": 35,
                "subject": 8
              },
              {
                "accuracy_gain_pp": -0.6510416666666667,
                "ce_gain": 0.0017199455633519767,
                "seed": 36,
                "subject": 8
              }
            ],
            "seed_accuracy_gains_pp": [
              -0.5353009259259259,
              -0.2314814814814815
            ],
            "subject_accuracy_gains_pp": [
              -0.5208333333333334,
              -2.669270833333333,
              -0.1953125,
              -0.06510416666666667,
              1.0416666666666667,
              0.5208333333333333,
              0.2604166666666667,
              -0.9114583333333334,
              -0.9114583333333334
            ]
          }
        },
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "reason": "complete frozen six-source selection-transfer diagnostic did not pass the fixed main gate",
        "round_id": "mvcnet-source-selection-transfer-d0-lab10-r8"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-selection-transfer-d0-lab10-r8_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-selection-transfer-d0-lab10-r8",
      "round_id": "mvcnet-source-selection-transfer-d0-lab10-r8",
      "run": {
        "bundle_id": "2026-09-14_mvcnet_sstd0_lab10_bundle_r8",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 18,
        "estimated_training_hours": 1.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-14T15:28:04.530324+00:00",
        "retry_of": "2026-09-14_mvcnet_sstd0_lab10_r7-full-w1",
        "round_id": "mvcnet-source-selection-transfer-d0-lab10-r8",
        "run_prefix": "2026-09-14_mvcnet_sstd0_lab10_r8",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-14T15:28:30.523978+00:00",
            "result": {
              "action": "UPLOADED_VERIFIED",
              "archive_sha256": "9d56849d0509e2cb10090f3f18a6b858c5cab6b9f6f65034085a475bf8fffdd2",
              "files": 111,
              "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-14T15:28:42.695209+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-14T15:28:58.664248+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ed8a7c71def64770486b2027a1af12d08b74f1c9fe3cf48d4d5911f16fdff21e",
                "execution_seconds": 12.328562498092651,
                "queue_seconds": 1.2366766929626465,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
                "transaction_id": "mvcnet-sstd0-tx-20260914-r8",
                "waiting_for_resources": true,
                "wall_seconds": 13.565239191055298
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-14T15:39:14.040736+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "ed8a7c71def64770486b2027a1af12d08b74f1c9fe3cf48d4d5911f16fdff21e",
                "execution_seconds": 211.79992842674255,
                "queue_seconds": 62.43610668182373,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
                "transaction_id": "mvcnet-sstd0-tx-20260914-r8",
                "waiting_for_resources": false,
                "wall_seconds": 274.2360351085663
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-14T15:41:12.974670+00:00",
            "result": {
              "artifact_manifest_sha256": "80e5ed7587fd7bca995fe3d3153af73ca56bcc47debe85d712abb5383a18cee9",
              "contract_sha256": "ed8a7c71def64770486b2027a1af12d08b74f1c9fe3cf48d4d5911f16fdff21e",
              "run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
              "transaction_id": "mvcnet-sstd0-tx-20260914-r8",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "aggregate": {
          "N0-S0": {
            "gates_passed": false,
            "loo_gains_pp": [
              0.6944444444444444,
              0.7269965277777778,
              0.4014756944444444,
              0.5967881944444444,
              0.3255208333333333,
              0.7052951388888888,
              0.6510416666666666,
              0.11935763888888891,
              1.1610243055555556
            ],
            "mean_accuracy_gain_pp": 0.5979938271604939,
            "mean_ce_gain": 0.03157671338227008,
            "minimum_pair_gain_pp": -8.159722222222221,
            "seed_gains_pp": [
              0.0,
              1.1959876543209877
            ],
            "subject_gains_pp": [
              -0.17361111111111116,
              -0.4340277777777779,
              2.170138888888889,
              0.607638888888889,
              2.7777777777777777,
              -0.2604166666666665,
              0.17361111111111094,
              4.427083333333333,
              -3.9062499999999996
            ]
          },
          "P0-N0": {
            "gates_passed": false,
            "loo_gains_pp": [
              -1.07421875,
              -1.0416666666666665,
              -0.9982638888888888,
              -0.9982638888888888,
              -0.9006076388888888,
              -1.1935763888888888,
              -1.1610243055555556,
              -0.6293402777777777,
              -1.3780381944444444
            ],
            "mean_accuracy_gain_pp": -1.0416666666666667,
            "mean_ce_gain": -0.0011569742718150046,
            "minimum_pair_gain_pp": -5.381944444444445,
            "seed_gains_pp": [
              -0.7523148148148149,
              -1.3310185185185186
            ],
            "subject_gains_pp": [
              -0.7812499999999999,
              -1.0416666666666667,
              -1.3888888888888888,
              -1.3888888888888888,
              -2.170138888888889,
              0.17361111111111105,
              -0.08680555555555558,
              -4.340277777777778,
              1.6493055555555558
            ]
          },
          "P0-S0": {
            "gates_passed": false,
            "loo_gains_pp": [
              -0.3797743055555556,
              -0.31467013888888895,
              -0.5967881944444444,
              -0.4014756944444445,
              -0.5750868055555556,
              -0.48828125000000006,
              -0.509982638888889,
              -0.509982638888889,
              -0.2170138888888889
            ],
            "mean_accuracy_gain_pp": -0.44367283950617287,
            "mean_ce_gain": 0.030419739110455077,
            "minimum_pair_gain_pp": -5.902777777777778,
            "seed_gains_pp": [
              -0.7523148148148149,
              -0.13503086419753085
            ],
            "subject_gains_pp": [
              -0.9548611111111112,
              -1.4756944444444444,
              0.78125,
              -0.7812500000000001,
              0.6076388888888888,
              -0.08680555555555547,
              0.08680555555555558,
              0.08680555555555558,
              -2.2569444444444446
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "round_id": "mvcnet-shared-subnetwork-screen-lab10-r3"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-shared-subnetwork-screen-lab10-r3_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-shared-subnetwork-screen-lab10-r3",
      "round_id": "mvcnet-shared-subnetwork-screen-lab10-r3",
      "run": {
        "bundle_id": "2026-09-15_mvcnet_ssn_lab10_bundle_r3",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 97,
        "estimated_training_hours": 8.083,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-15T07:06:13.012664+00:00",
        "recovery_of": "2026-09-15_mvcnet_ssn_lab10_r2-full-w1",
        "round_id": "mvcnet-shared-subnetwork-screen-lab10-r3",
        "run_prefix": "2026-09-15_mvcnet_ssn_lab10_r3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-15T07:06:31.311452+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-15T07:07:33.669773+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-15T07:07:46.953169+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4a390b9306d39bf8aa5021cfa4e0f812ec866a2f05bb3e96f96f13d19d79d303",
                "execution_seconds": 10.972963809967041,
                "queue_seconds": 0.8107006549835205,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
                "transaction_id": "mvcnet-shared-subnetwork-tx-20260915-r3",
                "waiting_for_resources": false,
                "wall_seconds": 11.783664464950562
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-15T11:27:14.476911+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "4a390b9306d39bf8aa5021cfa4e0f812ec866a2f05bb3e96f96f13d19d79d303",
                "execution_seconds": 7079.972918987274,
                "queue_seconds": 1.6073341369628906,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
                "transaction_id": "mvcnet-shared-subnetwork-tx-20260915-r3",
                "waiting_for_resources": false,
                "wall_seconds": 7081.580253124237
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-15T11:28:10.801255+00:00",
            "result": {
              "artifact_manifest_sha256": "58c08e4b6ec5f40ee3f4aff8dd1745467282bb675ea62b730a123892c51cd8d2",
              "contract_sha256": "4a390b9306d39bf8aa5021cfa4e0f812ec866a2f05bb3e96f96f13d19d79d303",
              "run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
              "transaction_id": "mvcnet-shared-subnetwork-tx-20260915-r3",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "aggregate": {
          "D01-D00": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.7426697530864198,
              0.7040895061728395
            ],
            "bootstrap_ce_gain_ci": [
              -0.017615773511917152,
              0.094077370563808
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": true,
            "ci_level": 95.0,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.02170138888888886,
              -0.17361111111111113,
              0.0759548611111111,
              -3.469446951953614e-17,
              -0.17361111111111113,
              -0.3363715277777778,
              -0.09765625000000003,
              0.043402777777777755,
              0.11935763888888887
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": -0.05787037037037039,
            "mean_ce_gain": 0.026108075162186925,
            "minimum_pair_gain_pp": -1.7361111111111112,
            "seed_accuracy_gains_pp": [
              -0.5594135802469136,
              0.4436728395061728
            ],
            "subject_accuracy_gains_pp": [
              -0.6944444444444444,
              0.8680555555555555,
              -1.1284722222222223,
              -0.5208333333333333,
              0.8680555555555555,
              2.170138888888889,
              0.2604166666666667,
              -0.8680555555555556,
              -1.4756944444444444
            ]
          },
          "D10-D00": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.935570987654321,
              0.6462191358024693
            ],
            "bootstrap_ce_gain_ci": [
              -0.03842189869068714,
              0.015229840241639519
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": false,
            "ci_level": 95.0,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -0.2061631944444444,
              -0.16276041666666663,
              -0.21701388888888884,
              -0.5642361111111112,
              -0.3255208333333333,
              -0.21701388888888884,
              5.204170427930421e-17,
              -0.07595486111111108,
              -0.14105902777777773
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": -0.21219135802469133,
            "mean_ce_gain": -0.010222560427125334,
            "minimum_pair_gain_pp": -3.8194444444444446,
            "seed_accuracy_gains_pp": [
              -0.1350308641975308,
              -0.28935185185185186
            ],
            "subject_accuracy_gains_pp": [
              -0.2604166666666667,
              -0.6076388888888888,
              -0.17361111111111116,
              2.604166666666667,
              0.6944444444444445,
              -0.17361111111111113,
              -1.9097222222222223,
              -1.3020833333333333,
              -0.78125
            ]
          },
          "D11-D00": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.1091820987654322,
              1.4371141975308641
            ],
            "bootstrap_ce_gain_ci": [
              -0.07475953884083085,
              0.0677195831730413
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": false,
            "ci_level": 98.33333333333333,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.10850694444444448,
              0.0759548611111111,
              0.6076388888888888,
              0.1736111111111111,
              0.24956597222222224,
              0.09765625,
              0.4014756944444444,
              0.1736111111111111,
              0.6293402777777778
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.2797067901234568,
            "mean_ce_gain": 0.00027058503454198873,
            "minimum_pair_gain_pp": -6.25,
            "seed_accuracy_gains_pp": [
              0.38580246913580246,
              0.17361111111111116
            ],
            "subject_accuracy_gains_pp": [
              1.6493055555555554,
              1.9097222222222223,
              -2.34375,
              1.1284722222222223,
              0.5208333333333333,
              1.7361111111111112,
              -0.6944444444444444,
              1.1284722222222223,
              -2.517361111111111
            ]
          },
          "D11-D01": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.6688046553497943,
              1.4018293467078236
            ],
            "bootstrap_ce_gain_ci": [
              -0.08021215276526114,
              0.017450475300456826
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": true,
            "ci_level": 98.33333333333333,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.08680555555555551,
              0.2495659722222222,
              0.5316840277777777,
              0.1736111111111111,
              0.42317708333333326,
              0.43402777777777773,
              0.4991319444444444,
              0.13020833333333331,
              0.5099826388888888
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.33757716049382713,
            "mean_ce_gain": -0.025837490127644937,
            "minimum_pair_gain_pp": -4.861111111111111,
            "seed_accuracy_gains_pp": [
              0.945216049382716,
              -0.2700617283950617
            ],
            "subject_accuracy_gains_pp": [
              2.34375,
              1.0416666666666665,
              -1.2152777777777777,
              1.6493055555555554,
              -0.3472222222222221,
              -0.4340277777777778,
              -0.9548611111111112,
              1.9965277777777777,
              -1.0416666666666667
            ]
          },
          "D11-D10": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.954861111111111,
              1.7939814814814816
            ],
            "bootstrap_ce_gain_ci": [
              -0.035860211079001586,
              0.05702133568372893
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": false,
            "ci_level": 98.33333333333333,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.31467013888888895,
              0.23871527777777785,
              0.8246527777777779,
              0.7378472222222223,
              0.5750868055555556,
              0.31467013888888895,
              0.40147569444444453,
              0.24956597222222232,
              0.7703993055555556
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.4918981481481482,
            "mean_ce_gain": 0.010493145461667321,
            "minimum_pair_gain_pp": -5.208333333333333,
            "seed_accuracy_gains_pp": [
              0.5208333333333334,
              0.462962962962963
            ],
            "subject_accuracy_gains_pp": [
              1.9097222222222223,
              2.517361111111111,
              -2.170138888888889,
              -1.4756944444444442,
              -0.17361111111111094,
              1.9097222222222223,
              1.215277777777778,
              2.4305555555555554,
              -1.7361111111111112
            ]
          },
          "interaction": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.42438271604938266,
              1.6010802469135803
            ],
            "bootstrap_ce_gain_ci": [
              -0.05828274247145702,
              0.0210623603943979
            ],
            "bootstrap_replicates": 20000,
            "ce_tradeoff": true,
            "ci_level": 95.0,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              0.29296875,
              0.4123263888888889,
              0.7486979166666666,
              0.7378472222222222,
              0.7486979166666666,
              0.6510416666666666,
              0.4991319444444444,
              0.20616319444444442,
              0.6510416666666666
            ],
            "material_stable": false,
            "mean_accuracy_gain_pp": 0.5497685185185185,
            "mean_ce_gain": -0.01561492970051961,
            "minimum_pair_gain_pp": -5.034722222222222,
            "seed_accuracy_gains_pp": [
              1.0802469135802468,
              0.01929012345679014
            ],
            "subject_accuracy_gains_pp": [
              2.6041666666666665,
              1.6493055555555554,
              -1.0416666666666665,
              -0.9548611111111109,
              -1.0416666666666667,
              -0.2604166666666667,
              0.9548611111111112,
              3.298611111111111,
              -0.2604166666666667
            ]
          }
        },
        "contribution_map": {
          "D01-D00": "none",
          "D10-D00": "none",
          "D11-D00": "none",
          "D11-D01": "none",
          "D11-D10": "none",
          "interaction": "none"
        },
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "round_id": "mvcnet-contrastive-factorial-diagnostic-lab10-r3"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-contrastive-factorial-diagnostic-lab10-r3_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-contrastive-factorial-diagnostic-lab10-r3",
      "round_id": "mvcnet-contrastive-factorial-diagnostic-lab10-r3",
      "run": {
        "bundle_id": "2026-09-15_mvcnet_ccf_lab10_bundle_r3",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 136,
        "estimated_training_hours": 8.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 149,
        "recorded_at": "2026-09-16T04:01:08.957913+00:00",
        "recovery_of": "2026-09-15_mvcnet_ccf_lab10_r2a-full-w1",
        "round_id": "mvcnet-contrastive-factorial-diagnostic-lab10-r3",
        "run_prefix": "2026-09-15_mvcnet_ccf_lab10_r3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-16T04:01:19.061054+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-16T04:07:17.173026+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T04:07:25.059214+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 4.572739362716675,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": false,
                "wall_seconds": 4.572739362716675
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T06:04:06.645753+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 4720.632656574249,
                "queue_seconds": 2285.6753590106964,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": false,
                "wall_seconds": 7006.308015584946
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T10:45:53.471731+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 18302.470905303955,
                "queue_seconds": 5608.437703132629,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": true,
                "wall_seconds": 23910.908608436584
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T10:48:34.144352+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 18302.47124838829,
                "queue_seconds": 5769.123576402664,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": true,
                "wall_seconds": 24071.594824790955
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T11:56:54.000394+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 18302.47284221649,
                "queue_seconds": 9869.011158943176,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": true,
                "wall_seconds": 28171.484001159668
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T15:00:08.517358+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 18302.472361326218,
                "queue_seconds": 20863.918405056,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": true,
                "wall_seconds": 39166.39076638222
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T16:36:56.898000+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 18302.471775770187,
                "queue_seconds": 26669.953315734863,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": true,
                "wall_seconds": 44972.42509150505
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T18:02:35.136098+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 18302.4728243351,
                "queue_seconds": 31808.312581539154,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": true,
                "wall_seconds": 50110.78540587425
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-17T03:37:59.160938+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
                "execution_seconds": 22236.9811770916,
                "queue_seconds": 32686.180792331696,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
                "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
                "waiting_for_resources": false,
                "wall_seconds": 54923.161969423294
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-17T03:45:15.995606+00:00",
            "result": {
              "artifact_manifest_sha256": "eca0c136bdea92106a1ec58189c561fb429e1da27e85a79dad32588d34cf4126",
              "contract_sha256": "632ffeef9f8853ebfe35542cc645f6e990262d8cb9e2aef4a80fbd5157582483",
              "run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
              "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r3",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "aggregate": {
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -3.423996913580247,
              0.14467592592592593
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260917,
            "ce_gain_nonnegative": false,
            "ci_level": 95.0,
            "direction": "descriptive",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              -1.26953125,
              -1.3780381944444444,
              -1.5082465277777777,
              -1.3020833333333333,
              -1.3237847222222223,
              -1.2261284722222223,
              -1.4865451388888888,
              -1.3888888888888888,
              -0.22786458333333331
            ],
            "mean_accuracy_gain_pp": -1.2345679012345678,
            "mean_ce_gain": -0.021747564294052793,
            "seed_accuracy_gains_pp": [
              -1.7939814814814816,
              -0.6751543209876544
            ],
            "subject_accuracy_gains_pp": [
              -0.954861111111111,
              -0.08680555555555558,
              0.954861111111111,
              -0.6944444444444444,
              -0.5208333333333333,
              -1.3020833333333333,
              0.78125,
              0.0,
              -9.288194444444445
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.6847993827160493,
              3.607253086419753
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260917,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "loo_accuracy_gains_pp": [
              1.0308159722222223,
              1.4539930555555556,
              1.0633680555555556,
              1.0308159722222223,
              0.9765625,
              1.2369791666666667,
              1.1827256944444444,
              1.2478298611111112,
              0.06510416666666671
            ],
            "mean_accuracy_gain_pp": 1.0320216049382716,
            "mean_ce_gain": -0.030486518824137967,
            "seed_accuracy_gains_pp": [
              1.6396604938271604,
              0.42438271604938277
            ],
            "subject_accuracy_gains_pp": [
              1.0416666666666667,
              -2.34375,
              0.78125,
              1.0416666666666667,
              1.4756944444444444,
              -0.6076388888888888,
              -0.17361111111111094,
              -0.6944444444444444,
              8.76736111111111
            ]
          },
          "P0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.1670524691358024,
              0.6944444444444445
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260917,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.23871527777777773,
              0.07595486111111113,
              -0.4448784722222222,
              -0.27126736111111105,
              -0.3472222222222222,
              0.010850694444444503,
              -0.3038194444444444,
              -0.14105902777777773,
              -0.16276041666666663
            ],
            "mean_accuracy_gain_pp": -0.20254629629629625,
            "mean_ce_gain": -0.052234083118190756,
            "seed_accuracy_gains_pp": [
              -0.15432098765432098,
              -0.2507716049382716
            ],
            "subject_accuracy_gains_pp": [
              0.08680555555555558,
              -2.4305555555555554,
              1.7361111111111112,
              0.3472222222222223,
              0.9548611111111112,
              -1.9097222222222223,
              0.6076388888888888,
              -0.6944444444444444,
              -0.5208333333333333
            ]
          }
        },
        "decision": "NO_SIGNAL",
        "interpretation_boundary": "selection-used discovery only; no default protocol or paper claim",
        "round_id": "mvcnet-cross-objective-collision-screen-lab10-r8"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-cross-objective-collision-screen-lab10-r8_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-cross-objective-collision-screen-lab10-r8",
      "round_id": "mvcnet-cross-objective-collision-screen-lab10-r8",
      "run": {
        "bundle_id": "2026-09-17_mvcnet_coc_lab10_bundle_r8",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 56,
        "estimated_training_hours": 3.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-19T07:43:26.307662+00:00",
        "recovery_of": "2026-09-17_mvcnet_coc_lab10_r7-full-w1",
        "round_id": "mvcnet-cross-objective-collision-screen-lab10-r8",
        "run_prefix": "2026-09-17_mvcnet_coc_lab10_r8",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-19T07:44:32.295734+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-19T07:44:34.672438+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T07:45:01.856963+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 24.91859006881714,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": false,
                "wall_seconds": 24.91859006881714
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T08:15:02.197883+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 1336.66539645195,
                "queue_seconds": 488.6252529621124,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": false,
                "wall_seconds": 1825.2906494140625
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T10:49:07.612905+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 2896.700206756592,
                "queue_seconds": 8172.53889298439,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": true,
                "wall_seconds": 11069.239099740982
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T14:14:43.618841+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 3067.3624591827393,
                "queue_seconds": 20338.647734880447,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": true,
                "wall_seconds": 23406.010194063187
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T15:44:52.499988+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 3604.545350790024,
                "queue_seconds": 25210.469210863113,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": true,
                "wall_seconds": 28815.014561653137
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T16:51:23.053758+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 4864.8332986831665,
                "queue_seconds": 25542.590287685394,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": false,
                "wall_seconds": 30407.42358636856
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T17:45:54.269884+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
                "execution_seconds": 4864.8332986831665,
                "queue_seconds": 25542.590287685394,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
                "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
                "waiting_for_resources": false,
                "wall_seconds": 30407.42358636856
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-19T17:58:16.976417+00:00",
            "result": {
              "artifact_manifest_sha256": "09361ad755c752f77b130b07c0f9fb8c9cc495eed88b62939b44dabd9116e995",
              "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
              "verified": true
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-19T17:59:21.790968+00:00",
            "result": {
              "artifact_manifest_sha256": "09361ad755c752f77b130b07c0f9fb8c9cc495eed88b62939b44dabd9116e995",
              "contract_sha256": "5814414916aed7d1066bcd30affb974494de5a78af788da0f70e08dafb564b2a",
              "run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
              "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r8",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "aggregate": {
          "C0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -0.8584104938271605,
              1.707175925925926
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": true,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              0.4231770833333333,
              0.5750868055555556,
              0.7703993055555556,
              0.4123263888888889,
              0.3146701388888889,
              0.5099826388888888,
              0.14105902777777773,
              0.8138020833333334,
              0.20616319444444442
            ],
            "mean_accuracy_gain_pp": 0.46296296296296297,
            "mean_ce_gain": 0.011149484206088764,
            "seed_accuracy_gains_pp": [
              0.9645061728395061,
              -0.03858024691358023
            ],
            "subject_accuracy_gains_pp": [
              0.78125,
              -0.43402777777777773,
              -1.996527777777778,
              0.8680555555555556,
              1.6493055555555554,
              0.08680555555555547,
              3.0381944444444446,
              -2.34375,
              2.517361111111111
            ]
          },
          "N0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.4564043209876543,
              0.5883487654320987
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.4448784722222222,
              -0.6510416666666666,
              -0.4774305555555555,
              -0.4774305555555555,
              -0.010850694444444461,
              -0.3797743055555555,
              -0.2712673611111111,
              -0.43402777777777773,
              -0.23871527777777773
            ],
            "mean_accuracy_gain_pp": -0.3761574074074074,
            "mean_ce_gain": -0.015178489716008757,
            "seed_accuracy_gains_pp": [
              -1.2924382716049383,
              0.5401234567901234
            ],
            "subject_accuracy_gains_pp": [
              0.1736111111111111,
              1.8229166666666665,
              0.4340277777777778,
              0.4340277777777777,
              -3.2986111111111107,
              -0.3472222222222222,
              -1.2152777777777777,
              0.08680555555555552,
              -1.4756944444444444
            ]
          },
          "N0-S0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.0321421682098766,
              1.089891975308642
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "descriptive",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.021701388888888964,
              -0.07595486111111117,
              0.29296874999999994,
              -0.06510416666666673,
              0.3038194444444444,
              0.13020833333333326,
              -0.13020833333333343,
              0.3797743055555555,
              -0.032552083333333384
            ],
            "mean_accuracy_gain_pp": 0.0868055555555555,
            "mean_ce_gain": -0.004029005509919994,
            "seed_accuracy_gains_pp": [
              -0.32793209876543217,
              0.5015432098765432
            ],
            "subject_accuracy_gains_pp": [
              0.9548611111111112,
              1.3888888888888888,
              -1.5625,
              1.3020833333333333,
              -1.6493055555555558,
              -0.26041666666666663,
              1.8229166666666667,
              -2.2569444444444446,
              1.0416666666666665
            ]
          },
          "P0-C0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.9483024691358024,
              1.7169415509259331
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_passed": false,
            "harm_below_minus5pp_subjects": 0,
            "loo_accuracy_gains_pp": [
              -0.05425347222222221,
              -0.04340277777777776,
              -0.7161458333333334,
              -0.35807291666666663,
              0.22786458333333337,
              -0.4991319444444444,
              0.18446180555555558,
              -0.4448784722222222,
              0.054253472222222265
            ],
            "mean_accuracy_gain_pp": -0.18325617283950615,
            "mean_ce_gain": -0.04262437858586407,
            "seed_accuracy_gains_pp": [
              0.17361111111111108,
              -0.5401234567901234
            ],
            "subject_accuracy_gains_pp": [
              -1.2152777777777777,
              -1.3020833333333333,
              4.079861111111112,
              1.2152777777777777,
              -3.4722222222222223,
              2.34375,
              -3.125,
              1.909722222222222,
              -2.0833333333333335
            ]
          },
          "P0-N0": {
            "bootstrap_accuracy_gain_pp_ci": [
              -1.3213734567901234,
              1.7746913580246912
            ],
            "bootstrap_replicates": 20000,
            "bootstrap_seed": 20260920,
            "ce_gain_nonnegative": false,
            "ci_level": 97.5,
            "direction": "none",
            "gates_pas
```
