# High-Quality Literature Anchoring Protocol

Use verified high-quality literature to anchor major scientific decisions without treating journal prestige as scientific authority. The governing chain is:

**scientific object / decision → relevant literature role → verified source → generalizable logic → design-fit check → adaptation → residual contribution → evidence requirement**

Literature informs the question, construct, design, method, threat map, and exposition. It does not replace the paper's own evidence, establish identification, authorize a method, or change a frozen object.

## Source roles

Classify a source by the job it performs. Do not require every citation to be Q1/Q2.

1. **VERIFIED Q1/Q2 BENCHMARK:** a primary benchmark for the scientific conversation, closest published literature, construct or empirical architecture, field convention, or paper architecture. Unless the PI specifies another system, “SCIE / SSCI Q1/Q2” means an SCIE or SSCI journal classified as JCR Q1 or Q2 in a scientifically relevant category for a declared JCR year.
2. **CANONICAL METHODOLOGICAL SOURCE:** foundational econometric, statistical, identification, inference, diagnostic, book, or authoritative methodological work. Current JCR classification may be inapplicable and is not required.
3. **FRONTIER WORKING PAPER:** current competition or emerging method from sources such as NBER, CEPR, IZA, SSRN, an institution, or an author. Label it `WORKING PAPER`; do not represent it as a published Q1/Q2 article.
4. **OFFICIAL / PRIMARY SOURCE:** policy, law, institutional rule, administrative timing, official data definition, or database documentation. Journal prestige is irrelevant to this factual role.
5. **HIGH-LEVEL CHINESE LITERATURE:** supports Chinese institutional context, domestic debate, China-specific constructs, mechanisms, or policy relevance. For an SSCI Q2+ project, it normally complements rather than fully replaces relevant international high-quality benchmarks.
6. **DISCOVERY-ONLY SOURCE:** a lower-tier article, thesis, blog, aggregator, unverified summary, or AI-generated list used to find stronger sources. It is not the sole anchor for a central scientific decision when stronger primary or high-quality evidence exists.

Source role is not a quality score. Citation count and journal quartile do not substitute for relevance, full-text support, design fit, or accurate interpretation.

## Q1/Q2 verification

For each source counted as a `VERIFIED Q1/Q2 BENCHMARK`, record:

- title, authors, year, journal, and DOI or stable identifier;
- index: `SCIE`, `SSCI`, `BOTH`, or `OTHER`;
- ranking system, normally `JCR` for a formal PERW Q1/Q2 claim;
- JCR year, scientifically relevant category, and quartile;
- verification source and verification date;
- full-text status: `FULL TEXT`, `PARTIAL`, or `ABSTRACT ONLY`;
- citation verification: `YES` or `NO`.

Never silently mix JCR quartiles, SJR quartiles, CiteScore percentiles, CAS / 中科院分区, or an arbitrary website ranking. If another system is used, name it explicitly and do not relabel it as JCR. A journal may have different JCR quartiles in different categories; record the relevant categories where practical, or state the chosen category and its scientific relevance. Do not select an unrelated category merely to obtain a better quartile.

Journal rankings are time-varying. For “currently Q1/Q2,” use the latest JCR year that can be verified. For “Q1/Q2 when published,” verify the publication-year or appropriate historical JCR before stating it. Never treat a quartile as a permanent journal attribute.

Use ranking states:

- `VERIFIED`: authoritative evidence supports the recorded system, year, category, and quartile;
- `PROVISIONAL`: metadata guide discovery but a material ranking claim remains unresolved;
- `UNVERIFIED`: the ranking has not been established.

When authoritative ranking access is unavailable, do not fabricate or infer the quartile from another system. Record authoritative journal metadata that can be verified and follow existing data/access handoff logic if exact ranking is materially required.

## Benchmark set and coverage

An SSCI Q2+ empirical project should normally maintain a verified high-quality benchmark set when relevant literature exists. Working papers, reviews, domestic papers, discovery sources, and journal homepages may complement it but cannot alone satisfy the published international benchmark role.

Do not impose fixed counts such as 40 papers, ten Q1 papers, or five closest papers. Sufficiency is based on coverage. As relevant, cover seminal foundations, current frontier, the closest published paper, working-paper competition, construct and measurement, method and identification, mechanisms and rivals, and target-field publication exemplars.

## Major decision anchoring

For a materially important decision, identify the literature role and design-fit implication where relevant:

- **Core Question / closest paper:** establish the scientific conversation, unresolved problem, strongest novelty threat, and residual contribution.
- **Construct / measurement:** verify definitions, operationalization, validation, and known limits.
- **Claim Type / Evidence Architecture / identification:** establish what evidence and assumptions the intended claim normally requires.
- **Estimator / inference / robustness:** use canonical or high-quality methodological sources that fit the actual design and named threat.
- **Mechanism / rival / heterogeneity:** anchor the theory and dimension before examining favorable results.
- **Publication architecture:** use verified strong papers to learn exhibit functions, result ordering, and writing architecture without copying paper-specific design or prose.

Trivial software, formatting, or mechanical implementation choices do not require a literature anchor.

## Literature-to-design translation

For every major borrowed architecture, answer:

