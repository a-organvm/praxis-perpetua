---
commission_id: INQ-2026-013
work_id: SGO-2026-COM-001
title: >-
  Navigation of the Three Self-Reference Impossibilities — Operationalization of the
  RES P0 Foundational Bundle
short_name: The RES Bundle
tier: implementation_commission
faculty: governance
advisory_faculty: measurement, naming-infrastructure
commissioned: 2026-05-09
status: drafting
location: praxis-perpetua/commissions/2026-05-09-RES-bundle-commission.md
plan_file: ~/.claude/plans/open-tasks-vectorized-pretzel.md
irf_rows:
  - IRF-RES-003
  - IRF-RES-004
  - IRF-RES-006
  - IRF-RES-007
  - IRF-RES-008
  - IRF-RES-009
  - IRF-RES-010
  - IRF-RES-011
  - IRF-RES-012
  - IRF-RES-013
  - IRF-RES-014
te_budget_total: 1430000
calendar_floor: 3 weeks (human gates)
sources:
  - RP-02-self-reference-limits
  - RP-03-rhizome-vs-hierarchy
  - RP-04-naming-problem
  - RP-05-latour-network-ontology
  - RP-07-measurement-theory
  - SYN-02-governance-impossibility
  - SYN-03-naming-as-infrastructure
  - SYN-04-flat-ontology-measurement
---

# Commission RFC: Navigation of the Three Self-Reference Impossibilities

**INQ-2026-013** | **2026-05-09** | **Status: drafting**

## Executive summary

The IRF carries 11 P0 items in domain `RES` (`IRF-RES-003`, `004`, `006`–`014`),
all flagged "P0 — Foundational (must precede other research programme work)." Their
combined section header announces them as a *prerequisites bundle*, not 11
independent items.

Reading the eight prior research artifacts they cite reveals these 11 items are not
governance refinements. They are **the operational maneuvers around three structural
impossibility theorems**:

| Theorem | Source | RES items operationalizing the navigation |
|---|---|---|
| **Tarski** — no formal language can contain its own truth-predicate | RP-02 §5–6, SYN-02 §1–3 | RES-008 (IRA panel as external truth oracle) |
| **Goodhart-Campbell** — when a measure becomes a target, it ceases to be a good measure | RP-07 §7.3, SYN-02 §3, SYN-04 §3 | RES-013 (temporal staging), RES-003 (gaming-budget reframe), metric rotation |
| **Löb** — no consistent system can prove its own consistency | RP-02 §5.1, §6.4 | RES-010 (architectural separation of self-maintenance from self-improvement) |

The remaining 8 items provide the *infrastructure* that makes the three escapes work:
controlled vocabulary (RES-006), visible incompleteness (RES-007), semantic-accuracy
tracking (RES-009), context-specific norms (RES-014), hybrid topology codification
(RES-011), boundary-object redesign of governance artifacts (RES-012), construct
validity for "readiness" (RES-003), and exploratory factor analysis on the omega
scorecard (RES-004).

The commission's true purpose is not "11 governance improvements." It is to **stop
ORGANVM from violating the three impossibility theorems silently**, by making each
violation visible (RES-007), externally checked (RES-008), or architecturally
separated (RES-010 + RES-013).

## Scope

| Strand | Theoretical motor | Items | Wave assignment |
|---|---|---|---|
| Tarskian | Self-reference impossibility | RES-007, 008, 009, 010, 013 | W3, W4, W4, W5, W2 |
| Boundary-objects + naming | Coordination across interpretive communities | RES-006, 011, 012 | W1, W2, W5 |
| Measurement validity | What we measure must equal what we mean | RES-003, 004, 014 | W3, W1, W4 (conditional) |

Total: 11 items, 5 waves, ~1.43M TE, ≥3 weeks calendar floor.

## Source citations (per item)

