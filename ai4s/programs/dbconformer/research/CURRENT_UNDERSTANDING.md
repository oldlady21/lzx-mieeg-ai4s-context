# DBConformer：当前研究理解

## 基模来源与认识边界

同一论文的加工材料不作独立证据计数。路径从本文件位置解析：

| 材料 | 用途 |
|---|---|
| [DBConformer-paper.md](../../../../refs/paper-cards/dbconformer/DBConformer-paper.md) | 原文读取材料 |
| [DBConformer-paper-card.md](../../../../refs/paper-cards/dbconformer/DBConformer-paper-card.md) | 贡献与证据边界 |
| [DBConformer-paper-xray.md](../../../../refs/paper-cards/dbconformer/DBConformer-paper-xray.md) | 设计推演 |
| [DBConformer-note.md](../../../../refs/paper-cards/dbconformer/DBConformer-note.md) | 综合理解 |

### 基模设计理解

作者报告：T-Conformer先混合通道并保留时间patch，S-Conformer按通道提取局部时间特征、沿时间池化后保留通道token；两路Transformer输出拼接分类（X-Ray §1–4；Note §1–3）。阅读解释：关键取舍是保留哪一维作为后续注意力可直接比较的token；时间支路仍含空间混合，空间支路也含时间编码。论文消融支持整条S支路/注意力汇聚在所测设置中的作用，但未证明空间token是唯一增益原因，也未证明两路统计独立。当前实现以 `src/models/dbconformer/baseline.py`、`src/baselines/dbconformer.py` 为核对入口；EA不等同类别分布对齐。独立补充表S1/S6未提供，依赖它们的结论保持未知；本地各方法增量与关闭边界见下方证据记录。

下文区分作者报告、阅读推断、实现和本地实验证据；局部筛查只约束其冻结范围。重要认识附适用条件、直接依据和可能改变判断的新证据。历史轮次链接原报告；运行态只读 STATE.yaml。论文材料提出的问题不限定该Program的全部研究范围。

## 当前综合、反例与未决问题

**2026-11-09 DBF-A 概念核对。** SCR 两臂都跨试次重组，只改变供体被试一致性。独立编码后可构造无波形接缝的配对对照，原生全段 T 卷积及 S 池化不满足窗口隔离。合成反例表明，固定单窗边际仍可改变加性读出 CE，原差值判据不足。只保留固定局部表征上的加性与低阶交互诊断，尚无独立确认和论文核心资格。0 新拟合与推理。[概念记录](reassessment_20261106_post_source_coverage/dbf_a_cross_window_concept.md)。

**2026-11-09 本试次提示前基线停在冻结前。** 2a 原 GDF 的 5,184 个开始与类别标记均隔 500 样本，2,139 个左右手试次通过名义共同条件。Dreyer 前两轮是假反馈，Cho 有 52 人独立顺序档，尚缺原矩阵与 run 对账及独立资格。后续只筛解剖侧与优势手能否区分逐人错误风险，未选定论文核心。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/pre_cue_baseline_pairing_qualification.md) · [来源核验](reassessment_20261106_post_source_coverage/pre_cue_baseline_pairing_source_audit.json) · [后续筛查](reassessment_20261106_post_source_coverage/hand_dominance_risk_screen.md)。

**2026-11-09 下一轮方向筛查。** 保留停止想象及生动度的原裁决。优先核同一左右手想象窗使用本试次提示前基线，能否优于同 run 等量历史基线与因果滚动基线。2a 有名义连续开发窗，Dreyer 与 Cho 的原始时序、暴露和独立角色待核。ds007221 的 14 人双 Graz 会话无可追溯环境及实际次序，真实故障与 EEG–MEG 的配对复核也缺资产。当前无合格论文核心，0 新拟合与推理。[筛查与停止条件](reassessment_20261106_post_source_coverage/pre_cue_baseline_pairing_screen.md) · [环境语料核验](reassessment_20261106_post_source_coverage/environment_mi_screen_source_audit.json)。

**2026-11-09 停止想象指令后的原手别输出停在冻结前。** González-Villar 2016 的停止音按计划在箭头后 300 ms 播放，箭头持续 500 ms。只有无声继续，缺可复核的物理时点与独立想象启动证据。2022 加了等亮度绿箭头继续，仍无同声继续或合格独立复核。后续初筛中，Leeuwis 与 Cho 的问卷粒度和 YOTO 的任务都无法满足逐试次左右手自评，当前无合格核心方向。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/imagery_stop_command_qualification.md) · [来源审计](reassessment_20261106_post_source_coverage/imagery_stop_command_source_audit.json) · [后续初筛](reassessment_20261106_post_source_coverage/trial_vividness_screen.md)。

**2026-11-09 同动作跨想象策略停在冻结前。** Yang 2021 的两次 ME→KMI 与两次 VO→VMI 只支持任务组合的名义跨会话比较，策略与前置活动完全绑定。PMC 原始论文附件未发布逐试次 EEG 或轨迹，5 V TTL 只报告会话前同步。Zapała 公开目录只有派生表，Inamoto 只有单动作方向，未取得同估计量确认。下一项仅筛停止想象指令后的原手别残留输出。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/imagery_strategy_transfer_qualification.md) · [来源审计](reassessment_20261106_post_source_coverage/imagery_strategy_source_audit.json) · [后续初筛](reassessment_20261106_post_source_coverage/imagery_stop_command_screen.md)。

**2026-11-09 同听觉手别指令的睁闭眼方向停在冻结前。** Brandl 16 份原始 MAT 共 96 个反馈 run，两条件在同一阶段且先后可变，事件支持等量同试次名义配对。缺逐试次闭眼与独立眼电，静息 alpha 只支持静息操纵，既往反馈与在线自适应未隔离。Zapała 2023 是 24 人的策略研究，初筛所链接的单人说法更正，仍无同任务独立复核。下一条仅筛同动作跨想象策略。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/eye_state_auditory_mi_qualification.md) · [原件审计](reassessment_20261106_post_source_coverage/eye_state_auditory_source_audit.json) · [后续初筛](reassessment_20261106_post_source_coverage/imagery_strategy_transfer_screen.md)。

