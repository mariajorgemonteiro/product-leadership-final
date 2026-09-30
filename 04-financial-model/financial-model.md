# Financial Model: Fable

> Module 5 · Master Product Financials & Strategic Bets, ★ Deliverable 5
>
> The business case for funding your bet, and the explicit kill criteria that would tell you to stop.

## 1. Business case

_Why this initiative is worth funding over the alternatives._

**The bet.** Rock: "Create a crisis mode flow for acute anxiety moments", tied to **KR3** (raise 12-month renewal among users who converted during an acute phase).

- **Outcome:** raise 12-month renewal among acute-phase converters from **25% to 35%** (+10 percentage points).
- **Who it serves:** premium users who converted during a hard stretch. They are our highest-intent payers and our worst churners.
- **Mechanism:** crisis mode turns the moment that drove conversion into proof the product works when it matters. That raises renewal, and renewal is where LTV comes from.

### Assumptions (ranked by how much they change the conclusion)

| Assumption | Value | Source / rationale |
|---|---|---|
| **1. Lift size** (load-bearing) | +10 pts renewal across all acute converters | At 40% adoption, adopters must renew at about 50% instead of 25%. Phase 1 exists to test it. If this is off by 30%, the case falls below the go line. |
| **2. Causality** | Using crisis mode leads to renewal, not faster recovery and earlier exit | Tested by the holdout. If this is wrong, the case returns nothing. |
| **3. Leading indicator** | Auto-renew still on at month 6 predicts 12-month renewal | Checked against last year's cohort before launch. |
| **4. Adoption** | ≥ 40% of acute-flagged users use crisis mode during an episode | Required for the lift in #1 to reach the whole converter base. |
| **5. Clinical line** | Wellness-only: grounding, breathing, routing to crisis lines; no assessment or scoring | Review is costed inside Phase 1. Hard stop if the flow would be classified as a medical device. |
| **6. Baseline** | 40k acute converters a year, 25% 12-month renewal | Current cohort data. |
| **7. Ongoing renewal** | Users who renew once keep renewing at 60% a year (stress case 50%) | Drives LTV of a renewer. |
| **8. Price and run cost** | €60/year with a 15% store fee; run cost €100k/year (1 engineer + clinical content upkeep, down from €150k) | Pricing unchanged; run cost reduced in the finalized case. |

### Expected return

**Unit level (per acute-phase converter)**

| Metric | Value | Calculation |
|---|---|---|
| Net renewal revenue | €51 / year | €60 × 85% (after 15% store fee) |
| LTV of one renewer | €127.50 | €51 ÷ 0.40 annual churn |
| Incremental LTV per exposed converter | €12.75 | €127.50 × +10 pts lift |
| CAC | Not applicable | No new acquisition: the bet targets users who already converted |

**At scale**

| Metric | Value |
|---|---|
| Investment required | €350k total: €150k Phase 1 + €200k gated Phase 2, plus €100k/year run cost |
| Exposure | 24k converters in year 1 (20% holdout), 36k a year after (10% holdout) |
| Incremental renewers | ~2,400 from the year-1 cohort, then ~3,600 a year |
| Payback period | ~4 years |
| Expected return | 8-year NPV of €608k at a 10% discount rate; five cohorts return 2.0 : 1 on lifetime value against build + run cost (1.6 : 1 if churn is 10 pts higher) |
| Stress tests | +20% cost → payback 4.3 years; higher cost and higher churn → 4.5 years |
| Go line | At +7 pts lift, payback is 5.3 years and NPV only €179k. That's why +10 pts is the go line. |
| Limit | Full-build economics don't reach 3 : 1 (that would take ~+15 pts). The case to approve is a **€150k experiment with capped downside**, not a €350k build. |

### Why this over the alternatives

- **Therapist-matching premium tier (not funded this year).** We have no evidence it moves retention, and a vetted therapist network is a large, hard-to-reverse cost and liability commitment. It removes a revenue and retention lever the CEO was counting on, so it stays open: if data shows real demand for human support, we bring a scoped pilot to next year's roadmap.
- **Dependency with Growth.** Growth asked for 2 engineers and access to the AI check-in layer for 6 weeks this quarter; the personalised prompt trigger needs about 2 weeks of engineering. With it, Growth targets +15% Day-7 activation (Q3 OKR); without it, a lower-confidence experiment reaches about +7%. Agreed: Core assesses a small first delivery in the first month, then continues the full AI layer.

> **The case in one paragraph:** Acute-phase converters are our highest-intent payers and our worst churners: 40k a year renewing at only 25%. A wellness-only crisis mode turns the moment that drove conversion into proof the product works, and we bet it lifts 12-month renewal to 35%. At +10 pts each exposed converter is worth €12.75 of extra LTV, for about 3,600 extra renewers a year, a ~4-year payback and an 8-year NPV of €608k. The economics only clear the bar at +10 pts and never reach 3 : 1 at full build, so we're not asking for €350k. We're asking for a €150k Phase 1 with a 20% holdout that tests lift and causality, with Phase 2's €200k released only if the kill criteria pass, and a maximum loss of about €225k. We choose this over a therapist-matching tier, which has no retention evidence and a costly, hard-to-reverse network behind it.

## 2. Kill criteria

_The specific signals that would tell you this bet is no longer worth pursuing. Be explicit about the metric, the threshold, and the timeline._

Phase 1 runs a 20% holdout of acute-flagged users: about 4k holdout and 16k treated users in the first 6 months, enough to detect a 5-point gap reliably.

> **Early kill:** If **crisis mode adoption among acute-flagged users** does not reach **25%** by **launch + 3 months**, we will **stop: Phase 2's €200k is not spent, the flow is sunset within one quarter, and the pod moves to the next Rock**.
>
> **Main kill:** If **auto-renew-still-on among treated users** does not beat the holdout by **at least 10 points** by **launch + 6 months**, we will **stop: Phase 2's €200k is not spent, the flow is sunset within one quarter (removing the €100k annual run cost), and the pod moves to the next Rock**.
>
> **Hard stop:** If **the clinical review classifies the flow as a medical device**, we will **stop immediately**.

Maximum loss if a kill fires: about **€225k**. If both checks pass, Phase 2 is released and the holdout drops to 10% to confirm actual 12-month renewal.

## Link to full artifact

- [financial-model-part2.md](financial-model-part2.md): Module 5 lab, business case and kill criteria
- [financial-model-v0.md](financial-model-v0.md): Module 4 lab, alignment message and negotiation notes
