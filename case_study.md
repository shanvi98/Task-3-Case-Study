# Where to start with AI at Client B: measure the steel first

**From:** Shanvi (Forward Deployed Engineer) · **For:** Cost Control and management · **Stage:** Proposal after our first two calls

Throughout, I try to be clear about what you told me, what I'm assuming, and what I don't know yet. I've used ₹90 to US$1 as a working exchange rate, and the steel and scrap prices are placeholders for you to replace.

---

## 1. What I understood

### What you asked for, and what you need

You asked where AI could help, and picked nesting first. But the problem you described is really about measurement: *"we don't have the data to say how much steel is wasted, how much of that we could have prevented, or which material is sitting unused."*

So before anyone can say whether software would save you steel, you need two things:

1. **A trusted figure for where your steel goes.**
2. **A fair test of whether hand nesting really beats the automatic nesting you already own in Strumis.**

Three points shape this:

- **You already have an auto-nester.** Your nesting team finds it wastes more. They may be right, but nobody has measured it.
- **Not all "waste" is a nesting problem.** Bolt holes, steel lost in cutting, parts recut after drawing changes, and offcuts on the rack usually all count. Better nesting can only reduce part of that.
- **Sharing steel between projects is an accounting question first.** Steel is charged to the project that buys it, so if project B uses project A's offcut, B gets it free and nobody has a reason to look. Certificate rules may also apply. I don't know yet.

### What the numbers can and can't tell us

You gave me 20–25% waste on plate, 5–10% on profiles and 7–10% overall. I haven't seen how these are calculated, so I treat them with care:

- **They only fit together if profile waste is low (about 5–7%).** Then plate is roughly 10–33% of your steel. In the middle case it's about a fifth of your steel but half your waste (Appendix A).
- **"20 to 25%" may be one figure measured two ways.** 20% of steel bought is exactly 25% of steel shipped.
- **80,000 tonnes is your capacity, and many projects are on hold.** So I assume 60,000 tonnes a year for money estimates.
- **Low trailer use and still hiring trailers can both be true.** Dispatch peaks, unused bookings, or too few trucks or drivers would explain it. It doesn't prove you have too many trailers.

### How work flows today

**Bid → estimating** (prices the job; I assume it sets the waste allowance) **→ planning → purchasing** (buys steel per project and charges it there) **→ engineering** (drawings; revisions keep coming, with no clear record) **→ store yard** (no set storage order) **→ nesting** (by hand in Strumis, one project at a time, offcuts checked first) **→ sizing** (CNC cutting) **→ fabrication → coating → dispatch** (about 13 own trailers, plus hires).

The gap sits right where waste happens. The nesting plan is recorded. What actually became scrap, which offcuts were reused, and why parts were recut probably aren't. Full table in Appendix B.

### Who's involved

- **You (Cost Control)** are championing this but don't hold the budget. You need a small, clear first step you can stand behind this week.
- **Management and finance** decide and pay. They'll want a limited commitment and results in money.
- **The nesting team** owns the process, and their support will make or break this. They need to know we're measuring, not replacing, and that they sign off on results.
- **Engineering** will engage if revision tracking is about recovering client claims, not blame.
- **IT** needs to know we only read data.

Only you, and briefly your colleague, were on the calls. So everything I know about nesting is second-hand (full map in Appendix C).

---

## 2. What I don't know yet

| # | Question for our next call | Why it matters | If the answer isn't what we hope | My assumption until then |
|---|---|---|---|---|
| 1 | Does Strumis keep past nesting jobs, and can IT export them for us to read? | Decides whether the study runs as planned | Rebuild profile jobs from part lists, record plates as they happen, or start with trailers | Yes, to be checked |
| 2 | How are the waste figures worked out? What did you buy and ship last year? What do steel and scrap cost? | Every money estimate depends on it | We resize the estimates, maybe stop early | Waste = (bought − used in parts) ÷ bought; 60,000 t; ₹81,000/t steel; ₹27,000/t scrap |
| 3 | Will your nesting lead join a side-by-side test, with the right to reject results? | Without them, nobody trusts the outcome | Test profiles only, or pause | Yes, if it's clearly measurement |
| 4 | Roughly what did you spend on hired trailers last year? | Decides whether trailers go first | Above ~₹7 crore a year, I'd start there | Below that |
| 5 | Can steel move between projects, and who decides? | Decides whether sharing steel can be built | Limit to uncertified stock, or drop | Not today; finance to decide |

