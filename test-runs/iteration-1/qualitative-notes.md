# Statecraft skill, iteration 1: qualitative notes

These notes read each case the way a demanding think-tank editor would. The question is which answer a real leadership team would rather have on its desk, and what the skill adds and what it costs. All grading is from the output files only; there were no transcripts. For with-skill runs, "the answer" means the reply plus the dossier.

| Case | With skill: pass, words, time | Without skill: pass, words, time |
|---|---|---|
| US wealth gap | 6/6, 13,271 words (reply 2,401 + dossier 10,870), 1,451s, 271k tokens | 5/6, 4,864 words, 598s, 140k tokens |
| Singapore AI strategy | 6/6, 11,244 words (1,845 + 9,399), 1,223s, 250k tokens | 5/6, 4,813 words, 560s, 152k tokens |
| US defense industrial base | 6/6, 9,376 words (2,011 + 7,365), 1,043s, 214k tokens | 6/6, 3,370 words, 490s, 146k tokens |

## The headline

The skill wins on the scoreboard, 18/18 against 16/18. That margin is real but narrow, and it overstates the skill's value, because the assertions mostly check for things the skill's template forces: a named seat, a split problem, routes, opponents, phases, tripwires, a pre-mortem. The two failures in the baseline are both missing template parts: no pre-mortem or case-against (wealth gap), and no early-warning signals (Singapore).

On substance, the more striking finding is how strong the baseline already is. In all three cases the two arms reach essentially the same core strategy:

- **Wealth gap:** build on the existing Trump Accounts and Saver's Match, add progressive deposits, and fund them by making the top "play by the same rules".
- **Singapore:** become the verifiable compute jurisdiction, lead on adoption, hold memory and packaging, set a joint standard with Johor, and decide on nuclear by 2029.
- **Defense:** credible demand rather than money, multi-year frameworks with termination protection, the Senate's 19-munition list, drop the foreign-warship fight, defer the battleship.

So the skill does not change *what* the model recommends. It changes how the answer is packaged and grounded, and how long it is. The packaging gains are real: owner tables, dashboards, decision lists, and in one case much better political grounding. They come at about 2.3–2.8x the reading load, 2.1–2.4x the wall time and 1.5–1.9x the tokens. They also bring a set of template habits that a sharp principal would find wearing.

## Case 1: the US wealth gap

**For a real White House team, the with-skill answer is the more useful one, and the reason is grounding.** It finds the actual seat before it designs anything:

- a lame-duck President with 26 months left;
- 32% approval;
- going by AP's count, Democratic majorities in both chambers from January;
- the filibuster intact.

From that it draws the decisive conclusion: "Anything that passes in 2027–28 passes as a bipartisan deal, it has to be paid for, and it has to be something the President actually wants." Everything follows from there. The vehicle is the President's own branded program. The pay-for comes from positions he floated in 2025. The progressive top-up gets a Democratic name. The plan is something a chief of staff could take into a room.

The baseline writes for "a president of either party" with "thin margins", calls its first phase "the first 100 days" as if a term were starting, and makes year-one budget reconciliation its main vehicle. In the real configuration, that would mean a Republican President signing a Democratic reconciliation bill that taxes inherited gains. It never checks who holds power. That is the gap the skill's "fix the seat and the clock" instruction exists to close, and it closes it.

The with-skill answer also contains the single best insight in either version. The official wealth data leave out Social Security, which is the bottom half's largest asset (Catherine et al.: the top-1% share rises 7.6 points without it, 1.5 points with it). So the 2032 trust-fund cliff, now confirmed by the 2026 Trustees report, is "the biggest scheduled widening of the wealth gap in the next decade". That reframing is non-obvious, true and decision-relevant. The floor-versus-ceiling question at the end is also a genuinely useful values fork to hand the principal.

The baseline is not weak. Its prose is cleaner and its "two problems with one name" framing is crisper. Several of its ideas are ones the with-skill answer lacks:

- **A Canada-style trade:** keep the $15M estate exemption in exchange for ending step-up in basis, so each side can sell it to its own voters.
- **Highway money tied to housing permits:** use the expired surface-transportation authorisation to reward metro areas that build. This is a real federal lever on zoning, where the with-skill answer's housing plank is limp.
- **A dedicated trust fund:** route the top-end revenue into children's deposits by formula, which creates defenders of the revenue itself.

