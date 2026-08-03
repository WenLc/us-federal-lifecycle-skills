# US Federal Lifecycle Skills

A set of 15 Claude Code skills covering the full employee lifecycle under the framework of US employment compliance and federal labor laws. Each skill is a self-contained methodology that activates automatically via trigger keywords in conversation and produces executable steps and decision criteria.

## What This Is

15 ready-to-use HR and employment compliance methodology skills spanning the complete employee lifecycle — from workforce planning, recruiting, and onboarding, through performance, compensation, benefits, and employee relations, to termination and layoff. Each skill directory contains a single `SKILL.md`, organized into six sections:

| Section | Purpose |
|---|---|
| **R — Core Idea** | The core problem this methodology addresses |
| **I — Framework** | The methodology structure, with counterintuitive points made explicit |
| **A1 — Applications** | Demonstrations in real-world scenarios |
| **A2 — Triggers** | When this skill should be invoked |
| **E — Execution** | Step-by-step actions + completion criteria + stop conditions |
| **B — Boundaries** | When not to use it / common failure modes / methodological limits |

## What These Skills Can Do

### Strategy & Planning
| Skill | What it solves |
|---|---|
| `workforce-planning` | Derive workforce needs from strategy, close gaps via buy/build/borrow/rent, and make succession a standing process |

### Talent Acquisition
| Skill | What it solves |
|---|---|
| `employment-law-basics` | Legal foundation before any employment decision: at-will exceptions, disparate treatment vs. impact, retaliation, independent-contractor classification |
| `job-analysis-and-ada` | Define what a job truly requires first; essential functions and reasonable accommodation follow |
| `recruiting-and-hiring` | Behavioral interviews / structured scoring / reference checks / offer — evidence-based hiring decisions |
| `onboarding` | 30/60/90 onboarding structure that gets new hires to full productivity |

### Employee Experience
| Skill | What it solves |
|---|---|
| `employee-experience-and-retention` | Engagement is measurable and manageable; turnover has costs and causes |
| `rewards-and-recognition` | Start recognition design by asking employees; rewards can't fix bad leadership |

### Total Rewards
| Skill | What it solves |
|---|---|
| `compensation-and-pay-equity` | Job evaluation → market pricing → structured pay system + controlled-gap pay equity audits |
| `benefits-and-leave` | FMLA/COBRA/WARN/ERISA statutory benefit boundaries — check the thresholds before applying the rules |

### Employee Development
| Skill | What it solves |
|---|---|
| `performance-management` | Year-round closed loop of goals → feedback → documentation; a PIP is a path to improvement, not a prelude to termination |
| `development-and-coaching` | Assess needs before designing development; coaching is a confidential relationship, not a fix-it tool |

### Employee Relations
| Skill | What it solves |
|---|---|
| `harassment-and-investigation` | Harassment determination (impact over intent) + know-and-act obligations + investigation process |
| `dei` | DEI is a six-step journey, data first; affirmative action is not quotas |
| `documentation-and-policies` | Documentation as protection: facts not conclusions, document as it happens, third-party readable |
| `termination-and-layoff` | Prepare terminations/layoffs like interviews: classification, evidence discipline, termination-meeting scripts |

## Who It's For

- **HR professionals**: apply the methodologies directly to process design and compliance management.
- **People managers and decision-makers**: get a structured path for high-risk situations such as discipline, termination, and harassment complaints.
- **Small business owners and startups**: establish a baseline of employment compliance without a formal HR department.
- **HR tech product and AI agent developers**: integrate these skills as invocable tools into your own products and workflows.

## How to Use

### Install

```bash
# User-level (available in all projects)
cp -r <skill-slug> ~/.claude/skills/

# Or project-level
cp -r <skill-slug> .claude/skills/
```

Copy the skill directories you need into your skills folder. No additional configuration is required.

### Trigger

Ask a question in Claude Code / Cursor, and the matching skill activates automatically:

```
> An employee keeps missing targets. Should I terminate or give a chance to improve? How do I document it?
→ Activates performance-management: attribute the gap → PIP (a path to improvement)
```

Each skill's `description` field defines the trigger conditions and the "not applicable" boundaries; the agent's routing logic decides activation.

## Legal Disclaimer

The content in this repository is organized under the framework of US federal employment law (at-will / Title VII / ADA / ADEA / FMLA / COBRA / WARN / FLSA / ERISA / NLRA, etc.). Statutory provisions and specific thresholds (e.g., FLSA exempt salary threshold, WARN notice headcounts, OWBPA consideration periods) change over time and with regulatory amendments — verify current law before use, and consult a qualified attorney for high-stakes decisions. State law varies significantly; readers outside the US must substitute their local employment law.
