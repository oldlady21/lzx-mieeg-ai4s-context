# State 阅读分段 1

完整脱敏文件：`ai4s/programs/dbconformer/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`2186a6c6abd15d7d9bf4449ab6157f5b7f21c7e35c21cf5e1e0b072a183adbc6`。UTF-8 字节范围：[0, 500000) / 1171181。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
{
  "active_operation": null,
  "active_research": "sgp_r1",
  "active_round": null,
  "active_run": null,
  "active_run_history": [
    {
      "bundle_id": "2026-10-18_dbconformer_bsp_r1_lab10_bundle_r1",
      "dispatch_status": "REMOTE_ACCEPTED",
      "estimated_training_hours": 25.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 30,
      "recorded_at": "2026-10-18T10:01:46.785444+00:00",
      "round_id": "dbconformer-bsp-r1",
      "run_prefix": "2026-10-18_dbconformer_bsp_r1_lab10_r1",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-18T10:05:28.454401+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-18T10:05:33.323941+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T10:05:59.199910+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "1712d2fc73d36daa63f2e5cff2426e5675dd268b173a3573595245d69b8f4e94",
              "execution_seconds": 21.071316957473755,
              "queue_seconds": 2.430514335632324,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 23.50183129310608
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T17:42:46.383267+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "1712d2fc73d36daa63f2e5cff2426e5675dd268b173a3573595245d69b8f4e94",
              "execution_seconds": 1292.6729867458344,
              "queue_seconds": 2.430514335632324,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 1295.1035010814667
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_bundle_r1",
      "contract_metadata": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair1.yaml",
      "contract_sha256": "ab796b3782a214c801f848581401f6c2e39eafad39a1260d636e95616be564ec",
      "dispatch_status": "REMOTE_ACCEPTED",
      "dispatch_units": 27,
      "estimated_runtime_hours": 23.0,
      "estimated_training_hours": 23.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "fresh_training_units": 27,
      "imported_technical_units": 3,
      "new_scientific_units": 27,
      "new_technical_units": 0,
      "planned_unique_fit_evidence": 30,
      "planned_units": 27,
      "recorded_at": "2026-10-18T19:33:46.410175+00:00",
      "round_contract_path": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair1.yaml",
      "round_id": "dbconformer-bsp-r1-repair1",
      "run_prefix": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1",
      "terminal_disposition": "FAILED_ZERO_FIT_SCREEN_ENTRY_REPAIR",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-18T19:36:23.221429+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-18T19:36:27.775104+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T19:37:23.507900+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "ab796b3782a214c801f848581401f6c2e39eafad39a1260d636e95616be564ec",
              "execution_seconds": 9.060137510299683,
              "queue_seconds": 0.0,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 9.060137510299683
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_bundle_r1",
      "contract_metadata": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair2.yaml",
      "contract_sha256": "4bea4f548eb0bfb2d344e73552089f8ffaacd0ef2ea077958a9be1930be969e0",
      "dispatch_status": "REMOTE_ACCEPTED",
      "dispatch_units": 27,
      "estimated_runtime_hours": 23.0,
      "estimated_training_hours": 23.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "fresh_training_units": 27,
      "imported_technical_units": 3,
      "new_scientific_units": 27,
      "new_technical_units": 0,
      "planned_unique_fit_evidence": 30,
      "planned_units": 27,
      "recorded_at": "2026-10-18T19:59:42.679912+00:00",
      "recovery_of": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1",
      "round_contract_path": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair2.yaml",
      "round_id": "dbconformer-bsp-r1-repair2",
      "run_prefix": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1",
      "terminal_disposition": "FAILED_PRE_DATA_READ_AUTHORIZATION_CHECK_REPAIR",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-18T20:10:36.076746+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
            "verified_server_copy": {
              "destination": "[REDACTED_MACHINE]",
              "launch_claim_present": false,
              "new_fits": 0,
              "partial_directory_preserved": "[REDACTED_MACHINE]",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
              "source": "[REDACTED_MACHINE]",
              "source_manifest_sha256": "1319f738d1694b281adb3ef97b74f1b5e3ff3c29e933a3a6859301bee9ec98f3",
              "status": "PASS_EXACT_SERVER_COPY_FRESH_DESTINATION",
              "verified_files": 360
            }
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-18T20:10:49.559261+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T20:11:03.983717+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "4bea4f548eb0bfb2d344e73552089f8ffaacd0ef2ea077958a9be1930be969e0",
              "execution_seconds": 10.24918007850647,
              "queue_seconds": 1.0317401885986328,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair2-tx",
              "waiting_for_resources": true,
              "wall_seconds": 11.280920267105103
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T20:13:21.016295+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "4bea4f548eb0bfb2d344e73552089f8ffaacd0ef2ea077958a9be1930be969e0",
              "execution_seconds": 145.82820463180542,
              "queue_seconds": 2.496445655822754,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair2-tx",
              "waiting_for_resources": false,
              "wall_seconds": 148.32465028762817
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T20:13:59.970110+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "4bea4f548eb0bfb2d344e73552089f8ffaacd0ef2ea077958a9be1930be969e0",
              "execution_seconds": 163.1253137588501,
              "queue_seconds": 2.496445655822754,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair2-tx",
              "waiting_for_resources": false,
              "wall_seconds": 165.62175941467285
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_bundle_r1",
      "contract_metadata": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair3.yaml",
      "contract_sha256": "12cdee83ad1578a1fc1b542d1d8f832978c60868d5e6cbb8d058b9f37d7c03bf",
      "dispatch_status": "REMOTE_ACCEPTED",
      "dispatch_units": 27,
      "estimated_runtime_hours": 23.0,
      "estimated_training_hours": 23.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "fresh_training_units": 27,
      "imported_technical_units": 3,
      "new_scientific_units": 27,
      "new_technical_units": 0,
      "planned_unique_fit_evidence": 30,
      "planned_units": 27,
      "recorded_at": "2026-10-18T20:24:22.057970+00:00",
      "recovery_of": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
      "round_contract_path": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair3.yaml",
      "round_id": "dbconformer-bsp-r1-repair3",
      "run_prefix": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1",
      "terminal_disposition": "FAILED_PARTIAL_CONTINUATION_OOM_AFTER_23_SCI",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-18T20:24:35.942195+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
            "verified_server_copy": {
              "destination": "[REDACTED_MACHINE]",
              "launch_claim_present": false,
              "new_fits": 0,
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
              "source": "[REDACTED_MACHINE]",
              "source_manifest_sha256": "592b92df588a3d389896ea313f3d0fa9ab190f9d0afe0bfa9ab66c4a37b189ef",
              "status": "PASS_QUALIFIED_SERVER_COPY_FRESH_DESTINATION",
              "verified_files": 450
            }
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-18T20:24:39.936814+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T20:24:52.337424+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "12cdee83ad1578a1fc1b542d1d8f832978c60868d5e6cbb8d058b9f37d7c03bf",
              "execution_seconds": 7.851548433303833,
              "queue_seconds": 0.0,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair3-tx",
              "waiting_for_resources": false,
              "wall_seconds": 7.851548433303833
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T20:25:30.280285+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "12cdee83ad1578a1fc1b542d1d8f832978c60868d5e6cbb8d058b9f37d7c03bf",
              "execution_seconds": 11.386600255966187,
              "queue_seconds": 34.41314196586609,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair3-tx",
              "waiting_for_resources": true,
              "wall_seconds": 45.799742221832275
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-18T20:26:18.296587+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "12cdee83ad1578a1fc1b542d1d8f832978c60868d5e6cbb8d058b9f37d7c03bf",
              "execution_seconds": 56.12015509605408,
              "queue_seconds": 37.680238008499146,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair3-tx",
              "waiting_for_resources": false,
              "wall_seconds": 93.80039310455322
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-19T02:39:02.988663+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "12cdee83ad1578a1fc1b542d1d8f832978c60868d5e6cbb8d058b9f37d7c03bf",
              "execution_seconds": 4738.192981719971,
              "queue_seconds": 37.680238008499146,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bsp-r1-repair3-tx",
              "waiting_for_resources": false,
              "wall_seconds": 4775.87321972847
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-10-19_dbconformer_srt_r1_lab10_bundle_r1",
      "dispatch_status": "REMOTE_ACCEPTED",
      "estimated_training_hours": 34.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 40,
      "recorded_at": "2026-10-19T13:49:19.783606+00:00",
      "repair_preparation": {
        "additional_budget_hours_requested": 0,
        "new_fits_started": 0,
        "original_run_failure_preserved": true,
        "proposal_ref": {
          "path": "ai4s/programs/dbconformer/research/srt_r1/REPAIR_FRESH_TECH_PROPOSAL.json",
          "sha256": "6ec126b797cdcbbbe067d5dc16d93f8045faf739a4901d993d5f0934c54aedc6"
        },
        "recorded_at": "2026-10-19T15:53:19.831775+00:00",
        "requires_cumulative_fit_limit": 44,
        "status": "AWAITING_EXPLICIT_CUMULATIVE_FIT_LIMIT_44"
      },
      "round_id": "dbconformer-srt-r1",
      "run_prefix": "2026-10-19_dbconformer_srt_r1_lab10_r1",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-19T13:50:16.624891+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_srt_r1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-19T13:50:18.909057+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-19_dbconformer_srt_r1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-19T13:50:59.313965+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-19_dbconformer_srt_r1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "7feaf3388de87eb217d108ef3485117f4ec1686a14bdbe3c521d96eae163a03c",
              "execution_seconds": 28.788165807724,
              "queue_seconds": 9.189244031906128,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_srt_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-srt-r1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 37.97740983963013
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-19T15:45:18.347722+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-19_dbconformer_srt_r1_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "7feaf3388de87eb217d108ef3485117f4ec1686a14bdbe3c521d96eae163a03c",
              "execution_seconds": 1247.7862932682037,
              "queue_seconds": 9.189244031906128,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-19_dbconformer_srt_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-srt-r1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 1256.9755373001099
            }
          }
        }
      ]
    },
    {
      "automatic_retries": 0,
      "bundle_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_bundle_r2",
      "contract_metadata": "ai4s/programs/dbconformer/research/dbconformer-srt-r1-repair2.yaml",
      "contract_sha256": "c430e5f82fdf3560a56b5e5c915bbfb0daebdcd03bde913fbe952e7896005bb7",
      "dispatch_status": "REMOTE_ACCEPTED",
      "dispatch_units": 40,
      "estimated_training_hours": 14.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "fresh_training_units": 40,
      "initial_dispatch_units": 4,
      "new_scientific_units": 36,
      "new_technical_units": 4,
      "planned_unique_fit_evidence": 44,
      "planned_units": 40,
      "prior_technical_units": 4,
      "recorded_at": "2026-10-20T07:32:25.309743+00:00",
      "round_contract_path": "ai4s/programs/dbconformer/research/dbconformer-srt-r1-repair2.yaml",
      "round_id": "dbconformer-srt-r1-repair2",
      "run_prefix": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2",
      "screen_requires_smoke_technical_pass": true,
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-20T07:32:59.448129+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-20T07:33:01.880580+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-20T07:33:38.300188+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "smoke",
            "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "c430e5f82fdf3560a56b5e5c915bbfb0daebdcd03bde913fbe952e7896005bb7",
              "execution_seconds": 3.0288684368133545,
              "queue_seconds": 29.552326917648315,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1",
              "transaction_id": "dbconformer-srt-r1-repair2-tx",
              "waiting_for_resources": true,
              "wall_seconds": 32.58119535446167
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-20T07:35:57.185488+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "c430e5f82fdf3560a56b5e5c915bbfb0daebdcd03bde913fbe952e7896005bb7",
              "execution_seconds": 137.16551518440247,
              "queue_seconds": 34.314486503601074,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1",
              "transaction_id": "dbconformer-srt-r1-repair2-tx",
              "waiting_for_resources": false,
              "wall_seconds": 171.48000168800354
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-20T13:05:56.196345+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "c430e5f82fdf3560a56b5e5c915bbfb0daebdcd03bde913fbe952e7896005bb7",
              "execution_seconds": 17776.151104688644,
              "queue_seconds": 1947.2605228424072,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-20_dbconformer_srt_r1_repair2_lab10_r2-full-w1",
              "transaction_id": "dbconformer-srt-r1-repair2-tx",
              "waiting_for_resources": false,
              "wall_seconds": 19723.41162753105
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-10-21_dbconformer_bgc_r1_lab10_bundle_r1",
      "dispatch_status": "REMOTE_ACCEPTED",
      "estimated_training_hours": 14.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 40,
      "recorded_at": "2026-10-21T07:56:31.669459+00:00",
      "round_id": "dbconformer-bgc-r1",
      "run_prefix": "2026-10-21_dbconformer_bgc_r1_lab10_r1",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-21T07:56:55.742590+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-21T07:57:41.792707+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T07:57:52.859368+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "ac661fe5e1f909d017a6b6f6f917ffc2978944e60d3c1472de0e2beeaf6020d9",
              "execution_seconds": 6.038255453109741,
              "queue_seconds": 2.912031412124634,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 8.950286865234375
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T11:16:00.711586+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "ac661fe5e1f909d017a6b6f6f917ffc2978944e60d3c1472de0e2beeaf6020d9",
              "execution_seconds": 2457.087661266327,
              "queue_seconds": 2.912031412124634,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 2459.9996926784515
            }
          }
        }
      ]
    },
    {
      "automatic_retries": 0,
      "bundle_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_bundle_r1",
      "dispatch_status": "REMOTE_ACCEPTED",
      "dispatch_units": 36,
      "estimated_training_hours": 11.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "new_scientific_units": 36,
      "new_technical_units": 0,
      "planned_units": 40,
      "prior_technical_units": 4,
      "recorded_at": "2026-10-21T11:35:41.543845+00:00",
      "recovery_of": "2026-10-21_dbconformer_bgc_r1_lab10_r1-full-w1",
      "round_id": "dbconformer-bgc-r1-repair1",
      "run_prefix": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-21T11:36:06.600329+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-21T11:37:24.686508+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T11:37:35.342297+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "90f3ba923f2fe66dd28f727ea3d05e8eae1c6c73412721cef08c165198b71fea",
              "execution_seconds": 7.912842273712158,
              "queue_seconds": 0.0,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 7.912842273712158
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T11:38:33.932274+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "90f3ba923f2fe66dd28f727ea3d05e8eae1c6c73412721cef08c165198b71fea",
              "execution_seconds": 63.73872470855713,
              "queue_seconds": 2.775022506713867,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 66.513747215271
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T12:22:51.772655+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "screen",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "90f3ba923f2fe66dd28f727ea3d05e8eae1c6c73412721cef08c165198b71fea",
              "execution_seconds": 2721.6982877254486,
              "queue_seconds": 2.775022506713867,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 2724.4733102321625
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T15:31:56.842372+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "screen",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "90f3ba923f2fe66dd28f727ea3d05e8eae1c6c73412721cef08c165198b71fea",
              "execution_seconds": 5676.2141036987305,
              "queue_seconds": 8393.85088801384,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-repair1-tx",
              "waiting_for_resources": true,
              "wall_seconds": 14070.06499171257
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-21T15:34:43.587128+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "screen",
            "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "90f3ba923f2fe66dd28f727ea3d05e8eae1c6c73412721cef08c165198b71fea",
              "execution_seconds": 5676.679199934006,
              "queue_seconds": 8560.161652565002,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-21_dbconformer_bgc_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bgc-r1-repair1-tx",
              "waiting_for_resources": true,
              "wall_seconds": 14236.840852499008
            }
          }
        }
      ]
    },
    {
      "bundle_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_bundle_r1",
      "dispatch_status": "REMOTE_ACCEPTED",
      "estimated_training_hours": 6.0,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 19,
      "recorded_at": "2026-10-23T15:10:51.281796+00:00",
      "round_id": "dbconformer-svs-r1-repair1",
      "run_prefix": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-10-23T15:11:35.976627+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "launch",
          "recorded_at": "2026-10-23T15:11:38.249029+00:00",
          "result": {
            "action": "SUBMISSION_SENT_NOT_VERIFIED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1"
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-23T15:11:45.336880+00:00",
          "result": {
            "action": "WAIT_FOR_RESOURCES",
            "node_id": "smoke",
            "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "cf60743c98de5131a9838e9b27157bde4225491d97aa888442fcf08fcd6b524c",
              "execution_seconds": 2.9456350803375244,
              "queue_seconds": 2.2035248279571533,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-svs-r1-repair1-tx",
              "waiting_for_resources": true,
              "wall_seconds": 5.149159908294678
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-23T15:12:41.282319+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1",
            "status": "RUNNING",
            "timing": {
              "contract_sha256": "cf60743c98de5131a9838e9b27157bde4225491d97aa888442fcf08fcd6b524c",
              "execution_seconds": 52.18023228645325,
              "queue_seconds": 8.910121440887451,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-svs-r1-repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 61.0903537273407
            }
          }
        },
        {
          "operation": "probe",
          "recorded_at": "2026-10-23T18:03:22.881814+00:00",
          "result": {
            "action": "RECONCILE_SAME_NODE",
            "node_id": "smoke",
            "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1",
            "status": "FAILED",
            "timing": {
              "contract_sha256": "cf60743c98de5131a9838e9b27157bde4225491d97aa888442fcf08fcd6b524c",
              "execution_seconds": 512.952424287796,
              "queue_seconds": 8.910121440887451,
              "queue_time_policy": "exclude_resource_wait",
              "run_id": "2026-10-23_dbconformer_svs_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-svs-r1-repair1-tx",
              "waiting_for_resources": false,
              "wall_seconds": 521.8625457286835
            }
          }
        }
      ]
    }
  ],
  "archived_campaigns": [
    {
      "campaign_id": "dbconformer-ptsr-d0-20260921",
      "closed_at": "2026-09-22T14:53:16.688747+00:00",
      "closing_decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "interpretation_boundary": "selection-used fixed-backbone readout diagnostic only; no causal, training-utility or paper claim",
        "reason": "Frozen spatial-resolution diagnostic gates not all passed",
        "round_id": "dbconformer-ptsr-d0-r2"
      },
      "closing_round": "dbconformer-ptsr-d0-r2",
      "closing_run": {
        "artifact_manifest_sha256": "ba07c7c861aa125210c3b27a49f103c5ed88e3c7197aa976bd41e2bfd31f8bfd",
        "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
        "intake_path": "results/logs/remote/2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
        "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-ptsr-d0-r2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized next EIR-D0 round and six hours; see ai4s/programs/dbconformer/research/eir_d0/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dbconformer-eir-d0-20260922",
      "closed_at": "2026-09-23T08:09:03.287061+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_electrode_identity_only",
        "interpretation_boundary": "selection-used fixed-backbone readout diagnostic only; no causal, training-utility or paper claim",
        "reason": "Frozen electrode-identity diagnostic gates not all passed",
        "round_id": "dbconformer-eir-d0-r1-repair2"
      },
      "closing_round": "dbconformer-eir-d0-r1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "b7dd1d399158ce72a6792bc1d7bc05fb1ed3f6c405f818139b18c7c7a9ff53ff",
        "contract_sha256": "943dcdde09b8f87ef5a6f897d465847f5ea0c69a8d3c6e9c1a7f69cfbafde634",
        "intake_path": "results/logs/remote/2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
        "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-eir-d0-r1-repair2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized one next research and new six hours; see ai4s/programs/dbconformer/research/csu_d0/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dbconformer-csu-d0-20260923",
      "closed_at": "2026-09-23T13:41:45.281008+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_path_use_only",
        "interpretation_boundary": "selection-used frozen source-validation path-use diagnostic only; no causal, training-utility, generalization or paper claim",
        "reason": "Frozen conditional spatial-use gates not all passed",
        "round_id": "dbconformer-csu-d0-r1"
      },
      "closing_round": "dbconformer-csu-d0-r1",
      "closing_run": {
        "artifact_manifest_sha256": "8a071618e24d2b4a552d0d9e983da7d418212fcd19e5257cd0a64b9e20341c70",
        "contract_sha256": "508f91b98d5f32d1b0be1d4bab84be7a7a8077b8e8f9a757b3459a67cfea7ff8",
        "intake_path": "results/logs/remote/2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
        "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-csu-d0-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized TPB-D0 upload launch and one round using remaining CSU budget; see ai4s/programs/dbconformer/research/tpb_d0/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dbconformer-tpb-d0-20260923",
      "closed_at": "2026-09-23T14:55:40.840897+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_temporal_position_binding_only",
        "interpretation_boundary": "selection-used frozen source-validation temporal position-binding diagnostic only; no causal, training-utility, generalization or paper claim",
        "reason": "Frozen temporal position-binding gates passed",
        "round_id": "dbconformer-tpb-d0-r1"
      },
      "closing_round": "dbconformer-tpb-d0-r1",
      "closing_run": {
        "artifact_manifest_sha256": "b587c0f4633eba1f35e3a9f3449165b0dec5ba98bc30f4935b03008e441fa887",
        "contract_sha256": "4de87a8c1a4fe9fca7d0abac8875a385bf58d04b6c6c697ecaba81b3412acc0c",
        "intake_path": "results/logs/remote/2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
        "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-tpb-d0-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized BPC-R1 launch and new 6 hours for one round; see ai4s/programs/dbconformer/research/bpc_r1/AUTHORIZATION.md"
    },
    {
      "campaign_id": "dbconformer-bpc-r1-20260923",
      "closed_at": "2026-09-23T16:22:39.001451+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_CALIBRATION_SUPPORT",
        "evidence_scope": "frozen_backbone_source_calibration_only",
        "gates": {
          "accuracy": false,
          "b0": false,
          "comparators": false,
          "shuffle": false
        },
        "interpretation_boundary": "selection-used source-valid calibration screen; no independent confirmation or causal timing claim",
        "reason": "Frozen BPC-R1 gates not all passed",
        "round_id": "dbconformer-bpc-r1"
      },
      "closing_round": "dbconformer-bpc-r1",
      "closing_run": {
        "artifact_manifest_sha256": "23c7bf17a9cd9c544d339f492637f239543be12680462518c74fba16d2e47be9",
        "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
        "intake_path": "results/logs/remote/2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
        "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bpc-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests one next automatic research round and explicitly selects new six hours; start request 2026-09-23T16:17:35.624Z, budget confirmed 16:17:57.927Z. Scientific selection pending, no Run authorized by this command."
    },
    {
      "campaign_id": "dbconformer-next-20260924",
      "closed_at": "2026-09-23T17:13:25.493991+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_slot_moment_corrected_binding_only",
        "interpretation_boundary": "slot-moment corrected source-valid diagnostic; ratio/center attenuation are descriptive only",
        "reason": "Frozen SMP gates passed",
        "round_id": "dbconformer-smp-d0-r1"
      },
      "closing_round": "dbconformer-smp-d0-r1",
      "closing_run": {
        "artifact_manifest_sha256": "cc21743c6372bfb16d2c8f9b3c1413536185781d57f43b6c4d54c297752dd6d6",
        "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-smp-d0-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests one next research using SMP diagnostic evidence and explicitly chooses previous closed balance 5.183858183611111 hours; no new six-hour allocation; research request at 2026-09-23T17:09:40.228Z. Scientific selection pending."
    },
    {
      "campaign_id": "dbconformer-next-20260924b",
      "closed_at": "2026-09-24T01:31:46.411221+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_paired_slot_distance_only",
        "gates": {
          "difference": true,
          "far": true,
          "loo": true,
          "seeds": true,
          "subjects": true
        },
        "interpretation_boundary": "fixed endpoint-balanced near/far pairing comparison on selection-used source-valid; pair identity and perturbation magnitude confounded; no causal distance or training-utility claim",
        "reason": "Frozen PDX gates passed",
        "round_id": "dbconformer-pdx-d0-r1"
      },
      "closing_round": "dbconformer-pdx-d0-r1",
      "closing_run": {
        "artifact_manifest_sha256": "4504e145f8eec838105def7718f3abeea1d340ad9ab0b2c05adac4950137ee65",
        "contract_sha256": "654e6c6fa137e6734d4a8c26521a32c7c8fd4f276c88ca379f9d3052be5978ba",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-pdx-d0-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests next research using diagnostic evidence and explicitly carries the closed PDX remaining 4.105478948888888 hours for one round. Request 2026-09-24T01:27:21.259Z; budget reply 01:30:10.151Z."
    },
    {
      "campaign_id": "dbconformer-dra-r1-20260924",
      "closed_at": "2026-09-24T06:09:58.060452+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_DISTANCE_ADAPTATION_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_distance_attention_adaptation_only",
        "gates": {
          "accuracy": true,
          "b0": false,
          "comparators": false
        },
        "interpretation_boundary": "selection-used source-valid frozen-checkpoint adaptation screen; no independent confirmation or target claim",
        "reason": "Frozen DRA-R1 gates not all passed",
        "round_id": "dbconformer-dra-r1"
      },
      "closing_round": "dbconformer-dra-r1",
      "closing_run": {
        "artifact_manifest_sha256": "bb529da99ced994006020701d28554f28d8c7649769e98ea620998bfca2b9788",
        "contract_sha256": "e536a8b1f76dbca132a7cd56f433e4f95a7b43530ef16f819d669998d164adfc",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-dra-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requests automatic design and execution of next research and selects new six hours, one round. Prior DRA-R1 verified and closed; no rescue of its exact negative. Select next question from accumulated evidence."
    },
    {
      "campaign_id": "dbconformer-next-20260924c",
      "closed_at": "2026-09-24T07:36:50.533338+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_PROJECTION_ADAPTATION_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_attention_projection_adaptation_only",
        "gates": {
          "accuracy": true,
          "b0": true,
          "comparators": false
        },
        "interpretation_boundary": "selection-used source-valid frozen-checkpoint adaptation screen; no independent confirmation or target claim",
        "reason": "Frozen APR-R1 gates not all passed",
        "round_id": "dbconformer-apr-r1"
      },
      "closing_round": "dbconformer-apr-r1",
      "closing_run": {
        "artifact_manifest_sha256": "b087e30c62f507c516257c789f37ac80f0396c76db287bad87aa80d646019d84",
        "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-apr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests automatic next-round research and explicitly selects new six-hour single-round budget. NDD-D0 uses verified sealed APR logits for norm-direction output diagnosis; no new model training or target evaluation; preserve APR closed boundary."
    },
    {
      "campaign_id": "dbconformer-next-20260924d",
      "closed_at": "2026-09-24T13:19:02.592832+00:00",
      "closing_decision": {
        "arm_summaries": {
          "C0": {
            "category_fractions": {
              "correct": 0.721743295019157,
              "corrected": 0.033345306513409965,
              "harmed": 0.03190852490421456,
              "unchanged_wrong": 0.19821599616858238,
              "wrong_to_wrong": 0.014786877394636015
            },
            "category_gain_contributions": {
              "correct": 0.04496404284624812,
              "corrected": 0.015296033266553717,
              "harmed": -0.012625747992145182,
              "unchanged_wrong": -0.037237354115176625,
              "wrong_to_wrong": -0.0010819369382228678
            },
            "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
            "direction_group_means": [
              0.015319715387603974,
              0.018188600200102902,
              0.014708158979337367,
              0.028896659724878836,
              0.008267505257982068,
              0.003133319282539702,
              0.015552067932655218,
              0.011178604947452311,
              0.006519413785532297
            ],
            "direction_loo_min": 0.01160842322165073,
            "interaction": -0.0018264612583647616,
            "phi_direction": 0.013529338388676074,
            "phi_norm": -0.004214301321418917,
            "seed_summary": [
              {
                "phi_direction": 0.018272933553320582,
                "phi_norm": -0.005776079468577329,
                "total_gain": 0.012496854084743249
              },
              {
                "phi_direction": 0.008785743224031568,
                "phi_norm": -0.002652523174260504,
                "total_gain": 0.006133220049771067
              }
            ],
            "total_gain": 0.00931503706725716,
            "unchanged_argmax_fraction": 0.9199592911877394
          },
          "G0": {
            "category_fractions": {
              "correct": 0.7243773946360155,
              "corrected": 0.03148946360153257,
              "harmed": 0.029274425287356323,
              "unchanged_wrong": 0.19989224137931036,
              "wrong_to_wrong": 0.014966475095785439
            },
            "category_gain_contributions": {
              "correct": 0.0397038733720918,
              "corrected": 0.013401637023210846,
              "harmed": -0.010649140941438685,
              "unchanged_wrong": -0.03333111629468323,
              "wrong_to_wrong": -0.001369085293470876
            },
            "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
            "direction_group_means": [
              0.014413363991003724,
              0.024894765312092303,
              0.004785852723165713,
              0.022538955611644,
              0.0099610343496279,
              0.006265349504414692,
              0.010338089928123618,
              0.007902804462291609,
              -0.0014376504361890347
            ],
            "direction_loo_min": 0.009345975016760277,
            "interaction": -0.0010008331337003134,
            "phi_direction": 0.011073618382908277,
            "phi_norm": -0.0033174505171984217,
            "seed_summary": [
              {
                "phi_direction": 0.01723690866458428,
                "phi_norm": -0.004024359239083457,
                "total_gain": 0.013212549425500823
              },
              {
                "phi_direction": 0.0049103281012322815,
                "phi_norm": -0.0026105417953133873,
                "total_gain": 0.0022997863059188942
              }
            ],
            "total_gain": 0.007756167865709859,
            "unchanged_argmax_fraction": 0.9242696360153256
          },
          "P1": {
            "category_fractions": {
              "correct": 0.726352969348659,
              "corrected": 0.027538314176245207,
              "harmed": 0.027298850574712638,
              "unchanged_wrong": 0.20575909961685823,
              "wrong_to_wrong": 0.013050766283524905
            },
            "category_gain_contributions": {
              "correct": 0.02081759950115886,
              "corrected": 0.009755338155056087,
              "harmed": -0.008174808125928593,
              "unchanged_wrong": -0.010610747887520882,
              "wrong_to_wrong": 2.85540418911167e-05
            },
            "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
            "direction_group_means": [
              0.009324928157310433,
              0.024360751040422915,
              0.006380441836903754,
              0.012349172200690093,
              0.01094029717810787,
              0.007208903720000682,
              0.009926553784130548,
              0.00647245697862329,
              -0.0007832318639749341
            ],
            "direction_loo_min": 0.007727440248973967,
            "interaction": 0.0003195898842810556,
            "phi_direction": 0.009575585892468295,
            "phi_norm": 0.002240349792188295,
            "seed_summary": [
              {
                "phi_direction": 0.011870715350658347,
                "phi_norm": 0.0019499782165673515,
                "total_gain": 0.013820693567225699
              },
              {
                "phi_direction": 0.0072804564342782395,
                "phi_norm": 0.0025307213678092376,
                "total_gain": 0.009811177802087477
              }
            ],
            "total_gain": 0.01181593568465659,
            "unchanged_argmax_fraction": 0.9321120689655172
          }
        },
        "claim_release": false,
        "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
        "interpretation_boundary": "Repeatedly selection-used source-valid centered-logit two-order attribution only; no calibration, network causal mechanism, target generalization or candidate promotion.",
        "primary_arm": "P1",
        "round_id": "dbconformer-ndd-d0"
      },
      "closing_round": "dbconformer-ndd-d0",
      "closing_run": {
        "artifact_manifest_sha256": "b087e30c62f507c516257c789f37ac80f0396c76db287bad87aa80d646019d84",
        "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-apr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorizes automatic design and execution of one next research round, explicitly permitting a new trainable direction rather than diagnostics only; carries forward NDD-D0 settled remainder 5.72295531 hours. Preserve all prior exact closures and selection exposure. No automatic second round."
    },
    {
      "campaign_id": "dbconformer-next-20260924e",
      "closed_at": "2026-09-24T15:21:12.522387+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_TEMPORAL_MOMENT_READOUT_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_temporal_moment_readout_only",
        "gates": {
          "b0": false,
          "comparators": false,
          "harm": false
        },
        "interpretation_boundary": "Selection-used overlapping source validation; no independent confirmation, novelty, target generalization or automatic next round.",
        "reason": "Frozen accuracy and harm gates not all passed",
        "round_id": "dbconformer-tmr-r1"
      },
      "closing_round": "dbconformer-tmr-r1",
      "closing_run": {
        "artifact_manifest_sha256": "d88792e3e99ec9f4de601e4b84a4aadb75aa0128996b5fec73ce4f9445cd3b68",
        "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-tmr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorizes automatic design and execution of one next research round, permits new trainable directions beyond diagnostics, and explicitly carries forward TMR-R1 settled remaining 4.1776342425 hours. Preserve prior exact closures and source selection exposure; no automatic second round. Zero automatic training retries; allow read-only forensics, same-Run transport recovery and post-intake bookkeeping repair within budget."
    },
    {
      "campaign_id": "dbconformer-next-20260924f",
      "closed_at": "2026-09-24T16:06:34.808419+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_CROSS_BRANCH_READOUT_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_cross_branch_readout_only",
        "gates": {
          "b0": false,
          "comparators": false,
          "harm": false
        },
        "interpretation_boundary": "Selection-used overlapping source validation; no independent confirmation, novelty, target generalization or automatic next round.",
        "reason": "Frozen accuracy and harm gates not all passed",
        "round_id": "dbconformer-cbr-r1"
      },
      "closing_round": "dbconformer-cbr-r1",
      "closing_run": {
        "artifact_manifest_sha256": "c5fe181ae1c18f90fb85aa45f5ef6fd2e0dd2219979acfbf2446be9be00abb7d",
        "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
        "intake_path": "results/logs/remote/2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
        "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-cbr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests automatic design and execution of one next research round and explicitly carries forward CBR-R1 settled remaining 3.510813297222222 hours. Preserve all historical exact closures and selection exposure. Lab10 same executor; no automatic second round or training retries. Allow read-only forensics, same-Run transport recovery and post-intake bookkeeping repair within budget."
    },
    {
      "campaign_id": "dbconformer-next-20260925a",
      "closed_at": "2026-09-24T18:39:09.842847+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_NUISANCE_READOUT_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_source_nuisance_readout_only",
        "gates": {
          "b0": false,
          "comparators": false,
          "harm": true
        },
        "interpretation_boundary": "Selection-used overlapping source validation; no independent confirmation, novelty, target generalization or automatic next round.",
        "reason": "Frozen accuracy and harm gates not all passed",
        "round_id": "dbconformer-snr-r1"
      },
      "closing_round": "dbconformer-snr-r1",
      "closing_run": {
        "artifact_manifest_sha256": "4e0009fc10a4b5abf21b94779b41db3d0755d0be63fd5bb67c3228eef9e9b870",
        "contract_sha256": "b9999de1d1266d8ffa53a8e8bba0b6021e3b4fd02a8ce1d6b3e53d5c51d97daf",
        "intake_path": "results/logs/remote/2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
        "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-snr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requests AI4S v3.0 next research round, selects new six hours only one round, and adds automatic authorization and experiment push. Scope includes local design/implementation/technical acceptance and upload of the frozen round runtime code/config/splits/checkpoints or necessary derived data to existing Lab10 executor via [REDACTED_MACHINE], launch/probe/fetch/intake/analysis. Prefer paired joint architecture training; preserve historical closures, data semantics and selection exposure. No automatic second round or training retries; allow same-Run transport recovery and non-scientific closeout repairs within six hours."
    },
    {
      "campaign_id": "dbconformer-v3-20260925b",
      "closed_at": "2026-09-25T02:38:35.971758+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training",
        "gates": {
          "both_seeds": false,
          "mean": false,
          "robustness": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects; no mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-bpm-r1"
      },
      "closing_round": "dbconformer-bpm-r1",
      "closing_run": {
        "artifact_manifest_sha256": "2d72d91caacec46c08bf68c4440a9dcd2e7bb49494b0ece218202aa4a43ee995",
        "contract_sha256": "b44e6306269baef4fe31c3a2cb89f9aa0d7914151db13ee76b65462eff536235",
        "intake_path": "results/logs/remote/2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
        "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bpm-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requests next automatic AI4S v3.0 research and selects new six hours only one round. Prior automatic authorization and experiment push preference applies to this bounded next round. Includes design, implementation, technical acceptance, immutable upload and launch to registered Lab10, same-Run monitor/fetch/verify/intake/analysis; no automatic second round, no training retries, no widening historical closed scientific objects."
    },
    {
      "campaign_id": "dbconformer-v3-20260925c",
      "closed_at": "2026-09-26T08:42:25.220690+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training",
        "gates": {
          "both_seeds": false,
          "mean": false,
          "robustness": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects; no mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-hds-r1-repair3"
      },
      "closing_round": "dbconformer-hds-r1-repair3",
      "closing_run": {
        "artifact_manifest_sha256": "8e039b42ea5687538c57e4e4eb0e6872af0fef1913fbb65ceae4772e483f619c",
        "contract_sha256": "7b0c4fe2f2a32c7ebb5d22bca456f5dab17dab0f60474546ff3ef0d0aadda12b",
        "intake_path": "results/logs/remote/2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
        "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-hds-r1-repair3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized next automatic research and fresh six-hour single-round budget; retain complete HDS negative boundary and prior exposure."
    },
    {
      "campaign_id": "dbconformer-v3-20260926-sve",
      "closed_at": "2026-09-26T15:39:13.962394+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training_single_seed",
        "gates": {
          "mean": false,
          "robustness": false,
          "single_seed_positive": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; no cross-seed stability, mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-sve-r1-repair1"
      },
      "closing_round": "dbconformer-sve-r1-repair1",
      "closing_run": {
        "artifact_manifest_sha256": "6f72e2fb6bdd8d947f8520436a4443d0c12558f3d55da30ab63b30c6a974cb36",
        "contract_sha256": "280962add6452a78b08c684bb44a5b4a4df6af79cd58810f89edf42c936e29bd",
        "intake_path": "results/logs/remote/2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
        "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-sve-r1-repair1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests next research and explicitly grants fresh six hours one round; automatic upload and launch authorization persists. Test training-only branch stochastic dropout against fresh original B0."
    },
    {
      "campaign_id": "dbconformer-v3-20260926-bsd",
      "closed_at": "2026-09-27T08:31:26.823367+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training_single_seed",
        "gates": {
          "mean": false,
          "robustness": false,
          "single_seed_positive": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; no cross-seed stability, mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-bsd-r1-repair1"
      },
      "closing_round": "dbconformer-bsd-r1-repair1",
      "closing_run": {
        "artifact_manifest_sha256": "0c62695643ef144d3c1738cb79a907da39f3754f7c39beaafb859511138d0398",
        "contract_sha256": "b60f49dff90759b63d9f860ccebed3febe489206e3b163d88cd0c8c5bbbf3497",
        "intake_path": "results/logs/remote/2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
        "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bsd-r1-repair1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests next research and grants fresh six hours one round; persistent automatic upload and launch authorization. Read prior exact negative boundaries and prepare one paired structural screen."
    },
    {
      "campaign_id": "dbconformer-v3-20260927-sdt",
      "closed_at": "2026-09-27T15:31:52.445260+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training_single_seed",
        "gates": {
          "mean": false,
          "robustness": false,
          "single_seed_positive": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; no cross-seed stability, mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-sdt-r1"
      },
      "closing_round": "dbconformer-sdt-r1",
      "closing_run": {
        "artifact_manifest_sha256": "58b2d2c836fa484d8606732303223a5ad72c112e776fd70cd17a4dfbd9500942",
        "contract_sha256": "0d759dd45f74091604c713cf9eaa8150836b9f03ae35050efe471a5615a8385c",
        "intake_path": "results/logs/remote/2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
        "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-sdt-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requests next research and explicitly grants fresh six hours one round. Explore fixed single-electrode dropout training against fresh B0 with exhaustive missing-electrode evaluation and clean accuracy guard; prior exact objects remain closed; automatic upload/start authorization persists."
    },
    {
      "campaign_id": "dbconformer-v3-20260927-edr",
      "closed_at": "2026-09-28T14:11:25.521111+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_electrode_robustness_single_seed",
        "gates": {
          "baseline_sensitivity": true,
          "clean_preserved": true,
          "clean_subject_safeguard": false,
          "robust_mean": true,
          "robust_stability": true,
          "single_seed_positive": true,
          "subjects": true
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; 22 dependent zero-electrode views, no real hardware robustness, cross-seed stability, novelty, mechanism attribution, independent confirmation, or automatic next round.",
        "reason": "Frozen electrode robustness and clean protection gates evaluated",
        "round_id": "dbconformer-edr-r1"
      },
      "closing_round": "dbconformer-edr-r1",
      "closing_run": {
        "artifact_manifest_sha256": "054bb2cad2ba3ebdd38b62288260c6ecabbfec956e44f9b3464d44e00f53c90b",
        "contract_sha256": "e2e1993e7baa6940b599671fa56c21ae5b22b95063364452ac5b5f0197e5392c",
        "intake_path": "results/logs/remote/2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
        "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-edr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly requests a next research round on clean-specific information and missing-channel redundancy, grants fresh six hours one round. Prepare fresh B0, mixed clean/masked shared-normalization M0 and condition-specific BN-statistics P1; preserve prior EDR closure and no automatic further round."
    },
    {
      "campaign_id": "dbconformer-v3-20260928-cmn",
      "closed_at": "2026-09-29T08:11:56.668785+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "disposition": "CLOSE_BOTH_EXACT_OBJECTS",
        "evidence_scope": "exploratory_cue_aligned_loso_clean_missing_normalization_single_seed",
        "gates": {
          "M0_utility": {
            "baseline_sensitivity": true,
            "clean_coverage": false,
            "clean_mean": true,
            "clean_subject_safeguard": false,
            "robust_mean": true,
            "robust_stability": true,
            "robust_subjects": true
          },
          "P1_utility": {
            "baseline_sensitivity": true,
            "clean_coverage": false,
            "clean_mean": true,
            "clean_subject_safeguard": false,
            "robust_mean": true,
            "robust_stability": true,
            "robust_subjects": true
          },
          "normalization_increment": {
            "clean_mean": false,
            "clean_stability": false,
            "clean_subjects": false,
            "robust_noninferiority": false
          }
        },
        "interpretation_boundary": "Exploratory9subjects seed0 and22dependentviews; known missingness metadata; no information-loss theorem, mechanism proof, cross-seed claim or automatic next round. P1 wrong-bank clean view describes same-weight inference-statistics effect only.",
        "reason": "Prospective clean preservation, robustness and conditional-normalization increment gates evaluated",
        "round_id": "dbconformer-cmn-r1-repair1"
      },
      "closing_round": "dbconformer-cmn-r1-repair1",
      "closing_run": {
        "artifact_manifest_sha256": "7819d8be7a5475feecf5f89eef1b8c4c78860940ea90179cb2463fe9bfc229bc",
        "contract_sha256": "9dd1413561e6c18a5b10972a4eacd116dc74dd2a19cf90fba79b776effac4de2",
        "intake_path": "results/logs/remote/2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
        "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-cmn-r1-repair1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User confirmed fresh six hours one CPA-R1 round on 2026-09-29; frozen clean B0 anchors plus missing-only matched spatial adapters U0/P1,18science2smoke. Existing automatic upload launch authorization retained; no further round."
    },
    {
      "campaign_id": "dbconformer-v3-20260929-cpa",
      "closed_at": "2026-09-30T05:24:56.094991+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INVALID",
        "reason": "CPA evidence/integrity closure failed",
        "round_id": "dbconformer-cpa-r1"
      },
      "closing_round": "dbconformer-cpa-r1",
      "closing_run": {
        "artifact_manifest_sha256": "fdcff8d4be74f9033362cc772dc3a791fa0c338a5c1a2e841ea6536d7d73f898",
        "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
        "intake_path": "results/logs/remote/2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
        "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-cpa-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly selected 6 hours for one CPA-U0-R2 round; prior autonomous design upload launch authorization applies. Fixed seed0 B0 anchors and unchanged U0, fresh adapter seeds1/2,18science2smoke. Recovery separately accepted; original CPA INVALID preserved. No further round."
    },
    {
      "campaign_id": "dbconformer-v3-20260930-cpa-u0-r2",
      "closed_at": "2026-10-03T10:15:31.081264+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "CPA_U0_ADAPTER_SEED_STABILITY_SUPPORT",
        "interpretation_boundary": "9 subjects are the statistical units; two adapter seeds are repeated training, seed0 is descriptive only and never pooled to rescue a failure.",
        "reason": "both fresh-seed gates and subject-wise fresh-seed-average gate evaluated",
        "round_id": "dbconformer-cpa-u0-r2-packagefix3",
        "utility_gates": {
          "seed1": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.347892992424242,
                7.350852272727273
              ],
              [
                7.289693813131313,
                7.292653093434344
              ],
              [
                5.749881628787881,
                5.751854482323234
              ],
              [
                6.90893308080808,
                6.910905934343435
              ],
              [
                7.302517361111111,
                7.305476641414142
              ],
              [
                6.604127209595959,
                6.606100063131314
              ],
              [
                6.737294823232323,
                6.740254103535354
              ],
              [
                7.353811553030304,
                7.356770833333335
              ],
              [
                7.710898042929292,
                7.7138573232323235
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.00056116722784,
              "positive_subjects": 9,
              "worst_subject": 1.3178661616161662
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          },
          "seed2": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.449494949494949,
                7.451467803030303
              ],
              [
                7.39425505050505,
                7.396227904040404
              ],
              [
                6.0625789141414135,
                6.064551767676767
              ],
              [
                7.091422032828281,
                7.093394886363635
              ],
              [
                7.53728693181818,
                7.539259785353534
              ],
              [
                6.9296480429292915,
                6.931620896464645
              ],
              [
                6.717566287878785,
                6.718552714646463
              ],
              [
                7.351838699494948,
                7.353811553030302
              ],
              [
                7.930871212121212,
                7.931857638888888
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.163650392817065,
              "positive_subjects": 9,
              "worst_subject": 1.025883838383841
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          },
          "subject_wise_fresh_seed_mean": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.398693970959596,
                7.401160037878787
              ],
              [
                7.3419744318181825,
                7.344440498737374
              ],
              [
                5.906230271464648,
                5.908203125
              ],
              [
                7.000177556818182,
                7.002150410353535
              ],
              [
                7.419902146464646,
                7.422368213383837
              ],
              [
                6.766887626262626,
                6.768860479797979
              ],
              [
                6.7274305555555545,
                6.729403409090908
              ],
              [
                7.352825126262627,
                7.355291193181818
              ],
              [
                7.820884627525253,
                7.8228574810606055
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.082105780022453,
              "positive_subjects": 9,
              "worst_subject": 1.1718750000000036
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          }
        }
      },
      "closing_round": "dbconformer-cpa-u0-r2-packagefix3",
      "closing_run": {
        "artifact_manifest_sha256": "1a160b40e8decfe88885d460bc74ea0de5fe30b10d2615755543c53d1dad80f1",
        "contract_sha256": "b8b7793d437ae6843dde84d51ad48651af3c12928c6880c39a8fe7385c353aec",
        "intake_path": "results/logs/remote/2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
        "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-cpa-u0-r2-packagefix3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested independent B0 backbone performance and backbone-dependence study, and explicitly selected new six hours for one round. Fixed nine original source splits; B0 seeds1/2, unchanged U0 adapter seed1 paired to every new B0. No target-based anchor exclusion or next round."
    },
    {
      "campaign_id": "dbconformer-v3-20261003-bda-r1",
      "closed_at": "2026-10-04T09:10:18.766796+00:00",
      "closing_decision": {
        "b0_absolute_performance": {
          "n_fits": 18,
          "n_subjects": 9,
          "rows": [
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "3cb3f362924f053537c7f1278f331860d83f97cfbb56c4d894bde9f0fef7a0a4",
              "difference_vs_seed0_clean_pp": -1.2152777777777786,
              "difference_vs_seed0_missing_pp": -0.3314393939393909,
              "historical_seed0_clean_acc_pp": 62.15277777777778,
              "historical_seed0_missing_acc_pp": 48.07449494949494,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 78.23275862068965,
              "subject": 0,
              "target_clean_acc_pp": 60.9375,
              "target_missing_acc_pp": 47.74305555555555,
              "target_missing_per_channel_acc_pp": [
                56.25,
                54.6875,
                56.770833333333336,
                59.02777777777778,
                56.423611111111114,
                46.875,
                60.06944444444444,
                28.47222222222222,
                45.3125,
                38.88888888888889,
                51.90972222222222,
                48.95833333333333,
                52.43055555555556,
                33.50694444444444,
                53.47222222222222,
                33.15972222222222,
                46.875,
                46.52777777777778,
                37.15277777777778,
                59.375,
                42.1875,
                42.01388888888889
              ],
              "task_id": "B0_s0_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "bf2d5a11c1abc85427a00a8ce981a9c37c80249e29c4e095f27e0efa3fb11f15",
              "difference_vs_seed0_clean_pp": -2.256944444444443,
              "difference_vs_seed0_missing_pp": 0.4419191919191974,
              "historical_seed0_clean_acc_pp": 62.15277777777778,
              "historical_seed0_missing_acc_pp": 48.07449494949494,
              "source_valid_best_epoch": 89,
              "source_valid_clean_acc_pp": 78.125,
              "subject": 0,
              "target_clean_acc_pp": 59.895833333333336,
              "target_missing_acc_pp": 48.51641414141414,
              "target_missing_per_channel_acc_pp": [
                57.8125,
                55.208333333333336,
                57.986111111111114,
                55.03472222222222,
                55.729166666666664,
                46.875,
                58.15972222222222,
                27.77777777777778,
                48.78472222222222,
                37.84722222222222,
                58.68055555555556,
                45.65972222222222,
                58.68055555555556,
                36.45833333333333,
                59.201388888888886,
                43.40277777777778,
                43.22916666666667,
                48.61111111111111,
                45.48611111111111,
                49.82638888888889,
                42.53472222222222,
                34.375
              ],
              "task_id": "B0_s0_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "a941537ccff0ebbffd3773550b14d6466a43329fa1bc71667328debb81c8c531",
              "difference_vs_seed0_clean_pp": -0.6944444444444429,
              "difference_vs_seed0_missing_pp": 0.6313131313131315,
              "historical_seed0_clean_acc_pp": 42.88194444444444,
              "historical_seed0_missing_acc_pp": 31.723484848484848,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 82.11206896551724,
              "subject": 1,
              "target_clean_acc_pp": 42.1875,
              "target_missing_acc_pp": 32.35479797979798,
              "target_missing_per_channel_acc_pp": [
                35.59027777777778,
                31.25,
                31.944444444444443,
                40.10416666666667,
                35.9375,
                37.84722222222222,
                37.84722222222222,
                37.15277777777778,
                30.90277777777778,
                28.125,
                30.729166666666668,
                34.54861111111111,
                35.41666666666667,
                25.17361111111111,
                31.07638888888889,
                31.770833333333332,
                25.0,
                25.694444444444443,
                28.819444444444443,
                40.10416666666667,
                26.041666666666668,
                30.729166666666668
              ],
              "task_id": "B0_s1_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "b6e915b22d74eeef22c7c26ae6f41fdea8cb0af80b88dfa6918b96191b4e6dd2",
              "difference_vs_seed0_clean_pp": -1.2152777777777715,
              "difference_vs_seed0_missing_pp": -0.2840909090909136,
              "historical_seed0_clean_acc_pp": 42.88194444444444,
              "historical_seed0_missing_acc_pp": 31.723484848484848,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 82.86637931034483,
              "subject": 1,
              "target_clean_acc_pp": 41.66666666666667,
              "target_missing_acc_pp": 31.439393939393934,
              "target_missing_per_channel_acc_pp": [
                34.02777777777778,
                33.50694444444444,
                40.10416666666667,
                33.33333333333333,
                32.29166666666667,
                27.604166666666668,
                30.208333333333332,
                31.944444444444443,
                31.42361111111111,
                24.479166666666664,
                37.84722222222222,
                34.54861111111111,
                37.67361111111111,
                25.520833333333332,
                33.33333333333333,
                25.0,
                30.03472222222222,
                26.5625,
                26.90972222222222,
                37.5,
                26.5625,
                31.25
              ],
              "task_id": "B0_s1_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "459a3377d0fed180b12cf708a364fecc91d144de74e57a49cc5bdd2920c58387",
              "difference_vs_seed0_clean_pp": -1.5625,
              "difference_vs_seed0_missing_pp": 2.3674242424242493,
              "historical_seed0_clean_acc_pp": 81.07638888888889,
              "historical_seed0_missing_acc_pp": 57.930871212121204,
              "source_valid_best_epoch": 96,
              "source_valid_clean_acc_pp": 77.37068965517241,
              "subject": 2,
              "target_clean_acc_pp": 79.51388888888889,
              "target_missing_acc_pp": 60.29829545454545,
              "target_missing_per_channel_acc_pp": [
                73.4375,
                65.97222222222221,
                78.29861111111111,
                79.34027777777779,
                71.875,
                81.59722222222221,
                55.38194444444444,
                44.27083333333333,
                63.541666666666664,
                41.84027777777778,
                75.52083333333334,
                64.40972222222221,
                80.90277777777779,
                40.79861111111111,
                68.75,
                45.3125,
                49.65277777777778,
                57.638888888888886,
                45.48611111111111,
                53.125,
                42.53472222222222,
                46.875
              ],
              "task_id": "B0_s2_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "0817f219b8ce3e81c3977984c4dea417245203f214f1144ea773a209e4e57838",
              "difference_vs_seed0_clean_pp": 1.3888888888889,
              "difference_vs_seed0_missing_pp": -0.3472222222222143,
              "historical_seed0_clean_acc_pp": 81.07638888888889,
              "historical_seed0_missing_acc_pp": 57.930871212121204,
              "source_valid_best_epoch": 89,
              "source_valid_clean_acc_pp": 75.86206896551724,
              "subject": 2,
              "target_clean_acc_pp": 82.46527777777779,
              "target_missing_acc_pp": 57.58364898989899,
              "target_missing_per_channel_acc_pp": [
                79.16666666666666,
                63.541666666666664,
                82.46527777777779,
                74.13194444444444,
                76.73611111111111,
                76.5625,
                49.30555555555556,
                39.40972222222222,
                52.604166666666664,
                45.65972222222222,
                64.0625,
                63.541666666666664,
                82.46527777777779,
                30.555555555555557,
                64.0625,
                47.91666666666667,
                47.74305555555556,
                40.79861111111111,
                32.63888888888889,
                59.72222222222222,
                40.45138888888889,
                53.298611111111114
              ],
              "task_id": "B0_s2_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "4aea046c5051a104f0bc6d1166c777722eaa92269ce31f0a3948e060960d2e08",
              "difference_vs_seed0_clean_pp": 1.3888888888888928,
              "difference_vs_seed0_missing_pp": -0.38667929292930125,
              "historical_seed0_clean_acc_pp": 50.34722222222222,
              "historical_seed0_missing_acc_pp": 38.99147727272727,
              "source_valid_best_epoch": 91,
              "source_valid_clean_acc_pp": 79.84913793103449,
              "subject": 3,
              "target_clean_acc_pp": 51.736111111111114,
              "target_missing_acc_pp": 38.60479797979797,
              "target_missing_per_channel_acc_pp": [
                46.875,
                45.83333333333333,
                50.69444444444444,
                43.57638888888889,
                44.44444444444444,
                39.0625,
                44.27083333333333,
                27.430555555555557,
                33.85416666666667,
                34.375,
                40.27777777777778,
                31.25,
                47.74305555555556,
                27.77777777777778,
                47.56944444444444,
                44.61805555555556,
                27.604166666666668,
                37.5,
                26.041666666666668,
                53.81944444444444,
                25.520833333333332,
                29.166666666666668
              ],
              "task_id": "B0_s3_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "4959383f762e094f21b93bcbf657d3f7da48930928d566f2e8c497ce289212ea",
              "difference_vs_seed0_clean_pp": -3.2986111111111143,
              "difference_vs_seed0_missing_pp": -2.012310606060602,
              "historical_seed0_clean_acc_pp": 50.34722222222222,
              "historical_seed0_missing_acc_pp": 38.99147727272727,
              "source_valid_best_epoch": 92,
              "source_valid_clean_acc_pp": 80.60344827586206,
              "subject": 3,
              "target_clean_acc_pp": 47.04861111111111,
              "target_missing_acc_pp": 36.97916666666667,
              "target_missing_per_channel_acc_pp": [
                43.75,
                39.0625,
                43.40277777777778,
                47.04861111111111,
                41.49305555555556,
                36.11111111111111,
                41.14583333333333,
                26.73611111111111,
                37.15277777777778,
                33.68055555555556,
                37.15277777777778,
                29.86111111111111,
                43.75,
                30.03472222222222,
                46.35416666666667,
                42.88194444444444,
                34.20138888888889,
                38.54166666666667,
                25.520833333333332,
                42.01388888888889,
                28.645833333333332,
                25.0
              ],
              "task_id": "B0_s3_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "c4627c2430e5889278c43e3c1027d739cb5d7a83b925726609ddb74ba95b5001",
              "difference_vs_seed0_clean_pp": -1.0416666666666572,
              "difference_vs_seed0_missing_pp": 1.2468434343434325,
              "historical_seed0_clean_acc_pp": 44.27083333333333,
              "historical_seed0_missing_acc_pp": 34.540719696969695,
              "source_valid_best_epoch": 86,
              "source_valid_clean_acc_pp": 81.46551724137932,
              "subject": 4,
              "target_clean_acc_pp": 43.22916666666667,
              "target_missing_acc_pp": 35.78756313131313,
              "target_missing_per_channel_acc_pp": [
                42.88194444444444,
                28.819444444444443,
                44.09722222222222,
                43.57638888888889,
                26.21527777777778,
                29.166666666666668,
                42.01388888888889,
                44.44444444444444,
                39.93055555555556,
                34.54861111111111,
                35.41666666666667,
                27.256944444444443,
                31.07638888888889,
                25.868055555555557,
                36.80555555555556,
                36.63194444444444,
                28.47222222222222,
                35.76388888888889,
                25.0,
                51.388888888888886,
                26.90972222222222,
                51.041666666666664
              ],
              "task_id": "B0_s4_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "180fdc7bde7efd4ac1ec2c39000da067cf434bd4f48681c7f316a8a37a51eeae",
              "difference_vs_seed0_clean_pp": -0.86805555555555,
              "difference_vs_seed0_missing_pp": 0.09469696969696173,
              "historical_seed0_clean_acc_pp": 44.27083333333333,
              "historical_seed0_missing_acc_pp": 34.540719696969695,
              "source_valid_best_epoch": 100,
              "source_valid_clean_acc_pp": 79.95689655172413,
              "subject": 4,
              "target_clean_acc_pp": 43.40277777777778,
              "target_missing_acc_pp": 34.63541666666666,
              "target_missing_per_channel_acc_pp": [
                45.3125,
                36.45833333333333,
                45.83333333333333,
                38.54166666666667,
                29.34027777777778,
                33.15972222222222,
                36.28472222222222,
                42.53472222222222,
                32.29166666666667,
                37.84722222222222,
                37.84722222222222,
                31.59722222222222,
                42.88194444444444,
                25.520833333333332,
                28.645833333333332,
                25.17361111111111,
                34.20138888888889,
                26.041666666666668,
                25.0,
                47.22222222222222,
                26.041666666666668,
                34.20138888888889
              ],
              "task_id": "B0_s4_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "31a0c0fa12231b5491adc8506b4a2d65408366776cd8f118f6c480e750bcbd65",
              "difference_vs_seed0_clean_pp": 1.7361111111111143,
              "difference_vs_seed0_missing_pp": 1.6414141414141383,
              "historical_seed0_clean_acc_pp": 34.54861111111111,
              "historical_seed0_missing_acc_pp": 32.23642676767677,
              "source_valid_best_epoch": 89,
              "source_valid_clean_acc_pp": 79.95689655172413,
              "subject": 5,
              "target_clean_acc_pp": 36.28472222222222,
              "target_missing_acc_pp": 33.87784090909091,
              "target_missing_per_channel_acc_pp": [
                29.6875,
                35.24305555555556,
                31.59722222222222,
                28.819444444444443,
                34.89583333333333,
                38.54166666666667,
                28.993055555555557,
                31.42361111111111,
                29.166666666666668,
                25.17361111111111,
                43.22916666666667,
                38.71527777777778,
                35.24305555555556,
                42.36111111111111,
                32.63888888888889,
                30.90277777777778,
                37.67361111111111,
                41.66666666666667,
                35.59027777777778,
                28.993055555555557,
                33.85416666666667,
                30.90277777777778
              ],
              "task_id": "B0_s5_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "210429b0d3f0b505e6cb9c5b1c95d3277852256e95214c30c0d55ac2758736fb",
              "difference_vs_seed0_clean_pp": -0.17361111111110716,
              "difference_vs_seed0_missing_pp": 1.6019570707070727,
              "historical_seed0_clean_acc_pp": 34.54861111111111,
              "historical_seed0_missing_acc_pp": 32.23642676767677,
              "source_valid_best_epoch": 80,
              "source_valid_clean_acc_pp": 78.98706896551724,
              "subject": 5,
              "target_clean_acc_pp": 34.375,
              "target_missing_acc_pp": 33.83838383838384,
              "target_missing_per_channel_acc_pp": [
                27.256944444444443,
                32.63888888888889,
                34.54861111111111,
                28.645833333333332,
                34.54861111111111,
                38.54166666666667,
                27.95138888888889,
                33.50694444444444,
                33.15972222222222,
                25.17361111111111,
                39.93055555555556,
                37.5,
                35.9375,
                40.45138888888889,
                28.819444444444443,
                30.208333333333332,
                37.32638888888889,
                39.58333333333333,
                41.84027777777778,
                30.381944444444443,
                34.54861111111111,
                31.944444444444443
              ],
              "task_id": "B0_s5_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "a97762b8efc99c3c2a028892526541418d91a4d8d4cae9c99db6c9b5df57f80b",
              "difference_vs_seed0_clean_pp": -3.298611111111107,
              "difference_vs_seed0_missing_pp": -2.8882575757575566,
              "historical_seed0_clean_acc_pp": 64.75694444444444,
              "historical_seed0_missing_acc_pp": 49.58964646464645,
              "source_valid_best_epoch": 82,
              "source_valid_clean_acc_pp": 78.34051724137932,
              "subject": 6,
              "target_clean_acc_pp": 61.458333333333336,
              "target_missing_acc_pp": 46.70138888888889,
              "target_missing_per_channel_acc_pp": [
                57.291666666666664,
                47.04861111111111,
                62.5,
                56.25,
                57.986111111111114,
                43.22916666666667,
                55.729166666666664,
                52.25694444444444,
                48.61111111111111,
                48.09027777777778,
                53.125,
                57.986111111111114,
                59.201388888888886,
                25.868055555555557,
                48.61111111111111,
                30.381944444444443,
                40.79861111111111,
                30.381944444444443,
                29.86111111111111,
                58.50694444444444,
                30.90277777777778,
                32.8125
              ],
              "task_id": "B0_s6_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "8c3eb86a37a89e559c82ff3fda355fa39d0b751a6ea06a6aef8da5796a1f928e",
              "difference_vs_seed0_clean_pp": 0.5208333333333428,
              "difference_vs_seed0_missing_pp": -0.7891414141414117,
              "historical_seed0_clean_acc_pp": 64.75694444444444,
              "historical_seed0_missing_acc_pp": 49.58964646464645,
              "source_valid_best_epoch": 96,
              "source_valid_clean_acc_pp": 78.01724137931035,
              "subject": 6,
              "target_clean_acc_pp": 65.27777777777779,
              "target_missing_acc_pp": 48.80050505050504,
              "target_missing_per_channel_acc_pp": [
                53.125,
                57.46527777777778,
                65.10416666666666,
                57.291666666666664,
                50.69444444444444,
                40.27777777777778,
                63.020833333333336,
                48.78472222222222,
                48.95833333333333,
                52.083333333333336,
                55.55555555555556,
                54.513888888888886,
                54.6875,
                27.604166666666668,
                57.8125,
                28.47222222222222,
                50.69444444444444,
                47.22222222222222,
                26.041666666666668,
                57.986111111111114,
                38.19444444444444,
                38.02083333333333
              ],
              "task_id": "B0_s6_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "a0c3ed318e1f129fd119f3d73457f47d59b8708d747611c34ca0f137ac2502a7",
              "difference_vs_seed0_clean_pp": 0.0,
              "difference_vs_seed0_missing_pp": 2.1780303030303187,
              "historical_seed0_clean_acc_pp": 71.875,
              "historical_seed0_missing_acc_pp": 53.117108585858574,
              "source_valid_best_epoch": 99,
              "source_valid_clean_acc_pp": 77.47844827586206,
              "subject": 7,
              "target_clean_acc_pp": 71.875,
              "target_missing_acc_pp": 55.29513888888889,
              "target_missing_per_channel_acc_pp": [
                59.375,
                67.88194444444444,
                59.72222222222222,
                58.68055555555556,
                55.03472222222222,
                49.30555555555556,
                40.45138888888889,
                42.01388888888889,
                58.333333333333336,
                27.77777777777778,
                67.01388888888889,
                62.15277777777778,
                64.40972222222221,
                56.25,
                66.31944444444444,
                56.076388888888886,
                50.34722222222222,
                43.05555555555556,
                59.548611111111114,
                65.10416666666666,
                46.18055555555556,
                61.458333333333336
              ],
              "task_id": "B0_s7_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "2d8ea31b4bbf6c996b83d519f44c9ffba79a08ca75b12fa282f4a9a63762ef3e",
              "difference_vs_seed0_clean_pp": 6.423611111111114,
              "difference_vs_seed0_missing_pp": 6.178977272727288,
              "historical_seed0_clean_acc_pp": 71.875,
              "historical_seed0_missing_acc_pp": 53.117108585858574,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 76.1853448275862,
              "subject": 7,
              "target_clean_acc_pp": 78.29861111111111,
              "target_missing_acc_pp": 59.29608585858586,
              "target_missing_per_channel_acc_pp": [
                67.1875,
                77.08333333333334,
                65.45138888888889,
                60.24305555555556,
                59.548611111111114,
                49.65277777777778,
                67.70833333333334,
                47.04861111111111,
                68.57638888888889,
                34.89583333333333,
                66.14583333333334,
                61.63194444444444,
                69.44444444444444,
                54.6875,
                68.57638888888889,
                61.80555555555556,
                47.56944444444444,
                43.05555555555556,
                60.59027777777778,
                71.70138888888889,
                44.96527777777778,
                56.94444444444444
              ],
              "task_id": "B0_s7_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "fb10dd569188db5eee48c91b766fe169ab4d6dc982b6e9c8503b42a5a939a342",
              "difference_vs_seed0_clean_pp": 6.944444444444443,
              "difference_vs_seed0_missing_pp": 0.46559343434342537,
              "historical_seed0_clean_acc_pp": 61.63194444444444,
              "historical_seed0_missing_acc_pp": 53.55113636363637,
              "source_valid_best_epoch": 99,
              "source_valid_clean_acc_pp": 78.01724137931035,
              "subject": 8,
              "target_clean_acc_pp": 68.57638888888889,
              "target_missing_acc_pp": 54.01672979797979,
              "target_missing_per_channel_acc_pp": [
                62.326388888888886,
                63.888888888888886,
                65.625,
                61.111111111111114,
                53.99305555555556,
                52.77777777777778,
                64.23611111111111,
                49.13194444444444,
                62.15277777777778,
                47.74305555555556,
                58.15972222222222,
                50.173611111111114,
                48.4375,
                43.75,
                57.8125,
                56.59722222222222,
                48.4375,
                32.29166666666667,
                47.56944444444444,
                61.63194444444444,
                50.86805555555556,
                49.65277777777778
              ],
              "task_id": "B0_s8_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "ff55b3976df7b137174c841acf4e70455432b4ca13214f5c2e9801949206ee91",
              "difference_vs_seed0_clean_pp": 0.8680555555555571,
              "difference_vs_seed0_missing_pp": 0.055239898989889014,
              "historical_seed0_clean_acc_pp": 61.63194444444444,
              "historical_seed0_missing_acc_pp": 53.55113636363637,
              "source_valid_best_epoch": 89,
              "source_valid_clean_acc_pp": 78.55603448275862,
              "subject": 8,
              "target_clean_acc_pp": 62.5,
              "target_missing_acc_pp": 53.606376262626256,
              "target_missing_per_channel_acc_pp": [
                56.94444444444444,
                64.23611111111111,
                61.979166666666664,
                54.34027777777778,
                50.173611111111114,
                47.74305555555556,
                57.46527777777778,
                46.35416666666667,
                61.458333333333336,
                50.34722222222222,
                55.208333333333336,
                50.69444444444444,
                50.520833333333336,
                44.79166666666667,
                60.59027777777778,
                52.25694444444444,
                47.56944444444444,
                48.61111111111111,
                59.375,
                62.5,
                50.520833333333336,
                45.65972222222222
              ],
              "task_id": "B0_s8_seed2"
            }
          ],
          "unit": "subject"
        },
        "claim_release": false,
        "decision": "CPA_U0_INDEPENDENT_BACKBONE_SUPPORT",
        "interpretation_boundary": "9 subjects are statistical units; the two backbone seeds are repeated training, and original seed0 is excluded from this decision.",
        "reason": "both backbone-seed gates and subject-wise paired-mean gate evaluated",
        "round_id": "dbconformer-bda-r1-ccmu2",
        "utility_gates": {
          "seed1": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                6.928661616161615,
                6.929648042929292
              ],
              [
                7.415956439393938,
                7.416942866161615
              ],
              [
                6.049755366161615,
                6.049755366161615
              ],
              [
                7.102272727272726,
                7.103259154040403
              ],
              [
                7.484019886363636,
                7.485006313131313
              ],
              [
                6.890190972222222,
                6.8911773989899
              ],
              [
                6.732362689393939,
                6.733349116161616
              ],
              [
                7.044073547979797,
                7.045059974747474
              ],
              [
                7.523476957070707,
                7.524463383838384
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.018974466891135,
              "positive_subjects": 9,
              "worst_subject": 2.9829545454545467
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          },
          "seed2": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.368607954545452,
                7.370580808080806
              ],
              [
                7.630011047979795,
                7.632970328282825
              ],
              [
                5.865293560606059,
                5.867266414141412
              ],
              [
                7.41497001262626,
                7.417929292929291
              ],
              [
                7.670454545454543,
                7.6734138257575735
              ],
              [
                7.071693497474745,
                7.0736663510100986
              ],
              [
                6.749131944444442,
                6.752091224747472
              ],
              [
                7.581676136363634,
                7.584635416666664
              ],
              [
                8.044310290404038,
                8.04726957070707
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.267115600448936,
              "positive_subjects": 9,
              "worst_subject": 1.0416666666666714
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          },
          "subject_wise_fresh_seed_mean": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.148634785353534,
                7.150114425505049
              ],
              [
                7.522983743686867,
                7.52495659722222
              ],
              [
                5.957524463383837,
                5.958510890151514
              ],
              [
                7.258621369949493,
                7.260594223484847
              ],
              [
                7.57723721590909,
                7.579210069444443
              ],
              [
                6.9809422348484835,
                6.982421874999999
              ],
              [
                6.74074731691919,
                6.742720170454544
              ],
              [
                7.312874842171715,
                7.314847695707069
              ],
              [
                7.783893623737372,
                7.785866477272727
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.143045033670035,
              "positive_subjects": 9,
              "worst_subject": 2.012310606060609
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          }
        }
      },
      "closing_round": "dbconformer-bda-r1-ccmu2",
      "closing_run": {
        "artifact_manifest_sha256": "c0d5f8d927edeba8922861f0aaccc433d649ed49e6e87d894fb6b8e0207bcf1c",
        "contract_sha256": "f632d23a344581a5bd1f1bde01506d4759fb6f5f19839910ec937d6305797160",
        "intake_path": "results/logs/remote/2026-10-03_dbconformer_bda_r1_ccmu_r2-full-w1",
        "run_id": "2026-10-03_dbconformer_bda_r1_ccmu_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bda-r1-ccmu2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户要求执行一次决定U0去留的近邻对照，并明确授权新设6小时仅本次对照；复用冻结B0/U0，仅新增RIDGE及SSF对照，不扩展轮数。"
    },
    {
      "campaign_id": "dbconformer-v3-20261004-nnc-r1",
      "closed_at": "2026-10-04T16:11:47.794443+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparison_gates": {
          "U0-B0": {
            "seed1": {
              "determinate": true,
              "pass": true,
              "subgates": {
                "all_loo_positive": true,
                "mean": true,
                "positive_subjects": true,
                "worst_subject": true
              }
            },
            "seed2": {
              "determinate": true,
              "pass": true,
              "subgates": {
                "all_loo_positive": true,
                "mean": true,
                "positive_subjects": true,
                "worst_subject": true
              }
            },
            "subject_wise_fresh_seed_mean": {
              "determinate": true,
              "pass": true,
              "subgates": {
                "all_loo_positive": true,
                "mean": true,
                "positive_subjects": true,
                "worst_subject": true
              }
            }
          },
          "U0-RIDGE": {
            "seed1": {
              "determinate": true,
              "pass": false,
              "subgates": {
                "all_loo_positive": false,
                "mean": false,
                "positive_subjects": false,
                "worst_subject": false
              }
            },
            "seed2": {
              "determinate": true,
              "pass": false,
              "subgates": {
                "all_loo_positive": false,
                "mean": false,
                "positive_subjects": false,
                "worst_subject": false
              }
            },
            "subject_wise_fresh_seed_mean": {
              "determinate": true,
              "pass": false,
              "subgates": {
                "all_loo_positive": false,
                "mean": false,
                "positive_subjects": false,
                "worst_subject": false
              }
            }
          },
          "U0-SSF": {
            "seed1": {
              "determinate": true,
              "pass": false,
              "subgates": {
                "all_loo_positive": true,
                "mean": true,
                "positive_subjects": false,
                "worst_subject": true
              }
            },
            "seed2": {
              "determinate": true,
              "pass": false,
              "subgates": {
                "all_loo_positive": true,
                "mean": true,
                "positive_subjects": true,
                "worst_subject": false
              }
            },
            "subject_wise_fresh_seed_mean": {
              "determinate": true,
              "pass": true,
              "subgates": {
                "all_loo_positive": true,
                "mean": true,
                "positive_subjects": true,
                "worst_subject": true
              }
            }
          }
        },
        "decision": "INSUFFICIENT_U0_NEAREST_NEIGHBOR_SUPPORT",
        "interpretation_boundary": "Nine subjects are statistical units; the two existing backbone seeds are repeated fits; no independent population or capacity-matched causal conclusion.",
        "next_disposition": "retire_standalone_u0_keep_baseline",
        "reason": "all three paired comparisons and all frozen subject/seed groups evaluated",
        "round_id": "dbconformer-nnc-r1-repair1"
      },
      "closing_round": "dbconformer-nnc-r1-repair1",
      "closing_run": {
        "artifact_manifest_sha256": "e2f111cf6392024f0694f5db5f19746c2a24c7b9d7dd7d554f6058f3e72b615d",
        "contract_sha256": "5991d67b2b884837729daa2b27f8f153c0f2ab459929dbc9cdedfa1ce3c65ead",
        "intake_path": "results/logs/remote/2026-10-04_dbconformer_nnc_r1_ccmu_r2-full-w1",
        "run_id": "2026-10-04_dbconformer_nnc_r1_ccmu_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-nnc-r1-repair1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户明确收口U0和RIDGE定位，要求继续网络结构创新主线，且选择新设8小时仅一轮。授权本轮设计实现、ccmu上传启动、回拉核验和分析。"
    },
    {
      "campaign_id": "dbconformer-v3-20261005-architecture-r1",
      "closed_at": "2026-10-05T06:02:02.994686+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.4756944444444444,
                -1.4756944444444444
              ],
              [
                -0.7161458333333334,
                -0.7161458333333334
              ],
              [
                -0.3038194444444444,
                -0.3038194444444444
              ],
              [
                -0.5425347222222222,
                -0.5425347222222222
              ],
              [
                -0.9982638888888888,
                -0.9982638888888888
              ],
              [
                0.1953125,
                0.1953125
              ],
              [
                0.0,
                0.0
              ],
              [
                -1.0633680555555556,
                -1.0633680555555556
              ],
              [
                -0.3038194444444444,
                -0.3038194444444444
              ]
            ],
            "mean_delta_pp": -0.5787037037037037,
            "mean_interval_pp": [
              -0.5787037037037037,
              -0.5787037037037037
            ],
            "midpoint_mean_delta_pp": -0.5787037037037037,
            "pass": false,
            "positive_subject_count_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                6.597222222222222,
                6.597222222222222
              ],
              [
                0.5208333333333334,
                0.5208333333333334
              ],
              [
                -2.7777777777777777,
                -2.7777777777777777
              ],
              [
                -0.8680555555555556,
                -0.8680555555555556
              ],
              [
                2.7777777777777777,
                2.7777777777777777
              ],
              [
                -6.770833333333333,
                -6.770833333333333
              ],
              [
                -5.208333333333333,
                -5.208333333333333
              ],
              [
                3.298611111111111,
                3.298611111111111
              ],
              [
                -2.7777777777777777,
                -2.7777777777777777
              ]
            ],
            "worst_subject_interval_pp": [
              -6.770833333333333,
              -6.770833333333333
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.2387152777777778,
                -0.2387152777777778
              ],
              [
                1.2369791666666667,
                1.2369791666666667
              ],
              [
                0.8029513888888888,
                0.8029513888888888
              ],
              [
                1.2803819444444444,
                1.2803819444444444
              ],
              [
                0.5208333333333334,
                0.5208333333333334
              ],
              [
                1.0416666666666667,
                1.0416666666666667
              ],
              [
                0.8680555555555556,
                0.8680555555555556
              ],
              [
                0.6944444444444444,
                0.6944444444444444
              ],
              [
                0.390625,
                0.390625
              ]
            ],
            "mean_delta_pp": 0.7330246913580247,
            "mean_interval_pp": [
              0.7330246913580247,
              0.7330246913580247
            ],
            "midpoint_mean_delta_pp": 0.7330246913580247,
            "pass": false,
            "positive_subject_count_interval": [
              5,
              5
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": true,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                8.506944444444445,
                8.506944444444445
              ],
              [
                -3.298611111111111,
                -3.298611111111111
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                -3.6458333333333335,
                -3.6458333333333335
              ],
              [
                2.4305555555555554,
                2.4305555555555554
              ],
              [
                -1.7361111111111112,
                -1.7361111111111112
              ],
              [
                -0.3472222222222222,
                -0.3472222222222222
              ],
              [
                1.0416666666666667,
                1.0416666666666667
              ],
              [
                3.4722222222222223,
                3.4722222222222223
              ]
            ],
            "worst_subject_interval_pp": [
              -3.6458333333333335,
              -3.6458333333333335
            ]
          }
        },
        "decision": "INSUFFICIENT_LOCAL_TEMPORAL_INCREMENT_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; no claim of independent confirmation, statistical significance, unique mechanism, novelty, or paper readiness.",
        "reason": "at least one required clean-utility contrast fails a determinate frozen gate",
        "round_id": "dbconformer-lta-r1-repair3"
      },
      "closing_round": "dbconformer-lta-r1-repair3",
      "closing_run": {
        "artifact_manifest_sha256": "f1344aad26ee94fbb9b9c03288e03e0cfa3cbbaa02b0d81269ed2e4d86396844",
        "contract_sha256": "76c7e6c7daca1dcdde77b82d76ef088fae30a80cb6fa61c908ff75ae3a0e32b5",
        "intake_path": "results/logs/remote/2026-10-05_dbconformer_lta_r1_ccmu_r4-full-w1",
        "run_id": "2026-10-05_dbconformer_lta_r1_ccmu_r4-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-lta-r1-repair3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户要求在LTA-R1精确负边界后设计并继续下一轮网络结构创新，并明确选择新设8小时仅一轮；授权方向筛选、实现、冻结CCMU新Run上传启动及回拉核验回放分析。新科学对象在设计审查后单独登记，不复活LTA或U0独立候选。"
    },
    {
      "campaign_id": "dbconformer-v3-20261005-architecture-r2",
      "closed_at": "2026-10-05T11:31:35.903945+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.6076388888888888,
                -0.6076388888888888
              ],
              [
                0.4774305555555556,
                0.4774305555555556
              ],
              [
                1.0199652777777777,
                1.0199652777777777
              ],
              [
                0.5642361111111112,
                0.5642361111111112
              ],
              [
                0.4774305555555556,
                0.4774305555555556
              ],
              [
                1.1935763888888888,
                1.1935763888888888
              ],
              [
                1.1067708333333333,
                1.1067708333333333
              ],
              [
                0.06510416666666667,
                0.06510416666666667
              ],
              [
                0.390625,
                0.390625
              ]
            ],
            "mean_delta_pp": 0.5208333333333334,
            "mean_interval_pp": [
              0.5208333333333334,
              0.5208333333333334
            ],
            "midpoint_mean_delta_pp": 0.5208333333333334,
            "pass": false,
            "positive_subject_count_interval": [
              6,
              6
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                9.54861111111111,
                9.54861111111111
              ],
              [
                0.8680555555555556,
                0.8680555555555556
              ],
              [
                -3.4722222222222223,
                -3.4722222222222223
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                0.8680555555555556,
                0.8680555555555556
              ],
              [
                -4.861111111111111,
                -4.861111111111111
              ],
              [
                -4.166666666666667,
                -4.166666666666667
              ],
              [
                4.166666666666667,
                4.166666666666667
              ],
              [
                1.5625,
                1.5625
              ]
            ],
            "worst_subject_interval_pp": [
              -4.861111111111111,
              -4.861111111111111
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.3689236111111111,
                -0.3689236111111111
              ],
              [
                0.9114583333333334,
                0.9114583333333334
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                0.3689236111111111,
                0.3689236111111111
              ],
              [
                0.08680555555555555,
                0.08680555555555555
              ],
              [
                0.9982638888888888,
                0.9982638888888888
              ],
              [
                1.0633680555555556,
                1.0633680555555556
              ],
              [
                0.2387152777777778,
                0.2387152777777778
              ],
              [
                -0.5208333333333334,
                -0.5208333333333334
              ]
            ],
            "mean_delta_pp": 0.3279320987654321,
            "mean_interval_pp": [
              0.3279320987654321,
              0.3279320987654321
            ],
            "midpoint_mean_delta_pp": 0.3279320987654321,
            "pass": false,
            "positive_subject_count_interval": [
              5,
              5
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                5.902777777777778,
                5.902777777777778
              ],
              [
                -4.340277777777778,
                -4.340277777777778
              ],
              [
                1.5625,
                1.5625
              ],
              [
                0.0,
                0.0
              ],
              [
                2.2569444444444446,
                2.2569444444444446
              ],
              [
                -5.034722222222222,
                -5.034722222222222
              ],
              [
                -5.555555555555555,
                -5.555555555555555
              ],
              [
                1.0416666666666667,
                1.0416666666666667
              ],
              [
                7.118055555555555,
                7.118055555555555
              ]
            ],
            "worst_subject_interval_pp": [
              -5.555555555555555,
              -5.555555555555555
            ]
          }
        },
        "decision": "INSUFFICIENT_CROSS_BRANCH_COUPLING_INCREMENT_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; no independent confirmation or paper claim.",
        "reason": "at least one RCC contrast fails a determinate frozen gate",
        "round_id": "dbconformer-rcc-r1-native1"
      },
      "closing_round": "dbconformer-rcc-r1-native1",
      "closing_run": {
        "artifact_manifest_sha256": "d8859a33eebe343c17198cf942b01e6e58972926081d0554515d4cf33eaa0c9d",
        "contract_sha256": "d4e8674af26b1dbd5e097f9d3dfd1815cd38568ef39f7439e696b6ef8882848f",
        "intake_path": "results/logs/remote/2026-10-05_dbconformer_rcc_r1_ccmu_r2-full-w1",
        "run_id": "2026-10-05_dbconformer_rcc_r1_ccmu_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-rcc-r1-native1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "用户要求在RCC-R1有效负边界后设计并继续下一轮网络结构创新，明确选择新设8小时仅一轮；授权证据复核、查新、实现、冻结新对象及CCMU上传启动。按用户最新指令，核验正式训练启动后即交回，不持续监控，后续应请求检查并完成同Run回拉核验回放分析。新科学对象经候选审查后单独登记，不复活RCC/LTA或U0独立候选。"
    },
    {
      "campaign_id": "dbconformer-v3-20261005-architecture-r3",
      "closed_at": "2026-10-08T12:04:34.863641+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.6710069444444444,
                -1.6710069444444444
              ],
              [
                -1.3020833333333333,
                -1.3020833333333333
              ],
              [
                -0.7161458333333334,
                -0.7161458333333334
              ],
              [
                -1.0416666666666667,
                -1.0416666666666667
              ],
              [
                -1.1935763888888888,
                -1.1935763888888888
              ],
              [
                -0.6076388888888888,
                -0.6076388888888888
              ],
              [
                -0.9765625,
                -0.9765625
              ],
              [
                -1.5842013888888888,
                -1.5842013888888888
              ],
              [
                0.06510416666666667,
                0.06510416666666667
              ]
            ],
            "mean_delta_pp": -1.0030864197530864,
            "mean_interval_pp": [
              -1.0030864197530864,
              -1.0030864197530864
            ],
            "midpoint_mean_delta_pp": -1.0030864197530864,
            "pass": false,
            "positive_subject_count_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                4.340277777777778,
                4.340277777777778
              ],
              [
                1.3888888888888888,
                1.3888888888888888
              ],
              [
                -3.298611111111111,
                -3.298611111111111
              ],
              [
                -0.6944444444444444,
                -0.6944444444444444
              ],
              [
                0.5208333333333334,
                0.5208333333333334
              ],
              [
                -4.166666666666667,
                -4.166666666666667
              ],
              [
                -1.2152777777777777,
                -1.2152777777777777
              ],
              [
                3.6458333333333335,
                3.6458333333333335
              ],
              [
                -9.54861111111111,
                -9.54861111111111
              ]
            ],
            "worst_subject_interval_pp": [
              -9.54861111111111,
              -9.54861111111111
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.08680555555555555,
                -0.08680555555555555
              ],
              [
                0.5425347222222222,
                0.5425347222222222
              ],
              [
                -0.3689236111111111,
                -0.3689236111111111
              ],
              [
                -0.6076388888888888,
                -0.6076388888888888
              ],
              [
                0.06510416666666667,
                0.06510416666666667
              ],
              [
                0.0,
                0.0
              ],
              [
                0.2604166666666667,
                0.2604166666666667
              ],
              [
                0.1519097222222222,
                0.1519097222222222
              ],
              [
                0.390625,
                0.390625
              ]
            ],
            "mean_delta_pp": 0.038580246913580245,
            "mean_interval_pp": [
              0.038580246913580245,
              0.038580246913580245
            ],
            "midpoint_mean_delta_pp": 0.038580246913580245,
            "pass": false,
            "positive_subject_count_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                1.0416666666666667,
                1.0416666666666667
              ],
              [
                -3.9930555555555554,
                -3.9930555555555554
              ],
              [
                3.298611111111111,
                3.298611111111111
              ],
              [
                5.208333333333333,
                5.208333333333333
              ],
              [
                -0.1736111111111111,
                -0.1736111111111111
              ],
              [
                0.3472222222222222,
                0.3472222222222222
              ],
              [
                -1.7361111111111112,
                -1.7361111111111112
              ],
              [
                -0.8680555555555556,
                -0.8680555555555556
              ],
              [
                -2.7777777777777777,
                -2.7777777777777777
              ]
            ],
            "worst_subject_interval_pp": [
              -3.9930555555555554,
              -3.9930555555555554
            ]
          }
        },
        "decision": "INSUFFICIENT_CHANNEL_LOCAL_PATH_AREA_INCREMENT_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; no independent confirmation or paper claim.",
        "reason": "at least one PAT contrast fails a determinate frozen gate",
        "round_id": "dbconformer-pat-r1-repair5"
      },
      "closing_round": "dbconformer-pat-r1-repair5",
      "closing_run": {
        "artifact_manifest_sha256": "4a024da6f3955f88c7e59bd9d8539578823b41d8ab5de896075bf1c5a0c15f3e",
        "contract_sha256": "c7c8a72950d3709daf0c8573b7ccedae207c54f01d1bf9b8b43f2cbd8242809a",
        "intake_path": "results/logs/remote/2026-10-07_dbconformer_pat_r1_ccmu_repair5-full-w1",
        "run_id": "2026-10-07_dbconformer_pat_r1_ccmu_repair5-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-pat-r1-repair5-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized LRC-R1 Lab10 launch and new8h single round; full DyST-GT published-method qualification independently PROCEED_WITH_LIMITS, known low-novelty exploratory marginal-control question only; prepare exact30 freshfits, upload launch probe and sameRun closure, no next research or claim. Preserve historical PAT negative closure."
    },
    {
      "campaign_id": "dbconformer-v3-20261008-lrc-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User explicitly authorized LRC-R1 Lab10 launch and new8h single round; full DyST-GT published-method qualification independently PROCEED_WITH_LIMITS, known low-novelty exploratory marginal-control question only; prepare exact30 freshfits, upload launch probe and sameRun closure, no next research or claim. Preserve historical PAT negative closure.",
        "campaign_id": "dbconformer-v3-20261008-lrc-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/lrc_r1/AUTHORIZATION.md",
          "campaign_id": "dbconformer-v3-20261008-lrc-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-08T12:04:38.334660+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "prepool-local-relation-content-coupling-v01"
            ],
            "allowed_stages": [
              "local_relation_content_clean_screen"
            ],
            "data_scope_id": "BNCI2014001-cue0_4s-loso-exposed9-seed0-exploratory",
            "question_id": "matched-window-relation-content-increment"
          },
          "source_sha256": "107907238752bbc759b31c2b0340ec172202173852b02d01df16c0f68316ec6d"
        },
        "extensions": [
          {
            "authorized_at": "2026-10-09T06:05:51.972264+00:00",
            "new_max_rounds": 1,
            "new_night_budget_hours": 24.336381490296787,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 8.0,
            "reason": "Direct user authorized six additional usable hours from 2026-10-09T06:03:36Z, only dbconformer-lrc-r1-repair1, same science 30 fits, Lab10. Preserve original start/history; cumulative budget maps this prospective deadline, not a reset or extra round. Authority: ai4s/programs/dbconformer/research/lrc_r1/repair_20261009/TIME_EXTENSION_AUTHORIZATION.json"
          },
          {
            "authorized_at": "2026-10-09T12:27:08.063233+00:00",
            "new_max_rounds": 1,
            "new_night_budget_hours": 30.490734323130713,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 24.336381490296787,
            "reason": "Direct user confirmed six usable hours from 2026-10-09T12:25:45Z, single repair2, same 30 fresh fits, direct Lab10. Preserve old started_at and history, exclude only verified resource queue. Authority: ai4s/programs/dbconformer/research/lrc_r1_repair2/TIME_EXTENSION_AUTHORIZATION.json"
          },
          {
            "authorized_at": "2026-10-10T01:43:57.390971+00:00",
            "new_max_rounds": 1,
            "new_night_budget_hours": 40.65241423481041,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 30.490734323130713,
            "reason": "Direct user confirmation: single repair3, six prospective usable hours from 2026-10-10T01:42:02Z; same fresh30 matrix; smoke7200 screen10800; preserve campaign clock and verified queue; authority ai4s/programs/dbconformer/research/lrc_r1_repair3/TIME_EXTENSION_AUTHORIZATION.json"
          },
          {
            "additional_hours": 10.0,
            "authorized_at": "2026-10-10T08:24:59.198783+00:00",
            "budget_argument_semantics": "night_budget_hours is the new cumulative campaign total, not an increment",
            "new_max_rounds": 1,
            "new_night_budget_hours": 50.65241423481041,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 40.65241423481041,
            "reason": "Direct user selected additional10h and screen6h; single repair4, source-smoke2h, same fresh30. Preserve old campaign clock and remaining credit. Authority ai4s/programs/dbconformer/research/lrc_r1_repair4/TIME_EXTENSION_AUTHORIZATION.json"
          }
        ],
        "governance_chain_id": "dbconformer-transaction-v3.0",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-08_dbconformer_lrc_r1_lab10_r1-full-w1": {
            "contract_sha256": "88e621c6e5b8af5b5c23e5554e85b42a8d152f4fb4db621edc4863afba4c4769",
            "queue_seconds": 1.026634931564331,
            "run_id": "2026-10-08_dbconformer_lrc_r1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-tx"
          },
          "2026-10-09_dbconformer_lrc_r1_repair1_lab10_r1-full-w1": {
            "contract_sha256": "c2f1f06957d03174b8a6e9395251366d30f2d662e9ace5966bde84895d1672e2",
            "queue_seconds": 773.3298017978668,
            "run_id": "2026-10-09_dbconformer_lrc_r1_repair1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-repair1-tx"
          },
          "2026-10-09_dbconformer_lrc_r1_repair2_rev1_lab10_r1-full-w1": {
            "contract_sha256": "a1591589000dd21942452e867212db9a53f643357f4e801c83c71359c52c3b5b",
            "queue_seconds": 11194.95231795311,
            "run_id": "2026-10-09_dbconformer_lrc_r1_repair2_rev1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-repair2-rev1-tx"
          },
          "2026-10-10_dbconformer_lrc_r1_repair3_lab10_r1-full-w1": {
            "contract_sha256": "f3fc313e9ad6ed86102ded557d5f8615175f45ff232a1c905b57709141cf4f6b",
            "queue_seconds": 3382.6558492183685,
            "run_id": "2026-10-10_dbconformer_lrc_r1_repair3_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-repair3-tx"
          },
          "2026-10-10_dbconformer_lrc_r1_repair4_lab10_r1-full-w1": {
            "contract_sha256": "a1c37c4d3b98af87edd740bbb642058f0d32d8a4207e2e791b6b8df1337cb5b1",
            "queue_seconds": 70974.79329824448,
            "run_id": "2026-10-10_dbconformer_lrc_r1_repair4_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-repair4-tx"
          },
          "2026-10-11_dbconformer_lrc_r1_deploy1_lab10_r1-full-w1": {
            "contract_sha256": "6086b4188a479b33a91edfedb94ca04caa587628b3be034bc6c669050b0c4b4f",
            "queue_seconds": 0.0,
            "run_id": "2026-10-11_dbconformer_lrc_r1_deploy1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-deploy1-tx"
          },
          "2026-10-11_dbconformer_lrc_r1_deploy2_lab10_r1-full-w1": {
            "contract_sha256": "7df5e6e683100cf2aa38e87268bdc1ddb81692658c90bbd9f135ca72595925a0",
            "queue_seconds": 9.640594482421875,
            "run_id": "2026-10-11_dbconformer_lrc_r1_deploy2_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-deploy2-tx"
          },
          "2026-10-11_dbconformer_lrc_r1_last1_lab10_r1-full-w1": {
            "contract_sha256": "e6d70785cd14ed882893eae462124f23fd7cf0b7f2e2c00f1449a98390a4b551",
            "queue_seconds": 0.0,
            "run_id": "2026-10-11_dbconformer_lrc_r1_last1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-last1-tx"
          },
          "2026-10-11_dbconformer_lrc_r1_last1fix1_lab10_r1-full-w1": {
            "contract_sha256": "4741b7407722a8ddf059dee0063d739d34233657f820d1e02d5b0294802839be",
            "queue_seconds": 16.178080081939697,
            "run_id": "2026-10-11_dbconformer_lrc_r1_last1fix1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-lrc-r1-last1fix1-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INSUFFICIENT_LOCAL_RELATION_CONTENT_INCREMENT_SUPPORT",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-lrc-r1-last1fix1_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-dbconformer-lrc-r1-last1fix1",
            "recorded_at": "2026-10-11T14:48:48.637393+00:00",
            "round_id": "dbconformer-lrc-r1-last1fix1"
          }
        ],
        "started_at": "2026-10-08T11:43:24+00:00"
      },
      "closed_at": "2026-10-11T17:07:14.084310+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.6510416666666666,
                0.6510416666666666
              ],
              [
                -0.5425347222222222,
                -0.5425347222222222
              ],
              [
                0.3689236111111111,
                0.3689236111111111
              ],
              [
                -0.021701388888888888,
                -0.021701388888888888
              ],
              [
                -0.6076388888888888,
                -0.6076388888888888
              ],
              [
                -0.8680555555555556,
                -0.8680555555555556
              ],
              [
                0.4774305555555556,
                0.4774305555555556
              ],
              [
                -0.4123263888888889,
                -0.4123263888888889
              ],
              [
                -0.08680555555555555,
                -0.08680555555555555
              ]
            ],
            "mean_delta_pp": -0.11574074074074074,
            "mean_interval_pp": [
              -0.11574074074074074,
              -0.11574074074074074
            ],
            "pass": false,
            "positive_subject_count_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                -6.25,
                -6.25
              ],
              [
                3.298611111111111,
                3.298611111111111
              ],
              [
                -3.9930555555555554,
                -3.9930555555555554
              ],
              [
                -0.8680555555555556,
                -0.8680555555555556
              ],
              [
                3.8194444444444446,
                3.8194444444444446
              ],
              [
                5.902777777777778,
                5.902777777777778
              ],
              [
                -4.861111111111111,
                -4.861111111111111
              ],
              [
                2.2569444444444446,
                2.2569444444444446
              ],
              [
                -0.3472222222222222,
                -0.3472222222222222
              ]
            ],
            "worst_subject_interval_pp": [
              -6.25,
              -6.25
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.8246527777777778,
                -0.8246527777777778
              ],
              [
                -1.4756944444444444,
                -1.4756944444444444
              ],
              [
                -0.6076388888888888,
                -0.6076388888888888
              ],
              [
                -0.6944444444444444,
                -0.6944444444444444
              ],
              [
                -0.7161458333333334,
                -0.7161458333333334
              ],
              [
                -0.9548611111111112,
                -0.9548611111111112
              ],
              [
                -0.4991319444444444,
                -0.4991319444444444
              ],
              [
                -1.4539930555555556,
                -1.4539930555555556
              ],
              [
                -1.4539930555555556,
                -1.4539930555555556
              ]
            ],
            "mean_delta_pp": -0.9645061728395061,
            "mean_interval_pp": [
              -0.9645061728395061,
              -0.9645061728395061
            ],
            "pass": false,
            "positive_subject_count_interval": [
              3,
              3
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                -2.0833333333333335,
                -2.0833333333333335
              ],
              [
                3.125,
                3.125
              ],
              [
                -3.8194444444444446,
                -3.8194444444444446
              ],
              [
                -3.125,
                -3.125
              ],
              [
                -2.951388888888889,
                -2.951388888888889
              ],
              [
                -1.0416666666666667,
                -1.0416666666666667
              ],
              [
                -4.6875,
                -4.6875
              ],
              [
                2.951388888888889,
                2.951388888888889
              ],
              [
                2.951388888888889,
                2.951388888888889
              ]
            ],
            "worst_subject_interval_pp": [
              -4.6875,
              -4.6875
            ]
          }
        },
        "decision": "INSUFFICIENT_LOCAL_RELATION_CONTENT_INCREMENT_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "function_support": {
          "interpretation_boundary": "Source-only functional observability; does not change either clean-utility contrast or its classification.",
          "measurable_subject_count": 1,
          "required_subject_count": 6,
          "status": "mechanistic_support_not_established",
          "subjects": [
            {
              "artifact_sha256": "217f8f57dcf2c92b1c73ae019d51093b23ebe10ed61ae217abbba92a805b96d4",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 0
            },
            {
              "artifact_sha256": "ca7ee47102dade4863dd38b0bf3a57650411923ae18195229a6f1586196348cf",
              "inputs": 96,
              "measurable": true,
              "positive_input_count": 96,
              "subject": 1
            },
            {
              "artifact_sha256": "52faffc1ee29429869381e21e4bd76a8c9db313ffd36f24ad3be1f9b6d98de9b",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 2
            },
            {
              "artifact_sha256": "f1d7f753232df575543e929b55c13c4607e0dec8b5c7c2b07884557d798aedf8",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 3
            },
            {
              "artifact_sha256": "9c0ca15aec2139ea3f8435bfa9ec3b8cec42f12c25d492298b31d025569f0be7",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 4
            },
            {
              "artifact_sha256": "c6fc80761d4fa76230dffbf229ecafde85eb4be08fa1c3db150c2f2013a44869",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 5
            },
            {
              "artifact_sha256": "d87a37c5d0c975f5b49ec381840d083f01ba9ce4043630a7e9398bc21bc1a282",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 6
            },
            {
              "artifact_sha256": "dd9dfb42463fe225f03f292d3ab2c96413641423d46e2e0005b5a4030bee2a57",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 7
            },
            {
              "artifact_sha256": "89300ae7945f3e8ac5518aca89e7ef28e035c60b231bfaee67e595508568c604",
              "inputs": 96,
              "measurable": false,
              "positive_input_count": 0,
              "subject": 8
            }
          ]
        },
        "interpretation_boundary": "One exposed 9-subject single-seed screen; not independent confirmation, statistical significance, unique mechanism, novelty, or paper readiness.",
        "reason": "at least one required contrast fails a determinate frozen gate",
        "round_id": "dbconformer-lrc-r1-last1fix1"
      },
      "closing_round": "dbconformer-lrc-r1-last1fix1",
      "closing_run": {
        "artifact_manifest_sha256": "e214c0a95f185237c42ec1cb26c4906ca8e8365d9b3dac35f1d02abe880f1bef",
        "contract_sha256": "4741b7407722a8ddf059dee0063d739d34233657f820d1e02d5b0294802839be",
        "intake_path": "results/logs/remote/2026-10-11_dbconformer_lrc_r1_last1fix1_lab10_r1-full-w1",
        "run_id": "2026-10-11_dbconformer_lrc_r1_last1fix1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-lrc-r1-last1fix1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved new10h single WCR-R1 round max20 newfits and external9B0; preserve closed LRC cost and evidence; no retries seeds tuning or next round.",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/wcr_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "49f1ec1960b32aa74761f93843cb66620f485c888f01453242b64fce5cd2bbdf"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 50.65241423481041,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-08T11:43:24+00:00"
      }
    },
    {
      "campaign_id": "dbconformer-v3-20261012-wcr-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User approved new10h single WCR-R1 round max20 newfits and external9B0; preserve closed LRC cost and evidence; no retries seeds tuning or next round.",
        "campaign_id": "dbconformer-v3-20261012-wcr-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/wcr_r1/AUTHORIZATION.md",
          "campaign_id": "dbconformer-v3-20261012-wcr-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-11T17:07:16.336856+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "window-conditioned-temporal-to-electrode-readout-v01"
            ],
            "allowed_stages": [
              "window_context_electrode_readout_clean_screen"
            ],
            "data_scope_id": "BNCI2014001-cue0_4s-loso-exposed9-seed0-exploratory",
            "question_id": "matched-temporal-context-electrode-readout-increment"
          },
          "source_sha256": "1ed3ce7a98b469daa0338cd825d78589008fd45d413d4e926fa9cdf1926e3768"
        },
        "governance_chain_id": "dbconformer-transaction-v3.1",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-12_dbconformer_wcr_r1_lab10_r1-full-w1": {
            "contract_sha256": "70d416697fb6495d13310a6ccfb34521a6f2da59aa5647ee3cac2e9688c523ae",
            "queue_seconds": 1514.8143980503082,
            "run_id": "2026-10-12_dbconformer_wcr_r1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-wcr-r1-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INVALID",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-wcr-r1_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-dbconformer-wcr-r1",
            "recorded_at": "2026-10-12T05:08:56.975487+00:00",
            "round_id": "dbconformer-wcr-r1"
          }
        ],
        "started_at": "2026-10-11T17:03:46+00:00"
      },
      "closed_at": "2026-10-12T11:50:02.111179+00:00",
      "closing_decision": {
        "claim_release": false,
        "decision": "INVALID",
        "reason": "WCR evidence, external baseline reference, or technical integrity closure failed",
        "round_id": "dbconformer-wcr-r1"
      },
      "closing_round": "dbconformer-wcr-r1",
      "closing_run": {
        "artifact_manifest_sha256": "2964b9c4d27c51bc4d863db6d5956bbd65a0cb998bb7443312ce67732763b159",
        "contract_sha256": "70d416697fb6495d13310a6ccfb34521a6f2da59aa5647ee3cac2e9688c523ae",
        "intake_path": "results/logs/remote/2026-10-12_dbconformer_wcr_r1_lab10_r1-full-w1",
        "run_id": "2026-10-12_dbconformer_wcr_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-wcr-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved SGR Lab10 materials and new10h single max20 newfit round; external9 LRC B0; preserve old evidence and costs; no extra retries seeds tuning next round",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/sgr_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "a2a88586d39c66e50eab459c6ea7c61dfada080f9ec8d428272056395495f43e"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 10.0,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-11T17:03:46+00:00"
      }
    },
    {
      "campaign_id": "dbconformer-v3-20261012-sgr-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User approved SGR Lab10 materials and new10h single max20 newfit round; external9 LRC B0; preserve old evidence and costs; no extra retries seeds tuning next round",
        "budget_extensions": [
          {
            "additional_seeds_candidates_tuning_or_next_round": false,
            "allowed_destination_host": "[REDACTED_MACHINE]",
            "authorization_registered_at": "2026-10-13T05:58:52Z",
            "automatic_retries": 0,
            "billable_elapsed_hours_at_confirmation": 18.389022620386548,
            "credentials_upload": false,
            "cumulative_budget_cap_hours": 28.389022620386548,
            "cumulative_cap_rule": "billable elapsed at confirmation plus 10 usable hours; original start and cost retained",
            "exclude_verified_stopped_seconds": false,
            "external_B0_rows": 9,
            "imported_technical_fits": 2,
            "increase_to_cumulative_cap_hours": 18.389022620386548,
            "new_fit_limit": 18,
            "new_technical_fits": 0,
            "original_costs_and_start_preserved": true,
            "original_started_at": "2026-10-12T11:35:22Z",
            "previous_budget_cap_hours": 10,
            "question_item_id": "[\"request_user_input_async\",\"call_578e14a3688e44ceb830eca4cb4101ff\",0]",
            "queue_time_policy": "exclude_resource_wait",
            "raw_eeg_X_upload": false,
            "research_id": "sgr_r1",
            "schema": "sgr_repair2_budget_extension_v1",
            "source_run_id": "2026-10-12_dbconformer_sgr_r1_repair1_lab10_r1-full-w1",
            "usable_hours_from_confirmation": 10,
            "user_answer": "新增10小时，补原18项（推荐）",
            "verified_queue_seconds_preserved": 9.518566608428955
          }
        ],
        "campaign_id": "dbconformer-v3-20261012-sgr-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/sgr_r1/AUTHORIZATION.md",
          "campaign_id": "dbconformer-v3-20261012-sgr-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-12T11:50:04.678331+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "source-subject-risk-weighted-training-v01"
            ],
            "allowed_stages": [
              "source_subject_risk_clean_screen"
            ],
            "data_scope_id": "BNCI2014001-cue0_4s-loso-exposed9-seed0-exploratory",
            "question_id": "source-risk-weighting-beyond-balanced-batches"
          },
          "source_sha256": "7f1d682ff5a96eb8673c6dcd1e00705530957197f2b0218a4a9b643a09fdc23b"
        },
        "governance_chain_id": "dbconformer-transaction-v3.1",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-12_dbconformer_sgr_r1_repair1_lab10_r1-full-w1": {
            "contract_sha256": "5091b8cf174db750ee6f62917bd198a393624ebf14ce7330b9f04ef118302af7",
            "queue_seconds": 9.518566608428955,
            "run_id": "2026-10-12_dbconformer_sgr_r1_repair1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-sgr-r1-repair1-tx"
          },
          "2026-10-13_dbconformer_sgr_r1_repair3_lab10_r1-full-w1": {
            "contract_sha256": "71afd160c4e26fbbab5d62e73e1c9c6b8d1579845d182a56d80c8bf9f5300863",
            "queue_seconds": 9.40251874923706,
            "run_id": "2026-10-13_dbconformer_sgr_r1_repair3_lab10_r1-full-w1",
            "transaction_id": "dbconformer-sgr-r1-repair3-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INSUFFICIENT_SOURCE_SUBJECT_RISK_DUAL_UTILITY_SUPPORT",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-sgr-r1-repair3_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-dbconformer-sgr-r1-repair3",
            "recorded_at": "2026-10-13T13:19:12.571021+00:00",
            "round_id": "dbconformer-sgr-r1-repair3"
          }
        ],
        "started_at": "2026-10-12T11:35:22Z"
      },
      "closed_at": "2026-10-14T00:03:53.135445+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.3454861111111112,
                -1.3454861111111112
              ],
              [
                -2.4522569444444446,
                -2.4522569444444446
              ],
              [
                -1.6710069444444444,
                -1.6710069444444444
              ],
              [
                -2.170138888888889,
                -2.170138888888889
              ],
              [
                -2.756076388888889,
                -2.756076388888889
              ],
              [
                -2.5390625,
                -2.5390625
              ],
              [
                -1.8229166666666667,
                -1.8229166666666667
              ],
              [
                -1.8012152777777777,
                -1.8012152777777777
              ],
              [
                -0.6293402777777778,
                -0.6293402777777778
              ]
            ],
            "mean_delta_pp": -1.9097222222222223,
            "mean_interval_pp": [
              -1.9097222222222223,
              -1.9097222222222223
            ],
            "pass": false,
            "positive_subject_count_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                -6.423611111111111,
                -6.423611111111111
              ],
              [
                2.4305555555555554,
                2.4305555555555554
              ],
              [
                -3.8194444444444446,
                -3.8194444444444446
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                4.861111111111111,
                4.861111111111111
              ],
              [
                3.125,
                3.125
              ],
              [
                -2.6041666666666665,
                -2.6041666666666665
              ],
              [
                -2.7777777777777777,
                -2.7777777777777777
              ],
              [
                -12.152777777777779,
                -12.152777777777779
              ]
            ],
            "worst_subject_interval_pp": [
              -12.152777777777779,
              -12.152777777777779
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.1501736111111112,
                -1.1501736111111112
              ],
              [
                -0.6944444444444444,
                -0.6944444444444444
              ],
              [
                -0.3472222222222222,
                -0.3472222222222222
              ],
              [
                -1.4973958333333333,
                -1.4973958333333333
              ],
              [
                -0.8029513888888888,
                -0.8029513888888888
              ],
              [
                -1.7144097222222223,
                -1.7144097222222223
              ],
              [
                -0.3472222222222222,
                -0.3472222222222222
              ],
              [
                0.08680555555555555,
                0.08680555555555555
              ],
              [
                0.7378472222222222,
                0.7378472222222222
              ]
            ],
            "mean_delta_pp": -0.6365740740740741,
            "mean_interval_pp": [
              -0.6365740740740741,
              -0.6365740740740741
            ],
            "pass": false,
            "positive_subject_count_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "subject_delta_intervals_pp": [
              [
                3.4722222222222223,
                3.4722222222222223
              ],
              [
                -0.1736111111111111,
                -0.1736111111111111
              ],
              [
                -2.951388888888889,
                -2.951388888888889
              ],
              [
                6.25,
                6.25
              ],
              [
                0.6944444444444444,
                0.6944444444444444
              ],
              [
                7.986111111111111,
                7.986111111111111
              ],
              [
                -2.951388888888889,
                -2.951388888888889
              ],
              [
                -6.423611111111111,
                -6.423611111111111
              ],
              [
                -11.631944444444445,
                -11.631944444444445
              ]
            ],
            "worst_subject_interval_pp": [
              -11.631944444444445,
              -11.631944444444445
            ]
          }
        },
        "decision": "INSUFFICIENT_SOURCE_SUBJECT_RISK_DUAL_UTILITY_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; exploratory only, not independent confirmation, significance, mechanism proof, novelty, or paper readiness.",
        "reason": "at least one required comparison fails a determinate frozen utility gate",
        "round_id": "dbconformer-sgr-r1-repair3"
      },
      "closing_round": "dbconformer-sgr-r1-repair3",
      "closing_run": {
        "artifact_manifest_sha256": "d65c3ec44dfcbd3fd544964079112207fa3a4276de66ee4e30f7dbd4dc82e396",
        "contract_sha256": "71afd160c4e26fbbab5d62e73e1c9c6b8d1579845d182a56d80c8bf9f5300863",
        "intake_path": "results/logs/remote/2026-10-13_dbconformer_sgr_r1_repair3_lab10_r1-full-w1",
        "run_id": "2026-10-13_dbconformer_sgr_r1_repair3_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-sgr-r1-repair3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User confirmed SCR new10h single20fit round; external9B0; retain prior evidence/costs and no extra retries/seeds/tuning/next round",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/scr_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "8d7b1312ae334b026f35a3ce3f54a7e5438e08e8ba3b32b52624519b4f2c5898"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 28.389022620386548,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-12T11:35:22Z"
      }
    },
    {
      "campaign_id": "dbconformer-v3-20261014-scr-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User confirmed SCR new10h single20fit round; external9B0; retain prior evidence/costs and no extra retries/seeds/tuning/next round",
        "budget_extensions": [
          {
            "automatic_retries": 0,
            "billable_hours_at_confirmation": 9.281203823426864,
            "confirmed_at": "2026-10-14T09:06:05.122561+00:00",
            "cumulative_budget_cap_hours": 19.281203823426864,
            "external_B0": 9,
            "extra_seed_candidate_tuning_next_round": false,
            "imported_technical_fits": 2,
            "maximum_rounds": 1,
            "new_fit_limit": 18,
            "new_technical_fits": 0,
            "old_started_at": "2026-10-13T23:48:56+00:00",
            "original_costs_and_start_preserved": true,
            "previous_budget_cap_hours": 10.0,
            "queue_time_policy": "exclude_resource_wait",
            "research_id": "scr_r1",
            "source_run_id": "2026-10-14_dbconformer_scr_r1_lab10_r1-full-w1",
            "usable_hours_from_confirmation": 10,
            "user_answer": "新增10小时，补原18项（推荐）"
          },
          {
            "authorization_ref": {
              "path": "ai4s/programs/dbconformer/research/scr_r1_parallel_repair1/BUDGET_AUTHORIZATION.json",
              "sha256": "84265a0b42c8e3af71b59a0d0875ecef8bc8c13aa3c7e7e1b2adf01a0f3f8b85"
            },
            "automatic_retries": 0,
            "confirmed_at": "2026-10-14T17:42:48.563720+00:00",
            "contract_ref": {
              "path": "ai4s/programs/dbconformer/research/dbconformer-scr-r1-parallel-repair1.yaml",
              "sha256": "8d215fce2664e10fc72baf8b3f63700d8e63054d713fb7c8f8570339f9ccf38e"
            },
            "cpu_qualification_ref": {
              "path": "ai4s/programs/dbconformer/research/scr_r1_parallel_repair1/REMOTE_CPU_QUALIFICATION.json",
              "sha256": "959e882951d76a388ec6bdafcda63ce5262901c5850bba83cc289c31bbe3a286"
            },
            "cumulative_budget_cap_hours": 25.281203823426864,
            "existing_scientific_closure": 18,
            "external_B0": 9,
            "extra_seed_candidate_tuning_next_round": false,
            "first_attempt_fits": 5,
            "imported_technical_fits": 2,
            "maximum_rounds": 1,
            "new_fit_limit": 7,
            "new_technical_fits": 0,
            "old_started_at": "2026-10-13T23:48:56+00:00",
            "original_costs_and_start_preserved": true,
            "parallel_recovery_run_id": "2026-10-15_dbconformer_scr_r1_parallel_repair1_lab10_r1-full-w1",
            "previous_budget_cap_hours": 19.281203823426864,
            "queue_time_policy": "wall_clock",
            "replacement_attempts": 2,
            "research_id": "scr_r1",
            "source_live_identity_ref": {
              "path": "ai4s/programs/dbconformer/research/scr_r1_parallel_repair1/SOURCE_LIVE_IDENTITIES.json",
              "sha256": "ee9172a1e63150b50cf9aa7b6628d8286b869f73b5441b40c2e2289025a28b4b"
            },
            "source_run_id": "2026-10-14_dbconformer_scr_r1_deploy2_lab10_r1-full-w1",
            "usable_hours_from_confirmation": 6.0,
            "user_answer": "追加6小时，启动原七项补跑（推荐）",
            "verified_pure_queue_seconds": 538.8113858699799
          },
          {
            "authorization_ref": {
              "path": "ai4s/programs/dbconformer/research/scr_r1_shared_repair2/BUDGET_AUTHORIZATION.json",
              "sha256": "ff8590e2c2639bb7cc8b325cef87b338f5f648902d12788b8ec8ed7dbc996c77"
            },
            "available_new_seconds": 21600,
            "cumulative_budget_cap_hours": 31.281203823426864,
            "execution_start_epoch": 1792040459.7846107,
            "new_run_id": "2026-10-15_dbconformer_scr_r1_shared_repair2_lab10_r1-full-w1",
            "old_costs_preserved": true,
            "old_started_at": "2026-10-13T23:48:56+00:00",
            "previous_budget_cap_hours": 25.281203823426864,
            "pure_queue_accounting": "ONLY_CONTINUOUSLY_VERIFIED_NEW_RUN_WAIT",
            "source_run_id": "2026-10-15_dbconformer_scr_r1_parallel_repair1_lab10_r1-full-w1"
          }
        ],
        "budget_policy": {
          "exclude_verified_stopped_seconds": true
        },
        "campaign_id": "dbconformer-v3-20261014-scr-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/scr_r1/AUTHORIZATION.md",
          "campaign_id": "dbconformer-v3-20261014-scr-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-14T00:03:56.296029+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "source-coherent-segment-recombination-v01"
            ],
            "allowed_stages": [
              "source_coherent_augmentation_clean_screen"
            ],
            "data_scope_id": "BNCI2014001-cue0_4s-loso-exposed9-seed0-exploratory",
            "question_id": "source-coherent-recombination-beyond-fragment-marginal-control"
          },
          "source_sha256": "36cb952cc6f9bbd66221eafcf32edf6d8380e3e3c7d7b6ede76bb36e30861c8b"
        },
        "governance_chain_id": "dbconformer-transaction-v3.1",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-14_dbconformer_scr_r1_deploy1_lab10_r1-full-w1": {
            "contract_sha256": "1a686632c43859fe14b9ec86038eedc1676f715d196d095382f8ccb69f254d79",
            "queue_seconds": 0.0,
            "run_id": "2026-10-14_dbconformer_scr_r1_deploy1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-scr-r1-deploy1-tx"
          },
          "2026-10-14_dbconformer_scr_r1_deploy2_lab10_r1-full-w1": {
            "contract_sha256": "0485385123f6600921db7ec898790180d10e5f52a1ad37dadf5d494f32f74b84",
            "queue_seconds": 0.0,
            "run_id": "2026-10-14_dbconformer_scr_r1_deploy2_lab10_r1-full-w1",
            "transaction_id": "dbconformer-scr-r1-deploy2-tx"
          },
          "2026-10-14_dbconformer_scr_r1_lab10_r1-full-w1": {
            "contract_sha256": "d837a5b38344cdfe0a50fc7bfc63d0b619d1d99002e43e920dc203415a68f425",
            "queue_seconds": 16.7887966632843,
            "run_id": "2026-10-14_dbconformer_scr_r1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-scr-r1-tx"
          },
          "2026-10-14_dbconformer_scr_r1_repair1_lab10_r1-full-w1": {
            "contract_sha256": "5b1b2e3dfa9f9d6a0ee1c8ef111924a910f18a75b1d9541a07d93caff37198e7",
            "queue_seconds": 522.0225892066956,
            "run_id": "2026-10-14_dbconformer_scr_r1_repair1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-scr-r1-repair1-tx"
          },
          "2026-10-15_dbconformer_scr_r1_shared_repair2_lab10_r1-full-w1": {
            "contract_sha256": "ec14821857c02143bd1fb8ca63214f0172f42fed0f0db43c58be9b03db5639da",
            "evidence_ref": {
              "path": "ai4s/programs/dbconformer/research/scr_r1_shared_repair2/COMPLETION_RECEIPT_20261015.json",
              "sha256": "da79abcbdd3a90eac378d6d87d8f2f0d5e84bb223a1aed6763b73420f7c179a8"
            },
            "policy": "CONSERVATIVE_CONTINUOUS_FRESH_QUEUE_ONLY_WITHOUT_ANY_LIVE_FIT",
            "queue_seconds": 6.51574969291687,
            "run_id": "2026-10-15_dbconformer_scr_r1_shared_repair2_lab10_r1-full-w1",
            "transaction_id": "dbconformer-scr-r1-shared-repair2-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INSUFFICIENT_SOURCE_COHERENT_RECOMBINATION_DUAL_UTILITY_SUPPORT",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-scr-r1-merged-closeout_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-SCR-R1-MERGED-20261015",
            "recorded_at": "2026-10-15T09:41:41.544736+00:00",
            "round_id": "dbconformer-scr-r1-merged-closeout"
          }
        ],
        "started_at": "2026-10-13T23:48:56+00:00",
        "stopped_accounting": [
          {
            "authorization_ref": "ai4s/programs/dbconformer/research/scr_r1_shared_repair2/BUDGET_AUTHORIZATION.json",
            "end": 1792040459.7846107,
            "evidence_ref": "ai4s/programs/dbconformer/research/scr_r1_parallel_repair1/STOPPED_RECONCILIATION_20261015T044253156215Z.json",
            "reason": "OLD_RUN_STOPPED_AT_CAP_UNTIL_NEW_RECOVERY_START_NO_GPU_FITS",
            "source_run_id": "2026-10-15_dbconformer_scr_r1_parallel_repair1_lab10_r1-full-w1",
            "start": 1792026878.4555843
          }
        ]
      },
      "closed_at": "2026-10-15T11:50:36.492280+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.1519097222222222,
                -0.1519097222222222
              ],
              [
                -0.8897569444444444,
                -0.8897569444444444
              ],
              [
                -0.9114583333333334,
                -0.9114583333333334
              ],
              [
                -1.5625,
                -1.5625
              ],
              [
                -1.7578125,
                -1.7578125
              ],
              [
                -1.9748263888888888,
                -1.9748263888888888
              ],
              [
                -1.171875,
                -1.171875
              ],
              [
                -1.953125,
                -1.953125
              ],
              [
                -1.4322916666666667,
                -1.4322916666666667
              ]
            ],
            "mean_delta_interval_pp": [
              -1.3117283950617284,
              -1.3117283950617284
            ],
            "pass": false,
            "positive_subjects_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -10.590277777777779,
              -10.590277777777779
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.06510416666666667,
                0.06510416666666667
              ],
              [
                0.2170138888888889,
                0.2170138888888889
              ],
              [
                0.6727430555555556,
                0.6727430555555556
              ],
              [
                -0.1736111111111111,
                -0.1736111111111111
              ],
              [
                -1.3454861111111112,
                -1.3454861111111112
              ],
              [
                -1.1935763888888888,
                -1.1935763888888888
              ],
              [
                0.6727430555555556,
                0.6727430555555556
              ],
              [
                -0.9114583333333334,
                -0.9114583333333334
              ],
              [
                0.4340277777777778,
                0.4340277777777778
              ]
            ],
            "mean_delta_interval_pp": [
              -0.1736111111111111,
              -0.1736111111111111
            ],
            "pass": false,
            "positive_subjects_interval": [
              3,
              3
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -6.944444444444445,
              -6.944444444444445
            ]
          }
        },
        "decision": "INSUFFICIENT_SOURCE_COHERENT_RECOMBINATION_DUAL_UTILITY_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; exploratory only, not independent confirmation, significance, mechanism proof, novelty, or paper readiness.",
        "reason": "at least one required comparison fails a determinate frozen utility gate",
        "round_id": "dbconformer-scr-r1"
      },
      "closing_round": "dbconformer-scr-r1",
      "closing_run": {
        "analysis_ref": {
          "path": "ai4s/programs/dbconformer/research/scr_r1_shared_repair2/MERGED_ANALYSIS.json",
          "sha256": "e4c60c31e5ce211d4e745a38d3a362f46c9b08195e1e7edfae37820399cab463"
        },
        "intake_root": "./ai4s\\programs\\dbconformer\\research\\scr_r1_shared_repair2\\merged_intake_r2\\view",
        "source_run_ids": [
          "2026-10-14_dbconformer_scr_r1_deploy2_lab10_r1-full-w1",
          "2026-10-14_dbconformer_scr_r1_repair1_lab10_r1-full-w1",
          "2026-10-15_dbconformer_scr_r1_shared_repair2_lab10_r1-full-w1"
        ],
        "verification_ref": {
          "path": "ai4s/programs/dbconformer/research/scr_r1_shared_repair2/MERGED_VERIFICATION.json",
          "sha256": "3949a91499f95bb6c090bdfdad269171187b43de5fa873ca3a3133898e874167"
        },
        "verification_type": "multi_run_union",
        "verified": true
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User confirmed FSC single2TECH+18science new10usable hours; retain FSC prep origin and old SCR cost; external9B0; no retries/seed/tuning/next round",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/fsc_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "c9c92c49aa5f3d526196ea31dcc79a4439647ffc50fc96bfd3ec8a16d557b603"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 31.281203823426864,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-13T23:48:56+00:00"
      }
    },
    {
      "campaign_id": "dbconformer-v3-20261015-fsc-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User confirmed FSC single2TECH+18science new10usable hours; retain FSC prep origin and old SCR cost; external9B0; no retries/seed/tuning/next round",
        "budget_extensions": [
          {
            "additional_usable_seconds": 36000,
            "all_previous_campaign_costs_preserved": true,
            "automatic_retries": 0,
            "billable_seconds_at_confirmation": 4555.758,
            "budget_policy": "original preparation origin retained; exclude only verified pure resource wait",
            "confirmed_at": "2026-10-15T11:46:19.232000+00:00",
            "cumulative_budget_cap_hours": 11.265488333333334,
            "external_B0": 9,
            "extra_seeds_candidates_tuning_next_round": false,
            "maximum_rounds": 1,
            "new_fit_limit": 20,
            "new_scientific_fits": 18,
            "new_technical_fits": 2,
            "original_research_started_at": "2026-10-15T10:30:23.474000+00:00",
            "question_item_id": "[\"request_user_input_async\",\"call_e225213753a74bd39c36fbf6fe549103\",0]",
            "scientific_ceiling_seconds": 21600,
            "technical_ceiling_seconds": 7200,
            "timestamp_source": "current conversation user response timestamps",
            "user_answer": "新增10小时，启动单轮 FSC-R1（推荐）",
            "verified_queue_seconds_at_confirmation": 0
          },
          {
            "accepted_stopped_seconds": 27330.467861890793,
            "additional_cap_hours": 4,
            "authorization_ref": "ai4s/programs/dbconformer/research/fsc_r1_repair1/AUTHORIZATION.json",
            "automatic_retries": 0,
            "cumulative_budget_cap_hours": 15.265488333333334,
            "new_fit_limit": 3,
            "new_nonfit_gate_tasks": 1,
            "new_run_id": "2026-10-16_dbconformer_fsc_r1_repair1_lab10_r1-full-w1",
            "old_costs_preserved": true,
            "previous_cumulative_cap_hours": 11.265488333333334,
            "retained_scientific": 15,
            "retained_technical": 2,
            "source_run_id": "2026-10-15_dbconformer_fsc_r1_lab10_r1-full-w1",
            "stopped_accounting_ref": "ai4s/programs/dbconformer/research/fsc_r1_repair1/BUDGET_PROPOSAL.json"
          }
        ],
        "budget_policy": {
          "exclude_verified_stopped_seconds": true
        },
        "campaign_id": "dbconformer-v3-20261015-fsc-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/fsc_r1_repair1/AUTHORIZATION.json",
          "campaign_id": "dbconformer-v3-20261015-fsc-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-16T03:05:52.003579+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "band-energy-channel-embedding-v01"
            ],
            "allowed_stages": [
              "frequency_grouping_joint_clean_screen"
            ],
            "data_scope_id": "BNCI2014001-cue0_4s-loso-exposed9-seed0-exploratory",
            "question_id": "contiguous-frequency-energy-vs-dispersed-frequency-groups-in-original-host"
          },
          "source_sha256": "a7439333b48de2fe693d8f77187055ebe7a28f8006c7c274ff4846bd16620a55"
        },
        "extensions": [
          {
            "additional_hours": 15.0,
            "authorized_at": "2026-10-16T17:01:45.532463+00:00",
            "budget_argument_semantics": "night_budget_hours is the new cumulative campaign total, not an increment",
            "new_max_rounds": 1,
            "new_night_budget_hours": 30.2654883333333,
            "previous_max_rounds": 1,
            "previous_night_budget_hours": 15.265488333333334,
            "reason": "User explicitly approved +15h cumulative30.265488333333334 for same FSC repair1 original3 fits only; preserve origin costs stopped credit and all frozen science; source ai4s/programs/dbconformer/research/fsc_r1_repair1/AUTHORIZATION_EXTENSION_20261017.json"
          }
        ],
        "governance_chain_id": "dbconformer-transaction-v3.1",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-15_dbconformer_fsc_r1_lab10_r1-full-w1": {
            "contract_sha256": "c3a7b9a0365039bf7a1b42778c55b1bdb8b1ea62b1bb0ce6b7d72d6e1eb6c895",
            "queue_seconds": 1326.4641633033752,
            "run_id": "2026-10-15_dbconformer_fsc_r1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-fsc-r1-tx"
          },
          "2026-10-16_dbconformer_fsc_r1_repair1_lab10_r1-full-w1": {
            "contract_sha256": "778e2b7a67e19f2a97bfa4af4739da505a5ce9ffb20866e00f9613bb69c20585",
            "queue_seconds": 3577.745524406433,
            "run_id": "2026-10-16_dbconformer_fsc_r1_repair1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-fsc-r1-repair1-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INSUFFICIENT_FREQUENCY_GROUPING_DUAL_UTILITY_SUPPORT",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-fsc-r1-joint-closeout_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-FSC-R1-JOINT-20261017",
            "recorded_at": "2026-10-17T04:17:36.181536+00:00",
            "round_id": "dbconformer-fsc-r1-joint-closeout",
            "scientific_anchor_round": "dbconformer-fsc-r1"
          }
        ],
        "started_at": "2026-10-15T10:30:23.474000+00:00",
        "stopped_accounting": [
          {
            "authorization_ref": "ai4s/programs/dbconformer/research/fsc_r1_repair1/AUTHORIZATION.json",
            "authorization_sha256": "a7439333b48de2fe693d8f77187055ebe7a28f8006c7c274ff4846bd16620a55",
            "credit_basis": "user_accepted_terminal_to_first_inspection_lifecycle_evidence",
            "end": "2026-10-16T01:09:17.487+00:00",
            "evidence_ref": "ai4s/programs/dbconformer/research/fsc_r1_repair1/BUDGET_PROPOSAL.json",
            "evidence_sha256": "4204a7bef05c6d298718fcc9e87dcad8d7e9a38a13f650812933dc62a473fc6f",
            "historical_continuous_monitoring_available": false,
            "source_run_id": "2026-10-15_dbconformer_fsc_r1_lab10_r1-full-w1",
            "start": 1792085627.019138
          }
        ]
      },
      "closed_at": "2026-10-17T12:14:44.106046+00:00",
      "closing_decision": {
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -2.8645833333333335,
                -2.8645833333333335
              ],
              [
                -3.1901041666666665,
                -3.1901041666666665
              ],
              [
                -3.1684027777777777,
                -3.1684027777777777
              ],
              [
                -3.515625,
                -3.515625
              ],
              [
                -3.537326388888889,
                -3.537326388888889
              ],
              [
                -3.884548611111111,
                -3.884548611111111
              ],
              [
                -3.6024305555555554,
                -3.6024305555555554
              ],
              [
                -2.34375,
                -2.34375
              ],
              [
                -2.5390625,
                -2.5390625
              ]
            ],
            "mean_delta_interval_pp": [
              -3.1828703703703702,
              -3.1828703703703702
            ],
            "pass": false,
            "positive_subjects_interval": [
              2,
              2
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -9.895833333333334,
              -9.895833333333334
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -2.2786458333333335,
                -2.2786458333333335
              ],
              [
                -2.1050347222222223,
                -2.1050347222222223
              ],
              [
                -1.8880208333333333,
                -1.8880208333333333
              ],
              [
                -2.1484375,
                -2.1484375
              ],
              [
                -1.8663194444444444,
                -1.8663194444444444
              ],
              [
                -1.9965277777777777,
                -1.9965277777777777
              ],
              [
                -2.3871527777777777,
                -2.3871527777777777
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                -1.3020833333333333,
                -1.3020833333333333
              ]
            ],
            "mean_delta_interval_pp": [
              -1.7554012345679013,
              -1.7554012345679013
            ],
            "pass": false,
            "positive_subjects_interval": [
              5,
              5
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -17.1875,
              -17.1875
            ]
          }
        },
        "decision": "INSUFFICIENT_FREQUENCY_GROUPING_DUAL_UTILITY_SUPPORT",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; exploratory only, not independent confirmation, significance, mechanism proof, novelty, or paper readiness.",
        "reason": "at least one required comparison fails a determinate frozen utility gate",
        "round_id": "dbconformer-fsc-r1"
      },
      "closing_round": "dbconformer-fsc-r1",
      "closing_run": {
        "analysis_ref": {
          "path": "ai4s/programs/dbconformer/research/fsc_r1_repair1/joint_closure_20261017/recovery/LOCAL_JOINT_ANALYSIS.json",
          "sha256": "e3e3c5267ab598cec1467894d09a4d32c3bcd5895449096083803c99a8dea19e"
        },
        "repair_intake_root": "./results\\logs\\remote\\2026-10-16_dbconformer_fsc_r1_repair1_lab10_r1-full-w1",
        "repair_verification_marker_ref": {
          "path": "tmp/remote_download/2026-10-16_dbconformer_fsc_r1_repair1_lab10_r1-full-w1/verification.json",
          "sha256": "e107df7c81c3529d174e75b76aeaa0fde256ddaedc3b442075e496a7da96e19f"
        },
        "source_failed_run_whole_intake_verified": false,
        "source_run_ids": [
          "2026-10-15_dbconformer_fsc_r1_lab10_r1-full-w1",
          "2026-10-16_dbconformer_fsc_r1_repair1_lab10_r1-full-w1"
        ],
        "verification_type": "multi_run_scientific_union",
        "verified": true
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved FSA single3TECH+27science new26usable hours; retain preparation origin and all FSC costs; external9B0;0retries/no extra seed/tuning/round",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/fsa_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "9a36d909b12f5f3424e31ac5de2afbfd0ed9198d10640ec368adfda2a0cb18fe"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 30.2654883333333,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-15T10:30:23.474000+00:00"
      }
    },
    {
      "campaign_id": "dbconformer-v3-20261017-fsa-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User approved FSA single3TECH+27science new26usable hours; retain preparation origin and all FSC costs; external9B0;0retries/no extra seed/tuning/round",
        "budget_extensions": [
          {
            "additional_usable_hours": 26,
            "additional_usable_seconds": 93600,
            "all_previous_campaign_costs_preserved": true,
            "automatic_retries": 0,
            "billable_seconds_at_confirmation": 2856.0,
            "confirmed_at": "2026-10-17T12:11:04+00:00",
            "cumulative_budget_cap_hours": 26.793333333333333,
            "external_B0": 9,
            "extra_seeds_candidates_tuning_next_round": false,
            "maximum_rounds": 1,
            "new_fit_limit": 30,
            "new_scientific_fits": 27,
            "new_technical_fits": 3,
            "original_research_started_at": "2026-10-17T11:23:28+00:00",
            "preparation_fetch_replay_analysis_reserve_seconds": 10800,
            "queue_policy": "exclude only verified pure resource wait; do not subtract other pending tasks while any task runs",
            "schema": "fsa_r1_execution_budget_authorization_v1",
            "scientific_ceiling_seconds": 75600,
            "technical_ceiling_seconds": 7200,
            "timestamp_source": {
              "started_at_unix": 1792239064,
              "thread_id": "01a11f37-2edb-7ad3-ab77-48db20b0aae7",
              "tool": "codex_app.read_thread",
              "turn_id": "01a149c5-d621-79f0-8e27-e5c678e107b1"
            },
            "transaction_ceiling_seconds": 82800,
            "user_instruction": "追加26小时，启动单轮FSA-R1，按3项完整技术训练通过后放行27项科研训练的方案执行，复用9项旧B0，保留已计准备成本和历史记录，核验的纯资源排队不计预算。",
            "verified_queue_seconds_at_confirmation": 0,
            "verified_stopped_seconds_at_confirmation": 0
          }
        ],
        "campaign_id": "dbconformer-v3-20261017-fsa-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/fsa_r1/EXECUTION_AUTHORIZATION.md",
          "campaign_id": "dbconformer-v3-20261017-fsa-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-17T12:14:46.684375+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "preserved-front-end-spectral-auxiliary-v01"
            ],
            "allowed_stages": [
              "spectral_auxiliary_joint_clean_screen"
            ],
            "data_scope_id": "BNCI2014001-cue0_4s-loso-exposed9-seed0-exploratory",
            "question_id": "preserved-frontend-spectral-auxiliary-utility-and-fixed-view-controls"
          },
          "source_sha256": "b36260abbe22a81e11a7b28b463ae4151e63af76f044091adef984f299238ddf"
        },
        "governance_chain_id": "dbconformer-transaction-v3.1",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-17_dbconformer_fsa_r1_lab10_r1-full-w1": {
            "contract_sha256": "a3edae2c07168d4c0b29051c29e77d64637d69e05d4006675cf6f581889dc1db",
            "queue_seconds": 13.082890748977661,
            "run_id": "2026-10-17_dbconformer_fsa_r1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-fsa-r1-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INSUFFICIENT_SPECTRAL_AUXILIARY_UTILITY",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-fsa-r1_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-dbconformer-fsa-r1",
            "recorded_at": "2026-10-18T04:07:19.067161+00:00",
            "round_id": "dbconformer-fsa-r1"
          }
        ],
        "started_at": "2026-10-17T11:23:28+00:00"
      },
      "closed_at": "2026-10-18T10:01:36.475731+00:00",
      "closing_decision": {
        "attribution_support": false,
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.3689236111111111,
                0.3689236111111111
              ],
              [
                -0.6076388888888888,
                -0.6076388888888888
              ],
              [
                -0.2821180555555556,
                -0.2821180555555556
              ],
              [
                -0.1519097222222222,
                -0.1519097222222222
              ],
              [
                -0.7595486111111112,
                -0.7595486111111112
              ],
              [
                -0.8680555555555556,
                -0.8680555555555556
              ],
              [
                -0.2170138888888889,
                -0.2170138888888889
              ],
              [
                0.3255208333333333,
                0.3255208333333333
              ],
              [
                0.2821180555555556,
                0.2821180555555556
              ]
            ],
            "mean_delta_interval_pp": [
              -0.21219135802469136,
              -0.21219135802469136
            ],
            "pass": false,
            "positive_subjects_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -4.861111111111111,
              -4.861111111111111
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -0.5208333333333334,
                -0.5208333333333334
              ],
              [
                -0.1519097222222222,
                -0.1519097222222222
              ],
              [
                0.08680555555555555,
                0.08680555555555555
              ],
              [
                0.2821180555555556,
                0.2821180555555556
              ],
              [
                0.021701388888888888,
                0.021701388888888888
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                0.1736111111111111,
                0.1736111111111111
              ],
              [
                1.1067708333333333,
                1.1067708333333333
              ],
              [
                -0.3038194444444444,
                -0.3038194444444444
              ]
            ],
            "mean_delta_interval_pp": [
              0.09645061728395062,
              0.09645061728395062
            ],
            "pass": false,
            "positive_subjects_interval": [
              5,
              5
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -7.986111111111111,
              -7.986111111111111
            ]
          },
          "P1-C1": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.78125,
                0.78125
              ],
              [
                1.8880208333333333,
                1.8880208333333333
              ],
              [
                1.171875,
                1.171875
              ],
              [
                1.8880208333333333,
                1.8880208333333333
              ],
              [
                1.6276041666666667,
                1.6276041666666667
              ],
              [
                1.3020833333333333,
                1.3020833333333333
              ],
              [
                1.3020833333333333,
                1.3020833333333333
              ],
              [
                2.0833333333333335,
                2.0833333333333335
              ],
              [
                1.6710069444444444,
                1.6710069444444444
              ]
            ],
            "mean_delta_interval_pp": [
              1.5239197530864197,
              1.5239197530864197
            ],
            "pass": true,
            "positive_subjects_interval": [
              6,
              6
            ],
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            },
            "worst_subject_interval_pp": [
              -2.951388888888889,
              -2.951388888888889
            ]
          }
        },
        "control_promotion_allowed": false,
        "decision": "INSUFFICIENT_SPECTRAL_AUXILIARY_UTILITY",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed 9-subject single-seed screen; exploratory only, not independent confirmation, significance, mechanism proof, novelty, or paper readiness.",
        "reason": "candidate fails the determinate independent-B0 utility screen",
        "round_id": "dbconformer-fsa-r1",
        "utility_support": false
      },
      "closing_round": "dbconformer-fsa-r1",
      "closing_run": {
        "artifact_manifest_sha256": "10773643f0950f7fed55459928fb04bbce0b2484f5c362e724640c4819243d64",
        "contract_sha256": "a3edae2c07168d4c0b29051c29e77d64637d69e05d4006675cf6f581889dc1db",
        "intake_path": "results/logs/remote/2026-10-17_dbconformer_fsa_r1_lab10_r1-full-w1",
        "run_id": "2026-10-17_dbconformer_fsa_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-fsa-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User-confirmed BSP-R1 single 30-fit scope; preserve prior costs; reuse nine B0; zero retries",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/bsp_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "3accc737939daab0f9116f78ae3b535240fa293cd0c7d8452b4e52aa7445aa7d"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 26.793333333333333,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-17T11:23:28+00:00"
      }
    },
    {
      "campaign_id": "dbconformer-v3-20261018-bsp-r1",
      "campaign_snapshot": {
        "allowed_transitions": [
          "SCREEN_NEW"
        ],
        "authorization_reason": "User-confirmed BSP-R1 single 30-fit scope; preserve prior costs; reuse nine B0; zero retries",
        "budget_extensions": [
          {
            "additional_usable_hours": 28,
            "all_previous_campaign_costs_preserved": true,
            "authorization_source": {
              "confirmed_at": "2026-10-18T09:58:54+00:00",
              "kind": "user_message",
              "message_id": "01a14e73-32ab-7e71-b1c5-954ec3dda537",
              "thread_id": "01a11f37-2edb-7ad3-ab77-48db20b0aae7",
              "timestamp_basis": "Codex read_thread current user-confirmation turn.startedAt Unix1792317534",
              "turn_id": "01a14e73-321f-7b81-b53a-a1a272706845"
            },
            "automatic_retries": 0,
            "billable_seconds_at_confirmation": 5060.594335,
            "budget_authorized": true,
            "budget_proposal_sha256": "fc8477c67be71c152270c7c78eef0dbf1f66837b29b77b18570b0514ddef21f9",
            "campaign_id": "dbconformer-v3-20261018-bsp-r1",
            "compute_matching_qualified": false,
            "confirmed_at": "2026-10-18T09:58:54+00:00",
            "cumulative_budget_cap_hours": 29.405720648611112,
            "evidence_sha256": {
              "B0_BSP_REPLAY_QUALIFICATION.json": "cf5c098f3b29c1897e986dfcf522ff8a90bd3da7b2268f79c50905b0a8551926",
              "BUDGET_PROPOSAL.json": "fc8477c67be71c152270c7c78eef0dbf1f66837b29b77b18570b0514ddef21f9",
              "DESIGN_PROVENANCE.json": "1e1f34b36ccb151311ef27dfc849ad6a2e8188b294bd9ae84f8534801a365fb3",
              "GPU_PROFILE.json": "2e1cecb37c3f9f0b184b8cbc6c189388c330011c0d911b5c3243d402e19683b9",
              "PROFILE_EVIDENCE_RECEIPT.json": "a2d735e7b2d34b664e73a764c4b235b5228cba8a8731e7cafc24ef054dd7b426",
              "REMOTE_CPU_ACCEPTANCE.json": "34510eec913357ac0241ba793a079efd9b6822498fdd6419e63229c0060a33f5",
              "RESOURCE_ESTIMATE.json": "63e5d26b6fb8feaccec8bf8b152f3ee7c302248d49b2a8b9ea60ac208484da65"
            },
            "external_B0": 9,
            "extra_seeds_candidates_tuning_next_round": false,
            "full_real_fit_lifetime_qualified": false,
            "maximum_rounds": 1,
            "new_fit_limit": 30,
            "new_scientific_fits": 27,
            "new_technical_fits": 3,
            "old_FSA_budget_transfer": false,
            "original_research_started_at": "2026-10-18T08:34:33.405665+00:00",
            "queue_time_policy": "exclude_resource_wait",
            "research_id": "bsp_r1",
            "resource_estimate_sha256": "63e5d26b6fb8feaccec8bf8b152f3ee7c302248d49b2a8b9ea60ac208484da65",
            "schema": "bsp_r1_execution_budget_authorization_v1",
            "user_instruction": "新增28小时，按已准备方案启动单轮BSP-R1",
            "verified_queue_seconds_at_confirmation": 0,
            "verified_stopped_seconds_at_confirmation": 0
          },
          {
            "authorization_ref": {
              "path": "ai4s/programs/dbconformer/research/bsp_r1_repair1/BUDGET_AUTHORIZATION.json",
              "sha256": "3bcd9d99725df93f202501e98136474ed12f953ceec497338823bb2b6945050d"
            },
            "available_new_hours": 7.0,
            "budget_origin_reset_authorized": false,
            "cumulative_budget_cap_hours": 36.40572064861111,
            "new_run_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1",
            "old_costs_preserved": true,
            "old_started_at": "2026-10-18T08:34:33.405665+00:00",
            "previous_budget_cap_hours": 29.405720648611112,
            "source_run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1",
            "stopped_interval_deduction_authorized": false
          }
        ],
        "campaign_id": "dbconformer-v3-20261018-bsp-r1",
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
          "authorization_ref": "ai4s/programs/dbconformer/research/bsp_r1/EXECUTION_AUTHORIZATION.md",
          "campaign_id": "dbconformer-v3-20261018-bsp-r1",
          "executor_id": "lab10",
          "recorded_at": "2026-10-18T10:01:41.799243+00:00",
          "research_scope": {
            "allow_new_module": false,
            "allowed_module_ids": [
              "band-specific-spatial-energy-v01"
            ],
            "allowed_stages": [
              "band_specific_spatial_energy_joint_screen"
            ],
            "data_scope_id": "bnci2014001-official-cue0-4s-loso-seed0",
            "question_id": "dbconformer-bsp-r1-band-spatial-utility"
          },
          "source_sha256": "edf8895dbc971df79cbab8bb71c3fa0cfd9e88f5fb3eaac15d9c1f17fcf862cf"
        },
        "governance_chain_id": "dbconformer-transaction-v3.1",
        "invalid_behavior": "fail_closed_without_advancing",
        "positive_signal_behavior": "pause_for_human_review",
        "purpose": "user-authorized bounded AI4S campaign",
        "queue_accounting": {
          "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1": {
            "contract_sha256": "1712d2fc73d36daa63f2e5cff2426e5675dd268b173a3573595245d69b8f4e94",
            "queue_seconds": 2.430514335632324,
            "run_id": "2026-10-18_dbconformer_bsp_r1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-bsp-r1-tx"
          },
          "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1": {
            "contract_sha256": "ab796b3782a214c801f848581401f6c2e39eafad39a1260d636e95616be564ec",
            "queue_seconds": 0.0,
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair1_lab10_r1-full-w1",
            "transaction_id": "dbconformer-bsp-r1-repair1-tx"
          },
          "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1": {
            "contract_sha256": "4bea4f548eb0bfb2d344e73552089f8ffaacd0ef2ea077958a9be1930be969e0",
            "queue_seconds": 2.496445655822754,
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair2_lab10_r1-full-w1",
            "transaction_id": "dbconformer-bsp-r1-repair2-tx"
          },
          "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1": {
            "contract_sha256": "12cdee83ad1578a1fc1b542d1d8f832978c60868d5e6cbb8d058b9f37d7c03bf",
            "queue_seconds": 37.680238008499146,
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair3_lab10_r1-full-w1",
            "transaction_id": "dbconformer-bsp-r1-repair3-tx"
          },
          "2026-10-19_dbconformer_bsp_r1_repair4_lab10_r1-full-w1": {
            "contract_sha256": "3d0fa6eed22a87595508de3921e95e2594cdabf7e6d1f349e5c948a0c1427aa7",
            "queue_seconds": 2.6305313110351562,
            "run_id": "2026-10-19_dbconformer_bsp_r1_repair4_lab10_r1-full-w1",
            "transaction_id": "dbconformer-bsp-r1-repair4-tx"
          }
        },
        "round_decisions": [
          {
            "decision": "INSUFFICIENT_BAND_SPATIAL_UTILITY",
            "decision_record": "ai4s/programs/dbconformer/research/dbconformer-bsp-r1-repair4_decision.yaml",
            "evidence_id": "AI4S-DBCONFORMER-dbconformer-bsp-r1-repair4",
            "recorded_at": "2026-10-19T10:13:25.518345+00:00",
            "round_id": "dbconformer-bsp-r1-repair4"
          }
        ],
        "started_at": "2026-10-18T08:34:33.405665+00:00"
      },
      "closed_at": "2026-10-19T13:49:13.238960+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.6727430555555556,
                0.6727430555555556
              ],
              [
                -0.5425347222222222,
                -0.5425347222222222
              ],
              [
                0.08680555555555555,
                0.08680555555555555
              ],
              [
                -0.06510416666666667,
                -0.06510416666666667
              ],
              [
                -0.6944444444444444,
                -0.6944444444444444
              ],
              [
                -0.9982638888888888,
                -0.9982638888888888
              ],
              [
                -0.4557291666666667,
                -0.4557291666666667
              ],
              [
                0.021701388888888888,
                0.021701388888888888
              ],
              [
                0.4123263888888889,
                0.4123263888888889
              ]
            ],
            "mean_delta_interval_pp": [
              -0.1736111111111111,
              -0.1736111111111111
            ],
            "pass": false,
            "positive_subjects_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -6.944444444444445,
              -6.944444444444445
            ]
          },
          "P1-C0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.4123263888888889,
                0.4123263888888889
              ],
              [
                -0.021701388888888888,
                -0.021701388888888888
              ],
              [
                0.13020833333333334,
                0.13020833333333334
              ],
              [
                0.8246527777777778,
                0.8246527777777778
              ],
              [
                0.3038194444444444,
                0.3038194444444444
              ],
              [
                0.2604166666666667,
                0.2604166666666667
              ],
              [
                0.390625,
                0.390625
              ],
              [
                0.9114583333333334,
                0.9114583333333334
              ],
              [
                0.4340277777777778,
                0.4340277777777778
              ]
            ],
            "mean_delta_interval_pp": [
              0.4050925925925926,
              0.4050925925925926
            ],
            "pass": false,
            "positive_subjects_interval": [
              7,
              7
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": true,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -3.6458333333333335,
              -3.6458333333333335
            ]
          },
          "P1-C1": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.9331597222222222,
                0.9331597222222222
              ],
              [
                0.2387152777777778,
                0.2387152777777778
              ],
              [
                1.0199652777777777,
                1.0199652777777777
              ],
              [
                1.5407986111111112,
                1.5407986111111112
              ],
              [
                0.7595486111111112,
                0.7595486111111112
              ],
              [
                0.043402777777777776,
                0.043402777777777776
              ],
              [
                -0.3255208333333333,
                -0.3255208333333333
              ],
              [
                0.9331597222222222,
                0.9331597222222222
              ],
              [
                0.5859375,
                0.5859375
              ]
            ],
            "mean_delta_interval_pp": [
              0.6365740740740741,
              0.6365740740740741
            ],
            "pass": false,
            "positive_subjects_interval": [
              4,
              4
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": true,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -6.597222222222222,
              -6.597222222222222
            ]
          }
        },
        "control_promotion_allowed": false,
        "control_support": false,
        "decision": "INSUFFICIENT_BAND_SPATIAL_UTILITY",
        "evidence_scope": "exploratory_exposed_nine_subject_single_seed_clean_utility",
        "interpretation_boundary": "One exposed nine-subject seed0 screen; exploratory only, not independent confirmation, significance, unique mechanism proof, novelty, or paper readiness.",
        "reason": "P1 fails the determinate independent-B0 utility and risk screen",
        "round_id": "dbconformer-bsp-r1-repair4",
        "utility_support": false
      },
      "closing_round": "dbconformer-bsp-r1-repair4",
      "closing_run": {
        "artifact_manifest_sha256": "cb7bd27c3e730d1b6a1653dd27809117141ac2f38baf3240143487c8a32eca9e",
        "contract_sha256": "3d0fa6eed22a87595508de3921e95e2594cdabf7e6d1f349e5c948a0c1427aa7",
        "intake_path": "results/logs/remote/2026-10-19_dbconformer_bsp_r1_repair4_lab10_r1-full-w1",
        "run_id": "2026-10-19_dbconformer_bsp_r1_repair4_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bsp-r1-repair4-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User confirmed36h single SRT40 fits,4TECH before36SCI,zero retries",
      "full_state_snapshot": {
        "path": "ai4s/programs/dbconformer/research/srt_r1/PREVIOUS_CAMPAIGN_STATE.json",
        "sha256": "7fab2908836c0070873ac5d6111d05e2543cf1ef8d1fae3dbd8085816c9489c3"
      },
      "run_control": {
        "continuation_policy_version": "evidence_to_design_v1",
        "continue_after_positive": false,
        "max_rounds": 1,
        "monitor": "blocking",
        "night_budget_hours": 36.40572064861111,
        "queue_time_policy": "exclude_resource_wait",
        "round_index": 1,
        "started_at": "2026-10-18T08:34:33.405665+00:00"
      }
    },
    {
      "campaign_id": "dbconformer-srt-r1-campaign",
      "closed_at": "2026-10-21T07:56:17.612384+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "P1-B0": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.1501736111111112,
                -1.1501736111111112
              ],
              [
                -2.0833333333333335,
                -2.0833333333333335
              ],
              [
                -1.2369791666666667,
                -1.2369791666666667
              ],
              [
                -2.8428819444444446,
                -2.8428819444444446
              ],
              [
                -2.6041666666666665,
                -2.6041666666666665
              ],
              [
                -2.8428819444444446,
                -2.8428819444444446
              ],
              [
                -2.2569444444444446,
                -2.2569444444444446
              ],
              [
                -2.0616319444444446,
                -2.0616319444444446
              ],
              [
                -2.1918402777777777,
                -2.1918402777777777
              ]
            ],
            "mean_delta_interval_pp": [
              -2.1412037037037037,
              -2.1412037037037037
            ],
            "pass": false,
            "positive_subjects_interval": [
              3,
              3
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -10.069444444444445,
              -10.069444444444445
            ]
          },
          "P1-Cpair": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                0.7595486111111112,
                0.7595486111111112
              ],
              [
                1.3671875,
                1.3671875
              ],
              [
                0.9982638888888888,
                0.9982638888888888
              ],
              [
                0.13020833333333334,
                0.13020833333333334
              ],
              [
                0.7161458333333334,
                0.7161458333333334
              ],
              [
                0.3255208333333333,
                0.3255208333333333
              ],
              [
                0.6944444444444444,
                0.6944444444444444
              ],
              [
                0.6944444444444444,
                0.6944444444444444
              ],
              [
                0.043402777777777776,
                0.043402777777777776
              ]
            ],
            "mean_delta_interval_pp": [
              0.6365740740740741,
              0.6365740740740741
            ],
            "pass": false,
            "positive_subjects_interval": [
              5,
              5
            ],
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -5.208333333333333,
              -5.208333333333333
            ]
          },
          "P1-Cpow": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.171875,
                -1.171875
              ],
              [
                -1.6927083333333333,
                -1.6927083333333333
              ],
              [
                -1.1067708333333333,
                -1.1067708333333333
              ],
              [
                -1.9097222222222223,
                -1.9097222222222223
              ],
              [
                -1.4105902777777777,
                -1.4105902777777777
              ],
              [
                -1.7144097222222223,
                -1.7144097222222223
              ],
              [
                -1.3888888888888888,
                -1.3888888888888888
              ],
              [
                -1.0633680555555556,
                -1.0633680555555556
              ],
              [
                -2.0833333333333335,
                -2.0833333333333335
              ]
            ],
            "mean_delta_interval_pp": [
              -1.5046296296296295,
              -1.5046296296296295
            ],
            "pass": false,
            "positive_subjects_interval": [
              3,
              3
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -5.034722222222222,
              -5.034722222222222
            ]
          },
          "P1-Ctime": {
            "determinate": true,
            "loo_mean_intervals_pp": [
              [
                -1.2152777777777777,
                -1.2152777777777777
              ],
              [
                -1.2152777777777777,
                -1.2152777777777777
              ],
              [
                -0.5425347222222222,
                -0.5425347222222222
              ],
              [
                -2.170138888888889,
                -2.170138888888889
              ],
              [
                -1.3888888888888888,
                -1.3888888888888888
              ],
              [
                -1.4105902777777777,
                -1.4105902777777777
              ],
              [
                -1.953125,
                -1.953125
              ],
              [
                -0.7161458333333334,
                -0.7161458333333334
              ],
              [
                -2.0616319444444446,
                -2.0616319444444446
              ]
            ],
            "mean_delta_interval_pp": [
              -1.408179012345679,
              -1.408179012345679
            ],
            "pass": false,
            "positive_subjects_interval": [
              3,
              3
            ],
            "subgates": {
              "all_loo_positive": false,
              "mean": false,
              "positive_subjects": false,
              "worst_subject": false
            },
            "worst_subject_interval_pp": [
              -8.333333333333334,
              -8.333333333333334
            ]
          }
        },
        "decision": "INSUFFICIENT_ROUTING_UTILITY",
        "evidence_scope": "exploratory_selection_used_nine_subject_single_seed",
        "interpretation_boundary": "Selection-used nine-subject single-seed exploratory screen; no independent confirmation, claim, or paper-readiness conclusion.",
        "round_id": "dbconformer-srt-r1-repair3"
      },
      "closing_round": "dbconformer-srt-r1-repair3",
      "closing_run": {
        "artifact_manifest_sha256": "e266b4d709e8b7e3a99f7d5a7006baa15f671c30a34e4b007d5afc107b1a1b27",
        "contract_sha256": "9d66d8c12fa61f3ec148f381187ed907836d367de808b80fae3b7235416a8cda",
        "intake_path": "results/logs/remote/2026-10-20_dbconformer_srt_r1_repair3_lab10_r2-full-w1",
        "run_id": "2026-10-20_dbconformer_srt_r1_repair3_lab10_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-srt-r1-repair3-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User 2026-10-21: design and launch; fixed BGC four arms, 4 TECH plus 36 SCI, zero retry, one round, new finite 18h budget"
    },
    {
      "campaign_id": "dbconformer-bgc-r1-campaign",
      "closed_at": "2026-10-22T09:17:52.165080+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "P-A": {
            "gates": {
              "mean_ge_0_5pp": false,
              "worst_ge_minus_3pp": true
            },
            "loo_mean_delta_pp": [
              0.1953125,
              -0.2604166666666667,
              -0.3472222222222222,
              0.13020833333333334,
              -0.06510416666666667,
              0.13020833333333334,
              -0.06510416666666667,
              -0.2604166666666667,
              -0.3255208333333333
            ],
            "mean_delta_pp": -0.09645061728395062,
            "pass": false,
            "positive_subjects": 4,
            "subject_delta_pp": [
              -2.4305555555555554,
              1.2152777777777777,
              1.9097222222222223,
              -1.9097222222222223,
              -0.3472222222222222,
              -1.9097222222222223,
              -0.3472222222222222,
              1.2152777777777777,
              1.7361111111111112
            ],
            "worst_subject_delta_pp": -2.4305555555555554
          },
          "P-B0": {
            "gates": {
              "mean_ge_0_5pp": true,
              "worst_ge_minus_3pp": true
            },
            "loo_mean_delta_pp": [
              1.1935763888888888,
              1.1501736111111112,
              1.4539930555555556,
              1.8663194444444444,
              0.9765625,
              1.1501736111111112,
              1.5190972222222223,
              1.5842013888888888,
              1.4322916666666667
            ],
            "mean_delta_pp": 1.3695987654320987,
            "pass": true,
            "positive_subjects": 7,
            "subject_delta_pp": [
              2.7777777777777777,
              3.125,
              0.6944444444444444,
              -2.6041666666666665,
              4.513888888888889,
              3.125,
              0.1736111111111111,
              -0.3472222222222222,
              0.8680555555555556
            ],
            "worst_subject_delta_pp": -2.6041666666666665
          },
          "P-N": {
            "gates": {
              "mean_ge_0_5pp": false,
              "worst_ge_minus_3pp": false
            },
            "loo_mean_delta_pp": [
              0.6727430555555556,
              0.5208333333333334,
              0.6944444444444444,
              0.9982638888888888,
              0.13020833333333334,
              0.08680555555555555,
              -0.2604166666666667,
              -0.8246527777777778,
              -0.10850694444444445
            ],
            "mean_delta_pp": 0.21219135802469136,
            "pass": false,
            "positive_subjects": 5,
            "subject_delta_pp": [
              -3.4722222222222223,
              -2.2569444444444446,
              -3.6458333333333335,
              -6.076388888888889,
              0.8680555555555556,
              1.2152777777777777,
              3.9930555555555554,
              8.506944444444445,
              2.7777777777777777
            ],
            "worst_subject_delta_pp": -6.076388888888889
          }
        },
        "decision": "BGC_PRIMARY_UTILITY_DIRECTIONAL_ATTRIBUTION_INCOMPLETE",
        "disposition": "primary_signal_directional_attribution_pending",
        "interpretation_boundary": "Exposed nine-subject single-seed exploratory screen; no independent confirmation, claim, or paper-readiness conclusion.",
        "round_id": "dbconformer-bgc-r1-repair2"
      },
      "closing_round": "dbconformer-bgc-r1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "44ca7fa3ed33a8fb14bb630f362d1e917f46b6c4bb2ef3a7e4145f854c94b20c",
        "contract_sha256": "1419e28b217dbb7002dce9f93844becaa72b8078df975c4cb14505df375d1910",
        "intake_path": "results/logs/remote/2026-10-21_dbconformer_bgc_r1_repair2_lab10_r1-full-w1",
        "run_id": "2026-10-21_dbconformer_bgc_r1_repair2_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bgc-r1-repair2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User EXECUTION_AUTHORIZATION.json: BAS-R1 only, 2 TECH then 36 SCI, new24h accounting since 2026-10-22T08:53:00Z, no R2"
    },
    {
      "campaign_id": "dbconformer-bas-r1-campaign",
      "closed_at": "2026-10-23T03:20:35.238534+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "A-B0": {
            "gates": {
              "all_18_pairs_ge_minus_3pp": false,
              "seed1_mean_gt_0pp": false,
              "seed2_mean_gt_0pp": false,
              "subject_weighted_mean_ge_0_5pp": false
            },
            "loo_mean_delta_pp": [
              -1.638454861111111,
              -2.1809895833333335,
              -1.6601562499999998,
              -2.0507812499999996,
              -1.812065972222222,
              -1.150173611111111,
              -1.8229166666666667,
              -1.6818576388888888,
              -2.2352430555555554
            ],
            "mean_delta_pp": -1.8036265432098761,
            "pair_delta_pp": [
              {
                "delta_pp": -1.0416666666666667,
                "seed": 1,
                "subject": 0
              },
              {
                "delta_pp": -5.208333333333333,
                "seed": 2,
                "subject": 0
              },
              {
                "delta_pp": -3.298611111111111,
                "seed": 1,
                "subject": 1
              },
              {
                "delta_pp": 5.729166666666667,
                "seed": 2,
                "subject": 1
              },
              {
                "delta_pp": -1.5625,
                "seed": 1,
                "subject": 2
              },
              {
                "delta_pp": -4.340277777777778,
                "seed": 2,
                "subject": 2
              },
              {
                "delta_pp": 1.5625,
                "seed": 1,
                "subject": 3
              },
              {
                "delta_pp": -1.2152777777777777,
                "seed": 2,
                "subject": 3
              },
              {
                "delta_pp": 0.8680555555555556,
                "seed": 1,
                "subject": 4
              },
              {
                "delta_pp": -4.340277777777778,
                "seed": 2,
                "subject": 4
              },
              {
                "delta_pp": -5.208333333333333,
                "seed": 1,
                "subject": 5
              },
              {
                "delta_pp": -8.854166666666666,
                "seed": 2,
                "subject": 5
              },
              {
                "delta_pp": -3.125,
                "seed": 1,
                "subject": 6
              },
              {
                "delta_pp": -0.1736111111111111,
                "seed": 2,
                "subject": 6
              },
              {
                "delta_pp": -1.2152777777777777,
                "seed": 1,
                "subject": 7
              },
              {
                "delta_pp": -4.340277777777778,
                "seed": 2,
                "subject": 7
              },
              {
                "delta_pp": -1.3888888888888888,
                "seed": 1,
                "subject": 8
              },
              {
                "delta_pp": 4.6875,
                "seed": 2,
                "subject": 8
              }
            ],
            "pass": false,
            "positive_subjects": 3,
            "seed_mean_delta_pp": {
              "1": -1.60108024691358,
              "2": -2.0061728395061724
            },
            "subject_mean_delta_pp": {
              "0": -3.125,
              "1": 1.215277777777778,
              "2": -2.951388888888889,
              "3": 0.17361111111111116,
              "4": -1.7361111111111112,
              "5": -7.03125,
              "6": -1.6493055555555556,
              "7": -2.7777777777777777,
              "8": 1.6493055555555556
            },
            "worst_subject_seed_delta_pp": -8.854166666666666
          }
        },
        "decision": "BAS_R1_FIXED_AUX_BENEFIT_NOT_SUPPORTED_STOP",
        "disposition": "stop_after_single_R1_screen_no_automatic_R2_or_claim",
        "interpretation_boundary": "Exposed nine-subject two-seed paired replication; supports only this fixed recipe decision, with no automatic R2 or claim.",
        "round_id": "dbconformer-bas-r1"
      },
      "closing_round": "dbconformer-bas-r1",
      "closing_run": {
        "artifact_manifest_sha256": "447bf72e5d34264588a88a7250cdd80fd4d2f22fc46f0a9cfc031dbe64bcdf08",
        "contract_sha256": "3644d238b26415a1afa40b4a246ebb629b02b779f61f057cf19c8dac0db5b958",
        "intake_path": "results/logs/remote/2026-10-22_dbconformer_bas_r1_lab10_r1-full-w1",
        "run_id": "2026-10-22_dbconformer_bas_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bas-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User explicitly authorized BNS-R1 only, 2 TECH before 36 SCI, new16h including preparation; BNS-R2 not authorized; EXECUTION_AUTHORIZATION.json"
    },
    {
      "campaign_id": "dbconformer-bns-r1-campaign",
      "closed_at": "2026-10-23T14:03:14.065184+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "P-B0": {
            "gates": {
              "all_pairs_ge_minus_3pp": false,
              "each_seed_mean_ge_minus_0_5pp": true,
              "subject_mean_ge_minus_0_5pp": true
            },
            "mean_delta_pp": 0.28935185185185186,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": 0.925925925925926,
              "4": -0.3472222222222222
            },
            "subject_mean_delta_pp": {
              "0": 0.6944444444444444,
              "1": 0.6944444444444444,
              "2": -0.1736111111111111,
              "3": 3.4722222222222223,
              "4": -3.4722222222222223,
              "5": 0.6944444444444444,
              "6": 0.3472222222222223,
              "7": -3.0381944444444446,
              "8": 3.385416666666667
            },
            "worst_subject_seed_delta_pp": -4.513888888888889
          }
        },
        "decision": "BNS_R1_SIMPLIFICATION_SCREEN_FAIL_STOP",
        "round_id": "dbconformer-bns-r1"
      },
      "closing_round": "dbconformer-bns-r1",
      "closing_run": {
        "artifact_manifest_sha256": "4cf6f5088b93f2eaf0bd7dc90cde220e4f4321375732167ef219a210d953ba63",
        "contract_sha256": "8c0682fabb6450a2a657224339fa0b2fbd0fc5d1cbdc10354e80ac97e54929d3",
        "intake_path": "results/logs/remote/2026-10-23_dbconformer_bns_r1_lab10_r1-full-w1",
        "run_id": "2026-10-23_dbconformer_bns_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-bns-r1-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized SVS-R1 new 12h budget, 1 full source-only TECH then 18 SCI, no SVS-R2; accounting begins at 2026-10-23T13:34:48.014112Z"
    },
    {
      "campaign_id": "dbconformer-svs-r1-campaign",
      "closed_at": "2026-10-24T04:59:18.483235+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "D6-F6": {
            "gates": {
              "all_pairs_ge_minus_3pp": false,
              "each_seed_positive": false,
              "mean_ge_0_5pp": false
            },
            "mean_delta_pp": -2.787422839506173,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": -2.970679012345679,
              "4": -2.604166666666666
            },
            "subject_mean_delta_pp": {
              "0": -2.951388888888889,
              "1": -0.2604166666666667,
              "2": -1.0416666666666665,
              "3": -12.586805555555555,
              "4": 3.9062500000000004,
              "5": -4.079861111111111,
              "6": -3.7326388888888884,
              "7": -3.5590277777777777,
              "8": -0.7812500000000001
            },
            "worst_pair_delta_pp": -12.847222222222221
          },
          "D6-R6": {
            "gates": {
              "all_pairs_ge_minus_3pp": false,
              "each_seed_positive": false,
              "mean_ge_0_5pp": false
            },
            "mean_delta_pp": -3.3275462962962963,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": -2.0061728395061724,
              "4": -4.64891975308642
            },
            "subject_mean_delta_pp": {
              "0": -4.774305555555555,
              "1": 0.6944444444444444,
              "2": -0.6944444444444444,
              "3": -12.239583333333334,
              "4": -0.78125,
              "5": -4.079861111111111,
              "6": -5.902777777777778,
              "7": -3.2986111111111107,
              "8": 1.1284722222222223
            },
            "worst_pair_delta_pp": -13.715277777777779
          }
        },
        "decision": "SVS_R1_SELECTION_SCREEN_FAIL_STOP",
        "round_id": "dbconformer-svs-r1-repair2"
      },
      "closing_round": "dbconformer-svs-r1-repair2",
      "closing_run": {
        "artifact_manifest_sha256": "76fe1d28d568ed548abd39d2ff14b821fad65cdb14be6a3bea64c28a68fcfa32",
        "contract_sha256": "b8948d5688b9c724c213f947ec638bc46d77fcec30a225f9eefbb79bf4c01b30",
        "intake_path": "results/logs/remote/2026-10-24_dbconformer_svs_r1_repair2_lab10_r1-full-w1",
        "run_id": "2026-10-24_dbconformer_svs_r1_repair2_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-svs-r1-repair2-tx",
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "按方案实施并启动 FCA-R1，接受有限无标签目标会话校准设定，确认新增18小时预算，先完成可行性检查和工程验收，再运行54项科学训练；FCA-R2暂不启动。"
    },
    {
      "campaign_id": "dbconformer-fca-r1-campaign",
      "closed_at": "2026-10-28T10:50:49.181595+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "E-B": {
            "gates": {
              "all_pairs_ge_minus_3pp": false,
              "each_seed_positive": true,
              "mean_ge_0_5pp": true
            },
            "mean_delta_pp": 3.5698784722222223,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": 3.0164930555555554,
              "4": 4.123263888888889
            },
            "subject_mean_delta_pp": {
              "0": 10.9375,
              "1": -2.5390625,
              "2": 3.61328125,
              "3": -2.24609375,
              "4": 2.44140625,
              "5": 8.203125,
              "6": 9.375,
              "7": 2.734375,
              "8": -0.390625
            },
            "worst_pair_delta_pp": -4.4921875
          },
          "E-D": {
            "gates": {
              "all_pairs_ge_minus_3pp": false,
              "each_seed_positive": true,
              "mean_ge_0_5pp": true
            },
            "mean_delta_pp": 1.7795138888888888,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": 0.1519097222222222,
              "4": 3.4071180555555554
            },
            "subject_mean_delta_pp": {
              "0": 10.546875,
              "1": -0.68359375,
              "2": -0.78125,
              "3": -4.00390625,
              "4": 4.4921875,
              "5": 2.83203125,
              "6": 2.5390625,
              "7": 6.93359375,
              "8": -5.859375
            },
            "worst_pair_delta_pp": -8.203125
          }
        },
        "decision": "FCA_R1_CALIBRATION_SCREEN_FAIL_STOP",
        "round_id": "dbconformer-fca-r1"
      },
      "closing_round": "dbconformer-fca-r1",
      "closing_run": {
        "analysis_receipt_sha256": "3f90c184d215ade0dbfaed716a5f0b317aa9d22045111d93d958181d67c266ec",
        "artifact_manifest_sha256": "02ebd353fc3e89b9ec7904457f9630b71df43e09f00e053a9ec5ea2451e386c9",
        "contract_sha256": "00768c87a103701c6ac753cdc0543a7fbc5aecae62361f18096ba6543b492d74",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-28_dbconformer_fca_r1_repair5_packfix80_lab10_r1-full-w1",
        "intake_scope": "analysis_v1_recovery",
        "recovery_addendum_sha256": "4a31aab5295ee3a53af4f60139082f226be31501496f91f07f146fc60b45e10d",
        "recovery_verifier_sha256": "7e4b40f7dc86a34967b315c67020fae9f8865f908de9691e4867518dcf84fa52",
        "run_id": "2026-10-28_dbconformer_fca_r1_repair5_packfix80_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-fca-r1-repair5-packfix80-tx",
        "transfer_bytes": 34378548,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized CGB-R1 design implementation and launch; 3 CPU TECH then27SCI; preserve FCA full history; accounting anchor18:00 and2h closeout; no R2",
      "full_prior_campaign_snapshot": {
        "campaign": {
          "allowed_transitions": [
            "SCREEN_NEW"
          ],
          "authorization_reason": "按方案实施并启动 FCA-R1，接受有限无标签目标会话校准设定，确认新增18小时预算，先完成可行性检查和工程验收，再运行54项科学训练；FCA-R2暂不启动。",
          "campaign_id": "dbconformer-fca-r1-campaign",
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
            "authorization_ref": "ai4s/programs/dbconformer/research/fca_r1_repair2/AUTHORIZATION.md",
            "campaign_id": "dbconformer-fca-r1-campaign",
            "executor_id": "lab10",
            "recorded_at": "2026-10-25T03:23:40.345835+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "cal32-shrink005-full-vs-diagonal-v1"
              ],
              "allowed_stages": [
                "calibration_screen"
              ],
              "data_scope_id": "bnci001-exposed-sessioncal32-seeds3_4",
              "question_id": "dbconformer-finite-calibration-covariance-value"
            },
            "source_sha256": "28745a6faf8e1a305d82b21a4188b6ab82f21a8e2c85d41d7503bc9513044bf7"
          },
          "governance_chain_id": "dbconformer-transaction-v3.2",
          "invalid_behavior": "fail_closed_without_advancing",
          "positive_signal_behavior": "pause_for_human_review",
          "purpose": "user-authorized bounded AI4S campaign",
          "queue_accounting": {
            "2026-10-24_dbconformer_fca_r1_lab10_r1p1-full-w1": {
              "contract_sha256": "70aeb27a2c506bcc7d1be80f87d5919f64ba1ca80c88f9be1bb74a0fde25d979",
              "queue_seconds": 3.6021833419799805,
              "run_id": "2026-10-24_dbconformer_fca_r1_lab10_r1p1-full-w1",
              "transaction_id": "dbconformer-fca-r1-tx"
            },
            "2026-10-24_dbconformer_fca_r1_lab10_r1p2-full-w1": {
              "contract_sha256": "09580e677994aa3a9098943202ef83bf927fff0c38816848f743e57599603d3b",
              "queue_seconds": 686.0674872398376,
              "run_id": "2026-10-24_dbconformer_fca_r1_lab10_r1p2-full-w1",
              "transaction_id": "dbconformer-fca-r1-tx"
            },
            "2026-10-24_dbconformer_fca_r1_repair1_lab10_r1-full-w1": {
              "contract_sha256": "1fb7a2f3da0ec3216b021d508021ab1533db7a4d22b98b862f2c0528f7fe9364",
              "queue_seconds": 8080.700441360474,
              "run_id": "2026-10-24_dbconformer_fca_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-fca-r1-repair1-tx"
            },
            "2026-10-25_dbconformer_fca_r1_repair2_lab10_r1-full-w1": {
              "contract_sha256": "3b86fc5dd57507d357014c8b549e1afe48d8b28cfc4723740312fa3971879561",
              "queue_seconds": 37092.216574668884,
              "run_id": "2026-10-25_dbconformer_fca_r1_repair2_lab10_r1-full-w1",
              "transaction_id": "dbconformer-fca-r1-repair2-tx"
            },
            "2026-10-26_dbconformer_fca_r1_repair3_lab10_r1-full-w1": {
              "contract_sha256": "19a2bb30130fca7efb825df676318b668524a66a50f00f95a64b0c997af74008",
              "queue_seconds": 1678.3748066425323,
              "run_id": "2026-10-26_dbconformer_fca_r1_repair3_lab10_r1-full-w1",
              "transaction_id": "dbconformer-fca-r1-repair3-tx"
            },
            "2026-10-26_dbconformer_fca_r1_repair4_lab10_r1-full-w1": {
              "contract_sha256": "53a0d90f6981cb3937a4f95b425047e5ebbc507466861998234ea84f0a59085d",
              "queue_seconds": 9774.48754286766,
              "run_id": "2026-10-26_dbconformer_fca_r1_repair4_lab10_r1-full-w1",
              "transaction_id": "dbconformer-fca-r1-repair4-tx"
            },
            "2026-10-28_dbconformer_fca_r1_repair5_budget76_lab10_r1-full-w1": {
              "contract_sha256": "533a81b1f331d73342a2787a4e3793bbb4fcff86668fb1c64109f4a6798e8c18",
              "queue_seconds": 536.1061675548553,
              "run_id": "2026-10-28_dbconformer_fca_r1_repair5_budget76_lab10_r1-full-w1",
              "transaction_id": "dbconformer-fca-r1-repair5-budget76-tx"
            },
            "2026-10-28_dbconformer_fca_r1_repair5_packfix80_lab10_r1-full-w1": {
              "contract_sha256": "00768c87a103701c6ac753cdc0543a7fbc5aecae62361f18096ba6543b492d74",
              "queue_seconds": 2885.031313419342,
              "run_id": "2026-10-28_dbconformer_fca_r1_repair5_packfix80_lab10_r1-full-w1",
              "transaction_id": "dbconformer-fca-r1-repair5-packfix80-tx"
            }
          },
          "round_decisions": [
            {
              "decision": "FCA_R1_CALIBRATION_SCREEN_FAIL_STOP",
              "decision_record": "ai4s/programs/dbconformer/research/dbconformer-fca-r1_decision.yaml",
              "evidence_id": "AI4S-DBCONFORMER-dbconformer-fca-r1",
              "recorded_at": "2026-10-28T07:48:39.048246+00:00",
              "round_id": "dbconformer-fca-r1"
            }
          ],
          "started_at": "2026-10-24T04:59:18.483235+00:00"
        },
        "closure_budget_accounting": {
          "accounted_hours": 82.67377071914012,
          "accounting_started_at": "2026-10-24T12:23:48.589375+08:00",
          "all_costs_preserved": true,
          "budget_increased_this_recovery": false,
          "closed_at": "2026-10-28T15:56:30.750481+08:00",
          "elapsed_hours": 99.54504475166667,
          "interpretation": "Training completed earlier within the authorized envelope; delayed retrieval/repair/closeout wall accounting is retained, not erased.",
          "limit_hours": 80,
          "overrun_hours": 2.6737707191401228,
          "verified_queue_excluded_hours": 16.871274032526546,
          "verified_stopped_excluded_hours": 0.0
        },
        "run_control": {
          "accounting_anchor_basis": "FCA-R1 authorized preparation included; no old budget transfer",
          "continuation_policy_version": "evidence_to_design_v1",
          "continue_after_positive": false,
          "max_rounds": 1,
          "monitor": "blocking",
          "night_budget_hours": 80,
          "queue_time_policy": "exclude_resource_wait",
          "round_index": 1,
          "started_at": "2026-10-24T12:23:48.589375+08:00"
        }
      },
      "full_prior_campaign_snapshot_sha256": "7732f60dea51d0fa36e5ca6998d39113667b4acab68f359ea1ae6fc2dc4e3933"
    },
    {
      "campaign_id": "dbconformer-cgb-r1-campaign",
      "closed_at": "2026-10-28T18:31:23.858869+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "G_B": {
            "each_seed_mean_ge_minus_1pp": false,
            "each_subject_seed_ge_minus_3pp": false,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": -22.981770833333332,
              "4": -23.046875
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": -25.9765625,
                "1": -14.0625,
                "2": -38.4765625,
                "3": -18.359375,
                "4": -14.453125,
                "5": -11.1328125,
                "6": -31.8359375,
                "7": -30.6640625,
                "8": -21.875
              },
              "4": {
                "0": -26.5625,
                "1": -14.453125,
                "2": -33.59375,
                "3": -22.65625,
                "4": -14.6484375,
                "5": -10.7421875,
                "6": -30.46875,
                "7": -31.25,
                "8": -23.046875
              }
            },
            "two_seed_subject_mean_delta_pp": -23.014322916666664,
            "worst_subject_seed_delta_pp": -38.4765625
          },
          "G_D": {
            "each_seed_mean_ge_minus_1pp": false,
            "each_subject_seed_ge_minus_3pp": false,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": -24.24045138888889,
              "4": -22.157118055555557
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": -21.484375,
                "1": -14.453125,
                "2": -35.9375,
                "3": -21.484375,
                "4": -13.8671875,
                "5": -16.6015625,
                "6": -37.890625,
                "7": -25.1953125,
                "8": -31.25
              },
              "4": {
                "0": -28.7109375,
                "1": -8.3984375,
                "2": -33.59375,
                "3": -12.890625,
                "4": -15.8203125,
                "5": -12.5,
                "6": -38.0859375,
                "7": -18.9453125,
                "8": -30.46875
              }
            },
            "two_seed_subject_mean_delta_pp": -23.19878472222222,
            "worst_subject_seed_delta_pp": -38.0859375
          },
          "G_E": {
            "each_seed_mean_ge_minus_1pp": false,
            "each_subject_seed_ge_minus_3pp": false,
            "pass": false,
            "seed_mean_delta_pp": {
              "3": -18.467881944444443,
              "4": -19.639756944444443
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": -31.4453125,
                "1": -6.4453125,
                "2": -28.125,
                "3": -11.9140625,
                "4": -14.2578125,
                "5": -10.546875,
                "6": -26.7578125,
                "7": -24.21875,
                "8": -12.5
              },
              "4": {
                "0": -28.90625,
                "1": -8.3984375,
                "2": -31.25,
                "3": -11.71875,
                "4": -15.0390625,
                "5": -16.796875,
                "6": -32.421875,
                "7": -24.0234375,
                "8": -8.203125
              }
            },
            "two_seed_subject_mean_delta_pp": -19.053819444444443,
            "worst_subject_seed_delta_pp": -32.421875
          }
        },
        "decision": "CGB_R1_FIXED_REFERENCE_INSUFFICIENT_STOP",
        "reason": "fixed geometric pipeline retention rule failed",
        "round_id": "dbconformer-cgb-r1"
      },
      "closing_round": "dbconformer-cgb-r1",
      "closing_run": {
        "analysis_receipt_sha256": "350dbd0de421701d720fcbcf4b7a5107a859dc9df3041300d62534f206223e75",
        "artifact_manifest_sha256": "48b979e70b8413a9555bffe5a2c978ee6cdab7b8141ffa19721bc536e8038e19",
        "contract_sha256": "d29480d9e93b7f3bd1fce47fe08efb43acef5a0fcd447c46985f357047bb3b48",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-28_dbconformer_cgb_r1_lab10_r1-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-10-28_dbconformer_cgb_r1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-cgb-r1-tx",
        "transfer_bytes": 42138460,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User requested BCU-R1 launch; original 01:07 preparation anchor, 48h, two TECH then gated 36 SCI; immutable prelaunch packfix1 preserves all history.",
      "full_prior_campaign_snapshot": {
        "campaign": {
          "allowed_transitions": [
            "SCREEN_NEW"
          ],
          "authorization_reason": "User authorized CGB-R1 design implementation and launch; 3 CPU TECH then27SCI; preserve FCA full history; accounting anchor18:00 and2h closeout; no R2",
          "campaign_id": "dbconformer-cgb-r1-campaign",
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
            "authorization_ref": "ai4s/programs/dbconformer/research/cgb_r1/AUTHORIZATION.md",
            "campaign_id": "dbconformer-cgb-r1-campaign",
            "executor_id": "lab10",
            "recorded_at": "2026-10-28T10:51:46.347254+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "fixed-oas-tslr-bde-reference-v1"
              ],
              "allowed_stages": [
                "lightweight_reference_screen"
              ],
              "data_scope_id": "bnci001-exposed-fca-cal32-fixed-splits",
              "question_id": "dbconformer-calibration-decoder-investment"
            },
            "source_sha256": "f1f807e2641b15a0ef946239b8c6795a5b58b4b6b4bd8be06b09cc9b7cf03bda"
          },
          "governance_chain_id": "dbconformer-transaction-v3.2",
          "invalid_behavior": "fail_closed_without_advancing",
          "positive_signal_behavior": "pause_for_human_review",
          "purpose": "user-authorized bounded AI4S campaign",
          "round_decisions": [
            {
              "decision": "CGB_R1_FIXED_REFERENCE_INSUFFICIENT_STOP",
              "decision_record": "ai4s/programs/dbconformer/research/dbconformer-cgb-r1_decision.yaml",
              "evidence_id": "AI4S-DBCONFORMER-dbconformer-cgb-r1",
              "recorded_at": "2026-10-28T14:21:34.222435+00:00",
              "round_id": "dbconformer-cgb-r1"
            }
          ],
          "started_at": "2026-10-28T10:50:49.181595+00:00"
        },
        "closure_budget_accounting": {
          "accounted_hours": 82.67377071914012,
          "accounting_started_at": "2026-10-24T12:23:48.589375+08:00",
          "all_costs_preserved": true,
          "budget_increased_this_recovery": false,
          "closed_at": "2026-10-28T15:56:30.750481+08:00",
          "elapsed_hours": 99.54504475166667,
          "interpretation": "Training completed earlier within the authorized envelope; delayed retrieval/repair/closeout wall accounting is retained, not erased.",
          "limit_hours": 80,
          "overrun_hours": 2.6737707191401228,
          "verified_queue_excluded_hours": 16.871274032526546,
          "verified_stopped_excluded_hours": 0.0
        },
        "run_control": {
          "accounting_anchor_basis": "CGB-R1 AUTHORIZATION.json; preparation included; no reset",
          "continuation_policy_version": "evidence_to_design_v1",
          "continue_after_positive": false,
          "max_rounds": 1,
          "monitor": "blocking",
          "night_budget_hours": 6.0,
          "preparation_included": true,
          "queue_time_policy": "wall_clock",
          "round_index": 1,
          "started_at": "2026-10-28T18:00:00+08:00"
        }
      },
      "full_prior_campaign_snapshot_sha256": "91b1f9bec953d415e7afbd31b667db0170389648f53d0fb482a7c69e4ac53ebd"
    },
    {
      "campaign_id": "dbconformer-bcu-r1-campaign",
      "closed_at": "2026-10-29T11:35:33.026141+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "P-B": {
            "all_pairs_ge_minus_3pp": false,
            "comparison_role": "advancement_safety_gate_only",
            "main_each_seed_strictly_positive": null,
            "main_overall_ge_0_5pp": null,
            "overall_mean_delta_pp": 3.9713541666666665,
            "passes_registered_gate": false,
            "seed_mean_delta_pp": {
              "3": 3.5590277777777777,
              "4": 4.383680555555555
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": 8.0078125,
                "1": -6.640625,
                "2": 4.8828125,
                "3": 2.1484375,
                "4": -1.953125,
                "5": 5.078125,
                "6": 15.625,
                "7": 5.859375,
                "8": -0.9765625
              },
              "4": {
                "0": 7.8125,
                "1": -0.1953125,
                "2": 5.859375,
                "3": -0.390625,
                "4": 1.7578125,
                "5": 11.71875,
                "6": 5.859375,
                "7": 2.34375,
                "8": 4.6875
              }
            },
            "worst_subject_seed_delta_pp": -6.640625
          },
          "P-C0": {
            "all_pairs_ge_minus_3pp": false,
            "comparison_role": "primary",
            "main_each_seed_strictly_positive": false,
            "main_overall_ge_0_5pp": false,
            "overall_mean_delta_pp": 0.3038194444444444,
            "passes_registered_gate": false,
            "seed_mean_delta_pp": {
              "3": -0.3255208333333333,
              "4": 0.9331597222222222
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": -0.5859375,
                "1": -5.46875,
                "2": 3.515625,
                "3": -1.171875,
                "4": -3.125,
                "5": -2.734375,
                "6": 6.0546875,
                "7": -0.1953125,
                "8": 0.78125
              },
              "4": {
                "0": -4.4921875,
                "1": 0.0,
                "2": -3.515625,
                "3": 9.375,
                "4": 2.734375,
                "5": 5.2734375,
                "6": -4.6875,
                "7": -1.171875,
                "8": 4.8828125
              }
            },
            "worst_subject_seed_delta_pp": -5.46875
          },
          "P-D": {
            "all_pairs_ge_minus_3pp": false,
            "comparison_role": "advancement_safety_gate_only",
            "main_each_seed_strictly_positive": null,
            "main_overall_ge_0_5pp": null,
            "overall_mean_delta_pp": 2.1809895833333335,
            "passes_registered_gate": false,
            "seed_mean_delta_pp": {
              "3": 0.6944444444444444,
              "4": 3.6675347222222223
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": 10.9375,
                "1": -8.0078125,
                "2": 1.7578125,
                "3": -6.0546875,
                "4": 0.9765625,
                "5": -2.1484375,
                "6": 9.5703125,
                "7": 6.640625,
                "8": -7.421875
              },
              "4": {
                "0": 4.1015625,
                "1": 4.8828125,
                "2": 0.1953125,
                "3": 4.296875,
                "4": 2.9296875,
                "5": 8.203125,
                "6": -1.7578125,
                "7": 9.9609375,
                "8": 0.1953125
              }
            },
            "worst_subject_seed_delta_pp": -8.0078125
          },
          "P-E0": {
            "all_pairs_ge_minus_3pp": false,
            "comparison_role": "primary",
            "main_each_seed_strictly_positive": true,
            "main_overall_ge_0_5pp": false,
            "overall_mean_delta_pp": 0.4014756944444444,
            "passes_registered_gate": false,
            "seed_mean_delta_pp": {
              "3": 0.5425347222222222,
              "4": 0.2604166666666667
            },
            "subject_seed_delta_pp": {
              "3": {
                "0": -4.4921875,
                "1": -3.3203125,
                "2": 5.2734375,
                "3": 2.1484375,
                "4": -4.1015625,
                "5": 0.1953125,
                "6": 9.765625,
                "7": 2.734375,
                "8": -3.3203125
              },
              "4": {
                "0": -1.5625,
                "1": 1.5625,
                "2": -1.7578125,
                "3": 4.1015625,
                "4": -0.9765625,
                "5": 0.1953125,
                "6": -7.03125,
                "7": 0.0,
                "8": 7.8125
              }
            },
            "worst_subject_seed_delta_pp": -7.03125
          }
        },
        "decision": "BCU_R1_FIXED_SCREEN_GATE_NOT_MET_STOP",
        "round_id": "dbconformer-bcu-r1"
      },
      "closing_round": "dbconformer-bcu-r1",
      "closing_run": {
        "analysis_receipt_sha256": "e3a1beccf4f4bbaf7eafd73c097167963c9451d7164dc91af0e92072af8fb9c6",
        "artifact_manifest_sha256": "e836e92779bf0ac944026b0ab2d498c782d80ad6690c7cb10ffc15f8845a9d3c",
        "contract_sha256": "b8f56098d0b64a29d4bbe58e5825e3973837706943817cb9d165adbc29a2e2c4",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-29_dbconformer_bcu_r1_packfix1_lab10_r1-full-w1",
        "intake_scope": "analysis_v1_recovery",
        "recovery_addendum_sha256": "928c86a62a972dc96434a1df61bc39ce2edb668103ce706279a00bc104c754f0",
        "recovery_verifier_sha256": "628b2e5d9c9c662da3fede5b7a9e52b5e090a6b98d50451031399ada014009d3",
        "run_id": "2026-10-29_dbconformer_bcu_r1_packfix1_lab10_r1-full-w1",
        "run_status": "complete",
        "source_metadata_sha256": {
          "reference/fca_formal_receipt.json": "3f90c184d215ade0dbfaed716a5f0b317aa9d22045111d93d958181d67c266ec",
          "reference/fca_full_manifest.json": "02ebd353fc3e89b9ec7904457f9630b71df43e09f00e053a9ec5ea2451e386c9"
        },
        "supplemental_index_sha256": "3904cd29a769efeeb339d96a76f12f26ef39b657c01e96b115b8e9b84679ef7b",
        "transaction_id": "dbconformer-bcu-r1-packfix1-tx",
        "transfer_bytes": 508392035,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User approved SBN-R1 launch and six hours; preserve original preparation anchor and all prior costs, zero gradient fits, real technical gates before 54 scores, no R2"
    },
    {
      "campaign_id": "dbconformer-sbn-r1-campaign",
      "closed_at": "2026-10-29T15:13:06.773516+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "decision": "SBN_R1_FIXED_GATE_NOT_MET_STOP",
        "failed_comparisons": [
          "Preal-B0",
          "Preal-Cmix"
        ],
        "round_id": "dbconformer-sbn-r1",
        "scope": "exposed conditional screening; not independent confirmation"
      },
      "closing_round": "dbconformer-sbn-r1",
      "closing_run": {
        "analysis_receipt_sha256": "6241ad396fb1b1788dc6796c212b15081df494b9f13cb08456288b212a1c1f03",
        "artifact_manifest_sha256": "7fac57b48be6621b83d2127774f5a19dded9ef69a4b6016ce265c2b880726a4d",
        "authorization_sha256": "72e9ef9c88b23de1ba1681bf0af6e4fcda2e88685c8764611e5a313e2119fe40",
        "contract_sha256": "cbfaf7042ba906422c06ed6955020f0547786d250493003848a1ad48f457e640",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-29_dbconformer_sbn_r1_packfix1_lab10_r1-full-w1",
        "intake_scope": "analysis_v1_recovery",
        "native_analysis_v1_pass": false,
        "original_manifest_sha256": "7fac57b48be6621b83d2127774f5a19dded9ef69a4b6016ce265c2b880726a4d",
        "original_policy_sha256": "481b4833dd1556576c990f957454578b522f3b8a68a47c97a50ae137e72592bc",
        "plan_sha256": "604a95be497aaf1ef0e40f2cf40d6977d8d67caf02d61de5614ae0ed250d9997",
        "run_id": "2026-10-29_dbconformer_sbn_r1_packfix1_lab10_r1-full-w1",
        "run_status": "complete",
        "selected_closed_hashes": {
          "_recovery/SUPPLEMENTAL_INDEX.json": "efcb9e7dba15a299744c3d64e180b1a13f48cb85537254b3bb9d126e8af7b586",
          "qualification/captured_command.json": "fe345318ad04efe964722fa7d1903aa0da3c2ad2c6755d317c01423e67b74f22",
          "qualification/cost_gate.json": "705fed033c08e9d650a4143518587be79460f8ebb79c7e038028998156226617",
          "qualification/node_result.json": "a67ae058913468a62e110b19fb5a965b0153d1f6e37d50e3c9df5a4519cff6ad",
          "qualification/scheduler_lane_logs/qualification_s0_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "qualification/scheduler_metrics.json": "f286238f01ef647abe1849f5e7562c3e62d600514489e77e3c25a453abd5636c",
          "qualification/source_integrity.json": "38e44ab3b8a8fab32661c6a8a598d457eb870faa0edcffc8a397e37b47013857",
          "qualification/tasks/qualification_s0_seed3/task_result.json": "8d97f870f8e94d2d4dbc3c385663ef439024f628b92121e84161ee2c065c6be4",
          "qualification/tasks/qualification_s0_seed3/worker/buffer_audit.json": "61a912ba698eafc422f590c5994f043fadb3b7849cae89c78332dabeef060316",
          "qualification/tasks/qualification_s0_seed3/worker/source_audit.json": "56c84cbd8bdc4ec06fb01cd14ff75cd1d7236f8edeea2e48c5b23d4597dccb10",
          "qualification/tasks/qualification_s0_seed3/worker/task_manifest.json": "d2a2b3e61c3015160ff54efc010202c5ceb68663d45c184c9967aa2c1929e0a1",
          "qualification/tasks/qualification_s0_seed3/worker/task_result.json": "998be5721fe0283a24530e9241040445fd1163d5af8f8691e32d668023c0ab5a",
          "reference/B_s0_seed3/provenance.json": "808217e5c683fb5b34efbe93c27455b18765770d4300163dab7bdaee4781eae5",
          "reference/B_s0_seed3/target_predictions.npz": "e3b03ed0fcd2eae944e0a0c24c246789a6070c18b38d9fc352d8132cbc26f3f5",
          "reference/B_s0_seed3/waveform_source_stats.npz": "5a95e61371c402565745cb8504cab7abf62ccd5b8ecb149eb7115db5bb0f835b",
          "reference/B_s0_seed4/provenance.json": "2ddfc386f2772742ef4d7ca9930f56587e9b19b8d8a47a4d04ebe9f039b780ad",
          "reference/B_s0_seed4/target_predictions.npz": "d94f729486566c6a7f29e59d6aa7721e6e2ccec1de3ea94144ad994ff9d8bdbe",
          "reference/B_s0_seed4/waveform_source_stats.npz": "5a95e61371c402565745cb8504cab7abf62ccd5b8ecb149eb7115db5bb0f835b",
          "reference/B_s1_seed3/provenance.json": "82fc0881621d47941bfa68e22eec543ca30a05b32b137ee3f33671f583eff43a",
          "reference/B_s1_seed3/target_predictions.npz": "b8916a4874f628f9ea973cb308e0017d78de1a067c5ef12aae3123e165dbbf6b",
          "reference/B_s1_seed3/waveform_source_stats.npz": "bb2c7f7b660099d9ff8c1c68595158534a26577dbba2f2a2e0f3509fec066281",
          "reference/B_s1_seed4/provenance.json": "e66ebbcb76ec9fc931a7fcbd00d44a7617b534c53f728b80dc9e456c9d1c17b4",
          "reference/B_s1_seed4/target_predictions.npz": "479cc97acd1676d2fd4d8d13200753be1ff6c1b59966749c3f5d5a9b08308796",
          "reference/B_s1_seed4/waveform_source_stats.npz": "bb2c7f7b660099d9ff8c1c68595158534a26577dbba2f2a2e0f3509fec066281",
          "reference/B_s2_seed3/provenance.json": "6954a00bf873c8394782725dc663d672e54c8b2fd8bbe0189c8616484c1e6306",
          "reference/B_s2_seed3/target_predictions.npz": "540f3ad67abd65b47f2b74c41e1f3fd15cf7819751ef7b6f472f949c247f240a",
          "reference/B_s2_seed3/waveform_source_stats.npz": "3dc0299fb1292e897da9d7d4c6f3eee5cdd315ee670cb3425212afcd98fe9121",
          "reference/B_s2_seed4/provenance.json": "afd7a1915c353ace32ca3ffb9d41ee7175c52865f69408c3cc6bb9cfaac5d14c",
          "reference/B_s2_seed4/target_predictions.npz": "1f214992e4a040d5b526f038f7f16afce6dd0f905545c786274b487bcf123b54",
          "reference/B_s2_seed4/waveform_source_stats.npz": "3dc0299fb1292e897da9d7d4c6f3eee5cdd315ee670cb3425212afcd98fe9121",
          "reference/B_s3_seed3/provenance.json": "28b30b6554b75f8c1c62cfbe18fa0f9a83446d77ceac5dccb2dbb640110d04ca",
          "reference/B_s3_seed3/target_predictions.npz": "542f9fd5af532dca2835a7d40713c69332b7994be63201f33567a5f178e8ee98",
          "reference/B_s3_seed3/waveform_source_stats.npz": "82586cad3c4a7045e37bf4df837129447a2c43a9befbbeecde4fce28f995709c",
          "reference/B_s3_seed4/provenance.json": "7685d79dd40599a9b1f35bf58033d68c299c42d2e1971f341dab0677c04c894a",
          "reference/B_s3_seed4/target_predictions.npz": "26b1b867b5c3c57e9ad51a4268585e8798c12258662d1b9814ca90851e369b0a",
          "reference/B_s3_seed4/waveform_source_stats.npz": "82586cad3c4a7045e37bf4df837129447a2c43a9befbbeecde4fce28f995709c",
          "reference/B_s4_seed3/provenance.json": "4456a498472c75d4dda48bb43ecb3d79b67a87be86ca3817ac30f61f46cd6684",
          "reference/B_s4_seed3/target_predictions.npz": "3d081f37779e68f56a52ecede243522f32d5305817b61e1633d1eff65e2316f8",
          "reference/B_s4_seed3/waveform_source_stats.npz": "8b80716c43c4e7b511417a84a336ab35f8dc74e76ae8b10e1401d9f426df649e",
          "reference/B_s4_seed4/provenance.json": "0e574caa33f52d604a3ead6621091e9f02d1d4d8ef07acc0ee20953c52a2ca03",
          "reference/B_s4_seed4/target_predictions.npz": "9627fe006fdc90c312ae199e7f89e5d3b23024df5477c10cb1f425ec0a6a40d4",
          "reference/B_s4_seed4/waveform_source_stats.npz": "8b80716c43c4e7b511417a84a336ab35f8dc74e76ae8b10e1401d9f426df649e",
          "reference/B_s5_seed3/provenance.json": "96dd29bb85782c7070f93eb9714cd113f58ec0e48f91fadf5b31684037ebe863",
          "reference/B_s5_seed3/target_predictions.npz": "cde945e2c59b18219c29e636dfebf494c299dfbab6743bad757c969c40213090",
          "reference/B_s5_seed3/waveform_source_stats.npz": "be236c21ece20f796bf94355f8862bdeaaa4f3a7e6a1341b22b8f7fc3714fa17",
          "reference/B_s5_seed4/provenance.json": "a3e6364f589d8d2c80983f7258f17cd6d0bbc6de7430808ab528211aef766a90",
          "reference/B_s5_seed4/target_predictions.npz": "1cdf8d55f523eb420a062ae0260355cb53d0c691e63782a2cc671570e88de61c",
          "reference/B_s5_seed4/waveform_source_stats.npz": "be236c21ece20f796bf94355f8862bdeaaa4f3a7e6a1341b22b8f7fc3714fa17",
          "reference/B_s6_seed3/provenance.json": "9791567ad891f7cb92df23d8d64d04f7df230de717dad383de88a00ad0020406",
          "reference/B_s6_seed3/target_predictions.npz": "c35f2990a9e1fe5c09cf2d2dd71ee74758fc239ca5a36556a892d2bffc0bfaba",
          "reference/B_s6_seed3/waveform_source_stats.npz": "e861d4ed43805531ed28bd82986ebf37acca739a46594ab4dd096d29f4ad1e1a",
          "reference/B_s6_seed4/provenance.json": "e180b9b02b87319b654680236c62f55052449aa21a90ddb9a488f379a9bd2bb4",
          "reference/B_s6_seed4/target_predictions.npz": "763ab6e8a0168f596745b6c0ab4653573ff7776ccdfdfc2d90808ddc2f9322b8",
          "reference/B_s6_seed4/waveform_source_stats.npz": "e861d4ed43805531ed28bd82986ebf37acca739a46594ab4dd096d29f4ad1e1a",
          "reference/B_s7_seed3/provenance.json": "a6b4bc25e86723b8469b8b32cc66b008d4c1883d5a9aa5c007b4f931e28220fe",
          "reference/B_s7_seed3/target_predictions.npz": "aecbea53de07a79071a3c79fa23d6c2b6a987eca09758a9fd17340c1f4f9344c",
          "reference/B_s7_seed3/waveform_source_stats.npz": "77c5c2ae79274d396136bfd280509e76b8fb547f273c2c8ce8ddbe6f9f7a7a7f",
          "reference/B_s7_seed4/provenance.json": "fc09c0d8e52f64785d88d4c6c773129e7cd40667611190dcab32800289783ce8",
          "reference/B_s7_seed4/target_predictions.npz": "4a6b333e329dd7afc62de19b736c728d798ee34b77106f0ab4ab21b6662b91a3",
          "reference/B_s7_seed4/waveform_source_stats.npz": "77c5c2ae79274d396136bfd280509e76b8fb547f273c2c8ce8ddbe6f9f7a7a7f",
          "reference/B_s8_seed3/provenance.json": "e6562264d664c22d596aeb03ed227f553fa3d88b24944eb3f8317aa44883b416",
          "reference/B_s8_seed3/target_predictions.npz": "f52f89df18012d23378430cb7c890f0142e887b046673c4d9ddd89736ac40190",
          "reference/B_s8_seed3/waveform_source_stats.npz": "de565a2f78cad8b37bfceba5a7e41c375f16c97c718a1eb88117a06d269c0161",
          "reference/B_s8_seed4/provenance.json": "6a6858d34726b4cdd8d9e9b1666c2006b004bc23844ba9d8dd62a0c3d1632ad4",
          "reference/B_s8_seed4/target_predictions.npz": "c2081793d1b3ef07f2abf3fd63361119c65f9569a56442427fe25c946a23f1cf",
          "reference/B_s8_seed4/waveform_source_stats.npz": "de565a2f78cad8b37bfceba5a7e41c375f16c97c718a1eb88117a06d269c0161",
          "reference/remote_check.json": "fdf997b4f08e2008f6d51cc470fa8e7b4292e23e1678f8cd26e400aca3006102",
          "reference/remote_lineage.json": "4fe47cd7c8df9ba0d26c9b86f3a1afa78182e101c2b0478ab225e271b12855c8",
          "reference/roster.json": "73bd21fa3e24dddebd808d32b781a17a16582c098c4c32a028f1282ee0aa80d4",
          "reference/splits/s0_cal32.npz": "20cb9f8df3a385a681f15ad263892ad206017ca657ff668592f14f84aecf0ac3",
          "reference/splits/s1_cal32.npz": "425b0e2aba8c501bcc5961c9e3da863bb999764b2a1d94f8777eb6c2632911c7",
          "reference/splits/s2_cal32.npz": "a9235b54e39ec775f2ea960841face0f9597a06f0cc240819384014bd6c7f671",
          "reference/splits/s3_cal32.npz": "c1d6193b8c3a8f1a501147c90e2a95d11be7710d5efde77c0a5f77047af5fb1e",
          "reference/splits/s4_cal32.npz": "4c7da9ea0c0ef0a29edd4faa9dd93a9e99e503a9788eb4c941d627f65fc3d25c",
          "reference/splits/s5_cal32.npz": "54407498f2f0e4ffd9b1939e37c1772ef2a75b59cc7b28dca6f75d7c5c9b36a3",
          "reference/splits/s6_cal32.npz": "e488a75ba4cd39dc5cc0c85b75fd41dfe0783e62e54d4e40442fdd880e9fa085",
          "reference/splits/s7_cal32.npz": "f6cae599089c77f72be1ec2b3598f86c6a87089ab63aafc06c251b38de545d0f",
          "reference/splits/s8_cal32.npz": "20e9905c316b08c08905ec97150a2316ae20433fe8ec837949ae1e38b9594e67",
          "replay/captured_command.json": "f62eed2032380265262ccdac4e1d7a4746055ad3c21a6276e9a83066499461d8",
          "replay/node_result.json": "3685ad764294af96a1cc3dda153eecae088f12a930e638309ef1fb849a14cd84",
          "replay/replay_gate.json": "366481aaca15e4e8a5b65044ba5711dd70cbb4833d6e2c2b39f9c7fcbd8b219b",
          "replay/scheduler_lane_logs/replay_s0_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s0_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s1_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s1_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s2_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s2_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s3_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s3_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s4_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s4_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s5_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s5_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s6_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s6_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s7_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s7_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s8_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_lane_logs/replay_s8_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "replay/scheduler_metrics.json": "2d42b9ab7803e23c27717f6c87161507e77e068663fe6f989f210dce0944e243",
          "replay/source_integrity.json": "b58994425ea02e34233560099f2e0255d0f0f310512ec9957159a199c37bb244",
          "replay/tasks/replay_s0_seed3/task_result.json": "bdde015b19768f218e7f565d72cd6b176b4c72e2349ff8ec31fbef1b63da9e91",
          "replay/tasks/replay_s0_seed3/worker/predictions.npz": "c228e2cd29de81840e58c422d8cbdef0cfd0e387247bdcaf819bd2419ff0c88a",
          "replay/tasks/replay_s0_seed3/worker/task_manifest.json": "d7f4a11621546cb976070cd3efaa34ab04b2829a8aa5e33e86dbad7aa2e11f17",
          "replay/tasks/replay_s0_seed3/worker/task_result.json": "75685f60c8ff65846e4acefebbf5981cb92e9db419458561a9892787d528f146",
          "replay/tasks/replay_s0_seed4/task_result.json": "60ac98677afcdfc00b43401c525ed8fd9ff4b71419b1006eda88018016d3d028",
          "replay/tasks/replay_s0_seed4/worker/predictions.npz": "623a553c7ec8aeef8d17b82d335dc68570a3089a4aa30d726282bc930c2ffb9f",
          "replay/tasks/replay_s0_seed4/worker/task_manifest.json": "b5131bc2c1f234fc77e46ba26cf3343b917e7a1ce377b14b237449357e21fa8a",
          "replay/tasks/replay_s0_seed4/worker/task_result.json": "fbe875c7ea9c730e0757b50dee2dfc1075cf64b558ac191e5e537b0554b13aa3",
          "replay/tasks/replay_s1_seed3/task_result.json": "f51ada4d4e2f292fa6020a8fea7c5bdb9d0042afcbac30de8416d02a52c12ceb",
          "replay/tasks/replay_s1_seed3/worker/predictions.npz": "f6fb585e567605a5bc7c3b1678150b7bedbde20096b9fd502b167da39a7d46ab",
          "replay/tasks/replay_s1_seed3/worker/task_manifest.json": "76d25a96ca57e38f709ee86670dc621b58cc47c15f83dde43cbc296751a673b5",
          "replay/tasks/replay_s1_seed3/worker/task_result.json": "d380e5d2ba5c972858913b404bc4df4c0251eab37fb6519c7af29ecd9cf8830e",
          "replay/tasks/replay_s1_seed4/task_result.json": "b8990280a370c3a908cd711178b11478b071465333dd714bc2244f20808c15ba",
          "replay/tasks/replay_s1_seed4/worker/predictions.npz": "d90961c66e692e41eb496cc0b2fe8b30566f0808eb903d1b40b6013680adea4f",
          "replay/tasks/replay_s1_seed4/worker/task_manifest.json": "70a574003f179715536449c2e3d34d3fdfdf83a86b038beabbcd2fb43d426aa5",
          "replay/tasks/replay_s1_seed4/worker/task_result.json": "22e64fbfc07d9157a6368f1afd194a873e713e0cc38a4bf05b6a6f317a7ed847",
          "replay/tasks/replay_s2_seed3/task_result.json": "7d5d5a38f126feadc792dc34afe8b5bc88d445a0b01f2ae11db7cc34da7a9550",
          "replay/tasks/replay_s2_seed3/worker/predictions.npz": "c1581b56182c022d68496f9c58d1b7fd87de8ca4821c6edb8e62ebe5772156e4",
          "replay/tasks/replay_s2_seed3/worker/task_manifest.json": "005e44180c09e8fc08ce082a775e54dc9d6bdc17ecdaaeb79cf6f119791685c0",
          "replay/tasks/replay_s2_seed3/worker/task_result.json": "a71d37be366ea8aafbb02303f804ed3c9a69f7bc8d64aa55f512f834b108ebea",
          "replay/tasks/replay_s2_seed4/task_result.json": "e45bd80ffe00611f58421ce289341199bf0dc08e07b5bdf038e37d7b9af30906",
          "replay/tasks/replay_s2_seed4/worker/predictions.npz": "56564db708cf4d9474b447e43c68f074b23d571871c2116d4978636a8acb5a4a",
          "replay/tasks/replay_s2_seed4/worker/task_manifest.json": "4fd120dc02b083ef5ae12700050982053a2a05ba3abe15ee06cec1a278817aa8",
          "replay/tasks/replay_s2_seed4/worker/task_result.json": "5d60890cc5dfdf12399692c1e82ebfc3674639464d140b9674087aff0b6dd88d",
          "replay/tasks/replay_s3_seed3/task_result.json": "03cff2ff7184e0c589bd80908fffa1c2a7768830d108e623813fb8b94813dc13",
          "replay/tasks/replay_s3_seed3/worker/predictions.npz": "a2522ebf0d6134517e80fec02734f9bac0470ce22aded9d7d8f37db3933762ca",
          "replay/tasks/replay_s3_seed3/worker/task_manifest.json": "153c67dc6830265c22753d6f5d06428ef6b3e353bf9fd73f20e16f5a1863a9dd",
          "replay/tasks/replay_s3_seed3/worker/task_result.json": "0d9d94aec140fe6c03fb19c24c37a80e087e9b14c4ac985d460856f77ea49f83",
          "replay/tasks/replay_s3_seed4/task_result.json": "9ed240fc477a792f48f3065e4616045f6930f8120d85b6e610f5d98939e78aa2",
          "replay/tasks/replay_s3_seed4/worker/predictions.npz": "7f8004adb8078af09792cbd9cdad6f3e438300f560abc68064da098dbc8a77f0",
          "replay/tasks/replay_s3_seed4/worker/task_manifest.json": "3cb5e9aa55d31e0612183917c10f31ddf1601c26d3532c7824c299e88c7b3946",
          "replay/tasks/replay_s3_seed4/worker/task_result.json": "7f88bb031bd6ece4865979a88491fd2a550381e12037a5a83997fd5051c9e50a",
          "replay/tasks/replay_s4_seed3/task_result.json": "cc737c46e5e7d4894a80929147df4a90a4304aabddf2cad256a16fa5c38eac0f",
          "replay/tasks/replay_s4_seed3/worker/predictions.npz": "595b1fab440b818f62a84d75018a29b31d64696edcd82370d859a34bd4a08328",
          "replay/tasks/replay_s4_seed3/worker/task_manifest.json": "c2b749fcb528618c26b2444329360ea2e8c0aa8bff7af40b30b600ac7f755097",
          "replay/tasks/replay_s4_seed3/worker/task_result.json": "ba287d521072af815cb57b577a7040ed9738cbed573613384f5f94e2d3d5a46c",
          "replay/tasks/replay_s4_seed4/task_result.json": "ece3d5c68d7dc1126e5a40d03eee3a8b7db981e903e73c0dfc185387708f47f6",
          "replay/tasks/replay_s4_seed4/worker/predictions.npz": "02cfaecbd8d60f7996fa7e0e1305f758e67848101c9c503040e25566b7241de4",
          "replay/tasks/replay_s4_seed4/worker/task_manifest.json": "cdaf80eddf94feadd49d499e01bc3f60a99dd2f2b0f1aaed5d73ddbcce08b160",
          "replay/tasks/replay_s4_seed4/worker/task_result.json": "6ae89c5fa2e03f9f79992781296ed41ca00158108cec7734050141a753631109",
          "replay/tasks/replay_s5_seed3/task_result.json": "2858fb0ba19382a81a011735ad8a67dd7633a0a4694ee835436c160d101c05b8",
          "replay/tasks/replay_s5_seed3/worker/predictions.npz": "ac4d1108fd058f09e7101b302c2b73d28fc52003351a7a4ba112909e5abd67de",
          "replay/tasks/replay_s5_seed3/worker/task_manifest.json": "4d95ab48fe5e3ca47c1810f7d500f9ad8affd25cb43ff0390d8b96c6cf7f7369",
          "replay/tasks/replay_s5_seed3/worker/task_result.json": "9222783bbf0a1a65b3e8f16dac0adc4ccc983a6d2d538d745e865df515943de7",
          "replay/tasks/replay_s5_seed4/task_result.json": "2db8644422943adb55cc149de007047dc7cdb29dcfc01a5a35740eec3e9e7efa",
          "replay/tasks/replay_s5_seed4/worker/predictions.npz": "086416047211f47fe7f2e8f180c3e737653d8f10531763468dbf9d2822a995f1",
          "replay/tasks/replay_s5_seed4/worker/task_manifest.json": "84fe88d05c60089930cd7a0194877d76d31bfb78e3ad7f926f8d493c5077e069",
          "replay/tasks/replay_s5_seed4/worker/task_result.json": "73611c281b2d1862d81dcf05fd74d78f0cba16a8db851d7e7ec9a10ac92132ef",
          "replay/tasks/replay_s6_seed3/task_result.json": "aec13338b95b7262533141c3cc5f5d208cc6e5e5a4e707110845928330715eb9",
          "replay/tasks/replay_s6_seed3/worker/predictions.npz": "316a3535357bf2761f5c27e3ac51585f0c9518036d2f6a7a1bd2e4889f406928",
          "replay/tasks/replay_s6_seed3/worker/task_manifest.json": "4ce1742b11f482bc96012d9fc0c8556730f850d58508642db0aead38c6459c9b",
          "replay/tasks/replay_s6_seed3/worker/task_result.json": "7f9dfdde9058c934636872d90c9bd318e95d4471b5cd3c0c31528be26c87c3cb",
          "replay/tasks/replay_s6_seed4/task_result.json": "8f15ad2e5beda18404f382c56891e3ba646ccfe262ee9dcf729291cbc009e3ac",
          "replay/tasks/replay_s6_seed4/worker/predictions.npz": "f4045836819e592f61f6a92ce77f201ee37085f749596adec66c81f592efb09f",
          "replay/tasks/replay_s6_seed4/worker/task_manifest.json": "10c3923c9a4fce102b6e1cf72ae7367778ffb838376d1d546d50328f4b3557bd",
          "replay/tasks/replay_s6_seed4/worker/task_result.json": "7beddc1f1380cd25ced9f49c63e12ffe8c15a9145a0c6f683cc6fdd76eb2695a",
          "replay/tasks/replay_s7_seed3/task_result.json": "f48b6ddea8091b0745d18adb67e152af56f867defd388feb57969c3666ab0570",
          "replay/tasks/replay_s7_seed3/worker/predictions.npz": "7c81039bfe387dea00ab0b83a8e3ad3f59f813f18c9709e547ce29d8b04879be",
          "replay/tasks/replay_s7_seed3/worker/task_manifest.json": "1bbe61288477e485e3b708a77044c75a76b0527ab905d87f13ccd4f5072b9daa",
          "replay/tasks/replay_s7_seed3/worker/task_result.json": "664ba7928c8e69cb455a878df3b1eda2d68e27009da653279e2dae2cbbd6d7bf",
          "replay/tasks/replay_s7_seed4/task_result.json": "768048710cd5016264139cd390fe72a87f4da1da30510cf60d4b2be9d9f846f7",
          "replay/tasks/replay_s7_seed4/worker/predictions.npz": "c6ca20aecc83588b8d280bc48e2859666332dc22fbf51f61aeac3571fc842d74",
          "replay/tasks/replay_s7_seed4/worker/task_manifest.json": "444c64819ab1d7d7cc8786cf1d118dc1614cc0089ec2bab33f50347709cdc5dc",
          "replay/tasks/replay_s7_seed4/worker/task_result.json": "46f1af323f7dc118b3dcf80aee97c17e8821d5e91ee87461d9cfe70f49e17308",
          "replay/tasks/replay_s8_seed3/task_result.json": "631491dc0262f98075444de451aff11ad58f76a9067d4a859ea8385448bab67f",
          "replay/tasks/replay_s8_seed3/worker/predictions.npz": "ee7dc0f4cba71b07d013eb123cf09cc17e15efef20584c4e58ce9ed4a4e8009d",
          "replay/tasks/replay_s8_seed3/worker/task_manifest.json": "b22eb382492e41e0b67f870ae3f6b253da4e9166f20318be1f9217a0ee4fe346",
          "replay/tasks/replay_s8_seed3/worker/task_result.json": "ef17a8e2f3c84e6a5a676df0f792eb020c036a7fd9ed496f362748ac98ac1f80",
          "replay/tasks/replay_s8_seed4/task_result.json": "5dfd5ff525c345faf1d88820418131352ca740c34128341bc364be0934d1854a",
          "replay/tasks/replay_s8_seed4/worker/predictions.npz": "7b617507fc35ed6b469b07664c5283566d4a9d3dea97ca841998f629053a2dab",
          "replay/tasks/replay_s8_seed4/worker/task_manifest.json": "317bf192aec8b63d3f576f02ae61bf2482d61127d80669bdd4306a0bdf5a10e9",
          "replay/tasks/replay_s8_seed4/worker/task_result.json": "66f9ddd6aba6001b248edab7d1b093bee31e4e9c4a45ae8a5ef958876f784484",
          "run_status.json": "49adbbb438852e1823be00e212b8d312654e6cc9ce5da11275c821db4fa8d825",
          "science/captured_command.json": "9a80d1eef12cd3ebeada17711af8862863125fe681f7cbd82e37fd56f7128d1d",
          "science/node_result.json": "d54dd7edc02aa1d3d400ef0fa8259808c9d42781562d2900489a1f26efe942ab",
          "science/scheduler_lane_logs/science_s0_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s0_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s1_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s1_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s2_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s2_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s3_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s3_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s4_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s4_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s5_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s5_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s6_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s6_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s7_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s7_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s8_seed3.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_lane_logs/science_s8_seed4.log": "83b383c65c0ecc1b16d1d2351f1e87907236c3d76e5cd06d2f628ce144efc8a5",
          "science/scheduler_metrics.json": "7f5fa0a9527b59571167c3960a285c461a00bdbe9a6d8dd1c42b1f235d0d3ab6",
          "science/source_integrity.json": "5efc639aadfa28c909640fc7a606b3ed20abae857cdf56944b6eddb35a4263bf",
          "science/tasks/science_s0_seed3/task_result.json": "4fd6682f895fd2523abf5920882e8ad9bf036b90f3701fac406ab8a0059e53d1",
          "science/tasks/science_s0_seed3/worker/Cmix_predictions.npz": "ff412741676bdee285365a546a0eaf9f6b86d69c93fb3857537e96b0be11612b",
          "science/tasks/science_s0_seed3/worker/Preal_predictions.npz": "999a061e1eb9a72e6e5dab0ace6a16e3fa57615865eabd5362b3ed4029524790",
          "science/tasks/science_s0_seed3/worker/buffer_audit.json": "bea5519238c6034af167a8028d7c212ba66a8b02ab3dfb793abc113056d6b7af",
          "science/tasks/science_s0_seed3/worker/source_audit.json": "85ced028b93eaae912be969df19fb06329351d95614f75586c957498b4694d77",
          "science/tasks/science_s0_seed3/worker/task_manifest.json": "2fb5734e63fe5e19af0c7f3f5a8d5ad4f813a6bc161dc174c29d69777496ab1f",
          "science/tasks/science_s0_seed3/worker/task_result.json": "968ff664f22fd843e2b82d165057cbab16d06385495cbed057eaed635aac8553",
          "science/tasks/science_s0_seed4/task_result.json": "991a1ef8146f6c716dbb3405d5aafd436ff04e3be1ae916de6157483e39afffd",
          "science/tasks/science_s0_seed4/worker/Cmix_predictions.npz": "317191472659167823b30df063127c99f38fc8d184b3c6c0d0d228baa99f0ee3",
          "science/tasks/science_s0_seed4/worker/Preal_predictions.npz": "f5fd9f2845832458958ca0205a41a660b929906c030f6fad225e407f13117a66",
          "science/tasks/science_s0_seed4/worker/buffer_audit.json": "bfd420834bde3cc591b09a6c55d41cedf4794e8cd6840787e11b9954060362b0",
          "science/tasks/science_s0_seed4/worker/source_audit.json": "7ae96ad3c8cf383dd98eaa7486544b209473e94d7020e988cd188175796689fe",
          "science/tasks/science_s0_seed4/worker/task_manifest.json": "e1155f6129614179c62c5faf9fd0252f8b428419ea448aed4ccbf62f8d1f1dc7",
          "science/tasks/science_s0_seed4/worker/task_result.json": "1d53d06583ee27b3d155adcbcac2c2b7f0625b4e6c1faadd16c6e20a1aba794e",
          "science/tasks/science_s1_seed3/task_result.json": "5da78253cc101d9c999fa69e48c1251c5a475ad852170725aab4840a0e48966f",
          "science/tasks/science_s1_seed3/worker/Cmix_predictions.npz": "9915e06c5379040d50d94da53c41671bfd2bdcc8e8f4e11950ab9fbebd42d711",
          "science/tasks/science_s1_seed3/worker/Preal_predictions.npz": "2316f474b2f4584d8bfcc44bce3c9799df95f5bdcb0f7d2b6c068c3e25f754be",
          "science/tasks/science_s1_seed3/worker/buffer_audit.json": "88218978c7f2e3fb0c80ee538bbe1dc7006a4e182c1a9e2b7b5b6c46b6a61a2e",
          "science/tasks/science_s1_seed3/worker/source_audit.json": "f8a6463510bfc6d877ce25b1434b06b558b6318fe2c390e9d675040804830955",
          "science/tasks/science_s1_seed3/worker/task_manifest.json": "324008c6d60643e8ac667ec10f42e0df7b2ecfec392ed5562776e3dac5934270",
          "science/tasks/science_s1_seed3/worker/task_result.json": "3f746932a43e7bbe7b6512bf93c6f539ceed5fabdee8b62930282432b0611202",
          "science/tasks/science_s1_seed4/task_result.json": "f62b95fd1625a862b7ad9919ce8b665d33c86dd82b8796056f4fc5b6166a0311",
          "science/tasks/science_s1_seed4/worker/Cmix_predictions.npz": "2dce2587d567b41cbe9bb1d8a3eb4a5cd0f9e7bb4b3c04746216a48113614e12",
          "science/tasks/science_s1_seed4/worker/Preal_predictions.npz": "e3cc28529fec1bfa07b9c0ebff91bd9cbfa86fe2f031ec2f0f6824dbab79458f",
          "science/tasks/science_s1_seed4/worker/buffer_audit.json": "735d25468b8064faa935e66f4c994918ad32f218060859393f3bade0640489fc",
          "science/tasks/science_s1_seed4/worker/source_audit.json": "a7a8016fd5d50fe8a1ffbd617b70cf4bbc03614da081a345ff6349c2b292c2af",
          "science/tasks/science_s1_seed4/worker/task_manifest.json": "9c747ba884cc34e46f9b84fc2458daacc4a6a3cafff91f0806b893a3ba9b3b78",
          "science/tasks/science_s1_seed4/worker/task_result.json": "fc2692ff14bec1a49969e6c9f45d856a0653c2e49f30e3bbeb5b2a3c288e28bb",
          "science/tasks/science_s2_seed3/task_result.json": "a1f935c0f78cf1b45e607e464d86dfefd56d3c9c028612a50a5d2eb291bfe651",
          "science/tasks/science_s2_seed3/worker/Cmix_predictions.npz": "74694d85947b653a3c46f43454b174b9984a71882f63f2de7cb441e5475a0317",
          "science/tasks/science_s2_seed3/worker/Preal_predictions.npz": "8beb7145d5f4fb685c5e368e4d1920796f180c0b4fe1e7edb87001e6010db6f6",
          "science/tasks/science_s2_seed3/worker/buffer_audit.json": "361eb898320ae732af7b08b1a96ad7f7eb1a443841fd22d94c1ab5bcfacc71d1",
          "science/tasks/science_s2_seed3/worker/source_audit.json": "d76a09412928a560bbd032e159b65e31854b966fda82d4e6034b549452e212ee",
          "science/tasks/science_s2_seed3/worker/task_manifest.json": "f36d61c683a6d3ce0ca0edd107f6cdfa36cd8a28abb488b97468f1a0efc65d74",
          "science/tasks/science_s2_seed3/worker/task_result.json": "f85e184ffa676bb2ccb249d4eed8d2999ea4df79245644ad7f78c320b38a1b03",
          "science/tasks/science_s2_seed4/task_result.json": "32336e881a4577bdf8897a5cc685843826ce64abf56c6e7cc243a3ae758d3e04",
          "science/tasks/science_s2_seed4/worker/Cmix_predictions.npz": "44f59e7b44600cf3ad629892461f86d104e61433d1708e373c268c8aaabfc618",
          "science/tasks/science_s2_seed4/worker/Preal_predictions.npz": "71fe7686713e6a5879e875e37e9bdd65a95514bacdaf89b4a34535549a5f4356",
          "science/tasks/science_s2_seed4/worker/buffer_audit.json": "52e41376dee2515ca175bba8dd2d6916c12f56c84f0bbcbe877259ff2dda7e6c",
          "science/tasks/science_s2_seed4/worker/source_audit.json": "c725945da4d382f43cc9f45f05bf6c496bb98b66c4c42f72e646e93884e51608",
          "science/tasks/science_s2_seed4/worker/task_manifest.json": "6873ba4f26a130fc26577a0bf6f5ca1626d59c5e6ce671e04d21fffff58121ee",
          "science/tasks/science_s2_seed4/worker/task_result.json": "5905df1fede3168d1aac0323127754306b0ceacc04fd8713eef1feccd402b7c8",
          "science/tasks/science_s3_seed3/task_result.json": "c4ad944ed6b48229194952d44b37b4afa58e7c5fbb36ec2cec137ee8dac172a4",
          "science/tasks/science_s3_seed3/worker/Cmix_predictions.npz": "bcf216a49c577bb5d7d9d0081da7fa4273643cdf6e99990d14f03074159bff79",
          "science/tasks/science_s3_seed3/worker/Preal_predictions.npz": "76475a47a91b33ddfa2953130055e0c94c28f14e6ac0289aa2c35759ad8c7c93",
          "science/tasks/science_s3_seed3/worker/buffer_audit.json": "420c430c665734244e5a9bd036d478f75ca39140d29247b80a751d6ebfd31029",
          "science/tasks/science_s3_seed3/worker/source_audit.json": "be893315403445ec591d18450a742d9fece0d8ef948f874698b9b94b2dcb5f35",
          "science/tasks/science_s3_seed3/worker/task_manifest.json": "29577e224495b4fc779026b036fb3a908521b4fb71660ba6bf75f4bb8dc98050",
          "science/tasks/science_s3_seed3/worker/task_result.json": "954f56062651eda4d3e7e128c0c35b32df9b439f98355f51822eabdc5595505a",
          "science/tasks/science_s3_seed4/task_result.json": "832b1a51d5eda5758663be01f6fbdd625431bb04a727ea9378d26289fbccd318",
          "science/tasks/science_s3_seed4/worker/Cmix_predictions.npz": "61a4cad38583d217b6a57b39c7e2856ab2205d5b10b18fcb73cc3d42d5ca3e62",
          "science/tasks/science_s3_seed4/worker/Preal_predictions.npz": "6e0200dee9e5a1605e6dfec44ce7d3eb7a1197f1dc85ad1e660f1db5a4a37c5f",
          "science/tasks/science_s3_seed4/worker/buffer_audit.json": "a13b52718861f5d97b0099d3266cbc0c7c162767298bd2942ceb11c8b614f1c5",
          "science/tasks/science_s3_seed4/worker/source_audit.json": "e7c58d9bbf1bf9f272886e2d52a0ad023c9c2b3fd3db5d26593bfbbd5b749541",
          "science/tasks/science_s3_seed4/worker/task_manifest.json": "134bc960310341a9c0cd73af2a90f9683d0128656b89fc5d9672f952613800a2",
          "science/tasks/science_s3_seed4/worker/task_result.json": "3f7c7431be04b96325c2fa917178dec6b3c672ac96176b234c62a5ddd889c69c",
          "science/tasks/science_s4_seed3/task_result.json": "892d674ad6d4b287c50df900adee55863aaef1ef9a62588eb6ee088af192eef1",
          "science/tasks/science_s4_seed3/worker/Cmix_predictions.npz": "2637a45d4526bc977af94e7cd8757ebcabce24c59828ac95fc54b45ae20764c6",
          "science/tasks/science_s4_seed3/worker/Preal_predictions.npz": "2f8c8a49eff1bbee02d0b0ff4be42e230a1b14af077fd53aa77c93819835ab68",
          "science/tasks/science_s4_seed3/worker/buffer_audit.json": "dde1efa2b6ca0bca9df70560242cb713e8b6344cf9aa8bb7537d17339253a473",
          "science/tasks/science_s4_seed3/worker/source_audit.json": "d812d93b0cfdf3775e0bc657486e84ae9471dfd59947d1efb0df7dfd1b9908de",
          "science/tasks/science_s4_seed3/worker/task_manifest.json": "746095e684c8c3510823ad267691522aa8a46b8892e5ec802206665ce4124e69",
          "science/tasks/science_s4_seed3/worker/task_result.json": "0031ea42604decea36487971ecdc8feb5e7ad46daa926143f3cdc047ad931671",
          "science/tasks/science_s4_seed4/task_result.json": "960f349ce6dd5ef4d6215d3aad1d72e5c8e762acc5cc8f83cb05e310697455e5",
          "science/tasks/science_s4_seed4/worker/Cmix_predictions.npz": "8dd1d835d8dc8a969b5b9bafbbe93a990339160fc1c0d27b8bb0681e72569907",
          "science/tasks/science_s4_seed4/worker/Preal_predictions.npz": "4dba8090faf8bc754495809f5928e60be91bb68004f6f1947f3836ffeaebf746",
          "science/tasks/science_s4_seed4/worker/buffer_audit.json": "524903119ef8c61410911faeb96ae019d0491b612ca9d2bb86aaa1bad91e3695",
          "science/tasks/science_s4_seed4/worker/source_audit.json": "5a5bc2215f8da4240315749fcb3569c99ccf7976cbc9bcd6778ed2394a69c650",
          "science/tasks/science_s4_seed4/worker/task_manifest.json": "2959bd862a5bee82fb2bbb04a59b4e8f556e7f77d2e02516e72bd7e06ce3f533",
          "science/tasks/science_s4_seed4/worker/task_result.json": "f2b76ce0d76fd6bfdf41e20173b5be55f404a64b5ac962a2fe366f1776745528",
          "science/tasks/science_s5_seed3/task_result.json": "9ce282e57b15ab0e5e8dd636a10032862136b1dde69569ba4d123d83641ab5a5",
          "science/tasks/science_s5_seed3/worker/Cmix_predictions.npz": "f1b6dbf9860538ebc4243cdeb75443d7cf4fa26d37006cf8130a76191a9cf4da",
          "science/tasks/science_s5_seed3/worker/Preal_predictions.npz": "c87e657765a67822e4b2f7ca3805b29c83f890d6b53581ddcf306756e9f05edb",
          "science/tasks/science_s5_seed3/worker/buffer_audit.json": "14e177d80ec4d705e7c9ed0c860a08d6499d9b0acdf127ec92aa7f1501b48584",
          "science/tasks/science_s5_seed3/worker/source_audit.json": "e2d6771891ad67fa8cd1efcf7d7d9a7d1ec93720c25a9f0b135c33f631cd9108",
          "science/tasks/science_s5_seed3/worker/task_manifest.json": "2557088ee0d67157ce348c0a47760b986cf60b41f02df1abf622aa9fd7531691",
          "science/tasks/science_s5_seed3/worker/task_result.json": "73c7a27a2e19bb0ad5bf512998e5296192825a567ece9941e8b62d4b8af0eb2e",
          "science/tasks/science_s5_seed4/task_result.json": "48371d95d0dadc755d4e2005fa0a7e923fcbf51d720859ab80d275c7aa236042",
          "science/tasks/science_s5_seed4/worker/Cmix_predictions.npz": "f3a5e298106e70e0a7e6932a402bb7b91d8b44a8c1bb379aa0aeda5010ac96e4",
          "science/tasks/science_s5_seed4/worker/Preal_predictions.npz": "a9d1ebc65ac7d140bf6cbb7a770c485e3f02a6324ff4c9fd8cba34e339d439b5",
          "science/tasks/science_s5_seed4/worker/buffer_audit.json": "d1b212847be8c114e9058fa7229a74bf9ea8da6327c58e74dc696bb411cbb693",
          "science/tasks/science_s5_seed4/worker/source_audit.json": "18efe7b501994ffbddaa5f436d2bb1f640dfcee96e211995c2f545b8000e5dfc",
          "science/tasks/science_s5_seed4/worker/task_manifest.json": "b3720f9be93431e70d2760a1e40cd0c7a96806cf830e3810704620dfcfc23daf",
          "science/tasks/science_s5_seed4/worker/task_result.json": "c06b01ae6f53337f29804816307712af61e0df59c2fd9ad277dbef6d5d228292",
          "science/tasks/science_s6_seed3/task_result.json": "409cd10ce6e8a6686108f9a67c8ef886d457ac4e6108f13765cb6f34aa1344ad",
          "science/tasks/science_s6_seed3/worker/Cmix_predictions.npz": "b7e226af06f53eff12537dafb269fc3645c6c31a8e523cbd34e9f90b399d2cdf",
          "science/tasks/science_s6_seed3/worker/Preal_predictions.npz": "ab14d5a190ce6a120a6c546e7743331d1b189c44b79c592076346d442455715e",
          "science/tasks/science_s6_seed3/worker/buffer_audit.json": "11b36834db20f250a0ebee4ac2bda351317d9280b35204e6d6a9e338e341c498",
          "science/tasks/science_s6_seed3/worker/source_audit.json": "03e781879e3b7bce504cbddbd7e5e1487a48249cabfd525d2893304a288c2e69",
          "science/tasks/science_s6_seed3/worker/task_manifest.json": "d5dc83fcf6ce737b77004b3af00c3d3569bd64dc59449777e9d17a0c43edb9de",
          "science/tasks/science_s6_seed3/worker/task_result.json": "4f9d868fb2dfdae1dc58a6cceaa7889ae0202fc3d04bbf091503609b0e784f9d",
          "science/tasks/science_s6_seed4/task_result.json": "47f5a00ceb8d97ab5eba626f47012c81574dcbc2be71e450c44ed1a739ccacfb",
          "science/tasks/science_s6_seed4/worker/Cmix_predictions.npz": "e81dcc4e820c82cec482f15a3cc4e7d50ddf3df72b18815fd4651e04abc5f4ab",
          "science/tasks/science_s6_seed4/worker/Preal_predictions.npz": "5b18744b2a47a969d86ed0e1bc8d9e2b4b2b94558c775b63d3f5a81a88a641e6",
          "science/tasks/science_s6_seed4/worker/buffer_audit.json": "1053ee5165623db8c7f90dfc9355bb74d5083a2d5e4a4e89b900a120de1bf308",
          "science/tasks/science_s6_seed4/worker/source_audit.json": "13068c51f12cf3db5ac8c71c8f3067c38c22270ab12f04182c7d1fdbec0e1797",
          "science/tasks/science_s6_seed4/worker/task_manifest.json": "34c66e609cc7b7b4c235b9d22cc3564ba52bafc91bbc05e1d45e83cac9a798c8",
          "science/tasks/science_s6_seed4/worker/task_result.json": "9aa0eff7cf767783672fcb609c085fc1d895618443b00cab6ac7ee529f4aca0b",
          "science/tasks/science_s7_seed3/task_result.json": "add011e9dddec13949593efa31e7ea77f0ed5043b18f4322f6fc29f43abd4fb4",
          "science/tasks/science_s7_seed3/worker/Cmix_predictions.npz": "24eae6c36ff36bad6c9f09514c0e444032502c21d67fcac9f7a59ddc07be4c83",
          "science/tasks/science_s7_seed3/worker/Preal_predictions.npz": "6dca9a9ca12bb17f3785119c4fbd0eb35f666bce5707f7ad8a936883e7343136",
          "science/tasks/science_s7_seed3/worker/buffer_audit.json": "9bbe5d96e6a075faceae40d03bc0caca51dd2b5935f45cbe7cbaa0e8793e02f8",
          "science/tasks/science_s7_seed3/worker/source_audit.json": "92daab3126df57ccc757cd65805cd7abca78158edfbd4a04c4233f750919d877",
          "science/tasks/science_s7_seed3/worker/task_manifest.json": "dbac9bec118f9323e4821c6b0bef30b9c9391e752730208535048c3fe65ec323",
          "science/tasks/science_s7_seed3/worker/task_result.json": "e176cd9e12bc4e729974af4e0897b46755392be4516a7796fcc489082b8820e2",
          "science/tasks/science_s7_seed4/task_result.json": "3a006a455e47ec97794ae014ff2d52f36d80269049b748c60ecb0247ea40c7d9",
          "science/tasks/science_s7_seed4/worker/Cmix_predictions.npz": "9f0d79a6293ae2cf084b4a2ce7c4e29aa8ad1cff08c9a18add3b63122d63b4f6",
          "science/tasks/science_s7_seed4/worker/Preal_predictions.npz": "2a12bb7bb4e51e3a0b2df022f37b52d5f15782752d966371b7c814ac9239f762",
          "science/tasks/science_s7_seed4/worker/buffer_audit.json": "ac08b23937f054c6664c12e29b159e44a5f61f49d92094ef86926b2601041d0f",
          "science/tasks/science_s7_seed4/worker/source_audit.json": "416c99bdf7e48c9fa0b6f7a0aca48c5a8eee1673aa11649537c2fe00a93016a9",
          "science/tasks/science_s7_seed4/worker/task_manifest.json": "2d2dfbc2edd92fab80c7929097a7b8b0ed4ea87c74d95bd3ce90036530f04715",
          "science/tasks/science_s7_seed4/worker/task_result.json": "16a0dce6df1de52d91f69a2b645a0a78add8113e86a8b465032a5d7103ccd8ea",
          "science/tasks/science_s8_seed3/task_result.json": "da3a12b0f4e10ed680888e1d8d67797af33f874854499530b76e6baa3f95d12d",
          "science/tasks/science_s8_seed3/worker/Cmix_predictions.npz": "6592655ca135cbf34f481a19ed30dec3535e266c18b947a32cd2b860ae216bb4",
          "science/tasks/science_s8_seed3/worker/Preal_predictions.npz": "3b7010457efff1899a616f0eb77ae8e1a2cbb88a76249d4f29dfcd79eb21693b",
          "science/tasks/science_s8_seed3/worker/buffer_audit.json": "c5e24c77ff330f1a51b8a927b5d237f704c451499a9578aa06a2941bacba48c5",
          "science/tasks/science_s8_seed3/worker/source_audit.json": "50b065b9f584319e5e6342b85592c6a7649f09d05c775c6202abb95374e42453",
          "science/tasks/science_s8_seed3/worker/task_manifest.json": "d3a7f2c81169b0d8338fc39eb433b999b09821a83447cfffa6fc326e3be3092d",
          "science/tasks/science_s8_seed3/worker/task_result.json": "143f41224d665bd9b43773b3b81fdb139fbbec887db312711cb643a101ed2a5d",
          "science/tasks/science_s8_seed4/task_result.json": "bc2052dc480695d5302b70b9865b1e855de258455b719c00589b5f379c4b24f0",
          "science/tasks/science_s8_seed4/worker/Cmix_predictions.npz": "2ed23428cd5f94949c74fec4fb6bb7c59bc03c91ead06f67ec868ad277adfd66",
          "science/tasks/science_s8_seed4/worker/Preal_predictions.npz": "e3504a25e1062689a76e291a3561961704721b3eb3afb7ab0e92e6718089aafc",
          "science/tasks/science_s8_seed4/worker/buffer_audit.json": "937bde7e00dcd2e258b980e6e95c1bcab15cb617887c8768296a5bbb297add65",
          "science/tasks/science_s8_seed4/worker/source_audit.json": "d88f5a8c90b9f91dc86d1c9d4920fab898bafd0b09686e628f87f17f561eecf9",
          "science/tasks/science_s8_seed4/worker/task_manifest.json": "56ec5f467ac5f60d6b0e125a6d2c65deba4c751b3186bc6042dc72cd142ed19f",
          "science/tasks/science_s8_seed4/worker/task_result.json": "3294b17de4c61a5026fb39db38865ebfa820822042c7f5294dec67c97b59da93",
          "transaction_status.json": "7c9a247560fc865d8833c8a700dcabde29e434c510778c549530c04b429e65f3"
        },
        "supplemental_index_sha256": "efcb9e7dba15a299744c3d64e180b1a13f48cb85537254b3bb9d126e8af7b586",
        "transaction_id": "dbconformer-sbn-r1-packfix1-tx",
        "transfer_bytes": 3244188,
        "verified": true,
        "verified_at": null,
        "verifier_sha256": "f4cd10b0a392d66a102c633e8fe8578856b2b86ca1bffa2c1f9e426993e6099c"
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized launch and 48 cumulative hours: 2 source-only technical fits then dynamic versus fixed spatial QK 36 scientific fits; retain 2026-10-29T14:00Z preparation anchor; zero retries; stop after one round. Pre-dispatch dependency-only package revision preserves all science and budget.",
      "full_prior_campaign_snapshot": {
        "campaign": {
          "allowed_transitions": [
            "SCREEN_NEW"
          ],
          "authorization_reason": "User approved SBN-R1 launch and six hours; preserve original preparation anchor and all prior costs, zero gradient fits, real technical gates before 54 scores, no R2",
          "campaign_id": "dbconformer-sbn-r1-campaign",
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
            "authorization_ref": "ai4s/programs/dbconformer/research/sbn_r1/AUTHORIZATION_AND_BUDGET.json",
            "campaign_id": "dbconformer-sbn-r1-campaign",
            "executor_id": "lab10",
            "recorded_at": "2026-10-29T11:37:18.052226+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "source-only-population-bn-real-vs-mixture-v1"
              ],
              "allowed_stages": [
                "source_bn_screen"
              ],
              "data_scope_id": "bnci001-exposed-fca-cal32-fixed-splits",
              "question_id": "dbconformer-source-bn-statistic-composition"
            },
            "source_sha256": "d38cb60921f2adff970e052fddd197b4915c9ad8c33c5e4de89d2da63366ac00"
          },
          "governance_chain_id": "dbconformer-transaction-v3.2",
          "invalid_behavior": "fail_closed_without_advancing",
          "positive_signal_behavior": "pause_for_human_review",
          "purpose": "user-authorized bounded AI4S campaign",
          "round_decisions": [
            {
              "decision": "SBN_R1_FIXED_GATE_NOT_MET_STOP",
              "decision_record": "ai4s/programs/dbconformer/research/dbconformer-sbn-r1_decision.yaml",
              "evidence_id": "AI4S-DBCONFORMER-dbconformer-sbn-r1",
              "recorded_at": "2026-10-29T13:57:04.940711+00:00",
              "round_id": "dbconformer-sbn-r1"
            }
          ],
          "started_at": "2026-10-29T11:35:33.026141+00:00"
        },
        "closure_budget_accounting": {
          "accounted_hours": 82.67377071914012,
          "accounting_started_at": "2026-10-24T12:23:48.589375+08:00",
          "all_costs_preserved": true,
          "budget_increased_this_recovery": false,
          "closed_at": "2026-10-28T15:56:30.750481+08:00",
          "elapsed_hours": 99.54504475166667,
          "interpretation": "Training completed earlier within the authorized envelope; delayed retrieval/repair/closeout wall accounting is retained, not erased.",
          "limit_hours": 80,
          "overrun_hours": 2.6737707191401228,
          "verified_queue_excluded_hours": 16.871274032526546,
          "verified_stopped_excluded_hours": 0.0
        },
        "pending_execution_budget": null,
        "run_control": {
          "accounting_anchor_basis": "SBN-R1 authorization; preparation included; no reset",
          "continuation_policy_version": "evidence_to_design_v1",
          "continue_after_positive": false,
          "max_rounds": 1,
          "monitor": "blocking",
          "night_budget_hours": 6.0,
          "preparation_included": true,
          "queue_time_policy": "wall_clock",
          "round_index": 1,
          "started_at": "2026-10-29T10:53:47.286204+00:00"
        }
      },
      "full_prior_campaign_snapshot_sha256": "1dc2a84f41a22da741a3d32059540f0d7e61aca8028f979f077fb1a1def9c377"
    },
    {
      "campaign_id": "dbconformer-sqk-r1-campaign",
      "closed_at": "2026-10-31T06:27:21.493849+00:00",
      "closing_decision": {
        "automatic_continuation": false,
        "claim_release": false,
        "comparisons": {
          "B0-Cstatic": {
            "all_subject_seed_pairs_ge_minus_3pp": false,
            "one_sided_exact_subject_signflip_p": 0.408203125,
            "seed_mean_delta_pp": {
              "3": 0.6558641975308643,
              "4": 0.057870370370370336
            },
            "signflip_assignments": 512,
            "subject_delta_pp": {
              "0": 0.4340277777777778,
              "1": 0.6076388888888891,
              "2": -2.6909722222222223,
              "3": -4.166666666666667,
              "4": 2.083333333333333,
              "5": -0.6076388888888888,
              "6": 2.430555555555556,
              "7": 8.59375,
              "8": -3.472222222222222
            },
            "subject_mean_delta_pp": 0.35686728395061723,
            "support_gates": {
              "each_seed_mean_positive": true,
              "mean_delta_positive": true,
              "one_sided_exact_signflip_p_le_0_05": false
            },
            "supported": false,
            "worst_subject_seed_delta_pp": -6.770833333333333
          }
        },
        "decision": "SQK_R1_DYNAMIC_UTILITY_NOT_ESTABLISHED_STOP",
        "round_id": "dbconformer-sqk-r1"
      },
      "closing_round": "dbconformer-sqk-r1",
      "closing_run": {
        "analysis_receipt_sha256": "e27bc3d0bcf1d86e0caaf0d32c3a87acefda12d82b2d73e99d5721755295727e",
        "artifact_manifest_sha256": "9f0d31d0445ada399f84d1b2c1ad4c202c1d94d34b1e956f22ab6b23344464ba",
        "contract_sha256": "5c94c838534d4794dd56d03b84559661a68e7242bf5a42df469863ce8d2cb556",
        "full_payload_local": false,
        "intake_path": "results/logs/remote/2026-10-29_dbconformer_sqk_r1_packfix1_lab10_r1-full-w1",
        "intake_scope": "analysis_v1",
        "run_id": "2026-10-29_dbconformer_sqk_r1_packfix1_lab10_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "dbconformer-sqk-r1-packfix1-tx",
        "transfer_bytes": 549776006,
        "verified": true,
        "verified_at": null
      },
      "closing_status": "COMPLETE_MAX_ROUNDS",
      "closure_reason": "User authorized production wiring GPU qualification three-arm decision and formal scientific training; new 72h envelope anchored 2026-10-31T06:03:45+00:00 includes preparation; 57 fresh fits no retry no successor.",
      "full_prior_campaign_snapshot": {
        "campaign": {
          "allowed_transitions": [
            "SCREEN_NEW"
          ],
          "authorization_reason": "User authorized launch and 48 cumulative hours: 2 source-only technical fits then dynamic versus fixed spatial QK 36 scientific fits; retain 2026-10-29T14:00Z preparation anchor; zero retries; stop after one round. Pre-dispatch dependency-only package revision preserves all science and budget.",
          "campaign_id": "dbconformer-sqk-r1-campaign",
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
            "authorization_ref": "ai4s/programs/dbconformer/research/sqk_r1/EXECUTION_AUTHORIZATION.md",
            "campaign_id": "dbconformer-sqk-r1-campaign",
            "executor_id": "lab10",
            "recorded_at": "2026-10-29T15:13:35.438235+00:00",
            "research_scope": {
              "allow_new_module": false,
              "allowed_module_ids": [
                "spatial-position-qk-control-v1"
              ],
              "allowed_stages": [
                "spatial_qk_mechanism_screen"
              ],
              "data_scope_id": "bnci2014001-exposed-loso-cue0_4s-seeds3_4",
              "question_id": "dbconformer-input-dependent-spatial-qk"
            },
            "source_sha256": "0fcbb86c294258365e4baeecc0cd13c5460be5556e4f1d9d13f46bc964d33fe4"
          },
          "governance_chain_id": "dbconformer-transaction-v3.3",
          "invalid_behavior": "fail_closed_without_advancing",
          "positive_signal_behavior": "pause_for_human_review",
          "purpose": "user-authorized bounded AI4S campaign",
          "queue_accounting": {
            "2026-10-29_dbconformer_sqk_r1_packfix1_lab10_r1-full-w1": {
              "contract_sha256": "5c94c838534d4794dd56d03b84559661a68e7242bf5a42df469863ce8d2cb556",
              "queue_seconds": 60.67300796508789,
              "run_id": "2026-10-29_dbconformer_sqk_r1_packfix1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-sqk-r1-packfix1-tx"
            }
          },
          "round_decisions": [
            {
              "decision": "SQK_R1_DYNAMIC_UTILITY_NOT_ESTABLISHED_STOP",
              "decision_record": "ai4s/programs/dbconformer/research/dbconformer-sqk-r1_decision.yaml",
              "evidence_id": "AI4S-DBCONFORMER-dbconformer-sqk-r1",
              "recorded_at": "2026-10-30T17:52:33.291395+00:00",
              "round_id": "dbconformer-sqk-r1"
            }
          ],
          "started_at": "2026-10-29T15:13:06.773516+00:00"
        },
        "closure_budget_accounting": {
          "accounted_hours": 82.67377071914012,
          "accounting_started_at": "2026-10-24T12:23:48.589375+08:00",
          "all_costs_preserved": true,
          "budget_increased_this_recovery": false,
          "closed_at": "2026-10-28T15:56:30.750481+08:00",
          "elapsed_hours": 99.54504475166667,
          "interpretation": "Training completed earlier within the authorized envelope; delayed retrieval/repair/closeout wall accounting is retained, not erased.",
          "limit_hours": 80,
          "overrun_hours": 2.6737707191401228,
          "verified_queue_excluded_hours": 16.871274032526546,
          "verified_stopped_excluded_hours": 0.0
        },
        "pending_execution_budget": null,
        "run_control": {
          "accounting_anchor_basis": "Conservative start-of-hour preceding this launch preparation; includes preparation; not a measured duration; never reset at launch",
          "continuation_policy_version": "evidence_to_design_v1",
          "continue_after_positive": false,
          "max_rounds": 1,
          "monitor": "blocking",
          "night_budget_hours": 48.0,
          "preparation_included": true,
          "queue_time_policy": "exclude_resource_wait",
          "round_index": 1,
          "started_at": "2026-10-29T14:00:00+00:00"
        }
      },
      "full_prior_campaign_snapshot_sha256": "9e9f86e4664d989223a0ce40b52367e512366eaa0b3b3bc9734054dd4390dba5"
    }
  ],
  "bounded_recovery": {
    "automatic_retries": 0,
    "budget_authorization_ref": {
      "path": "ai4s/programs/dbconformer/research/srt_r1_repair3/BUDGET_AUTHORIZATION.json",
      "sha256": "1668b74d976f4eef8a05142510a627c9792dea6227158cb53d98fb571764fa27"
    },
    "closure_reserve_hours": 2,
    "contract_ref": {
      "path": "ai4s/programs/dbconformer/research/dbconformer-srt-r1-repair3-r2.yaml",
      "sha256": "1026b6d34efd04cd5f4f0da41e20cee29b96979f5580d238c74ddb63277b503f"
    },
    "contract_sha256": "9d66d8c12fa61f3ec148f381187ed907836d367de808b80fae3b7235416a8cda",
    "cumulative_fit_limit": 45,
    "dispatch_started": false,
    "new_scientific_fits": 1,
    "offline_chain_ref": {
      "path": "ai4s/programs/dbconformer/research/srt_r1_repair3/OFFLINE_CHAIN_ACCEPTANCE_R2.json",
      "sha256": "e399a5877b435a0ac8b22f0c2cdc15bcfe16f8c2ba9b0c96bed4fe6590d7ff96"
    },
    "preserved_scientific_fits": 35,
    "preserved_technical_fits": 4,
    "production_acceptance_ref": {
      "path": "ai4s/programs/dbconformer/research/srt_r1_repair3/PRODUCTION_CPU_ACCEPTANCE_R2.json",
      "sha256": "633fa591958e1477cf33d23de63cd75cb662ebd3072c12f33cc0cd7bed9d111a"
    },
    "run_id": "2026-10-20_dbconformer_srt_r1_repair3_lab10_r2-full-w1",
    "schema": "srt_r1_repair3_registration_cas_v1",
    "screen_gate": "same_run_smoke_import_verification_pass",
    "source_run_record_ref": {
      "path": "ai4s/programs/dbconformer/research/srt_r1_repair3/SOURCE_RECORD.json",
      "sha256": "792ae437d189febab48c151306d263ca1ea9d8229bf1944155ddc5d7a5a5800d"
    },
    "status": "FROZEN_PENDING_UPLOAD",
    "transaction_timeout_seconds": 7800,
    "user_authorization_source_ref": {
      "path": "ai4s/programs/dbconformer/research/srt_r1_repair3/USER_AUTHORIZATION_SOURCE.json",
      "sha256": "b0361e9bde17564351911d2f845724acf297c08edaa08634e42e93272baa31e6"
    }
  },
  "budget_extensions": [
    {
      "additional_hours": 24,
      "authorization_ref": "ai4s/programs/dbconformer/research/fca_r1_repair1/AUTHORIZATION.md",
      "cumulative_hours": 42,
      "old_costs_preserved": true,
      "recorded_at": "2026-10-24T16:27:33.216981+00:00"
    },
    {
      "additional_hours": 18,
      "authorization_ref": "ai4s/programs/dbconformer/research/fca_r1_repair2/AUTHORIZATION.md",
      "cumulative_hours": 60,
      "old_costs_preserved": true,
      "recorded_at": "2026-10-25T03:23:40.345835+00:00"
    },
    {
      "accounting_started_at_preserved": "2026-10-24T12:23:48.589375+08:00",
      "additional_hours": 5,
      "authorization_ref": "ai4s/programs/dbconformer/research/fca_r1_repair3/AUTHORIZATION.md",
      "authorization_sha256": "2ca8ab59f360d9bf898965af3ba25f8302aedf4ec3cf78272c421b864bf124fa",
      "cumulative_hours": 65,
      "old_costs_preserved": true,
      "previous_total_hours": 60,
      "recorded_at": "2026-10-26T10:32:28.942130+00:00"
    },
    {
      "accounting_started_at_preserved": "2026-10-24T12:23:48.589375+08:00",
      "additional_hours": 6,
      "authorization_ref": "ai4s/programs/dbconformer/research/fca_r1_repair4/AUTHORIZATION.md",
      "authorization_sha256": "ae4cde7151ea159345534abcdbc300d0033507bfc0cef39f568ffe83a59279e8",
      "cumulative_hours": 71,
      "old_costs_preserved": true,
      "previous_total_hours": 65,
      "recorded_at": "2026-10-26T17:25:38.715068+00:00"
    },
    {
      "additional_budget_hours": 72,
      "authorization": "ai4s/programs/dbconformer/research/sgp_r1_budget1/EXECUTION_AUTHORIZATION.json",
      "authorization_sha256": "85f0efc64b05f88fb2f9b43effb97a37d88eadcc12b8e63342c725ba39eeee23",
      "cumulative_budget_hours": 144,
      "original_anchor": "2026-10-31T06:03:45+00:00",
      "original_budget_hours": 72,
      "recorded_at": "2026-10-31T13:20:34.374434+00:00",
      "source_run_id": "2026-10-31_dbconformer_sgp_r1_lab10_r1-full-w1"
    }
  ],
  "campaign": {
    "allowed_transitions": [
      "SCREEN_NEW"
    ],
    "authorization_reason": "User authorized production wiring GPU qualification three-arm decision and formal scientific training; new 72h envelope anchored 2026-10-31T06:03:45+00:00 includes preparation; 57 fresh fits no retry no successor.",
    "campaign_id": "dbconformer-sgp-r1-campaign",
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
      "authorization_ref": "ai4s/programs/dbconformer/research/sgp_r1/EXECUTION_AUTHORIZATION.md",
      "campaign_id": "dbconformer-sgp-r1-campaign",
      "executor_id": "lab10",
      "recorded_at": "2026-10-31T06:27:31.017056+00:00",
      "research_scope": {
        "allow_new_module": false,
        "allowed_module_ids": [
          "same-forward-real-prefix-source-group-symmetric-projection-v1"
        ],
        "allowed_stages": [
          "source_group_projection_screen"
        ],
        "data_scope_id": "bnci2014001-exposed-loso-cue0_4s-seeds3_4",
        "question_id": "dbconformer-source-group-projection-applicability"
      },
      "source_sha256": "2346ca80d7c80525ffdd3b635e732ad2052718a821b668b0cce23d725b714d90"
    },
    "governance_chain_id": "dbconformer-transaction-v3.3",
    "invalid_behavior": "fail_closed_without_advancing",
    "positive_signal_behavior": "pause_for_human_review",
    "purpose": "user-authorized bounded AI4S campaign",
    "queue_accounting": {
      "2026-10-31_dbconformer_sgp_r1_lab10_budget1-full-w1": {
        "contract_sha256": "01c415c4eece0d26c3f9581adc14adfd62fda0b2b9cafd26bd1040233e97f7a0",
        "queue_seconds": 71279.37181305885,
        "run_id": "2026-10-31_dbconformer_sgp_r1_lab10_budget1-full-w1",
        "transaction_id": "dbconformer-sgp-r1-budget1-tx"
      },
      "2026-10-31_dbconformer_sgp_r1_lab10_r1-full-w1": {
        "contract_sha256": "6f9e6fea42781c442530511fed798c6b3e2a97147651c54fc9ef9b4965228977",
        "queue_seconds": 12193.73873090744,
        "run_id": "2026-10-31_dbconformer_sgp_r1_lab10_r1-full-w1",
        "transaction_id": "dbconformer-sgp-r1-tx"
      }
    },
    "round_decisions": [
      {
        "decision": "SGP_R1_GROUP_STRUCTURE_UTILITY_NOT_ESTABLISHED_STOP",
        "decision_record": "ai4s/programs/dbconformer/research/dbconformer-sgp-r1-budget1_decision.yaml",
        "evidence_id": "AI4S-DBCONFORMER-dbconformer-sgp-r1-budget1",
        "recorded_at": "2026-11-04T05:58:38.570613+00:00",
        "round_id": "dbconformer-sgp-r1-budget1"
      }
    ],
    "started_at": "2026-10-31T06:27:21.493849+00:00"
  },
  "closure_budget_accounting": {
    "accounted_hours": 82.67377071914012,
    "accounting_started_at": "2026-10-24T12:23:48.589375+08:00",
    "all_costs_preserved": true,
    "budget_increased_this_recovery": false,
    "closed_at": "2026-10-28T15:56:30.750481+08:00",
    "elapsed_hours": 99.54504475166667,
    "interpretation": "Training completed earlier within the authorized envelope; delayed retrieval/repair/closeout wall accounting is retained, not erased.",
    "limit_hours": 80,
    "overrun_hours": 2.6737707191401228,
    "verified_queue_excluded_hours": 16.871274032526546,
    "verified_stopped_excluded_hours": 0.0
  },
  "completed_rounds": [
    {
      "decision": {
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "interpretation_boundary": "selection-used fixed-backbone readout diagnostic only; no causal, training-utility or paper claim",
        "reason": "Frozen spatial-resolution diagnostic gates not all passed",
        "round_id": "dbconformer-ptsr-d0-r2"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-ptsr-d0-r2_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-ptsr-d0-r2",
      "round_id": "dbconformer-ptsr-d0-r2",
      "run": {
        "bundle_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-22T06:44:22.608200+00:00",
        "round_id": "dbconformer-ptsr-d0-r2",
        "run_prefix": "2026-09-22_dbconformer_ptsr_d0_lab10_r2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-22T06:44:52.213810+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-22T06:44:52.842399+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T06:45:19.788777+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
                "execution_seconds": 7.769137620925903,
                "queue_seconds": 18.18872618675232,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
                "transaction_id": "dbconformer-ptsr-d0-r2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 25.957863807678223
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T06:47:06.541107+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
                "execution_seconds": 7.769191265106201,
                "queue_seconds": 124.94532203674316,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
                "transaction_id": "dbconformer-ptsr-d0-r2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 132.71451330184937
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T08:27:28.587271+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
                "execution_seconds": 1476.0124804973602,
                "queue_seconds": 4676.371246814728,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
                "transaction_id": "dbconformer-ptsr-d0-r2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 6152.383727312088
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T09:14:02.872971+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
                "execution_seconds": 1769.340232372284,
                "queue_seconds": 7177.3431050777435,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
                "transaction_id": "dbconformer-ptsr-d0-r2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 8946.683337450027
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T09:20:31.320735+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
                "execution_seconds": 1859.1919989585876,
                "queue_seconds": 7475.956962585449,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
                "transaction_id": "dbconformer-ptsr-d0-r2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 9335.148961544037
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-22T11:21:26.466851+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
                "execution_seconds": 2193.3556592464447,
                "queue_seconds": 8077.544718503952,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
                "transaction_id": "dbconformer-ptsr-d0-r2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10270.900377750397
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-22T11:21:55.667985+00:00",
            "result": {
              "artifact_manifest_sha256": "ba07c7c861aa125210c3b27a49f103c5ed88e3c7197aa976bd41e2bfd31f8bfd",
              "contract_sha256": "b66172ca0cea16c987c2777dee299db0fc72e1798bb6fd2d744670c47e502c6c",
              "run_id": "2026-09-22_dbconformer_ptsr_d0_lab10_r2-full-w1",
              "transaction_id": "dbconformer-ptsr-d0-r2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_electrode_identity_only",
        "interpretation_boundary": "selection-used fixed-backbone readout diagnostic only; no causal, training-utility or paper claim",
        "reason": "Frozen electrode-identity diagnostic gates not all passed",
        "round_id": "dbconformer-eir-d0-r1-repair2"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-eir-d0-r1-repair2_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-eir-d0-r1-repair2",
      "round_id": "dbconformer-eir-d0-r1-repair2",
      "run": {
        "bundle_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-23T06:53:16.055089+00:00",
        "round_id": "dbconformer-eir-d0-r1-repair2",
        "run_prefix": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T06:53:22.711430+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T06:53:23.326642+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T06:53:47.223221+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "943dcdde09b8f87ef5a6f897d465847f5ea0c69a8d3c6e9c1a7f69cfbafde634",
                "execution_seconds": 23.148553609848022,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
                "transaction_id": "dbconformer-eir-d0-r1-repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 23.148553609848022
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T06:59:48.269939+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "943dcdde09b8f87ef5a6f897d465847f5ea0c69a8d3c6e9c1a7f69cfbafde634",
                "execution_seconds": 384.20238423347473,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
                "transaction_id": "dbconformer-eir-d0-r1-repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 384.20238423347473
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T07:05:20.363069+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "943dcdde09b8f87ef5a6f897d465847f5ea0c69a8d3c6e9c1a7f69cfbafde634",
                "execution_seconds": 679.5794863700867,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
                "transaction_id": "dbconformer-eir-d0-r1-repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 679.5794863700867
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T07:05:52.367190+00:00",
            "result": {
              "artifact_manifest_sha256": "b7dd1d399158ce72a6792bc1d7bc05fb1ed3f6c405f818139b18c7c7a9ff53ff",
              "contract_sha256": "943dcdde09b8f87ef5a6f897d465847f5ea0c69a8d3c6e9c1a7f69cfbafde634",
              "run_id": "2026-09-23_dbconformer_eir_d0_lab10_r1_repair2-full-w1",
              "transaction_id": "dbconformer-eir-d0-r1-repair2-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_path_use_only",
        "interpretation_boundary": "selection-used frozen source-validation path-use diagnostic only; no causal, training-utility, generalization or paper claim",
        "reason": "Frozen conditional spatial-use gates not all passed",
        "round_id": "dbconformer-csu-d0-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-csu-d0-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-csu-d0-r1",
      "round_id": "dbconformer-csu-d0-r1",
      "run": {
        "bundle_id": "2026-09-23_dbconformer_csu_d0_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-23T08:28:38.606830+00:00",
        "round_id": "dbconformer-csu-d0-r1",
        "run_prefix": "2026-09-23_dbconformer_csu_d0_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T12:09:53.815958+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T12:09:54.543107+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T12:10:19.477534+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "508f91b98d5f32d1b0be1d4bab84be7a7a8077b8e8f9a757b3459a67cfea7ff8",
                "execution_seconds": 24.04076385498047,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-csu-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 24.04076385498047
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T12:17:54.654500+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "508f91b98d5f32d1b0be1d4bab84be7a7a8077b8e8f9a757b3459a67cfea7ff8",
                "execution_seconds": 479.24312829971313,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-csu-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 479.24312829971313
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T12:26:00.287858+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "508f91b98d5f32d1b0be1d4bab84be7a7a8077b8e8f9a757b3459a67cfea7ff8",
                "execution_seconds": 915.4864966869354,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-csu-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 915.4864966869354
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T12:26:34.059237+00:00",
            "result": {
              "artifact_manifest_sha256": "8a071618e24d2b4a552d0d9e983da7d418212fcd19e5257cd0a64b9e20341c70",
              "contract_sha256": "508f91b98d5f32d1b0be1d4bab84be7a7a8077b8e8f9a757b3459a67cfea7ff8",
              "run_id": "2026-09-23_dbconformer_csu_d0_lab10_r1-full-w1",
              "transaction_id": "dbconformer-csu-d0-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_temporal_position_binding_only",
        "interpretation_boundary": "selection-used frozen source-validation temporal position-binding diagnostic only; no causal, training-utility, generalization or paper claim",
        "reason": "Frozen temporal position-binding gates passed",
        "round_id": "dbconformer-tpb-d0-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-tpb-d0-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-tpb-d0-r1",
      "round_id": "dbconformer-tpb-d0-r1",
      "run": {
        "bundle_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-23T13:42:44.326758+00:00",
        "round_id": "dbconformer-tpb-d0-r1",
        "run_prefix": "2026-09-23_dbconformer_tpb_d0_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T13:42:56.879310+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T13:42:57.740829+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T13:43:27.644502+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4de87a8c1a4fe9fca7d0abac8875a385bf58d04b6c6c697ecaba81b3412acc0c",
                "execution_seconds": 29.12767481803894,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tpb-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 29.12767481803894
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T13:50:00.982034+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "4de87a8c1a4fe9fca7d0abac8875a385bf58d04b6c6c697ecaba81b3412acc0c",
                "execution_seconds": 422.4717493057251,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tpb-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 422.4717493057251
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T13:58:28.629612+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "4de87a8c1a4fe9fca7d0abac8875a385bf58d04b6c6c697ecaba81b3412acc0c",
                "execution_seconds": 880.0445342063904,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tpb-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 880.0445342063904
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T13:59:02.285076+00:00",
            "result": {
              "artifact_manifest_sha256": "b587c0f4633eba1f35e3a9f3449165b0dec5ba98bc30f4935b03008e441fa887",
              "contract_sha256": "4de87a8c1a4fe9fca7d0abac8875a385bf58d04b6c6c697ecaba81b3412acc0c",
              "run_id": "2026-09-23_dbconformer_tpb_d0_lab10_r1-full-w1",
              "transaction_id": "dbconformer-tpb-d0-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_CALIBRATION_SUPPORT",
        "evidence_scope": "frozen_backbone_source_calibration_only",
        "gates": {
          "accuracy": false,
          "b0": false,
          "comparators": false,
          "shuffle": false
        },
        "interpretation_boundary": "selection-used source-valid calibration screen; no independent confirmation or causal timing claim",
        "reason": "Frozen BPC-R1 gates not all passed",
        "round_id": "dbconformer-bpc-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-bpc-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-bpc-r1",
      "round_id": "dbconformer-bpc-r1",
      "run": {
        "bundle_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-23T15:21:27.041430+00:00",
        "round_id": "dbconformer-bpc-r1",
        "run_prefix": "2026-09-23_dbconformer_bpc_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T15:23:31.690660+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T15:23:32.481144+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T15:23:45.500110+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
                "execution_seconds": 11.992807865142822,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpc-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 11.992807865142822
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T15:31:40.829244+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
                "execution_seconds": 487.3517572879791,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpc-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 487.3517572879791
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T15:33:07.894966+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
                "execution_seconds": 574.4110946655273,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpc-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 574.4110946655273
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T15:43:19.277802+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
                "execution_seconds": 1185.8182151317596,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpc-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1185.8182151317596
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T15:54:59.172811+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
                "execution_seconds": 1873.4250271320343,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpc-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1873.4250271320343
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T15:56:10.342447+00:00",
            "result": {
              "artifact_manifest_sha256": "23c7bf17a9cd9c544d339f492637f239543be12680462518c74fba16d2e47be9",
              "contract_sha256": "1da59ecda8cbd3dac024d21721d17afbf3cce85eb47f437c104997328e7e1f64",
              "run_id": "2026-09-23_dbconformer_bpc_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bpc-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_slot_moment_corrected_binding_only",
        "interpretation_boundary": "slot-moment corrected source-valid diagnostic; ratio/center attenuation are descriptive only",
        "reason": "Frozen SMP gates passed",
        "round_id": "dbconformer-smp-d0-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-smp-d0-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-smp-d0-r1",
      "round_id": "dbconformer-smp-d0-r1",
      "run": {
        "bundle_id": "2026-09-24_dbconformer_smp_d0_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-23T16:38:47.316218+00:00",
        "round_id": "dbconformer-smp-d0-r1",
        "run_prefix": "2026-09-24_dbconformer_smp_d0_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T16:43:09.929812+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T16:43:11.155462+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:43:24.200018+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 12.072479486465454,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12.072479486465454
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:45:07.032238+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 114.91192436218262,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 114.91192436218262
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:47:20.867128+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 248.76622486114502,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 248.76622486114502
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:48:36.315931+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 324.2012243270874,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 324.2012243270874
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:49:48.285251+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 396.16101574897766,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 396.16101574897766
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:51:00.255394+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 468.1902976036072,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 468.1902976036072
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:53:22.841062+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 610.7769846916199,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 610.7769846916199
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:55:51.453333+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 759.3943920135498,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 759.3943920135498
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T16:58:03.283545+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 891.2345194816589,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 891.2345194816589
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T17:00:31.717807+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 1039.6780052185059,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1039.6780052185059
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T17:01:30.901307+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
                "execution_seconds": 1063.550226688385,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-smp-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1063.550226688385
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T17:02:16.885711+00:00",
            "result": {
              "artifact_manifest_sha256": "cc21743c6372bfb16d2c8f9b3c1413536185781d57f43b6c4d54c297752dd6d6",
              "contract_sha256": "7fa260322c2b4eba798083bafaf6d9859ba5acbb364792126d2229bdf77e0e6f",
              "run_id": "2026-09-24_dbconformer_smp_d0_lab10_r1-full-w1",
              "transaction_id": "dbconformer-smp-d0-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "DIAGNOSTIC_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_paired_slot_distance_only",
        "gates": {
          "difference": true,
          "far": true,
          "loo": true,
          "seeds": true,
          "subjects": true
        },
        "interpretation_boundary": "fixed endpoint-balanced near/far pairing comparison on selection-used source-valid; pair identity and perturbation magnitude confounded; no causal distance or training-utility claim",
        "reason": "Frozen PDX gates passed",
        "round_id": "dbconformer-pdx-d0-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-pdx-d0-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-pdx-d0-r1",
      "round_id": "dbconformer-pdx-d0-r1",
      "run": {
        "bundle_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-23T17:30:24.929354+00:00",
        "round_id": "dbconformer-pdx-d0-r1",
        "run_prefix": "2026-09-24_dbconformer_pdx_d0_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-23T17:54:50.980014+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-23T17:54:51.655266+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T17:55:07.985838+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "654e6c6fa137e6734d4a8c26521a32c7c8fd4f276c88ca379f9d3052be5978ba",
                "execution_seconds": 15.566301584243774,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-pdx-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15.566301584243774
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T18:02:16.358847+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "654e6c6fa137e6734d4a8c26521a32c7c8fd4f276c88ca379f9d3052be5978ba",
                "execution_seconds": 443.9486827850342,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-pdx-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 443.9486827850342
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T18:11:20.364062+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "654e6c6fa137e6734d4a8c26521a32c7c8fd4f276c88ca379f9d3052be5978ba",
                "execution_seconds": 987.9652287960052,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-pdx-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 987.9652287960052
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-23T18:12:20.059099+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "654e6c6fa137e6734d4a8c26521a32c7c8fd4f276c88ca379f9d3052be5978ba",
                "execution_seconds": 995.923642873764,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
                "transaction_id": "dbconformer-pdx-d0-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 995.923642873764
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-23T18:13:03.513382+00:00",
            "result": {
              "artifact_manifest_sha256": "4504e145f8eec838105def7718f3abeea1d340ad9ab0b2c05adac4950137ee65",
              "contract_sha256": "654e6c6fa137e6734d4a8c26521a32c7c8fd4f276c88ca379f9d3052be5978ba",
              "run_id": "2026-09-24_dbconformer_pdx_d0_lab10_r1-full-w1",
              "transaction_id": "dbconformer-pdx-d0-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_DISTANCE_ADAPTATION_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_distance_attention_adaptation_only",
        "gates": {
          "accuracy": true,
          "b0": false,
          "comparators": false
        },
        "interpretation_boundary": "selection-used source-valid frozen-checkpoint adaptation screen; no independent confirmation or target claim",
        "reason": "Frozen DRA-R1 gates not all passed",
        "round_id": "dbconformer-dra-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-dra-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-dra-r1",
      "round_id": "dbconformer-dra-r1",
      "run": {
        "bundle_id": "2026-09-24_dbconformer_dra_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "platform_approval_block": {
          "record": "ai4s/programs/dbconformer/research/dra_r1/DISPATCH_BLOCK.json",
          "recorded_at": "2026-09-24T01:59:45.338213+00:00",
          "resolved_by": "ai4s/programs/dbconformer/research/dra_r1/LAUNCH_AUTHORIZATION.md",
          "upload_executed": false
        },
        "recorded_at": "2026-09-24T01:58:51.564878+00:00",
        "round_id": "dbconformer-dra-r1",
        "run_prefix": "2026-09-24_dbconformer_dra_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T02:04:16.199497+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T02:04:16.920604+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T02:04:31.132459+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e536a8b1f76dbca132a7cd56f433e4f95a7b43530ef16f819d669998d164adfc",
                "execution_seconds": 13.210521459579468,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-dra-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13.210521459579468
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T02:15:52.433033+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e536a8b1f76dbca132a7cd56f433e4f95a7b43530ef16f819d669998d164adfc",
                "execution_seconds": 694.5216958522797,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-dra-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 694.5216958522797
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T02:31:05.990871+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "e536a8b1f76dbca132a7cd56f433e4f95a7b43530ef16f819d669998d164adfc",
                "execution_seconds": 1486.2455489635468,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-dra-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1486.2455489635468
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-24T02:31:47.275000+00:00",
            "result": {
              "artifact_manifest_sha256": "bb529da99ced994006020701d28554f28d8c7649769e98ea620998bfca2b9788",
              "contract_sha256": "e536a8b1f76dbca132a7cd56f433e4f95a7b43530ef16f819d669998d164adfc",
              "run_id": "2026-09-24_dbconformer_dra_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-dra-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_PROJECTION_ADAPTATION_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_attention_projection_adaptation_only",
        "gates": {
          "accuracy": true,
          "b0": true,
          "comparators": false
        },
        "interpretation_boundary": "selection-used source-valid frozen-checkpoint adaptation screen; no independent confirmation or target claim",
        "reason": "Frozen APR-R1 gates not all passed",
        "round_id": "dbconformer-apr-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-apr-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-apr-r1",
      "round_id": "dbconformer-apr-r1",
      "run": {
        "bundle_id": "2026-09-24_dbconformer_apr_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-24T06:31:49.220586+00:00",
        "round_id": "dbconformer-apr-r1",
        "run_prefix": "2026-09-24_dbconformer_apr_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T06:36:15.338651+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T06:36:16.201570+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T06:36:33.274792+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
                "execution_seconds": 16.10578441619873,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-apr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 16.10578441619873
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T06:38:39.245132+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
                "execution_seconds": 142.07470798492432,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-apr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 142.07470798492432
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T06:43:04.442678+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
                "execution_seconds": 407.26669907569885,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-apr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 407.26669907569885
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T07:02:45.085321+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
                "execution_seconds": 1529.759523153305,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-apr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1529.759523153305
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-24T07:03:32.283450+00:00",
            "result": {
              "artifact_manifest_sha256": "b087e30c62f507c516257c789f37ac80f0396c76db287bad87aa80d646019d84",
              "contract_sha256": "03e9553ee23ad106b42f341c1bac9bb2d50d9be7790529a7b70d183d4a9a65d6",
              "run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-apr-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "arm_summaries": {
          "C0": {
            "category_fractions": {
              "correct": 0.721743295019157,
              "corrected": 0.033345306513409965,
              "harmed": 0.03190852490421456,
              "unchanged_wrong": 0.19821599616858238,
              "wrong_to_wrong": 0.014786877394636015
            },
            "category_gain_contributions": {
              "correct": 0.04496404284624812,
              "corrected": 0.015296033266553717,
              "harmed": -0.012625747992145182,
              "unchanged_wrong": -0.037237354115176625,
              "wrong_to_wrong": -0.0010819369382228678
            },
            "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
            "direction_group_means": [
              0.015319715387603974,
              0.018188600200102902,
              0.014708158979337367,
              0.028896659724878836,
              0.008267505257982068,
              0.003133319282539702,
              0.015552067932655218,
              0.011178604947452311,
              0.006519413785532297
            ],
            "direction_loo_min": 0.01160842322165073,
            "interaction": -0.0018264612583647616,
            "phi_direction": 0.013529338388676074,
            "phi_norm": -0.004214301321418917,
            "seed_summary": [
              {
                "phi_direction": 0.018272933553320582,
                "phi_norm": -0.005776079468577329,
                "total_gain": 0.012496854084743249
              },
              {
                "phi_direction": 0.008785743224031568,
                "phi_norm": -0.002652523174260504,
                "total_gain": 0.006133220049771067
              }
            ],
            "total_gain": 0.00931503706725716,
            "unchanged_argmax_fraction": 0.9199592911877394
          },
          "G0": {
            "category_fractions": {
              "correct": 0.7243773946360155,
              "corrected": 0.03148946360153257,
              "harmed": 0.029274425287356323,
              "unchanged_wrong": 0.19989224137931036,
              "wrong_to_wrong": 0.014966475095785439
            },
            "category_gain_contributions": {
              "correct": 0.0397038733720918,
              "corrected": 0.013401637023210846,
              "harmed": -0.010649140941438685,
              "unchanged_wrong": -0.03333111629468323,
              "wrong_to_wrong": -0.001369085293470876
            },
            "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
            "direction_group_means": [
              0.014413363991003724,
              0.024894765312092303,
              0.004785852723165713,
              0.022538955611644,
              0.0099610343496279,
              0.006265349504414692,
              0.010338089928123618,
              0.007902804462291609,
              -0.0014376504361890347
            ],
            "direction_loo_min": 0.009345975016760277,
            "interaction": -0.0010008331337003134,
            "phi_direction": 0.011073618382908277,
            "phi_norm": -0.0033174505171984217,
            "seed_summary": [
              {
                "phi_direction": 0.01723690866458428,
                "phi_norm": -0.004024359239083457,
                "total_gain": 0.013212549425500823
              },
              {
                "phi_direction": 0.0049103281012322815,
                "phi_norm": -0.0026105417953133873,
                "total_gain": 0.0022997863059188942
              }
            ],
            "total_gain": 0.007756167865709859,
            "unchanged_argmax_fraction": 0.9242696360153256
          },
          "P1": {
            "category_fractions": {
              "correct": 0.726352969348659,
              "corrected": 0.027538314176245207,
              "harmed": 0.027298850574712638,
              "unchanged_wrong": 0.20575909961685823,
              "wrong_to_wrong": 0.013050766283524905
            },
            "category_gain_contributions": {
              "correct": 0.02081759950115886,
              "corrected": 0.009755338155056087,
              "harmed": -0.008174808125928593,
              "unchanged_wrong": -0.010610747887520882,
              "wrong_to_wrong": 2.85540418911167e-05
            },
            "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
            "direction_group_means": [
              0.009324928157310433,
              0.024360751040422915,
              0.006380441836903754,
              0.012349172200690093,
              0.01094029717810787,
              0.007208903720000682,
              0.009926553784130548,
              0.00647245697862329,
              -0.0007832318639749341
            ],
            "direction_loo_min": 0.007727440248973967,
            "interaction": 0.0003195898842810556,
            "phi_direction": 0.009575585892468295,
            "phi_norm": 0.002240349792188295,
            "seed_summary": [
              {
                "phi_direction": 0.011870715350658347,
                "phi_norm": 0.0019499782165673515,
                "total_gain": 0.013820693567225699
              },
              {
                "phi_direction": 0.0072804564342782395,
                "phi_norm": 0.0025307213678092376,
                "total_gain": 0.009811177802087477
              }
            ],
            "total_gain": 0.01181593568465659,
            "unchanged_argmax_fraction": 0.9321120689655172
          }
        },
        "claim_release": false,
        "decision": "OUTPUT_DIRECTION_COMPONENT_SUPPORT",
        "interpretation_boundary": "Repeatedly selection-used source-valid centered-logit two-order attribution only; no calibration, network causal mechanism, target generalization or candidate promotion.",
        "primary_arm": "P1",
        "round_id": "dbconformer-ndd-d0"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-ndd-d0_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-ndd-d0",
      "round_id": "dbconformer-ndd-d0",
      "run": {
        "execution_kind": "local_derived_analysis_no_new_remote_run",
        "source_run_id": "2026-09-24_dbconformer_apr_r1_lab10_r1-full-w1"
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_TEMPORAL_MOMENT_READOUT_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_temporal_moment_readout_only",
        "gates": {
          "b0": false,
          "comparators": false,
          "harm": false
        },
        "interpretation_boundary": "Selection-used overlapping source validation; no independent confirmation, novelty, target generalization or automatic next round.",
        "reason": "Frozen accuracy and harm gates not all passed",
        "round_id": "dbconformer-tmr-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-tmr-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-tmr-r1",
      "round_id": "dbconformer-tmr-r1",
      "run": {
        "bundle_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-24T14:15:45.384969+00:00",
        "round_id": "dbconformer-tmr-r1",
        "run_prefix": "2026-09-24_dbconformer_tmr_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T14:28:40.309703+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T14:28:45.388975+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:29:35.577530+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 49.43558692932129,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 49.43558692932129
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:30:55.681639+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 129.62234735488892,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 129.62234735488892
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:33:17.666140+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 271.5474441051483,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 271.5474441051483
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:34:23.715126+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 337.4007532596588,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 337.4007532596588
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:37:54.624609+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 548.4962785243988,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 548.4962785243988
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:41:17.857680+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 751.7140212059021,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 751.7140212059021
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:42:20.755735+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
                "execution_seconds": 758.5988059043884,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-tmr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 758.5988059043884
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-24T14:50:21.102379+00:00",
            "result": {
              "artifact_manifest_sha256": "d88792e3e99ec9f4de601e4b84a4aadb75aa0128996b5fec73ce4f9445cd3b68",
              "contract_sha256": "414edd543d76e26cb5bf9362af107d10c4c0b8c580ec6eb9bd62e827880ced06",
              "run_id": "2026-09-24_dbconformer_tmr_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-tmr-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_CROSS_BRANCH_READOUT_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_cross_branch_readout_only",
        "gates": {
          "b0": false,
          "comparators": false,
          "harm": false
        },
        "interpretation_boundary": "Selection-used overlapping source validation; no independent confirmation, novelty, target generalization or automatic next round.",
        "reason": "Frozen accuracy and harm gates not all passed",
        "round_id": "dbconformer-cbr-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-cbr-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-cbr-r1",
      "round_id": "dbconformer-cbr-r1",
      "run": {
        "bundle_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-24T15:37:45.695518+00:00",
        "round_id": "dbconformer-cbr-r1",
        "run_prefix": "2026-09-24_dbconformer_cbr_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T15:38:35.822292+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T15:38:37.609770+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T15:41:18.705249+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
                "execution_seconds": 160.4932301044464,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cbr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 160.4932301044464
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T15:43:20.525633+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
                "execution_seconds": 282.26796317100525,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cbr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 282.26796317100525
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T15:44:51.502526+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
                "execution_seconds": 373.26476407051086,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cbr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 373.26476407051086
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T15:50:11.883291+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
                "execution_seconds": 693.6957278251648,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cbr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 693.6957278251648
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T15:51:33.838957+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
                "execution_seconds": 773.4232034683228,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cbr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 773.4232034683228
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T15:52:45.211227+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
                "execution_seconds": 773.4232034683228,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cbr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 773.4232034683228
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-24T15:58:25.795289+00:00",
            "result": {
              "artifact_manifest_sha256": "c5fe181ae1c18f90fb85aa45f5ef6fd2e0dd2219979acfbf2446be9be00abb7d",
              "contract_sha256": "41637e91ed11124c829b72753fe2899532374f1e1506b371339d09c75f9c3870",
              "run_id": "2026-09-24_dbconformer_cbr_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-cbr-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_SOURCE_NUISANCE_READOUT_SUPPORT",
        "evidence_scope": "frozen_checkpoint_source_validation_source_nuisance_readout_only",
        "gates": {
          "b0": false,
          "comparators": false,
          "harm": true
        },
        "interpretation_boundary": "Selection-used overlapping source validation; no independent confirmation, novelty, target generalization or automatic next round.",
        "reason": "Frozen accuracy and harm gates not all passed",
        "round_id": "dbconformer-snr-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-snr-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-snr-r1",
      "round_id": "dbconformer-snr-r1",
      "run": {
        "bundle_id": "2026-09-25_dbconformer_snr_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 36,
        "recorded_at": "2026-09-24T16:19:35.961576+00:00",
        "round_id": "dbconformer-snr-r1",
        "run_prefix": "2026-09-25_dbconformer_snr_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T16:39:49.350588+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T16:39:50.767166+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T16:40:34.961062+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b9999de1d1266d8ffa53a8e8bba0b6021e3b4fd02a8ce1d6b3e53d5c51d97daf",
                "execution_seconds": 43.59336471557617,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-snr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 43.59336471557617
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T16:44:35.375533+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b9999de1d1266d8ffa53a8e8bba0b6021e3b4fd02a8ce1d6b3e53d5c51d97daf",
                "execution_seconds": 284.03380393981934,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-snr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 284.03380393981934
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T16:45:53.330768+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b9999de1d1266d8ffa53a8e8bba0b6021e3b4fd02a8ce1d6b3e53d5c51d97daf",
                "execution_seconds": 361.9625074863434,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-snr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 361.9625074863434
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T16:52:10.095398+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b9999de1d1266d8ffa53a8e8bba0b6021e3b4fd02a8ce1d6b3e53d5c51d97daf",
                "execution_seconds": 730.8876531124115,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-snr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 730.8876531124115
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-24T16:57:25.167765+00:00",
            "result": {
              "artifact_manifest_sha256": "4e0009fc10a4b5abf21b94779b41db3d0755d0be63fd5bb67c3228eef9e9b870",
              "contract_sha256": "b9999de1d1266d8ffa53a8e8bba0b6021e3b4fd02a8ce1d6b3e53d5c51d97daf",
              "run_id": "2026-09-25_dbconformer_snr_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-snr-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training",
        "gates": {
          "both_seeds": false,
          "mean": false,
          "robustness": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects; no mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-bpm-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-bpm-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-bpm-r1",
      "round_id": "dbconformer-bpm-r1",
      "run": {
        "bundle_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 38,
        "recorded_at": "2026-09-24T19:10:09.636346+00:00",
        "round_id": "dbconformer-bpm-r1",
        "run_prefix": "2026-09-25_dbconformer_bpm_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T19:49:53.430523+00:00",
            "result": {
              "action": "UPLOADED",
              "method": "SFTP reput with pre-resume prefix SHA and post-transfer whole-bundle SHA verification",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
              "same_run_transport_recovery": true,
              "source_manifest_sha256": "9e9672ff20aca0ceefb32df83c449ededdf1590608161fbf9ef7282b9f7eec01",
              "verified_remote_files": 68
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T19:50:36.413387+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T19:51:20.587846+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b44e6306269baef4fe31c3a2cb89f9aa0d7914151db13ee76b65462eff536235",
                "execution_seconds": 39.94365048408508,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpm-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 39.94365048408508
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T19:56:04.091078+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b44e6306269baef4fe31c3a2cb89f9aa0d7914151db13ee76b65462eff536235",
                "execution_seconds": 218.52182412147522,
                "queue_seconds": 105.17688274383545,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpm-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 323.69870686531067
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T02:20:56.284103+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b44e6306269baef4fe31c3a2cb89f9aa0d7914151db13ee76b65462eff536235",
                "execution_seconds": 9114.908820152283,
                "queue_seconds": 105.17688274383545,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-bpm-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9220.085702896118
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-25T02:24:20.095739+00:00",
            "result": {
              "artifact_manifest_sha256": "2d72d91caacec46c08bf68c4440a9dcd2e7bb49494b0ece218202aa4a43ee995",
              "contract_sha256": "b44e6306269baef4fe31c3a2cb89f9aa0d7914151db13ee76b65462eff536235",
              "run_id": "2026-09-25_dbconformer_bpm_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-bpm-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training",
        "gates": {
          "both_seeds": false,
          "mean": false,
          "robustness": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects; no mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-hds-r1-repair3"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-hds-r1-repair3_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-hds-r1-repair3",
      "round_id": "dbconformer-hds-r1-repair3",
      "run": {
        "bundle_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 9,
        "recorded_at": "2026-09-25T17:47:10.127368+00:00",
        "round_id": "dbconformer-hds-r1-repair3",
        "run_prefix": "2026-09-26_dbconformer_hds_r1_lab10_repair3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T17:47:53.692617+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
              "source_manifest_sha256": "78c6e50e6ab8cd916790e9cd42694010468bc7434092a9688474cbc86f8ad96a",
              "verified_files": 313
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T17:48:07.260528+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T17:48:25.180756+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7b0c4fe2f2a32c7ebb5d22bca456f5dab17dab0f60474546ff3ef0d0aadda12b",
                "execution_seconds": 11.711938381195068,
                "queue_seconds": 0.045995473861694336,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
                "transaction_id": "dbconformer-hds-r1-repair3-tx",
                "waiting_for_resources": true,
                "wall_seconds": 11.757933855056763
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T03:18:25.692486+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "7b0c4fe2f2a32c7ebb5d22bca456f5dab17dab0f60474546ff3ef0d0aadda12b",
                "execution_seconds": 3999.989282131195,
                "queue_seconds": 665.8486444950104,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
                "transaction_id": "dbconformer-hds-r1-repair3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4665.837926626205
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-26T03:20:41.904700+00:00",
            "result": {
              "artifact_manifest_sha256": "8e039b42ea5687538c57e4e4eb0e6872af0fef1913fbb65ceae4772e483f619c",
              "contract_sha256": "7b0c4fe2f2a32c7ebb5d22bca456f5dab17dab0f60474546ff3ef0d0aadda12b",
              "run_id": "2026-09-26_dbconformer_hds_r1_lab10_repair3-full-w1",
              "transaction_id": "dbconformer-hds-r1-repair3-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training_single_seed",
        "gates": {
          "mean": false,
          "robustness": false,
          "single_seed_positive": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; no cross-seed stability, mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-sve-r1-repair1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-sve-r1-repair1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-sve-r1-repair1",
      "round_id": "dbconformer-sve-r1-repair1",
      "run": {
        "bundle_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 2.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 4,
        "recorded_at": "2026-09-26T14:56:41.247509+00:00",
        "round_id": "dbconformer-sve-r1-repair1",
        "run_prefix": "2026-09-26_dbconformer_sve_r1_lab10_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-26T14:57:30.962930+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
              "source_manifest_sha256": "406ee1a68a8fb5f5f148eb98289cdb48acd34d840d07a6680c8bae75a30952e0",
              "verified_files": 199
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-26T14:57:43.220993+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T14:58:13.463061+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "280962add6452a78b08c684bb44a5b4a4df6af79cd58810f89edf42c936e29bd",
                "execution_seconds": 5.818862199783325,
                "queue_seconds": 20.1902973651886,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
                "transaction_id": "dbconformer-sve-r1-repair1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 26.009159564971924
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T15:25:41.745552+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "280962add6452a78b08c684bb44a5b4a4df6af79cd58810f89edf42c936e29bd",
                "execution_seconds": 896.0651471614838,
                "queue_seconds": 64.12675619125366,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
                "transaction_id": "dbconformer-sve-r1-repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 960.1919033527374
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-26T15:27:14.477937+00:00",
            "result": {
              "artifact_manifest_sha256": "6f72e2fb6bdd8d947f8520436a4443d0c12558f3d55da30ab63b30c6a974cb36",
              "contract_sha256": "280962add6452a78b08c684bb44a5b4a4df6af79cd58810f89edf42c936e29bd",
              "run_id": "2026-09-26_dbconformer_sve_r1_lab10_repair1-full-w1",
              "transaction_id": "dbconformer-sve-r1-repair1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training_single_seed",
        "gates": {
          "mean": false,
          "robustness": false,
          "single_seed_positive": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; no cross-seed stability, mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-bsd-r1-repair1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-bsd-r1-repair1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-bsd-r1-repair1",
      "round_id": "dbconformer-bsd-r1-repair1",
      "run": {
        "bundle_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 10,
        "recorded_at": "2026-09-27T02:53:46.293758+00:00",
        "round_id": "dbconformer-bsd-r1-repair1",
        "run_prefix": "2026-09-27_dbconformer_bsd_r1_lab10_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T02:55:22.466637+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
              "source_manifest_sha256": "a20572206578c75c2ab2e0e9eb4e9c7eb508e8cf75e9eea6d610b8c72510c4ac",
              "verified_files": 151
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T02:56:14.096501+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T02:56:54.420219+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b60f49dff90759b63d9f860ccebed3febe489206e3b163d88cd0c8c5bbbf3497",
                "execution_seconds": 37.199331283569336,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
                "transaction_id": "dbconformer-bsd-r1-repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 37.199331283569336
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T07:56:03.384500+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b60f49dff90759b63d9f860ccebed3febe489206e3b163d88cd0c8c5bbbf3497",
                "execution_seconds": 1249.8976700305939,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
                "transaction_id": "dbconformer-bsd-r1-repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 1249.8976700305939
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-27T07:57:41.738767+00:00",
            "result": {
              "artifact_manifest_sha256": "0c62695643ef144d3c1738cb79a907da39f3754f7c39beaafb859511138d0398",
              "contract_sha256": "b60f49dff90759b63d9f860ccebed3febe489206e3b163d88cd0c8c5bbbf3497",
              "run_id": "2026-09-27_dbconformer_bsd_r1_lab10_repair1-full-w1",
              "transaction_id": "dbconformer-bsd-r1-repair1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_joint_training_single_seed",
        "gates": {
          "mean": false,
          "robustness": false,
          "single_seed_positive": false,
          "subjects": false
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; no cross-seed stability, mechanism attribution, novelty, independent confirmation, or automatic next round.",
        "reason": "Frozen paired utility gates evaluated",
        "round_id": "dbconformer-sdt-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-sdt-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-sdt-r1",
      "round_id": "dbconformer-sdt-r1",
      "run": {
        "bundle_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 20,
        "recorded_at": "2026-09-27T08:45:16.706833+00:00",
        "round_id": "dbconformer-sdt-r1",
        "run_prefix": "2026-09-27_dbconformer_sdt_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T08:46:33.771605+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
              "source_manifest_sha256": "b58ce54e19b12bfa18b81c2c9814b4bc0af2a8c1d2e29a6ce5967758fcf8cc77",
              "verified_files": 62
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T08:47:29.906505+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T08:48:02.502644+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0d759dd45f74091604c713cf9eaa8150836b9f03ae35050efe471a5615a8385c",
                "execution_seconds": 28.89303469657898,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-sdt-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 28.89303469657898
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T15:20:59.305913+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "0d759dd45f74091604c713cf9eaa8150836b9f03ae35050efe471a5615a8385c",
                "execution_seconds": 8231.885428667068,
                "queue_seconds": 2560.6201968193054,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-sdt-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10792.505625486374
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-27T15:22:11.569309+00:00",
            "result": {
              "artifact_manifest_sha256": "58b2d2c836fa484d8606732303223a5ad72c112e776fd70cd17a4dfbd9500942",
              "contract_sha256": "0d759dd45f74091604c713cf9eaa8150836b9f03ae35050efe471a5615a8385c",
              "run_id": "2026-09-27_dbconformer_sdt_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-sdt-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "evidence_scope": "exploratory_cue_aligned_loso_paired_electrode_robustness_single_seed",
        "gates": {
          "baseline_sensitivity": true,
          "clean_preserved": true,
          "clean_subject_safeguard": false,
          "robust_mean": true,
          "robust_stability": true,
          "single_seed_positive": true,
          "subjects": true
        },
        "interpretation_boundary": "Exploratory historically exposed subjects and one seed; 22 dependent zero-electrode views, no real hardware robustness, cross-seed stability, novelty, mechanism attribution, independent confirmation, or automatic next round.",
        "reason": "Frozen electrode robustness and clean protection gates evaluated",
        "round_id": "dbconformer-edr-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-edr-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-edr-r1",
      "round_id": "dbconformer-edr-r1",
      "run": {
        "bundle_id": "2026-09-27_dbconformer_edr_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 3.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 20,
        "recorded_at": "2026-09-27T15:48:01.756150+00:00",
        "round_id": "dbconformer-edr-r1",
        "run_prefix": "2026-09-27_dbconformer_edr_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T15:48:57.454380+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
              "source_manifest_sha256": "39eee64c854eb08bc68e9fbe2d3eb21f85c995c0e76aabd95d6d2f45901c6ac7",
              "verified_files": 62
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T15:49:32.466774+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T15:50:07.035445+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e2e1993e7baa6940b599671fa56c21ae5b22b95063364452ac5b5f0197e5392c",
                "execution_seconds": 31.311785221099854,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-edr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 31.311785221099854
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T15:52:13.826927+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e2e1993e7baa6940b599671fa56c21ae5b22b95063364452ac5b5f0197e5392c",
                "execution_seconds": 126.6812379360199,
                "queue_seconds": 31.427278757095337,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-edr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 158.10851669311523
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T06:06:14.820255+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "e2e1993e7baa6940b599671fa56c21ae5b22b95063364452ac5b5f0197e5392c",
                "execution_seconds": 5989.2078359127045,
                "queue_seconds": 16309.588497161865,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-edr-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 22298.79633307457
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-28T06:12:14.010619+00:00",
            "result": {
              "artifact_manifest_sha256": "054bb2cad2ba3ebdd38b62288260c6ecabbfec956e44f9b3464d44e00f53c90b",
              "contract_sha256": "e2e1993e7baa6940b599671fa56c21ae5b22b95063364452ac5b5f0197e5392c",
              "run_id": "2026-09-27_dbconformer_edr_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-edr-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INSUFFICIENT_PAIRED_TRAINING_SUPPORT",
        "disposition": "CLOSE_BOTH_EXACT_OBJECTS",
        "evidence_scope": "exploratory_cue_aligned_loso_clean_missing_normalization_single_seed",
        "gates": {
          "M0_utility": {
            "baseline_sensitivity": true,
            "clean_coverage": false,
            "clean_mean": true,
            "clean_subject_safeguard": false,
            "robust_mean": true,
            "robust_stability": true,
            "robust_subjects": true
          },
          "P1_utility": {
            "baseline_sensitivity": true,
            "clean_coverage": false,
            "clean_mean": true,
            "clean_subject_safeguard": false,
            "robust_mean": true,
            "robust_stability": true,
            "robust_subjects": true
          },
          "normalization_increment": {
            "clean_mean": false,
            "clean_stability": false,
            "clean_subjects": false,
            "robust_noninferiority": false
          }
        },
        "interpretation_boundary": "Exploratory9subjects seed0 and22dependentviews; known missingness metadata; no information-loss theorem, mechanism proof, cross-seed claim or automatic next round. P1 wrong-bank clean view describes same-weight inference-statistics effect only.",
        "reason": "Prospective clean preservation, robustness and conditional-normalization increment gates evaluated",
        "round_id": "dbconformer-cmn-r1-repair1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-cmn-r1-repair1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-cmn-r1-repair1",
      "round_id": "dbconformer-cmn-r1-repair1",
      "run": {
        "bundle_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 30,
        "recorded_at": "2026-09-28T16:21:41.788402+00:00",
        "round_id": "dbconformer-cmn-r1-repair1",
        "run_prefix": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-28T16:22:18.028841+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
              "source_manifest_sha256": "3332ef21f988f79acf549394a5a8e6e0dd5bc8370e16df658fc18f496ee09a81",
              "verified_files": 62
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-28T16:23:03.890254+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T16:23:17.445041+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "9dd1413561e6c18a5b10972a4eacd116dc74dd2a19cf90fba79b776effac4de2",
                "execution_seconds": 10.985708475112915,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cmn-r1-repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10.985708475112915
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-28T16:25:14.742332+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "9dd1413561e6c18a5b10972a4eacd116dc74dd2a19cf90fba79b776effac4de2",
                "execution_seconds": 128.2819938659668,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cmn-r1-repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 128.2819938659668
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T02:23:58.290361+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "9dd1413561e6c18a5b10972a4eacd116dc74dd2a19cf90fba79b776effac4de2",
                "execution_seconds": 8739.552785158157,
                "queue_seconds": 476.88529753685,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cmn-r1-repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9216.438082695007
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-29T02:24:32.574424+00:00",
            "result": {
              "artifact_manifest_sha256": "7819d8be7a5475feecf5f89eef1b8c4c78860940ea90179cb2463fe9bfc229bc",
              "contract_sha256": "9dd1413561e6c18a5b10972a4eacd116dc74dd2a19cf90fba79b776effac4de2",
              "run_id": "2026-09-29_dbconformer_cmn_r1_repair1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-cmn-r1-repair1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "INVALID",
        "reason": "CPA evidence/integrity closure failed",
        "round_id": "dbconformer-cpa-r1"
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-cpa-r1_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-cpa-r1",
      "round_id": "dbconformer-cpa-r1",
      "run": {
        "bundle_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 20,
        "recorded_at": "2026-09-29T09:13:24.739188+00:00",
        "round_id": "dbconformer-cpa-r1",
        "run_prefix": "2026-09-29_dbconformer_cpa_r1_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T09:14:04.324058+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "source_manifest_sha256": "79a59bd47e72b49b4acbb5d058930ec0a7ba9b3ecbafabb57fa20fc36ec448da",
              "verified_files": 93
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T09:15:20.821497+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:15:36.624210+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
                "execution_seconds": 8.564533710479736,
                "queue_seconds": 2.0311388969421387,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-r1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 10.595672607421875
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T09:17:28.870151+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
                "execution_seconds": 8.56400728225708,
                "queue_seconds": 114.28172087669373,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-r1-tx",
                "waiting_for_resources": true,
                "wall_seconds": 122.8457281589508
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T11:45:17.375266+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
                "execution_seconds": 6611.000871419907,
                "queue_seconds": 2380.7822489738464,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8991.783120393753
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T13:02:26.251896+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
                "execution_seconds": 11240.101088762283,
                "queue_seconds": 2380.7822489738464,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13620.88333773613
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T13:23:32.349854+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
                "execution_seconds": 11535.728231191635,
                "queue_seconds": 2380.7822489738464,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-r1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 13916.510480165482
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-29T13:23:58.837903+00:00",
            "result": {
              "artifact_manifest_sha256": "fdcff8d4be74f9033362cc772dc3a791fa0c338a5c1a2e841ea6536d7d73f898",
              "contract_sha256": "911f8321dd199d408352fd7c05aaf53776a4c78ae2fab208866a293acd998c11",
              "run_id": "2026-09-29_dbconformer_cpa_r1_lab10_r1-full-w1",
              "transaction_id": "dbconformer-cpa-r1-tx",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_release": false,
        "decision": "CPA_U0_ADAPTER_SEED_STABILITY_SUPPORT",
        "interpretation_boundary": "9 subjects are the statistical units; two adapter seeds are repeated training, seed0 is descriptive only and never pooled to rescue a failure.",
        "reason": "both fresh-seed gates and subject-wise fresh-seed-average gate evaluated",
        "round_id": "dbconformer-cpa-u0-r2-packagefix3",
        "utility_gates": {
          "seed1": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.347892992424242,
                7.350852272727273
              ],
              [
                7.289693813131313,
                7.292653093434344
              ],
              [
                5.749881628787881,
                5.751854482323234
              ],
              [
                6.90893308080808,
                6.910905934343435
              ],
              [
                7.302517361111111,
                7.305476641414142
              ],
              [
                6.604127209595959,
                6.606100063131314
              ],
              [
                6.737294823232323,
                6.740254103535354
              ],
              [
                7.353811553030304,
                7.356770833333335
              ],
              [
                7.710898042929292,
                7.7138573232323235
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.00056116722784,
              "positive_subjects": 9,
              "worst_subject": 1.3178661616161662
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          },
          "seed2": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.449494949494949,
                7.451467803030303
              ],
              [
                7.39425505050505,
                7.396227904040404
              ],
              [
                6.0625789141414135,
                6.064551767676767
              ],
              [
                7.091422032828281,
                7.093394886363635
              ],
              [
                7.53728693181818,
                7.539259785353534
              ],
              [
                6.9296480429292915,
                6.931620896464645
              ],
              [
                6.717566287878785,
                6.718552714646463
              ],
              [
                7.351838699494948,
                7.353811553030302
              ],
              [
                7.930871212121212,
                7.931857638888888
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.163650392817065,
              "positive_subjects": 9,
              "worst_subject": 1.025883838383841
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          },
          "subject_wise_fresh_seed_mean": {
            "determinate": true,
            "loo_intervals_pp": [
              [
                7.398693970959596,
                7.401160037878787
              ],
              [
                7.3419744318181825,
                7.344440498737374
              ],
              [
                5.906230271464648,
                5.908203125
              ],
              [
                7.000177556818182,
                7.002150410353535
              ],
              [
                7.419902146464646,
                7.422368213383837
              ],
              [
                6.766887626262626,
                6.768860479797979
              ],
              [
                6.7274305555555545,
                6.729403409090908
              ],
              [
                7.352825126262627,
                7.355291193181818
              ],
              [
                7.820884627525253,
                7.8228574810606055
              ]
            ],
            "loo_per_omission_status": [
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true,
              true
            ],
            "pass": true,
            "point_estimate": {
              "mean": 7.082105780022453,
              "positive_subjects": 9,
              "worst_subject": 1.1718750000000036
            },
            "subgates": {
              "all_loo_positive": true,
              "mean": true,
              "positive_subjects": true,
              "worst_subject": true
            }
          }
        }
      },
      "decision_record": "ai4s/programs/dbconformer/research/dbconformer-cpa-u0-r2-packagefix3_decision.yaml",
      "evidence_id": "AI4S-DBCONFORMER-dbconformer-cpa-u0-r2-packagefix3",
      "round_id": "dbconformer-cpa-u0-r2-packagefix3",
      "run": {
        "bundle_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1_bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 20,
        "recorded_at": "2026-09-30T05:58:09.799781+00:00",
        "round_id": "dbconformer-cpa-u0-r2-packagefix3",
        "run_prefix": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-30T05:58:36.337584+00:00",
            "result": {
              "action": "UPLOADED",
              "asset_reused_files": 4,
              "method": "new code archive plus SHA-matched existing data copy; full bundle SHA verified",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "remote_bundle": "[REDACTED_MACHINE]",
              "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
              "source_manifest_sha256": "264529cb5fcf5ec4a216a5bb9cb3352de67370fffc29445bf36b44f43925a617",
              "verified_files": 104
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-30T05:59:50.332522+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-30T06:00:01.424120+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b8b7793d437ae6843dde84d51ad48651af3c12928c6880c39a8fe7385c353aec",
                "execution_seconds": 6.1747214794158936,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-u0-r2-packagefix3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 6.1747214794158936
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-30T06:02:26.919489+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b8b7793d437ae6843dde84d51ad48651af3c12928c6880c39a8fe7385c353aec",
                "execution_seconds": 151.6606843471527,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-u0-r2-packagefix3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 151.6606843471527
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-03T08:19:01.393555+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b8b7793d437ae6843dde84d51ad48651af3c12928c6880c39a8fe7385c353aec",
                "execution_seconds": 5558.900381565094,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_dbconformer_cpa_u0_r2_packagefix3_lab10_r1-full-w1",
                "transaction_id": "dbconformer-cpa-u0-r2-packagefix3-tx",
                "waiting_for_resources": false,
                "wall_seconds": 5558.900381565094
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "b0_absolute_performance": {
          "n_fits": 18,
          "n_subjects": 9,
          "rows": [
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "3cb3f362924f053537c7f1278f331860d83f97cfbb56c4d894bde9f0fef7a0a4",
              "difference_vs_seed0_clean_pp": -1.2152777777777786,
              "difference_vs_seed0_missing_pp": -0.3314393939393909,
              "historical_seed0_clean_acc_pp": 62.15277777777778,
              "historical_seed0_missing_acc_pp": 48.07449494949494,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 78.23275862068965,
              "subject": 0,
              "target_clean_acc_pp": 60.9375,
              "target_missing_acc_pp": 47.74305555555555,
              "target_missing_per_channel_acc_pp": [
                56.25,
                54.6875,
                56.770833333333336,
                59.02777777777778,
                56.423611111111114,
                46.875,
                60.06944444444444,
                28.47222222222222,
                45.3125,
                38.88888888888889,
                51.90972222222222,
                48.95833333333333,
                52.43055555555556,
                33.50694444444444,
                53.47222222222222,
                33.15972222222222,
                46.875,
                46.52777777777778,
                37.15277777777778,
                59.375,
                42.1875,
                42.01388888888889
              ],
              "task_id": "B0_s0_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "bf2d5a11c1abc85427a00a8ce981a9c37c80249e29c4e095f27e0efa3fb11f15",
              "difference_vs_seed0_clean_pp": -2.256944444444443,
              "difference_vs_seed0_missing_pp": 0.4419191919191974,
              "historical_seed0_clean_acc_pp": 62.15277777777778,
              "historical_seed0_missing_acc_pp": 48.07449494949494,
              "source_valid_best_epoch": 89,
              "source_valid_clean_acc_pp": 78.125,
              "subject": 0,
              "target_clean_acc_pp": 59.895833333333336,
              "target_missing_acc_pp": 48.51641414141414,
              "target_missing_per_channel_acc_pp": [
                57.8125,
                55.208333333333336,
                57.986111111111114,
                55.03472222222222,
                55.729166666666664,
                46.875,
                58.15972222222222,
                27.77777777777778,
                48.78472222222222,
                37.84722222222222,
                58.68055555555556,
                45.65972222222222,
                58.68055555555556,
                36.45833333333333,
                59.201388888888886,
                43.40277777777778,
                43.22916666666667,
                48.61111111111111,
                45.48611111111111,
                49.82638888888889,
                42.53472222222222,
                34.375
              ],
              "task_id": "B0_s0_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "a941537ccff0ebbffd3773550b14d6466a43329fa1bc71667328debb81c8c531",
              "difference_vs_seed0_clean_pp": -0.6944444444444429,
              "difference_vs_seed0_missing_pp": 0.6313131313131315,
              "historical_seed0_clean_acc_pp": 42.88194444444444,
              "historical_seed0_missing_acc_pp": 31.723484848484848,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 82.11206896551724,
              "subject": 1,
              "target_clean_acc_pp": 42.1875,
              "target_missing_acc_pp": 32.35479797979798,
              "target_missing_per_channel_acc_pp": [
                35.59027777777778,
                31.25,
                31.944444444444443,
                40.10416666666667,
                35.9375,
                37.84722222222222,
                37.84722222222222,
                37.15277777777778,
                30.90277777777778,
                28.125,
                30.729166666666668,
                34.54861111111111,
                35.41666666666667,
                25.17361111111111,
                31.07638888888889,
                31.770833333333332,
                25.0,
                25.694444444444443,
                28.819444444444443,
                40.10416666666667,
                26.041666666666668,
                30.729166666666668
              ],
              "task_id": "B0_s1_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "b6e915b22d74eeef22c7c26ae6f41fdea8cb0af80b88dfa6918b96191b4e6dd2",
              "difference_vs_seed0_clean_pp": -1.2152777777777715,
              "difference_vs_seed0_missing_pp": -0.2840909090909136,
              "historical_seed0_clean_acc_pp": 42.88194444444444,
              "historical_seed0_missing_acc_pp": 31.723484848484848,
              "source_valid_best_epoch": 97,
              "source_valid_clean_acc_pp": 82.86637931034483,
              "subject": 1,
              "target_clean_acc_pp": 41.66666666666667,
              "target_missing_acc_pp": 31.439393939393934,
              "target_missing_per_channel_acc_pp": [
                34.02777777777778,
                33.50694444444444,
                40.10416666666667,
                33.33333333333333,
                32.29166666666667,
                27.604166666666668,
                30.208333333333332,
                31.944444444444443,
                31.42361111111111,
                24.479166666666664,
                37.84722222222222,
                34.54861111111111,
                37.67361111111111,
                25.520833333333332,
                33.33333333333333,
                25.0,
                30.03472222222222,
                26.5625,
                26.90972222222222,
                37.5,
                26.5625,
                31.25
              ],
              "task_id": "B0_s1_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "459a3377d0fed180b12cf708a364fecc91d144de74e57a49cc5bdd2920c58387",
              "difference_vs_seed0_clean_pp": -1.5625,
              "difference_vs_seed0_missing_pp": 2.3674242424242493,
              "historical_seed0_clean_acc_pp": 81.07638888888889,
              "historical_seed0_missing_acc_pp": 57.930871212121204,
              "source_valid_best_epoch": 96,
              "source_valid_clean_acc_pp": 77.37068965517241,
              "subject": 2,
              "target_clean_acc_pp": 79.51388888888889,
              "target_missing_acc_pp": 60.29829545454545,
              "target_missing_per_channel_acc_pp": [
                73.4375,
                65.97222222222221,
                78.29861111111111,
                79.34027777777779,
                71.875,
                81.59722222222221,
                55.38194444444444,
                44.27083333333333,
                63.541666666666664,
                41.84027777777778,
                75.52083333333334,
                64.40972222222221,
                80.90277777777779,
                40.79861111111111,
                68.75,
                45.3125,
                49.65277777777778,
                57.638888888888886,
                45.48611111111111,
                53.125,
                42.53472222222222,
                46.875
              ],
              "task_id": "B0_s2_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "0817f219b8ce3e81c3977984c4dea417245203f214f1144ea773a209e4e57838",
              "difference_vs_seed0_clean_pp": 1.3888888888889,
              "difference_vs_seed0_missing_pp": -0.3472222222222143,
              "historical_seed0_clean_acc_pp": 81.07638888888889,
              "historical_seed0_missing_acc_pp": 57.930871212121204,
              "source_valid_best_epoch": 89,
              "source_valid_clean_acc_pp": 75.86206896551724,
              "subject": 2,
              "target_clean_acc_pp": 82.46527777777779,
              "target_missing_acc_pp": 57.58364898989899,
              "target_missing_per_channel_acc_pp": [
                79.16666666666666,
                63.541666666666664,
                82.46527777777779,
                74.13194444444444,
                76.73611111111111,
                76.5625,
                49.30555555555556,
                39.40972222222222,
                52.604166666666664,
                45.65972222222222,
                64.0625,
                63.541666666666664,
                82.46527777777779,
                30.555555555555557,
                64.0625,
                47.91666666666667,
                47.74305555555556,
                40.79861111111111,
                32.63888888888889,
                59.72222222222222,
                40.45138888888889,
                53.298611111111114
              ],
              "task_id": "B0_s2_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "4aea046c5051a104f0bc6d1166c777722eaa92269ce31f0a3948e060960d2e08",
              "difference_vs_seed0_clean_pp": 1.3888888888888928,
              "difference_vs_seed0_missing_pp": -0.38667929292930125,
              "historical_seed0_clean_acc_pp": 50.34722222222222,
              "historical_seed0_missing_acc_pp": 38.99147727272727,
              "source_valid_best_epoch": 91,
              "source_valid_clean_acc_pp": 79.84913793103449,
              "subject": 3,
              "target_clean_acc_pp": 51.736111111111114,
              "target_missing_acc_pp": 38.60479797979797,
              "target_missing_per_channel_acc_pp": [
                46.875,
                45.83333333333333,
                50.69444444444444,
                43.57638888888889,
                44.44444444444444,
                39.0625,
                44.27083333333333,
                27.430555555555557,
                33.85416666666667,
                34.375,
                40.27777777777778,
                31.25,
                47.74305555555556,
                27.77777777777778,
                47.56944444444444,
                44.61805555555556,
                27.604166666666668,
                37.5,
                26.041666666666668,
                53.81944444444444,
                25.520833333333332,
                29.166666666666668
              ],
              "task_id": "B0_s3_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "4959383f762e094f21b93bcbf657d3f7da48930928d566f2e8c497ce289212ea",
              "difference_vs_seed0_clean_pp": -3.2986111111111143,
              "difference_vs_seed0_missing_pp": -2.012310606060602,
              "historical_seed0_clean_acc_pp": 50.34722222222222,
              "historical_seed0_missing_acc_pp": 38.99147727272727,
              "source_valid_best_epoch": 92,
              "source_valid_clean_acc_pp": 80.60344827586206,
              "subject": 3,
              "target_clean_acc_pp": 47.04861111111111,
              "target_missing_acc_pp": 36.97916666666667,
              "target_missing_per_channel_acc_pp": [
                43.75,
                39.0625,
                43.40277777777778,
                47.04861111111111,
                41.49305555555556,
                36.11111111111111,
                41.14583333333333,
                26.73611111111111,
                37.15277777777778,
                33.68055555555556,
                37.15277777777778,
                29.86111111111111,
                43.75,
                30.03472222222222,
                46.35416666666667,
                42.88194444444444,
                34.20138888888889,
                38.54166666666667,
                25.520833333333332,
                42.01388888888889,
                28.645833333333332,
                25.0
              ],
              "task_id": "B0_s3_seed2"
            },
            {
              "backbone_seed": 1,
              "checkpoint_sha256": "c4627c2430e5889278c43e3c1027d739cb5d7a83b925726609ddb74ba95b5001",
              "difference_vs_seed0_clean_pp": -1.0416666666666572,
              "difference_vs_seed0_missing_pp": 1.2468434343434325,
              "historical_seed0_clean_acc_pp": 44.27083333333333,
              "historical_seed0_missing_acc_pp": 34.540719696969695,
              "source_valid_best_epoch": 86,
              "source_valid_clean_acc_pp": 81.46551724137932,
              "subject": 4,
              "target_clean_acc_pp": 43.22916666666667,
              "target_missing_acc_pp": 35.78756313131313,
              "target_missing_per_channel_acc_pp": [
                42.88194444444444,
                28.819444444444443,
                44.09722222222222,
                43.57638888888889,
                26.21527777777778,
                29.166666666666668,
                42.01388888888889,
                44.44444444444444,
                39.93055555555556,
                34.54861111111111,
                35.41666666666667,
                27.256944444444443,
                31.07638888888889,
                25.868055555555557,
                36.80555555555556,
                36.63194444444444,
                28.47222222222222,
                35.76388888888889,
                25.0,
                51.388888888888886,
                26.90972222222222,
                51.041666666666664
              ],
              "task_id": "B0_s4_seed1"
            },
            {
              "backbone_seed": 2,
              "checkpoint_sha256": "180fdc7bde7efd4ac1ec2c39000da067cf434bd4f48681c7f316a8a37a51eeae",
              "difference_vs_seed0_clean_pp": -0.86805555555555,
              "difference_vs_seed0_missing_pp": 0.09469696969696173,
              "historical_seed0_clean_acc_pp": 44.27083333333333,
              "historical_seed0_missing_acc_pp": 34.540719696969695,
              "source_valid_best_epoch": 100,
              "source_valid_clean_acc_pp": 79.95689655172413,
              "subject": 4,
              "target_clean_acc_pp": 43.40277777777778,
              "target_missing_acc_pp": 34.63541666666666,
              "target_missing_per_channel_acc_pp": [
                45.3125,
                36.45833333333333,
                45.83333333333333,
                38.54166666666667,
                29.34027777777778,
                33.15972222222222,
                36.28472222222222,
                42.53472222222222,
                32.29166666666667,
                37.84722222222222,
                37.84722222222222,
                31.59722222222222,
                42.88194444444444,
                25.520833333333332,
                28.645833333333332,
                25.17361111111111,
                34.20138888888889,
                
```
