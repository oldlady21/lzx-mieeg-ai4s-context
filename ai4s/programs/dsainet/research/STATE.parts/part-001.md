# State 阅读分段 1

完整脱敏文件：`ai4s/programs/dsainet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`1f0d9357fbcff9406eb24e153a516868f12970335d8e748c39b3ff11220c1289`。UTF-8 字节范围：[0, 500000) / 952349。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
{
  "active_local_experiment": null,
  "active_operation": null,
  "active_research": "ds07-r1",
  "active_round": "ds07-r1-science1-readerfix1",
  "active_run": {
    "bundle_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1",
    "dispatch_status": "REMOTE_ACCEPTED",
    "estimated_training_hours": 39.0,
    "execution_mode": "user_managed",
    "executor_id": "lab10",
    "planned_units": 2,
    "recorded_at": "2026-11-02T13:45:45.558543+00:00",
    "round_id": "ds07-r1-science1-readerfix1",
    "run_prefix": "2026-11-02_dsainet_ds07_r1_science1-readerfix1",
    "transaction_operations": [
      {
        "operation": "upload",
        "recorded_at": "2026-11-02T13:47:08.648857+00:00",
        "result": {
          "action": "UPLOADED",
          "monitor_powershell": "[REDACTED_MACHINE]",
          "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1"
        }
      },
      {
        "operation": "launch",
        "recorded_at": "2026-11-02T13:48:29.044661+00:00",
        "result": {
          "action": "SUBMISSION_SENT_NOT_VERIFIED",
          "monitor_powershell": "[REDACTED_MACHINE]",
          "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1"
        }
      },
      {
        "operation": "probe",
        "recorded_at": "2026-11-02T13:48:45.189302+00:00",
        "result": {
          "action": "WAIT_FOR_RESOURCES",
          "node_id": "technical_reuse",
          "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
          "status": "RUNNING",
          "timing": {
            "contract_sha256": "d82104284d7dadd6a47831998c32727a97bca76aff0236c224fd56bfad02f243",
            "execution_seconds": 4.447636604309082,
            "queue_seconds": 9.206525564193726,
            "queue_time_policy": "exclude_resource_wait",
            "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
            "transaction_id": "dsainet-ds07-r1-science1-readerfix1",
            "waiting_for_resources": true,
            "wall_seconds": 13.654162168502808
          }
        }
      },
      {
        "operation": "probe",
        "recorded_at": "2026-11-02T13:51:27.710314+00:00",
        "result": {
          "action": "WAIT_FOR_RESOURCES",
          "node_id": "technical_reuse",
          "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
          "status": "RUNNING",
          "timing": {
            "contract_sha256": "d82104284d7dadd6a47831998c32727a97bca76aff0236c224fd56bfad02f243",
            "execution_seconds": 4.974616765975952,
            "queue_seconds": 171.19521069526672,
            "queue_time_policy": "exclude_resource_wait",
            "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
            "transaction_id": "dsainet-ds07-r1-science1-readerfix1",
            "waiting_for_resources": true,
            "wall_seconds": 176.16982746124268
          }
        }
      },
      {
        "operation": "probe",
        "recorded_at": "2026-11-02T15:46:48.540867+00:00",
        "result": {
          "action": "RECONCILE_SAME_NODE",
          "node_id": "technical_reuse",
          "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
          "status": "FAILED",
          "timing": {
            "contract_sha256": "d82104284d7dadd6a47831998c32727a97bca76aff0236c224fd56bfad02f243",
            "execution_seconds": 200.95534825325012,
            "queue_seconds": 5744.736851215363,
            "queue_time_policy": "exclude_resource_wait",
            "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
            "transaction_id": "dsainet-ds07-r1-science1-readerfix1",
            "waiting_for_resources": false,
            "wall_seconds": 5945.692199468613
          }
        }
      }
    ]
  },
  "archived_campaigns": [
    {
      "campaign_id": "pre-campaign-c1-exploration",
      "closed_at": "2026-08-29T18:05:16.406976+00:00",
      "closing_decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r03-c1-vs-native-stability-v0.1"
      },
      "closing_round": "dsainet-r03-c1-vs-native-stability-v0.1",
      "closing_run": {
        "bundle_id": "2026-08-29_dsainet_ai4s_c1_native_stability_r3",
        "estimated_training_hours": 1.759,
        "planned_units": 36,
        "recorded_at": "2026-08-29T15:04:02.464667+00:00",
        "round_id": "dsainet-r03-c1-vs-native-stability-v0.1",
        "run_prefix": "2026-08-29_dsainet_ai4s_c1_native_stability_r3"
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized four boundary-guided DSAINet AI4S rounds, recording decisions and continuing after any verified positive signal."
    },
    {
      "campaign_id": "dsainet-ai4s-boundary-guided-v2-2026-08-30",
      "closed_at": "2026-08-31T09:06:13.841375+00:00",
      "closing_decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r04-branch2-temporal-reversal-v0.1"
      },
      "closing_round": "dsainet-r04-branch2-temporal-reversal-v0.1",
      "closing_run": {
        "intake_path": "results/logs/remote/2026-08-30_dsainet_ai4s_branch2_temporal_reversal_r4-full-w1",
        "run_id": "2026-08-30_dsainet_ai4s_branch2_temporal_reversal_r4-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-08-30T04:49:12.0383999+00:00"
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized a continuous three-round DSAINet AI4S campaign after freezing O1/T1 topology permutations; record and continue through all verified rounds."
    },
    {
      "campaign_id": "dsainet-ai4s-spatial-anchor-v1-2026-08-31",
      "closed_at": "2026-09-05T16:59:45.851703+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r03-role-specific-token-pooling-v0.1"
      },
      "closing_round": "dsainet-r03-role-specific-token-pooling-v0.1",
      "closing_run": {
        "intake_path": "results/logs/remote/2026-09-05_dsainet_ai4s_role_specific_token_pooling_r3r4-full-w1",
        "run_id": "2026-09-05_dsainet_ai4s_role_specific_token_pooling_r3r4-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-05T09:32:36.1918431+00:00"
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized R03 independent seed confirmation as round one and autonomous evidence-driven later research, uploads and experiments within 10 hours; scope and original authorization: ai4s/programs/dsainet/research/role-pooling-confirmation-20260906/AUTHORIZATION.md. Conservative cap: 3 decision rounds; no exact-route rescue."
    },
    {
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "closed_at": "2026-09-07T03:14:52.821569+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r07-tapl-v0.1"
      },
      "closing_round": "dsainet-r07-tapl-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "8ac33c86128e8fc39ac7acf5e9c078ca0052cec71f40cbb9424a4d923733aaa2",
        "contract_sha256": "7b1c420c28ff04937cf81127ed19f3c51b0cbc67ed259df7f2205cf90ca837bf",
        "intake_path": "results/logs/remote/2026-09-07_dsainet_tapl_v0_1-full-w1",
        "run_id": "2026-09-07_dsainet_tapl_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-07_dsainet_tapl_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized upload and run of prepared Token Attention Utility Decomposition. One DIAGNOSE_ONCE round, 2h. Record: ai4s/programs/dsainet/research/tapl-attribution/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-taud-v1-2026-09-07",
      "closed_at": "2026-09-07T06:03:32.873737+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r01-taud-v0.1-r2"
      },
      "closing_round": "dsainet-r01-taud-v0.1-r2",
      "closing_run": {
        "artifact_manifest_sha256": "759f598aab894011a676e46562348c350fe0f3d7a05c41e23e531da27e83174c",
        "contract_sha256": "919baf33009df86ecf302378925f0f72e30a85c7aef62a303f316162b8e32303",
        "intake_path": "results/logs/remote/2026-09-07_dsainet_taud_v0_2-full-w1",
        "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-07_dsainet_taud_v0_2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized upload and run of prepared Source-estimated Frozen Template Audit v0.1. One DIAGNOSE_ONCE round, 2h. Record: ai4s/programs/dsainet/research/source-template-audit/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-sfta-v1-2026-09-07",
      "closed_at": "2026-09-07T07:57:34.345049+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r01-sfta-v0.1"
      },
      "closing_round": "dsainet-r01-sfta-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "dfe22019959d9fa9e8222801bb78bc2c1eaec093598c675f770733ffe3160deb",
        "contract_sha256": "2bb09ce1da93fc9d82a1fd55daa0d55aa443c2c76e51c295d9b36f5b555d22ca",
        "intake_path": "results/logs/remote/2026-09-07_dsainet_sfta_v0_1-full-w1",
        "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-07_dsainet_sfta_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized execution of Train-time Position Prior campaign design. SCREEN_NEW R1 only, 6h, ccmu GPU0. Record: ai4s/programs/dsainet/research/train-time-position-prior/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-ttpp-v1-2026-09-07",
      "closed_at": "2026-09-08T08:02:48.076204+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-ttpp-lab10-remaining-v0.2"
      },
      "closing_round": "dsainet-r01-ttpp-lab10-remaining-v0.2",
      "closing_run": {
        "artifact_manifest_sha256": "18330aea12e44c08f52b575c5b25ac7347840a6bf45b3616aae20bbf13c90521",
        "contract_sha256": "1ee0af4cc7d3a664b47f8100d0ce0d7b896eccd39668385076b9240f8b3da3d8",
        "intake_path": "results/logs/remote/2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
        "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized RORA-v0.1 on Lab10: 36 frozen D/U checkpoints and 72 fixed source-only probes; no backbone training; one diagnostic round only."
    },
    {
      "campaign_id": "dsainet-rora-v1-2026-09-08",
      "closed_at": "2026-09-08T10:13:29.146929+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-rora-v0.1"
      },
      "closing_round": "dsainet-r01-rora-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "ac5c5be0c7ab184a1b0ce8d593d9583b543888f360f7d5e5c227e4743428cdb6",
        "contract_sha256": "f890aec8bb4285880b8c720ccc123c61073b4575cb7b084f476bd5a6bf8dc09d",
        "intake_path": "results/logs/remote/2026-09-08_dsainet_rora_v0_1-full-w1",
        "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-08_dsainet_rora_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requested AAST-v0.1 design and Lab10 experiment dispatch. One new three-arm screen, 54 matched trainings, Program default 10-hour budget; preserve closed readout routes."
    },
    {
      "campaign_id": "dsainet-aast-v1-2026-09-08",
      "closed_at": "2026-09-08T14:56:04.473618+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-aast-v0.1"
      },
      "closing_round": "dsainet-r01-aast-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "c778b3a35b00349ea93451939aef5ec410e1475de11d274f9f28efc8faf1a045",
        "contract_sha256": "50ea4c918e79c764be0f8872e93bd2ef400bd535cec99e324dd9d470008bfd4d",
        "intake_path": "results/logs/remote/2026-09-08_dsainet_aast_v0_1-full-w1",
        "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-08_dsainet_aast_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests the next LVT-v0.1 research round in the existing Lab10 experiment workflow. One fresh three-arm 54-training SCREEN_NEW; 10-hour Program default budget; close AAST without filter rescue and preserve all readout/inter boundaries."
    },
    {
      "campaign_id": "dsainet-lvt-v1-2026-09-08",
      "closed_at": "2026-09-08T20:02:51.578735+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-lvt-v0.1"
      },
      "closing_round": "dsainet-r01-lvt-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "bd5bca1683efeaad4fb3a6eef9b71d3fe64b9596f3fda7aba3e38982717db7f7",
        "contract_sha256": "0443e9c9fc34bdf0c4db29df79dfe5522a1bfbf9155a04f591d218055e7fa1be",
        "intake_path": "results/logs/remote/2026-09-08_dsainet_lvt_v0_1-full-w1",
        "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-08_dsainet_lvt_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested independent NCA source-only frozen B0 normalization audit; no training or target evaluation; one DIAGNOSE_ONCE on Lab10"
    },
    {
      "campaign_id": "dsainet-nca-v1-2026-09-09",
      "closed_at": "2026-09-09T04:28:10.680113+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-nca-v0.1"
      },
      "closing_round": "dsainet-r01-nca-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "c5bb0ba452fd2a202aef55e6f5d2692e3e7f46a5b22e5af63a8234143aeb4a21",
        "contract_sha256": "410df6776c854f5063fe4702d3d2c804cd7fe45e469d70a6c427e671403ca0bb",
        "intake_path": "results/logs/remote/2026-09-09_dsainet_nca_v0_1-full-w1",
        "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-09_dsainet_nca_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested SDSA shared-trajectory source-disjoint selection audit, 36 fresh native trainings and 108 sealed final evaluations on Lab10; new independent profile and one round"
    },
    {
      "campaign_id": "dsainet-sdsa-v1-2026-09-09",
      "closed_at": "2026-09-09T07:04:44.679191+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-sdsa-v0.1-repair1"
      },
      "closing_round": "dsainet-r01-sdsa-v0.1-repair1",
      "closing_run": {
        "artifact_manifest_sha256": "b0bc854e8da0e8d8a32607698f44c2299187d95ad5a45c2641f4f4d9e8a9436b",
        "contract_sha256": "8da772dbabc1711c551479370dddf24bd6a599b3b828a680dec43468b23827dd",
        "intake_path": "results/logs/remote/2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
        "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests next SCSR research: one native architecture augmentation source-consistency screen on Lab10, 54 fresh trajectories, matched pseudo-group control, no SDSA or prior candidate rescue; bounded implementation/transport repair only."
    },
    {
      "campaign_id": "dsainet-scsr-v1-2026-09-09",
      "closed_at": "2026-09-09T10:14:07.791647+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-scsr-v0.1"
      },
      "closing_round": "dsainet-r01-scsr-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "0e0463f9a831d0a6b68435e73e027dae6e0d6d509f6759e09acb0528308bffa9",
        "contract_sha256": "ac123dba3711984e2bb437887ce9139f8ae4a81fa16b9c0137f7e9a255f17a71",
        "intake_path": "results/logs/remote/2026-09-09_dsainet_scsr_v0_1-full-w1",
        "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-09_dsainet_scsr_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests next CGX research round within authorized Lab10 workflow; exact SCSR boundary remains closed."
    },
    {
      "campaign_id": "dsainet-cgx-v1-2026-09-09",
      "closed_at": "2026-09-09T13:35:08.395640+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-cgx-v0.1"
      },
      "closing_round": "dsainet-r01-cgx-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "c18e72ec0fdcb1c6e920a614187b25135710f93e4446cc65585e42167f573334",
        "contract_sha256": "a1f0eecb2d031cf4d290a6cf6449a480a763b33d95350ed732695e35e7a2a7ec",
        "intake_path": "results/logs/remote/2026-09-09_dsainet_cgx_v0_1-full-w1",
        "run_id": "2026-09-09_dsainet_cgx_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-09_dsainet_cgx_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests PECI next round in authorized Lab10 workflow; CGX exact boundary closed."
    },
    {
      "campaign_id": "dsainet-peci-v1-2026-09-09",
      "closed_at": "2026-09-09T19:04:15.519012+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-peci-v0.1"
      },
      "closing_round": "dsainet-r01-peci-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "d1056940f7bf26a2e7a512d2e5f288cd252d561c148e66bf79360c6d8bf8d776",
        "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
        "intake_path": "results/logs/remote/2026-09-09_dsainet_peci_v0_1-full-w1",
        "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested SBA-v0.1 native-versus-balanced scale-budget audit; one paired Lab10 training round, no automatic successor."
    },
    {
      "campaign_id": "dsainet-sba-v1-2026-09-10",
      "closed_at": "2026-09-10T05:13:30.743150+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-sba-v0.1"
      },
      "closing_round": "dsainet-r01-sba-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "20912219573d210d96c8737114b23aedc179922e79db098e4a1bef7716bbb8eb",
        "contract_sha256": "bdfecbb8c879cbe15fbd6a9f363cd15a3f2dbe31aed71abda3dceed726d679b2",
        "intake_path": "results/logs/remote/2026-09-10_dsainet_sba_v0_1-full-w1",
        "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-10_dsainet_sba_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User selected CTOA cross-spectrum-preserving input organization audit and confirmed transformation after native augmentation; one Lab10 paired training round."
    },
    {
      "campaign_id": "dsainet-ctoa-v1-2026-09-10",
      "closed_at": "2026-09-10T13:43:12.949910+00:00",
      "closing_decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r01-ctoa-v0.1"
      },
      "closing_round": "dsainet-r01-ctoa-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "7dccb99b8ae5411c5ef4bd324d4f58877b23ebff062794e031e3521ade3487f7",
        "contract_sha256": "09bdd86c0ab6904a329a493e2c0b95aa5fd46753c91df32256b09b08953c6e39",
        "intake_path": "results/logs/remote/2026-09-10_dsainet_ctoa_v0_1-full-w1",
        "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-10_dsainet_ctoa_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User selected WOSA origin-shift audit after verified CTOA positive; one J training condition, reuse CTOA R/S, existing Lab10 environment, no automatic successor."
    },
    {
      "campaign_id": "dsainet-wosa-v1-2026-09-10",
      "closed_at": "2026-09-11T10:39:17.838560+00:00",
      "closing_decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r01-wosa-v0.1"
      },
      "closing_round": "dsainet-r01-wosa-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "212cde4ae3c283833b25be24217b8a65ddb5193d88ea12be4a6d9ed3aa9d7ea8",
        "contract_sha256": "d2c3eb518cfd8708483c2ce1683949c786908a2b9eaaff926c3f2a82804164ce",
        "intake_path": "results/logs/remote/2026-09-10_dsainet_wosa_v0_1-full-w1",
        "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-10_dsainet_wosa_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User explicitly authorized starting the reviewed 54-training spatial nonlinearity audit on Lab10; stop after one verified scientific decision."
    },
    {
      "campaign_id": "dsainet-sna-v1-2026-09-11",
      "closed_at": "2026-09-13T03:21:21.223857+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-sna-v0.1-repair2"
      },
      "closing_round": "dsainet-r01-sna-v0.1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "e8d31e0c1e8345d08912df91df7e08224a07cf31b5dfe9fed4351168626cd597",
        "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
        "intake_path": "results/logs/remote/2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
        "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户授权下一轮 TKS 研究自动上传启动；SNA已独立审阅并NO_SIGNAL关闭。单次54项原始输入结构筛选，不启动OpenBMI或追加变体。"
    },
    {
      "campaign_id": "dsainet-tks-v1-2026-09-13",
      "closed_at": "2026-09-14T07:27:01.548350+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-tks-v0.1"
      },
      "closing_round": "dsainet-r01-tks-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "46ba0b77f09303853c8416edf962eede679420693c75857cf00f8ee0ed49b810",
        "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
        "intake_path": "results/logs/remote/2026-09-13_dsainet_tks_v0_1-full-w1",
        "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户2026-09-14明确授权Grok审查后自动推进TCUA实现验收上传启动，并自行增加任务预算；TKS已NO_SIGNAL关闭。TCUA单轮18原生训练72探针，72小时含工程与收尾，纯资源等待扣除，不救援、不OpenBMI。授权记录ai4s/programs/dsainet/research/TCUA_AUTHORIZATION_2026-09-14.md"
    },
    {
      "campaign_id": "dsainet-tcua-v1-2026-09-14",
      "closed_at": "2026-09-14T15:41:57.168287+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-tcua-v0.1"
      },
      "closing_round": "dsainet-r01-tcua-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "32ba0651abad6f46895407aa05012f5d4347adec89de2bcd9d38865a08092a64",
        "contract_sha256": "0e01355a6990467b293e9cc3b0ac546a88eda3300c23791dbb37bf737d85ac0e",
        "intake_path": "results/logs/remote/2026-09-14_dsainet_tcua_v0_1-full-w1",
        "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-14_dsainet_tcua_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized GSF preparation upload and launch on Lab10; one frozen screen only."
    },
    {
      "campaign_id": "dsainet-gsf-v1-2026-09-14",
      "closed_at": "2026-09-15T13:36:53.649631+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-gsf-v0.1-repair2"
      },
      "closing_round": "dsainet-r01-gsf-v0.1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "87e720539edb38dae66b734dad5ba82247b269b24868771fa0bda793f590b720",
        "contract_sha256": "b26777ae1d1f00e4065c04839b7e8fc774cd943e2ddf4b59dfbd8e36a22708bd",
        "intake_path": "results/logs/remote/2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
        "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-15_dsainet_gsf_v0_1_repair2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized CMCR one 90-fit screen plus five source-only technical fits, Lab10 upload/launch/probe/fetch/intake, 24 actual hours excluding pure resource wait, one engineering repair preparation and zero automatic training retries; ai4s/programs/dsainet/research/cmcr-v0.1/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-cmcr-v0.1-2026-09-15",
      "closed_at": "2026-09-19T13:46:28.352780+00:00",
      "closing_decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r01-cmcr-v0.1-recovery5"
      },
      "closing_round": "dsainet-r01-cmcr-v0.1-recovery5",
      "closing_run": {
        "artifact_manifest_sha256": "d2c09e44c7cb51121eb66184d3dd0cdcb9a9a1444506d75debaaeff3f45da2ac",
        "contract_sha256": "8df3b225e96f5f4f758d4a3589251207adaf76da657688ac1bcb69af0c4d1b3c",
        "intake_path": "results/logs/remote/2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
        "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized DS-01 bounded source-audit campaign: 4 technical fits plus 54 formal fits on Lab10; one engineering repair preparation and zero automatic training retries; stop after one source decision."
    },
    {
      "campaign_id": "dsainet-ds01-v0.1-20260919",
      "closed_at": "2026-09-20T18:20:44.711175+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsa-ds01-v0.1-repair5"
      },
      "closing_round": "dsa-ds01-v0.1-repair5",
      "closing_run": {
        "artifact_manifest_sha256": "ab9e64f2e205aaee4a32836596af3ff278b20f3077745f3bd2758b8b5c34bd83",
        "contract_sha256": "51578ec200bd5fdc120032f523c49b815465be23fd2a600fa6e28edd57008e85",
        "intake_path": "results/logs/remote/2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1",
        "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User 2026-09-21 explicitly authorizes next evidence-grounded research, added budget and launch; PCR v0.2 new full-state source-only attribution; 19 tasks/76 fits, no target or automatic retries; DS01 remains closed."
    },
    {
      "campaign_id": "dsainet-pcr-v0.2-20260921",
      "closed_at": "2026-09-21T11:46:25.677351+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsa-pcr-v0.2-capacity1"
      },
      "closing_round": "dsa-pcr-v0.2-capacity1",
      "closing_run": {
        "artifact_manifest_sha256": "940e84cfc7ace315eaa1555277fa2f45775de5189a79712c5c3fa6731e4fd67e",
        "contract_sha256": "8899c7ab9258e0a5d951a2c7f271557a5b0ce78a841372eee2f16c2b9e407aca",
        "intake_path": "results/logs/remote/2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
        "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User stopped attribution branch and requested new KShape research; persistent automatic budget and launch authorization; 5 technical fits plus 90 fresh 100-epoch fits, global source-audit barrier, no target/probe, one wiring/transport repair preparation, zero automatic training retry."
    },
    {
      "campaign_id": "dsainet-kshape-v0.1-20260921",
      "closed_at": "2026-09-22T09:23:16.429862+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "leave_one_out_role": "descriptive_only",
        "reason": "at least one necessary frozen structural-utility gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-kshape-v0.1-repair5"
      },
      "closing_round": "dsa-kshape-v0.1-repair5",
      "closing_run": {
        "artifact_manifest_sha256": "823146ee33be8190a80a4de07574269957aa428498d2b57ab43cee7a7d4e8eb6",
        "contract_sha256": "bbdff55c974acd51e65938eba4589d13d0a704530a5e2de28ad9f5cd4c208a9d",
        "intake_path": "results/logs/remote/2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
        "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-22_dsainet_kshape_v0_1-repair5-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested next research and maintains automatic budget and launch authorization. Independent PMT source-only structural screen, 5 single-epoch technical fits plus 90 fresh 100-epoch fits and global-barrier audits, one wiring/transport repair preparation, zero automatic training retries; no target/probe, stop after one decision. See ai4s/programs/dsainet/research/dsa-pmt-v0.1/AUTHORIZATION.md."
    },
    {
      "campaign_id": "dsainet-pmt-v0.1-20260922",
      "closed_at": "2026-09-23T10:34:03.240445+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "leave_one_out_role": "descriptive_only",
        "reason": "at least one necessary frozen structural-utility gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-pmt-v0.1"
      },
      "closing_round": "dsa-pmt-v0.1",
      "closing_run": {
        "artifact_manifest_sha256": "8a0e589832bf0fc542f3c82dcc330a40a2b751d5c4d44fb69c5bb5ba96dc6493",
        "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
        "intake_path": "results/logs/remote/2026-09-22_dsainet_pmt_v0_1-full-w1",
        "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requested launch after AEC plan delivery. Lab10 12h excluding pure resource wait, 72 frozen checkpoints, 864 fixed linear fits, 288 native tail replays, zero DSAINet training, one wiring/transport repair preparation, zero automatic fit retries; stop after one diagnostic decision. ai4s/programs/dsainet/research/dsa-aec-v0.1/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-aec-v0.1-20260923",
      "closed_at": "2026-09-23T18:02:21.701056+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "DIAGNOSTIC_SUPPORT",
        "native_complementarity_use": "not_identified",
        "original_PMT_decision": "NO_SIGNAL",
        "reason": "Frozen G1/G2, harm and null gates; G3 mismatch sensitivity is descriptive only.",
        "round_id": "dsa-aec-v0.1-repair1"
      },
      "closing_round": "dsa-aec-v0.1-repair1",
      "closing_run": {
        "artifact_manifest_sha256": "7ebf33f164910becff0d015122629e7d3cc2cb71b3b568080df17971ae11d0d2",
        "contract_sha256": "b52f4539273532e60293780fea8078c105541df022dd0ce5d56ecf030b8ed240",
        "intake_path": "results/logs/remote/2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
        "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-23_dsainet_aec_v0_1_repair1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User 2026-09-24 启动 approves FUT: 3 one-epoch technical tail fits then 432 fixed 30-epoch tail fits; zero encoder training; shared capacity; one wiring repair preparation; no fit retry; stop after one source-only diagnosis. Authorization ai4s/programs/dsainet/research/dsa-fut-v0.1/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-fut-v0.1-20260924",
      "closed_at": "2026-09-25T04:42:22.458311+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "native_tail_use": "not_identified",
        "original_PMT_decision": "NO_SIGNAL",
        "reason": "FUT G1/G2, harm and null gates under the frozen representation-tail protocol.",
        "round_id": "dsa-fut-v0.1-repair5"
      },
      "closing_round": "dsa-fut-v0.1-repair5",
      "closing_run": {
        "artifact_manifest_sha256": "5ec5bdeba4e9bad8dc3dc0bd218f4dbb5943b33e50b8b133378f6621d4d55592",
        "contract_sha256": "adcf3d2865f994d278ae8b43b51a64bf93b19bf5606684c9fc7ebcaa86824535",
        "intake_path": "results/logs/remote/2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
        "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair5-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests v3 automatic next research and retains automatic budget/start authority; bounded AEL scope in ai4s/programs/dsainet/research/dsa-ael-v0.1/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dsainet-ael-v0.1-20260925",
      "closed_at": "2026-09-25T15:41:09.962182+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "C0-B0",
          "C0-S0",
          "C0-N0"
        ],
        "incomplete_reason": null,
        "leave_one_out_role": "required_gate_and_report",
        "namespace": "ael",
        "negative_objects_stopped": {
          "C0-B0": "stopped_negative_gate",
          "C0-N0": "stopped_negative_gate",
          "C0-S0": "stopped_negative_gate"
        },
        "reason": "H1 necessary gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-ael-v0.1-repair2"
      },
      "closing_round": "dsa-ael-v0.1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "98800ee77d9290b02396ee6e94ed816a13008dfad775cf72c4891149bdf820a1",
        "contract_sha256": "de788fc7475ddffe13ffc4f3e743f350f686d6bed23ff45fe0bcf59bfffa56b4",
        "intake_path": "results/logs/remote/2026-09-25_dsainet_ael_v0_1_repair2-full-w1",
        "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-25_dsainet_ael_v0_1_repair2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "Current user requests next research; standing automatic budget/start authority bound in ai4s/programs/dsainet/research/dsa-bsu-v0.1/AUTHORIZATION.md; constituent deletion72newfits only"
    },
    {
      "campaign_id": "dsainet-bsu-v0.1-20260925",
      "closed_at": "2026-09-27T08:58:52.913644+00:00",
      "closing_decision": {
        "capacity_caveat": true,
        "claim_status": "no_paper_claim",
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "leave_one_out_role": "primary_required_gate",
        "namespace": "bsu",
        "reason": "both constituent-retention gates required; secondary descriptive only",
        "research_qualification": "INSUFFICIENT_DUAL_RETENTION_SUPPORT",
        "round_id": "dsa-bsu-v0.1-repair3"
      },
      "closing_round": "dsa-bsu-v0.1-repair3",
      "closing_run": {
        "artifact_manifest_sha256": "24b839c72149c48e879cc48f4a5ab1d3138fa52f0f75a8cfb1ba3a67174ae5fb",
        "contract_sha256": "91d73e6fa7bd01b64af1ea72ff67ae70d2aaef6370077e90dd122befe8b43016",
        "intake_path": "results/logs/remote/2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
        "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-27_dsainet_bsu_v0_1_repair3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requested CES launch; standing automatic budget authorization; 2 smoke plus 36 fits plus 36 audits, no target or P0 training"
    },
    {
      "campaign_id": "dsainet-ces-v0.1-20260927",
      "closed_at": "2026-09-28T11:17:40.955109+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "failed_comparisons": [
          "G_C",
          "I"
        ],
        "interpretation_boundary": "architecture-conditional, exposed-source diagnostic screen",
        "leave_one_out_role": "required_gate_and_report",
        "namespace": "ces",
        "negative_objects_stopped": {
          "G_C": "stopped_negative_gate",
          "I": "stopped_negative_gate"
        },
        "reason": "one or more necessary CES diagnostic gates failed",
        "research_qualification": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "round_id": "dsa-ces-v0.1-repair3"
      },
      "closing_round": "dsa-ces-v0.1-repair3",
      "closing_run": {
        "artifact_manifest_sha256": "80db8802967e0b1dc2f28ffe2082cd3f5860cc89d04a22feaddd104a4559b499",
        "contract_sha256": "212546ccd97a37119e1767a12aed09bb5ba24429bd5d112608319e16b099725d",
        "intake_path": "results/logs/remote/2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
        "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-28_dsainet_ces_v0_1_repair3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly approved Lab10 24h, 2 technical fits, 54 new fits, 36 reused checkpoints, 90 target evaluations, 1 wiring/transport repair and 0 automatic fit retries; frozen P0 new-seed performance only."
    },
    {
      "campaign_id": "dsainet-pfc-v0.1-20260928",
      "closed_at": "2026-09-28T17:04:54.207331+00:00",
      "closing_decision": {
        "decision": "EVALUATION_COMPLETE",
        "evaluation_plan": {
          "path": "ai4s/programs/dsainet/research/dsa-pfc-v0.1/EVALUATION_PLAN.yaml",
          "scope_id": "bnci001-p0-b0-five-seed-frozen-replication",
          "sha256": "1e3d821c970a1f836c3f0d6eeeb63e8e28fe876e5ac593ba73e4a3f9dfed6e22"
        },
        "reason": "Complete90 target evaluations,54 new fits,36 reused checkpoints; independent predictions and frozen summary verified. Performance gate is reported separately from completion.",
        "round_id": "dsa-pfc-v0.1-r1"
      },
      "closing_round": "dsa-pfc-v0.1-r1",
      "closing_run": {
        "artifact_manifest_sha256": "c8cb637502c03e8b79666e8e0f165de640b122eecb82638afeeec19ef62f2e5e",
        "contract_sha256": "284b8751b7ed17024ae706cc2dc02de0ba7ab096692da405351fbfb3dabdf8b9",
        "intake_path": "results/logs/remote/2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
        "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-28_dsainet_pfc_v0_1_r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User confirmed launch of unchanged P0/native B0 five-seed full LOSO on BNCI004 and all109 PhysioNet subjects: 4 technical fits,1180 formal100epoch fits,1180 fixed target evaluations;72 active hours excluding pure resource wait;1 wiring/transport repair;0 automatic fit retries;one joint analysis then stop."
    },
    {
      "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
      "closed_at": "2026-09-29T13:15:23.638658+00:00",
      "closing_decision": {
        "decision": "EVALUATION_COMPLETE",
        "evaluation_plan": {
          "path": "ai4s/programs/dsainet/research/dsa-pfc-v0.1/EVALUATION_PLAN.yaml",
          "scope_id": "bnci001-p0-b0-five-seed-frozen-replication",
          "sha256": "1e3d821c970a1f836c3f0d6eeeb63e8e28fe876e5ac593ba73e4a3f9dfed6e22"
        },
        "reason": "Complete90 target evaluations,54 new fits,36 reused checkpoints; independent predictions and frozen summary verified. Performance gate is reported separately from completion.",
        "round_id": "dsa-pfc-v0.1-r1"
      },
      "closing_round": "dsa-pfc-xds-v0.1-repair4-004",
      "closing_run": {
        "artifact_manifest_sha256": "980380a769bee64ba871c5e42c4311c3356676c35e68e5a2c1389d395f4e5a7a",
        "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
        "intake_path": "results/logs/remote/2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
        "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User authorized SID 24h90fits+126forward; PhysioNet explicitly parked unfinished; no prior budget transferred"
    },
    {
      "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
      "closed_at": "2026-10-09T17:54:23.881897+00:00",
      "closing_decision": {
        "decision": "EVALUATION_COMPLETE",
        "evaluation_plan": {
          "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair3/EVALUATION_PLAN_SPLIT.yaml",
          "scope_id": "physionet-all-subjects-five-seed-loso",
          "sha256": "f28af045ea76b1059713ecca3416386652d6ee1af2548d4b00d8c86de35634d1"
        },
        "reason": "Complete PhysioNet1090 target evaluations and545 paired cells; original-runtime frozen prediction replay passed.",
        "round_id": "dsa-pfc-xds-v0.1-physionet-target-resume16"
      },
      "closing_round": "dsa-pfc-xds-v0.1-physionet-target-resume16",
      "closing_run": {
        "artifact_manifest_sha256": "789da51665f075182966f5fa302ad5ed1ebd2165e2d9b50a933a30ce589ee358",
        "contract_sha256": "11552934fda76a12fb4c4aa281733914f6dd84de4b478ff4c19105f1461024ca",
        "intake_path": "results/logs/remote/2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16-full-w1",
        "run_id": "2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户2026-10-10授权新v3.1结构研究与设计后Lab10启动；保留旧P0及冻结关闭边界，仅运行已完成设计的一轮DSA-RNS source-only五臂筛查，90科学fits+5技术fits，不自动扩展。"
    },
    {
      "campaign_id": "dsainet-rns-v0.1-20261010",
      "closed_at": "2026-10-11T11:04:28.214944+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "P0-B0",
          "P0-S0",
          "P0-N0"
        ],
        "incomplete_reason": null,
        "leave_one_out_role": "descriptive_only",
        "namespace": "rns",
        "negative_objects_stopped": {
          "P0-B0": "stopped_negative_utility_gate",
          "P0-S0": "stopped_negative_utility_gate"
        },
        "reason": "native utility or risk gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-rns-v0.1-audit-resume2"
      },
      "closing_round": "dsa-rns-v0.1-audit-resume2",
      "closing_run": {
        "artifact_manifest_sha256": "f7bf368f6547f3c47593c41e6cf6d533dc8ce3a08854b7b3d309b8e7ac6fb7bd",
        "contract_sha256": "94e987737a5edf497afb693900f20b107d3da495af456ed7ee1ea843fffc0cfd",
        "intake_path": "results/logs/remote/2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
        "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User 2026-10-11 requests launch under new CRU deployment contract; one selected five-arm source-only screen, 90 fresh fits and 90 frozen audits plus five technical smokes. New bounded 24h deployment choice; old RNS state and accrued costs preserved in PREVIOUS_STATE and BUDGET_LINEAGE, no old budget transfer."
    },
    {
      "campaign_id": "dsainet-cru-v0.1-20261011",
      "closed_at": "2026-10-12T12:04:01.676668+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "P0-B0",
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "incomplete_reason": null,
        "leave_one_out_role": "descriptive_only",
        "namespace": "cru",
        "negative_objects_stopped": {
          "P0-B0": "stopped_negative_utility_gate"
        },
        "next_design": null,
        "reason": "native utility or subject risk gate failed",
        "research_qualification": "NO_SIGNAL",
        "risk_failed_comparisons": [],
        "round_id": "dsa-cru-v0.1-resume2",
        "stopped": true,
        "target_evaluation": false
      },
      "closing_round": "dsa-cru-v0.1-resume2",
      "closing_run": {
        "artifact_manifest_sha256": "bee25c53764d87c8234d9771f25c8489f680fce728a726a0ca85f22fa6f27798",
        "contract_sha256": "3d65adbe7cf3ec041667de1697643ad61e0db780ce5128fd99612efd606c2503",
        "intake_path": "results/logs/remote/2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
        "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-12_dsainet_cru_v0_1_resume2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User 2026-10-12 explicitly requests launching the reviewed RCD design. One four-arm source6-val1-audit1 screen, 72 fresh fits and 72 locked audits plus four technical fits and audits. Agent bounded execution ceiling 24h, smoke-based feasibility required before science. Preserve closed CRU Run and accrued budget, no old balance transfer, no future rounds."
    },
    {
      "campaign_id": "dsainet-rcd-v0.1-20261012",
      "closed_at": "2026-10-15T06:45:02.843120+00:00",
      "closing_decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "P0-B0",
          "P0-S0",
          "P0-N0"
        ],
        "namespace": "rcd",
        "next_run_automatic": false,
        "primary_comparison": "P0-B0",
        "research_qualification": "NO_SIGNAL",
        "risk_failed_subjects": [
          2,
          4,
          5,
          7
        ],
        "round_id": "dsa-rcd-v0.1-resume3",
        "stopped": true,
        "target_evaluation": false
      },
      "closing_round": "dsa-rcd-v0.1-resume3",
      "closing_run": {
        "artifact_manifest_sha256": "8538e3fc4a273cf307b19377a58e139f4dfcf978bf51823d82d2fe2e3dbd6d4a",
        "contract_sha256": "155e3f431195919625e8c652193190fccde90fbd188d47c15a7a38bb49f47950",
        "intake_path": "results/logs/remote/2026-10-14_dsainet_rcd_v0_1_resume3-full-w1",
        "run_id": "2026-10-14_dsainet_rcd_v0_1_resume3-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-14_dsainet_rcd_v0_1_resume3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized ORD Stage A only and new cumulative24h; keep RCD closed and Stage B unauthorized."
    },
    {
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "closed_at": "2026-10-17T12:18:16.646217+00:00",
      "closing_decision": {
        "decision": "NO_SIGNAL",
        "reason": "classified by frozen DSA-ORD Stage-A analyzer gates",
        "round_id": "dsa-ord-v0.1-stageA-repair6"
      },
      "closing_round": "dsa-ord-v0.1-stageA-repair6",
      "closing_run": {
        "artifact_manifest_sha256": "f80e8ec665f31be48f04ad783f128eda3811e68c94cf1ebd24f52b997c2dd939",
        "contract_sha256": "f717c81959be42ded8d6364a397bb7257694de99c232807767c6fbf4b501bcac",
        "intake_path": "results/logs/remote/2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
        "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized D-only 72 fresh fits and audits, 72h new cumulative budget; F1 F2 and old Stage B prohibited. Technical qualification and measured remaining-budget admission required."
    },
    {
      "campaign_id": "dsainet-nfi-v0.1-D-20261017",
      "closed_at": "2026-10-18T05:27:42.574457+00:00",
      "closing_decision": {
        "F_auto_start": false,
        "analysis_input_sha256": "95698d2f7448e3ddcc0ff034a1acc56e2313847328f2ce6ddabeb9f43bbc0f4e",
        "analysis_repair": {
          "manifest": "ai4s/programs/dsainet/research/dsa-nfi-v0.1/analysis_repair/MANIFEST.json",
          "scope": "completion-interface-only; frozen science and raw artifacts unchanged",
          "sha256": "85626b6ce4ba399c34d5e8efa2618904abcd7c1e56648195bde55526553c210d"
        },
        "automatic_follow_up": false,
        "decision": "NFI_D_DIAGNOSTIC_RECORDED",
        "ordered_d_disposition": {
          "F_auto_start": false,
          "classification": "D_ATTRIBUTION_UNRESOLVED_METRIC_OR_SEED_CONFLICT",
          "stop_after_D": true,
          "trigger": {
            "contrast": "q",
            "nll_conflict": false,
            "seed_reversal": true
          }
        },
        "role": "diagnostic_observation",
        "round_id": "dsa-nfi-v0.1-D",
        "stop_after_D": true
      },
      "closing_round": "dsa-nfi-v0.1-D",
      "closing_run": {
        "artifact_manifest_sha256": "930bfd3fee5e705ec1f4c30a8fcd1ba31fab75ce450e6b4efedb12bb36d152d6",
        "contract_sha256": "e54ff5968bb342e2a9dc623150c2655d666da1452e166996f622ee9ae2afb9e9",
        "intake_path": "results/logs/remote/2026-10-17_dsainet_nfi_v0_1_D-full-w1",
        "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-17_dsainet_nfi_v0_1_D-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized Q 90 fits and audits after 8 technical checks; new 48h cumulative from preparation 2026-10-18T04:50:00Z; preserve D; no later stages."
    },
    {
      "campaign_id": "dsainet-nfi-v0.2-Q-20261018",
      "closed_at": "2026-10-18T11:18:36.432049+00:00",
      "closing_decision": {
        "K_auto_start": false,
        "analysis_input_sha256": "aef044dca837ac6c7d6a4ecac189efbf9203edc21f62bc88b1ebf1b03c89af3e",
        "automatic_follow_up": false,
        "decision": "NFI_Q_DIAGNOSTIC_RECORDED",
        "q_disposition": {
          "continue_worth_verifying": [
            "Q2-Q1"
          ],
          "contrasts": {
            "Q1-Q0": "SMALL_OR_UNSTABLE",
            "Q2-Q1": "CONTINUE_WORTH_VERIFYING",
            "Q3-Q2": "SMALL_OR_UNSTABLE",
            "Q4-Q3": "SMALL_OR_UNSTABLE"
          },
          "diagnostic_only": true,
          "small_or_unstable": [
            "Q1-Q0",
            "Q3-Q2",
            "Q4-Q3"
          ]
        },
        "role": "diagnostic_observation",
        "round_id": "dsa-nfi-v0.2-Q",
        "stop_after_Q": true
      },
      "closing_round": "dsa-nfi-v0.2-Q",
      "closing_run": {
        "artifact_manifest_sha256": "ddcd06d75490132cdc1435d1e6686746a1c0889938547d325a91349178222a99",
        "contract_sha256": "e3796326eaad981c97c7a24b95f936849cc42fc3d729cba4f69642db3a43068b",
        "intake_path": "results/logs/remote/2026-10-18_dsainet_nfi_v0_2_Q-full-w1",
        "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-18_dsainet_nfi_v0_2_Q-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized LC1 only: six technical fits/audits,135 formal fits/audits,48h including preparation from2026-10-18T10:50:00Z;preserveQ;noLC2/F1/F2/B;measured budget admission."
    },
    {
      "campaign_id": "dsainet-lcb-v0.1-LC1-20261018",
      "closed_at": "2026-10-19T07:28:13.475507+00:00",
      "closing_decision": {
        "analysis_input_sha256": "2d2ac38afc3f615e160997d5eec8b7c6c060d58f9255a1bde893c6de12959d70",
        "automatic_follow_up": false,
        "decision": "LC1_SCREEN_RECORDED",
        "lc1_disposition": {
          "automatic_follow_up": false,
          "diagnostic_only": true,
          "exposure_pass": true,
          "functional_direction_consistent": false,
          "lc2_authorized": false,
          "lc2_eligible_for_separate_authorization": false,
          "same_bias_pass": {
            "HH": false,
            "SS": false
          },
          "utility_pass": false
        },
        "lc2_authorized": false,
        "role": "diagnostic_observation",
        "round_id": "dsa-lcb-v0.1-LC1"
      },
      "closing_round": "dsa-lcb-v0.1-LC1",
      "closing_run": {
        "artifact_manifest_sha256": "4b65ba49e23d1971783027d728cac3ce13b2b816d6a21a2fbda9aa3d31d8aa86",
        "contract_sha256": "29024b327b5066e6d2e431132b85dec1de1592095bed0a3cf87222aa1e81d2c7",
        "intake_path": "results/logs/remote/2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
        "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户授权设计并启动NRC1，并确认48小时累计预算；保留原准备起点2026-10-19T05:18:30+00:00，只实施NRC1，TECH与实测预算通过后才派发正式任务，旧LC2/F1/F2/B不启动。"
    },
    {
      "campaign_id": "dsainet-dsa-nrc-v0.1-NRC1-20261019",
      "closed_at": "2026-10-23T13:54:50.817578+00:00",
      "closing_decision": {
        "decision": "LIFECYCLE_CLOSED_WITH_BUDGET_DEVIATION",
        "evidence_id": "dsainet-nrc1-repair3-complete-20261023",
        "formal_claim_created": false,
        "frozen_gate_pass": false,
        "role": "lifecycle_only_no_scientific_judgment",
        "round_id": "dsa-nrc-v0.1-NRC1",
        "scientific_decision": null
      },
      "closing_round": "dsa-nrc-v0.1-NRC1",
      "closing_run": {
        "artifact_manifest_sha256": "0e3956d5028517ae7f8fc33e91be70cfdb46b433e945d3bbc6a55282b0c2315f",
        "contract_sha256": "3666bec81ef4aab5bc6a437fb0fde27f9684f0c64f365b04be42ab29d40542ef",
        "evidence_id": "dsainet-nrc1-repair3-complete-20261023",
        "intake_path": "programs/dsainet/research/dsa-nrc-v0.1/intake/NRC1repair3_complete_20261023",
        "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
        "run_status": "complete_with_budget_deviation",
        "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-tx",
        "verified": true,
        "verified_at": "20261023T134933Z"
      },
      "closing_status": "PAUSED_FOR_HUMAN",
      "closure_reason": "User explicitly requested launch and confirmed24h exact Lab10 destination/payload; P0-CUE-R1 only, preserve NRC1 lifecycle and budget deviation."
    },
    {
      "campaign": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User explicitly requested launch and confirmed24h exact Lab10 destination/payload; P0-CUE-R1 only, preserve NRC1 lifecycle and budget deviation.",
        "budget_authorization_history": [
          {
            "additional_hours": 4,
            "authorization_ref": "ai4s/programs/dsainet/research/p0-pf-r1/execution/BUDGET_APPROVAL.md",
            "authorization_sha256": "a2b65cb9dc07a37fae7d504c6702b90f1e5cb638bfcfe30b3945c0c93ce8d085",
            "authorized_total_hours": 144,
            "closeout_reserve_hours": 4,
            "gate_report": "ai4s/programs/dsainet/research/p0-pf-r1/FINAL_BUDGET_GATE.json",
            "gate_report_sha256": "dedeb5f2732816c1dd0bc9ba166556f0129a1d301b93dc9d706a4dec716aeb4e",
            "gate_status": "BLOCK_CUMULATIVE_BUDGET",
            "launched": false,
            "original_started_at_preserved": "2026-10-23T13:28:00+00:00",
            "previous_total_hours": 140,
            "recorded_at": "2026-10-29T06:18:18.594097+00:00",
            "research_id": "p0-pf-r1",
            "round_extension_applied": false,
            "run_registered": false,
            "science_node_ceiling_hours": 23,
            "transaction_ceiling_hours": 27,
            "uploaded": false
          },
          {
            "additional_hours": 1,
            "authorization_ref": "ai4s/programs/dsainet/research/p0-pf-r1/execution/BUDGET_APPROVAL_157.md",
            "authorization_sha256": "9f2f5914116e61c46895acb538d0614cabdd6d7d7055ff0fc3f71ce39fdf840c",
            "authorized_total_hours": 157,
            "logical_round_index_preserved": 3,
            "max_rounds_preserved": 4,
            "previous_total_hours": 156,
            "science_node_ceiling_hours": 23,
            "started_at_preserved": "2026-10-23T13:28:00+00:00",
            "transaction_ceiling_hours": 27
          },
          {
            "additional_hours": 1,
            "authority": "user: 批准新增额度",
            "authorized_at": "2026-10-30T07:29:30.204850+00:00",
            "authorized_total_hours": 158,
            "four_hour_envelope_balance_sufficient": true,
            "original_started_at": "2026-10-23T13:28:00+00:00",
            "planned_science_cap_hours": 3.25,
            "planned_transaction_cap_hours": 4,
            "preserved_queue_seconds": 31055.862429380417,
            "previous_total_hours": 157,
            "record_id": "DSAINET-P0-ORD-EC-BUDGET158-20261030",
            "remaining_as_of": "2026-10-30T07:29:30.204850+00:00",
            "remaining_hours_snapshot": 4.601571549827895,
            "scientific_execution_authorized": false,
            "scientific_fits_started": 0,
            "scope": "budget approval only; previous hold on 108 scientific fits remains"
          },
          {
            "additional_hours": 5,
            "approved_proposal": "Additional 5h, cumulative 163h; retain original start, SCI3.25h/Tx4h; exact planned Lab10 directory and payload, upload and start 108 fits/audits after review and final gate",
            "authorized_at": "2026-10-30T12:02:42.506984+00:00",
            "original_started_at": "2026-10-23T13:28:00+00:00",
            "previous_total_hours": 158,
            "remote_root": "[REDACTED_MACHINE]",
            "ssh_host": "[REDACTED_MACHINE]",
            "total_hours": 163,
            "user_answer": "允许"
          },
          {
            "additional_hours": 28,
            "allowed_operations": [
              "implementation",
              "freeze",
              "upload",
              "technical_launch",
              "probe",
              "fetch",
              "intake",
              "cost_analysis"
            ],
            "interpreted_scope": "Accept prior concrete question: add28h total191, same start; exact DS07 TECH-only payload/directory; 4 arms8batch+5epoch; no scientific training",
            "new_total_hours": 191,
            "original_start_preserved": "2026-10-23T13:28:00+00:00",
            "p0_cue_remains_closed": true,
            "payload_scope": "N/C/S/R source, native source, config, 9 frozen splits and necessary technical proof; no EEG/checkpoints/credentials",
            "previous_total_hours": 163,
            "recorded_at": "2026-10-31T19:07:14.691947+00:00",
            "scientific_audits_authorized": 0,
            "scientific_fits_authorized": 0,
            "state_before_sha256": "9cf0584d64848b732f2b328810afc4cf577d3d492a496ed0d7d59e401933ab49",
            "technical_ceiling_hours": 2,
            "transport_destination": "[REDACTED_MACHINE]",
            "user_message": "确认新增"
          },
          {
            "additional_hours": 3,
            "allowed_operations": [
              "implementation",
              "freeze",
              "upload",
              "technical_launch",
              "probe",
              "fetch",
              "intake",
              "cost_analysis"
            ],
            "interpreted_scope": "Accept prior concrete request: add3h total194, original timer unchanged, same authorized DS07 TECH destination and scope; scientific training remains prohibited",
            "new_total_hours": 194,
            "original_start_preserved": "2026-10-23T13:28:00+00:00",
            "p0_cue_remains_closed": true,
            "payload_scope": "N/C/S/R source, native source, config, 9 frozen splits and necessary technical proof; no EEG/checkpoints/credentials",
            "previous_total_hours": 191,
            "recorded_at": "2026-11-01T04:38:52.993979+00:00",
            "scientific_audits_authorized": 0,
            "scientific_fits_authorized": 0,
            "state_before_sha256": "8daca74508d8a818dc3a2bb23854a6d8fa5b0977b729316eb91b381e3829943b",
            "technical_ceiling_hours": 2,
            "transport_destination": "[REDACTED_MACHINE]",
            "user_message": "确认"
          },
          {
            "additional_hours": 8,
            "allowed_operations": [
              "implementation",
              "freeze",
              "upload",
              "technical_launch",
              "probe",
              "fetch",
              "intake",
              "cost_analysis"
            ],
            "interpreted_scope": "Explicit total202 plus only this closed manual approval interval; resume now; same authorized TECH payload/directory and zero science",
            "manual_approval_wait": {
              "authorization": "explicit_user_approved_single_interval",
              "end_boundary_basis": "conservative: 10 seconds before first tool receipt observation; registration/implementation processing is charged",
              "end_utc": "2026-11-01T04:43:45.932671+00:00",
              "first_receipt_observation_utc": "2026-11-01T04:43:55.932671+00:00",
              "no_remote_tasks_running": true,
              "resume_at_end": true,
              "seconds": 115.93227,
              "source_request": "ai4s/programs/dsainet/research/ds07-r1/preparation/PROPOSED_WAIT_BOUNDARY.json",
              "source_request_sha256": "b31f1f05e808d07bb0a54e3b63ed5df343281f9db5e473bd56b962d4c4e50758",
              "start_utc": "2026-11-01T04:41:50.000401+00:00"
            },
            "new_total_hours": 202,
            "original_start_preserved": "2026-10-23T13:28:00+00:00",
            "p0_cue_remains_closed": true,
            "payload_scope": "N/C/S/R source, native source, config, 9 frozen splits and necessary technical proof; no EEG/checkpoints/credentials",
            "previous_total_hours": 194,
            "recorded_at": "2026-11-01T04:44:33.082441+00:00",
            "scientific_audits_authorized": 0,
            "scientific_fits_authorized": 0,
            "state_before_sha256": "3f7df447e096552ebccf3f02ca84541b2d50630e44e562f22149f8ce8cb01081",
            "technical_ceiling_hours": 2,
            "transport_destination": "[REDACTED_MACHINE]",
            "user_message": "同意追加8小时，总预算提高到202小时，并仅将本次申请至确认期间无任务运行的人工等待暂停计时；保留原起点及此前耗时，确认后恢复计时。按已授权范围继续四臂资格与5epoch TECH，完成验收和72项训练成本核算，暂不启动科学训练。"
          }
        ],
        "campaign_id": "dsainet-p0-cue-r1-20261023",
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
          "authorization_ref": "ai4s/programs/dsainet/research/p0-pf-r1/execution/PACKFIX1_AUTHORIZATION.md",
          "campaign_id": "dsainet-p0-cue-r1-20261023",
          "executor_id": "lab10",
          "recorded_at": "2026-10-29T07:50:18.675039+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "P0-PF-EQUAL-SHARED-BIAS-LS010"
            ],
            "allowed_stages": [
              "screen"
            ],
            "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
            "question_id": "p0-asymmetric-statistics-probability-fusion"
          },
          "source_sha256": "cfedbabf86581a2e0156f924036a5c506b5b8914b5703a29b7fd670a6cca6e2c"
        },
        "execution_authorization_history": [
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-23T13:55:58.802365+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R1-EA-DIRECT-CURRENT-SOURCE-PROTOCOL"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-nine-contexts",
              "question_id": "p0-current-source-protocol-net-utility"
            },
            "source_sha256": "636239881ff5d9016df9ee311601e6f54457a54ee9b374842e20307e6e33abd8"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r1-limit72-r1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-23T18:15:44.075473+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R1-EA-DIRECT-CURRENT-SOURCE-PROTOCOL"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-nine-contexts",
              "question_id": "p0-current-source-protocol-net-utility"
            },
            "source_sha256": "6312ecc33a78238b702cf345f65535e3cd331c67d18ac539919e56b544b8fd59"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r1-costcal-r1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-23T18:30:35.614284+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R1-EA-DIRECT-CURRENT-SOURCE-PROTOCOL"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-nine-contexts",
              "question_id": "p0-current-source-protocol-net-utility"
            },
            "source_sha256": "79814332c9a82e1a16ee6f6577b9fc4eff0780a9c0e3ce3aaa072271b43306f6"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-24T07:32:08.941649+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "9653f6cbba69104a07be33b8eabd073bce2f903745e643f1b1ebe4cd55e6ce48"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-packfix1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-24T07:41:34.656180+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "4a5b7e40de59ce0e561cc924dfb9fd189db46e4fa000348d2188164d76923c71"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-packfix2/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-24T15:15:24.548750+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "4f06daee59c64ee430458b955771b03f016403bb4cd44bf522ed9005b5612628"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-perffix1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-25T02:25:23.082415+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "75fc0750d744269940050a9b0856871d9667015ec1e8b2a48e54f3ef77ae4ebe"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-waitfix1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-25T14:43:06.163330+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "8c9f5ad30501cdb01ed2960064ad328205ee8372e28369eb2be8c74468527400"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-finitefix1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-25T17:21:50.498446+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "ddfecb01eb9b6f43849301ff780db95dbb66852c5159cdd28e3cb41b495a96c4"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-flatfix1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-26T03:17:18.788866+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "5c23bfcdc667102b58c95030e6738863e0460f353eba4b674a152b1aab82418f"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-typefix1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-26T15:06:02.434638+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "f062688ffa0fa96ea794ee4e8ab78437ec9f37d65e5ec351d4518543b48d8a8b"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-s0tech1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-27T05:30:19.841644+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "699da5d676462b0159da4748b651c1e95bb7b111b2f62fe3095d328882995571"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-science1/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-27T17:50:06.355689+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "f9b59b944b9ba1df3acc28877f154e1cca3a026c7e2e8e2e5ddafaeebd884ef6"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-science1-packfix1/TRANSPORT_PACKFIX1.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-27T17:59:03.524539+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "e6a69d5a532bb176b8d1c724afe13ff39940a2282ec308b56796c0ce62237204"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-science1-dispatchfix1/TRANSPORT_DISPATCHFIX1.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-27T18:14:25.896384+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "9e401e08bc7d1adb9e146097fe414ae5fb0c2c7bb2fed1131e9a5f1d21e2770b"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2-science1-dispatchfix2/TRANSPORT_DISPATCHFIX2.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "recorded_at": "2026-10-27T18:17:45.080427+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R2-LS010-TRAIN-ONLY"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-fixed-ls-net-utility-with-matched-controls"
            },
            "source_sha256": "e9bf5964fee8237be65d2837e27b85831b332e7608bda93696c6665206432d64"
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r3-cvar/execution/AUTHORIZATION.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-CUE-R3-LOCAL-CENTERED-VARIANCE"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-local-centering-net-utility"
            }
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-pf-r1/execution/BUDGET_APPROVAL_156.md",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-PF-EQUAL-SHARED-BIAS-LS010"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-asymmetric-statistics-probability-fusion"
            }
          },
          {
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
            "authorization_ref": "ai4s/programs/dsainet/research/p0-pf-r1/execution/PACKFIX1_AUTHORIZATION.md",
            "authorization_sha256": "cfedbabf86581a2e0156f924036a5c506b5b8914b5703a29b7fd670a6cca6e2c",
            "campaign_id": "dsainet-p0-cue-r1-20261023",
            "executor_id": "lab10",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "P0-PF-EQUAL-SHARED-BIAS-LS010"
              ],
              "allowed_stages": [
                "screen"
              ],
              "data_scope_id": "bnci001-cue4-source6-select1-audit1-exposed-development",
              "question_id": "p0-asymmetric-statistics-probability-fusion"
            }
          }
        ],
        "extensions": [
          {
            "additional_hours": 48.0,
            "authorized_at": "2026-10-23T18:14:06.029396+00:00",
            "budget_argument_semantics": "night_budget_hours is the new cumulative campaign total, not an increment",
            "new_max_rounds": 1,
            "new_night_budget_hours": 72.0,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 24.0,
            "reason": "User explicitly authorized cumulative72h(+48h), science60h, original start retained and new Lab10 limit72 directory; original Run remains INVALID."
          },
          {
            "additional_hours": 0,
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r2/execution/AUTHORIZATION.md",
            "new_max_rounds": 2,
            "new_night_budget_hours": 72,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 72,
            "reason": "User explicitly authorized exactly R2 with original72h and clock; no third round"
          },
          {
            "additional_hours": 14.0,
            "authorized_at": "2026-10-27T04:53:27.350272+00:00",
            "budget_argument_semantics": "night_budget_hours is the new cumulative campaign total, not an increment",
            "new_max_rounds": 2,
            "new_night_budget_hours": 86.0,
            "previous_max_rounds": 2,
            "previous_night_budget_hours": 72.0,
            "reason": "User explicitly approved +14h cumulative86h, original start retained; Lab10 acceptance then S0-only qualification/5epochTECH/cost report, preserve B0/P0/oldRuns, no SCI. Authorization ai4s/programs/dsainet/research/p0-cue-r2-s0tech1/execution/AUTHORIZATION.md"
          },
          {
            "additional_hours": 54.0,
            "authorized_at": "2026-10-27T17:17:02.201679+00:00",
            "budget_argument_semantics": "night_budget_hours is the new cumulative campaign total, not an increment",
            "new_max_rounds": 2,
            "new_night_budget_hours": 140.0,
            "previous_max_rounds": 2,
            "previous_night_budget_hours": 86.0,
            "reason": "User explicitly authorizes recalculated complete original scientific matrix and then training; +54h from86 to140 total, original2026-10-23 clock, SCI40h Tx44h, preserve B0/P0/S0 verified successes and every oldRun; no TECH retraining."
          },
          {
            "additional_hours": 0,
            "authorization_ref": "ai4s/programs/dsainet/research/p0-cue-r3-cvar/execution/AUTHORIZATION.md",
            "new_max_rounds": 3,
            "new_night_budget_hours": 140.0,
            "previous_max_rounds": 2,
            "previous_night_budget_hours": 140.0,
            "reason": "One explicitly authorized bounded P0-CUE-R3-CVAR round; original campaign clock and 140h cumulative cap retained.",
            "round_id": "p0-cue-r3-cvar",
            "started_at_preserved": "2026-10-23T13:28:00+00:00"
          },
          {
            "additional_hours": 12.0,
            "authorization_ref": "ai4s/programs/dsainet/research/p0-pf-r1/execution/BUDGET_APPROVAL_156.md",
            "new_max_rounds": 4,
            "new_night_budget_hours": 156.0,
            "previous_max_rounds": 3,
            "previous_night_budget_hours": 144.0,
            "reason": "One frozen 90-fit/90-audit P0-PF-R1 screen; add exactly twelve campaign hours to the existing 144-hour cumulative budget while preserving the original clock and all prior Run records.",
            "round_id": "p0-pf-r1-science1",
            "started_at_preserved": "2026-10-23T13:28:00+00:00"
          }
        ],
        "governance_chain_id": "dsainet-transaction-v3.2",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "preparation_origin_ref": "ai4s/programs/dsainet/research/p0-cue-r1/execution/CAMPAIGN_BUDGET_ORIGIN.json",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-23_dsainet_p0_cue_r1-full-w1": {
            "contract_sha256": "275470df3eb483b726e442a74ef34707797db6d9deccc0eaef5269b7ce963794",
            "queue_seconds": 0.0,
            "run_id": "2026-10-23_dsainet_p0_cue_r1-full-w1",
            "transaction_id": "2026-10-23_dsainet_p0_cue_r1-tx"
          },
          "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1": {
            "contract_sha256": "4c85683a4e5e4732d4f52a7d71fb3d89afbf6fdaa73106c2d2ada33371677a59",
            "queue_seconds": 0.0,
            "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
            "transaction_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-tx"
          },
          "2026-10-24_dsainet_p0_cue_r1_limit72_r1-full-w1": {
            "contract_sha256": "7a7bcb79bed75d8411563583bd86c91a7ac944acd2cc826c16ea310b7cd7328a",
            "queue_seconds": 0.0,
            "run_id": "2026-10-24_dsainet_p0_cue_r1_limit72_r1-full-w1",
            "transaction_id": "2026-10-24_dsainet_p0_cue_r1_limit72_r1-tx"
          },
          "2026-10-24_dsainet_p0_cue_r2_ls010-full-w1": {
            "contract_sha256": "8791dd9d32fd96e3b45b30b33feb96a0b5ac3817142a96bd053b47b6e6f2a0a9",
            "queue_seconds": 0.0,
            "run_id": "2026-10-24_dsainet_p0_cue_r2_ls010-full-w1",
            "transaction_id": "2026-10-24_dsainet_p0_cue_r2_ls010-tx"
          },
          "2026-10-24_dsainet_p0_cue_r2_ls010_packfix1-full-w1": {
            "contract_sha256": "cab3aebb0540187ea3a767db1e077bf3bee5983a079a641cca0c1a519cff0ca9",
            "queue_seconds": 0.0,
            "run_id": "2026-10-24_dsainet_p0_cue_r2_ls010_packfix1-full-w1",
            "transaction_id": "2026-10-24_dsainet_p0_cue_r2_ls010_packfix1-tx"
          },
          "2026-10-24_dsainet_p0_cue_r2_ls010_packfix2-full-w1": {
            "contract_sha256": "9fb39fb4783e613384803dadb5f45cf9ad22356e364669c43144dbe1c899d8f9",
            "queue_seconds": 0.0,
            "run_id": "2026-10-24_dsainet_p0_cue_r2_ls010_packfix2-full-w1",
            "transaction_id": "2026-10-24_dsainet_p0_cue_r2_ls010_packfix2-tx"
          },
          "2026-10-25_dsainet_p0_cue_r2_perffix1-full-w1": {
            "contract_sha256": "7fed9b4f5f97ddd2492727aef33dd49d776136ef4b84847c942af93062b69f52",
            "queue_seconds": 2219.925709962845,
            "run_id": "2026-10-25_dsainet_p0_cue_r2_perffix1-full-w1",
            "transaction_id": "2026-10-25_dsainet_p0_cue_r2_perffix1-tx"
          },
          "2026-10-25_dsainet_p0_cue_r2_waitfix1-full-w1": {
            "contract_sha256": "b005a91e4b41922a9b1a1e3ba7c1a1018552b1880d63e2f62ed1cb5435d8fa28",
            "queue_seconds": 4605.769246339798,
            "run_id": "2026-10-25_dsainet_p0_cue_r2_waitfix1-full-w1",
            "transaction_id": "2026-10-25_dsainet_p0_cue_r2_waitfix1-tx"
          },
          "2026-10-26_dsainet_p0_cue_r2_finitefix1-full-w1": {
            "contract_sha256": "3411f3741b53ede8d3dadac8a2c924c2a940d59d444017ff844a83e907e61a6b",
            "queue_seconds": 13299.394689798355,
            "run_id": "2026-10-26_dsainet_p0_cue_r2_finitefix1-full-w1",
            "transaction_id": "2026-10-26_dsainet_p0_cue_r2_finitefix1-tx"
          },
          "2026-10-26_dsainet_p0_cue_r2_flatfix1-full-w1": {
            "contract_sha256": "b6cd843fae9512ad9be7ee16b370dee0b5269ef0fecd49a2414ee72c2236e8ca",
            "queue_seconds": 2759.614337682724,
            "run_id": "2026-10-26_dsainet_p0_cue_r2_flatfix1-full-w1",
            "transaction_id": "2026-10-26_dsainet_p0_cue_r2_flatfix1-tx"
          },
          "2026-10-26_dsainet_p0_cue_r2_typefix1-full-w1": {
            "contract_sha256": "f5926b44f470b69e7acdad47756e71583188c733760254266078ea71b3fae6ae",
            "queue_seconds": 4907.745910644531,
            "run_id": "2026-10-26_dsainet_p0_cue_r2_typefix1-full-w1",
            "transaction_id": "2026-10-26_dsainet_p0_cue_r2_typefix1-tx"
          },
          "2026-10-27_dsainet_p0_cue_r2_s0tech1-full-w1": {
            "contract_sha256": "6f134af566aed6182fdf84eb92f4f1539ce0f32342c1b2c25ac4af1450b309eb",
            "queue_seconds": 1363.6136393547058,
            "run_id": "2026-10-27_dsainet_p0_cue_r2_s0tech1-full-w1",
            "transaction_id": "2026-10-27_dsainet_p0_cue_r2_s0tech1-tx"
          },
          "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1": {
            "contract_sha256": "1b19048a796f2a4366cc216c5d31b5c0145fc50af62c11b3ac31143464709006",
            "queue_seconds": 0.0,
            "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1",
            "transaction_id": "2026-10-28_dsainet_p0_cue_r2_recover53-tx"
          },
          "2026-10-28_dsainet_p0_cue_r2_science1_dispatchfix2-full-w1": {
            "contract_sha256": "a1b78f460036d59ea71e8073b9b6116d6d7a25ccd03aee7a07ce10d990a0f7e4",
            "queue_seconds": 1893.6444840431213,
            "run_id": "2026-10-28_dsainet_p0_cue_r2_science1_dispatchfix2-full-w1",
            "transaction_id": "2026-10-28_dsainet_p0_cue_r2_science1_dispatchfix2-tx"
          },
          "2026-10-28_dsainet_p0_cue_r2_science1_packfix1-full-w1": {
            "contract_sha256": "2f35dd24f04dcc7db2088b9cc85be0328a53bd256dd0a5d85f0e9a63dbbdd23d",
            "queue_seconds": 0.0,
            "run_id": "2026-10-28_dsainet_p0_cue_r2_science1_packfix1-full-w1",
            "transaction_id": "2026-10-28_dsainet_p0_cue_r2_science1_packfix1-tx"
          },
          "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1": {
            "contract_sha256": "607b8efa174bb0c68cd2d4757710f47e9f41547e9ae1a331548da001b4e39b9c",
            "queue_seconds": 6.154411554336548,
            "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
            "transaction_id": "2026-10-28_dsainet_p0_cue_r3_cvar-tx"
          },
          "2026-10-29_dsainet_p0_pf_r1_science1-full-w1": {
            "contract_sha256": "6e557c1fc957d8aad90d8faea4d01fd25f96832e5cf13b2df011c93503edbdf8",
            "queue_seconds": 0.0,
            "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-full-w1",
            "transaction_id": "2026-10-29_dsainet_p0_pf_r1_science1-tx"
          },
          "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1": {
            "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
            "queue_seconds": 0.0,
            "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
            "transaction_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "NO_SIGNAL",
            "decision_record": "ai4s/programs/dsainet/research/p0-cue-r1-costcal-r1_decision.yaml",
            "evidence_id": "AI4S-DSAINET-p0-cue-r1-costcal-r1",
            "recorded_at": "2026-10-24T04:12:58.925227+00:00",
            "round_id": "p0-cue-r1-costcal-r1"
          },
          {
            "decision": "NO_SIGNAL",
            "decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-recover53_decision.yaml",
            "evidence_id": "AI4S-DSAINET-p0-cue-r2-recover53",
            "recorded_at": "2026-10-28T07:27:55.036483+00:00",
            "round_id": "p0-cue-r2-recover53"
          },
          {
            "decision": "NO_SIGNAL",
            "decision_record": "ai4s/programs/dsainet/research/p0-pf-r1-science1-packfix1_decision.yaml",
            "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-REVALIDATED-ANALYSIS-20261029",
            "recorded_at": "2026-10-29T11:56:23.546781+00:00",
            "role": "exposed_development_revalidated_analysis",
            "round_id": "p0-pf-r1-science1-packfix1",
            "standard_verified_intake": false
          }
        ],
        "started_at": "2026-10-23T13:54:50.817578+00:00"
      },
      "campaign_id": "dsainet-p0-cue-r1-20261023",
      "closed_at": "2026-11-02T11:43:00.395+00:00",
      "closing_round": null,
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "New explicitly authorized DS07-R1 screen; old P0 campaign preserved without a new scientific disposition.",
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 4,
        "monitor": "blocking",
        "night_budget_hours": 212,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 4,
        "started_at": "2026-10-23T13:28:00+00:00"
      },
      "scientific_disposition_added": false
    }
  ],
  "automatic_follow_up": false,
  "budget_authorization_history": [
    {
      "additional": 10,
      "authorization": "ai4s/programs/dsainet/research/ds07-r1/preparation/AUTHORIZATION.json",
      "previous_total": 202,
      "recorded_at": "2026-11-01T15:36:09.131886+00:00",
      "total": 212
    },
    {
      "additional": 54,
      "authorization": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/USER_APPROVAL266.json",
      "authorization_sha256": "3da978a48b669541ea6fb4e831c1e90db762bc3a018a3303fb4887fff0589c69",
      "closeout_hours": 4,
      "original_start_preserved": "2026-10-23T13:28:00+00:00",
      "previous_total": 212,
      "record_id": "DS07-R1-SCIENCE1-266H-20261102",
      "recorded_at": "2026-11-02T11:43:00.395+00:00",
      "research_id": "ds07-r1",
      "science_ceiling_hours": 33,
      "technical_ceiling_hours": 2,
      "total": 266,
      "transaction_ceiling_hours": 39
    }
  ],
  "budget_extension_pending": {
    "additional_execution_hours": 48,
    "authorization": "User explicitly approved48h and continuation2026-10-06",
    "automatic_training_retries": 0,
    "configuration_unchanged": true,
    "contract_sha256": "263cf15d16ffe8a3ded7bf10f773e65f93c3c72b8afe7dbd040274a9ba7bd4a5",
    "helper_pid": 2019390,
    "helper_receipt": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume9/HELPER_RECEIPT.json",
    "live_training_tasks": 16,
    "recorded_at": "2026-10-06T08:49:33.256791+00:00",
    "round_id": "dsa-pfc-xds-v0.1-physionet-resume9",
    "run_id": "2026-10-06_dsainet_pfc_xds_v0_1_physionet_resume9-full-w1",
    "source_run": "2026-10-06_dsainet_pfc_xds_v0_1_physionet_resume8-full-w1",
    "status": "ACTIVATED_REMOTE_RUNNING",
    "training_workers_interrupted": false,
    "verified_at": "2026-10-06T16:52:49.207183+08:00"
  },
  "campaign": {
    "activation_contract_sha256": "39305fc39830c027f59b70f430ca261c95c2a6528c327a0a45515216d324e059",
    "authorization_reason": "DS07-R1-SCIENCE1-266H-20261102",
    "budget_origin": "2026-10-23T13:28:00+00:00",
    "budget_origin_total_hours": 266,
    "budget_policy": {
      "exclude_verified_stopped_seconds": true
    },
    "campaign_id": "dsainet-ds07-r1",
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
        "ENGINEERING_REPAIR"
      ],
      "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/USER_APPROVAL266.json",
      "authorization_sha256": "3da978a48b669541ea6fb4e831c1e90db762bc3a018a3303fb4887fff0589c69",
      "campaign_id": "dsainet-ds07-r1",
      "executor_id": "lab10",
      "readerfix1_transport_authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/EXPLICIT_TARGET_REPLY.json",
      "readerfix1_transport_authorization_sha256": "9fc0e3927efa3392330815e43a25538c227b2cbd5fe9d3c0e97536c5a48463fb",
      "research_scope": {
        "allow_new_module": false,
        "allowed_module_ids": [
          "dsainet.ds07-r1.paired-four-arm-model"
        ],
        "allowed_stages": [
          "screen"
        ],
        "data_scope_id": "dsainet.ds07-r1-cue4-source6-select1-audit1-exposed-development",
        "question_id": "dsainet.ds07-r1.ce100-four-arm-comparison"
      }
    },
    "governance_chain_id": "dsainet-transaction-v3.3",
    "invalid_behavior": "fail_closed_without_advancing",
    "positive_signal_behavior": "pause_for_human_review",
    "purpose": "User-authorized bounded DS07-R1 screen",
    "queue_accounting": {
      "2026-11-02_dsainet_ds07_r1_science1-full-w1": {
        "contract_sha256": "2bb53a03bdaadd9040b7159254b2ddba1a707b98f8222f7a5e715dbf3897cdd8",
        "proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/FAILURE_PROOF.json",
        "proof_sha256": "603b251d599280190614e3de9bff7abca1a292d3e7f7308c94e7f3a1edece5dc",
        "queue_seconds": 355.13456535339355,
        "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
        "transaction_id": "dsainet-ds07-r1-science1"
      },
      "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1": {
        "contract_sha256": "d82104284d7dadd6a47831998c32727a97bca76aff0236c224fd56bfad02f243",
        "queue_seconds": 5744.736851215363,
        "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
        "transaction_id": "dsainet-ds07-r1-science1-readerfix1"
      },
      "historical-resource-credit-1": {
        "proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/AUTHORIZATION212.json",
        "proof_sha256": "5fd3c09766a8ace704933b0ef137b0abc173a6b5c716c4f2e19df4a92a1de745",
        "queue_seconds": 32898.104853630066
      },
      "historical-resource-credit-2": {
        "proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/packfix1_queue_clock.json",
        "proof_sha256": "495d3fd9c8f21320d7d756879fb8da96fa50c05ec7cfc3a05b605b7e6c25250f",
        "queue_seconds": 20067.248963356018
      }
    },
    "round_decisions": [],
    "started_at": "2026-10-23T13:28:00+00:00",
    "stopped_accounting": [
      {
        "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/manual_wait1_request.json",
        "end": "2026-11-01T04:43:45.932671+00:00",
        "evidence_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/manual_wait1_request.json",
        "source_run_id": "2026-11-01_dsainet_ds07_r1_tech1-repair1-packfix1",
        "start": "2026-11-01T04:41:50.000401+00:00"
      },
      {
        "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/manual_wait2_request.json",
        "end": "2026-11-01T15:34:11.239164+00:00",
        "evidence_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/manual_wait2_request.json",
        "source_run_id": "2026-11-01_dsainet_ds07_r1_tech1-repair1-packfix1",
        "start": "2026-11-01T15:29:22.947289+00:00"
      },
      {
        "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/USER_APPROVAL266.json",
        "end": "2026-11-02T11:43:00.395+00:00",
        "evidence_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/BUDGET_REQUEST_20261102.json",
        "source_run_id": "2026-11-01_dsainet_ds07_r1_tech1-repair1-packfix1",
        "start": "2026-11-02T11:42:31.033614+00:00"
      },
      {
        "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/EXPLICIT_TARGET_REPLY.json",
        "end": "2026-11-02T13:44:23.354000+00:00",
        "evidence_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/TRANSPORT_REQUEST.json",
        "source_run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
        "start": "2026-11-02T13:22:18.396823+00:00"
      }
    ]
  },
  "capacity_calibration_recovery": {
    "added_budget_seconds": 0,
    "automatic_training_retries": 0,
    "contract_sha256": "aee609a64380758d4a035cee9c685b7012df890dbb9e655ce80f043d939fea28",
    "draining_tasks": [
      "physionet_B0_s2_t14",
      "physionet_P0_s4_t13"
    ],
    "engineering_failures_preserved": 2,
    "first_helper_failure": "OLD_PREFIX substitution collision before process or training mutation",
    "fit_commitment_mib": 2048,
    "gpu_ids": [
      1,
      3,
      4,
      6,
      7,
      9
    ],
    "helper_pid": 4115452,
    "new_run_started": true,
    "observed_at": "2026-10-04T01:51:41.324223+00:00",
    "old_run": "2026-10-02_dsainet_pfc_xds_v0_1_physionet_resume2-full-w1",
    "per_gpu_public_reserve_mib": 1024,
    "planned_run": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume3-full-w1",
    "profile_counts": {
      "B0": 46,
      "P0": 46
    },
    "receipt": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume3/STATUS_CHECK_20261004.json",
    "run_id": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume3-full-w1",
    "scientific_result": false,
    "script_sha256": "d7c3490c9f8573825e47c9858a79f0ab1db787527266a0f339a62002c9c4fda1",
    "status": "RUNNING_WITH_BLOCKED_B0_FAMILY"
  },
  "capacity_first_step_recovery": {
    "added_budget_seconds": 0,
    "automatic_training_retries": 0,
    "contract_sha256": "010305cae9048f2bc3080bc5bd77d666c3e278137409f4130971873f821199a2",
    "explicit_failed_tasks": [
      "physionet_B0_s4_t23",
      "physionet_B0_s1_t24"
    ],
    "first_real_step_guard": true,
    "fit_commitment_mib": 2048,
    "gpu_ids": [
      1,
      3,
      4,
      6,
      7,
      9
    ],
    "helper_pid": 1078432,
    "latest_observation": {
      "automatic_retry_performed": false,
      "contract_sha256": "010305cae9048f2bc3080bc5bd77d666c3e278137409f4130971873f821199a2",
      "failed": 1,
      "failure_error": "Unable to find a valid cuDNN algorithm to run convolution",
      "failure_stage": "initialization forward inside construct_and_check",
      "failure_task": "physionet_B0_s4_t37",
      "first_step_ready": 152,
      "new_completed": 147,
      "oom_flag": false,
      "pending": 549,
      "query_time": "2026-10-05T16:12:40.177626+08:00",
      "remaining_execution_hours": 20.8981469,
      "reused_fits": 388,
      "run_id": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume4-full-w1",
      "running": 5,
      "scientific_intake": false,
      "status": "RUNNING_WITH_ONE_FAILURE",
      "target_complete": 0,
      "total_completed": 535
    },
    "local_validation": "PASS_parameters_Adam_RNG_identical_no_extra_step",
    "maintenance_pid": 1081868,
    "new_run_started": true,
    "old_run": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume3-full-w1",
    "planned_run": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume4-full-w1",
    "public_reserve_per_gpu_mib": 1024,
    "run_id": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume4-full-w1",
    "scientific_result": false,
    "script_sha256": "24f46aa20dc4c26423435ca59e05e55c9e248e9fc750aef3b896e41c0b8186e1",
    "status": "RUNNING_WITH_ONE_FAILED_TASK"
  },
  "completed_local_experiments": [
    {
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-zhou-v0.1/AUTHORIZATION.json",
      "closure_ref": "ai4s\\programs\\dsainet\\research\\dsa-pfc-zhou-v0.1\\CLOSURE_VERIFICATION.json",
      "contract_sha256": "5f8f7cd9bff67ffa6bb1432e46b74606c936dbe731a6a5c605fa8ee4fdd27340",
      "exp_id": "2026-10-10_dsainet_p0_zhou2016_loso_local_w2",
      "launcher_pid": 7920,
      "local_status_path": "output/local/2026-10-10_dsainet_p0_zhou2016_loso_local_w2/STATUS.json",
      "old_remote_campaign_unchanged": true,
      "scientific_results_pending": true,
      "status": "ARCHIVED_ANALYZED_VERIFIED"
    }
  ],
  "completed_rounds": [
    {
      "continuation_reason": "User authorized R02 causal decomposition of generic post-inter residual capacity versus the symmetric/shared-mean C1 structure.",
      "continued_at": "2026-08-29T13:13:44.202323+00:00",
      "decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r01-scale-contrast-residual-v0.1"
      },
      "round_id": "dsainet-r01-scale-contrast-residual-v0.1",
      "run": {
        "bundle_id": "2026-08-29_dsainet_ai4s_scale_contrast_r1",
        "estimated_training_hours": 2.638,
        "planned_units": 54,
        "recorded_at": "2026-08-29T09:25:22.539488+00:00",
        "round_id": "dsainet-r01-scale-contrast-residual-v0.1",
        "run_prefix": "2026-08-29_dsainet_ai4s_scale_contrast_r1"
      }
    },
    {
      "continuation_reason": "User authorized R03 independent C1-versus-native B0 stability confirmation on new seeds 2/3.",
      "continued_at": "2026-08-29T15:03:59.625799+00:00",
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r02-shared-mean-vs-generic-residual-v0.1"
      },
      "round_id": "dsainet-r02-shared-mean-vs-generic-residual-v0.1",
      "run": {
        "bundle_id": "2026-08-29_dsainet_ai4s_capacity_structure_r2b",
        "estimated_training_hours": 0.879,
        "planned_units": 18,
        "recorded_at": "2026-08-29T13:18:25.129656+00:00",
        "round_id": "dsainet-r02-shared-mean-vs-generic-residual-v0.1",
        "run_prefix": "2026-08-29_dsainet_ai4s_capacity_structure_r2b"
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-confirm-role-pooling-seed23-repair2-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-confirm-role-pooling-seed23-repair2-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-confirm-role-pooling-seed23-repair2-v0.1",
      "round_id": "dsainet-confirm-role-pooling-seed23-repair2-v0.1",
      "run": {
        "bundle_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.056,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 37,
        "recorded_at": "2026-09-05T19:20:00.112988+00:00",
        "round_id": "dsainet-confirm-role-pooling-seed23-repair2-v0.1",
        "run_prefix": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-05T19:21:53.193977+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-05T19:22:03.583647+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-05T19:22:13.018254+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "confirm",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-05T20:22:08.960592+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "confirm",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-05T21:22:09.675522+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-05T21:24:07.847968+00:00",
            "result": {
              "artifact_manifest_sha256": "aff7ccce897c5e7564ac9417207bcd6dc771acbc5a6063c468fbeb585be1614d",
              "contract_sha256": "1709d79e32c7465765af859b71bbcbc9d4bb3414836ebdf2ec416da0c461ae25",
              "run_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4-full-w1",
              "transaction_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r02-inter-attention-lesion-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r02-inter-attention-lesion-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r02-inter-attention-lesion-v0.1",
      "round_id": "dsainet-r02-inter-attention-lesion-v0.1",
      "run": {
        "bundle_id": "2026-09-06_dsainet_inter_attention_lesion_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.056,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 37,
        "recorded_at": "2026-09-06T09:21:16.563991+00:00",
        "round_id": "dsainet-r02-inter-attention-lesion-v0.1",
        "run_prefix": "2026-09-06_dsainet_inter_attention_lesion_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-06T09:21:34.450474+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-06_dsainet_inter_attention_lesion_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-06T09:21:40.532580+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-06_dsainet_inter_attention_lesion_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T09:21:46.745130+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T09:46:47.551058+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T11:21:48.277385+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-06T11:25:37.804876+00:00",
            "result": {
              "artifact_manifest_sha256": "9ee6cb55157f8647a5cc4933bee1df362a9ee247272e64a07b7e6ee65fd40558",
              "contract_sha256": "42b14baa2fa218f55b29503cb267bc63d6fa11114b08d10e4a254354ce775e66",
              "run_id": "2026-09-06_dsainet_inter_attention_lesion_r1-full-w1",
              "transaction_id": "2026-09-06_dsainet_inter_attention_lesion_r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r03-ilud-v0.1-r4"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r03-ilud-v0.1-r4_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r03-ilud-v0.1-r4",
      "round_id": "dsainet-r03-ilud-v0.1-r4",
      "run": {
        "bundle_id": "2026-09-06_dsainet_ilud_v0_1_r4",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-06T16:29:08.800300+00:00",
        "round_id": "dsainet-r03-ilud-v0.1-r4",
        "run_prefix": "2026-09-06_dsainet_ilud_v0_1_r4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-06T16:29:17.023774+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-06_dsainet_ilud_v0_1_r4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-06T16:29:22.018943+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-06_dsainet_ilud_v0_1_r4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T16:29:30.644606+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnose",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T16:39:22.678036+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-06T16:41:54.037505+00:00",
            "result": {
              "artifact_manifest_sha256": "a6f641b3c5c8c99f3186c811a9d4bb3c42b282a1f228d7e7fe8107d2915eec56",
              "contract_sha256": "f5d24288d1786405cde2a8dea5d19061200eb102cd95a268a67fb794dc31ed90",
              "run_id": "2026-09-06_dsainet_ilud_v0_1_r4-full-w1",
              "transaction_id": "2026-09-06_dsainet_ilud_v0_1_r4-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r04-dnrua-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r04-dnrua-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r04-dnrua-v0.1",
      "round_id": "dsainet-r04-dnrua-v0.1",
      "run": {
        "bundle_id": "2026-09-07_dsainet_dnrua_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-06T17:38:02.528360+00:00",
        "round_id": "dsainet-r04-dnrua-v0.1",
        "run_prefix": "2026-09-07_dsainet_dnrua_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-06T17:42:23.020894+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_dnrua_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-06T17:43:14.428592+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_dnrua_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T17:43:34.674057+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-06T17:46:53.165903+00:00",
            "result": {
              "artifact_manifest_sha256": "071cc92a6363eadd5ed5452d9a19ff76c47eef10e4a642004bf150f02a2cbd59",
              "contract_sha256": "93aecdb23f5d3c4974d3b08291f395d8af39c97e842fd38b0be2bb8b20ea90ff",
              "run_id": "2026-09-07_dsainet_dnrua_v0_1-full-w1",
              "transaction_id": "2026-09-07_dsainet_dnrua_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r05-mroa-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r05-mroa-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r05-mroa-v0.1",
      "round_id": "dsainet-r05-mroa-v0.1",
      "run": {
        "bundle_id": "2026-09-07_dsainet_mroa_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-06T18:12:48.002038+00:00",
        "round_id": "dsainet-r05-mroa-v0.1",
        "run_prefix": "2026-09-07_dsainet_mroa_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-06T18:12:57.327811+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_mroa_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-06T18:13:02.231076+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_mroa_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T18:13:12.201206+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnose",
              "run_id": "2026-09-07_dsainet_mroa_v0_1-full-w1",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T18:23:44.360331+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-07_dsainet_mroa_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-06T18:24:05.943802+00:00",
            "result": {
              "artifact_manifest_sha256": "d4569665a7f4993cd3acadd4634d15f2e113db13d3a3085de5bad6b171ac273a",
              "contract_sha256": "4b16d8280cbcbf742cce74592ed6c31933c3990034ab02f1cf12d61465106376",
              "run_id": "2026-09-07_dsainet_mroa_v0_1-full-w1",
              "transaction_id": "2026-09-07_dsainet_mroa_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r06-cgmw-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r06-cgmw-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r06-cgmw-v0.1",
      "round_id": "dsainet-r06-cgmw-v0.1",
      "run": {
        "bundle_id": "2026-09-07_dsainet_cgmw_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-06T18:27:57.954122+00:00",
        "round_id": "dsainet-r06-cgmw-v0.1",
        "run_prefix": "2026-09-07_dsainet_cgmw_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-06T18:28:10.504083+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_cgmw_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-06T18:28:11.152576+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_cgmw_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T18:28:11.893539+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-07_dsainet_cgmw_v0_1-full-w1",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T18:38:29.182450+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-07_dsainet_cgmw_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-06T18:38:49.194943+00:00",
            "result": {
              "artifact_manifest_sha256": "c7f16c9c93f1dbfbee5b4849d40408afeac3284710053494027a978b64e6a206",
              "contract_sha256": "6af672b8ca71faf6c783ef0c00653358d8158816a129c34a83a5733dd4d5dc28",
              "run_id": "2026-09-07_dsainet_cgmw_v0_1-full-w1",
              "transaction_id": "2026-09-07_dsainet_cgmw_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r07-tapl-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r07-tapl-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r07-tapl-v0.1",
      "round_id": "dsainet-r07-tapl-v0.1",
      "run": {
        "bundle_id": "2026-09-07_dsainet_tapl_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-06T18:43:21.916487+00:00",
        "round_id": "dsainet-r07-tapl-v0.1",
        "run_prefix": "2026-09-07_dsainet_tapl_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-06T18:43:39.036737+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_tapl_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-06T18:43:39.640871+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_tapl_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T18:43:40.250990+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-07_dsainet_tapl_v0_1-full-w1",
              "status": "RUNNING"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-06T18:51:46.855754+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-07_dsainet_tapl_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION"
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-06T18:52:00.480276+00:00",
            "result": {
              "artifact_manifest_sha256": "8ac33c86128e8fc39ac7acf5e9c078ca0052cec71f40cbb9424a4d923733aaa2",
              "contract_sha256": "7b1c420c28ff04937cf81127ed19f3c51b0cbc67ed259df7f2205cf90ca837bf",
              "run_id": "2026-09-07_dsainet_tapl_v0_1-full-w1",
              "transaction_id": "2026-09-07_dsainet_tapl_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r01-taud-v0.1-r2"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-taud-v0.1-r2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-taud-v0.1-r2",
      "round_id": "dsainet-r01-taud-v0.1-r2",
      "run": {
        "bundle_id": "2026-09-07_dsainet_taud_v0_2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-07T03:32:09.330623+00:00",
        "round_id": "dsainet-r01-taud-v0.1-r2",
        "run_prefix": "2026-09-07_dsainet_taud_v0_2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-07T03:32:33.339898+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-07T03:32:34.020760+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T03:32:35.825924+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "919baf33009df86ecf302378925f0f72e30a85c7aef62a303f316162b8e32303",
                "execution_seconds": 1.6207036972045898,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1",
                "transaction_id": "2026-09-07_dsainet_taud_v0_2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1.6207036972045898
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T03:43:04.889237+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "919baf33009df86ecf302378925f0f72e30a85c7aef62a303f316162b8e32303",
                "execution_seconds": 22.262348413467407,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1",
                "transaction_id": "2026-09-07_dsainet_taud_v0_2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 22.262348413467407
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-07T03:44:57.780746+00:00",
            "result": {
              "artifact_manifest_sha256": "759f598aab894011a676e46562348c350fe0f3d7a05c41e23e531da27e83174c",
              "contract_sha256": "919baf33009df86ecf302378925f0f72e30a85c7aef62a303f316162b8e32303",
              "run_id": "2026-09-07_dsainet_taud_v0_2-full-w1",
              "transaction_id": "2026-09-07_dsainet_taud_v0_2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r01-sfta-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-sfta-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-sfta-v0.1",
      "round_id": "dsainet-r01-sfta-v0.1",
      "run": {
        "bundle_id": "2026-09-07_dsainet_sfta_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 2,
        "recorded_at": "2026-09-07T06:04:27.566686+00:00",
        "round_id": "dsainet-r01-sfta-v0.1",
        "run_prefix": "2026-09-07_dsainet_sfta_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-07T06:04:54.157604+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-07T06:04:55.029101+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T06:04:56.237098+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2bb09ce1da93fc9d82a1fd55daa0d55aa443c2c76e51c295d9b36f5b555d22ca",
                "execution_seconds": 1.096132755279541,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_sfta_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1.096132755279541
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T06:15:20.372830+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "2bb09ce1da93fc9d82a1fd55daa0d55aa443c2c76e51c295d9b36f5b555d22ca",
                "execution_seconds": 20.958243131637573,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_sfta_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 20.958243131637573
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-07T06:15:51.835050+00:00",
            "result": {
              "artifact_manifest_sha256": "dfe22019959d9fa9e8222801bb78bc2c1eaec093598c675f770733ffe3160deb",
              "contract_sha256": "2bb09ce1da93fc9d82a1fd55daa0d55aa443c2c76e51c295d9b36f5b555d22ca",
              "run_id": "2026-09-07_dsainet_sfta_v0_1-full-w1",
              "transaction_id": "2026-09-07_dsainet_sfta_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-ttpp-lab10-remaining-v0.2"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-remaining-v0.2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-ttpp-lab10-remaining-v0.2",
      "round_id": "dsainet-r01-ttpp-lab10-remaining-v0.2",
      "run": {
        "bundle_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.056,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 55,
        "recorded_at": "2026-09-08T04:54:41.342118+00:00",
        "round_id": "dsainet-r01-ttpp-lab10-remaining-v0.2",
        "run_prefix": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-08T04:54:51.165256+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-08T04:57:08.267541+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T04:57:22.315261+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1ee0af4cc7d3a664b47f8100d0ce0d7b896eccd39668385076b9240f8b3da3d8",
                "execution_seconds": 13.350927829742432,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
                "transaction_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.350927829742432
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T05:22:56.150672+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "1ee0af4cc7d3a664b47f8100d0ce0d7b896eccd39668385076b9240f8b3da3d8",
                "execution_seconds": 1428.8544292449951,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
                "transaction_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1428.8544292449951
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-08T05:23:40.016231+00:00",
            "result": {
              "artifact_manifest_sha256": "18330aea12e44c08f52b575c5b25ac7347840a6bf45b3616aae20bbf13c90521",
              "contract_sha256": "1ee0af4cc7d3a664b47f8100d0ce0d7b896eccd39668385076b9240f8b3da3d8",
              "run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
              "transaction_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-rora-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-rora-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-rora-v0.1",
      "round_id": "dsainet-r01-rora-v0.1",
      "run": {
        "bundle_id": "2026-09-08_dsainet_rora_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.111,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 2,
        "recorded_at": "2026-09-08T08:40:46.165346+00:00",
        "round_id": "dsainet-r01-rora-v0.1",
        "run_prefix": "2026-09-08_dsainet_rora_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-08T08:41:42.028651+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-08T08:47:10.921317+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T08:48:01.394403+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnose",
              "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f890aec8bb4285880b8c720ccc123c61073b4575cb7b084f476bd5a6bf8dc09d",
                "execution_seconds": 49.593786001205444,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_rora_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 49.593786001205444
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T09:10:32.150817+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "f890aec8bb4285880b8c720ccc123c61073b4575cb7b084f476bd5a6bf8dc09d",
                "execution_seconds": 1061.2594556808472,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_rora_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1061.2594556808472
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-08T09:28:58.507605+00:00",
            "result": {
              "artifact_manifest_sha256": "ac5c5be0c7ab184a1b0ce8d593d9583b543888f360f7d5e5c227e4743428cdb6",
              "contract_sha256": "f890aec8bb4285880b8c720ccc123c61073b4575cb7b084f476bd5a6bf8dc09d",
              "run_id": "2026-09-08_dsainet_rora_v0_1-full-w1",
              "transaction_id": "2026-09-08_dsainet_rora_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-aast-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-aast-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-aast-v0.1",
      "round_id": "dsainet-r01-aast-v0.1",
      "run": {
        "bundle_id": "2026-09-08_dsainet_aast_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.167,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-08T10:33:55.692786+00:00",
        "round_id": "dsainet-r01-aast-v0.1",
        "run_prefix": "2026-09-08_dsainet_aast_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-08T10:34:41.458126+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-08T10:35:23.374972+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T10:35:44.849514+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "50ea4c918e79c764be0f8872e93bd2ef400bd535cec99e324dd9d470008bfd4d",
                "execution_seconds": 20.12678289413452,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_aast_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 20.12678289413452
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T10:37:11.541863+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "50ea4c918e79c764be0f8872e93bd2ef400bd535cec99e324dd9d470008bfd4d",
                "execution_seconds": 106.87666392326355,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_aast_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 106.87666392326355
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T14:19:34.379702+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "50ea4c918e79c764be0f8872e93bd2ef400bd535cec99e324dd9d470008bfd4d",
                "execution_seconds": 3149.8864464759827,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_aast_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3149.8864464759827
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-08T14:24:24.914675+00:00",
            "result": {
              "artifact_manifest_sha256": "c778b3a35b00349ea93451939aef5ec410e1475de11d274f9f28efc8faf1a045",
              "contract_sha256": "50ea4c918e79c764be0f8872e93bd2ef400bd535cec99e324dd9d470008bfd4d",
              "run_id": "2026-09-08_dsainet_aast_v0_1-full-w1",
              "transaction_id": "2026-09-08_dsainet_aast_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-lvt-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-lvt-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-lvt-v0.1",
      "round_id": "dsainet-r01-lvt-v0.1",
      "run": {
        "bundle_id": "2026-09-08_dsainet_lvt_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.167,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-08T15:07:39.881369+00:00",
        "round_id": "dsainet-r01-lvt-v0.1",
        "run_prefix": "2026-09-08_dsainet_lvt_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-08T15:08:27.622309+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-08T15:08:45.818919+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T15:09:02.458157+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0443e9c9fc34bdf0c4db29df79dfe5522a1bfbf9155a04f591d218055e7fa1be",
                "execution_seconds": 15.910409927368164,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_lvt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15.910409927368164
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T15:09:53.123332+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0443e9c9fc34bdf0c4db29df79dfe5522a1bfbf9155a04f591d218055e7fa1be",
                "execution_seconds": 66.57968711853027,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_lvt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 66.57968711853027
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T19:31:46.748892+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "0443e9c9fc34bdf0c4db29df79dfe5522a1bfbf9155a04f591d218055e7fa1be",
                "execution_seconds": 3651.202419281006,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
                "transaction_id": "2026-09-08_dsainet_lvt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3651.202419281006
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-08T19:38:39.956949+00:00",
            "result": {
              "artifact_manifest_sha256": "bd5bca1683efeaad4fb3a6eef9b71d3fe64b9596f3fda7aba3e38982717db7f7",
              "contract_sha256": "0443e9c9fc34bdf0c4db29df79dfe5522a1bfbf9155a04f591d218055e7fa1be",
              "run_id": "2026-09-08_dsainet_lvt_v0_1-full-w1",
              "transaction_id": "2026-09-08_dsainet_lvt_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-nca-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-nca-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-nca-v0.1",
      "round_id": "dsainet-r01-nca-v0.1",
      "run": {
        "bundle_id": "2026-09-09_dsainet_nca_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.056,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-08T20:10:21.409254+00:00",
        "round_id": "dsainet-r01-nca-v0.1",
        "run_prefix": "2026-09-09_dsainet_nca_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-08T20:11:02.480162+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-08T20:11:25.282373+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T20:11:39.943984+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "410df6776c854f5063fe4702d3d2c804cd7fe45e469d70a6c427e671403ca0bb",
                "execution_seconds": 13.712819337844849,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_nca_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.712819337844849
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T20:12:56.642703+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnose",
              "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "410df6776c854f5063fe4702d3d2c804cd7fe45e469d70a6c427e671403ca0bb",
                "execution_seconds": 90.421635389328,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_nca_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 90.421635389328
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T02:21:35.880795+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "410df6776c854f5063fe4702d3d2c804cd7fe45e469d70a6c427e671403ca0bb",
                "execution_seconds": 423.8835349082947,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_nca_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 423.8835349082947
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T02:22:17.975069+00:00",
            "result": {
              "artifact_manifest_sha256": "c5bb0ba452fd2a202aef55e6f5d2692e3e7f46a5b22e5af63a8234143aeb4a21",
              "contract_sha256": "410df6776c854f5063fe4702d3d2c804cd7fe45e469d70a6c427e671403ca0bb",
              "run_id": "2026-09-09_dsainet_nca_v0_1-full-w1",
              "transaction_id": "2026-09-09_dsainet_nca_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-sdsa-v0.1-repair1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-sdsa-v0.1-repair1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-sdsa-v0.1-repair1",
      "round_id": "dsainet-r01-sdsa-v0.1-repair1",
      "run": {
        "bundle_id": "2026-09-09_dsainet_sdsa_v0_1_repair1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.111,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 74,
        "recorded_at": "2026-09-09T04:48:09.172602+00:00",
        "round_id": "dsainet-r01-sdsa-v0.1-repair1",
        "run_prefix": "2026-09-09_dsainet_sdsa_v0_1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-09T04:48:43.502117+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-09T04:49:00.049718+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T04:49:20.379782+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8da772dbabc1711c551479370dddf24bd6a599b3b828a680dec43468b23827dd",
                "execution_seconds": 19.485498428344727,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19.485498428344727
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T06:35:32.563012+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "8da772dbabc1711c551479370dddf24bd6a599b3b828a680dec43468b23827dd",
                "execution_seconds": 3312.4370324611664,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3312.4370324611664
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T06:41:44.464682+00:00",
            "result": {
              "artifact_manifest_sha256": "b0bc854e8da0e8d8a32607698f44c2299187d95ad5a45c2641f4f4d9e8a9436b",
              "contract_sha256": "8da772dbabc1711c551479370dddf24bd6a599b3b828a680dec43468b23827dd",
              "run_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-full-w1",
              "transaction_id": "2026-09-09_dsainet_sdsa_v0_1_repair1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-scsr-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-scsr-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-scsr-v0.1",
      "round_id": "dsainet-r01-scsr-v0.1",
      "run": {
        "bundle_id": "2026-09-09_dsainet_scsr_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.167,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-09T07:16:18.910235+00:00",
        "round_id": "dsainet-r01-scsr-v0.1",
        "run_prefix": "2026-09-09_dsainet_scsr_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-09T07:17:28.257545+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-09T07:17:52.542387+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T07:18:14.518447+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ac123dba3711984e2bb437887ce9139f8ae4a81fa16b9c0137f7e9a255f17a71",
                "execution_seconds": 21.26604390144348,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_scsr_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 21.26604390144348
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T09:33:05.722113+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "ac123dba3711984e2bb437887ce9139f8ae4a81fa16b9c0137f7e9a255f17a71",
                "execution_seconds": 4767.163182020187,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_scsr_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4767.163182020187
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T09:47:45.656099+00:00",
            "result": {
              "artifact_manifest_sha256": "0e0463f9a831d0a6b68435e73e027dae6e0d6d509f6759e09acb0528308bffa9",
              "contract_sha256": "ac123dba3711984e2bb437887ce9139f8ae4a81fa16b9c0137f7e9a255f17a71",
              "run_id": "2026-09-09_dsainet_scsr_v0_1-full-w1",
              "transaction_id": "2026-09-09_dsainet_scsr_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-cgx-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-cgx-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-cgx-v0.1",
      "round_id": "dsainet-r01-cgx-v0.1",
      "run": {
        "bundle_id": "2026-09-09_dsainet_cgx_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.111,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-09T10:29:35.391743+00:00",
        "round_id": "dsainet-r01-cgx-v0.1",
        "run_prefix": "2026-09-09_dsainet_cgx_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-09T10:34:09.765748+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-09_dsainet_cgx_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-09T10:34:45.296205+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-09_dsainet_cgx_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T10:35:24.769258+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_dsainet_cgx_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a1f0eecb2d031cf4d290a6cf6449a480a763b33d95350ed732695e35e7a2a7ec",
                "execution_seconds": 39.074461936950684,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_cgx_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_cgx_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 39.074461936950684
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T12:58:33.987120+00:00",
            "result": {
              "artifact_manifest_sha256": "c18e72ec0fdcb1c6e920a614187b25135710f93e4446cc65585e42167f573334",
              "contract_sha256": "a1f0eecb2d031cf4d290a6cf6449a480a763b33d95350ed732695e35e7a2a7ec",
              "run_id": "2026-09-09_dsainet_cgx_v0_1-full-w1",
              "transaction_id": "2026-09-09_dsainet_cgx_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-peci-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-peci-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-peci-v0.1",
      "round_id": "dsainet-r01-peci-v0.1",
      "run": {
        "bundle_id": "2026-09-09_dsainet_peci_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.111,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-09T14:12:03.841574+00:00",
        "round_id": "dsainet-r01-peci-v0.1",
        "run_prefix": "2026-09-09_dsainet_peci_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-09T14:15:40.572626+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-09T14:15:57.236920+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T14:16:14.587508+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
                "execution_seconds": 16.06537437438965,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 16.06537437438965
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T14:17:54.539193+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
                "execution_seconds": 116.00500249862671,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 116.00500249862671
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T15:48:34.033027+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
                "execution_seconds": 5555.624503135681,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 5555.624503135681
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T16:50:18.011997+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
                "execution_seconds": 9259.715908527374,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9259.715908527374
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T18:33:43.246848+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
                "execution_seconds": 10487.686157464981,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
                "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10487.686157464981
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-09T18:34:21.947577+00:00",
            "result": {
              "artifact_manifest_sha256": "d1056940f7bf26a2e7a512d2e5f288cd252d561c148e66bf79360c6d8bf8d776",
              "contract_sha256": "289105965ac9fa776ee38df69e4665eb0f77fecdb050c5dcbf677e0d429b0855",
              "run_id": "2026-09-09_dsainet_peci_v0_1-full-w1",
              "transaction_id": "2026-09-09_dsainet_peci_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-sba-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-sba-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-sba-v0.1",
      "round_id": "dsainet-r01-sba-v0.1",
      "run": {
        "bundle_id": "2026-09-10_dsainet_sba_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.111,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-09T19:09:56.888474+00:00",
        "round_id": "dsainet-r01-sba-v0.1",
        "run_prefix": "2026-09-10_dsainet_sba_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-09T19:10:37.433583+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-09T19:10:59.673186+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T19:11:28.479023+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bdfecbb8c879cbe15fbd6a9f363cd15a3f2dbe31aed71abda3dceed726d679b2",
                "execution_seconds": 27.53006672859192,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_sba_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 27.53006672859192
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-09T19:13:23.850465+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bdfecbb8c879cbe15fbd6a9f363cd15a3f2dbe31aed71abda3dceed726d679b2",
                "execution_seconds": 142.90179300308228,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_sba_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 142.90179300308228
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T04:12:31.173701+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "bdfecbb8c879cbe15fbd6a9f363cd15a3f2dbe31aed71abda3dceed726d679b2",
                "execution_seconds": 7802.5082585811615,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_sba_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 7802.5082585811615
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-10T04:12:57.025504+00:00",
            "result": {
              "artifact_manifest_sha256": "20912219573d210d96c8737114b23aedc179922e79db098e4a1bef7716bbb8eb",
              "contract_sha256": "bdfecbb8c879cbe15fbd6a9f363cd15a3f2dbe31aed71abda3dceed726d679b2",
              "run_id": "2026-09-10_dsainet_sba_v0_1-full-w1",
              "transaction_id": "2026-09-10_dsainet_sba_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "SCREEN_POSITIVE",
        "reason": "complete frozen screen passed all stability gates",
        "round_id": "dsainet-r01-ctoa-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-ctoa-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-ctoa-v0.1",
      "round_id": "dsainet-r01-ctoa-v0.1",
      "run": {
        "bundle_id": "2026-09-10_dsainet_ctoa_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.111,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-10T05:24:12.010967+00:00",
        "round_id": "dsainet-r01-ctoa-v0.1",
        "run_prefix": "2026-09-10_dsainet_ctoa_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-10T05:24:30.833962+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-10T05:24:44.143605+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T05:25:00.989714+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "09bdd86c0ab6904a329a493e2c0b95aa5fd46753c91df32256b09b08953c6e39",
                "execution_seconds": 2.46659517288208,
                "queue_seconds": 13.567854166030884,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_ctoa_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 16.034449338912964
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T05:27:14.847224+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "09bdd86c0ab6904a329a493e2c0b95aa5fd46753c91df32256b09b08953c6e39",
                "execution_seconds": 2.466615915298462,
                "queue_seconds": 147.42717099189758,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_ctoa_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 149.89378690719604
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T13:06:20.988696+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "09bdd86c0ab6904a329a493e2c0b95aa5fd46753c91df32256b09b08953c6e39",
                "execution_seconds": 2706.3685026168823,
                "queue_seconds": 7173.1827030181885,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_ctoa_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9879.55120563507
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-10T13:06:56.854957+00:00",
            "result": {
              "artifact_manifest_sha256": "7dccb99b8ae5411c5ef4bd324d4f58877b23ebff062794e031e3521ade3487f7",
              "contract_sha256": "09bdd86c0ab6904a329a493e2c0b95aa5fd46753c91df32256b09b08953c6e39",
              "run_id": "2026-09-10_dsainet_ctoa_v0_1-full-w1",
              "transaction_id": "2026-09-10_dsainet_ctoa_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r01-wosa-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-wosa-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-wosa-v0.1",
      "round_id": "dsainet-r01-wosa-v0.1",
      "run": {
        "bundle_id": "2026-09-10_dsainet_wosa_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.056,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-10T13:55:17.403245+00:00",
        "round_id": "dsainet-r01-wosa-v0.1",
        "run_prefix": "2026-09-10_dsainet_wosa_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-10T13:55:44.589845+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-10T13:56:03.505088+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T13:56:43.382344+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d2c3eb518cfd8708483c2ce1683949c786908a2b9eaaff926c3f2a82804164ce",
                "execution_seconds": 38.517657995224,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_wosa_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 38.517657995224
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-10T16:41:42.921112+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d2c3eb518cfd8708483c2ce1683949c786908a2b9eaaff926c3f2a82804164ce",
                "execution_seconds": 9938.316789627075,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_wosa_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9938.316789627075
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-11T08:23:09.311675+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "d2c3eb518cfd8708483c2ce1683949c786908a2b9eaaff926c3f2a82804164ce",
                "execution_seconds": 19315.15173101425,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
                "transaction_id": "2026-09-10_dsainet_wosa_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19315.15173101425
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-11T08:23:45.645702+00:00",
            "result": {
              "artifact_manifest_sha256": "212cde4ae3c283833b25be24217b8a65ddb5193d88ea12be4a6d9ed3aa9d7ea8",
              "contract_sha256": "d2c3eb518cfd8708483c2ce1683949c786908a2b9eaaff926c3f2a82804164ce",
              "run_id": "2026-09-10_dsainet_wosa_v0_1-full-w1",
              "transaction_id": "2026-09-10_dsainet_wosa_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-sna-v0.1-repair2"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-sna-v0.1-repair2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-sna-v0.1-repair2",
      "round_id": "dsainet-r01-sna-v0.1-repair2",
      "run": {
        "bundle_id": "2026-09-12_dsainet_sna_v0_1_repair2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.167,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-11T18:05:29.472278+00:00",
        "round_id": "dsainet-r01-sna-v0.1-repair2",
        "run_prefix": "2026-09-12_dsainet_sna_v0_1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-11T18:06:19.471478+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-11T18:06:46.555289+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-11T18:07:19.505450+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 11.732447624206543,
                "queue_seconds": 19.314449071884155,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 31.0468966960907
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-12T05:33:10.131637+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 40962.27269625664,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 41182.77127814293
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-12T08:16:08.616242+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 50740.82188749313,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 50961.320469379425
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-12T10:14:58.889772+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 57870.06879281998,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 58090.56737470627
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-12T14:59:42.502180+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 74953.43134093285,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 75173.92992281914
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-12T17:28:03.385604+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 83853.94528102875,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 84074.44386291504
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T00:53:55.030140+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 110606.94429135323,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 110827.44287323952
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T02:26:30.377465+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
                "execution_seconds": 112650.61952829361,
                "queue_seconds": 220.4985818862915,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 112871.1181101799
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-13T02:31:21.761347+00:00",
            "result": {
              "artifact_manifest_sha256": "e8d31e0c1e8345d08912df91df7e08224a07cf31b5dfe9fed4351168626cd597",
              "contract_sha256": "ce81ac269b645b9b0369d83e8faae9040b9fe906e2be19deb8103ce4b4123a85",
              "run_id": "2026-09-12_dsainet_sna_v0_1_repair2-full-w1",
              "transaction_id": "2026-09-12_dsainet_sna_v0_1_repair2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-tks-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-tks-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-tks-v0.1",
      "round_id": "dsainet-r01-tks-v0.1",
      "run": {
        "bundle_id": "2026-09-13_dsainet_tks_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.167,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-13T03:28:18.409289+00:00",
        "round_id": "dsainet-r01-tks-v0.1",
        "run_prefix": "2026-09-13_dsainet_tks_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-13T03:28:57.664899+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-13T03:29:11.485606+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T03:29:33.409619+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
                "execution_seconds": 20.398096323013306,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
                "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 20.398096323013306
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T03:30:47.920805+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
                "execution_seconds": 94.942556142807,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
                "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 94.942556142807
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T09:24:23.693545+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
                "execution_seconds": 21309.195843219757,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
                "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 21309.195843219757
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T12:32:21.195313+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
                "execution_seconds": 32586.875647306442,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
                "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 32586.875647306442
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-13T16:48:48.881235+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
                "execution_seconds": 47975.18222999573,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
                "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 47975.18222999573
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-14T04:13:05.533651+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
                "execution_seconds": 79084.2498691082,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
                "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 79084.2498691082
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-14T04:17:10.973718+00:00",
            "result": {
              "artifact_manifest_sha256": "46ba0b77f09303853c8416edf962eede679420693c75857cf00f8ee0ed49b810",
              "contract_sha256": "95dc8473f0a34a09aa45a2b16c1799ff2e1546cec0f089c694e131416d2313e9",
              "run_id": "2026-09-13_dsainet_tks_v0_1-full-w1",
              "transaction_id": "2026-09-13_dsainet_tks_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-tcua-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-tcua-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-tcua-v0.1",
      "round_id": "dsainet-r01-tcua-v0.1",
      "run": {
        "bundle_id": "2026-09-14_dsainet_tcua_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.056,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-09-14T07:49:03.093540+00:00",
        "round_id": "dsainet-r01-tcua-v0.1",
        "run_prefix": "2026-09-14_dsainet_tcua_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-14T07:49:48.574525+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-14T07:50:06.597833+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-14T07:50:33.002059+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0e01355a6990467b293e9cc3b0ac546a88eda3300c23791dbb37bf737d85ac0e",
                "execution_seconds": 25.355542182922363,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
                "transaction_id": "2026-09-14_dsainet_tcua_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 25.355542182922363
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-14T07:51:45.233024+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0e01355a6990467b293e9cc3b0ac546a88eda3300c23791dbb37bf737d85ac0e",
                "execution_seconds": 97.49622964859009,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
                "transaction_id": "2026-09-14_dsainet_tcua_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 97.49622964859009
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-14T12:51:23.184542+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "0e01355a6990467b293e9cc3b0ac546a88eda3300c23791dbb37bf737d85ac0e",
                "execution_seconds": 10115.957702636719,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
                "transaction_id": "2026-09-14_dsainet_tcua_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10115.957702636719
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-14T12:53:54.709898+00:00",
            "result": {
              "artifact_manifest_sha256": "32ba0651abad6f46895407aa05012f5d4347adec89de2bcd9d38865a08092a64",
              "contract_sha256": "0e01355a6990467b293e9cc3b0ac546a88eda3300c23791dbb37bf737d85ac0e",
              "run_id": "2026-09-14_dsainet_tcua_v0_1-full-w1",
              "transaction_id": "2026-09-14_dsainet_tcua_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsainet-r01-gsf-v0.1-repair2"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-gsf-v0.1-repair2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-gsf-v0.1-repair2",
      "round_id": "dsainet-r01-gsf-v0.1-repair2",
      "run": {
        "bundle_id": "2026-09-15_dsainet_gsf_v0_1_repair2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.167,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-09-15T09:04:33.189162+00:00",
        "round_id": "dsainet-r01-gsf-v0.1-repair2",
        "run_prefix": "2026-09-15_dsainet_gsf_v0_1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-15T09:05:02.549275+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-15T09:05:27.781937+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-15T09:05:50.784631+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b26777ae1d1f00e4065c04839b7e8fc774cd943e2ddf4b59dfbd8e36a22708bd",
                "execution_seconds": 21.262587308883667,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-15_dsainet_gsf_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 21.262587308883667
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-15T11:27:16.526901+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b26777ae1d1f00e4065c04839b7e8fc774cd943e2ddf4b59dfbd8e36a22708bd",
                "execution_seconds": 2419.265323638916,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-15_dsainet_gsf_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2419.265323638916
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-15T11:28:00.021050+00:00",
            "result": {
              "artifact_manifest_sha256": "87e720539edb38dae66b734dad5ba82247b269b24868771fa0bda793f590b720",
              "contract_sha256": "b26777ae1d1f00e4065c04839b7e8fc774cd943e2ddf4b59dfbd8e36a22708bd",
              "run_id": "2026-09-15_dsainet_gsf_v0_1_repair2-full-w1",
              "transaction_id": "2026-09-15_dsainet_gsf_v0_1_repair2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "PROMISING_INCOMPLETE",
        "reason": "positive average exists but complete formal stability/control gates do not all pass",
        "round_id": "dsainet-r01-cmcr-v0.1-recovery5"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1-recovery5_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsainet-r01-cmcr-v0.1-recovery5",
      "round_id": "dsainet-r01-cmcr-v0.1-recovery5",
      "run": {
        "bundle_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 8,
        "estimated_training_hours": 3.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 90,
        "recorded_at": "2026-09-16T16:46:12.750352+00:00",
        "recovery_of": "2026-09-16_dsainet_cmcr_v0_1_recovery4-full-w1",
        "round_id": "dsainet-r01-cmcr-v0.1-recovery5",
        "run_prefix": "2026-09-17_dsainet_cmcr_v0_1_recovery5",
        "runtime_estimate_basis": "recovery4 measured40-63 epochs in41min; shared throughput uncertainty",
        "source_results_from": "2026-09-16_dsainet_cmcr_v0_1_repair3-full-w1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-16T16:57:50.401663+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-16T16:57:51.346655+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T16:58:03.152753+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8df3b225e96f5f4f758d4a3589251207adaf76da657688ac1bcb69af0c4d1b3c",
                "execution_seconds": 9.894960641860962,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
                "transaction_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9.894960641860962
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T18:02:23.251172+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8df3b225e96f5f4f758d4a3589251207adaf76da657688ac1bcb69af0c4d1b3c",
                "execution_seconds": 3870.0863337516785,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
                "transaction_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3870.0863337516785
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-16T18:35:18.003825+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "8df3b225e96f5f4f758d4a3589251207adaf76da657688ac1bcb69af0c4d1b3c",
                "execution_seconds": 5302.678716421127,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
                "transaction_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 5302.678716421127
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-16T18:40:53.716749+00:00",
            "result": {
              "artifact_manifest_sha256": "d2c09e44c7cb51121eb66184d3dd0cdcb9a9a1444506d75debaaeff3f45da2ac",
              "contract_sha256": "8df3b225e96f5f4f758d4a3589251207adaf76da657688ac1bcb69af0c4d1b3c",
              "run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
              "transaction_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsa-ds01-v0.1-repair5"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair5_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-ds01-v0.1-repair5",
      "round_id": "dsa-ds01-v0.1-repair5",
      "run": {
        "bundle_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.222,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 58,
        "recorded_at": "2026-09-19T17:08:57.789130+00:00",
        "round_id": "dsa-ds01-v0.1-repair5",
        "run_prefix": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-19T17:09:43.124737+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-19T17:09:44.509831+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T17:09:54.199887+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "51578ec200bd5fdc120032f523c49b815465be23fd2a600fa6e28edd57008e85",
                "execution_seconds": 2.4519453048706055,
                "queue_seconds": 5.67011570930481,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1",
                "transaction_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-tx",
                "waiting_for_resources": true,
                "wall_seconds": 8.122061014175415
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-19T17:45:42.899602+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "51578ec200bd5fdc120032f523c49b815465be23fd2a600fa6e28edd57008e85",
                "execution_seconds": 1527.550166130066,
                "queue_seconds": 629.1784009933472,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-full-w1",
                "transaction_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2156.728567123413
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "overall paired delta is below the frozen minimum meaningful effect",
        "round_id": "dsa-pcr-v0.2-capacity1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-pcr-v0.2-capacity1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-pcr-v0.2-capacity1",
      "round_id": "dsa-pcr-v0.2-capacity1",
      "run": {
        "bundle_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 18,
        "recorded_at": "2026-09-21T07:40:20.905087+00:00",
        "round_id": "dsa-pcr-v0.2-capacity1",
        "run_prefix": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-21T07:40:53.851880+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-21T07:40:54.800759+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-21T07:41:40.414333+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8899c7ab9258e0a5d951a2c7f271557a5b0ce78a841372eee2f16c2b9e407aca",
                "execution_seconds": 5.047812223434448,
                "queue_seconds": 39.6263632774353,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
                "transaction_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 44.67417550086975
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-21T09:48:02.641798+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "8899c7ab9258e0a5d951a2c7f271557a5b0ce78a841372eee2f16c2b9e407aca",
                "execution_seconds": 6625.253738641739,
                "queue_seconds": 130.72524428367615,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
                "transaction_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 6755.978982925415
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-21T09:49:52.016944+00:00",
            "result": {
              "artifact_manifest_sha256": "940e84cfc7ace315eaa1555277fa2f45775de5189a79712c5c3fa6731e4fd67e",
              "contract_sha256": "8899c7ab9258e0a5d951a2c7f271557a5b0ce78a841372eee2f16c2b9e407aca",
              "run_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-full-w1",
              "transaction_id": "2026-09-21_dsainet_dsa_pcr_v0_2_capacity1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "leave_one_out_role": "descriptive_only",
        "reason": "at least one necessary frozen structural-utility gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-kshape-v0.1-repair5"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair5_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-kshape-v0.1-repair5",
      "round_id": "dsa-kshape-v0.1-repair5",
      "run": {
        "bundle_id": "2026-09-22_dsainet_kshape_v0_1-repair5-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 5.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 90,
        "recorded_at": "2026-09-22T06:36:23.250015+00:00",
        "round_id": "dsa-kshape-v0.1-repair5",
        "run_prefix": "2026-09-22_dsainet_kshape_v0_1-repair5",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-22T06:36:40.872059+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-22T06:36:41.868988+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T06:36:55.312256+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bbdff55c974acd51e65938eba4589d13d0a704530a5e2de28ad9f5cd4c208a9d",
                "execution_seconds": 11.51266622543335,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
                "transaction_id": "2026-09-22_dsainet_kshape_v0_1-repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 11.51266622543335
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T06:38:21.315852+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bbdff55c974acd51e65938eba4589d13d0a704530a5e2de28ad9f5cd4c208a9d",
                "execution_seconds": 50.99413013458252,
                "queue_seconds": 46.518431663513184,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
                "transaction_id": "2026-09-22_dsainet_kshape_v0_1-repair5-tx",
                "waiting_for_resources": true,
                "wall_seconds": 97.5125617980957
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T08:27:16.395781+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bbdff55c974acd51e65938eba4589d13d0a704530a5e2de28ad9f5cd4c208a9d",
                "execution_seconds": 3429.890813589096,
                "queue_seconds": 3200.3340656757355,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
                "transaction_id": "2026-09-22_dsainet_kshape_v0_1-repair5-tx",
                "waiting_for_resources": true,
                "wall_seconds": 6630.2248792648315
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T08:39:40.584670+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "bbdff55c974acd51e65938eba4589d13d0a704530a5e2de28ad9f5cd4c208a9d",
                "execution_seconds": 3633.9160237312317,
                "queue_seconds": 3687.4751822948456,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
                "transaction_id": "2026-09-22_dsainet_kshape_v0_1-repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 7321.391206026077
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-22T08:41:45.869087+00:00",
            "result": {
              "artifact_manifest_sha256": "823146ee33be8190a80a4de07574269957aa428498d2b57ab43cee7a7d4e8eb6",
              "contract_sha256": "bbdff55c974acd51e65938eba4589d13d0a704530a5e2de28ad9f5cd4c208a9d",
              "run_id": "2026-09-22_dsainet_kshape_v0_1-repair5-full-w1",
              "transaction_id": "2026-09-22_dsainet_kshape_v0_1-repair5-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "leave_one_out_role": "descriptive_only",
        "reason": "at least one necessary frozen structural-utility gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-pmt-v0.1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-pmt-v0.1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-pmt-v0.1",
      "round_id": "dsa-pmt-v0.1",
      "run": {
        "bundle_id": "2026-09-22_dsainet_pmt_v0_1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 5.278,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-09-22T09:45:42.602388+00:00",
        "round_id": "dsa-pmt-v0.1",
        "run_prefix": "2026-09-22_dsainet_pmt_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-22T09:46:24.667020+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-22T09:46:25.622753+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T09:46:46.718051+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 4.268972396850586,
                "queue_seconds": 15.503418207168579,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 19.772390604019165
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T14:07:02.532487+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 15222.809131622314,
                "queue_seconds": 413.15417098999023,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15635.963302612305
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T15:18:05.880705+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 19486.357476234436,
                "queue_seconds": 413.15417098999023,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19899.511647224426
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T16:04:11.700784+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 20256.631934404373,
                "queue_seconds": 413.15417098999023,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 20669.786105394363
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T16:21:14.518852+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 23275.087996006012,
                "queue_seconds": 413.15417098999023,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 23688.242166996002
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T17:12:14.874187+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 25291.457270383835,
                "queue_seconds": 1457.215149641037,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 26748.672420024872
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T06:18:15.519378+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 29833.432159423828,
                "queue_seconds": 4573.529294252396,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 34406.961453676224
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T06:29:20.375697+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 69958.36546278,
                "queue_seconds": 4617.012099981308,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 74575.3775627613
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T07:59:41.239674+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
                "execution_seconds": 70174.897772789,
                "queue_seconds": 4748.012846469879,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
                "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 74922.91061925888
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T08:07:25.266426+00:00",
            "result": {
              "artifact_manifest_sha256": "8a0e589832bf0fc542f3c82dcc330a40a2b751d5c4d44fb69c5bb5ba96dc6493",
              "contract_sha256": "13b79ee18ee0f9e7da8cb136253b1942f1af2cb7d8b0fb1c61176de6ecc91f56",
              "run_id": "2026-09-22_dsainet_pmt_v0_1-full-w1",
              "transaction_id": "2026-09-22_dsainet_pmt_v0_1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "DIAGNOSTIC_SUPPORT",
        "native_complementarity_use": "not_identified",
        "original_PMT_decision": "NO_SIGNAL",
        "reason": "Frozen G1/G2, harm and null gates; G3 mismatch sensitivity is descriptive only.",
        "round_id": "dsa-aec-v0.1-repair1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-aec-v0.1-repair1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-aec-v0.1-repair1",
      "round_id": "dsa-aec-v0.1-repair1",
      "run": {
        "bundle_id": "2026-09-23_dsainet_aec_v0_1_repair1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.278,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 77,
        "recorded_at": "2026-09-23T13:53:44.621659+00:00",
        "round_id": "dsa-aec-v0.1-repair1",
        "run_prefix": "2026-09-23_dsainet_aec_v0_1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T13:54:13.329693+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T13:54:14.643830+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T13:54:43.431022+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b52f4539273532e60293780fea8078c105541df022dd0ce5d56ecf030b8ed240",
                "execution_seconds": 26.98558235168457,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-23_dsainet_aec_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 26.98558235168457
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T15:41:16.780861+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b52f4539273532e60293780fea8078c105541df022dd0ce5d56ecf030b8ed240",
                "execution_seconds": 6420.553535461426,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-23_dsainet_aec_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 6420.553535461426
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:17:08.634687+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b52f4539273532e60293780fea8078c105541df022dd0ce5d56ecf030b8ed240",
                "execution_seconds": 8572.487836837769,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-23_dsainet_aec_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8572.487836837769
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:42:24.487895+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b52f4539273532e60293780fea8078c105541df022dd0ce5d56ecf030b8ed240",
                "execution_seconds": 8693.781769514084,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-23_dsainet_aec_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8693.781769514084
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T16:50:53.168181+00:00",
            "result": {
              "artifact_manifest_sha256": "7ebf33f164910becff0d015122629e7d3cc2cb71b3b568080df17971ae11d0d2",
              "contract_sha256": "b52f4539273532e60293780fea8078c105541df022dd0ce5d56ecf030b8ed240",
              "run_id": "2026-09-23_dsainet_aec_v0_1_repair1-full-w1",
              "transaction_id": "2026-09-23_dsainet_aec_v0_1_repair1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "native_tail_use": "not_identified",
        "original_PMT_decision": "NO_SIGNAL",
        "reason": "FUT G1/G2, harm and null gates under the frozen representation-tail protocol.",
        "round_id": "dsa-fut-v0.1-repair5"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-fut-v0.1-repair5_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-fut-v0.1-repair5",
      "round_id": "dsa-fut-v0.1-repair5",
      "run": {
        "bundle_id": "2026-09-25_dsainet_fut_v0_1_repair5-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.097,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 433,
        "recorded_at": "2026-09-25T02:28:04.035241+00:00",
        "round_id": "dsa-fut-v0.1-repair5",
        "run_prefix": "2026-09-25_dsainet_fut_v0_1_repair5",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T02:28:44.490371+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T02:28:46.893556+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T02:29:03.771093+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "adcf3d2865f994d278ae8b43b51a64bf93b19bf5606684c9fc7ebcaa86824535",
                "execution_seconds": 11.175865173339844,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
                "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 11.175865173339844
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T02:30:28.950014+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "adcf3d2865f994d278ae8b43b51a64bf93b19bf5606684c9fc7ebcaa86824535",
                "execution_seconds": 96.35666918754578,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
                "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 96.35666918754578
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T04:11:11.490815+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "adcf3d2865f994d278ae8b43b51a64bf93b19bf5606684c9fc7ebcaa86824535",
                "execution_seconds": 1428.861643075943,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
                "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1428.861643075943
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-25T04:16:41.306277+00:00",
            "result": {
              "artifact_manifest_sha256": "5ec5bdeba4e9bad8dc3dc0bd218f4dbb5943b33e50b8b133378f6621d4d55592",
              "contract_sha256": "adcf3d2865f994d278ae8b43b51a64bf93b19bf5606684c9fc7ebcaa86824535",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair5-full-w1",
              "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair5-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "C0-B0",
          "C0-S0",
          "C0-N0"
        ],
        "incomplete_reason": null,
        "leave_one_out_role": "required_gate_and_report",
        "namespace": "ael",
        "negative_objects_stopped": {
          "C0-B0": "stopped_negative_gate",
          "C0-N0": "stopped_negative_gate",
          "C0-S0": "stopped_negative_gate"
        },
        "reason": "H1 necessary gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-ael-v0.1-repair2"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-ael-v0.1-repair2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-ael-v0.1-repair2",
      "round_id": "dsa-ael-v0.1-repair2",
      "run": {
        "bundle_id": "2026-09-25_dsainet_ael_v0_1_repair2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 14.846,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-09-25T13:49:23.389700+00:00",
        "round_id": "dsa-ael-v0.1-repair2",
        "run_prefix": "2026-09-25_dsainet_ael_v0_1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T13:52:22.825365+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T13:52:25.364379+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T13:53:03.843675+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "de788fc7475ddffe13ffc4f3e743f350f686d6bed23ff45fe0bcf59bfffa56b4",
                "execution_seconds": 37.03207540512085,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-25_dsainet_ael_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 37.03207540512085
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T14:53:27.444185+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "de788fc7475ddffe13ffc4f3e743f350f686d6bed23ff45fe0bcf59bfffa56b4",
                "execution_seconds": 1647.8014013767242,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_ael_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-25_dsainet_ael_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1647.8014013767242
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "capacity_caveat": true,
        "claim_status": "no_paper_claim",
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "leave_one_out_role": "primary_required_gate",
        "namespace": "bsu",
        "reason": "both constituent-retention gates required; secondary descriptive only",
        "research_qualification": "INSUFFICIENT_DUAL_RETENTION_SUPPORT",
        "round_id": "dsa-bsu-v0.1-repair3"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair3_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-bsu-v0.1-repair3",
      "round_id": "dsa-bsu-v0.1-repair3",
      "run": {
        "bundle_id": "2026-09-27_dsainet_bsu_v0_1_repair3-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.654,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-09-27T02:40:18.526477+00:00",
        "round_id": "dsa-bsu-v0.1-repair3",
        "run_prefix": "2026-09-27_dsainet_bsu_v0_1_repair3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T02:41:16.644690+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T02:41:19.790665+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T02:41:35.315532+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "91d73e6fa7bd01b64af1ea72ff67ae70d2aaef6370077e90dd122befe8b43016",
                "execution_seconds": 13.82350468635559,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
                "transaction_id": "2026-09-27_dsainet_bsu_v0_1_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.82350468635559
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T07:55:46.546087+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "91d73e6fa7bd01b64af1ea72ff67ae70d2aaef6370077e90dd122befe8b43016",
                "execution_seconds": 228.4847333431244,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
                "transaction_id": "2026-09-27_dsainet_bsu_v0_1_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 228.4847333431244
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-27T08:13:20.061798+00:00",
            "result": {
              "artifact_manifest_sha256": "24b839c72149c48e879cc48f4a5ab1d3138fa52f0f75a8cfb1ba3a67174ae5fb",
              "contract_sha256": "91d73e6fa7bd01b64af1ea72ff67ae70d2aaef6370077e90dd122befe8b43016",
              "run_id": "2026-09-27_dsainet_bsu_v0_1_repair3-full-w1",
              "transaction_id": "2026-09-27_dsainet_bsu_v0_1_repair3-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "failed_comparisons": [
          "G_C",
          "I"
        ],
        "interpretation_boundary": "architecture-conditional, exposed-source diagnostic screen",
        "leave_one_out_role": "required_gate_and_report",
        "namespace": "ces",
        "negative_objects_stopped": {
          "G_C": "stopped_negative_gate",
          "I": "stopped_negative_gate"
        },
        "reason": "one or more necessary CES diagnostic gates failed",
        "research_qualification": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "round_id": "dsa-ces-v0.1-repair3"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair3_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-ces-v0.1-repair3",
      "round_id": "dsa-ces-v0.1-repair3",
      "run": {
        "bundle_id": "2026-09-28_dsainet_ces_v0_1_repair3-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.408,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-28T07:16:55.507330+00:00",
        "round_id": "dsa-ces-v0.1-repair3",
        "run_prefix": "2026-09-28_dsainet_ces_v0_1_repair3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-28T07:18:25.897071+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-28T07:18:27.847472+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T07:19:11.088179+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "212546ccd97a37119e1767a12aed09bb5ba24429bd5d112608319e16b099725d",
                "execution_seconds": 41.25083613395691,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
                "transaction_id": "2026-09-28_dsainet_ces_v0_1_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 41.25083613395691
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T08:39:16.672472+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "212546ccd97a37119e1767a12aed09bb5ba24429bd5d112608319e16b099725d",
                "execution_seconds": 825.9835786819458,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
                "transaction_id": "2026-09-28_dsainet_ces_v0_1_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 825.9835786819458
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-28T08:57:56.073435+00:00",
            "result": {
              "artifact_manifest_sha256": "80db8802967e0b1dc2f28ffe2082cd3f5860cc89d04a22feaddd104a4559b499",
              "contract_sha256": "212546ccd97a37119e1767a12aed09bb5ba24429bd5d112608319e16b099725d",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair3-full-w1",
              "transaction_id": "2026-09-28_dsainet_ces_v0_1_repair3-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "EVALUATION_COMPLETE",
        "evaluation_plan": {
          "path": "ai4s/programs/dsainet/research/dsa-pfc-v0.1/EVALUATION_PLAN.yaml",
          "scope_id": "bnci001-p0-b0-five-seed-frozen-replication",
          "sha256": "1e3d821c970a1f836c3f0d6eeeb63e8e28fe876e5ac593ba73e4a3f9dfed6e22"
        },
        "reason": "Complete90 target evaluations,54 new fits,36 reused checkpoints; independent predictions and frozen summary verified. Performance gate is reported separately from completion.",
        "round_id": "dsa-pfc-v0.1-r1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-pfc-v0.1-r1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-pfc-v0.1-r1",
      "round_id": "dsa-pfc-v0.1-r1",
      "run": {
        "bundle_id": "2026-09-28_dsainet_pfc_v0_1_r1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 22.972,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 92,
        "recorded_at": "2026-09-28T11:21:04.167133+00:00",
        "round_id": "dsa-pfc-v0.1-r1",
        "run_prefix": "2026-09-28_dsainet_pfc_v0_1_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-28T11:21:29.189919+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-28T11:22:39.570988+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T11:22:59.650199+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "284b8751b7ed17024ae706cc2dc02de0ba7ab096692da405351fbfb3dabdf8b9",
                "execution_seconds": 7.94434928894043,
                "queue_seconds": 9.6464204788208,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
                "transaction_id": "2026-09-28_dsainet_pfc_v0_1_r1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 17.59076976776123
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T16:06:55.522926+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "284b8751b7ed17024ae706cc2dc02de0ba7ab096692da405351fbfb3dabdf8b9",
                "execution_seconds": 8506.143109560013,
                "queue_seconds": 4232.593663692474,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
                "transaction_id": "2026-09-28_dsainet_pfc_v0_1_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12738.736773252487
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-28T16:08:30.602557+00:00",
            "result": {
              "artifact_manifest_sha256": "c8cb637502c03e8b79666e8e0f165de640b122eecb82638afeeec19ef62f2e5e",
              "contract_sha256": "284b8751b7ed17024ae706cc2dc02de0ba7ab096692da405351fbfb3dabdf8b9",
              "run_id": "2026-09-28_dsainet_pfc_v0_1_r1-full-w1",
              "transaction_id": "2026-09-28_dsainet_pfc_v0_1_r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "MIXED_UNCONFIRMED",
        "reason": "Complete verified factorial analysis; no stable attribution or positive replacement interaction under all applicable frozen gates; retain historical P0 candidate.",
        "recorded_at": "2026-09-30T04:36:39.133007+00:00",
        "round_id": "dsa-sid-v0.1-repair1b",
        "scientific_completion": true
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-sid-v0.1-repair1/DECISION.json",
      "evidence_id": "AI4S-DSAINET-dsa-sid-v0.1-repair1b",
      "round_id": "dsa-sid-v0.1-repair1b",
      "run": {
        "bundle_id": "2026-09-30_dsainet_sid_v0_1_repair1b-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 253,
        "recorded_at": "2026-09-30T04:19:36.159334+00:00",
        "round_id": "dsa-sid-v0.1-repair1b",
        "run_prefix": "2026-09-30_dsainet_sid_v0_1_repair1b",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-30T04:19:52.589431+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-30T04:20:42.194796+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-30T04:21:00.034838+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "preflight",
              "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "eebd3c51465bdd1d21ebabbd693128a001b10483ece7202286f611f9e775dedf",
                "execution_seconds": 15.860194206237793,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1",
                "transaction_id": "2026-09-30_dsainet_sid_v0_1_repair1b-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15.860194206237793
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-30T04:23:11.315287+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "eebd3c51465bdd1d21ebabbd693128a001b10483ece7202286f611f9e775dedf",
                "execution_seconds": 129.94760656356812,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1",
                "transaction_id": "2026-09-30_dsainet_sid_v0_1_repair1b-tx",
                "waiting_for_resources": false,
                "wall_seconds": 129.94760656356812
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-30T04:25:29.200495+00:00",
            "result": {
              "artifact_manifest_sha256": "ba38b7fdeff45217ccf77177684fae5d5292be724f570144727baf4d254a7a00",
              "contract_sha256": "eebd3c51465bdd1d21ebabbd693128a001b10483ece7202286f611f9e775dedf",
              "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1",
              "transaction_id": "2026-09-30_dsainet_sid_v0_1_repair1b-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "EVALUATION_COMPLETE",
        "evaluation_plan": {
          "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair3/EVALUATION_PLAN_SPLIT.yaml",
          "scope_id": "physionet-all-subjects-five-seed-loso",
          "sha256": "f28af045ea76b1059713ecca3416386652d6ee1af2548d4b00d8c86de35634d1"
        },
        "reason": "Complete PhysioNet1090 target evaluations and545 paired cells; original-runtime frozen prediction replay passed.",
        "round_id": "dsa-pfc-xds-v0.1-physionet-target-resume16"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-target-resume16_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-pfc-xds-v0.1-physionet-target-resume16",
      "round_id": "dsa-pfc-xds-v0.1-physionet-target-resume16",
      "run": {
        "bundle_id": "2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16-bundle",
        "contract_metadata": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-target-resume16/REMOTE_CONTRACT.json",
        "contract_sha256": "11552934fda76a12fb4c4aa281733914f6dd84de4b478ff4c19105f1461024ca",
        "dispatch_status": "REMOTE_EVALUATIONS_COMPLETE_CLOSURE_PENDING",
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "latest_observation": {
          "closure_files": [
            "performance_summary.json"
          ],
          "dispatch": {
            "added_budget_seconds": 0,
            "automatic_training_retries": 0,
            "contract_sha256": "11552934fda76a12fb4c4aa281733914f6dd84de4b478ff4c19105f1461024ca",
            "fit_commitment_mib": 2048,
            "gpu_ids": [
              0,
              1,
              3,
              4,
              5,
              6,
              7,
              8,
              9
            ],
            "new_technical_fits": 0,
            "pid": "[REDACTED_MACHINE]",
            "public_reserve_mib": 0,
            "remaining_execution_seconds": 12641,
            "remaining_formal_fits": 0,
            "remaining_target_evaluations": 3,
            "reused_formal_fits": 1090,
            "reused_target_evaluations": 1087,
            "run_id": "2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16-full-w1",
            "status": "SUBMITTED_NOT_YET_VERIFIED"
          },
          "fit_complete": 1090,
          "nodes": {
            "full": {
              "status": "RUNNING"
            },
            "smoke": {
              "status": "PASS"
            }
          },
          "query_time": "2026-10-08T21:03:03.497699+08:00",
          "remaining_execution_hours": 3.395971520675553,
          "scheduler": {
            "completed": 3,
            "failed": 0,
            "pending": 0,
            "running": 0,
            "updated_at": "2026-10-08T13:01:52.493887+00:00"
          },
          "scientific_intake": false,
          "tail_callback_reports": [
            {
              "callback_completed_under_lock": true,
              "commitment_mib": 2048,
              "gpu": 4,
              "peer_pending_mib": 881,
              "required_mib": 2778,
              "status": "READY",
              "task_id": "physionet_P0_s1_t86",
              "wait_seconds": 12.68988761678338
            },
            {
              "callback_completed_under_lock": true,
              "commitment_mib": 2048,
              "gpu": 4,
              "peer_pending_mib": 0,
              "required_mib": 1897,
              "status": "READY",
              "task_id": "physionet_P0_s2_t86",
              "wait_seconds": 0.23641838133335114
            },
            {
              "callback_completed_under_lock": true,
              "commitment_mib": 2048,
              "gpu": 4,
              "peer_pending_mib": 791,
              "required_mib": 2688,
              "status": "READY",
              "task_id": "physionet_P0_s3_t86",
              "wait_seconds": 6.4072143994271755
            }
          ],
          "target_closed_total": 1090,
          "target_receipts": 1090
        },
        "planned_units": 1090,
        "remaining_formal_fits_at_launch": 0,
        "remaining_target_evaluations_at_launch": 3,
        "reused_formal_fits": 1090,
        "reused_target_evaluations": 1087,
        "round_id": "dsa-pfc-xds-v0.1-physionet-target-resume16",
        "run_id": "2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16-full-w1",
        "run_prefix": "2026-10-08_dsainet_pfc_xds_v0_1_physionet_target_resume16",
        "scientific_intake": false
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "P0-B0",
          "P0-S0",
          "P0-N0"
        ],
        "incomplete_reason": null,
        "leave_one_out_role": "descriptive_only",
        "namespace": "rns",
        "negative_objects_stopped": {
          "P0-B0": "stopped_negative_utility_gate",
          "P0-S0": "stopped_negative_utility_gate"
        },
        "reason": "native utility or risk gate failed",
        "research_qualification": "NO_SIGNAL",
        "round_id": "dsa-rns-v0.1-audit-resume2"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-rns-v0.1-audit-resume2",
      "round_id": "dsa-rns-v0.1-audit-resume2",
      "run": {
        "bundle_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.523,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-10-11T05:26:51.512570+00:00",
        "round_id": "dsa-rns-v0.1-audit-resume2",
        "run_prefix": "2026-10-11_dsainet_rns_v0_1_audit_resume2",
        "transaction_operations": [
          {
            "operation": "launch",
            "recorded_at": "2026-10-11T05:29:14.756270+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-11T05:29:25.579656+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "94e987737a5edf497afb693900f20b107d3da495af456ed7ee1ea843fffc0cfd",
                "execution_seconds": 8.285282135009766,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
                "transaction_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8.285282135009766
              }
            }
          },
          {
            "observation_host": "[REDACTED_MACHINE]",
            "operation": "probe",
            "recorded_at": "2026-10-11T05:29:28.732052+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "contract_sha256": "94e987737a5edf497afb693900f20b107d3da495af456ed7ee1ea843fffc0cfd",
              "node_id": "screen",
              "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
              "status": "RUNNING",
              "transaction_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-tx"
            },
            "source": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume2/LATEST_STATUS_SNAPSHOT.json"
          },
          {
            "observation_host": "[REDACTED_MACHINE]",
            "operation": "probe",
            "recorded_at": "2026-10-11T05:30:14.310565+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "contract_sha256": "94e987737a5edf497afb693900f20b107d3da495af456ed7ee1ea843fffc0cfd",
              "node_id": "screen",
              "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
              "status": "RUNNING",
              "transaction_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-tx"
            },
            "source": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume2/LATEST_STATUS_SNAPSHOT.json"
          },
          {
            "observation_host": "[REDACTED_MACHINE]",
            "operation": "probe",
            "recorded_at": "2026-10-11T09:44:01.293447+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "contract_sha256": "94e987737a5edf497afb693900f20b107d3da495af456ed7ee1ea843fffc0cfd",
              "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "transaction_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-tx"
            },
            "source": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume2/LATEST_STATUS_SNAPSHOT.json"
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-11T09:48:27.481820+00:00",
            "result": {
              "artifact_manifest_sha256": "f7bf368f6547f3c47593c41e6cf6d533dc8ce3a08854b7b3d309b8e7ac6fb7bd",
              "contract_sha256": "94e987737a5edf497afb693900f20b107d3da495af456ed7ee1ea843fffc0cfd",
              "run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-full-w1",
              "transaction_id": "2026-10-11_dsainet_rns_v0_1_audit_resume2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "P0-B0",
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "incomplete_reason": null,
        "leave_one_out_role": "descriptive_only",
        "namespace": "cru",
        "negative_objects_stopped": {
          "P0-B0": "stopped_negative_utility_gate"
        },
        "next_design": null,
        "reason": "native utility or subject risk gate failed",
        "research_qualification": "NO_SIGNAL",
        "risk_failed_comparisons": [],
        "round_id": "dsa-cru-v0.1-resume2",
        "stopped": true,
        "target_evaluation": false
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-cru-v0.1-resume2_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-cru-v0.1-resume2",
      "round_id": "dsa-cru-v0.1-resume2",
      "run": {
        "bundle_id": "2026-10-12_dsainet_cru_v0_1_resume2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 5.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-10-12T05:01:17.502754+00:00",
        "round_id": "dsa-cru-v0.1-resume2",
        "run_prefix": "2026-10-12_dsainet_cru_v0_1_resume2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-12T05:02:06.971294+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-12T05:02:09.392758+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-12T05:02:23.221375+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "3d65adbe7cf3ec041667de1697643ad61e0db780ce5128fd99612efd606c2503",
                "execution_seconds": 8.212976217269897,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
                "transaction_id": "2026-10-12_dsainet_cru_v0_1_resume2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8.212976217269897
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-12T05:03:32.927005+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "3d65adbe7cf3ec041667de1697643ad61e0db780ce5128fd99612efd606c2503",
                "execution_seconds": 52.327181577682495,
                "queue_seconds": 25.58627438545227,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
                "transaction_id": "2026-10-12_dsainet_cru_v0_1_resume2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 77.91345596313477
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-12T06:49:29.647959+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "3d65adbe7cf3ec041667de1697643ad61e0db780ce5128fd99612efd606c2503",
                "execution_seconds": 3127.4310269355774,
                "queue_seconds": 493.1737926006317,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
                "transaction_id": "2026-10-12_dsainet_cru_v0_1_resume2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3620.604819536209
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-12T06:53:53.607653+00:00",
            "result": {
              "artifact_manifest_sha256": "bee25c53764d87c8234d9771f25c8489f680fce728a726a0ca85f22fa6f27798",
              "contract_sha256": "3d65adbe7cf3ec041667de1697643ad61e0db780ce5128fd99612efd606c2503",
              "run_id": "2026-10-12_dsainet_cru_v0_1_resume2-full-w1",
              "transaction_id": "2026-10-12_dsainet_cru_v0_1_resume2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "failed_comparisons": [
          "P0-B0",
          "P0-S0",
          "P0-N0"
        ],
        "namespace": "rcd",
        "next_run_automatic": false,
        "primary_comparison": "P0-B0",
        "research_qualification": "NO_SIGNAL",
        "risk_failed_subjects": [
          2,
          4,
          5,
          7
        ],
        "round_id": "dsa-rcd-v0.1-resume3",
        "stopped": true,
        "target_evaluation": false
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-resume3_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-rcd-v0.1-resume3",
      "round_id": "dsa-rcd-v0.1-resume3",
      "run": {
        "bundle_id": "2026-10-14_dsainet_rcd_v0_1_resume3-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 26.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-10-14T13:59:46.876332+00:00",
        "round_id": "dsa-rcd-v0.1-resume3",
        "run_prefix": "2026-10-14_dsainet_rcd_v0_1_resume3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-14T14:00:30.497874+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-14_dsainet_rcd_v0_1_resume3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-14T14:00:33.548502+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-14_dsainet_rcd_v0_1_resume3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-14T14:01:05.096336+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-14_dsainet_rcd_v0_1_resume3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "155e3f431195919625e8c652193190fccde90fbd188d47c15a7a38bb49f47950",
                "execution_seconds": 24.976973056793213,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-14_dsainet_rcd_v0_1_resume3-full-w1",
                "transaction_id": "2026-10-14_dsainet_rcd_v0_1_resume3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 24.976973056793213
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-15T04:46:46.962790+00:00",
            "result": {
              "artifact_manifest_sha256": "8538e3fc4a273cf307b19377a58e139f4dfcf978bf51823d82d2fe2e3dbd6d4a",
              "contract_sha256": "155e3f431195919625e8c652193190fccde90fbd188d47c15a7a38bb49f47950",
              "run_id": "2026-10-14_dsainet_rcd_v0_1_resume3-full-w1",
              "transaction_id": "2026-10-14_dsainet_rcd_v0_1_resume3-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "reason": "classified by frozen DSA-ORD Stage-A analyzer gates",
        "round_id": "dsa-ord-v0.1-stageA-repair6"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-ord-v0.1-stageA-repair6_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-ord-v0.1-stageA-repair6",
      "round_id": "dsa-ord-v0.1-stageA-repair6",
      "run": {
        "bundle_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "formal_audits_to_run": 1,
        "formal_fits_to_run": 0,
        "planned_units": 57,
        "recorded_at": "2026-10-17T11:30:12.478685+00:00",
        "repair_kind": "completed_audit_recovery",
        "replaces_failed_run": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
        "reused_formal_audits": 53,
        "reused_formal_fits": 54,
        "round_id": "dsa-ord-v0.1-stageA-repair6",
        "run_prefix": "2026-10-17_dsainet_ord_v0_1_stageA_repair6",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-17T11:30:49.825115+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_verified_files": 2187,
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
              "transport": "exclusive_verified_source_copy_and_delta"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-17T11:31:07.278414+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T11:32:22.634271+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f717c81959be42ded8d6364a397bb7257694de99c232807767c6fbf4b501bcac",
                "execution_seconds": 59.43681073188782,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
                "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-tx",
                "waiting_for_resources": false,
                "wall_seconds": 59.43681073188782
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T11:33:45.724349+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "f717c81959be42ded8d6364a397bb7257694de99c232807767c6fbf4b501bcac",
                "execution_seconds": 73.49517369270325,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
                "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-tx",
                "waiting_for_resources": false,
                "wall_seconds": 73.49517369270325
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-17T11:35:00.843180+00:00",
            "result": {
              "artifact_manifest_sha256": "f80e8ec665f31be48f04ad783f128eda3811e68c94cf1ebd24f52b997c2dd939",
              "contract_sha256": "f717c81959be42ded8d6364a397bb7257694de99c232807767c6fbf4b501bcac",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-full-w1",
              "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair6-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "F_auto_start": false,
        "analysis_input_sha256": "95698d2f7448e3ddcc0ff034a1acc56e2313847328f2ce6ddabeb9f43bbc0f4e",
        "analysis_repair": {
          "manifest": "ai4s/programs/dsainet/research/dsa-nfi-v0.1/analysis_repair/MANIFEST.json",
          "scope": "completion-interface-only; frozen science and raw artifacts unchanged",
          "sha256": "85626b6ce4ba399c34d5e8efa2618904abcd7c1e56648195bde55526553c210d"
        },
        "automatic_follow_up": false,
        "decision": "NFI_D_DIAGNOSTIC_RECORDED",
        "ordered_d_disposition": {
          "F_auto_start": false,
          "classification": "D_ATTRIBUTION_UNRESOLVED_METRIC_OR_SEED_CONFLICT",
          "stop_after_D": true,
          "trigger": {
            "contrast": "q",
            "nll_conflict": false,
            "seed_reversal": true
          }
        },
        "role": "diagnostic_observation",
        "round_id": "dsa-nfi-v0.1-D",
        "stop_after_D": true
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-nfi-v0.1-D_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-nfi-v0.1-D",
      "round_id": "dsa-nfi-v0.1-D",
      "run": {
        "bundle_id": "2026-10-17_dsainet_nfi_v0_1_D-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 70.551,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-10-17T12:51:51.301653+00:00",
        "round_id": "dsa-nfi-v0.1-D",
        "run_prefix": "2026-10-17_dsainet_nfi_v0_1_D",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-17T12:52:37.860235+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-17T12:52:40.863270+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T12:52:57.019734+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e54ff5968bb342e2a9dc623150c2655d666da1452e166996f622ee9ae2afb9e9",
                "execution_seconds": 13.334602355957031,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
                "transaction_id": "2026-10-17_dsainet_nfi_v0_1_D-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.334602355957031
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T12:55:11.941974+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e54ff5968bb342e2a9dc623150c2655d666da1452e166996f622ee9ae2afb9e9",
                "execution_seconds": 148.45320415496826,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
                "transaction_id": "2026-10-17_dsainet_nfi_v0_1_D-tx",
                "waiting_for_resources": false,
                "wall_seconds": 148.45320415496826
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T03:03:44.185210+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "e54ff5968bb342e2a9dc623150c2655d666da1452e166996f622ee9ae2afb9e9",
                "execution_seconds": 8792.122475862503,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_nfi_v0_1_D-full-w1",
                "transaction_id": "2026-10-17_dsainet_nfi_v0_1_D-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8792.122475862503
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "K_auto_start": false,
        "analysis_input_sha256": "aef044dca837ac6c7d6a4ecac189efbf9203edc21f62bc88b1ebf1b03c89af3e",
        "automatic_follow_up": false,
        "decision": "NFI_Q_DIAGNOSTIC_RECORDED",
        "q_disposition": {
          "continue_worth_verifying": [
            "Q2-Q1"
          ],
          "contrasts": {
            "Q1-Q0": "SMALL_OR_UNSTABLE",
            "Q2-Q1": "CONTINUE_WORTH_VERIFYING",
            "Q3-Q2": "SMALL_OR_UNSTABLE",
            "Q4-Q3": "SMALL_OR_UNSTABLE"
          },
          "diagnostic_only": true,
          "small_or_unstable": [
            "Q1-Q0",
            "Q3-Q2",
            "Q4-Q3"
          ]
        },
        "role": "diagnostic_observation",
        "round_id": "dsa-nfi-v0.2-Q",
        "stop_after_Q": true
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-nfi-v0.2-Q_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-nfi-v0.2-Q",
      "round_id": "dsa-nfi-v0.2-Q",
      "run": {
        "bundle_id": "2026-10-18_dsainet_nfi_v0_2_Q-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 46.427,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 98,
        "recorded_at": "2026-10-18T05:27:59.871279+00:00",
        "round_id": "dsa-nfi-v0.2-Q",
        "run_prefix": "2026-10-18_dsainet_nfi_v0_2_Q",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-18T05:29:06.188952+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-18T05:29:09.445178+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T05:29:30.966161+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e3796326eaad981c97c7a24b95f936849cc42fc3d729cba4f69642db3a43068b",
                "execution_seconds": 18.697433710098267,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1",
                "transaction_id": "2026-10-18_dsainet_nfi_v0_2_Q-tx",
                "waiting_for_resources": false,
                "wall_seconds": 18.697433710098267
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T08:34:53.058788+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "e3796326eaad981c97c7a24b95f936849cc42fc3d729cba4f69642db3a43068b",
                "execution_seconds": 6121.984403133392,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_dsainet_nfi_v0_2_Q-full-w1",
                "transaction_id": "2026-10-18_dsainet_nfi_v0_2_Q-tx",
                "waiting_for_resources": false,
                "wall_seconds": 6121.984403133392
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "analysis_input_sha256": "2d2ac38afc3f615e160997d5eec8b7c6c060d58f9255a1bde893c6de12959d70",
        "automatic_follow_up": false,
        "decision": "LC1_SCREEN_RECORDED",
        "lc1_disposition": {
          "automatic_follow_up": false,
          "diagnostic_only": true,
          "exposure_pass": true,
          "functional_direction_consistent": false,
          "lc2_authorized": false,
          "lc2_eligible_for_separate_authorization": false,
          "same_bias_pass": {
            "HH": false,
            "SS": false
          },
          "utility_pass": false
        },
        "lc2_authorized": false,
        "role": "diagnostic_observation",
        "round_id": "dsa-lcb-v0.1-LC1"
      },
      "decision_record": "ai4s/programs/dsainet/research/dsa-lcb-v0.1-LC1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-dsa-lcb-v0.1-LC1",
      "round_id": "dsa-lcb-v0.1-LC1",
      "run": {
        "bundle_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 46.254,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 141,
        "recorded_at": "2026-10-18T11:36:46.316556+00:00",
        "round_id": "dsa-lcb-v0.1-LC1",
        "run_prefix": "2026-10-18_dsainet_lcb_v0_1_LC1r2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-18T11:38:16.606545+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-18T11:38:22.015498+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T11:38:43.792449+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "29024b327b5066e6d2e431132b85dec1de1592095bed0a3cf87222aa1e81d2c7",
                "execution_seconds": 19.387455463409424,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
                "transaction_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19.387455463409424
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T11:42:54.385307+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "29024b327b5066e6d2e431132b85dec1de1592095bed0a3cf87222aa1e81d2c7",
                "execution_seconds": 270.00545597076416,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
                "transaction_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 270.00545597076416
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T17:42:48.166394+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "29024b327b5066e6d2e431132b85dec1de1592095bed0a3cf87222aa1e81d2c7",
                "execution_seconds": 21211.915272951126,
                "queue_seconds": 652.987076997757,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
                "transaction_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 21864.902349948883
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T02:39:08.341612+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "29024b327b5066e6d2e431132b85dec1de1592095bed0a3cf87222aa1e81d2c7",
                "execution_seconds": 22522.801649808884,
                "queue_seconds": 652.987076997757,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
                "transaction_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 23175.78872680664
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-19T02:53:18.747231+00:00",
            "result": {
              "artifact_manifest_sha256": "4b65ba49e23d1971783027d728cac3ce13b2b816d6a21a2fbda9aa3d31d8aa86",
              "contract_sha256": "29024b327b5066e6d2e431132b85dec1de1592095bed0a3cf87222aa1e81d2c7",
              "run_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-full-w1",
              "transaction_id": "2026-10-18_dsainet_lcb_v0_1_LC1r2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "automatic_follow_up": false,
        "claim_created": false,
        "decision": "NO_SIGNAL",
        "exact_rule_kind": "P0_CUE_R1_INVESTMENT_RULE_V1",
        "frozen_gate_results": {
          "P0_vs_B0": {
            "both_seed_directions": true,
            "every_subject_mean_ge_minus3pp": false,
            "mean_accuracy": true,
            "mean_raw_nll_nonincrease": false,
            "pass": false
          },
          "P0_vs_S0": {
            "both_seed_directions": true,
            "every_subject_mean_ge_minus3pp": false,
            "mean_accuracy": true,
            "mean_raw_nll_nonincrease": false,
            "pass": false
          }
        },
        "reason": "Both exact frozen net-utility contrasts must pass; raw-NLL and subject-harm gates fail despite positive mean ACC.",
        "round_id": "p0-cue-r1-costcal-r1",
        "scope": "Exact P0-CUE-R1 current source6/select1/audit1 cue4 development protocol; not all P0 variants or general mechanisms."
      },
      "decision_record": "ai4s/programs/dsainet/research/p0-cue-r1-costcal-r1_decision.yaml",
      "evidence_id": "AI4S-DSAINET-p0-cue-r1-costcal-r1",
      "round_id": "p0-cue-r1-costcal-r1",
      "run": {
        "bundle_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 64.974,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-10-23T18:30:41.320993+00:00",
        "round_id": "p0-cue-r1-costcal-r1",
        "run_prefix": "2026-10-24_dsainet_p0_cue_r1_costcal_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-23T18:34:06.718184+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-23T18:34:08.899929+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-23T18:34:25.883997+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4c85683a4e5e4732d4f52a7d71fb3d89afbf6fdaa73106c2d2ada33371677a59",
                "execution_seconds": 14.687018394470215,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
                "transaction_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 14.687018394470215
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-23T18:36:49.048257+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4c85683a4e5e4732d4f52a7d71fb3d89afbf6fdaa73106c2d2ada33371677a59",
                "execution_seconds": 157.85014653205872,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
                "transaction_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 157.85014653205872
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-24T03:58:52.661204+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "4c85683a4e5e4732d4f52a7d71fb3d89afbf6fdaa73106c2d2ada33371677a59",
                "execution_seconds": 11131.197738647461,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
                "transaction_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 11131.197738647461
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-24T04:04:14.709491+00:00",
            "result": {
              "artifact_manifest_sha256": "122b7739c8f0f2309c13e23867a589b0e939c06146fe0562e914f69d93144729",
              "contract_sha256": "4c85683a4e5e4732d4f52a7d71fb3d89afbf6fdaa73106c2d2ada33371677a59",
              "run_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-full-w1",
              "transaction_id": "2026-10-24_dsainet_p0_cue_r1_costcal_r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "automatic_follow_up": false,
        "claim_created": false,
        "decision": "NO_SIGNAL",
        "exact_rule_kind": "P0_CUE_R2_LS010_INVESTMENT_V1",
        "frozen_gate_results": {
          "P0_LS_vs_B0_CE": {
            "each_seed_strictly_positive": true,
            "mean_acc": true,
            "mean_raw_nll_nonincrease": true,
            "per_subject_floor": false
          },
          "P0_LS_vs_B0_LS": {
            "each_seed_strictly_positive": true,
            "mean_acc": true,
            "mean_raw_nll_nonincrease": true,
            "per_subject_floor": false
          },
          "P0_LS_vs_S0_CE": {
            "each_seed_strictly_positive": true,
            "mean_acc": true,
            "mean_raw_nll_nonincrease": true,
            "per_subject_floor": false
          },
          "P0_LS_vs_S0_LS": {
            "each_seed_strictly_positive": false,
            "mean_acc": true,
            "mean_raw_nll_nonincrease": true,
            "per_subject_floor": false
          }
        },
        "reason": "All four frozen subject-risk gates fail; P0-LS vs S0-LS also fails seed0 strict positivity, despite positive mean accuracy and lower raw NLL.",
        "round_id": "p0-cue-r2-recover53",
        "scope": "Fixed LS epsilon0.10 P0-CUE-R2 exposed development instance only, not all P0 variants."
      },
      "decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-recover53_decision.yaml",
      "evidence_id": "AI4S-DSAINET-p0-cue-r2-recover53",
      "round_id": "p0-cue-r2-recover53",
      "run": {
        "bundle_id": "2026-10-28_dsainet_p0_cue_r2_recover53",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 6.283,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 55,
        "recorded_at": "2026-10-28T05:56:32.597587+00:00",
        "round_id": "p0-cue-r2-recover53",
        "run_prefix": "2026-10-28_dsainet_p0_cue_r2_recover53",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-28T05:59:00.326729+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-28T05:59:04.593813+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T05:59:41.513053+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1b19048a796f2a4366cc216c5d31b5c0145fc50af62c11b3ac31143464709006",
                "execution_seconds": 32.279359102249146,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1",
                "transaction_id": "2026-10-28_dsainet_p0_cue_r2_recover53-tx",
                "waiting_for_resources": false,
                "wall_seconds": 32.279359102249146
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T07:10:05.674845+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "1b19048a796f2a4366cc216c5d31b5c0145fc50af62c11b3ac31143464709006",
                "execution_seconds": 979.5545961856842,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1",
                "transaction_id": "2026-10-28_dsainet_p0_cue_r2_recover53-tx",
                "waiting_for_resources": false,
                "wall_seconds": 979.5545961856842
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-28T07:17:00.320699+00:00",
            "result": {
              "artifact_manifest_sha256": "c0371f6c2a16f2c55a1b5e1851d00b39b6c6dcbbb0c91da39d0965a03658cc61",
              "contract_sha256": "1b19048a796f2a4366cc216c5d31b5c0145fc50af62c11b3ac31143464709006",
              "run_id": "2026-10-28_dsainet_p0_cue_r2_recover53-full-w1",
              "transaction_id": "2026-10-28_dsainet_p0_cue_r2_recover53-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "decision": "NO_SIGNAL",
        "record": "ai4s/programs/dsainet/research/p0-cue-r3-cvar/closeout/REPORT.md",
        "scope": "independent recovered development artifacts; standard intake false"
      },
      "independent_revalidation": {
        "A_net_utility_pass": false,
        "B_parent_retention_pass": false,
        "audits": 18,
        "contract_sha256": "607b8efa174bb0c68cd2d4757710f47e9f41547e9ae1a331548da001b4e39b9c",
        "decision": "NO_SIGNAL_STOP_CUE4_CONTINUOUS_TUNING",
        "evidence_id": "DSAINET-P0-CUE-R3-CVAR-RECOVERED-ANALYSIS-20261028",
        "fits": 18,
        "follow_up_disposition": "STOP_CUE4_CONTINUOUS_TUNING; no further dispatch; preserve historical candidate and prior negative evidence",
        "formal_claim": false,
        "independent_index_sha256": "c0be0ac1654bf609c8c810ad25138bbea053fb4122b56183549574b27257d22f",
        "local_recompute_sha256": "e2ae64d16deaf9665e340079df26db78ff633439cb7041ee35ac5f4d102e99d0",
        "observed_at": "2026-10-28T14:42:12.755782+00:00",
        "original_run_status": "FAILED_PRESERVED",
        "proof_sha256": "f9881f8964083876693a01b06f7de461b30f28e5b36e467bdfb23f7477db1275",
        "reference_cells": 90,
        "remaining_campaign_hours_snapshot": 27.389751846326718,
        "report": "ai4s/programs/dsainet/research/p0-cue-r3-cvar/closeout/REPORT.md",
        "report_sha256": "c99d3b82b30de9082896f1fcf48dc8b060928e075768113d3ebda7b5d38c51e1",
        "result_sha256": "0ee56e29221335b331de32b050a410962ff396c900d779916aab594d574def29",
        "revalidation_status": "PASS_EXISTING_ARTIFACT_REVALIDATION",
        "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
        "standard_verified_intake": false,
        "transaction_id": "2026-10-28_dsainet_p0_cue_r3_cvar-tx"
      },
      "original_run_terminal_status": "FAILED",
      "round_id": "p0-cue-r3-cvar",
      "run": {
        "bundle_id": "2026-10-28_dsainet_p0_cue_r3_cvar",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 18.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 20,
        "recorded_at": "2026-10-28T10:58:36.968637+00:00",
        "round_id": "p0-cue-r3-cvar",
        "run_prefix": "2026-10-28_dsainet_p0_cue_r3_cvar",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-28T10:59:13.735443+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-28T10:59:15.937275+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T10:59:53.360798+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "607b8efa174bb0c68cd2d4757710f47e9f41547e9ae1a331548da001b4e39b9c",
                "execution_seconds": 35.16918325424194,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
                "transaction_id": "2026-10-28_dsainet_p0_cue_r3_cvar-tx",
                "waiting_for_resources": false,
                "wall_seconds": 35.16918325424194
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T11:01:15.463622+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "607b8efa174bb0c68cd2d4757710f47e9f41547e9ae1a331548da001b4e39b9c",
                "execution_seconds": 117.27505850791931,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
                "transaction_id": "2026-10-28_dsainet_p0_cue_r3_cvar-tx",
                "waiting_for_resources": false,
                "wall_seconds": 117.27505850791931
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T14:40:31.873519+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "607b8efa174bb0c68cd2d4757710f47e9f41547e9ae1a331548da001b4e39b9c",
                "execution_seconds": 1987.7884907722473,
                "queue_seconds": 6.154411554336548,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_dsainet_p0_cue_r3_cvar-full-w1",
                "transaction_id": "2026-10-28_dsainet_p0_cue_r3_cvar-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1993.9429023265839
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "G1_net_utility_pass": false,
        "G2_asymmetric_structure_pass": true,
        "G3_joint_prediction_pass": true,
        "I_ACC_supports_same_direction_interaction": false,
        "automatic_follow_up": false,
        "claim_created": false,
        "claim_status": "NOT_A_FORMAL_CLAIM",
        "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
        "decision": "NO_SIGNAL",
        "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-REVALIDATED-ANALYSIS-20261029",
        "exact_rule_kind": "P0_PF_R1_FROZEN_GATES_V1",
        "full_payload_local": false,
        "intake_scope": "remote_analysis_key_delivery_revalidated",
        "investment_decision": "NO_SIGNAL_STOP_PF_R1",
        "program_id": "dsainet",
        "reason": "G1 fails against matched LS anchors and R2 parent retention; I_ACC is negative. G2/G3 remain bounded exposed-development signals.",
        "recorded_at": "2026-10-29T11:56:23.546781+00:00",
        "research_id": "p0-pf-r1",
        "role": "exposed_development_revalidated_analysis",
        "round_id": "p0-pf-r1-science1-packfix1",
        "run_action": "NO_RUN",
        "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
        "schema_version": "dsainet-pf-r1-revalidated-analysis-decision-v1",
        "scope": "Fixed equal-probability-fusion PF-R1 exposed development instance; not closure of all asymmetric P0 structures.",
        "source_artifact_manifest_sha256": "cb6e9cebb2d53d73fc85ac05a103614a58633c4a1c482d5c65ad30c8c3defca4",
        "source_run_status": "COMPLETE_PRESERVED",
        "sources": {
          "acceptance": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/reports/KEY_DELIVERY_ACCEPTANCE.json",
            "sha256": "15e9cc9aa2b8ad9007c6fa8ce7bce324853e61d184c38c48bc47c114da3d16c4"
          },
          "delivery_receipt": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/KEY_EVIDENCE/DELIVERY_RECEIPT.json",
            "sha256": "678cfc64ffb8f030faab880db994ee07babb6c4958f344c6d638cbd5098b70b1"
          },
          "external_review": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/review/REVIEW_RESPONSE.md",
            "sha256": "e0793db95d8624d923bf3e50f8ce2b40777597ffaa0da7c4aea83b6e1f9199e3"
          },
          "external_trace": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/review/TRACE_META.json",
            "sha256": "d0d9bd5f201a13c13570678eadb9fc043747bd2f0485b9746995aa3e5794014b"
          },
          "independent_recompute": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/reports/INDEPENDENT_RECOMPUTE.json",
            "sha256": "073fe9dd2da7cacc2297b06abd3b5ad11eb7f46d303ef04cdf4f2c5d80d6100b"
          },
          "local_frozen_analysis": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/reports/LOCAL_RECOMPUTE.json",
            "sha256": "67b683561d39f318873a9357613b33fbd55c9ab6c2ea2da63a5e003e7d1d6a59"
          },
          "report": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/REPORT_ZH.md",
            "sha256": "7bab1bd5244fabeec95a632bd3d2451d1dc87efce9ab406a30c7509a10855e37"
          },
          "review_disposition": {
            "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/review/REVIEW_DISPOSITION.md",
            "sha256": "471dab8b04a09c9140c3dc4e9cc95290b6887d6652a68799181f609892fd0864"
          }
        },
        "standard_analysis_v1_intake": false,
        "standard_verified_intake": false
      },
      "decision_record": "ai4s/programs/dsainet/research/p0-pf-r1-science1-packfix1_decision.yaml",
      "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-REVALIDATED-ANALYSIS-20261029",
      "independent_revalidation": {
        "G1": false,
        "G2": true,
        "G3": true,
        "I": false,
        "acceptance": {
          "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/reports/KEY_DELIVERY_ACCEPTANCE.json",
          "sha256": "15e9cc9aa2b8ad9007c6fa8ce7bce324853e61d184c38c48bc47c114da3d16c4"
        },
        "audits": 90,
        "automatic_follow_up": false,
        "budget": {
          "closeout_included_hours": 4,
          "execution_seconds_this_run": 2356.4859709739685,
          "idle_or_stopped_refund_hours": 0,
          "original_start": "2026-10-23T13:28:00+00:00",
          "remaining_campaign_hours_snapshot": 23.153421013439015,
          "science_node_limit_hours": 23,
          "snapshot_at": "2026-10-29T11:56:23.546781+00:00",
          "total_hours": 157,
          "transaction_limit_hours": 27,
          "verified_resource_queue_seconds": 31055.862429380417
        },
        "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
        "decision": "NO_SIGNAL_STOP_PF_R1",
        "decision_record": {
          "path": "ai4s/programs/dsainet/research/p0-pf-r1-science1-packfix1_decision.yaml",
          "sha256": "395439da0f78dcd5dee102e645bf4b417c85001537cd2a90f68bb4c347179e15"
        },
        "delivery_receipt": {
          "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/KEY_EVIDENCE/DELIVERY_RECEIPT.json",
          "sha256": "678cfc64ffb8f030faab880db994ee07babb6c4958f344c6d638cbd5098b70b1"
        },
        "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-REVALIDATED-ANALYSIS-20261029",
        "external_review": {
          "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/review/REVIEW_RESPONSE.md",
          "sha256": "e0793db95d8624d923bf3e50f8ce2b40777597ffaa0da7c4aea83b6e1f9199e3"
        },
        "failed_audits": 0,
        "failed_fits": 0,
        "fits": 90,
        "follow_up_disposition": "STOP_FIXED_PF_R1; NO_NEW_EXPERIMENT; retain bounded structure clues, all old Runs and evidence",
        "formal_claim": false,
        "full_payload_local": false,
        "historical_cells": 90,
        "intake_scope": "remote_analysis_key_delivery_revalidated",
        "key_files_verified": 682,
        "observed_at": "2026-10-29T11:56:23.546781+00:00",
        "remote_artifact_files": 2008,
        "remote_full_artifact_verification": true,
        "report": {
          "path": "ai4s/programs/dsainet/research/p0-pf-r1/analysis_closeout/REPORT_ZH.md",
          "sha256": "7bab1bd5244fabeec95a632bd3d2451d1dc87efce9ab406a30c7509a10855e37"
        },
        "revalidation_status": "PASS_REVALIDATED_KEY_DELIVERY",
        "role": "exposed_development_revalidated_analysis",
        "round_id": "p0-pf-r1-science1-packfix1",
        "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
        "source_run_status": "COMPLETE_PRESERVED",
        "standard_analysis_v1_intake": false,
        "standard_verified_intake": false
      },
      "original_run_terminal_status": "COMPLETE_PRESERVED",
      "round_id": "p0-pf-r1-science1-packfix1",
      "run": {
        "bundle_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 26.41646869707033,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 91,
        "recorded_at": "2026-10-29T07:50:45.745950+00:00",
        "round_id": "p0-pf-r1-science1-packfix1",
        "run_prefix": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-29T07:51:48.299894+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-29T07:51:59.054452+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-29T07:54:14.469117+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
                "execution_seconds": 133.52719449996948,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
                "transaction_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 133.52719449996948
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-29T10:56:29.184369+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
                "execution_seconds": 2356.4859709739685,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
                "transaction_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2356.4859709739685
              }
            }
          }
        ]
      }
    }
  ],
  "continuation_history": [
    {
      "bundle_id": "2026-08-31_dsainet_ai4s_early_scale_merge_r2",
      "campaign_id": "dsainet-ai4s-spatial-anchor-v1-2026-08-31",
      "consumed_at": "2026-08-31T13:44:46.713851+00:00",
      "continuation_id": "dsainet:dsainet-ai4s-spatial-anchor-v1-2026-08-31:slot-2",
      "contract": "research/dsainet-r02-early-scale-merge-v0.1.yaml",
      "created_at": "2026-08-31T13:26:11.666415+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-08-31T13:40:25.030452+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/archive/programs/dsainet/research/dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1",
      "parent_round_id": "dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1",
      "parent_verified_intake": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r3-full-w1",
      "program_id": "dsainet",
      "round_id": "dsainet-r02-early-scale-merge-v0.1",
      "round_slot": 2,
      "run_prefix": "2026-08-31_dsainet_ai4s_early_scale_merge_r2",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3",
      "campaign_id": "dsainet-ai4s-spatial-anchor-v1-2026-08-31",
      "consumed_at": "2026-09-01T02:31:40.352686+00:00",
      "continuation_id": "dsainet:dsainet-ai4s-spatial-anchor-v1-2026-08-31:slot-3",
      "contract": "research/dsainet-r03-role-specific-token-pooling-v0.1.yaml",
      "created_at": "2026-08-31T17:12:17.452491+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-08-31T17:39:15.252927+00:00",
      "parent_decision": "PROMISING_INCOMPLETE",
      "parent_decision_record": "ai4s/archive/programs/dsainet/research/dsainet-r02-early-scale-merge-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r02-early-scale-merge-v0.1",
      "parent_round_id": "dsainet-r02-early-scale-merge-v0.1",
      "parent_verified_intake": "2026-08-31_dsainet_ai4s_early_scale_merge_r2-full-w1",
      "program_id": "dsainet",
      "round_id": "dsainet-r03-role-specific-token-pooling-v0.1",
      "round_slot": 3,
      "run_prefix": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-06_dsainet_inter_attention_lesion_r1",
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "consumed_at": "2026-09-06T09:21:16.563981+00:00",
      "continuation_id": "dsainet:dsainet-role-pooling-confirmation-v1-2026-09-06:slot-2",
      "contract": "research/dsainet-r02-inter-attention-lesion-v0.1.yaml",
      "created_at": "2026-09-05T21:25:16.034729+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-09-06T09:20:26.076828+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-confirm-role-pooling-seed23-repair2-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-confirm-role-pooling-seed23-repair2-v0.1",
      "parent_round_id": "dsainet-confirm-role-pooling-seed23-repair2-v0.1",
      "parent_verified_intake": "2026-09-06_dsainet_role_pooling_confirm_seed23_r4-full-w1",
      "program_id": "dsainet",
      "research_gate": {
        "hypothesis_id": "identity-skip-inter-attention-vs-native",
        "module_id": "dsainet-inter-attention-lesion-v0.1",
        "paired_seed_cap": 5,
        "paired_seeds_after_freeze": [
          0,
          1
        ],
        "transition": "SCREEN_NEW"
      },
      "round_id": "dsainet-r02-inter-attention-lesion-v0.1",
      "round_slot": 2,
      "run_prefix": "2026-09-06_dsainet_inter_attention_lesion_r1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-06_dsainet_ilud_v0_1_r3",
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "consumed_at": "2026-09-06T11:46:40.636271+00:00",
      "continuation_id": "dsainet:dsainet-role-pooling-confirmation-v1-2026-09-06:slot-3",
      "contract": "research/dsainet-r03-ilud-v0.1-r3.yaml",
      "created_at": "2026-09-06T11:26:15.251961+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-09-06T11:46:05.744357+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-r02-inter-attention-lesion-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r02-inter-attention-lesion-v0.1",
      "parent_round_id": "dsainet-r02-inter-attention-lesion-v0.1",
      "parent_verified_intake": "2026-09-06_dsainet_inter_attention_lesion_r1-full-w1",
      "program_id": "dsainet",
      "research_gate": {
        "hypothesis_id": "ilud-source-linear-access-v0.1",
        "module_id": "dsainet-inter-stage-label-utility",
        "paired_seed_cap": 5,
        "paired_seeds_after_freeze": [
          0,
          1
        ],
        "transition": "DIAGNOSE_ONCE"
      },
      "round_id": "dsainet-r03-ilud-v0.1-r3",
      "round_slot": 3,
      "run_prefix": "2026-09-06_dsainet_ilud_v0_1_r3",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-07_dsainet_dnrua_v0_1",
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "consumed_at": "2026-09-06T17:38:02.528360+00:00",
      "continuation_id": "dsainet:dsainet-role-pooling-confirmation-v1-2026-09-06:slot-4",
      "contract": "research/dsainet-r04-dnrua-v0.1.yaml",
      "created_at": "2026-09-06T16:45:39.030296+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-09-06T17:37:31.562176+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-r03-ilud-v0.1-r4_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r03-ilud-v0.1-r4",
      "parent_round_id": "dsainet-r03-ilud-v0.1-r4",
      "parent_verified_intake": "2026-09-06_dsainet_ilud_v0_1_r4-full-w1",
      "program_id": "dsainet",
      "research_gate": {
        "hypothesis_id": "dnrua-native-readout-v0.1",
        "module_id": "dsainet-native-message-direction-audit",
        "paired_seed_cap": 5,
        "paired_seeds_after_freeze": [
          0,
          1
        ],
        "transition": "DIAGNOSE_ONCE"
      },
      "round_id": "dsainet-r04-dnrua-v0.1",
      "round_slot": 4,
      "run_prefix": "2026-09-07_dsainet_dnrua_v0_1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-07_dsainet_mroa_v0_1",
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "consumed_at": "2026-09-06T18:12:48.002027+00:00",
      "continuation_id": "dsainet:dsainet-role-pooling-confirmation-v1-2026-09-06:slot-5",
      "contract": "research/dsainet-r05-mroa-v0.1.yaml",
      "created_at": "2026-09-06T17:47:47.396760+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-09-06T18:12:34.550177+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-r04-dnrua-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r04-dnrua-v0.1",
      "parent_round_id": "dsainet-r04-dnrua-v0.1",
      "parent_verified_intake": "2026-09-07_dsainet_dnrua_v0_1-full-w1",
      "program_id": "dsainet",
      "research_gate": {
        "hypothesis_id": "mroa-label-free-proxy-v0.1",
        "module_id": "dsainet-message-risk-observability",
        "paired_seed_cap": 5,
        "paired_seeds_after_freeze": [
          0,
          1
        ],
        "transition": "DIAGNOSE_ONCE"
      },
      "round_id": "dsainet-r05-mroa-v0.1",
      "round_slot": 5,
      "run_prefix": "2026-09-07_dsainet_mroa_v0_1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-07_dsainet_cgmw_v0_1",
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "consumed_at": "2026-09-06T18:27:57.954111+00:00",
      "continuation_id": "dsainet:dsainet-role-pooling-confirmation-v1-2026-09-06:slot-6",
      "contract": "research/dsainet-r06-cgmw-v0.1.yaml",
      "created_at": "2026-09-06T18:25:08.026414+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-09-06T18:27:57.215904+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-r05-mroa-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r05-mroa-v0.1",
      "parent_round_id": "dsainet-r05-mroa-v0.1",
      "parent_verified_intake": "2026-09-07_dsainet_mroa_v0_1-full-w1",
      "program_id": "dsainet",
      "research_gate": {
        "hypothesis_id": "cgmw-preconf-median-withhold-v0.1",
        "module_id": "dsainet-message-risk-observability",
        "paired_seed_cap": 5,
        "paired_seeds_after_freeze": [
          0,
          1
        ],
        "transition": "DIAGNOSE_ONCE"
      },
      "round_id": "dsainet-r06-cgmw-v0.1",
      "round_slot": 6,
      "run_prefix": "2026-09-07_dsainet_cgmw_v0_1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-07_dsainet_tapl_v0_1",
      "campaign_id": "dsainet-role-pooling-confirmation-v1-2026-09-06",
      "consumed_at": "2026-09-06T18:43:21.916477+00:00",
      "continuation_id": "dsainet:dsainet-role-pooling-confirmation-v1-2026-09-06:slot-7",
      "contract": "research/dsainet-r07-tapl-v0.1.yaml",
      "created_at": "2026-09-06T18:40:21.412751+00:00",
      "executor_id": "ccmu_lab",
      "frozen_at": "2026-09-06T18:43:21.185845+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-r06-cgmw-v0.1_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r06-cgmw-v0.1",
      "parent_round_id": "dsainet-r06-cgmw-v0.1",
      "parent_verified_intake": "2026-09-07_dsainet_cgmw_v0_1-full-w1",
      "program_id": "dsainet",
      "research_gate": {
        "hypothesis_id": "tapl-uniform-mean-vs-native-v0.1",
        "module_id": "dsainet-token-attention-pooling",
        "paired_seed_cap": 5,
        "paired_seeds_after_freeze": [
          0,
          1
        ],
        "transition": "DIAGNOSE_ONCE"
      },
      "round_id": "dsainet-r07-tapl-v0.1",
      "round_slot": 7,
      "run_prefix": "2026-09-07_dsainet_tapl_v0_1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "campaign_id": "dsainet-ttpp-v1-2026-09-07",
      "continuation_id": "dsainet:dsainet-ttpp-v1-2026-09-07:slot-2",
      "created_at": "2026-09-08T05:31:00.828500+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-remaining-v0.2_decision.yaml",
      "parent_evidence_id": "AI4S-DSAINET-dsainet-r01-ttpp-lab10-remaining-v0.2",
      "parent_round_id": "dsainet-r01-ttpp-lab10-remaining-v0.2",
      "parent_verified_intake": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_2-full-w1",
      "previous_status": "PENDING_CONTRACT",
      "program_id": "dsainet",
      "round_slot": 2,
      "status": "SUPERSEDED_BY_NEW_CAMPAIGN",
      "supersede_reason": "User authorized RORA-v0.1 on Lab10: 36 frozen D/U checkpoints and 72 fixed source-only probes; no backbone training; one diagnostic round only.",
      "superseded_at": "2026-09-08T08:02:48.076204+00:00",
      "superseded_by_campaign_id": "dsainet-rora-v1-2026-09-08"
    },
    {
      "budget_hours": 64,
      "budget_snapshot": {
        "anchor_cache_seconds_each": 22.502154052257538,
        "audit_cache_remaining": [
          "AUDITCACHE_s0_t0",
          "AUDITCACHE_s0_t1",
          "AUDITCACHE_s0_t2",
          "AUDITCACHE_s0_t3",
          "AUDITCACHE_s0_t4",
          "AUDITCACHE_s0_t5",
          "AUDITCACHE_s0_t6",
          "AUDITCACHE_s0_t7",
          "AUDITCACHE_s0_t8",
          "AUDITCACHE_s1_t0",
          "AUDITCACHE_s1_t1",
          "AUDITCACHE_s1_t2",
          "AUDITCACHE_s1_t3",
          "AUDITCACHE_s1_t4",
          "AUDITCACHE_s1_t5",
          "AUDITCACHE_s1_t6",
          "AUDITCACHE_s1_t7",
          "AUDITCACHE_s1_t8",
          "AUDITCACHE_s2_t0",
          "AUDITCACHE_s2_t1",
          "AUDITCACHE_s2_t2",
          "AUDITCACHE_s2_t3",
          "AUDITCACHE_s2_t4",
          "AUDITCACHE_s2_t5",
          "AUDITCACHE_s2_t6",
          "AUDITCACHE_s2_t7",
          "AUDITCACHE_s2_t8"
        ],
        "audit_seconds_each": 14.48308526724577,
        "audits_remaining": [
          "GL_s0_t0",
          "GL_s0_t1",
          "GL_s0_t2",
          "GL_s0_t3",
          "GL_s0_t4",
          "GL_s0_t5",
          "GL_s0_t6",
          "GL_s0_t7",
          "GL_s0_t8",
          "GL_s1_t0",
          "GL_s1_t1",
          "GL_s1_t2",
          "GL_s1_t3",
          "GL_s1_t4",
          "GL_s1_t5",
          "GL_s1_t6",
          "GL_s1_t7",
          "GL_s1_t8",
          "GL_s2_t0",
          "GL_s2_t1",
          "GL_s2_t2",
          "GL_s2_t3",
          "GL_s2_t4",
          "GL_s2_t5",
          "GL_s2_t6",
          "GL_s2_t7",
          "GL_s2_t8",
          "GG_s0_t0",
          "GG_s0_t1",
          "GG_s0_t2",
          "GG_s0_t3",
          "GG_s0_t4",
          "GG_s0_t5",
          "GG_s0_t6",
          "GG_s0_t7",
          "GG_s0_t8",
          "GG_s1_t0",
          "GG_s1_t1",
          "GG_s1_t2",
          "GG_s1_t3",
          "GG_s1_t4",
          "GG_s1_t5",
          "GG_s1_t6",
          "GG_s1_t7",
          "GG_s1_t8",
          "GG_s2_t0",
          "GG_s2_t1",
          "GG_s2_t2",
          "GG_s2_t3",
          "GG_s2_t4",
          "GG_s2_t5",
          "GG_s2_t6",
          "GG_s2_t7",
          "GG_s2_t8",
          "LL_s0_t0",
          "LL_s0_t1",
          "LL_s0_t2",
          "LL_s0_t3",
          "LL_s0_t4",
          "LL_s0_t5",
          "LL_s0_t6",
          "LL_s0_t7",
          "LL_s0_t8",
          "LL_s1_t0",
          "LL_s1_t1",
          "LL_s1_t2",
          "LL_s1_t3",
          "LL_s1_t4",
          "LL_s1_t5",
          "LL_s1_t6",
          "LL_s1_t7",
          "LL_s1_t8",
          "LL_s2_t0",
          "LL_s2_t1",
          "LL_s2_t2",
          "LL_s2_t3",
          "LL_s2_t4",
          "LL_s2_t5",
          "LL_s2_t6",
          "LL_s2_t7",
          "LL_s2_t8",
          "G_s0_t0",
          "G_s0_t1",
          "G_s0_t2",
          "G_s0_t3",
          "G_s0_t4",
          "G_s0_t5",
          "G_s0_t6",
          "G_s0_t7",
          "G_s0_t8",
          "G_s1_t0",
          "G_s1_t1",
          "G_s1_t2",
          "G_s1_t3",
          "G_s1_t4",
          "G_s1_t5",
          "G_s1_t6",
          "G_s1_t7",
          "G_s1_t8",
          "G_s2_t0",
          "G_s2_t1",
          "G_s2_t2",
          "G_s2_t3",
          "G_s2_t4",
          "G_s2_t5",
          "G_s2_t6",
          "G_s2_t7",
          "G_s2_t8",
          "L_s0_t0",
          "L_s0_t1",
          "L_s0_t2",
          "L_s0_t3",
          "L_s0_t4",
          "L_s0_t5",
          "L_s0_t6",
          "L_s0_t7",
          "L_s0_t8",
          "L_s1_t0",
          "L_s1_t1",
          "L_s1_t2",
          "L_s1_t3",
          "L_s1_t4",
          "L_s1_t5",
          "L_s1_t6",
          "L_s1_t7",
          "L_s1_t8",
          "L_s2_t0",
          "L_s2_t1",
          "L_s2_t2",
          "L_s2_t3",
          "L_s2_t4",
          "L_s2_t5",
          "L_s2_t6",
          "L_s2_t7",
          "L_s2_t8",
          "GW_s0_t0",
          "GW_s0_t1",
          "GW_s0_t2",
          "GW_s0_t3",
          "GW_s0_t4",
          "GW_s0_t5",
          "GW_s0_t6",
          "GW_s0_t7",
          "GW_s0_t8",
          "GW_s1_t0",
          "GW_s1_t1",
          "GW_s1_t2",
          "GW_s1_t3",
          "GW_s1_t4",
          "GW_s1_t5",
          "GW_s1_t6",
          "GW_s1_t7",
          "GW_s1_t8",
          "GW_s2_t0",
          "GW_s2_t1",
          "GW_s2_t2",
          "GW_s2_t3",
          "GW_s2_t4",
          "GW_s2_t5",
          "GW_s2_t6",
          "GW_s2_t7",
          "GW_s2_t8",
          "LW_s0_t0",
          "LW_s0_t1",
          "LW_s0_t2",
          "LW_s0_t3",
          "LW_s0_t4",
          "LW_s0_t5",
          "LW_s0_t6",
          "LW_s0_t7",
          "LW_s0_t8",
          "LW_s1_t0",
          "LW_s1_t1",
          "LW_s1_t2",
          "LW_s1_t3",
          "LW_s1_t4",
          "LW_s1_t5",
          "LW_s1_t6",
          "LW_s1_t7",
          "LW_s1_t8",
          "LW_s2_t0",
          "LW_s2_t1",
          "LW_s2_t2",
          "LW_s2_t3",
          "LW_s2_t4",
          "LW_s2_t5",
          "LW_s2_t6",
          "LW_s2_t7",
          "LW_s2_t8"
        ],
        "budget_hours": 64,
        "budget_seconds": 230400.0,
        "budget_supplement_sha256": "bf13e0aaba73b91129d3db44058cd0f9daec7ac2dd40e0dde6a008cc0457e7da",
        "cache_remaining": [],
        "closeout_seconds": 3600,
        "conservative_capacity_slots": 1,
        "contract_sha256": "3666bec81ef4aab5bc6a437fb0fde27f9684f0c64f365b04be42ab29d40542ef",
        "current_node_remaining_seconds": 89026.73486685753,
        "current_resource_queue_seconds": 660.7560687065125,
        "family_profile_commitment_mib": 1235,
        "fit_seconds_each": 457.0878318399191,
        "fits_remaining": [
          "GL_s0_t1",
          "GL_s0_t5",
          "GL_s0_t6",
          "GL_s0_t7",
          "GL_s0_t8",
          "GL_s1_t0",
          "GL_s1_t1",
          "GL_s1_t2",
          "GL_s1_t3",
          "GL_s1_t4",
          "GL_s1_t5",
          "GL_s1_t6",
          "GL_s1_t7",
          "GL_s1_t8",
          "GL_s2_t0",
          "GL_s2_t1",
          "GL_s2_t2",
          "GL_s2_t3",
          "GL_s2_t4",
          "GL_s2_t5",
          "GL_s2_t6",
          "GL_s2_t7",
          "GL_s2_t8",
          "GG_s0_t1",
          "GG_s0_t5",
          "GG_s0_t6",
          "GG_s0_t7",
          "GG_s0_t8",
          "GG_s1_t0",
          "GG_s1_t1",
          "GG_s1_t2",
          "GG_s1_t3",
          "GG_s1_t4",
          "GG_s1_t5",
          "GG_s1_t6",
          "GG_s1_t7",
          "GG_s1_t8",
          "GG_s2_t0",
          "GG_s2_t1",
          "GG_s2_t2",
          "GG_s2_t3",
          "GG_s2_t4",
          "GG_s2_t5",
          "GG_s2_t6",
          "GG_s2_t7",
          "GG_s2_t8",
          "LL_s0_t1",
          "LL_s0_t4",
          "LL_s0_t5",
          "LL_s0_t6",
          "LL_s0_t7",
          "LL_s0_t8",
          "LL_s1_t0",
          "LL_s1_t1",
          "LL_s1_t2",
          "LL_s1_t3",
          "LL_s1_t4",
          "LL_s1_t5",
          "LL_s1_t6",
          "LL_s1_t7",
          "LL_s1_t8",
          "LL_s2_t0",
          "LL_s2_t1",
          "LL_s2_t2",
          "LL_s2_t3",
          "LL_s2_t4",
          "LL_s2_t5",
          "LL_s2_t6",
          "LL_s2_t7",
          "LL_s2_t8",
          "G_s0_t1",
          "G_s0_t4",
          "G_s0_t5",
          "G_s0_t6",
          "G_s0_t7",
          "G_s0_t8",
          "G_s1_t0",
          "G_s1_t1",
          "G_s1_t2",
          "G_s1_t3",
          "G_s1_t4",
          "G_s1_t6",
          "G_s1_t7",
          "G_s1_t8",
          "G_s2_t0",
          "G_s2_t1",
          "G_s2_t2",
          "G_s2_t3",
          "G_s2_t4",
          "G_s2_t5",
          "G_s2_t6",
          "G_s2_t7",
          "G_s2_t8",
          "L_s0_t1",
          "L_s0_t3",
          "L_s0_t4",
          "L_s0_t5",
          "L_s0_t6",
          "L_s0_t7",
          "L_s0_t8",
          "L_s1_t0",
          "L_s1_t1",
          "L_s1_t2",
          "L_s1_t3",
          "L_s1_t4",
          "L_s1_t5",
          "L_s1_t6",
          "L_s1_t7",
          "L_s1_t8",
          "L_s2_t0",
          "L_s2_t1",
          "L_s2_t2",
          "L_s2_t3",
          "L_s2_t4",
          "L_s2_t5",
          "L_s2_t6",
          "L_s2_t7",
          "L_s2_t8",
          "GW_s0_t1",
          "GW_s0_t3",
          "GW_s0_t4",
          "GW_s0_t5",
          "GW_s0_t6",
          "GW_s0_t7",
          "GW_s0_t8",
          "GW_s1_t0",
          "GW_s1_t1",
          "GW_s1_t2",
          "GW_s1_t3",
          "GW_s1_t4",
          "GW_s1_t5",
          "GW_s1_t6",
          "GW_s1_t7",
          "GW_s1_t8",
          "GW_s2_t0",
          "GW_s2_t1",
          "GW_s2_t2",
          "GW_s2_t3",
          "GW_s2_t4",
          "GW_s2_t5",
          "GW_s2_t6",
          "GW_s2_t7",
          "GW_s2_t8",
          "LW_s0_t1",
          "LW_s0_t4",
          "LW_s0_t5",
          "LW_s0_t6",
          "LW_s0_t7",
          "LW_s0_t8",
          "LW_s1_t0",
          "LW_s1_t1",
          "LW_s1_t2",
          "LW_s1_t3",
          "LW_s1_t4",
          "LW_s1_t5",
          "LW_s1_t6",
          "LW_s1_t7",
          "LW_s1_t8",
          "LW_s2_t0",
          "LW_s2_t1",
          "LW_s2_t2",
          "LW_s2_t3",
          "LW_s2_t4",
          "LW_s2_t5",
          "LW_s2_t6",
          "LW_s2_t7",
          "LW_s2_t8"
        ],
        "measured_profile_sha256": "0ea3578d2d1989052c2947c3bf184222ecca0df0cab59f5d9cf7adef2f4217cd",
        "node_remaining_seconds": {
          "screen": 89026.73486685753,
          "tech": null
        },
        "old_budget_transferred": false,
        "original_budget_hours": 48,
        "phase_wall_seconds": {
          "anchor_cache": 0.0,
          "audit": 2737.3031155094504,
          "audit_cache": 607.5581594109535,
          "closeout": 3600.0,
          "fit": 76333.66791726649,
          "temperature": 94.6578426361084
        },
        "previous_supplement_hours": 8,
        "previous_supplement_sha256": "f3f525bd825093d5190af1355aa3a879c3366cc0ad05563f751e4d53092435b0",
        "previous_total_budget_hours": 56,
        "queue_seconds_verified": 660.7560687065125,
        "reads_scientific_effects": false,
        "remaining_anchor_cache_count": 0,
        "remaining_audit_cache_count": 27,
        "remaining_audit_count": 189,
        "remaining_fit_count": 167,
        "remaining_seconds": 108325.57206082344,
        "remaining_temperature_fit_count": 216,
        "required_seconds": 83373.187034823,
        "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
        "spent_execution_and_preparation_seconds": 122735.18400788307,
        "status": "PASS",
        "temperature_seconds_each": 0.4382307529449463,
        "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-tx",
        "transaction_remaining_seconds": 88819.10651254654,
        "transaction_spent_seconds": 83980.89348745346,
        "verified_resource_wait_seconds": 660.7560687065125
      },
      "cache_completed": 27,
      "checked_at": "2026-10-20T15:24:35.898857+00:00",
      "formal_audit_authorized": 189,
      "formal_audit_completed": 0,
      "formal_fit_completed": 22,
      "formal_fit_remaining": 167,
      "missing_success_telemetry": [
        "GG_s0_t2",
        "GG_s0_t3",
        "GL_s0_t4",
        "GW_s0_t2",
        "G_s0_t2",
        "G_s0_t3",
        "LL_s0_t2",
        "LL_s0_t3",
        "LW_s0_t2",
        "L_s0_t2"
      ],
      "normalization_cache_checks": "27/27 PASS; corrupt controls 27/27 rejected",
      "other_stages_authorized": false,
      "recovery_id": "2026-10-20_NRC1repair3_standardizer_r1",
      "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair_standardizer/REPORT.md",
      "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
      "scientific_claim": false,
      "source_file_count": 831,
      "source_hash_errors": [],
      "status": "BLOCKED_INCOMPLETE_PRESERVED_TELEMETRY",
      "technical_audit_completed": 8,
      "technical_fit_completed": 8,
      "worker_dispatched": false,
      "worker_import": "PASS; not end-to-end GPU qualification"
    },
    {
      "audits_required": 189,
      "cumulative_budget_hours": 64,
      "dispatch_state": "WAITING_GPU_CAPACITY",
      "fits_not_retrained": 12,
      "gpus_observed": 10,
      "independent_replays_authorized": 10,
      "latest_monitor": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_telemetry/STATUS_20261021_1515.md",
      "local_tests_passed": 19,
      "original_fit_artifacts_preserved": 22,
      "original_start_and_costs_preserved": true,
      "other_stages_authorized": false,
      "pid": "[REDACTED_MACHINE]",
      "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_telemetry/REAL_QUALIFICATION_FINAL64.json",
      "real_entry_checks_passed": 5,
      "recorded_at": "2026-10-20T16:21:31.739981+00:00",
      "recovery_id": "2026-10-20_NRC1repair3_telemetry_r1",
      "remaining_fits_after_replays": 167,
      "replay_completed": 0,
      "replay_pending": 10,
      "replay_running": 0,
      "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_telemetry/REPORT.md",
      "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
      "scientific_effects_read": false,
      "screen_timeout_hours": 64,
      "source_files_hash_verified": 831,
      "status": "FAILED",
      "supplement_sha256": "879c1a59daa5ff50853c1b6fa4b870dda4069a741bd755c7c127ec68375016cd",
      "transaction_timeout_hours": 64
    },
    {
      "additional_hours": 24,
      "audits_required": 189,
      "authorized_replays": 10,
      "checked_at": "2026-10-21T11:16:29.803656+00:00",
      "cumulative_budget_hours": 88,
      "original_campaign_start": 1792387110,
      "original_completed_fits": 22,
      "other_stages_authorized": false,
      "phases": {
        "fits_remaining167": {
          "attempts": [],
          "completed": null,
          "failed": null,
          "families": null,
          "journals": 0,
          "pending": null,
          "resource_admission": null,
          "running": null,
          "running_tasks": null,
          "total": null,
          "updated_at": null,
          "verified_journal_results": []
        },
        "fits_replay10": {
          "attempts": [
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 3,
              "task_id": "GG_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 3,
              "task_id": "GW_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 0,
              "task_id": "GL_s0_t4"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 3,
              "task_id": "LL_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 0,
              "task_id": "G_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 0,
              "task_id": "L_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 3,
              "task_id": "LW_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 3,
              "task_id": "G_s0_t3"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 0,
              "task_id": "GG_s0_t3"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 3,
              "task_id": "LL_s0_t3"
            }
          ],
          "completed": 10,
          "failed": 0,
          "families": {
            "dsa-nrc-v0.1-NRC1:fit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629": {
              "calibration_source": "unknown_family_serial_start",
              "commitment": 3072,
              "expand_after_measurement": true,
              "failed": false,
              "limit": 189,
              "max_family_jobs": 189,
              "peak": 907
            }
          },
          "journals": 10,
          "pending": 0,
          "resource_admission": {},
          "running": 0,
          "running_tasks": {},
          "total": 10,
          "updated_at": "2026-10-21T07:57:50.912895+00:00",
          "verified_journal_results": [
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 3,
              "task_id": "GG_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 0,
              "task_id": "L_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 3,
              "task_id": "LL_s0_t3"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 3,
              "task_id": "GW_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 0,
              "task_id": "GG_s0_t3"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 0,
              "task_id": "G_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 0,
              "task_id": "GL_s0_t4"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 3,
              "task_id": "G_s0_t3"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 907,
              "physical_gpu": 3,
              "task_id": "LL_s0_t2"
            },
            {
              "exit_code": 0,
              "full_process_memory": true,
              "peak_memory_mib": 895,
              "physical_gpu": 3,
              "task_id": "LW_s0_t2"
            }
          ]
        }
      },
      "pid": "[REDACTED_MACHINE]",
      "preserved_full_telemetry_fits": 12,
      "preserved_original_files": 886,
      "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_scope88/QUALIFICATION_FINAL.json",
      "recovery_id": "2026-10-21_NRC1repair3_scope88_r1",
      "remaining_other_fits": 167,
      "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_scope88/REPAIR_NOTES.md",
      "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
      "scientific_effects_read": false,
      "snapshot": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_scope88/STATUS.json",
      "status": "FAILED",
      "supplement_sha256": "4a7d7655706ffc01019e941a9fcab5f19b44a71621040d6986900bdadfb135d6"
    },
    {
      "additional_hours": 0,
      "audits_required": 189,
      "checked_at": "2026-10-21T11:46:16.383126+00:00",
      "cumulative_budget_hours": 88,
      "dispatch_observation": "WAITING_RESOURCE_ADMISSION_NO_WORKER_YET",
      "dynamic_expansion_configured": true,
      "dynamic_expansion_observed": false,
      "original_campaign_start": 1792387110,
      "original_completed_fits": 22,
      "other_stages_authorized": false,
      "phases": {
        "audit": {
          "completed": null,
          "failed": null,
          "families": null,
          "journals": 0,
          "pending": null,
          "resource_admission": null,
          "running": null,
          "running_tasks": null,
          "total": null,
          "updated_at": null,
          "verified_results": []
        },
        "fits_remaining167": {
          "completed": null,
          "failed": null,
          "families": null,
          "journals": 0,
          "pending": null,
          "resource_admission": null,
          "running": null,
          "running_tasks": null,
          "total": null,
          "updated_at": null,
          "verified_results": []
        }
      },
      "pid": "[REDACTED_MACHINE]",
      "preservation_errors": [],
      "preserved_full_telemetry_fits": 12,
      "preserved_original_files": 1021,
      "promoted_replays": 10,
      "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_intake88/QUALIFICATION_FINAL.json",
      "recovery_id": "2026-10-21_NRC1repair3_intake88_r1",
      "remaining_fits_authorized": 167,
      "remaining_seconds": 122556.2725687027,
      "replay_dispatch_count": 0,
      "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_intake88/REPAIR_NOTES.md",
      "resource_admission_check": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_intake88/RESOURCE_ADMISSION_CHECK.json",
      "reused_successful_replays": 10,
      "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
      "scientific_effects_read": false,
      "snapshot": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_intake88/STATUS.json",
      "status": "RUNNING",
      "supplement_sha256": "f9fe47411a0186d751a29f6739d529f048b16b259158a0415d0749c8630edddb"
    },
    {
      "additional_hours": 0,
      "audits_required": 189,
      "checked_at": "2026-10-21T16:01:20.847881+00:00",
      "cumulative_budget_hours": 88,
      "dispatch_observation": "WAITING_RESOURCE_ADMISSION_NO_WORKER_YET",
      "dynamic_expansion_configured": true,
      "dynamic_expansion_observed": false,
      "historical_wait_deduction_authorized": false,
      "old_scheduler_stop_receipt": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_resource88/STOP_RECEIPT.json",
      "original_campaign_start": 1792387110,
      "original_completed_fits": 22,
      "other_stages_authorized": false,
      "phases": {
        "audit": {
          "completed": null,
          "failed": null,
          "families": null,
          "journals": 0,
          "pending": null,
          "resource_admission": null,
          "running": null,
          "running_tasks": null,
          "total": null,
          "updated_at": null,
          "verified_results": []
        },
        "fits_remaining167": {
          "completed": 0,
          "failed": 0,
          "families": {
            "dsa-nrc-v0.1-NRC1:fit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629": {
              "calibration_source": "unknown_family_serial_start",
              "commitment": 3072,
              "expand_after_measurement": true,
              "failed": false,
              "limit": 1,
              "max_family_jobs": 189,
              "peak": 0
            }
          },
          "journals": 0,
          "pending": 167,
          "resource_admission": {
            "0": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 166,
              "observed_utilization_pct": 89,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2906,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "1": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 5,
              "observed_free_mib": 289,
              "observed_utilization_pct": 98,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2783,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "2": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 172,
              "observed_utilization_pct": 94,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2900,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "3": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 32,
              "observed_utilization_pct": 89,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -3040,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "4": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 5,
              "observed_free_mib": 289,
              "observed_utilization_pct": 99,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2783,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "5": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 170,
              "observed_utilization_pct": 91,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2902,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "6": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 164,
              "observed_utilization_pct": 93,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2908,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "7": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 164,
              "observed_utilization_pct": 67,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2908,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "8": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 4,
              "observed_free_mib": 168,
              "observed_utilization_pct": 91,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2904,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            },
            "9": {
              "eligibility": "insufficient_reserved_memory",
              "existing_compute_processes": 5,
              "observed_free_mib": 293,
              "observed_utilization_pct": 99,
              "pool_capacity_available": false,
              "post_launch_headroom_mib": -2779,
              "reserve_mib": 0,
              "task_id": "GL_s0_t1"
            }
          },
          "running": 0,
          "running_tasks": {},
          "total": 167,
          "updated_at": "2026-10-21T16:01:16.739897+00:00",
          "verified_results": []
        }
      },
      "pid": "[REDACTED_MACHINE]",
      "preservation_errors": [],
      "preserved_full_telemetry_fits": 12,
      "preserved_original_files": 1155,
      "promoted_replays": 10,
      "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_resource88/QUALIFICATION_FINAL.json",
      "recovery_id": "2026-10-21_NRC1repair3_resource88_r1",
      "remaining_fits_authorized": 167,
      "remaining_seconds": 111200.98102760315,
      "replay_dispatch_count": 0,
      "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_resource88/REPAIR_NOTES.md",
      "resource_admission_check": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_resource88/CLOCK_SCAN_CHECK.json",
      "reused_successful_replays": 10,
      "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
      "scientific_effects_read": false,
      "snapshot": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_resource88/STATUS.json",
      "status": "RUNNING",
      "supplement_sha256": "d0994874ea99b7e3453dd48ea240b0593122b9585f06386c3f0c6c1a51320e2f"
    }
  ],
  "continuation_preparation": {
    "automatic_continuation_authorized": true,
    "expected_reused_formal_fits": 1087,
    "helper_alive": true,
    "helper_pid": 2241926,
    "record": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume11/WITHDRAWAL_RECEIPT.json",
    "remaining_execution_hours": 21.13990393982993,
    "remaining_formal_fits": 3,
    "retained_epochs": [
      93,
      96
    ],
    "round_id": "dsa-pfc-xds-v0.1-physionet-resume11",
    "status": "REMOTE_RUNNING"
  },
  "controlled_withdrawal": {
    "added_budget_seconds": 0,
    "automatic_training_retries": 0,
    "gpu_ids": [
      0,
      1,
      3,
      4,
      5,
      6,
      7,
      8,
      9
    ],
    "helper_pid": 2241926,
    "helper_script_sha256": "bddf42a54ad15a27d1bd3a3bfa7068fbb08d4f13f629b089290e1eb059581620",
    "retained_initialized_tasks": [
      "physionet_B0_s2_t59",
      "physionet_B0_s4_t59"
    ],
    "retained_tasks_first_real_step_pass": true,
    "scientific_intake": false,
    "status": "REQUEUE_RUNNING",
    "successful_fit_count": 1085,
    "training_configuration_changed": false,
    "updated_at": "2026-10-07T15:49:36.583151+00:00",
    "withdrawn": [
      {
        "actual_cuda_mib": 0,
        "capacity": {
          "assessment": {
            "eligibility": "eligible",
            "existing_compute_processes": 3,
            "post_launch_headroom_mib": 2123,
            "reserve_mib": 0
          },
          "callback_completed_under_lock": false,
          "checks": 873,
          "commitment_mib": 2048,
          "contract_commitment_mib": 2048,
          "free_mib": 4171,
          "gpu": 3,
          "gpu_uuid": "GPU-b97c52a6-7497-cd20-3475-d9a15ec08f84",
          "new_reservation_created": false,
          "own_mib": 0,
          "peer_pending_mib": 5390,
          "required_mib": 7438,
          "reserve_once_mib": 0,
          "status": "WAITING_CAPACITY_BEFORE_FIT",
          "wait_seconds": 4047.2349444292486
        },
        "files": [
          "pre_cuda_capacity.json"
        ],
        "pid": "[REDACTED_MACHINE]",
        "pid_starttimes": {
          "2018308": 2577289616
        },
        "task_id": "physionet_B0_s1_t92",
        "zero_training_steps_proven": true
      },
      {
        "actual_cuda_mib": 0,
        "capacity": {
          "assessment": {
            "eligibility": "eligible",
            "existing_compute_processes": 3,
            "post_launch_headroom_mib": 2123,
            "reserve_mib": 0
          },
          "callback_completed_under_lock": false,
          "checks": 873,
          "commitment_mib": 2048,
          "contract_commitment_mib": 2048,
          "free_mib": 4171,
          "gpu": 3,
          "gpu_uuid": "GPU-b97c52a6-7497-cd20-3475-d9a15ec08f84",
          "new_reservation_created": false,
          "own_mib": 0,
          "peer_pending_mib": 5390,
          "required_mib": 7438,
          "reserve_once_mib": 0,
          "status": "WAITING_CAPACITY_BEFORE_FIT",
          "wait_seconds": 4048.801216699183
        },
        "files": [
          "pre_cuda_capacity.json"
        ],
        "pid": "[REDACTED_MACHINE]",
        "pid_starttimes": {
          "2018328": 2577289659
        },
        "task_id": "physionet_B0_s4_t101",
        "zero_training_steps_proven": true
      },
      {
        "actual_cuda_mib": 0,
        "capacity": {
          "assessment": {
            "eligibility": "eligible",
            "existing_compute_processes": 3,
            "post_launch_headroom_mib": 2123,
            "reserve_mib": 0
          },
          "callback_completed_under_lock": false,
          "checks": 873,
          "commitment_mib": 2048,
          "contract_commitment_mib": 2048,
          "free_mib": 4171,
          "gpu": 3,
          "gpu_uuid": "GPU-b97c52a6-7497-cd20-3475-d9a15ec08f84",
          "new_reservation_created": false,
          "own_mib": 0,
          "peer_pending_mib": 5390,
          "required_mib": 7438,
          "reserve_once_mib": 0,
          "status": "WAITING_CAPACITY_BEFORE_FIT",
          "wait_seconds": 4044.8290573097765
        },
        "files": [
          "pre_cuda_capacity.json"
        ],
        "pid": "[REDACTED_MACHINE]",
        "pid_starttimes": {
          "2018344": 2577289701
        },
        "task_id": "physionet_B0_s3_t102",
        "zero_training_steps_proven": true
      }
    ]
  },
  "current_research_preparation": {
    "budget_authorization_ref": "ai4s/programs/dsainet/research/p0-ord-ec-r1/preparation/BUDGET_AUTHORIZATION_163.json",
    "continuation_status_ref": "programs\\dsainet\\research\\p0-ord-ec-r1\\CONTINUATION_STATUS.json",
    "execution_authorization_ref": "programs\\dsainet\\research\\p0-ord-ec-r1\\science_bundle\\EXECUTION_AUTHORIZATION.json",
    "external_review": "PASS_LIMITED_DATA_ROLE_AND_SEAL_SCOPE",
    "necessary_reachability_pass": true,
    "new_science_authorized": true,
    "parent_qualification": 36,
    "prediction_qualification": 108,
    "record": "ai4s/programs/dsainet/research/p0-ord-ec-r1/PREPARATION_REPORT.md",
    "research_id": "p0-ord-ec-r1",
    "scientific_fits": 0,
    "ssh_host": "[REDACTED_MACHINE]",
    "status": "COMPLETE_VERIFIED_NO_SIGNAL",
    "technical_fits": 6,
    "upload_performed": true
  },
  "dataset_recovery_runs": {
    "004": {
      "active_run": {
        "bundle_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 53.401,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 92,
        "recorded_at": "2026-09-29T11:52:52.302678+00:00",
        "round_id": "dsa-pfc-xds-v0.1-repair4-004",
        "run_prefix": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T11:53:17.289895+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T11:54:10.792201+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:54:29.764645+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
                "execution_seconds": 8.670788764953613,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8.670788764953613
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:59:07.915109+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
                "execution_seconds": 286.8270494937897,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 286.8270494937897
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:59:59.895810+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
                "execution_seconds": 338.80351996421814,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 338.80351996421814
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T12:00:52.393675+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
                "execution_seconds": 391.31048250198364,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 391.31048250198364
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T12:01:43.317791+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
                "execution_seconds": 431.8802402019501,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 431.8802402019501
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-29T12:02:33.984315+00:00",
            "result": {
              "artifact_manifest_sha256": "980380a769bee64ba871c5e42c4311c3356676c35e68e5a2c1389d395f4e5a7a",
              "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
              "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
              "verified": true
            }
          }
        ]
      },
      "analysis": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair4/RESULT_ANALYSIS_004.md",
      "analysis_pending": false,
      "claim_release": false,
      "does_not_control_physionet_recipe": true,
      "evidence_id": "AI4S-DSAINET-dsa-pfc-xds-v0.1-repair4-004",
      "intake": {
        "artifact_manifest_sha256": "980380a769bee64ba871c5e42c4311c3356676c35e68e5a2c1389d395f4e5a7a",
        "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
        "intake_path": "results/logs/remote/2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
        "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx",
        "verified": true,
        "verified_at": null
      }
    }
  },
  "dataset_separation_authorization": {
    "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair4/AUTHORIZATION.md",
    "budget_extended": false,
    "registered_at": "2026-09-29T12:02:54.050134+00:00",
    "scopes": [
      "004",
      "physionet"
    ],
    "whole_claim_requires_both": true
  },
  "direction_control": {
    "attention_scale": {
      "date": "2026-09-17",
      "record": "ai4s/programs/dsainet/research/ATTENTION_SCALE_PAUSE_20260917.md",
      "scope": "new research, diagnostics and submissions in attention-scale; resume only on explicit user request",
      "status": "PAUSED_BY_USER"
    },
    "mechanism_research": {
      "authority": "User: 停止机制挖掘，回到原样冻结P0，开始性能确认，进行下一轮扩大研究",
      "date": "2026-09-28",
      "scope": "No further A/E complementarity, Coarse-E specificity, attention-scale or gain-attribution mechanism studies; retain historical evidence.",
      "status": "STOPPED_BY_USER"
    },
    "next_direction": {
      "active_run": null,
      "closure_record": "ai4s/programs/dsainet/research/P0_CANDIDATE_RETENTION_20261010.md",
      "entry": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1/RESEARCH_PLAN.md",
      "execution_authorized": false,
      "inherits_previous_campaign_budget": false,
      "name": "DSA-PFC-XDS-v0.1",
      "proposed_hours": 72,
      "scientific_result": true,
      "selected_scope": "unchanged P0/native B0, five seeds, all9 BNCI004 and all109 PhysioNet subject LOSO",
      "status": "CLOSED_BY_USER",
      "user_selected_scientific_scope": true
    },
    "p0_candidate_disposition": {
      "authority": "User explicitly retains P0 as historical performance candidate, structural experience and candidate innovation while closing its unchanged broad cross-dataset stable superiority claim.",
      "candidate_id": "DSA-AEL-P0-FROZEN-20260927",
      "candidate_innovation_verified": false,
      "claim_disposition": "CLOSE_UNCHANGED_P0_BROAD_CROSS_DATASET_STABLE_SUPERIORITY",
      "claim_ledger_reviews_unchanged": true,
      "date": "2026-10-10",
      "design_disposition": "Retain unchanged P0 implementation, all artifacts, dataset-specific historical evidence, candidate innovation and structural design lessons.",
      "direction_id": "P0-RETAIN-INNOVATION-CANDIDATE-CLOSE-BROAD-CLAIM-20261010",
      "formal_claim_release": false,
      "historical_verdicts_unchanged": true,
      "new_execution_authorized": false,
      "next_contrast": null,
      "next_design": null,
      "record": "ai4s/programs/dsainet/research/P0_CANDIDATE_RETENTION_20261010.md",
      "role": "user_direction_control_not_external_claim_judgement",
      "source_evidence_ids": [
        "AI4S-DSAINET-dsa-pfc-xds-v0.1-repair4-004",
        "AI4S-DSAINET-dsa-pfc-xds-v0.1-physionet-target-resume16",
        "LOCAL-DSAINET-PFC-ZHOU-20261010"
      ]
    },
    "post_checkpoint_gain_attribution": {
      "branches": [
        "PCR",
        "FRA",
        "SPAR",
        "DSA-OT"
      ],
      "date": "2026-09-21",
      "record": "ai4s/programs/dsainet/research/ATTRIBUTION_BRANCH_CLOSURE_20260921.md",
      "scope": "no new fits, diagnostic expansions or rescue; retain historical conclusions and evidence",
      "status": "STOPPED_BY_USER"
    }
  },
  "direction_control_history": [
    {
      "field": "next_direction",
      "prior": {
        "active_run": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
        "entry": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1/RESEARCH_PLAN.md",
        "execution_authorized": true,
        "inherits_previous_campaign_budget": false,
        "name": "DSA-PFC-XDS-v0.1",
        "proposed_hours": 72,
        "scientific_result": false,
        "selected_scope": "unchanged P0/native B0, five seeds, all9 BNCI004 and all109 PhysioNet subject LOSO",
        "status": "RUNNING",
        "user_selected_scientific_scope": true
      },
      "reason": "Reconcile stale historical RUNNING pointer after completed campaign and current user closure",
      "record": "ai4s/programs/dsainet/research/P0_CANDIDATE_RETENTION_20261010.md"
    },
    {
      "field": "next_research_preparation",
      "prior": {
        "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/AUTHORIZATION.md",
        "budget_extended": false,
        "new_formal_fits": 1052,
        "note": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/RESUME_NOTE.md",
        "p0_preserved": true,
        "recorded_at": "2026-09-30T05:53:38.338268+00:00",
        "research_id": "dsa-pfc-xds-v0.1",
        "reused_formal_fits": 38,
        "round_id": "dsa-pfc-xds-v0.1-physionet-resume1",
        "run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1",
        "scientific_result": false,
        "scope_id": "physionet-all-subjects-five-seed-loso",
        "seeds": [
          0,
          1,
          2,
          3,
          4
        ],
        "status": "RUNNING_PHYSIONET_FROZEN_CONFIRMATION",
        "subject_count": 109
      },
      "reason": "Preserve historical preparation pointer while registering the user-requested next RCD design; no historical result or execution state changed",
      "record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/DESIGN_TRANSITION.json"
    }
  ],
  "engineering_operation_history": [
    {
      "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/preparation/AUTHORIZATION.json",
      "authorized_tasks": [
        "N",
        "C",
        "S",
        "R"
      ],
      "completed_technical_arms": [],
      "contract": "ai4s/programs/dsainet/research/ds07-r1/preparation/engineering_contract.json",
      "contract_sha256": "076e3b6b8bb44455fbf4d910e6c6dcf217687cefcab9c53a601367ec80f003f1",
      "epochs_each": 5,
      "executor_id": "lab10",
      "failure": "NameError timezone undefined in runner budget consumer before model initialization",
      "governance_chain_id": "dsainet-transaction-v3.3",
      "host": "[REDACTED_MACHINE]",
      "kind": "engineering_technical_qualification",
      "last_observed_resource_wait_seconds": 1842.242424249649,
      "last_probe_at": "2026-11-01T23:11:22.419684+08:00",
      "last_verified_resource_wait_seconds": 1842.242424249649,
      "launched": true,
      "operation_id": "dsainet:ds07-r1:tech1",
      "postprocess_pid": "[REDACTED_MACHINE]",
      "postprocess_receipt": "ai4s/programs/dsainet/research/ds07-r1/preparation/POSTPROCESS_LAUNCH_RECEIPT.json",
      "postprocess_status": "STOP_TECH_CLOSURE_FAILED",
      "qualification_batches_each": 8,
      "registered_at": "2026-11-01T04:50:56.179587+00:00",
      "remaining_budget_hours_at_last_probe": -6.552328478906549,
      "remote_manifest_sha256": "30f866a2f95270cf9c28a019c89ece4cab1dd3ebb83a600271194cf527176cfb",
      "remote_pid": "[REDACTED_MACHINE]",
      "remote_root": "[REDACTED_MACHINE]",
      "remote_status": "TECH_DRIVER_FAILED",
      "repair_preparation": {
        "run_id": "2026-11-01_dsainet_ds07_r1_tech1-repair1",
        "science_dispatch_allowed": false,
        "status": "AUTHORIZED_PREPARING"
      },
      "research_id": "ds07-r1",
      "run_id": "2026-11-01_dsainet_ds07_r1_tech1",
      "science_cost_estimate": "UNKNOWN_NO_EPOCH_MEASUREMENT",
      "scientific_dispatch_allowed": false,
      "status": "FAILED",
      "status_report": "ai4s/programs/dsainet/research/ds07-r1/preparation/STATUS_REPORT_20261101_LATE.md",
      "technical_acceptance": "FAILED_BEFORE_QUALIFICATION",
      "technical_scope_only": true,
      "uploaded": true
    },
    {
      "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/preparation/AUTHORIZATION.json",
      "authorized_tasks": [
        "N",
        "C",
        "S",
        "R"
      ],
      "completed_technical_arms": [],
      "contract": "ai4s/programs/dsainet/research/ds07-r1/preparation/engineering_contract.json",
      "contract_sha256": "1c5a607320df4657f07225434990e013dc55f723aaf9b1984da6e2cca3b7efbc",
      "epochs_each": 5,
      "executor_id": "lab10",
      "failure": "unexpected authorized bundle destination; guard retained old Run suffix; zero children and qualifications",
      "governance_chain_id": "dsainet-transaction-v3.3",
      "host": "[REDACTED_MACHINE]",
      "kind": "engineering_technical_qualification",
      "last_observed_resource_wait_seconds": 0,
      "last_probe_at": null,
      "last_verified_resource_wait_seconds": 0,
      "launched": true,
      "operation_id": "dsainet:ds07-r1:tech1-repair1",
      "parent_failed_run": "2026-11-01_dsainet_ds07_r1_tech1",
      "postprocess_pid": null,
      "postprocess_status": "STOP_TECH_CLOSURE_FAILED",
      "qualification_batches_each": 8,
      "real_budget_preflight": "PASS",
      "registered_at": "2026-11-01T15:41:48.747461+00:00",
      "remaining_budget_at_launch": 3.0133486600895734,
      "remote_manifest_sha256": "cd7812cfa9477fb9dd327638e3be8f3addcbebcb9d3788eb7d2f21906c6a9790",
      "remote_pid": "[REDACTED_MACHINE]",
      "remote_root": "[REDACTED_MACHINE]",
      "remote_status": "FAILED_BEFORE_QUEUE",
      "research_id": "ds07-r1",
      "run_id": "2026-11-01_dsainet_ds07_r1_tech1-repair1",
      "science_cost_estimate": "PENDING_REPAIR_TECH",
      "scientific_dispatch_allowed": false,
      "status": "FAILED",
      "technical_acceptance": "PENDING_REPAIR_TECH",
      "technical_scope_only": true,
      "uploaded": true
    },
    {
      "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/preparation/AUTHORIZATION.json",
      "authorized_tasks": [
        "N",
        "C",
        "S",
        "R"
      ],
      "budget_report_time_utc": "2026-11-02T06:45:44.981441+00:00",
      "closed_for_followup_at": "2026-11-02T11:43:00.395+00:00",
      "completed_technical_arms": [
        "N",
        "C",
        "S",
        "R"
      ],
      "contract": "ai4s/programs/dsainet/research/ds07-r1/preparation/engineering_contract.json",
      "contract_sha256": "95cca71e70b08b6da3c134d1fcf15591df084bc16b781f2c9388af6d19a8fc6d",
      "epochs_each": 5,
      "executor_id": "lab10",
      "governance_chain_id": "dsainet-transaction-v3.3",
      "host": "[REDACTED_MACHINE]",
      "kind": "engineering_technical_qualification",
      "last_observed_resource_wait_seconds": 20067.248963356018,
      "last_probe_at": "2026-11-02T14:28:29.072162+08:00",
      "last_verified_resource_wait_seconds": 20067.248963356018,
      "launched": true,
      "monitor_powershell": "[REDACTED_MACHINE]",
      "operation_id": "dsainet:ds07-r1:tech1-repair1-packfix1",
      "original_status": "FAILED_TECH_CLOSURE",
      "parent_failed_run": "2026-11-01_dsainet_ds07_r1_tech1-repair1",
      "postprocess_pid": "[REDACTED_MACHINE]",
      "postprocess_status": "STOP_TECH_CLOSURE_FAILED",
      "qualification_batches_each": 8,
      "real_budget_preflight": "PASS_ON_LAB10_REAL_CONSUMER",
      "registered_at": "2026-11-01T15:47:25.299688+00:00",
      "remaining_budget_hours_at_last_probe": -6.183192823180224,
      "remaining_budget_hours_at_report_time": -6.470945410837203,
      "remote_manifest_sha256": "1412aac8206873e4adf1349893e42b01957b93d714ab616736a23d555fe2b85a",
      "remote_pid": "[REDACTED_MACHINE]",
      "remote_root": "[REDACTED_MACHINE]",
      "remote_status": "FOUR_ARMS_COMPLETED_CLOSURE_BLOCKED",
      "research_id": "ds07-r1",
      "run_id": "2026-11-01_dsainet_ds07_r1_tech1-repair1-packfix1",
      "science_cost_estimate": "PROVISIONAL_NOT_GATE_ELIGIBLE",
      "scientific_dispatch_allowed": false,
      "scientific_interpretation": "NONE; telemetry closure failure preserved",
      "status": "FAILED",
      "status_report": "ai4s/programs/dsainet/research/ds07-r1/repair1/STATUS_REPORT_20261102.md",
      "technical_acceptance": "BLOCKED_N_FULL_PROCESS_MEMORY_TAIL",
      "technical_scope_only": true,
      "technical_startup_preflight": "PASS_TO_CAPACITY_BOUNDARY_NO_GPU_CHILD",
      "uploaded": true
    }
  ],
  "engineering_recovery": {
    "attempt_class": "external_host_interruption_unarchived",
    "reason": "User authorized R03 continuation after server-side interruptions; preserve r3r3 as unarchived engineering evidence and rerun the unchanged frozen 36-unit matrix under a new immutable GPU0 Bundle.",
    "recorded_at": "2026-09-05T02:55:15.841447+00:00",
    "recovered_from": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3-full-w1"
  },
  "engineering_recovery_history": [
    {
      "contract_sha256": "d82104284d7dadd6a47831998c32727a97bca76aff0236c224fd56bfad02f243",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "603b251d599280190614e3de9bff7abca1a292d3e7f7308c94e7f3a1edece5dc",
      "repair_id": "readerfix1",
      "replacement_round_id": "ds07-r1-science1-readerfix1",
      "scientific_disposition": "NONE",
      "source_run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
      "status": "ENGINEERING_INVALID_SOURCE_ARCHIVED"
    }
  ],
  "evidence_status": "p0_ord_ec_r1_verified_complete_no_signal",
  "external_interruption_recovery": {
    "failed_run_id": "2026-10-13_dsainet_rcd_v0_1_resume1-full-w1",
    "reason_class": "USER_AUTHORIZED_REDEPLOYMENT",
    "recorded_at": "2026-10-14T00:14:24.748027+00:00",
    "replacement_round_id": "dsa-rcd-v0.1-resume2",
    "report": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-resume2/REDEPLOYMENT_REPORT.json",
    "research_gate": {
      "hypothesis_id": "raw-summary-conditioned-native-grid",
      "module_id": "trial-conditioned-common-depthwise-spacing",
      "paired_seed_cap": 5,
      "paired_seeds_after_freeze": [
        0,
        1
      ],
      "transition": "SCREEN_NEW"
    }
  },
  "failed_attempts": [
    {
      "engineering_reason": "Pilot task plan must be a JSON list; repaired only its one-element PowerShell serialization.",
      "failed_run": {
        "bundle_id": "2026-08-29_dsainet_ai4s_capacity_structure_r2",
        "estimated_training_hours": 0.879,
        "planned_units": 18,
        "recorded_at": "2026-08-29T13:13:47.266947+00:00",
        "round_id": "dsainet-r02-shared-mean-vs-generic-residual-v0.1",
        "run_prefix": "2026-08-29_dsainet_ai4s_capacity_structure_r2"
      },
      "failed_run_id": "2026-08-29_dsainet_ai4s_capacity_structure_r2-pilot-w1",
      "formal_status": {
        "detail": "entrypoint exit=2",
        "stage": "pilot",
        "status": "failed",
        "updated_at": "2026-08-29T13:15:20.241731+00:00"
      },
      "retry_recorded_at": "2026-08-29T13:18:25.129656+00:00",
      "round_id": "dsainet-r02-shared-mean-vs-generic-residual-v0.1"
    },
    {
      "engineering_reason": "User-authorized engineering-only recovery: repair the verified singleton pilot task-plan serialization; preserve O1 scientific contract and failed r3 evidence.",
      "failed_run": {
        "bundle_id": "2026-08-30_dsainet_ai4s_crossed_intra_ownership_r3",
        "estimated_training_hours": 0.879,
        "planned_units": 18,
        "recorded_at": "2026-08-29T22:43:45.875543+00:00",
        "round_id": "dsainet-r03-crossed-intra-ownership-v0.1",
        "run_prefix": "2026-08-30_dsainet_ai4s_crossed_intra_ownership_r3"
      },
      "failed_run_id": "2026-08-30_dsainet_ai4s_crossed_intra_ownership_r3-pilot-w1",
      "formal_status": {
        "detail": "entrypoint exit=2",
        "stage": "pilot",
        "status": "failed",
        "updated_at": "2026-08-29T22:44:53.399894+00:00"
      },
      "retry_recorded_at": "2026-08-30T02:00:50.408618+00:00",
      "round_id": "dsainet-r03-crossed-intra-ownership-v0.1"
    },
    {
      "attempt_class": "scheduler_contract_invalid",
      "engineering_reason": "User authorized engineering-only r2 recovery: route the unchanged zero-training B0 diagnostic matrix through ccmu_lane_executor so the mandatory scheduler_metrics and scheduler_report are emitted; preserve r1 archive.",
      "failed_run": {
        "bundle_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r1",
        "estimated_training_hours": 0.879,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 18,
        "recorded_at": "2026-08-31T12:10:18.557884+00:00",
        "round_id": "dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1",
        "run_prefix": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r1"
      },
      "failed_run_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r1-pilot-w1",
      "formal_status": {
        "detail": "branch-conditioned spatial sensitivity pilot completed with identity parity",
        "stage": "pilot",
        "status": "complete",
        "updated_at": "2026-08-31T12:11:28.143407+00:00"
      },
      "retry_recorded_at": "2026-08-31T12:18:08.252275+00:00",
      "round_id": "dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1",
      "scheduler_report": {
        "algorithm_id": "ccmu-lane-autopilot-v3",
        "autopilot_eligible": false,
        "bundle_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r1",
        "classification": "invalid",
        "controller_status": "process_succeeded",
        "formal_run_status": "complete",
        "generated_at": "2026-08-31T12:11:29.315078+00:00",
        "observed": {},
        "plan_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r1-schedule",
        "profile_fingerprint": "de31bf612d965172c9fee7e4e9bb77efc0b29cbe2252d00101ebf11658fe2802",
        "reasons": [
          "scheduler_metrics.json is missing"
        ],
        "run_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r1-pilot-w1",
        "schema_version": "ccmu-scheduler-report-v2",
        "stage": "pilot",
        "workers_per_gpu": 1
      }
    },
    {
      "engineering_reason": "User-authorized engineering-only r3 recovery: serialize the unchanged one-unit pilot plan as an explicit JSON list; preserve r2 failed archive and frozen diagnostic contract.",
      "failed_run": {
        "bundle_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r2",
        "estimated_training_hours": 0.879,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 18,
        "recorded_at": "2026-08-31T12:18:08.252275+00:00",
        "round_id": "dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1",
        "run_prefix": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r2"
      },
      "failed_run_id": "2026-08-31_dsainet_ai4s_branch_conditioned_spatial_sensitivity_r2-pilot-w1",
      "formal_status": {
        "detail": "entrypoint exit=2",
        "stage": "pilot",
        "status": "failed",
        "updated_at": "2026-08-31T12:19:42.649002+00:00"
      },
      "retry_recorded_at": "2026-08-31T12:22:15.027529+00:00",
      "round_id": "dsainet-r01-branch-conditioned-spatial-sensitivity-v0.1"
    },
    {
      "attempt_class": "external_host_interruption_unarchived",
      "engineering_reason": "Host reboot terminated the unarchived full run before formal failure or archive generation; rerun the unchanged frozen R03 matrix under a new immutable Bundle.",
      "failed_run": {
        "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3",
        "estimated_training_hours": 1.759,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 36,
        "recorded_at": "2026-09-01T02:31:40.352686+00:00",
        "round_id": "dsainet-r03-role-specific-token-pooling-v0.1",
        "run_prefix": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3"
      },
      "failed_run_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3-full-w1",
      "formal_status": {
        "formal_run_status_before_interruption": "running",
        "status": "unarchived_external_interruption"
      },
      "interruption_evidence": {
        "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3",
        "evidence_summary": "At remote observation the active full-run process was absent, no transfer archive existed, and host uptime was below 11 minutes. The started P2 task log predated the inferred reboot. The host reboot therefore terminated the run before the remote runner could write a formal failure or archive.",
        "formal_run_status": "running",
        "host_reboot_observed": true,
        "last_task_log_at": "2026-09-01T12:26:17.579+08:00",
        "observed_uptime_seconds_less_than": 660,
        "process_not_running": true,
        "remote_observed_at": "2026-09-01T13:13:15+08:00",
        "run_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3-full-w1",
        "schema_version": "mieeg-ai4s-external-interruption-evidence-v1",
        "scope_boundary": "This is engineering interruption evidence only. No partial C2/P2 output may be reused for scientific comparison, decision, or claim.",
        "stage": "full",
        "transfer_archive_present": false
      },
      "retry_recorded_at": "2026-09-01T05:17:44.161706+00:00",
      "round_id": "dsainet-r03-role-specific-token-pooling-v0.1"
    },
    {
      "attempt_class": "external_host_interruption_unarchived",
      "engineering_reason": "Second host reboot interrupted an unarchived full run after P2 seed0 subject8 stopped progressing; rerun the unchanged frozen matrix under a fresh Bundle with the audited 900-second per-task failure bound.",
      "failed_run": {
        "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r1",
        "estimated_training_hours": 1.759,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 36,
        "recorded_at": "2026-09-01T05:17:44.161706+00:00",
        "round_id": "dsainet-r03-role-specific-token-pooling-v0.1",
        "run_prefix": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r1"
      },
      "failed_run_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r1-full-w1",
      "formal_status": {
        "formal_run_status_before_interruption": "running",
        "status": "unarchived_external_interruption"
      },
      "interruption_evidence": {
        "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r1",
        "evidence_summary": "C2 completed 18 lane task launches and P2 seed-0 launched 9 tasks. The final P2 seed-0 subject-8 task wrote epochs through 33/100, then made no further progress. The host booted at 18:00:09 and was only six minutes old at observation; the active process was absent, formal status was still running, and no transfer archive existed.",
        "formal_run_status": "running",
        "host_boot_at": "2026-09-01T18:00:09+08:00",
        "host_reboot_observed": true,
        "last_task_progress_at": "2026-09-01T16:27:43+08:00",
        "matrix_task_count": 36,
        "observed_lane_task_logs": 27,
        "observed_uptime_seconds_less_than": 420,
        "process_not_running": true,
        "remote_observed_at": "2026-09-01T18:07:05+08:00",
        "run_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r1-full-w1",
        "schema_version": "mieeg-ai4s-external-interruption-evidence-v1",
        "scope_boundary": "This is engineering interruption evidence only. The 27 unarchived task artifacts are not eligible for scientific comparison, result freezing, decision, or claim.",
        "stage": "full",
        "stalled_task": "screen_p2_s0_t8",
        "stalled_task_last_epoch": 33,
        "transfer_archive_present": false
      },
      "retry_recorded_at": "2026-09-01T12:13:28.844690+00:00",
      "round_id": "dsainet-r03-role-specific-token-pooling-v0.1"
    },
    {
      "attempt_class": "external_host_interruption_unarchived",
      "engineering_reason": "User authorized continuation on isolated GPU0; preserve third reboot as unarchived engineering interruption and rerun unchanged frozen R03 matrix under a new immutable Bundle.",
      "failed_run": {
        "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r2",
        "estimated_training_hours": 1.759,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 36,
        "recorded_at": "2026-09-01T12:13:28.844690+00:00",
        "round_id": "dsainet-r03-role-specific-token-pooling-v0.1",
        "run_prefix": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r2"
      },
      "failed_run_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r2-full-w1",
      "formal_status": {
        "formal_run_status_before_interruption": "running",
        "status": "unarchived_external_interruption"
      },
      "interruption_evidence": {
        "bundle_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r2",
        "evidence_summary": "The third full attempt was absent after the host reboot. Formal status remained running and no transfer archive existed. Only six lane task logs were observed, so the full matrix was incomplete.",
        "formal_run_status": "running",
        "host_boot_at": "2026-09-01T22:07:20+08:00",
        "host_reboot_observed": true,
        "matrix_task_count": 36,
        "observed_lane_task_logs": 6,
        "observed_uptime_seconds_less_than": 660,
        "process_not_running": true,
        "remote_observed_at": "2026-09-01T22:17:53+08:00",
        "run_id": "2026-09-01_dsainet_ai4s_role_specific_token_pooling_r3r2-full-w1",
        "schema_version": "mieeg-ai4s-external-interruption-evidence-v1",
        "scope_boundary": "This is engineering interruption evidence only. The six unarchived task artifacts are not eligible for scientific comparison, result freezing, decision, or claim.",
        "stage": "full",
        "transfer_archive_present": false
      },
      "retry_recorded_at": "2026-09-02T10:21:26.809453+00:00",
      "round_id": "dsainet-r03-role-specific-token-pooling-v0.1"
    },
    {
      "attempt_class": "external_host_interruption_unarchived",
      "engineering_reason": "User authorized R03 continuation after server-side interruptions; preserve r3r3 as unarchived engineering evidence and rerun the unchanged frozen 36-unit matrix under a new immutable GPU0 Bundle.",
      "failed_run": {
        "bundle_id": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3",
        "estimated_training_hours": 1.759,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 36,
        "recorded_at": "2026-09-02T10:21:26.809453+00:00",
        "round_id": "dsainet-r03-role-specific-token-pooling-v0.1",
        "run_prefix": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3"
      },
      "failed_run_id": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3-full-w1",
      "formal_status": {
        "formal_run_status_before_interruption": "running",
        "status": "unarchived_external_interruption"
      },
      "interruption_evidence": {
        "bundle_id": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3",
        "evidence_summary": "The full-run process was absent, formal status remained running, and no transfer archive existed after the host rebooted at 22:13:53+08:00. The preceding boot at 21:41 also lasted only 31 minutes.",
        "formal_run_status": "running",
        "host_boot_at": "2026-09-02T22:13:53+08:00",
        "host_reboot_observed": true,
        "observed_uptime_seconds_less_than": 900,
        "process_not_running": true,
        "remote_observed_at": "2026-09-02T22:28:06+08:00",
        "run_id": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3-full-w1",
        "schema_version": "mieeg-ai4s-external-interruption-evidence-v1",
        "scope_boundary": "This is engineering interruption evidence only. Any partial full-run artifacts are not eligible for scientific comparison, result freezing, decision, or claim.",
        "stage": "full",
        "transfer_archive_present": false
      },
      "retry_recorded_at": "2026-09-05T02:55:15.841447+00:00",
      "round_id": "dsainet-r03-role-specific-token-pooling-v0.1"
    },
    {
      "attempt_class": "user_confirmed_external_host_interruption_unarchived",
      "engineering_reason": "User explicitly authorized the Lab10 replacement after confirming the ccmu host reboot was manual; the full 54-task matrix replaces the interrupted unarchived Run and its partial artifacts remain ineligible.",
      "failed_run": {
        "bundle_id": "2026-09-07_dsainet_ttpp_v0_1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.056,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 55,
        "recorded_at": "2026-09-07T07:58:41.100037+00:00",
        "round_id": "dsainet-r01-ttpp-v0.1",
        "run_prefix": "2026-09-07_dsainet_ttpp_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-07T08:00:09.551555+00:00",
            "result": {
              "action": "UPLOADED",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-07T08:00:26.332393+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:00:53.811004+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 27.32974934577942,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 27.32974934577942
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:03:47.407482+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 200.93548679351807,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 200.93548679351807
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:04:04.686789+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 218.2122642993927,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 218.2122642993927
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:05:36.053365+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 309.58458852767944,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 309.58458852767944
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:07:07.537298+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 401.0740888118744,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 401.0740888118744
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:08:38.958837+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 492.4795138835907,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 492.4795138835907
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:10:10.243717+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 583.7872195243835,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 583.7872195243835
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:11:41.549187+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 675.0961074829102,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 675.0961074829102
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:13:12.764597+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 766.3140320777893,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 766.3140320777893
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:14:45.203541+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 858.6954791545868,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 858.6954791545868
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:16:16.547880+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 950.1013650894165,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 950.1013650894165
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:17:47.843749+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1041.3872587680817,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1041.3872587680817
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:19:19.170716+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1132.7187187671661,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1132.7187187671661
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:20:50.271624+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1223.8297233581543,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1223.8297233581543
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:22:21.472466+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1315.0340762138367,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1315.0340762138367
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:23:52.968553+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1406.5336124897003,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1406.5336124897003
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:25:24.493817+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1498.061488866806,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1498.061488866806
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:26:55.828406+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1589.4019961357117,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1589.4019961357117
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:28:27.209291+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1680.777736902237,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1680.777736902237
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:29:58.484512+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1772.063435792923,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1772.063435792923
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:31:29.665251+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1863.2491528987885,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1863.2491528987885
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:33:00.736332+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 1954.320158958435,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1954.320158958435
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:34:32.026473+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 2045.6141362190247,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2045.6141362190247
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:36:03.328090+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 2136.9137768745422,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2136.9137768745422
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:37:34.875198+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 2228.459602832794,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2228.459602832794
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:39:06.208149+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 2319.804042339325,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2319.804042339325
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:40:37.454588+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 2411.056348323822,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2411.056348323822
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T08:42:08.685453+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 2502.293130636215,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2502.293130636215
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T10:52:31.438862+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "67506f4e49013fb8da79b594b453692466cd594cc891ad16367f5277d5018075",
                "execution_seconds": 10325.152110338211,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
                "transaction_id": "2026-09-07_dsainet_ttpp_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10325.152110338211
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-09-07_dsainet_ttpp_v0_1-full-w1",
      "interruption_report": "ai4s/programs/dsainet/research/train-time-position-prior/LAB10_RECOVERY.md",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-09-07T15:27:27.666744+00:00",
      "round_id": "dsainet-r01-ttpp-v0.1"
    },
    {
      "attempt_class": "engineering_capacity_recovery",
      "campaign_id": "dsainet-cmcr-v0.1-2026-09-15",
      "failed_run_id": "2026-09-16_dsainet_cmcr_v0_1_repair3-full-w1",
      "recorded_at": "2026-09-16T15:49:22.447834+00:00",
      "recovery_run_id": "2026-09-16_dsainet_cmcr_v0_1_recovery4-full-w1",
      "retry_task_ids": [
        "b0_s1_t8",
        "c0_s1_t6",
        "c0_s1_t7",
        "c0_s1_t8",
        "c0_s1_t5",
        "b0_s1_t7",
        "s0_s1_t8",
        "n0_s1_t8"
      ],
      "reused_task_ids": [
        "b0_s0_t0",
        "b0_s0_t1",
        "b0_s0_t2",
        "b0_s0_t3",
        "b0_s0_t4",
        "b0_s0_t5",
        "b0_s0_t6",
        "b0_s0_t7",
        "b0_s0_t8",
        "b0_s1_t0",
        "b0_s1_t1",
        "b0_s1_t2",
        "b0_s1_t3",
        "b0_s1_t4",
        "b0_s1_t5",
        "b0_s1_t6",
        "c0_s0_t0",
        "c0_s0_t1",
        "c0_s0_t2",
        "c0_s0_t3",
        "c0_s0_t4",
        "c0_s0_t5",
        "c0_s0_t6",
        "c0_s0_t7",
        "c0_s0_t8",
        "c0_s1_t0",
        "c0_s1_t1",
        "c0_s1_t2",
        "c0_s1_t3",
        "c0_s1_t4",
        "n0_s0_t0",
        "n0_s0_t1",
        "n0_s0_t2",
        "n0_s0_t3",
        "n0_s0_t4",
        "n0_s0_t5",
        "n0_s0_t6",
        "n0_s0_t7",
        "n0_s0_t8",
        "n0_s1_t0",
        "n0_s1_t1",
        "n0_s1_t2",
        "n0_s1_t3",
        "n0_s1_t4",
        "n0_s1_t5",
        "n0_s1_t6",
        "n0_s1_t7",
        "p0_s0_t0",
        "p0_s0_t1",
        "p0_s0_t2",
        "p0_s0_t3",
        "p0_s0_t4",
        "p0_s0_t5",
        "p0_s0_t6",
        "p0_s0_t7",
        "p0_s0_t8",
        "p0_s1_t0",
        "p0_s1_t1",
        "p0_s1_t2",
        "p0_s1_t3",
        "p0_s1_t4",
        "p0_s1_t5",
        "p0_s1_t6",
        "p0_s1_t7",
        "p0_s1_t8",
        "s0_s0_t0",
        "s0_s0_t1",
        "s0_s0_t2",
        "s0_s0_t3",
        "s0_s0_t4",
        "s0_s0_t5",
        "s0_s0_t6",
        "s0_s0_t7",
        "s0_s0_t8",
        "s0_s1_t0",
        "s0_s1_t1",
        "s0_s1_t2",
        "s0_s1_t3",
        "s0_s1_t4",
        "s0_s1_t5",
        "s0_s1_t6",
        "s0_s1_t7"
      ],
      "scientific_decision": false
    },
    {
      "attempt_class": "engineering_capacity_recovery",
      "failed_run_id": "2026-09-16_dsainet_cmcr_v0_1_recovery4-full-w1",
      "recorded_at": "2026-09-16T16:46:12.750352+00:00",
      "recovery_run_id": "2026-09-17_dsainet_cmcr_v0_1_recovery5-full-w1",
      "retry_task_ids": [
        "b0_s1_t8",
        "c0_s1_t6",
        "c0_s1_t7",
        "c0_s1_t8",
        "c0_s1_t5",
        "b0_s1_t7",
        "s0_s1_t8",
        "n0_s1_t8"
      ],
      "scientific_decision": false,
      "source_results_from": "2026-09-16_dsainet_cmcr_v0_1_repair3-full-w1"
    },
    {
      "attempt_class": "explicit_fut_capacity_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair2/AUTHORIZATION.md",
      "campaign_id": "dsainet-fut-v0.1-20260924",
      "failed_run_id": "2026-09-24_dsainet_fut_v0_1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-24_dsainet_fut_v0_1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.884,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 433,
        "recorded_at": "2026-09-24T01:43:59.044857+00:00",
        "round_id": "dsa-fut-v0.1",
        "run_prefix": "2026-09-24_dsainet_fut_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T01:44:45.516451+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dsainet_fut_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T01:44:46.931203+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dsainet_fut_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T01:45:02.199690+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-24_dsainet_fut_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "da74c32481f4261c1a7529edda6e2366d4b29a3287aab98e9031ac8b9b5eb5a4",
                "execution_seconds": 11.393534421920776,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dsainet_fut_v0_1-full-w1",
                "transaction_id": "2026-09-24_dsainet_fut_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 11.393534421920776
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T06:08:43.449960+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dsainet_fut_v0_1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "da74c32481f4261c1a7529edda6e2366d4b29a3287aab98e9031ac8b9b5eb5a4",
                "execution_seconds": 1660.6660592556,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dsainet_fut_v0_1-full-w1",
                "transaction_id": "2026-09-24_dsainet_fut_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1660.6660592556
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-24T06:21:18.753117+00:00",
      "rerun_task_ids": [
        "P0_s0_t1__SELF__real",
        "C0_s0_t1__SELF__real",
        "B0_s0_t1__SELF__within_subject_permuted",
        "C0_s0_t1__SELF__within_subject_permuted",
        "S0_s0_t1__SELF__within_subject_permuted",
        "B0_s0_t2__SELF__real",
        "P0_s0_t2__SELF__real",
        "C0_s0_t2__SELF__real",
        "S0_s0_t2__SELF__real",
        "B0_s0_t2__SELF__within_subject_permuted",
        "P0_s0_t2__SELF__within_subject_permuted",
        "C0_s0_t2__SELF__within_subject_permuted",
        "S0_s0_t2__SELF__within_subject_permuted",
        "B0_s0_t3__SELF__real",
        "P0_s0_t3__SELF__real",
        "C0_s0_t3__SELF__real",
        "S0_s0_t3__SELF__real",
        "B0_s0_t3__SELF__within_subject_permuted",
        "P0_s0_t3__SELF__within_subject_permuted",
        "S0_s0_t3__SELF__within_subject_permuted",
        "B0_s0_t4__SELF__real",
        "P0_s0_t4__SELF__real",
        "C0_s0_t4__SELF__real",
        "S0_s0_t4__SELF__real",
        "B0_s0_t4__SELF__within_subject_permuted",
        "P0_s0_t4__SELF__within_subject_permuted",
        "C0_s0_t4__SELF__within_subject_permuted",
        "S0_s0_t4__SELF__within_subject_permuted",
        "B0_s0_t5__SELF__real",
        "P0_s0_t5__SELF__real",
        "C0_s0_t5__SELF__real",
        "S0_s0_t5__SELF__real",
        "B0_s0_t5__SELF__within_subject_permuted",
        "P0_s0_t5__SELF__within_subject_permuted",
        "C0_s0_t5__SELF__within_subject_permuted",
        "S0_s0_t5__SELF__within_subject_permuted",
        "B0_s0_t6__SELF__real",
        "P0_s0_t6__SELF__real",
        "C0_s0_t6__SELF__real",
        "S0_s0_t6__SELF__real",
        "B0_s0_t6__SELF__within_subject_permuted",
        "P0_s0_t6__SELF__within_subject_permuted",
        "C0_s0_t6__SELF__within_subject_permuted",
        "S0_s0_t6__SELF__within_subject_permuted",
        "B0_s0_t7__SELF__real",
        "P0_s0_t7__SELF__real",
        "C0_s0_t7__SELF__real",
        "S0_s0_t7__SELF__real",
        "B0_s0_t7__SELF__within_subject_permuted",
        "P0_s0_t7__SELF__within_subject_permuted",
        "C0_s0_t7__SELF__within_subject_permuted",
        "S0_s0_t7__SELF__within_subject_permuted",
        "B0_s0_t8__SELF__real",
        "P0_s0_t8__SELF__real",
        "C0_s0_t8__SELF__real",
        "S0_s0_t8__SELF__real",
        "B0_s0_t8__SELF__within_subject_permuted",
        "P0_s0_t8__SELF__within_subject_permuted",
        "C0_s0_t8__SELF__within_subject_permuted",
        "S0_s0_t8__SELF__within_subject_permuted",
        "B0_s1_t0__SELF__real",
        "P0_s1_t0__SELF__real",
        "C0_s1_t0__SELF__real",
        "S0_s1_t0__SELF__real",
        "B0_s1_t0__SELF__within_subject_permuted",
        "P0_s1_t0__SELF__within_subject_permuted",
        "C0_s1_t0__SELF__within_subject_permuted",
        "S0_s1_t0__SELF__within_subject_permuted",
        "B0_s1_t1__SELF__real",
        "P0_s1_t1__SELF__real",
        "C0_s1_t1__SELF__real",
        "S0_s1_t1__SELF__real",
        "B0_s1_t1__SELF__within_subject_permuted",
        "P0_s1_t1__SELF__within_subject_permuted",
        "C0_s1_t1__SELF__within_subject_permuted",
        "S0_s1_t1__SELF__within_subject_permuted",
        "B0_s1_t2__SELF__real",
        "P0_s1_t2__SELF__real",
        "C0_s1_t2__SELF__real",
        "S0_s1_t2__SELF__real",
        "B0_s1_t2__SELF__within_subject_permuted",
        "P0_s1_t2__SELF__within_subject_permuted",
        "C0_s1_t2__SELF__within_subject_permuted",
        "S0_s1_t2__SELF__within_subject_permuted",
        "B0_s1_t3__SELF__real",
        "P0_s1_t3__SELF__real",
        "C0_s1_t3__SELF__real",
        "S0_s1_t3__SELF__real",
        "B0_s1_t3__SELF__within_subject_permuted",
        "P0_s1_t3__SELF__within_subject_permuted",
        "C0_s1_t3__SELF__within_subject_permuted",
        "S0_s1_t3__SELF__within_subject_permuted",
        "B0_s1_t4__SELF__real",
        "P0_s1_t4__SELF__real",
        "C0_s1_t4__SELF__real",
        "S0_s1_t4__SELF__real",
        "B0_s1_t4__SELF__within_subject_permuted",
        "P0_s1_t4__SELF__within_subject_permuted",
        "C0_s1_t4__SELF__within_subject_permuted",
        "S0_s1_t4__SELF__within_subject_permuted",
        "B0_s1_t5__SELF__real",
        "P0_s1_t5__SELF__real",
        "C0_s1_t5__SELF__real",
        "S0_s1_t5__SELF__real",
        "B0_s1_t5__SELF__within_subject_permuted",
        "P0_s1_t5__SELF__within_subject_permuted",
        "C0_s1_t5__SELF__within_subject_permuted",
        "S0_s1_t5__SELF__within_subject_permuted",
        "B0_s1_t6__SELF__real",
        "P0_s1_t6__SELF__real",
        "C0_s1_t6__SELF__real",
        "S0_s1_t6__SELF__real",
        "B0_s1_t6__SELF__within_subject_permuted",
        "P0_s1_t6__SELF__within_subject_permuted",
        "C0_s1_t6__SELF__within_subject_permuted",
        "S0_s1_t6__SELF__within_subject_permuted",
        "B0_s1_t7__SELF__real",
        "P0_s1_t7__SELF__real",
        "C0_s1_t7__SELF__real",
        "S0_s1_t7__SELF__real",
        "B0_s1_t7__SELF__within_subject_permuted",
        "P0_s1_t7__SELF__within_subject_permuted",
        "C0_s1_t7__SELF__within_subject_permuted",
        "S0_s1_t7__SELF__within_subject_permuted",
        "B0_s1_t8__SELF__real",
        "P0_s1_t8__SELF__real",
        "C0_s1_t8__SELF__real",
        "S0_s1_t8__SELF__real",
        "B0_s1_t8__SELF__within_subject_permuted",
        "P0_s1_t8__SELF__within_subject_permuted",
        "C0_s1_t8__SELF__within_subject_permuted",
        "S0_s1_t8__SELF__within_subject_permuted",
        "S0_s0_t0__SELF__real",
        "P0_s0_t0__SELF__real",
        "C0_s0_t3__SELF__within_subject_permuted",
        "P0_s0_t0__DIRECT__real",
        "B0_s0_t2__DIRECT__real",
        "C0_s0_t2__DIRECT__within_subject_permuted",
        "B0_s0_t3__CROSS__within_subject_permuted",
        "P0_s0_t3__CROSS__within_subject_permuted",
        "C0_s0_t4__CROSS__within_subject_permuted",
        "B0_s0_t5__DIRECT__real",
        "P0_s0_t5__DIRECT__real",
        "S0_s0_t5__DIRECT__real",
        "B0_s0_t5__DIRECT__within_subject_permuted",
        "P0_s0_t5__DIRECT__within_subject_permuted",
        "C0_s0_t5__DIRECT__within_subject_permuted",
        "S0_s0_t5__DIRECT__within_subject_permuted",
        "B0_s0_t6__DIRECT__real",
        "P0_s0_t6__DIRECT__real",
        "C0_s0_t6__DIRECT__real",
        "S0_s0_t6__DIRECT__real",
        "B0_s0_t6__DIRECT__within_subject_permuted",
        "P0_s0_t6__DIRECT__within_subject_permuted",
        "C0_s0_t6__DIRECT__within_subject_permuted",
        "S0_s0_t6__DIRECT__within_subject_permuted",
        "B0_s0_t7__DIRECT__real",
        "P0_s0_t7__DIRECT__real",
        "C0_s0_t7__DIRECT__real",
        "S0_s0_t7__DIRECT__real",
        "B0_s0_t7__DIRECT__within_subject_permuted",
        "P0_s0_t7__DIRECT__within_subject_permuted",
        "C0_s0_t7__DIRECT__within_subject_permuted",
        "S0_s0_t7__DIRECT__within_subject_permuted",
        "B0_s0_t8__DIRECT__real",
        "P0_s0_t8__DIRECT__real",
        "C0_s0_t8__DIRECT__real",
        "S0_s0_t8__DIRECT__real",
        "B0_s0_t8__DIRECT__within_subject_permuted",
        "P0_s0_t8__DIRECT__within_subject_permuted",
        "C0_s0_t8__DIRECT__within_subject_permuted",
        "S0_s0_t8__DIRECT__within_subject_permuted",
        "B0_s1_t0__DIRECT__real",
        "P0_s1_t0__DIRECT__real",
        "C0_s1_t0__DIRECT__real",
        "S0_s1_t0__DIRECT__real",
        "B0_s1_t0__DIRECT__within_subject_permuted",
        "P0_s1_t0__DIRECT__within_subject_permuted",
        "C0_s1_t0__DIRECT__within_subject_permuted",
        "S0_s1_t0__DIRECT__within_subject_permuted",
        "B0_s1_t1__DIRECT__real",
        "P0_s1_t1__DIRECT__real",
        "C0_s1_t1__DIRECT__real",
        "S0_s1_t1__DIRECT__real",
        "B0_s1_t1__DIRECT__within_subject_permuted",
        "P0_s1_t1__DIRECT__within_subject_permuted",
        "C0_s1_t1__DIRECT__within_subject_permuted",
        "S0_s1_t1__DIRECT__within_subject_permuted",
        "B0_s1_t2__DIRECT__real",
        "P0_s1_t2__DIRECT__real",
        "C0_s1_t2__DIRECT__real",
        "S0_s1_t2__DIRECT__real",
        "B0_s1_t2__DIRECT__within_subject_permuted",
        "P0_s1_t2__DIRECT__within_subject_permuted",
        "C0_s1_t2__DIRECT__within_subject_permuted",
        "S0_s1_t2__DIRECT__within_subject_permuted",
        "B0_s1_t3__DIRECT__real",
        "P0_s1_t3__DIRECT__real",
        "C0_s1_t3__DIRECT__real",
        "S0_s1_t3__DIRECT__real",
        "B0_s1_t3__DIRECT__within_subject_permuted",
        "P0_s1_t3__DIRECT__within_subject_permuted",
        "C0_s1_t3__DIRECT__within_subject_permuted",
        "S0_s1_t3__DIRECT__within_subject_permuted",
        "B0_s1_t4__DIRECT__real",
        "P0_s1_t4__DIRECT__real",
        "C0_s1_t4__DIRECT__real",
        "S0_s1_t4__DIRECT__real",
        "B0_s1_t4__DIRECT__within_subject_permuted",
        "P0_s1_t4__DIRECT__within_subject_permuted",
        "C0_s1_t4__DIRECT__within_subject_permuted",
        "S0_s1_t4__DIRECT__within_subject_permuted",
        "B0_s1_t5__DIRECT__real",
        "P0_s1_t5__DIRECT__real",
        "C0_s1_t5__DIRECT__real",
        "S0_s1_t5__DIRECT__real",
        "B0_s1_t5__DIRECT__within_subject_permuted",
        "P0_s1_t5__DIRECT__within_subject_permuted",
        "C0_s1_t5__DIRECT__within_subject_permuted",
        "S0_s1_t5__DIRECT__within_subject_permuted",
        "B0_s1_t6__DIRECT__real",
        "P0_s1_t6__DIRECT__real",
        "C0_s1_t6__DIRECT__real",
        "S0_s1_t6__DIRECT__real",
        "B0_s1_t6__DIRECT__within_subject_permuted",
        "P0_s1_t6__DIRECT__within_subject_permuted",
        "C0_s1_t6__DIRECT__within_subject_permuted",
        "S0_s1_t6__DIRECT__within_subject_permuted",
        "B0_s1_t7__DIRECT__real",
        "P0_s1_t7__DIRECT__real",
        "C0_s1_t7__DIRECT__real",
        "S0_s1_t7__DIRECT__real",
        "B0_s1_t7__DIRECT__within_subject_permuted",
        "P0_s1_t7__DIRECT__within_subject_permuted",
        "C0_s1_t7__DIRECT__within_subject_permuted",
        "S0_s1_t7__DIRECT__within_subject_permuted",
        "B0_s1_t8__DIRECT__real",
        "P0_s1_t8__DIRECT__real",
        "C0_s1_t8__DIRECT__real",
        "S0_s1_t8__DIRECT__real",
        "B0_s1_t8__DIRECT__within_subject_permuted",
        "P0_s1_t8__DIRECT__within_subject_permuted",
        "C0_s1_t8__DIRECT__within_subject_permuted",
        "S0_s1_t8__DIRECT__within_subject_permuted",
        "C0_s0_t5__DIRECT__real",
        "S0_s0_t5__CROSS__real",
        "C0_s0_t6__CROSS__real",
        "C0_s0_t6__CROSS__within_subject_permuted",
        "C0_s0_t8__CROSS__within_subject_permuted",
        "S0_s0_t8__CROSS__within_subject_permuted",
        "B0_s1_t0__CROSS__real",
        "P0_s1_t0__CROSS__real",
        "C0_s1_t0__CROSS__real",
        "S0_s1_t0__CROSS__real",
        "B0_s1_t0__CROSS__within_subject_permuted",
        "P0_s1_t0__CROSS__within_subject_permuted",
        "C0_s1_t0__CROSS__within_subject_permuted",
        "S0_s1_t0__CROSS__within_subject_permuted",
        "B0_s1_t1__CROSS__real",
        "P0_s1_t1__CROSS__real",
        "C0_s1_t1__CROSS__real",
        "S0_s1_t1__CROSS__real",
        "B0_s1_t1__CROSS__within_subject_permuted",
        "P0_s1_t1__CROSS__within_subject_permuted",
        "S0_s1_t1__CROSS__within_subject_permuted",
        "B0_s1_t2__CROSS__real",
        "P0_s1_t2__CROSS__real",
        "C0_s1_t2__CROSS__real",
        "S0_s1_t2__CROSS__real",
        "B0_s1_t2__CROSS__within_subject_permuted",
        "P0_s1_t2__CROSS__within_subject_permuted",
        "C0_s1_t2__CROSS__within_subject_permuted",
        "S0_s1_t2__CROSS__within_subject_permuted",
        "B0_s1_t3__CROSS__real",
        "P0_s1_t3__CROSS__real",
        "C0_s1_t3__CROSS__real",
        "S0_s1_t3__CROSS__real",
        "B0_s1_t3__CROSS__within_subject_permuted",
        "P0_s1_t3__CROSS__within_subject_permuted",
        "C0_s1_t3__CROSS__within_subject_permuted",
        "S0_s1_t3__CROSS__within_subject_permuted",
        "B0_s1_t4__CROSS__real",
        "P0_s1_t4__CROSS__real",
        "C0_s1_t4__CROSS__real",
        "S0_s1_t4__CROSS__real",
        "B0_s1_t4__CROSS__within_subject_permuted",
        "P0_s1_t4__CROSS__within_subject_permuted",
        "C0_s1_t4__CROSS__within_subject_permuted",
        "S0_s1_t4__CROSS__within_subject_permuted",
        "B0_s1_t5__CROSS__real",
        "P0_s1_t5__CROSS__real",
        "C0_s1_t5__CROSS__real",
        "S0_s1_t5__CROSS__real",
        "B0_s1_t5__CROSS__within_subject_permuted",
        "P0_s1_t5__CROSS__within_subject_permuted",
        "C0_s1_t5__CROSS__within_subject_permuted",
        "S0_s1_t5__CROSS__within_subject_permuted",
        "B0_s1_t6__CROSS__real",
        "P0_s1_t6__CROSS__real",
        "C0_s1_t6__CROSS__real",
        "S0_s1_t6__CROSS__real",
        "B0_s1_t6__CROSS__within_subject_permuted",
        "P0_s1_t6__CROSS__within_subject_permuted",
        "C0_s1_t6__CROSS__within_subject_permuted",
        "S0_s1_t6__CROSS__within_subject_permuted",
        "B0_s1_t7__CROSS__real",
        "P0_s1_t7__CROSS__real",
        "C0_s1_t7__CROSS__real",
        "S0_s1_t7__CROSS__real",
        "B0_s1_t7__CROSS__within_subject_permuted",
        "P0_s1_t7__CROSS__within_subject_permuted",
        "C0_s1_t7__CROSS__within_subject_permuted",
        "S0_s1_t7__CROSS__within_subject_permuted",
        "B0_s1_t8__CROSS__real",
        "P0_s1_t8__CROSS__real",
        "C0_s1_t8__CROSS__real",
        "S0_s1_t8__CROSS__real",
        "B0_s1_t8__CROSS__within_subject_permuted",
        "P0_s1_t8__CROSS__within_subject_permuted",
        "C0_s1_t8__CROSS__within_subject_permuted",
        "S0_s1_t8__CROSS__within_subject_permuted",
        "C0_s1_t1__CROSS__within_subject_permuted",
        "S0_s0_t7__CROSS__within_subject_permuted"
      ],
      "reused_task_ids": [
        "B0_s0_t0__CROSS__real",
        "B0_s0_t0__CROSS__within_subject_permuted",
        "B0_s0_t0__DIRECT__real",
        "B0_s0_t0__DIRECT__within_subject_permuted",
        "B0_s0_t0__SELF__real",
        "B0_s0_t0__SELF__within_subject_permuted",
        "B0_s0_t1__CROSS__real",
        "B0_s0_t1__CROSS__within_subject_permuted",
        "B0_s0_t1__DIRECT__real",
        "B0_s0_t1__DIRECT__within_subject_permuted",
        "B0_s0_t1__SELF__real",
        "B0_s0_t2__CROSS__real",
        "B0_s0_t2__CROSS__within_subject_permuted",
        "B0_s0_t2__DIRECT__within_subject_permuted",
        "B0_s0_t3__CROSS__real",
        "B0_s0_t3__DIRECT__real",
        "B0_s0_t3__DIRECT__within_subject_permuted",
        "B0_s0_t4__CROSS__real",
        "B0_s0_t4__CROSS__within_subject_permuted",
        "B0_s0_t4__DIRECT__real",
        "B0_s0_t4__DIRECT__within_subject_permuted",
        "B0_s0_t5__CROSS__real",
        "B0_s0_t5__CROSS__within_subject_permuted",
        "B0_s0_t6__CROSS__real",
        "B0_s0_t6__CROSS__within_subject_permuted",
        "B0_s0_t7__CROSS__real",
        "B0_s0_t7__CROSS__within_subject_permuted",
        "B0_s0_t8__CROSS__real",
        "B0_s0_t8__CROSS__within_subject_permuted",
        "C0_s0_t0__CROSS__real",
        "C0_s0_t0__CROSS__within_subject_permuted",
        "C0_s0_t0__DIRECT__real",
        "C0_s0_t0__DIRECT__within_subject_permuted",
        "C0_s0_t0__SELF__real",
        "C0_s0_t0__SELF__within_subject_permuted",
        "C0_s0_t1__CROSS__real",
        "C0_s0_t1__CROSS__within_subject_permuted",
        "C0_s0_t1__DIRECT__real",
        "C0_s0_t1__DIRECT__within_subject_permuted",
        "C0_s0_t2__CROSS__real",
        "C0_s0_t2__CROSS__within_subject_permuted",
        "C0_s0_t2__DIRECT__real",
        "C0_s0_t3__CROSS__real",
        "C0_s0_t3__CROSS__within_subject_permuted",
        "C0_s0_t3__DIRECT__real",
        "C0_s0_t3__DIRECT__within_subject_permuted",
        "C0_s0_t4__CROSS__real",
        "C0_s0_t4__DIRECT__real",
        "C0_s0_t4__DIRECT__within_subject_permuted",
        "C0_s0_t5__CROSS__real",
        "C0_s0_t5__CROSS__within_subject_permuted",
        "C0_s0_t7__CROSS__real",
        "C0_s0_t7__CROSS__within_subject_permuted",
        "C0_s0_t8__CROSS__real",
        "P0_s0_t0__CROSS__real",
        "P0_s0_t0__CROSS__within_subject_permuted",
        "P0_s0_t0__DIRECT__within_subject_permuted",
        "P0_s0_t0__SELF__within_subject_permuted",
        "P0_s0_t1__CROSS__real",
        "P0_s0_t1__CROSS__within_subject_permuted",
        "P0_s0_t1__DIRECT__real",
        "P0_s0_t1__DIRECT__within_subject_permuted",
        "P0_s0_t1__SELF__within_subject_permuted",
        "P0_s0_t2__CROSS__real",
        "P0_s0_t2__CROSS__within_subject_permuted",
        "P0_s0_t2__DIRECT__real",
        "P0_s0_t2__DIRECT__within_subject_permuted",
        "P0_s0_t3__CROSS__real",
        "P0_s0_t3__DIRECT__real",
        "P0_s0_t3__DIRECT__within_subject_permuted",
        "P0_s0_t4__CROSS__real",
        "P0_s0_t4__CROSS__within_subject_permuted",
        "P0_s0_t4__DIRECT__real",
        "P0_s0_t4__DIRECT__within_subject_permuted",
        "P0_s0_t5__CROSS__real",
        "P0_s0_t5__CROSS__within_subject_permuted",
        "P0_s0_t6__CROSS__real",
        "P0_s0_t6__CROSS__within_subject_permuted",
        "P0_s0_t7__CROSS__real",
        "P0_s0_t7__CROSS__within_subject_permuted",
        "P0_s0_t8__CROSS__real",
        "P0_s0_t8__CROSS__within_subject_permuted",
        "S0_s0_t0__CROSS__real",
        "S0_s0_t0__CROSS__within_subject_permuted",
        "S0_s0_t0__DIRECT__real",
        "S0_s0_t0__DIRECT__within_subject_permuted",
        "S0_s0_t0__SELF__within_subject_permuted",
        "S0_s0_t1__CROSS__real",
        "S0_s0_t1__CROSS__within_subject_permuted",
        "S0_s0_t1__DIRECT__real",
        "S0_s0_t1__DIRECT__within_subject_permuted",
        "S0_s0_t1__SELF__real",
        "S0_s0_t2__CROSS__real",
        "S0_s0_t2__CROSS__within_subject_permuted",
        "S0_s0_t2__DIRECT__real",
        "S0_s0_t2__DIRECT__within_subject_permuted",
        "S0_s0_t3__CROSS__real",
        "S0_s0_t3__CROSS__within_subject_permuted",
        "S0_s0_t3__DIRECT__real",
        "S0_s0_t3__DIRECT__within_subject_permuted",
        "S0_s0_t4__CROSS__real",
        "S0_s0_t4__CROSS__within_subject_permuted",
        "S0_s0_t4__DIRECT__real",
        "S0_s0_t4__DIRECT__within_subject_permuted",
        "S0_s0_t5__CROSS__within_subject_permuted",
        "S0_s0_t6__CROSS__real",
        "S0_s0_t6__CROSS__within_subject_permuted",
        "S0_s0_t7__CROSS__real",
        "S0_s0_t8__CROSS__real"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair2/SOURCE_REUSE_MANIFEST.json",
        "sha256": "36ef5b973230cf11bb82779244c3b99e7b3b32930271ed7fe5a5cc78bfdc52b5"
      }
    },
    {
      "attempt_class": "explicit_fut_capacity_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair3/AUTHORIZATION.md",
      "campaign_id": "dsainet-fut-v0.1-20260924",
      "failed_run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-24_dsainet_fut_v0_1_repair2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 5.185,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 433,
        "recorded_at": "2026-09-24T06:21:57.162734+00:00",
        "round_id": "dsa-fut-v0.1-repair2",
        "run_prefix": "2026-09-24_dsainet_fut_v0_1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T06:22:32.860792+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T06:22:34.408878+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T06:22:55.986257+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "c0079193203e370a4c3534751d660f4c16f43a4373e42bc771172b46998085e3",
                "execution_seconds": 17.31287980079651,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-24_dsainet_fut_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 17.31287980079651
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T06:24:17.294311+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "c0079193203e370a4c3534751d660f4c16f43a4373e42bc771172b46998085e3",
                "execution_seconds": 98.61843156814575,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dsainet_fut_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-24_dsainet_fut_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 98.61843156814575
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-24T13:52:11.524544+00:00",
      "rerun_task_ids": [
        "P0_s0_t5__DIRECT__real",
        "B0_s0_t5__DIRECT__within_subject_permuted",
        "S0_s0_t6__DIRECT__real",
        "P0_s0_t5__DIRECT__within_subject_permuted",
        "C0_s0_t6__DIRECT__real",
        "B0_s0_t6__DIRECT__real",
        "S0_s0_t6__DIRECT__within_subject_permuted",
        "P0_s0_t6__DIRECT__real",
        "C0_s0_t6__DIRECT__within_subject_permuted",
        "B0_s0_t6__DIRECT__within_subject_permuted",
        "S0_s0_t7__DIRECT__real",
        "P0_s0_t6__DIRECT__within_subject_permuted",
        "C0_s0_t7__DIRECT__real",
        "B0_s0_t7__DIRECT__real",
        "S0_s0_t7__DIRECT__within_subject_permuted",
        "P0_s0_t7__DIRECT__real",
        "C0_s0_t7__DIRECT__within_subject_permuted",
        "B0_s0_t7__DIRECT__within_subject_permuted",
        "S0_s0_t8__DIRECT__real",
        "P0_s0_t7__DIRECT__within_subject_permuted",
        "C0_s0_t8__DIRECT__real",
        "B0_s0_t8__DIRECT__real",
        "S0_s0_t8__DIRECT__within_subject_permuted",
        "P0_s0_t8__DIRECT__real",
        "C0_s0_t8__DIRECT__within_subject_permuted",
        "B0_s0_t8__DIRECT__within_subject_permuted",
        "S0_s1_t0__DIRECT__real",
        "P0_s0_t8__DIRECT__within_subject_permuted",
        "C0_s1_t0__DIRECT__real",
        "B0_s1_t0__DIRECT__real",
        "S0_s1_t0__DIRECT__within_subject_permuted",
        "P0_s1_t0__DIRECT__real",
        "C0_s1_t0__DIRECT__within_subject_permuted",
        "B0_s1_t0__DIRECT__within_subject_permuted",
        "S0_s1_t1__DIRECT__real",
        "P0_s1_t0__DIRECT__within_subject_permuted",
        "C0_s1_t1__DIRECT__real",
        "B0_s1_t1__DIRECT__real",
        "S0_s1_t1__DIRECT__within_subject_permuted",
        "P0_s1_t1__DIRECT__real",
        "C0_s1_t1__DIRECT__within_subject_permuted",
        "B0_s1_t1__DIRECT__within_subject_permuted",
        "S0_s1_t2__DIRECT__real",
        "P0_s1_t1__DIRECT__within_subject_permuted",
        "C0_s1_t2__DIRECT__real",
        "B0_s1_t2__DIRECT__real",
        "S0_s1_t2__DIRECT__within_subject_permuted",
        "P0_s1_t2__DIRECT__real",
        "C0_s1_t2__DIRECT__within_subject_permuted",
        "B0_s1_t2__DIRECT__within_subject_permuted",
        "S0_s1_t3__DIRECT__real",
        "P0_s1_t2__DIRECT__within_subject_permuted",
        "C0_s1_t3__DIRECT__real",
        "B0_s1_t3__DIRECT__real",
        "S0_s1_t3__DIRECT__within_subject_permuted",
        "P0_s1_t3__DIRECT__real",
        "C0_s1_t3__DIRECT__within_subject_permuted",
        "B0_s1_t3__DIRECT__within_subject_permuted",
        "S0_s1_t4__DIRECT__real",
        "P0_s1_t3__DIRECT__within_subject_permuted",
        "C0_s1_t4__DIRECT__real",
        "B0_s1_t4__DIRECT__real",
        "S0_s1_t4__DIRECT__within_subject_permuted",
        "P0_s1_t4__DIRECT__real",
        "C0_s1_t4__DIRECT__within_subject_permuted",
        "B0_s1_t4__DIRECT__within_subject_permuted",
        "S0_s1_t5__DIRECT__real",
        "P0_s1_t4__DIRECT__within_subject_permuted",
        "C0_s1_t5__DIRECT__real",
        "B0_s1_t5__DIRECT__real",
        "S0_s1_t5__DIRECT__within_subject_permuted",
        "P0_s1_t5__DIRECT__real",
        "C0_s1_t5__DIRECT__within_subject_permuted",
        "B0_s1_t5__DIRECT__within_subject_permuted",
        "S0_s1_t6__DIRECT__real",
        "P0_s1_t5__DIRECT__within_subject_permuted",
        "C0_s1_t6__DIRECT__real",
        "B0_s1_t6__DIRECT__real",
        "S0_s1_t6__DIRECT__within_subject_permuted",
        "P0_s1_t6__DIRECT__real",
        "C0_s1_t6__DIRECT__within_subject_permuted",
        "B0_s1_t6__DIRECT__within_subject_permuted",
        "C0_s1_t7__DIRECT__real",
        "B0_s1_t7__DIRECT__real",
        "S0_s1_t7__DIRECT__within_subject_permuted",
        "P0_s1_t7__DIRECT__real",
        "C0_s1_t7__DIRECT__within_subject_permuted",
        "B0_s1_t7__DIRECT__within_subject_permuted",
        "S0_s1_t8__DIRECT__real",
        "P0_s1_t7__DIRECT__within_subject_permuted",
        "C0_s1_t8__DIRECT__real",
        "B0_s1_t8__DIRECT__real",
        "S0_s1_t8__DIRECT__within_subject_permuted",
        "P0_s1_t8__DIRECT__real",
        "C0_s1_t8__DIRECT__within_subject_permuted",
        "B0_s1_t8__DIRECT__within_subject_permuted",
        "P0_s1_t8__DIRECT__within_subject_permuted",
        "C0_s0_t5__DIRECT__real",
        "C0_s0_t5__DIRECT__within_subject_permuted"
      ],
      "reused_task_ids": [
        "B0_s0_t0__CROSS__real",
        "B0_s0_t0__CROSS__within_subject_permuted",
        "B0_s0_t0__DIRECT__real",
        "B0_s0_t0__DIRECT__within_subject_permuted",
        "B0_s0_t0__SELF__real",
        "B0_s0_t0__SELF__within_subject_permuted",
        "B0_s0_t1__CROSS__real",
        "B0_s0_t1__CROSS__within_subject_permuted",
        "B0_s0_t1__DIRECT__real",
        "B0_s0_t1__DIRECT__within_subject_permuted",
        "B0_s0_t1__SELF__real",
        "B0_s0_t1__SELF__within_subject_permuted",
        "B0_s0_t2__CROSS__real",
        "B0_s0_t2__CROSS__within_subject_permuted",
        "B0_s0_t2__DIRECT__real",
        "B0_s0_t2__DIRECT__within_subject_permuted",
        "B0_s0_t2__SELF__real",
        "B0_s0_t2__SELF__within_subject_permuted",
        "B0_s0_t3__CROSS__real",
        "B0_s0_t3__CROSS__within_subject_permuted",
        "B0_s0_t3__DIRECT__real",
        "B0_s0_t3__DIRECT__within_subject_permuted",
        "B0_s0_t3__SELF__real",
        "B0_s0_t3__SELF__within_subject_permuted",
        "B0_s0_t4__CROSS__real",
        "B0_s0_t4__CROSS__within_subject_permuted",
        "B0_s0_t4__DIRECT__real",
        "B0_s0_t4__DIRECT__within_subject_permuted",
        "B0_s0_t4__SELF__real",
        "B0_s0_t4__SELF__within_subject_permuted",
        "B0_s0_t5__CROSS__real",
        "B0_s0_t5__CROSS__within_subject_permuted",
        "B0_s0_t5__DIRECT__real",
        "B0_s0_t5__SELF__real",
        "B0_s0_t5__SELF__within_subject_permuted",
        "B0_s0_t6__CROSS__real",
        "B0_s0_t6__CROSS__within_subject_permuted",
        "B0_s0_t6__SELF__real",
        "B0_s0_t6__SELF__within_subject_permuted",
        "B0_s0_t7__CROSS__real",
        "B0_s0_t7__CROSS__within_subject_permuted",
        "B0_s0_t7__SELF__real",
        "B0_s0_t7__SELF__within_subject_permuted",
        "B0_s0_t8__CROSS__real",
        "B0_s0_t8__CROSS__within_subject_permuted",
        "B0_s0_t8__SELF__real",
        "B0_s0_t8__SELF__within_subject_permuted",
        "B0_s1_t0__CROSS__real",
        "B0_s1_t0__CROSS__within_subject_permuted",
        "B0_s1_t0__SELF__real",
        "B0_s1_t0__SELF__within_subject_permuted",
        "B0_s1_t1__CROSS__real",
        "B0_s1_t1__CROSS__within_subject_permuted",
        "B0_s1_t1__SELF__real",
        "B0_s1_t1__SELF__within_subject_permuted",
        "B0_s1_t2__CROSS__real",
        "B0_s1_t2__CROSS__within_subject_permuted",
        "B0_s1_t2__SELF__real",
        "B0_s1_t2__SELF__within_subject_permuted",
        "B0_s1_t3__CROSS__real",
        "B0_s1_t3__CROSS__within_subject_permuted",
        "B0_s1_t3__SELF__real",
        "B0_s1_t3__SELF__within_subject_permuted",
        "B0_s1_t4__CROSS__real",
        "B0_s1_t4__CROSS__within_subject_permuted",
        "B0_s1_t4__SELF__real",
        "B0_s1_t4__SELF__within_subject_permuted",
        "B0_s1_t5__CROSS__real",
        "B0_s1_t5__CROSS__within_subject_permuted",
        "B0_s1_t5__SELF__real",
        "B0_s1_t5__SELF__within_subject_permuted",
        "B0_s1_t6__CROSS__real",
        "B0_s1_t6__CROSS__within_subject_permuted",
        "B0_s1_t6__SELF__real",
        "B0_s1_t6__SELF__within_subject_permuted",
        "B0_s1_t7__CROSS__real",
        "B0_s1_t7__CROSS__within_subject_permuted",
        "B0_s1_t7__SELF__real",
        "B0_s1_t7__SELF__within_subject_permuted",
        "B0_s1_t8__CROSS__real",
        "B0_s1_t8__CROSS__within_subject_permuted",
        "B0_s1_t8__SELF__real",
        "B0_s1_t8__SELF__within_subject_permuted",
        "C0_s0_t0__CROSS__real",
        "C0_s0_t0__CROSS__within_subject_permuted",
        "C0_s0_t0__DIRECT__real",
        "C0_s0_t0__DIRECT__within_subject_permuted",
        "C0_s0_t0__SELF__real",
        "C0_s0_t0__SELF__within_subject_permuted",
        "C0_s0_t1__CROSS__real",
        "C0_s0_t1__CROSS__within_subject_permuted",
        "C0_s0_t1__DIRECT__real",
        "C0_s0_t1__DIRECT__within_subject_permuted",
        "C0_s0_t1__SELF__real",
        "C0_s0_t1__SELF__within_subject_permuted",
        "C0_s0_t2__CROSS__real",
        "C0_s0_t2__CROSS__within_subject_permuted",
        "C0_s0_t2__DIRECT__real",
        "C0_s0_t2__DIRECT__within_subject_permuted",
        "C0_s0_t2__SELF__real",
        "C0_s0_t2__SELF__within_subject_permuted",
        "C0_s0_t3__CROSS__real",
        "C0_s0_t3__CROSS__within_subject_permuted",
        "C0_s0_t3__DIRECT__real",
        "C0_s0_t3__DIRECT__within_subject_permuted",
        "C0_s0_t3__SELF__real",
        "C0_s0_t3__SELF__within_subject_permuted",
        "C0_s0_t4__CROSS__real",
        "C0_s0_t4__CROSS__within_subject_permuted",
        "C0_s0_t4__DIRECT__real",
        "C0_s0_t4__DIRECT__within_subject_permuted",
        "C0_s0_t4__SELF__real",
        "C0_s0_t4__SELF__within_subject_permuted",
        "C0_s0_t5__CROSS__real",
        "C0_s0_t5__CROSS__within_subject_permuted",
        "C0_s0_t5__SELF__real",
        "C0_s0_t5__SELF__within_subject_permuted",
        "C0_s0_t6__CROSS__real",
        "C0_s0_t6__CROSS__within_subject_permuted",
        "C0_s0_t6__SELF__real",
        "C0_s0_t6__SELF__within_subject_permuted",
        "C0_s0_t7__CROSS__real",
        "C0_s0_t7__CROSS__within_subject_permuted",
        "C0_s0_t7__SELF__real",
        "C0_s0_t7__SELF__within_subject_permuted",
        "C0_s0_t8__CROSS__real",
        "C0_s0_t8__CROSS__within_subject_permuted",
        "C0_s0_t8__SELF__real",
        "C0_s0_t8__SELF__within_subject_permuted",
        "C0_s1_t0__CROSS__real",
        "C0_s1_t0__CROSS__within_subject_permuted",
        "C0_s1_t0__SELF__real",
        "C0_s1_t0__SELF__within_subject_permuted",
        "C0_s1_t1__CROSS__real",
        "C0_s1_t1__CROSS__within_subject_permuted",
        "C0_s1_t1__SELF__real",
        "C0_s1_t1__SELF__within_subject_permuted",
        "C0_s1_t2__CROSS__real",
        "C0_s1_t2__CROSS__within_subject_permuted",
        "C0_s1_t2__SELF__real",
        "C0_s1_t2__SELF__within_subject_permuted",
        "C0_s1_t3__CROSS__real",
        "C0_s1_t3__CROSS__within_subject_permuted",
        "C0_s1_t3__SELF__real",
        "C0_s1_t3__SELF__within_subject_permuted",
        "C0_s1_t4__CROSS__real",
        "C0_s1_t4__CROSS__within_subject_permuted",
        "C0_s1_t4__SELF__real",
        "C0_s1_t4__SELF__within_subject_permuted",
        "C0_s1_t5__CROSS__real",
        "C0_s1_t5__CROSS__within_subject_permuted",
        "C0_s1_t5__SELF__real",
        "C0_s1_t5__SELF__within_subject_permuted",
        "C0_s1_t6__CROSS__real",
        "C0_s1_t6__CROSS__within_subject_permuted",
        "C0_s1_t6__SELF__real",
        "C0_s1_t6__SELF__within_subject_permuted",
        "C0_s1_t7__CROSS__real",
        "C0_s1_t7__CROSS__within_subject_permuted",
        "C0_s1_t7__SELF__real",
        "C0_s1_t7__SELF__within_subject_permuted",
        "C0_s1_t8__CROSS__real",
        "C0_s1_t8__CROSS__within_subject_permuted",
        "C0_s1_t8__SELF__real",
        "C0_s1_t8__SELF__within_subject_permuted",
        "P0_s0_t0__CROSS__real",
        "P0_s0_t0__CROSS__within_subject_permuted",
        "P0_s0_t0__DIRECT__real",
        "P0_s0_t0__DIRECT__within_subject_permuted",
        "P0_s0_t0__SELF__real",
        "P0_s0_t0__SELF__within_subject_permuted",
        "P0_s0_t1__CROSS__real",
        "P0_s0_t1__CROSS__within_subject_permuted",
        "P0_s0_t1__DIRECT__real",
        "P0_s0_t1__DIRECT__within_subject_permuted",
        "P0_s0_t1__SELF__real",
        "P0_s0_t1__SELF__within_subject_permuted",
        "P0_s0_t2__CROSS__real",
        "P0_s0_t2__CROSS__within_subject_permuted",
        "P0_s0_t2__DIRECT__real",
        "P0_s0_t2__DIRECT__within_subject_permuted",
        "P0_s0_t2__SELF__real",
        "P0_s0_t2__SELF__within_subject_permuted",
        "P0_s0_t3__CROSS__real",
        "P0_s0_t3__CROSS__within_subject_permuted",
        "P0_s0_t3__DIRECT__real",
        "P0_s0_t3__DIRECT__within_subject_permuted",
        "P0_s0_t3__SELF__real",
        "P0_s0_t3__SELF__within_subject_permuted",
        "P0_s0_t4__CROSS__real",
        "P0_s0_t4__CROSS__within_subject_permuted",
        "P0_s0_t4__DIRECT__real",
        "P0_s0_t4__DIRECT__within_subject_permuted",
        "P0_s0_t4__SELF__real",
        "P0_s0_t4__SELF__within_subject_permuted",
        "P0_s0_t5__CROSS__real",
        "P0_s0_t5__CROSS__within_subject_permuted",
        "P0_s0_t5__SELF__real",
        "P0_s0_t5__SELF__within_subject_permuted",
        "P0_s0_t6__CROSS__real",
        "P0_s0_t6__CROSS__within_subject_permuted",
        "P0_s0_t6__SELF__real",
        "P0_s0_t6__SELF__within_subject_permuted",
        "P0_s0_t7__CROSS__real",
        "P0_s0_t7__CROSS__within_subject_permuted",
        "P0_s0_t7__SELF__real",
        "P0_s0_t7__SELF__within_subject_permuted",
        "P0_s0_t8__CROSS__real",
        "P0_s0_t8__CROSS__within_subject_permuted",
        "P0_s0_t8__SELF__real",
        "P0_s0_t8__SELF__within_subject_permuted",
        "P0_s1_t0__CROSS__real",
        "P0_s1_t0__CROSS__within_subject_permuted",
        "P0_s1_t0__SELF__real",
        "P0_s1_t0__SELF__within_subject_permuted",
        "P0_s1_t1__CROSS__real",
        "P0_s1_t1__CROSS__within_subject_permuted",
        "P0_s1_t1__SELF__real",
        "P0_s1_t1__SELF__within_subject_permuted",
        "P0_s1_t2__CROSS__real",
        "P0_s1_t2__CROSS__within_subject_permuted",
        "P0_s1_t2__SELF__real",
        "P0_s1_t2__SELF__within_subject_permuted",
        "P0_s1_t3__CROSS__real",
        "P0_s1_t3__CROSS__within_subject_permuted",
        "P0_s1_t3__SELF__real",
        "P0_s1_t3__SELF__within_subject_permuted",
        "P0_s1_t4__CROSS__real",
        "P0_s1_t4__CROSS__within_subject_permuted",
        "P0_s1_t4__SELF__real",
        "P0_s1_t4__SELF__within_subject_permuted",
        "P0_s1_t5__CROSS__real",
        "P0_s1_t5__CROSS__within_subject_permuted",
        "P0_s1_t5__SELF__real",
        "P0_s1_t5__SELF__within_subject_permuted",
        "P0_s1_t6__CROSS__real",
        "P0_s1_t6__CROSS__within_subject_permuted",
        "P0_s1_t6__DIRECT__within_subject_permuted",
        "P0_s1_t6__SELF__real",
        "P0_s1_t6__SELF__within_subject_permuted",
        "P0_s1_t7__CROSS__real",
        "P0_s1_t7__CROSS__within_subject_permuted",
        "P0_s1_t7__SELF__real",
        "P0_s1_t7__SELF__within_subject_permuted",
        "P0_s1_t8__CROSS__real",
        "P0_s1_t8__CROSS__within_subject_permuted",
        "P0_s1_t8__SELF__real",
        "P0_s1_t8__SELF__within_subject_permuted",
        "S0_s0_t0__CROSS__real",
        "S0_s0_t0__CROSS__within_subject_permuted",
        "S0_s0_t0__DIRECT__real",
        "S0_s0_t0__DIRECT__within_subject_permuted",
        "S0_s0_t0__SELF__real",
        "S0_s0_t0__SELF__within_subject_permuted",
        "S0_s0_t1__CROSS__real",
        "S0_s0_t1__CROSS__within_subject_permuted",
        "S0_s0_t1__DIRECT__real",
        "S0_s0_t1__DIRECT__within_subject_permuted",
        "S0_s0_t1__SELF__real",
        "S0_s0_t1__SELF__within_subject_permuted",
        "S0_s0_t2__CROSS__real",
        "S0_s0_t2__CROSS__within_subject_permuted",
        "S0_s0_t2__DIRECT__real",
        "S0_s0_t2__DIRECT__within_subject_permuted",
        "S0_s0_t2__SELF__real",
        "S0_s0_t2__SELF__within_subject_permuted",
        "S0_s0_t3__CROSS__real",
        "S0_s0_t3__CROSS__within_subject_permuted",
        "S0_s0_t3__DIRECT__real",
        "S0_s0_t3__DIRECT__within_subject_permuted",
        "S0_s0_t3__SELF__real",
        "S0_s0_t3__SELF__within_subject_permuted",
        "S0_s0_t4__CROSS__real",
        "S0_s0_t4__CROSS__within_subject_permuted",
        "S0_s0_t4__DIRECT__real",
        "S0_s0_t4__DIRECT__within_subject_permuted",
        "S0_s0_t4__SELF__real",
        "S0_s0_t4__SELF__within_subject_permuted",
        "S0_s0_t5__CROSS__real",
        "S0_s0_t5__CROSS__within_subject_permuted",
        "S0_s0_t5__DIRECT__real",
        "S0_s0_t5__DIRECT__within_subject_permuted",
        "S0_s0_t5__SELF__real",
        "S0_s0_t5__SELF__within_subject_permuted",
        "S0_s0_t6__CROSS__real",
        "S0_s0_t6__CROSS__within_subject_permuted",
        "S0_s0_t6__SELF__real",
        "S0_s0_t6__SELF__within_subject_permuted",
        "S0_s0_t7__CROSS__real",
        "S0_s0_t7__CROSS__within_subject_permuted",
        "S0_s0_t7__SELF__real",
        "S0_s0_t7__SELF__within_subject_permuted",
        "S0_s0_t8__CROSS__real",
        "S0_s0_t8__CROSS__within_subject_permuted",
        "S0_s0_t8__SELF__real",
        "S0_s0_t8__SELF__within_subject_permuted",
        "S0_s1_t0__CROSS__real",
        "S0_s1_t0__CROSS__within_subject_permuted",
        "S0_s1_t0__SELF__real",
        "S0_s1_t0__SELF__within_subject_permuted",
        "S0_s1_t1__CROSS__real",
        "S0_s1_t1__CROSS__within_subject_permuted",
        "S0_s1_t1__SELF__real",
        "S0_s1_t1__SELF__within_subject_permuted",
        "S0_s1_t2__CROSS__real",
        "S0_s1_t2__CROSS__within_subject_permuted",
        "S0_s1_t2__SELF__real",
        "S0_s1_t2__SELF__within_subject_permuted",
        "S0_s1_t3__CROSS__real",
        "S0_s1_t3__CROSS__within_subject_permuted",
        "S0_s1_t3__SELF__real",
        "S0_s1_t3__SELF__within_subject_permuted",
        "S0_s1_t4__CROSS__real",
        "S0_s1_t4__CROSS__within_subject_permuted",
        "S0_s1_t4__SELF__real",
        "S0_s1_t4__SELF__within_subject_permuted",
        "S0_s1_t5__CROSS__real",
        "S0_s1_t5__CROSS__within_subject_permuted",
        "S0_s1_t5__SELF__real",
        "S0_s1_t5__SELF__within_subject_permuted",
        "S0_s1_t6__CROSS__real",
        "S0_s1_t6__CROSS__within_subject_permuted",
        "S0_s1_t6__SELF__real",
        "S0_s1_t6__SELF__within_subject_permuted",
        "S0_s1_t7__CROSS__real",
        "S0_s1_t7__CROSS__within_subject_permuted",
        "S0_s1_t7__DIRECT__real",
        "S0_s1_t7__SELF__real",
        "S0_s1_t7__SELF__within_subject_permuted",
        "S0_s1_t8__CROSS__real",
        "S0_s1_t8__CROSS__within_subject_permuted",
        "S0_s1_t8__SELF__real",
        "S0_s1_t8__SELF__within_subject_permuted"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair3/SOURCE_REUSE_MANIFEST.json",
        "sha256": "64b6ba170687cedfd18a96d7ef4490a44f8e8477b120214475bfe683a6dc2e2d"
      }
    },
    {
      "attempt_class": "explicit_fut_capacity_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair4/AUTHORIZATION.md",
      "campaign_id": "dsainet-fut-v0.1-20260924",
      "failed_run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-24_dsainet_fut_v0_1_repair3-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.691,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
    
```