---

## 3. Options, and what we recommend

You asked for advice first and a build after, and for help on where to start and where else to look. I scored ten options from 1 to 5 on value, data available, speed to a result, likely adoption, effort, and how easily the return could be proved (Appendix D).

| Option | Score | My view |
|---|---|---|
| Trailer hire review | 3.90 | **Close second.** Data exists; value depends on your hire bill |
| **Steel waste study** | 3.65 | **Recommended** |
| Advice only | 3.40 | Leaves you without data, the problem you raised |
| Offcut sharing, revision tracking, fleet system | 2.25–3.00 | Later, once conditions are met |
| Yard or trailer loading plans | 1.95 | No data to work from yet |
| **AI to run nesting** | 1.90 | **Last in every version of the scoring.** Nothing to measure it against |

**To be straight with you: the trailer review scored highest**, because CarTrack and your booking system already hold the data. In money terms, though, a year's steel is likely worth far more than your hire bill. A fix saving 20–40% of hire costs would only beat the steel opportunity if the bill were above roughly ₹7–14 crore a year. So: **steel first, unless your hire bill is above about ₹7 crore a year.**

### My recommendation: a six-week steel waste study

1. **Where the steel went.** For 8–12 finished projects, we trace every tonne bought into parts, offcuts kept, offcuts reused, recuts, and what's left (scrap and cutting loss). Scrap is usually sold in bulk, so we also check the factory total against scrap actually sold.
2. **Hand vs automatic nesting.** We redo about 30 past profile jobs and 30 plate jobs three ways, with the same parts and steel: as your team did it; with Strumis's auto-nest set up to your team's rules; and with a specialist optimiser that shows the best realistic result. (I still need to confirm Strumis covers both plates and profiles.)
3. **Steel that could have gone elsewhere.** How much offcut and on-hold stock matched other projects' needs. Measured only; nothing moves.
4. **A readout.** Avoidable waste in money, a clear hand-vs-auto answer, the cost-sharing question for finance, and next steps.

**Why this fits:** it answers your three questions, settles the hand-vs-auto debate without changing anyone's work, sits with Cost Control, and builds the base for everything after. It doesn't wait for on-hold projects either.

**What I'd leave out:** no AI (there's no history to learn from, nesting is a well-solved maths problem, and every number must be checkable); no new nesting system; nothing written back into Strumis; no automatic steel sharing; no yard, loading, revision or fleet tools yet; and no advice to buy software until I know whether your current licence is fully used.

**Keeping the test fair.** I don't take sides. Your nesting lead writes down the rules a good nest must follow (margins, grain direction, part priority, machine limits, smallest offcut worth keeping) before seeing results. We tune the auto settings on five separate jobs, then lock them. Both methods get the same steel. Where practical, your lead reviews pairs without knowing which is automatic. Their team's nests were actually cut, so rejecting one would flag an inconsistent review. A rejected auto nest earns auto no credit.

**Sharing steel across projects.** We size the opportunity; finance decides the rule. One starting point: the receiving project pays the original price for the weight it uses, and offcuts get an agreed rate. Quality confirms certificate rules. A tool comes later, if it's worth it.

**Where I'd push back:** measure before automating; agree the costing rule before building anything for sharing; one area at a time, not five; don't read low trailer use as "too many trailers"; and start revision tracking with claimable client changes, not engineering errors.

### Where else, and what to fix without software

| Next | Start when |
|---|---|
| Trailer hire review | After the readout, or **first** if hire costs exceed ~₹7 crore a year |
| Sharing offcuts and idle stock | Finance agrees a costing rule and the study shows it's worth it |
| Tagging why each revision happened | The study shows recuts are a real share of waste |
| Yard and loading plans | On-hold projects settle and there's location or load data |

