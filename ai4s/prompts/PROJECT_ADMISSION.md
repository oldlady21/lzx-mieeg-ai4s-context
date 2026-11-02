# 项目接入与三级生成

1. 按基模查找已有 Program；同一基模的新 research 进入原 Program，不按 idea 新建 Program。无对应 Program 时读取活动链的共享 L1/L2、用户长期目标、必须保留模块和探索边界；新工作默认采用 v3.1 研究与执行规则，既有 Program 的活动 Run、campaign 和冻结续接继续遵守其绑定版本。
2. 定位 Program、State、Evidence Index、handoff、训练/分析入口及数据协议；逐项记录来源和 VERIFIED/INFERRED/MISSING。
3. 生成独立 L3：长期目标、稳定事实地图、研究接口、数据与指标风险、能力引用。L3 必须说明“论文问题→可证伪干预→最小配对检验→结果去向”的接口；诊断按是否改变取舍决定，当前候选、预算、Run 和结果留在动态层。
4. 运行候选链兼容检查，核验准确路径、父版本、单位和 stage/arm。v3 `SCREEN_NEW` 只核对单份 `research_brief` 的路径和 SHA-256；旧链继续核对 Problem/Literature/Implementation 三卡。新 campaign 的 continuation policy 使用 `evidence_to_design_v1`；新执行授权必须包含 `research_scope.question_id`、`data_scope_id`、`allowed_stages`、`allowed_module_ids` 和 `allow_new_module`，新合同的 `governance_binding` 精确键为 `chain_id`、`continuation_policy_version`、`campaign_id`、`question_id`、`data_scope_id`。缺少科学关键事实保持草案，可选能力按实际 readiness 标记。
5. 将 L3、兼容报告及新旧差异完整交用户确认；确认后只更新对应 Program 的活动链。诊断支持只有在能映射到具体设计时才形成后续训练准备，筛查正信号优先补同一对象的关键证据缺口。
6. 接入不创建 campaign、不转移母项目执行权限、不自动释放 claim。跨 Program 只共享问题、控制方法和证据引用，不迁移结果或运行权限。既有活动 Run 绑定旧规则完成收尾。

输入清单：project_id、用户长期目标、保留模块、允许探索/禁止边界、研究来源、Program 路径、状态和证据入口、executor profiles。v3 新候选还需一份包含问题/文献/实施/对照的 `research_brief`，以及唯一冻结的 Transaction v2 科学配置。

新接入或修改执行接口时，按活动 L2 第4节核对训练产物、任务回执、读取校验与节点汇总之间的真实衔接，并标明工程样本与生产技术门各自覆盖。三级保留项目特有接口及边界，共享验收规则由 L2 统一维护；接入兼容 PASS 只证明所检查的身份／路径，不代表技术运行已通过。

新执行路径接入的部署、资源与恢复规则统一读取 `TRANSACTION_RUNTIME.md` 的“执行可靠性与设置校准”“新工作的部署、预算与恢复”“新启动接口的离线验收”。新包的合同派生资源、runtime身份及静态兼容信息从“包内资源策略摘要”核对，不能据摘要认定GPU验收通过。三级只保留模型差异，旧活动对象沿原绑定；接入不启动实验。