The baseline also handles evidence more honestly. It calls Zewde's 15.8:1 → 1.4:1 result "a simulation, not a result anyone has seen".

**Factual and craft problems in the with-skill run:**

- **Units:** it compares $25–30k "in today's money" with a $4,000 seed-only balance that is nominal.
- **Sourcing:** the 25% fall in Black household wealth, a dashboard baseline, comes from theGrio rather than the Fed's SCF.
- **Dates:** Pew is said to have found something "in August", but the citation is dated October.
- **Odds:** it publishes probabilities to sub-1% precision ("a wealth tax about 0.1%"). A skeptical reader will treat this as theatre, which undercuts the honest judgments around it.

**Problems the skill appears to cause:**

- **Length.** 13,271 words for a question a principal would want answered in ten minutes of reading.
- **Duplication.** The reply is a 2,400-word compressed copy of the dossier. The four problems, the Toledo baby, the odds line and the Statecraft lesson all appear twice. Verbatim overlap is only about 15% of 8-word sequences, but the arguments and numbers overlap almost completely.
- **Forced sections.** "Markets and foreign reaction: Minimal" exists only because the template has a wargame slot for markets. Singapore's CPF, Mexico's Progresa and Bismarck appear because they sit in the skill's case library, not because a US wealth memo needs them.
- **Framework vocabulary in client-facing prose.** "the 'change space' that Andrews, Pritchett and Woolcock call authority, acceptance and ability"; "The Permanent Secretary and the Citizen at the Counter disagree". These are the skill's thinking tools showing through. A President does not need the citations, and a reader who has never seen the skill will find "the Citizen at the Counter" baffling.

One artifact is not the skill's fault. The block of AP tool-disclaimer text ("The label 'Majority reached'... is not a call by AP"), pasted into a presidential memo, also appears in the without-skill defense run, so it comes from the election-results tool. But the skill's insistence on verifying officeholders sends the model to that tool. Nothing in the skill tells it to turn tool output into a plain planning assumption ("Planning assumption: Democratic majorities in both chambers from 3 January").

## Case 2: Singapore's national AI strategy

**This one is closer, and a good editor would want to merge the two.** Both answers correctly treat the 16 November BIS rule and the Megaspeed affair as the event that reorders everything. Both give the same thesis: align with the US at the chip and compute layer, stay open to China everywhere else, and turn trust into verifiable infrastructure.

The with-skill dossier is the better operating document. It has:

- a delivery table with an accountable minister and lead agencies for each pillar;
- the Digital Infrastructure Bill, already in Parliament, as a fast legislative vehicle;
- the UAE approved-entity arrangement as a precise negotiating template;
- dated deadlines (18 January comments, 17 February licences);
- a dashboard with tripwire-to-response pairs;
- four vivid failure stories;
- a crisp list of five decisions for the PM.

If I were a Permanent Secretary, this is what I would want on Monday.

The baseline is the better strategic memo, and it has more original ideas per page:

- **A symmetric anti-circumvention principle.** Write into Singapore law that Singapore will not be a conduit for evading *any* major partner's export controls, citing China's own MOFCOM Announcement No. 26 on rare-earth rerouting. This is the cleverest single move in either answer for the Beijing problem: it makes compliance defensible in Beijing, not just tolerable.
- **SEA-LION's dependence on Alibaba's Qwen.** It flags this as a strategic fragility and proposes a base-agnostic rebuild pipeline.
- **New niches:** a tropical-efficiency niche for data centres, an AI assurance, insurance and arbitration hub that builds on Singapore's reinsurance and arbitration strengths, a 90-day cap on pilot procurement, and a diaspora return programme.
- **Better diagnosis.** It explains *why* Washington sees a conduit: Nvidia billed 18% of FY2025 revenue to Singapore but shipped under 2% there.
- **Better currency.** It reports that Jensen Huang lost the Nvidia CEO job over the scandal. Search confirms the resignation, and the with-skill run missed it.

The baseline's weaknesses are exactly the assertions it fails or barely passes. Most actions have no named owner. Its 2029 scorecard mixes real targets with "tracked and growing". It discusses how the strategy could fail but never says what early signal would show it. Its closing aside to the user as a founder is off-question for "if you were running Singapore", though some users would welcome it.

**Problems in the with-skill run:**

