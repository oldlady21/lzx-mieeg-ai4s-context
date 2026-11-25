# State 阅读分段 2

完整脱敏文件：`ai4s/programs/mvcnet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`e4bbd71f1b3f7c159d00b49a944954388e7ce38af1dbe9ad75ac1ca7064ce86b`。UTF-8 字节范围：[500000, 804996) / 804996。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
ed_accuracy_gains_pp": [
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
      "queue_credit_seconds": 0,
      "reason": "non-operative implementation repair",
      "repair_authorization_ref": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/packfix1/AUTHORIZATION.json",
      "repair_authorization_sha256": "1f366eb28c3b316cd442dc33d06d78661abe2e18157a20278b9fd34d73475f6a",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-acm-r1-screen-lab10-checkrepair2.yaml",
      "repair_contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
      "repair_round_id": "mvcnet-acm-r1-screen-lab10-checkrepair2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-acm-r1-screen-lab10-r1-repair1_decision.yaml",
      "source_round_id": "mvcnet-acm-r1-screen-lab10-r1-repair1",
      "source_run_id": "2026-11-04_mvcnet_acm_r1_lab10_r1_repair1-full-w1",
      "stopped_time_credit": false
    },
    {
      "authorized_at": "2026-11-06T05:39:46.331383+00:00",
      "reason": "Python 3.9 Path.write_text compatibility before any scheduler task dispatch",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1.yaml",
      "repair_round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1_decision.yaml",
      "source_round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1",
      "source_run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1-full-w1"
    },
    {
      "authorized_at": "2026-11-08T11:29:07.476976+00:00",
      "reason": "reuse 36 immutable fits; restore original qualification definitions and run only sealed checks",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix1.yaml",
      "repair_round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix1",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1_decision.yaml",
      "source_round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1",
      "source_run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1-full-w1"
    },
    {
      "authorized_at": "2026-11-08T11:33:19.088227+00:00",
      "reason": "check-only 3h Transaction cap; same original 36 fits, matrix and stopped accounting",
      "repair_contract": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2.yaml",
      "repair_round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix2",
      "source_decision_record": "ai4s/programs/mvcnet/research/mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix1_decision.yaml",
      "source_round_id": "mvcnet-cue-aligned-two-arm-full-lab10-r1-py39fix1-sealfix1",
      "source_run_id": "2026-11-06_mvcnet_cue4_b0_ce_lab10_full_r1_py39fix1_sealfix1-full-w1"
    }
  ],
  "last_decision": {
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
  "last_remote_verified_analysis": {
    "analysis_report": "ai4s/programs/mvcnet/research/augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/REPORT.md",
    "claim_release": "none",
    "decision": "NO_SIGNAL",
    "decision_record": "ai4s/programs/mvcnet/research/augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/DECISION.json",
    "evidence_id": "AI4S-MVCNET-mvcnet-augmentation-readout-screen-lab10-r1-resume69-repair2",
    "registered_at": "2026-10-23T18:51:33.808954+00:00",
    "replayed_checks": 72
  },
  "last_remote_verified_intake": {
    "artifact_manifest_sha256": "22ed7b9b61f5514c2178e88cef65b6d137f4604ad4de62c34ab829294fb7e9f3",
    "local_full_intake": false,
    "received_results": "ai4s/programs/mvcnet/research/augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/downloaded_results",
    "remote_run_root": "[REDACTED_MACHINE]",
    "run_id": "2026-10-18_mvcnet_augmentation_readout_lab10_r1_resume69_repair2-full-w1",
    "verification_record": "ai4s/programs/mvcnet/research/augmentation_readout/repair_resume69_oom_20261018/analysis_20261024/REMOTE_FULL_VERIFICATION.json",
    "verified": true,
    "verified_at": "2026-10-23T18:51:33.808954+00:00"
  },
  "last_round_evidence": {
    "decision_record": "ai4s/programs/mvcnet/research/mvcnet-reflectcvc-001-development-v1_decision.yaml",
    "evidence_id": "AI4S-MVCNET-mvcnet-reflectcvc-001-development-v1",
    "role": "exact_negative_boundary"
  },
  "last_run_reconciliation": "ai4s/programs/mvcnet/research/acm-r1/factorial/CONTROLLER_RECONCILIATION_20261116.json",
  "last_verified_intake": {
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
  "last_verified_preflight": {
    "bundle_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-bundle",
    "contract": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/QUALIFICATION_CONTRACT.json",
    "evidence_role": "engineering_preflight_only_no_performance_claim",
    "executor_id": "lab10",
    "intake": {
      "analysis_receipt_sha256": "17ff181fda91b4c21da381cf7c91b2992c6918dab1bb744aeea0184a37e2d42c",
      "artifact_manifest_sha256": "954c42e83fa37da2a85ab0ead642c06c1546ad1e048758542cb5d47dbc6f3e54",
      "contract_sha256": "bf546927f022abe901122fc048c4144c09d352b31596db323e0111dcd7e18e30",
      "full_payload_local": false,
      "intake_path": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/qualification_intake",
      "intake_scope": "analysis_v1",
      "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-full-w1",
      "run_status": "complete",
      "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-tx",
      "transfer_bytes": 55993,
      "verified": true
    },
    "interpretation_boundary": "Runtime-capacity evidence only; it is not a B0 comparison, candidate result, or paper claim.",
    "operation_id": "mvcnet:engineering_preflight:2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-full-w1",
    "preflight": {
      "artifact": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/qualification_intake/qualification_result.json",
      "artifact_sha256": "b027923e38a2b5d6ae376c4f326616a47f05a598d6ab1715a2e0a1439ac08c59",
      "peak_memory_observed_mib": 7621,
      "peak_memory_status": "three_arm_source_only_five_epoch_observed",
      "peak_mib_by_arm": {
        "D0": 7621,
        "I0": 7621,
        "S0": 7619
      },
      "profile_kind": "three_arm_source_only_five_epoch"
    },
    "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-full-w1"
  },
  "operation_history": [
    {
      "bundle_id": "2026-08-31_ai4s_mvcnet_r03_lab10_b0_preflight_bundle_r14_basedir_retry",
      "contract": "ai4s/archive/programs/mvcnet/research/mvcnet-r03-vcn-p1-lab10-seed78-independent-confirmation-v1.1.yaml",
      "executor_id": "lab10",
      "expected_artifact": "b0_preflight.json",
      "intake": {
        "intake_path": "results/logs/remote/2026-08-31_ai4s_mvcnet_r03_lab10_b0_preflight-r14-basedir-retry",
        "run_id": "2026-08-31_ai4s_mvcnet_r03_lab10_b0_preflight-r14-basedir-retry",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-08-31T14:47:26.736270+00:00"
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-08-31_ai4s_mvcnet_r03_lab10_b0_preflight-r14-basedir-retry",
      "preflight": {
        "artifact": "results/logs/remote/2026-08-31_ai4s_mvcnet_r03_lab10_b0_preflight-r14-basedir-retry/b0_preflight.json",
        "environment_fingerprint": "617ff7880890f57f005ed5dbf1cbc67350538a5fe87e87baabcb37abef04d830",
        "peak_memory_observed_mib": 7727,
        "peak_memory_status": "pid_delta_observed_during_full_100_epoch_B0"
      },
      "registered_at": "2026-08-31T14:49:30.572733+00:00",
      "remote_completion": "adopted_after_controller_gap_no_intake_asserted",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": true,
      "resume_status": "READY_NEXT_ROUND",
      "run_id": "2026-08-31_ai4s_mvcnet_r03_lab10_b0_preflight-r14-basedir-retry",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-08-31T14:49:42.964638+00:00"
    },
    {
      "bundle_id": "2026-08-31_ai4s_mvcnet_r03_lab10_p1_preflight_bundle_r1_fixed1024",
      "contract": "ai4s/archive/programs/mvcnet/research/mvcnet-r03-vcn-p1-lab10-p1-preflight-v1.2.yaml",
      "executor_id": "lab10",
      "expected_artifact": "p1_preflight.json",
      "intake": {
        "intake_path": "results/logs/remote/2026-08-31_ai4s_mvcnet_r03_lab10_p1_preflight-r1-fixed1024",
        "run_id": "2026-08-31_ai4s_mvcnet_r03_lab10_p1_preflight-r1-fixed1024",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-08-31T16:03:48.663779+00:00"
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-08-31_ai4s_mvcnet_r03_lab10_p1_preflight-r1-fixed1024",
      "preflight": {
        "arm": "P1",
        "artifact": "results/logs/remote/2026-08-31_ai4s_mvcnet_r03_lab10_p1_preflight-r1-fixed1024/p1_preflight.json",
        "environment_fingerprint": "617ff7880890f57f005ed5dbf1cbc67350538a5fe87e87baabcb37abef04d830",
        "peak_memory_observed_mib": 7723,
        "peak_memory_status": "pid_delta_observed_during_full_100_epoch_P1"
      },
      "registered_at": "2026-08-31T15:27:29.783436+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": true,
      "resume_status": "READY_NEXT_ROUND",
      "run_id": "2026-08-31_ai4s_mvcnet_r03_lab10_p1_preflight-r1-fixed1024",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-08-31T16:04:03.567877+00:00"
    },
    {
      "bundle_id": "2026-09-03_ai4s_mvcnet_scva_p0_preflight_bundle_lab10_r1",
      "contract": "ai4s/archive/programs/mvcnet/research/mvcnet-scva-cvc-p0-preflight-lab10-v0.1.yaml",
      "executor_id": "lab10",
      "expected_artifact": "p0_preflight.json",
      "intake": {
        "intake_path": "results/logs/remote/2026-09-03_ai4s_mvcnet_scva_p0_preflight_lab10_r1",
        "run_id": "2026-09-03_ai4s_mvcnet_scva_p0_preflight_lab10_r1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-02T19:58:57.056274+00:00"
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-09-03_ai4s_mvcnet_scva_p0_preflight_lab10_r1",
      "preflight": {
        "arm": "P0",
        "artifact": "results/logs/remote/2026-09-03_ai4s_mvcnet_scva_p0_preflight_lab10_r1/p0_preflight.json",
        "environment_fingerprint": "617ff7880890f57f005ed5dbf1cbc67350538a5fe87e87baabcb37abef04d830",
        "peak_memory_observed_mib": 7723,
        "peak_memory_status": "pid_delta_observed_during_full_100_epoch_P0"
      },
      "registered_at": "2026-09-02T18:51:23.815425+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-09-03_ai4s_mvcnet_scva_p0_preflight_lab10_r1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-09-02T19:59:01.683294+00:00"
    },
    {
      "bundle_id": "2026-09-03_ai4s_mvcnet_vogd_v0_1_preflight_bundle_lab10_r1",
      "closed_at": "2026-09-05T10:41:17.496197+00:00",
      "closure_reason": "user authorized closing old VOGD active_operation for Transaction v2 admission",
      "contract": "ai4s/archive/programs/mvcnet/research/mvcnet-vogd-v0.1-lab10-preflight.yaml",
      "executor_id": "lab10",
      "expected_artifact": "vogd_preflight.json",
      "intake_verified": false,
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-09-03_ai4s_mvcnet_vogd_v0_1_preflight_lab10_r1-pilot-w1",
      "registered_at": "2026-09-03T14:33:48.373561+00:00",
      "remote_process_status": "NOT_OBSERVED_BY_THIS_CLOSURE",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY_NEXT_ROUND",
      "run_id": "2026-09-03_ai4s_mvcnet_vogd_v0_1_preflight_lab10_r1-pilot-w1",
      "scientific_interpretation": "NONE; no success, negative boundary or claim inferred",
      "status": "CLOSED_BY_USER"
    },
    {
      "bundle_id": "2026-11-20_mvcnet_block_exchange_001_lab10_qualification_r2-bundle",
      "contract": "ai4s/programs/mvcnet/research/cross_subject_block_exchange_20261120/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "4be1ba2a866b39ddbe3674bcaa6c5938b0273b70cc78eed63d066b8d79339594",
        "artifact_manifest_sha256": "6aaa3015eedfbee3ad5dd649851f4c3a104d889f5176a8cccd57826b308e64f5",
        "contract_sha256": "617926b42b2e2eb55cf03e2efeb58abe847619aade39ac1bdfcc4019c9eeca8b",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/cross_subject_block_exchange_20261120/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10_qualification_r2-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-20_mvcnet_block_exchange_001_lab10_qualification_r2-tx",
        "transfer_bytes": 56300,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-20_mvcnet_block_exchange_001_lab10_qualification_r2-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/cross_subject_block_exchange_20261120/qualification_intake/qualification_result.json",
        "artifact_sha256": "69b275613d3926d8f1239828ee3388b9fa27de68f0c04286f969a925377ea737",
        "peak_memory_observed_mib": 7619,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "S0": 7619,
          "W0": 7619,
          "X0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-20T15:54:03.323043+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-20_mvcnet_block_exchange_001_lab10_qualification_r2-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-20T16:39:32.978469+00:00"
    },
    {
      "bundle_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/envelope_preserving_rotation_20261122/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "71c17e2123a3ff5fae173348c0588ea682f6e12c64d37eb94b996d28ef90eead",
        "artifact_manifest_sha256": "262dc26b0e7fb3c9152214137b85a72ecc9a46360506edf514e81be615ea2363",
        "contract_sha256": "c8293baa7e81a12d1cb86ac8edd36d57b08e1322dcf698eb25c980caba657992",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/envelope_preserving_rotation_20261122/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10_qualification-tx",
        "transfer_bytes": 56255,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-22_mvcnet_envelope_rotation_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/envelope_preserving_rotation_20261122/qualification_intake/qualification_result.json",
        "artifact_sha256": "2d74d1e822fcab82385f1990f4b8d121ab9b0bd03c916208c029227f6cebde96",
        "peak_memory_observed_mib": 7631,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "C0": 7631,
          "I0": 7631,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-21T17:25:25.769844+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-22_mvcnet_envelope_rotation_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-21T17:29:20.654058+00:00"
    },
    {
      "bundle_id": "2026-11-22_mvcnet_rate125_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/physical_time_pooling_125hz_20261122/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "0265c27c9607a71db5313c10cc449ccff03060b6bd30dcf8804f78c8726c555a",
        "artifact_manifest_sha256": "c425eb72f5c3720f8a94f28256b1989220f5f3f3f02462e5cb9ac98aafb03d65",
        "contract_sha256": "3fa61783780822ff67495f39d082f06d20db908ad8d322ee4d6476383e7c3e4b",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/physical_time_pooling_125hz_20261122/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_rate125_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_rate125_001_lab10_qualification-tx",
        "transfer_bytes": 55922,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-22_mvcnet_rate125_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/physical_time_pooling_125hz_20261122/qualification_intake/qualification_result.json",
        "artifact_sha256": "85040499532ab7e1537e395d3e56a419f3164e94b3b2ada4bd9ca339fe2beee6",
        "peak_memory_observed_mib": 7619,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "A125": 6151,
          "S0": 7619,
          "T125": 6111
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-22T09:24:38.602634+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-22_mvcnet_rate125_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-22T09:27:27.300840+00:00"
    },
    {
      "bundle_id": "2026-11-22_mvcnet_auxrate_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/asymmetric_auxiliary_rate_20261122/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "843596ae743e33d7fd2b73cee3bc8ec3e75d62515053cb92efb55bdc4ae8e2e9",
        "artifact_manifest_sha256": "65279220228850b8852ff07b703c491e3b00dfe4ad009f70b85c003e00b3cfcf",
        "contract_sha256": "d3ed266514baaa75fda1ea401cc763c8f13ae875a7a3c475b81dee21021afc81",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/asymmetric_auxiliary_rate_20261122/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_auxrate_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_auxrate_001_lab10_qualification-tx",
        "transfer_bytes": 55902,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-22_mvcnet_auxrate_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/asymmetric_auxiliary_rate_20261122/qualification_intake/qualification_result.json",
        "artifact_sha256": "6b18a57729d56764be6d85941cc34dc5fb369e0845864620e7b4f3720d44895a",
        "peak_memory_observed_mib": 7619,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "F125": 6315,
          "L500": 6315,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-22T15:04:04.681461+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-22_mvcnet_auxrate_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-22T15:13:58.228615+00:00"
    },
    {
      "bundle_id": "2026-11-22_mvcnet_auxspace_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/spatial_auxiliary_basis_20261122/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "ce88b718c2257a2fd873048f55228c0c643ab4e09062073267af05d32a42612e",
        "artifact_manifest_sha256": "17341fdb08051901103bbc8980d7c21f2a3755d87d23b834a93496872592e080",
        "contract_sha256": "a3d6e73eda27fc10d9cf2321aa31499ec6e7c351c56483cdefef3e757a80071d",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/spatial_auxiliary_basis_20261122/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-22_mvcnet_auxspace_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-22_mvcnet_auxspace_001_lab10_qualification-tx",
        "transfer_bytes": 55842,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-22_mvcnet_auxspace_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/spatial_auxiliary_basis_20261122/qualification_intake/qualification_result.json",
        "artifact_sha256": "59801441ba35e956d7fbb6c90f8beb399d8b8f1f49bbdb236e0097a16416899c",
        "peak_memory_observed_mib": 7619,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "J8": 6287,
          "P8": 6287,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-22T15:23:02.905983+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-22_mvcnet_auxspace_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-22T15:26:11.168509+00:00"
    },
    {
      "bundle_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/cvc_reflection_axis_20261123/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "7f86999f1486a6aad2a28ff5a620f879ef4ea5b1bb5b01090e09406f2d4cadf2",
        "artifact_manifest_sha256": "5d1bcbf3bd0a0956c7cb49ea0d9c0509795a19fb93b999528ccad66e1cf2e751",
        "contract_sha256": "d65f929f0bb36d51225846d878c6e14cd99ea8751ac6eea03991dec4b6006fdc",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/cvc_reflection_axis_20261123/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_qualification-tx",
        "transfer_bytes": 56007,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-23_mvcnet_reflectcvc_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/cvc_reflection_axis_20261123/qualification_intake/qualification_result.json",
        "artifact_sha256": "6687de6410e50b48358f0ac14af2100e4b1d23e50f522ea9e38e6ee15e13d977",
        "peak_memory_observed_mib": 7619,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "H0": 7619,
          "K0": 7619,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-23T02:41:38.671283+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-23T02:52:19.638528+00:00"
    },
    {
      "bundle_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "17ff181fda91b4c21da381cf7c91b2992c6918dab1bb744aeea0184a37e2d42c",
        "artifact_manifest_sha256": "954c42e83fa37da2a85ab0ead642c06c1546ad1e048758542cb5d47dbc6f3e54",
        "contract_sha256": "bf546927f022abe901122fc048c4144c09d352b31596db323e0111dcd7e18e30",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-tx",
        "transfer_bytes": 55993,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/qualification_intake/qualification_result.json",
        "artifact_sha256": "b027923e38a2b5d6ae376c4f326616a47f05a598d6ab1715a2e0a1439ac08c59",
        "peak_memory_observed_mib": 7621,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "D0": 7621,
          "I0": 7621,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-23T13:17:16.714019+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-23T13:33:12.026271+00:00"
    }
  ],
  "paused": false,
  "pending_execution_budget": {
    "accounting_started_at": "2026-11-04T13:54:00+00:00",
    "auto_budget_extension_authorized": false,
    "automatic_training_retries": 0,
    "budget_reset": false,
    "closeout_reserve_hours": 6,
    "duration_hours": 42,
    "engineering_repairs": 1,
    "operations": [
      "upload",
      "launch",
      "probe",
      "fetch",
      "intake"
    ],
    "queue_credit_seconds": 0,
    "repair_authorization_ref": "ai4s/programs/mvcnet/research/acm-r1/execution/checkrepair2/packfix1/AUTHORIZATION.json",
    "repair_authorization_sha256": "1f366eb28c3b316cd442dc33d06d78661abe2e18157a20278b9fd34d73475f6a",
    "repair_contract_sha256": "012358fb085a8f819ac864e361677901f025123a73695726355b437fccca06e7",
    "source_run_id": "2026-11-04_mvcnet_acm_r1_lab10_r1_repair1-full-w1",
    "stage2_authorized": false,
    "stopped_time_credit": false,
    "transaction_hours": 4
  },
  "prelaunch_supersessions": [
    {
      "bundle_id": "2026-09-15_mvcnet_ccf_lab10_bundle_r2",
      "dispatch_status": "PENDING_UPLOAD",
      "dispatch_units": 147,
      "estimated_training_hours": 9.188,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "planned_units": 149,
      "recorded_at": "2026-09-15T17:26:41.540391+00:00",
      "recovery_of": "2026-09-15_mvcnet_ccf_lab10_r1-full-w1",
      "round_id": "mvcnet-contrastive-factorial-diagnostic-lab10-r2",
      "run_prefix": "2026-09-15_mvcnet_ccf_lab10_r2",
      "transaction_operations": [
        {
          "operation": "upload",
          "recorded_at": "2026-09-15T17:27:14.655612+00:00",
          "result": {
            "action": "UPLOADED",
            "monitor_powershell": "[REDACTED_MACHINE]",
            "run_id": "2026-09-15_mvcnet_ccf_lab10_r2-full-w1"
          }
        }
      ]
    }
  ],
  "program_id": "mvcnet",
  "provenance_corrections": [
    {
      "previous": {
        "intake_path": "results/logs/remote/2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
        "run_id": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
        "run_status": "complete",
        "verified": true,
        "verified_at": "2026-09-03T11:34:40.725862+00:00"
      },
      "reason": "manual TAPR verified intake did not refresh last_verified_intake; correct pointer without changing decisions or budget",
      "replacement": {
        "artifact_manifest_sha256": "c7fab3f9dc8f664e0a3d7f7b2ceee0798932a28d1f08ffc62cc5a7bd27d5d065",
        "contract_sha256": "87d7eecf49066a5d37be3fb2ec895c86c549941977d8599c05679fd825233253",
        "intake_path": "results/logs/remote/2026-09-07_mvcnet_tapr_lab10_r5-full-w1",
        "pointer_corrected_at": "2026-09-07T06:12:49.977039+00:00",
        "run_id": "2026-09-07_mvcnet_tapr_lab10_r5-full-w1",
        "run_status": "complete",
        "transaction_id": "mvcnet-tapr-tx-20260907-r5",
        "verification_record": "ai4s/programs/mvcnet/research/tapr_r4_r5_analysis/r5_verified_intake.json",
        "verified": true
      }
    }
  ],
  "retired_continuations": [
    {
      "campaign_id": "mvcnet-scva-autonomous-3r-20260903",
      "continuation_id": "mvcnet:mvcnet-scva-autonomous-3r-20260903:slot-3",
      "created_at": "2026-09-03T11:34:17.066475+00:00",
      "parent_decision": "NO_SIGNAL",
      "parent_decision_record": "ai4s/archive/programs/mvcnet/research/mvcnet-scva-cvc-s0p0-screen-lab10-v0.2_decision.yaml",
      "parent_evidence_id": "AI4S-MVCNET-mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
      "parent_round_id": "mvcnet-scva-cvc-s0p0-screen-lab10-v0.2",
      "parent_verified_intake": "2026-09-03_ai4s_mvcnet_scva_s0p0_lab10_r2-full-w1",
      "program_id": "mvcnet",
      "reason": "legacy campaign retired at v2 admission",
      "retired_at": "2026-09-05T10:41:17.496197+00:00",
      "round_slot": 3,
      "status": "PENDING_CONTRACT"
    }
  ],
  "run_control": {
    "continuation_policy_version": "evidence_to_design_v1",
    "continue_after_positive": false,
    "max_rounds": 1,
    "monitor": "blocking",
    "night_budget_hours": 30.0,
    "queue_time_policy": "exclude_resource_wait",
    "round_index": 0,
    "started_at": "2026-11-23T13:12:25.635158+00:00"
  },
  "schema_version": "mieeg-ai4s-state-v1",
  "source_recovery_history": [
    {
      "budget_admission": {
        "allowed": true,
        "blockers": [],
        "estimate_basis": "frozen_transaction_timeout",
        "estimate_note": "frozen execution timeout, separate from the qualification-derived process-hour estimate",
        "excluded": {
          "queue_hours": 0.0,
          "verified_stopped_hours": 0.0
        },
        "excluded_hours": 0.0,
        "expected_training_hours": 7.918,
        "reason": "fits remaining budget",
        "remaining_hours": 11.152,
        "shortfall_hours": 0.0,
        "spent_hours": 3.848,
        "total_hours": 15.0
      },
      "fresh_fit_task_ids": [
        "fit-K0-001-seed0-outer4",
        "fit-K0-001-seed0-outer5",
        "fit-K0-001-seed0-outer6",
        "fit-K0-001-seed0-outer7",
        "fit-K0-001-seed0-outer8",
        "fit-K0-001-seed4-outer0",
        "fit-K0-001-seed4-outer1",
        "fit-K0-001-seed4-outer2",
        "fit-K0-001-seed4-outer3",
        "fit-K0-001-seed4-outer4",
        "fit-K0-001-seed4-outer5",
        "fit-K0-001-seed4-outer6",
        "fit-K0-001-seed4-outer7",
        "fit-K0-001-seed4-outer8",
        "fit-S0-001-seed0-outer1",
        "fit-S0-001-seed0-outer2",
        "fit-S0-001-seed0-outer3",
        "fit-S0-001-seed0-outer4",
        "fit-S0-001-seed0-outer5",
        "fit-S0-001-seed0-outer6",
        "fit-S0-001-seed0-outer7",
        "fit-S0-001-seed0-outer8",
        "fit-S0-001-seed4-outer0",
        "fit-S0-001-seed4-outer1",
        "fit-S0-001-seed4-outer2",
        "fit-S0-001-seed4-outer3",
        "fit-S0-001-seed4-outer4",
        "fit-S0-001-seed4-outer5",
        "fit-S0-001-seed4-outer6",
        "fit-S0-001-seed4-outer7",
        "fit-S0-001-seed4-outer8"
      ],
      "registered_at": "2026-11-23T06:30:10.765478+00:00",
      "replacement_contract_sha256": "5203100406b966ec7c6c0b4d4eeaa8f7b306ca6d7ec0d8594230aaa82ffd9ae5",
      "replacement_run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10_repair1-full-w1",
      "reused_task_ids": [
        "fit-H0-001-seed0-outer0",
        "fit-H0-001-seed0-outer1",
        "fit-H0-001-seed0-outer2",
        "fit-H0-001-seed0-outer3",
        "fit-H0-001-seed0-outer4",
        "fit-H0-001-seed0-outer5",
        "fit-H0-001-seed0-outer6",
        "fit-H0-001-seed0-outer7",
        "fit-H0-001-seed0-outer8",
        "fit-H0-001-seed4-outer0",
        "fit-H0-001-seed4-outer1",
        "fit-H0-001-seed4-outer2",
        "fit-H0-001-seed4-outer3",
        "fit-H0-001-seed4-outer4",
        "fit-H0-001-seed4-outer5",
        "fit-H0-001-seed4-outer6",
        "fit-H0-001-seed4-outer7",
        "fit-H0-001-seed4-outer8",
        "fit-K0-001-seed0-outer0",
        "fit-K0-001-seed0-outer1",
        "fit-K0-001-seed0-outer2",
        "fit-K0-001-seed0-outer3",
        "fit-S0-001-seed0-outer0"
      ],
      "scientific_status": "incomplete_no_claim",
      "source_contract_sha256": "be191c0a80f5299d49b73a6099dd695ff66ecb300603c60209f30f2ab6fa0df2",
      "source_proof": {
        "path": "ai4s/programs/mvcnet/research/cvc_reflection_axis_20261123/repair1/SOURCE_CAPTURE.json",
        "sha256": "c5e9a01a73bcf8d79103c49d32bd86715c8e4f8d90d7370288b13fbeb4643067"
      },
      "source_run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1",
      "source_status": "FAILED",
      "source_timing": {
        "contract_sha256": "be191c0a80f5299d49b73a6099dd695ff66ecb300603c60209f30f2ab6fa0df2",
        "execution_seconds": 9615.973244667053,
        "queue_seconds": 1.7761497497558594,
        "queue_time_policy": "exclude_resource_wait",
        "run_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-full-w1",
        "transaction_id": "2026-11-23_mvcnet_reflectcvc_001_lab10-tx",
        "waiting_for_resources": false,
        "wall_seconds": 9617.749394416809
      }
    },
    {
      "budget_admission": {
        "allowed": true,
        "blockers": [],
        "estimate_basis": "frozen_transaction_timeout",
        "estimate_note": "frozen execution timeout, separate from the qualification-derived process-hour estimate",
        "excluded": {
          "queue_hours": 0.001,
          "verified_stopped_hours": 0.0
        },
        "excluded_hours": 0.001,
        "expected_training_hours": 8.0,
        "reason": "fits remaining budget",
        "remaining_hours": 11.957,
        "shortfall_hours": 0.0,
        "spent_hours": 12.043,
        "total_hours": 24.0
      },
      "fresh_fit_task_ids": [
        "fit-D0-001-seed0-outer7",
        "fit-D0-001-seed0-outer8",
        "fit-D0-001-seed4-outer0",
        "fit-D0-001-seed4-outer1",
        "fit-D0-001-seed4-outer2",
        "fit-D0-001-seed4-outer3",
        "fit-D0-001-seed4-outer4",
        "fit-D0-001-seed4-outer5",
        "fit-D0-001-seed4-outer6",
        "fit-D0-001-seed4-outer7",
        "fit-D0-001-seed4-outer8",
        "fit-S0-001-seed0-outer3",
        "fit-S0-001-seed0-outer4",
        "fit-S0-001-seed0-outer5",
        "fit-S0-001-seed0-outer6",
        "fit-S0-001-seed0-outer7",
        "fit-S0-001-seed0-outer8",
        "fit-S0-001-seed4-outer0",
        "fit-S0-001-seed4-outer1",
        "fit-S0-001-seed4-outer2",
        "fit-S0-001-seed4-outer3",
        "fit-S0-001-seed4-outer4",
        "fit-S0-001-seed4-outer5",
        "fit-S0-001-seed4-outer6",
        "fit-S0-001-seed4-outer7",
        "fit-S0-001-seed4-outer8"
      ],
      "registered_at": "2026-11-24T01:15:03.583553+00:00",
      "replacement_contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
      "replacement_run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
      "reused_task_ids": [
        "fit-D0-001-seed0-outer0",
        "fit-D0-001-seed0-outer1",
        "fit-D0-001-seed0-outer2",
        "fit-D0-001-seed0-outer3",
        "fit-D0-001-seed0-outer4",
        "fit-D0-001-seed0-outer5",
        "fit-D0-001-seed0-outer6",
        "fit-I0-001-seed0-outer0",
        "fit-I0-001-seed0-outer1",
        "fit-I0-001-seed0-outer2",
        "fit-I0-001-seed0-outer3",
        "fit-I0-001-seed0-outer4",
        "fit-I0-001-seed0-outer5",
        "fit-I0-001-seed0-outer6",
        "fit-I0-001-seed0-outer7",
        "fit-I0-001-seed0-outer8",
        "fit-I0-001-seed4-outer0",
        "fit-I0-001-seed4-outer1",
        "fit-I0-001-seed4-outer2",
        "fit-I0-001-seed4-outer3",
        "fit-I0-001-seed4-outer4",
        "fit-I0-001-seed4-outer5",
        "fit-I0-001-seed4-outer6",
        "fit-I0-001-seed4-outer7",
        "fit-I0-001-seed4-outer8",
        "fit-S0-001-seed0-outer0",
        "fit-S0-001-seed0-outer1",
        "fit-S0-001-seed0-outer2"
      ],
      "scientific_status": "incomplete_no_claim",
      "source_contract_sha256": "12578c24b50b29c67bd65ac860da7b591ec64c6c4bf32133b92e7dc81acc6066",
      "source_proof": {
        "path": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/repair1/SOURCE_CAPTURE.json",
        "sha256": "1611b5b22a958e53ffb448fe6a46f779baaf25f53ef8c971bfe9649f71d459b7"
      },
      "source_run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1",
      "source_status": "FAILED",
      "source_timing": {
        "contract_sha256": "12578c24b50b29c67bd65ac860da7b591ec64c6c4bf32133b92e7dc81acc6066",
        "execution_seconds": 13019.206773042679,
        "queue_seconds": 1.8278789520263672,
        "queue_time_policy": "exclude_resource_wait",
        "run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-full-w1",
        "transaction_id": "2026-11-23_mvcnet_cvcdropout_001_lab10-tx",
        "waiting_for_resources": false,
        "wall_seconds": 13021.034651994705
      }
    },
    {
      "budget_admission": {
        "allowed": true,
        "blockers": [],
        "estimate_basis": "frozen_transaction_timeout",
        "estimate_note": "frozen execution timeout, separate from the qualification-derived process-hour estimate",
        "excluded": {
          "queue_hours": 4.545,
          "verified_stopped_hours": 0.0
        },
        "excluded_hours": 4.545,
        "expected_training_hours": 7.0,
        "reason": "fits remaining budget",
        "remaining_hours": 11.263,
        "shortfall_hours": 0.0,
        "spent_hours": 18.737,
        "total_hours": 30.0
      },
      "fresh_fit_task_ids": [
        "fit-D0-001-seed4-outer5",
        "fit-D0-001-seed4-outer6",
        "fit-D0-001-seed4-outer7",
        "fit-D0-001-seed4-outer8",
        "fit-S0-001-seed4-outer6",
        "fit-S0-001-seed4-outer7",
        "fit-S0-001-seed4-outer8"
      ],
      "registered_at": "2026-11-24T12:29:21.058598+00:00",
      "replacement_contract_sha256": "753d12cc8df38aa780fa551c0495d9059e59802da9ebf3ca5983a38a9cb9bdde",
      "replacement_run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair2-full-w1",
      "reused_task_ids": [
        "fit-D0-001-seed0-outer0",
        "fit-D0-001-seed0-outer1",
        "fit-D0-001-seed0-outer2",
        "fit-D0-001-seed0-outer3",
        "fit-D0-001-seed0-outer4",
        "fit-D0-001-seed0-outer5",
        "fit-D0-001-seed0-outer6",
        "fit-D0-001-seed0-outer7",
        "fit-D0-001-seed0-outer8",
        "fit-D0-001-seed4-outer0",
        "fit-D0-001-seed4-outer1",
        "fit-D0-001-seed4-outer2",
        "fit-D0-001-seed4-outer3",
        "fit-D0-001-seed4-outer4",
        "fit-I0-001-seed0-outer0",
        "fit-I0-001-seed0-outer1",
        "fit-I0-001-seed0-outer2",
        "fit-I0-001-seed0-outer3",
        "fit-I0-001-seed0-outer4",
        "fit-I0-001-seed0-outer5",
        "fit-I0-001-seed0-outer6",
        "fit-I0-001-seed0-outer7",
        "fit-I0-001-seed0-outer8",
        "fit-I0-001-seed4-outer0",
        "fit-I0-001-seed4-outer1",
        "fit-I0-001-seed4-outer2",
        "fit-I0-001-seed4-outer3",
        "fit-I0-001-seed4-outer4",
        "fit-I0-001-seed4-outer5",
        "fit-I0-001-seed4-outer6",
        "fit-I0-001-seed4-outer7",
        "fit-I0-001-seed4-outer8",
        "fit-S0-001-seed0-outer0",
        "fit-S0-001-seed0-outer1",
        "fit-S0-001-seed0-outer2",
        "fit-S0-001-seed0-outer3",
        "fit-S0-001-seed0-outer4",
        "fit-S0-001-seed0-outer5",
        "fit-S0-001-seed0-outer6",
        "fit-S0-001-seed0-outer7",
        "fit-S0-001-seed0-outer8",
        "fit-S0-001-seed4-outer0",
        "fit-S0-001-seed4-outer1",
        "fit-S0-001-seed4-outer2",
        "fit-S0-001-seed4-outer3",
        "fit-S0-001-seed4-outer4",
        "fit-S0-001-seed4-outer5"
      ],
      "scientific_status": "incomplete_no_claim",
      "source_contract_sha256": "ee228aa1ed837eb1f83e88a39624283c3ec041dfba3a236297b0f95ac8da239d",
      "source_proof": {
        "path": "ai4s/programs/mvcnet/research/cvc_shared_dropout_20261123/repair2/SOURCE_CAPTURE.json",
        "sha256": "4cd2f7fd32b2cd83a7912e225322d6ef139603868217fca6dfa3041f9d590949"
      },
      "source_run_id": "2026-11-23_mvcnet_cvcdropout_001_lab10_repair1-full-w1",
      "source_status": "FAILED",
      "source_timing": {
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
  ],
  "status": "WAITING_REMOTE",
  "updated_at": "2026-11-25T09:31:18.893921+00:00",
  "v3_follow_up": {
    "decision_record": "ai4s/programs/mvcnet/research/mvcnet-reflectcvc-001-development-v1_decision.yaml",
    "evidence_id": "AI4S-MVCNET-mvcnet-reflectcvc-001-development-v1",
    "next_design": null,
    "reason": "mvcnet_reflectcvc_001_single_development_round"
  },
  "vbr_r1_repair1_recovery": {
    "authorization_ref": "ai4s/programs/mvcnet/research/vbr-r1/execution/REPAIR1_AUTHORIZATION.json",
    "authorization_sha256": "48ede83524b13817920f342fbdcfa159cce0ddbe1ff9e719c338a40b4c62bfac",
    "campaign_budget_reset": false,
    "closeout_reserve_hours": 6,
    "contract_file_sha256": "d276bcbd0ed19b3fbbe77bc6ca782e23a5396b9287301525b26fe338c8aebff7",
    "contract_sha256": "2a0238f72648bf88011df9e711165081a03b310bbbaf04da8cd91b683feaa337",
    "dispatch_started": false,
    "new_fits_started": 0,
    "replacement_round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair1",
    "source_failure_receipt_sha256": "d33b7257cd38b38ae0b56da519ffbcfd0b942229a3f2b2bbdc46f359346a407b",
    "source_failure_record_sha256": "91f8368394c93fa44072910cb7aca526293a39376d104eea37e83268e7b5978e",
    "source_invalid_retained": true,
    "source_round_id": "mvcnet-vbr-r1-screen-lab10-r1",
    "source_run_id": "2026-10-24_mvcnet_vbr_r1_lab10_r1-full-w1",
    "status": "READY_FOR_RECORD_RUN_NOT_REGISTERED_NOT_DISPATCHED",
    "transaction_cap_hours": 180,
    "transaction_id": "mvcnet-vbr-r1-tx-20261024-r1-repair1"
  },
  "vbr_r1_repair2_packfix1_recovery": {
    "authorization_ref": "ai4s/programs/mvcnet/research/vbr-r1/execution/REPAIR2_PACKFIX1_AUTHORIZATION.json",
    "authorization_sha256": "752672ce5101703222a3f0114a50d6906d2b98a20dd74f0357951bf4783cb2af",
    "campaign_budget_reset": false,
    "closeout_reserve_hours": 6,
    "completed_qualification_manifest_sha256": "cf44e6ba526da9067656180f7d873760c0f454403e4feb96ac7133d7dbfae9a6",
    "contract_sha256": "43e22c0e6dae8958a4ea73d828cf2cd066bdaaae712d4933bef6efdd5c0e8b8a",
    "dispatch_started": false,
    "fresh_qualification_task_ids": [
      "qualification-P0-seed69-outer0-replica1"
    ],
    "replacement_round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair2-packfix1",
    "reused_technical_task_ids": [
      "qualification-B0-seed69-outer0",
      "qualification-B0-seed69-outer0-replica1",
      "qualification-N0-seed69-outer0",
      "qualification-N0-seed69-outer0-replica1",
      "qualification-P0-seed69-outer0",
      "qualification-S0-seed69-outer0",
      "qualification-S0-seed69-outer0-replica1"
    ],
    "science_fits_started": 0,
    "source_failure_record_sha256": "0e35b965f9d2d2b678ac8d54796ea6a60d81f31b522a6f95010e162cfe42c4b1",
    "source_invalid_retained": true,
    "source_round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair1",
    "source_run_id": "2026-10-24_mvcnet_vbr_r1_lab10_r1_repair1-full-w1",
    "status": "READY_FOR_RECORD_RUN_NOT_DISPATCHED",
    "transaction_cap_hours": 170,
    "transaction_id": "mvcnet-vbr-r1-tx-20261025-r1-repair2-packfix1"
  },
  "vbr_r1_repair3_packfix2_recovery": {
    "authorization_ref": "ai4s/programs/mvcnet/research/vbr-r1/execution/repair3/AUTHORIZATION_PACKFIX2.json",
    "authorization_sha256": "d723cb60e21d810dabc9155b20909640f372ae518ffd1ad11adb0e812b389b1e",
    "campaign_budget_reset": false,
    "closeout_reserve_hours": 6,
    "contract_sha256": "57dfc4bd89fc84bad17a024df6ec1a313e7ac468e401443884209e56fb33ffdf",
    "cumulative_budget_hours": 275,
    "dispatch_started": false,
    "qualification_task_ids": [
      "qualification-B0-seed69-outer0",
      "qualification-B0-seed69-outer0-replica1",
      "qualification-S0-seed69-outer0",
      "qualification-S0-seed69-outer0-replica1",
      "qualification-N0-seed69-outer0",
      "qualification-N0-seed69-outer0-replica1",
      "qualification-P0-seed69-outer0",
      "qualification-P0-seed69-outer0-replica1"
    ],
    "qualification_verification_sha256": "6a7ffd4b42868dd5fe4f25f0a031b8e834cb66ded052a696559bb30bb7d54df4",
    "replacement_round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair3",
    "science_cap_hours": 238,
    "science_fits_started": 0,
    "source_failure_record_sha256": "18ff60487d354d1d03fc036937cc71917b91c25e4416491cbd7e551da41209ba",
    "source_invalid_retained": true,
    "source_round_id": "mvcnet-vbr-r1-screen-lab10-r1-repair2-packfix1",
    "source_run_id": "2026-10-25_mvcnet_vbr_r1_lab10_r1_repair2_packfix1-full-w1",
    "status": "READY_FOR_RECORD_RUN_NOT_DISPATCHED",
    "transaction_cap_hours": 237.25,
    "transaction_id": "mvcnet-vbr-r1-tx-20261028-r1-repair3-packfix2"
  },
  "withdrawn_rounds": [
    {
      "bundle_id": "2026-08-31_ai4s_mvcnet_r02_seed78_b0p1_bundle_r1",
      "decision": "WITHDRAWN_BY_USER_NO_SCIENTIFIC_INTERPRETATION",
      "executor_id": "ccmu_lab",
      "intake_status": "intentionally_not_fetched_or_intaked",
      "reason": "user_ended_current_round_and_selected_lab10_for_next_round",
      "recorded_at": "2026-08-31",
      "remote_check_run_id": "2026-08-31_ai4s_mvcnet_r02_seed78_b0p1-check",
      "remote_check_status": "complete",
      "round_id": "mvcnet-r02-vcn-p1-independent-seed-confirmation-v0.1",
      "run_prefix": "2026-08-31_ai4s_mvcnet_r02_seed78_b0p1"
    }
  ],
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
}

```
