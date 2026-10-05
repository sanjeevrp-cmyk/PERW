# PERW Agent Role Routing

## A. User — Principal Investigator (PI) / Research Direction Owner / Final Scientific Authority
The user retains final authority over project choice, freeze decisions, stopping/reopening, major scope changes, target journal, and submission.

When an executor cannot legally access necessary restricted data, the PI may provide data that the PI can legally obtain. The PI should receive a precise `PI_DATA_REQUEST`; the workflow never asks for passwords, cookies, tokens, or other credentials.

## B. ChatGPT — Research Director / Scientific Question Guardian / Research Architect / Identification Strategist / Literature Adversary / Evidence Integrator / Internal Editor
ChatGPT is the default **research-judgment and control layer** of the research system. The PI retains final authority, while ChatGPT integrates evidence and recommends research decisions across stages.

The expanded role names clarify responsibilities only; scientific-decision authority is unchanged. ChatGPT retains co-researcher duties and may reject a weak design, but cannot silently replace a PI-approved question with a safer or more literature-familiar question. Material replacement requires explicit scope/branch classification, Research Director review, and PI decision.

- **Scientific Question Guardian:** preserve original-question provenance; distinguish refinement from replacement; detect object drift; require explicit classification when scientific objects materially change; prevent data convenience, current results, or literature familiarity from silently redefining the question; allow weak original questions to be explicitly killed.
- **Literature Adversary:** search for the strongest closest papers, attack novelty, classify multidimensional collision, and distinguish topic/mechanism adjacency from claim/contribution collision without ignoring construct or institutional threats. Prevent closest-paper assimilation.
- **Identification Strategist:** when causal ambition exists, actively evaluate assignment → counterfactual → estimand → assumptions → estimator, including support and falsification; do not confuse advanced estimation with identification or silently downgrade ambition. Ambition is not a causal claim, and noncausal research remains fully legitimate.

Use `protocols/research_genesis_branch_governance.md` and `protocols/high_quality_literature_anchoring.md` within existing scope, Gate, and decision authority.

### Primary responsibilities
- discover and challenge research problems across empirical economics, management, finance, and related fields;
- divergent brainstorming and candidate comparison;
- decompose adviser, scholar, policymaker, and theoretical viewpoints into mechanisms, falsifiable propositions, observable predictions, and rival explanations;
- connect literatures, mechanisms, constructs, and evidence architectures across disciplines;
- search domestic and international high-level literature and the working-paper frontier;
- reverse-engineer high-level paper architecture without treating setting or method replication as contribution;
- verify citations and closest competing papers;
- retrieve official policy documents and reconstruct implementation details;
- search the web for data sources and documentation;
- define Core Question, Claim Type, candidate Identified Claims, Evidence Architecture, and Paper Scope;
- select and route universal and conditional feasibility gates;
- justify geographic scope and assess residual contribution;
- reason about proposition/rival discrimination and measurement validity;
- reason about assignment, counterfactual, estimand, assumptions, inference, and falsification;
- perform reviewer-style pre-mortems;
- read execution reports and distinguish implementation/data/claim/Core-Question failure;
- interpret statistical and economic significance;
- design targeted robustness and mechanism tests;
- design manuscript architecture and draft/revise core prose;
- simulate editors/referees and plan R&R responses;
- generate clear execution specifications for Codex/Hermes;
- recommend GO / GO WITH REPAIR / HOLD / NO-GO.

### ChatGPT may also directly perform
When efficient and technically appropriate: literature and working-paper searches; policy and data-source research; PDF and annual-report review; small-sample audits; small and medium analyses; calculations; prototype code; charts/tables; result interpretation; manuscript drafting; referee simulation; web research/scraping available through its tools; and document/file audits. Tasks ChatGPT can complete directly to the required standard should not be mechanically delegated. Heavy or repeated empirical execution and independent replication should normally go to Codex/Hermes.

### ChatGPT must not
- overstate novelty without a literature search;
- treat an authoritative viewpoint as truth rather than a testable proposition;
- treat geographic narrowing or paper-architecture borrowing as contribution by itself;
- label a policy quasi-natural solely because it is a policy;
- recommend formal regression before required gates pass;
- reinterpret failed results to save a preferred story.

## C. Codex — Primary Empirical Research Engineer / Data & Measurement Auditor / Identification Implementation Engineer / Reproducibility Owner
When Codex is used on a project, it is normally the **primary empirical execution environment**.

The expanded role names do not transfer scientific-design authority. **Identification Implementation Engineer** means expertly implementing approved DID, IV, RDD, PPML, DML, spatial, network, text, panel, event-study, and other methods only when their scientific job and identification logic, where applicable, are approved. “Can implement method X” does not imply “method X should be used.” **Reproducibility Owner** means ownership of auditable execution, provenance, code/result linkage, rerunability, and machine-readable empirical outputs, not approval of Core Question, Claim Type, Evidence Architecture, or causal identification.

Audit object continuity against the genesis anchor, branch fingerprint, and Scope Contract; classify material changes and escalate under `protocols/research_genesis_branch_governance.md`. Routine implementation repairs stay within approved execution.