**2026-11-09 同一手别提示下的误触发停在冻结前。** Kaya 七人公开清单显示两种条件分会话，F/M 名义次序与论文统一描述冲突。K 两份原件重核后保留 319 对同手别、同前提示和等长前后窗。两份第 22 列同步可复算，但 marker 由该列对齐回填，无法校验真实屏幕刷新。其余六人未取得可复算原件，现有独立近邻缺同估计量。下一项只筛相同听觉指令的睁闭眼条件，尚无合格核心。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/same_cue_passive_activation_qualification.md) · [原件审计](reassessment_20261106_post_source_coverage/same_cue_passive_source_audit.json) · [后续初筛](reassessment_20261106_post_source_coverage/eye_state_auditory_mi_screen.md)。

**2026-11-09 坐站姿势间想象方向判别停在冻结前。** 两人四原会话抽查 34 个触发，22 人转换事件支持名义等量同测试，但同箭头分别包含实际起始姿势下的转换和静态意图。转换记录首个姿势均为坐，原件抽查有两种编排与肌电覆盖缺口，圆形静息无法匹配箭头提示，无同估计量独立复核。下一条初筛为 Kaya 相同手别提示下被动观看的误触发，候选顺序和独立精度待核。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/posture_direction_transfer_qualification.md) · [原件审计](reassessment_20261106_post_source_coverage/posture_direction_source_audit.json) · [后续初筛](reassessment_20261106_post_source_coverage/same_cue_passive_activation_screen.md)。

**2026-11-09 视觉／听觉提示切换停在冻结前。** Choi 有名义双向组合，未取得原始试次、实际声光时点、实采次序或只提示不想象。BCI IV-1 的 4 个真人固定先视觉后语音，时程和环境一并变化；Samek 五人的左手／足部材料未核定可用原件。固定晚窗、同提示不想象和独立精度是后续门槛。转入坐站起始姿势的四码筛查，仍需先解决动作语义及独立复核。0 新拟合和推理。[停止记录](reassessment_20261106_post_source_coverage/cue_modality_transfer_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/posture_direction_transfer_screen.md)。

**2026-11-09 留出想象握力等级停在冻结前。** 2024 全部 60 份原件有等量跨文件名义配对，0% 段是想象松手，公开原件缺同步 FDS EMG 与真实触发。2025 的 200 份规范文件每人每档只有一次独立录制，另有一份哈希重复，无法分开换力度与换文件。两批缺可追溯的跨力度次序与合格独立复核。保留等量同试次、仅提示、仅真实文件次序及逐人误激活与漏检的设计约束。下一项只筛跨提示模态下晚期想象窗的排序与风险，已有直接近邻且缺合格语料。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/imagined_force_transfer_qualification.md) · [原件审计](reassessment_20261106_post_source_coverage/imagined_force_transfer_source_audit.json) · [后续筛查](reassessment_20261106_post_source_coverage/cue_modality_transfer_screen.md)。

**2026-11-09 留出动作左右侧判别停在冻结前。** IMU-MI_A 原 DPA 的五人文件开始顺序相同，25 份原 CEO 中 24 份共用一个经典左右码序列。抽查 5 份 CDT 的 664 个事件与 Trigger 低字节完全对齐，但没有独立左右码表、实际屏幕锚或双侧 EMG 标定。双阶段时长与文档不合，且大部分文件缺阶段码。等量共用测试在名义上成立，动作与区块无法拆分，独立复核未合格。后续保留想象力度留出线索，当前无合格论文核心方向。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/effector_side_transfer_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/imagined_force_transfer_screen.md)。

**2026-11-09 左右半球镜像一致性停在冻结前。** 2a 原 GDF 头和 OpenBMI 原 MAT 通道顺序已核，二者同名闭合交集 21 导，OpenBMI 缺 FCz 且有两个颞侧标签未配对。2a 左乳突参考无法合成真实对侧参考。已有原／镜像同参数双前向前作，OpenBMI 亦已被 DBConformer 原论文使用。保留同试次合成诊断，真实手别错误与个人风险单独判读。随后筛查留出动作类型的左右侧判别，公开 IMU-MI_A 仅 5 人且动作、区块与独立复核未闭合，仍无合格论文核心方向。0 新拟合与推理。[停止记录](reassessment_20261106_post_source_coverage/hemisphere_reflection_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/effector_side_transfer_screen.md)。

**2026-11-09 注视方向与想象手别停在冻结前。** Eye-BCI 原提示日志只有手别，三份有公共锚的抽样会话每手至多 0–6 对自然反向偏移，另两份无 Tobii 共同时钟。Shin 同步 HEOG/VEOG 可作代理，未独立操纵注视。Meng 已研究左右手 MI 与注视交叉，原始数据须材料转让且未获可复核配对。现有材料仅支持条件关联。随后筛查左右半球镜像一致性，保留合成诊断边界及直接前作，当前仍无合格论文核心方向。0 新拟合和推理。[停止记录](reassessment_20261106_post_source_coverage/gaze_hand_decoupling_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/hemisphere_reflection_screen.md)。

**2026-11-09 短休恢复方向停在冻结前。** MI-rest/MI-rTMS 两组均休息，分别配假刺激与真刺激。两份原始 BDF 能定位四个 50 标记区块，不能直接由标记间隔复算休息和刺激起止。Evetović 的原始文件有 8 人的配对区块，但控制会话为被动观看，缺少等量左右手探针及可对齐的个体疲劳量。Yang、Pan、Kaya 缺相同休息对照，未满足独立复核。后续仅保留眼动与手别可区分性的筛查线索，当前无合格论文核心方向。0 新拟合和推理。[短休停止记录](reassessment_20261106_post_source_coverage/fatigue_recovery_qualification.md) · [眼动方向筛查](reassessment_20261106_post_source_coverage/gaze_hand_decoupling_screen.md)。

**2026-11-09 Wang 感觉引导联合训练停在冻结前。** CMU v1 三随机臂 31 人均有两次会话的首轮候选文件。联合学习和触觉对照的抽样首轮均无在线输出字段，BCI2000 对照的真实反馈状态仍有论文表述冲突及状态缺口。NEMAR 转换丢弃短段，另缺触觉组一人，保留计数不作为物理剂量。缺少原始显示/触觉日志及同估计量独立复核，故该资料只支持来源与配对资格核查。已继续筛查等剂量左右手 MI 后的短休恢复对照，现有两份材料均无法同时支撑共同探针与独立确认，仍无合格论文核心方向。0 新拟合和推理。[Wang 停止记录](reassessment_20261106_post_source_coverage/sensory_training_retention_qualification.md) · [短休方向筛查](reassessment_20261106_post_source_coverage/fatigue_recovery_screen.md)。

