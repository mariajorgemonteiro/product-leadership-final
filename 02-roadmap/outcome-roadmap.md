# Outcome Roadmap & Trade-off Memo: Fable

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2
>
> Translate your strategy into a multi-team, outcome-driven roadmap, and a memo defending the hard prioritization calls behind it.

**From getting through it to staying well.** Fable is the wellbeing app people keep paying for after they're already better. We turn each user's private history of what helped them into readiness for what comes next.

**Objective:** Keep users active after an acute stretch

- **KR1:** Day-120+ retention of the premium cohort up 10% in 12 months
- **KR2:** 50% of retained graduates maintain or improve their wellbeing score, day 90 → 180
- **KR3:** 12-month renewal among users who converted while acute up 10%

## 1. Outcome roadmap

_A multi-team roadmap organized by **outcomes**, not feature lists. Show how near-term revenue pressure is balanced against long-term platform bets._

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | **Bet 1 · KR3 Renewal.** If users save "what helped me" as their personal playbook while leaving a hard stretch, they'll see value beyond the crisis and renew at 12 months. _(Replaces: crisis mode flow. Capture the playbook at the moment of relief.)_ | _to assign_ | % of acute users with ≥1 saved entry; premium cancellations at 30 and 90 days compared with a control group |
| Now (0 to 3 mo) | **Bet 2 · KR2 Wellbeing.** If we combine sleep and activity signals with a quick self-report check-in, we can spot a user drifting before their wellbeing score drops. _(Replaces: Apple Watch integration. Apple Health + Health Connect, both platforms.)_ | _to assign_ | Opt-in rate; how often a change in signals comes before a drop in score |
| Now (0 to 3 mo) | **Bet 3 · KR1 Retention.** If users who are better get a milestone-based maintenance path built from existing content, they'll keep checking in lightly past day 120. _(Replaces: content library. Put existing content in order instead of making new content.)_ | _to assign_ | First-path start and completion rates; check-in rhythm at days 60 and 90 |
| Now · prerequisites (not bets) | Feature flags and experimentation analytics (buy); wellbeing score baseline recorded at day 90 for every cohort; counsel and clinical advisory review of any flow that touches distress | _to assign_ | In place before Now bets launch |
| Next (3 to 6 mo) | **Lifecycle state engine** (acute, recovering, steady, re-entering). Needs Now Bets 1 + 2: states can only be defined once playbook and signal data exist. | _to assign_ | Unlocked by Now evidence |
| Next (3 to 6 mo) | **Graduation rhythm and humane re-entry.** Needs the state engine: we must know when someone is graduating or slipping, or it will feel like a retention trick. | _to assign_ | Unlocked by state engine |
| Next (3 to 6 mo) | **Lifecycle messaging and orchestration (buy).** Needs defined moments: buying earlier just automates generic nudges. | _to assign_ | Unlocked by defined moments |
| Next (3 to 6 mo) | **Second-path re-entry.** Needs Now Bet 3: only worth doing once first-path completion data shows the path format works. | _to assign_ | Second-path re-entry rate per cohort |
| Next (3 to 6 mo) | **Personal trigger awareness** ("your early warning signs"). Needs enough history and counsel sign-off; must stay on the wellness side of the clinical line. | _to assign_ | Unlocked by history + counsel sign-off |
| Later (6 to 12 mo) | **Bets, not commitments:** playbook engine that predicts what each user needs next; research partnership publishing outcomes (needs 180-day cohort data from KR2); new content production only where gaps show up in the paths; research-updated techniques feed reviewed by clinical advisors; wearables beyond Apple Health and Health Connect | _to assign_ | Right direction, not yet resourceable |

> **Hard no · holds on every horizon:** No community or social layer. Requests for "peer stories" get the same no. Safety exposure and user trust come first.

Full visual roadmap: [roadmap.html](roadmap.html)

## 2. Trade-off memo

_What did you sequence first, what did you push out, and what did you cut entirely, and why? Use WSJF / cost of delay reasoning where it helps._

> I chose to sequence **the three Now bets (playbook captured at relief, passive signals on both platforms, maintenance paths from existing content)** first because each one keeps the need behind an original Rock but aims it at the part only Fable can own: the user's own history. We already win the crisis moment, and a content library is what incumbents do well, so the Rocks were reframed from features into bets:
>
> - Crisis mode flow → Playbook captured at relief
> - Apple Watch integration → Passive signals on both platforms
> - Content library → Maintenance paths from existing content
>
> I pushed out **the lifecycle state engine, graduation and re-entry, lifecycle messaging, second-path re-entry and personal trigger awareness** because each depends on evidence the Now bets have to produce first. States can't be defined without playbook and signal data, messaging bought before we know the moments just automates generic nudges, and trigger awareness needs enough history plus counsel sign-off to stay on the wellness side of the clinical line.
>
> I cut **a community or social layer** entirely because it would surface crisis disclosures in semi-public settings, pulling us toward clinical positioning, and would change the private relationship users trusted us with. I also cut **a premium tier with therapist-matching**, because it isn't clear it would help retain users, and **"Fable for Teams"**, because the effort would pull us away from fixing retention for the users we already have.

### Management system: three things to fix

- **Say what "10%" means.** KR1 and KR3 need a baseline and should say whether it's relative or percentage points.
- **Track the wellbeing score monthly.** KR2 depends on it, but it isn't in the review.
- **Add leading indicators.** Review playbook entries saved and check-in rhythm monthly so we can change course within the quarter.

## Link to full artifact

[02-roadmap/roadmap.html](roadmap.html)