- **The power cap doesn't bind.** Its headline constraint is a cap on data centres at "roughly 12% of the grid by 2030". The baseline's own source (TechNode, July 2026) says data centres are already projected to reach about 12% by the end of the decade. The cap restates the baseline and is presented as a decision for the PM. This is the kind of error a checklist hides: the "Definition of success" slot got filled without anyone asking whether the target bites.
- **Talent is thin** (500–1,000 hires and a wage-insurance pilot), even though the user named talent explicitly.

**Problems the skill appears to cause:**

- **The four-gates frame fits poorly.** The framework is built for passing domestic policy. Here it relabels "Washington's licence" as the "Passes gate", which adds vocabulary, not insight.
- **The odds line becomes a ritual.** "About 15% → about 30%" is followed at once by an apology: "the low overall number reflects how demanding the full target set is, not a fragile plan." When the model has to explain away its own number every time, the number is not earning its place.
- **Template parts repeat across unrelated problems.** "The Economist and the Geostrategist disagree here", Hirschman's perversity, futility and jeopardy, "What History Teaches" with a case-library case, a Statecraft lesson and "a question to sit with" in both reply and dossier. These make a Singapore AI strategy read like the same form as a US wealth memo.

## Case 3: the US defense industrial base

**Both arms pass every assertion, and on usefulness per minute of a principal's time the baseline is arguably better.** Both make the same core argument: this is a credible-demand problem, so trade topline for durability. Both make the same lame-duck moves: CR anomalies, the Senate's 19-munition list, no veto over the foreign-yard restriction, defer the battleship.

The baseline quantifies the problem more vividly. Six weeks of the Iran war consumed roughly 1,700 Patriot interceptors, against 620 produced in all of 2025. Its workforce diagnosis gets to the mechanism: shipyard pay has fallen from 3–4x to 1.2–1.4x comparable work, and first-year attrition is 50–60%. It shows that fixing maintenance would raise deployable attack submarines from 32 to 43, which is "more combat power, sooner, than any construction program".

It also finds three sharp political-budget moves the with-skill answer does not:

- **Separate interceptor replenishment from the contested $87.6bn Iran supplemental**, so members who oppose the war can still vote to rebuild the stockpile.
- **Put the unspent 2025 reconciliation defense money on multi-year contracts** before Democratic appropriators can claw it back. The with-skill answer never mentions this existing pot of money at all, a real gap for a "budget-wise" question.
- **Accept the Senate's equity-stake guardrails voluntarily**, so the tool survives oversight.

The with-skill answer has strengths the baseline lacks:

- a "four problems on four clocks" table that sets realistic fix times by asset class;
- reconciliation timing arithmetic (42–85 days needed against about 20 session days left);
- a named power map (Smith, Reed, Rogers, Wicker, DeLauro, Murray);
- an explicit list of concessions the President must make.

The concessions list is genuine speaking truth to power ("Slow the battleship... This is the President's signature programme, which is exactly why someone has to say it").

**Errors in the with-skill run:**

- **An unexplained figure.** A "$60bn package" appears twice with no explanation, even though the reconciliation figure everywhere else is $350bn.
- **Shaky history in the lesson.** The Statecraft lesson's history is overstated. The 1936 Merchant Marine Act gave about five years of orders before Pearl Harbor, not "a decade". French pre-war orders were mainly aircraft, not ships. It appears in both reply and dossier.
- **A forced analogy.** "Thatcher and the coal stockpiles" is pressed onto rare-earth stockpiling because it sits in the skill's case library.

**Problems the skill appears to cause** are the same as in the other cases: about 9,400 words, the four-clocks table and both odds lines duplicated across reply and dossier, a three-story pre-mortem and Hirschman labels whether or not they add anything, and the Statecraft lesson twice.

## Problems the skill causes across all three cases

**It produces a full dossier on the first turn every time, against its own instructions.** The skill says the default mode is Counsel ("No document. Usually a few hundred to about a thousand words") and that the dossier is for "once a real strategy has formed". It also warns that "padding a short answer into a dossier makes it worse." All three prompts were broad first-turn questions, closer to the Country Brief register. Yet every run produced a 1,800–2,400-word reply *plus* a 7,000–11,000-word dossier. The skill's description ("and a strategy dossier") and its 17-section dossier spec pull harder than the mode guidance does.

**The reply and the dossier say the same thing twice.** The reply is not a cover note; it is a second, shorter version of the dossier. Same arguments, same numbers, same odds line, same Statecraft lesson.

**Ritual elements appear regardless of fit:**

