# Work Architecture — WA-0001

Status: admitted for `WORK-0001` bootstrap and execution.

## Purpose and boundary

Engineering Subject: build, verify, and close one knowledge-only information-analytical contour whose Product is a standalone professional analysis of the Russian economy at the end of Q2 2026 for a Russian bank focused on corporate lending and materially exposed to agribusiness borrowers.

Boundary:
- project state and durable results live only in `madaraii-pilot`;
- governing reusable definitions come only from `MADARAII`;
- external sources may be used only for the substantive economic Research;
- other repositories, workspaces, prior projects, prior chats, model memory, and file-library material are outside the project knowledge boundary;
- no separate software Product is in scope.

Architecture Baseline: bootstrap absence in an empty repository on 2026-09-11.
Governing basis: `ForestTiger-GH/MADARAII@7d5ef3d92c4e0982061d422208fdf913c55cc604`.
Commission: the current user instruction and attached project statement authorize end-to-end execution and repository mutation within the stated boundary.

## Semantic owners and current paths

| Role / owner | Current path | Responsibility |
| --- | --- | --- |
| Workspace front-door projection | `_mw/WORKSPACE.md` | cold entry, current owner routes, governing basis, resolver rules |
| Work State owner | `_mw/work/WORK-0001.md` | current posture, Baseline, completed results, next safe action, residue |
| Source Commission record | `_mw/commission/COMMISSION-0001.md` | durable project mandate and effect limits derived from the source carrier |
| Raw human input owner | `_mw/inbox/INBOX-0001.md` | preserved source-fidelity HUMAN INBOX carrier |
| Developed actor-input Result | `_mw/input/INPUT-0001.md` | normalized semantic acts and routing; never the raw carrier |
| Research program owner | `_mw/research/AGENDA.md` | qualified Topics, contracts, dispositions, execution state |
| Research History | `_mw/research/results/` | standalone source-traceable Research Results |
| Evidence/source registry | `_mw/evidence/SOURCES.md` | registered external sources and typed uses; not scientific truth |
| Knowledge Product Architecture | `_mw/knowledge/KPA.md` | semantic roles, assembly contract, read/lookup and lifecycle rules |
| Current Scientific Knowledge / final Product | `_mw/knowledge/RUSSIAN-ECONOMY-Q2-2026.md` | admitted current knowledge and standalone analytical document |
| Questions and uncertainty owner | `_mw/state/QUESTIONS.md` | materially unresolved questions, UNKNOWNs, reopen triggers |
| Decision owner | `_mw/state/DECISIONS.md` | project-local admitted decisions affecting scope/assembly; no external facts |
| Verification evidence | `_mw/verification/VERIFICATION.md` | role-specific verification verdicts and reliance boundary |
| Work report | `_mw/reports/WORK-REPORT.md` | semantic summary of the completed contour |
| Closure verdict | `_mw/closure/CLOSURE.md` | development-contour closure audit and terminal posture |

Only surfaces that become materially necessary are realized. Empty speculative surfaces are omitted until their role activates.

## Work geometry

1. Bootstrap organization and physical workspace so a cold actor can resolve current state.
2. Preserve and develop the source human input.
3. Reconcile Work State and commission bounded Research Topic development from admitted input semantics.
4. Qualify a purpose-bound Research program from consumer jobs and economic transmission mechanisms, rather than a standard macro indicator checklist.
5. Execute independent external descriptive Research Results where distinct evidence contours add value. Topics may run independently when they do not rely on one another; all feed a later reconciliative fan-in.
6. Account Research History and form/revise the Knowledge Product Architecture once enough substantive shape is visible.
7. Reconcile Research into Current Scientific Knowledge and the standalone reader Product.
8. Verify material claims, causal logic, temporal consistency, corporate-finance translation, bank implications, AПК depth, coverage, and proportionality.
9. Produce the Work report, reconcile residue, and audit contour closure.

The route above states likely composition. Every transition still depends on current Work State; instruction numbering does not commission successors.

## Authority and effects

- The user Commission authorizes the agent to create and modify files in `madaraii-pilot` needed to complete this contour.
- `MADARAII` is read-only governing material for this contour.
- External web sources may be read for substantive Research. No external write/action is authorized.
- Research Results establish evidence-bound findings; they do not become current Scientific Knowledge until assembly/admission.
- The Work State owner may admit project-local Research agenda and knowledge architecture choices needed to fulfill the user Commission, while preserving uncertainty and evidence limits.
- Final factual knowledge remains bounded by evidence and date; project process decisions do not increase factual certainty.

## Identity, naming, and resolver policy

Durable entities use stable IDs where cross-session identity matters: `WORK-0001`, `INBOX-0001`, `INPUT-0001`, `TOPIC-NN`, `RR-NN`, `KPA-0001`, `VR-0001`, `CLOSURE-0001`. Display filenames are locators, not identity.

Mandatory-input resolution order:
1. read `_mw/WORKSPACE.md`;
2. resolve the named semantic owner and current locator from its owner table;
3. inspect the intended current artifact and its declared Baseline/status;
4. follow only typed required relations named by the active Work contract;
5. if zero/multiple/currentness-conflicted resolutions occur, treat them as a binding defect and reconcile via `WORK-0001` rather than choose by filename similarity.

Derived indexes and summaries never override their source owners. Git history preserves earlier revisions; one current file per owner is maintained after cutover.

## Recovery and closure

`WORK-0001` is the durable recovery cursor. At material checkpoints it records governing revision, current phase/posture, established Results, active Baselines, unresolved residue, and next safe action.

Cold recovery succeeds when an actor can start from `README.md` → `_mw/WORKSPACE.md` → `_mw/work/WORK-0001.md`, resolve every required owner without prior chat memory, and continue from the stated next safe posture.

Local closure requires every material Research/Knowledge/verification obligation to be established or terminally dispositioned, the final Product to have one current path, unresolved material uncertainty to have an owner/reopen trigger, and `CLOSURE-0001` to state a truthful terminal posture.

## Realization contract

Realize the owner paths above only when activated; initialize front door, Work State, Commission record, raw inbox, developed-input Result, and the Research/Knowledge surfaces required for immediate next Work. Preserve exact source-fidelity payload for `INBOX-0001`. Do not materialize implementation/product-development machinery because this is a knowledge-only contour.

Physical realization must leave exactly one current locator for each activated owner, keep Research History distinct from Current Scientific Knowledge, and retain Git history as the recoverable pre-mutation Baseline.
