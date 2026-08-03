# US Federal Lifecycle Skills

一套覆盖美国雇佣合规与联邦劳动法框架下、员工全生命周期管理的 15 个 Claude Code skills。每个 skill 是一个自包含的方法论, 在对话中通过触发词自动激活, 直接输出可执行的操作步骤与判断标准。

## 这是什么

15 个开箱即用的 HR / 雇佣合规方法论 skills, 覆盖从岗位规划、招聘、入职, 到绩效、薪酬、福利、员工关系, 再到终止雇佣的完整员工生命周期。每个 skill 目录包含一个 `SKILL.md`, 分六段组织:

| 段落 | 作用 |
|---|---|
| **R — 核心要旨** | 该方法论要解决的核心问题 |
| **I — 方法论骨架** | 反直觉要点显式标出的方法论结构 |
| **A1 — 应用案例** | 真实场景中的应用示范 |
| **A2 — 触发场景** | 什么情况下应该调用它 |
| **E — 可执行步骤** | 1-2-3 步骤 + 完成标准 + 判停条件 |
| **B — 边界** | 何时不适用 / 常见失败模式 / 方法论局限 |

## 能干什么

### 战略与规划
| Skill | 解决什么问题 |
|---|---|
| `workforce-planning` | 从战略倒推人力需求, 用买/建/借/租补缺口, 继任做成常设流程 |

### 人才获取
| Skill | 解决什么问题 |
|---|---|
| `employment-law-basics` | 人事决策前的法律地基: at-will 例外、歧视双理论、报复与身份二分 |
| `job-analysis-and-ada` | 先定义"职位到底要什么", 核心职能与合理便利由此而来 |
| `recruiting-and-hiring` | 行为面试/结构化评分/背调/offer — 用证据做录用决策, 宁缺毋滥 |
| `onboarding` | 30/60/90 入职结构, 把新人安全送到"能干活" |

### 员工体验
| Skill | 解决什么问题 |
|---|---|
| `employee-experience-and-retention` | 敬业度可测量可管理, 流失有成本有归因 |
| `rewards-and-recognition` | 认可设计的起点是问员工; 奖励救不了坏领导 |

### 全面回报
| Skill | 解决什么问题 |
|---|---|
| `compensation-and-pay-equity` | 职位评估→市场定价→成结构的薪酬系统 + pay equity 受控差距审计 |
| `benefits-and-leave` | FMLA/COBRA/WARN/ERISA 法定福利边界 — 先查门槛再套规则 |

### 员工发展
| Skill | 解决什么问题 |
|---|---|
| `performance-management` | 目标→反馈→文档全年闭环; PIP 是改进之路而非辞退前奏 |
| `development-and-coaching` | 先评估需求再设计发展; 教练是保密关系而非修理工具 |

### 员工关系
| Skill | 解决什么问题 |
|---|---|
| `harassment-and-investigation` | 骚扰判定 (影响重于意图) + 知情即行动 + 调查流程 |
| `dei` | DEI 是六步旅程, 数据先行, 平权行动不是配额 |
| `documentation-and-policies` | 文档是保护层: 事实非结论、事发即记、第三方可读 |
| `termination-and-layoff` | 解雇/裁员像面试一样准备: 分类/证据纪律/终止会议脚本 |

## 适合谁

- **HR 专业人员**: 把方法论直接用于流程设计与合规管理, 减少凭经验拍脑袋。
- **人事 / 管理决策者**: 面临纪律处分、解雇、骚扰投诉等高风险场景时, 获得结构化的应对路径。
- **中小企业主 / 初创团队**: 没有成型 HR 部门时, 用这些 skill 建立基本的合规底线。
- **HR 科技产品 / AI agent 开发者**: 把这些技能作为可调用的工具, 集成进自己的产品与工作流。

## 如何使用

### 安装

```bash
# 用户级 (所有项目可用)
cp -r <skill-slug> ~/.claude/skills/

# 或项目级
cp -r <skill-slug> .claude/skills/
```

把需要的 skill 目录复制到你的 skills 目录即可, 无需额外配置。

### 触发

在 Claude Code / Cursor 中提问, 触发词命中即自动激活对应 skill, 例如:

```
> 下属持续不达标, 直接开人还是先给改进机会? 怎么留证据?
→ 激活 performance-management: 差距归因 → PIP (改进之路)
```

每个 skill 的 `description` 字段定义了触发条件与"不适用"边界, 由 agent 的路由逻辑决定激活。

## 法律声明

本仓库内容基于美国联邦雇佣法框架 (at-will / Title VII / ADA / ADEA / FMLA / COBRA / WARN / FLSA / ERISA / NLRA 等) 整理。法律条文与具体阈值 (如 FLSA 豁免薪资门槛、WARN 通知人数、OWBPA 考虑期) 会随时间与法规修订而变化, 使用前务必核实现行法条, 高风险决策请咨询专业律师。各州法律差异巨大, 非美国司法辖区的读者需替换为当地劳动法。
