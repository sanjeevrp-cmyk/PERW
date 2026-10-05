# Research Genesis & Branch Governance

Preserve the provenance of the scientific question without protecting a weak idea because it came first. This protocol documents and audits existing question, scope, and authority boundaries; it adds no Stage, Gate, passing criterion, claim architecture, identification standard, or Stop / Reopen rule. Use `protocols/escalation_protocol.md` and `templates/SCOPE_CHANGE_MEMO.md` for changes already requiring scientific review and PI decision.

## Research Genesis Anchor

At research genesis in Stage 0–1, create a lean `templates/RESEARCH_GENESIS_ANCHOR.md` record with a stable GENESIS ID. Capture the originating question, source, original scientific object, actor, affected/outcome population, relation, construct, theoretical object, envisioned unit, setting, mechanism/proposition, rival, intended claim, initial evidence architecture if any, causal ambition, interpretation, and what would or would not answer it. Unknown fields may remain explicitly OPEN; do not invent an original design. For retrospective reconstruction, label it RETROSPECTIVE and record dated sources, uncertainty, and missing information rather than inventing historical intent.

The anchor is a provenance record, **not a permanent design freeze**. Preserve the original record and append dated clarifications; do not overwrite it to match later results. Divergence may generate multiple questions and multiple anchors where origins differ. An original PI/adviser idea may be explicitly repaired, split, downgraded, held, killed, or replaced when evidence warrants. Scientific value, novelty, measurement, data, identification, and feasibility remain decisive; the idea's origin grants no scientific privilege.

## Scientific Object Fingerprint

Compare branches qualitatively across:

- Core Question;
- focal actor / exposure actor;
- affected actor / outcome population;
- outcome / primary evidence;
- unit of analysis;
- core construct;
- core relation;
- central mechanism target;
- Claim Type;
- Evidence Architecture;
- causal / noncausal inference ambition;
- setting / geography when scientifically material.

Record OLD → PROPOSED objects, the evidence motivating a change, and why it does or does not change the central scientific question. Use the genesis anchor to preserve origin, the current branch fingerprint to identify the approved question, and the Scope Contract to identify frozen design objects. The origin is not assumed to be the current approved branch. A fingerprint is not a mechanical similarity score, numerical distance, weighted index, or automatic branch decision.

## Scope-drift classification

| Classification | Meaning and handling |
|---|---|
| IMPLEMENTATION REPAIR | Same scientific object and claim; different code, source, or implementation within the approved architecture. Log execution/provenance and validate as relevant; no unnecessary new branch or scope approval. |
| DESIGN REPAIR | Same underlying Core Question, but material measurement, evidence, or identification repair. Record affected objects and use existing Scope Change / Gate reassessment wherever PERW already requires it. |
| EXTENSION | A scientifically subordinate additional question that leaves the central paper and primary object intact. Record the relation to the parent; material frozen-object changes still use existing scope governance. |
| NEW BRANCH | The scientific question materially changes, especially its actor, outcome population, core relation, mechanism target, Claim Type, or Evidence Architecture. Create a distinct branch record and review its scientific job and evidence on their own merits. |
| BRANCH REPLACEMENT | A project explicitly abandons or supersedes a parent branch after Research Director review and PI decision. Preserve the history and rationale; do not overwrite the parent. |

A changed estimator, code path, or data source alone does not imply a new branch. Conversely, changing methods while continuing to answer a different question is not an implementation repair. A material architecture change may repair the same question or create a different branch; explain the scientific distinction rather than classify by the field name alone. Uncertain classifications are proposals for Research Director review, not executor permission to redesign.

## Drift triggers and execution handling

Check for drift when, after substantial development, data constraints, literature, nulls, method limits, or implementation pressure materially change the focal/exposure actor, affected actor, outcome population, primary outcome/evidence, unit, key construct, core relation, central mechanism target, Claim Type, Evidence Architecture, causal object, sample population, or scientifically constitutive geography.

At Stages 6–10, compare the proposed design against the **Genesis Anchor + current branch fingerprint + Scope Contract**. If it is not routine implementation repair, stop affected execution while classifying the change and recording the parent history. This is the existing affected-branch structural-escalation boundary, not a new scientific STOP/NO-GO condition or a whole-project restart. Resume under existing approval, Gate reassessment, and Scope Change rules where applicable; unaffected approved work may continue. A diagnostic discrepancy or technical failure without a proposed scientific-object change does not itself require a new branch. Ordinary reporting of uncertainty or a null within the approved claim boundary does not itself replace the question.

## Branch preservation and evidence reuse

