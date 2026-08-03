---
name: employment-law-basics
description: |
  用户在做任何高风险人事决策前想先懂法律地基——如"能不能想开就开某人""这样解雇违法吗""这是歧视吗""顾问算员工吗""员工举报后给差评算报复吗";或写手册/政策前担心措辞构成默示合同。关键 trigger: 解雇合不合法、歧视/差别对待/差别影响、at-will/随意雇佣、顾问算不算雇员/错分类、报复/retaliation、BFOQ。不适用于: 正被起诉/仲裁的高风险个案(须即时找律师)、非美国法域、具体法律数字查询(有保质期)。本 skill 提供 at-will 三大例外、歧视双理论、报复、BFOQ、IRS 雇员-承包人分类等每次人事决策前该扫一遍的法律地基。 EN trigger: can we fire, is this discrimination, discrimination, disparate treatment, disparate impact, at-will, wrongful termination, implied contract, independent contractor vs employee, misclassification, retaliation, BFOQ, employment law
tags: [legal, employment-law, discrimination, at-will, compliance]
related_skills:
  - slug: job-analysis-and-ada
    relation: depended-on-by
  - slug: recruiting-and-hiring
    relation: depended-on-by
  - slug: benefits-and-leave
    relation: depended-on-by
  - slug: harassment-and-investigation
    relation: depended-on-by
---

# 用工法律地基 (Legal Landscape of Employee Rights)

## R — 核心要旨 (Reading)

歧视有两种理论: 差别对待——因受保护特征而对处境相似的另一位员工故意区别对待; 差别影响——表面中立的政策在无意中对某受保护群体产生歧视性效果。意图清白不等于合规, 表面中立也可能违法。

---

## I — 方法论骨架 (Interpretation)

每次人事决策(录用、晋升、解雇、政策措辞)之前, 先扫一遍美国用工法律的地基, 而不是出事后再补。

1. **Employment-at-will**: 原则上雇主可"有因、无因甚至坏因"解雇、员工可随时辞职, 但它已被三大例外侵蚀——公共政策、默示合同(手册/口头承诺)、善意诚信。所以"想炒就炒"是错的。
2. **歧视双理论**: 差别对待(故意因受保护特征区别对待同类员工) + 差别影响(表面中立、一视同仁的规则却对某受保护群体产生排他效果, 不问意图)。后者是面试/裁员里最隐蔽的坑。
3. **报复**: 任何因员工举报、反对歧视、作证而受到的不利对待都算报复, 与恶意无关——赢了歧视官司却事后报复, 会把赢了的案子输回去。
4. **身份二分**: 一个人是雇员还是独立承包人, 看行为控制/财务控制/关系性质三组测试的实质, 不看你叫他什么; 错分类要补税补福利。

核心心智: 法律不是限制, 而是每次人事决策的地基; 意图清白不等于合规, 表面中立也可能违法。

---

## A1 — 应用案例 (Past Application)

### 案例 1: Griggs v. Duke Power (差别影响奠基判例)
- **问题**: Willie Griggs 因缺高中文凭、两项预录用测试成绩差而被拒绝晋升; 公司坚持这些是中立要求。
- **方法论的使用**: 用"歧视双理论"审视——这些要求表面中立, 却对受保护群体产生排他效果(disparate impact), 且与工作无关; 归责不依赖雇主意图。
- **结论**: 表面公平不够, 筛选要求必须与职位实质相关, 并做影响分析。
- **结果**: 最高法院判定构成歧视, 成为差别影响理论的奠基判例。

### 案例 2: Bostock v. Clayton County (2020) (法律演进警示)
- **问题**: Title VII 的"性别"歧视是否涵盖性取向与性别认同?
- **方法论的使用**: 用 but-for 因果标准解释"because of sex", 并借此示范"法律随社会变化而变"——HR 必须跟进法律演进, 而不是背下某个静态版本。
- **结论**: 反歧视政策中的受保护类别清单不是写一次就完事。
- **结果**: 最高院 2020 年裁定涵盖性取向与性别认同, 成为"法律会变"的行动触发点。

---

## A2 — 触发场景 (Future Trigger) ★

### 用户会在什么情境下需要这个 skill?

1. 用户问"能不能就这样解雇/辞退某人""有没有法律风险"——解雇、降职、不给晋升前的合法性质疑。
2. 用户问"这是不是歧视""为什么表面公平的规则也会被告"——录用、裁员、测试、薪酬政策的自检。
3. 用户问"外包工/顾问/自由职业者到底算不算员工"——身份错分类的担忧。
4. 用户在写员工手册、offer、离职流程措辞, 担心"会不会变成合同/被反咬"。

### 语言信号 (用户的话里出现这些就应激活)

- "解雇/开除合法吗" / "歧视" / "差别对待" / "报复" / "顾问算雇员吗" / "at-will" / "随意雇佣"
- "can we fire" / "discrimination" / "disparate impact/treatment" / "retaliation" / "independent contractor" / "misclassification" / "legal risk"
- "员工举报后想给差评" / "这么写政策有风险吗"

### 与相邻 skill 的区分