**Easy wins to start now:** weigh scrap bins monthly; record where each offcut is stored; mark each revision as client or internal; check for trailers booked but not used.

---

## 4. How it works

**Data and who holds it:**
- Steel bought per project: Cost Control and purchasing.
- Part lists and revisions: engineering.
- Past nests: the nesting team, exported by IT. I need to confirm what Strumis keeps.
- Offcut register: nesting and the yard.
- Scrap sales: finance. I assume scrap is weighed.
- Client revision claims: commercial. I think these exist because you can claim them back.
- Current stock: the store.
- A one-page rules sheet from your nesting lead.

**Checking it.** We recalculate steel weights from dimensions (flagging anything over 3% out), check every nested part is on a released drawing, and spot-check 20 offcuts in the yard. Anything that doesn't add up is shown as "unexplained", not hidden in other numbers.

**Methods, and why:**

| Part | How | Why |
|---|---|---|
| Where the steel went | A plain tally | Nothing to predict; Cost Control can check every line |
| Profiles | An exact cutting-length optimiser (free, open-source) | A solved problem; answers in seconds |
| Plates | Strumis auto-nest with your rules; a specialist tool only to show the best case | Tests the real choice with software you own |
| Steel for other projects | Matching on grade, size and section | Easy to explain; sizes the opportunity |

