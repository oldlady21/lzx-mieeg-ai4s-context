# State 阅读分段 2

完整脱敏文件：`ai4s/programs/dsainet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`f82348654ac8c6f7aa650bb18e93964fe7d7ff12011e22926810756e98c7e30f`。UTF-8 字节范围：[500000, 1000000) / 1146765。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
cal_gpu": 3,
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
  "devicefix1_recovery": {
    "budget_authority_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/BUDGET_AUTHORITY.json",
    "budget_authority_sha256": "0d5cd9313870c766edfc238d571b1147ff8cebe6d830ff677104a0c31a1cf7f5",
    "campaign_id": "dsainet-ds07-r1",
    "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/FAILURE_PROOF.json",
    "failure_proof_sha256": "3b73f29709b6e739e0306dd39a3ab2a93eae20f2a60f5228e747e0572fd7af2f",
    "local_replay_receipt_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/LOCAL_REPLAY_RECEIPT.json",
    "local_replay_receipt_sha256": "5d3399bea2811185d5071a37f1ffba4c49a188c8b4aab1fa88df34b137420a7c",
    "previous_total_hours": 296,
    "recovered_at": "2026-11-04T06:25:28.927092+00:00",
    "replacement_round_id": "ds07-r1-science1-devicefix1",
    "reuse_contract_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/REUSE_CONTRACT.json",
    "reuse_contract_sha256": "80030c85e3f00bbdb57d50c7076cbcc65d70a4e93ca74bd45efaccf4733dba77",
    "science_ceiling_hours": 41,
    "source_run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
    "status": "READY_NOT_REGISTERED",
    "technical_ceiling_hours": 2,
    "total_hours": 312,
    "transaction_ceiling_hours": 47
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
    },
    {
      "contract_sha256": "ee394e5bc6ddf2b0bf5603fd8dc10419e5b88e2e36f9c032db8df5e8d77afb68",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "09c3bfa6b5498a16f01a7e306015e318c8e5af403f9937d9c5bd5d27a73c195c",
      "repair_id": "telemetryfix1",
      "replacement_round_id": "ds07-r1-science1-telemetryfix1",
      "scientific_disposition": "NONE",
      "source_run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
      "status": "ENGINEERING_INVALID_SOURCE_ARCHIVED"
    },
    {
      "contract_sha256": "e72dd5f020f21d4b52fb749265c08a3759befee5507f392ccf5b7355e019b59e",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "ddc071fdf3a34d914d644d1e72b403f01388fee0002883b0e41a3d9bb3270893",
      "repair_id": "summaryfix1",
      "replacement_round_id": "ds07-r1-science1-summaryfix1",
      "scientific_disposition": "NONE",
      "source_run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
      "status": "ENGINEERING_INVALID_SOURCE_ARCHIVED"
    },
    {
      "contract_sha256": "b9824b039bc8dcaaaa907ac8a1c7cdfd0d03b90cbb7a73cc82438edce1c748ef",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "3b73f29709b6e739e0306dd39a3ab2a93eae20f2a60f5228e747e0572fd7af2f",
      "repair_id": "devicefix1",
      "replacement_round_id": "ds07-r1-science1-devicefix1",
      "scientific_disposition": "NONE",
      "source_run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
      "status": "ENGINEERING_INVALID_SOURCE_ARCHIVED"
    },
    {
      "authorization_ref": "ai4s/programs/dsainet/research/b0_spatial_filter_radius_repair1_20261123/AUTHORIZATION.md",
      "contract_sha256": "68c335464cec00edfac0b499a51964588e39e3a6fb0454ed15224a329b79ab1a",
      "inherited_task_ids": [
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "C0_s0_t3",
        "C0_s0_t4",
        "C0_s0_t5",
        "C0_s1_t3",
        "C0_s1_t4",
        "C0_s1_t5",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s1_t3",
        "P0_s1_t5"
      ],
      "inventory_sha256": "7e4d942edaf25a728738e55504784a47818699d3f469e5651d2ecc1ccc1d727d",
      "kind": "radius_cudnn_single_task_repair1",
      "pinned_gpu": 7,
      "previous_active_run": {
        "bundle_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 19,
        "recorded_at": "2026-11-23T06:50:49.801581+00:00",
        "round_id": "dsainet-b0-spatial-filter-radius-r1",
        "run_prefix": "2026-11-23_dsainet_b0_spatial_filter_radius_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-23T06:55:31.861739+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-23T06:55:54.981265+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-23T06:57:20.596594+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4e426521b0b1e32dae933f6fc49cd85a51c29192885aa79ad6b40ee23ec15724",
                "execution_seconds": 2.1204333305358887,
                "queue_seconds": 82.03466510772705,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1",
                "transaction_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 84.15509843826294
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-23T12:25:44.451725+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "4e426521b0b1e32dae933f6fc49cd85a51c29192885aa79ad6b40ee23ec15724",
                "execution_seconds": 2803.303638935089,
                "queue_seconds": 10774.293335676193,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1",
                "transaction_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13577.596974611282
              }
            }
          }
        ]
      },
      "previous_authorization": {
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
        "authorization_ref": "ai4s/programs/dsainet/research/b0_spatial_filter_radius_20261123/AUTHORIZATION.md",
        "campaign_id": "dsainet-b0-spatial-filter-radius-20261123",
        "executor_id": "lab10",
        "recorded_at": "2026-11-23T06:50:42.923221+00:00",
        "research_scope": {
          "allow_new_module": false,
          "allowed_module_ids": [
            "dsainet.native-spatial-filter-radius.r1"
          ],
          "allowed_stages": [
            "source_native_spatial_filter_radius"
          ],
          "data_scope_id": "bnci001-cue4-exposed-A04-A06-no-target",
          "question_id": "tokenizer-fixed-radius-space-versus-time"
        },
        "source_sha256": "16e820ef2ced62b6e398e0d8b6f1d615668f0d3cc06dc8d3eb58b3ec214b3291"
      },
      "recorded_at": "2026-11-23T12:34:35.520834+00:00",
      "retry_task_ids": [
        "P0_s1_t4"
      ],
      "scientific_result": false,
      "source_identity": {
        "contract_sha256": "4e426521b0b1e32dae933f6fc49cd85a51c29192885aa79ad6b40ee23ec15724",
        "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1",
        "transaction_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-tx"
      }
    },
    {
      "authorization_ref": "ai4s/programs/dsainet/research/b0_spatial_filter_radius_repair1_20261123/AUTHORIZATION.md",
      "contract_sha256": "64640ec460385163defd6d5549025e63ee5fe4875002df7cecb6b1edd8d9edb7",
      "inherited_task_ids": [
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "C0_s0_t3",
        "C0_s0_t4",
        "C0_s0_t5",
        "C0_s1_t3",
        "C0_s1_t4",
        "C0_s1_t5",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s1_t3",
        "P0_s1_t5"
      ],
      "inventory_sha256": "7e4d942edaf25a728738e55504784a47818699d3f469e5651d2ecc1ccc1d727d",
      "kind": "radius_cudnn_repair1_gpu_allowlist_preworker_fix",
      "pinned_gpu": 7,
      "previous_active_run": {
        "bundle_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.2,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 2,
        "recorded_at": "2026-11-23T12:34:35.520834+00:00",
        "round_id": "dsainet-b0-spatial-filter-radius-r1-repair1",
        "run_prefix": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-23T12:34:54.229876+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-23T12:34:57.723502+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-23T12:35:30.425213+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "68c335464cec00edfac0b499a51964588e39e3a6fb0454ed15224a329b79ab1a",
                "execution_seconds": 1.8123822212219238,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1-full-w1",
                "transaction_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1.8123822212219238
              }
            }
          }
        ]
      },
      "previous_authorization": {
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
        "authorization_ref": "ai4s/programs/dsainet/research/b0_spatial_filter_radius_repair1_20261123/AUTHORIZATION.md",
        "campaign_id": "dsainet-b0-spatial-filter-radius-20261123",
        "executor_id": "lab10",
        "recorded_at": "2026-11-23T12:34:35.520834+00:00",
        "repair_contract_sha256": "68c335464cec00edfac0b499a51964588e39e3a6fb0454ed15224a329b79ab1a",
        "repair_task_ids": [
          "P0_s1_t4"
        ],
        "research_scope": {
          "allow_new_module": false,
          "allowed_module_ids": [
            "dsainet.native-spatial-filter-radius.r1"
          ],
          "allowed_stages": [
            "source_native_spatial_filter_radius"
          ],
          "data_scope_id": "bnci001-cue4-exposed-A04-A06-no-target",
          "question_id": "tokenizer-fixed-radius-space-versus-time"
        },
        "source_sha256": "16e820ef2ced62b6e398e0d8b6f1d615668f0d3cc06dc8d3eb58b3ec214b3291"
      },
      "recorded_at": "2026-11-23T12:36:38.693771+00:00",
      "retry_task_ids": [
        "P0_s1_t4"
      ],
      "scientific_result": false,
      "source_identity": {
        "contract_sha256": "4e426521b0b1e32dae933f6fc49cd85a51c29192885aa79ad6b40ee23ec15724",
        "run_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-full-w1",
        "transaction_id": "2026-11-23_dsainet_b0_spatial_filter_radius_r1-tx"
      }
    }
  ],
  "evidence_status": "exposed_development_screen_recorded_no_claim_release",
  "external_interruption_recovery": {
    "failed_run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1",
    "reason_class": "USER_AUTHORIZED_REDEPLOYMENT",
    "recorded_at": "2026-11-22T14:56:41.625852+00:00",
    "replacement_round_id": "dsainet-b0-attention-token-grid-r1-py39fix1",
    "report": "ai4s/programs/dsainet/research/b0_asymmetric_token_grid_20261122_py39fix1/REDEPLOYMENT.json",
    "research_gate": {
      "hypothesis_id": "allocation-of-a-fixed-attention-grid-budget",
      "module_id": "dsainet.native-attention-token-grid.r1",
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
        "planned_units": 433,
        "recorded_at": "2026-09-24T13:52:31.445065+00:00",
        "round_id": "dsa-fut-v0.1-repair3",
        "run_prefix": "2026-09-24_dsainet_fut_v0_1_repair3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T13:53:38.266522+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T13:53:42.811145+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T13:54:55.458657+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "caae28a866833a762a1bc617fc95d08cd7e44e9f820a2cb761d04b4b6d3e7dd6",
                "execution_seconds": 68.8112382888794,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1",
                "transaction_id": "2026-09-24_dsainet_fut_v0_1_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 68.8112382888794
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T18:42:19.809633+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "caae28a866833a762a1bc617fc95d08cd7e44e9f820a2cb761d04b4b6d3e7dd6",
                "execution_seconds": 3117.924150466919,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dsainet_fut_v0_1_repair3-full-w1",
                "transaction_id": "2026-09-24_dsainet_fut_v0_1_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3117.924150466919
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-24T18:49:46.927158+00:00",
      "rerun_task_ids": [
        "B0_s1_t1__DIRECT__real",
        "B0_s1_t1__DIRECT__within_subject_permuted",
        "B0_s1_t2__DIRECT__real",
        "B0_s1_t2__DIRECT__within_subject_permuted",
        "B0_s1_t3__DIRECT__real",
        "B0_s1_t3__DIRECT__within_subject_permuted",
        "B0_s1_t4__DIRECT__real",
        "B0_s1_t4__DIRECT__within_subject_permuted",
        "B0_s1_t5__DIRECT__real",
        "B0_s1_t5__DIRECT__within_subject_permuted",
        "B0_s1_t6__DIRECT__real",
        "B0_s1_t6__DIRECT__within_subject_permuted",
        "B0_s1_t7__DIRECT__real",
        "B0_s1_t7__DIRECT__within_subject_permuted",
        "B0_s1_t8__DIRECT__real",
        "B0_s1_t8__DIRECT__within_subject_permuted",
        "C0_s0_t5__DIRECT__real",
        "C0_s0_t5__DIRECT__within_subject_permuted",
        "C0_s1_t0__DIRECT__within_subject_permuted",
        "C0_s1_t1__DIRECT__real",
        "C0_s1_t1__DIRECT__within_subject_permuted",
        "C0_s1_t2__DIRECT__real",
        "C0_s1_t2__DIRECT__within_subject_permuted",
        "C0_s1_t3__DIRECT__real",
        "C0_s1_t3__DIRECT__within_subject_permuted",
        "C0_s1_t4__DIRECT__real",
        "C0_s1_t4__DIRECT__within_subject_permuted",
        "C0_s1_t5__DIRECT__real",
        "C0_s1_t5__DIRECT__within_subject_permuted",
        "C0_s1_t6__DIRECT__real",
        "C0_s1_t6__DIRECT__within_subject_permuted",
        "C0_s1_t7__DIRECT__real",
        "C0_s1_t7__DIRECT__within_subject_permuted",
        "C0_s1_t8__DIRECT__real",
        "C0_s1_t8__DIRECT__within_subject_permuted",
        "P0_s1_t0__DIRECT__within_subject_permuted",
        "P0_s1_t1__DIRECT__real",
        "P0_s1_t2__DIRECT__real",
        "P0_s1_t2__DIRECT__within_subject_permuted",
        "P0_s1_t3__DIRECT__real",
        "P0_s1_t3__DIRECT__within_subject_permuted",
        "P0_s1_t4__DIRECT__real",
        "P0_s1_t4__DIRECT__within_subject_permuted",
        "P0_s1_t5__DIRECT__real",
        "P0_s1_t5__DIRECT__within_subject_permuted",
        "P0_s1_t6__DIRECT__real",
        "P0_s1_t7__DIRECT__real",
        "P0_s1_t7__DIRECT__within_subject_permuted",
        "P0_s1_t8__DIRECT__real",
        "P0_s1_t8__DIRECT__within_subject_permuted",
        "S0_s1_t1__DIRECT__real",
        "S0_s1_t1__DIRECT__within_subject_permuted",
        "S0_s1_t2__DIRECT__real",
        "S0_s1_t2__DIRECT__within_subject_permuted",
        "S0_s1_t3__DIRECT__real",
        "S0_s1_t3__DIRECT__within_subject_permuted",
        "S0_s1_t4__DIRECT__real",
        "S0_s1_t4__DIRECT__within_subject_permuted",
        "S0_s1_t5__DIRECT__real",
        "S0_s1_t5__DIRECT__within_subject_permuted",
        "S0_s1_t6__DIRECT__real",
        "S0_s1_t6__DIRECT__within_subject_permuted",
        "S0_s1_t7__DIRECT__within_subject_permuted",
        "S0_s1_t8__DIRECT__real",
        "S0_s1_t8__DIRECT__within_subject_permuted"
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
        "B0_s0_t5__DIRECT__within_subject_permuted",
        "B0_s0_t5__SELF__real",
        "B0_s0_t5__SELF__within_subject_permuted",
        "B0_s0_t6__CROSS__real",
        "B0_s0_t6__CROSS__within_subject_permuted",
        "B0_s0_t6__DIRECT__real",
        "B0_s0_t6__DIRECT__within_subject_permuted",
        "B0_s0_t6__SELF__real",
        "B0_s0_t6__SELF__within_subject_permuted",
        "B0_s0_t7__CROSS__real",
        "B0_s0_t7__CROSS__within_subject_permuted",
        "B0_s0_t7__DIRECT__real",
        "B0_s0_t7__DIRECT__within_subject_permuted",
        "B0_s0_t7__SELF__real",
        "B0_s0_t7__SELF__within_subject_permuted",
        "B0_s0_t8__CROSS__real",
        "B0_s0_t8__CROSS__within_subject_permuted",
        "B0_s0_t8__DIRECT__real",
        "B0_s0_t8__DIRECT__within_subject_permuted",
        "B0_s0_t8__SELF__real",
        "B0_s0_t8__SELF__within_subject_permuted",
        "B0_s1_t0__CROSS__real",
        "B0_s1_t0__CROSS__within_subject_permuted",
        "B0_s1_t0__DIRECT__real",
        "B0_s1_t0__DIRECT__within_subject_permuted",
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
        "C0_s0_t6__DIRECT__real",
        "C0_s0_t6__DIRECT__within_subject_permuted",
        "C0_s0_t6__SELF__real",
        "C0_s0_t6__SELF__within_subject_permuted",
        "C0_s0_t7__CROSS__real",
        "C0_s0_t7__CROSS__within_subject_permuted",
        "C0_s0_t7__DIRECT__real",
        "C0_s0_t7__DIRECT__within_subject_permuted",
        "C0_s0_t7__SELF__real",
        "C0_s0_t7__SELF__within_subject_permuted",
        "C0_s0_t8__CROSS__real",
        "C0_s0_t8__CROSS__within_subject_permuted",
        "C0_s0_t8__DIRECT__real",
        "C0_s0_t8__DIRECT__within_subject_permuted",
        "C0_s0_t8__SELF__real",
        "C0_s0_t8__SELF__within_subject_permuted",
        "C0_s1_t0__CROSS__real",
        "C0_s1_t0__CROSS__within_subject_permuted",
        "C0_s1_t0__DIRECT__real",
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
        "P0_s0_t5__DIRECT__real",
        "P0_s0_t5__DIRECT__within_subject_permuted",
        "P0_s0_t5__SELF__real",
        "P0_s0_t5__SELF__within_subject_permuted",
        "P0_s0_t6__CROSS__real",
        "P0_s0_t6__CROSS__within_subject_permuted",
        "P0_s0_t6__DIRECT__real",
        "P0_s0_t6__DIRECT__within_subject_permuted",
        "P0_s0_t6__SELF__real",
        "P0_s0_t6__SELF__within_subject_permuted",
        "P0_s0_t7__CROSS__real",
        "P0_s0_t7__CROSS__within_subject_permuted",
        "P0_s0_t7__DIRECT__real",
        "P0_s0_t7__DIRECT__within_subject_permuted",
        "P0_s0_t7__SELF__real",
        "P0_s0_t7__SELF__within_subject_permuted",
        "P0_s0_t8__CROSS__real",
        "P0_s0_t8__CROSS__within_subject_permuted",
        "P0_s0_t8__DIRECT__real",
        "P0_s0_t8__DIRECT__within_subject_permuted",
        "P0_s0_t8__SELF__real",
        "P0_s0_t8__SELF__within_subject_permuted",
        "P0_s1_t0__CROSS__real",
        "P0_s1_t0__CROSS__within_subject_permuted",
        "P0_s1_t0__DIRECT__real",
        "P0_s1_t0__SELF__real",
        "P0_s1_t0__SELF__within_subject_permuted",
        "P0_s1_t1__CROSS__real",
        "P0_s1_t1__CROSS__within_subject_permuted",
        "P0_s1_t1__DIRECT__within_subject_permuted",
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
        "S0_s0_t6__DIRECT__real",
        "S0_s0_t6__DIRECT__within_subject_permuted",
        "S0_s0_t6__SELF__real",
        "S0_s0_t6__SELF__within_subject_permuted",
        "S0_s0_t7__CROSS__real",
        "S0_s0_t7__CROSS__within_subject_permuted",
        "S0_s0_t7__DIRECT__real",
        "S0_s0_t7__DIRECT__within_subject_permuted",
        "S0_s0_t7__SELF__real",
        "S0_s0_t7__SELF__within_subject_permuted",
        "S0_s0_t8__CROSS__real",
        "S0_s0_t8__CROSS__within_subject_permuted",
        "S0_s0_t8__DIRECT__real",
        "S0_s0_t8__DIRECT__within_subject_permuted",
        "S0_s0_t8__SELF__real",
        "S0_s0_t8__SELF__within_subject_permuted",
        "S0_s1_t0__CROSS__real",
        "S0_s1_t0__CROSS__within_subject_permuted",
        "S0_s1_t0__DIRECT__real",
        "S0_s1_t0__DIRECT__within_subject_permuted",
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
        "path": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair4/SOURCE_REUSE_MANIFEST.json",
        "sha256": "32031cabc1c308ee2eed48353062eddf867a915eb437f7f2791cc434442309ef"
      }
    },
    {
      "attempt_class": "explicit_fut_capacity_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair5/AUTHORIZATION.md",
      "campaign_id": "dsainet-fut-v0.1-20260924",
      "failed_run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-25_dsainet_fut_v0_1_repair4-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 11.732,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 433,
        "recorded_at": "2026-09-24T18:50:12.224908+00:00",
        "round_id": "dsa-fut-v0.1-repair4",
        "run_prefix": "2026-09-25_dsainet_fut_v0_1_repair4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T18:52:40.485695+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T18:52:43.554427+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T18:52:59.928526+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b68a82811e4c678c8bbef8e63991d6e6fd1081638edf680524c7d7f223b82c4b",
                "execution_seconds": 12.491556167602539,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
                "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair4-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12.491556167602539
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T18:53:44.780402+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "precheck",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b68a82811e4c678c8bbef8e63991d6e6fd1081638edf680524c7d7f223b82c4b",
                "execution_seconds": 57.28926348686218,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
                "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair4-tx",
                "waiting_for_resources": false,
                "wall_seconds": 57.28926348686218
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T02:20:54.395662+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "b68a82811e4c678c8bbef8e63991d6e6fd1081638edf680524c7d7f223b82c4b",
                "execution_seconds": 11949.837693691254,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_fut_v0_1_repair4-full-w1",
                "transaction_id": "2026-09-25_dsainet_fut_v0_1_repair4-tx",
                "waiting_for_resources": false,
                "wall_seconds": 11949.837693691254
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-25T02:27:50.352141+00:00",
      "rerun_task_ids": [
        "B0_s1_t4__DIRECT__within_subject_permuted",
        "B0_s1_t5__DIRECT__real",
        "B0_s1_t5__DIRECT__within_subject_permuted",
        "B0_s1_t6__DIRECT__real",
        "B0_s1_t6__DIRECT__within_subject_permuted",
        "B0_s1_t7__DIRECT__real",
        "B0_s1_t7__DIRECT__within_subject_permuted",
        "B0_s1_t8__DIRECT__real",
        "B0_s1_t8__DIRECT__within_subject_permuted",
        "C0_s1_t3__DIRECT__real",
        "C0_s1_t3__DIRECT__within_subject_permuted",
        "C0_s1_t4__DIRECT__real",
        "C0_s1_t4__DIRECT__within_subject_permuted",
        "C0_s1_t6__DIRECT__real",
        "C0_s1_t6__DIRECT__within_subject_permuted",
        "C0_s1_t7__DIRECT__real",
        "C0_s1_t7__DIRECT__within_subject_permuted",
        "C0_s1_t8__DIRECT__real",
        "C0_s1_t8__DIRECT__within_subject_permuted",
        "P0_s1_t4__DIRECT__within_subject_permuted",
        "P0_s1_t5__DIRECT__real",
        "P0_s1_t5__DIRECT__within_subject_permuted",
        "P0_s1_t6__DIRECT__real",
        "P0_s1_t7__DIRECT__real",
        "S0_s1_t4__DIRECT__real",
        "S0_s1_t4__DIRECT__within_subject_permuted",
        "S0_s1_t5__DIRECT__real",
        "S0_s1_t5__DIRECT__within_subject_permuted",
        "S0_s1_t6__DIRECT__real",
        "S0_s1_t6__DIRECT__within_subject_permuted",
        "S0_s1_t8__DIRECT__real",
        "S0_s1_t8__DIRECT__within_subject_permuted"
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
        "B0_s0_t5__DIRECT__within_subject_permuted",
        "B0_s0_t5__SELF__real",
        "B0_s0_t5__SELF__within_subject_permuted",
        "B0_s0_t6__CROSS__real",
        "B0_s0_t6__CROSS__within_subject_permuted",
        "B0_s0_t6__DIRECT__real",
        "B0_s0_t6__DIRECT__within_subject_permuted",
        "B0_s0_t6__SELF__real",
        "B0_s0_t6__SELF__within_subject_permuted",
        "B0_s0_t7__CROSS__real",
        "B0_s0_t7__CROSS__within_subject_permuted",
        "B0_s0_t7__DIRECT__real",
        "B0_s0_t7__DIRECT__within_subject_permuted",
        "B0_s0_t7__SELF__real",
        "B0_s0_t7__SELF__within_subject_permuted",
        "B0_s0_t8__CROSS__real",
        "B0_s0_t8__CROSS__within_subject_permuted",
        "B0_s0_t8__DIRECT__real",
        "B0_s0_t8__DIRECT__within_subject_permuted",
        "B0_s0_t8__SELF__real",
        "B0_s0_t8__SELF__within_subject_permuted",
        "B0_s1_t0__CROSS__real",
        "B0_s1_t0__CROSS__within_subject_permuted",
        "B0_s1_t0__DIRECT__real",
        "B0_s1_t0__DIRECT__within_subject_permuted",
        "B0_s1_t0__SELF__real",
        "B0_s1_t0__SELF__within_subject_permuted",
        "B0_s1_t1__CROSS__real",
        "B0_s1_t1__CROSS__within_subject_permuted",
        "B0_s1_t1__DIRECT__real",
        "B0_s1_t1__DIRECT__within_subject_permuted",
        "B0_s1_t1__SELF__real",
        "B0_s1_t1__SELF__within_subject_permuted",
        "B0_s1_t2__CROSS__real",
        "B0_s1_t2__CROSS__within_subject_permuted",
        "B0_s1_t2__DIRECT__real",
        "B0_s1_t2__DIRECT__within_subject_permuted",
        "B0_s1_t2__SELF__real",
        "B0_s1_t2__SELF__within_subject_permuted",
        "B0_s1_t3__CROSS__real",
        "B0_s1_t3__CROSS__within_subject_permuted",
        "B0_s1_t3__DIRECT__real",
        "B0_s1_t3__DIRECT__within_subject_permuted",
        "B0_s1_t3__SELF__real",
        "B0_s1_t3__SELF__within_subject_permuted",
        "B0_s1_t4__CROSS__real",
        "B0_s1_t4__CROSS__within_subject_permuted",
        "B0_s1_t4__DIRECT__real",
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
        "C0_s0_t5__DIRECT__real",
        "C0_s0_t5__DIRECT__within_subject_permuted",
        "C0_s0_t5__SELF__real",
        "C0_s0_t5__SELF__within_subject_permuted",
        "C0_s0_t6__CROSS__real",
        "C0_s0_t6__CROSS__within_subject_permuted",
        "C0_s0_t6__DIRECT__real",
        "C0_s0_t6__DIRECT__within_subject_permuted",
        "C0_s0_t6__SELF__real",
        "C0_s0_t6__SELF__within_subject_permuted",
        "C0_s0_t7__CROSS__real",
        "C0_s0_t7__CROSS__within_subject_permuted",
        "C0_s0_t7__DIRECT__real",
        "C0_s0_t7__DIRECT__within_subject_permuted",
        "C0_s0_t7__SELF__real",
        "C0_s0_t7__SELF__within_subject_permuted",
        "C0_s0_t8__CROSS__real",
        "C0_s0_t8__CROSS__within_subject_permuted",
        "C0_s0_t8__DIRECT__real",
        "C0_s0_t8__DIRECT__within_subject_permuted",
        "C0_s0_t8__SELF__real",
        "C0_s0_t8__SELF__within_subject_permuted",
        "C0_s1_t0__CROSS__real",
        "C0_s1_t0__CROSS__within_subject_permuted",
        "C0_s1_t0__DIRECT__real",
        "C0_s1_t0__DIRECT__within_subject_permuted",
        "C0_s1_t0__SELF__real",
        "C0_s1_t0__SELF__within_subject_permuted",
        "C0_s1_t1__CROSS__real",
        "C0_s1_t1__CROSS__within_subject_permuted",
        "C0_s1_t1__DIRECT__real",
        "C0_s1_t1__DIRECT__within_subject_permuted",
        "C0_s1_t1__SELF__real",
        "C0_s1_t1__SELF__within_subject_permuted",
        "C0_s1_t2__CROSS__real",
        "C0_s1_t2__CROSS__within_subject_permuted",
        "C0_s1_t2__DIRECT__real",
        "C0_s1_t2__DIRECT__within_subject_permuted",
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
        "C0_s1_t5__DIRECT__real",
        "C0_s1_t5__DIRECT__within_subject_permuted",
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
        "P0_s0_t5__DIRECT__real",
        "P0_s0_t5__DIRECT__within_subject_permuted",
        "P0_s0_t5__SELF__real",
        "P0_s0_t5__SELF__within_subject_permuted",
        "P0_s0_t6__CROSS__real",
        "P0_s0_t6__CROSS__within_subject_permuted",
        "P0_s0_t6__DIRECT__real",
        "P0_s0_t6__DIRECT__within_subject_permuted",
        "P0_s0_t6__SELF__real",
        "P0_s0_t6__SELF__within_subject_permuted",
        "P0_s0_t7__CROSS__real",
        "P0_s0_t7__CROSS__within_subject_permuted",
        "P0_s0_t7__DIRECT__real",
        "P0_s0_t7__DIRECT__within_subject_permuted",
        "P0_s0_t7__SELF__real",
        "P0_s0_t7__SELF__within_subject_permuted",
        "P0_s0_t8__CROSS__real",
        "P0_s0_t8__CROSS__within_subject_permuted",
        "P0_s0_t8__DIRECT__real",
        "P0_s0_t8__DIRECT__within_subject_permuted",
        "P0_s0_t8__SELF__real",
        "P0_s0_t8__SELF__within_subject_permuted",
        "P0_s1_t0__CROSS__real",
        "P0_s1_t0__CROSS__within_subject_permuted",
        "P0_s1_t0__DIRECT__real",
        "P0_s1_t0__DIRECT__within_subject_permuted",
        "P0_s1_t0__SELF__real",
        "P0_s1_t0__SELF__within_subject_permuted",
        "P0_s1_t1__CROSS__real",
        "P0_s1_t1__CROSS__within_subject_permuted",
        "P0_s1_t1__DIRECT__real",
        "P0_s1_t1__DIRECT__within_subject_permuted",
        "P0_s1_t1__SELF__real",
        "P0_s1_t1__SELF__within_subject_permuted",
        "P0_s1_t2__CROSS__real",
        "P0_s1_t2__CROSS__within_subject_permuted",
        "P0_s1_t2__DIRECT__real",
        "P0_s1_t2__DIRECT__within_subject_permuted",
        "P0_s1_t2__SELF__real",
        "P0_s1_t2__SELF__within_subject_permuted",
        "P0_s1_t3__CROSS__real",
        "P0_s1_t3__CROSS__within_subject_permuted",
        "P0_s1_t3__DIRECT__real",
        "P0_s1_t3__DIRECT__within_subject_permuted",
        "P0_s1_t3__SELF__real",
        "P0_s1_t3__SELF__within_subject_permuted",
        "P0_s1_t4__CROSS__real",
        "P0_s1_t4__CROSS__within_subject_permuted",
        "P0_s1_t4__DIRECT__real",
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
        "P0_s1_t7__DIRECT__within_subject_permuted",
        "P0_s1_t7__SELF__real",
        "P0_s1_t7__SELF__within_subject_permuted",
        "P0_s1_t8__CROSS__real",
        "P0_s1_t8__CROSS__within_subject_permuted",
        "P0_s1_t8__DIRECT__real",
        "P0_s1_t8__DIRECT__within_subject_permuted",
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
        "S0_s0_t6__DIRECT__real",
        "S0_s0_t6__DIRECT__within_subject_permuted",
        "S0_s0_t6__SELF__real",
        "S0_s0_t6__SELF__within_subject_permuted",
        "S0_s0_t7__CROSS__real",
        "S0_s0_t7__CROSS__within_subject_permuted",
        "S0_s0_t7__DIRECT__real",
        "S0_s0_t7__DIRECT__within_subject_permuted",
        "S0_s0_t7__SELF__real",
        "S0_s0_t7__SELF__within_subject_permuted",
        "S0_s0_t8__CROSS__real",
        "S0_s0_t8__CROSS__within_subject_permuted",
        "S0_s0_t8__DIRECT__real",
        "S0_s0_t8__DIRECT__within_subject_permuted",
        "S0_s0_t8__SELF__real",
        "S0_s0_t8__SELF__within_subject_permuted",
        "S0_s1_t0__CROSS__real",
        "S0_s1_t0__CROSS__within_subject_permuted",
        "S0_s1_t0__DIRECT__real",
        "S0_s1_t0__DIRECT__within_subject_permuted",
        "S0_s1_t0__SELF__real",
        "S0_s1_t0__SELF__within_subject_permuted",
        "S0_s1_t1__CROSS__real",
        "S0_s1_t1__CROSS__within_subject_permuted",
        "S0_s1_t1__DIRECT__real",
        "S0_s1_t1__DIRECT__within_subject_permuted",
        "S0_s1_t1__SELF__real",
        "S0_s1_t1__SELF__within_subject_permuted",
        "S0_s1_t2__CROSS__real",
        "S0_s1_t2__CROSS__within_subject_permuted",
        "S0_s1_t2__DIRECT__real",
        "S0_s1_t2__DIRECT__within_subject_permuted",
        "S0_s1_t2__SELF__real",
        "S0_s1_t2__SELF__within_subject_permuted",
        "S0_s1_t3__CROSS__real",
        "S0_s1_t3__CROSS__within_subject_permuted",
        "S0_s1_t3__DIRECT__real",
        "S0_s1_t3__DIRECT__within_subject_permuted",
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
        "S0_s1_t7__DIRECT__within_subject_permuted",
        "S0_s1_t7__SELF__real",
        "S0_s1_t7__SELF__within_subject_permuted",
        "S0_s1_t8__CROSS__real",
        "S0_s1_t8__CROSS__within_subject_permuted",
        "S0_s1_t8__SELF__real",
        "S0_s1_t8__SELF__within_subject_permuted"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-fut-v0.1/repair5/SOURCE_REUSE_MANIFEST.json",
        "sha256": "620a3d2a0f9bbea2598327ecbac6d6e0b972b7c89e89d52fbb5f9f644c1cae77"
      }
    },
    {
      "attempt_class": "explicit_ael_missing_only_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-ael-v0.1-repair2/AUTHORIZATION.md",
      "campaign_id": "dsainet-ael-v0.1-20260925",
      "failed_run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-25_dsainet_ael_v0_1_repair1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 18.493,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-09-25T09:46:43.541115+00:00",
        "round_id": "dsa-ael-v0.1-repair1",
        "run_prefix": "2026-09-25_dsainet_ael_v0_1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T09:47:18.535794+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T09:47:21.388736+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T09:47:40.074735+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1293bfd97a697978fb201e3c55c9a376fc0dc7f439cc2762723c8e98eae9a5f4",
                "execution_seconds": 10.85989785194397,
                "queue_seconds": 6.591592788696289,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-25_dsainet_ael_v0_1_repair1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 17.45149064064026
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T13:26:00.789660+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "1293bfd97a697978fb201e3c55c9a376fc0dc7f439cc2762723c8e98eae9a5f4",
                "execution_seconds": 5044.404266119003,
                "queue_seconds": 1429.134648323059,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_ael_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-25_dsainet_ael_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 6473.538914442062
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-25T13:49:07.120582+00:00",
      "rerun_task_ids": [
        "B0_s0_t7",
        "C0_s0_t7",
        "N0_s0_t7",
        "S0_s0_t7"
      ],
      "reused_task_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t6",
        "B0_s1_t7",
        "B0_s1_t8",
        "C0_s0_t0",
        "C0_s0_t1",
        "C0_s0_t2",
        "C0_s0_t3",
        "C0_s0_t4",
        "C0_s0_t5",
        "C0_s0_t6",
        "C0_s0_t8",
        "C0_s1_t0",
        "C0_s1_t1",
        "C0_s1_t2",
        "C0_s1_t3",
        "C0_s1_t4",
        "C0_s1_t5",
        "C0_s1_t6",
        "C0_s1_t7",
        "C0_s1_t8",
        "N0_s0_t0",
        "N0_s0_t1",
        "N0_s0_t2",
        "N0_s0_t3",
        "N0_s0_t4",
        "N0_s0_t5",
        "N0_s0_t6",
        "N0_s0_t8",
        "N0_s1_t0",
        "N0_s1_t1",
        "N0_s1_t2",
        "N0_s1_t3",
        "N0_s1_t4",
        "N0_s1_t5",
        "N0_s1_t6",
        "N0_s1_t7",
        "N0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t1",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t2",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7",
        "S0_s1_t8"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ael-v0.1-repair2/SOURCE_REUSE_MANIFEST.json",
        "sha256": "5672a8f9290a86f1576680b994222fd1a3a61b6b673541afc2bb51ed06e64b78"
      }
    },
    {
      "attempt_class": "explicit_ael_missing_only_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair1/AUTHORIZATION.md",
      "campaign_id": "dsainet-bsu-v0.1-20260925",
      "failed_run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-25_dsainet_bsu_v0_1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 23.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-09-25T15:43:00.608658+00:00",
        "round_id": "dsa-bsu-v0.1",
        "run_prefix": "2026-09-25_dsainet_bsu_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T15:43:30.914525+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T15:43:33.177841+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T15:43:55.997035+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "8f7a9eb643631b2a1405fe59569172434e7e7e42a1e635e4b17be5ccbd73a84e",
                "execution_seconds": 8.53479290008545,
                "queue_seconds": 12.06078553199768,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1",
                "transaction_id": "2026-09-25_dsainet_bsu_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 20.59557843208313
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T03:18:35.653588+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "8f7a9eb643631b2a1405fe59569172434e7e7e42a1e635e4b17be5ccbd73a84e",
                "execution_seconds": 11493.862538576126,
                "queue_seconds": 621.4084074497223,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dsainet_bsu_v0_1-full-w1",
                "transaction_id": "2026-09-25_dsainet_bsu_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12115.270946025848
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-26T12:17:20.092097+00:00",
      "rerun_task_ids": [
        "CA_s0_t3",
        "CA_s0_t4",
        "CA_s0_t5",
        "CA_s0_t6",
        "CA_s0_t7",
        "CA_s0_t8",
        "CA_s1_t0",
        "CA_s1_t1",
        "CA_s1_t2",
        "CA_s1_t3",
        "CA_s1_t4",
        "CA_s1_t5",
        "CA_s1_t6",
        "CA_s1_t7",
        "CA_s1_t8",
        "FE_s1_t8"
      ],
      "reused_task_ids": [
        "CA_s0_t0",
        "CA_s0_t1",
        "CA_s0_t2",
        "CE_s0_t0",
        "CE_s0_t1",
        "CE_s0_t2",
        "CE_s0_t3",
        "CE_s0_t4",
        "CE_s0_t5",
        "CE_s0_t6",
        "CE_s0_t7",
        "CE_s0_t8",
        "CE_s1_t0",
        "CE_s1_t1",
        "CE_s1_t2",
        "CE_s1_t3",
        "CE_s1_t4",
        "CE_s1_t5",
        "CE_s1_t6",
        "CE_s1_t7",
        "CE_s1_t8",
        "FA_s0_t0",
        "FA_s0_t1",
        "FA_s0_t2",
        "FA_s0_t3",
        "FA_s0_t4",
        "FA_s0_t5",
        "FA_s0_t6",
        "FA_s0_t7",
        "FA_s0_t8",
        "FA_s1_t0",
        "FA_s1_t1",
        "FA_s1_t2",
        "FA_s1_t3",
        "FA_s1_t4",
        "FA_s1_t5",
        "FA_s1_t6",
        "FA_s1_t7",
        "FA_s1_t8",
        "FE_s0_t0",
        "FE_s0_t1",
        "FE_s0_t2",
        "FE_s0_t3",
        "FE_s0_t4",
        "FE_s0_t5",
        "FE_s0_t6",
        "FE_s0_t7",
        "FE_s0_t8",
        "FE_s1_t0",
        "FE_s1_t1",
        "FE_s1_t2",
        "FE_s1_t3",
        "FE_s1_t4",
        "FE_s1_t5",
        "FE_s1_t6",
        "FE_s1_t7"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair1/SOURCE_REUSE_MANIFEST.json",
        "sha256": "1beb9d484abe8d622371a6a1f8d64c7fed2269b9ca32967fc57cf78409b140fc"
      }
    },
    {
      "attempt_class": "explicit_ael_missing_only_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair2/AUTHORIZATION.md",
      "campaign_id": "dsainet-bsu-v0.1-20260925",
      "failed_run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-26_dsainet_bsu_v0_1_repair1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.07,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-09-26T12:17:39.162841+00:00",
        "round_id": "dsa-bsu-v0.1-repair1",
        "run_prefix": "2026-09-26_dsainet_bsu_v0_1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-26T12:18:27.568318+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-26T12:18:30.381486+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T12:18:44.697908+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0dc99a7d34126da5b37a8af026edbfe582e5be6952382fe06bcc66c21eddd7ca",
                "execution_seconds": 12.581054925918579,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-26_dsainet_bsu_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12.581054925918579
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T14:39:10.799714+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "0dc99a7d34126da5b37a8af026edbfe582e5be6952382fe06bcc66c21eddd7ca",
                "execution_seconds": 1299.3805923461914,
                "queue_seconds": 228.59621000289917,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dsainet_bsu_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-26_dsainet_bsu_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1527.9768023490906
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-26T14:44:47.061970+00:00",
      "rerun_task_ids": [
        "CA_s1_t7"
      ],
      "reused_task_ids": [
        "CA_s0_t0",
        "CA_s0_t1",
        "CA_s0_t2",
        "CA_s0_t3",
        "CA_s0_t4",
        "CA_s0_t5",
        "CA_s0_t6",
        "CA_s0_t7",
        "CA_s0_t8",
        "CA_s1_t0",
        "CA_s1_t1",
        "CA_s1_t2",
        "CA_s1_t3",
        "CA_s1_t4",
        "CA_s1_t5",
        "CA_s1_t6",
        "CA_s1_t8",
        "CE_s0_t0",
        "CE_s0_t1",
        "CE_s0_t2",
        "CE_s0_t3",
        "CE_s0_t4",
        "CE_s0_t5",
        "CE_s0_t6",
        "CE_s0_t7",
        "CE_s0_t8",
        "CE_s1_t0",
        "CE_s1_t1",
        "CE_s1_t2",
        "CE_s1_t3",
        "CE_s1_t4",
        "CE_s1_t5",
        "CE_s1_t6",
        "CE_s1_t7",
        "CE_s1_t8",
        "FA_s0_t0",
        "FA_s0_t1",
        "FA_s0_t2",
        "FA_s0_t3",
        "FA_s0_t4",
        "FA_s0_t5",
        "FA_s0_t6",
        "FA_s0_t7",
        "FA_s0_t8",
        "FA_s1_t0",
        "FA_s1_t1",
        "FA_s1_t2",
        "FA_s1_t3",
        "FA_s1_t4",
        "FA_s1_t5",
        "FA_s1_t6",
        "FA_s1_t7",
        "FA_s1_t8",
        "FE_s0_t0",
        "FE_s0_t1",
        "FE_s0_t2",
        "FE_s0_t3",
        "FE_s0_t4",
        "FE_s0_t5",
        "FE_s0_t6",
        "FE_s0_t7",
        "FE_s0_t8",
        "FE_s1_t0",
        "FE_s1_t1",
        "FE_s1_t2",
        "FE_s1_t3",
        "FE_s1_t4",
        "FE_s1_t5",
        "FE_s1_t6",
        "FE_s1_t7",
        "FE_s1_t8"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair2/SOURCE_REUSE_MANIFEST.json",
        "sha256": "6b33cf4778b0becb136cebfccd04d7b892f0e07ac43443f33d649aa2f76a07ab"
      }
    },
    {
      "attempt_class": "explicit_bsu_audit_only_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair3/AUTHORIZATION.md",
      "campaign_id": "dsainet-bsu-v0.1-20260925",
      "failed_run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-26_dsainet_bsu_v0_1_repair2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 6.676,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-09-26T14:44:50.027524+00:00",
        "round_id": "dsa-bsu-v0.1-repair2",
        "run_prefix": "2026-09-26_dsainet_bsu_v0_1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-26T14:45:49.358622+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-26T14:45:51.637443+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T14:46:12.563470+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "708d5ddaafc290bc8bc51511ada0e09e2767f7f1a39f2a9cff5847b447a03399",
                "execution_seconds": 19.200015544891357,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-26_dsainet_bsu_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19.200015544891357
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T15:25:43.358295+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "708d5ddaafc290bc8bc51511ada0e09e2767f7f1a39f2a9cff5847b447a03399",
                "execution_seconds": 1250.4396498203278,
                "queue_seconds": 1139.7656750679016,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-26_dsainet_bsu_v0_1_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2390.2053248882294
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T16:54:57.439942+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "708d5ddaafc290bc8bc51511ada0e09e2767f7f1a39f2a9cff5847b447a03399",
                "execution_seconds": 2374.6302008628845,
                "queue_seconds": 5369.927595376968,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-26_dsainet_bsu_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 7744.557796239853
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T02:27:30.733060+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "708d5ddaafc290bc8bc51511ada0e09e2767f7f1a39f2a9cff5847b447a03399",
                "execution_seconds": 3314.370765209198,
                "queue_seconds": 6837.871200799942,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dsainet_bsu_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-26_dsainet_bsu_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10152.24196600914
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-27T02:40:05.914548+00:00",
      "rerun_task_ids": [
        "CA_s0_t5",
        "CE_s0_t2",
        "FA_s0_t5",
        "FA_s1_t0",
        "FA_s1_t1",
        "FA_s1_t2",
        "FA_s1_t3",
        "FA_s1_t4",
        "FA_s1_t5",
        "FA_s1_t6",
        "FA_s1_t7",
        "FA_s1_t8",
        "FE_s0_t5",
        "FE_s0_t8",
        "FE_s1_t0"
      ],
      "reused_audit_task_ids": [
        "CA_s0_t0",
        "CA_s0_t1",
        "CA_s0_t2",
        "CA_s0_t3",
        "CA_s0_t4",
        "CA_s0_t6",
        "CA_s0_t7",
        "CA_s0_t8",
        "CA_s1_t0",
        "CA_s1_t1",
        "CA_s1_t2",
        "CA_s1_t3",
        "CA_s1_t4",
        "CA_s1_t5",
        "CA_s1_t6",
        "CA_s1_t7",
        "CA_s1_t8",
        "CE_s0_t0",
        "CE_s0_t1",
        "CE_s0_t3",
        "CE_s0_t4",
        "CE_s0_t5",
        "CE_s0_t6",
        "CE_s0_t7",
        "CE_s0_t8",
        "CE_s1_t0",
        "CE_s1_t1",
        "CE_s1_t2",
        "CE_s1_t3",
        "CE_s1_t4",
        "CE_s1_t5",
        "CE_s1_t6",
        "CE_s1_t7",
        "CE_s1_t8",
        "FA_s0_t0",
        "FA_s0_t1",
        "FA_s0_t2",
        "FA_s0_t3",
        "FA_s0_t4",
        "FA_s0_t6",
        "FA_s0_t7",
        "FA_s0_t8",
        "FE_s0_t0",
        "FE_s0_t1",
        "FE_s0_t2",
        "FE_s0_t3",
        "FE_s0_t4",
        "FE_s0_t6",
        "FE_s0_t7",
        "FE_s1_t1",
        "FE_s1_t2",
        "FE_s1_t3",
        "FE_s1_t4",
        "FE_s1_t5",
        "FE_s1_t6",
        "FE_s1_t7",
        "FE_s1_t8"
      ],
      "reused_task_ids": [
        "CA_s0_t0",
        "CA_s0_t1",
        "CA_s0_t2",
        "CA_s0_t3",
        "CA_s0_t4",
        "CA_s0_t5",
        "CA_s0_t6",
        "CA_s0_t7",
        "CA_s0_t8",
        "CA_s1_t0",
        "CA_s1_t1",
        "CA_s1_t2",
        "CA_s1_t3",
        "CA_s1_t4",
        "CA_s1_t5",
        "CA_s1_t6",
        "CA_s1_t7",
        "CA_s1_t8",
        "CE_s0_t0",
        "CE_s0_t1",
        "CE_s0_t2",
        "CE_s0_t3",
        "CE_s0_t4",
        "CE_s0_t5",
        "CE_s0_t6",
        "CE_s0_t7",
        "CE_s0_t8",
        "CE_s1_t0",
        "CE_s1_t1",
        "CE_s1_t2",
        "CE_s1_t3",
        "CE_s1_t4",
        "CE_s1_t5",
        "CE_s1_t6",
        "CE_s1_t7",
        "CE_s1_t8",
        "FA_s0_t0",
        "FA_s0_t1",
        "FA_s0_t2",
        "FA_s0_t3",
        "FA_s0_t4",
        "FA_s0_t5",
        "FA_s0_t6",
        "FA_s0_t7",
        "FA_s0_t8",
        "FA_s1_t0",
        "FA_s1_t1",
        "FA_s1_t2",
        "FA_s1_t3",
        "FA_s1_t4",
        "FA_s1_t5",
        "FA_s1_t6",
        "FA_s1_t7",
        "FA_s1_t8",
        "FE_s0_t0",
        "FE_s0_t1",
        "FE_s0_t2",
        "FE_s0_t3",
        "FE_s0_t4",
        "FE_s0_t5",
        "FE_s0_t6",
        "FE_s0_t7",
        "FE_s0_t8",
        "FE_s1_t0",
        "FE_s1_t1",
        "FE_s1_t2",
        "FE_s1_t3",
        "FE_s1_t4",
        "FE_s1_t5",
        "FE_s1_t6",
        "FE_s1_t7",
        "FE_s1_t8"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-bsu-v0.1-repair3/SOURCE_REUSE_MANIFEST.json",
        "sha256": "708f6d4babdd71a42518277f5baf96364f5ba97b13283944af1f3e6cf3b6135b"
      }
    },
    {
      "attempt_class": "explicit_ces_technical_aggregation_repair",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair1/AUTHORIZATION.md",
      "campaign_id": "dsainet-ces-v0.1-20260927",
      "failed_run_id": "2026-09-27_dsainet_ces_v0_1-full-w1",
      "new_formal_tasks": 36,
      "previous_active_run": {
        "bundle_id": "2026-09-27_dsainet_ces_v0_1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 11.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-27T09:06:28.334808+00:00",
        "round_id": "dsa-ces-v0.1",
        "run_prefix": "2026-09-27_dsainet_ces_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T09:09:57.244430+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dsainet_ces_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T09:10:11.032099+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dsainet_ces_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T09:10:29.352520+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-27_dsainet_ces_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b62e197225754fe5c9497baed56227f256c23dc88acc56227e36bdd13c68abb4",
                "execution_seconds": 2.67767333984375,
                "queue_seconds": 14.910809993743896,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dsainet_ces_v0_1-full-w1",
                "transaction_id": "2026-09-27_dsainet_ces_v0_1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 17.588483333587646
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T15:20:59.038941+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_dsainet_ces_v0_1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "b62e197225754fe5c9497baed56227f256c23dc88acc56227e36bdd13c68abb4",
                "execution_seconds": 52.49685525894165,
                "queue_seconds": 34.777644634246826,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dsainet_ces_v0_1-full-w1",
                "transaction_id": "2026-09-27_dsainet_ces_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 87.27449989318848
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-27T15:30:26.208463+00:00",
      "reused_task_ids": [
        "smoke_CM",
        "smoke_FM"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair1/SOURCE_REUSE_MANIFEST.json",
        "sha256": "1ce4ad1bd69e3d70d17e0411f245508c8a4959de24b9da04a94aa8b1ec40aabd"
      }
    },
    {
      "attempt_class": "explicit_ces_two_missing_fit_recovery",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair2/AUTHORIZATION.md",
      "campaign_id": "dsainet-ces-v0.1-20260927",
      "failed_run_id": "2026-09-27_dsainet_ces_v0_1_repair1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-27_dsainet_ces_v0_1_repair1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.984,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-27T15:30:36.877022+00:00",
        "round_id": "dsa-ces-v0.1-repair1",
        "run_prefix": "2026-09-27_dsainet_ces_v0_1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T15:31:12.521443+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dsainet_ces_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T15:31:14.141033+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dsainet_ces_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T15:31:45.177504+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-27_dsainet_ces_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4460bdeb325992ebcc9f060336fa3015a1f7b91dc6416245f43ec90df16a87d9",
                "execution_seconds": 29.806356191635132,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dsainet_ces_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-27_dsainet_ces_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 29.806356191635132
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-28T06:17:36.614163+00:00",
      "rerun_task_ids": [
        "CM_s0_t7",
        "CM_s1_t0"
      ],
      "reused_task_ids": [
        "CM_s0_t0",
        "CM_s0_t1",
        "CM_s0_t2",
        "CM_s0_t3",
        "CM_s0_t4",
        "CM_s0_t5",
        "CM_s0_t6",
        "CM_s0_t8",
        "CM_s1_t1",
        "CM_s1_t2",
        "CM_s1_t3",
        "CM_s1_t4",
        "CM_s1_t5",
        "CM_s1_t6",
        "CM_s1_t7",
        "CM_s1_t8",
        "FM_s0_t0",
        "FM_s0_t1",
        "FM_s0_t2",
        "FM_s0_t3",
        "FM_s0_t4",
        "FM_s0_t5",
        "FM_s0_t6",
        "FM_s0_t7",
        "FM_s0_t8",
        "FM_s1_t0",
        "FM_s1_t1",
        "FM_s1_t2",
        "FM_s1_t3",
        "FM_s1_t4",
        "FM_s1_t5",
        "FM_s1_t6",
        "FM_s1_t7",
        "FM_s1_t8"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair2/SOURCE_REUSE_MANIFEST.json",
        "sha256": "73725377214e1d5446b749f5d2875b600782fcdb9478b987b650f7be0163d6db"
      }
    },
    {
      "attempt_class": "explicit_ces_two_missing_fit_recovery",
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair3/AUTHORIZATION.md",
      "campaign_id": "dsainet-ces-v0.1-20260927",
      "failed_run_id": "2026-09-28_dsainet_ces_v0_1_repair2-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-28_dsainet_ces_v0_1_repair2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 5.393,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-28T06:20:02.731239+00:00",
        "round_id": "dsa-ces-v0.1-repair2",
        "run_prefix": "2026-09-28_dsainet_ces_v0_1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-28T06:25:32.620610+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-28T06:25:49.079819+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T06:26:20.832130+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-28_dsainet_ces_v0_1_repair2-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "f637488b99f0f47464a4fd11212f28f5ae4b2a60321df6b9f9b6447a050842cf",
                "execution_seconds": 8.672837018966675,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-28_dsainet_ces_v0_1_repair2-full-w1",
                "transaction_id": "2026-09-28_dsainet_ces_v0_1_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8.672837018966675
              }
            }
          }
        ]
      },
      "recorded_at": "2026-09-28T07:16:43.701511+00:00",
      "rerun_task_ids": [
        "CM_s0_t7",
        "CM_s1_t0"
      ],
      "reused_task_ids": [
        "CM_s0_t0",
        "CM_s0_t1",
        "CM_s0_t2",
        "CM_s0_t3",
        "CM_s0_t4",
        "CM_s0_t5",
        "CM_s0_t6",
        "CM_s0_t8",
        "CM_s1_t1",
        "CM_s1_t2",
        "CM_s1_t3",
        "CM_s1_t4",
        "CM_s1_t5",
        "CM_s1_t6",
        "CM_s1_t7",
        "CM_s1_t8",
        "FM_s0_t0",
        "FM_s0_t1",
        "FM_s0_t2",
        "FM_s0_t3",
        "FM_s0_t4",
        "FM_s0_t5",
        "FM_s0_t6",
        "FM_s0_t7",
        "FM_s0_t8",
        "FM_s1_t0",
        "FM_s1_t1",
        "FM_s1_t2",
        "FM_s1_t3",
        "FM_s1_t4",
        "FM_s1_t5",
        "FM_s1_t6",
        "FM_s1_t7",
        "FM_s1_t8"
      ],
      "scientific_decision": false,
      "source_ledger_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ces-v0.1-repair2/LAUNCH_STATUS.json",
        "sha256": "f166160f6520523d9e2f733497a9b231a40a95d5471b5cc8ad7788f7d677ef1b"
      }
    },
    {
      "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair1/AUTHORIZATION.md",
      "failed_run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
      "new_fits": 1054,
      "previous_active_run": {
        "bundle_id": "2026-09-29_dsainet_pfc_xds_v0_1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 70.766,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 1184,
        "recorded_at": "2026-09-28T17:19:48.013513+00:00",
        "round_id": "dsa-pfc-xds-v0.1",
        "run_prefix": "2026-09-29_dsainet_pfc_xds_v0_1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-28T17:21:19.428626+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-28T17:22:33.193522+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T17:23:07.163068+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f22b2dfbb67aa7a2197166a3b403e508c7fa9726923ce20a599200e66d7a7575",
                "execution_seconds": 18.0113627910614,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 18.0113627910614
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T17:25:07.283051+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f22b2dfbb67aa7a2197166a3b403e508c7fa9726923ce20a599200e66d7a7575",
                "execution_seconds": 79.27274370193481,
                "queue_seconds": 58.8441367149353,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 138.11688041687012
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T02:24:25.836322+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "f22b2dfbb67aa7a2197166a3b403e508c7fa9726923ce20a599200e66d7a7575",
                "execution_seconds": 19129.54788541794,
                "queue_seconds": 549.629141330719,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19679.177026748657
              }
            }
          }
        ]
      },
      "reason": "user-authorized XDS startup and transport recovery",
      "recorded_at": "2026-09-29T02:40:09.542203+00:00",
      "replacement_round_id": "dsa-pfc-xds-v0.1-repair1",
      "reused_tasks": 126,
      "scientific_decision": false,
      "source_identity": {
        "contract_sha256": "f22b2dfbb67aa7a2197166a3b403e508c7fa9726923ce20a599200e66d7a7575",
        "run_id": "2026-09-29_dsainet_pfc_xds_v0_1-full-w1",
        "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1-tx"
      },
      "source_ledger": {
        "path": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair1/SOURCE_REUSE_MANIFEST.json",
        "sha256": "074e760a7b33c9eecc9fe971e949a8fb0b36527a2fe208b79842818157e5b1cb"
      }
    },
    {
      "failed_run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 61.569,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 1184,
        "recorded_at": "2026-09-29T02:40:30.387531+00:00",
        "round_id": "dsa-pfc-xds-v0.1-repair1",
        "run_prefix": "2026-09-29_dsainet_pfc_xds_v0_1_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T02:42:18.607489+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T02:43:38.577880+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T02:44:08.667112+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f506484eebfad01b60eb98985c8f4bedea23fc3679e3984b509e92da3fe02a51",
                "execution_seconds": 13.28366732597351,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.28366732597351
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T05:38:09.867094+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f506484eebfad01b60eb98985c8f4bedea23fc3679e3984b509e92da3fe02a51",
                "execution_seconds": 10454.161110639572,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10454.161110639572
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T08:32:54.273663+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "observation_ref": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-repair2/LATEST_REMOTE_STATUS.json",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "f506484eebfad01b60eb98985c8f4bedea23fc3679e3984b509e92da3fe02a51",
                "execution_seconds": 20718.343574285507,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 20718.343574285507
              },
              "transport_host": "[REDACTED_MACHINE]"
            }
          }
        ]
      },
      "reason": "Settlement repair and GPU2 containment; user-authorized dataset-separated recovery",
      "recorded_at": "2026-09-29T08:41:48.685354+00:00",
      "scientific_decision": false,
      "source_identity": {
        "contract_sha256": "f506484eebfad01b60eb98985c8f4bedea23fc3679e3984b509e92da3fe02a51",
        "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
        "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-tx"
      }
    },
    {
      "failed_run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 56.054,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 92,
        "recorded_at": "2026-09-29T08:42:37.243473+00:00",
        "round_id": "dsa-pfc-xds-v0.1-repair2-004",
        "run_prefix": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T08:43:55.125033+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T08:45:35.248283+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T08:51:53.930084+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d2265c46eccb3826e8c06657aa5fc5e5760a61da5070bac26f2238441f6842dd",
                "execution_seconds": 18.164737224578857,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair2_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 18.164737224578857
              }
            }
          }
        ]
      },
      "reason": "004 stopped before target: incomplete CUDA RNG in repair1 fits; preserve gate and retrain exact invalid units",
      "recorded_at": "2026-09-29T08:53:13.379093+00:00",
      "scientific_decision": false,
      "source_identity": {
        "contract_sha256": "f506484eebfad01b60eb98985c8f4bedea23fc3679e3984b509e92da3fe02a51",
        "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-full-w1",
        "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair1-tx"
      }
    },
    {
      "failed_run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 55.855,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 92,
        "recorded_at": "2026-09-29T08:53:23.823154+00:00",
        "round_id": "dsa-pfc-xds-v0.1-repair3-004",
        "run_prefix": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T08:54:00.468631+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T08:57:02.584987+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T08:57:28.520272+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 19.79321265220642,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19.79321265220642
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:20:49.254104+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1122.8735942840576,
                "queue_seconds": 297.70758867263794,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1420.5811829566956
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:21:46.769331+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1122.8733389377594,
                "queue_seconds": 355.2381932735443,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1478.1115322113037
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:22:38.558493+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1123.8445744514465,
                "queue_seconds": 406.0590169429779,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1529.9035913944244
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:25:23.850890+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1189.637226819992,
                "queue_seconds": 505.5571391582489,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1695.194365978241
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:26:25.180805+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1189.63432097435,
                "queue_seconds": 566.8812882900238,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1756.5156092643738
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:27:20.002082+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1190.0646805763245,
                "queue_seconds": 621.2819628715515,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1811.346643447876
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:28:12.852900+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1190.0666086673737,
                "queue_seconds": 674.1444864273071,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1864.2110950946808
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:29:05.708185+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1230.9652771949768,
                "queue_seconds": 686.1024312973022,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1917.067708492279
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:29:58.651578+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1251.0091021060944,
                "queue_seconds": 719.0036234855652,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 1970.0127255916595
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:30:51.387683+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1271.0255136489868,
                "queue_seconds": 751.7242362499237,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2022.7497498989105
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:31:44.651877+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1271.0251016616821,
                "queue_seconds": 804.9924559593201,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2076.017557621002
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:32:37.670945+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1271.023344039917,
                "queue_seconds": 858.0128331184387,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2129.0361771583557
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:33:31.318011+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1292.5274333953857,
                "queue_seconds": 890.1564702987671,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2182.683903694153
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:34:23.777670+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1306.3186490535736,
                "queue_seconds": 928.8340442180634,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 2235.152693271637
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:35:17.133058+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1329.9341394901276,
                "queue_seconds": 958.5824456214905,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2288.516585111618
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:36:11.690631+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1329.9333906173706,
                "queue_seconds": 1013.1393814086914,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2343.072772026062
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:37:04.499624+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1329.9321658611298,
                "queue_seconds": 1065.945232629776,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2395.8773984909058
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:37:56.691397+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1329.934163570404,
                "queue_seconds": 1118.1432795524597,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2448.0774431228638
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:38:48.758717+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1330.0692727565765,
                "queue_seconds": 1170.0776054859161,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2500.1468782424927
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:39:40.148848+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1330.0714137554169,
                "queue_seconds": 1221.472338438034,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2551.543752193451
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:40:33.114517+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1330.0658786296844,
                "queue_seconds": 1274.42902469635,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2604.4949033260345
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:41:26.109231+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1330.0676743984222,
                "queue_seconds": 1327.4276123046875,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2657.4952867031097
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:42:21.556584+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1330.888065814972,
                "queue_seconds": 1382.0638461112976,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2712.9519119262695
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:43:14.923846+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1330.95818734169,
                "queue_seconds": 1435.3662025928497,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2766.32438993454
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:44:08.306483+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1333.6416728496552,
                "queue_seconds": 1486.0720596313477,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2819.713732481003
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:45:01.852745+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1334.319331407547,
                "queue_seconds": 1538.9389989376068,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2873.258330345154
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:45:53.989640+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1336.7680914402008,
                "queue_seconds": 1588.6305425167084,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2925.398633956909
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:46:46.427130+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1336.8624830245972,
                "queue_seconds": 1640.9810254573822,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 2977.8435084819794
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:47:39.450000+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1337.5703353881836,
                "queue_seconds": 1693.2926888465881,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 3030.8630242347717
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:48:32.440553+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1337.569192647934,
                "queue_seconds": 1746.2864112854004,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 3083.8556039333344
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:49:25.138742+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1376.192167043686,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3136.558357000351
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:50:17.800449+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1428.8461689949036,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3189.2123589515686
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:51:10.529898+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1481.5901556015015,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3241.9563455581665
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:52:03.037912+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1534.1003603935242,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3294.466550350189
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:52:55.236636+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1586.3015613555908,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3346.667751312256
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:53:48.219014+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1639.27778506279,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3399.643975019455
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:54:40.121112+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1691.1878471374512,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3451.554037094116
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:55:32.444263+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1743.5152795314789,
                "queue_seconds": 1760.366189956665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3503.881469488144
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:56:24.403100+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1776.4573321342468,
                "queue_seconds": 1779.3855743408203,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 3555.842906475067
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:57:17.367953+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1808.3536028862,
                "queue_seconds": 1800.4534945487976,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3608.8070974349976
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:58:11.805002+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1838.647133588791,
                "queue_seconds": 1824.599074602127,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": true,
                "wall_seconds": 3663.246208190918
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:59:04.763739+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1875.6570613384247,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3716.207801103592
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:59:57.467471+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1928.3691651821136,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3768.919904947281
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:00:49.725210+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 1980.6228404045105,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3821.1735801696777
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:01:42.060310+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2032.9630951881409,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3873.513834953308
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:02:35.697571+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2086.603851556778,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3927.154591321945
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:03:29.916579+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2140.8236191272736,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3981.374358892441
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:04:23.477301+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2194.386885166168,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4034.9376249313354
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:05:16.410567+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:06:07.380301+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:07:00.599644+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:07:52.071141+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:08:43.755000+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:09:36.133527+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:10:28.756504+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:11:21.646078+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:12:14.235925+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:13:04.685448+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:13:54.739431+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:14:44.731065+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:15:34.850591+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:16:24.908845+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:17:15.418071+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:18:05.496917+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:18:55.608269+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:19:45.701960+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:20:35.931324+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:21:25.688848+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:22:15.585294+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:23:05.238780+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:23:55.038405+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:24:44.694744+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:25:34.472012+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:26:24.181900+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:27:13.938895+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:28:03.758335+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:28:53.519923+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:29:43.176925+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:30:32.964451+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:31:22.777037+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:32:12.606424+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:33:02.317742+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:33:52.051646+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:34:41.570209+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:35:31.257586+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:36:20.930239+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:37:10.838236+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:38:00.633835+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:38:50.411621+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:39:40.141131+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:40:30.337639+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:41:20.218350+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:42:10.033982+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:42:59.801232+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:43:49.605568+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:44:39.371736+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:45:29.191443+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:46:18.835285+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:47:08.655078+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:47:58.418257+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:48:48.239026+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:49:38.127918+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:50:28.019943+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:51:17.836302+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:52:07.585101+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:52:57.387065+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:53:47.206256+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:54:37.118685+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:55:26.969181+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:56:16.860032+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:57:06.671826+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:57:56.642158+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:58:46.419249+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T10:59:36.227058+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:00:26.055020+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:01:16.032493+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:02:05.905137+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:02:55.802264+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:03:45.683186+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:04:35.577235+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:05:25.411477+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:06:15.394570+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:07:05.282261+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:07:55.187779+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:08:44.957206+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:09:34.908391+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:10:24.818296+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:11:14.638232+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:12:04.545320+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:12:54.554264+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:13:44.362991+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:14:34.427526+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:15:24.595659+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:16:14.485485+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:17:04.507747+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:17:54.965881+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:18:44.888622+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:19:34.856668+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:20:24.954048+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:21:14.891703+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:22:04.800709+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:22:54.860214+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:23:44.735900+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:24:34.611527+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:25:24.655083+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:26:14.727570+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:27:04.647738+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:27:54.703765+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:28:44.835986+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:29:42.308734+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:30:33.382709+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:31:23.543634+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:32:13.743948+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:33:04.229478+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:33:54.422592+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:34:44.680519+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:35:34.861778+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:36:25.422731+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:37:15.369522+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:38:05.374790+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:38:55.704979+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:39:46.078871+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:40:36.753605+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:41:27.231921+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:42:18.388815+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:43:08.597332+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:43:58.898472+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
                "execution_seconds": 2232.2230002880096,
                "queue_seconds": 1840.5507397651672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
                "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4072.773740053177
              }
            }
          }
        ]
      },
      "reason": "004target:76complete,2OOM,12blocked; all90training preserved; no scientific decision",
      "recorded_at": "2026-09-29T11:52:35.025081+00:00",
      "scientific_decision": false,
      "source_identity": {
        "contract_sha256": "d31ee7ce5dfcd8e8919641bf21287290bd05ddd2ca8ffb316242d4616256bab2",
        "run_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-full-w1",
        "transaction_id": "2026-09-29_dsainet_pfc_xds_v0_1_repair3_004-tx"
      }
    },
    {
      "failed_run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
      "previous_active_run": {
        "bundle_id": "2026-09-29_dsainet_sid_v0_1_r1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 23.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 254,
        "recorded_at": "2026-09-29T13:15:56.621863+00:00",
        "round_id": "dsa-sid-v0.1-r1",
        "run_prefix": "2026-09-29_dsainet_sid_v0_1_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T13:16:14.972562+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T13:16:46.604302+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T13:17:02.892990+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b96941332ced11b61aae3b42c6ffe0a90baf5f2d1f5b9f845c649a270eeaadca",
                "execution_seconds": 13.3518545627594,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
                "transaction_id": "2026-09-29_dsainet_sid_v0_1_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.3518545627594
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T13:18:39.798973+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b96941332ced11b61aae3b42c6ffe0a90baf5f2d1f5b9f845c649a270eeaadca",
                "execution_seconds": 110.254478931427,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
                "transaction_id": "2026-09-29_dsainet_sid_v0_1_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 110.254478931427
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T15:14:43.871198+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b96941332ced11b61aae3b42c6ffe0a90baf5f2d1f5b9f845c649a270eeaadca",
                "execution_seconds": 7074.668950557709,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
                "transaction_id": "2026-09-29_dsainet_sid_v0_1_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 7074.668950557709
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T16:50:04.977789+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b96941332ced11b61aae3b42c6ffe0a90baf5f2d1f5b9f845c649a270eeaadca",
                "execution_seconds": 12796.034311771393,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
                "transaction_id": "2026-09-29_dsainet_sid_v0_1_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12796.034311771393
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-30T03:55:17.584210+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "full",
              "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "b96941332ced11b61aae3b42c6ffe0a90baf5f2d1f5b9f845c649a270eeaadca",
                "execution_seconds": 20970.850610733032,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dsainet_sid_v0_1_r1-full-w1",
                "transaction_id": "2026-09-29_dsainet_sid_v0_1_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 20970.850610733032
              }
            }
          }
        ]
      },
      "reason": "90 new fits complete;125/126 new targets complete; first-convolution cuDNN failure; user authorized one target retry",
      "recorded_at": "2026-09-30T04:16:56.738818+00:00",
      "scientific_decision": false,
      "source_ledger": "ai4s/programs/dsainet/research/dsa-sid-v0.1-repair1/SOURCE_LEDGER.json"
    },
    {
      "attempt_class": "user_confirmed_redeployment_waiting_resources",
      "engineering_reason": "User authorized incremental memory-capacity dispatch without distinct-four-GPU gate; preserve4 complete inputs,68 remaining fits,72 audits and24h cumulative ceiling",
      "failed_run": {
        "bundle_id": "2026-10-13_dsainet_rcd_v0_1_resume1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 19.283,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 76,
        "recorded_at": "2026-10-13T12:18:01.656857+00:00",
        "round_id": "dsa-rcd-v0.1-resume1",
        "run_prefix": "2026-10-13_dsainet_rcd_v0_1_resume1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-13T12:18:39.561738+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-13_dsainet_rcd_v0_1_resume1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-13T12:18:42.131747+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-13_dsainet_rcd_v0_1_resume1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-13T12:19:01.313387+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-10-13_dsainet_rcd_v0_1_resume1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5991469137ac958860e8363ddd79ad53a2d3d681da0c259aeaf4800e051c6b29",
                "execution_seconds": 9.184878587722778,
                "queue_seconds": 6.056146144866943,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-13_dsainet_rcd_v0_1_resume1-full-w1",
                "transaction_id": "2026-10-13_dsainet_rcd_v0_1_resume1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 15.241024732589722
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-13_dsainet_rcd_v0_1_resume1-full-w1",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-10-14T00:14:24.741680+00:00",
      "redeployment_report": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-resume2/REDEPLOYMENT_REPORT.json",
      "round_id": "dsa-rcd-v0.1-resume1"
    },
    {
      "attempt_class": "engineering_technical_evidence_aggregation_failed",
      "authorization_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair1/AUTHORIZATION.json",
        "sha256": "61ae711dbb185c28240b9cf0a2a9f264da0e7bbf50821fd1f7827fbf29c1dbbf"
      },
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "failed_run": {
        "bundle_id": "2026-10-15_dsainet_ord_v0_1_stageA-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 22.491,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-10-15T07:03:36.692924+00:00",
        "round_id": "dsa-ord-v0.1-stageA",
        "run_prefix": "2026-10-15_dsainet_ord_v0_1_stageA",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-15T07:04:01.411525+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-15T07:04:03.515079+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T07:04:21.877241+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "15b3e5be41d9af185e7c0a2ce8f6ba9ca54dce9448d91a9f63224c689d6f5d1c",
                "execution_seconds": 10.856500148773193,
                "queue_seconds": 5.114879369735718,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15.971379518508911
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T07:05:53.072910+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "15b3e5be41d9af185e7c0a2ce8f6ba9ca54dce9448d91a9f63224c689d6f5d1c",
                "execution_seconds": 65.73059010505676,
                "queue_seconds": 41.42785358428955,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA-tx",
                "waiting_for_resources": false,
                "wall_seconds": 107.15844368934631
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T08:38:22.948286+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "15b3e5be41d9af185e7c0a2ce8f6ba9ca54dce9448d91a9f63224c689d6f5d1c",
                "execution_seconds": 352.208957195282,
                "queue_seconds": 82.44010066986084,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA-tx",
                "waiting_for_resources": false,
                "wall_seconds": 434.6490578651428
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
      "recorded_at": "2026-10-15T09:08:23.930815+00:00",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ord-v0.1-stageA-repair1.yaml",
      "repaired_by_bundle_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-bundle",
      "repaired_by_run_prefix": "2026-10-15_dsainet_ord_v0_1_stageA_repair1",
      "round_id": "dsa-ord-v0.1-stageA",
      "scientific_fits_started": 0,
      "scientific_partial_artifacts_eligible": false,
      "source_contract_sha256": "15b3e5be41d9af185e7c0a2ce8f6ba9ca54dce9448d91a9f63224c689d6f5d1c",
      "source_inventory_sha256": "32513c4e91e8f6bcc4a1a8fbd9e5b0267001443b340422d31a1f500bd17ac5f5",
      "source_ledger_sha256": "84887d863ef341b28e0a203ac353b883decf619462a1f61657acb3653f3a4868",
      "technical_artifacts_replay_eligible": true,
      "technical_fit_retries": 0
    },
    {
      "attempt_class": "engineering_technical_replay_output_precondition_failed",
      "authorization_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair1/AUTHORIZATION.json",
        "sha256": "61ae711dbb185c28240b9cf0a2a9f264da0e7bbf50821fd1f7827fbf29c1dbbf"
      },
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "failed_run": {
        "bundle_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 19.92,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-10-15T09:08:23.268567+00:00",
        "repair_kind": "technical_evidence_consumer_replay",
        "replaces_failed_run": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
        "round_id": "dsa-ord-v0.1-stageA-repair1",
        "run_prefix": "2026-10-15_dsainet_ord_v0_1_stageA_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-15T09:09:16.664700+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-15T09:09:19.183515+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T09:09:44.835759+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "52184ec023043b377d4b86d24a4f2d712936084b89e0639a50833aa92789ad34",
                "execution_seconds": 0.9257984161376953,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 0.9257984161376953
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-full-w1",
      "failure_report_sha256": "1b1e24f9f6347bf964e57e4d25b6f64db3cb54ee99c8f23eef2e0d17390c9e1a",
      "original_technical_source_run": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
      "recorded_at": "2026-10-15T09:22:35.680075+00:00",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ord-v0.1-stageA-repair2.yaml",
      "repaired_by_bundle_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-bundle",
      "repaired_by_run_prefix": "2026-10-15_dsainet_ord_v0_1_stageA_repair2",
      "round_id": "dsa-ord-v0.1-stageA-repair1",
      "scientific_fits_started": 0,
      "scientific_partial_artifacts_eligible": false,
      "source_contract_sha256": "52184ec023043b377d4b86d24a4f2d712936084b89e0639a50833aa92789ad34",
      "technical_artifacts_replay_eligible": false,
      "technical_fit_retries": 0
    },
    {
      "attempt_class": "pretraining_resource_admission_failed",
      "authorization_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair3/AUTHORIZATION.json",
        "sha256": "b750bee0dab18a7c31b96861601fb8315e7e99df8bbed3bf8d6dd10c5f733058"
      },
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "eligible_fit_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t7",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t6",
        "B0_s1_t7",
        "B0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t7",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7"
      ],
      "failed_run": {
        "bundle_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 19.701,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 57,
        "recorded_at": "2026-10-15T09:22:35.128664+00:00",
        "repair_kind": "technical_evidence_consumer_replay",
        "replaces_failed_run": "2026-10-15_dsainet_ord_v0_1_stageA_repair1-full-w1",
        "round_id": "dsa-ord-v0.1-stageA-repair2",
        "run_prefix": "2026-10-15_dsainet_ord_v0_1_stageA_repair2",
        "technical_source_run": "2026-10-15_dsainet_ord_v0_1_stageA-full-w1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-15T09:23:00.072775+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-15T09:23:02.567881+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T09:23:36.241500+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a4499422c3a0809b17d780e316632cdb8942b741daf51c45e5bce92825e947f7",
                "execution_seconds": 30.41254734992981,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 30.41254734992981
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T09:25:33.728865+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a4499422c3a0809b17d780e316632cdb8942b741daf51c45e5bce92825e947f7",
                "execution_seconds": 147.91074633598328,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 147.91074633598328
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T13:28:02.134970+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "screen",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a4499422c3a0809b17d780e316632cdb8942b741daf51c45e5bce92825e947f7",
                "execution_seconds": 13981.431732416153,
                "queue_seconds": 712.4521403312683,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 14693.883872747421
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-15T15:26:04.589878+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a4499422c3a0809b17d780e316632cdb8942b741daf51c45e5bce92825e947f7",
                "execution_seconds": 18503.435101270676,
                "queue_seconds": 3272.3565516471863,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 21775.791652917862
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-16T01:09:14.850964+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "a4499422c3a0809b17d780e316632cdb8942b741daf51c45e5bce92825e947f7",
                "execution_seconds": 32998.367760419846,
                "queue_seconds": 5626.83117890358,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
                "transaction_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 38625.198939323425
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
      "ineligible_failed_fit_ids": [
        "P0_s0_t1",
        "P0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t8"
      ],
      "recorded_at": "2026-10-16T01:41:04.738740+00:00",
      "repaired_by_run_prefix": "2026-10-16_dsainet_ord_v0_1_stageA_repair3",
      "round_id": "dsa-ord-v0.1-stageA-repair2",
      "scientific_partial_artifacts_eligible": true,
      "source_contract_sha256": "a4499422c3a0809b17d780e316632cdb8942b741daf51c45e5bce92825e947f7",
      "source_inventory_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair3/SOURCE_INVENTORY.json",
        "sha256": "7cd86b941d25a3dc17fc1acc3e9714dc2fb1946d4d940c70f76da63cc206bc2f"
      },
      "technical_artifacts_replay_eligible": true
    },
    {
      "attempt_class": "subset_family_cap_preworker_failure",
      "authorization_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair3/AUTHORIZATION4.json",
        "sha256": "d133b86428e359e9f2414fc4f6c94fe661ae8d642a845048eaf404c70d18f8e5"
      },
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "eligible_fit_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t7",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t6",
        "B0_s1_t7",
        "B0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t7",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7"
      ],
      "failed_run": {
        "bundle_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 15.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "formal_fits_to_run": 4,
        "planned_units": 57,
        "recorded_at": "2026-10-16T01:41:04.738740+00:00",
        "repair_kind": "completed_fit_recovery",
        "replaces_failed_run": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
        "reused_formal_fits": 50,
        "round_id": "dsa-ord-v0.1-stageA-repair3",
        "run_prefix": "2026-10-16_dsainet_ord_v0_1_stageA_repair3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-16T01:41:50.286478+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-16T01:41:57.006375+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-16T01:42:22.147663+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "684777dccc61f2eee41964fc81b1842ef0faef29c3b1cef7dc240ea39658c534",
                "execution_seconds": 15.906128883361816,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1",
                "transaction_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15.906128883361816
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-16T01:43:27.713141+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "684777dccc61f2eee41964fc81b1842ef0faef29c3b1cef7dc240ea39658c534",
                "execution_seconds": 47.25245499610901,
                "queue_seconds": 25.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1",
                "transaction_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 72.25245499610901
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1",
      "ineligible_failed_fit_ids": [
        "P0_s0_t1",
        "P0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t8"
      ],
      "new_scientific_fits": 0,
      "original_training_source_run": "2026-10-15_dsainet_ord_v0_1_stageA_repair2-full-w1",
      "predecessor_zero_task_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair3/PREDECESSOR4_ZERO_TASK_PROOF.json",
        "sha256": "80ef10fb8bb5f83bbb0d19525eaf0509542f145172d668f0e07820f0630df542"
      },
      "recorded_at": "2026-10-16T17:06:05.208371+00:00",
      "repaired_by_run_prefix": "2026-10-16_dsainet_ord_v0_1_stageA_repair4",
      "round_id": "dsa-ord-v0.1-stageA-repair3",
      "scientific_partial_artifacts_eligible": true,
      "source_contract_sha256": "684777dccc61f2eee41964fc81b1842ef0faef29c3b1cef7dc240ea39658c534",
      "source_inventory_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair3/SOURCE_INVENTORY.json",
        "sha256": "7cd86b941d25a3dc17fc1acc3e9714dc2fb1946d4d940c70f76da63cc206bc2f"
      },
      "technical_artifacts_replay_eligible": true
    },
    {
      "attempt_class": "single_audit_cudnn_runtime_failure",
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "eligible_audit_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t7",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t7",
        "B0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t1",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t2",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t7",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7",
        "S0_s1_t8"
      ],
      "eligible_fit_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t7",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t6",
        "B0_s1_t7",
        "B0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t1",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t2",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t7",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7",
        "S0_s1_t8"
      ],
      "failed_audit_ids": [
        "B0_s1_t6"
      ],
      "failed_run": {
        "bundle_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 15.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "formal_fits_to_run": 4,
        "planned_units": 57,
        "recorded_at": "2026-10-16T17:06:05.208371+00:00",
        "repair_kind": "completed_fit_recovery",
        "replaces_failed_run": "2026-10-16_dsainet_ord_v0_1_stageA_repair3-full-w1",
        "reused_formal_fits": 50,
        "round_id": "dsa-ord-v0.1-stageA-repair4",
        "run_prefix": "2026-10-16_dsainet_ord_v0_1_stageA_repair4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-16T17:10:34.972113+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-16T17:10:48.178800+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-16T17:11:27.785399+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2e8545f8a053fe7c819d407f593b001847cf617d0c751edb1c1468b0ff879fa6",
                "execution_seconds": 27.413994073867798,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
                "transaction_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-tx",
                "waiting_for_resources": false,
                "wall_seconds": 27.413994073867798
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-16T17:12:50.723514+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2e8545f8a053fe7c819d407f593b001847cf617d0c751edb1c1468b0ff879fa6",
                "execution_seconds": 80.5348973274231,
                "queue_seconds": 30.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
                "transaction_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-tx",
                "waiting_for_resources": false,
                "wall_seconds": 110.5348973274231
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T02:13:01.949038+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "2e8545f8a053fe7c819d407f593b001847cf617d0c751edb1c1468b0ff879fa6",
                "execution_seconds": 12751.280703783035,
                "queue_seconds": 2183.1906900405884,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
                "transaction_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-tx",
                "waiting_for_resources": false,
                "wall_seconds": 14934.471393823624
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
      "recorded_at": "2026-10-17T04:34:27.217955+00:00",
      "repaired_by_run_prefix": "2026-10-17_dsainet_ord_v0_1_stageA_repair5",
      "round_id": "dsa-ord-v0.1-stageA-repair4",
      "source_contract_sha256": "2e8545f8a053fe7c819d407f593b001847cf617d0c751edb1c1468b0ff879fa6",
      "source_inventory_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair5/SOURCE_INVENTORY.json",
        "sha256": "1b0ccb61c74f3e8e1d3a57116ba271a83990b49c57ad9dea59aeffbc6aa8cada"
      }
    },
    {
      "attempt_class": "audit_dispatch_budget_double_counted_reused_audits",
      "campaign_id": "dsainet-ord-v0.1-stageA-20261015",
      "eligible_audit_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t7",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t7",
        "B0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t1",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t2",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t7",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7",
        "S0_s1_t8"
      ],
      "eligible_fit_ids": [
        "B0_s0_t0",
        "B0_s0_t1",
        "B0_s0_t2",
        "B0_s0_t3",
        "B0_s0_t4",
        "B0_s0_t5",
        "B0_s0_t6",
        "B0_s0_t7",
        "B0_s0_t8",
        "B0_s1_t0",
        "B0_s1_t1",
        "B0_s1_t2",
        "B0_s1_t3",
        "B0_s1_t4",
        "B0_s1_t5",
        "B0_s1_t6",
        "B0_s1_t7",
        "B0_s1_t8",
        "P0_s0_t0",
        "P0_s0_t1",
        "P0_s0_t2",
        "P0_s0_t3",
        "P0_s0_t4",
        "P0_s0_t5",
        "P0_s0_t6",
        "P0_s0_t7",
        "P0_s0_t8",
        "P0_s1_t0",
        "P0_s1_t1",
        "P0_s1_t2",
        "P0_s1_t3",
        "P0_s1_t4",
        "P0_s1_t5",
        "P0_s1_t6",
        "P0_s1_t7",
        "P0_s1_t8",
        "S0_s0_t0",
        "S0_s0_t1",
        "S0_s0_t2",
        "S0_s0_t3",
        "S0_s0_t4",
        "S0_s0_t5",
        "S0_s0_t6",
        "S0_s0_t7",
        "S0_s0_t8",
        "S0_s1_t0",
        "S0_s1_t1",
        "S0_s1_t2",
        "S0_s1_t3",
        "S0_s1_t4",
        "S0_s1_t5",
        "S0_s1_t6",
        "S0_s1_t7",
        "S0_s1_t8"
      ],
      "failed_audit_ids": [
        "B0_s1_t6"
      ],
      "failed_run": {
        "bundle_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "formal_audits_to_run": 1,
        "formal_fits_to_run": 0,
        "planned_units": 57,
        "recorded_at": "2026-10-17T04:34:27.217955+00:00",
        "repair_kind": "completed_audit_recovery",
        "replaces_failed_run": "2026-10-16_dsainet_ord_v0_1_stageA_repair4-full-w1",
        "reused_formal_audits": 53,
        "reused_formal_fits": 54,
        "round_id": "dsa-ord-v0.1-stageA-repair5",
        "run_prefix": "2026-10-17_dsainet_ord_v0_1_stageA_repair5",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-17T04:44:17.751621+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_verified_files": 2185,
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
              "transport": "sha256_verified_archive_exclusive_destination"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-17T04:44:43.449282+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T04:45:28.108690+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "62a2cfa0bb09c71f7d1c89ced501f795c327230fa5e406b5acacb3355d3d7f5b",
                "execution_seconds": 27.808178424835205,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
                "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 27.808178424835205
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T04:51:36.965520+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "62a2cfa0bb09c71f7d1c89ced501f795c327230fa5e406b5acacb3355d3d7f5b",
                "execution_seconds": 134.34614324569702,
                "queue_seconds": 260.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
                "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 394.346143245697
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-17T06:39:28.760151+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "62a2cfa0bb09c71f7d1c89ced501f795c327230fa5e406b5acacb3355d3d7f5b",
                "execution_seconds": 330.6122536659241,
                "queue_seconds": 725.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
                "transaction_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1055.612253665924
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-17_dsainet_ord_v0_1_stageA_repair5-full-w1",
      "recorded_at": "2026-10-17T11:30:12.478148+00:00",
      "repaired_by_run_prefix": "2026-10-17_dsainet_ord_v0_1_stageA_repair6",
      "round_id": "dsa-ord-v0.1-stageA-repair5",
      "source_contract_sha256": "62a2cfa0bb09c71f7d1c89ced501f795c327230fa5e406b5acacb3355d3d7f5b",
      "source_inventory_ref": {
        "path": "ai4s/programs/dsainet/research/dsa-ord-v0.1/repair5/SOURCE_INVENTORY.json",
        "sha256": "1b0ccb61c74f3e8e1d3a57116ba271a83990b49c57ad9dea59aeffbc6aa8cada"
      }
    },
    {
      "attempt_class": "user_authorized_packaging_dependency_repair_zero_training",
      "failed_run": {
        "bundle_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-bundle-r3",
        "contract": "ai4s/programs/dsainet/research/dsa-nrc-v0.1-NRC1.yaml",
        "contract_sha256": "6cef465a2e649cbdc9eb266cf24cb24d68d263adeb145f1b32a281dc4e679628",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 19.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 251,
        "recorded_at": "2026-10-19T09:55:13.128798+00:00",
        "round_id": "dsa-nrc-v0.1-NRC1",
        "run_prefix": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-19T09:56:09.111369+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-19T09:56:12.717302+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T09:56:30.456118+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "6cef465a2e649cbdc9eb266cf24cb24d68d263adeb145f1b32a281dc4e679628",
                "execution_seconds": 12.07155466079712,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12.07155466079712
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T10:02:27.061283+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "6cef465a2e649cbdc9eb266cf24cb24d68d263adeb145f1b32a281dc4e679628",
                "execution_seconds": 215.48438143730164,
                "queue_seconds": 153.20870900154114,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 368.6930904388428
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:21:54.191886+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "6cef465a2e649cbdc9eb266cf24cb24d68d263adeb145f1b32a281dc4e679628",
                "execution_seconds": 622.2952656745911,
                "queue_seconds": 398.91890811920166,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1021.2141737937927
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-10-19T15:34:30.284521+00:00",
      "repair_authorization": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair1/AUTHORIZATION.md",
      "scientific_effect_evaluated": false,
      "source_forensics": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair1/SOURCE_FORENSICS.json",
      "source_forensics_sha256": "ee29b647d2a91c3907513355beeef7a63bd64bd9544c3ceeef78d287f4600605"
    },
    {
      "attempt_class": "user_authorized_worker_device_validation_repair_zero_training",
      "failed_run": {
        "bundle_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-bundle",
        "contract": "ai4s/programs/dsainet/research/dsa-nrc-v0.1-NRC1-repair1.yaml",
        "contract_sha256": "ef6dd910b4556a97574e613db375d7ce319b7a0164d8755e3940455c2d3325aa",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 19.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 251,
        "recorded_at": "2026-10-19T15:34:30.287560+00:00",
        "retry_of": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1-full-w1",
        "round_id": "dsa-nrc-v0.1-NRC1",
        "run_prefix": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-19T15:35:19.832692+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-19T15:35:23.741816+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:35:40.144256+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ef6dd910b4556a97574e613db375d7ce319b7a0164d8755e3940455c2d3325aa",
                "execution_seconds": 12.234907865524292,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12.234907865524292
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:37:27.144914+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ef6dd910b4556a97574e613db375d7ce319b7a0164d8755e3940455c2d3325aa",
                "execution_seconds": 119.24664044380188,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 119.24664044380188
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:38:52.333273+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "ef6dd910b4556a97574e613db375d7ce319b7a0164d8755e3940455c2d3325aa",
                "execution_seconds": 161.70412230491638,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 161.70412230491638
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-10-19T15:40:22.426329+00:00",
      "repair_authorization": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair2/AUTHORIZATION.md",
      "scientific_effect_evaluated": false,
      "source_forensics": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair2/SOURCE_FORENSICS.json",
      "source_forensics_sha256": "bfd244e96e7b94b56a95b51503dc6086797f59cabfc5f3099792d8fc111682f6"
    },
    {
      "attempt_class": "user_authorized_worker_timeout_accounting_repair_zero_formal_training",
      "failed_run": {
        "bundle_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-bundle",
        "contract": "ai4s/programs/dsainet/research/dsa-nrc-v0.1-NRC1-repair2.yaml",
        "contract_sha256": "9ab1cda662c6d7461e50693d861a68f3815c4eaa414a399f094ecbf5d8baf373",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 19.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 251,
        "recorded_at": "2026-10-19T15:40:22.427370+00:00",
        "retry_of": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair1-full-w1",
        "round_id": "dsa-nrc-v0.1-NRC1",
        "run_prefix": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-19T15:40:48.762617+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-19T15:40:53.561320+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:41:06.336052+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "tech",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "9ab1cda662c6d7461e50693d861a68f3815c4eaa414a399f094ecbf5d8baf373",
                "execution_seconds": 8.62845778465271,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8.62845778465271
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:44:38.438672+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "9ab1cda662c6d7461e50693d861a68f3815c4eaa414a399f094ecbf5d8baf373",
                "execution_seconds": 220.72219824790955,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 220.72219824790955
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T15:48:39.624035+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "9ab1cda662c6d7461e50693d861a68f3815c4eaa414a399f094ecbf5d8baf373",
                "execution_seconds": 416.5798225402832,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
                "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 416.5798225402832
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair2-full-w1",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-10-19T15:52:05.591927+00:00",
      "repair_authorization": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair3/AUTHORIZATION.md",
      "scientific_effect_evaluated": false,
      "source_forensics": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/repair3/SOURCE_FORENSICS.json",
      "source_forensics_sha256": "96e4643d9da63102c72586d257e01a5e217504437ef87ea18571947e1e8ac507"
    },
    {
      "attempt_class": "engineering_invalid_pre_science_readerfix1",
      "campaign_id": "dsainet-ds07-r1",
      "engineering_disposition": "INVALID_ENGINEERING_PRE_SCIENCE",
      "failed_run": {
        "bundle_id": "2026-11-02_dsainet_ds07_r1_science1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 39.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 2,
        "recorded_at": "2026-11-02T12:26:00.562320+00:00",
        "round_id": "ds07-r1-science1",
        "run_prefix": "2026-11-02_dsainet_ds07_r1_science1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-02T12:26:59.119881+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-02T12:29:06.630293+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-02T12:29:23.771743+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "technical_reuse",
              "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2bb53a03bdaadd9040b7159254b2ddba1a707b98f8222f7a5e715dbf3897cdd8",
                "execution_seconds": 5.084010601043701,
                "queue_seconds": 9.55618691444397,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1",
                "waiting_for_resources": true,
                "wall_seconds": 14.640197515487671
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "603b251d599280190614e3de9bff7abca1a292d3e7f7308c94e7f3a1edece5dc",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-11-02T13:45:25.816291+00:00",
      "round_id": "ds07-r1-science1",
      "scientific_decision": false
    },
    {
      "attempt_class": "engineering_invalid_pre_science_telemetryfix1",
      "campaign_id": "dsainet-ds07-r1",
      "engineering_disposition": "INVALID_ENGINEERING_N_TELEMETRY",
      "failed_run": {
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
      "failed_run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "09c3bfa6b5498a16f01a7e306015e318c8e5af403f9937d9c5bd5d27a73c195c",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-11-02T16:50:07.348007+00:00",
      "round_id": "ds07-r1-science1-readerfix1",
      "scientific_decision": false,
      "scientific_disposition": "NONE; N checkpoint retained but not qualified or reusable"
    },
    {
      "attempt_class": "engineering_invalid_summaryfix1_tech_closure",
      "campaign_id": "dsainet-ds07-r1",
      "engineering_disposition": "INVALID_TECH_SUMMARY_INTERFACE",
      "failed_run": {
        "bundle_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 47.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 2,
        "recorded_at": "2026-11-02T16:50:29.882840+00:00",
        "round_id": "ds07-r1-science1-telemetryfix1",
        "run_prefix": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-02T16:51:09.837173+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-02T16:51:13.456023+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-02T16:52:11.815333+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "technical_reuse",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ee394e5bc6ddf2b0bf5603fd8dc10419e5b88e2e36f9c032db8df5e8d77afb68",
                "execution_seconds": 4.650516986846924,
                "queue_seconds": 50.88400745391846,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-telemetryfix1",
                "waiting_for_resources": true,
                "wall_seconds": 55.53452444076538
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-02T16:54:23.631079+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "technical_reuse",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "ee394e5bc6ddf2b0bf5603fd8dc10419e5b88e2e36f9c032db8df5e8d77afb68",
                "execution_seconds": 5.271691083908081,
                "queue_seconds": 182.07463479042053,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-telemetryfix1",
                "waiting_for_resources": true,
                "wall_seconds": 187.3463258743286
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-03T13:09:53.853737+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "technical_reuse",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "ee394e5bc6ddf2b0bf5603fd8dc10419e5b88e2e36f9c032db8df5e8d77afb68",
                "execution_seconds": 164.34781575202942,
                "queue_seconds": 1763.9529342651367,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-telemetryfix1",
                "waiting_for_resources": false,
                "wall_seconds": 1928.3007500171661
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "ddc071fdf3a34d914d644d1e72b403f01388fee0002883b0e41a3d9bb3270893",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-11-03T14:09:52.027274+00:00",
      "round_id": "ds07-r1-science1-telemetryfix1",
      "scientific_decision": false,
      "scientific_disposition": "NONE; N/C/S/R qualified parent results remain reusable only through CPU evidence replay"
    },
    {
      "attempt_class": "engineering_invalid_device_index_before_training",
      "campaign_id": "dsainet-ds07-r1",
      "engineering_disposition": "INVALID_CUDA_DEVICE_INDEX_BEFORE_TRAINING",
      "failed_run": {
        "bundle_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 47.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 2,
        "recorded_at": "2026-11-03T14:11:11.000321+00:00",
        "round_id": "ds07-r1-science1-summaryfix1",
        "run_prefix": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-03T14:13:38.472077+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-03T14:13:42.763647+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-03T14:14:23.572639+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e72dd5f020f21d4b52fb749265c08a3759befee5507f392ccf5b7355e019b59e",
                "execution_seconds": 6.7571306228637695,
                "queue_seconds": 30.665966987609863,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-summaryfix1",
                "waiting_for_resources": true,
                "wall_seconds": 37.42309761047363
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-03T14:20:35.583175+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e72dd5f020f21d4b52fb749265c08a3759befee5507f392ccf5b7355e019b59e",
                "execution_seconds": 8.093563795089722,
                "queue_seconds": 400.7561135292053,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-summaryfix1",
                "waiting_for_resources": true,
                "wall_seconds": 408.84967732429504
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-04T05:42:34.314015+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "e72dd5f020f21d4b52fb749265c08a3759befee5507f392ccf5b7355e019b59e",
                "execution_seconds": 19.086092948913574,
                "queue_seconds": 1498.042162656784,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-summaryfix1",
                "waiting_for_resources": false,
                "wall_seconds": 1517.1282556056976
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
      "failure_proof_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/FAILURE_PROOF.json",
      "failure_proof_sha256": "3b73f29709b6e739e0306dd39a3ab2a93eae20f2a60f5228e747e0572fd7af2f",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-11-04T06:25:28.927092+00:00",
      "round_id": "ds07-r1-science1-summaryfix1",
      "scientific_decision": false,
      "scientific_disposition": "NONE; parent TECH PASS and prior qualified evidence remain reusable only through bound CPU replay"
    },
    {
      "engineering_disposition": "INVALID_R_PARTIAL_ROLE_CHECK",
      "failed_run": {
        "bundle_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 47.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 2,
        "recorded_at": "2026-11-04T06:26:56.603601+00:00",
        "round_id": "ds07-r1-science1-devicefix1",
        "run_prefix": "2026-11-04_dsainet_ds07_r1_science1-devicefix1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-04T06:35:37.164147+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-04T06:38:02.203078+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-04T06:38:47.163479+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b9824b039bc8dcaaaa907ac8a1c7cdfd0d03b90cbb7a73cc82438edce1c748ef",
                "execution_seconds": 42.21297478675842,
                "queue_seconds": 0.8287975788116455,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
                "transaction_id": "dsainet-ds07-r1-science1-devicefix1",
                "waiting_for_resources": false,
                "wall_seconds": 43.04177236557007
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
      "reusable_audits": 54,
      "reusable_fits": 72,
      "scientific_decision": false,
      "training_repeated": false
    },
    {
      "attempt_class": "user_authorized_dsainet_attention_grid_py39_failed_smoke_repair",
      "engineering_reason": "User-authorized Python 3.9 repair of the sole failed smoke, original 24-fit matrix and gates preserved.",
      "failed_run": {
        "bundle_id": "2026-11-22_dsainet_b0_attention_token_grid_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 1.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 25,
        "recorded_at": "2026-11-22T09:38:50.845345+00:00",
        "round_id": "dsainet-b0-attention-token-grid-r1",
        "run_prefix": "2026-11-22_dsainet_b0_attention_token_grid_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-22T09:39:11.514024+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-22T09:39:15.158318+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T09:39:28.175241+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "97ace9a39ab522246a841cb8a25f4738e68656dc139c34bfb5ee6e584034bfce",
                "execution_seconds": 1.8964934349060059,
                "queue_seconds": 10.340312957763672,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1",
                "transaction_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 12.236806392669678
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T14:49:46.793157+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "97ace9a39ab522246a841cb8a25f4738e68656dc139c34bfb5ee6e584034bfce",
                "execution_seconds": 20.793821573257446,
                "queue_seconds": 3556.570862531662,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1",
                "transaction_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3577.3646841049194
              }
            }
          }
        ]
      },
      "failed_run_id": "2026-11-22_dsainet_b0_attention_token_grid_r1-full-w1",
      "partial_artifacts_eligible": false,
      "recorded_at": "2026-11-22T14:56:41.625852+00:00",
      "redeployment_report": "ai4s/programs/dsainet/research/b0_asymmetric_token_grid_20261122_py39fix1/REDEPLOYMENT.json",
      "round_id": "dsainet-b0-attention-token-grid-r1",
      "scientific_fits": 0,
      "scientific_intake": false,
      "source_contract_sha256": "97ace9a39ab522246a841cb8a25f4738e68656dc139c34bfb5ee6e584034bfce",
      "task_attempts": 1
    }
  ],
  "follow_up": {
    "action": "STOP_FIXED_DS07_R1",
    "automatic_next_round": false,
    "budget_clock_paused": false,
    "budget_reset": false,
    "user_instruction": "先不启动新实验"
  },
  "frozen_modules": [
    {
      "evidence_record": "ai4s/archive/programs/dsainet/research/C1_MODULE_FREEZE_2026-08-30.md",
      "frozen_at": "2026-08-29T18:05:09.032300+00:00",
      "module_id": "DSAINetScaleContrastResidual/symmetric_control/C1",
      "prohibited_follow_up": [
        "new C1 training or validation",
        "parameter rescue or architecture variants",
        "benchmark or paper claim promotion"
      ],
      "reason": "R03 independent-seed C1-versus-B0 screen did not pass the frozen stability gates; user closed this specific module.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/archive/programs/dsainet/research/O1_T1_TOPOLOGY_PERMUTATION_FREEZE_2026-08-31.md",
      "frozen_at": "2026-08-31T09:00:24.649971+00:00",
      "module_id": "DSAINetTopologyPermutation/crossed_intra_ownership/O1",
      "prohibited_follow_up": [
        "new DSAINetTopologyPermutation/crossed_intra_ownership/O1 training or validation",
        "parameter rescue or architecture variants",
        "benchmark or paper claim promotion"
      ],
      "reason": "User closed O1/T1 topology-permutation exploration; verified O1 screen did not meet frozen stability gates.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/archive/programs/dsainet/research/O1_T1_TOPOLOGY_PERMUTATION_FREEZE_2026-08-31.md",
      "frozen_at": "2026-08-31T09:00:27.987446+00:00",
      "module_id": "DSAINetTopologyPermutation/branch2_temporal_reversal/T1",
      "prohibited_follow_up": [
        "new DSAINetTopologyPermutation/branch2_temporal_reversal/T1 training or validation",
        "parameter rescue or architecture variants",
        "benchmark or paper claim promotion"
      ],
      "reason": "User closed O1/T1 topology-permutation exploration; independent T1 seeds 2/3 confirmation did not establish stable uplift.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/role-pooling-confirmation-20260906/P0_MODULE_FREEZE_20260906.md",
      "frozen_at": "2026-09-05T21:29:02.923882+00:00",
      "module_id": "DSAINetRoleSpecificTokenPooling/role-specific-vs-shared-average/P0",
      "prohibited_follow_up": [
        "new DSAINetRoleSpecificTokenPooling/role-specific-vs-shared-average/P0 training or validation",
        "seed4 rescue or pooling older seed means to overturn seeds 2/3",
        "architecture variants or P0/C0/B0 recombination under the frozen confirmation contract",
        "benchmark or paper claim promotion"
      ],
      "reason": "Independent-seed confirmation on seeds 2/3 did not pass frozen stability gates versus shared-average control.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/inter-attention-lesion-20260906/L0_MODULE_FREEZE_20260906.md",
      "frozen_at": "2026-09-06T11:26:40.386215+00:00",
      "module_id": "DSAINetInterAttentionLesion/identity-skip-vs-native/P0",
      "prohibited_follow_up": [
        "new DSAINetInterAttentionLesion/identity-skip-vs-native/P0 training or validation",
        "seed rescue or recombination with I1 attention-order variants",
        "benchmark or paper claim promotion"
      ],
      "reason": "Verified 36-task screen of identity-skip inter-attention versus native did not pass frozen stability gates.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/ilud-20260906/ILUD_DIAGNOSTIC_FREEZE_20260907.md",
      "frozen_at": "2026-09-06T16:46:30.005563+00:00",
      "module_id": "DSAINetInterStageLabelUtility/ilud-source-linear-access/v0.1",
      "prohibited_follow_up": [
        "new DSAINetInterStageLabelUtility/ilud-source-linear-access/v0.1 diagnostic with extra seeds, windows, C, losses or decoder training",
        "target inference or pooling/lesion/RACR/RAIA rescue from this diagnostic",
        "benchmark or paper claim promotion"
      ],
      "reason": "Verified source-only ILUD diagnostic completed once; controller primary contrast missed the +1 pp gate.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/cgmw-20260907/CGMW_RULE_FREEZE_20260907.md",
      "frozen_at": "2026-09-06T18:41:19.413720+00:00",
      "module_id": "DSAINetInterEvidenceTransfer/cgmw-preconf-median-withhold/v0.1",
      "prohibited_follow_up": [
        "threshold search, one-direction rewrite, or trained gate/adapter rescue of this median-withhold rule",
        "benchmark or paper claim promotion"
      ],
      "reason": "Verified train-median pre_conf withhold did not change source-validation accuracy versus always-native.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/INTER_EVIDENCE_TRANSFER_FAMILY_CLOSE_20260907.md",
      "frozen_at": "2026-09-06T18:41:19.638237+00:00",
      "module_id": "DSAINetInterEvidenceTransfer/native-message-utility/v0.1",
      "prohibited_follow_up": [
        "new inter-message identity skip, direction suppressor, or observable-gated message training under this family",
        "seed/threshold/adapter rescue of native inter-message utility",
        "benchmark or paper claim promotion"
      ],
      "reason": "Lesion, ILUD, DNRUA, MROA ranking, and CGMW withhold jointly failed to produce an inter-message performance candidate.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/tapl-20260907/TAPL_SCREEN_FREEZE_20260907.md",
      "frozen_at": "2026-09-06T18:52:47.560829+00:00",
      "module_id": "DSAINetTokenAttentionPooling/uniform-mean-vs-native/v0.1",
      "prohibited_follow_up": [
        "independent-seed confirmation or trained pooling candidate without new authorization",
        "recombination with closed P0 role-specific vs shared-average pooling",
        "benchmark or paper claim promotion"
      ],
      "reason": "Frozen B0 target-LOSO token attention beat uniform mean pooling; screen support only, no confirmation or P0 rescue.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/tapl-attribution/TAUD_SCREEN_FREEZE_20260907.md",
      "frozen_at": "2026-09-07T03:45:57.475539+00:00",
      "module_id": "DSAINetTokenAttentionUtility/weight-permutation-vs-native/v0.1",
      "prohibited_follow_up": [
        "trained pooling candidate or independent-seed confirmation without new authorization",
        "recombination with closed P0 role-specific pooling",
        "benchmark or paper claim promotion"
      ],
      "reason": "Frozen B0 target-LOSO native weights beat eight fixed both-branch permutations; screen support only.",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/dsainet/research/source-template-audit/SFTA_SCREEN_FREEZE_20260907.md",
      "frozen_at": "2026-09-07T06:16:48.851448+00:00",
      "module_id": "DSAINetSourceFrozenTemplate/source-mean-vs-branch1-mean/v0.1",
      "prohibited_follow_up": [
        "class-conditional templates, target-informed retuning, or trained fixed pooling without new authorization",
        "recombination with closed P0 role-specific pooling",
        "benchmark or paper claim promotion"
      ],
      "reason": "Source-train frozen branch1 template beat branch1 uniform mean on frozen B0 target LOSO; screen support only.",
      "status": "FROZEN_EVIDENCE_ONLY"
    }
  ],
  "handoff": {
    "completed_at": "2026-08-29",
    "confirmed_by_user": true,
    "note": "RACR and RAIA are imported as closed/no-signal route boundaries only; their performance, authorization, and claim status do not transfer to AI4S.",
    "racr_reconciled": true,
    "raia_closed_and_confirmed": true,
    "record": "ai4s/archive/programs/dsainet/research/PROPOSED_HANDOFF_2026-08-29.md"
  },
  "invalid_closure": {
    "intake": {
      "intake_path": null,
      "reason": "verified intake requires intake directory, verification marker, and run_status.json",
      "run_id": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3-full-w1",
      "verified": false
    },
    "reason": "Fourth R03 full attempt was interrupted by consecutive [REDACTED_MACHINE] host reboots. The process is absent, formal run_status remains running, and no transfer archive exists; partial artifacts are ineligible for reuse, result freezing, decision, or claim.",
    "recorded_at": "2026-09-05T02:47:15.454083+00:00",
    "run_id": "2026-09-02_dsainet_ai4s_role_specific_token_pooling_r3r3-full-w1"
  },
  "invalid_repair_authorizations": [
    {
      "authorized_at": "2026-09-05T17:58:10.857621+00:00",
      "reason": "Repair only the pre-training GPU resource gate observability and bounded transient wait; no partial task output is reused.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-confirm-role-pooling-seed23-repair-v0.1.yaml",
      "repair_round_id": "dsainet-confirm-role-pooling-seed23-repair-v0.1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-confirm-role-pooling-seed23-v0.1_decision.yaml",
      "source_round_id": "dsainet-confirm-role-pooling-seed23-v0.1",
      "source_run_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r2-full-w1"
    },
    {
      "authorized_at": "2026-09-05T19:19:39.502369+00:00",
      "reason": "Ignore stale dead nvidia-smi compute PIDs and the parent launcher PID; live foreign occupancy still fails immediately; no partial task output is reused.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-confirm-role-pooling-seed23-repair2-v0.1.yaml",
      "repair_round_id": "dsainet-confirm-role-pooling-seed23-repair2-v0.1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-confirm-role-pooling-seed23-repair-v0.1_decision.yaml",
      "source_round_id": "dsainet-confirm-role-pooling-seed23-repair-v0.1",
      "source_run_id": "2026-09-06_dsainet_role_pooling_confirm_seed23_r3-full-w1"
    },
    {
      "authorized_at": "2026-09-06T16:28:42.811896+00:00",
      "reason": "Load frozen B0 checkpoints without weights_only= on ccmu mieeg torch; scientific panel unchanged.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r03-ilud-v0.1-r4.yaml",
      "repair_round_id": "dsainet-r03-ilud-v0.1-r4",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r03-ilud-v0.1-r3_decision.yaml",
      "source_round_id": "dsainet-r03-ilud-v0.1-r3",
      "source_run_id": "2026-09-06_dsainet_ilud_v0_1_r3-full-w1"
    },
    {
      "authorized_at": "2026-09-07T03:31:16.036274+00:00",
      "reason": "Drop argsort(stable=) so rank-only weights run on ccmu mieeg torch; scientific panel unchanged.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-taud-v0.1-r2.yaml",
      "repair_round_id": "dsainet-r01-taud-v0.1-r2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-taud-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-taud-v0.1",
      "source_run_id": "2026-09-07_dsainet_taud_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-07T15:46:05.993050+00:00",
      "reason": "Repair the scheduler task-priority encoding from nonconforming labels to the scheduler-required P0 through P53 sequence; no scientific task had started and no partial result is reused.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-repair-v0.1.yaml",
      "repair_round_id": "dsainet-r01-ttpp-lab10-repair-v0.1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-ttpp-lab10-v0.1",
      "source_run_id": "2026-09-07_dsainet_ttpp_lab10_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-08T04:50:21.716918+00:00",
      "reason": "User-authorized remaining-task recovery after timeout: preserve 39 verified completed tasks with original provenance, train only 15 unfinished tasks; repair per-GPU family admission.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-remaining-v0.1.yaml",
      "repair_round_id": "dsainet-r01-ttpp-lab10-remaining-v0.1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-repair-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-ttpp-lab10-repair-v0.1",
      "source_run_id": "2026-09-07_dsainet_ttpp_lab10_repair_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-08T04:54:21.785209+00:00",
      "reason": "User-authorized remaining-task recovery after timeout: preserve 39 verified completed tasks with original provenance, train only 15 unfinished tasks; repair per-GPU family admission.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-remaining-v0.2.yaml",
      "repair_round_id": "dsainet-r01-ttpp-lab10-remaining-v0.2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-ttpp-lab10-remaining-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-ttpp-lab10-remaining-v0.1",
      "source_run_id": "2026-09-08_dsainet_ttpp_lab10_remaining_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-09T04:47:58.025817+00:00",
      "reason": "Strict frozen batch partition for one scientific node, with mandatory verified seal prerequisite; original science unchanged; zero original scientific training.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-sdsa-v0.1-repair1.yaml",
      "repair_round_id": "dsainet-r01-sdsa-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-sdsa-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-sdsa-v0.1",
      "source_run_id": "2026-09-09_dsainet_sdsa_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-11T18:05:24.634853+00:00",
      "reason": "User-authorized clean paired resubmission after post-training identity exception; no partial artifact reuse",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-sna-v0.1-repair2.yaml",
      "repair_round_id": "dsainet-r01-sna-v0.1-repair2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-sna-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-sna-v0.1",
      "source_run_id": "2026-09-11_dsainet_sna_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-15T07:11:16.285732+00:00",
      "reason": "CPU/CUDA post-training audit repair; explicitly authorized 36 retrains and independently verified 18 B0 imports",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-gsf-v0.1-repair1.yaml",
      "repair_round_id": "dsainet-r01-gsf-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-gsf-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-gsf-v0.1",
      "source_run_id": "2026-09-14_dsainet_gsf_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-15T09:04:24.476379+00:00",
      "reason": "Resource admission 2048MiB and scope wiring correction before any candidate train; same authorized 36 trainings and 18 B0 imports",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-gsf-v0.1-repair2.yaml",
      "repair_round_id": "dsainet-r01-gsf-v0.1-repair2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-gsf-v0.1-repair1_decision.yaml",
      "source_round_id": "dsainet-r01-gsf-v0.1-repair1",
      "source_run_id": "2026-09-15_dsainet_gsf_v0_1_repair1-full-w1"
    },
    {
      "authorized_at": "2026-09-15T13:56:35.478059+00:00",
      "reason": "Bare python resolved to system Python 3.8 before scheduler/task creation; bind both node commands to verified mieeg Python 3.9 absolute path.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1-repair1.yaml",
      "repair_round_id": "dsainet-r01-cmcr-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1_decision.yaml",
      "source_round_id": "dsainet-r01-cmcr-v0.1",
      "source_run_id": "2026-09-15_dsainet_cmcr_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-15T17:35:46.667296+00:00",
      "reason": "Set native deterministic cuDNN options at real checker entrance; preserve exact model and tolerances; shared GPU reserve policy; independently verified B0 technical reuse.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1-repair2.yaml",
      "repair_round_id": "dsainet-r01-cmcr-v0.1-repair2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1-repair1_decision.yaml",
      "source_round_id": "dsainet-r01-cmcr-v0.1-repair1",
      "source_run_id": "2026-09-15_dsainet_cmcr_v0_1_repair1-full-w1"
    },
    {
      "authorized_at": "2026-09-16T07:13:33.196656+00:00",
      "reason": "Correct native augmented sample-count validation (B32 K3 gives62). Requalify the changed runner with five source-only technical fits, then execute the unchanged90-task matrix.",
      "repair_contract": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1-repair3.yaml",
      "repair_round_id": "dsainet-r01-cmcr-v0.1-repair3",
      "source_decision_record": "ai4s/programs/dsainet/research/dsainet-r01-cmcr-v0.1-repair2_decision.yaml",
      "source_round_id": "dsainet-r01-cmcr-v0.1-repair2",
      "source_run_id": "2026-09-16_dsainet_cmcr_v0_1_repair2-full-w1"
    },
    {
      "authorized_at": "2026-09-19T14:04:25.430911+00:00",
      "reason": "One bounded engineering repair: bind Transaction node scopes to lab10_node.py so the shared executor expands task_json; no scientific matrix or model change.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair1.yaml",
      "repair_round_id": "dsa-ds01-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-ds01-v0.1_decision.yaml",
      "source_round_id": "dsa-ds01-v0.1",
      "source_run_id": "2026-09-19_dsainet_dsa_ds01_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-19T14:25:53.436069+00:00",
      "reason": "Python 3.8 compatibility repair for the transaction path-boundary validator; no scientific matrix or model change.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair2.yaml",
      "repair_round_id": "dsa-ds01-v0.1-repair2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair1_decision.yaml",
      "source_round_id": "dsa-ds01-v0.1-repair1",
      "source_run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair1-full-w1"
    },
    {
      "authorized_at": "2026-09-19T14:37:27.789725+00:00",
      "reason": "Python 3.8 compatibility repair for DS-01 runner string prefix parsing; no scientific matrix or model change.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair3.yaml",
      "repair_round_id": "dsa-ds01-v0.1-repair3",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair2_decision.yaml",
      "source_round_id": "dsa-ds01-v0.1-repair2",
      "source_run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair2-full-w1"
    },
    {
      "authorized_at": "2026-09-19T15:13:22.140245+00:00",
      "reason": "Correct the locally introduced runner indentation error after DS-01 repair3 dependency-scan failure; no scientific matrix or model change.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair4.yaml",
      "repair_round_id": "dsa-ds01-v0.1-repair4",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair3_decision.yaml",
      "source_round_id": "dsa-ds01-v0.1-repair3",
      "source_run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair3-full-w1"
    },
    {
      "authorized_at": "2026-09-19T17:08:45.721187+00:00",
      "reason": "Isolate one task per GPU and disable same-owner sharing after repair4 GPU OOM and cuDNN resource contention; preserve scientific matrix and measured memory commitments.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair5.yaml",
      "repair_round_id": "dsa-ds01-v0.1-repair5",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-ds01-v0.1-repair4_decision.yaml",
      "source_round_id": "dsa-ds01-v0.1-repair4",
      "source_run_id": "2026-09-19_dsainet_dsa_ds01_v0_1_repair4-full-w1"
    },
    {
      "authorized_at": "2026-09-21T07:40:18.462730+00:00",
      "reason": "Planned stop of zero-attempt queue to correct unauthorized isolation; no scientific failure or training retry; original memory-only same-owner policy restored.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-pcr-v0.2-capacity1.yaml",
      "repair_round_id": "dsa-pcr-v0.2-capacity1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-pcr-v0.2_decision.yaml",
      "source_round_id": "dsa-pcr-v0.2",
      "source_run_id": "2026-09-21_dsainet_dsa_pcr_v0_2-full-w1"
    },
    {
      "authorized_at": "2026-09-21T12:19:24.279917+00:00",
      "reason": "Scheduler priority schema wiring only; zero fits before failure, science unchanged.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair1.yaml",
      "repair_round_id": "dsa-kshape-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-kshape-v0.1_decision.yaml",
      "source_round_id": "dsa-kshape-v0.1",
      "source_run_id": "2026-09-21_dsainet_kshape_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-21T13:56:38.485976+00:00",
      "reason": "Exact task 100-step validation separated from 500-step reused node aggregate; completed technical tasks independently verified; no new technical fits.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair2.yaml",
      "repair_round_id": "dsa-kshape-v0.1-repair2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair1_decision.yaml",
      "source_round_id": "dsa-kshape-v0.1-repair1",
      "source_run_id": "2026-09-21_dsainet_kshape_v0_1-repair1-full-w1"
    },
    {
      "authorized_at": "2026-09-22T04:18:17.911357+00:00",
      "reason": "Explicit user-authorized fresh-process retry of C0_s1_t0 only; preserve hash-verified 89 complete fits, then audit original 90-unit closure.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair3.yaml",
      "repair_round_id": "dsa-kshape-v0.1-repair3",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair2_decision.yaml",
      "source_round_id": "dsa-kshape-v0.1-repair2",
      "source_run_id": "2026-09-21_dsainet_kshape_v0_1-repair2-full-w1"
    },
    {
      "authorized_at": "2026-09-22T04:25:38.923471+00:00",
      "reason": "Close the original 90-ID scheduler scope: 89 hash-only zero-step reuse checks and the single authorized C0_s1_t0 fit; repair3 had zero new fit attempts.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair4.yaml",
      "repair_round_id": "dsa-kshape-v0.1-repair4",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair3_decision.yaml",
      "source_round_id": "dsa-kshape-v0.1-repair3",
      "source_run_id": "2026-09-22_dsainet_kshape_v0_1-repair3-full-w1"
    },
    {
      "authorized_at": "2026-09-22T06:36:21.077545+00:00",
      "reason": "Recover all 90 immutable fits and 87 complete frozen audits; rerun only 3 failed audits, temporarily avoid GPU5 while preserving capacity sharing; no new training.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair5.yaml",
      "repair_round_id": "dsa-kshape-v0.1-repair5",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-kshape-v0.1-repair4_decision.yaml",
      "source_round_id": "dsa-kshape-v0.1-repair4",
      "source_run_id": "2026-09-22_dsainet_kshape_v0_1-repair4-full-w1"
    },
    {
      "authorized_at": "2026-09-23T13:53:07.130690+00:00",
      "reason": "Explicit user recovery: preserve 54 hash-bound extractions as new verified inputs, recheck shared capacity before forward, complete exact missing18 and original864 probes; no scientific protocol change.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-aec-v0.1-repair1.yaml",
      "repair_round_id": "dsa-aec-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-aec-v0.1_decision.yaml",
      "source_round_id": "dsa-aec-v0.1",
      "source_run_id": "2026-09-23_dsainet_aec_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-09-25T09:46:40.590293+00:00",
      "reason": "repair operative receipt and true equivalence validation; quarantine unresolved GPU8 errors; unchanged science",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-ael-v0.1-repair1.yaml",
      "repair_round_id": "dsa-ael-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-ael-v0.1_decision.yaml",
      "source_round_id": "dsa-ael-v0.1",
      "source_run_id": "2026-09-25_dsainet_ael_v0_1_launch1-full-w1"
    },
    {
      "authorized_at": "2026-10-11T03:10:51.867057+00:00",
      "reason": "User 2026-10-11 explicitly authorizes one missing audit; individual source artifacts requalified by exact hashes",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume1.yaml",
      "repair_round_id": "dsa-rns-v0.1-audit-resume1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-rns-v0.1_decision.yaml",
      "source_round_id": "dsa-rns-v0.1",
      "source_run_id": "2026-10-10_dsainet_rns_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-10-11T05:26:40.128893+00:00",
      "reason": "User 2026-10-11 explicitly authorizes repair and one missing audit; missing own CUDA telemetry receives zero credit with unchanged frozen floor",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume2.yaml",
      "repair_round_id": "dsa-rns-v0.1-audit-resume2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-rns-v0.1-audit-resume1_decision.yaml",
      "source_round_id": "dsa-rns-v0.1-audit-resume1",
      "source_run_id": "2026-10-11_dsainet_rns_v0_1_audit_resume1-full-w1"
    },
    {
      "authorized_at": "2026-10-11T11:27:34.951275+00:00",
      "reason": "zero-training parser failure; single engineering preparation; same campaign, accrued cost, science and zero automatic training retries",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-cru-v0.1-repair1.yaml",
      "repair_round_id": "dsa-cru-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-cru-v0.1_decision.yaml",
      "source_round_id": "dsa-cru-v0.1",
      "source_run_id": "2026-10-11_dsainet_cru_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-10-11T15:06:08.794999+00:00",
      "reason": "User requested 补跑: preserve 15 separately hash-qualified complete fits and 5 technical smokes, execute 75 untouched fits and 90 audits; fail-closed transient GPU telemetry recovery; same accrued campaign budget",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-cru-v0.1-resume1.yaml",
      "repair_round_id": "dsa-cru-v0.1-resume1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-cru-v0.1-repair1_decision.yaml",
      "source_round_id": "dsa-cru-v0.1-repair1",
      "source_run_id": "2026-10-11_dsainet_cru_v0_1_repair1-full-w1"
    },
    {
      "authorized_at": "2026-10-12T04:59:34.805239+00:00",
      "reason": "User requested 补跑: preserve 89 separately hash-qualified complete fits and 5 technical smokes, rerun only failed B0_s0_t8 and execute90 audits; unchanged runner with conservative4096MiB commitment; same accrued campaign budget",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-cru-v0.1-resume2.yaml",
      "repair_round_id": "dsa-cru-v0.1-resume2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-cru-v0.1-resume1_decision.yaml",
      "source_round_id": "dsa-cru-v0.1-resume1",
      "source_run_id": "2026-10-11_dsainet_cru_v0_1_resume1-full-w1"
    },
    {
     
```