- the odds line, with its "judgment, not measurement" caveat;
- the cabinet disagreement device;
- Hirschman's three attacks;
- the History section built from case-library cases;
- the Statecraft lesson plus a question to sit with, in both reply and dossier.

None of these is bad once. Together, in every answer, they make the outputs feel templated, and a principal will start skimming past them.

**The skill's internal vocabulary leaks into client-facing prose.** Examples: "binding gate", "Passes gate", "change space", "policy-feedback logic of Pierson and Patashnik", "List's voltage effect", "Barber's deliverology", "the Citizen at the Counter". A grep for just a subset of these names finds a dozen hits across the with-skill outputs. The skill meant these as thinking tools.

**Probabilities are falsely precise.** Multiplying four judgment calls and publishing 0.1% or 0.6% invites ridicule. The real value of the odds line, showing which gate a design choice moves, comes through just as well in coarse bands.

**Hypothesis: the checklist may crowd out the search for non-obvious levers.** In Singapore and defense, the baseline found the more original moves: the symmetric export-control principle, spending existing reconciliation money, decoupling replenishment from the Iran supplemental. The skill runs spent more than twice as long, plausibly much of it filling sections. This is not proven from three cases, but it is consistent with what I see.

**What the skill clearly does well:**

- grounding in the actual seat and current political configuration (decisive in the wealth case);
- named owners and delivery architecture;
- tripwires with pre-agreed responses;
- "decisions required from the principal" lists;
- willingness to tell the principal unwelcome things.

These are worth keeping. The task is to keep them while cutting the volume and the ritual.

## Suggestions for the skill's instructions

1. **Make the first-turn default one integrated answer of about 1,500–3,000 words** for broad "what should X do" prompts. It should open with the answer, the seat and planning assumptions, the strategy with owners and sequence, the top risks with tripwires, and the decisions for the principal. Then *offer* the dossier. Produce a dossier unprompted only once the user has engaged with a direction.
2. **If a dossier is produced, cap the chat reply at about 250 words**: the bottom line, three decisions, the biggest risk and a pointer. Never write a second full version. Add an explicit rule against restating the dossier's arguments, tables, odds line or lesson in the reply.
3. **Turn the 17-section dossier into a core plus a menu.** Require six sections: Cabinet Brief; Problem and target; Seat, constraints and route; Strategy and sequence with owners; Pre-mortem with tripwires; First 100 days. Allow the rest only when they change a decision. Set a soft cap (say 4,000 words), and say plainly that "Minimal" or filler sections should be cut.
4. **Keep the thinking tools out of the output.** Tell the model: "Use the four gates, the cabinet and the framework library to think; present conclusions in plain language. Don't name frameworks, scholars or cabinet personas unless the user asks." The same goes for case-library cases: cite a precedent only if it changes the recommendation.
5. **Coarsen the odds line.** Use rounded figures (nearest 5%, never below 1%) or low/medium/high bands. Give the "judgment, not measurement" caveat once at most. Use it mainly to show which design choice moves which gate.
6. **Make the Statecraft lesson optional and once per response.** Never put it in both reply and dossier, and skip it in staff-style documents.
7. **Add two substance checks to the final checklist.** First: "Have I used money, authorities and vehicles already in motion before proposing new ones?" (the defense run missed the 2025 reconciliation funds). Second: "Does every target and constraint I propose actually bind against the projected baseline?" (the Singapore 12% cap does not). Also add: "Name two or three non-obvious moves a smart opponent would not expect."
8. **Tell the model to turn tool and search outputs into clean planning assumptions** and never paste tool-compliance language into advice.
9. **Let the gates framework flex for non-domestic problems.** For small states and foreign-policy questions, tell the model to describe external dependence directly rather than forcing it into "Passes".

## Notes on the evals

- **They don't discriminate.** Defense gives 6/6 to both arms. The two baseline failures are template sections, not quality.
- **Assertions to add:**
  - the seat is grounded in the *current* officeholder and partisan control;
  - targets carry baselines and actually bind;
  - each major action has a named owner;
  - the answer uses existing vehicles and money;
  - talent is covered (Singapore), since the user named it;
  - the wealth-gap answer is politically even-handed, as its expected outcome asks;
  - the key recommendation and first moves are in the first ~400 words;
  - no unexplained figures;
  - reply and dossier don't duplicate each other.
- **Add a blind pairwise judgment** ("which would a chief of staff rather receive?"). That is the only way to capture the originality and concision where the baseline sometimes wins.