**2026-11-09 真实反馈向无反馈测试资格核验**。随机真／假反馈近邻的共同开环前后测是右手想象与放松。BMI-HDEEG 公布事件缺分组和回放配对，EDF 抽查有试次越界。Dreyer 左右手条件的假与真反馈按校准／在线固定排序。未获得共同左右手无反馈前后测及独立复核，停在冻结前。下一项只筛感觉引导训练包是否改变下一会话的无辅助校准选模。[停止记录](reassessment_20261106_post_source_coverage/feedback_contingency_transfer_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/sensory_training_retention_screen.md)

**2026-11-09 同一声流注意要求资格核验**。Brandl 原始事件可识别新闻、无分心、数字搜索和反馈，未发布可配对的原始新闻声流及主动／被动操纵。双任务前作无相同声流和延后答题证据，也未找到合格独立语料。停在冻结前。后续仅筛真反馈训练后的相对模型优势能否留到统一无反馈测试，尚无核心资格。[停止记录](reassessment_20261106_post_source_coverage/auditory_attention_interference_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/feedback_contingency_transfer_screen.md)

**2026-11-09 外部决策截止资格核验**。PhysioNet 327 份任务事件侧车及 18 个任务 EDF 已核，12 个异常 run 的事件采用原始 EDF 内嵌标注。旧整段预处理在合成检查中读入截止后信息；T0 只支持协议休息，独立自由空闲及风险精度未闭合，停在冻结前。下一项初筛同声流下主动与被动注意的差异，当前仍无合格论文核心。[截止停止记录](reassessment_20261106_post_source_coverage/decision_deadline_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/auditory_attention_interference_screen.md)

**2026-11-09 真实动作选模资格核验**。Eye-BCI 的原始 E-Prime 日志和派生事件支持 51 个同人同会话 ME／MI 配对；跨独立后续 MI 运行有 16 人，档案最多 17 人。SEFMEID V5 受限，原始配对与时序未知，停止方案冻结。下一项只筛相同因果前缀下外部决策截止是否改变排序和逐人风险，尚无核心资格。[停止记录](reassessment_20261106_post_source_coverage/me_proxy_model_selection_qualification.md) · [后续筛查](reassessment_20261106_post_source_coverage/decision_deadline_screen.md)

**2026-11-09 下一方向筛选**。保留 ds008446 停止原判，把实际区块可追溯、独立确认和全试次与匹配子集分开判读列为设计约束。优先核“少量真实动作能否在固定源域模型之间选出后续 MI 更可靠的解码器”。以源域固定规则、等量目标 MI 选模、标签置换作对照。PhysioNet 为开发资料，Eye-BCI 与 SEFMEID 待核次序、校准和测试隔离及独立精度。尚未进入冻结，SGP 直接优化继续停止。[选择依据和停止条件](reassessment_20261106_post_source_coverage/me_proxy_model_selection_screen.md)

**2026-11-08 ds008446 提示顺序资格核验**。原始 CSV 的四段 Marker 支持转换表时钟修正。区块日志和运行侧车均标 10∶10，但有 12/20 人互相冲突，EDF 时戳不能裁决。同人、同转移、等窗的宽位置配对有 661 对，精确位置仅 111 对，且未找到独立复核采集。停在方案冻结前，保留全风险集与匹配子集分开判读的设计约束。[核验与停止](reassessment_20261106_post_source_coverage/cue_order_predictability_qualification.md)

**2026-11-08 Liu 来源分组核验**。三对的原始发布 EDF 和 NEMAR 转换件呈信号重叠或高度相似。原始 MAT 的带内相关较弱，公开材料未闭合采集身份。20+20 事件支持名义等量替换，三个疑似来源簇及缺少独立语料限制排序和个体风险判断。停在冻结前，保留完整性记录。下一项筛提示顺序可预测性及提示前后模型差，先核原始事件钟与独立语料。[停止记录](reassessment_20261106_post_source_coverage/liu_provenance_qualification.md) · [后续筛选](reassessment_20261106_post_source_coverage/cue_order_predictability_screen.md)

**2026-11-08 EA 未来批次回放资格**。Zhou 原始八窗抽查提示高幅，18/22 导与已核 2a 权重吻合，未定位匹配固定权重及独立确认，停在回放前，效果未知。下一方向核公开 ID 与独立采集来源是否一致，以来源簇隔离与等训练量 ID 隔离的配对差为候选，尚无核心方向。[回放停止记录](reassessment_20261106_post_source_coverage/ea_context_replay_gate.md) · [方向筛选](reassessment_20261106_post_source_coverage/provenance_group_split_screen.md)

**2026-11-08 未来批次依赖核验**。原生整批 EA 的同试次合成配对可变；原生 LOSO 实际评分用逐试次 EA。固定早期校准和不读目标批次均严格不变。Zhou 有 120 个会话具元数据配对支持，真实模型排序、逐人判定和独立确认仍未知。[代码、合成与停止判据](reassessment_20261106_post_source_coverage/ea_context_qualification.md)

**2026-11-08 Shin 反馈限速原始核验**。110 文件头、40 个 CV 原件哈希及 960 段状态已核，9 人四档同序、S01 名义 300 异日且参数异常，全试次共同窗口仅 0.128 秒。与次序无法分离，独立复核未闭合，停在描述层。下一项筛固定同一试次时未来批次组成是否改变 EA 下的模型选择，仍为设计。[限速资格核验](reassessment_20261106_post_source_coverage/shin_feedback_qualification.md) · [下一方向](reassessment_20261106_post_source_coverage/ea_context_invariance_screen.md)

**2026-11-08 外周干扰资格核验与下一方向**。Cho 非任务干扰和 Jeong 真实动作可作外周测量正对照，独立左右头皮耦合尚未识别，同一 MI 试次的真实等剂量方向对照停在冻结前。下一项核闭环参数变化是否使离线模型排序改变。Shin 2022 有参数族内随机次序和四档光标限速目录，尚须追溯原始 run、时间窗和独立确认。[外周停止记录](reassessment_20261106_post_source_coverage/peripheral_mapping_qualification.md) · [反馈方向筛选](reassessment_20261106_post_source_coverage/feedback_policy_rank_screen.md)

