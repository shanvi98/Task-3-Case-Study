# Submission form: Task 3, Client B (structural steel)

## 1. Two sentences: the real problem vs what they asked for

They asked where AI could help, starting with nesting, but the problem they described is that they can't measure how much steel they waste, how much was avoidable, or what sits idle, and can't tell whether hand nesting really beats the auto-nester they already own. The real need is a trusted measurement and a fair same-input test of the software they have, plus a cost-policy decision on reusing material across projects, before any nesting "AI" can be judged.

## 2. Who is in this deal and what does each need to hear?

- **Cost Control contact** (champion; on both calls; not the budget holder): a small, dated first step with defensible numbers for their office update this week.
- **Management / finance** (economic buyer and decision-maker; not on calls): a limited first commitment (₹18 lakh), results in their money, payback, and a swap to fleet hire if that bill is larger.
- **Nesting team** (process owner, end user, likely blocker; not on calls): we measure before changing anything; they write the rules before seeing results, review every nest, and a veto counts against auto.
- **Engineering** (supplies drawings and revisions; not on calls): revision data starts with claimable client changes, not with counting their errors.
- **IT / Strumis admins** (control data access): read-only exports, nothing written into Strumis.
- **Yard, purchasing, planning, factory** (data and inputs): nothing in their routine changes during the pilot.
- **Logistics / fleet:** "low utilisation" will be diagnosed, not assumed to mean too many trailers.
- **Competing supplier** (sells packages): not an audience. Our position is to test whether the existing licence is underused before anyone buys.

Every process owner and the budget holder were missing from both calls.

## 3. Five ranked questions, why they matter, and what I assume while waiting

1. **What does Strumis store about past nests, and can IT export it read-only?** Decides feasibility. *Assume:* nests are stored with stock, parts and yield, and can be exported (to verify).
2. **What's behind the 20–25 / 5–10 / 7–10% figures (definition, base, period)? Actual tonnes bought and shipped by type? Steel and scrap prices?** Every value number depends on it. *Assume:* (bought − net drawn) ÷ bought, including offcuts and recuts; 60,000 t throughput (80,000 is capacity); ₹81,000/t steel, ₹27,000/t scrap (at ₹90 = US$1).
3. **Will the nesting lead agree to a same-input side-by-side with veto rights?** Without them nobody will accept the result. *Assume:* yes, if framed as measurement.
4. **What's the annual trailer hire spend?** Decides whether fleet diagnosis should go first (above ~₹7 crore/yr it should). *Assume:* below that.
5. **Can material move between projects (costing rule, certificate restrictions), and who decides?** Decides whether remnant matching can ever be built. *Assume:* not today; needs Finance and Quality.

## 4. Options considered, why this one, what was ruled out and why

**Considered (ten):** the client's five areas, plus a production nesting optimiser, a yield baseline with nesting benchmark, remnant/idle-stock matching, profile cut optimisation, fleet hire diagnosis, and do-nothing/roadmap. Each was scored on value, data readiness, time to first result, adoption risk, effort and provable ROI, with four weighting scenarios.

**Chosen:** a 6-week, read-only **Material Yield Baseline and Nesting Benchmark**:
- a waste ledger for completed projects;
- about 30 profile and 30 plate nests re-run with Strumis auto and a reference optimiser on the same inputs;
- an idle-stock match, measured only.

The client explicitly asked for consultation first, then development, so a diagnostic with a build path fits the ask.

It answers their three questions directly, settles the manual-vs-auto dispute, sits with the sponsor's own function, targets the probable largest money lever, and is the foundation for everything after it.

**Honest caveat:** fleet hire diagnosis scored highest on base weights because its data already exists. It only drops behind once value is measured in money. I'd swap it to first if hire spend is above about ₹7 crore a year.

**Ruled out:**
- **AI in production nesting:** last in every scenario. No baseline, and the process owner wasn't consulted.
- **Cross-project auto-allocation:** blocked by cost loading and possibly certificates; we measure it instead.
- **Yard and trailer load plan:** no location or load data; the yard is unstable while projects are on hold.
- **Revision tracking:** deferred; politically sensitive for engineering.
- **Machine learning anywhere:** no labelled history; these are well-defined optimisation and accounting problems.

## 5. How the client knows the pilot worked

