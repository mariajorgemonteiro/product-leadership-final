# Lead and Develop High-Performing Teams, Module 3 Lab

## Name the situation
- **Who they are (role, not name), what you have observed, and how long it has been happening.:** In my company, it's expected the PMs to work closely with the development team and be responsible for the team's backlog management.
And in some products, like mine, we have a Overall PM (me) to coordinate the Area PMs, mentoring them, define the working model, make sure we have the space to review the product vision, etc.
The situation with one Senior PM is that she doesn't like to do backlog management, and she is managing 2 teams, this means that in one team I have a team leader doing her job and on the other team, the team leader refuse to do it and give her feedback to improve.
She want s to work on overall topics, specially topics that she likes, and push topics that she likes towards them teams, or bring technical topics for the team because since they are technical, they do not need her support (which is wrong).

I provided feedback already, with the situations, behaviour, told her the expectations and she plays the victim and that maybe her expectation towards the role maybe are wrong. But she knew since the beginning because the job description mentioning that. She wasn't expected to have such backlog and "bureaucracy" work.
She working with us for 2 years, but specially the last year, she is being more pushy to be autonomous, work on other topics and ask about how are the overall topics and in one specific topic, people complained that she did micromanaging.
On a more recent situation, she decided to change a date of a penetration test on it's own without clarifying with the other Area PMs/teams if they were having time to resolve the findings from last year penetration. Just because she shared a concern with me about the period that I previously set, and that I aligned individually with everyone involved.

## Make a diagnosis
- **Your diagnosis, plus one sentence on why. Is your frustration with their behavior, or with a decision you made?:** Hiring mismatch: she was already provided feedback about this. Before the role of Area PM and Overall PM wasn't clear, and the same for UX role (Area UX and Overall UX) and we create a RACI matrix for our team . We are a Product Team with all the PMs and UXs working on the Product,

Every time I provide feedback with concrete example of the situation, the behaviour, what it make me feel on in other and the impact of it, eventually she played the victim role that she though she was doing the right thing, but maybe the expectations were clearer.

## Write your opening line
- **One next action I will take in the next two weeks is:** I already provide the feedback in regards with the situation of the pen test. She already sent a message to the PMs involved. So I will wait for the next interactions since one PM is OoO.
- **The first sentence of the conversation I need to have is:** Regarding the situation of the pen test that you wanted to change, was a good initiative to ask for feedback for the other PM regarding the change of the dates after my feedback. It's important for the relationship between PMs that one of us is making decision that affects them or their teams without informing them.

## AI role-play
- **After you step out: what did the role-play change about how you will open this conversation for real?:** I didn't change.
I need to clarify to the person my expectations towards her role and provide her feedback because I want her to be part of the solution and not the problem.

## Refine and complete your charter
- **What We Own. What this team owns.:** Shared definitions

The rules below depend on these terms. Core owns the definitions, and changing one is a joint call.
 * Acute user (temporary definition, until the lifecycle state engine ships). A user is acute if any of these is true:
    ** they entered the crisis flow in the last [30] days
    ** their latest self-reported wellbeing score is in the bottom band
   ** the check-in safety guardrail flagged a disclosure in the last [14] days
 If a user's state is unknown or disputed, treat them as acute.
 * Onboarding handoff. A user moves from PM 1 to PM 2 at their first saved playbook entry or first completed check-in, or on day [14], whichever comes first.
 * Message. Anything that interrupts or prompts the user: push notifications, email, in-app banners or modals, and check-in prompts sent outside the app. Content the user opens themselves doesn't count.
 * Guardrail metric. A metric another team owns that an experiment must not harm. Guardrails are named before launch.

What the core Fable team owns (we decide)
 * The personal playbook and record engine (Bet 1). Saving "what helped me" at the moment of relief, how it's stored, and how it's used later.
* The shared user record and lifecycle state engine. The definitions of acute, recovering, steady, re-entering. There is one source of truth, every team uses it, and only we change it.
* Collecting passive signals. The Apple Health and Health Connect integrations, the consent records, and the data they produce.
* The acute / crisis flow and the core meditation and sleep content. Our proven strength, and part of the constraints.
* Shared platform: feature flags, experimentation analytics, holdout groups, and the definition of the day-90 wellbeing score baseline.
* The safety review process: making sure every flow that touches distress goes through counsel and the clinical advisors.



