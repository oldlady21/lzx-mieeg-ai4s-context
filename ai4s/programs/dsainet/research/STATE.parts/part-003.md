# State 阅读分段 3

完整脱敏文件：`ai4s/programs/dsainet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`546294f490c37739bda04797b439fd05243a3b3cd8b4b5effc331321bba2400a`。UTF-8 字节范围：[1000000, 1036464) / 1036464。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml

  },
  "operation_history": [
    {
      "bundle_id": "2026-09-07_dsainet_ttpp_lab10_preflight_v0_1",
      "contract": "ai4s/programs/dsainet/staging/2026-09-07_dsainet_ttpp_lab10_preflight_v0_1/contracts/round_contract.yaml",
      "executor_id": "lab10",
      "expected_artifact": "b0_preflight.json",
      "intake": {
        "intake_path": "results/logs/remote/2026-09-07_dsainet_ttpp_lab10_preflight_v0_1-r1",
        "run_id": "2026-09-07_dsainet_ttpp_lab10_preflight_v0_1-r1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-07T15:09:00.718213+00:00"
      },
      "kind": "engineering_preflight",
      "operation_id": "dsainet:engineering_preflight:2026-09-07_dsainet_ttpp_lab10_preflight_v0_1-r1",
      "preflight": {
        "arm": "B0",
        "artifact": "results/logs/remote/2026-09-07_dsainet_ttpp_lab10_preflight_v0_1-r1/b0_preflight.json",
        "environment_fingerprint": "a6c5fc972fca1bb1f49b38c0b1cb5dc595f3957ed7e9c74c562c5cc97ac6ecef",
        "peak_memory_observed_mib": 1551,
        "peak_memory_status": "pid_delta_observed_during_full_100_epoch_B0"
      },
      "registered_at": "2026-09-07T14:46:20.499252+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "WAITING_REMOTE",
      "run_id": "2026-09-07_dsainet_ttpp_lab10_preflight_v0_1-r1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-09-07T15:09:18.552255+00:00"
    },
    {
      "bundle_id": "2026-09-24_dsainet_fut_v0_1_profile-bundle",
      "contract": "ai4s/programs/dsainet/research/dsa-fut-v0.1/PROFILE_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "tail_profile.json",
      "failure": {
        "automatic_retry_permitted": false,
        "formal_stage_started": false,
        "kind": "TECHNICAL_OOM_BEFORE_FIRST_GRADIENT",
        "record": "ai4s/programs/dsainet/research/dsa-fut-v0.1/forensics/FORENSIC_VERIFICATION.json",
        "task_id": "profile_SELF"
      },
      "kind": "engineering_preflight",
      "operation_id": "dsainet:engineering_preflight:2026-09-24_dsainet_fut_v0_1_profile-r1",
      "registered_at": "2026-09-23T18:13:39.020059+00:00",
      "repair_run_id": "2026-09-24_dsainet_fut_v0_1_profile_repair1-r1",
      "result_role": "engineering_frozen_tail_profile_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-09-24_dsainet_fut_v0_1_profile-r1",
      "status": "FAILED_TECHNICAL_SUPERSEDED_BY_AUTHORIZED_REPAIR"
    },
    {
      "bundle_id": "2026-09-24_dsainet_fut_v0_1_profile_repair1-bundle",
      "contract": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair1/PROFILE_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "tail_profile.json",
      "intake": {
        "intake_path": "results/logs/remote/2026-09-24_dsainet_fut_v0_1_profile_repair1-r1",
        "run_id": "2026-09-24_dsainet_fut_v0_1_profile_repair1-r1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-24T01:39:09.316321+00:00"
      },
      "kind": "engineering_preflight",
      "operation_id": "dsainet:engineering_preflight:2026-09-24_dsainet_fut_v0_1_profile_repair1-r1",
      "registered_at": "2026-09-24T01:35:29.219586+00:00",
      "repair_verification": {
        "external_source_contract_sha256": "1e7119e8207cb0646c5e045d7ece40a96339ffcceb3cd3a30b8373ae18400d1d",
        "logical_task_units": 3,
        "manifest_files": 14,
        "new_task_ids": [
          "profile_SELF"
        ],
        "peak_memory_observed_mib": 909,
        "reused_task_ids": [
          "profile_CROSS",
          "profile_DIRECT"
        ],
        "status": "VERIFIED"
      },
      "result_role": "engineering_frozen_tail_profile_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-09-24_dsainet_fut_v0_1_profile_repair1-r1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-09-24T01:39:09.735321+00:00"
    },
    {
      "acceptance_path": "ai4s/programs/dsainet/research/p0-pf-r1/technical_closeout/PF_TECH_ACCEPTANCE.json",
      "acceptance_sha256": "067d9de387f579353f4dcfbc988d4c4ada09134184e3f25cf1cf95f2c0dda553",
      "bundle_id": "2026-10-29_dsainet_p0_pf_r1_tech1",
      "contract": "ai4s/programs/dsainet/research/p0-pf-r1/TECHNICAL_CONTRACT.json",
      "cost_sha256": "cea3f44e4a68b5c2ecfb9fc230f14b4bdd4981d797b8af88144d5c8a4879d24a",
      "executor_id": "lab10",
      "expected_artifact": "PF_TECH_ACCEPTANCE.json",
      "kind": "engineering_preflight",
      "operation_id": "dsainet:engineering_preflight:2026-10-29_dsainet_p0_pf_r1_tech1",
      "original_error": "NameError json in technical summary",
      "original_terminal_status": "FAILED_PRESERVED",
      "recovered_read_only": true,
      "reference_cells": 90,
      "registered_at": "2026-10-28T18:09:41.110643+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": true,
      "resume_status": "COMPLETE_MAX_ROUNDS",
      "run_id": "2026-10-29_dsainet_p0_pf_r1_tech1",
      "science_fits_started": 0,
      "standard_transaction_intake": false,
      "status": "RECOVERED_ENGINEERING_ARTIFACTS_VERIFIED",
      "technical_tasks": 5,
      "transport_archive_sha256": "53f6361ac683efe13086faa80f4420d69815eb8e0ecb4763ca9d9d9dd4330650",
      "verified_at": "2026-10-28T18:20:05.396760+00:00"
    },
    {
      "contract_path": "ai4s/programs/dsainet/research/p0-fd-r1/packfix2_contract.json",
      "contract_sha256": "8bb24f5e5d65963bf44ab83881c516e3e4c90bb1d399ae8a2099cf1a4534c0a8",
      "deployment_note": "generic science round preflight remains non-applicable (closed 4/4 training campaign); this exact new diagnostic uses separately recorded explicit user authorization and shared Transaction runtime, no fabricated record-run PASS",
      "evidence": {
        "automatic_follow_up": false,
        "checkpoint_replays": 36,
        "claim_created": false,
        "contract_sha256": "8bb24f5e5d65963bf44ab83881c516e3e4c90bb1d399ae8a2099cf1a4534c0a8",
        "decision": "NO_SIGNAL_STOP_FIXED_READOUT_REPAIR",
        "evidence_id": "DSAINET-P0-FD-R1-CROSSED-READOUT-20261029",
        "full_payload_local": false,
        "historical_failures_preserved": [
          "2026-10-29_dsainet_p0_fd_r1-full-w1",
          "2026-10-29_dsainet_p0_fd_r1-packfix1-full-w1"
        ],
        "intake_scope": "analysis_v1",
        "matched_AA_pass": false,
        "matrix_cells": 144,
        "new_fits": 0,
        "observed_at": "2026-10-29T12:59:33.828041+00:00",
        "parent_retention_pass": false,
        "remaining_budget_hours_snapshot": 22.100565107883455,
        "report": "ai4s/programs/dsainet/research/p0-fd-r1/RESULTS_ZH.md",
        "report_sha256": "e59e3a2d651016ea5ac4bf5910438334a18078090e996b3244e73bc479f19241",
        "research_id": "p0-fd-r1",
        "result_sha256": "142e6b4c0fe22c1ce079cf2bead518a77e13ffbfffa0ce323b5a6e52f145ed53",
        "role": "exposed_development_fixed_checkpoint_diagnostic",
        "run_id": "2026-10-29_dsainet_p0_fd_r1-packfix2-full-w1",
        "standard_verified_intake": true,
        "verification_sha256": "7f8e5268b37c0daa47d3c7e436fe9cfd40fef50fb6eff5b2a0f7657c08f3f5a0"
      },
      "kind": "user_authorized_bounded_no_fit_diagnostic",
      "no_new_training": true,
      "operation_id": "p0-fd-r1-fixed-checkpoint-replay",
      "original_round_accounting_preserved": true,
      "recorded_at": "2026-10-29T12:48:55.718973+00:00",
      "remaining_campaign_seconds_at_dispatch": 80200.1434563804,
      "remote_root": "[REDACTED_MACHINE]",
      "run_id": "2026-10-29_dsainet_p0_fd_r1-packfix2-full-w1",
      "status": "COMPLETE",
      "successor_history": [
        {
          "first_error": "raw JSON contract identity differed from shared reader",
          "model_forwards": 0,
          "run_id": "2026-10-29_dsainet_p0_fd_r1-full-w1",
          "status": "FAILED_PRESERVED"
        },
        {
          "first_error": "raw CONFIG preparation data path was not bound to frozen versioned asset",
          "model_forwards": 0,
          "run_id": "2026-10-29_dsainet_p0_fd_r1-packfix1-full-w1",
          "status": "FAILED_PRESERVED"
        }
      ],
      "user_authorization": {
        "scope": "exact bounded diagnostic under same accounting; no fitting or follow-up",
        "user_request": "按方案实施并启动P0-FD-R1，先核验36份R2原检查点的复用资格和恒等回退，通过技术与成本门后完成交叉读出分析；保留原预算、计时起点及全部历史记录，不新增训练。"
      }
    },
    {
      "allowed_operations": [
        "upload",
        "launch",
        "probe",
        "fetch_verify_intake",
        "local_analysis"
      ],
      "bundle_id": "2026-10-29_dsainet_p0_wmp_d1_stagea",
      "closed_training_rounds_preserved": true,
      "contract": "ai4s/programs/dsainet/research/p0-wmp-d1/stagea_contract.json",
      "contract_sha256": "20dd39535800fc93e4ffb85baf2537945c59323e97083e61a99f7a31479afd25",
      "dispatch": {
        "contract_sha256": "20dd39535800fc93e4ffb85baf2537945c59323e97083e61a99f7a31479afd25",
        "dispatched_at_unix": 1793288634.7513068,
        "new_neural_fits_authorized": 0,
        "pid": "[REDACTED_MACHINE]",
        "probe_fits_authorized": 0,
        "remaining_campaign_seconds": 69701.11446404457,
        "run_id": "2026-10-29_dsainet_p0_wmp_d1_stagea-full-w1",
        "status": "DISPATCHED"
      },
      "evidence": {
        "claim_created": false,
        "contract_sha256": "20dd39535800fc93e4ffb85baf2537945c59323e97083e61a99f7a31479afd25",
        "decision": "NO_SIGNAL_STOP_FIXED_PHASE_TEMPLATE",
        "evidence_id": "DSAINET-P0-WMP-D1-STAGE-A-20261029",
        "fit_checkpoint_extracts": 36,
        "full_payload_local": false,
        "intake_scope": "analysis_v1",
        "neural_training_eligible": false,
        "new_neural_fits": 0,
        "next_action": "STOP_WMP_D1_NO_PROBES",
        "observed_at": "2026-10-29T16:17:22.707588+00:00",
        "paired_EA_context_count": 0,
        "probe_fits": 0,
        "remaining_budget_hours_snapshot": 18.80295534705013,
        "report": "ai4s/programs/dsainet/research/p0-wmp-d1/stagea_analysis_local/REPORT_ZH.md",
        "report_sha256": "d24ac8a072e0758ffad03d279021c5fdf843b85047828be803112d737bbb94b6",
        "research_id": "p0-wmp-d1",
        "result_sha256": "2bb3ba4db810ab4f48064dad03e166fd0123bf9dcc26ee7e9a901857c06e818e",
        "role": "exposed_source_development_nondegeneracy_diagnostic",
        "run_id": "2026-10-29_dsainet_p0_wmp_d1_stagea-full-w1",
        "stage_a_pass": false,
        "stage_b_authorized_conditionally": true,
        "standard_verified_intake": true,
        "verification_sha256": "2b5bacfaf6c14b2e858bdaa060f1830e028d82f94fe01761cb89198bcefcd4e9"
      },
      "executor_id": "lab10",
      "expected_artifact": "analysis-v1.zip",
      "explicit_transport_authorization": {
        "approved_at": "2026-10-29T15:38:55.316506+00:00",
        "archive_sha256": "a1e7bd829b2bd84725bf120cd8a9d096337e24c421cfdd828196e3a627e08019",
        "budget_reset": false,
        "payload": "13 source/contract/brief/synthetic-test files; 68056 bytes; no EEG/checkpoints/credentials",
        "prior_platform_rejection": "Initial upload invocation rejected before process creation: payload/new destination needed explicit binding; no transfer/start occurred",
        "question_item_id": "call_7f380a6980c848a2a4fca9e801d53c60:0",
        "remote_root": "[REDACTED_MACHINE]",
        "scope": "upload then automatic exact-Run reuse/TECH/cost qualification and 36-cell Stage A; zero neural/probe fits; 157h original start; 7200s cap",
        "user_answer": "明确允许上述载荷上传并启动"
      },
      "generic_controller_note": "The legacy controller only models engineering_preflight operations and the closed 4/4 training campaign. Its generic deployment report remains NOT_READY, not relabeled PASS. This separately user-authorized diagnostic uses this exact scope guard and the shared Transaction runtime; it is not an engineering result or another neural-training round.",
      "kind": "user_authorized_bounded_source_only_diagnostic",
      "new_neural_fits": 0,
      "operation_id": "dsainet:p0-wmp-d1:stage-a",
      "original_budget_and_start_preserved": true,
      "probe_fits_in_this_stage": 0,
      "recorded_at": "2026-10-29T15:37:22.920133+00:00",
      "remaining_campaign_hours_at_registration": 19.470261748994545,
      "remote_root": "[REDACTED_MACHINE]",
      "result_role": "exposed_source_development_diagnostic",
      "resume_paused": true,
      "resume_status": "COMPLETE_MAX_ROUNDS",
      "run_id": "2026-10-29_dsainet_p0_wmp_d1_stagea-full-w1",
      "source_manifest_sha256": "2f10cfeafe2180107b069e3056f1d8a6ab2bd8c258455b5829cae1c88fe66172",
      "status": "COMPLETE",
      "user_authorization": {
        "bound_plan_sha256": "d1916c8acdce1c48587ae50c0c117124cae7e4a7b1762581a832ab35723ef687",
        "scope": "Implement and execute the revised conditional P0-WMP-D1 plan within the original 157h accounting; Stage A first, Stage B only after positive verified Stage A and its own TECH/cost gate; zero neural training.",
        "user_request": "按方案推进研究"
      }
    }
  ],
  "parked_campaign_work": [
    {
      "active_round": "dsa-pfc-xds-v0.1-repair4b-physionet",
      "active_run": {
        "bundle_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 53.197,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 1092,
        "recorded_at": "2026-09-29T12:03:19.141627+00:00",
        "round_id": "dsa-pfc-xds-v0.1-repair4b-physionet",
        "run_prefix": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T12:03:37.444473+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T12:04:16.024498+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T12:04:43.872294+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b100b2750fde546499667c6156ca468d8333f156dc1cd694c2fd1012a0010298",
                "execution_seconds": 8.170534133911133,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8.170534133911133
              }
            }
          }
        ]
      },
      "artifacts_preserved": true,
      "automatic_resume": false,
      "campaign": {
        "allowed_transitions": [
          "EVALUATE_FROZEN"
        ],
        "authorization_reason": "User confirmed launch of unchanged P0/native B0 five-seed full LOSO on BNCI004 and all109 PhysioNet subjects: 4 technical fits,1180 formal100epoch fits,1180 fixed target evaluations;72 active hours excluding pure resource wait;1 wiring/transport repair;0 automatic fit retries;one joint analysis then stop.",
        "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
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
            "EVALUATE_FROZEN"
          ],
          "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair4/AUTHORIZATION.md",
          "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
          "evaluation_plan": {
            "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair3/EVALUATION_PLAN_SPLIT.yaml",
            "scope_ids": [
              "004-all-subjects-five-seed-loso",
              "physionet-all-subjects-five-seed-loso"
            ],
            "sha256": "f28af045ea76b1059713ecca3416386652d6ee1af2548d4b00d8c86de35634d1"
          },
          "executor_id": "lab10",
          "recorded_at": "2026-09-29T11:52:36.615274+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "dsa-pfc-xds-v0.1"
            ],
            "allowed_stages": [
              "full"
            ],
            "data_scope_id": "bnci004-physionet-all-subjects-five-seed-loso",
            "question_id": "frozen-p0-cross-dataset-loso-performance"
          },
          "source_sha256": "861f017df1f20e013c5d4b72ce575c65dcff36856567cc4714b8a8e4c2e389cd"
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
              "EVALUATE_FROZEN"
            ],
            "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1/AUTHORIZATION.md",
            "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
            "evaluation_plan": {
              "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1/EVALUATION_PLAN.yaml",
              "scope_ids": [
                "bnci004-physionet-all-subjects-five-seed-loso"
              ],
              "sha256": "2a489ed3639de0afd9d803e7752b332ffd3ef090a4576f04e0493723f3eb7d0f"
            },
            "executor_id": "lab10",
            "recorded_at": "2026-09-28T17:07:47.671459+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "dsa-pfc-xds-v0.1"
              ],
              "allowed_stages": [
                "full"
              ],
              "data_scope_id": "bnci004-physionet-all-subjects-five-seed-loso",
              "question_id": "frozen-p0-cross-dataset-loso-performance"
            },
            "source_sha256": "bcc88a91edefef97fe7b54c05d23963bb87e517bec6969cfb0e34f926850015a"
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
              "EVALUATE_FROZEN"
            ],
            "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair2/AUTHORIZATION.md",
            "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
            "evaluation_plan": {
              "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair2/EVALUATION_PLAN_SPLIT.yaml",
              "scope_ids": [
                "004-all-subjects-five-seed-loso",
                "physionet-all-subjects-five-seed-loso"
              ],
              "sha256": "aa44c0f0c38b4dbbfae935531d030fb0fd54bd58b95ac69db7b501af22967cae"
            },
            "executor_id": "lab10",
            "recorded_at": "2026-09-29T08:42:29.782262+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "dsa-pfc-xds-v0.1"
              ],
              "allowed_stages": [
                "full"
              ],
              "data_scope_id": "bnci004-physionet-all-subjects-five-seed-loso",
              "question_id": "frozen-p0-cross-dataset-loso-performance"
            },
            "source_sha256": "b36858d30c372fd54a10e31c2947637dfde0ade051909130d800eb9d7ba3110d"
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
              "EVALUATE_FROZEN"
            ],
            "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair3/AUTHORIZATION.md",
            "campaign_id": "dsainet-pfc-xds-v0.1-20260929",
            "evaluation_plan": {
              "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair3/EVALUATION_PLAN_SPLIT.yaml",
              "scope_ids": [
                "004-all-subjects-five-seed-loso",
                "physionet-all-subjects-five-seed-loso"
              ],
              "sha256": "f28af045ea76b1059713ecca3416386652d6ee1af2548d4b00d8c86de35634d1"
            },
            "executor_id": "lab10",
            "recorded_at": "2026-09-29T08:53:15.075083+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "dsa-pfc-xds-v0.1"
              ],
              "allowed_stages": [
                "full"
              ],
              "data_scope_id": "bnci004-physionet-all-subjects-five-seed-loso",
              "question_id": "frozen-p0-cross-dataset-loso-performance"
            },
            "source_sha256": "ce00a53a48309b844c755cbdd9a7b8107d88254b2c712cb78dc32e27e596cee8"
          }
        ],
        "governance_chain_id": "dsainet-transaction-v3.0",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-09-29_dsainet_pfc_xds_v0_1-full-w1": {
            "contract_sha256": "f22b2dfbb67aa7a2197166a3b403e508c7fa9726923ce20a599200e66d7a7575",
            "queue_seconds": 549.629141330719,
            "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
            "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1-tx"
          },
          "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1": {
            "contract_sha256": "f506484eebfad01b60eb98985c8f4bedea23fc3679e3984b509e92da3fe02a51",
            "queue_seconds": 0.0,
            "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
            "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-tx"
          },
          "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1": {
            "contract_sha256": "d2265c46eccb3826e8c06657aa5fc5e5760a61da5070bac26f2238441f6842dd",
            "queue_seconds": 0.0,
            "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1",
            "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-tx"
          },
          "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1": {
            "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
            "queue_seconds": 1840.5507397651672,
            "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
            "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx"
          },
          "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1": {
            "contract_sha256": "81d9426ef27c33099478873049bb2e01bd7071822ff85a49b4772a95970cfc37",
            "queue_seconds": 0.0,
            "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-full-w1",
            "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4_004-tx"
          },
          "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1": {
            "contract_sha256": "b100b2750fde546499667c6156ca468d8333f156dc1cd694c2fd1012a0010298",
            "queue_seconds": 0.0,
            "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1",
            "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-tx"
          }
        },
        "round_decisions": [],
        "started_at": "2026-09-28T17:04:54.207331+00:00"
      },
      "parked_at": "2026-09-29T13:15:22.725032+00:00",
      "resume_round_id": "dsa-pfc-xds-v0.1-physionet-resume1",
      "resumed_at": "2026-09-30T05:46:31.157466+00:00",
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 72.0,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 0,
        "started_at": "2026-09-28T17:04:54.207331+00:00"
      },
      "scientific_decision": false,
      "snapshot": "ai4s/programs/dsainet/research/dsa-sid-v0.1/PAUSED_PREDECESSOR_STATE.json",
      "status": "RESUMED_BY_USER"
    }
  ],
  "paused": true,
  "pending_continuation": null,
  "performance_candidate_retention_history": [
    {
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/AUTHORIZATION.md",
      "candidate_id": "DSA-AEL-P0-FROZEN-20260927",
      "implementation_changed": false,
      "recorded_at": "2026-09-30T05:53:38.338268+00:00",
      "scientific_verdicts_unchanged": true
    }
  ],
  "performance_candidates": [
    {
      "broad_cross_dataset_stable_superiority_claim": "CLOSED_BY_USER",
      "candidate_id": "DSA-AEL-P0-FROZEN-20260927",
      "candidate_innovation_verified": false,
      "manifest": "ai4s/programs/dsainet/research/P0_FROZEN_PERFORMANCE_CANDIDATE.json",
      "retention_record": "ai4s/programs/dsainet/research/P0_CANDIDATE_RETENTION_20261010.md",
      "scientific_verdicts_unchanged": true,
      "status": "RETAINED_HISTORICAL_PERFORMANCE_AND_INNOVATION_CANDIDATE"
    }
  ],
  "physionet_resume": {
    "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/AUTHORIZATION.md",
    "budget_extended": false,
    "last_observation": {
      "checked_at": "2026-09-30T09:14:40.809647+00:00",
      "does_not_change_run_status": true,
      "record": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/STATUS_CHECK_20260930.json",
      "status": "REMOTE_OBSERVATION_UNAVAILABLE"
    },
    "manual_successor_run_id": "2026-10-02_dsainet_pfc_xds_v0_1_physionet_resume2-full-w1",
    "manual_successor_status": "USER_REPORTED_RUNNING",
    "new_technical_fits": 0,
    "original_run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair4b_physionet-full-w1",
    "original_runtime_preserved": true,
    "p0_preserved": true,
    "pre_resume_state": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/PRE_RESUME_STATE.json",
    "recorded_at": "2026-09-30T05:53:38.338268+00:00",
    "remaining_formal_fits": 1052,
    "remaining_original_seconds_at_freeze": 129492,
    "remote_check": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/REMOTE_CHECK.json",
    "remote_status": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume1/LIVE_STATUS.json",
    "reused_formal_fits": 38,
    "reused_technical_fits": 2,
    "round_id": "dsa-pfc-xds-v0.1-physionet-resume1",
    "run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1",
    "scientific_result": false,
    "status": "RUNNING"
  },
  "preparation_accounting": {
    "charged_from": "2026-10-18T04:50:00+00:00",
    "reason": "Count all Q preparation under user authorized 48h; no old budget transfer",
    "registered_at": "2026-10-18T05:27:42.574457+00:00"
  },
  "previous_active_run_before_resume4_reconciliation": {
    "bundle_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-bundle",
    "dispatch_status": "REMOTE_ACCEPTED",
    "estimated_training_hours": 35.47,
    "execution_mode": "user_managed",
    "executor_id": "lab10",
    "planned_units": 1092,
    "recorded_at": "2026-09-30T05:47:33.174577+00:00",
    "round_id": "dsa-pfc-xds-v0.1-physionet-resume1",
    "run_prefix": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1",
    "transaction_operations": [
      {
        "operation": "upload",
        "recorded_at": "2026-09-30T05:48:30.378747+00:00",
        "result": {
          "action": "UPLOADED",
          "monitor_powershell": "[REDACTED_MACHINE]",
          "run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1"
        }
      },
      {
        "operation": "launch",
        "recorded_at": "2026-09-30T05:50:21.948966+00:00",
        "result": {
          "action": "SUBMISSION_SENT_NOT_VERIFIED",
          "monitor_powershell": "[REDACTED_MACHINE]",
          "run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1"
        }
      },
      {
        "operation": "probe",
        "recorded_at": "2026-09-30T05:50:59.103913+00:00",
        "result": {
          "action": "RECONCILE_SAME_NODE",
          "node_id": "full",
          "run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1",
          "status": "RUNNING",
          "timing": {
            "contract_sha256": "7628f86f356660223ebd7ba50be5486de96a594dbd0a8eb205ed1675bc848ccb",
            "execution_seconds": 26.487927675247192,
            "queue_seconds": 0.0,
            "queue_time_policy": "exclude_resource_wait",
            "run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1",
            "transaction_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-tx",
            "waiting_for_resources": false,
            "wall_seconds": 26.487927675247192
          }
        }
      }
    ]
  },
  "program_id": "dsainet",
  "readerfix1_recovery": {
    "budget_authority_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/BUDGET_AUTHORITY.json",
    "budget_authority_sha256": "1dd52c1541888da5d84803bff21788046ead7216d8ff09c3ae47d608b0a787db",
    "campaign_id": "dsainet-ds07-r1",
    "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/FAILURE_PROOF.json",
    "failure_proof_sha256": "603b251d599280190614e3de9bff7abca1a292d3e7f7308c94e7f3a1edece5dc",
    "recovered_at": "2026-11-02T13:45:25.816291+00:00",
    "replacement_round_id": "ds07-r1-science1-readerfix1",
    "science_ceiling_hours": 33,
    "source_run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
    "status": "READY_NOT_REGISTERED",
    "total_hours": 266,
    "transaction_ceiling_hours": 39
  },
  "run_control": {
    "continuation_policy_version": "evidence_to_design_v1",
    "continue_after_positive": false,
    "max_rounds": 1,
    "monitor": "blocking",
    "night_budget_hours": 312,
    "queue_time_policy": "exclude_resource_wait",
    "round_index": 1,
    "started_at": "2026-10-23T13:28:00+00:00"
  },
  "schema_version": "mieeg-ai4s-state-v1",
  "scientific_interpretation": {
    "claim_ledger_revision": "20261008-r1-pending",
    "claim_release": false,
    "complete_valid_evaluation": true,
    "gate_count": 6,
    "gate_pass_count": 0,
    "independent_joint_review": "pending_missing_final_reports_after_bounded_review",
    "performance_gate_pass": false,
    "review_status": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-target-resume16/review/REVIEW_STATUS.json",
    "round_id": "dsa-pfc-xds-v0.1-physionet-target-resume16",
    "scope_closed": true
  },
  "status": "COMPLETE_MAX_ROUNDS",
  "summaryfix1_recovery": {
    "budget_authority_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/BUDGET_AUTHORITY.json",
    "budget_authority_sha256": "81de064bb3b1abb886f28a8ed8bd441030de829782e514c0ad3a107e59d0cb3b",
    "campaign_id": "dsainet-ds07-r1",
    "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/FAILURE_PROOF.json",
    "failure_proof_sha256": "ddc071fdf3a34d914d644d1e72b403f01388fee0002883b0e41a3d9bb3270893",
    "local_replay_receipt_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/LOCAL_REPLAY_RECEIPT.json",
    "local_replay_receipt_sha256": "22ff29d281114958d9e69baa11f4d4cc9020a493a026a3582f5bd4e772f56d47",
    "previous_total_hours": 276,
    "recovered_at": "2026-11-03T14:09:52.027274+00:00",
    "replacement_round_id": "ds07-r1-science1-summaryfix1",
    "reuse_contract_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/REUSE_CONTRACT.json",
    "reuse_contract_sha256": "80030c85e3f00bbdb57d50c7076cbcc65d70a4e93ca74bd45efaccf4733dba77",
    "science_ceiling_hours": 41,
    "source_run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
    "status": "READY_NOT_REGISTERED",
    "technical_ceiling_hours": 2,
    "total_hours": 296,
    "transaction_ceiling_hours": 47
  },
  "target_recovery_preparation": {
    "added_budget_seconds": 0,
    "guard_relocation_synthetic_validation": "PASS",
    "remaining_target_evaluations": 1071,
    "reused_target_evaluations": 19,
    "round_id": "dsa-pfc-xds-v0.1-physionet-target-resume13",
    "source_fit_count": 1090,
    "status": "RUNNING",
    "zero_forward_proof": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-target-resume13/TARGET_ZERO_FORWARD_PROOF.json"
  },
  "telemetryfix1_recovery": {
    "budget_authority_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/BUDGET_AUTHORITY.json",
    "budget_authority_sha256": "c7f7349ef80d8845c1ffadb4e0f0a58a8b2afa313b91e1604709db59158d9a97",
    "campaign_id": "dsainet-ds07-r1",
    "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/FAILURE_PROOF.json",
    "failure_proof_sha256": "09c3bfa6b5498a16f01a7e306015e318c8e5af403f9937d9c5bd5d27a73c195c",
    "previous_total_hours": 266,
    "recovered_at": "2026-11-02T16:50:07.348007+00:00",
    "replacement_round_id": "ds07-r1-science1-telemetryfix1",
    "science_ceiling_hours": 41,
    "source_run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
    "status": "READY_NOT_REGISTERED",
    "total_hours": 276,
    "transaction_ceiling_hours": 47
  },
  "updated_at": "2026-11-05T13:09:08.803027+00:00",
  "user_pause": {
    "archive_reason": "解除 PhysioNet 用户暂停：恢复指令见本轮 AUTHORIZATION.md。",
    "archived": true,
    "archived_at": "2026-09-30T05:46:31.157466+00:00",
    "at": "2026-09-29T12:07:25.751143+00:00",
    "preserve_artifacts": true,
    "reason": "004 only; do not continue PhysioNet",
    "remote_owned_processes_exited": [
      2586415,
      2587818,
      2588412
    ]
  },
  "v3_follow_up": {
    "decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-recover53_decision.yaml",
    "evidence_id": "AI4S-DSAINET-p0-cue-r2-recover53",
    "next_design": null,
    "reason": "round_limit"
  },
  "verified_resource_wait_history": [
    {
      "already_in_runtime_baseline_seconds": 32898.104853630066,
      "queue_sha256": "f05512f71dfe3e25d1d1b1e2b2b73728b069b24c7a0820a732d36e4410c6942e",
      "run_id": "2026-11-01_dsainet_ds07_r1_tech1",
      "seconds": 1842.242424249649
    }
  ],
  "zero_public_reserve_recovery": {
    "added_budget_seconds": 0,
    "automatic_training_retries": 0,
    "completed_total": 551,
    "contract_sha256": "d4f40832a7bc391bc2af1e02bc0829fe27b390ce1b4538173a01be8ee2fc4cda",
    "explicit_failed_unit_recovery": [
      "physionet_B0_s4_t43",
      "physionet_P0_s1_t61"
    ],
    "failed": 0,
    "fit_commitment_mib": 2048,
    "full": "RUNNING",
    "pending": 536,
    "public_reserve_mib": 0,
    "query_time": "2026-10-06T07:44:25.486571+08:00",
    "recorded_at": "2026-10-05T23:43:50.881781+00:00",
    "remaining_execution_seconds": 36817,
    "remaining_formal_fits": 539,
    "reused_formal_fits": 551,
    "run_id": "2026-10-06_dsainet_pfc_xds_v0_1_physionet_resume8-full-w1",
    "running": 3,
    "scientific_intake": false,
    "smoke": "PASS",
    "status": "RUNNING",
    "target_complete": 0
  }
}

```