- **Baseline:** (a) a ledger of completed projects, balanced per project and factory-wide against scrap sold (scrap is likely pooled, not per project); (b) the manual nest as executed, compared with alternatives on the *same* parts and stock. No before/after over time, because project mix confounds it.
- **Metric:** yield Y = net part weight ÷ (stock consumed − c × usable offcut), where c is the historical offcut reuse rate (0.5 if unknown), also shown at c = 0 and 1. Paired ΔY = Y(auto) − Y(manual), plus acceptance rate and the reference-optimiser ceiling.
- **Threshold** (set at equal money, ≈ ₹1.3 crore/yr, i.e. ₹1,29,60,000):
  - **Pass:** plates median +2.0 pts, profiles +0.5 pts, 90% interval above 0, and acceptance ≥ 80% (plates) / ≥ 90% (profiles).
  - **No yield case:** within ±1.0 pts (plates) or ±0.25 pts (profiles).
  - **Manual wins:** −2.0 pts or worse (plates) or −0.5 pts or worse (profiles).
- **Runs:** at least 30 profile and 30 plate pairs, from at least 5 projects, sampled at random.
- **Protocol controls:** auto settings tuned on 5 separate nests, then frozen; both methods get the same stock; pairs reviewed blind (A/B) where practical, and a veto on a manual nest (which was actually cut) flags an inconsistent review. A pass needs all three conditions and leads to a supervised live trial, not a switch.
- **Who measures:** we compute; the contact independently recomputes 5 random pairs; the nesting lead signs off cuttability, and vetoes count as zero gain.
- **Stop conditions:**
  - Week 3: fewer than 30 benchmarkable pairs for both materials → stop, data-gap report, Phase 1 fee only. Only one material qualifies → Phase 2 on that material at a reduced price.
  - After the benchmark: the reference ceiling is below 1 pt (plates) and 0.25 pt (profiles) → stop the nesting track and advise against buying a nesting package. Without an independent plate engine, the plate conclusion is limited to "Strumis auto doesn't help".
  - Plates: over 50% of auto nests vetoed for constraints that can't be configured → stop the plate track.

## 6. Cost to client and to us, arithmetic, pricing, value

- **Effort:** all in rupees at ₹90 = US$1 (an adjustable assumption): FDE 25 days × ₹1,08,000 = ₹27,00,000; engineer 15 × ₹90,000 = ₹13,50,000; engagement lead 4 × ₹1,44,000 = ₹5,76,000. **Total 44 days = ₹46,26,000** at rates.
- **Price:** Phase 1 **₹18,00,000 fixed** (50% when the data export arrives, 50% at the week-3 gate). Phase 2 **₹27,00,000 fixed, only if go** (50% at week 4, 50% at readout). **Total ₹45,00,000** plus travel at cost (cap ₹2,70,000). The client's maximum exposure before the gate is ₹18,00,000.
- **Our cost:** about 55% of rates = ₹25,44,300, so margin is about ₹19,55,700 (43%).
- **Running cost:** about ₹0 in software (their Strumis licence, open-source solver); about 1 client analyst-day a month afterwards.
- **Value (material only):** tonnes × waste rate × avoidable fraction × net ₹/t, where net = ₹81,000 steel − ₹27,000 scrap = **₹54,000/t** (placeholders to adjust):

| Case | Calculation | Value/yr |
|---|---|---|
| Low | 50,000 × 7% × 5% = 175 t | **₹94,50,000** (≈ ₹95 lakh) |
| Base | 60,000 × 8.5% × 10% = 510 t | **₹2,75,40,000** (≈ ₹2.75 crore) |
| High | 80,000 × 10% × 20% = 1,600 t | **₹8,64,00,000** (≈ ₹8.6 crore) |

- **Sensitivity:** ±₹9,000/t moves the base case by ±₹45,90,000.
- **Break-even:** ₹45,00,000 ÷ ₹54,000 = 83.3, so 84 t/yr.
- **Labour savings:** kept separate and not counted (nesting team size unknown).
- **Realisation:** savings come only from a later phase that changes practice. The pilot buys a decision.

## 7. Timeline: first result, when, and client-dependent steps

