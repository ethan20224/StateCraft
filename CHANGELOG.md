# Changelog

## v2.0 — 2026-11-25

Version 2 is a revision driven by the iteration-1 side-by-side test (see `test-runs/iteration-1/`). The test showed v1's method was right: it beat plain Claude on grounding plans in who actually holds power, and it named bottlenecks, odds and tripwires. But v1 packaged its thinking badly. Version 2 keeps the method and fixes the packaging. It also adds three substance checks, each aimed at a specific miss.

### Changed

- **The first answer is one integrated reply, not a dossier.** For a big strategy question, the skill now gives one integrated answer of 1,500–3,000 words, with the recommendation and first moves in the opening paragraphs. It ends with the fork question and an offer to build the dossier. In v1, every test run produced a 7,000–11,000-word dossier on the first turn, against the "when a strategy forms" design choice.
- **The dossier is a lean core, not a 16-section template.** It now has six core sections: Cabinet Brief; Problem and Target; Seat, Constraints and Route; Strategy and Sequence; Risks and Tripwires; First 100 Days. Other material comes as optional modules, used only when they change a decision. The target length is 3,000–6,000 words. Filler sections get cut.
- **The chat reply beside a dossier is about 250 words.** It no longer restates the dossier.
- **Thinking tools stay backstage.** Dossiers are written in plain language for a leader's staff. They don't name frameworks or scholars, use cabinet personas, or say "the Passes gate". The cabinet never appears in the output as a dialogue.
- **Odds lines are coarse.** They are rounded to the nearest 5%, written as "under 5%" rather than a fake tiny figure, or given as bands. The caveat that they are judgments appears once at most.
- **The statecraft lesson appears once per turn, in the chat reply,** and never inside a dossier.
- **Case-library discipline.** A case is cited only when it changes or sharpens the recommendation. Fresh, domain-specific precedents beat the generic library.
- **In foreign policy, "Passes" includes external consent:** what allies, adversaries, markets or a great power's licensing regime will allow.

### Added

- **Use what's already in motion.** Before proposing anything new, the skill inventories money appropriated but unspent, powers on the books but unused, programmes already created (including the other side's), and deadlines and must-pass vehicles. The America section gains a matching paragraph. *Fixes: the defense run missed getting the 2025 reconciliation money onto contracts.*
- **Hunt for non-obvious moves.** It looks for two or three moves a smart opponent wouldn't expect: trades each side can sell at home, using the opponent's own programme, rules that apply to every great power, must-pass vehicles, and ring-fencing a popular item from a contested one. *Fixes: plain Claude found sharper moves than v1 in two of three cases.*
- **Targets must bind.** Every cap, target and threshold is checked against the projected baseline. *Fixes: a Singapore data-centre cap that matched the existing trend, so it would have changed nothing.*
- **Scan the last 90 days** of developments before diagnosing.
- **A named owner for every major action.**
- **Numbers hygiene.** Primary sources over news write-ups, no mixing of real and nominal figures, and no unexplained figures.
- **Tool output becomes dated planning assumptions.** The skill still follows any tool's rules on how results may be stated, but no tool boilerplate gets pasted into strategy documents.
- **The final check gains five questions:** current seat, existing levers, binding targets, non-obvious moves, recommendation up front, and template filler.

### Not yet done

- Version 2 has not been re-run against the three test prompts. A retest would confirm the shorter first answer still carries enough depth, and that the new checks actually produce sharper moves.

## v1.0 — 2026-11-25

First version: the four-gates method, bedrock truths, the strategist's sequence, the cabinet of lenses, six modes (Counsel, Country Brief, Strategy Dossier, War Room, Red Team, Crisis Desk), a 16-section dossier template, the American operating system, six domain playbooks, 19 frameworks, about 40 historical cases, thinking traps, neutrality rules, the statecraft lesson, and boundaries.
