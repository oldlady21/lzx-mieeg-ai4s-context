# State 阅读分段 3

完整脱敏文件：`ai4s/programs/mvcnet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`feb7cd87e1a257f71a3858e0f98467a7da5f287f9d54ab9f4b174fb0f1e9d7f0`。UTF-8 字节范围：[1000000, 1075674) / 1075674。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
it_seconds": 0,
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
    "decision_record": "ai4s/programs/mvcnet/research/mvcnet-ifnet-reference-rank1-001-development-v1_decision.yaml",
    "evidence_id": "AI4S-MVCNET-mvcnet-ifnet-reference-rank1-001-development-v1",
    "role": "exact_negative_boundary"
  },
  "last_run_reconciliation": "ai4s/programs/mvcnet/research/acm-r1/factorial/CONTROLLER_RECONCILIATION_20261116.json",
  "last_verified_intake": {
    "analysis_receipt_sha256": "2c03c7fa843aeabdb084fd78fc480ba12991e898d47b85967de1eb6bceb79ec7",
    "artifact_manifest_sha256": "19215faccfc901f4b1eb1771bd1d59931702c36e0b20c908a6248dfde549144c",
    "contract_sha256": "e0d2e6281771ed4c075ed88e0a15b23c74e93d08a3929c472d59a23cac9b961c",
    "full_payload_local": false,
    "intake_path": "results/logs/remote/2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
    "intake_scope": "analysis_v1",
    "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-full-w1",
    "run_status": "complete",
    "transaction_id": "2026-11-28_mvcnet_reference_rank1_001_lab10-tx",
    "transfer_bytes": 1517993,
    "verified": true,
    "verified_at": null
  },
  "last_verified_preflight": {
    "bundle_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-bundle",
    "contract": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/QUALIFICATION_MEMORY_CONTRACT.json",
    "evidence_role": "engineering_preflight_only_no_performance_claim",
    "executor_id": "lab10",
    "intake": {
      "analysis_receipt_sha256": "47206a9d7361ba6f5fba6cf2a3894d2a06fc8a6e402b588ff10b323a69dfb79d",
      "artifact_manifest_sha256": "46f128395190149641b1289b92742fc7d825323bde7009b00df3b1965a8cfbf7",
      "contract_sha256": "29d062697b194301ec0b9271234feab36f35b7070607cfa4be59563a3d0b994d",
      "full_payload_local": false,
      "intake_path": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/qualification_memory_intake",
      "intake_scope": "analysis_v1",
      "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1",
      "run_status": "complete",
      "transaction_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-tx",
      "transfer_bytes": 56907,
      "verified": true
    },
    "interpretation_boundary": "Runtime-capacity evidence only; it is not a B0 comparison, candidate result, or paper claim.",
    "operation_id": "mvcnet:engineering_preflight:2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1",
    "preflight": {
      "artifact": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/qualification_memory_intake/qualification_result.json",
      "artifact_sha256": "839760a806f00be4caa9d7bdb96f65bab68734ca27cd942bcf24d92d9547f591",
      "peak_memory_observed_mib": 7647,
      "peak_memory_status": "three_arm_source_only_five_epoch_observed",
      "peak_mib_by_arm": {
        "G0": 7647,
        "J0": 7647,
        "S0": 7619
      },
      "profile_kind": "three_arm_source_only_five_epoch"
    },
    "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1"
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
    },
    {
      "bundle_id": "2026-11-26_mvcnet_centralrow_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/central_row_augmentation_20261126/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "5d337c367dd3c06f3161336a987b5d96819907ff4e3f3bafd961877947d7966b",
        "artifact_manifest_sha256": "a9315022707d9bc6c89a4618fe2ce4efa9933632c53e844ef5f6ce3930e208f6",
        "contract_sha256": "bb3030c4db5cde48250dc344868e64ee7755d695e14626f606d5c6e2353d3fc1",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/central_row_augmentation_20261126/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-26_mvcnet_centralrow_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-26_mvcnet_centralrow_001_lab10_qualification-tx",
        "transfer_bytes": 55983,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-26_mvcnet_centralrow_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/central_row_augmentation_20261126/qualification_intake/qualification_result.json",
        "artifact_sha256": "6fdc9b4f0be86366426f7686baca15b5ac02d2758f0c95def0ac0db44e4a7497",
        "peak_memory_observed_mib": 7627,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "G0": 7627,
          "J0": 7627,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-26T08:43:06.488066+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-26_mvcnet_centralrow_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-26T09:03:09.867068+00:00"
    },
    {
      "bundle_id": "2026-11-27_mvcnet_pool_antialias_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/ifnet_pool_antialias_20261127/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "636294bce617d9c69b7763a14825dc17e342f76c9bf041890b78d46b6b258700",
        "artifact_manifest_sha256": "aba09233f09b234fa61a830934c1c5963fe7a58005a6a82a3c80b520c1925596",
        "contract_sha256": "141ba0f6554b10e16218680c0e377863f416cda64108449e171be188d095f6b1",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/ifnet_pool_antialias_20261127/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-27_mvcnet_pool_antialias_001_lab10_qualification-tx",
        "transfer_bytes": 56254,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-27_mvcnet_pool_antialias_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/ifnet_pool_antialias_20261127/qualification_intake/qualification_result.json",
        "artifact_sha256": "9169132289397272e7446ffe4f2290f5cc26ef27bd85ad1ef2b9eeff51928035",
        "peak_memory_observed_mib": 7695,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "G0": 7695,
          "J0": 7619,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-27T07:05:05.699073+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-27_mvcnet_pool_antialias_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-27T07:07:54.636657+00:00"
    },
    {
      "bundle_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10_qualification-bundle",
      "contract": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_20261127/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "6e34a11b5c0899fb4c5763e52e8f6630dd83321618c001114864d200e7006d60",
        "artifact_manifest_sha256": "9fae176b45ba82f56abfb47bd11d28f06cd413a9ae4c5c314653be4dd7f0beb3",
        "contract_sha256": "4e0e6b376c6c22e0fca6fe77e137b190bcedc0daa9efca3dc7e7023ca92ba8ce",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_20261127/qualification_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10_qualification-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10_qualification-tx",
        "transfer_bytes": 56336,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-27_mvcnet_view_ce_balance_001_lab10_qualification-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_20261127/qualification_intake/qualification_result.json",
        "artifact_sha256": "0ab47830d0400f193a53b708e6b618c13079d9c229b20e3918a7d21cceb1b3af",
        "peak_memory_observed_mib": 7619,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "G0": 7619,
          "J0": 7619,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-27T14:27:11.373935+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-27_mvcnet_view_ce_balance_001_lab10_qualification-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-27T14:43:15.786025+00:00"
    },
    {
      "bundle_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification-bundle",
      "completed_at": "2026-11-27T18:15:39.478972+00:00",
      "contract": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_xdataset_20261128/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "failure_class": "MISSING_HISTORICAL_CR_CALLBACK_AND_INCOMPLETE_DRIVER_TELEMETRY",
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification-full-w1",
      "registered_at": "2026-11-27T18:05:45.588104+00:00",
      "remote_capture": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_xdataset_20261128/QUALIFICATION_FAILED_PARTIAL_004.json",
      "remote_capture_sha256": "985f9da4f5baf84e840597bbfaee212a87268f448de18a3b08c5c034829c7e01",
      "repair_run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification_r1-full-w1",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification-full-w1",
      "status": "FAILED",
      "verified_intake": false
    },
    {
      "bundle_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification_r1-bundle",
      "contract": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_xdataset_20261128/QUALIFICATION_REPAIR_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "d3acede5ab98e3763d170de93b4387009b98c9b02469a1d42ee86718e32de1ed",
        "artifact_manifest_sha256": "f7efed9915f209d3b07eb7933c14203a300d3deeddcbc4424dac1c2fcd47ba2d",
        "contract_sha256": "71ba4cb12a63df4a7546803bca5fc3a98ce35ba3d0705006d2360e10e53e7bb1",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_xdataset_20261128/qualification_repair_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification_r1-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification_r1-tx",
        "transfer_bytes": 163525,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification_r1-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/ifnet_view_ce_balance_xdataset_20261128/qualification_repair_intake/qualification_result.json",
        "artifact_sha256": "6885393366fcdc9a3a9e6c36dcbc10eb7ad93bd910db6a95540c97ea1315c366",
        "peak_memory_observed_mib": 6415,
        "peak_memory_status": "nine_job_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "BNCI2014002/G0": 6415,
          "BNCI2014002/J0": 6415,
          "BNCI2014002/S0": 6415,
          "BNCI2014004/G0": 6131,
          "BNCI2014004/J0": 6131,
          "BNCI2014004/S0": 6131,
          "Zhou2016/G0": 6399,
          "Zhou2016/J0": 6399,
          "Zhou2016/S0": 6399
        },
        "profile_kind": "nine_job_source_only_five_epoch"
      },
      "registered_at": "2026-11-27T18:16:55.563304+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-28_mvcnet_view_ce_balance_xdataset_lab10_qualification_r1-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-27T18:22:08.074195+00:00"
    },
    {
      "bundle_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification-bundle",
      "completed_at": "2026-11-28T05:54:55.645030+00:00",
      "contract": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/QUALIFICATION_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "failure_class": "USER_SUPERSEDED_CAPACITY_POLICY_ZERO_ATTEMPTS",
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-28_mvcnet_reference_rank1_001_lab10_qualification-full-w1",
      "registered_at": "2026-11-28T03:55:43.551451+00:00",
      "remote_capture_sha256": "15458f3bafae4d9fba091d6ffb20e8521e5efc8bf1aa791118719969d52a232f",
      "replacement_run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification-full-w1",
      "status": "FAILED",
      "verified_intake": false
    },
    {
      "bundle_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-bundle",
      "contract": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/QUALIFICATION_MEMORY_CONTRACT.json",
      "executor_id": "lab10",
      "expected_artifact": "qualification_result.json",
      "intake": {
        "analysis_receipt_sha256": "47206a9d7361ba6f5fba6cf2a3894d2a06fc8a6e402b588ff10b323a69dfb79d",
        "artifact_manifest_sha256": "46f128395190149641b1289b92742fc7d825323bde7009b00df3b1965a8cfbf7",
        "contract_sha256": "29d062697b194301ec0b9271234feab36f35b7070607cfa4be59563a3d0b994d",
        "full_payload_local": false,
        "intake_path": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/qualification_memory_intake",
        "intake_scope": "analysis_v1",
        "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1",
        "run_status": "complete",
        "transaction_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-tx",
        "transfer_bytes": 56907,
        "verified": true
      },
      "kind": "engineering_preflight",
      "operation_id": "mvcnet:engineering_preflight:2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1",
      "preflight": {
        "artifact": "ai4s/programs/mvcnet/research/ifnet_reference_rank1_20261128/qualification_memory_intake/qualification_result.json",
        "artifact_sha256": "839760a806f00be4caa9d7bdb96f65bab68734ca27cd942bcf24d92d9547f591",
        "peak_memory_observed_mib": 7647,
        "peak_memory_status": "three_arm_source_only_five_epoch_observed",
        "peak_mib_by_arm": {
          "G0": 7647,
          "J0": 7647,
          "S0": 7619
        },
        "profile_kind": "three_arm_source_only_five_epoch"
      },
      "registered_at": "2026-11-28T05:54:59.569550+00:00",
      "result_role": "engineering_preflight_only_no_performance_claim",
      "resume_paused": false,
      "resume_status": "READY",
      "run_id": "2026-11-28_mvcnet_reference_rank1_001_lab10_qualification_mem-full-w1",
      "status": "VERIFIED_INTAKE",
      "verified_at": "2026-11-28T05:58:34.024402+00:00"
    }
  ],
  "paused": true,
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
    "night_budget_hours": 18.0,
    "queue_time_policy": "exclude_resource_wait",
    "round_index": 1,
    "started_at": "2026-11-28T03:51:22.421184+00:00"
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
  "status": "COMPLETE_MAX_ROUNDS",
  "updated_at": "2026-11-28T11:07:15.985509+00:00",
  "v3_follow_up": {
    "decision_record": "ai4s/programs/mvcnet/research/mvcnet-ifnet-reference-rank1-001-development-v1_decision.yaml",
    "evidence_id": "AI4S-MVCNET-mvcnet-ifnet-reference-rank1-001-development-v1",
    "next_design": null,
    "reason": "mvcnet_ifnet_reference_rank1_001_single_development_round"
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