- 与 `termination-and-layoff` 的区别: 那是解雇/裁员**执行**的流程(证据三分、终止会议、不利影响分析); 本 skill 是决策前判断**合不合法**的地基, 它先于执行。
- 与 `job-analysis-and-ada` 的区别: ADA 合理便利是本法律地基的一个**具体应用**; 本 skill 覆盖全局(at-will/歧视/报复/身份), 不止 ADA。
- 与 `documentation-and-policies` 的区别: 手册措辞的**法律后果**(默示合同)是本 skill 的判断范围; 那是对文档**纪律**本身。

---

## E — 可执行步骤 (Execution)

当 skill 被激活后, agent 应按以下步骤执行:

1. **给人事决策定性**
   - 完成标准: 明确该决策属于哪一类(解雇/身份分类/政策措辞/筛选标准/晋升), 并写出对应适用的法律(at-will 三大例外 / 歧视双理论 / NLRA / IRS 三组测试)。

2. **用双理论自检 + 核对 at-will 例外**
   - 完成标准: 逐一回答——是否因受保护特征区别对待"同类情形"的员工(差别对待)? 表面中立的规则是否对某受保护群体有排他效果(差别影响)? 手册/口头是否有暗示工作保障的表述(默示合同)? 各列出证据与结论。
   - 判停条件: 若决策涉解雇/裁员/身份错分类等**高危动作**, 不自作主张下"合法"结论, 在步骤 3 显式标注"建议咨询律师"。

3. **文档化决策依据并标注法律意见阈值**
   - 完成标准: 决策依据只写客观事实(时间/行为/证据); 在高危项旁标注"此处理需律师复核"。
   - 判停条件: 若已进入诉讼/仲裁、或涉及具体州法差异(书只覆盖联邦法+州法概述), **停止**并移交律师, 不继续输出法律结论。

---

## B — 边界 (Boundary) ★

### 不要在以下情况使用此 skill

- 已经收到诉讼/仲裁通知的高风险个案: 需要律师实时介入, 不是查手册能解决的。
- 非美国法域: 整体法律均为美国联邦/州法, 对其他法域直接套用会出错。
- 查询具体法律数字(FLSA 薪资门槛、联邦最低工资、FMLA 周数): 有保质期, 应查最新法规。

### 常见失败模式

- **at-will ≠ 任意解雇**: 手册或口头"保障就业安全"的表述会被法院认定为默示合同, 例外比原则本身更危险。
- **别以为 NLRA 只约束有工会的组织**: 无工会企业同样受制于协同活动权利, 压制员工讨论工资即可能构成不当劳动行为。
- **别靠"叫咨询顾问"规避身份**: IRS/EEOC 看实质不看名分, 错分类要补缴税款与补发福利。
- **别给自愿离职附加条件**: 强制提前通知否则不得再雇佣, 会把 at-will 变成受约束的合同关系。

### 方法论局限 / 适用边界

- 美国法语境, 且各州差异极大; 具体法律数字随时随法规修订而变, 法律章节有"保质期"。
- 书反复以"咨询你的律师"结尾——在风险最高处, 书本身提供不了可独立站立的答案。
- 雇主视角写作, 不处理员工自身能动性与实际权力不对等。

### 容易混淆的邻近方法论

- 与 `harassment-and-investigation` 的报复条款: 报复在本 skill 是"举报后不利对待"的独立歧视形式; 反骚扰 skill 的报复是"知情即须行动"的边界。
- 与 `compensation-and-pay-equity` 的 FLSA 豁免: 那是薪酬合规的专属, 别在本 skill 里展开薪酬细节。

---

## 快速理解: 5 个示例问题

用这 5 个最常被问到的场景快速上手本 skill, 每个问题都对应它真正触发的处理动作:

1. **能不能就这样开掉一个没签合同的员工? 会不会被告?** — at-will 三大例外扫描
2. **公司招人要求本科以上, 结果被说歧视, 这算差别影响还是差别对待?** — 歧视双理论分析
3. **我们用的外包顾问, 到底算员工还是独立承包人?** — IRS 三组测试判断身份
4. **员工手册里写'公司可随时解雇', 会有风险吗?** — 措辞是否构成默示合同
5. **我们被起诉了, 对方说差别对待, 快帮我准备答辩。** — 判停: 已涉诉讼移交律师

## 相关 skills

本 skill 是整体的**法律地基**, 被以下 skill 依赖; 触发它们之前, 应先用这里的 at-will 例外、歧视双理论、报复与身份二分扫描一遍。

- **depended-on-by** [`job-analysis-and-ada`](../job-analysis-and-ada/SKILL.md) — ADA 合理便利是本法律地基的一个具体应用 (残疾定义 / undue hardship 判断)。
- **depended-on-by** [`recruiting-and-hiring`](../recruiting-and-hiring/SKILL.md) — 合法面试题与筛选标准的歧视红线源自歧视双理论。
- **depended-on-by** [`benefits-and-leave`](../benefits-and-leave/SKILL.md) — FMLA / ERISA / COBRA / WARN 等福利法律域的术语与门槛。
- **depended-on-by** [`harassment-and-investigation`](../harassment-and-investigation/SKILL.md) — quid pro quo / hostile environment / 报复的法定形态定义。
