# State 阅读分段 2

完整脱敏文件：`ai4s/programs/dsainet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`5facb7140fb8c0d253b3f264b975d0fec60c9086af9553f6322c9439338ea52b`。UTF-8 字节范围：[500000, 1000000) / 1086722。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
ecution_mode": "ai4s_autopilot",
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
      "authorized_at": "2026-10-12T13:31:22.244478+00:00",
      "reason": "Remove unsupported scheduler CLI option; policy remains read from frozen contract. Zero fits, no science change, original campaign clock/cost retained.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-repair1.yaml",
      "repair_round_id": "dsa-rcd-v0.1-repair1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1_decision.yaml",
      "source_round_id": "dsa-rcd-v0.1",
      "source_run_id": "2026-10-12_dsainet_rcd_v0_1-full-w1"
    },
    {
      "authorized_at": "2026-10-13T05:40:46.216956+00:00",
      "reason": "User-authorized repair: sampler-to-worker telemetry ACK; hash-qualified technical asset recovery, one B0 audit only. No original scientific output admitted.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-repair2.yaml",
      "repair_round_id": "dsa-rcd-v0.1-repair2",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-repair1_decision.yaml",
      "source_round_id": "dsa-rcd-v0.1-repair1",
      "source_run_id": "2026-10-12_dsainet_rcd_v0_1_repair1-full-w1"
    },
    {
      "authorized_at": "2026-10-13T12:17:53.448154+00:00",
      "reason": "User-authorized bounded telemetry-timeout repair; independently hash-qualified four complete fit inputs and four technical tasks; only68 remaining fits then72 audits; all accrued cost retained.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-resume1.yaml",
      "repair_round_id": "dsa-rcd-v0.1-resume1",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-repair2_decision.yaml",
      "source_round_id": "dsa-rcd-v0.1-repair2",
      "source_run_id": "2026-10-13_dsainet_rcd_v0_1_repair2-full-w1"
    },
    {
      "authorized_at": "2026-10-14T13:59:38.721341+00:00",
      "reason": "User authorized repair with cumulative48h: keep all hash-qualified complete fits after natural source drain; train only exact remainder with10800s engineering deadline and unchanged numerical protocol, then72 audits.",
      "repair_contract": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-resume3.yaml",
      "repair_round_id": "dsa-rcd-v0.1-resume3",
      "source_decision_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-resume2_decision.yaml",
      "source_round_id": "dsa-rcd-v0.1-resume2",
      "source_run_id": "2026-10-14_dsainet_rcd_v0_1_resume2-full-w1"
    },
    {
      "authorized_at": "2026-10-23T18:15:18.086627+00:00",
      "reason": "User-authorized limit-only revision: cumulative72h/science60h, same original start/matrix/estimator; old Run immutable.",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r1-limit72-r1.yaml",
      "repair_round_id": "p0-cue-r1-limit72-r1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r1_decision.yaml",
      "source_round_id": "p0-cue-r1",
      "source_run_id": "2026-10-23_dsainet_p0_cue_r1-full-w1"
    },
    {
      "authorized_at": "2026-10-23T18:30:33.549052+00:00",
      "reason": "Explicit user-authorized engineering cost calibration: retain72h/60h, original clock and54x100 matrix, source-only3x5epoch technical qualification, unchanged scientific effects/gates.",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r1-costcal-r1.yaml",
      "repair_round_id": "p0-cue-r1-costcal-r1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r1-limit72-r1_decision.yaml",
      "source_round_id": "p0-cue-r1-limit72-r1",
      "source_run_id": "2026-10-24_dsainet_p0_cue_r1_limit72_r1-full-w1"
    },
    {
      "authorized_at": "2026-10-24T07:41:15.291497+00:00",
      "reason": "Correct final transport authorization byte binding before immutable packaging; source verification stopped all TECH before model execution; preserve science and budget",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-packfix1.yaml",
      "repair_round_id": "p0-cue-r2-packfix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2_decision.yaml",
      "source_round_id": "p0-cue-r2",
      "source_run_id": "2026-10-24_dsainet_p0_cue_r2_ls010-full-w1"
    },
    {
      "authorized_at": "2026-10-24T15:15:22.785460+00:00",
      "reason": "User explicitly raises SCI cap37h, preserves original72h/clock/41h Tx/matrix; separate science bound from4h closeout total bound",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-packfix2.yaml",
      "repair_round_id": "p0-cue-r2-packfix2",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-packfix1_decision.yaml",
      "source_round_id": "p0-cue-r2-packfix1",
      "source_run_id": "2026-10-24_dsainet_p0_cue_r2_ls010_packfix1-full-w1"
    },
    {
      "authorized_at": "2026-10-25T02:25:17.946804+00:00",
      "reason": "Diagnosed steady-epoch dominated cost; instrument phases/resources and qualify CPU thread cap before unchanged scientific matrix/cost policy",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-perffix1.yaml",
      "repair_round_id": "p0-cue-r2-perffix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-packfix2_decision.yaml",
      "source_round_id": "p0-cue-r2-packfix2",
      "source_run_id": "2026-10-24_dsainet_p0_cue_r2_ls010_packfix2-full-w1"
    },
    {
      "authorized_at": "2026-10-25T14:43:04.263934+00:00",
      "reason": "Zero GPU attempts timed out because capacity polling closed queue clock and exceeded heartbeat freshness; repair accounting boundary only with original budget/clock/matrix/gates",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-waitfix1.yaml",
      "repair_round_id": "p0-cue-r2-waitfix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-perffix1_decision.yaml",
      "source_round_id": "p0-cue-r2-perffix1",
      "source_run_id": "2026-10-25_dsainet_p0_cue_r2_perffix1-full-w1"
    },
    {
      "authorized_at": "2026-10-25T17:21:48.608634+00:00",
      "reason": "Optimize diagnostic-only gradient finiteness host synchronization; qualify exact GPU trajectory before remeasuring unchanged complete-stage cost; no gate relaxation",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-finitefix1.yaml",
      "repair_round_id": "p0-cue-r2-finitefix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-waitfix1_decision.yaml",
      "source_round_id": "p0-cue-r2-waitfix1",
      "source_run_id": "2026-10-25_dsainet_p0_cue_r2_waitfix1-full-w1"
    },
    {
      "authorized_at": "2026-10-26T03:17:16.538663+00:00",
      "reason": "Fresh post-owner GPU health and verified pre-model capacity deferral; flatten diagnostic reduction; qualify exact GPU trajectory then remeasure unchanged full scientific cost without budget relaxation",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-flatfix1.yaml",
      "repair_round_id": "p0-cue-r2-flatfix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-finitefix1_decision.yaml",
      "source_round_id": "p0-cue-r2-finitefix1",
      "source_run_id": "2026-10-26_dsainet_p0_cue_r2_finitefix1-full-w1"
    },
    {
      "authorized_at": "2026-10-26T15:06:00.493300+00:00",
      "reason": "Strict canonical GPU index parsing fixes real string/int producer-consumer mismatch; unchanged science/qualification/TECH/cost gates and cumulative budget",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-typefix1.yaml",
      "repair_round_id": "p0-cue-r2-typefix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-flatfix1_decision.yaml",
      "source_round_id": "p0-cue-r2-flatfix1",
      "source_run_id": "2026-10-26_dsainet_p0_cue_r2_flatfix1-full-w1"
    },
    {
      "authorized_at": "2026-10-27T05:30:10.210012+00:00",
      "reason": "explicit86h S0-only technical repair; original-environment acceptance before S0 qualification/5epochTECH; retain old B0/P0; CPU cost report only, no scientific training",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-s0tech1.yaml",
      "repair_round_id": "p0-cue-r2-s0tech1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-typefix1_decision.yaml",
      "source_round_id": "p0-cue-r2-typefix1",
      "source_run_id": "2026-10-26_dsainet_p0_cue_r2_typefix1-full-w1"
    },
    {
      "authorized_at": "2026-10-27T17:50:03.083790+00:00",
      "reason": "new explicit user authorization for original SCI matrix after verified CPU technical recovery; reuse completed source-only TECH without retraining; original failed record preserved",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-science1.yaml",
      "repair_round_id": "p0-cue-r2-science1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-s0tech1_decision.yaml",
      "source_round_id": "p0-cue-r2-s0tech1",
      "source_run_id": "2026-10-27_dsainet_p0_cue_r2_s0tech1-full-w1"
    },
    {
      "authorized_at": "2026-10-27T17:59:00.656974+00:00",
      "reason": "new explicit user authorization for original SCI matrix after verified CPU technical recovery; reuse completed source-only TECH without retraining; original failed record preserved",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-science1-packfix1.yaml",
      "repair_round_id": "p0-cue-r2-science1-packfix1",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-s0tech1_decision.yaml",
      "source_round_id": "p0-cue-r2-s0tech1",
      "source_run_id": "2026-10-27_dsainet_p0_cue_r2_s0tech1-full-w1"
    },
    {
      "authorized_at": "2026-10-27T18:16:41.007687+00:00",
      "reason": "pre-dispatch audit-reserve serialization ABI fix; original formula/cost unchanged; prior Run reuse and cost PASS but no scientific task dispatched; preserve failure and52.0389s execution without refund",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-science1-dispatchfix2.yaml",
      "repair_round_id": "p0-cue-r2-science1-dispatchfix2",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-science1-packfix1_decision.yaml",
      "source_round_id": "p0-cue-r2-science1-packfix1",
      "source_run_id": "2026-10-28_dsainet_p0_cue_r2_science1_packfix1-full-w1"
    },
    {
      "authorized_at": "2026-10-28T05:56:09.810254+00:00",
      "reason": "user explicitly authorized exact53 forensic artifact reuse and only missing B0_s0_t7 fit, then original54 audit; fix resource wait exit propagation; old INVALID preserved",
      "repair_contract": "ai4s/programs/dsainet/research/p0-cue-r2-recover53.yaml",
      "repair_round_id": "p0-cue-r2-recover53",
      "source_decision_record": "ai4s/programs/dsainet/research/p0-cue-r2-science1-dispatchfix2_decision.yaml",
      "source_round_id": "p0-cue-r2-science1-dispatchfix2",
      "source_run_id": "2026-10-28_dsainet_p0_cue_r2_science1_dispatchfix2-full-w1"
    }
  ],
  "last_audit2_96_recovery": {
    "actual_process_count": 0,
    "additional_budget_hours": 0,
    "automatic_monitor_enabled": false,
    "campaign_started_at_epoch": 1792387110,
    "checked_at": "2026-10-23T07:55:13.322030+00:00",
    "controller_failure": {
      "at": "2026-10-23T06:39:14.750316+00:00",
      "error": "prior scope not exactly 187 successes plus authorized 2 missing",
      "error_type": "AssertionError",
      "status": "BLOCKED_NO_AUTOMATIC_RETRY",
      "traceback": "Traceback (most recent call last):\n  File \"[REDACTED_MACHINE]\", line 58, in <module>\n    try:main()\n  File \"[REDACTED_MACHINE]\", line 35, in main\n    assert len(done)==187 and ids-done==MISSING,'prior scope not exactly 187 successes plus authorized 2 missing'\nAssertionError: prior scope not exactly 187 successes plus authorized 2 missing\n"
    },
    "controller_pid": 3102670,
    "cumulative_budget_hours": 96,
    "dispatch_count": 0,
    "dispatch_scope": [
      "GW_s0_t7",
      "GW_s1_t7"
    ],
    "failed_audit_ids": [
      "GL_s2_t5",
      "GW_s0_t7",
      "GW_s1_t7"
    ],
    "formal_audits_completed": 186,
    "mode": "one-shot pidfd blocking drain then qualify and launch",
    "other_stages_authorized": false,
    "preflight_status": "NOT_STARTED_PRIOR_CLOSURE_FAILED",
    "preservation_errors": [],
    "preserved_required_audits": 187,
    "prior_pid": 2646206,
    "prior_scheduler_exited": true,
    "recovery_id": "2026-10-23_NRC1repair3_audit2_96_r1",
    "remaining_seconds": 16090.221801042557,
    "remaining_seconds_at_wait": 24075.79141497612,
    "remote_package": "[REDACTED_MACHINE]",
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit2_96/REPAIR_NOTES.md",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "status": "BLOCKED_PRIOR_CLOSURE_186_NOT_187"
  },
  "last_audit3_96_recovery": {
    "analysis": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit3_96/ANALYSIS.json",
    "analysis_sha256": "82ed2cdf8e2be595a495a5d7806374d44505950de37d0472f87762ba16a0818a",
    "artifact_manifest_sha256": "0e3956d5028517ae7f8fc33e91be70cfdb46b433e945d3bbc6a55282b0c2315f",
    "automation_enabled": false,
    "budget_checked_at": "2026-10-23T12:45:19.136995+00:00",
    "budget_compliance": "EXCEEDED_DURING_CLOSEOUT_INTAKE_ANALYSIS",
    "budget_limit_hours": 96,
    "budget_remaining_seconds_at_last_check": -1315.5931639671326,
    "contract_sha256": "3666bec81ef4aab5bc6a437fb0fde27f9684f0c64f365b04be42ab29d40542ef",
    "evidence_id": "dsainet-nrc1-repair3-complete-20261023",
    "formal_audits_completed": 189,
    "formal_claim_created": false,
    "frozen_gate_pass": false,
    "independent_metrics_sha256": "92cc39127b5f4d7808d44bec957c4a08ea9c79aff839d0f2184c3ba69541100a",
    "intake": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/intake/NRC1repair3_complete_20261023",
    "matrix": {
      "formal_audit_count": 189,
      "formal_fit_count": 189,
      "technical_audit_count": 8,
      "technical_fit_count": 8,
      "temperature_fit_count": 216
    },
    "new_successful_audits": 3,
    "other_stages_started": false,
    "prior_success_preserved": 186,
    "recovery_id": "2026-10-23_NRC1repair3_audit3_96_r1",
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit3_96/RESULTS_ZH.md",
    "report_sha256": "be39afa7937a6debd8c2bae3b811dbac30f58fa7f0807baae68aabc1651507ac",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "scientific_interpretation": "native fallback preserved; modest improvement; frozen effective complementarity gates not established",
    "status": "ARTIFACTS_VERIFIED_ANALYSIS_COMPLETE_WITH_BUDGET_DEVIATION"
  },
  "last_audit96_recovery": {
    "actual_audit_worker_count": 1,
    "additional_budget_hours": 8,
    "audit_cache_preserved": 27,
    "automatic_monitor_enabled": false,
    "automatic_retry": false,
    "cache_dispatch_count": 0,
    "calibration_preserved": 216,
    "campaign_started_at_epoch": 1792387110,
    "checked_at": "2026-10-23T07:55:13.322030+00:00",
    "cumulative_budget_hours": 96,
    "failed_audit_ids": [
      "GL_s2_t5",
      "GW_s0_t7",
      "GW_s1_t7"
    ],
    "failure_reason": "two consecutive fresh GPU memory observations not obtained within original 60-second resource preflight",
    "fit_dispatch_count": 0,
    "formal_audits_completed": 186,
    "new_worker_returns": {
      "checked_at": "2026-10-23T02:59:30.146165+00:00",
      "failures": [],
      "new_returned": 2,
      "new_successful": 2,
      "overlap_preserved": [],
      "task_ids": [
        "GL_s0_t3",
        "GG_s0_t3"
      ]
    },
    "observed_physical_gpus": [
      1,
      2,
      4,
      8,
      9
    ],
    "other_stages_authorized": false,
    "parent_pid": 2646206,
    "preservation_errors": [],
    "preserved_audits": 18,
    "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit96/QUALIFICATION_REMOTE.json",
    "recovery_id": "2026-10-23_NRC1repair3_audit96_r1",
    "remaining_audit_dispatch_scope": 171,
    "remaining_seconds": 16090.221801042557,
    "remote_package": "[REDACTED_MACHINE]",
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit96/REPAIR_NOTES.md",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "scheduler_snapshot": {
      "completed": 124,
      "failed": 2,
      "families": {
        "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629": {
          "calibration_source": "unknown_family_serial_start",
          "commitment": 3072,
          "expand_after_measurement": true,
          "failed": false,
          "limit": 189,
          "max_family_jobs": 189,
          "peak": 899
        }
      },
      "journal_count": 130,
      "pending": 42,
      "running": 3,
      "running_tasks": {
        "GG_s2_t3": {
          "attempt_output": "task_attempts/GG_s2_t3/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 8,
          "observed": 0,
          "pids": []
        },
        "GL_s2_t3": {
          "attempt_output": "task_attempts/GL_s2_t3/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 1,
          "observed": 0,
          "pids": [
            3059233
          ]
        },
        "LL_s2_t3": {
          "attempt_output": "task_attempts/LL_s2_t3/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 2,
          "observed": 0,
          "pids": []
        }
      },
      "total": 171,
      "updated_at": "2026-10-23T05:28:07.591694+00:00"
    },
    "status": "FAILED",
    "training_preserved": 189
  },
  "last_audit_cache2_recovery": {
    "audit_cache_new_failures": 0,
    "audit_cache_pending": 0,
    "audit_cache_recovered": 2,
    "audit_cache_running": 0,
    "automatic_monitor_enabled": false,
    "budget_limit_hours": 88,
    "cache_intake_pending": true,
    "checked_at": "2026-10-23T01:44:51.319432+00:00",
    "execution_state": "SCHEDULER_TELEMETRY_FAILED_WORKERS_RETURNED_SUCCESS",
    "failure_reason": "shared GPU owner ps lookup timed out after 2 seconds",
    "formal_audits_completed": 0,
    "formal_audits_expected": 189,
    "launched_epoch": 1792693988.5188887,
    "parent_pid": 1336657,
    "preservation_errors": [],
    "preserved_audit_cache_count": 25,
    "preserved_training_count": 189,
    "recovery_id": "2026-10-23_NRC1repair3_auditcache2_88_r1",
    "remaining_audit_cache_ids": [
      "AUDITCACHE_s1_t7",
      "AUDITCACHE_s2_t3"
    ],
    "remaining_seconds": 8868.423919439316,
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_auditcache2_88/REPAIR_NOTES.md",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "status": "FAILED",
    "worker_return_evidence": "programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_auditcache2_88/WORKER_STATUS_20261023.txt"
  },
  "last_audit_only_recovery": {
    "audit_cache_completed": 25,
    "audit_cache_failed": 2,
    "audit_cache_running": 0,
    "automatic_retry": false,
    "budget_limit_hours": 88,
    "calibration_records": 216,
    "checked_at": "2026-10-22T17:37:06.527325+00:00",
    "completion_followup_automation_id": "nrc1",
    "completion_followup_automation_status": "DELETED_BY_USER_REQUEST",
    "failed_task_ids": [
      "AUDITCACHE_s1_t7",
      "AUDITCACHE_s2_t3"
    ],
    "failure_evidence": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit88/AUDIT_CACHE_FAILURES.json",
    "failure_notification_at": "2026-10-22T15:19:49.803172+00:00",
    "failure_reason": "GPU resource preflight: no two consecutive fresh observations within 60 seconds",
    "fit_dispatch_count": 0,
    "formal_audits_completed": 0,
    "formal_audits_expected": 189,
    "monitor_powershell": "[REDACTED_MACHINE]",
    "other_stages_authorized": false,
    "parent_pid": 357673,
    "preservation_errors": [],
    "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit88/QUALIFICATION_Q4.json",
    "recovery_id": "2026-10-22_NRC1repair3_audit88_r1",
    "remaining_seconds": 35916.12140893936,
    "remote_package": "[REDACTED_MACHINE]",
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit88/REPAIR_NOTES.md",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "snapshot": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit88/STATUS.json",
    "status": "FAILED",
    "supplement_sha256": "5009bf8eda2e09dcfa22829b1f6f37faf4e24228a7a579601027f088b32ba866",
    "training_completed": 189
  },
  "last_audit_resume88_recovery": {
    "actual_audit_worker_count": 1,
    "audit_cache_preserved": 27,
    "audit_worker_failures": [],
    "automatic_monitor_enabled": false,
    "budget_limit_hours": 88,
    "cache_dispatch_count": 0,
    "checked_at": "2026-10-23T02:26:11.468382+00:00",
    "fit_dispatch_count": 0,
    "formal_audits_completed": 9,
    "formal_audits_expected": 189,
    "last_dispatch_budget": {
      "anchor_cache_seconds_each": 22.502154052257538,
      "audit_cache_seconds_each": null,
      "audit_seconds_each": 14.48308526724577,
      "checked_at_epoch": 1792722348.3352711,
      "closeout_reserve_seconds": 3600,
      "closeout_seconds": 3600,
      "contract_sha256": "3666bec81ef4aab5bc6a437fb0fde27f9684f0c64f365b04be42ab29d40542ef",
      "dispatch_timeout_cap_seconds": 2823.159722328186,
      "family_task_upper_bound_seconds": 14.48308526724577,
      "fit_seconds_each": 457.0878318399191,
      "guard_error": null,
      "measured_profile_sha256": "0ea3578d2d1989052c2947c3bf184222ecca0df0cab59f5d9cf7adef2f4217cd",
      "node_remaining_seconds": 44724.322528362274,
      "phase": "audit",
      "predicted_task_seconds": 14.48308526724577,
      "remaining_anchor_cache_count": 0,
      "remaining_audit_cache_count": 0,
      "remaining_audit_count": 181,
      "remaining_fit_count": 0,
      "remaining_seconds": 6423.159722328186,
      "remaining_temperature_fit_count": 0,
      "required_seconds": 6221.438433371484,
      "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
      "status": "PASS",
      "task_id": "LL_s0_t1",
      "transaction_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-tx",
      "transaction_remaining_seconds": 44505.01469349861
    },
    "observed_physical_gpus": [
      1,
      2,
      8,
      9
    ],
    "parent_pid": 2574584,
    "preservation_errors": [],
    "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_auditresume88/QUALIFICATION_REMOTE.json",
    "recovery_id": "2026-10-23_NRC1repair3_auditresume88_r1",
    "remaining_seconds": 6414.077608346939,
    "remote_package": "[REDACTED_MACHINE]",
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_auditresume88/REPAIR_NOTES.md",
    "scheduler_snapshot": {
      "completed": 1,
      "failed": 0,
      "families": {
        "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629": {
          "calibration_source": "unknown_family_serial_start",
          "commitment": 3072,
          "expand_after_measurement": true,
          "failed": false,
          "limit": 189,
          "max_family_jobs": 189,
          "peak": 899
        }
      },
      "journal_count": 9,
      "pending": 180,
      "running": 8,
      "running_tasks": {
        "GG_s0_t0": {
          "attempt_output": "task_attempts/GG_s0_t0/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 2,
          "observed": 0,
          "pids": []
        },
        "GG_s0_t1": {
          "attempt_output": "task_attempts/GG_s0_t1/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 1,
          "observed": 0,
          "pids": []
        },
        "GL_s0_t1": {
          "attempt_output": "task_attempts/GL_s0_t1/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 1,
          "observed": 0,
          "pids": []
        },
        "GW_s0_t0": {
          "attempt_output": "task_attempts/GW_s0_t0/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 9,
          "observed": 0,
          "pids": []
        },
        "G_s0_t0": {
          "attempt_output": "task_attempts/G_s0_t0/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 8,
          "observed": 0,
          "pids": []
        },
        "LL_s0_t0": {
          "attempt_output": "task_attempts/LL_s0_t0/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 2,
          "observed": 0,
          "pids": []
        },
        "LW_s0_t0": {
          "attempt_output": "task_attempts/LW_s0_t0/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 9,
          "observed": 0,
          "pids": []
        },
        "L_s0_t0": {
          "attempt_output": "task_attempts/L_s0_t0/1",
          "family": "dsa-nrc-v0.1-NRC1:audit:a0c95f6604d28c48:99e31cab575ba5db:f3c06e0663085629",
          "gpu": 8,
          "observed": 0,
          "pids": []
        }
      },
      "total": 189,
      "updated_at": "2026-10-23T02:25:00.959764+00:00"
    },
    "status": "RUNNING",
    "successful_worker_returns_verified": 9,
    "training_preserved": 189
  },
  "last_completed_run": {
    "bundle_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1",
    "dispatch_status": "REMOTE_ACCEPTED",
    "estimated_training_hours": 6.5,
    "execution_mode": "user_managed",
    "executor_id": "lab10",
    "planned_units": 2,
    "recorded_at": "2026-11-05T12:11:18.488398+00:00",
    "round_id": "ds07-r1-audit18-r18fix1",
    "run_prefix": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1",
    "transaction_operations": [
      {
        "operation": "upload",
        "recorded_at": "2026-11-05T12:12:57.701803+00:00",
        "result": {
          "action": "UPLOADED",
          "monitor_powershell": "[REDACTED_MACHINE]",
          "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1"
        }
      },
      {
        "operation": "launch",
        "recorded_at": "2026-11-05T12:18:13.335709+00:00",
        "result": {
          "action": "SUBMISSION_SENT_NOT_VERIFIED",
          "monitor_powershell": "[REDACTED_MACHINE]",
          "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1"
        }
      },
      {
        "operation": "probe",
        "recorded_at": "2026-11-05T12:18:47.080909+00:00",
        "result": {
          "action": "RECONCILE_SAME_NODE",
          "node_id": "science",
          "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
          "status": "RUNNING",
          "timing": {
            "contract_sha256": "95372fc340bc257e5b42dd11c80ec909ab53e5f81defd1202693f750d6749caa",
            "execution_seconds": 32.21760702133179,
            "queue_seconds": 0.8470947742462158,
            "queue_time_policy": "exclude_resource_wait",
            "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
            "transaction_id": "dsainet-ds07-r1-audit18-r18fix1",
            "waiting_for_resources": false,
            "wall_seconds": 33.064701795578
          }
        }
      },
      {
        "operation": "probe",
        "recorded_at": "2026-11-05T12:22:30.670116+00:00",
        "result": {
          "action": "FETCH_VERIFY_INTAKE",
          "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
          "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
          "timing": {
            "contract_sha256": "95372fc340bc257e5b42dd11c80ec909ab53e5f81defd1202693f750d6749caa",
            "execution_seconds": 83.5814757347107,
            "queue_seconds": 0.8470947742462158,
            "queue_time_policy": "exclude_resource_wait",
            "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
            "transaction_id": "dsainet-ds07-r1-audit18-r18fix1",
            "waiting_for_resources": false,
            "wall_seconds": 84.42857050895691
          }
        }
      },
      {
        "operation": "fetch",
        "recorded_at": "2026-11-05T12:53:34.876208+00:00",
        "result": {
          "analysis_receipt_sha256": "50d281479aef6a12015c6c0c058c89b245db75e39326ab6107800b1c9c9d72d0",
          "artifact_manifest_sha256": "472328bb9c78bbf8b431cfaa8d1c6dd01fc061b6ff56f24d03c7f873e36bcc9c",
          "contract_sha256": "95372fc340bc257e5b42dd11c80ec909ab53e5f81defd1202693f750d6749caa",
          "full_payload_local": false,
          "intake_scope": "analysis_v1",
          "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
          "transaction_id": "dsainet-ds07-r1-audit18-r18fix1",
          "transfer_bytes": 1101797,
          "verified": true
        }
      }
    ]
  },
  "last_decision": {
    "decision": "NO_SIGNAL",
    "disposition": "STOP_PATCH_PREELU_POLYPHASE",
    "round_id": "dsainet-b0-patch-preelu-polyphase-r1"
  },
  "last_ds07_activation": {
    "authorization_id": "DS07-R1-SCIENCE1-266H-20261102",
    "authorization_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/USER_APPROVAL266.json",
    "authorization_sha256": "3da978a48b669541ea6fb4e831c1e90db762bc3a018a3303fb4887fff0589c69",
    "old_campaign_preserved": true,
    "old_operation_archived_as_failed": true,
    "original_start_preserved": "2026-10-23T13:28:00+00:00",
    "round_id": "ds07-r1-science1",
    "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
    "status": "AUTHORIZED_READY_TO_REGISTER",
    "total_hours": 266,
    "updated_at": "2026-11-02T12:25:46.884997+00:00"
  },
  "last_ds07_devicefix1_launch_check": {
    "audit_completed": 0,
    "budget_gate": "PASS",
    "checked_at_utc": "2026-11-04T06:51:46.391226+00:00",
    "cost_gate": "PASS",
    "failed_macro_tasks": 0,
    "formal_TECH": "PASS",
    "remaining_hours_at_check": 48.77682771965664,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/LAUNCH_STATUS_REPORT.md",
    "run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
    "science_node": "RUNNING",
    "scientific_training_worker_started": true,
    "training_completed": 1,
    "waiting_for_resources": false
  },
  "last_ds07_devicefix1_status_check": {
    "TECH": "PASS",
    "audit_completed": 54,
    "audit_expected": 72,
    "audit_receipt_files_by_arm": {
      "C": 18,
      "N": 18,
      "S": 18
    },
    "checked_at_beijing": "2026-11-05T19:36:34.166726+08:00",
    "failed_at_beijing": "2026-11-05T01:11:29.116256+08:00",
    "failed_task": "ds07-audit-R-c00-s0",
    "failed_task_receipt": false,
    "fit_barrier": "SEALED_72_RECEIPTS",
    "fit_completed": 72,
    "fit_expected": 72,
    "full_process_memory": true,
    "last_budget_gate": "PASS",
    "macro_failed": 1,
    "oom": false,
    "reason": "R pre-audit source-only role counts (3456,576) compared against full (3456,576,576)",
    "remaining_hours": 20.030223414283398,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/STATUS_20261105_REPORT.md",
    "restarted": false,
    "run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
    "running": 0,
    "science_node": "FAILED",
    "scientific_effects_read": false,
    "timed_out": false,
    "total_budget_hours": 312,
    "transaction_active_hours": 10.557772743105888,
    "unattempted_audits": 17
  },
  "last_ds07_operator_stop": {
    "failure_proof": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/FAILURE_PROOF.json",
    "frozen_sources_modified": false,
    "n_profile_gpu_workers": 0,
    "recorded_at": "2026-11-02T12:51:35.166892+00:00",
    "remaining_live_pids": [],
    "run_id": "2026-11-02_dsainet_ds07_r1_science1-full-w1",
    "scientific_audits": 0,
    "scientific_fits": 0,
    "status": "STOPPED_ENGINEERING_BEFORE_GPU_WORK",
    "successor_status": "LOCAL_PREPARATION_PENDING_EXACT_TRANSPORT_BINDING"
  },
  "last_ds07_r18fix1_completion": {
    "Grok_review1": "PENDING_PRESERVED",
    "Grok_review2": "PASS_ENGINEERING_PRELAUNCH",
    "TECH": "PASS",
    "additional_budget_hours": 0,
    "all_old_records_preserved": true,
    "artifact_manifest_sha256": "472328bb9c78bbf8b431cfaa8d1c6dd01fc061b6ff56f24d03c7f873e36bcc9c",
    "budget_gate": "PASS",
    "checked_at_beijing": "2026-11-05T20:23:49.299254+08:00",
    "checkpoint_payload_fetched": false,
    "combined_audit_count": 72,
    "combined_fit_count": 72,
    "contract_sha256": "95372fc340bc257e5b42dd11c80ec909ab53e5f81defd1202693f750d6749caa",
    "cost_gate": "PASS",
    "failure_count": 0,
    "finished_at_beijing": "2026-11-05T20:19:35.899546+08:00",
    "full_payload_fetched": false,
    "local_tests": 29,
    "mixed_provenance": true,
    "new_R_audit_count": 18,
    "new_R_diagnostic_count": 18,
    "new_manual_pause_seconds": 0,
    "new_training_count": 0,
    "next_step": "separate allowed analysis export, verify, intake and frozen analysis; no new experiment",
    "old_Run_stage_limits_unchanged": true,
    "optimizer_updates": 0,
    "original_start": "2026-10-23T13:28:00+00:00",
    "parent_run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
    "parent_unchanged_verification": "PASS",
    "remaining_budget_hours": 19.242921904903028,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/r18fix1/COMPLETION_REPORT.md",
    "resource_wait_seconds": 0.8470947742462158,
    "resume_receipt_sha256": "b8cdd76a51feb928d81bae6538c9eb0b9b70957d173e4bdce253210586369943",
    "reused_audit_count": 54,
    "reused_fit_count": 72,
    "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
    "runtime_execution_seconds": 83.5814757347107,
    "scientific_effects_read": false,
    "scientific_result_analyzed": false,
    "shared_interface_tests": 62,
    "shared_launch_skips": 1,
    "shared_launch_tests": 148,
    "single_run_claim_permitted": false,
    "source_files": 140,
    "source_manifest_sha256": "33f8e3663aa22df6941f6bfec0790798f0d877e20a0ac1eb0bbe3fc0bbf8a3c8",
    "status": "REMOTE_COMPLETE_AND_ARTIFACTS_VERIFIED_AWAITING_ANALYSIS_INTAKE",
    "successor_limits_hours": {
      "TECH": 0.25,
      "Transaction": 6.5,
      "closeout": 4,
      "science": 2.25
    },
    "total_budget_hours": 312,
    "verified_local_intake": false
  },
  "last_ds07_r1_merged_analysis": {
    "PE_ablation_stage_eligible": false,
    "R_diagnostics": 18,
    "artifacts": {
      "ANALYSIS_PLAN.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/ANALYSIS_PLAN.json",
        "sha256": "e2f2099a964e817e8bd615012d99220a1e277984d5f73255b91847321f30369f"
      },
      "GROK_CHAT_HISTORY.jsonl": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/GROK_CHAT_HISTORY.jsonl",
        "sha256": "65f88e555bd036165436fd581bc7d7996993eff2ab574ce75869b1e2475334de"
      },
      "GROK_REVIEW_REPORT.md": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/GROK_REVIEW_REPORT.md",
        "sha256": "ff646cb387cc6be8c4ccd6160c35a655845a5f73d72d06369dbd1cf50c8a9d68"
      },
      "INDEPENDENT_RECOMPUTE.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/INDEPENDENT_RECOMPUTE.json",
        "sha256": "b1ecdd6d4c191f0043866602175ad01e016e77157da7ff321dd8f93dfaa88a80"
      },
      "LOCAL_REPLAY_VERIFICATION.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/LOCAL_REPLAY_VERIFICATION.json",
        "sha256": "7b84a0dade6762ca098b23db3aadcf3a1f1b9b756bc07ce0541b016f134e8787"
      },
      "REPORT_ZH.md": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/REPORT_ZH.md",
        "sha256": "b763bd9f863c7762f212a51777817de40311abdeea2faca88fe956c55747f454"
      },
      "REVIEW_DISPOSITION.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/REVIEW_DISPOSITION.json",
        "sha256": "233923025a361912aa2f08c09d5ae1f4e58396969a6f8c010a9b7d1ddc958202"
      },
      "VERIFIED_MIXED_INTAKE.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/VERIFIED_MIXED_INTAKE.json",
        "sha256": "5d294612f5ed0fac2859fed1099e3366d953aa4e6213119592f61ecd748ff088"
      },
      "intake/critical_artifacts/INPUT_MANIFEST.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/intake/critical_artifacts/INPUT_MANIFEST.json",
        "sha256": "4406cb6b141233b8e226d93c4706e4f1066306b933c388c81556fcaaf8c3ff58"
      },
      "intake/critical_artifacts/PACKAGE_MANIFEST.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/intake/critical_artifacts/PACKAGE_MANIFEST.json",
        "sha256": "9407b496eac2d5cffadf4b5cfc7d7922532823f15e33f2d591d53f902728d64e"
      },
      "intake/critical_artifacts/RESULTS.json": {
        "ref": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/intake/critical_artifacts/RESULTS.json",
        "sha256": "c36ef931dd3a1bd26919438149fc7deafae5e5a12d35024eb41d40daf1de7372"
      }
    },
    "budget": {
      "charged_hours": 293.512495809812,
      "checked_at_beijing": "2026-11-05T21:09:08.803027+08:00",
      "clock_reset": false,
      "closeout_ceiling_hours": 4,
      "closeout_spent_hours": 0.8258065226342943,
      "new_budget_hours": 0,
      "new_pause_seconds": 0,
      "original_start": "2026-10-23T13:28:00+00:00",
      "pipeline_closed_does_not_pause_budget_clock": true,
      "previous_authorized_manual_pause_seconds": 3094.9218889999997,
      "remaining_hours": 18.48750419018802,
      "total_hours": 312,
      "verified_resource_wait_seconds_once": 62328.89622282982
    },
    "checkpoints_local": false,
    "claim_created": false,
    "critical_file_count": 312,
    "critical_selected_bytes": 7508066,
    "decision": "STOP_FIXED_DS07_R1_NO_AUTOMATIC_EXPANSION",
    "decision_record": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/DECISION.json",
    "decision_record_sha256": "4d60175d977f6d59762bda4149a34ff68ba69d0dcd9da720894b974e6132a689",
    "evidence_id": "DSAINET-DS07-R1-MERGED-VERIFIED-ANALYSIS-20261105",
    "four_arm_means": {
      "C": {
        "mean_acc": 0.5134066358024691,
        "mean_nll": 1.3219667820019116,
        "per_seed_mean_acc": {
          "0": 0.5081018518518519,
          "1": 0.5187114197530864
        },
        "per_seed_mean_nll": {
          "0": 1.3867760152339288,
          "1": 1.2571575487698945
        },
        "per_subject": {
          "0": {
            "mean_acc": 0.5920138888888888,
            "mean_nll": 1.0830771009433517,
            "seeds": {
              "0": {
                "acc": 0.5260416666666666,
                "nll": 1.1840173711598223
              },
              "1": {
                "acc": 0.6579861111111112,
                "nll": 0.9821368307268811
              }
            }
          },
          "1": {
            "mean_acc": 0.4626736111111111,
            "mean_nll": 1.7070747618071698,
            "seeds": {
              "0": {
                "acc": 0.4479166666666667,
                "nll": 1.8734160611361537
              },
              "1": {
                "acc": 0.4774305555555556,
                "nll": 1.5407334624781859
              }
            }
          },
          "2": {
            "mean_acc": 0.5555555555555556,
            "mean_nll": 1.05010037461907,
            "seeds": {
              "0": {
                "acc": 0.5173611111111112,
                "nll": 1.1066704768025502
              },
              "1": {
                "acc": 0.59375,
                "nll": 0.9935302724355901
              }
            }
          },
          "3": {
            "mean_acc": 0.5460069444444444,
            "mean_nll": 1.6620615589108594,
            "seeds": {
              "0": {
                "acc": 0.5538194444444444,
                "nll": 1.6262229199482514
              },
              "1": {
                "acc": 0.5381944444444444,
                "nll": 1.6979001978734671
              }
            }
          },
          "4": {
            "mean_acc": 0.4774305555555556,
            "mean_nll": 1.5373613509106996,
            "seeds": {
              "0": {
                "acc": 0.5,
                "nll": 1.425924922672397
              },
              "1": {
                "acc": 0.4548611111111111,
                "nll": 1.6487977791490023
              }
            }
          },
          "5": {
            "mean_acc": 0.3550347222222222,
            "mean_nll": 1.633762962090324,
            "seeds": {
              "0": {
                "acc": 0.4253472222222222,
                "nll": 1.8784939025761105
              },
              "1": {
                "acc": 0.2847222222222222,
                "nll": 1.3890320216045375
              }
            }
          },
          "6": {
            "mean_acc": 0.28125,
            "mean_nll": 1.4609505464538035,
            "seeds": {
              "0": {
                "acc": 0.3020833333333333,
                "nll": 1.5180127814104876
              },
              "1": {
                "acc": 0.2604166666666667,
                "nll": 1.4038883114971195
              }
            }
          },
          "7": {
            "mean_acc": 0.7482638888888888,
            "mean_nll": 0.6983701949425452,
            "seeds": {
              "0": {
                "acc": 0.7083333333333334,
                "nll": 0.7819517207966198
              },
              "1": {
                "acc": 0.7881944444444444,
                "nll": 0.6147886690884704
              }
            }
          },
          "8": {
            "mean_acc": 0.6024305555555556,
            "mean_nll": 1.064942187339382,
            "seeds": {
              "0": {
                "acc": 0.5920138888888888,
                "nll": 1.0862739806029664
              },
              "1": {
                "acc": 0.6128472222222222,
                "nll": 1.0436103940757977
              }
            }
          }
        }
      },
      "N": {
        "mean_acc": 0.5000964506172839,
        "mean_nll": 1.413528101930077,
        "per_seed_mean_acc": {
          "0": 0.49151234567901236,
          "1": 0.5086805555555556
        },
        "per_seed_mean_nll": {
          "0": 1.424855814207753,
          "1": 1.4022003896524007
        },
        "per_subject": {
          "0": {
            "mean_acc": 0.6848958333333334,
            "mean_nll": 0.8221562461061508,
            "seeds": {
              "0": {
                "acc": 0.6770833333333334,
                "nll": 0.8193905618983202
              },
              "1": {
                "acc": 0.6927083333333334,
                "nll": 0.8249219303139814
              }
            }
          },
          "1": {
            "mean_acc": 0.3958333333333333,
            "mean_nll": 1.7452963732919073,
            "seeds": {
              "0": {
                "acc": 0.3697916666666667,
                "nll": 1.8559216607077162
              },
              "1": {
                "acc": 0.421875,
                "nll": 1.6346710858760984
              }
            }
          },
          "2": {
            "mean_acc": 0.4045138888888889,
            "mean_nll": 1.2967626848684013,
            "seeds": {
              "0": {
                "acc": 0.4045138888888889,
                "nll": 1.2584435344282083
              },
              "1": {
                "acc": 0.4045138888888889,
                "nll": 1.3350818353085945
              }
            }
          },
          "3": {
            "mean_acc": 0.4878472222222222,
            "mean_nll": 1.6158785444165153,
            "seeds": {
              "0": {
                "acc": 0.4583333333333333,
                "nll": 1.5460633977855405
              },
              "1": {
                "acc": 0.5173611111111112,
                "nll": 1.6856936910474902
              }
            }
          },
          "4": {
            "mean_acc": 0.5008680555555556,
            "mean_nll": 1.3809384867123748,
            "seeds": {
              "0": {
                "acc": 0.4878472222222222,
                "nll": 1.3850587598625692
              },
              "1": {
                "acc": 0.5138888888888888,
                "nll": 1.3768182135621805
              }
            }
          },
          "5": {
            "mean_acc": 0.40625,
            "mean_nll": 2.4270566562576072,
            "seeds": {
              "0": {
                "acc": 0.4253472222222222,
                "nll": 2.4903647095647243
              },
              "1": {
                "acc": 0.3871527777777778,
                "nll": 2.36374860295049
              }
            }
          },
          "6": {
            "mean_acc": 0.3463541666666667,
            "mean_nll": 1.4622903316273521,
            "seeds": {
              "0": {
                "acc": 0.3576388888888889,
                "nll": 1.4677261830366328
              },
              "1": {
                "acc": 0.3350694444444444,
                "nll": 1.4568544802180716
              }
            }
          },
          "7": {
            "mean_acc": 0.6909722222222222,
            "mean_nll": 0.8639787287817371,
            "seeds": {
              "0": {
                "acc": 0.671875,
                "nll": 0.9348600529489737
              },
              "1": {
                "acc": 0.7100694444444444,
                "nll": 0.7930974046145005
              }
            }
          },
          "8": {
            "mean_acc": 0.5833333333333334,
            "mean_nll": 1.1073948653086447,
            "seeds": {
              "0": {
                "acc": 0.5711805555555556,
                "nll": 1.0658734676370913
              },
              "1": {
                "acc": 0.5954861111111112,
                "nll": 1.148916262980198
              }
            }
          }
        }
      },
      "R": {
        "mean_acc": 0.49594907407407407,
        "mean_nll": 1.4088727677632145,
        "per_seed_mean_acc": {
          "0": 0.5100308641975309,
          "1": 0.4818672839506173
        },
        "per_seed_mean_nll": {
          "0": 1.337944748723781,
          "1": 1.4798007868026481
        },
        "per_subject": {
          "0": {
            "mean_acc": 0.6449652777777778,
            "mean_nll": 0.9061402941009085,
            "seeds": {
              "0": {
                "acc": 0.6475694444444444,
                "nll": 0.909225894411542
              },
              "1": {
                "acc": 0.6423611111111112,
                "nll": 0.9030546937902749
              }
            }
          },
          "1": {
            "mean_acc": 0.4019097222222222,
            "mean_nll": 1.506260242582158,
            "seeds": {
              "0": {
                "acc": 0.4479166666666667,
                "nll": 1.457591524725442
              },
              "1": {
                "acc": 0.3559027777777778,
                "nll": 1.5549289604388743
              }
            }
          },
          "2": {
            "mean_acc": 0.3836805555555556,
            "mean_nll": 1.2818725650134746,
            "seeds": {
              "0": {
                "acc": 0.4149305555555556,
                "nll": 1.2256352092956493
              },
              "1": {
                "acc": 0.3524305555555556,
                "nll": 1.3381099207312996
              }
            }
          },
          "3": {
            "mean_acc": 0.4965277777777778,
            "mean_nll": 1.4503506333837932,
            "seeds": {
              "0": {
                "acc": 0.4895833333333333,
                "nll": 1.3694442501454909
              },
              "1": {
                "acc": 0.5034722222222222,
                "nll": 1.5312570166220956
              }
            }
          },
          "4": {
            "mean_acc": 0.5243055555555556,
            "mean_nll": 1.2934965674653904,
            "seeds": {
              "0": {
                "acc": 0.53125,
                "nll": 1.1928161424910104
              },
              "1": {
                "acc": 0.5173611111111112,
                "nll": 1.3941769924397702
              }
            }
          },
          "5": {
            "mean_acc": 0.4010416666666667,
            "mean_nll": 2.8897427802166225,
            "seeds": {
              "0": {
                "acc": 0.3993055555555556,
                "nll": 2.5081903565376766
              },
              "1": {
                "acc": 0.4027777777777778,
                "nll": 3.2712952038955683
              }
            }
          },
          "6": {
            "mean_acc": 0.2829861111111111,
            "mean_nll": 1.3957447549064816,
            "seeds": {
              "0": {
                "acc": 0.3125,
                "nll": 1.4058591446233284
              },
              "1": {
                "acc": 0.2534722222222222,
                "nll": 1.385630365189635
              }
            }
          },
          "7": {
            "mean_acc": 0.7421875,
            "mean_nll": 0.9316422655538984,
            "seeds": {
              "0": {
                "acc": 0.7482638888888888,
                "nll": 0.9394724816445427
              },
              "1": {
                "acc": 0.7361111111111112,
                "nll": 0.9238120494632541
              }
            }
          },
          "8": {
            "mean_acc": 0.5859375,
            "mean_nll": 1.0246048066462041,
            "seeds": {
              "0": {
                "acc": 0.5989583333333334,
                "nll": 1.033267734639346
              },
              "1": {
                "acc": 0.5729166666666666,
                "nll": 1.015941878653062
              }
            }
          }
        }
      },
      "S": {
        "mean_acc": 0.5072337962962963,
        "mean_nll": 1.395202976580038,
        "per_seed_mean_acc": {
          "0": 0.5244984567901234,
          "1": 0.48996913580246915
        },
        "per_seed_mean_nll": {
          "0": 1.33272936154267,
          "1": 1.457676591617406
        },
        "per_subject": {
          "0": {
            "mean_acc": 0.6614583333333334,
            "mean_nll": 0.8891194613704286,
            "seeds": {
              "0": {
                "acc": 0.671875,
                "nll": 0.882997116217854
              },
              "1": {
                "acc": 0.6510416666666666,
                "nll": 0.8952418065230032
              }
            }
          },
          "1": {
            "mean_acc": 0.4461805555555556,
            "mean_nll": 1.584047743766611,
            "seeds": {
              "0": {
                "acc": 0.4565972222222222,
                "nll": 1.465376011550851
              },
              "1": {
                "acc": 0.4357638888888889,
                "nll": 1.7027194759823712
              }
            }
          },
          "2": {
            "mean_acc": 0.3671875,
            "mean_nll": 1.307867978669099,
            "seeds": {
              "0": {
                "acc": 0.3715277777777778,
                "nll": 1.3119878813331634
              },
              "1": {
                "acc": 0.3628472222222222,
                "nll": 1.3037480760050346
              }
            }
          },
          "3": {
            "mean_acc": 0.5234375,
            "mean_nll": 1.647757662637051,
            "seeds": {
              "0": {
                "acc": 0.5538194444444444,
                "nll": 1.496652672277226
              },
              "1": {
                "acc": 0.4930555555555556,
                "nll": 1.7988626529968756
              }
            }
          },
          "4": {
            "mean_acc": 0.5095486111111112,
            "mean_nll": 1.3984777145388598,
            "seeds": {
              "0": {
                "acc": 0.5138888888888888,
                "nll": 1.4703990431401879
              },
              "1": {
                "acc": 0.5052083333333334,
                "nll": 1.3265563859375318
              }
            }
          },
          "5": {
            "mean_acc": 0.4053819444444444,
            "mean_nll": 2.457077957516815,
            "seeds": {
              "0": {
                "acc": 0.4149305555555556,
                "nll": 2.2511150825875417
              },
              "1": {
                "acc": 0.3958333333333333,
                "nll": 2.663040832446088
              }
            }
          },
          "6": {
            "mean_acc": 0.3107638888888889,
            "mean_nll": 1.4990782130500147,
            "seeds": {
              "0": {
                "acc": 0.34375,
                "nll": 1.457869602568086
              },
              "1": {
                "acc": 0.2777777777777778,
                "nll": 1.5402868235319433
              }
            }
          },
          "7": {
            "mean_acc": 0.7378472222222222,
            "mean_nll": 0.7136707319615979,
            "seeds": {
              "0": {
                "acc": 0.765625,
                "nll": 0.6221730814910907
              },
              "1": {
                "acc": 0.7100694444444444,
                "nll": 0.8051683824321051
              }
            }
          },
          "8": {
            "mean_acc": 0.6032986111111112,
            "mean_nll": 1.0597293257098641,
            "seeds": {
              "0": {
                "acc": 0.6284722222222222,
                "nll": 1.0359937627180293
              },
              "1": {
                "acc": 0.578125,
                "nll": 1.0834648887016989
              }
            }
          }
        }
      }
    },
    "full_payload_local": false,
    "merged_audits": 72,
    "mixed_provenance": true,
    "negative_boundary": "fixed exposed DS07-R1 only; no universal relationship/graph/PE claim",
    "new_R_audits": 18,
    "new_closeout_inference": 0,
    "new_closeout_training": 0,
    "new_experiment_authorized": false,
    "next_action": "STOP_FIXED_DS07_R1_NO_NEW_EXPERIMENT",
    "parent_contract_sha256": "b9824b039bc8dcaaaa907ac8a1c7cdfd0d03b90cbb7a73cc82438edce1c748ef",
    "parent_engineering_failed_preserved": true,
    "parent_run_id": "2026-11-04_dsainet_ds07_r1_science1-devicefix1-full-w1",
    "parent_standard_intake": false,
    "program_id": "dsainet",
    "recorded_at": "2026-11-05T13:09:08.803027+00:00",
    "report": "ai4s/programs/dsainet/research/ds07-r1/analysis_20261105/REPORT_ZH.md",
    "research_id": "ds07-r1",
    "resume_contract_sha256": "95372fc340bc257e5b42dd11c80ec909ab53e5f81defd1202693f750d6749caa",
    "resume_run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
    "reused_NCS_audits": 54,
    "reused_fits": 72,
    "role": "exposed_development_four_arm_system_net_utility_screen",
    "round_id": "ds07-r1-audit18-r18fix1",
    "sameP_readout_stage_eligible": false,
    "single_run_claim_permitted": false,
    "standard_R18_intake": {
      "analysis_receipt_sha256": "50d281479aef6a12015c6c0c058c89b245db75e39326ab6107800b1c9c9d72d0",
      "artifact_manifest_sha256": "472328bb9c78bbf8b431cfaa8d1c6dd01fc061b6ff56f24d03c7f873e36bcc9c",
      "contract_sha256": "95372fc340bc257e5b42dd11c80ec909ab53e5f81defd1202693f750d6749caa",
      "full_payload_local": false,
      "intake_path": "results/logs/remote/2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
      "intake_scope": "analysis_v1",
      "run_id": "2026-11-05_dsainet_ds07_r1_audit18-r18fix1-full-w1",
      "run_status": "complete",
      "transaction_id": "dsainet-ds07-r1-audit18-r18fix1",
      "transfer_bytes": 1101797,
      "verified": true,
      "verified_at": null
    }
  },
  "last_ds07_readerfix1_launch_check": {
    "N_qualification": "PENDING_RESOURCE_ADMISSION",
    "TECH_overall": "PENDING_REAL_N",
    "approved_total_hours": 266,
    "audit": "NOT_STARTED",
    "checked_at_utc": "2026-11-02T13:52:43.581532+00:00",
    "contract_sha256": "d82104284d7dadd6a47831998c32727a97bca76aff0236c224fd56bfad02f243",
    "original_start": "2026-10-23T13:28:00+00:00",
    "remaining_hours_at_check_conservative": 40.935179102509665,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/LAUNCH_STATUS_REPORT.md",
    "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
    "scientific_training": "NOT_STARTED",
    "status": "RUNNING_WAIT_FOR_RESOURCES"
  },
  "last_ds07_readerfix1_status_check": {
    "N_profile_epochs_completed": 5,
    "N_qualification_batches_completed": 8,
    "checked_at_utc": "2026-11-02T15:52:02.816513+00:00",
    "formal_TECH": "FAILED",
    "formal_cost_gate": "NOT_REACHED",
    "remaining_hours": 40.494708730154116,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/status_20261102_2346/STATUS_REPORT.md",
    "run_id": "2026-11-02_dsainet_ds07_r1_science1-readerfix1-full-w1",
    "scientific_audits_completed": 0,
    "scientific_training_completed": 0,
    "status": "FAILED_TECH_INNER_TELEMETRY_UNKNOWN"
  },
  "last_ds07_science_preparation": {
    "approved_total_hours": 212,
    "proposed_total_hours": 266,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/READINESS_REPORT.md",
    "request": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/BUDGET_REQUEST_20261102.json",
    "science_dispatched": false,
    "status": "READY_PENDING_NUMERIC_BUDGET_AND_REAL_N_TECH",
    "updated_at": "2026-11-02T11:42:31.033614+00:00"
  },
  "last_ds07_summaryfix1_launch_check": {
    "approved_total_hours": 296,
    "audit_completed": 0,
    "checked_at_utc": "2026-11-03T14:22:32.413716+00:00",
    "contract_sha256": "e72dd5f020f21d4b52fb749265c08a3759befee5507f392ccf5b7355e019b59e",
    "cost_gate": "PASS",
    "formal_TECH": "PASS",
    "original_start": "2026-10-23T13:28:00+00:00",
    "remaining_hours_conservative_at_check": 48.71355884924205,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/LAUNCH_STATUS_REPORT.md",
    "run_id": "2026-11-03_dsainet_ds07_r1_science1-summaryfix1-full-w1",
    "science_pre_dispatch_budget_gate": "PASS",
    "scientific_fit_completed": 0,
    "status": "SCIENCE_SUBMITTED_WAITING_FOR_GPU"
  },
  "last_ds07_telemetryfix1_launch_check": {
    "approved_total_hours": 276,
    "checked_at_utc": "2026-11-02T16:55:01.553314+00:00",
    "contract_sha256": "ee394e5bc6ddf2b0bf5603fd8dc10419e5b88e2e36f9c032db8df5e8d77afb68",
    "remaining_hours_conservative_at_check": 49.50053507842921,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/LAUNCH_STATUS_REPORT.md",
    "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
    "status": "RUNNING_WAIT_FOR_RESOURCES"
  },
  "last_ds07_telemetryfix1_status_check": {
    "N_epochs": 5,
    "N_qualification": "PASS",
    "approved_total_hours": 276.0,
    "audit_completed": 0,
    "checked_at_utc": "2026-11-03T13:14:13.789445+00:00",
    "cost_gate": "PASS",
    "formal_TECH_node": "FAILED_SUMMARY_NOT_ACCEPTED",
    "original_start": "2026-10-23T13:28:00+00:00",
    "remaining_hours": 29.61988012524904,
    "report": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/status_20261103_2110/STATUS_REPORT.md",
    "run_id": "2026-11-03_d
```
