# Trusted Node, Fastest Adopter
### A national AI strategy for Singapore that can survive Washington, Beijing and the grid

*Strategy dossier · 25 November 2026 · Prepared for the Prime Minister in his role as chair of the National AI Council*

**Working assumptions.** The principal couldn't be consulted, so I have assumed the following. **Seat:** the Prime Minister, working with the current Cabinet and statutory boards. **Horizon:** this term, up to the general election due by 2030, with a view out to 2035. **Values:** Singapore wants to stay commercially open to China while keeping access to the American AI stack. Where those two goals collide, the dossier says so and leaves the choice to the Prime Minister. Facts are current as of 25 November 2026 and are sourced inline. Odds and targets are my judgement and are marked as such.

---

## 0. Cabinet Brief

**Bottom line.** Singapore can't win the AI race as a contestant, and it doesn't need to: it already matters through chips, capital and hub functions. Since 19 November 2026 the danger is that it matters as the leak. Washington now requires a licence for every advanced AI chip entering Singapore, and has said it will weigh the effectiveness of the destination's own export-control regime when it decides. The strategy turns trust into verifiable infrastructure within 90 days, then spends the rest of the term making AI pay Singaporean workers.

**Recommended strategy.** Five moves, in order of urgency:

1. **Trusted compute.** Use the Digital Infrastructure Bill, which is already through First Reading, to build the most auditable compute regime in Asia. Then use that regime to negotiate a UAE-style approved-entity pathway with Washington.
2. **Indispensable hardware.** Concentrate semiconductor effort on memory, HBM advanced packaging, equipment and photonics. These are the parts of the AI supply chain the US itself needs Singapore for. Don't chase a leading-edge logic fab.
3. **Value-priced power.** Keep compute on Singapore soil for high-value inference, regulated workloads and sovereign workloads. Price megawatts by value. Build a jointly verified compute ring in Johor and beyond. Take a nuclear go/no-go decision by 2029.
4. **Diffusion as the main event.** Set up a small delivery unit that answers to one test: productivity and real wages in SMEs and in the four National AI Mission sectors. Add a sovereign fallback so that no foreign switch can turn off the government.
5. **Talent with a political licence.** Import the few hundred people Singapore can't grow at home, and visibly tie them to Singaporean capability. Make the transition pay displaced workers, so the public keeps consenting to openness.

**Decisions required from the Prime Minister.**
1. **The values call.** Will Singapore be verifiably on the US side of the line on frontier-compute chokepoints (advanced chips, controlled compute), while staying open to Chinese firms, models, capital and talent everywhere else? I recommend yes. The cost is real and is set out in section 9.
2. **The vehicle.** Should compute-integrity powers go into the Digital Infrastructure Bill at Second Reading, which is fast but will draw industry pushback, or into a separate bill, which is cleaner but slower? I recommend the Bill.
3. **The power cap.** Should data centres be held to a fixed share of the grid, with all new capacity awarded on value per megawatt? I recommend yes, at roughly 12% by 2030, though that figure is a judgement.
4. **Nuclear.** Should Singapore fix a decision date (2029) and fund the pre-decision work now? I recommend yes.
5. **Accountability.** Name one minister accountable for "trusted access" and appoint a special envoy to Washington this week.

**Single biggest risk.** Washington may keep Singapore on the licence list as bargaining leverage whatever Singapore does, while Beijing reads Singapore's compliance as alignment and quietly retaliates. A compliance problem would then become a squeeze from both sides. The design answers to this are in sections 9 and 10.

**Odds line.**
> As things stand: Works 0.65 · Passes 0.6 · Delivered 0.55 · Lasts 0.7 → **about 15%** of hitting most of the 2030 targets in section 1.5.
> With this design: Works 0.7 · Passes 0.8 · Delivered 0.7 · Lasts 0.75 → **about 30%**.
> **Binding gate now: Passes.** For a small open economy, "assembling the authority" includes external permission, and Washington's licence is that authority. **From 2028 the binding gate shifts to Delivered:** SME diffusion and power supply.
> My judgement is that the trusted-access objective alone has a 65–70% chance of being secured by the end of 2027. The low overall figure reflects how demanding the full set of targets is together. It does not mean the plan is fragile.

**This week.** Convene the National AI Council in emergency session. Name the accountable minister and the envoy. Announce that compute-integrity amendments will go into the Digital Infrastructure Bill, and stand up a joint enforcement taskforce. Brief Beijing and Kuala Lumpur privately before the announcement, not after.

---

## 1. The Problem, Reframed

### 1.1 What is actually happening

**The official strategy is better than its reputation.** NAIS 2.0 (December 2023) was refreshed on 20 May 2026 into ten priorities spanning industry, government, research, talent, capabilities, ecosystem, compute, data, a trusted environment and international leadership. It names Singapore's ASEAN chairmanship in 2027 as a platform ([MDDI factsheet](https://mddi.gov.sg/newsroom/update-to-singapore-s-national-ai-strategy--refreshed-priorities-to-harness-ai-for-the-public-good-factsheet)). The Prime Minister has chaired a National AI Council since February 2026. Budget 2026 brought several measures ([ComputerWeekly](https://www.computerweekly.com/news/366638920/Singapore-to-form-National-AI-Council-expands-tax-breaks-to-ease-AI-adoption)):
- National AI Missions in advanced manufacturing, connectivity and logistics, finance, and healthcare
- a 400% tax deduction on AI spending for YA2027–28, capped at S$50,000 a year
- a Champions of AI programme
- S$37bn under RIE2030

PM Wong's own framing is correct: "Our advantage does not lie in building the largest frontier models." The strategy's weakness is not its ideas. **It has ten priorities, which in practice means none, and it was written before the ground moved.**