| Item | Primary sources | Section / load-bearing claim |
|---|---|---|
| `RES-003` | RP-07, SYN-02, SYN-04 | RP-07 §7 I1 (readiness construct grounded in measurement theory); SYN-04 §4.1 (relational psychometrics) |
| `RES-004` | RP-07, SYN-02 | RP-07 §6.2–6.3 (factor analysis); SYN-02 §5.5 R2 |
| `RES-006` | RP-04, SYN-03 | RP-04 §5.1 Principle 4 ("synonymy catastrophe" at ~50–100 naming decisions); SYN-03 §5.1 (controlled vocabulary as repository-type boundary object) |
| `RES-007` | RP-02, SYN-02, RP-04 | RP-04 §3.1 (5 failure modes: reference / collision / drift / mismatch / governance); SYN-02 §5.5 R1 |
| `RES-008` | RP-02, SYN-02 | SYN-02 §4.5, §5.3 (Tarskian escape via IRA panel); RP-02 §6.3 |
| `RES-009` | RP-02, SYN-02 | SYN-02 §5.4 (semantic-accuracy registry); RP-02 §6.2–6.4 |
| `RES-010` | RP-02 | RP-02 §5.7, §6.4 (self-maintenance vs. self-improvement, Löb-theorem application) |
| `RES-011` | RP-03, SYN-02 | RP-03 §3.4–3.5, §6.1–6.4 (coupling structure); SYN-02 §4.2 |
| `RES-012` | RP-05, SYN-02, SYN-03 | SYN-03 §5.1 (4 boundary-object structural types); RP-05 §4.3, §5.2, §7.1 (immutable mobiles + per-actant enforcement paths) |
| `RES-013` | RP-02, SYN-02 | SYN-02 §4.1, §5.2 (temporal staging — never validate self with self) |
| `RES-014` | RP-07, SYN-02, SYN-04 | RP-07 §7 I4 (context-specific norms); SYN-04 §5.2 |

## Wave structure (~1.43M TE, ≥3 weeks calendar floor)

```
Wave 1 (Bedrock + EFA)
  └── RES-006 (vocabulary registry, retroactive reconciliation) ── 110K TE
  └── RES-004 (Bayesian EFA + DIF on omega scorecard) ──────── 200K TE

Wave 2 (Parallel-independent — can start alongside W1)
  └── RES-011 (hybrid topology codification + effective-coupling tracking) ── 80K TE
  └── RES-013 (temporal staging refactor of all governance validators) ── 130K TE

Wave 3 (Define, informed by W1 EFA results)
  └── RES-003 (define "readiness" construct + gaming-budget reframe) ── 180K TE [HUMAN]
  └── RES-007 (visible incompleteness via 5 failure-mode schema) ── 90K TE

Wave 4 (Apply)
  └── RES-008 (IRA panel charter + Tarskian-escape protocol) ── 120K TE [HUMAN]
  └── RES-009 (seed.yaml semantic-accuracy registry) ── 140K TE
  └── RES-014 (context-specific governance norms) ── 100K TE [CONDITIONAL on RES-004 result]

Wave 5 (Architectural top)
  └── RES-010 (self-maintenance / self-improvement separation) ── 130K TE
  └── RES-012 (boundary-object redesign × 3 typology mappings + per-actant paths) ── 250K TE
```

### Critical path

`RES-006 → RES-007 → RES-009 → RES-012` — ~470K TE end-to-end on the longest chain.
Parallel-independent slack: RES-004, RES-011, RES-013 can run concurrently.

### Hard dependencies (post full-corpus grounding)