**2026-11-06 最小切换诊断与下一方向筛选**。固定当前类的两种切换用于判定错类分数是否向上一类偏移，切换对重复用于估计总体困难。Jeong 仅作跨任务复核候选，独立确认人数与精度未闭合。保留机制冻结前停止。下一项只核外周干扰方向是否有独立校准与可追溯的头皮测量映射，论文核心方法仍未选定。[描述性诊断](reassessment_20261106_post_source_coverage/switch_descriptive_plan.md) · [方向筛选](reassessment_20261106_post_source_coverage/peripheral_shortcut_screen.md)

**2026-11-06 上一类偏移概念核验**。Zhou 严格匹配有 982 个前类配对，20 人三类均有支持。类别配额产生前后标签依赖，严格未来比较只有 151 对，同格四组合只剩 2 人。未来类仅作辅助诊断。Jeong 三抓握事件有独立采集且跨任务匹配支持，原始边界、计时和确认角色待核；2a 保留既有暴露。使用两个错误类别之间的分数份额，与切换对重复的总体损失分开判读。[概念核验与停止条件](reassessment_20261106_post_source_coverage/switch_predecessor_concept.md)。

**2026-11-06 来源复访再核与下一方向**。Yang 仍缺可追溯日序；Stieger 的日期、随机组和一维左右任务码有作者定义，但原版与 EEG 共封装，公开转换件未保留可直接核验的映射。保持跨日复访冻结前停止。下一项优先核验多类指令切换后是否定向偏向上一类，以固定当前类及同一候选错误类、未来类别安慰剂和简单模型区分一般切换困难。Zhou 事件的六类有向对已有粗支持，尚无确认队列或论文核心方法。[复核与下一方向](reassessment_20261106_post_source_coverage/research_brief.md)。

**2026-11-06 来源数据配置资料核验完成**。处置 `NOT_QUALIFIED_CURRENT_ASSETS / STOP_BEFORE_FREEZE`。Ma、Yang 和 Zhou 七日数据的公开事件计数足够，但 Yang 51 人仅 20 人的三个扫描日期与会话编号同序，两个转换均复现该差异。Zhou 来自独立团队，公开日期列不能复核日序，按原 12 名来源人的配置最多剩 8 名独立确认目标。要重开须取得权威访视映射并补足独立确认精度。[资料资格核验](reassessment_20261106_source_coverage/asset_qualification.md)。

**2026-11-06 来源数据配置核验（仅设计）**。已完成上轮独立视觉刺激的限定资产核验，未找到合格的现成同人四格 MI 数据，停止该实例。将下一项资料核验转为固定原始试次数、被试×访视单元数及访视构成下，比较增加来源被试与对同一来源被试跨日复访，重点检验未见被试的后续访视。2026 年 EEG scaling 预印本已经比较等窗口量的人数与每人窗口分配，区别限于真实复访和后续访视交互。Ma 2022 与 Yang 2025 的协议具备候选结构，文件、暴露和独立确认仍待核。当前未选定论文核心方法或授权 Run。[选择依据、关键对照与停止条件](reassessment_20261106_source_coverage/research_brief.md)。


**2026-11-06 PJDD 后方向重评**。当前裁决 `NO_QUALIFIED_DIRECTION`。SGP 的均值与个体风险分开，几何 R1 和 PJDD 的描述性观察不足以确定方法效用。优先保留一次资料核验，寻找能在同一被试中独立分配视觉刺激方向和指令想象手的范式。2a 与已核 Eye-BCI 的类别线索仍绑定，Trocellier 等已有 cue 起点切窗对照。若无独立交叉资产就停止此实例。若查到资产，只进入诊断设计，估计指定刺激对解码输出的总效应，并用任务负荷、训练关联及同输入简单模型限制解释。固定试次数下的来源人数与采集块覆盖暂列备选。Grok 原判与处置见[本轮简报](reassessment_20261106_post_pjdd/research_brief.md)。

**2026-11-05 几何R1后下一轮重评（仅设计）**：完整比较三视角六候选并限定核对一手前作，当前仍无论文核心方法；独立Grok原判NO_QUALIFIED_CORE_DIRECTION、备选NONE，主Agent接受。只把“可独立识别的测量迁移能否与神经/任务差异分开”作为有退出条件的资料/理论问题，不接受模板inverse＋loss或低秩/平滑的换名版本。共享模板不观测个体L_s，前向零重建可能代数恒可满足，破坏算子还可能被后层学回；须先关闭识别、非等价控制及真实测量资产缺口。原几何合同仅注册四项EEG/标签/身份/metadata，未注册个体测量识别材料，不据此声称外部不存在。若这些门不能关闭，停止该实例及同信息等价改名扩展，不把L1检索或L2拒判递补核心。原宿主源码另更正T显式radix=1，不把默认radix=2当实际多尺度或性能缺陷。0新训练/前向/EEG特征目标分析/Run/合同/预算/Claim，SGP直接优化和旧几何对象仍停止，State/旧合同与成本不变。审后控制补充是主Agent修订，未伪称外审改判。[选择依据、关键对照与停止条件](reassessment_20261105_post_geometry/research_brief.md)、[原判与处置](reassessment_20261105_post_geometry/review/DISPOSITION.md)。

**2026-11-05 源内识别R1完整收尾**：4次100epoch/3600步、单次attempt全部完成，原SCI封装错误经同Run元数据重放恢复，0重训；远端全量核验、2.89MB精简回传/intake、冻结分析、独立全特征重算与标准决策已完成。INCONCLUSIVE/STOP：16个C均正，但仅11/16观测过噪声相对门、4/8人在两个encoder下均过，不满足冻结全面一致性。正号不是信噪保证，不能选择子组/更佳encoder补救；不支持据此建session关系loss，也不证明整个类别几何家族无效。共享encoder和历史暴露保留，0Claim/后继。State暂停、无活动Run，SGP直接优化继续停。[结果、局限与处置](source_geometry_r1/FINAL_REPORT.md)。下方启动段均为历史快照。