Lane |	Owns |	Primary metric
PM 1: Onboarding |	Sign-up to first value, days 0–7 activation, the UX of permission prompts (including the health-data ask)	Activation → feeds KR3
PM 2: Retention |	Maintenance paths (Bet 3), graduation rhythm, re-entry, second-path re-entry, the wording and timing of lifecycle messages after onboarding. | 	KR1
PM 3: AI check-in |	The check-in engine: questions, pacing logic, AI responses, drift detection (Bet 2), and the safety guardrails for disclosures inside a check-in |	KR2
Growth	Acquisition, paywall and pricing, free-to-premium conversion, running the messaging platform, win-back for users who have cancelled |	Conversion, resubscription

The rule for the AI check-in: it appears on other teams' screens, so the team whose screen it is (PM 1 or PM 2) decides where it goes, how often it shows up, and how it's framed on that screen. PM 3 decides what the check-in says and does, plus its safety behavior. PM 3 doesn't place check-ins on other teams' screens alone. Surface owners don't rewrite check-in logic.
- **What is out of scope.:** * Community, social, or "peer stories" features. This is our hard no.
* Anything diagnostic, treatment-like, or that suggests clinical claims.
* New content production. We sequence existing content until the paths show a gap.
* Wearables beyond Apple Health and Health Connect, for now.
* Children and teenagers. The product is for 25–45-year-olds only.
* Acquisition and pricing strategy. That's Growth's.
- **Cross-boundary decisions that need a joint call.:** These need everyone affected to agree before anyone ships:

Any change to the lifecycle state definitions or the shared user record. Core decides, but the affected PMs are consulted first.
Anything shown to a user in the acute state, whichever team owns the screen. Counsel and the clinical advisors must be involved.
A paywall or upsell shown to acute or recovering users. This affects KR3 directly and carries a trust risk.
The total weekly messaging budget per user. It's shared across PM 2, PM 3 and Growth and set once a quarter. No team goes over it alone.
Where check-ins appear and how often on onboarding or retention screens.
The timing and wording of the health-data consent ask.
Changes to how the wellbeing score is defined or collected, because KR2 depends on it.
Experiments that affect another team's KR or use shared cohorts and holdout groups.
Win-back campaigns aimed at users in the re-entering state. This is where Growth and PM 2 overlap.
Any new user-facing claim about wellbeing outcomes. Counsel reviews it.
- **How We Decide. Who decides feature and scope calls.:** Every decision has one owner. Each decision names a Driver, one Approver, the people Consulted, and the people Informed. If nobody is named, the owner of the lane where the work ships decides.
Tie-breakers, applied in this order:
User safety and trust
The hard no and the clinical line
The shared objective (KR1–3)
A single team's local metric
Short-term conversion never wins against day-120+ retention or renewal.
Match speed to reversibility. If a change is reversible and behind a feature flag, the owner decides and informs others within a day. If it's hard to undo (data model, consent, pricing, anything touching acute users), it's a joint call as "consult first, with a 2-day window to object; if there's an objection, it goes into escalation." Unanimity is required only for the counsel veto.

Default while a decision is pending: the status quo stays. The contested change stays behind a flag that's switched off.
- **How cross-team conflicts escalate.:** 1. Raise it (day 0). Any PM posts a one-page decision brief in the decisions channel. It covers the problem, the options, the data, which KR each option affects, and a recommendation.
2. The PMs involved resolve it themselves (within 2 business days). They meet with their eng and design leads and apply the tie-breakers. Most conflicts should end here. The outcome goes in the decision log.
3. Escalate to me (within 3 business days). I decide in the weekly product triage or sooner, after hearing both sides from the brief. If core is one of the parties, it skips me and goes straight to step 4.
- **Who resolves escalations from outside the team.:** 4. Escalate to Head of Product and the Growth lead (within 5 business days). This is for Product vs Growth conflicts, or when core is a party. If they can't agree, it goes to the CEO.
5. Safety fast-track (within 24 hours). Any conflict that touches distress, crisis disclosure, or clinical claims goes straight to counsel and the clinical advisors. The default is not to ship until they clear it.

## Show and swap your team charter
- **Where does the charter leave room for interpretation that could cause a conflict?:** _(not filled in)_
