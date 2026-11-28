# State 阅读分段 2

完整脱敏文件：`ai4s/programs/mvcnet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`feb7cd87e1a257f71a3858e0f98467a7da5f287f9d54ab9f4b174fb0f1e9d7f0`。UTF-8 字节范围：[500000, 1000000) / 1075674。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
sed": false,
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-dual-atom-screen-lab10-r4_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-dual-atom-screen-lab10-r4",
      "round_id": "mvcnet-dual-atom-screen-lab10-r4",
      "run": {
        "bundle_id": "2026-09-24_mvcnet_mv03_lab10_bundle_r4",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 1,
        "estimated_training_hours": 0.062,
        "execution_mode": "agent_managed",
        "executor_id": "lab10",
        "planned_units": 149,
        "recorded_at": "2026-09-24T01:40:59.804767+00:00",
        "retry_of": "2026-09-23_mvcnet_mv03_lab10_r3-full-w1",
        "round_id": "mvcnet-dual-atom-screen-lab10-r4",
        "run_prefix": "2026-09-24_mvcnet_mv03_lab10_r4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T01:41:19.642897+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T01:41:20.743055+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T01:41:33.191371+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "00283c8161394537060b277a1abdc92d37884528fd80ec4bcb3d3617b3debe81",
                "execution_seconds": 8.894522905349731,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
                "transaction_id": "mvcnet-dual-atom-tx-20260924-r4",
                "waiting_for_resources": false,
                "wall_seconds": 8.894522905349731
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T01:43:07.296272+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "00283c8161394537060b277a1abdc92d37884528fd80ec4bcb3d3617b3debe81",
                "execution_seconds": 45.561349868774414,
                "queue_seconds": 9.631254196166992,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
                "transaction_id": "mvcnet-dual-atom-tx-20260924-r4",
                "waiting_for_resources": false,
                "wall_seconds": 55.192604064941406
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-24T01:44:07.662370+00:00",
            "result": {
              "artifact_manifest_sha256": "417737db7572bb6279f224ef1cfe9aa442342c587b4c62536392d1034930fe8f",
              "contract_sha256": "00283c8161394537060b277a1abdc92d37884528fd80ec4bcb3d3617b3debe81",
              "run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
              "transaction_id": "mvcnet-dual-atom-tx-20260924-r4",
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-risk-screen-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-risk-screen-lab10-r1",
      "round_id": "mvcnet-source-risk-screen-lab10-r1",
      "run": {
        "bundle_id": "2026-09-24_mvcnet_source_risk_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-24T14:16:53.633586+00:00",
        "round_id": "mvcnet-source-risk-screen-lab10-r1",
        "run_prefix": "2026-09-24_mvcnet_source_risk_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-24T14:18:41.367778+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-24T14:18:44.150550+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-24T14:19:14.077709+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "228d6d2c448996df946c88d03b0be401a71ebe8a46e630a1ca8e5e145d9373a6",
                "execution_seconds": 7.046514272689819,
                "queue_seconds": 20.16990876197815,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1",
                "transaction_id": "mvcnet-source-risk-tx-20260924-r1",
                "waiting_for_resources": true,
                "wall_seconds": 27.21642303466797
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T02:21:22.277306+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "228d6d2c448996df946c88d03b0be401a71ebe8a46e630a1ca8e5e145d9373a6",
                "execution_seconds": 24378.74681687355,
                "queue_seconds": 3072.5465037822723,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-24_mvcnet_source_risk_lab10_r1-full-w1",
                "transaction_id": "mvcnet-source-risk-tx-20260924-r1",
                "waiting_for_resources": false,
                "wall_seconds": 27451.293320655823
              }
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-channel-bilinear-screen-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-channel-bilinear-screen-lab10-r1",
      "round_id": "mvcnet-channel-bilinear-screen-lab10-r1",
      "run": {
        "bundle_id": "2026-09-25_mvcnet_channel_bilinear_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-25T03:10:49.166729+00:00",
        "round_id": "mvcnet-channel-bilinear-screen-lab10-r1",
        "run_prefix": "2026-09-25_mvcnet_channel_bilinear_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T03:11:45.313797+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T03:11:47.400630+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T03:12:11.353773+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "6b20b45d9b9e58df44a0b42261a6c13a54e31a357d8c68da4b60b273cba60d56",
                "execution_seconds": 7.657834053039551,
                "queue_seconds": 12.738386154174805,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
                "transaction_id": "mvcnet-channel-bilinear-tx-20260925-r1",
                "waiting_for_resources": true,
                "wall_seconds": 20.396220207214355
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T09:12:11.371675+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "6b20b45d9b9e58df44a0b42261a6c13a54e31a357d8c68da4b60b273cba60d56",
                "execution_seconds": 17180.323969602585,
                "queue_seconds": 3147.5613884925842,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
                "transaction_id": "mvcnet-channel-bilinear-tx-20260925-r1",
                "waiting_for_resources": false,
                "wall_seconds": 20327.88535809517
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-25T09:18:35.007174+00:00",
            "result": {
              "artifact_manifest_sha256": "11f32ef434896e08eb6802eac58e18751f66fa35cfa51a703ab23733c01e60e5",
              "contract_sha256": "6b20b45d9b9e58df44a0b42261a6c13a54e31a357d8c68da4b60b273cba60d56",
              "run_id": "2026-09-25_mvcnet_channel_bilinear_lab10_r1-full-w1",
              "transaction_id": "mvcnet-channel-bilinear-tx-20260925-r1",
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-ordered-pool-screen-lab10-r2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-ordered-pool-screen-lab10-r2",
      "round_id": "mvcnet-ordered-pool-screen-lab10-r2",
      "run": {
        "bundle_id": "2026-09-25_mvcnet_ordered_pool_lab10_bundle_r2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 56,
        "estimated_training_hours": 3.5,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-25T15:11:53.754479+00:00",
        "retry_of": "2026-09-25_mvcnet_ordered_pool_lab10_r1-full-w1",
        "round_id": "mvcnet-ordered-pool-screen-lab10-r2",
        "run_prefix": "2026-09-25_mvcnet_ordered_pool_lab10_r2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-25T15:12:41.104754+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-25T15:13:56.679824+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T15:14:26.524469+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
                "execution_seconds": 22.07349133491516,
                "queue_seconds": 3.5101680755615234,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
                "waiting_for_resources": true,
                "wall_seconds": 25.583659410476685
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T15:54:31.896332+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
                "execution_seconds": 1905.6281459331512,
                "queue_seconds": 521.7387149333954,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
                "waiting_for_resources": false,
                "wall_seconds": 2427.3668608665466
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T16:41:06.511570+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
                "execution_seconds": 4675.343775033951,
                "queue_seconds": 546.4507944583893,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
                "waiting_for_resources": false,
                "wall_seconds": 5221.79456949234
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-25T17:28:33.479398+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
                "execution_seconds": 7522.671271085739,
                "queue_seconds": 546.4507944583893,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
                "waiting_for_resources": false,
                "wall_seconds": 8069.122065544128
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T03:18:27.060356+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
                "execution_seconds": 9862.262130737305,
                "queue_seconds": 763.5263221263885,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
                "waiting_for_resources": false,
                "wall_seconds": 10625.788452863693
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-26T03:19:51.291757+00:00",
            "result": {
              "artifact_manifest_sha256": "863cb239feaa8cfab694035de70b54ef7043b19210e63bb4a0be7186d42e4694",
              "contract_sha256": "00fbfc7bca868afd7b304f0d45b6a80a0e85a36f86e0bfc0dfdb86921d79f763",
              "run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
              "transaction_id": "mvcnet-ordered-pool-tx-20260925-r2",
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-temporal-tied-head-screen-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-temporal-tied-head-screen-lab10-r1",
      "round_id": "mvcnet-temporal-tied-head-screen-lab10-r1",
      "run": {
        "bundle_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-26T09:09:22.252902+00:00",
        "round_id": "mvcnet-temporal-tied-head-screen-lab10-r1",
        "run_prefix": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-26T12:19:58.523884+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-26T12:20:03.866900+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-26T12:22:21.145732+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "430920fb1d3bef31e1ee6eae99770140e2ddcdf666045304f95c55c70ca66049",
                "execution_seconds": 7.168579339981079,
                "queue_seconds": 127.25073575973511,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1",
                "transaction_id": "mvcnet-temporal-tied-head-tx-20260926-r1",
                "waiting_for_resources": true,
                "wall_seconds": 134.4193150997162
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T02:27:58.775566+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "430920fb1d3bef31e1ee6eae99770140e2ddcdf666045304f95c55c70ca66049",
                "execution_seconds": 14000.336123228073,
                "queue_seconds": 20281.91461777687,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-26_mvcnet_temporal_tied_head_lab10_r1-full-w1",
                "transaction_id": "mvcnet-temporal-tied-head-tx-20260926-r1",
                "waiting_for_resources": false,
                "wall_seconds": 34282.250741004944
              }
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-spatial-locality-screen-lab10-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-spatial-locality-screen-lab10-r1",
      "round_id": "mvcnet-spatial-locality-screen-lab10-r1",
      "run": {
        "bundle_id": "2026-09-27_mvcnet_spatial_locality_lab10_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-27T03:06:19.389366+00:00",
        "round_id": "mvcnet-spatial-locality-screen-lab10-r1",
        "run_prefix": "2026-09-27_mvcnet_spatial_locality_lab10_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T03:07:02.677788+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T03:07:04.688432+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T03:07:33.506627+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "57b87dd86d7e08e520824988b48ea42af383c5e65594fc52d08c92e568c79f5d",
                "execution_seconds": 7.288430213928223,
                "queue_seconds": 18.098403692245483,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1",
                "transaction_id": "mvcnet-spatial-locality-tx-20260927-r1",
                "waiting_for_resources": true,
                "wall_seconds": 25.386833906173706
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T07:55:47.502946+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "57b87dd86d7e08e520824988b48ea42af383c5e65594fc52d08c92e568c79f5d",
                "execution_seconds": 10022.822256565094,
                "queue_seconds": 186.22122168540955,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_spatial_locality_lab10_r1-full-w1",
                "transaction_id": "mvcnet-spatial-locality-tx-20260927-r1",
                "waiting_for_resources": false,
                "wall_seconds": 10209.043478250504
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-cosine-readout-screen-lab10-r2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-cosine-readout-screen-lab10-r2",
      "round_id": "mvcnet-cosine-readout-screen-lab10-r2",
      "run": {
        "bundle_id": "2026-09-27_mvcnet_cosine_readout_lab10_bundle_r2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 112,
        "recorded_at": "2026-09-27T08:57:03.778664+00:00",
        "round_id": "mvcnet-cosine-readout-screen-lab10-r2",
        "run_prefix": "2026-09-27_mvcnet_cosine_readout_lab10_r2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-27T08:57:54.917221+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-27T08:57:57.083635+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T08:58:21.772828+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "21d14cbd7b5fd6b9b3154d8613de3125116372b534035652042a51f3df7f403f",
                "execution_seconds": 19.049607753753662,
                "queue_seconds": 3.2671587467193604,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
                "transaction_id": "mvcnet-cosine-readout-tx-20260927-r2",
                "waiting_for_resources": false,
                "wall_seconds": 22.316766500473022
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T08:59:28.842217+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "21d14cbd7b5fd6b9b3154d8613de3125116372b534035652042a51f3df7f403f",
                "execution_seconds": 53.8481879234314,
                "queue_seconds": 35.57124400138855,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
                "transaction_id": "mvcnet-cosine-readout-tx-20260927-r2",
                "waiting_for_resources": false,
                "wall_seconds": 89.41943192481995
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T09:00:26.255192+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "21d14cbd7b5fd6b9b3154d8613de3125116372b534035652042a51f3df7f403f",
                "execution_seconds": 107.58514380455017,
                "queue_seconds": 39.21762561798096,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
                "transaction_id": "mvcnet-cosine-readout-tx-20260927-r2",
                "waiting_for_resources": false,
                "wall_seconds": 146.80276942253113
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-27T15:20:59.647163+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "21d14cbd7b5fd6b9b3154d8613de3125116372b534035652042a51f3df7f403f",
                "execution_seconds": 13549.23893070221,
                "queue_seconds": 5617.021144866943,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_cosine_readout_lab10_r2-full-w1",
                "transaction_id": "mvcnet-cosine-readout-tx-20260927-r2",
                "waiting_for_resources": false,
                "wall_seconds": 19166.260075569153
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r7_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-conv-sam-screen-lab10-r7",
      "round_id": "mvcnet-conv-sam-screen-lab10-r7",
      "run": {
        "bundle_id": "2026-09-27_mvcnet_conv_sam_lab10_bundle_r7",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 0.25,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 4,
        "recorded_at": "2026-09-29T13:32:37.048443+00:00",
        "round_id": "mvcnet-conv-sam-screen-lab10-r7",
        "run_prefix": "2026-09-27_mvcnet_conv_sam_lab10_r7",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-29T13:35:07.827534+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-29T13:38:21.984609+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T13:38:46.379209+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "9602f44fcb743179f53887d9ec1252bfcdda90776e9873b86f8fe3553b60ffbf",
                "execution_seconds": 20.999347686767578,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
                "transaction_id": "mvcnet-conv-sam-tx-20260927-r7",
                "waiting_for_resources": false,
                "wall_seconds": 20.999347686767578
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-29T15:14:39.163371+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "9602f44fcb743179f53887d9ec1252bfcdda90776e9873b86f8fe3553b60ffbf",
                "execution_seconds": 250.99546098709106,
                "queue_seconds": 14.798622131347656,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
                "transaction_id": "mvcnet-conv-sam-tx-20260927-r7",
                "waiting_for_resources": false,
                "wall_seconds": 265.7940831184387
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-09-29T15:18:48.957032+00:00",
            "result": {
              "artifact_manifest_sha256": "1dd2952e772da44d040790abbbfffcd91db2c8b5e3193be7ea807236770717f3",
              "contract_sha256": "9602f44fcb743179f53887d9ec1252bfcdda90776e9873b86f8fe3553b60ffbf",
              "run_id": "2026-09-27_mvcnet_conv_sam_lab10_r7-full-w1",
              "transaction_id": "mvcnet-conv-sam-tx-20260927-r7",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r4_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-excluded-distillation-screen-lab10-r4",
      "round_id": "mvcnet-source-excluded-distillation-screen-lab10-r4",
      "run": {
        "bundle_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_bundle_r4",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 58,
        "estimated_training_hours": 3.625,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 167,
        "recorded_at": "2026-10-03T13:30:29.979396+00:00",
        "round_id": "mvcnet-source-excluded-distillation-screen-lab10-r4",
        "run_prefix": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-03T13:32:32.660781+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-03T13:32:35.156898+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-03T13:33:01.393234+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5762262e18c88c87faf0b16d29fdaecc627d1a5b6f60749fd17cbed980211974",
                "execution_seconds": 11.31966781616211,
                "queue_seconds": 9.504286766052246,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
                "transaction_id": "mvcnet-source-excluded-distillation-tx-20260930-r4",
                "waiting_for_resources": true,
                "wall_seconds": 20.823954582214355
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-03T15:09:02.642084+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5762262e18c88c87faf0b16d29fdaecc627d1a5b6f60749fd17cbed980211974",
                "execution_seconds": 11.319624423980713,
                "queue_seconds": 5771.001242160797,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
                "transaction_id": "mvcnet-source-excluded-distillation-tx-20260930-r4",
                "waiting_for_resources": true,
                "wall_seconds": 5782.320866584778
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-04T01:17:04.600866+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "5762262e18c88c87faf0b16d29fdaecc627d1a5b6f60749fd17cbed980211974",
                "execution_seconds": 3349.537891626358,
                "queue_seconds": 20131.762219905853,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
                "transaction_id": "mvcnet-source-excluded-distillation-tx-20260930-r4",
                "waiting_for_resources": false,
                "wall_seconds": 23481.30011153221
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-04T01:26:44.747989+00:00",
            "result": {
              "artifact_manifest_sha256": "849ac59d2c34ddd26d0549d1a81bbabc6c0903039f1aed7cab6cb6e069cb18c7",
              "contract_sha256": "5762262e18c88c87faf0b16d29fdaecc627d1a5b6f60749fd17cbed980211974",
              "run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r4-full-w1",
              "transaction_id": "mvcnet-source-excluded-distillation-tx-20260930-r4",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-class-relation-screen-ccmu-r6_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-class-relation-screen-ccmu-r6",
      "round_id": "mvcnet-source-class-relation-screen-ccmu-r6",
      "run": {
        "bundle_id": "2026-10-05_mvcnet_source_class_relation_ccmu_bundle_r6",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 81,
        "estimated_training_hours": 16.667,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 169,
        "recorded_at": "2026-10-05T13:36:47.962735+00:00",
        "round_id": "mvcnet-source-class-relation-screen-ccmu-r6",
        "run_prefix": "2026-10-05_mvcnet_source_class_relation_ccmu_r6",
        "transaction_operations": [
          {
            "operation": "launch",
            "recorded_at": "2026-10-05T13:37:38.533147+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-05T13:37:57.588221+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "q_seal",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
                "execution_seconds": 18.110548496246338,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
                "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
                "waiting_for_resources": false,
                "wall_seconds": 18.110548496246338
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-05T13:39:25.801034+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
                "execution_seconds": 106.31927990913391,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
                "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
                "waiting_for_resources": false,
                "wall_seconds": 106.31927990913391
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-05T13:46:58.433001+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
                "execution_seconds": 558.715626001358,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
                "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
                "waiting_for_resources": false,
                "wall_seconds": 558.715626001358
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-05T23:19:36.471549+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
                "execution_seconds": 34917.5870923996,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
                "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
                "waiting_for_resources": false,
                "wall_seconds": 34917.5870923996
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-06T08:41:45.874332+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
                "execution_seconds": 42051.42586350441,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
                "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
                "waiting_for_resources": false,
                "wall_seconds": 42051.42586350441
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-06T08:46:35.260548+00:00",
            "result": {
              "artifact_manifest_sha256": "aee5c5b85e08ed2d31204f53e9ec3cf51119bc855248c185d3b8edabe13aebba",
              "contract_sha256": "a74246a82909cfb9fb26947ead8d0370022e457fb81a64ddae3ace4e3e190dfa",
              "run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r6-full-w1",
              "transaction_id": "mvcnet-source-class-relation-tx-20261005-r6",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-class-mean-alignment-screen-ccmu-r1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-class-mean-alignment-screen-ccmu-r1",
      "round_id": "mvcnet-source-class-mean-alignment-screen-ccmu-r1",
      "run": {
        "bundle_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_bundle_r1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 81,
        "estimated_training_hours": 16.667,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 168,
        "recorded_at": "2026-10-06T12:21:27.033672+00:00",
        "round_id": "mvcnet-source-class-mean-alignment-screen-ccmu-r1",
        "run_prefix": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-06T12:22:25.102730+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-06T12:22:26.639728+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-06T12:22:43.666020+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "coverage",
              "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0f153a10f061916eb6d41c67cb31dd7b5e5fba5f7fa8a0698bf0c10be04580c7",
                "execution_seconds": 16.455005884170532,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
                "transaction_id": "mvcnet-source-class-mean-alignment-tx-20261006-r1",
                "waiting_for_resources": false,
                "wall_seconds": 16.455005884170532
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-06T12:24:14.749335+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0f153a10f061916eb6d41c67cb31dd7b5e5fba5f7fa8a0698bf0c10be04580c7",
                "execution_seconds": 107.53944420814514,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
                "transaction_id": "mvcnet-source-class-mean-alignment-tx-20261006-r1",
                "waiting_for_resources": false,
                "wall_seconds": 107.53944420814514
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-06T15:33:15.047078+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0f153a10f061916eb6d41c67cb31dd7b5e5fba5f7fa8a0698bf0c10be04580c7",
                "execution_seconds": 11448.134041547775,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
                "transaction_id": "mvcnet-source-class-mean-alignment-tx-20261006-r1",
                "waiting_for_resources": false,
                "wall_seconds": 11448.134041547775
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-07T03:34:29.263587+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "0f153a10f061916eb6d41c67cb31dd7b5e5fba5f7fa8a0698bf0c10be04580c7",
                "execution_seconds": 42699.823024749756,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-06_mvcnet_source_class_mean_alignment_ccmu_r1-full-w1",
                "transaction_id": "mvcnet-source-class-mean-alignment-tx-20261006-r1",
                "waiting_for_resources": false,
                "wall_seconds": 42699.823024749756
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-head-meta-screen-ccmu-r4_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-source-head-meta-screen-ccmu-r4",
      "round_id": "mvcnet-source-head-meta-screen-ccmu-r4",
      "run": {
        "bundle_id": "2026-10-08_mvcnet_source_head_meta_ccmu_bundle_r4",
        "contract": "ai4s/programs/mvcnet/research/mvcnet-source-head-meta-screen-ccmu-r4.yaml",
        "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 9,
        "estimated_training_hours": 1.852,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 168,
        "recorded_at": "2026-10-08T09:28:27.036406+00:00",
        "recovery_of": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1",
        "round_id": "mvcnet-source-head-meta-screen-ccmu-r4",
        "run_prefix": "2026-10-08_mvcnet_source_head_meta_ccmu_r4",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-08T09:28:56.841623+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-08T09:28:58.569923+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T09:30:02.417208+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
                "execution_seconds": 63.18827486038208,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
                "waiting_for_resources": false,
                "wall_seconds": 63.18827486038208
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T09:30:43.113216+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
                "execution_seconds": 103.88889980316162,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
                "waiting_for_resources": false,
                "wall_seconds": 103.88889980316162
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T09:33:03.437356+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
                "execution_seconds": 244.2145881652832,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
                "waiting_for_resources": false,
                "wall_seconds": 244.2145881652832
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T09:36:51.512401+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
                "execution_seconds": 472.07116436958313,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
                "waiting_for_resources": false,
                "wall_seconds": 472.07116436958313
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T11:05:04.350679+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
                "execution_seconds": 673.451967716217,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
                "waiting_for_resources": false,
                "wall_seconds": 673.451967716217
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-08T11:26:03.184602+00:00",
            "result": {
              "artifact_manifest_sha256": "6b45cc01797cefa88ade5f7fa25cc4c5844523054573c0bf4e3d511a1cb90e8a",
              "contract_sha256": "3412eb303a5889ec85282f11833fb5c45d7ccc7877d0eede151aff276dbfaa48",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
              "transaction_id": "mvcnet-source-head-meta-tx-20261008-r4",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2",
      "round_id": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2",
      "run": {
        "bundle_id": "2026-10-18_mvcnet_augmentation_readout_lab10_bundle_r1_resume69_repair2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 69,
        "estimated_training_hours": 140.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "local_full_intake_materialized": false,
        "planned_units": 150,
        "recorded_at": "2026-10-18T04:11:21.876704+00:00",
        "remote_analysis_record": "ai4s/programs/mvcnet/research/augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/DECISION.json",
        "remote_terminal_status": "complete",
        "round_id": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2",
        "run_prefix": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-18T04:12:55.882770+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-18T04:12:58.928028+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T04:13:21.252652+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7e6ba57cf52614bb92d2678a83b8d33bfa260a4fda6b516ca6e6e57f4d885c6a",
                "execution_seconds": 17.44379711151123,
                "queue_seconds": 0.914806604385376,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
                "transaction_id": "mvcnet-augmentation-readout-tx-20261018-r1-resume69-repair2",
                "waiting_for_resources": true,
                "wall_seconds": 18.358603715896606
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-18T04:14:07.332218+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7e6ba57cf52614bb92d2678a83b8d33bfa260a4fda6b516ca6e6e57f4d885c6a",
                "execution_seconds": 17.61801838874817,
                "queue_seconds": 46.834956884384155,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
                "transaction_id": "mvcnet-augmentation-readout-tx-20261018-r1-resume69-repair2",
                "waiting_for_resources": true,
                "wall_seconds": 64.45297527313232
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-19T03:17:08.709645+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "7e6ba57cf52614bb92d2678a83b8d33bfa260a4fda6b516ca6e6e57f4d885c6a",
                "execution_seconds": 82489.54448604584,
                "queue_seconds": 557.9990754127502,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
                "transaction_id": "mvcnet-augmentation-readout-tx-20261018-r1-resume69-repair2",
                "waiting_for_resources": false,
                "wall_seconds": 83047.54356145859
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-vbr-r1-screen-lab10-r1-repair3_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-vbr-r1-screen-lab10-r1-repair3",
      "round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair3",
      "run": {
        "bundle_id": "2026-10-28_mvcnet_vbr_r1_lab10_bundle_r1_repair3_packfix2",
        "contract": "ai4s/programs/mvcnet/research/mvcnet-vbr-r1-screen-lab10-r1-repair3-packfix2.yaml",
        "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 72,
        "estimated_training_hours": 237.25,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 154,
        "recorded_at": "2026-10-28T10:39:40.244448+00:00",
        "round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair3",
        "run_prefix": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-28T10:40:01.247008+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-28T10:40:04.053942+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T10:41:11.257196+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
                "execution_seconds": 17.72791576385498,
                "queue_seconds": 44.65704536437988,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
                "transaction_id": "mvcnet-vbr-r1-tx-20261028-r1-repair3-packfix2",
                "waiting_for_resources": true,
                "wall_seconds": 62.38496112823486
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T14:18:55.498078+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
                "execution_seconds": 12876.69152545929,
                "queue_seconds": 250.2412736415863,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
                "transaction_id": "mvcnet-vbr-r1-tx-20261028-r1-repair3-packfix2",
                "waiting_for_resources": false,
                "wall_seconds": 13126.932799100876
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-28T17:52:20.734832+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
                "execution_seconds": 23155.940205812454,
                "queue_seconds": 252.24397730827332,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
                "transaction_id": "mvcnet-vbr-r1-tx-20261028-r1-repair3-packfix2",
                "waiting_for_resources": false,
                "wall_seconds": 23408.184183120728
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-10-28T18:22:27.857480+00:00",
            "result": {
              "addendum_sha256": "191e86ebf84071b7c06a52c09888734bb91949315d4f438038d1d7c0e46cf6a9",
              "artifact_manifest_sha256": "206ac78625979fe528c4061543e8158f3a41a5595451ff724a95bf543116812f",
              "bundle_manifest_sha256": "8ed6eb37ce031dc04af05fd31695670e9acb082d8fe55f50415bdfbb4337d946",
              "complete_remote": true,
              "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
              "core_manifest_sha256": "8f23d0cf6a3c85870189581f8bb578816bcc4cb10bb4cd2778aa461adba0a516",
              "full_payload_local": false,
              "intake_scope": "analysis_v1_recovery",
              "run_id": "2026-10-28_mvcnet_vbr_r1_lab10_r1_repair3_packfix2-full-w1",
              "support_sha256": "44326a309be05f654410a5c92c8742185cc2000a6ad61c01aceb5151eca1ffed",
              "transaction_id": "mvcnet-vbr-r1-tx-20261028-r1-repair3-packfix2",
              "transfer_bytes": 27222739,
              "verified": true,
              "verified_at_utc": "2026-10-28T18:21:05.601717+00:00"
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-xsn-r1-screen-lab10-r1-budget480_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-xsn-r1-screen-lab10-r1-budget480",
      "round_id": "mvcnet-xsn-r1-screen-lab10-r1-budget480",
      "run": {
        "bundle_id": "2026-10-31_mvcnet_xsn_r1_lab10_bundle_r1_budget480_packfix1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 90,
        "estimated_training_hours": 432.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 192,
        "recorded_at": "2026-10-30T20:52:28.157406+00:00",
        "round_id": "mvcnet-xsn-r1-screen-lab10-r1-budget480",
        "run_prefix": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-30T20:53:44.038286+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-30T20:55:15.199824+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-30T20:56:26.727135+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 43.385329723358154,
                "queue_seconds": 16.164865493774414,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": true,
                "wall_seconds": 59.55019521713257
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-31T05:58:29.132025+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 137.63391637802124,
                "queue_seconds": 32444.993614673615,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": true,
                "wall_seconds": 32582.627531051636
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-01T04:44:45.961077+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 10687.505733728409,
                "queue_seconds": 103871.65816307068,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": true,
                "wall_seconds": 114559.16389679909
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-01T14:54:25.530479+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 10773.1220099926,
                "queue_seconds": 140363.5455532074,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": true,
                "wall_seconds": 151136.6675632
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-02T15:46:35.823019+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 11022.066134214401,
                "queue_seconds": 229645.34784460068,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": true,
                "wall_seconds": 240667.41397881508
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-03T13:10:06.823755+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "diagnostic",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 11208.993481636047,
                "queue_seconds": 306468.8509852886,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": true,
                "wall_seconds": 317677.84446692467
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-04T12:30:27.875234+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
                "execution_seconds": 30514.033852100372,
                "queue_seconds": 311798.2159655094,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
                "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
                "waiting_for_resources": false,
                "wall_seconds": 342312.2498176098
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-04T12:56:02.418090+00:00",
            "result": {
              "action": "FETCHED_VERIFIED",
              "analysis_receipt_sha256": "8e90ad02bcc9e445b3978a363e10360c595348af85eccebe7786640c5356bccc",
              "artifact_manifest_sha256": "0644f17901c81030a03c080bdafdbf09818e5f7ed2fcd6651c6b5242104b26d5",
              "contract_sha256": "1c199413e43a6c42faa6badcee0db2ef1f056838527818063b47a6948618f3a8",
              "full_payload_local": false,
              "intake_scope": "analysis_v1_recovery",
              "receipt_ref": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/FETCH_VERIFIED.json",
              "run_id": "2026-10-31_mvcnet_xsn_r1_lab10_r1_budget480-full-w1",
              "transaction_id": "mvcnet-xsn-r1-tx-20261031-budget480",
              "transfer_bytes": 31464578,
              "transport": "same-Run compact recovery tarball",
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-acm-r1-screen-lab10-checkrepair2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-acm-r1-screen-lab10-checkrepair2",
      "round_id": "mvcnet-acm-r1-screen-lab10-checkrepair2",
      "run": {
        "bundle_id": "2026-11-05_mvcnet_acm_r1_lab10_bundle_checkrepair2_packfix1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 72,
        "estimated_training_hours": 4.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 73,
        "recorded_at": "2026-11-05T13:20:29.025038+00:00",
        "round_id": "mvcnet-acm-r1-screen-lab10-checkrepair2",
        "run_prefix": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-05T13:20:44.386843+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-05T13:20:45.919585+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-05T13:21:07.586705+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "source-integrity",
              "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
                "execution_seconds": 18.50507140159607,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
                "transaction_id": "mvcnet-acm-r1-tx-20261105-checkrepair2",
                "waiting_for_resources": false,
                "wall_seconds": 18.50507140159607
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-05T13:27:39.288167+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
                "execution_seconds": 409.41458225250244,
                "queue_seconds": 0.788313627243042,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
                "transaction_id": "mvcnet-acm-r1-tx-20261105-checkrepair2",
                "waiting_for_resources": false,
                "wall_seconds": 410.2028958797455
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-05T13:28:42.409006+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
                "execution_seconds": 415.4840364456177,
                "queue_seconds": 0.788313627243042,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
                "transaction_id": "mvcnet-acm-r1-tx-20261105-checkrepair2",
                "waiting_for_resources": false,
                "wall_seconds": 416.2723500728607
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-05T13:32:45.724090+00:00",
            "result": {
              "analysis_receipt_sha256": "510b47660658f3dd969953cfea81a8f0f06e7240a9235bdb7dfad690ec6ff1c1",
              "artifact_manifest_sha256": "33535de00eadda737f59f7011965b57e042fb9485db6c80a054e1bb41a35808c",
              "contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-05_mvcnet_acm_r1_lab10_checkrepair2-full-w1",
              "transaction_id": "mvcnet-acm-r1-tx-20261105-checkrepair2",
              "transfer_bytes": 22225398,
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
        "round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2"
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2",
      "round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2",
      "run": {
        "bundle_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_bundle_r1_py39fix1_sealfix2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 4.562,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 73,
        "recorded_at": "2026-11-08T11:33:23.470108+00:00",
        "round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2",
        "run_prefix": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-08T11:34:23.967713+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-08T11:34:58.954728+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-08T11:35:15.991667+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "df5a3476a80c807f4b81a0344683cd987b7977c9741516fc06d184f2a308ea57",
                "execution_seconds": 16.04147219657898,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1",
                "transaction_id": "mvcnet-cue-aligned-two-arm-tx-20261106-r1-py39fix1-sealfix2",
                "waiting_for_resources": false,
                "wall_seconds": 16.04147219657898
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-08T13:58:54.799185+00:00",
            "result": {
              "analysis_receipt_sha256": "8d1162a88ab3e42e674558e18d234462404bb2af3c0f5bf1658d3342dd385277",
              "artifact_manifest_sha256": "eccf1daa200552ee68f3546fa09e40f000bd4afe1dd49f70252c8059d1069f47",
              "contract_sha256": "df5a3476a80c807f4b81a0344683cd987b7977c9741516fc06d184f2a308ea57",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix2-full-w1",
              "transaction_id": "mvcnet-cue-aligned-two-arm-tx-20261106-r1-py39fix1-sealfix2",
              "transfer_bytes": 5309246,
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-nonadjacent-context-filter-development_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-nonadjacent-context-filter-development",
      "round_id": "mvcnet-nonadjacent-context-filter-development",
      "run": {
        "bundle_id": "2026-11-12_mvcnet_context_filter_lab10_development-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 9.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 24,
        "recorded_at": "2026-11-12T15:48:32.691672+00:00",
        "round_id": "mvcnet-nonadjacent-context-filter-development",
        "run_prefix": "2026-11-12_mvcnet_context_filter_lab10_development",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-12T15:49:01.176360+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-12_mvcnet_context_filter_lab10_development-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-12T15:49:43.102310+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-12_mvcnet_context_filter_lab10_development-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-12T15:50:10.524276+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-12_mvcnet_context_filter_lab10_development-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "86c240553fdc85c3f0976ed7a9397ff5acf802bc63fddbcd534d6df8473e0679",
                "execution_seconds": 21.237293481826782,
                "queue_seconds": 4.206317901611328,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-12_mvcnet_context_filter_lab10_development-full-w1",
                "transaction_id": "2026-11-12_mvcnet_context_filter_lab10_development-tx",
                "waiting_for_resources": false,
                "wall_seconds": 25.44361138343811
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-13T17:09:58.377697+00:00",
            "result": {
              "analysis_receipt_sha256": "5aeb23d303b9ea5e35d5baec393455f3da1a30b0fa560a3d6220f609261b1a30",
              "artifact_manifest_sha256": "5546c584176bd04dc6eb98a052c8eccc38de1fcc9f1dc38225738dd16350d513",
              "contract_sha256": "86c240553fdc85c3f0976ed7a9397ff5acf802bc63fddbcd534d6df8473e0679",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-12_mvcnet_context_filter_lab10_development-full-w1",
              "transaction_id": "2026-11-12_mvcnet_context_filter_lab10_development-tx",
              "transfer_bytes": 1696098,
              "verified": true
            }
          }
        ]
      }
    },
    {
      "administrative_reconciliation": true,
      "continuation_intake": {
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
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-acm-factorial-development_decision.yaml",
      "evidence_id": "MVCNET-ACM-FACTORIAL-CHECKFINISH2-CLOSEOUT-20261116",
      "reconciliation": "ai4s/programs/mvcnet/research/acm-r1/factorial/CONTROLLER_RECONCILIATION_20261116.json",
      "recorded_at": "2026-11-16T15:44:37.744328+00:00",
      "round_id": "mvcnet-acm-factorial-development",
      "run": {
        "bundle_id": "2026-11-14_mvcnet_acm_factorial_lab10-bundle",
        "dispatch_status": "REMOTE_FAILED_RECONCILED",
        "estimated_training_hours": 30.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 72,
        "recorded_at": "2026-11-13T20:44:36.881398+00:00",
        "round_id": "mvcnet-acm-factorial-development",
        "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
        "run_prefix": "2026-11-14_mvcnet_acm_factorial_lab10",
        "status": "FAILED",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-13T20:44:54.032026+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-13T20:45:24.189885+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-13T20:45:42.442052+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "319ed6901d80740804e782c889a427fbb5047983c78f08771e5abd89f0600a8c",
                "execution_seconds": 6.152045965194702,
                "queue_seconds": 11.314758777618408,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
                "transaction_id": "2026-11-14_mvcnet_acm_factorial_lab10-tx",
                "waiting_for_resources": true,
                "wall_seconds": 17.46680474281311
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-14T03:13:09.223220+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "319ed6901d80740804e782c889a427fbb5047983c78f08771e5abd89f0600a8c",
                "execution_seconds": 8749.735214948654,
                "queue_seconds": 14514.89348244667,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
                "transaction_id": "2026-11-14_mvcnet_acm_factorial_lab10-tx",
                "waiting_for_resources": true,
                "wall_seconds": 23264.628697395325
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-14T04:49:44.451365+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "319ed6901d80740804e782c889a427fbb5047983c78f08771e5abd89f0600a8c",
                "execution_seconds": 10573.775741815567,
                "queue_seconds": 18486.178591012955,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-14_mvcnet_acm_factorial_lab10-full-w1",
                "transaction_id": "2026-11-14_mvcnet_acm_factorial_lab10-tx",
                "waiting_for_resources": true,
                "wall_seconds": 29059.95433282852
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-acm-s8-loso-stability_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-acm-s8-loso-stability",
      "round_id": "mvcnet-acm-s8-loso-stability",
      "run": {
        "bundle_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 44.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 180,
        "recorded_at": "2026-11-17T11:50:23.168917+00:00",
        "round_id": "mvcnet-acm-s8-loso-stability",
        "run_prefix": "2026-11-17_mvcnet_acm_s8_loso_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-17T11:50:50.533407+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-17T11:51:50.159577+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-17T11:52:09.592646+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2f67bb81cbe745c52cc0b9d1d5c1efce687f7022ce36a652e2f74f2e9f92cfad",
                "execution_seconds": 13.065919399261475,
                "queue_seconds": 4.973520517349243,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
                "transaction_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 18.039439916610718
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-17T13:11:52.799325+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2f67bb81cbe745c52cc0b9d1d5c1efce687f7022ce36a652e2f74f2e9f92cfad",
                "execution_seconds": 4796.371497392654,
                "queue_seconds": 4.973520517349243,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
                "transaction_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4801.345017910004
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-17T14:47:08.486434+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2f67bb81cbe745c52cc0b9d1d5c1efce687f7022ce36a652e2f74f2e9f92cfad",
                "execution_seconds": 10512.162744760513,
                "queue_seconds": 4.973520517349243,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
                "transaction_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10517.136265277863
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-18T01:02:17.868443+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "2f67bb81cbe745c52cc0b9d1d5c1efce687f7022ce36a652e2f74f2e9f92cfad",
                "execution_seconds": 18230.377185821533,
                "queue_seconds": 13.416983842849731,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-full-w1",
                "transaction_id": "2026-11-17_mvcnet_acm_s8_loso_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 18243.794169664383
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-acm-s8-loso-extension-gpu10-pack1-checkfix1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-acm-s8-loso-extension-gpu10-pack1-checkfix1",
      "round_id": "mvcnet-acm-s8-loso-extension-gpu10-pack1-checkfix1",
      "run": {
        "bundle_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-bundle",
        "capacity_rollover_of": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-full-w1",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 270,
        "estimated_training_hours": 32.357,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 540,
        "recorded_at": "2026-11-18T08:39:07.605625+00:00",
        "round_id": "mvcnet-acm-s8-loso-extension-gpu10-pack1-checkfix1",
        "run_prefix": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-18T08:39:15.320776+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-18T08:51:08.101392+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-18T08:57:49.923207+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "0d46c75539dd242e5a97fe3122d3b8d53b3c7297ef4fc92489377ea35e99cfdb",
                "execution_seconds": 400.27956914901733,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1",
                "transaction_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 400.27956914901733
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-18T09:52:26.309783+00:00",
            "result": {
              "analysis_receipt_sha256": "03cacc13a31d84d3bfcc3981a4c938003fa7f107ad2e9a8691dacf58fe9d5047",
              "artifact_manifest_sha256": "5c2ed567e98cb13c346241bb22bd5abdf2a100e232c4de19590977b5e9abb8a8",
              "contract_sha256": "0d46c75539dd242e5a97fe3122d3b8d53b3c7297ef4fc92489377ea35e99cfdb",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-full-w1",
              "transaction_id": "2026-11-18_mvcnet_acm_s8_loso_extension_lab10-gpu10-pack1-checkfix1-tx",
              "transfer_bytes": 2879694,
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-dual-bn-004-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-dual-bn-004-development-v1",
      "round_id": "mvcnet-dual-bn-004-development-v1",
      "run": {
        "bundle_id": "2026-11-19_mvcnet_dual_bn_004_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 18.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 72,
        "recorded_at": "2026-11-19T15:00:40.587002+00:00",
        "round_id": "mvcnet-dual-bn-004-development-v1",
        "run_prefix": "2026-11-19_mvcnet_dual_bn_004_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-19T15:01:16.740740+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-19T15:01:18.627595+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-19T15:01:50.609783+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "30329075e7b0c8530966aff6da5a842fb21d9c75d5753d2c80a58de7a408086a",
                "execution_seconds": 30.387417793273926,
                "queue_seconds": 0.8414535522460938,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
                "transaction_id": "2026-11-19_mvcnet_dual_bn_004_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 31.22887134552002
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-19T16:12:59.574098+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "30329075e7b0c8530966aff6da5a842fb21d9c75d5753d2c80a58de7a408086a",
                "execution_seconds": 4270.166758775711,
                "queue_seconds": 2.5296928882598877,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
                "transaction_id": "2026-11-19_mvcnet_dual_bn_004_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4272.696451663971
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-19T16:13:17.575204+00:00",
            "result": {
              "analysis_receipt_sha256": "a1e424b56ccc43ea68a2cdffa90d706f262cea1a4196c1474304821b0b01f1d5",
              "artifact_manifest_sha256": "a27630b7749ac37ab532f0f20fb1ffffb1e695ca4d0ceb182a1ca3b75ae2bc11",
              "contract_sha256": "30329075e7b0c8530966aff6da5a842fb21d9c75d5753d2c80a58de7a408086a",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-19_mvcnet_dual_bn_004_lab10-full-w1",
              "transaction_id": "2026-11-19_mvcnet_dual_bn_004_lab10-tx",
              "transfer_bytes": 893085,
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-dual-bn-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-dual-bn-001-development-v1",
      "round_id": "mvcnet-dual-bn-001-development-v1",
      "run": {
        "bundle_id": "2026-11-20_mvcnet_dual_bn_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 20.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-19T16:39:03.936411+00:00",
        "round_id": "mvcnet-dual-bn-001-development-v1",
        "run_prefix": "2026-11-20_mvcnet_dual_bn_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-19T16:39:23.207723+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-19T16:39:37.550614+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-19T16:39:52.574891+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "2f61a543d54eb1293078ca94296c4fa7eed3997fc97f6aea673a95adf7a8c2ec",
                "execution_seconds": 13.36691927909851,
                "queue_seconds": 0.8366456031799316,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
                "transaction_id": "2026-11-20_mvcnet_dual_bn_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 14.203564882278442
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-20T08:16:21.972983+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "2f61a543d54eb1293078ca94296c4fa7eed3997fc97f6aea673a95adf7a8c2ec",
                "execution_seconds": 8181.123764514923,
                "queue_seconds": 1.6739814281463623,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
                "transaction_id": "2026-11-20_mvcnet_dual_bn_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8182.7977459430695
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-20T08:17:36.199873+00:00",
            "result": {
              "analysis_receipt_sha256": "2a9c3aa26d12d0eed0c1dbda793496ea4736ba7256bb57a29db88fe77613a811",
              "artifact_manifest_sha256": "7e7d6d77e261adc208935ec7aba2de6efe8da8eaedb4c894a5f2bed43d5d8d0c",
              "contract_sha256": "2f61a543d54eb1293078ca94296c4fa7eed3997fc97f6aea673a95adf7a8c2ec",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-20_mvcnet_dual_bn_001_lab10-full-w1",
              "transaction_id": "2026-11-20_mvcnet_dual_bn_001_lab10-tx",
              "transfer_bytes": 1498314,
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-cross-subject-block-exchange-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-cross-subject-block-exchange-001-development-v1",
      "round_id": "mvcnet-cross-subject-block-exchange-001-development-v1",
      "run": {
        "bundle_id": "2026-11-20_mvcnet_block_exchange_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 20.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-20T16:39:40.659001+00:00",
        "round_id": "mvcnet-cross-subject-block-exchange-001-development-v1",
        "run_prefix": "2026-11-20_mvcnet_block_exchange_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-20T16:39:56.115354+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-20T16:39:58.461614+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-20T16:40:24.264589+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "603cff7167906e833f841880dcff172c46e3478d3784f72275e939597d78ec56",
                "execution_seconds": 24.095725536346436,
                "queue_seconds": 0.8280825614929199,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1",
                "transaction_id": "2026-11-20_mvcnet_block_exchange_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 24.923808097839355
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-20T23:48:50.784791+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "603cff7167906e833f841880dcff172c46e3478d3784f72275e939597d78ec56",
                "execution_seconds": 8507.837190628052,
                "queue_seconds": 1.6664395332336426,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10-full-w1",
                "transaction_id": "2026-11-20_mvcnet_block_exchange_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8509.503630161285
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-envelope-rotation-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-envelope-rotation-001-development-v1",
      "round_id": "mvcnet-envelope-rotation-001-development-v1",
      "run": {
        "bundle_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 10.005,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-21T17:30:15.560968+00:00",
        "round_id": "mvcnet-envelope-rotation-001-development-v1",
        "run_prefix": "2026-11-22_mvcnet_envelope_rotation_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-21T17:30:50.808887+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-21T17:30:53.366481+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-21T17:31:06.619200+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "b2580fa756600f1d63b875b0d87f32f796c102c17d20d508e181b432430d96e8",
                "execution_seconds": 11.27688217163086,
                "queue_seconds": 0.966965913772583,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 12.243848085403442
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T02:24:25.337729+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "b2580fa756600f1d63b875b0d87f32f796c102c17d20d508e181b432430d96e8",
                "execution_seconds": 8684.193619251251,
                "queue_seconds": 1.9324514865875244,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 8686.126070737839
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-22T02:29:18.768980+00:00",
            "result": {
              "analysis_receipt_sha256": "805ea5f744b764ee0aa1f9dae5ff2eefe1f79ad55f91de89121043b540a99c9d",
              "artifact_manifest_sha256": "9b3addfe80bdfef92bc8521d8955db13a15c8fe18412d8f0e1a2e729a711037e",
              "contract_sha256": "b2580fa756600f1d63b875b0d87f32f796c102c17d20d508e181b432430d96e8",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-full-w1",
              "transaction_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10-tx",
              "transfer_bytes": 1513051,
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-rate125-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-rate125-001-development-v1",
      "round_id": "mvcnet-rate125-001-development-v1",
      "run": {
        "bundle_id": "2026-11-22_mvcnet_rate125_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 8.217,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-22T09:28:14.410434+00:00",
        "round_id": "mvcnet-rate125-001-development-v1",
        "run_prefix": "2026-11-22_mvcnet_rate125_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-22T09:29:02.157561+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-22T09:29:05.987538+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T09:29:22.443643+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "146dae04f6ca68f5c0d47995f37d18a3862081918d3ff6c7d3b8dd095cd035fd",
                "execution_seconds": 14.550769567489624,
                "queue_seconds": 0.9573426246643066,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_rate125_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15.50811219215393
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T14:49:59.779949+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "146dae04f6ca68f5c0d47995f37d18a3862081918d3ff6c7d3b8dd095cd035fd",
                "execution_seconds": 7061.8200516700745,
                "queue_seconds": 2.1281442642211914,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_rate125_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 7063.948195934296
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-22T14:53:28.150965+00:00",
            "result": {
              "analysis_receipt_sha256": "b966ce08e419120d40a3a587cc4dd56e0f2d81494f1c87ba6e2096e1e3af0c1a",
              "artifact_manifest_sha256": "4bef95abf1155ca4cb979bcc1e271d8f097b2f95b916bd1cb3c6fb92b774bce2",
              "contract_sha256": "146dae04f6ca68f5c0d47995f37d18a3862081918d3ff6c7d3b8dd095cd035fd",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-22_mvcnet_rate125_001_lab10-full-w1",
              "transaction_id": "2026-11-22_mvcnet_rate125_001_lab10-tx",
              "transfer_bytes": 1506970,
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-auxspace-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-auxspace-001-development-v1",
      "round_id": "mvcnet-auxspace-001-development-v1",
      "run": {
        "bundle_id": "2026-11-22_mvcnet_auxspace_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 10.474,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-22T15:26:49.552823+00:00",
        "round_id": "mvcnet-auxspace-001-development-v1",
        "run_prefix": "2026-11-22_mvcnet_auxspace_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-22T15:27:42.141737+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-22T15:27:44.808907+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T15:27:56.161509+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c09b99b026ff56392fd91b12aa3332650fdbe5e488813502ba2c53f69069bc1",
                "execution_seconds": 8.257291793823242,
                "queue_seconds": 1.7266566753387451,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_auxspace_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9.983948469161987
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-22T15:43:48.928203+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1c09b99b026ff56392fd91b12aa3332650fdbe5e488813502ba2c53f69069bc1",
                "execution_seconds": 961.0509648323059,
                "queue_seconds": 1.7266566753387451,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_auxspace_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 962.7776215076447
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-23T01:45:29.599282+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "1c09b99b026ff56392fd91b12aa3332650fdbe5e488813502ba2c53f69069bc1",
                "execution_seconds": 18901.529859781265,
                "queue_seconds": 5.886039972305298,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-22_mvcnet_auxspace_001_lab10-full-w1",
                "transaction_id": "2026-11-22_mvcnet_auxspace_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 18907.41589975357
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-reflectcvc-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-reflectcvc-001-development-v1",
      "round_id": "mvcnet-reflectcvc-001-development-v1",
      "run": {
        "bundle_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-bundle",
        "contract": "ai4s/programs/mvcnet/research/cvc_reflection_axis_20261123/repair1/transaction_contract.yaml",
        "contract_sha256": "5203100406b966ec7c6c0b4d4eeaa8f7b306ca6d7ec0d8594230aaa82ffd9ae5",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 85,
        "estimated_training_hours": 7.918,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-23T06:30:10.765478+00:00",
        "round_id": "mvcnet-reflectcvc-001-development-v1",
        "run_prefix": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-23T06:39:24.600369+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-23T06:40:47.962624+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-23T06:41:51.866266+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "5203100406b966ec7c6c0b4d4eeaa8f7b306ca6d7ec0d8594230aaa82ffd9ae5",
                "execution_seconds": 62.78172707557678,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1",
                "transaction_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-tx",
                "waiting_for_resources": false,
                "wall_seconds": 62.78172707557678
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-cvcdropout-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-cvcdropout-001-development-v1",
      "round_id": "mvcnet-cvcdropout-001-development-v1",
      "run": {
        "bundle_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-bundle",
        "contract": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/repair2/transaction_contract.yaml",
        "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 61,
        "estimated_training_hours": 7.0,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-24T12:29:21.059136+00:00",
        "round_id": "mvcnet-cvcdropout-001-development-v1",
        "run_prefix": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-24T12:29:52.229924+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-24T12:29:55.053980+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-24T12:30:07.099535+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 10.208120822906494,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 10.208120822906494
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-24T12:34:39.394794+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 181.69474077224731,
                "queue_seconds": 100.79511427879333,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 282.48985505104065
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-25T00:51:48.783206+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 10288.968613386154,
                "queue_seconds": 34224.07346892357,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 44513.04208230972
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-25T09:31:18.893921+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 10502.589548110962,
                "queue_seconds": 65181.27285146713,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 75683.8623995781
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-25T14:52:51.578232+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 10759.294158220291,
                "queue_seconds": 84217.80614876747,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 94977.10030698776
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-25T15:34:32.186361+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 10770.947411298752,
                "queue_seconds": 86706.79974651337,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 97477.74715781212
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-25T17:52:40.092698+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 10816.046522140503,
                "queue_seconds": 94949.81195187569,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": true,
                "wall_seconds": 105765.85847401619
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-26T06:27:08.262882+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
                "execution_seconds": 11125.731113672256,
                "queue_seconds": 105377.76346206665,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
                "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
                "waiting_for_resources": false,
                "wall_seconds": 116503.4945757389
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-26T06:29:56.188371+00:00",
            "result": {
              "analysis_receipt_sha256": "55c2492b55087166d9e8f997adc1e0d657761d77130b70811c4481e6d8799796",
              "artifact_manifest_sha256": "2bdf2655fa887c696444fd5924d941dbf48ad50fe364ac4e6e41b9992109ce85",
              "contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
              "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-tx",
              "transfer_bytes": 1416234,
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-centralrow-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-centralrow-001-development-v1",
      "round_id": "mvcnet-centralrow-001-development-v1",
      "run": {
        "bundle_id": "2026-11-26_mvcnet_centralrow_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 9.99,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-26T09:04:44.041139+00:00",
        "round_id": "mvcnet-centralrow-001-development-v1",
        "run_prefix": "2026-11-26_mvcnet_centralrow_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-26T09:07:26.426116+00:00",
            "result": {
              "action": "UPLOADED",
              "bundle_id": "2026-11-26_mvcnet_centralrow_001_lab10-bundle",
              "contract_sha256": "83e76e54b73dc2ab298cecc85342c600359e31daa4724646fa87d3bc1670528f",
              "existing_files": 54,
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
              "source_manifest_sha256": "258aa944b576b30417a80a7c81219ae06ddffbe177b3360f86105641017accfa",
              "verified_files": 54
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-26T09:07:51.566159+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-26T09:08:38.365865+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "83e76e54b73dc2ab298cecc85342c600359e31daa4724646fa87d3bc1670528f",
                "execution_seconds": 45.47701835632324,
                "queue_seconds": 0.8194389343261719,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
                "transaction_id": "2026-11-26_mvcnet_centralrow_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 46.296457290649414
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-27T06:19:03.044658+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "83e76e54b73dc2ab298cecc85342c600359e31daa4724646fa87d3bc1670528f",
                "execution_seconds": 9246.339370965958,
                "queue_seconds": 33713.5954079628,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
                "transaction_id": "2026-11-26_mvcnet_centralrow_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 42959.93477892876
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-27T06:21:27.850677+00:00",
            "result": {
              "analysis_receipt_sha256": "c85dbadd5157178e81f729685241e84fd38e360a9ccce287a8d72290b57b79c1",
              "artifact_manifest_sha256": "f50edaf790c666635eb4276d6968f91393488a73365351cb9ef4de3d9cc21158",
              "contract_sha256": "83e76e54b73dc2ab298cecc85342c600359e31daa4724646fa87d3bc1670528f",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-26_mvcnet_centralrow_001_lab10-full-w1",
              "transaction_id": "2026-11-26_mvcnet_centralrow_001_lab10-tx",
              "transfer_bytes": 1507428,
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-pool-antialias-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-pool-antialias-001-development-v1",
      "round_id": "mvcnet-pool-antialias-001-development-v1",
      "run": {
        "bundle_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 10.254,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-27T07:08:23.526175+00:00",
        "round_id": "mvcnet-pool-antialias-001-development-v1",
        "run_prefix": "2026-11-27_mvcnet_pool_antialias_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-27T07:08:43.352325+00:00",
            "result": {
              "action": "UPLOADED",
              "bundle_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-bundle",
              "contract_sha256": "1fc9a9961bbd63ed7d9ba32d3b383c78fe252593007c606b2bd2765deda64f6f",
              "existing_files": 0,
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
              "source_manifest_sha256": "effb8347c3e5fadaa5666ef427024fc03ed395fd4e34756dbe7cb23658db3afc",
              "verified_files": 54
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-27T07:08:46.669484+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-27T07:08:51.335833+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "1fc9a9961bbd63ed7d9ba32d3b383c78fe252593007c606b2bd2765deda64f6f",
                "execution_seconds": 2.621110677719116,
                "queue_seconds": 1.1528501510620117,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
                "transaction_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 3.773960828781128
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-27T13:04:34.914182+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "1fc9a9961bbd63ed7d9ba32d3b383c78fe252593007c606b2bd2765deda64f6f",
                "execution_seconds": 9717.336873292923,
                "queue_seconds": 1.9639127254486084,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
                "transaction_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 9719.300786018372
              }
            }
          },
          {
            "operation": "fetch",
            "recorded_at": "2026-11-27T13:06:39.860810+00:00",
            "result": {
              "analysis_receipt_sha256": "38a1085f9cdf32fddce8fc3cd98384c3e652bf6855cda2f287d62f7e9088dcd1",
              "artifact_manifest_sha256": "b78a11588d1687d5399306792dd9ba04344052f39e2790a7e41a7c90b80e6830",
              "contract_sha256": "1fc9a9961bbd63ed7d9ba32d3b383c78fe252593007c606b2bd2765deda64f6f",
              "full_payload_local": false,
              "intake_scope": "analysis_v1",
              "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-full-w1",
              "transaction_id": "2026-11-27_mvcnet_pool_antialias_001_lab10-tx",
              "transfer_bytes": 1512328,
              "verified": true
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-view-ce-balance-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-view-ce-balance-001-development-v1",
      "round_id": "mvcnet-view-ce-balance-001-development-v1",
      "run": {
        "bundle_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 12.027,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-27T14:43:45.736801+00:00",
        "round_id": "mvcnet-view-ce-balance-001-development-v1",
        "run_prefix": "2026-11-27_mvcnet_view_ce_balance_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-27T14:44:25.306454+00:00",
            "result": {
              "action": "UPLOADED",
              "bundle_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-bundle",
              "contract_sha256": "c770189c413e9aabb8b23fd745995d01fa197979f8af666caf0fc6efa98d0088",
              "existing_files": 0,
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-full-w1",
              "source_manifest_sha256": "4fab0e4f90c313c3bb7d458e6f6ab80b7d2faf2294874520a97e99eb3035a405",
              "verified_files": 54
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-27T14:44:30.221008+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-27T14:44:36.436539+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "c770189c413e9aabb8b23fd745995d01fa197979f8af666caf0fc6efa98d0088",
                "execution_seconds": 4.410159349441528,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-full-w1",
                "transaction_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 4.410159349441528
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
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
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-view-ce-balance-xdataset-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-view-ce-balance-xdataset-development-v1",
      "round_id": "mvcnet-view-ce-balance-xdataset-development-v1",
      "run": {
        "bundle_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 13.304,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 324,
        "recorded_at": "2026-11-27T18:23:08.711699+00:00",
        "round_id": "mvcnet-view-ce-balance-xdataset-development-v1",
        "run_prefix": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-27T18:23:35.693537+00:00",
            "result": {
              "action": "UPLOADED",
              "bundle_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-bundle",
              "contract_sha256": "bfd0092145cc3bfd64df7cf878cf0a34b40eabef9a6386db57b036bef2381473",
              "existing_files": 0,
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-full-w1",
              "source_manifest_sha256": "c5c7dae59302417c62bd9c7f845d99a9f72ae28f7bd7b64c00946fd599d8c29b",
              "verified_files": 70
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-27T18:23:38.982481+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-27T18:23:44.061555+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "science",
              "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "bfd0092145cc3bfd64df7cf878cf0a34b40eabef9a6386db57b036bef2381473",
                "execution_seconds": 2.841238498687744,
                "queue_seconds": 0.7480173110961914,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-full-w1",
                "transaction_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10-tx",
                "waiting_for_resources": true,
                "wall_seconds": 3.5892558097839355
              }
            }
          }
        ]
      }
    },
    {
      "decision": {
        "claim_status": "no_paper_claim",
        "decision": "NO_SIGNAL",
        "next_training_authorized": false,
        "reason": "DEVELOPMENT_GATE_FAILURE",
        "round_id": "mvcnet-ifnet-reference-rank1-001-development-v1",
        "run_action": "STOP",
        "view_ce_balance_analysis": {
          "contrasts": {
            "G0_minus_J0": {
              "ci95_pp": [
                -1.5817901234567902,
                0.7137345679012346
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.4340277777777778,
              "per_seed_pp": [
                -1.253858024691358,
                0.38580246913580246
              ],
              "per_subject_pp": [
                0.6076388888888888,
                -1.2152777777777777,
                -3.0381944444444446,
                -0.8680555555555556,
                1.6493055555555556,
                -0.08680555555555555,
                -2.951388888888889,
                -0.5208333333333334,
                2.517361111111111
              ]
            },
            "G0_minus_S0": {
              "ci95_pp": [
                -1.3409047067901234,
                0.7426697530864198
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": -0.23148148148148148,
              "per_seed_pp": [
                -0.9259259259259259,
                0.46296296296296297
              ],
              "per_subject_pp": [
                0.9548611111111112,
                -3.3854166666666665,
                0.0,
                0.5208333333333334,
                1.1284722222222223,
                -0.08680555555555555,
                -2.6041666666666665,
                -0.4340277777777778,
                1.8229166666666667
              ]
            },
            "J0_minus_S0": {
              "ci95_pp": [
                -0.636574074074074,
                1.1284722222222223
              ],
              "harmed_at_least_10pp": 0,
              "harmed_at_least_5pp": 0,
              "mean_pp": 0.2025462962962963,
              "per_seed_pp": [
                0.3279320987654321,
                0.07716049382716049
              ],
              "per_subject_pp": [
                0.3472222222222222,
                -2.170138888888889,
                3.0381944444444446,
                1.3888888888888888,
                -0.5208333333333334,
                0.0,
                0.3472222222222222,
                0.08680555555555555,
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
              "accuracy_pp": 67.01388888888889,
              "arm": "S0",
              "correct": 386,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 68.05555555555556,
              "arm": "J0",
              "correct": 392,
              "count": 576,
              "outer": 0,
              "seed": 0
            },
            {
              "accuracy_pp": 65.79861111111111,
              "arm": "G0",
              "correct": 379,
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
              "accuracy_pp": 42.1875,
              "arm": "J0",
              "correct": 243,
              "count": 576,
              "outer": 1,
              "seed": 0
            },
            {
              "accuracy_pp": 39.236111111111114,
              "arm": "G0",
              "correct": 226,
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
              "accuracy_pp": 82.46527777777777,
              "arm": "J0",
              "correct": 475,
              "count": 576,
              "outer": 2,
              "seed": 0
            },
            {
              "accuracy_pp": 77.60416666666667,
              "arm": "G0",
              "correct": 447,
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
              "accuracy_pp": 53.125,
              "arm": "G0",
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
              "accuracy_pp": 41.145833333333336,
              "arm": "J0",
              "correct": 237,
              "count": 576,
              "outer": 4,
              "seed": 0
            },
            {
              "accuracy_pp": 40.798611111111114,
              "arm": "G0",
              "correct": 235,
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
              "accuracy_pp": 45.3125,
              "arm": "J0",
              "correct": 261,
              "count": 576,
              "outer": 5,
              "seed": 0
            },
            {
              "accuracy_pp": 42.88194444444444,
              "arm": "G0",
              "correct": 247,
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
              "accuracy_pp": 58.15972222222222,
              "arm": "J0",
              "correct": 335,
              "count": 576,
              "outer": 6,
              "seed": 0
            },
            {
              "accuracy_pp": 55.208333333333336,
              "arm": "G0",
              "correct": 318,
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
              "accuracy_pp": 72.04861111111111,
              "arm": "J0",
              "correct": 415,
              "count": 576,
              "outer": 7,
              "seed": 0
            },
            {
              "accuracy_pp": 72.39583333333333,
              "arm": "G0",
              "correct": 417,
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
              "accuracy_pp": 66.31944444444444,
              "arm": "J0",
              "correct": 382,
              "count": 576,
              "outer": 8,
              "seed": 0
            },
            {
              "accuracy_pp": 71.35416666666667,
              "arm": "G0",
              "correct": 411,
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
              "accuracy_pp": 66.31944444444444,
              "arm": "J0",
              "correct": 382,
              "count": 576,
              "outer": 0,
              "seed": 4
            },
            {
              "accuracy_pp": 69.79166666666667,
              "arm": "G0",
              "correct": 402,
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
              "accuracy_pp": 42.1875,
              "arm": "G0",
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
              "accuracy_pp": 81.77083333333333,
              "arm": "J0",
              "correct": 471,
              "count": 576,
              "outer": 2,
              "seed": 4
            },
            {
              "accuracy_pp": 80.55555555555556,
              "arm": "G0",
              "correct": 464,
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
              "accuracy_pp": 50.0,
              "arm": "J0",
              "correct": 288,
              "count": 576,
              "outer": 3,
              "seed": 4
            },
            {
              "accuracy_pp": 49.13194444444444,
              "arm": "G0",
              "correct": 283,
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
              "accuracy_pp": 40.97222222222222,
              "arm": "J0",
              "correct": 236,
              "count": 576,
              "outer": 4,
              "seed": 4
            },
            {
              "accuracy_pp": 44.61805555555556,
              "arm": "G0",
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
              "accuracy_pp": 41.666666666666664,
              "arm": "J0",
              "correct": 240,
              "count": 576,
              "outer": 5,
              "seed": 4
            },
            {
              "accuracy_pp": 43.923611111111114,
              "arm": "G0",
              "correct": 253,
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
              "accuracy_pp": 61.979166666666664,
              "arm": "J0",
              "correct": 357,
              "count": 576,
              "outer": 6,
              "seed": 4
            },
            {
              "accuracy_pp": 59.02777777777778,
              "arm": "G0",
              "correct": 340,
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
              "accuracy_pp": 72.74305555555556,
              "arm": "J0",
              "correct": 419,
              "count": 576,
              "outer": 7,
              "seed": 4
            },
            {
              "accuracy_pp": 71.35416666666667,
              "arm": "G0",
              "correct": 411,
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
              "accuracy_pp": 69.27083333333333,
              "arm": "J0",
              "correct": 399,
              "count": 576,
              "outer": 8,
              "seed": 4
            },
            {
              "accuracy_pp": 69.27083333333333,
              "arm": "G0",
              "correct": 399,
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
        }
      },
      "decision_record": "ai4s/programs/mvcnet/research/mvcnet-ifnet-reference-rank1-001-development-v1_decision.yaml",
      "evidence_id": "AI4S-MVCNET-mvcnet-ifnet-reference-rank1-001-development-v1",
      "round_id": "mvcnet-ifnet-reference-rank1-001-development-v1",
      "run": {
        "bundle_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-bundle",
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 14.609,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 108,
        "recorded_at": "2026-11-28T05:59:24.487322+00:00",
        "round_id": "mvcnet-ifnet-reference-rank1-001-development-v1",
        "run_prefix": "2026-11-28_mvcnet_reference_rank1_001_lab10",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-11-28T05:59:31.832854+00:00",
            "result": {
              "action": "UPLOADED",
              "bundle_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-bundle",
              "contract_sha256": "e0d2e6281771ed4c075ed88e0a15b23c74e93d08a3929c472d59a23cac9b961c",
              "existing_files": 0,
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
              "source_manifest_sha256": "08f96c5f82b583e72eb0207e724b2c40b740b3ffcb3b1500ddfb1f532b646690",
              "verified_files": 56
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-11-28T05:59:35.434402+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-28T05:59:57.103291+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "science",
              "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "e0d2e6281771ed4c075ed88e0a15b23c74e93d08a3929c472d59a23cac9b961c",
                "execution_seconds": 17.75497317314148,
                "queue_seconds": 1.9134023189544678,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
                "transaction_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 19.668375492095947
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-11-28T11:03:20.815857+00:00",
            "result": {
              "action": "FETCH_VERIFY_INTAKE",
              "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
              "scientific_stop_boundary": "NEXT_SCIENTIFIC_DECISION",
              "timing": {
                "contract_sha256": "e0d2e6281771ed4c075ed88e0a15b23c74e93d08a3929c472d59a23cac9b961c",
                "execution_seconds": 15805.754630804062,
                "queue_seconds": 3.274580240249634,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
                "transaction_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-tx",
                "waiting_for_resources": false,
                "wall_seconds": 15809.029211044312
              }
            }
          }
        ]
      }
    }
  ],
  "continuation_history": [
    {
      "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l2_seed910_bundle_fixed1024_r1",
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "consumed_at": "2026-09-01T03:28:33.011537+00:00",
      "continuation_id": "mvcnet:mvcnet-lab10-three-round-fixed1024-20260831:slot-2",
      "contract": "research/mvcnet-lab10-l2-seed910-fixed1024-v1.0.yaml",
      "created_at": "2026-09-01T03:26:02.352786+00:00",
      "executor_id": "lab10",
      "frozen_at": "2026-09-01T03:27:18.782335+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l1-seed78-fixed1024-v1.0_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-lab10-l1-seed78-fixed1024-v1.0",
      "parent_round_id": "mvcnet-lab10-l1-seed78-fixed1024-v1.0",
      "parent_verified_intake": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_fixed1024_r1b-full-w1",
      "program_id": "mvcnet",
      "round_id": "mvcnet-lab10-l2-seed910-fixed1024-v1.0",
      "round_slot": 2,
      "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l2_seed910_fixed1024_r1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l3_seed1112_bundle_fixed1024_r1",
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "consumed_at": "2026-09-01T12:13:26.525251+00:00",
      "continuation_id": "mvcnet:mvcnet-lab10-three-round-fixed1024-20260831:slot-3",
      "contract": "research/mvcnet-lab10-l3-seed1112-fixed1024-v1.0.yaml",
      "created_at": "2026-09-01T12:10:11.359621+00:00",
      "executor_id": "lab10",
      "frozen_at": "2026-09-01T12:10:59.539889+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l2-seed910-fixed1024-v1.0_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-lab10-l2-seed910-fixed1024-v1.0",
      "parent_round_id": "mvcnet-lab10-l2-seed910-fixed1024-v1.0",
      "parent_verified_intake": "2026-09-01_ai4s_mvcnet_lab10_l2_seed910_fixed1024_r1-full-w1",
      "program_id": "mvcnet",
      "round_id": "mvcnet-lab10-l3-seed1112-fixed1024-v1.0",
      "round_slot": 3,
      "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l3_seed1112_fixed1024_r1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l4_seed1314_bundle_fixed1024_r1",
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "consumed_at": "2026-09-01T16:09:04.732950+00:00",
      "continuation_id": "mvcnet:mvcnet-lab10-three-round-fixed1024-20260831:slot-4",
      "contract": "research/mvcnet-lab10-l4-seed1314-fixed1024-v1.0.yaml",
      "created_at": "2026-09-01T16:08:11.743329+00:00",
      "executor_id": "lab10",
      "frozen_at": "2026-09-01T16:09:01.873963+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l3-seed1112-fixed1024-v1.0_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-lab10-l3-seed1112-fixed1024-v1.0",
      "parent_round_id": "mvcnet-lab10-l3-seed1112-fixed1024-v1.0",
      "parent_verified_intake": "2026-09-01_ai4s_mvcnet_lab10_l3_seed1112_fixed1024_r1-full-w1",
      "program_id": "mvcnet",
      "round_id": "mvcnet-lab10-l4-seed1314-fixed1024-v1.0",
      "round_slot": 4,
      "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l4_seed1314_fixed1024_r1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-01_ai4s_mvcnet_lab10_l5_seed1516_bundle_fixed1024_r1",
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "consumed_at": "2026-09-01T22:11:00.611170+00:00",
      "continuation_id": "mvcnet:mvcnet-lab10-three-round-fixed1024-20260831:slot-5",
      "contract": "research/mvcnet-lab10-l5-seed1516-fixed1024-v1.0.yaml",
      "created_at": "2026-09-01T20:11:41.403350+00:00",
      "executor_id": "lab10",
      "frozen_at": "2026-09-01T22:10:57.751739+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l4-seed1314-fixed1024-v1.0_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-lab10-l4-seed1314-fixed1024-v1.0",
      "parent_round_id": "mvcnet-lab10-l4-seed1314-fixed1024-v1.0",
      "parent_verified_intake": "2026-09-01_ai4s_mvcnet_lab10_l4_seed1314_fixed1024_r1-full-w1",
      "program_id": "mvcnet",
      "round_id": "mvcnet-lab10-l5-seed1516-fixed1024-v1.0",
      "round_slot": 5,
      "run_prefix": "2026-09-01_ai4s_mvcnet_lab10_l5_seed1516_fixed1024_r1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-02_ai4s_mvcnet_lab10_l6_seed1718_bundle_fixed1024_r1",
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "consumed_at": "2026-09-02T04:16:01.581269+00:00",
      "continuation_id": "mvcnet:mvcnet-lab10-three-round-fixed1024-20260831:slot-6",
      "contract": "research/mvcnet-lab10-l6-seed1718-fixed1024-v1.0.yaml",
      "created_at": "2026-09-02T04:15:09.169557+00:00",
      "executor_id": "lab10",
      "frozen_at": "2026-09-02T04:15:58.633356+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l5-seed1516-fixed1024-v1.0_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-lab10-l5-seed1516-fixed1024-v1.0",
      "parent_round_id": "mvcnet-lab10-l5-seed1516-fixed1024-v1.0",
      "parent_verified_intake": "2026-09-01_ai4s_mvcnet_lab10_l5_seed1516_fixed1024_r1-full-w1",
      "program_id": "mvcnet",
      "round_id": "mvcnet-lab10-l6-seed1718-fixed1024-v1.0",
      "round_slot": 6,
      "run_prefix": "2026-09-02_ai4s_mvcnet_lab10_l6_seed1718_fixed1024_r1",
      "status": "CONSUMED_BY_RUN"
    },
    {
      "bundle_id": "2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_bundle_fixed1024_r1",
      "campaign_id": "mvcnet-lab10-three-round-fixed1024-20260831",
      "consumed_at": "2026-09-02T08:15:38.984875+00:00",
      "continuation_id": "mvcnet:mvcnet-lab10-three-round-fixed1024-20260831:slot-7",
      "contract": "research/mvcnet-lab10-l7-seed1920-fixed1024-v1.0.yaml",
      "created_at": "2026-09-02T08:14:58.498902+00:00",
      "executor_id": "lab10",
      "frozen_at": "2026-09-02T08:15:36.334393+00:00",
      "parent_decision": "SCREEN_POSITIVE",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-lab10-l6-seed1718-fixed1024-v1.0_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-lab10-l6-seed1718-fixed1024-v1.0",
      "parent_round_id": "mvcnet-lab10-l6-seed1718-fixed1024-v1.0",
      "parent_verified_intake": "2026-09-02_ai4s_mvcnet_lab10_l6_seed1718_fixed1024_r1-full-w1",
      "program_id": "mvcnet",
      "round_id": "mvcnet-lab10-l7-seed1920-fixed1024-v1.0",
      "round_slot": 7,
      "run_prefix": "2026-09-02_ai4s_mvcnet_lab10_l7_seed1920_fixed1024_r1",
      "status": "CONSUMED_BY_RUN"
    }
  ],
  "discovery_history": [
    {
      "decision": "DISCOVER_NEXT",
      "execution_authorized": false,
      "next_design": {
        "arms": [
          "S0",
          "P0",
          "N0",
          "C0"
        ],
        "contrast": [
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "data_scope_id": "seven-source-fresh-split63-64-developmental",
        "intervention_id": "source-class-mean-alignment-v01",
        "next_stage": "source_class_mean_alignment_screen",
        "next_transition": "SCREEN_NEW",
        "question_id": "source-class-feature-centroid-alignment",
        "source_evidence_ids": [
          "AI4S-MVCNET-mvcnet-source-class-relation-screen-ccmu-r6",
          "AI4S-MVCNET-mvcnet-source-excluded-distillation-screen-lab10-r4",
          "AI4S-MVCNET-mvcnet-source-factorized-head-screen-lab10-r2",
          "AI4S-MVCNET-mvcnet-source-risk-screen-lab10-r1",
          "AI4S-MVCNET-mvcnet-cross-objective-collision-screen-lab10-r8",
          "AI4S-MVCNET-mvcnet-vogr-d0-diagnostic-lab10-r1"
        ]
      },
      "record": "ai4s/programs/mvcnet/research/discover_next_20261006/DESIGN_TRANSITION.json",
      "recorded_at": "2026-10-06T09:28:43.591618+00:00",
      "research_brief": {
        "path": "ai4s/programs/mvcnet/research/discover_next_20261006/RESEARCH_BRIEF.md",
        "sha256": "d0d8dbb792e3b8efd8b76169cbded97c93db9aac2918864a222208d8c1384d9a"
      },
      "run_action": "DESIGN_ONLY",
      "runtime_status_preserved": "COMPLETE_MAX_ROUNDS",
      "sha256": "e2ec1a8b50b278b5d90c4a89d81023e902dda747a862fe678a6ae8130c770fb1",
      "status": "DESIGN_READY"
    },
    {
      "decision": "DISCOVER_NEXT",
      "execution_authorized": false,
      "next_design": {
        "arms": [
          "S0",
          "P0",
          "N0",
          "C0"
        ],
        "contrast": [
          "P0-S0",
          "P0-N0",
          "P0-C0"
        ],
        "data_scope_id": "seven-source-prospective-split65-66-developmental",
        "eligible_for_training": false,
        "intervention_id": "source-disjoint-head-meta-v01",
        "method_originality": "known MLDG(FC)/ANIL mechanism; no originality claim",
        "next_stage": "source_disjoint_head_meta_screen",
        "next_transition": "SCREEN_NEW",
        "qualification_state": "INCOMPLETE; strict profile-source occupancy unproven",
        "question_id": "source-shared-readout-update-compatibility",
        "source_evidence_ids": [
          "AI4S-MVCNET-mvcnet-source-class-mean-alignment-screen-ccmu-r1",
          "AI4S-MVCNET-mvcnet-source-class-relation-screen-ccmu-r6",
          "AI4S-MVCNET-mvcnet-source-excluded-distillation-screen-lab10-r4",
          "AI4S-MVCNET-mvcnet-source-factorized-head-screen-lab10-r2",
          "AI4S-MVCNET-mvcnet-source-risk-screen-lab10-r1",
          "AI4S-MVCNET-mvcnet-vogr-d0-diagnostic-lab10-r1",
          "AI4S-MVCNET-mvcnet-conv-sam-screen-lab10-r7",
          "AI4S-MVCNET-mvcnet-srtd-d0-diagnostic-lab10-r1"
        ]
      },
      "record": "ai4s/programs/mvcnet/research/discover_next_20261007/DESIGN_TRANSITION.json",
      "recorded_at": "2026-10-07T10:49:47.296083+00:00",
      "research_brief": {
        "path": "ai4s/programs/mvcnet/research/discover_next_20261007/RESEARCH_BRIEF.md",
        "sha256": "8b12d317fb3432f2bcf6602d561ce2bdefb08ef5f7c7504d239d2360208e4ddf"
      },
      "run_action": "DESIGN_ONLY",
      "runtime_status_preserved": "COMPLETE_MAX_ROUNDS",
      "sha256": "259851ae3385f4244ca19a4405355d272ee6a42af33d72ac4e78a4dc2056e0b9",
      "status": "DESIGN_READY_QUALIFICATION_PENDING",
      "superseded_as_current_design_at": "2026-10-09T14:03:40.583171+08:00",
      "superseded_reason": "consumed by head-meta campaign and closed by r4; preserve historical qualification snapshot"
    }
  ],
  "discovery_transition": {
    "decision": "DISCOVER_NEXT",
    "execution_authorized": false,
    "governance_chain_id": "mvcnet-transaction-v3.1",
    "next_design": {
      "arms": [
        "S0",
        "N0",
        "P0",
        "C0"
      ],
      "data_scope_id": "prospective-seven-source-developmental-not-frozen",
      "eligible_for_training": false,
      "execution_authorized": false,
      "intervention_id": "augmentation-readout-separation-v01",
      "mechanism_contrasts": [
        "P0-N0",
        "P0-C0"
      ],
      "method_originality": "known-mechanism-adaptation; novelty-unverified",
      "primary_contrast": "P0-S0",
      "qualification_state": "synthetic_only; actual_runner_GPU_and_frozen_contract_pending",
      "question_id": "augmentation-specific-training-readout",
      "review_verdict": "ACCEPT_WITH_LIMITS"
    },
    "record": "ai4s/programs/mvcnet/research/discover_next_20261009/DESIGN_TRANSITION.json",
    "recorded_at": "2026-10-09T14:03:40.583171+08:00",
    "research_brief": {
      "path": "ai4s/programs/mvcnet/research/discover_next_20261009/RESEARCH_BRIEF.md",
      "sha256": "fc9529a2a4223cd65c9e4d3f90d986e79e26c85d5a04a03d9a5e1ff8817e4b34"
    },
    "run_action": "DESIGN_ONLY",
    "runtime_status_preserved": "COMPLETE_MAX_ROUNDS",
    "sha256": "b0b279bfddc7484bc0828df87e355423f84b23bea418cbfe585f55c6573d9cfd",
    "status": "DESIGN_READY_QUALIFICATION_PENDING"
  },
  "engineering_diagnosis": {
    "contract": "programs\\mvcnet\\research\\conv_sam\\gpu_diagnosis_r3_20260928\\diagnosis_contract.json",
    "role": "bounded_engineering_fault_reproduction_no_scientific_intake",
    "run_id": "2026-09-28_conv_sam_r3_gpu_trace",
    "status": "COMPLETE_TECHNICAL_ONLY",
    "verification": "programs\\mvcnet\\research\\conv_sam\\GPU_DIAGNOSIS_VERIFY.json"
  },
  "engineering_state_repairs": [
    {
      "at": "2026-09-28T09:51:15.225883+00:00",
      "budget_check": {
        "allowed": true,
        "estimate_basis": "runtime_anchor",
        "expected_training_hours": 7.0,
        "reason": "fits remaining budget",
        "remaining_hours": 8.372
      },
      "reason": "extend-campaign preserves BUDGET_EXHAUSTED despite sufficient newly authorized budget; restore already authorized r4 READY without resetting clocks or authorization"
    }
  ],
  "evidence_status": "campaign_active_with_archived_evidence_only_no_claim_release",
  "failed_attempts": [
    {
      "detail": "entrypoint exit=1",
      "failed_run_id": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1-check",
      "failed_status": "failed",
      "reason": "missing_DBConformer_import_dependency_before_P1_check",
      "recorded_at": "2026-08-30T05:40:20.694905+00:00",
      "repaired_by_bundle_id": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1_bundle_r1b",
      "repaired_by_run_prefix": "2026-08-30_ai4s_mvcnet_r01_seed56_b0p1b",
      "round_id": "mvcnet-r01-vcn-p1-new-seed-stability-v0.1"
    },
    {
      "detail": "entrypoint exit=1",
      "failed_run_id": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_fixed1024-full-w1",
      "failed_status": "failed",
      "reason": "scheduler-only_priority_field_violated_strict_frozen_task_schema_before_training",
      "recorded_at": "2026-08-31T17:18:35.803010+00:00",
      "repaired_by_bundle_id": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_bundle_fixed1024_r1b",
      "repaired_by_run_prefix": "2026-08-31_ai4s_mvcnet_lab10_l1_seed78_fixed1024_r1b",
      "round_id": "mvcnet-lab10-l1-seed78-fixed1024-v1.0"
    },
    {
      "evidence_status": "user_terminal_report_not_verified_intake",
      "failed_run_id": "2026-09-06_mvcnet_tapr_lab10_r2-full-w1",
      "failed_status": "FAILED_USER_REPORTED",
      "reason": "Adam post-step hook API unavailable",
      "recorded_at": "2026-09-06T10:27:20.341324+00:00",
      "repaired_by_bundle_id": "2026-09-06_mvcnet_tapr_lab10_bundle_r3",
      "repaired_by_run_prefix": "2026-09-06_mvcnet_tapr_lab10_r3",
      "round_id": "mvcnet-tapr-v0.1-screen-lab10-r1",
      "source_report_sha256": "21ee877f98f9878be48728f7167c0d1106849f8eb1357e5f0cee2b9155d7e37e"
    },
    {
      "failed_run_id": "2026-09-06_mvcnet_tapr_lab10_r3-full-w1",
      "reason": "resource queue consumed legacy 1800 second smoke timeout",
      "repaired_by_run_prefix": "2026-09-07_mvcnet_tapr_lab10_r4",
      "scientific_result": false,
      "source_ledger_sha256": "78f06469f4096fb5f18d7c29e8df6ebe310d2d87f7b3813f3929c8d69f35b9cb"
    },
    {
      "failed_run_id": "2026-09-07_mvcnet_tapr_lab10_r4-full-w1",
      "reason": "eight nonfinite parameter failures, all on GPU2",
      "repaired_by_run_prefix": "2026-09-07_mvcnet_tapr_lab10_r5",
      "source_archive_sha256": "8356e71140d237b4dcc7c7f478d9243239fca5928f4b7f5716f8594f335c3bef"
    },
    {
      "failed_run_id": "2026-09-07_mvcnet_vogr_lab10_r2-full-w1",
      "reason": "seven nonfinite parameter failures, all on GPU2",
      "repaired_by_run_prefix": "2026-09-07_mvcnet_vogr_lab10_r3",
      "source_archive_sha256": "e73a39c872bbd595770614da736c6a093c2e772ff03226d2c6738cac001812aa"
    },
    {
      "attempt_class": "user_authorized_scheduler_repair_before_any_fit",
      "failed_run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
      "failure_ledger_sha256": "32fb9bcef382f746672b28ad816ee5a0994e599d4969b9ae77fa157f12ae690e",
      "partial_artifacts_eligible": false,
      "reason": "whole-account lock blocked independent GPUs",
      "recorded_at": "2026-09-07T18:29:28.029390+00:00",
      "repaired_by_run_prefix": "2026-09-08_mvcnet_ocst_lab10_r2",
      "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1",
      "scientific_result": false,
      "source_run": {
        "bundle_id": "2026-09-08_mvcnet_ocst_lab10_bundle_r1",
        "dispatch_receipt": {
          "observed_at": "2026-09-07T17:56:46.319278+00:00",
          "path": "ai4s/_work/ocst_20260908/remote_launch/transaction_status.json",
          "sha256": "5c7935f528cf792fdb9b00b62774f32e06e50dd674fded64cebf3092a63b2f79",
          "type": "transaction_ledger"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.917,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-09-07T17:55:37.115168+00:00",
        "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1",
        "run_prefix": "2026-09-08_mvcnet_ocst_lab10_r1",
        "ssh_alias": "[REDACTED_MACHINE]",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-07T17:56:46.319278+00:00",
            "result": {
              "action": "UPLOADED_VERIFIED",
              "receipt": "ai4s/programs/mvcnet/research/OCST_UPLOAD_RECEIPT_20260908.json"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-07T17:56:46.319278+00:00",
            "result": {
              "action": "REMOTE_ACCEPTED",
              "pid": "[REDACTED_MACHINE]",
              "receipt_sha256": "5c7935f528cf792fdb9b00b62774f32e06e50dd674fded64cebf3092a63b2f79",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T17:56:47.797768+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d622d22d7074801c3ce8aea9c5cd28a912a51869edc8c1e200e1724baee65555",
                "execution_seconds": 3.4682133197784424,
                "queue_seconds": 44.229721546173096,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r1",
                "waiting_for_resources": true,
                "wall_seconds": 47.69793486595154
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T17:57:44.666044+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d622d22d7074801c3ce8aea9c5cd28a912a51869edc8c1e200e1724baee65555",
                "execution_seconds": 3.4672019481658936,
                "queue_seconds": 101.10063004493713,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r1",
                "waiting_for_resources": true,
                "wall_seconds": 104.56783199310303
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T18:07:03.281334+00:00",
            "result": {
              "action": "WAIT_FOR_RESOURCES",
              "node_id": "smoke",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "d622d22d7074801c3ce8aea9c5cd28a912a51869edc8c1e200e1724baee65555",
                "execution_seconds": 3.467240810394287,
                "queue_seconds": 659.9768307209015,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r1",
                "waiting_for_resources": true,
                "wall_seconds": 663.4440715312958
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T18:20:00.195072+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "smoke",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "d622d22d7074801c3ce8aea9c5cd28a912a51869edc8c1e200e1724baee65555",
                "execution_seconds": 3.4663069248199463,
                "queue_seconds": 1044.9685266017914,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r1",
                "waiting_for_resources": false,
                "wall_seconds": 1048.4348335266113
              }
            }
          }
        ]
      },
      "zero_fit_tasks_verified": true
    },
    {
      "attempt_class": "actual_execution_timeout_with_oom_partial_results",
      "failed_run_id": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1",
      "partial_failure_capture_sha256": "0742ff38c2a3fe77ebd4920c9eed22e00caef00a454c1eefec958a34553073f8",
      "partial_successes": 34,
      "recorded_at": "2026-09-08T04:46:53.855070+00:00",
      "repaired_by_run_prefix": "2026-09-08_mvcnet_ocst_lab10_r3",
      "scientific_result": false,
      "source_run": {
        "bundle_id": "2026-09-08_mvcnet_ocst_lab10_bundle_r2",
        "dispatch_receipt": {
          "observed_at": "2026-09-07T18:30:46.997431+00:00",
          "path": "ai4s/_work/ocst_20260908/r2_launch/transaction_status.json",
          "sha256": "8fa286812d4f2863ac39111570698b74811986f06829d23e33d4a45b987843e2",
          "type": "transaction_ledger"
        },
        "dispatch_status": "REMOTE_ACCEPTED",
        "estimated_training_hours": 7.917,
        "execution_mode": "user_managed",
        "executor_id": "lab10",
        "planned_units": 95,
        "recorded_at": "2026-09-07T18:29:28.029390+00:00",
        "retry_of": "2026-09-08_mvcnet_ocst_lab10_r1-full-w1",
        "round_id": "mvcnet-ocst-v0.1-screen-lab10-r1-repair1",
        "run_prefix": "2026-09-08_mvcnet_ocst_lab10_r2",
        "ssh_alias": "[REDACTED_MACHINE]",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-09-07T18:30:46.997431+00:00",
            "result": {
              "action": "UPLOADED_VERIFIED",
              "receipt": "ai4s/programs/mvcnet/research/OCST_R2_UPLOAD_RECEIPT_20260908.json"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-09-07T18:30:46.997431+00:00",
            "result": {
              "action": "REMOTE_ACCEPTED",
              "pid": "[REDACTED_MACHINE]",
              "receipt_sha256": "8fa286812d4f2863ac39111570698b74811986f06829d23e33d4a45b987843e2",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-07T18:31:38.377396+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "14c6996542e8156d2317325a109d21d9c8962c551d8a21983b2ccc861024081c",
                "execution_seconds": 83.15452837944031,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r2",
                "waiting_for_resources": false,
                "wall_seconds": 83.15452837944031
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-09-08T04:36:58.762237+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "screen",
              "run_id": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1",
              "status": "FAILED",
              "timing": {
                "contract_sha256": "14c6996542e8156d2317325a109d21d9c8962c551d8a21983b2ccc861024081c",
                "execution_seconds": 27072.47567009926,
                "queue_seconds": 3115.0681054592133,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-09-08_mvcnet_ocst_lab10_r2-full-w1",
                "transaction_id": "mvcnet-ocst-tx-20260908-r2",
                "waiting_for_resources": false,
                "wall_seconds": 30187.54377555847
              }
            }
          }
        ]
      }
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "engineering_reason": "User instructed no concurrency-count caps; planned scheduler-only interruption and immutable recovery",
      "failed_run_id": "2026-09-10_mvcnet_sfh_lab10_r1-full-w1",
      "partial_artifacts_eligible": "engineering_reuse_until_verified_intake",
      "recorded_at": "2026-09-10T07:34:27.292111+00:00",
      "recovery_manifest": "ai4s/programs/mvcnet/staging/2026-09-10_mvcnet_sfh_lab10_bundle_r2/recovery_source/manifest.json",
      "rerun_task_ids": [
        "N0-seed31-subject2",
        "S0-seed31-subject3",
        "P0-seed31-subject3",
        "N0-seed31-subject3",
        "S0-seed31-subject4",
        "P0-seed31-subject4",
        "N0-seed31-subject4",
        "S0-seed31-subject5",
        "P0-seed31-subject5",
        "N0-seed31-subject5",
        "S0-seed31-subject6",
        "P0-seed31-subject6",
        "N0-seed31-subject6",
        "S0-seed31-subject7",
        "P0-seed31-subject7",
        "N0-seed31-subject7",
        "S0-seed31-subject8",
        "P0-seed31-subject8",
        "N0-seed31-subject8",
        "S0-seed32-subject0",
        "P0-seed32-subject0",
        "N0-seed32-subject0",
        "S0-seed32-subject1",
        "P0-seed32-subject1",
        "N0-seed32-subject1",
        "S0-seed32-subject2",
        "P0-seed32-subject2",
        "N0-seed32-subject2",
        "S0-seed32-subject3",
        "P0-seed32-subject3",
        "N0-seed32-subject3",
        "S0-seed32-subject4",
        "P0-seed32-subject4",
        "N0-seed32-subject4",
        "S0-seed32-subject5",
        "P0-seed32-subject5",
        "N0-seed32-subject5",
        "S0-seed32-subject6",
        "P0-seed32-subject6",
        "N0-seed32-subject6",
        "S0-seed32-subject7",
        "P0-seed32-subject7",
        "N0-seed32-subject7",
        "S0-seed32-subject8",
        "P0-seed32-subject8",
        "N0-seed32-subject8"
      ],
      "reused_task_ids": [
        "N0-seed31-subject0",
        "N0-seed31-subject1",
        "P0-seed31-subject0",
        "P0-seed31-subject1",
        "P0-seed31-subject2",
        "S0-seed31-subject0",
        "S0-seed31-subject1",
        "S0-seed31-subject2"
      ],
      "round_id": "mvcnet-source-factorized-head-screen-lab10-r1",
      "scientific_decision": false,
      "source_ledger": "ai4s/programs/mvcnet/research/source_factorized_head/repair_r2/capture/run/transaction_status.json"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-energy-complementarity-20260910",
      "engineering_reason": "authorized energy device diagnostic recovery after nonfinite on GPU2 and scheduler family OOM",
      "failed_run_id": "2026-09-10_mvcnet_energy_lab10_r1-full-w1",
      "partial_artifacts_eligible": "engineering_reuse_until_verified_intake",
      "recorded_at": "2026-09-11T09:01:05.901282+00:00",
      "recovery_manifest": "ai4s/programs/mvcnet/staging/2026-09-11_mvcnet_energy_lab10_bundle_r2/recovery_source/manifest.json",
      "rerun_task_ids": [
        "C0-seed33-subject7",
        "C0-seed34-subject2",
        "C0-seed34-subject4",
        "S0-seed34-subject5",
        "S0-seed34-subject8",
        "C0-seed34-subject8",
        "P0-seed34-subject8"
      ],
      "reused_task_ids": [
        "C0-seed33-subject0",
        "C0-seed33-subject1",
        "C0-seed33-subject2",
        "C0-seed33-subject3",
        "C0-seed33-subject4",
        "C0-seed33-subject5",
        "C0-seed33-subject6",
        "C0-seed33-subject8",
        "C0-seed34-subject0",
        "C0-seed34-subject1",
        "C0-seed34-subject3",
        "C0-seed34-subject5",
        "C0-seed34-subject6",
        "C0-seed34-subject7",
        "P0-seed33-subject0",
        "P0-seed33-subject1",
        "P0-seed33-subject2",
        "P0-seed33-subject3",
        "P0-seed33-subject4",
        "P0-seed33-subject5",
        "P0-seed33-subject6",
        "P0-seed33-subject7",
        "P0-seed33-subject8",
        "P0-seed34-subject0",
        "P0-seed34-subject1",
        "P0-seed34-subject2",
        "P0-seed34-subject3",
        "P0-seed34-subject4",
        "P0-seed34-subject5",
        "P0-seed34-subject6",
        "P0-seed34-subject7",
        "S0-seed33-subject0",
        "S0-seed33-subject1",
        "S0-seed33-subject2",
        "S0-seed33-subject3",
        "S0-seed33-subject4",
        "S0-seed33-subject5",
        "S0-seed33-subject6",
        "S0-seed33-subject7",
        "S0-seed33-subject8",
        "S0-seed34-subject0",
        "S0-seed34-subject1",
        "S0-seed34-subject2",
        "S0-seed34-subject3",
        "S0-seed34-subject4",
        "S0-seed34-subject6",
        "S0-seed34-subject7"
      ],
      "round_id": "mvcnet-energy-complementarity-screen-lab10-r1",
      "scientific_decision": false,
      "source_ledger": "ai4s/programs/mvcnet/research/energy_complementarity/failure_capture_r1/run/transaction_status.json"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-energy-complementarity-20260910",
      "engineering_reason": "bounded operational retry after nonfinite diagnostic was not reproduced; original scheduler OOM remains; root cause unresolved",
      "failed_run_id": "2026-09-11_mvcnet_energy_lab10_r2-full-w1",
      "partial_artifacts_eligible": "engineering_reuse_until_verified_intake",
      "recorded_at": "2026-09-11T09:10:36.901187+00:00",
      "recovery_manifest": "ai4s/programs/mvcnet/staging/2026-09-11_mvcnet_energy_lab10_bundle_r3/recovery_source/manifest.json",
      "rerun_task_ids": [
        "C0-seed33-subject7",
        "C0-seed34-subject2",
        "C0-seed34-subject4",
        "S0-seed34-subject5",
        "S0-seed34-subject8",
        "C0-seed34-subject8",
        "P0-seed34-subject8"
      ],
      "reused_task_ids": [
        "C0-seed33-subject0",
        "C0-seed33-subject1",
        "C0-seed33-subject2",
        "C0-seed33-subject3",
        "C0-seed33-subject4",
        "C0-seed33-subject5",
        "C0-seed33-subject6",
        "C0-seed33-subject8",
        "C0-seed34-subject0",
        "C0-seed34-subject1",
        "C0-seed34-subject3",
        "C0-seed34-subject5",
        "C0-seed34-subject6",
        "C0-seed34-subject7",
        "P0-seed33-subject0",
        "P0-seed33-subject1",
        "P0-seed33-subject2",
        "P0-seed33-subject3",
        "P0-seed33-subject4",
        "P0-seed33-subject5",
        "P0-seed33-subject6",
        "P0-seed33-subject7",
        "P0-seed33-subject8",
        "P0-seed34-subject0",
        "P0-seed34-subject1",
        "P0-seed34-subject2",
        "P0-seed34-subject3",
        "P0-seed34-subject4",
        "P0-seed34-subject5",
        "P0-seed34-subject6",
        "P0-seed34-subject7",
        "S0-seed33-subject0",
        "S0-seed33-subject1",
        "S0-seed33-subject2",
        "S0-seed33-subject3",
        "S0-seed33-subject4",
        "S0-seed33-subject5",
        "S0-seed33-subject6",
        "S0-seed33-subject7",
        "S0-seed33-subject8",
        "S0-seed34-subject0",
        "S0-seed34-subject1",
        "S0-seed34-subject2",
        "S0-seed34-subject3",
        "S0-seed34-subject4",
        "S0-seed34-subject6",
        "S0-seed34-subject7"
      ],
      "round_id": "mvcnet-energy-complementarity-screen-lab10-r2",
      "scientific_decision": false,
      "source_ledger": "ai4s/programs/mvcnet/research/energy_complementarity/recovery_r2/capture/run/transaction_status.json"
    },
    {
      "attempt_class": "user_authorized_scheduler_repair_before_any_fit",
      "campaign_id": "mvcnet-source-selection-transfer-d0-20260911",
      "failed_run_id": "2026-09-11_mvcnet_sstd0_lab10_r1-full-w1",
      "failure_ledger_sha256": "3729b7e29f156e399a816bb4703c1cc045e54277e5428c05d499297b8d7034be",
      "partial_artifacts_eligible": false,
      "reason": "r1 smoke timeout during resource admission; no scientific task started",
      "recorded_at": "2026-09-12T08:37:33.697491+00:00",
      "repaired_by_bundle_id": "2026-09-12_mvcnet_sstd0_lab10_bundle_r2",
      "repaired_by_run_prefix": "2026-09-12_mvcnet_sstd0_lab10_r2",
      "round_id": "mvcnet-source-selection-transfer-d0-lab10-r1",
      "scientific_result": false,
      "source_contract_sha256": "6af4a173b4d12a501527c4c96b66efb679273f0f71a0c5a9cc594da5bd75f68e",
      "zero_fit_tasks_verified": true
    },
    {
      "reason": "USER_RESOURCE_REVISION_7680_TOTAL",
      "recorded_at": "2026-09-13T01:04:10.603742+00:00",
      "repaired_by_run_prefix": "2026-09-13_mvcnet_sstd0_lab10_r3",
      "round_id": "mvcnet-source-selection-transfer-d0-lab10-r2",
      "scientific_result": false,
      "source_contract_sha256": "444a985cef226691e75e0243814f5e7d6ca7f726098341c349ab46395f87423a",
      "source_ledger_sha256": "89bc814a3633e69991809e4148a41533e75093994a1c0824a10a22aed07807fa",
      "source_run_id": "2026-09-12_mvcnet_sstd0_lab10_r2-full-w1",
      "source_smoke_preserved": true,
      "stop_receipt_sha256": "6433b3d7942caf18ef8fdec6429784ad04f998b90940e3a4fffa55e101491810"
    },
    {
      "contract_sha256": "da616313867f0097ab132b750c141554ed09e125fa6ebc4cfad32bdb1f3fa2eb",
      "reason": "execution_budget_stop_extended_by_user",
      "recorded_at": "2026-09-13T05:29:12.094452+00:00",
      "remaining_tasks": [
        "train-seed36-outer0",
        "train-seed36-outer1",
        "train-seed36-outer2",
        "train-seed36-outer3",
        "train-seed36-outer4",
        "train-seed36-outer5",
        "train-seed36-outer6",
        "train-seed36-outer7",
        "train-seed36-outer8"
      ],
      "replacement_run_id": "2026-09-13_mvcnet_sstd0_lab10_r4-full-w1",
      "reused_tasks": [
        "train-seed35-outer0",
        "train-seed35-outer1",
        "train-seed35-outer2",
        "train-seed35-outer3",
        "train-seed35-outer4",
        "train-seed35-outer5",
        "train-seed35-outer6",
        "train-seed35-outer7",
        "train-seed35-outer8"
      ],
      "run_id": "2026-09-13_mvcnet_sstd0_lab10_r3-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-sstd0-tx-20260913-r3"
    },
    {
      "contract_sha256": "8e6bb74ef9c449bcf5d1599eb41574184421ea3a5d68156fe1e271033a644a60",
      "reason": "cuda_oom_bounded_missing_only_recovery",
      "recorded_at": "2026-09-13T16:55:24.642375+00:00",
      "remaining_tasks": [
        "train-seed36-outer4",
        "train-seed36-outer5",
        "train-seed36-outer6",
        "train-seed36-outer7",
        "train-seed36-outer8"
      ],
      "replacement_run_id": "2026-09-14_mvcnet_sstd0_lab10_r5-full-w1",
      "reused_tasks": [
        "train-seed35-outer5",
        "train-seed35-outer0",
        "train-seed35-outer3",
        "train-seed35-outer8",
        "train-seed35-outer1",
        "train-seed35-outer2",
        "train-seed35-outer4",
        "train-seed35-outer6",
        "train-seed35-outer7",
        "train-seed36-outer3",
        "train-seed36-outer0",
        "train-seed36-outer2",
        "train-seed36-outer1"
      ],
      "run_id": "2026-09-13_mvcnet_sstd0_lab10_r4-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-sstd0-tx-20260913-r4"
    },
    {
      "contract_sha256": "e2a567a1d84a706ebb04b028f1218ea269ea10375b78bbb0aeb2f11ded245ca3",
      "reason": "cuda_oom_bounded_missing_only_recovery",
      "recorded_at": "2026-09-14T04:22:27.235564+00:00",
      "remaining_tasks": [
        "train-seed36-outer8"
      ],
      "replacement_run_id": "2026-09-14_mvcnet_sstd0_lab10_r6-full-w1",
      "reused_tasks": [
        "train-seed35-outer5",
        "train-seed36-outer3",
        "train-seed35-outer0",
        "train-seed36-outer0",
        "train-seed35-outer3",
        "train-seed36-outer2",
        "train-seed35-outer8",
        "train-seed35-outer1",
        "train-seed36-outer1",
        "train-seed35-outer2",
        "train-seed35-outer4",
        "train-seed35-outer6",
        "train-seed35-outer7",
        "train-seed36-outer7",
        "train-seed36-outer4",
        "train-seed36-outer5",
        "train-seed36-outer6"
      ],
      "run_id": "2026-09-14_mvcnet_sstd0_lab10_r5-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-sstd0-tx-20260914-r5"
    },
    {
      "contract_sha256": "42e57443ab22da82bd686dbedae420bf404581ba2c2e1830b5229e0385cb6664",
      "reason": "cuda_oom_bounded_missing_only_recovery",
      "recorded_at": "2026-09-14T14:46:08.342240+00:00",
      "remaining_tasks": [
        "train-seed36-outer8"
      ],
      "replacement_run_id": "2026-09-14_mvcnet_sstd0_lab10_r7-full-w1",
      "reused_tasks": [
        "train-seed35-outer5",
        "train-seed36-outer3",
        "train-seed35-outer0",
        "train-seed36-outer0",
        "train-seed35-outer3",
        "train-seed36-outer2",
        "train-seed35-outer8",
        "train-seed35-outer1",
        "train-seed36-outer1",
        "train-seed35-outer2",
        "train-seed35-outer4",
        "train-seed35-outer6",
        "train-seed35-outer7",
        "train-seed36-outer7",
        "train-seed36-outer4",
        "train-seed36-outer5",
        "train-seed36-outer6"
      ],
      "run_id": "2026-09-14_mvcnet_sstd0_lab10_r6-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-sstd0-tx-20260914-r6"
    },
    {
      "contract_sha256": "f0f463f54dc2186e0bfca5d728c497f5a92f2adbe1fb546eeca44548de756242",
      "reason": "cross_check_model_return_interface_repair_no_training",
      "recorded_at": "2026-09-14T15:28:04.530324+00:00",
      "remaining_tasks": [],
      "replacement_run_id": "2026-09-14_mvcnet_sstd0_lab10_r8-full-w1",
      "reused_tasks": [
        "train-seed36-outer7",
        "train-seed35-outer5",
        "train-seed36-outer3",
        "train-seed35-outer0",
        "train-seed36-outer0",
        "train-seed35-outer3",
        "train-seed36-outer2",
        "train-seed36-outer4",
        "train-seed35-outer8",
        "train-seed35-outer1",
        "train-seed36-outer1",
        "train-seed35-outer2",
        "train-seed36-outer5",
        "train-seed35-outer4",
        "train-seed35-outer6",
        "train-seed35-outer7",
        "train-seed36-outer6",
        "train-seed36-outer8"
      ],
      "run_id": "2026-09-14_mvcnet_sstd0_lab10_r7-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-sstd0-tx-20260914-r7"
    },
    {
      "attempt_class": "planned_capacity_adjustment",
      "contract_sha256": "38b88c774f9c2349edbeb7e5b492c2ed81ccad420ee2456afeed2ed93696acb0",
      "evidence_ref": "ai4s/programs/mvcnet/research/shared_subnetwork/resource_r2/STOP_EVIDENCE.json",
      "reason": "user requests measured-peak plus512MiB reserve; no tasks started",
      "recorded_at": "2026-09-14T17:51:35.500045+00:00",
      "replacement_run_id": "2026-09-15_mvcnet_ssn_lab10_r2-full-w1",
      "run_id": "2026-09-15_mvcnet_ssn_lab10_r1-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-shared-subnetwork-tx-20260915-r1"
    },
    {
      "attempt_class": "bounded_oom_missing_only_recovery",
      "contract_sha256": "fd497d056abc9cdacb39fc6627d28dee3a1df632f16599c0d301bec43649d5d0",
      "evidence_ref": "ai4s/programs/mvcnet/research/shared_subnetwork/recovery_r3/SOURCE_EVIDENCE.json",
      "recorded_at": "2026-09-15T07:06:13.012664+00:00",
      "remaining_training": 42,
      "replacement_run_id": "2026-09-15_mvcnet_ssn_lab10_r3-full-w1",
      "reused_training": 12,
      "run_id": "2026-09-15_mvcnet_ssn_lab10_r2-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-shared-subnetwork-tx-20260915-r2"
    },
    {
      "attempt_class": "bounded_oom_missing_smoke_recovery",
      "contract_sha256": "836317c6e1e20d6cd7a1e3afbf63344f6073b0fb89c2a627a681190e006c0913",
      "evidence_ref": "ai4s/programs/mvcnet/research/contrastive_factorial/recovery_r2/SOURCE_EVIDENCE.json",
      "recorded_at": "2026-09-15T17:26:41.540391+00:00",
      "replacement_run_id": "2026-09-15_mvcnet_ccf_lab10_r2-full-w1",
      "run_id": "2026-09-15_mvcnet_ccf_lab10_r1-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r1"
    },
    {
      "attempt_class": "bounded_oom_missing_training_recovery",
      "contract_sha256": "5edad2203718cffb02d1cba9d5476388b7665ee4bfe750b58d6bc728fa304ec5",
      "evidence_ref": "ai4s/programs/mvcnet/research/contrastive_factorial/recovery_r3/SOURCE_EVIDENCE.json",
      "recorded_at": "2026-09-16T04:01:08.957913+00:00",
      "replacement_run_id": "2026-09-15_mvcnet_ccf_lab10_r3-full-w1",
      "run_id": "2026-09-15_mvcnet_ccf_lab10_r2a-full-w1",
      "scientific_result": false,
      "transaction_id": "mvcnet-contrastive-factorial-tx-20260915-r2a"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "7951dede3c3d527306f68c8bc38433ea18629e851efe35af71fc350f0b96107a",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r2/SOURCE_EVIDENCE.json",
      "recorded_at": "2026-09-17T05:44:14.865920+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r2-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r1-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 0,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r1"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "afa7aa5a347e5e5489dcd78ffd63d9fda87f4b869928750699c0ff26f98e9ebe",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r3/SOURCE_EVIDENCE.json",
      "recorded_at": "2026-09-17T05:51:26.834512+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r3-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r2-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 0,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r2"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "c28be88306c78e28ba4abdcb6cfbc6bc457ed2cd1bda88f060e1ec2dfb2a910c",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r4/SOURCE_EVIDENCE.json",
      "explicit_user_authorization_ref": "ai4s/programs/mvcnet/staging/2026-09-17_mvcnet_coc_lab10_bundle_r4/ai4s/programs/mvcnet/research/cross_objective_collision/AUTHORIZATION_R4.md",
      "explicit_user_authorization_sha256": "3ab071b65584650c799c9a3df5ad0f1a054b5dba384101dd169be12aa14b4750",
      "manual_extra_repair": true,
      "recorded_at": "2026-09-17T09:15:01.550182+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r4-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r3-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 2,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r3"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "287d183c7af5f8efc5698b3d8f67c37f22da5425d8268679afc0a1e00a1037d6",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r5/SOURCE_EVIDENCE.json",
      "explicit_user_authorization_ref": "ai4s/programs/mvcnet/staging/2026-09-17_mvcnet_coc_lab10_bundle_r5/ai4s/programs/mvcnet/research/cross_objective_collision/AUTHORIZATION_R5.md",
      "explicit_user_authorization_sha256": "a0a901235d26ef53bd1a0b08f27e54ca14f13492ea7c7fb1bd709463654e958e",
      "manual_extra_repair": true,
      "recorded_at": "2026-09-17T13:01:54.981952+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r5-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r4-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 5,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r4",
      "unstarted_tasks": 51
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "546201575438b4c1a2922996313bc01410a049b33971d952647e873528501199",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r6/SOURCE_EVIDENCE.json",
      "explicit_user_authorization_ref": "ai4s/programs/mvcnet/staging/2026-09-17_mvcnet_coc_lab10_bundle_r6/ai4s/programs/mvcnet/research/cross_objective_collision/AUTHORIZATION_R6.md",
      "explicit_user_authorization_sha256": "3885dc0b11099d4d1b7040f95284ec3ddd460df6d6e8d14947f575606e3d8470",
      "manual_extra_repair": true,
      "recorded_at": "2026-09-18T06:56:01.504893+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r6-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r5-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 13,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r5",
      "unstarted_tasks": 43
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "3bbdf04f094bb2dab326513a49939bc53fc8608c28a20ab3142cd12a76db5a3e",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r7/SOURCE_EVIDENCE.json",
      "explicit_user_authorization_ref": "ai4s/programs/mvcnet/staging/2026-09-17_mvcnet_coc_lab10_bundle_r7/ai4s/programs/mvcnet/research/cross_objective_collision/AUTHORIZATION_R7.md",
      "explicit_user_authorization_sha256": "044183dc4b92c48aac1a02f4c1ae0ff77c14429e4536467be3d87b9e6b52988e",
      "incomplete_train": 13,
      "manual_extra_repair": true,
      "recorded_at": "2026-09-19T02:21:52.463417+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r7-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r6-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 44,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r6"
    },
    {
      "attempt_class": "engineering_capacity_repair",
      "campaign_id": "mvcnet-cross-objective-collision-20260917",
      "contract_sha256": "2b4e683ca16eb48ead0a004ba5a3148b6622a67d0a44aa9a2c08b05949892028",
      "evidence_ref": "ai4s/programs/mvcnet/research/cross_objective_collision/recovery_r8/SOURCE_EVIDENCE.json",
      "explicit_user_authorization_ref": "ai4s/programs/mvcnet/staging/2026-09-17_mvcnet_coc_lab10_bundle_r8/ai4s/programs/mvcnet/research/cross_objective_collision/AUTHORIZATION_R8.md",
      "explicit_user_authorization_sha256": "d3ee0cfef52ca1669951610d25ca3efc662e24f4b66d4efe3e0164e55130a492",
      "incomplete_train": 1,
      "manual_extra_repair": true,
      "recorded_at": "2026-09-19T07:43:26.307662+00:00",
      "replacement_run_id": "2026-09-17_mvcnet_coc_lab10_r8-full-w1",
      "run_id": "2026-09-17_mvcnet_coc_lab10_r7-full-w1",
      "scientific_result": false,
      "scientific_tasks_rerun": 0,
      "successful_tasks": 56,
      "transaction_id": "mvcnet-cross-objective-collision-tx-20260917-r7"
    },
    {
      "attempt_class": "engineering_missing_check_recovery",
      "authorization_ref": "ai4s/programs/mvcnet/research/dual_atom/repair3/AUTHORIZATION.md",
      "campaign_id": "mvcnet-dual-atom-20260920",
      "reason": "one terminal cuDNN backend check failure, oom=false",
      "recorded_at": "2026-09-23T06:40:11.911056+00:00",
      "remaining_check": [
        "check-N0-seed44-outer8"
      ],
      "replacement_run_id": "2026-09-23_mvcnet_mv03_lab10_r3-full-w1",
      "reused_check": 71,
      "reused_train": 72,
      "scientific_result": false,
      "source_contract_sha256": "446be208600284dfc3041a39f603463770fd63f7020632f8a4ff421dc64dc0fe",
      "source_inventory_sha256": "ca7a223b4dd5f853baf8df22d6b1a8f571e27f82bd21a1e609df335ff370b15f",
      "source_ledger_sha256": "57dc5695ac7155132bd4dcc84749d3cecb6cadc0052b5f7dedae3d2393da3b33",
      "source_run_id": "2026-09-21_mvcnet_mv03_lab10_r2-full-w1",
      "source_transaction_id": "mvcnet-dual-atom-tx-20260921-r2"
    },
    {
      "attempt_class": "engineering_technical_telemetry_recovery",
      "authorization_ref": "ai4s/programs/mvcnet/research/dual_atom/repair4/AUTHORIZATION.md",
      "campaign_id": "mvcnet-dual-atom-20260920",
      "reason": "r3 smoke execution complete but P0/C0 full-process-memory telemetry absent",
      "recorded_at": "2026-09-24T01:40:59.804767+00:00",
      "remaining_check": [
        "check-N0-seed44-outer8"
      ],
      "replacement_run_id": "2026-09-24_mvcnet_mv03_lab10_r4-full-w1",
      "reused_check": 71,
      "reused_smoke": 4,
      "reused_train": 72,
      "scientific_result": false,
      "source_contract_sha256": "f2e720a332d8d995978f763066c55abc793100f2aaa1aa016bc33cf879b53f26",
      "source_inventory_sha256": "1733b6955353f05394cbbd6db62bdca936d0dd3233a70374235b8cf29c446cfb",
      "source_ledger_sha256": "ec6d998194b98c8801ad64d5e0299cffd69396a56f5dd660a337d59d44362824",
      "source_run_id": "2026-09-23_mvcnet_mv03_lab10_r3-full-w1",
      "source_transaction_id": "mvcnet-dual-atom-tx-20260923-r3"
    },
    {
      "attempt_class": "engineering_finite_cudnn_retry",
      "authorization_ref": "ai4s/programs/mvcnet/research/ordered_pool/repair2/AUTHORIZATION.md",
      "campaign_id": "mvcnet-ordered-pool-20260925",
      "recorded_at": "2026-09-25T15:11:53.754479+00:00",
      "remaining_check": 54,
      "remaining_train": [
        "train-P0-seed49-outer2"
      ],
      "replacement_run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r2-full-w1",
      "reused_train": 53,
      "scientific_result": false,
      "source_contract_sha256": "0c0f1a6c505b02d3273c60a67dc550739761e0c709e5a65257fbbb349822f92e",
      "source_inventory_sha256": "06ec9ce028fbf92fa3c50b2c8156f46652e685555396225d8873b22e5f47b35a",
      "source_run_id": "2026-09-25_mvcnet_ordered_pool_lab10_r1-full-w1",
      "source_transaction_id": "mvcnet-ordered-pool-tx-20260925-r1"
    },
    {
      "attempt_class": "engineering_post_training_seal_metadata_recovery",
      "authorization_ref": "ai4s/programs/mvcnet/research/source_head_meta/recovery_r3/AUTHORIZATION.md",
      "budget_clock_preserved": true,
      "campaign_id": "mvcnet-source-head-meta-20261008",
      "failed_run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
      "new_dispatch_training_equivalent_units": 9,
      "reason": "all 72 training fits succeeded; global seal metadata identity mismatch",
      "recorded_at": "2026-10-08T09:04:34.507439+00:00",
      "remaining_tasks": 73,
      "replacement_run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1",
      "reused_technical": 23,
      "reused_train": 72,
      "round_id": "mvcnet-source-head-meta-screen-ccmu-r2",
      "scientific_result": false,
      "source_contract_sha256": "f7708138f61aaf3eaae14dda54f3068ecb29844ba807d73d7de6c6ff04e9f32a",
      "source_ledger_sha256": "be285b3f5e70650ecd07eafd3500913865501e3f66c124a4bac4951c13f568b6",
      "source_manifest_sha256": "e055dfd5152b81a6a00c65a4f36906921aedd2efddfd6302fb1c5553aa804d22",
      "source_report_sha256": "f05a6bc75a28c68ca5cef1b92fb1953016b3b03a8a5b0e46f3a6734886a58c17",
      "source_run": {
        "bundle_id": "2026-10-08_mvcnet_source_head_meta_ccmu_bundle_r2",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 81,
        "estimated_training_hours": 16.667,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 168,
        "recorded_at": "2026-10-07T17:37:46.338352+00:00",
        "round_id": "mvcnet-source-head-meta-screen-ccmu-r2",
        "run_prefix": "2026-10-08_mvcnet_source_head_meta_ccmu_r2",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-07T17:38:26.550237+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-07T17:38:28.337643+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-07T17:38:41.338575+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "coverage",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f7708138f61aaf3eaae14dda54f3068ecb29844ba807d73d7de6c6ff04e9f32a",
                "execution_seconds": 12.424733638763428,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r2",
                "waiting_for_resources": false,
                "wall_seconds": 12.424733638763428
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-07T17:39:33.209612+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f7708138f61aaf3eaae14dda54f3068ecb29844ba807d73d7de6c6ff04e9f32a",
                "execution_seconds": 64.29411888122559,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r2",
                "waiting_for_resources": false,
                "wall_seconds": 64.29411888122559
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T02:46:27.130840+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f7708138f61aaf3eaae14dda54f3068ecb29844ba807d73d7de6c6ff04e9f32a",
                "execution_seconds": 32878.373270750046,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r2",
                "waiting_for_resources": false,
                "wall_seconds": 32878.373270750046
              }
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T05:31:12.906424+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "f7708138f61aaf3eaae14dda54f3068ecb29844ba807d73d7de6c6ff04e9f32a",
                "execution_seconds": 42764.852850437164,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r2",
                "waiting_for_resources": false,
                "wall_seconds": 42764.852850437164
              }
            }
          }
        ]
      }
    },
    {
      "attempt_class": "engineering_post_training_seal_metadata_recovery",
      "authorization_ref": "ai4s/programs/mvcnet/research/source_head_meta/recovery_r4/AUTHORIZATION.md",
      "budget_clock_preserved": true,
      "campaign_id": "mvcnet-source-head-meta-20261008",
      "failed_run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1",
      "new_dispatch_training_equivalent_units": 9,
      "reason": "r3 check entry rejected seal_summary missing operative/finite/shape/identity; all 72 failures occurred before check-data reads; GPU peak 0",
      "recorded_at": "2026-10-08T09:28:27.036406+00:00",
      "remaining_tasks": 73,
      "replacement_run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r4-full-w1",
      "reused_technical": 23,
      "reused_train": 72,
      "round_id": "mvcnet-source-head-meta-screen-ccmu-r3",
      "scientific_result": false,
      "source_contract_sha256": "6f24e4ee7de261ef02e8720dfa03e51019d28b000994f21fc2283c2bb97fe983",
      "source_ledger_sha256": "36951ac48d4ad59d84ba62b98ad78e2e6f6364c736de60dd338df4e39a5df179",
      "source_manifest_sha256": "5da3f176f4c049af586767bce033eda15a584c7dcf2b04cf60bc4e2289b3dfea",
      "source_report_sha256": "3518cef9b9a3967b36d076477c046620db45dfa43f688e7a5229dd2b1dee2534",
      "source_run": {
        "bundle_id": "2026-10-08_mvcnet_source_head_meta_ccmu_bundle_r3",
        "contract": "ai4s/programs/mvcnet/research/mvcnet-source-head-meta-screen-ccmu-r3.yaml",
        "contract_sha256": "6f24e4ee7de261ef02e8720dfa03e51019d28b000994f21fc2283c2bb97fe983",
        "dispatch_status": "REMOTE_ACCEPTED",
        "dispatch_units": 9,
        "estimated_training_hours": 1.852,
        "execution_mode": "ai4s_autopilot",
        "executor_id": "ccmu_lab",
        "planned_units": 168,
        "recorded_at": "2026-10-08T09:04:34.507439+00:00",
        "recovery_of": "2026-10-08_mvcnet_source_head_meta_ccmu_r2-full-w1",
        "round_id": "mvcnet-source-head-meta-screen-ccmu-r3",
        "run_prefix": "2026-10-08_mvcnet_source_head_meta_ccmu_r3",
        "transaction_operations": [
          {
            "operation": "upload",
            "recorded_at": "2026-10-08T09:05:27.949051+00:00",
            "result": {
              "action": "UPLOADED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1"
            }
          },
          {
            "operation": "launch",
            "recorded_at": "2026-10-08T09:05:29.730497+00:00",
            "result": {
              "action": "SUBMISSION_SENT_NOT_VERIFIED",
              "monitor_powershell": "[REDACTED_MACHINE]",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1"
            }
          },
          {
            "operation": "probe",
            "recorded_at": "2026-10-08T09:05:42.063651+00:00",
            "result": {
              "action": "RECONCILE_SAME_NODE",
              "node_id": "diagnostic",
              "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1",
              "status": "RUNNING",
              "timing": {
                "contract_sha256": "6f24e4ee7de261ef02e8720dfa03e51019d28b000994f21fc2283c2bb97fe983",
                "execution_seconds": 11.654631853103638,
                "queue_seconds": 0.0,
                "queue_time_policy": "exclude_resource_wait",
                "run_id": "2026-10-08_mvcnet_source_head_meta_ccmu_r3-full-w1",
                "transaction_id": "mvcnet-source-head-meta-tx-20261008-r3",
                "waiting_for_resources": false,
                "wall_seconds": 11.654631853103638
              }
            }
          }
        ]
      }
    }
  ],
  "frozen_modules": [
    {
      "evidence_record": "ai4s/programs/mvcnet/research/vbr-r1/execution/repair3/analysis_20261029/PRECISE_CLOSURE.json",
      "frozen_at": "2026-10-28T18:31:35.458828+00:00",
      "module_id": "vcn-view-batch-renorm-v01",
      "prohibited_follow_up": [
        "Extra seeds, reruns or gate changes to rescue the exact v01 configuration",
        "Post-result tuning or rebranding of the same v01 BRN schedule, clipping or recipe",
        "Promoting N0 or secondary contrasts to new training or paper Claim without separate authorization"
      ],
      "reason": "Frozen VBR-R1 screen NO_SIGNAL: P0-S0 +0.019290pp, one negative seed,4/9 positive subjects; close only this fixed developmental instance",
      "status": "FROZEN_EVIDENCE_ONLY"
    },
    {
      "evidence_record": "ai4s/programs/mvcnet/research/xsn-r1/execution/budget480/analysis_20261104/PRECISE_CLOSURE.json",
      "frozen_at": "2026-11-04T13:06:08.408292+00:00",
      "module_id": "xsn-cross-source-same-class-negative-protection-v01",
      "prohibited_follow_up": [
        "No extra seeds, changed thresholds, masks, temperature or rescue reruns for this exact configuration",
        "No automatic promotion of control arms, recombinations or ACM training"
      ],
      "reason": "Frozen XSN NO_SIGNAL: P0-S0 -0.192901pp, both seeds negative,5/9positive subjects; exact developmental instance only",
      "status": "FROZEN_EVIDENCE_ONLY"
    }
  ],
  "frozen_output_correction_boundary": {
    "basis": "user direction after verified SRTD-C1",
    "next_design": "ai4s/programs/mvcnet/research/source_factorized_head/PREPARATION.md",
    "preserve": "D0 labeled correctability; prior decisions and VCN-P1 anchor",
    "scope": "current SRTD frozen-logit donor/affine/condition/regularization search",
    "status": "PAUSED_BY_USER"
  },
  "handoff": {
    "completed_at": "2026-08-30",
    "confirmed_by_user": true,
    "note": "MVCNet evidence is imported as anchor, route boundary, or reference only; no proposed-research state transfers.",
    "record": "ai4s/archive/programs/mvcnet/research/PROPOSED_HANDOFF_2026-08-30.md"
  },
  "invalid_repair_authorizations": [
    {
      "authorized_at": "2026-09-03T01:07:08.856607+00:00",
      "reason": "v0.1 的 SCVA 投影未进入官方 MVCNet_LOSO 的优化器与 CVC 损失路径；v0.2 已以 release-owned IFNet 动态回归测试验证投影被优化且仅选择 CVC 表征。",
      "repair_contract": "ai4s/archive/programs/mvcnet/research/mvcnet-scva-cvc-s0p0-screen-lab10-v0.2.yaml",
      "repair_round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
      "source_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-scva-cvc-s0p0-screen-lab10-v0.1_decision.yaml",
      "source_round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.1",
      "source_run_id": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-09-09T16:30:48.401183+00:00",
      "reason": "CPU generator CUDA smoke mismatch; technical operative field and task data hash binding; no scientific tasks executed",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-srtd-t1-diagnostic-lab10-r2.yaml",
      "repair_round_id": "mvcnet-srtd-t1-diagnostic-lab10-r2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-srtd-t1-diagnostic-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-srtd-t1-diagnostic-lab10-r1",
      "source_run_id": "2026-09-10_mvcnet_srtd_t1_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-09-21T07:34:58.130254+00:00",
      "reason": "Fix duplicate reserve_mib in admission status merge before first GPU task; no scientific changes or reused partial outputs",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-dual-atom-screen-lab10-r2.yaml",
      "repair_round_id": "mvcnet-dual-atom-screen-lab10-r2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-dual-atom-screen-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-dual-atom-screen-lab10-r1",
      "source_run_id": "2026-09-21_mvcnet_mv03_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-09-28T06:13:29.441832+00:00",
      "reason": "Explicitly include unchanged dynamically loaded DBConformer source; validate final package initialization; zero science started in r1.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r2.yaml",
      "repair_round_id": "mvcnet-conv-sam-screen-lab10-r2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-conv-sam-screen-lab10-r1",
      "source_run_id": "2026-09-27_mvcnet_conv_sam_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-09-28T06:22:38.629197+00:00",
      "reason": "Second and final bounded engineering repair: retry exact cuDNN initialization failures per task with existing capped attempts/cooldowns; original algorithm and scientific matrix unchanged.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r3.yaml",
      "repair_round_id": "mvcnet-conv-sam-screen-lab10-r3",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r2_decision.yaml",
      "source_round_id": "mvcnet-conv-sam-screen-lab10-r2",
      "source_run_id": "2026-09-27_mvcnet_conv_sam_lab10_r2-full-w1"
    },
    {
      "authorized_at": "2026-09-28T08:57:49.289112+00:00",
      "reason": "User authorized one further engineering recovery after idle-GPU original-source replay passed; failed task retries require coordinated peers; add error-only step telemetry; no scientific design change.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r4.yaml",
      "repair_round_id": "mvcnet-conv-sam-screen-lab10-r4",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r3_decision.yaml",
      "source_round_id": "mvcnet-conv-sam-screen-lab10-r3",
      "source_run_id": "2026-09-27_mvcnet_conv_sam_lab10_r3-full-w1"
    },
    {
      "authorized_at": "2026-09-29T03:13:11.961502+00:00",
      "reason": "User-authorized engineering recovery after independent source-artifact qualification; six failures rerun from seed on alternative GPUs, mandatory finite 16-step production prefix; no nonfinite repair or automatic scientific error retry.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r5.yaml",
      "repair_round_id": "mvcnet-conv-sam-screen-lab10-r5",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r4_decision.yaml",
      "source_round_id": "mvcnet-conv-sam-screen-lab10-r4",
      "source_run_id": "2026-09-27_mvcnet_conv_sam_lab10_r4-full-w1"
    },
    {
      "authorized_at": "2026-09-29T08:32:04.144924+00:00",
      "reason": "User-authorized bounded technical repair: missing positive driver-memory sample retries only technical smoke up to existing three-attempt limit, never scientific training; preserve r4 qualified 48 plus six recovery tasks.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r6.yaml",
      "repair_round_id": "mvcnet-conv-sam-screen-lab10-r6",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r5_decision.yaml",
      "source_round_id": "mvcnet-conv-sam-screen-lab10-r5",
      "source_run_id": "2026-09-27_mvcnet_conv_sam_lab10_r5-full-w1"
    },
    {
      "authorized_at": "2026-09-29T13:32:17.147385+00:00",
      "reason": "User-authorized memory-only retry admission on any GPU. Preserve 54 training, 53 successful checks and original seal; execute only the remaining N0 check. Idle source scheduler intentionally stopped; no scientific change.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r7.yaml",
      "repair_round_id": "mvcnet-conv-sam-screen-lab10-r7",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-conv-sam-screen-lab10-r6_decision.yaml",
      "source_round_id": "mvcnet-conv-sam-screen-lab10-r6",
      "source_run_id": "2026-09-27_mvcnet_conv_sam_lab10_r6-full-w1"
    },
    {
      "authorized_at": "2026-09-30T04:20:48.738372+00:00",
      "reason": "User-authorized bounded engineering retry: preserve 32 independently validated teachers; four failed teachers restart from seed after a finite 16-update prefix. No loss, gradient, precision, data, GPU eligibility, or science matrix change.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r2.yaml",
      "repair_round_id": "mvcnet-source-excluded-distillation-screen-lab10-r2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-source-excluded-distillation-screen-lab10-r1",
      "source_run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-09-30T05:19:44.796843+00:00",
      "reason": "User confirmed temporary GPU2 exclusion after repeated finite-gradient failures. Rerun all three technical smokes, then retain the same qualified 32 R1 teachers and retry the same four. No hardware-fault claim; no algorithm or gradient-rule change.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r3.yaml",
      "repair_round_id": "mvcnet-source-excluded-distillation-screen-lab10-r3",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r2_decision.yaml",
      "source_round_id": "mvcnet-source-excluded-distillation-screen-lab10-r2",
      "source_run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r2-full-w1"
    },
    {
      "authorized_at": "2026-10-03T13:30:25.826480+00:00",
      "reason": "User requested repair and rerun; qualify 36 teachers, 18 caches, 53 students independently; retry only train-N0-seed59-outer1, then seal and all 54 checks. No scientific change or cuDNN-error automatic retry.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r4.yaml",
      "repair_round_id": "mvcnet-source-excluded-distillation-screen-lab10-r4",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-excluded-distillation-screen-lab10-r3_decision.yaml",
      "source_round_id": "mvcnet-source-excluded-distillation-screen-lab10-r3",
      "source_run_id": "2026-09-30_mvcnet_source_excluded_distillation_lab10_r3-full-w1"
    },
    {
      "authorized_at": "2026-10-05T13:17:43.794392+00:00",
      "reason": "Bounded technical repair of the R4 global Q-seal/node-result filename collision and Q file-hash comparison; same scientific screen, no reuse of R4 Q seal, students, checks, or GPU-smoke outputs.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-source-class-relation-screen-ccmu-r5.yaml",
      "repair_round_id": "mvcnet-source-class-relation-screen-ccmu-r5",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-class-relation-screen-ccmu-r4_decision.yaml",
      "source_round_id": "mvcnet-source-class-relation-screen-ccmu-r4",
      "source_run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r4-full-w1"
    },
    {
      "authorized_at": "2026-10-05T13:36:09.179082+00:00",
      "reason": "Final bounded technical repair of the R5 C0 GPU-smoke device-routing failure; same scientific screen and frozen matrix, with no reuse of any R5 Q/seal/smoke output or student/check artifact.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-source-class-relation-screen-ccmu-r6.yaml",
      "repair_round_id": "mvcnet-source-class-relation-screen-ccmu-r6",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-source-class-relation-screen-ccmu-r5_decision.yaml",
      "source_round_id": "mvcnet-source-class-relation-screen-ccmu-r5",
      "source_run_id": "2026-10-05_mvcnet_source_class_relation_ccmu_r5-full-w1"
    },
    {
      "authorized_at": "2026-10-11T05:20:28.358391+00:00",
      "reason": "same zero-training scientific screen; explicitly authorized new permissive deployment and storage-only memory repair",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1-permissive-redeploy1.yaml",
      "repair_round_id": "mvcnet-augmentation-readout-screen-lab10-r1-permissive-redeploy1",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-augmentation-readout-screen-lab10-r1",
      "source_run_id": "2026-10-09_mvcnet_augmentation_readout_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-10-17T05:17:47.373855+00:00",
      "reason": "2026-10-17 user-authorized engineering recovery: verified exact3 complete students; remaining69 original fits; original72 seal before72 checks; same campaign cumulative300h.",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair1.yaml",
      "repair_round_id": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair1",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1-permissive-redeploy1_decision.yaml",
      "source_round_id": "mvcnet-augmentation-readout-screen-lab10-r1-permissive-redeploy1",
      "source_run_id": "2026-10-11_mvcnet_augmentation_readout_lab10_r1_permissive_redeploy1-full-w1"
    },
    {
      "authorized_at": "2026-10-18T04:11:15.478517+00:00",
      "reason": "2026-10-18 authorized shared-GPU admission margin and bounded OOM recovery; original three students and scientific configuration preserved",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2.yaml",
      "repair_round_id": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair1_decision.yaml",
      "source_round_id": "mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair1",
      "source_run_id": "2026-10-17_mvcnet_augmentation_readout_lab10_r1_resume69_repair1-full-w1"
    },
    {
      "authorized_at": "2026-10-30T04:05:05.300245+00:00",
      "reason": "Isolated lazy package exports prevent unrelated DBConformer eager import; no scientific task started in failed Run",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-xsn-r1-screen-lab10-r1-repair1.yaml",
      "repair_round_id": "mvcnet-xsn-r1-screen-lab10-r1-repair1",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-xsn-r1-screen-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-xsn-r1-screen-lab10-r1",
      "source_run_id": "2026-10-29_mvcnet_xsn_r1_lab10_r1-full-w1"
    },
    {
      "authorized_at": "2026-10-30T20:52:22.854460+00:00",
      "reason": "Explicit cumulative480h extension after frozen cost stop; reuse ten remotely verified completed technical qualifications, same science and fresh scientific fits only",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-xsn-r1-screen-lab10-r1-budget480.yaml",
      "repair_round_id": "mvcnet-xsn-r1-screen-lab10-r1-budget480",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-xsn-r1-screen-lab10-r1-repair1_decision.yaml",
      "source_round_id": "mvcnet-xsn-r1-screen-lab10-r1-repair1",
      "source_run_id": "2026-10-30_mvcnet_xsn_r1_lab10_r1_repair1-full-w1"
    },
    {
      "authorized_at": "2026-11-04T15:41:10.382694+00:00",
      "budget_reset": false,
      "queue_credit_seconds": 0,
      "reason": "non-operative implementation repair",
      "repair_authorization_ref": "ai4s/programs/mvcnet/research/acm-r1/execution/repair1/AUTHORIZATION.json",
      "repair_authorization_sha256": "401affd9c0ff0ca62878e3ca440f43d88e206e4de03cd3cf2b8d65077ff82cfe",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-acm-r1-screen-lab10-r1-repair1.yaml",
      "repair_contract_sha256": "c67eb18a7d6915267d13dab4380e4a743fd0d47dc0c8216ec1c3b77c86478286",
      "repair_round_id": "mvcnet-acm-r1-screen-lab10-r1-repair1",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-acm-r1-screen-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-acm-r1-screen-lab10-r1",
      "source_run_id": "2026-11-04_mvcnet_acm_r1_lab10_r1-full-w1",
      "stopped_time_credit": false
    },
    {
      "authorized_at": "2026-11-05T13:14:49.287654+00:00",
      "budget_reset": false,
      "provenance_correction": {
        "backup_path": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/packfix1/PROVENANCE_CORRECTION_BEFORE.json",
        "contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
        "corrected_at": "2026-11-05T13:20:09.233911+00:00",
        "correction_id": "acm-r1-checkrepair2-packfix1-authref-20261105",
        "new_authorization_ref": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/packfix1/AUTHORIZATION.json",
        "new_authorization_sha256": "1f366eb28c3b316cd442dc33d06d78661abe2e18157a20278b9fd34d73475f6a",
        "old_authorization_ref": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/AUTHORIZATION.json",
        "old_authorization_sha256": "1f366eb28c3b316cd442dc33d06d78661abe2e18157a20278b9fd34d73475f6a",
        "reason": "packfix1 AUTH SHA was recorded with the pre-packfix1 path"
      },
      "queue_cred
```