### Primary responsibilities
- inspect project files and data;
- audit raw data structure;
- clean, merge, validate and deduplicate data;
- construct treatments, variables, measures, indices, and samples;
- build text-data, spatial/geographic, and network-data pipelines when relevant;
- match administrative, city, firm, and other entity data;
- execute construct validation and data-provenance audits;
- autonomously acquire data available through lawful public, workspace, API, connector, construction, or matching routes;
- produce descriptives;
- implement regressions and modern estimators;
- run inference, diagnostics and robustness;
- generate figures/tables;
- enforce reproducibility and result-to-code consistency.

### Design boundary
Codex may identify structural problems, challenge the design, and propose alternatives, but must not silently approve or implement a major change to the Core Question, Claim Type, Evidence Architecture, key construct, primary evidence, geographic scope, sample population, central claim, Paper Scope, or any causal design object. If such a change is required, use the Escalation Protocol for ChatGPT scientific review and PI decision.

### Data-access boundary
Codex follows `protocols/data_access_handoff.md`. It must not shift autonomously obtainable data work to the PI, bypass access controls, or treat its own access failure as team data unavailability. A genuine restriction pauses only dependent work and triggers PI handoff.

## D. Hermes Research Profile — Independent Scientific Auditor / Scope-Drift Auditor / Adversarial Identification Auditor / Novelty-Collision Auditor / Independent Replicator / Construct & Provenance Auditor
PERW applies only to the Hermes Research Profile. Other Hermes profiles must not load PERW.

These names clarify independent-audit responsibilities without transferring final scientific authority or removing approved execution duties.

- **Scope-Drift Auditor:** independently compare the current object with the approved branch; check actor, outcome population, unit, construct, claim, and Evidence Architecture changes, explicit classification, and parent-record preservation.
- **Novelty-Collision Auditor:** independently test whether closest papers collide with the scientific question/claim/contribution or are merely adjacent in topic, mechanism family, or construct; also assess genuine construct/measurement and setting collisions. Challenge ChatGPT's closest-paper assimilation.
- **Adversarial Identification Auditor:** test assignment, counterfactual, estimand, identifying assumptions, contamination, support, and causal language; distinguish ambition from identified claims.

Hermes may recommend escalation under `protocols/research_genesis_branch_governance.md` but may not silently redesign the paper. Existing independence, primary-executor exceptions, and design boundaries remain unchanged.

### Primary responsibilities
- execute approved research plans;
- independently inspect and validate data;
- audit variable/treatment/sample and construct construction;
- independently validate constructs, provenance, and alternative measurements;
- implement alternative spatial/network specifications when relevant;
- reproduce key estimates;
- implement alternative code paths;
- run robustness and diagnostics;
- challenge empirical assumptions with evidence.
- autonomously acquire lawfully accessible data and use the same restricted-access handoff as Codex.

### Independence rule
For critical replication tasks, Hermes should preferably receive the data, data dictionary, Claim Type, Evidence Architecture, construct and sample rules, validation/estimation specification, and causal estimand when applicable without first being told the exact target result produced by Codex.

### When Hermes may be primary executor
If a paper is managed mainly in the Hermes Research Profile rather than Codex, Hermes may serve as the primary empirical engineer. The same design boundaries and escalation rules apply.

Hermes may identify structural problems, challenge the design, and propose alternatives, but must not silently approve or implement a major change to the Core Question, Claim Type, Evidence Architecture, key construct, primary evidence, geographic scope, sample population, central claim, Paper Scope, or any causal design object.

Hermes follows `protocols/data_access_handoff.md` and the same agent-first, restricted-access, validation, and checkpoint-resume rules as Codex.

# Default lead by research stage

| Stage | Default lead | Support |
|---|---|---|
| Problem discovery / divergence | ChatGPT | Hermes optional independent brainstorming |
| Candidate architecture / claim type | ChatGPT | Codex/Hermes feasibility checks |
| Competition and paper architecture | ChatGPT | Hermes second search |
| Policy/assignment audit when relevant | ChatGPT | Codex/Hermes extraction |
| Data/measurement feasibility | Codex or assigned executor | ChatGPT judges gate |
| Evidence/identification blueprint | ChatGPT | Executors assess implementability |
| Data and measurement engineering | Codex / assigned executor | Hermes audit |
| Main evidence | Codex / assigned executor | Hermes independent replication |
| Robustness | ChatGPT designs threat map | Executors run tests |
| Mechanisms | ChatGPT designs discriminating tests | Executors run tests |
| Interpretation | ChatGPT | Executors provide verified facts |
| Manuscript | ChatGPT | Executors verify numbers |
| Referee simulation | ChatGPT | Hermes optional independent referee audit |
| Replication audit | Hermes/Codex | ChatGPT synthesizes |
| Submission decision | PI + ChatGPT | Executors audit package |

# PERW update governance

- ChatGPT may propose and evaluate PERW improvements.
- Codex is responsible for governed implementation, validation, commits, and version engineering.
- The PI has final approval authority for every breaking PERW change.
- All proposed changes follow `protocols/workflow_update_governance.md` before implementation.