Use `templates/RESEARCH_BRANCH_REGISTRY.md` with stable GENESIS ID and BRANCH ID; link each branch to its parent, origin, fingerprint, trigger, relation, status, and material PI decision. At Stage 4, record GENESIS ID and BRANCH ID in the Scope Contract. The Scope Contract remains the formal freeze under existing authority.

A scientifically valuable parent branch must not silently disappear merely because a narrower branch is easier to execute. Keep its record and explicitly decide whether it remains ACTIVE, goes on HOLD, is ARCHIVED, is KILLED, or is COMPLETED. These are registry statuses, not new Gate decisions or overrides of existing Stop / Reopen rules. Branch preservation is **not topic preservation or sunk-cost preservation**: a scientifically failed branch may be explicitly killed, with no obligation to continue research after NO-GO. Retaining a historical record does not reopen it.

A new or replacement branch does not automatically inherit the parent's supported claims, Gate decisions, or scope approval. Record what data, code, validated constructs, or evidence remain reusable and what is branch-specific; reassess their relevance, support, provenance, and validity under existing criteria before reuse. Historical evidence answers only the question and population it actually supports.

## Causal ambition declaration and resolution

Declare causal ambition separately from Claim Type:

- CAUSAL IF CREDIBLY IDENTIFIABLE;
- NONCAUSAL;
- OPEN / UNDECIDED.

**Causal ambition is not a causal claim.** When causal ambition is declared, the Research Director actively evaluates assignment, counterfactual, estimand, identifying assumption, support, and falsification before recommending an associational downgrade. Reason from assignment → counterfactual → estimand → assumptions → estimator; advanced estimation does not establish identification. Record credible evidence, unresolved issues, and why identification is or is not currently supportable. This feasibility assessment creates no extra Identification Gate for a noncausal claim; causal claims remain subject to the full existing causal sequence and standards.

Use the branch record or a linked Research Director review to record DATE / BRANCH ID; ASSIGNMENT; COUNTERFACTUAL; ESTIMAND; IDENTIFYING ASSUMPTION; SUPPORT; FALSIFICATION; SOURCE EVIDENCE / UNRESOLVED ISSUES; RESOLUTION / RATIONALE; and PI DECISION where material. Do not substitute a method name for this assessment.

If credible causal identification cannot currently be established, record an explicit resolution, rationale, and existing decision authority:

- KEEP CAUSAL DESIGN;
- CAUSAL DESIGN WITH REPAIR;
- DOWNGRADE CLAIM WITH PI APPROVAL;
- SPLIT CAUSAL AND NONCAUSAL BRANCHES;
- HOLD;
- NO-GO.

These record the treatment of ambition; they do not replace GO / GO WITH REPAIR / HOLD / NO-GO Gate decisions. Neither KEEP nor REPAIR permits a causal claim without passing existing identification standards. Do not silently relabel a causal branch as associational. Material downgrade, split, or replacement uses Research Director review and PI decision, with Scope Change / Gate reassessment where already required. OPEN ambition must be clarified before a causal claim is approved, and NONCAUSAL must be revisited explicitly before any causal upgrade. Noncausal research may be scientifically excellent; transparency is the rule, not a default preference for causality.

## Stage and role integration

- **Stage 0–1:** capture origins, allow plural questions without premature freeze, then compare literature-refined candidates with their anchors to distinguish refinement from assimilation.
- **Stage 2–3:** distinguish original, repaired, and new branches where relevant; use the multidimensional collision audit in `protocols/high_quality_literature_anchoring.md`. Existing Gate routing, criteria, and decisions remain unchanged.
- **Stage 4–5:** link the selected branch to genesis and parent history in the formal Scope Contract; record ambition assessment/resolution without changing freeze authority or identification standards.
- **Stage 6–10:** apply the material-change comparison and existing affected-branch escalation; preserve history and check evidence reuse.

ChatGPT guards question provenance, attacks novelty, reviews identification feasibility, and recommends scientific decisions under existing authority. Codex implements approved designs, audits drift and reproducibility, and escalates structural changes. Hermes independently audits object continuity, novelty collision, identification, and provenance and may recommend escalation; it cannot silently redesign a paper. The PI retains final scientific authority over material replacement, scope changes, stopping/reopening, and freeze decisions. ChatGPT may reject a weak design but cannot silently replace a PI-approved question with a safer or more literature-familiar one.

Central adoption does not migrate active projects. Any later adoption affecting an active design requires a separate `PERW_MIGRATION_ASSESSMENT` under `protocols/workflow_update_governance.md` and, where needed, explicit genesis/scope reconciliation. Project-specific anchors and branches belong in project files, never in central PERW.
