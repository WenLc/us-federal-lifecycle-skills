---
name: compensation-and-pay-equity
description: |
  用户要搭建或审查薪酬系统时调用: 建薪资结构/薪等带宽、职位评估、市场对标 (lead/lag/match)、判定 exempt/加班、做薪酬公平审计、处理同岗不同薪疑虑、沟通薪资。不适用于: 单次解雇的加班费诉讼应对 (转 employment-law-basics 或咨询律师); 法定福利/休假 (转 benefits-and-leave); 钱以外的认可设计 (转 rewards-and-recognition)。关键 trigger: 薪酬结构/薪资带宽/职位评估/同工同酬/薪酬审计/exempt/加班判定/市场对标 — compensation / salary structure / pay equity / job evaluation / pay gap / overtime classification / exempt。 EN trigger: compensation, salary, pay structure, pay grade, pay band, salary range, salary midpoint, job evaluation, market pricing, benchmark, market data, exempt, nonexempt, overtime, overtime pay, pay equity, pay gap, equal pay, compa-ratio, how much should we pay, Glassdoor, lead lag match
tags: [compensation, pay-equity, salary-structure, job-evaluation, flsa]
related_skills:
  - slug: job-analysis-and-ada
    relation: depends-on
  - slug: rewards-and-recognition
    relation: contrasts-with
  - slug: benefits-and-leave
    relation: composes-with
  - slug: dei
    relation: composes-with
---

# 薪酬结构与薪酬公平 (Compensation and Pay Equity)

## R — 核心要旨 (Reading)

薪酬公平审计用来识别差距在哪里: 只比较核心职责相同的岗位, 用回归分析 (OLS) 估计各因素对薪酬的影响, 关注控制变量之后的"受控差距"——小差异是统计噪音, 大而广且统计显著的差异才需纠正。薪酬结构由职位评估 → 市场定价 → 成结构三段式构成。

---

## I — 方法论骨架 (Interpretation)

薪酬系统不是"给每个岗位定个价", 而是三段式工程:

1. **职位评估** — 用点因子法等量化方法给职位的相对价值排序; 记住评估的是"职位"不是"人"。
2. **市场定价** — 用外部薪酬调查确定可比岗位行情: 按职责而非头衔匹配, 用至少三份可信调查交叉验证; 众包/爬取数据只能作补充。
3. **成结构** — 把内部职位价值与市场数据合成薪等与带宽: 中点由市场驱动, 显式选择 lead/lag/match 市场定位。

全程用**五重约束**当检查清单: 使命、文化、队伍、外部竞争、内部公平——五者同时成立才算合格。

找公平差距时做 **pay equity audit**: 只比较核心职责相同的岗位, 用回归 (OLS) 看控制变量后的"受控差距"; 小差异是统计噪音, 大而广且统计显著的差异才需纠正。配套用 compa-ratio (工资÷带宽中点) 诊断带内位置, 识别 green/red-circle 与 salary compression 等结构信号。

所有法律数字 (如 FLSA 豁免薪资门槛) 都是美国语境、会随时间变化, 用前必须查证。

---

## A1 — 应用案例 (Past Application)

### 案例 1: "专注的黛比" — 未授权的加班也必须付薪
- **问题**: 员工为避开早高峰提前 30 分钟上班并开始干活, 每周多出 2.5 小时"未授权"加班。
- **方法论的使用**: FLSA 规则——只要实际工作了 (且属 nonexempt), 无论是否获授权, 雇主都必须计入工时付加班费; 付钱与纪律处分是两件事。
- **结论**: 不能以"未批准"为由拒付; 管理杠杆是事先声明"加班须经批准"并对违规者按政策纪律处分。
- **结果**: 雇主照付加班费, 同时建立加班授权声明与纪律程序, 而不是用拒付控制成本。

### 案例 2: "匹配市场 75 分位" 的沟通翻车
- **问题**: 薪酬经理向经理和员工解释"为了领先市场, 岗位匹配到市场数据第 75 百分位"。
- **方法论的使用**: 员工不了解薪资结构如何构建, 把"75 分位"听成了"只拿到岗位价值的 75%"。
- **结论**: 薪酬术语必须具体——解释工具与方法、数据来源、为何可信, 并讲清薪资带宽的构成。
- **结果**: 沟通改用通俗语言与逐项解释, 避免单个百分位数字被误解为"被打折"。

