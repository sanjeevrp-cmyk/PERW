# Early Data Feasibility / Observability Screen

## Purpose and boundary

Use this protocol in the later part of Stage 1 and during Stage 2 before a promising candidate receives expensive literature, design, or data-engineering effort. It is a **pre-Gate screen and research-effort allocation tool**, not a second Data / Measurement Gate. It does not establish construct validity, pass Stage 3, or change GO / HOLD / NO-GO standards.

The question comes first. A project must be scientifically worth studying before data feasibility matters. Data availability does not establish importance, contribution, or journal potential; construct difficulty does not establish novelty. The screen asks only how much additional effort is justified before feasibility is verified.

## Evidence chain

Record the following chain for every screened candidate:

**Scientific Question → Claim Type → Required Evidence → Observable Evidence → Missing Evidence → Feasibility Risk → Cheapest Feasibility Test → Development Decision**

- **Required Evidence:** what would be needed for the scientific claim to be credible, stated before checking convenience.
- **Observable Evidence:** what the team can currently obtain lawfully and construct reliably.
- **Missing Evidence:** the gap between required and observable evidence.

A variable name in a database is not evidence of construct validity.

## Screen

1. **Core X / key construct and primary evidence.** Classify each separately as:
   - `DIRECT`: structured and closely aligned with the scientific object;
   - `DERIVED`: a transparent, verifiable ordinary construction;
   - `RECONSTRUCTED`: dependent on complex rules, multiple sources, or historical relationships;
   - `MANUAL`: dependent on substantial human reading, classification, or adjudication;
   - `UNKNOWN`: not yet verified.
2. **Unit, identifier, time, and geography.** Record the observational unit, entity ID, time index, geography, event date, and panel support. Distinguish a direct-key join from entity resolution, fuzzy matching, or historical matching.
3. **Critical data layers.** List the layers on which the scientific object depends, such as firm, city, transaction, ownership, person, geography, policy, text, or network. Source count alone is not risk; dependence on several layers all being joined correctly is.
4. **Historical reconstruction.** Identify any required recovery of historical ownership, control, address, identity, policy status, event history, group affiliation, business relationship, or other state. Raise risk when a core object depends on it.
5. **Manual judgment.** Estimate the scale of document reading, PDF coding, ambiguous classification, adjudication, and unresolved cases. For material manual coding, cheaply test the coding rule, inter-rater feasibility when relevant, expected adjudication rate, and scalability.
6. **Construct burden.** Count the core scientific objects being built for the first time. Treat simultaneous unverified construction of treatment, outcome, network, and mechanism measures as a concentration risk.
7. **Expected support.** Use the cheapest proportionate evidence—bounded schema/missingness inspection, support count, identifier audit, pilot extraction, or small representative audit—to estimate observable rate, usable sample support, event support where relevant, match rate, ambiguity, and missingness. This precedes confirmatory modeling and must not be presented as such. Do not impose a universal sample-size threshold.
8. **Access states.** Following `protocols/data_access_handoff.md`, record `SOURCE EXISTS`, `TEAM ACCESS`, `EXECUTOR ACCESS`, `DELIVERY STATUS`, and `VALIDATION STATUS` separately. Executor access failure is not team-level unavailability or scientific failure.
9. **Failure locality.** Classify a data-source or construct failure as `LOCAL` when it removes only a secondary mechanism, robustness check, or extension, and `CORE` when it defeats the Primary Claim, core X, primary evidence, or Core Question. Identify architectures with a core single point of failure.
10. **Cheapest feasibility test.** Name the smallest test that answers “is expensive data engineering justified?” It need not answer the paper's scientific question.

## Qualitative Data Risk

Record `DATA RISK: LOW / MEDIUM / HIGH / UNKNOWN` with a short rationale. Do not calculate a weighted total or use Data Risk as a publication-quality score.

- `LOW`: core X and primary evidence are structured; identifiers and time align naturally; joins and derivations are ordinary; no core historical reconstruction or large manual classification is required.
- `MEDIUM`: a key construct, complex match, moderate text extraction, or moderate spatial/network construction is required, but a cheap audit can establish scalability early.
- `HIGH`: several risks combine, such as novel treatment or outcome reconstruction, multiple entity-resolution layers, historical state recovery, heavy adjudication, sparse support, reliance on unverified/proprietary data, several new core objects, or a claim that requires every layer to succeed.
- `UNKNOWN`: evidence is insufficient even for a reasoned qualitative classification.

`HIGH` is not automatic NO-GO; it requires stronger cheap feasibility evidence before expensive commitment. `LOW` is not automatic GO; scientific value, contribution, and formal Gates remain separate.

## Development and portfolio use

Record a reasoned next step: continue candidate development, run a bounded feasibility test first, defer pending a named capability or source, or remove the candidate from the current shortlist. This is a resource-allocation decision, not a scientific-validity Gate decision.

When the PI values stable paper output, show scientific upside—including what is learned from null or contradictory outcomes—Data Risk, workload, and cheapest feasibility evidence together. Maintain risk heterogeneity when practical; do not require fixed counts of LOW, MEDIUM, or HIGH candidates. Avoid a shortlist in which every candidate depends on the same unverified high-risk construction.

An early pilot that looks feasible still must pass the formal Stage 3 Data / Measurement Gate. A failed early test may redirect or defer development, but it does not silently redefine the Core Question or replace existing Stop / Reopen rules.
