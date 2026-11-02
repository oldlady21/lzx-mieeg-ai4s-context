# OTA 当前研究认识

## 基模来源与实现

OTA 当前依据是本 Program 自身的状态占据—滞后关联实现，不把其他基模论文当作 OTA 原论文。实现与设计材料：[model.py](ota-v0.1/model.py)、[node.py](ota-v0.1/node.py)、[reference.py](ota-v0.1/reference.py)、[analyze.py](ota-v0.1/analyze.py)、[LITERATURE.md](ota-v0.1/LITERATURE.md)、[PROBLEM.md](ota-v0.1/PROBLEM.md)、[RESEARCH_PLAN.md](ota-v0.1/RESEARCH_PLAN.md)。精确来源文献依 `LITERATURE.md` 核验；不把后续文献解读冒充本地实验结果。

## 基础理解与边界

原设计的共享局部方差编码先形成软状态序列；占据支读取状态均值，关联支读取有限滞后的联合表经 log 与双中心化后的特征。状态是学习型局部模式，不等同 EEG microstate；联合表不等于条件转移矩阵，也不预设 Markov 性。`model.py/build_paired_models` 将候选状态复制给匹配控制，并为自由关联读出构造同初始函数；这些是实现与设计事实，不证明两支互补或新效用。依据为上列研究计划 §1–2、model.py 与 reference.py。

## 当前综合

以下更新于2026-10-29，来自已登记的开发/source证据阅读与设计综合，没有新实验。动态状态仍由 `STATE.yaml` 管理；本总览不解除暂停、不清除未对账Run，不把v3.3文本交付等同链激活。

| 当前认识与条件 | 直接来源 | 改变的设计选择与修正条件 |
|---|---|---|
| 原OTA精确实例无相对占据增量，P0−S0 −5.761pp、P0−N0 −5.011pp；固定probe微小正差不能救主门 | `AI4S-OTA-ota-r01-v0.1-r2`；[原分析](ota-v0.1/analysis/OTA_v0.1_RESULT_ANALYSIS.md) | 不继续调旧Q/lag或追加seed。新问题必须区分状态表示、摘要和优化；不能把失败唯一归于Q。原88+2跨Run合并有效，仍不是单个完整Transaction |
| OTA-RL说明去掉的主效应仍可读，但Gpre未过原幅度门，旧外审incomplete | `AI4S-OTA-ota-rl-r01-v0.1-repair1`；[决策](ota-rl-r01-v0.1-repair1_decision.yaml) | 保留边际竞争解释；不把冻结可读性当联合训练效用或独立确认。Softmax可恢复中心化logits，不能直接称其删除全部信息 |
| 连续内容集合也不是已成立的基础：MCP A0比B0低31.952336pp，阶段二未启动 | `AI4S-OTA-mcp-dual-r01-v0.1`；[结果](mcp-dual-v0.1/RESULT_ANALYSIS.md)、[设计](mcp-dual-v0.1/RESEARCH_PLAN.md) | “保留连续内容”不足以支持主线；新状态索引必须超过简单拼接/粗时段内容袋，并正面保留同前端失败反例 |
| DSA-OT有净增益但未分离可加/重连/逐点对照；FRA归因未解决 | `AI4S-OTA-dsa-ot-r01-v0.2-r1`、`AI4S-OTA-dsa-fra-r01-v0.1`；[DSA-OT](dsa-ot-v0.2-r1/RESULT_ANALYSIS.md)、[FRA](dsa-fra-v0.1/RESULT_ANALYSIS.md) | 配对关系主张须胜过同配方可加端点和无序/容量对照。原涨点归因分支已用户停止，引用不恢复它 |

跨Program只形成控制约束：

- `AI4S-DSAINET-p0-cue-r2-recover53` 的[报告](../../dsainet/research/p0-cue-r2-recover53/analysis_remote/RESULTS_ZH.md)说明同配方S0也获益，P0均值不能覆盖个体风险失败；保留同训练配方、seed方向与实际被试风险。
- `AI4S-DSAINET-dsa-ces-v0.1-repair3` 的[报告](../../dsainet/research/dsa-ces-v0.1-repair3/RESULT_ANALYSIS.md)说明能量包含均值平方、原Coarse特异诊断不足；不能移植“均值漂移已证明”或“中心化必然有效”。OTA原方差前端不等于该DSA能量接口。
- `AI4S-MVCNET-mvcnet-vbr-r1-screen-lab10-r1-repair3` 的[报告](../../mvcnet/research/vbr-r1/execution/repair3/analysis_20261029/REPORT.md)保留P0−B0 +2.015818pp与P0−S0仅+0.019290pp的区别；主比较须面对有竞争力的支架。
- `AI4S-SSTDPN-teo-r01-v0.1-e1` 的[报告](../../sstdpn/research/teo-r01-v0.1-e1/REPORT.md)没有稳定有向能量probe增量；不能从时序量存在、测试时打乱敏感或固定读出可读推出联合训练收益。

