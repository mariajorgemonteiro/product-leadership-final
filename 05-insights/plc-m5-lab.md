# Master Product Financials & Strategic Bets, Module 5 Lab

## Make your evaluation and funding decision
- **What assumption is doing the most work? If this number is 20-30% off, what changes?:** The assumption of the 4% individual-to-team conversion rate. The Churn and the team size are only relevant once a team exists.
The conversion rate decides how many teams exists

If the number is 20-30% down, then reach the kill criterion.
The 4.7-month payback doesn't reproduce from the stated inputs. If you charge acquisition cost to the team deal, you have to acquire 1 / 0.04 = 25 individuals to get one converting team:

CAC per team: 25 × $38 = $950
Monthly team revenue: $12 × 6 = $72
Payback: $950 / $72 ≈ 13.2 months, not 4.7
- **What is the structural problem in this case? Look past the headline numbers for something that does not hold up on closer inspection.:** We user to convert into a team maybe be already an existing user or a new user. We don't know
- **Is the kill criterion complete and actionable? Does it name the consequence, or hand the decision back to the room?:** Hand the decision back to the room. The decision is reevaluateed.
- **Your verdict: FUND / FUND WITH ONE CONDITION / DO NOT FUND. If a condition, name it; otherwise explain in one sentence.:** FUND WITH ONE CONDITION
First check how manny users are interested in having Fable being users on their team. Discover the baseline and compare with the 4% conversion rate guess assumed on the assumption.
Fund based on concrete data

## Write your business case
- **The strategic bet. What specific outcome are you backing, who does it serve, and what is the mechanism that connects the product decision to a financial result?:** ROCK: "Create a "crisis mode" flow for acute anxiety moments" , because it is tied to KR3 (12-month renewal among users who converted during an acute phase by 10%).

OUTCOME: Raise 12-month renewal among acute-phase converters from 25% to 35% (+10 percentage points). 

WHO SERVE: the premium users who converted during a hard stretch. They are my highest-intent payers and my worst churners.

MECHANISM: Crisis mode turns the moment that drove conversion into proof the product works when it matters. That raises renewal, and renewal is where LTV comes from.
- **The assumptions. List the assumptions your case rests on, then rank them: which one, if wrong, most changes your conclusion?:** ASSUMPTIONS
1) Lift size: +10 pts across all acute converters. This is the load-bearing number. At 40% adoption, adopters must renew at about 50% instead of 25%. Phase 1 exists to test it.
2) Causality: using crisis mode leads to renewal rather than faster recovery and earlier exit. The holdout tests this
3) Leading indicator: auto-renew still on at month 6 predicts 12-month renewal. We check this against last year's cohort before launch.
4) Adoption: at least 40% of acute-flagged users use crisis mode during an episode.
5) Clinical line: the flow stays wellness-only, with grounding, breathing and routing to crisis lines, and no assessment or scoring. The review is costed inside Phase 1, and it's a hard stop if the flow would be classified as a medical device.
6) Baseline: 40k acute converters a year, 25% renewal.
7) Ongoing renewal: users who renew once keep renewing at 60% a year. The stress case is 50%.
8) Costs and price: run cost is €100k a year (1 engineer plus clinical content upkeep, down from €150k). Price stays at €60 a year with a 15% store fee.


If #2 is wrong, the case returns nothing. If #1 is off by 30%, it falls below the go line.
- **The expected return. What does the bet generate and when? Express it at unit level (per customer) and at scale (what volume hits target).:** Unit level (per acute-phase converter):
 - Net renewal revenue: €60 × 85% = €51
 - LTV of one renewer: €51 ÷ 0.40 = €127.50
 - Incremental LTV per exposed converter at +10 pts: €12.75

At scale:
- Investment: €150k in Phase 1 plus €200k in gated Phase 2, €350k in total. Run cost is €100k a year.
- Exposure: 24k converters in year 1 (20% holdout) and 36k a year after (10% holdout).
- Incremental renewers: about 2,400 in year 1, then about 3,600 a year.
- Payback is about 4 years, and 8-year NPV at a 10% discount rate is €608k.
- Five cohorts return 2.0 : 1 on lifetime value against build plus run cost, or 1.6 : 1 if churn is 10 points higher.
- Stress tests: with 20% higher cost, payback is 4.3 years. With higher cost and higher churn, it's 4.5 years.
- At a +7-point lift, payback is 5.3 years and NPV only €179k. That's why +10 is the go line.
- Full-build economics don't reach 3:1. That would take about +15 points. The case to approve is a €150k experiment with its downside capped, not a €350k build.
- **The kill criterion. Name the specific metric, threshold, timeline, and financial consequence that tells the team to stop. Actionable, not a conversation.:** Phase 1 runs a 20% holdout of acute-flagged users. That gives about 4k holdout users and 16k treated users in the first 6 months, enough to detect a 5-point gap reliably.