**The ground moved on 16 November 2026.** The US Bureau of Industry and Security issued an interim final rule, effective 19 November ([Hogan Lovells](https://hlc.com/en/publications/bis-issues-new-controls-targeting-remote-access-to-advanced-us-computing-power); [Steptoe](https://www.steptoe.com/en/news-publications/international-compliance-blog/bis-targets-data-center-remote-access-and-imposes-steeper-requirements-on-foundries-and-osats.html)). It does five things:
- It **adds Singapore, Malaysia, Thailand, Indonesia and Brazil to a licence requirement** for advanced AI chips, as destinations with elevated diversion risk.
- Licence review is **case by case**. The stated factors include "the effectiveness of the destination's export control regime" and its coordination with BIS on enforcement. BIS warns that countries which tolerate evasion face downgraded status, import restrictions and Entity List designations.
- **US-headquartered consignees are exempt.** Singapore-headquartered ones are not.
- Any data centre anywhere providing more than 12 million TPP of compute to China-headquartered companies needs a licence. That threshold works out to roughly 750 top-end GPUs ([e27](https://e27.co/a-750-chip-ceiling-how-us-curbs-redraw-the-map-for-malaysias-ai-data-centres-20261118/)).
- Foundries and OSATs can no longer use due-diligence routes to clear advanced logic chips from designers based in the five countries, unless those designers hold approved status.

Existing data centres must be licensed by **17 February 2027**. Comments on the rule are due by **18 January 2027**.

The trigger was Megaspeed, a Singapore-based cloud firm and Nvidia's largest buyer in Southeast Asia. US authorities have run a criminal investigation into Megaspeed since 2024, and Singaporean law enforcement joined a 2025 on-site check ([SCMP](https://scmp.com/tech/tech-war/article/3374742/us-details-criminal-probe-nvidia-customer-megaspeed-over-potential-chip-diversion)). Reports put the alleged diversion at somewhere between US$4bn and more than US$7.5bn. Megaspeed denies wrongdoing ([Fortune](https://fortune.com/2026/11/17/sg-us-ai-chip-controls-southeast-asia/); [The Standard](https://www.thestandard.com.hk/world/article/348776/Singapore-in-damage-control-after-Nvidia-scandal-exposes-China-loophole)).

Singapore responded on 16–17 November. It said it does not condone the use of a Singapore association to get around other countries' laws, that it is engaging US authorities, and that it is exploring "trusted access" for legitimate firms ([Let's Data Science](https://letsdatascience.com/news/singapore-seeks-trusted-access-to-ai-chips-after-new-us-curb-c1cf0c3b); [ANN](https://asianews.network/?p=315540)). Its standing legal position, stated in Parliament in February 2025, is that Singapore has "no legal obligations to enforce the unilateral export controls of other countries." It acts only where firms use deceptive practices under Singapore law. In that same reply, physical Nvidia deliveries into Singapore were put at under 1% of Nvidia's revenue, even though far more is billed to Singapore entities ([METI](https://www.meti.gov.sg/newsroom/oral-reply-to-pqs-on-singapore-s-approach-to-export-controls/)). That combination served Singapore well in a globalised world. In a chokepoint world it reads as tolerance.

The irony is that only eleven months earlier, Singapore became the only Southeast Asian founding signatory of the US-led Pax Silica declaration on trusted AI supply chains ([Fortune](https://fortune.com/2025/12/30/why-singapore-is-the-only-southeast-asian-country-in-pax-silica-ai/); [ITIF](https://itif.org/publications/2026/11/16/pax-silica-timeline/)). **Membership of the inner circle did not protect Singapore. Its enforcement record decided its status.**

**Frontier models are now a chokepoint too.** On 12 June 2026, a US export-control directive forced Anthropic to cut off all foreign nationals from its newest models ([Al Jazeera](https://www.aljazeera.com/economy/2026/6/14/us-orders-anthropic-to-disable-ai-models-for-all-foreign-nationals)). As of July, the most capable of them was still limited to a small number of US organisations ([Bloomberg Government](https://news.bgov.com/bloomberg-government-news/us-limits-on-anthropics-mythos-keep-foreign-firms-in-limbo-1)). GIC co-led Anthropic's US$65bn Series H in May 2026, with Temasek as a significant investor ([TechNode Global](https://technode.global/2026/05/29/gic-temasek-anchor-singapores-investment-in-anthropics-65b-series-h-round/)). **The lesson is that capital does not buy access. Access is decided between governments.**

**The AI boom is already Singapore's growth engine.** GDP grew 6.1% in the first half of 2026. The full-year forecast was raised to 4.5–5.5% on the back of global AI capital expenditure ([METI](https://www.meti.gov.sg/newsroom/mti-upgrades-2026-gdp-growth-forecast-to--4-5-to-5-5-per-cent-/)). Singapore makes about one in ten of the world's chips and a fifth of its semiconductor equipment. A new S$800m semiconductor R&D flagship (2026–30) prioritises advanced packaging, silicon photonics and power electronics ([EDB](https://www.edb.gov.sg/en/news-and-insights/singapore-announces-sg-semiconductor-to-strengthen-its-role-in-the-global-semiconductor-ecosystem)). Micron's US$7bn HBM advanced-packaging plant, its first outside Taiwan, begins output in early 2027, and a US$24bn wafer fab follows in the second half of 2028 ([The Star/Bernama](https://www.thestar.com.my/aseanplus/aseanplus-news/2026/11/07/micron-strengthens-singapore-footprint-with-us24bil-investment-in-ai-driven-manufacturing)).

**Compute is capped by power and land.** Singapore had about 1.4GW of data-centre capacity across more than 70 facilities when the Green Data Centre Roadmap was set in 2024 ([EDB](https://www.edb.gov.sg/en/news-and-insights/singapore-to-expand-data-centre-capacity-by-at-least-one-third-pushes-for-green-energy-use)). Data centres use more than 7% of national electricity and vacancy is under 2% ([King & Wood Mallesons](https://www.mallesons.com/content/mallesons/sg/en/insights/latest-thinking/singapore-launches-200mw-data-centre-call-for-application-dc-cfa2)). The second Data Centre Call-for-Application allocated 200MW to four operators in August 2026, with requirements of at least 50% green energy and a PUE of 1.25 ([EDB](https://www.edb.gov.sg/en/about-edb/media-releases-publications/four-data-centre-proposals-selected-as-part-of-second-data-centre.html)). The national supercomputer ASPIRE 2B has 1,536 H200 GPUs ([NSCC](https://www.nscc.sg/portfolio/item/nsccs-aspire-2b-debuts-at-rank-44-and-184-on-top500-list/)). That is a useful research machine, and it is orders of magnitude short of a frontier training cluster.

**Energy is the hard physical constraint.** Up to 95% of Singapore's electricity comes from natural gas. In October 2026, Wood Mackenzie projected that imported low-carbon power will reach about 15% of the mix by 2035, roughly half the official target. Of 9.25GW of approved import capacity, none has reached financial close. Malaysia is the only corridor with a credible path this decade: 900MW is approved, including 300MW from Sembcorp that could flow by 2029 ([NST/Reuters](https://www.nst.com.my/amp/business/economy/2026/10/1550070/singapore-set-miss-2035-green-power-import-target)). The government calls the energy challenge "existential" and is "seriously studying" small modular reactors, but has made no decision ([Malay Mail](https://www.malaymail.com/news/singapore/2026/03/03/singapore-eyes-nuclear-shift-as-energy-crunch-turns-existential-parliament-told/211157); [EMA](https://ema.gov.sg/news-events/news/feature-stories/2026/understanding-advanced-nuclear-energy-technologies-how-singapore-is-assessing-its-potential)). The Ministry of Trade and Industry became the Ministry of Energy, Trade and Industry (METI) on 1 October 2026 ([Mothership](https://mothership.sg/2026/07/ministry-energy-trade-industry-new-name/)).

**Diffusion is real but lopsided.** In 2025, 23.5% of enterprises used AI, up from 14.7% the year before. Among SMEs the figure was 23.4%, against 70.4% for larger firms. Some 86% of workers report using AI at work ([IMDA via People Matters](https://sea.peoplemattersglobal.com/news/ai-and-emerging-tech/singapore-ai-adoption-rises-to-235percent-as-digital-economy-reaches-dollar1441bn-52560)).

**Labour anxiety is rising.** Retrenchments hit 3,830 in Q1 2026, the highest since 2023. About 6.2% of firms reported AI-related headcount cuts ([The Star/ST](https://www.thestar.com.my/aseanplus/aseanplus-news/2026/06/15/more-retrenchments-in-singapore-in-q1-2026-as-job-vacancies-drop)). A Tripartite Jobs Council on AI disruption was announced in April ([MOM](https://mom.gov.sg/newsroom/press-releases/2026/0430-formation-of-tripartite-jobs-council)).

**Talent and labs.** The ONE Pass (AI and Tech) track replaces the Tech.Pass from January 2027, with a S$30,000 monthly threshold that can now count equity ([SGN](https://singaporeglobalnetwork.gov.sg/stories/business/explained-singapores-2026-global-talent-policy-changes-and-why-it-works-in-favour-of-top-talent/)). OpenAI and Google DeepMind run applied AI labs in Singapore, and OpenAI has committed S$300m to the ecosystem ([Fortune](https://fortune.com/2026/06/19/us-china-ai-firms-set-up-singapore-offices-neutral-hub/)). Anthropic opened an office in October 2026 and signed a safety and evaluation MoU with MDDI. More than 1,500 GovTech engineers use its coding tool ([eWeek](https://www.eweek.com/news/anthropic-apac-singapore-office-ai-safety-deal/)). I could not find a published progress figure against NAIS 2.0's target of 15,000 AI practitioners.

**US–China backdrop.** The trade truce was extended to 10 January 2027. Reports say Washington refused to put chip controls on the table, and a crisis-management "AI dialogue" was announced ([Cyprus Mail, opinion](https://cyprus-mail.com/2026/10/18/trump-xi-meeting-just-kicked-can-down-the-road)). Washington's own chip policy has swung repeatedly. The January 2025 Diffusion Rule was rescinded. A narrow, tariffed channel for some H200-class sales to China opened in January 2026 ([White & Case](https://www.whitecase.com/insight-alert/president-trump-orders-narrowly-targeted-25-section-232-tariff-certain-advanced)). The November rule then tightened on Southeast Asia. **Washington wants to control the channel, not to stop every sale. Singapore's opening is to be a controlled channel rather than a leaky one.**

### 1.2 Four versions of "mattering", and which one to pursue

| Version | What it would take | Verdict |
|---|---|---|
| **Contestant**: frontier models, leading-edge fabs | Gigawatts of power, hundreds of thousands of GPUs, a home market, US$20bn+ per fab | **Reject.** Physically and financially out of reach. The PM has already said so publicly. |
| **Trusted node**: the place the AI supply chain runs through and believes | Verifiable compliance, memory and packaging indispensability, connectivity, capital, legal certainty | **Pursue. This is urgent.** It is the asset now at risk. |
| **Fastest adopter**: the place where AI shows up first in productivity and wages | Firm-level capability, workforce transition, government as lead customer | **Pursue. This is the main event.** It is fully in Singapore's control, and it is where legitimacy comes from. |
| **Rule-shaper**: convenor of standards and safety practice | Credible testing and assurance, incident reporting, the ASEAN chair | **Pursue as a multiplier.** It is cheap, but it can't substitute for hard assets. |

**Sovereign resilience** is the floor under all four: the ability to keep government and critical services running if a foreign switch is flipped.

### 1.3 Root-cause tree: why Singapore could end up mattering in the wrong way

- **No scale** (land, power, market) → can't host frontier training → value has to come from *position*, not *mass*.
- **The trust model was built for globalisation.** Light-touch openness made Singapore a billing hub far larger than its physical deliveries, and the legal stance of not enforcing others' unilateral controls was designed for neutrality. In a chokepoint world both read as tolerance → the November rule → slower chip inflow.
- **The rule favours US landlords.** US-headquartered firms are exempt and Singapore-headquartered ones are not → Singapore-owned compute now carries a licence cost that AWS, Azure and Google Cloud don't → sovereign capacity gets squeezed.
- **Energy is dependent on gas,** imports are slipping and nuclear is undecided → compute growth is physically capped.
- **The diffusion gap** (SMEs at 23% versus large firms at 70%) → gains concentrate in MNCs and foreign talent → wage anxiety and political pressure on openness.

**The feedback loop to protect:** compute access → labs and hyperscalers → talent → startups and adoption → more compute demand. Throttled licences run the same loop in reverse.

**Who benefits from the status quo**, and is therefore the first opponent:
- grey-zone GPU-as-a-service resellers and billing intermediaries
- operators with large China-headquartered AI tenants
- firms that value light-touch oversight
- inside government, a promotion-first culture that has historically outranked enforcement

### 1.4 The cost of doing nothing

If Singapore treats this as a public-relations problem, three things follow:
- Licences slow. Hyperscalers route new Asian AI capacity to Japan, Korea, India and Australia. Labs keep sales offices in Singapore but put compute elsewhere.
- Singapore-based chip designers face longer foundry lead times under the new presumption.
- Any further diversion case risks escalation to downgraded status or Entity List designations of Singapore entities, which is the outcome BIS has explicitly threatened.

Meanwhile domestic diffusion stalls, because ten parallel priorities have no single owner. The status quo is not stable. It is drifting towards a smaller, more suspect Singapore.

### 1.5 Definition of success (targets are judgement; baselines to be confirmed)

| Objective | Metric | Target | Date |
|---|---|---|---|
| Trusted access | Approved-entity or G2G arrangement covering Singapore government agencies and named Singapore operators | Signed | End-2027 |
| Trusted access | Median BIS licence decision time for Singapore applicants | Under 60 days, more than 90% approved | End-2027 |
| Integrity | New major diversion cases traced to licensed Singapore facilities | Zero | Ongoing |
| Hardware | Micron HBM ramp on schedule, plus new advanced-packaging or photonics anchors | 2 or more new anchors | 2028 |
| Power | Data-centre share of national electricity | 12% or less, with rising value per MW | 2030 |
| Power | Import corridors at financial close; nuclear decision | 2 or more corridors; decision taken | 2028; 2029 |
| Diffusion | SMEs using AI in a core business process (a new, stricter measure) | 50% or more | 2030 |
| Dividend | Labour productivity growth in Mission sectors; real median wage growth | At least 3% a year; at least 2% a year | 2027–30 average |
| Transition | AI-displaced PMETs re-employed within 6 months | 70% or more | From 2028 |
| Resilience | Critical government services running on sovereign-hosted models in a cut-off drill | 90 days sustained | Tested annually from 2027 |

---

## 2. The Seat and the Constraints

**Principal and powers.** The Prime Minister chairs the National AI Council and leads a government with a large majority from the May 2025 election. Its levers are unusually direct. Statutory boards (EDB, IMDA, EMA, JTC, A*STAR, Customs) can move within weeks. Legislation passes in one or two sittings. Fiscal room is ample. What the PM cannot do is direct GIC or Temasek's investment decisions, because their independence is part of their credibility. He also can't legislate Washington's or Beijing's choices, or create land and power.

**The clock.**

| Date | Event |
|---|---|
| 10 January 2027 | US–China truce expires |
| 18 January 2027 | Comments due on the BIS rule |
| January 2027 | ONE Pass (AI and Tech) launches; Singapore takes the ASEAN chair |
| February 2027 | Budget 2027 |
| 17 February 2027 | Licence deadline for existing data centres |
| Early 2027 | Micron HBM output |
| 2028 | Kampong AI opens; Micron fab starts |
| By 2030 | General election |

**Political capital** is high now and will be needed for two fights: industry over compliance costs, and the public over energy and foreign talent. Spend it on the first in the next 90 days, while the Megaspeed shock makes the case for you.

**External constraints.** US licensing and frontier-model controls. Chinese economic leverage: China is Singapore's largest trading partner, and Chinese firms use Singapore as their gateway abroad. Neighbours' export-permit regimes for power. Section 232 and successor tariff uncertainty after the US Supreme Court struck down the IEEPA tariffs in February 2026 ([METI](https://www.meti.gov.sg/newsroom/oral-reply-to-pqs-on-updated-assessment-on-impact-on-singapore-s-economy-and-businesses-from-new-15--tariffs/)).

**Legal constraints.** The Strategic Goods (Control) Act tracks multilateral regimes, not US unilateral lists. Any compute-integrity regime has to be Singapore law protecting Singapore's integrity, not an import of US law. That is a design constraint, not an obstacle (see the Netherlands precedent below).

---

## 3. What History Teaches

**Swiss banking secrecy, 2009–2017.** The neutral-haven model collapsed once the hegemon could make market access conditional. UBS paid US$780m and handed over client names in 2009, and Switzerland moved to automatic exchange of tax information within a decade. Swiss wealth management survived by trading secrecy for verifiability. The banks and jurisdictions that resisted lost business. *What transfers:* a neutrality premium doesn't survive weaponised interdependence, but a trust premium does. *What doesn't:* Switzerland had EU market access as a cushion. Singapore has no equivalent.

**MAS and 1MDB, 2016.** Singapore shut BSI Bank's Singapore operation, its first bank closure in 32 years, and then Falcon Private Bank's branch. It acted faster and harder than foreign regulators expected, and the financial centre's brand came out stronger. The 2023 S$3bn money-laundering case was followed by tightened AML rules rather than defensiveness. *What transfers:* when the hub's brand is on the line, Singapore's own history says to over-correct quickly and visibly.

**The Netherlands and ASML, 2023.** Under US pressure, the Dutch did not apply US law. They issued their own national export regulations on advanced lithography, which kept a sovereign decision-maker in The Hague while meeting the substance of US concerns. *What transfers:* this is the exact template for reconciling Singapore's legal stance with what Washington needs. Make the rules Singapore's own. A chokepoint got the Dutch a seat at the table, not immunity.

**The UAE, 2024–2026.** The UAE was once suspected as a diversion route. It reached a privileged position through hard choices and paperwork: G42 divested from Chinese hardware, deep partnerships with US hyperscalers, and in July 2026 a BIS rule listing approved UAE entities (government agencies, two AI firms on time-limited authorisation, and subsidiaries of US hyperscalers) for licence-free access. Law-firm analysis calls this "the template" for strategic partners ([Morgan Lewis](https://www.morganlewis.com/ru/pubs/2026/07/bis-upgrades-uae-export-control-status-with-ai-chip-access-limited-to-approved-entities)). *What transfers:* the approved-entity architecture. *What doesn't:* the UAE's trillion-dollar investment pledges. Singapore has to pay mainly in verification and rule of law, and secondarily in its sovereign investors' US exposure.

**Electricity and the factory, 1890s–1920s.** Paul David's classic finding is that factories took decades to show productivity gains from electric power, because the gains required redesigning the work, not just changing the motor. *What transfers:* adoption statistics will rise long before productivity does. Singapore's advantage is a state that can redesign workflows sector by sector. The trap is measuring the tool and not the work.

**CHIPS Act fabs, 2022 onwards, and Korean industrial policy.** Money without workforce, permitting and suppliers produced delays in America. Korea's support worked because it was conditional on export performance, with cut-offs. *What transfers:* every semiconductor incentive should be conditional and clawback-able, and the technician pipeline is a binding input.

**What doesn't transfer at all:** Taiwan's and Korea's scale, the UAE's cheque and political system, and the EU's protective umbrella around the Dutch.

---

## 4. The Power Map

| Actor | Power over outcome | Stance | Intensity | What they want | What moves them |
|---|---|---|---|---|---|
| **US Commerce/BIS, NSC, Treasury** | Decisive (licences) | Suspicious | High | No diversion to China; control of the channel; allies buying the American stack | Verifiable regime, information-sharing, joint end-use checks, visible prosecutions |
| **White House** | Decisive at the top | Transactional | Medium | Investment, "wins", tariff leverage | Investment framing; Pax Silica; Singapore as showcase partner for US AI exports |
| **Congress China hawks (both parties)** | Indirect but persistent | Hawkish | High | Tighter controls, location verification | A regime ahead of their demands; no new scandals |
| **US hyperscalers and Nvidia** | High (lobby, investment) | Ally if engaged | Medium-high | Keep selling into and operating in Singapore | Clarity; an approved-entity path for their Singapore partners and customers |
| **Micron, AMAT, GlobalFoundries etc.** | High (they *are* the indispensability) | Ally | Medium | Supply-chain continuity, workforce | Technician pipeline; help with the new OSAT/foundry obligations |
| **Beijing (MOFCOM, MFA, security services)** | High (economic leverage) | Wary | Medium-high | Third-country compute access; a Singapore that stays "neutral" | Rules-based, non-discriminatory framing; continued openness to Chinese firms everywhere outside controlled compute |
| **Chinese firms in Singapore** (ByteDance, Alibaba Cloud, Tencent, gateway firms) | Medium | At risk | High for those with AI compute | Keep operating; keep the regional HQ | Clear lines; transition time; reassurance about non-AI business |
| **Malaysia (Johor) and Indonesia (Batam)** | Medium (power, overflow capacity) | Competitor-partner | Medium | Get off the list themselves; capture data-centre investment | Shared verification standard under the JS-SEZ and ASEAN chair; power-import revenue |
| **Data-centre operators** (US-headquartered and Singapore-headquartered) | Medium | Split | High | Licences by 17 February; predictable rules | Licensing clinic; regime that wins approved status; compliance costs kept proportionate |
| **Frontier labs** (OpenAI, Google DeepMind, Anthropic) | Medium | Supportive | Medium | Talent, enterprise customers, a trusted base in Asia | Talent passes, government as anchor customer, evaluation partnerships |
| **NTUC and workers** | Medium (legitimacy) | Conditional | Rising | "No jobless growth"; wage gains | Visible transition support; a say through the Tripartite Jobs Council |
| **SMEs and the SBF** | Medium | Supportive but under-capacitated | Medium | Practical help, not more grants to apply for | Done-for-you implementation; outcome-based funding |
| **Opposition parties** | Low on votes, medium on narrative | Critical on cost of living, foreign talent, sovereignty | Medium | Accountability | Transparency on energy pricing, talent data, and the enforcement report |
| **Inside government: EDB culture versus enforcement agencies** | Medium | Tension | Medium | Investment *or* integrity | Make integrity part of the promotion pitch, so certainty becomes the product |

**Veto points:** Washington's licences; Beijing's retaliation; neighbours' export permits for power; domestic consent on energy prices and foreign talent; whether industry is willing to comply.

**Coalition path:** US hyperscalers, Nvidia and Micron (whose own business depends on Singapore being approved), plus Singapore operators and the labs, plus the tripartite partners at home. Opposed by grey-zone resellers, whom Singapore should be happy to lose.

---

## 5. Options Considered

| Option | Works | Passes | Delivered | Lasts | ≈ Odds | Size of prize |
|---|---|---|---|---|---|---|
| **A. Stay neutral and lobby.** Defend sovereignty, minimal changes, argue for removal. | 0.30 | 0.25 | 0.90 | 0.35 | ~2% | Medium |
| **B. Sovereign scale.** Gigawatt data centres, a national frontier model, a leading-edge logic fab. | 0.20 | 0.40 | 0.30 | 0.40 | ~1% | Large but illusory |
| **C. Pure adopter.** Drop hub ambitions and use AI from wherever it is cheapest. | 0.55 | 0.90 | 0.60 | 0.55 | ~16% | Small to medium |
| **D. Trusted Node, Fastest Adopter** (as designed below) | 0.70 | 0.80 | 0.70 | 0.75 | **~30%** | **Large** |

Option A fails Works because the rule itself prices regime effectiveness. Lobbying without a regime asks Washington to take Singapore's word, which it just declined to do. Option B fails on physics: Singapore can't power or license its way to frontier scale, and ASPIRE 2B is orders of magnitude short. Option C is the honest challenger. It scores almost as well as an undesigned version of D, because it needs nothing from Washington. But its prize is smaller, and its durability is weak. A pure adopter has no leverage when access to models is cut, and it gives up the chips, data-centre and HQ base that drove 2026 growth.

**The Economist and the Geostrategist disagree here.** The Economist would take C's odds. The Geostrategist points out that C makes Singapore a price-taker in exactly the chokepoints now being weaponised. D is C plus the trust, hardware and energy work that gives Singapore leverage. **It wins on odds multiplied by prize.**

---

## 6. The Strategy

**Theory of change.** If Singapore makes its compute ecosystem the most verifiable in Asia, Washington's licensing logic flips from "Singapore is a leak" to "Singapore is the safe channel", because the rule explicitly rewards regime effectiveness. That restores chip and model access, which keeps hyperscalers, labs and talent in Singapore. If Singapore then spends its political capital on diffusion, AI's gains show up in Singaporean productivity and wages. That sustains the public's consent to the openness the hub depends on: foreign talent, energy imports and foreign firms.

**The organising principle is to be aligned on chokepoints and open on everything else.** On hardware and controlled compute, Singapore is verifiably inside the US-compliant perimeter, because there is no alternative supply of leading-edge accelerators at scale, and because Singapore's own semiconductor base sits inside that ecosystem. On models, talent, trade, capital and corporate presence, Singapore stays open to all lawful business, Chinese included. Running Chinese open-weight models on compliant hardware is not restricted by the November rule. This is the needle Singapore can thread. It is the hardest call in this dossier, and it belongs to the Prime Minister.

### Pillar 1: Trusted Compute (the binding gate; 0–12 months)

**Law.** Amend the Digital Infrastructure Bill at Second Reading. It already licenses data centres of 10MW or more and major cloud providers, and lets DC-CFA commitments be enforced as licence conditions ([MDDI](https://www.mddi.gov.sg/newsroom/new-digital-infrastructure-bill-to-strengthen-the-foundations-for-singapore-s-digital-economy/)). Add a compute-integrity part covering:
- know-your-compute-customer obligations, including the ultimate parent
- an accelerator register, reconciled quarterly against Customs import data and physical audits
- a duty to report suspected diversion
- inspection powers for IMDA and Customs
- penalties up to licence revocation, plus criminal liability for false declarations

The design is the Dutch one. This is **Singapore law protecting Singapore's integrity**, applied to every nationality alike, and modelled on AML know-your-customer rules. It is not an extraterritorial import of US law. It also converts thousands of private customer attestations, which the rule already requires operators to give exporters, into one sovereign assurance.

**Enforcement.** Set up a Joint Compute Integrity Taskforce of Customs, IMDA, CSA, the Commercial Affairs Department and MAS (for financial flows). In its first 60 days it runs a voluntary-disclosure window and a census of every accelerator in licensed facilities. Publish an annual enforcement report. On Megaspeed, let due process run, but run it visibly and quickly. The 1MDB playbook applies.

**Negotiation.** Appoint a special envoy and a single accountable minister. Before 18 January, propose a **Trusted Compute Arrangement** to Washington. Singapore government agencies, named Singapore operators and US-hyperscaler subsidiaries would receive approved-entity treatment, on the UAE pattern. In return Singapore offers its regime, routine information-sharing and joint end-use checks. Line up supporting comments from US hyperscalers, Nvidia and Micron, all of whom have Singapore exposure. Keep the arrangement at agency level (BIS and Customs) so it survives changes of administration.

**Near-term triage.** Run a government licensing clinic so every existing operator files before 17 February. The priority is Singapore-headquartered operators, who lack the exemption US-headquartered firms enjoy.

**Frontier-model access.** Offer Singapore's AI testing institute as an evaluation partner for restricted models. Make "allied access for evaluated partners" a standing ask in every lab MoU and in US talks. Plan as if that ask fails (Pillar 4's sovereign fallback).

**Governance diplomacy, kept practical.** Lead with incident reporting and testing standards. Wong's October proposal for an international AI incident-reporting pilot fits ([AF.net/AsiaOne](https://af.net/realtime/singapore-pm-lawrence-wong-proposes-international-ai-incident-reporting-pilot/)). Keep a low profile on calls for new UN institutions while the licence question is open, because Washington has been openly hostile to centralised international AI governance. Singapore co-signed the September 2026 call for frontier-AI oversight with the EU and 20 others ([ANN](https://asianews.network/?p=302935)). That is defensible, but this is not the quarter to lead it.

**The Beijing channel.** Brief Beijing at senior level before the announcement. The message: the rules are non-discriminatory; Chinese firms are welcome; workloads that don't involve controlled US chips are unaffected; and Singapore remains Chinese firms' best gateway to the world, which Beijing doesn't want to lose either.

### Pillar 2: Indispensable hardware

**Stop:** no subsidy race for a leading-edge logic fab.

**Go:** HBM and advanced packaging (Micron's ramp, plus OSAT and substrate suppliers), silicon photonics and co-packaged optics, power electronics for data centres, and equipment. These are the parts of the AI bill of materials where scarcity now sits, and where Washington needs Singapore. Target two or more new anchors by 2028. Make every incentive conditional on output and technician-training milestones, with clawbacks.

**Help industry live with the new rule.** Stand up a shared classification and compliance service through EDB, A*STAR and Customs. It would help Singapore-based chip designers win "approved IC designer" status, and help OSATs rebuild customer screening under the new presumption.

**Workforce.** The CHIPS lesson is that technicians are the binding input. Expand the ITE and polytechnic pipelines into packaging and photonics, co-designed with anchor firms.

**Leverage, used quietly.** Micron's HBM, which feeds American AI accelerators, will be packaged in Singapore. Indispensability is a negotiating asset. Mention it once, privately.

### Pillar 3: Value-priced power

**Principle.** Singapore's megawatts are among the scarcest and dearest in Asia. Allocate them by value, not by queue.

**What stays on Singapore soil:** latency-sensitive inference; regulated financial, health and government workloads; the sovereign fallback; and the regional inference endpoints of labs and hyperscalers. Bulk training goes elsewhere.

**Pricing and cap.** Data centres pay the full marginal cost of new supply plus a green premium, so households are not cross-subsidising them. Their share of the grid is capped at about 12% by 2030 (a judgement to be validated by EMA). All new allocations go through DC-CFA-style competitions scored on value per megawatt: R&D, local jobs, compute access for Singapore firms, and efficiency.

**The regional ring.** Under the Johor–Singapore Special Economic Zone, propose a joint verification standard, essentially Pillar 1 exported, so that Johor capacity can safely serve Singapore firms. As ASEAN chair in 2027, table an **ASEAN Compute Integrity Framework**: a common standard that gives all four listed ASEAN states a route off the list together. Its value to neighbours is chip access. Its value to Singapore is a credible overflow ring.

**Supply.** Wood Mackenzie names four blockers on imports: export permits, bankability, transmission finance and carbon accounting. Attack them with government-backed offtake for the first corridors, recognition of the carbon value of imported power, and blended finance for transmission. Prioritise Malaysia, the only corridor credible this decade.

**Nuclear.** Hold the IAEA infrastructure review in 2027 and commit publicly to a go/no-go decision in 2029. Fund regulator- and skills-building now as option value. If the answer is yes, first power arrives in the mid-to-late 2030s. Deciding late means none at all.

### Pillar 4: Diffusion is the main event (binding gate from 2028)

**The machine.** Create an **AI Delivery Unit** in the Prime Minister's Office: perhaps 20 people, reporting to the National AI Council, with five priorities, trajectories and a monthly stocktake with the PM. Barber's deliverology, applied. Replace the ten published priorities with five measured ones, without abolishing anything.

**Mission owners.** Each National AI Mission gets one owner with a budget and a public outcome target. Examples (to be set with sector agencies):
- healthcare: polyclinic administrative hours per patient
- logistics: port and airport throughput per worker
- finance: advisory and compliance productivity
- manufacturing: yield and changeover time

**SMEs.** The gap is capability, not cost. Create an "AI Implementation Corps": certified partners paid on outcomes delivered, not on hours or applications. Build sector-wide shared tools once and use them thousands of times: agents for F&B, retail, logistics and professional services, built by GovTech and IMDA with industry. Keep the 400% deduction, but recognise it as small. Convert the Productivity Solutions Grant to outcome-based tranches.

**Government as proof.** Redesign every high-volume citizen service around AI by 2028. Publish the productivity gains, including the 1,500 GovTech engineers already using AI coding tools.

**Sovereign fallback (minimum viable sovereignty).** Keep a domestically hosted stack of the best available open-weight models, plus Singapore and Southeast Asian fine-tunes, on national compute. Run quarterly cut-off drills for critical services. Be explicitly model-agnostic. **Do not build a national frontier model.** Its kill criterion is in section 12.

**Measurement, guarded against Goodhart.** Always pair adoption metrics with output metrics, so that "used AI" never substitutes for "did more with it".

### Pillar 5: Talent with a political licence

**Top end.** Use the ONE Pass (AI and Tech) actively, not passively. A small headhunting unit should target about 500–1,000 frontier-grade people by 2029: applied-AI leads, packaging and photonics engineers, AI evaluators.

**Middle.** "AI bilingual" Singaporeans: domain experts with AI skills in the Mission sectors, through funded mid-career conversion with salary support.

**Base.** Universal AI literacy, and AI fluency built into the school curriculum.

**The political licence.**
- Make a local capability commitment (apprenticeships, research chairs, Singaporean leadership tracks) a standard part of every lab and anchor deal, following the pattern of OpenAI's S$300m.
- Publish annual data on Singaporeans' share of AI jobs and wages.
- Give the Tripartite Jobs Council a pilot of **wage insurance**: a time-limited top-up of part of the pay gap when an AI-displaced worker takes a lower-paid new job. This makes the transition visibly fair, at modest cost.

---

## 7. The Campaign

| Phase | Window | Aim | Signature moves |
|---|---|---|---|
| **0. Stabilise trust** | Now to February 2027 | Stop the downgrade spiral | Envoy; taskforce; accelerator census; Bill amendments; BIS comments by 18 January; every operator filed by 17 February |
| **1. Lock in access, launch the machine** | 2027 | Approved-entity arrangement; Delivery Unit running | Budget 2027 funding; ASEAN Compute Integrity Framework; ONE Pass (AI and Tech) recruitment; IAEA review; first cut-off drill |
| **2. Scale the dividend** | 2028–29 | Diffusion shows in productivity and wages | Mission outcomes published; Implementation Corps at scale; Kampong AI; Micron fab; nuclear decision in 2029 |
| **3. Lock in before the election** | 2029–30 | Make it durable | Statutory reporting; regime seen as Singapore's brand; constituencies in place |

**Why this order.** Trust comes first because the licence clock is running and political capital is highest right after the shock. It is also the only pillar where delay compounds against Singapore. Diffusion is the bigger prize, but it isn't time-critical in the same way, and it needs an apparatus that takes six months to build. Energy decisions have long lead times, so the nuclear option is bought now even though it is used later.

**Narrative by audience.**
- *Washington:* "Singapore is the safest channel for American AI in Asia."
- *Beijing:* "Rules, not sides. Open to all lawful business."
- *Industry:* "Certainty is the product."
- *Singaporeans:* "AI that raises your pay, not your power bill."
- *ASEAN:* "One standard that keeps the chips flowing to all of us."

**Handling the losers.**
- Grey-zone resellers: enforced out, without compensation.
- Operators with China-headquartered AI tenants: a time-limited transition, clarity on which workloads need licences, and support to re-tenant controlled capacity.
- SMEs: implementation done for them, not more grant forms.
- Displaced workers: wage insurance, Jobseeker Support and conversion programmes.
- Households: protected by data centres paying marginal cost.

---

## 8. Delivery Architecture

| Pillar | Accountable minister | Lead agencies | Instrument |
|---|---|---|---|
| Trusted Compute | One named minister (recommend the Minister for Digital Development and Information), plus a special envoy | IMDA, Customs, CSA, Commercial Affairs Department, MAS; MFA for the G2G track | Digital Infrastructure Bill amendments; G2G arrangement; taskforce |
| Hardware | Minister for Trade and Industry (Energy and Industry) | EDB, A*STAR, JTC, ITE and polytechnics | Conditional incentives; RIE2030 semiconductor flagship; compliance service |
| Power | Minister for Trade and Industry (Energy and Industry) | EMA, IMDA (data-centre allocation), JTC | DC-CFA scoring; tariff design; import offtake; nuclear programme |
| Diffusion | PM through the National AI Council; AI Delivery Unit in the PMO | IMDA, EnterpriseSG, GovTech, sector agencies | Missions; Implementation Corps; outcome-based grants |
| Talent and transition | Minister for Manpower, with NTUC and SNEF | MOM, SkillsFuture Singapore, EDB | ONE Pass (AI and Tech); Tripartite Jobs Council; wage-insurance pilot |

**Budget.** The compliance regime and taskforce cost tens of millions a year. The Implementation Corps and wage-insurance pilot cost low hundreds of millions over the term. All of this is small next to the S$37bn RIE2030 envelope and the S$1bn-plus national AI R&D plan. The expensive items are energy offtake guarantees and conditional semiconductor incentives, both already within normal EDB and EMA practice. These are orders of magnitude, not costings.

**Capacity gaps.** Compliance and forensic-audit skills for compute, which Customs has for goods but not at scale for GPUs. Technical evaluators. Implementation partners for SMEs. Close them by seconding staff from the Big Four and the hyperscalers' trust and safety teams, and by paying market rates for a small core.

**Pilot to scale.** Expect results to shrink at scale, as List's voltage effect predicts. Pilot the Implementation Corps in two sectors for six months before scaling, with pre-registered outcome metrics.

---

## 9. The Wargame

| Actor | Their goal | Their best move against us | Our counter | Second-order effect |
|---|---|---|---|---|
| **Washington** | No leakage; leverage | Keep Singapore listed to extract tariff or investment concessions; demand intrusive US inspections | A regime that makes approval the low-effort path; allies (hyperscalers, Nvidia, Micron) lobbying for us; inspections done jointly under Singapore law; an investment narrative using sovereign-fund exposure | If it works, Singapore becomes the regional reference model and Malaysia and Indonesia follow its standard |
| **Beijing** | Keep third-country compute; deter alignment | Quiet economic signalling; steer Chinese firms' regional HQs to Hong Kong or Kuala Lumpur; frame Singapore as a US proxy | Non-discriminatory rules; visible welcome for Chinese firms' non-controlled business; senior-level diplomacy; the ASEAN chair's convening role | Some China-headquartered AI compute leaves (accepted cost); gateway functions mostly stay |
| **Malaysia** | Data-centre investment; off the list | Move faster with its own regime and court the hyperscalers' next Asian builds | Offer the joint JS-SEZ standard first; turn the competition into a shared ring | Johor becomes Singapore's verified overflow rather than its rival |
| **Grey-zone intermediaries** | Keep arbitrage | Re-domicile, layer entities, argue "over-regulation" | Ultimate-parent KYC; Customs reconciliation; publish enforcement | They leave, which is the point |
| **US policy whiplash** (2028–29) | — | A new administration loosens or tightens sharply | The regime has value either way: tighter rules mean Singapore is already compliant; looser rules mean the trust brand still sells | Durability doesn't depend on any one US administration |
| **Domestic critics** | Accountability | "Doing America's bidding"; "data centres eat our power"; "jobs for foreigners" | Sovereignty framing (Singapore law, the Dutch precedent); marginal-cost energy pricing; published talent and wage data; wage insurance | Openness keeps its licence |

**Three months.** Licences filed, the census complete, the Bill amended, and a G2G proposal on the table. Expect friction from China-headquartered tenants, and a scare story or two in the region's press.

**Three years.** The approved-entity arrangement is in place. Johor and Batam are inside a shared standard. Diffusion metrics are visible in two or three Mission sectors, and the nuclear decision is due.

**Ten years.** Singapore is to AI compute what it became to finance after 2016: the jurisdiction the system trusts. It is not the biggest. It is the one others route through. The open question is whether a parallel Chinese stack becomes globally competitive. Model-layer openness is the hedge that keeps Singapore relevant to both.

---

## 10. Pre-Mortem and Red Team

**Failure story 1: licensed into irrelevance.** It's 2031. Singapore treated the rule as a PR problem. It defended its sovereignty on principle and delayed the Bill amendments for a year of industry consultation. Approvals stayed slow, and hyperscalers sited Asian AI build-outs in Japan, India and Australia. The labs kept sales teams in Singapore, not compute. *Countered by:* speed in Phase 0, and the Bill as the vehicle.

**Failure story 2: squeezed from both sides.** Singapore over-rotated into public alignment with Washington. Beijing responded quietly and Chinese gateway firms moved to Hong Kong. Then the 2029 US administration loosened China policy, and the sacrifice looked pointless. *Countered by:* keeping alignment technical (chokepoints only), not rhetorical; non-discriminatory rules; and a regime whose value doesn't depend on US policy direction.

**Failure story 3: a hub without a dividend.** Singapore won the hub game: licences, packaging plants, lab offices. But SME adoption stalled around 35% and the gains went to MNCs and foreign talent. Graduate retrenchments rose, and the 2030 election turned on foreign talent and electricity prices. Openness was rolled back. *Countered by:* the Delivery Unit, output metrics, wage insurance and published distribution data.

**Failure story 4: the power wall.** Import corridors slipped, as Wood Mackenzie predicted. A gas price spike hit households, data centres became a political target, and the nuclear decision was deferred again. Inference demand left for Johor without a shared standard. *Countered by:* marginal-cost pricing, the cap, government offtake for first corridors, and a fixed nuclear decision date.

**The opposition's strongest case.** "The government is outsourcing Singapore's sovereignty to Washington's export-control bureaucracy. It is accepting a rule that exempts American firms and penalises Singaporean ones, and calling it trust. It will alienate our largest trading partner for chips we could buy elsewhere in five years. Meanwhile ordinary Singaporeans get higher power bills and more foreign competition for jobs." Parts of this are true. The rule *is* asymmetric. The answer is not that the critique is wrong. It is that the alternative is worse, and that the design limits the cost. The approved-entity ask exists precisely to remove the asymmetry for Singaporean operators.

**The three classic attacks (Hirschman):**
- *Perversity* ("strict compliance drives business away"). The business at risk is the business that cannot pass verification. Legitimate volume needs the licence, and the licence needs the regime.
- *Futility* ("a small state can't move US policy"). The rule's own text names regime effectiveness as a factor. The UAE was upgraded in July 2026. Singapore makes one in ten of the world's chips and will package HBM for American accelerators.
- *Jeopardy* ("this endangers sovereignty and neutrality"). Singapore didn't lose sovereignty by meeting FATF standards or closing BSI. It gained credibility. Sovereignty is exercised by writing Singapore's own law, as the Dutch did.

---

## 11. Durability

**Lock-in mechanisms.**
- *Statute, not circulars.* The compute-integrity regime sits in the Digital Infrastructure Act with an annual public enforcement report, which makes quiet backsliding visible.
- *Agency-level G2G arrangements* (BIS and Customs, AI testing institute and lab partners) rather than leader-level understandings, so they survive changes of administration in Washington and of personnel in Singapore.
- *A regional standard* through the ASEAN framework: once neighbours adopt it, Singapore's regime is the reference model, and abandoning it costs everyone.

**Constituencies the policy creates.** Approved operators and their customers, who would lose the most if trust lapsed. Anchor semiconductor firms with conditional incentives. SMEs using shared tools. Workers covered by wage insurance. Each is a defender with a concrete stake: the policy-feedback logic of Pierson and Patashnik.

**The long view.** This locks Singapore into the American hardware ecosystem for frontier compute for a decade or more. That is the core trade-off. Openness at the model, talent and capital layers is the hedge if a Chinese stack becomes globally competitive. Revisit the question explicitly in 2029.

---

## 12. The Dashboard

| Indicator | Type | Baseline | Target | Tripwire → pre-agreed response |
|---|---|---|---|---|
| Median BIS licence decision time and approval rate for Singapore applicants | Leading | New (Nov 2026) | Under 60 days; over 90% by end-2027 | Over 120 days or under 70% approval by June 2027 → leader-level escalation; move government workloads to US-headquartered hosts while talks continue |
| Status of the G2G Trusted Compute Arrangement | Milestone | None | Signed by end-2027 | No movement by Q3 2027 → revise the offer (joint inspections, investment framing) |
| Accelerator census: unexplained gap between imports and installed hardware | Leading | To be measured in December 2026 | Under 1% | Any facility over 5% → immediate audit and licence suspension |
| Published enforcement actions | Leading | — | Annual report | US alleges new cases with no Singapore action → independent review of the taskforce |
| Net regional HQ moves by Chinese firms | Leading | — | Roughly neutral | Three or more major exits in six months → senior engagement with Beijing and a reassurance package |
| Data-centre share of electricity; value per MW | Lagging | Over 7% | 12% or less by 2030; value per MW rising | Over 10% before 2028 → pause allocations except value-scored ones |
| Import corridors at financial close | Leading | 0 of 9.25GW | 2 or more by end-2028 | None by end-2027 → government offtake or guarantee; accelerate nuclear work |
| IAEA review; nuclear decision | Milestone | Preparing | Review 2027; decision 2029 | More than 12 months' slip → ministerial review |
| SMEs using AI in a core process | Leading | ~23% any-AI use (2025) | 50% or more by 2030 | Under 30% by end-2027 → redesign the SME programme |
| Productivity growth in Mission sectors | Lagging | Set in Q1 2027 | At least 3% a year | Below trend for two years → reset the mission and its owner |
| Real median wage growth | Lagging | — | At least 2% a year | Below 1% for two years alongside rising productivity → distribution review |
| Degree-holder retrenchment rate; six-month re-employment | Leading | 3.1 per 1,000 (Q1 2026) | Re-employment of 70% or more | Above 4 per 1,000 for two quarters → scale wage insurance |
| ONE Pass (AI and Tech) holders; retention; local hires per holder | Leading | 0 | 500 or more by 2028, 1,000 by 2029; retention over 80% | Uptake under 50% of target → review package and recruitment |
| Sovereign fallback drill | Milestone | None | Quarterly; 90 days sustained | Failed drill → funded fix within one quarter |
| Micron HBM ramp; new packaging and photonics anchors | Lagging | Under construction | Output early 2027; 2 or more anchors by 2028 | Slippage → workforce and supplier intervention |

**Review cadence.** Monthly Delivery Unit stocktake with the PM. Quarterly National AI Council review. An annual published "State of AI Singapore" report covering outcomes, not activities.

**Kill criteria.**
- Any proposal for a national frontier model is rejected unless the national compute budget exceeds frontier-cluster scale, which it will not.
- Semiconductor incentives that miss output milestones two years running are clawed back.
- Mission programmes with no measurable output gain after 24 months are closed or re-scoped.

---

## 13. The First 100 Days (from 30 November 2026)

| When | Action | Owner |
|---|---|---|
| **Week 1** | Emergency session of the National AI Council. Name the accountable minister and the special envoy to Washington. Announce compute-integrity amendments and the Joint Compute Integrity Taskforce. Brief Beijing and Kuala Lumpur privately first. | PM; MDDI; MFA |
| **Weeks 2–4** | Taskforce opens a voluntary-disclosure window and starts the accelerator census for all facilities of 10MW or more. Open the licensing clinic, prioritising Singapore-headquartered operators. Draft the Trusted Compute Arrangement and recruit supporting comments from hyperscalers, Nvidia and Micron. Give a public timeline update on Megaspeed, consistent with due process. | Customs; IMDA; EDB; envoy |
| **By 10 January** | Scenario plans for expiry of the US–China truce: extension, lapse, escalation. | METI; MFA |
| **January** | ASEAN chair begins; table a compute-integrity workstream at the first senior officials' meeting. Propose the joint JS-SEZ verification standard to Malaysia. | MFA; MDDI; METI |
| **By 18 January** | Formal comments to BIS, with the G2G proposal delivered in parallel. | Envoy; MDDI; METI |
| **Late January** | ONE Pass (AI and Tech) opens; the headhunting unit begins targeted outreach. Second Reading of the Digital Infrastructure Bill with the compute-integrity part. | MOM; EDB; MDDI |
| **February** | Budget 2027 funds the Delivery Unit, the Implementation Corps pilots, import-corridor support, pre-decision nuclear work and the wage-insurance pilot. Committee of Supply publishes the Council's five priorities and their metrics. | MOF; PMO |
| **By 17 February** | Every existing operator has filed licence applications; daily tracking of the approval pipeline. | IMDA; taskforce |
| **March** | First Delivery Unit stocktake with the PM. First sovereign cut-off drill. EMA publishes the date of the IAEA review and the 2029 decision commitment. Wage-insurance pilot design agreed with the Tripartite Jobs Council. | PMO; GovTech; EMA; MOM |

---

## 14. Confidence and Open Questions

**What we know.** The text of the November rule, its deadlines and its licence factors. Singapore's legal stance. Its energy dependence and the slipping import pipeline. The adoption gap. The existence of the UAE approved-entity template. The Digital Infrastructure Bill as an available vehicle.

**What we assume.** That Washington will in practice reward a credible regime, as the rule's text and the UAE precedent suggest, rather than using the listing purely as leverage. That Beijing's interest in Singapore as a gateway outweighs its irritation at technical compliance. That Singapore-headquartered operators can absorb the compliance costs.

**What is judgement.** Every odds figure. The 12% power cap. The talent and diffusion targets. The cost orders of magnitude.

**What would change the recommendation.**
- If Washington signals that removal from the list depends on concessions unrelated to diversion, such as tariffs or exclusivity against Chinese firms, Pillar 1 shifts. Singapore would accept a US-headquartered-hosted model for sensitive compute, accelerate the sovereign fallback and the Johor ring, and refuse demands for exclusivity.
- If Beijing retaliates materially, slow the rhetoric, not the regime.
- If Washington opens allied access to restricted frontier models for evaluated partners, upgrade the AI testing institute into a central asset.
- If SMR technology matures faster than expected, bring the nuclear decision forward.
- If AI capital spending turns down sharply, protect Pillar 4 and slow Pillars 2 and 3. Diffusion is the counter-cyclical asset.

**Open questions for the principal.** How much China friction are you prepared to absorb for guaranteed compute access? And do you want the power cap stated publicly, which makes it credible but is a hostage to fortune, or held as internal policy?

---

## 15. The Statecraft Lesson

In a world of weaponised chokepoints, small states don't escape great-power rivalry by being neutral. They escape it by being indispensable and verifiable. Neutrality is a posture the great powers can ignore. Verifiability is an asset they must price. Switzerland learned this between 2009 and 2017, when bank secrecy collapsed and the banking centre survived only by becoming auditable. Singapore's own finance hub learned it in 2016, when shutting BSI cost a bank and bought a reputation. The pattern will recur wherever a hegemon controls a critical input: the hub that converts trust from a claim into infrastructure keeps its place.

**A question to sit with:** if a future US administration flips policy again in 2029, which part of this strategy still pays off, and is that the part you should be building first?

---

## Sources

- MDDI, [Update to Singapore's National AI Strategy (factsheet), 20 May 2026](https://mddi.gov.sg/newsroom/update-to-singapore-s-national-ai-strategy--refreshed-priorities-to-harness-ai-for-the-public-good-factsheet)
- ComputerWeekly, [Singapore to form National AI Council, expands tax breaks](https://www.computerweekly.com/news/366638920/Singapore-to-form-National-AI-Council-expands-tax-breaks-to-ease-AI-adoption)
- Hogan Lovells, [BIS issues new controls targeting remote access to advanced US computing power](https://hlc.com/en/publications/bis-issues-new-controls-targeting-remote-access-to-advanced-us-computing-power)
- Steptoe, [BIS targets data center remote access and imposes steeper requirements on foundries and OSATs](https://www.steptoe.com/en/news-publications/international-compliance-blog/bis-targets-data-center-remote-access-and-imposes-steeper-requirements-on-foundries-and-osats.html)
- BIS, [Rule addressing remote access to American super intelligence technology, 16 Nov 2026](https://bis.gov/press-release/bis-issues-rule-addressing-remote-access-american-super-intelligence-technology)
- Fortune, [US AI chip controls hit Southeast Asia, 17 Nov 2026](https://fortune.com/2026/11/17/sg-us-ai-chip-controls-southeast-asia/)
- SCMP, [US details criminal probe of Nvidia customer Megaspeed](https://scmp.com/tech/tech-war/article/3374742/us-details-criminal-probe-nvidia-customer-megaspeed-over-potential-chip-diversion)
- The Standard, [Singapore in damage control after Nvidia scandal](https://www.thestandard.com.hk/world/article/348776/Singapore-in-damage-control-after-Nvidia-scandal-exposes-China-loophole)
- Let's Data Science, [Singapore seeks "trusted access" after new US curbs](https://letsdatascience.com/news/singapore-seeks-trusted-access-to-ai-chips-after-new-us-curb-c1cf0c3b); ANN, [Teo on trusted access](https://asianews.network/?p=315540)
- e27, [A 750-chip ceiling: how US curbs redraw the map for Malaysia's AI data centres](https://e27.co/a-750-chip-ceiling-how-us-curbs-redraw-the-map-for-malaysias-ai-data-centres-20261118/)
- METI, [Oral reply on Singapore's approach to export controls, Feb 2025](https://www.meti.gov.sg/newsroom/oral-reply-to-pqs-on-singapore-s-approach-to-export-controls/)
- Morgan Lewis, [BIS upgrades UAE export control status, July 2026](https://www.morganlewis.com/ru/pubs/2026/07/bis-upgrades-uae-export-control-status-with-ai-chip-access-limited-to-approved-entities)
- Fortune, [Why Singapore is the only Southeast Asian country in Pax Silica](https://fortune.com/2025/12/30/why-singapore-is-the-only-southeast-asian-country-in-pax-silica-ai/); ITIF, [Pax Silica timeline](https://itif.org/publications/2026/11/16/pax-silica-timeline/)
- Al Jazeera, [US orders Anthropic to disable AI models for all foreign nationals](https://www.aljazeera.com/economy/2026/6/14/us-orders-anthropic-to-disable-ai-models-for-all-foreign-nationals); Bloomberg Government, [US limits on Mythos keep foreign firms in limbo](https://news.bgov.com/bloomberg-government-news/us-limits-on-anthropics-mythos-keep-foreign-firms-in-limbo-1)
- TechNode Global, [GIC, Temasek anchor Singapore's investment in Anthropic's Series H](https://technode.global/2026/05/29/gic-temasek-anchor-singapores-investment-in-anthropics-65b-series-h-round/)
- METI, [2026 GDP forecast upgraded to 4.5–5.5%](https://www.meti.gov.sg/newsroom/mti-upgrades-2026-gdp-growth-forecast-to--4-5-to-5-5-per-cent-/)
- EDB, [SG Semiconductor](https://www.edb.gov.sg/en/news-and-insights/singapore-announces-sg-semiconductor-to-strengthen-its-role-in-the-global-semiconductor-ecosystem); The Star/Bernama, [Micron's Singapore investments](https://www.thestar.com.my/aseanplus/aseanplus-news/2026/11/07/micron-strengthens-singapore-footprint-with-us24bil-investment-in-ai-driven-manufacturing)
- EDB, [Green Data Centre Roadmap, May 2024](https://www.edb.gov.sg/en/news-and-insights/singapore-to-expand-data-centre-capacity-by-at-least-one-third-pushes-for-green-energy-use); King & Wood Mallesons, [DC-CFA2](https://www.mallesons.com/content/mallesons/sg/en/insights/latest-thinking/singapore-launches-200mw-data-centre-call-for-application-dc-cfa2); EDB, [DC-CFA2 selections, Aug 2026](https://www.edb.gov.sg/en/about-edb/media-releases-publications/four-data-centre-proposals-selected-as-part-of-second-data-centre.html)
- NSCC, [ASPIRE 2B](https://www.nscc.sg/portfolio/item/nsccs-aspire-2b-debuts-at-rank-44-and-184-on-top500-list/)
- NST/Reuters, [Singapore set to miss 2035 green-power import target](https://www.nst.com.my/amp/business/economy/2026/10/1550070/singapore-set-miss-2035-green-power-import-target)
- Malay Mail, [Singapore eyes nuclear shift](https://www.malaymail.com/news/singapore/2026/03/03/singapore-eyes-nuclear-shift-as-energy-crunch-turns-existential-parliament-told/211157); EMA, [Assessing advanced nuclear](https://ema.gov.sg/news-events/news/feature-stories/2026/understanding-advanced-nuclear-energy-technologies-how-singapore-is-assessing-its-potential)
- Mothership, [MTI renamed Ministry of Energy, Trade and Industry](https://mothership.sg/2026/07/ministry-energy-trade-industry-new-name/)
- People Matters/IMDA, [AI adoption rises to 23.5%](https://sea.peoplemattersglobal.com/news/ai-and-emerging-tech/singapore-ai-adoption-rises-to-235percent-as-digital-economy-reaches-dollar1441bn-52560)
- The Star/ST, [More retrenchments in Q1 2026](https://www.thestar.com.my/aseanplus/aseanplus-news/2026/06/15/more-retrenchments-in-singapore-in-q1-2026-as-job-vacancies-drop); MOM, [Tripartite Jobs Council](https://mom.gov.sg/newsroom/press-releases/2026/0430-formation-of-tripartite-jobs-council)
- Singapore Global Network, [2026 talent policy changes](https://singaporeglobalnetwork.gov.sg/stories/business/explained-singapores-2026-global-talent-policy-changes-and-why-it-works-in-favour-of-top-talent/)
- Fortune, [US and Chinese AI firms set up Singapore offices](https://fortune.com/2026/06/19/us-china-ai-firms-set-up-singapore-offices-neutral-hub/); eWeek, [Anthropic's Singapore office and MoU](https://www.eweek.com/news/anthropic-apac-singapore-office-ai-safety-deal/)
- MDDI, [Digital Infrastructure Bill](https://www.mddi.gov.sg/newsroom/new-digital-infrastructure-bill-to-strengthen-the-foundations-for-singapore-s-digital-economy/)
- AF.net/AsiaOne, [Wong proposes international AI incident-reporting pilot](https://af.net/realtime/singapore-pm-lawrence-wong-proposes-international-ai-incident-reporting-pilot/); ANN, [Singapore joins call for control of frontier AI](https://asianews.network/?p=302935)
- Cyprus Mail (opinion), [Trump–Xi meeting kicked the can down the road](https://cyprus-mail.com/2026/10/18/trump-xi-meeting-just-kicked-can-down-the-road)
- White & Case, [Section 232 tariff on certain advanced semiconductors, Jan 2026](https://www.whitecase.com/insight-alert/president-trump-orders-narrowly-targeted-25-section-232-tariff-certain-advanced); METI, [Oral reply on new US tariffs, Mar 2026](https://www.meti.gov.sg/newsroom/oral-reply-to-pqs-on-updated-assessment-on-impact-on-singapore-s-economy-and-businesses-from-new-15--tariffs/)
- NST, [Tighter US chip rules cloud Malaysia's data-centre outlook](https://www.nst.com.my/amp/business/economy/2026/11/1580155/tighter-us-chip-rules-cloud-malaysias-data-centre-outlook-watch)