### 案例 3: 点因子法职位评估 (Position A 得 1,982 分)
- **问题**: 要给无薪级体系的组织建立内部公平的职位价值排序。
- **方法论的使用**: 识别基准职位 → 选可计酬因素 (知识/复杂度/判断/影响等) → 加权 → 分档赋分 → 逐职位打分求和。
- **结论**: 量化、成文的评估体系使薪酬结构在法律上可辩护, 面对同酬审查是护身符。
- **结果**: Position A 总分 1,982, 与 B/C 排序对比后用于定级与市场锚定, 而非拍脑袋定薪。

---

## A2 — 触发场景 (Future Trigger) ★

### 用户会在什么情境下需要这个 skill?

1. 要建/改薪资结构: 给一批岗位从零建薪资带、定带宽中点与等级
2. 做薪酬公平审计: 怀疑男女/种族同岗不同薪, 问"这算歧视吗, 要不要纠偏"
3. 判定豁免与加班: "这个经理算 exempt 吗""员工在家回邮件要付加班费吗"
4. 市场对标决策: "用 Glassdoor 数据定价行吗""我们应该 lead 还是 lag"
5. 薪酬沟通: 宣布薪资带宽/调薪, 怕被员工误解

### 语言信号 (用户的话里出现这些就应激活)

- "薪酬结构" / "薪资带宽" / "职位评估" / "同工同酬" / "薪酬审计" / "exempt" / "加班判定" / "市场对标" / "薪酬哲学" / "compa-ratio"
- "compensation" / "salary structure" / "pay equity" / "pay gap" / "job evaluation" / "pay grade" / "overtime classification" / "exempt vs nonexempt" / "market benchmark"

### 与相邻 skill 的区分

- 与 `employment-law-basics` 的区别: 该 skill 是每次人事决策前的通用法律地基 (at-will / 歧视双理论 / 承包二分); 本 skill 是把法律落地为"薪酬系统设计与公平审计"的工程方法。单次解雇的加班费纠纷是法律问题, 转走。
- 与 `benefits-and-leave` 的区别: 同属"全面回报", 但薪酬 = 直接报酬 (工资/奖金/股权), 福利 = 间接报酬 (保险/休假); 谈 FMLA/COBRA/WARN 转走。
- 与 `rewards-and-recognition` 的区别: 薪酬管"钱" (结构、带宽、审计), 认可管"钱以外的低成本认可"; 谈月度之星/表彰转走。
- 与 `job-analysis-and-ada` 的区别: 职位分析 (job analysis) 是本 skill 职位评估 (job evaluation) 的前置输入, 不是同一件事; 本 skill 的触发点是"定价/定级/审公平"而非"写职位描述/合理便利"。

---

## E — 可执行步骤 (Execution)

当 skill 被激活后, agent 应按以下步骤执行:

1. **先立薪酬哲学与组织前提**
   - 完成标准: 成文一份薪酬哲学声明, 显式选择 lead/lag/match; 逐条过五重约束 (使命/文化/队伍/外部竞争/内部公平); 记录组织前提 (规模/生命周期/行业/营利性质/地理分布)。
   - 判停条件: 若组织连基本职位清单和职位描述都没有 → 停止, 先转 job-analysis-and-ada 完成职位分析再回来 (评估前提是职位被称职地定义)。

2. **建薪资结构 (评估 → 市场 → 成结构)**
   - 完成标准: 每个基准职位有职位评估分; 市场调查 ≥3 份、每份 ≥10 家机构 / ≥15 个任职者、按职责而非头衔匹配; 每个薪等有下限/中点/上限, 带宽宽度符合层级惯例 (执行层 50–60% / 专业 40–50% / 时薪 30–40%)。
   - 判停条件: 若拿不到 3 份可信市场调查 (样本不足) → 停止定价, 先用保守近似并把不确定性显式标注在结构中, 不得用众包数据独自定价。

