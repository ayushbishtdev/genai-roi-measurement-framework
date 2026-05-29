# GenAI ROI Cheatsheet

> One-page reference for practitioners. All data sourced from [agileleadershipdayindia.org](https://agileleadershipdayindia.org). Last updated: May 2026.

---

## The Core Formula: Cost-Per-Outcome ROI

```
(Human Cost Per Outcome)
− (AI Cost Per Outcome + API Orchestration Overhead)
= Net Realized Savings Per Outcome

Net Savings × Monthly Volume of Successful Outcomes = Monthly Realized ROI
```

**What counts as an ironclad "outcome":**
- Tier 1 support ticket fully resolved — no escalation
- Legally compliant contract generated and routed for signature
- Legacy code migrated and passing all automated security tests

---

## The 3-Tier ROI Model

| Tier | When | What Value Looks Like | What to Measure |
|---|---|---|---|
| **Tier 1: Capability ROI** | Q1–Q2 | RAG pipelines, prompt libraries, governance, workforce fluency | Reusable assets created; deployment speed |
| **Tier 2: Realized ROI** | Q2–Q4 | Workflow automation, direct cost takeout, vendor consolidation | Tickets resolved without humans; vendor contracts cancelled |
| **Tier 3: Strategic ROI** | Q4+ | AI-enabled revenue, market differentiation | Revenue delta from AI products; sales cycle compression |

**Rule:** Never judge a Tier 1 project on Tier 2 metrics. That's how the 95% "failure" rate is manufactured.

---

## The 5 GenAI Value Dimensions

| Dimension | Measure | Don't Fall For |
|---|---|---|
| Time Savings | Hours × fully-loaded cost | Stopping at reclaimed hours — track redeployment |
| Productivity | Throughput + quality at constant headcount | Velocity without paired defect counter-metric |
| Cost Reduction | Actual vendor/headcount cuts | Indirect or estimated saves without attribution |
| Revenue Growth | A/B tested revenue delta from AI features | Over-attribution — apply conservative discount rate |
| Strategic Differentiation | Time-to-capability, data asset IP, talent retention | Forcing dollar figures where none are credible |

---

## 3 Board-Ready Metrics (Use These, Not Prompts/Seats)

1. **Direct Operational Cost Takeout** — Audited contract cancellations + vendor offboarding attributable to AI. No estimates.
2. **Deferred CapEx** — Fully-loaded cost of roles not hired because AI absorbed the workload (salary + benefits + equipment + recruiting).
3. **Defensible Revenue Lift** — A/B tested; control group required; conservative discount rate applied before presenting.

---

## Agentic AI vs RPA: Quick Decision Table

| Dimension | RPA | Agentic AI |
|---|---|---|
| Primary driver | Linear cost takeout | End-to-end outcome delivery |
| Cost structure | Fixed licensing | Variable tokens + orchestration |
| Exception handling | Fails — human required | Adapts autonomously |
| Payback horizon | 3–6 months | Mid-to-long term (staged) |
| Maintenance burden | High (breaks on UI changes) | Low (adapts to variation) |

**Deploy RPA when:** Highly standardized, rule-bound tasks on legacy systems with no APIs.  
**Deploy Agentic AI when:** Unstructured data, decision-making, or frequent process variations.  
**Best architecture:** Agentic AI as orchestrator + RPA bots as executors.

---

## Pilot-to-Production ROI Gates

Only **11% of AI agents reach production** (2026 data). Run these checks before scaling:

| Gate | Red Flag |
|---|---|
| Exception Rate Penalty | HITL rate not decreasing during pilot → won't scale profitably |
| Integration-to-Inference Ratio | Spending >$3 infra per $1 AI compute → broken unit economics |
| Model Drift Baseline | No rolling accuracy measurement → production will expose it expensively |

---

## 7 Agile AI Productivity KPIs (Ranked by CFO Trust)

1. **AI-Assisted Cycle Time Reduction** — Full pipeline, not just coding phase
2. **AI Code Acceptance Rate** — % usable without heavy refactor; <50% = distraction
3. **Sprint Goal Attainment vs. Story Point Inflation** — Goals met, not points burned
4. **DORA Delta** — Deployment Frequency + Change Failure Rate since AI adoption
5. **Time-to-Resolution for AI-Generated Defects** — Rising TTR = codebase comprehension loss
6. **HITL Exception Rate** — Flat rate = AI not learning, ROI stalling
7. **Outcome-Based Value Delivery** — Sprint output linked to revenue/cost/churn metrics

---

## GenAI Value in Scrum: 5-Step Model

1. **Lock baseline** — Cycle time + defect escape rate + sprint goal attainment (last 3–5 sprints)
2. **Decouple motion from outcome** — Lines of code ≠ ROI; measure lead time compression + bug reduction
3. **Update Definition of Done** — Add: AI peer review, security scan for hallucinated vulns, architectural standards check
4. **Embed into scrum events** — Daily Scrum: AI blockers. Sprint Planning: tag AI-heavy items. Retro: acceptance rate review
5. **Speak PO language** — "AI let us pull 2 additional roadmap items into this sprint" beats "we coded 30% faster"

---

## CFO Business Case Required Sections

- [ ] Strategic alignment (board-level priority, not tech features)
- [ ] Full cost forecast (inference + pipeline + integration + observability + HITL reviewer hourly)
- [ ] Capability ROI framing (build phase as infrastructure asset, not sunk cost)
- [ ] NPV/IRR model — 3 scenarios: conservative, baseline, aggressive
- [ ] Risk section: model drift, data privacy/governance, vendor lock-in + swap strategy
- [ ] Agreed baseline signed off by finance *before* pilot starts

---

## GCC Intelligence Arbitrage: The One-Line Test

> "Can a generic vendor LLM replicate this output without our contextual enterprise data?"

If yes → cost arbitrage play → defensible only short-term.  
If no → intelligence arbitrage play → defensible long-term.

**Track under GCC 4.0:**
- Time-to-Context (your pods vs. generic vendor for same specialized agent)
- IP Export Value (reusable assets shipped to global HQ)
- P&L Attribution (India-built capability → global revenue/cost impact)

---

## Key Industry Benchmarks (May 2026)

| Stat | Source |
|---|---|
| 95% of GenAI projects show no measurable ROI | MIT GenAI Divide study |
| ~25% of AI initiatives deliver expected ROI | IBM CEO research |
| 16% of AI initiatives scale enterprise-wide | IBM CEO research |
| 93% productivity lift among high GenAI adopters | PMI 2026 research |
| 71% of orgs deploying AI agents | 2026 industry data |
| Only 11% of AI agents reach production | 2026 industry data |
| Operational benefit: 7% → 25% in one half-year | Mindbreeze 2026 GenAI Confidence Index |
| GenAI value proof is the #1 hurdle to adoption | Gartner (nearly half of business leaders) |

---

*All frameworks sourced from Sanjay Saini's GenAI ROI series at [agileleadershipdayindia.org](https://agileleadershipdayindia.org/blogs/genai-roi-measurement-framework/genai-roi-measurement-framework.html). Submit corrections via GitHub issues.*