- Early kill at launch + 3 months: if adoption among acute-flagged users is below 35%, stop.
- Main kill at launch + 6 months: if treated users don't beat the holdout by at least 10 points on auto-renew-still-on, stop.
- If either fires: Phase 2's €200k is not spent, the flow is sunset within one quarter (removing the €100k annual run cost), and the pod moves to the next rock. Maximum loss is about €175k.
- If both pass: Phase 2 is released and the holdout drops to 10% to confirm actual 12-month renewal.

## Stress-test and finalize
- **Paste your finalized business case here.:** ROCK: "Create a "crisis mode" flow for acute anxiety moments" , because it is tied to KR3 (12-month renewal among users who converted during an acute phase by +10 pts).

OUTCOME: Raise 12-month renewal among acute-phase converters from 25% to 35% (+10 percentage points). 

WHO SERVE: the premium users who converted during a hard stretch. They are my highest-intent payers and my worst churners.

MECHANISM: Crisis mode turns the moment that drove conversion into proof the product works when it matters. That raises renewal, and renewal is where LTV comes from.



** ASSUMPTIONS
1) Lift size: +10 pts across all acute converters. This is the load-bearing number. At 40% adoption, adopters must renew at about 50% instead of 25%. Phase 1 exists to test it.
2) Causality: using crisis mode leads to renewal rather than faster recovery and earlier exit. The holdout tests this
3) Leading indicator: auto-renew still on at month 6 predicts 12-month renewal. We check this against last year's cohort before launch.
4) Adoption: at least 40% of acute-flagged users use crisis mode during an episode.
5) Clinical line: the flow stays wellness-only, with grounding, breathing and routing to crisis lines, and no assessment or scoring. The review is costed inside Phase 1, and it's a hard stop if the flow would be classified as a medical device.
6) Baseline: 40k acute converters a year, 25% renewal.
7) Ongoing renewal: users who renew once keep renewing at 60% a year. The stress case is 50%.
8) Costs and price: run cost is €100k a year (1 engineer plus clinical content upkeep, down from €150k). Price stays at €60 a year with a 15% store fee.


If #2 is wrong, the case returns nothing. If #1 is off by 30%, it falls below the go line.


** EXPECTED RETURN
Unit level (per acute-phase converter):
 - Net renewal revenue: €60 × 85% = €51
 - LTV of one renewer: €51 ÷ 0.40 = €127.50
 - Incremental LTV per exposed converter at +10 pts: €12.75

At scale:
- Investment: €150k in Phase 1 plus €200k in gated Phase 2, €350k in total. Run cost is €100k a year.
- Exposure: 24k converters in year 1 (20% holdout) and 36k a year after (10% holdout).
- Incremental renewers: about 2,400 from the year-1 cohort, then about 3,600 a year.
- Payback is about 4 years, and 8-year NPV at a 10% discount rate is €608k.
- Five cohorts return 2.0 : 1 on lifetime value against build plus run cost, or 1.6 : 1 if churn is 10 points higher.
- Stress tests: with 20% higher cost, payback is 4.3 years. With higher cost and higher churn, it's 4.5 years.
- At a +7-point lift, payback is 5.3 years and NPV only €179k. That's why +10 is the go line.
- Full-build economics don't reach 3:1. That would take about +15 points. The case to approve is a €150k experiment with its downside capped, not a €350k build.


** KILL CRITERION
 Phase 1 runs a 20% holdout of acute-flagged users. That gives about 4k holdout users and 16k treated users in the first 6 months, enough to detect a 5-point gap reliably.

- Early kill at launch + 3 months: if adoption among acute-flagged users is below 25%, stop.
- Main kill at launch + 6 months: if treated users don't beat the holdout by at least 10 points on auto-renew-still-on, stop.
- If either fires: Phase 2's €200k is not spent, the flow is sunset within one quarter (removing the €100k annual run cost), and the pod moves to the next rock. Maximum loss is about €225k.
- If both pass: Phase 2 is released and the holdout drops to 10% to confirm actual 12-month renewal.
