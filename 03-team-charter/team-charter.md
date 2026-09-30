# Team Charter: Fable

> Module 3 · Lead and Develop High-Performing Teams, ★ Deliverable 3
>
> Define how your team operates. Two completed components: **What We Own** and **How We Decide**.

## 1. What We Own

_The team's mandate: the outcomes and surfaces this team is accountable for end-to-end, and the explicit edges where your ownership stops._

| Area | We own it | We influence it (don't own) |
|---|---|---|
| **Core · Personal playbook & record engine** (Bet 1) | Saving "what helped me" at the moment of relief, how it's stored, and how it's used later | How other lanes use the playbook on their surfaces |
| **Core · Shared user record & lifecycle state engine** | The definitions of acute, recovering, steady and re-entering. One source of truth that every team uses and only Core changes | Affected PMs are consulted before any change |
| **Core · Passive signals** | Apple Health and Health Connect integrations, the consent records, and the data they produce | Timing and wording of the health-data consent ask (PM 1's screen, joint call) |
| **Core · Acute / crisis flow & core content** | The crisis flow and the core meditation and sleep content, our proven strength | Anything shown to acute users on other teams' screens (joint call with counsel and clinical advisors) |
| **Core · Shared platform** | Feature flags, experimentation analytics, holdout groups, and the definition of the day-90 wellbeing score baseline | Experiments that affect another team's KR or use shared cohorts |
| **Core · Safety review process** | Making sure every flow that touches distress goes through counsel and the clinical advisors | The clearance itself belongs to counsel and the clinical advisors |
| **PM 1 · Onboarding** (Activation → KR3) | Sign-up to first value, days 0–7 activation, the UX of permission prompts (including the health-data ask) | What the AI check-in says and does on onboarding screens (PM 3) |
| **PM 2 · Retention** (KR1) | Maintenance paths (Bet 3), graduation rhythm, re-entry, second-path re-entry, the wording and timing of lifecycle messages after onboarding | The weekly messaging budget (shared with PM 3 and Growth); win-back for re-entering users (overlap with Growth) |
| **PM 3 · AI check-in** (KR2) | The check-in engine: questions, pacing logic, AI responses, drift detection (Bet 2), and the safety guardrails for disclosures inside a check-in | Where check-ins appear and how often on PM 1 and PM 2 screens |
| **Growth** (Conversion, resubscription) | Acquisition, paywall and pricing, free-to-premium conversion, running the messaging platform, win-back for users who have cancelled | Paywalls or upsells shown to acute or recovering users (joint call) |

> Our mission in one line: From getting through it to staying well. We turn each user's private history of what helped them into readiness for what comes next.

### Shared definitions

The rules in this charter depend on these terms. Core owns the definitions, and changing one is a joint call.

- **Acute user** (temporary definition, until the lifecycle state engine ships). A user is acute if any of these is true: they entered the crisis flow in the last [30] days; their latest self-reported wellbeing score is in the bottom band; or the check-in safety guardrail flagged a disclosure in the last [14] days. If a user's state is unknown or disputed, treat them as acute.
- **Onboarding handoff.** A user moves from PM 1 to PM 2 at their first saved playbook entry or first completed check-in, or on day [14], whichever comes first.
- **Message.** Anything that interrupts or prompts the user: push notifications, email, in-app banners or modals, and check-in prompts sent outside the app. Content the user opens themselves doesn't count.
- **Guardrail metric.** A metric another team owns that an experiment must not harm. Guardrails are named before launch.

### The AI check-in rule

The check-in appears on other teams' screens. The team whose screen it is (PM 1 or PM 2) decides where it goes, how often it shows up, and how it's framed on that screen. PM 3 decides what the check-in says and does, plus its safety behavior. PM 3 doesn't place check-ins on other teams' screens alone, and surface owners don't rewrite check-in logic.

### Out of scope

- Community, social, or "peer stories" features. This is our hard no.
- Anything diagnostic, treatment-like, or that suggests clinical claims.
- New content production. We sequence existing content until the paths show a gap.
- Wearables beyond Apple Health and Health Connect, for now.
- Children and teenagers. The product is for 25–45-year-olds only.
- Acquisition and pricing strategy. That's Growth's.

## 2. How We Decide

_The team's decision-making operating model: the decisions you make, who makes each call, and how disagreements resolve._

Every decision has one owner and names a Driver, one Approver, the people Consulted, and the people Informed. If nobody is named, the owner of the lane where the work ships decides.

| Decision type | Who decides | Who's consulted | How we break a tie |
|---|---|---|---|
| Reversible change behind a feature flag, inside one lane | Lane owner | Others informed within a day | Tie-breaker order (below) |
| Hard-to-undo change (data model, consent, pricing, anything touching acute users) | Joint call | Everyone affected, consulted first with a 2-day window to object | Any objection goes into escalation |
| Lifecycle state definitions or the shared user record | Core | Affected PMs, consulted first | Straight to Head of Product and Growth lead (Core is a party) |
| Anything shown to a user in the acute state, whichever team owns the screen | Joint call | Counsel and the clinical advisors (must be involved) | Safety fast-track; default is not to ship until cleared |
| Paywall or upsell shown to acute or recovering users | Joint call | Growth and the affected PMs | Short-term conversion never wins against day-120+ retention or renewal (KR3 and trust risk) |
| Total weekly messaging budget per user | Joint call, set once a quarter | PM 2, PM 3, Growth | No team goes over it alone; escalation ladder |
| Where check-ins appear and how often on onboarding or retention screens | Surface owner (PM 1 or PM 2) | PM 3 | AI check-in rule, then escalation ladder |
| Check-in content, logic and safety behavior | PM 3 | Counsel and clinical advisors for anything touching distress | Safety fast-track |
| Timing and wording of the health-data consent ask | Joint call | PM 1, Core | Tie-breaker order: user safety and trust first |
| How the wellbeing score is defined or collected | Joint call | Core, PM 3 (KR2 depends on it) | Tie-breaker order |
| Experiments that affect another team's KR or use shared cohorts and holdout groups | Joint call | Owners of the affected KRs; guardrails named before launch | Tie-breaker order |
| Win-back campaigns aimed at users in the re-entering state | Joint call | Growth, PM 2 | Head of Product and Growth lead |
| Any new user-facing claim about wellbeing outcomes | Joint call | Counsel reviews it (veto) | Counsel veto is the only decision that requires unanimity |

> Our default: the owner of the lane where the work ships decides; we escalate to the Overall PM when the PMs involved can't resolve it themselves within 2 business days.

### Tie-breakers, applied in this order

1. User safety and trust
2. The hard no and the clinical line
3. The shared objective (KR1–3)
4. A single team's local metric

Short-term conversion never wins against day-120+ retention or renewal. While a decision is pending, the status quo stays and the contested change stays behind a flag that's switched off.

### Escalation path

1. **Raise it (day 0).** Any PM posts a one-page decision brief in the decisions channel covering the problem, the options, the data, which KR each option affects, and a recommendation.
2. **The PMs involved resolve it themselves (within 2 business days).** They meet with their eng and design leads and apply the tie-breakers. Most conflicts should end here. The outcome goes in the decision log.
3. **Escalate to the Overall PM (within 3 business days).** Decided in the weekly product triage or sooner, after hearing both sides from the brief. If Core is one of the parties, skip to step 4.
4. **Escalate to the Head of Product and the Growth lead (within 5 business days).** For Product vs Growth conflicts, or when Core is a party. If they can't agree, it goes to the CEO.
5. **Safety fast-track (within 24 hours).** Any conflict that touches distress, crisis disclosure, or clinical claims goes straight to counsel and the clinical advisors. The default is not to ship until they clear it.

## Link to full artifact

[03-team-charter/team-charter-v0.md](team-charter-v0.md) (Module 3 lab working notes)
