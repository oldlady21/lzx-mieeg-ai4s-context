# State 阅读分段 2

完整脱敏文件：`ai4s/programs/dsainet/research/STATE.yaml`（[原文件](../STATE.yaml)）。

完整公开文件 SHA-256：`1f0d9357fbcff9406eb24e153a516868f12970335d8e748c39b3ff11220c1289`。UTF-8 字节范围：[500000, 952349) / 952349。

这是连续文本片段，可能从 JSON 字段中间开始；按分段顺序拼接代码块可恢复完整脱敏正文。不是单独有效的 State，也不授予执行权限。

```yaml
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
    }
  ],
  "follow_up": {
    "action": "STOP_FIXED_PF_R1",
    "automatic_next_round": false,
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
    "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-REVALIDATED-ANALYSIS-20261029",
    "run_id": "2026-10-29_dsainet_p0_pf_r1_science1-packfix1-full-w1",
    "standard_verified_intake": false,
    "status": "COMPLETE"
  },
  "last_decision": {
    "decision": "NO_SIGNAL_STOP_FIXED_ORD_EC",
    "evidence_id": "DSAINET-P0-ORD-EC-R1-VERIFIED-ANALYSIS-20261031",
    "neural_training_eligible": false,
    "new_experiment_authorized": false,
    "role": "exposed_source_development_fixed_parent_bounded_readout_screen",
    "round_id": "p0-ord-ec-r1-science-1"
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
    "decision_record": "ai4s/programs/dsainet/research/p0-pf-r1-science1-packfix1_decision.yaml",
    "evidence_id": "DSAINET-P0-PF-R1-PACKFIX1-REVALIDATED-ANALYSIS-20261029",
    "role": "exposed_development_revalidated_analysis"
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
    "analysis_receipt_sha256": "69d69b9ea081523aa0663315d2a9f1fbee3b56498facd725242839815367b42e",
    "artifact_manifest_sha256": "1400fc1ecac5224fa9f4a63a906f8095e1d194c065a24b89a4321f632d6a21a7",
    "contract_sha256": "a12e54ae3ce0cf46bef48286ede40f6f1712d7dc231741e27922d71805a1dce5",
    "full_payload_local": false,
    "intake_path": "ai4s/programs/dsainet/research/p0-ord-ec-r1/verified_intake",
    "intake_scope": "analysis_v1",
    "run_id": "2026-10-30_dsainet_p0_ord_ec_r1_science1-full-w1",
    "transaction_id": "2026-10-30_dsainet_p0_ord_ec_r1_science1-tx",
    "transfer_bytes": 13495094,
    "verified": true,
    "verified_at": "2026-10-30T20:31:27.753228+00:00"
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
  "paused": false,
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
    "night_budget_hours": 266,
    "queue_time_policy": "exclude_resource_wait",
    "round_index": 0,
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
  "status": "WAITING_REMOTE",
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
  "updated_at": "2026-11-02T15:46:48.540867+00:00",
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