这些均有各自宿主、数据角色与曝光，不能汇总成OTA的效应证据或转移确认资格。本轮未消费DBConformer活动SBN中间效果；未重新解码EEG或重放预测。原验收/外审限制仍按各自记录。

## 未决问题

2026-10-31 SIC-R1后续：完整72项已通过analysis_v1正式intake，66原件逐字节复用、6缺口补跑；不回拉完整载荷。证据`AI4S-OTA-ota-sic-r1-repair1`：U0−C0仅+0.063pp且NLL变差，U0−T0为−10.251pp，两项主门失败；M0均值不退化门通过不改变整体NO_SIGNAL。判断更新为当前U实例缺乏继续投入依据，关闭该实例，V/B不推进；未来如另获授权须先保留粗时间信息，并以T0/C0为必要对照，不从本负结果推出普遍无效或target/滞后机制结论。详见[72项收尾报告](sic-r1/repair1/resourcefix1/analysis/REPORT.md)。以下历史问题保留其提出时语义，当前取舍以上述精确负边界为准。

1. 同一连续局部描述子上，状态索引的内容矩U是否超出 `concat(m,mean(c))` 和固定粗时段内容袋？这与MCP的无状态集合不同，但仍是未验证假设，软字典编码本身有已知文献近邻。
2. 只有内容基础值得继续时，再问状态对内容V是否超出可加端点、无序配对及保留粗时间包络的对照。U成立不证明V；代数恢复m/J/均值不等于完整信息保真。
3. 条件滞后余量 `R=J−EπJ` 作为暂缓替代问题：它只相对指定分段参照解释，不能消除全部自相关、滤波和窗口重叠效应。

设计取舍、关键对照、停止句及真实Grok反驳见[2026-10-29 brief](design_20261029/RESEARCH_BRIEF.md)。对应 Foundry 卡为 `IF-20261029-01/IF-20261029-OTA-01 card-v2`（主推荐）及 `OTA-02 card-v2`（暂缓wildcard）。完整原卡见 [Foundry Portfolio](../../../../idea-stage/foundry/IF-20261029-01/PORTFOLIO.md)；卡片本身不授予实验资格。

2026-10-29 后续用户明确选择主推荐的 U-only 首阶段，并授权 Lab10 上 4 臂×2 seed×9 固定 source 划分、100 epoch、24 小时执行上限、零自动训练重试、阶段结束停止。新研究为 `OTA-SIC-R1`，具体方案与授权见 [RESEARCH_BRIEF](sic-r1/RESEARCH_BRIEF.md)、[EXECUTION_AUTHORIZATION](sic-r1/EXECUTION_AUTHORIZATION.md)。V 与 B 仍暂缓。22:51已完成方案冻结、上传和真实执行器启动，技术阶段等待显存资源，尚无拟合；后续状态以 State 与[启动记录](sic-r1/LAUNCH_REPORT.md)为准。尚无新的科学结果或正式 Claim。

2026-10-30：原SIC技术4/4通过，正式66项退出正常，3项实际失败及3项受阻未启动，不能判科学NO_SIGNAL。用户随后明确授权仅补6项并完成原筛查。原Run完整快照及66项身份/选模/独立预测核验通过，另540个初始参数张量均匹配原Lab10 CPU期望。失败M0/s1/f1的初始temporal权重全零；同环境CPU重建正常，未唯一识别底层成因，恢复加入严格保值的初值/设备检查且保留原有效梯度门。首次修复包在派发闭集校验前失败、0拟合；其证据及成本保留。实际执行器入口已补测，packfix1于12:39启动，66+4原件导入PASS，仅6项待资源，尚无新增拟合；原24h起点和79次累计拟合尝试上界不变。见[恢复记录](sic-r1/repair1/packfix1/PROGRESS.md)。尚无完整72矩阵或新科学结论。