**How we score a nest.** We use "yield": the share of steel that ends up in real parts. Usable offcuts get partial credit, based on how often your offcuts actually get reused (50% if we can't tell). We also show no credit and full credit, so leaving big offcuts that never get used can't flatter a nest.

**Sign-off.** Your nesting lead approves the rules (week 1) and every test pair (weeks 3–5). Cost Control and finance agree what counts as waste (week 2). You and we decide whether to continue (week 3). Management decides next steps (week 6).

**When the nesting lead says no,** we log why: a missed rule, cutting order, part handling, a machine limit, or an unusable offcut. Repeat reasons become auto settings, or documented reasons to keep nesting by hand.

**Fitting your routine.** Strumis stays your main system, and we only read from it. Daily nesting doesn't change. Your nesting lead gives a day at the start and about four hours a week in weeks 3–5. You end up with a spreadsheet Cost Control owns and updates monthly.

**If something goes wrong.** If there are no past nests, we rebuild profile jobs from part lists and record plates as they happen. If the tally doesn't add up, the gap is the finding. If the nesting lead can't join, we test profiles only. The nesting test doesn't depend on the tally, so one data problem won't sink both.

---

## 5. How we'll know it worked

**Starting point.** With no waste data, and project mix changing too much, a before-and-after comparison wouldn't be fair. Instead the tally of finished projects shows today's picture, and each nest as your team actually made it is the baseline the alternatives are compared against, on identical inputs.

**What we measure.**
- For each job, the yield difference between auto and hand, in percentage points.
- How far the best possible result is from your team's.
- The share of auto nests your lead accepts as cuttable.

**How many.** At least 30 profile and 30 plate jobs, from five or more projects and three or more thicknesses or section types, picked at random. We report the typical (median) result with a range showing how sure we are.

**Honest limits.** Thirty plate jobs can't pick up differences much below 2 points, and past jobs don't capture live pressure like urgent drawings. So a pass leads to a supervised live trial, not an instant switch.

**The bar.** Each threshold is worth about ₹1.3 crore a year (₹1,29,60,000) at my assumptions. One point of plate yield is 60,000 t × 20% × 1% = 120 t × ₹54,000 = ₹64,80,000, so the plate bar is 2 points. One point on profiles is 480 t × ₹54,000 = ₹2,59,20,000, so that bar is half a point.

| Result | Plates | Profiles | Next step |
|---|---|---|---|
| **Auto better** | +2 points or more, range above zero, 80%+ accepted | +0.5 or more, range above zero, 90%+ accepted | Supervised live trial: auto first, nester reviews |
| **No real difference** | Within ±1 point | Within ±0.25 | Neither claim holds; decide on nesting time |
| **Hand better** | −2 or worse | −0.5 or worse | Document the team's method; drop auto nesting |
| **In between** | | | Test 30 more once; if still unclear, call it no difference |

All three conditions are needed for a pass. A good average with too many rejections counts as "in between".

**When we'd stop.**
- **Week 3:** we continue only if at least one material has 30 usable test jobs. If neither does, we stop. You keep the tally, a list of what to start recording, and the roadmap, and pay only the first half. If just one qualifies, the second half covers that one at a lower agreed price.
- **After testing:** if even the best possible result beats your team by under 1 point on plates and 0.25 on profiles, better nesting can't justify new software, and we'll say "don't buy a nesting package" in writing. Without a specialist plate tool, we'd only claim Strumis's auto-nest doesn't help, not that nothing could.
- **Plates:** if your lead rejects over half the auto plate nests for reasons settings can't fix, we stop plate testing.

**Who checks.** We do the maths. You re-check five random jobs from the raw data. Your nesting lead confirms each nest can be cut. Disagreements are reported as they are.

---

## 6. Plan and timeline

Weeks count from sign-off.

| Week | What happens | What you see | What we need from you |
|---|---|---|---|
| This week | This summary to management; next call | Your office update | Who approves |
| 1 | On site: nesting, cutting, yard; rules sheet; data; agree "waste" | Rules signed | **IT data export (sets the pace)**; a day of the nesting lead; purchase and scrap figures |
| 2 | Tally for the first 3–5 projects | **First result: where the steel went** | Review the waste definition |
| 3 | Tally to 8–12 projects; set up tests | **Continue or stop** | A day from your Strumis admin |
| 4 | Profile tests; steel-for-other-projects check | Profile results | ~4 hours of the nesting lead |
| 5 | Plate tests | Plate results | ~4 hours of the nesting lead |
| 6 | Readout | Decisions, next steps, trailer review scope | Time with management |

**On-hold projects won't slow this down**: we use finished projects, and on-hold stock is part of what we measure. The first half is kept small (₹18,00,000) so it can go ahead even if budgets are tight. If the data arrives late, everything shifts by the same amount, and the first invoice waits.

---

## 7. Cost

| Who | First half (days) | Second half (days) | Total | Day rate | Value |
|---|---|---|---|---|---|
| Forward Deployed Engineer (on site) | 12 | 13 | 25 | ₹1,08,000 | ₹27,00,000 |
| Data and optimisation engineer | 5 | 10 | 15 | ₹90,000 | ₹13,50,000 |
| Engagement lead | 1.5 | 2.5 | 4 | ₹1,44,000 | ₹5,76,000 |
| **Total** | 18.5 | 25.5 | **44** | | **₹46,26,000** |

**Price.**
- **First half (weeks 1–3): ₹18,00,000 fixed.** Half when your data arrives, half at week 3.
- **Second half: ₹27,00,000 fixed, only if you continue.** Half at week 4, half at the readout.
- **Total ₹45,00,000**, plus travel at cost (capped at ₹2,70,000).
- **The most you risk before seeing whether it works is ₹18,00,000.**

**Running costs** are close to zero: your existing Strumis licence, a free optimiser, no cloud fees. Afterwards, the spreadsheet takes about a day a month to update.

**What it could be worth (steel only).** Tonnes a year × waste rate × share avoidable × value per tonne saved. Each tonne not wasted saves the steel price (₹81,000, placeholder) minus its scrap value (₹27,000, placeholder): **₹54,000 a tonne**.

| Case | Tonnes a year | Waste | Avoidable | Tonnes saved | **Value a year** |
|---|---|---|---|---|---|
| Cautious | 50,000 | 7% | 5% | 175 | **₹94,50,000** (about ₹95 lakh) |
| Middle | 60,000 | 8.5% | 10% | 510 | **₹2,75,40,000** (about ₹2.75 crore) |
| Optimistic | 80,000 | 10% | 20% | 1,600 | **₹8,64,00,000** (about ₹8.6 crore) |

I've kept the avoidable share low on purpose, because most headline waste isn't a nesting problem. The study replaces this guess with a real figure. Each ₹9,000 change in value per tonne moves the middle case by about ₹46 lakh (₹45,90,000). **The study pays for itself if it leads to saving 84 tonnes a year** (0.14% of 60,000 t).

Savings come from acting on the results, not from the study itself. With a follow-on phase of roughly ₹54–81 lakh (₹54,00,000–₹81,00,000; my estimate, not a quote), payback is about 4–6 months in the middle case and 13–16 months in the cautious case. Time saved by the nesting team isn't counted, because I don't know its size. Even a "no" has value: it stops you buying software that wouldn't pay back.

---

## 8. Risks

| What could go wrong | Likelihood | Impact | Early sign | Our response |
|---|---|---|---|---|
| **Records don't show where the steel went** | High | Medium | Factory scrap total off by 10%+ in week 2 | Nesting test unaffected; gap becomes a recording fix |
| Strumis lacks past nests, or the export is slow | Medium | High | No sample by day 5 | Ask on next call; profile fallback; invoice waits |
| Nesting team steps back or disputes results | Medium | High | Rules not signed in week 1 | Rules before results; right to reject; profiles first |
| Auto nests ignore real workshop limits | Medium | Medium | Many early rejections | Rejection log; stop plate testing |
| Savings turn out small | Medium | Medium | Measured waste well under 7% | A valid answer; move to the next priority |
| No management decision at week 6 | Medium | High | No manager booked for the readout | Confirm who approves now |
| Finance never sets the sharing rule | Medium | Medium | Finance not involved by week 4 | Raise it in week 4, with numbers |

**The most likely problem** is that records don't show where all the steel went, so a big share comes out "unexplained". I've planned for it: the hand-vs-auto test still gives an answer, and the gap becomes a short list of what to start recording.

---

## Appendix A. How much weight I give each claim

From strongest to weakest: **A** = data I've seen myself (none yet) · **B** = first-hand from the person doing the work · **C** = you, passing on data you handle · **D** = a figure passed on without a definition · **E** = passed on and untested, from the team whose own method it concerns.

| Claim | Grade | Why |
|---|---|---|
| Plate waste 20–25%, profiles 5–10% | D | From "manual data" I haven't seen; how it's calculated is unknown |
| Overall about 7–10% | D− | "You can take…" sounds like an estimating allowance |
| Hand nesting beats auto | E | The nesting team's view, passed on by you; it may well be true, and the test checks it fairly |
| Offcuts are underused | E/D | A view from outside the team, though the offcut check itself is real |
| Revisions are frequent | D | No record, yet client revisions are claimable, so some record must exist |
| Trailer use is very low | C | You produce these reports; "use" isn't defined |
| 80,000 t a year | C | Described as capacity; 80,000 ÷ 12 = 6,667 t a month, not the 7,000–8,000 mentioned |
| Steel charged per project when bought | B/C | Your own area |

**Making the waste figures fit.** Overall waste = plate share × plate waste + profile share × profile waste. So plate share = (overall − profile) ÷ (plate − profile).

- With profiles at 5%, an overall 7% and plate 25% gives a plate share of 10%.
- An overall 10% and plate 20% gives 33%.
- The middle case (8.5% overall, 22.5% plate) gives 3.5 ÷ 17.5 = 20%. There, plate makes up 4.5 of the 8.5 waste points.
- If profiles were really at 10%, an overall figure below 10% would be impossible.

## Appendix B. How work flows today, step by step

| Step | Who | What they decide | What gets recorded | What's probably missing | Told or inferred |
|---|---|---|---|---|---|
| Bid | Business development | Price; whether to bid | The bid | How it compares to the outcome | Both |
| Estimating | Estimators | Material rates; waste allowance | Estimated tonnes | Estimate vs actual waste | Both |
| Planning | Planning | When to buy and build | Schedule | Why projects go on hold | Told |
| Purchasing | Purchasing | What and when to buy, **per project** | Orders; **cost charged to project** | Why these sizes; certificate links | Told |
| Engineering | Engineering | Drawings and revisions | Drawings, part lists | **Why each revision happened, and its cost** | Told |
| Store yard | Yard | Where to stack (no set order) | Delivery receipt | Where things are | Both |
| Nesting | Nesting team, by hand in Strumis | Which parts go on which plate or bar; offcut use | Nests (to confirm) | Actual yield; reasons | Both |
| Sizing | Factory, CNC | Cutting order | Cut parts | Recuts; actual scrap | Both |
| Offcuts | Nesting / yard | Keep or scrap (about "half a sheet") | Offcut register | Location, age, how often reused | Both |
| Fabrication and coating | Factory | Order; coating per client | Hours | Rework | Told |
| Dispatch | Dispatch; ~13 trailers plus hires | Which trailer; when to hire | Booking system, CarTrack | Load plans; why each hire | Told |
| Cost control | You | Claim back or absorb | Reports, claims | **Losses from internal errors** | Told |

## Appendix C. Who's involved

| Who | On the calls? | What they care about | Likely worry | What earns their trust |
|---|---|---|---|---|
| Cost Control (you) | Yes | A credible update; numbers you can defend | "Is this really AI?" | A baseline built from your own data |
| Your colleague | Briefly | Yard, trailers, factory | "Our areas are being ignored" | A roadmap with reasons |
| Nesting team | No | Meeting budget; their expertise | "Auto wastes more" | A fair test they help set up |
| Engineering | No | Drawings out on time | Being blamed | Claims recovered |
| Yard / store | No | Less digging | More data entry | Keeping entry minimal |
| Purchasing / planning | No | Price; schedule | Pooled buying gets messy | Nothing changes until a rule is agreed |
| Factory / sizing | No | Throughput | Auto nests harder to cut | Their limits written into the rules |
| Logistics / fleet | No | On-time delivery | "Low use" sounding like blame | Diagnosis before judgement |
| IT / Strumis admins | No | Stability; security | Access requests | A narrow, read-only request |
| Management / finance | No | Margin; hire costs | "Where's the money?" | A small first step; your own numbers |
| The other supplier | n/a | Selling software packages | n/a | Not an audience for this |

## Appendix D. Scoring

Each option is scored 1–5, where 5 is best. Weights: value 25%, data 20%, speed 15%, adoption 15%, effort 10%, provable return 15%.

| Option | Value | Data | Speed | Adoption | Effort | Return | Score |
|---|---|---|---|---|---|---|---|
| Trailer hire review | 3 | 4 | 5 | 4 | 4 | 4 | 3.90 |
| Steel waste study | 4 | 3 | 4 | 3 | 4 | 4 | 3.65 |
| Advice only | 1 | 5 | 5 | 5 | 5 | 1 | 3.40 |
| Profile cutting optimisation | 3 | 3 | 4 | 3 | 4 | 4 | 3.40 |
| Fleet system | 3 | 3 | 3 | 3 | 3 | 3 | 3.00 |
| Offcut sharing tool | 3 | 2 | 3 | 3 | 3 | 3 | 2.80 |
| Revision tracking | 3 | 2 | 2 | 2 | 2 | 2 | 2.25 |
| Yard / loading plans | 2 | 1 | 2 | 3 | 2 | 2 | 1.95 |
| AI to run nesting | 4 | 1 | 1 | 1 | 1 | 2 | 1.90 |

**Changing the weights:**

| If I… | Top option |
|---|---|
| Use the weights above | Trailer hire review (3.90) |
| Weight value much more heavily (40/15/10/15/5/15) | A tie: trailers and the steel study at 3.70 each |
| Score value in money (steel study 5, trailers 2) | Steel study (3.90) over trailers (3.65) |
| Mostly avoid risk (15/25/25/20/10/5) | Advice only (4.20) |

## Appendix E. A possible prototype (suggested, not built)

**What it is:** a small worked example on made-up profile data. It compares a hand-style cutting plan with an optimal one, under four different ways of defining waste.

**What it would show:** that the scoring method works with data Strumis very likely already holds, and that the headline waste percentage swings a lot depending on how waste is defined.

**What it wouldn't show:** anything about your real yields, or about plates.