3. **审公平 + 透明沟通**
   - 完成标准: 产出 pay equity audit 报告——区分"统计噪音 vs 系统性差异" (受控差距回归, 仅大而广且统计显著的差异才纠正); 沟通材料无未解释的百分位/术语, 每个数字都说明来源与含义 (防"75 分位被听成 75%"的翻车); 涉及法律数字处标注"美国语境, 阈值会变, 用前查证"。

---

## B — 边界 (Boundary) ★

### 不要在以下情况使用此 skill

- 单次加班费/薪资纠纷的诉讼应对 — 那是法律问题, 转 employment-law-basics 或直接咨询律师。
- 非美国语境直接套用 FLSA 等美国法律数字 — 数字不通用。
- 无职位数据、无 HR 支撑的小团队想一步到位建完整薪资体系 — 方法假设存在成型的 HR 部门、预算与信息系统。

### 常见失败模式

- **未授权加班也不得拒付** (FLSA: 只要实际工作就必须付酬), 只能靠"事先授权声明 + 纪律处分"管理。
- **用百分位等术语含糊沟通** — "匹配市场 75 分位"被听成"只值 75%", 信任崩塌。
- **禁止员工讨论薪酬 / 报复谈论者** — 工资透明法禁止, 且压制无效。
- **靠头衔/月薪判断豁免** — 豁免看"薪资基础测试 + 职责测试"双重, 头衔无关。

### 方法论局限 / 适用边界

- **美国法律语境 + 阈值随时会变**: FLSA 豁免薪资门槛 ($684/周)、联邦最低工资 ($7.25/时)、薪酬透明与同酬立法 (如薪资历史禁令) 都随法规修订而变——本 skill 里的任何具体数字都必须"用前查证"。
- 假设组织具备实施条件: 检查清单预设存在成型的 HR 部门、政策体系、预算与信息系统, 对最需要帮助的中小企业/初创是空中楼阁。
- 反复以"咨询你的律师"结尾: 在风险最高处 (公平审计的诉讼特权设计、法律阈值), 书本身提供不了可独立站立的答案。
- 把 Fortune 500 语境下的最佳实践当通用方案, 未充分讨论组织规模/行业/文化的权变。

### 容易混淆的邻近方法论

- **总回报模型 (total rewards)**: 直接薪酬只是总回报的一半 (还有间接薪酬/认可/成长/弹性); 评估单点决策 (如砍学费报销) 要放回总回报看, 别只算现金。
- **compa-ratio vs 单一薪资数字**: 前者衡量"带内位置" (工资÷带宽中点), 后者只回答"给多少"; 诊断 salary compression / green/red-circle 时用的是前者。

---

## 快速理解: 5 个示例问题

用这 5 个最常被问到的场景快速上手本 skill, 每个问题都对应它真正触发的处理动作:

1. **男性和女性同岗不同薪, 这算歧视吗? 要不要纠偏?** — 受控差距回归的 pay equity audit
2. **这个技术经理算 exempt 吗? 该不该给加班费?** — FLSA 薪资基础 + 职责双测试
3. **用 Glassdoor 数据给岗位定价行吗? 我们该 lead 还是 lag?** — 薪酬调查守则 (≥3 份可信调查) + 市场定位
4. **要建薪资带宽, 每个薪级的中点怎么定?** — 职位评估 → 市场定价 → 成结构
5. **员工下班在家回邮件、晚上还写报告, 要付加班费吗?** — nonexempt + 实际工作则计酬

## 相关 skills

- **depends-on** [`job-analysis-and-ada`](../job-analysis-and-ada/SKILL.md) — 职位评估 (job evaluation) 以职位分析为前置; 无职位清单先回去做分析。
- **contrasts-with** [`rewards-and-recognition`](../rewards-and-recognition/SKILL.md) — 直接报酬 (工资/奖金/带宽) vs 钱以外的低成本认可。
- **composes-with** [`benefits-and-leave`](../benefits-and-leave/SKILL.md) — 同属总回报模型两翼: 直接报酬 + 间接报酬 (福利/休假)。
- **composes-with** [`dei`](../dei/SKILL.md) — 薪酬公平审计 (pay equity) 是 DEI 测量闭环的核心指标之一。