**2026-11-05 源内识别R1已启动（SGP仍停止）**：用户已明确授权补齐执行并启动4编码器，取代此前“仅设计/预算未分配”阶段限制。24h独立预算、原锚15:00Z计准备；A/B×两拟合会话、seed3/100epoch固定final，4SCI+1零拟合TECH，0重试/后继。真实GPU64样本前向exit0、峰值1217MiB；首次node因published缺transaction_id汇总失败，已保留原件并由原冻结消费者验证唯一父身份的派生补齐，0重执行后恢复同一Run。当前1运行/3待调度/0完成/0失败，无科研结论；4项完整后才核验/intake/冻结分析并停止。SGP直接优化、旧判和旧账保持关闭。[启动与封装恢复](source_geometry_r1/STARTUP_REPORT.md)。

**2026-11-04 下一轮源内识别准备**：冻结meta哈希核验，固定排除subject0后8名source共4608条，16个subject×session单元每类72条；每单元6个实际采集run按排序序号交错成两半，每半每类36条，cue窗不重叠但不宣称独立。旧BPM审计四文件SHA与冻结资产一致，逐run滤波源码和helper身份已回查，未重读波形。提出A/B互斥4人组×拟合会话交换的4编码器草案，查询人两会话均不参与其拟合；融合classifier输入预期80维，当前forward只返回logits，尚未抽取。来源已暴露、共享编码器依赖和普通CE解释仍保留；只有元数据可行性成立，尚无关系复现结果、主方法或执行资格。0拟合/forward/目标效果分析，预算UNASSIGNED，SGP直接优化仍停。[角色、描述量与待冻结判读](reassessment_20261104_post_sgp/source_identification_design/PROTOCOL_DRAFT.md)。

**2026-11-04 用户停止SGP直接优化并重选核心问题**：SGP均值改善、个体风险失败及机制未分离均保留为后续设计约束；不再默认补梯度方向遥测、受限投影、强度/阈值/分组/Adam变体，旧预算不转移。该最新明确停止更新下方历史条件性后继的优先级，不追改科学结果。三视角6候选归为5类后，尚无一项具论文核心方法资格；优先设计“编码器未接触的源会话/源被试上，类别相对关系是否含超出普通分类几何与采样噪声的可迁移信息”。这是有退出条件的源内识别问题，不先指定新loss/训练臂。Grok原判NEEDS_REVISION，主Agent已按训练暴露与RKD/SupCon反驳重写，未再次外审；K=2归一恒定与K≥3近单纯形退化是纸面反例，实际数据未测。0新拟合/forward/数据分析/Run/预算/Claim，State不变。见[下一轮方向与控制](reassessment_20261104_post_sgp/research_brief.md)、[SGP设计约束](reassessment_20261104_post_sgp/SGP_DESIGN_CONSTRAINTS.md)。

**2026-11-04 SGP梯度冲突与风险归因（仅旧证据）**：54任务/621000步全轨迹与合法源metadata、最差配对预测已核对。P/C冲突触发38.70%/36.14%，风险两例并非最大冲突/改变量，且相对改变量与负余弦在非退化对称投影下数学等价，不能作双证据。增强与实际Adam的组别方向、session结构及共享BN替代解释未区分；整体源验证改善也未预警两处目标风险。第一阶段完成但机制INCONCLUSIVE，第二阶段门未满足，0新候选/0训练，保持暂停。用户第三阶段“若唯一新受限候选仍均值改善却失败个体风险则终止方法线扩展”已记录，未假装新实验已发生。[诊断与处置](sgp_r1_budget1/attribution_20261104/REPORT.md)。

**2026-11-04 SGP-R1 budget1 冻结收尾**：54SCI及3旧TECH复用已完成核验/intake/分析/决策；P-B0 +1.2539pp（p=.0234375）、P-C +1.9387pp（p=.00390625），均有平均统计改善，但各1/18配对低于−3pp（subject7 seed3对B0−3.125pp，seed4对C−3.6458pp），冻结判定GROUP_STRUCTURE_UTILITY_NOT_ESTABLISHED_STOP。关闭固定实例，不放宽风险门或事后剔人；不把9人已暴露筛查改称独立确认或已找到可部署适用条件。State COMPLETE_MAX_ROUNDS/paused，无active Run/operation，0后继/Claim。[结果及核验证据](sgp_r1_budget1/FINAL_REPORT.md)，证据AI4S-DBCONFORMER-dbconformer-sgp-r1-budget1。下方运行/等待段为历史快照。

**2026-10-31 SGP-R1 budget1 授权修订并启动**：保留原3TECH资格与成本停止；累计预算72→144h、原起点/账本不变，单并发保守估算112.68h，120hSCI/126hTransaction/6h收尾。原3TECH独立入库与源闭集重新核验，新Run只54fresh SCI，标准控制器已确认远端接收。三臂科学配方/双对照/风险判定不变、无重试/后继。下方原成本停止为历史边界，本次不抹除；科学效用仍待完整SCI与intake。[修订启动记录](sgp_r1_budget1/STARTUP_REPORT.md)。

**2026-10-31 SGP-R1 实际成本停止**：三臂完整GPU TECH已通过并由冻结验证器复核；SCI派发前成本门失败，54SCI预计112.68h超过50h上限，实际SCI为0。当前不是NO_SIGNAL或方法负结果；P-B0与P-C效用及个体风险未检验。标准完整科学回传尚未形成，保留同Run失败，不重试或改预算。[现场核验](sgp_r1/status_check_20261031/REPORT.md)。此前启动段为历史快照。

**2026-10-31 SGP-R1 授权、生产接线与启动更新**：用户现已明确授权本适用条件研究的生产接线、GPU资格、预算设计与科研训练。新72h/57fit（3TECH+54SCI）合同已冻结并派发唯一Run；远端已接收，当前smoke等待GPU容量，GPU资格与科研结果均待真实产物。生产接线、本地正反例及最终包冷导入/parser已过，Grok增量审查READY_WITH_LIMITS，范围和本地补充验收明确分开。下方“预算未授权/生产未接线/仅纸面”段是此前阶段快照，已由本条执行授权更新，不追改原记录。研究仍是共享batch图下分组结构的暴露适用条件筛查，不是成熟原创主方法或独立确认。[启动记录](sgp_r1/STARTUP_REPORT.md)、[冻结合同](dbconformer-sgp-r1.yaml)。运行态只读STATE；真实技术和科学结果未回传前不作效用结论。

