# AI Business Case Pre-Submission Checklist

Use this before submitting any GenAI funding proposal to a finance committee or board. Each item maps to a known CFO objection. Incomplete items are the most common reason proposals are rejected.

Source framework: [agileleadershipdayindia.org/blogs/genai-roi-measurement-framework/](https://agileleadershipdayindia.org/blogs/genai-roi-measurement-framework/genai-roi-measurement-framework.html)

---

## Section 1: Strategic Framing

- [ ] **The proposal leads with a board-level strategic priority** — not a technology description. It says "reduce cost-to-serve by X%" or "accelerate time-to-revenue by Y quarters," not "implement an LLM."
- [ ] **All 5 GenAI value dimensions are addressed**, even if some are marked "directional" or "leading indicator only":
  - [ ] Time savings
  - [ ] Productivity gains
  - [ ] Cost reduction
  - [ ] Revenue growth
  - [ ] Strategic differentiation
- [ ] **Confidence levels are explicit per dimension.** "High confidence on cost and time, directional on revenue" is more credible than equal confidence across all five.
- [ ] **No superlatives** ("transformative," "revolutionary," "game-changing") in the executive summary.

---

## Section 2: Cost Forecast

- [ ] **Token/inference costs are modeled** with a variable range, not a flat estimate. Include a spike scenario (e.g., +20% inference cost).
- [ ] **Data pipeline build and maintenance costs are included** — not just the AI model licensing fee.
- [ ] **API integration costs are itemized.** The cost of routing enterprise data to external LLM APIs often exceeds the AI compute cost itself.
- [ ] **Observability and monitoring tooling costs are included** (vector database hosting, prompt optimization, drift monitoring).
- [ ] **Human-in-the-loop (HITL) reviewer costs are modeled.** Calculate the hourly cost of domain experts who must validate AI edge-case outputs. This is the most commonly omitted line item and the one that collapses margins in production.
- [ ] **Model drift and retraining costs are budgeted.** AI models degrade as real-world data diverges from training data. This is invisible in pilots and expensive in production.

---

## Section 3: ROI Staging (Capability → Realized → Strategic)

- [ ] **Tier 1 (Capability) ROI is explicitly named and described.** The proposal does not ask finance to fund only what shows up on the P&L in Q1.
- [ ] **The build-phase deliverables are defined as infrastructure assets**, not sunk costs: RAG pipelines, governance frameworks, prompt libraries, trained workforce.
- [ ] **Tier 2 (Realized) ROI has a specific timeline** (e.g., "direct cost takeout expected in Q3") with named metrics (support tickets resolved without human escalation; vendor contracts cancelled).
- [ ] **Tier 3 (Strategic) ROI is acknowledged** as a future compounding benefit — not overpromised, but not omitted.
- [ ] **Finance has signed off on the staged timeline before the pilot starts.** If the CFO doesn't agree on "what success looks like at month 3," they will use that ambiguity against you at the budget review.

---

## Section 4: Financial Model

- [ ] **NPV and IRR are calculated**, not just a simple payback period. AI requires heavy upfront investment before delivering compounding returns — NPV is the only metric that accurately captures lifecycle value.
- [ ] **Three scenarios are modeled**: conservative, baseline, aggressive.
  - Conservative: inference costs +20%, adoption 50% slower than forecast
  - Baseline: plan assumptions
  - Aggressive: faster adoption, volume discounts locked in
- [ ] **The model treats the AI as a digital labor asset, not a software license.** Fully-loaded cost of the legacy human process (salary + benefits + software + overhead) is the baseline.

---

## Section 5: Board-Ready Metrics (3 Required)

- [ ] **Direct Operational Cost Takeout is included**: specific vendor contracts to be cancelled, outsourced labor to be eliminated — audited, not estimated.
- [ ] **Deferred CapEx is calculated**: fully-loaded cost of roles not hired because AI absorbs the workload. Include salary + benefits + equipment + recruiting fees.
- [ ] **Defensible Revenue Lift uses A/B methodology**: a control group is defined, a conservative discount rate is applied, attribution logic is documented.
- [ ] **No vanity metrics in the board deck**: prompts run, seats licensed, pilots launched, and "time saved" without redeployment evidence are removed.

---

## Section 6: Risk Section (Non-Negotiable)

A business case with zero acknowledged risks will be rejected. Document these with specific mitigations:

- [ ] **Model drift risk**: How often will the model be retrained? What triggers a retraining cycle? What is the cost?
- [ ] **Data privacy and governance risk**: Where does enterprise data go when sent to an external LLM API? What data classification rules apply? Who audits compliance?
- [ ] **Vendor lock-in risk**: Is there a model-swap strategy? What would it cost and take to migrate to an alternative foundation model if pricing becomes predatory?
- [ ] **Production scaling risk**: The proposal explicitly models the pilot-to-production cost gap. Note: 71% of organizations deploy AI agents, only 11% reach production. Show that your model accounts for integration, governance, and cloud compute at scale.
- [ ] **HITL dependency risk**: What happens to margins if the human oversight requirement does not decrease as projected?

---

## Section 7: Baseline Agreement

- [ ] **A pre-AI baseline is documented and agreed upon with finance before the pilot starts.** This is the single most effective way to neutralize the "we can't prove the AI caused this" objection at the budget review.
- [ ] **Baseline captures**: cost-to-serve per unit, cycle time, defect escape rate, manual headcount for the target process, and current vendor spend in scope.
- [ ] **Both the technology leader and the finance sponsor have signed/stamped the baseline.** Email confirmation from the CFO's office is sufficient.

---

## Final Check Before Submission

- [ ] Does every number in the deck trace back to an audited source or an agreed baseline?
- [ ] Is the presentation structured as a diversified AI portfolio (low-risk cost-savers + high-risk revenue generators), not a single isolated pilot?
- [ ] Does the deck address the pilot-to-production gap explicitly — showing the board you know only 11% of AI agents reach production and that your plan accounts for that?
- [ ] Could a skeptical CFO read this and think "they understand the risks and have modeled them honestly"?

---

*Framework by Sanjay Saini. Full business case guide: [agileleadershipdayindia.org/blogs/genai-roi-measurement-framework/ai-investment-business-case-template.html](https://agileleadershipdayindia.org/blogs/genai-roi-measurement-framework/ai-investment-business-case-template.html)*