1. What scientific logic can generalize?
2. What is setting-specific?
3. Why does the logic fit or not fit this Claim Type and Evidence Architecture?
4. What is adapted rather than copied?
5. What residual scientific contribution remains after the closest-paper comparison?
6. What additional evidence does the adaptation require?

Reject **benchmark paper → copy method → change country/year/sample → claim novelty**. Publication prestige does not make a method valid, and a successful design elsewhere does not establish support, identification, or contribution here.

## Closest-paper and frontier discipline

Search adversarially for the paper most capable of reducing novelty, not a weak comparator that makes the contribution look larger. For each serious competitor record its question, population/geography, construct, data, Claim Type, Evidence Architecture, identification when applicable, findings, mechanisms, and remaining gap. Judge residual contribution only after this comparison.

For important anchor papers, use backward citations, forward citations, related/co-citation networks, competing literature clusters, and frontier working papers when they materially improve coverage. Citation topology is optional and targeted, not mandatory overhead. Citation count alone is not a quality rule; recent or low-citation work may be central.

Use bilingual discovery when the scientific setting requires it: search English and Chinese concepts, policy names, construct synonyms, and institutional terms for China-related work, while applying the same source-role and verification rules to the results.

## Multidimensional novelty collision and literature adversary

High-quality literature is used to **attack novelty, calibrate claims, and improve design**, not to **assimilate the project into the closest paper**. For every serious closest paper ask both: **WHAT DOES THIS PAPER OCCUPY?** and **WHAT SCIENTIFIC OBJECT DOES IT NOT OCCUPY?** Compare with the genesis anchor and current branch fingerprint under `protocols/research_genesis_branch_governance.md`; a nearby literature must not silently redefine the original question. Explicit evidence-based repair, rejection, or replacement remains legitimate.

Record overlap and difference, source evidence, uncertainty, and implications separately across:

| Dimension | Audit question |
|---|---|
| TOPIC ADJACENCY | Is the subject nearby without answering the same question? |
| MECHANISM-FAMILY ADJACENCY | Is only the general mechanism family shared, or is the central mechanism claim already answered? |
| CONSTRUCT / MEASUREMENT OVERLAP | Are the concept, operationalization, or proposed measurement contribution already occupied? |
| SCIENTIFIC-OBJECT / OUTCOME-POPULATION OVERLAP | Are the actor, affected population, outcome population, and relation the same? |
| SCIENTIFIC-QUESTION OVERLAP | Does the paper answer essentially the same Core Question? |
| CLAIM OVERLAP | Does it establish the intended scientific statement? |
| EVIDENCE-ARCHITECTURE / IDENTIFICATION OVERLAP | Does it provide the relevant evidence and, when needed, identification for that statement? |
| SETTING / INSTITUTIONAL OVERLAP | Is the institutional variation or setting-specific learning already occupied? |
| CONTRIBUTION COLLISION | After all differences are considered, what defensible residual contribution remains? |

Conclude qualitatively: ADJACENT / PARTIAL COLLISION / SUBSTANTIAL COLLISION / NEAR-DUPLICATE, with a rationale and unresolved facts. No weighted score, universal mathematical formula, or automatic decision. These labels document the existing Competition / Contribution Gate comparison; they do not change its criteria or replace GO / GO WITH REPAIR / HOLD / NO-GO.

High topic similarity or general mechanism-family similarity alone is not proof that the contribution is occupied. Conversely, a different estimator does not protect novelty if a paper already answers essentially the same scientific question for the same scientific object with the relevant evidence. The strongest threat usually comes from joint overlap in question, focal/outcome population, claim, construct, required evidence, and contribution. Any dimension may matter in context: do not restrict novelty threats exclusively to claim or Evidence Architecture overlap. A construct, measurement, or institutional contribution can collide on its own scientific terms. Neither adjacency nor an unoccupied object automatically establishes scientific value or novelty.

## Full text, citations, and writing boundary

Abstract-only reading is normally insufficient when a paper justifies a construct, identification strategy, estimator, mechanism, robustness procedure, or paper-architecture claim. Prefer full text and label any limitation. Do not state that a paper uses a method or supports a claim unless the source actually does so. Whenever practical, verify the original source rather than relying on a secondary citation.

Short quotations may be stored for verification within applicable limits. They are not manuscript-ready prose. Manuscript synthesis must be independently written, accurately attributed, and citation-verified; do not patch together source sentences.

## Stage integration and maintenance

Preserve independent scientific divergence at Stage 1. Use literature anchoring after an initial idea set to map the frontier, revise divergence, and then proceed to feasibility screening. Before expensive commitment or Stage 4–5 freeze, the Research Director should normally know the verified benchmark set, serious closest papers, frontier competition, construct/measurement anchors, applicable method anchors, and residual contribution.

At Stages 6–10, a material new estimator, inference method, robustness test, mechanism, rival test, heterogeneity dimension, or construct variation requires a scientific job, appropriate literature anchor, frozen-design fit, named threat or assumption, and incremental information check before `protocols/method_runtime_readiness.md` where applicable.

Before submission readiness, refresh the closest-literature and frontier search if material time has passed or the field has moved. Verify central literature claims, source identity, publication status, DOI, method/theory citations, and every formal Q1/Q2 claim.