- **This week:** the one-page note for the contact's office update, and the next call.
- **Week 1:** on-site walkthrough, nesting rules sheet, data exports.
- **End of week 2 (first visible result):** "where the steel went" for real completed projects.
- **Week 3:** go/stop gate.
- **Weeks 4–5:** profile and plate benchmark.
- **Week 6:** readout and decision pack.

**Depends on the client:**
- IT read-only export by end of week 1 (critical path; slips day for day, and the Phase 1 fee waits for it)
- Purchase and scrap data
- Nesting lead: about 1 day at kickoff, then about 4 hours a week in weeks 3–5
- Strumis admin: about 1 day
- A management slot in week 6

On-hold projects don't block it, because we work from completed projects and on-hold stock is an input.

## 8. Where did you push back, narrow, or say don't? (optional)

- **"AI for nesting":** measure first, using the auto-nester they already own. No ML; this is optimisation and accounting.
- **"Automatically reuse material across projects":** this is a cost-transfer and certificate policy for Finance and Quality first. We size the prize; we don't build the tool.
- **Five areas at once:** one engagement done properly, plus a roadmap with explicit triggers.
- **"Utilisation is very low but we hire trailers":** that doesn't prove there's too much fleet. Peaks, block bookings, or trucks and drivers could explain it. Diagnose before acting.
- **"Count our own engineering errors":** start with claimable client revisions so engineering cooperates.
- **The 20–25% headline:** we won't promise savings from it. Our base case assumes only 10% of total waste is avoidable.
- **The brief itself:** the brief says they "handle" 80,000 t; the notes say capacity. We use 60,000 t as base.

## 9. What is most likely to go wrong, and what in the notes didn't you trust? (optional)

**Most likely to go wrong:** the records don't show where the steel went (offcut and scrap weights not captured), so the ledger has a large "unexplained" share. The benchmark is designed not to depend on the ledger, so the manual-vs-auto question still gets answered, and the gap becomes a concrete recording fix. The next risk is that Strumis doesn't hold historical nests; that's question 1 on the next call.

**Didn't trust:**
- **Waste percentages.** Relayed "manual data" with no definition, from a contact who also says they have no waste data.
- **The figures don't fully agree.** They only reconcile if profile waste is ~5–7%. "20–25%" may be one number on two bases (20% of input = 25% of output).
- **"Manual beats auto."** Self-interested, untested, and doubted by the person relaying it. It could still be true, so we test it rather than dismiss it.
- **"Offcuts underused."** An outside opinion.
- **"Utilisation very low."** It contradicts the forced hiring, and there's no definition.
- **80,000 t.** That's capacity, and 80,000 ÷ 12 = 6,667 t/month, not the 7–8k quoted.
- **Revisions "not recorded".** Yet client revisions are claimable, so some record must exist.

## 10. What did you use AI for?

I used one AI tool, Claude (Sonnet 5.5), for most of the drafting. I wrote the instructions it worked from (a prompt that told it to analyse and comprehend, label every claim as fact, assumption or unknown, and work in stages), and I pasted the brief and the discovery notes into that session. The notes stayed in my private session and were not posted anywhere public.

**What the AI did:**
- Graded how reliable each client claim was, reconciled the waste percentages (the plate/profile mix), and mapped the process and stakeholders.
- Listed and scored ten options, tested the scoring under different weights, and drafted the recommendation, evaluation design, plan, cost and risks.
- Drafted the case study, the note to the client, and these form answers.
- Re-ran every calculation with a script (value ranges, thresholds, scores, effort, payback) and checked page counts by rendering the documents.
- Audited its own work against the brief.

**What was wrong or thrown away:**
- The audit found problems in the AI's first drafts, which were fixed: the client-facing case study showed our internal margin and called the nesting team a "blocker"; the week-3 go/stop rule needed 15 nests while the test needs 30 pairs; the payment terms contradicted each other; and the waste ledger assumed scrap is tracked per project, when it is probably sold in bulk.
- The AI's own scoring put trailer hire ahead of the steel study on the base weights. I kept that result in the document and added a rule for when to switch, instead of changing the scores to fit the recommendation.

**What I did not take from the AI on trust:** the exchange rate (₹90 to US$1), the day rates, the steel and scrap prices, the 60,000 t throughput and the follow-on phase estimate are placeholders the AI proposed, not client data or my firm's real figures. Nothing about Strumis's capabilities is verified; it is marked "to check" throughout. The optional prototype was proposed but not built.