- `RES-003 → RES-006` (need stable vocabulary to define construct)
- `RES-003 ← RES-004` (data reveals what's measurable; construct definition follows EFA evidence)
- `RES-007 → RES-006` (governance failure mode requires vocabulary to know what's in scope)
- `RES-008 → RES-007` (incompleteness must be visible before delegation to external panel)
- `RES-008 → RES-010` (IRA charter constrains how meta-governance separation can safely operate)
- `RES-009 → RES-006`, `RES-009 → RES-007`, `RES-009 → RES-013`
- `RES-012 → RES-006`, `RES-012 → RES-007`
- `RES-014 → RES-003`, `RES-014 → RES-006`
- `RES-014 → RES-004` (CONDITIONAL: only proceed if EFA reveals multi-factor + cross-organ DIF)

## Human-gated items (calendar floor)

| Item | Human action required | Wallclock |
|---|---|---|
| RES-003 | Convene expert panel for readiness-construct definition | 1–2 weeks |
| RES-008 | IRA panel calibration runs (multi-rater, **must include external participants**) | 1–2 weeks + recruitment |
| RES-014 | Domain-expert determination of context-specific thresholds | ~1 week |

These three items impose ≥3 weeks of wallclock floor regardless of TE expenditure.
**External rater recruitment for RES-008 is non-negotiable**: per SYN-02 + SYN-03,
single-operator IRA cannot escape Tarski's diagonal — the panel must include raters
outside ORGANVM to function as the Tarskian truth-oracle the system requires.

## Sample-size risk (Motor C — measurement validity)

**Risk**: ORGANVM has 145 repos. RP-07 §6.3 specifies sample-size requirements for
EFA: 5–10 observations per item × 17 omega items = 85–170 repos. ORGANVM is at the
**lower margin** of viability; underpowered for stable factor recovery via classical
EFA.

**Mitigation budgeted into RES-004**:
- Bayesian factor analysis (smaller-sample tolerance) instead of frequentist EFA — adds
  ~80K TE (raising RES-004 from 120K to 200K) but de-risks the entire measurement
  motor.
- "Minimal viable psychometrics" (RP-07 §7.2): item inter-correlations + ±0.15
  confidence intervals rather than point estimates.
- Stability test: re-run EFA on Organ-I (26 repos) vs. Organ-III (32 repos) subsamples;
  divergent factor structure = measurement non-invariance (governance scoring does not
  generalize across organs).

**Failure mode**: if EFA fails to converge or produces unstable factors, the entire
measurement-validity motor cannot deliver as specified. RES-014 collapses to a
close-as-DONE in this case (no context-specific differentiation needed if scorecard
is unidimensional).

## Constraints budget (non-negotiable)

1. **15% governance-debt budget** — per Strathern's audit-culture finding (RP-07 §7.3),
   metric gaming is a feature of any governance system, not a bug. Tolerate ~15%
   gaming as the intrinsic cost of automated governance. Metric rotation (rotate which
   8 of 17 omega items are scored annually) is structural, not optional.

2. **Continuous feedback loops are forbidden** — per Goodhart-Campbell (SYN-02 §3),
   outcome measurement cannot feed back into governance continuously without
   corrupting both. RES-013's staging is *mathematical necessity*. Tooling must
   enforce stage boundaries.

3. **Per-actant enforcement paths in three artifacts** — per RP-05 §5.2: "A CLAUDE.md
   that reads identically to human, AI, and CI/CD is a failed immutable mobile."
   RES-012 must inscribe three enforcement paths visibly per artifact (human:
   advisory, AI: behavioral constraint, CI/CD: compliance check), plus
   `interpretation_paths` per actant + `decision_gates` (obligatory passage points).

4. **External raters for IRA panel** — per SYN-03 §5.4 + SYN-02: single-operator IRA
   cannot escape Tarski's diagonal. RES-008 requires external participants. This adds
   recruitment + commissioning to the wallclock floor.

5. **Re-enrollment is continuous** — per RP-05 §7.3: enrollment contracts must be
   re-read as context changes. Static governance documents fail under scale.
   Subscription / notification layer required for redesigned artifacts.

## Success criteria (commission-level)

When the commission is closed, the following are concretely true:

- A controlled vocabulary registry exists, all governance artifacts cite it, CI hook
  validates new names against it. (RES-006)
- An EFA / Bayesian factor analysis on the omega scorecard has been completed; either
  unidimensional structure has been confirmed and validated, OR multi-factor structure
  with cross-organ DIF has been mapped. (RES-004)
- Every governance verdict emitter declares which of the 5 failure modes it covers and
  which it does not. (RES-007)
- An IRA panel charter exists with at least 3 external participants engaged; first
  calibration run is complete. (RES-008)
- A semantic-accuracy registry tracks which seed.yaml properties are validated and
  which are declared-but-unchecked. (RES-009)
- Self-maintenance and self-improvement are architecturally separated; tooling enforces
  the boundary. (RES-010)
- The hybrid topology principle is codified in `governance-rules.json` as enforceable
  law, with effective-vs-nominal coupling tracking. (RES-011)
- `seed.yaml`, `CLAUDE.md` template, and `governance-rules.json` are redesigned as
  boundary objects with per-actant enforcement paths visibly inscribed. (RES-012)
- Governance validators always validate previous state using current state, never
  current using itself. (RES-013)
- A "readiness" construct is defined independently of its operationalization, with a
  documented 15% gaming-debt budget. (RES-003)
- Context-specific governance norms exist by organ / language / project type — OR
  RES-014 is closed-as-DONE with documented finding that scorecard is unidimensional.
  (RES-014, conditional)

This is not a feature add. **It is a constitutional rewrite of ORGANVM's governance
layer.**

## Linkage / external indices to propagate

Per IRF "External Index Propagation" rule, completion of any item in this commission
must update:

1. **IRF** — move item to `## Completed` with session ID + date
2. **GitHub Issues** — close paired issue with commit-SHA reference
3. **Omega Scorecard** — `organvm omega status` to verify any criterion change
4. **Inquiry Log** (this file's parent index) — update INQ-2026-013 evidence list
5. **Testament Chain** — `organvm testament status` if the work is a significant system event
6. **Concordance** — if work introduces or retires governance IDs
7. **Registry** — if work changes repo state
8. **Seed contracts** — if work changes repo capabilities
9. **CLAUDE.md files** — if work adds/changes modules, routes, tools
10. **Companion indices** (Locorum, Nominum, Rerum) — when built

## References

- `~/Workspace/intake/research-adventures-2026-03/papers/phase-1/RP-02-self-reference-limits-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-2/RP-03-rhizome-vs-hierarchy-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-1/RP-04-naming-problem-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-2/RP-05-latour-network-ontology-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-1/RP-07-measurement-theory-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-3/SYN-02-governance-impossibility-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-2/SYN-03-naming-as-infrastructure-DRAFT-v2.md`
- `~/Workspace/intake/research-adventures-2026-03/papers/phase-3/SYN-04-flat-ontology-measurement-DRAFT-v2.md`
- Plan file: `~/.claude/plans/open-tasks-vectorized-pretzel.md`
- IRF: `~/Workspace/organvm/organvm-corpvs-testamentvm/INST-INDEX-RERUM-FACIENDARUM.md`

## Appendix: Per-item dossier (deliverables)

### RES-006 — Controlled vocabulary registry (Wave 1, 110K TE)

**Deliverable**: machine-readable JSON/YAML canonical→synonym map + CI hook
validating new names; initial canonical extraction across registry-v2.json,
governance-rules.json, all seed.yaml files, IRF domain codes (21), concordance
invocation namespaces (~7 namespaces, 100+ IDs), ontologia entity types; synonymy
reconciliation pass; drift report.

**Why retroactive, not preventive**: per RP-04 §5.1 Principle 4, the synonymy
catastrophe begins at ~50–100 independent naming decisions. ORGANVM has crossed
this threshold years ago — RES-006 must canonicalize existing usage, not just
gate future names.

**Why a boundary-object construction**: per SYN-03 §5.1, controlled vocabulary IS
the repository-type boundary object. Builds the pattern that RES-012 later applies
at higher abstraction.

### RES-004 — Bayesian factor analysis on omega scorecard (Wave 1, 200K TE)

**Deliverable**: Bayesian EFA on 17 omega items × 145 repos; factor structure
report with confidence intervals; DIF analysis across Organ-I vs Organ-III
subsamples; recommendation for RES-014 (proceed if multi-factor + cross-organ
DIF, else close).

**Why Wave 1 not Wave 2**: per SYN-04 + Agent 2's grounding, "data reveals what
is measurable; governance ideology should follow, not precede, measurement
evidence." Conducting EFA before RES-003's construct-definition workshop avoids
imposing a construct on data that may not support it.

### RES-007 — Visible incompleteness in governance verdicts (Wave 3, 90K TE)

**Deliverable**: schema + retrofit such that every governance verdict emitter
declares, for each of the 5 failure modes (reference / collision / drift /
mismatch / governance), whether the verdict covers it. Surface the 5-tuple in
verdict output.

**5-failure-mode taxonomy** (per RP-04 §3.1):
- Reference failure: name points to nothing
- Namespace collision: same name → multiple referents
- Semantic drift: meaning changed while name persisted
- Abstraction mismatch: same entity, different names per context
- Governance failure: no authoritative dispute resolution

### RES-008 — IRA panel as Tarskian escape (Wave 4, 120K TE, HUMAN)

**Deliverable**: IRA panel charter + appeal/override protocol; first calibration
run with multi-rater (≥3 raters, must include external participants per SYN-02
finding).

### RES-009 — seed.yaml semantic-accuracy registry (Wave 4, 140K TE)

**Deliverable**: registry of properties not covered by seed.yaml validation
(declared but unchecked); periodic re-validation protocol; translation-gap audit
methodology.

### RES-010 — Self-maintenance / self-improvement separation (Wave 5, 130K TE)

**Deliverable**: architectural separation of two operational modes (inner-loop
maintenance vs. outer-loop improvement) with tooling enforcement; documentation
of which operations are maintenance-allowed vs. improvement-only.

### RES-011 — Hybrid topology law codification (Wave 2, 80K TE)

**Deliverable**: codify inter-organ hierarchical (I→II→III no back-edges) +
intra-organ rhizomatic principle in `governance-rules.json` with enforcement;
add effective-vs-nominal coupling tracking dimension to address scaling-limit
finding (RP-03 §4.5).

**Why downward TE pressure**: per RP-03 §4.6, ORGANVM already instantiates the
principle; this is codification of existing law, not new imposition. The +10K
for effective-coupling tracking offsets the −20K from codification simplicity,
netting 80K.

### RES-012 — Boundary-object redesign (Wave 5, 250K TE)

**Deliverable**: redesign three artifacts using three different Star &
Griesemer boundary-object structural types:

| Artifact | BO type | What changes |
|---|---|---|
| `seed.yaml` | Repository | Per-community fields: human-prose summary, machine-parsable contract, AI-instruction layer |
| `CLAUDE.md` template | Standardized form | Explicit interpretive-community headers; separate machine-readable autogen zones from human-prose context |
| `governance-rules.json` | Ideal type | Convert flat rules to typed schemas with explicit local-adaptation slots |

Each artifact must inscribe three enforcement paths visibly (human: advisory,
AI: behavioral constraint, CI/CD: compliance check), plus `interpretation_paths`
per actant + `decision_gates` (OPPs) + a re-enrollment notification layer.

### RES-013 — Temporal staging refactor (Wave 2, 130K TE)

**Deliverable**: refactor all governance validators so they compare current↔
previous state, never current↔current. Touches every governance validator.
Includes staged-measurement protocol per Goodhart-Campbell mathematical necessity.

### RES-003 — Define "readiness" construct (Wave 3, 180K TE, HUMAN)

**Deliverable**: expert-panel definition of "repo readiness" independently of its
operationalization; integration with SYN-04's flat-ontology / relational-psychometrics
findings; documented 15% gaming-debt budget; metric rotation protocol.

### RES-014 — Context-specific governance norms (Wave 4, 100K TE, CONDITIONAL, HUMAN)

**Deliverable** (only if RES-004 reveals multi-factor structure with cross-organ DIF):
three governance profiles (Theoria / Poiesis / Ergon) with differential thresholds
per organ × language × project type.

**If RES-004 reveals unidimensional structure**: close as DONE-via-data with rationale.
