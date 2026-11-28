# State 阅读分段 3

完整脱敏文件：`ai4s/programs/dsainet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`f82348654ac8c6f7aa650bb18e93964fe7d7ff12011e22926810756e98c7e30f`。UTF-8 字节范围：[1000000, 1146765) / 1146765。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
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
    "disposition": "STOP_LATERAL_HAND_READOUT",
    "round_id": "dsainet-b0-lateral-hand-readout-r1"
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
    "run_id": "2026-11-03_dsainet_ds07_r1_science1-telemetryfix1-full-w1",
    "scientific_training_completed": 0,
    "status": "FAILED_TECH_SUMMARY_INTERFACE_AFTER_SUCCESSFUL_N_AND_COST"
  },
  "last_engineering_repair": {
    "budget_extended": false,
    "completed_at": "2026-09-30T04:36:39.133007+00:00",
    "evaluation_complete": 252,
    "evaluation_remaining": 0,
    "evaluation_reused": 251,
    "new_target_forward": 1,
    "new_training": 0,
    "recorded_at": "2026-09-30T04:16:56.739370+00:00",
    "repair_id": "dsa-sid-v0.1-repair1",
    "round_id": "dsa-sid-v0.1-repair1b",
    "run_id": "2026-09-30_dsainet_sid_v0_1_repair1b-full-w1",
    "scientific_result": true,
    "status": "COMPLETE_VERIFIED",
    "training_reused": 252
  },
  "last_fd_r1_analysis": {
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
  "last_missing_only_recovery": {
    "additional_hours": 0,
    "audits_required": 189,
    "checked_at": "2026-10-22T07:08:27.630254+00:00",
    "cumulative_budget_hours": 88,
    "dispatch_observation": "WAITING_RESOURCE_ADMISSION_NO_WORKER_YET",
    "dynamic_expansion_configured": true,
    "dynamic_expansion_observed": false,
    "historical_wait_deduction_authorized": false,
    "original_campaign_start": 1792387110,
    "original_completed_fits": 187,
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
      "fits_missing2": {
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
        "pending": 2,
        "resource_admission": {
          "0": {
            "eligibility": "eligible",
            "existing_compute_processes": 1,
            "observed_free_mib": 3965,
            "observed_utilization_pct": 53,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": 893,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "1": {
            "eligibility": "insufficient_reserved_memory",
            "existing_compute_processes": 2,
            "observed_free_mib": 616,
            "observed_utilization_pct": 62,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": -2456,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "2": {
            "eligibility": "eligible",
            "existing_compute_processes": 1,
            "observed_free_mib": 3965,
            "observed_utilization_pct": 11,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": 893,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "3": {
            "eligibility": "eligible",
            "existing_compute_processes": 1,
            "observed_free_mib": 3973,
            "observed_utilization_pct": 12,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": 901,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "4": {
            "eligibility": "insufficient_reserved_memory",
            "existing_compute_processes": 2,
            "observed_free_mib": 1062,
            "observed_utilization_pct": 37,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": -2010,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "5": {
            "eligibility": "insufficient_reserved_memory",
            "existing_compute_processes": 2,
            "observed_free_mib": 548,
            "observed_utilization_pct": 89,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": -2524,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "6": {
            "eligibility": "eligible",
            "existing_compute_processes": 1,
            "observed_free_mib": 3965,
            "observed_utilization_pct": 71,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": 893,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "7": {
            "eligibility": "eligible",
            "existing_compute_processes": 1,
            "observed_free_mib": 3973,
            "observed_utilization_pct": 72,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": 901,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "8": {
            "eligibility": "insufficient_reserved_memory",
            "existing_compute_processes": 2,
            "observed_free_mib": 616,
            "observed_utilization_pct": 76,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": -2456,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          },
          "9": {
            "eligibility": "eligible",
            "existing_compute_processes": 1,
            "observed_free_mib": 3973,
            "observed_utilization_pct": 86,
            "pool_capacity_available": false,
            "post_launch_headroom_mib": 901,
            "reserve_mib": 0,
            "task_id": "L_s1_t6"
          }
        },
        "running": 0,
        "running_tasks": {},
        "total": 2,
        "updated_at": "2026-10-22T07:08:20.901804+00:00",
        "verified_results": []
      }
    },
    "pid": "[REDACTED_MACHINE]",
    "preservation_errors": [],
    "preserved_full_telemetry_fits": 12,
    "preserved_original_files": 3147,
    "preserved_resource_fit_count": 165,
    "promoted_replays": 10,
    "qualification": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_missing2_88/QUALIFICATION_FINAL.json",
    "recovery_id": "2026-10-22_NRC1repair3_missing2_88_r1",
    "remaining_fits_authorized": 2,
    "remaining_seconds": 73539.74286389351,
    "replay_dispatch_count": 0,
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_missing2_88/REPAIR_NOTES.md",
    "resource_admission_check": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_missing2_88/QUALIFICATION_FINAL.json",
    "reused_successful_replays": 10,
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "scientific_effects_read": false,
    "snapshot": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_missing2_88/STATUS.json",
    "source_snapshot": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_missing2_88/SOURCE_SNAPSHOT.json",
    "status": "RUNNING",
    "supplement_sha256": "e4d3a090a138c66c393331d4ae75a94c140935ac001c051a752d05d7cdc161bb"
  },
  "last_nrc1_complete_intake": {
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
    "other_stages_started": false,
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_audit3_96/RESULTS_ZH.md",
    "report_sha256": "be39afa7937a6debd8c2bae3b811dbac30f58fa7f0807baae68aabc1651507ac",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "scientific_interpretation": "native fallback preserved; modest improvement; frozen effective complementarity gates not established",
    "status": "ARTIFACTS_VERIFIED_ANALYSIS_COMPLETE_WITH_BUDGET_DEVIATION"
  },
  "last_ord_ec_r1_analysis": {
    "A_pass": false,
    "B_pass": false,
    "P_accuracy": 0.5560378086419753,
    "P_fallback_W0": 16,
    "P_raw_nll": 1.19980785860034,
    "P_selected_W": 2,
    "P_vs_parent": {
      "accuracy_delta_pp": 0.009645061728395335,
      "nll_delta": 0.00046170620423291453
    },
    "archive_bytes": 10774803,
    "artifact_manifest_sha256": "1400fc1ecac5224fa9f4a63a906f8095e1d194c065a24b89a4321f632d6a21a7",
    "audit_count": 108,
    "budget": {
      "additional_authorization": false,
      "clock_reset": false,
      "original_started_at": "2026-10-23T13:28:00+00:00",
      "prior_queue_seconds": 31055.862429380417,
      "remaining_hours_at_closeout": -3.431080777394333,
      "remaining_hours_at_science_completion": 3.8827191375361547,
      "total_hours": 163
    },
    "checks": {
      "excluded_forward_count": 0,
      "frozen_analyzer_replay": "PASS",
      "independent_metrics_and_gates": "PASS",
      "max_native_replay_logit_error": 3.5762786865234375e-06,
      "report_parent_gate_label_clarified": true,
      "source_access_36fit_36select_36audit": "PASS"
    },
    "claim_created": false,
    "closed_active_run": {
      "bundle_id": "2026-10-30_dsainet_p0_ord_ec_r1_science1",
      "completed_at": "2026-10-30T21:12:38.073534+08:00",
      "contract": "ai4s/programs/dsainet/research/p0-ord-ec-r1/science_bundle163/transaction_contract.yaml",
      "contract_sha256": "a12e54ae3ce0cf46bef48286ede40f6f1712d7dc231741e27922d71805a1dce5",
      "dispatch_receipt": "ai4s/programs/dsainet/research/p0-ord-ec-r1/REMOTE_DISPATCH_RECEIPT.json",
      "dispatch_status": "REMOTE_COMPLETED_AWAITING_INTAKE",
      "dispatch_units": 108,
      "estimated_training_hours": 2.8278,
      "execution_mode": "user_managed",
      "executor_id": "lab10",
      "host": "[REDACTED_MACHINE]",
      "last_probe_counts": {
        "audits": 108,
        "fits": 108,
        "select_choices": 108
      },
      "last_probe_ref": "ai4s/programs/dsainet/research/p0-ord-ec-r1/STATUS_VERIFICATION_20261031.json",
      "old_campaign_remains_paused": true,
      "planned_units": 108,
      "previous_program_status": "COMPLETE_MAX_ROUNDS",
      "recorded_at": "2026-10-30T12:08:01.530201+00:00",
      "remote_root": "[REDACTED_MACHINE]",
      "round_id": "p0-ord-ec-r1-science-1",
      "run_id": "2026-10-30_dsainet_p0_ord_ec_r1_science1-full-w1",
      "run_prefix": "2026-10-30_dsainet_p0_ord_ec_r1_science1",
      "scope": "108 bounded convex fits and108 audits; no neural training"
    },
    "contract_sha256": "a12e54ae3ce0cf46bef48286ede40f6f1712d7dc231741e27922d71805a1dce5",
    "decision": "NO_SIGNAL_STOP_FIXED_ORD_EC",
    "evidence_id": "DSAINET-P0-ORD-EC-R1-VERIFIED-ANALYSIS-20261031",
    "external_result_review": "not_triggered_ordinary_negative_screen",
    "failed_nodes": 0,
    "fit_count": 108,
    "frozen_replay": "ai4s/programs/dsainet/research/p0-ord-ec-r1/closeout_analysis/REPLAY_AND_FIT_CHECKS.json",
    "full_payload_local": false,
    "independent_recompute": "ai4s/programs/dsainet/research/p0-ord-ec-r1/closeout_analysis/INDEPENDENT_METRICS.json",
    "independent_recompute_sha256": "7efb16611e03d2505e25a5267f53af8ae55c9287571f6a3a4f0005cbd10e3229",
    "intake_path": "ai4s/programs/dsainet/research/p0-ord-ec-r1/verified_intake",
    "intake_receipt_sha256": "69d69b9ea081523aa0663315d2a9f1fbee3b56498facd725242839815367b42e",
    "intake_scope": "analysis_v1",
    "new_closeout_fits_or_forward": 0,
    "new_neural_fits": 0,
    "next_action": "STOP_FIXED_ORD_EC_NO_NEW_EXPERIMENT",
    "observed_at": "2026-10-30T20:31:27.753228+00:00",
    "parent_count": 36,
    "previous_last_decision": {
      "decision": "NO_SIGNAL_STOP_FIXED_PHASE_TEMPLATE",
      "evidence_id": "DSAINET-P0-WMP-D1-STAGE-A-20261029",
      "neural_training_eligible": false,
      "role": "exposed_source_development_nondegeneracy_diagnostic",
      "round_id": "p0-wmp-d1-stage-a",
      "stage_b_eligible": false
    },
    "previous_last_verified_intake": {
      "analysis_receipt_sha256": "6a586b663219441c4a8c46c3105e1a05e5b36fecc0836488a0446a7e3ddf1cb6",
      "artifact_manifest_sha256": "04cc708e1628f222d7a410e36a6d3a32762db8058c9e8c1dbfe6086ad9ab51eb",
      "contract_sha256": "20dd39535800fc93e4ffb85baf2537945c59323e97083e61a99f7a31479afd25",
      "full_payload_local": false,
      "intake_path": "ai4s/programs/dsainet/research/p0-wmp-d1/stagea_verified_intake",
      "intake_scope": "analysis_v1",
      "run_id": "2026-10-29_dsainet_p0_wmp_d1_stagea-full-w1",
      "transaction_id": "2026-10-29_dsainet_p0_wmp_d1_stagea-tx",
      "transfer_bytes": 786429,
      "verified": true,
      "verified_at": "2026-10-29T16:17:25.223715+00:00"
    },
    "report": "ai4s/programs/dsainet/research/p0-ord-ec-r1/closeout_analysis/REPORT_ZH.md",
    "research_id": "p0-ord-ec-r1",
    "risk_context": 5,
    "risk_correct_count": 796,
    "risk_n": 1152,
    "risk_original_subject_index": 7,
    "role": "exposed_source_development_fixed_parent_bounded_readout_screen",
    "run_id": "2026-10-30_dsainet_p0_ord_ec_r1_science1-full-w1",
    "selected_file_count": 373,
    "selection_count": 108,
    "standard_verified_intake": true,
    "transaction_id": "2026-10-30_dsainet_p0_ord_ec_r1_science1-tx",
    "transfer_bytes": 13495094
  },
  "last_p0_pf_r1_budget_gate": {
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
  "last_p0_pf_r1_readonly_check": {
    "audits": {
      "completed": 90,
      "failed": 0,
      "failed_ids": [],
      "full_process_telemetry": 90,
      "oom": 0,
      "planned": 90,
      "scheduler_wall_seconds": 225.71468925476074,
      "task_count": 90,
      "timeout": 0
    },
    "barrier": "SEALED",
    "budget": {
      "closeout_reserved_hours": 4.0,
      "current_queue_hours": 0.0,
      "original_start": "2026-10-23T21:28:00+08:00",
      "paused_idle_or_stopped_refund_hours": 0,
      "remaining_hours": 24.113142334272336,
      "this_transaction_execution_hours": 0.6545794363816579,
      "total_hours": 157,
      "verified_prior_queue_hours": 8.626628452605672
    },
    "claim_created": false,
    "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
    "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-COMPLETE-STATUS-20261029T1858",
    "fits": {
      "completed": 90,
      "failed": 0,
      "failed_ids": [],
      "full_process_telemetry": 90,
      "oom": 0,
      "planned": 90,
      "scheduler_wall_seconds": 2053.531069755554,
      "task_count": 90,
      "timeout": 0
    },
    "local_verified_intake": false,
    "next_action": "FETCH_VERIFY_INTAKE; no resubmission or new scientific task",
    "observed_at": "2026-10-29T10:58:47.267663+00:00",
    "remote_full_artifact_verification": true,
    "report": "ai4s/programs/dsainet/research/p0-pf-r1/status/STATUS_20261029T1058Z.md",
    "report_sha256": "f26a6a5b682f8148d6023728c091f437bba2388f66cb754b512e4735a013df6a",
    "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
    "scientific_effect_analysis": false,
    "snapshot": "ai4s/programs/dsainet/research/p0-pf-r1/status/TERMINAL_VERIFIED_20261029T1058Z.json",
    "snapshot_sha256": "f919081468fc997a7602ecf0153b80887ba3373ae8301662677e8ff532327534",
    "status": "COMPLETE_VERIFIED_REMOTE",
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
  },
  "last_p0_pf_r1_revalidated_analysis": {
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
  "last_p0_pf_r1_scientific_launch": {
    "audit_barrier_present": false,
    "audit_receipt_count": 0,
    "claim_created": false,
    "closeout_hours": 4,
    "contract_sha256": "259f683fa93b9910e311be410bbe058d394cb563b06fe38a5186624f1af03ccd",
    "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-SCIENCE-START-20261029",
    "fits": {
      "completed": 5,
      "failed": 0,
      "pending": 55,
      "running": 30,
      "total": 90
    },
    "gates": {
      "old90_reuse": "PASS",
      "original_five_arm_tech_reuse": "PASS",
      "science_cost": "PASS",
      "source_manifest": "PASS"
    },
    "next_action": "sameRun probe only;90fit success seal before90audit; no automatic next candidate or retry",
    "observed_at": "2026-10-29T08:04:05.085232+00:00",
    "old_run": "2026-10-29_dsainet_p0_pf_r1_science1-full-w1",
    "old_run_status": "INVALID_ENGINEERING_FAILED_PRESERVED",
    "original_start": "2026-10-23T21:28:00+08:00",
    "remaining_campaign_hours_snapshot": 27.02520291538345,
    "report": "ai4s/programs/dsainet/research/p0-pf-r1/PACKFIX1_LAUNCH_REPORT.md",
    "report_sha256": "10be83da4bdda971c39e609c748d7aebd4f14b5e239a995359e8aec34e3a3da9",
    "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
    "science_hours": 23,
    "scientific_effect_reading": false,
    "snapshot": "ai4s/programs/dsainet/research/p0-pf-r1/status/PACKFIX1_20261029T0803Z.json",
    "snapshot_sha256": "1a0b7c261805316117009c52223725a6979730ba7edb7335480914ce7549d314",
    "technical_retraining": false,
    "total_hours": 157,
    "transaction_hours": 27
  },
  "last_p0_pf_r1_technical_recovery": {
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
  "last_recovery_analysis": {
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
  "last_revalidated_key_delivery": {
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
  "last_round_evidence": {
    "decision_record": "ai4s/programs/dsainet/research/serial_screen_20261128d/closeout/DECISION.json",
    "evidence_id": "AI4S-DSAINET-LATERAL-HAND-READOUT-R1",
    "role": "exposed_development_source_screen",
    "round_id": "dsainet-b0-lateral-hand-readout-r1"
  },
  "last_status_check": {
    "automatic_monitor_enabled": false,
    "budget_limit_hours": 88,
    "checked_at": "2026-10-22T18:37:20.462148+00:00",
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
    "remaining_seconds": 32302.186585903168,
    "report": "ai4s/programs/dsainet/research/dsa-nrc-v0.1/execution/recovery_auditcache2_88/REPAIR_NOTES.md",
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "status": "RUNNING"
  },
  "last_technical_only_recovery": {
    "contract_sha256": "6f134af566aed6182fdf84eb92f4f1539ce0f32342c1b2c25ac4af1450b309eb",
    "cost_status": "BLOCK_NOT_AUTHORIZED",
    "evidence_id": "DSAINET-S0TECH1-TECHACCEPT1-CPU-RECOVERY-20261028",
    "follow_up_disposition": "CPU recovery complete. Preserve failed original Run; no training or scientific successor is authorized. Any later experiment needs separately frozen authorization and budget/cap decision.",
    "new_training_or_remote_node_dispatch": false,
    "recovery_receipt": "ai4s/programs/dsainet/research/p0-cue-r2-s0tech1-techaccept1/RECOVERY_ACCEPTANCE.json",
    "recovery_receipt_sha256": "65939afba21818d9bdef5ab3dc14bcccdf841d4bf40224f4029924705ce749e1",
    "report": "ai4s/programs/dsainet/research/p0-cue-r2-s0tech1-techaccept1/REPORT.md",
    "run_id": "2026-10-27_dsainet_p0_cue_r2_s0tech1-full-w1",
    "technical_acceptance": "PASS_OFFLINE_REPLAY"
  },
  "last_verified_intake": {
    "analysis_receipt_sha256": "4503cdd61c1f4130e82fdbaa406bccf9b168bd78258e40918783309a0e656425",
    "artifact_manifest_sha256": "906b206b5070f51531984e71d8b8efce7e8fe48abe80f56e5d68247c94af1efe",
    "contract_sha256": "e41316d9cbd5e9c994c5c3d26d9909e88182b9674c68f97d883c8ae7e47986e4",
    "full_payload_local": false,
    "intake_path": "ai4s/programs/dsainet/research/serial_screen_20261128d/closeout/intake",
    "intake_scope": "analysis_v1",
    "run_id": "2026-11-28_dsainet_b0_lateral_hand_readout_r1-full-w1",
    "run_status": "complete",
    "transaction_id": "2026-11-28_dsainet_b0_lateral_hand_readout_r1-tx",
    "transfer_bytes": 322145,
    "verified": true,
    "verified_at": "2026-11-28T11:05:58.563273+00:00"
  },
  "last_verified_preflight": {
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
    "preflight": {
      "environment_fingerprint": "bf35bef4379ad992a7b03065ba2ee977a1d9f5954654e75690e3fe93b428739c",
      "peak_memory_observed_mib": 909,
      "profile_kind": "frozen_tail"
    },
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
  "last_wmp_d1_stage_a_analysis": {
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
  "lifecycle_closure": {
    "analysis_sha256": "82ed2cdf8e2be595a495a5d7806374d44505950de37d0472f87762ba16a0818a",
    "artifact_manifest_sha256": "0e3956d5028517ae7f8fc33e91be70cfdb46b433e945d3bbc6a55282b0c2315f",
    "budget_compliance": "EXCEEDED_DURING_CLOSEOUT_INTAKE_ANALYSIS",
    "budget_limit_hours": 96,
    "budget_remaining_seconds_at_last_check": -1315.5931639671326,
    "closed_at_utc": "20261023T134933Z",
    "contract_sha256": "3666bec81ef4aab5bc6a437fb0fde27f9684f0c64f365b04be42ab29d40542ef",
    "evidence_id": "dsainet-nrc1-repair3-complete-20261023",
    "formal_claim_created": false,
    "frozen_gate_pass": false,
    "kind": "NRC1_LIFECYCLE_CLOSED_WITH_BUDGET_DEVIATION",
    "prior_last_decision": {
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
    "run_id": "2026-10-19_dsainet_dsa_nrc_v0_1_NRC1repair3-full-w1",
    "scientific_decision": null,
    "state_snapshot": {
      "path": "programs\\dsainet\\research\\p0-cue-r1\\execution\\lifecycle_snapshots\\STATE_before_NRC1_lifecycle_reconcile_20261023T134933Z.bin",
      "sha256": "67a74d9989ecae1bbee680b3025aff572042322e61e7725775799276ea26385a"
    }
  },
  "local_performance_supplement_preparation": {
    "authorization_ref": "ai4s/programs/dsainet/research/dsa-pfc-zhou-v0.1/AUTHORIZATION.json",
    "baseline_exp_id": "2026-10-09_dsainet_zhou2016_loso_full_local_w2",
    "candidate_id": "DSA-AEL-P0-FROZEN-20260927",
    "evidence_id": "LOCAL-DSAINET-PFC-ZHOU-20261010",
    "new_scientific_evidence": false,
    "old_campaign_reopened": false,
    "preparation_contract": {
      "path": "output/local/2026-10-10_dsainet_p0_zhou2016_loso_local_w2/CONTRACT.json",
      "sha256": "5f8f7cd9bff67ffa6bb1432e46b74606c936dbe731a6a5c605fa8ee4fdd27340"
    },
    "preparation_id": "DSA-PFC-ZHOU-20261010",
    "proposed_execution": {
      "automatic_retries": 0,
      "executor": "local GPU0",
      "max_seconds": 7200,
      "workers": 2
    },
    "proposed_matrix": {
      "epochs": 100,
      "loso_targets": [
        0,
        1,
        2,
        3
      ],
      "new_formal_fits": 20,
      "reused_B0_fits": 20,
      "seeds": [
        0,
        1,
        2,
        3,
        4
      ],
      "technical_fits": 1
    },
    "research_plan": "ai4s/programs/dsainet/research/dsa-pfc-zhou-v0.1/RESEARCH_PLAN.md",
    "status": "ARCHIVED_ANALYZED_VERIFIED",
    "user_request": "Add unchanged frozen P0 experiments on Zhou2016, using local GPU and the completed local DSAINet baseline."
  },
  "manual_budget_pause_accounting": [
    {
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
    {
      "authorization": "explicit_user_approved_single_interval",
      "end_boundary_basis": "10 seconds before first tool observation; registration processing remains charged",
      "end_utc": "2026-11-01T15:34:11.239164+00:00",
      "first_receipt_observation_utc": "2026-11-01T15:34:21.239164+00:00",
      "no_remote_tasks_running": true,
      "resume_at_end": true,
      "seconds": 288.291875,
      "source_request": "ai4s/programs/dsainet/research/ds07-r1/repair1/REPAIR_AND_BUDGET_PROPOSAL.json",
      "source_request_sha256": "d265db99b537298a4a30f9a4b3019467996b4fa4be0bd770092051fc2bebb636",
      "start_utc": "2026-11-01T15:29:22.947289+00:00"
    },
    {
      "approval_source_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/proofs/USER_APPROVAL266.json",
      "approval_source_sha256": "3da978a48b669541ea6fb4e831c1e90db762bc3a018a3303fb4887fff0589c69",
      "authorization": "explicit_user_approved_single_interval",
      "end_boundary_basis": "exact approval timestamp; subsequent processing is charged",
      "end_utc": "2026-11-02T11:43:00.395+00:00",
      "no_remote_tasks_running": true,
      "resume_at_end": true,
      "seconds": 29.361386,
      "source_request": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/BUDGET_REQUEST_20261102.json",
      "source_request_sha256": "731157931b5edc77618d96536fabf38e0823d4dceb05948dbf82da971a3d61ed",
      "start_utc": "2026-11-02T11:42:31.033614+00:00"
    },
    {
      "approval_source_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/EXPLICIT_TARGET_REPLY.json",
      "approval_source_sha256": "9fc0e3927efa3392330815e43a25538c227b2cbd5fe9d3c0e97536c5a48463fb",
      "authorization": "explicit_user_approved_single_interval",
      "end_boundary_basis": "exact user approval; subsequent work is charged",
      "end_utc": "2026-11-02T13:44:23.354000+00:00",
      "no_remote_tasks_running": true,
      "resume_at_end": true,
      "seconds": 1324.957177,
      "source_request": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/readerfix1/TRANSPORT_REQUEST.json",
      "source_request_sha256": "4cd4bb3706bea6546ea66d4e35add7b6ec87a812ff6079d992dab448b62c9f9d",
      "start_utc": "2026-11-02T13:22:18.396823+00:00"
    },
    {
      "approval_source_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/EXPLICIT_TARGET_REPLY.json",
      "approval_source_sha256": "e5613e9df8044c3e259a58c32955ba30f8075cdf7eb70e170e7ac6f2a2868242",
      "authorization": "explicit_user_approved_single_interval",
      "end_utc": "2026-11-02T16:43:58.805000+00:00",
      "no_remote_tasks_running": true,
      "resume_at_end": true,
      "seconds": 17.63702,
      "source_request": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/telemetryfix1/BUDGET_TRANSPORT_REQUEST.json",
      "source_request_sha256": "af57fa49bd338444d9a7e8f569e6f69018050e0da50b72cb0424849f33c07495",
      "start_utc": "2026-11-02T16:43:41.167980+00:00"
    },
    {
      "approval_source_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/EXPLICIT_TARGET_REPLY.json",
      "approval_source_sha256": "600cc78238ff5e94a4c35bcd6b1109f5966cc17e8554f5f79f88039d21c838ed",
      "authorization": "explicit_user_approved_single_interval",
      "end_utc": "2026-11-03T14:08:00.226000+00:00",
      "no_remote_tasks_running": true,
      "resume_at_end": true,
      "seconds": 435.111564,
      "source_request": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/summaryfix1/BUDGET_TRANSPORT_REQUEST.json",
      "source_request_sha256": "fcbd58420dbd3b8c25ac9a4baa0ee6a4d8e1e6321db9dbde8d4009e2afa3fa66",
      "start_utc": "2026-11-03T14:00:45.114436+00:00"
    },
    {
      "approval_source_ref": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/EXPLICIT_TARGET_REPLY.json",
      "approval_source_sha256": "181ee8c457ce45998cc06f3dabcad7c126a5ffeabde56d69974c5b7c64f25913",
      "authorization": "explicit_user_approved_single_interval",
      "end_utc": "2026-11-04T06:23:37.244000+00:00",
      "no_remote_tasks_running": true,
      "resume_at_end": true,
      "seconds": 883.630597,
      "source_request": "ai4s/programs/dsainet/research/ds07-r1/science_preparation/devicefix1/BUDGET_TRANSPORT_REQUEST.json",
      "source_request_sha256": "ce60ed7690718d2e675ef816570963d60acce2ef2f76e15569d09119121236f2",
      "start_utc": "2026-11-04T06:08:53.613403+00:00"
    }
  ],
  "manual_physionet_resume": {
    "additional_recovery_window_hours": 72,
    "authorization": "2026-10-02 user: restore remaining experiments with previous budget specification",
    "automatic_retries": 0,
    "capacity_unchanged": true,
    "contract_sha256": "2378525f6fc972bd100baf48aa64f57f765829970a9661f8e41ef4310a3e1770",
    "full_status": "RUNNING",
    "independently_verified": false,
    "launcher_alive_reported": true,
    "launcher_pid": 670939,
    "minimum_complete_fits_expected": 140,
    "old_run_id": "2026-09-30_dsainet_pfc_xds_v0_1_physionet_resume1-full-w1",
    "p0_unchanged": true,
    "receipt": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume2/USER_SUBMISSION_RECEIPT.json",
    "recorded_at": "2026-10-02T07:21:59.694263+00:00",
    "remaining_formal_fits": 950,
    "reused_formal_fits": 140,
    "run_id": "2026-10-02_dsainet_pfc_xds_v0_1_physionet_resume2-full-w1",
    "scientific_result": false,
    "script": "ai4s/programs/dsainet/research/dsa-pfc-xds-v0.1-physionet-resume2/RESUME_PHYSIONET.ps1",
    "script_sha256": "c3c3c8ccb7c2da99f33c5f78a486e37cbd8441fb1f432315b5775412bf5e881a",
    "status": "USER_REPORTED_RUNNING",
    "submitted_at": "2026-10-02T07:25:19.781988+00:00",
    "target_units": 1090
  },
  "manual_physionet_resume3": {
    "B0_failure_tasks": [
      "physionet_B0_s4_t23",
      "physionet_B0_s1_t24"
    ],
    "actual_failures": 2,
    "added_budget_seconds": 0,
    "automatic_training_retries": 0,
    "blocked_unattempted": 388,
    "contract_sha256": "aee609a64380758d4a035cee9c685b7012df890dbb9e655ce80f043d939fea28",
    "failure_causes": [
      "cuDNN backward algorithm failure",
      "CUDA OOM, 126 MiB requested, 63.94 MiB free"
    ],
    "new_completed": 131,
    "pending": 317,
    "query_time": "2026-10-04T16:44:06+08:00",
    "remaining_execution_hours_approx": 44.335,
    "reused_fits": 234,
    "run_id": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume3-full-w1",
    "running": 18,
    "scientific_intake": false,
    "status": "RUNNING_WITH_BLOCKED_B0_FAMILY",
    "target_receipts": 0,
    "total_completed": 365
  },
  "manual_physionet_resume4": {
    "added_budget_seconds": 0,
    "contract_sha256": "010305cae9048f2bc3080bc5bd77d666c3e278137409f4130971873f821199a2",
    "explicit_failed_B0_recovery_complete": [
      "physionet_B0_s4_t23",
      "physionet_B0_s1_t24"
    ],
    "failed": 0,
    "first_step_guards_failed": 0,
    "first_step_guards_ready": 30,
    "fit_commitment_mib": 2048,
    "fit_receipts": 404,
    "pending": 672,
    "query_time": "2026-10-04T19:17:22+08:00",
    "receipt_settlement_gap": 1,
    "remaining_execution_hours_approx": 41.82,
    "reused_fits": 388,
    "run_id": "2026-10-04_dsainet_pfc_xds_v0_1_physionet_resume4-full-w1",
    "running": 15,
    "scheduler_completed": 15,
    "scientific_intake": false,
    "status": "RUNNING",
    "target_receipts": 0
  },
  "next_execution_gpu_scope": {
    "authorization": "User2026-10-06: include all GPUs except2; if interruption required leave current experiment unchanged",
    "current_gpu_ids": [
      1,
      3,
      4,
      6,
      7,
      9
    ],
    "current_run": "2026-10-06_dsainet_pfc_xds_v0_1_physionet_resume9-full-w1",
    "current_run_modified": false,
    "deployed_scheduler_sha256": "57f2933cafb12967a7dbfd66cd46bc2d61a20c567b8dd1dcff28c836e3944cdc",
    "fit_commitment_mib": 2048,
    "public_reserve_mib": 0,
    "reason": "Deployed scheduler parses GPU list once at startup and checks it against frozen contract; no hot reload",
    "recorded_at": "2026-10-06T12:01:31.538681+00:00",
    "requested_gpu_ids": [
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
    "status": "DEFERRED_UNTIL_NEXT_IMMUTABLE_CONTINUATION"
  },
  "next_research_preparation": {
    "active_run_id": "2026-10-13_dsainet_rcd_v0_1_repair2-full-w1",
    "actual_audits": 0,
    "actual_new_fits": 0,
    "actual_new_source_audits": 0,
    "actual_new_technical_audits": 1,
    "actual_new_technical_fits": 0,
    "actual_new_training_fits": 0,
    "authorization_ref": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/AUTHORIZATION.md",
    "authorization_scope": "User explicitly requested launching the selected RCD design; one closed four-arm source screen and necessary qualification.",
    "budget_hours_authorized": 24,
    "campaign_id": "dsainet-rcd-v0.1-20261012",
    "chain_id": "dsainet-transaction-v3.1",
    "claim_status": "no_paper_claim",
    "contrast": [
      "P0-B0",
      "P0-S0",
      "P0-N0"
    ],
    "data_preparation_check": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/DATA_PREPARATION_CHECK.json",
    "design_change": "One trial scalar conditions four native depthwise grids from band-power persistence; fresh cue asset and subject-disjoint source validation/audit.",
    "design_check": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/DESIGN_CHECK.json",
    "design_spec": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/DESIGN_SPEC.yaml",
    "design_spec_sha256": "e3c7aebbe9ef9250a5f689bc20c831dd91cd9b7de288aee57547213c65f83874",
    "execution_authorized": true,
    "external_verdict": "REVISE",
    "intervention_id": "DSA-RCD-v0.1-TRIAL-CONDITIONED-COMMON-DW-SPACING",
    "judgment_change": "CRU is closed; structural preservation does not establish utility. RCD is an independently supplied hypothesis about same-trial conditional sampling spacing, distinct from fixed-tap KShape and tokenizer TKS.",
    "launch_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-repair1/LAUNCH_RECORD.json",
    "new_run_authorized": true,
    "new_scientific_evidence": false,
    "next_stage": "source_subject_disjoint_development_screen",
    "next_transition": "SCREEN_NEW",
    "old_budget_transferred": false,
    "old_campaign_reopened": false,
    "planned_formal_fits": 72,
    "planned_source_audits": 72,
    "planned_technical_audits": 4,
    "planned_technical_fits": 4,
    "preparation_id": "DSA-RCD-20261012",
    "recorded_at": "2026-10-12T11:44:04.403939+00:00",
    "remaining_requirements": [
      "production consumer closure",
      "immutable bundle qualification",
      "remote GPU technical lifecycle"
    ],
    "remote_asset_check": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/REMOTE_ASSET_CHECK.json",
    "repair_record": "ai4s/programs/dsainet/research/dsa-rcd-v0.1-repair2/REPAIR_CLOSURE.json",
    "research_brief": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/research_brief.md",
    "research_brief_sha256": "88d133c8f87e897d7bc9251d27c0c850f4ec034f77f463bee7d125ab19de6058",
    "research_id": "dsa-rcd-v0.1",
    "review_disposition": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/refine-logs/DISPOSITION.json",
    "review_status": "COMPLETED_WITH_REVISE_AND_WRAPPER_PROTECTION_WARNING",
    "role": "research_preparation_not_scientific_evidence",
    "run_id": null,
    "scientific_evidence": false,
    "source_bindings": "ai4s/programs/dsainet/research/dsa-rcd-v0.1/SOURCE_BINDINGS.json",
    "source_evidence_ids": [
      "AI4S-DSAINET-dsa-cru-v0.1-resume2",
      "AI4S-DSAINET-dsa-kshape-v0.1-repair5",
      "AI4S-DSAINET-dsainet-r01-tks-v0.1"
    ],
    "status": "TECHNICAL_REPAIR_PASSED_SCIENCE_RESOURCE_WAIT",
    "target_evaluation": false,
    "updated_at": "2026-10-12T12:17:43.164825+00:00"
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
    "night_budget_hours": 1.75,
    "queue_time_policy": "exclude_resource_wait",
    "round_index": 1,
    "started_at": "2026-11-28T08:38:23.662030+00:00"
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
  "updated_at": "2026-11-28T11:05:59.792927+00:00",
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
    "decision_record": "ai4s/programs/dsainet/research/dsainet-b0-patch-preelu-polyphase-r1_decision.yaml",
    "evidence_id": "AI4S-DSAINET-dsainet-b0-patch-preelu-polyphase-r1",
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