**2026-10-31 适用条件问题具体化（用户选择后）**：已将“真实被试分组的冲突投影是否比同计数随机分组更有价值”具体化为同次forward、真实前缀CE按总batch数加权、35个四对四源被试分组轮换、类内置换伪组、增强梯度原样加入的三臂纸面研究。独立算子的合成CPU检查支持关闭恢复原CE梯度及Adam一步、组计数匹配、无额外BN/RNG状态变动；不代表DBConformer FP32/GPU资格或科学效用。0 EEG读取/0科研拟合/0GPU，生产训练器与三臂判定尚未接线，预算未授权，旧NEEDS_REVISION保留。[具体规则及结果去向](reassessment_20261031_post_sqk/research_brief.md#2026-10-31-用户选择后的适用条件研究具体化)、[记录](reassessment_20261031_post_sqk/APPLICABILITY_RECORD.json)。判断仍是适用条件研究待科学检验，不将其改称已成立主方法。

**2026-10-31 SQK结果与下一方向更新**：SQK-R1已完成2TECH+36SCI的冻结核验与标准intake/决策，B0动态Q/K与Cstatic固定Q/K均值56.7805%/56.4236%，差+0.3569pp、精确被试符号翻转p=.4082，4/18配对低于−3pp。原判`SQK_R1_DYNAMIC_UTILITY_NOT_ESTABLISHED_STOP`；不改称等效或静态简化成功，不推断空间信息无用。[结果](sqk_r1/FINAL_REPORT.md)，证据`AI4S-DBCONFORMER-dbconformer-sqk-r1`。这降低继续扫描Q/K层数、静态图或相近池化配方的投入优先级，没有证明历史失败来自优化冲突。

本轮三视角六候选及限定近邻核对后，只优先继续纸面研究“真实被试分组的冲突投影是否比随机分组更有价值”，保留完整宿主并控制真实/混源增强梯度及同图BN/dropout。Grok独立反驳原判`NEEDS_REVISION`：现方案属于成熟梯度手术的适配，尚不足指定为论文主方法；真实被试分组同时携带session等共变量，三臂不能证明纯来源因果。主Agent已收窄为适用条件/对照研究并明确类内置换控制，未重新外审或获得实验资格。跨源原型、前端共享/秩、可靠拒判和缺通道联合重建均保留为有风险备选；不将未选或未实现记为科学失败。若最终只有常规适配，停止主方法投入并保留DBConformer baseline。当前仍无成熟下一主方法；[方向、依据、关键控制和停止条件](reassessment_20261031_post_sqk/research_brief.md)。此次0拟合/0推理，不改变旧合同、状态或预算。下方10月29日设计段保留当时认识，不能代表SQK之后的优先级。

**2026-10-29 v3.3设计更新（无新实验）**：SBN收尾后已激活L1/L2/L3 v3.3，旧结果和状态不改。三视角六候选比较及Grok独立反驳后，下一方向优先继续设计“空间attention是否需要当前trial驱动的关系”，用完整动态QK与由原位置表驱动的固定QK比较，保留V/O、FFN、LN、残差与两层S编码器。依据是BNS整块删减没有分离动态关系与其他变换，不是BNS证明S无用。源码`MultiHeadAttention:190–216`和`TransformerEncoderBlock:246–265`确认该作用位置；参数形状相同仍不证明优化等价。该方案未实现、未训练，最近邻Synthesizer已有静态attention先例，贡献与最终独立评价仍未建立。若控制不够或只是常规适配，应继续收束。[本轮设计、选择依据与对照](reassessment_v33_20261029/research_brief.md)。

原初“均值＋有符号双段差”方案已降为低优先：同位置SVE失败仍保留，(m,d)与双段拼接线性等价，abs(d)还抹去相对符号，不能称纯时间顺序机制。Grok原判NEEDS_REVISION，最终Q/K细化为主Agent审后设计，未声称外审改判；保护文件变动告警与来源未归因限制见[处置](reassessment_v33_20261029/review/DISPOSITION.md)。默认运行选择仍为暂停与证据收束，这份方向记录不授予训练权限。

当前尚无已具论文主方法资格的新候选。FCA 的均值改善不能覆盖冻结个体风险失败；CGB、BCU、RCS 分别关闭其固定替换、重采样及共有对象假设的精确范围，不否定整个校准或架构家族。直接依据见下方对应结果报告。

SBN-R1已完成正式核心intake与独立复算：仅真实源数据重估BN相对原统计−0.2604pp、相对真实＋增强重估−0.2713pp，两主比较均值及逐seed门失败，前者另有2/18配对低于−3pp。Cmix−B0仅+0.0109pp，不能支持继续投入或把源增强解释为泛化问题的原因。关闭本固定两BN顺序population重估实例，不否定整个BN校准家族，不新增Claim或R2；[直接证据与处置](sbn_r1/closeout_20261029/CLOSEOUT_REPORT.md)。研究问题仍来自实际BN路径与源数据组成，[原设计依据](reassessment_20261029_post_rcs/research_brief.md)保留，不以RCS阴性证明。运行与投入授权仅看State，以下启动及设计段均为历史快照。

## 历史研究判断与来源（保留各时点记录）

更新：2026-10-29，SBN-R1 packfix1三节点/37任务、36科学BN状态/54评分完整通过，兼容回传与标准intake完成，独立复算一致。冻结决策SBN_R1_FIXED_GATE_NOT_MET_STOP；0梯度训练，本次恢复0模型推理，原合同/封存清单/6h起点及旧成本保留。State暂停、活动Run/operation为空，BCU-R2/SBN-R2不启动。[正式收尾](sbn_r1/closeout_20261029/CLOSEOUT_REPORT.md)。



更新：2026-10-29，SBN-R1 packfix1真实源资格、全18原B0重放和成本门均PASS，科学18组合任务已RUNNING；预计科学保守2564.98秒，0梯度训练，未读中间效果，无新Claim，BCU-R2/SBN-R2不启动。[启动与当前阶段](sbn_r1/STARTUP_REPORT.md)。

更新：2026-10-29，用户已批准SBN-R1及新增6h，packfix1正式启动。真实源数据GPU技术资格PASS，峰值1189MiB，18项原B0重放运行中；科学新统计未作效果读取，仍受完整重放与成本门约束。0梯度训练，实际宿主2BN源码更正已记录，原合同/旧结果/预算成本保留，BCU-R2/SBN-R2不启动。[实际启动及门控](sbn_r1/STARTUP_REPORT.md)。

更新：2026-10-29，RCS后新方向仅设计。暂定优先SBN-R1：固定原无对齐B权重，比较原BN统计、真实源数据重估与真实＋增强重估，区分统计刷新和数据组成。该问题由实际训练路径提出，不由RCS阴性证明；已有BN近邻，尚无新效用或原创机制证据。0新梯度训练但需要新源前向/评分，资产、执行预算及专项资格未完成，本轮无实验。共有对象门控与BCU-R2仍关闭。[候选比较及条件方案](reassessment_20261029_post_rcs/research_brief.md)。

更新：2026-10-29，RCS-R1已按2小时授权完成零训练预测分析。90份来源闭合、180会话分数及独立复算通过，18会话中0个满足三配方相对B/D在两seed共12差值均负的原判据。存在局部重复损失，但没有本轮定义的共有受损对象；停止以此为依据启动新方法，不把阴性解释为无风险或随机性已证实，无新Claim。BCU-R2不启动，原活动状态及旧成本保留。[RCS结果与处置](rcs_r1/RESULTS_REPORT.md)。

更新：2026-10-29，BCU后研究重评（仅设计）。当前没有足够依据继续相近训练配方或将DBConformer指定为主创新。优先证据收束；唯一展开的低成本下一轮为RCS-R1：利用已有五臂预测检查受损对象跨seed/配方的会话层一致性。共同模式缺失就停止该方法靶点投入，存在也不等于无标签可识别或因果机制成立。0新训练/模型前向，规划2小时未授权，尚未运行新分析；State/旧判/预算保留。[新方案](reassessment_20261029_post_bcu/research_brief.md)。

更新：2026-10-29，BCU-R1 packfix1正式核心intake、独立全量/核心复算及决策收尾完成。2 TECH+36 SCI、54旧参照均已核验，未重训；原合同/封存清单/全部结果保留。P/E0/C0平均ACC为60.7313/60.3299/60.4275%，P−E0 +0.4015pp、P−C0 +0.3038pp，均低于0.5pp且逐配对风险门失败，四项比较均不通过。决策BCU_R1_FIXED_SCREEN_GATE_NOT_MET_STOP，关闭固定源cal32 bootstrap bank32配方；不外推整个校准家族无效，无新Claim，BCU-R2不启动。State暂停、无活动Run或operation。原48h起点及全部成本不重置。[正式收尾与限定](bcu_r1/closeout_20261029/CLOSEOUT_REPORT.md)。

以下启动、设计与旧研究段保留各自当时状态，以本条正式收尾为本轮最新结论。

更新：2026-10-29。用户已要求启动BCU-R1，48h预算与01:07+08起点已绑定。实际packfix1 Run已在lab-codex接受，两项source-only GPU TECH运行，SCI0/36待TECH与实测成本门。旧54参照和FCA/CGB全部结果、成本及停止边界保留；没有新Claim，不启动任何R2。[实际启动与验收](bcu_r1/STARTUP_REPORT_PACKFIX1.md)。

以下保留先前研究判断及当时的状态；原BCU条件设计的“未授权”现由本轮用户启动指令及48h预算绑定取代。

更新：2026-10-28 22:22。CGB-R1已完成3TECH+27SCI的正式核心intake及独立复算，决策CGB_R1_FIXED_REFERENCE_INSUFFICIENT_STOP；State暂停、活动Run/operation均空，CGB-R2与FCA-R2均不启动。[CGB结果与处置](cgb_r1/RESULTS_REPORT.md)。FCA原FAIL_STOP、原合同、54结果及完整成本保留。

## 拟议主张

2026-10-28 FCA后强对照已完成：固定OAS/源参考切空间/StandardScaler/C1多类LR在B/D/E的ACC为33.746/35.352/41.276%，相对同臂原FCA平均−23.014/−23.199/−19.054pp；全部54个subject/reference-seed配对低于−3pp，冻结三臂保留门失败。由此关闭本固定低成本替换配方，不扫描频带/对齐/C或选最好臂救援；完整管线差距不证明纯架构贡献，也不否定所有几何方法。原FCA校准个体风险失败仍成立。当前无新结构主方法或正式Claim，继续暂停近邻神经模块/选模搜索并收束已有边界。[直接分析及处置](cgb_r1/RESULTS_REPORT.md)，证据AI4S-DBCONFORMER-dbconformer-cgb-r1；旧设计草案仅保留当时决策来源。

当前没有已具备主论文资格的新方法候选。FCA-R1固定完整协方差校准配方已因风险门失败关闭，FCA-R2不启动。固定辅助监督BAS、固定空间编码器删减BNS及固定D6选模实例SVS均已关闭；BAS-R2/BNS-R2/SVS-R2均不启动。建议暂停DBConformer的新模块及近邻选模配方搜索，保留完整2/2宿主baseline及已具来源的鲁棒性辅助分析和限定负结果。已有配置失败不证明整个模型家族没有可行创新。[SVS方案](reassessment_20261023_post_bns/research_brief.md)已完成18条六源训练轨迹，未满足进入完整八源B8比较的冻结前提。

2026-10-24再次重评保持上述主线判断。[FCA-R1方案](reassessment_20261024_post_svs/research_brief.md)在用户接受有限无标签目标会话校准后进入独立任务：完整2/2宿主比较无对齐、对角尺度校准、完整协方差对齐，检验成熟强baseline的价值，不作为结构创新。EA已有明确先例，本地尚无该固定cal32/5%配方效用证据；它不同于SVS选模、CMN缺通道条件归一化及原生EA协议。原方案的DESIGN_ONLY现由本次明确授权取代；旧关闭边界保持，目标访问仅限冻结合同规定的checkpoint选定后每会话最早32项无标签校准，剩余256项仅用于评分。FCA-R1结果现已完成正式验收，具体限定与关闭后果见下文；未释放Claim。

**CGB后的条件性设计（2026-10-28）**：下一项可选问题为BCU-R1源cal32重采样校准训练：部署端仍固定E，比较P与旧E及CovMix-cal32同宿主控制，不增加分支/辅助loss/校准强度扫描。旧SGR的平衡/GroupDRO和SCR同源拼接已失败，不能视为空白。拟36新SCI+最多2source-only TECH、复用旧54参照，48h仅为有条件总预算情景，尚无执行授权；CovMix来源配方、复用、真实TECH/成本未闭合，默认继续收束。外审READY_WITH_LIMITS只允许设计留档；任何新效用或机制主张均待检验。[设计与停止条件](reassessment_20261028_post_cgb/research_brief.md)。

## 关键缺口

BNS静态参数减少42.04%、限定MAC减少14.28%，但个体风险失败，不能作为获准简化方案；实际推理延迟未受控测量，不补测救援。平均保留不是统计非劣效；九名被试反复暴露，新seed不恢复独立评价。原论文已有整分支和深度消融，当前研究没有建立独立方法创新或正式论文Claim。SVS完成真实产物与来源核验，但其固定D6选择配方失败；同轨迹差异不能单独分离验证域组成/密度的作用，也未执行完整八源B8科学比较。新选模结果不会追改旧BAS/BNS失败，正式独立评价范围仍未建立。

## 当前认识

**完整协方差校准有平均收益，但未保住冻结个体风险。** FCA-R1 为已暴露九被试×seeds3/4 的每会话32项无标签校准筛查，54 SCI、3原TECH闭合。B/D/E平均ACC为56.760%/58.550%/60.330%；E-B +3.570pp、E-D +1.780pp，两seed均值均为正，但最差配对 -4.492pp/-8.203pp，低于-3pp分别3/18、5/18。固定cal32/5%完整协方差配方按原规则 FAIL_STOP，FCA-R2不启动，不以均值收益救援风险失败。E-D seed3仅+0.152pp、seed4 +3.407pp，增益稳定性也未建立；本轮不作独立确认或结构创新主张，不外推校准家族无效。证据 `AI4S-DBCONFORMER-dbconformer-fca-r1`；[正式分析与收尾](fca_r1_repair5_packfix80/intake_recovery_v1/CLOSEOUT_REPORT.md)。核心回传及分析接口错误已按精确原身份修复；原包/合同/结果不变、零重训，独立全量/核心复算一致。累计80小时上限未追加，延后回拉与收尾的累计超限按原账本保留。

**固定的未训练源被试验证选模没有改善目标泛化。** SVS-R1 repair2的18项SCI完整完成，1项原TECH无训练导入，54份预测独立NumPy重算与冻结分析一致。R6/D6/F6分别56.5490%/53.2215%/56.0089%；D6−R6 −3.3275pp、D6−F6 −2.7874pp，两个seed均为负，最差配对−13.7153pp/−12.8472pp，低于−3pp分别7/18和6/18，六门均失败。关闭本次两验证被试/抽样/六源训练配方，SVS-R2前提未满足；不换被试、加seed或调epoch窗口救援，不外推全部域泛化/选模无效。证据`AI4S-DBCONFORMER-dbconformer-svs-r1-repair2`，来源[结果报告](svs_r1_repair2/RESULTS_REPORT.md)。该Run实际执行约64分钟，训练在预算内完成；延后回拉收尾按原计时到decision累计14.444h，超过14h约0.444h，保留预算偏差及旧成本。

**删除空间Transformer没有保住预先要求的个体风险。** BNS-R1两臂9被试×seeds3/4，B0 56.7805%、P 57.0698%，P−B0 +0.2894pp；seed3 +0.9259pp、seed4 −0.3472pp，均符合新前瞻保留门。但3/18配对越过−3pp风险线，最差subject7/seed3 −4.5139pp；subject4两seed均越线。参数/MAC门通过不能救援风险失败。Evidence AI4S-DBCONFORMER-dbconformer-bns-r1，完整38项封存分析和独立36份数组重算一致；直接来源[结果报告](bns_r1/RESULTS_REPORT.md)。关闭固定2/0包，BNS-R2前提未满足。不外推空间信息无用或单一attention无用；P保留双前端/位置/池化/融合，C(0/2)没有执行。

**辅助监督正线索未复现。** BGC的P−B0 +1.3696pp但P−A −0.0965pp、必要控制失败；A−B0 seed0 +1.4660pp促成BAS。BAS两新seed平均−1.8036pp、两seed均负、最差−8.8542pp，四门失败，关闭固定A与分配续接。来源AI4S-DBCONFORMER-dbconformer-bgc-r1-repair2和AI4S-DBCONFORMER-dbconformer-bas-r1；[BGC报告](bgc_r1_repair2/RESULTS_REPORT.md)、[BAS报告](bas_r1/RESULTS_REPORT.md)。不调λ/加seed救援，不否定全部辅助监督。

**额外能量/关系实例与缺通道辅助证据各有明确范围。** FSC、BSP、SRT的P−B0分别−3.1829、−0.1736、−2.1412pp，各自必要门失败；其精确边界见对应decision及[历史入口](HISTORY_BOUNDARIES.md)、[v3.2证据表](discover_next_v32_20261020/research_brief.md)。BDA的U0缺通道适配在两backbone seeds获支持，但NNC中U0−RIDGE约−4.9738pp，已撤下独立创新，保留RIDGE强对照及限定鲁棒性来源，见[已有处置](architecture_next_20261005/CLOSEOUT.md)。这些历史不能移作clean改进证据，INVALID不按科学负结果聚合。BNS使用对称独立数据随机流的新训练B0，不能跨profile拿BAS/BGC绝对均值作配对比较。


### 2026-10-27 FCA-R1 repair5 部署续接

已登记累计71小时、SCI3小时/Transaction4小时的repair5。本地53 SCI+3 TECH来源、真实CPU入口、实际启动接口及最终包通过；仅授权补B_s6_seed3。上传时SSH在密钥交换前被远端关闭，未收到上传回执、未发出launch；真实GPU和SCI尚未由本次部署启动。原起点与全部历史成本保留，恢复连接后须先核对同一Run并重过实时预算门。无新增科学结论，FCA-R2不启动。[部署记录](fca_r1_repair5/DEPLOYMENT_STATUS.md)。



