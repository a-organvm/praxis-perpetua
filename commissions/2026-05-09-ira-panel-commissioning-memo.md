---
memo_id: MEMO-2026-001
parent_commission: INQ-2026-013
title: External IRA Panel — Commissioning Memo for IRF-RES-008
short_name: The Tarskian Panel
purpose: rater_recruitment
status: draft
authored: 2026-05-09
location: praxis-perpetua/commissions/2026-05-09-ira-panel-commissioning-memo.md
target_irf_row: IRF-RES-008
target_gh_issue: a-organvm/organvm-corpvs-testamentvm#345
wallclock_target: ≥1 week recruitment + ≥1-2 weeks calibration
---

# Commissioning Memo: External IRA Panel for IRF-RES-008

**Parent commission**: [INQ-2026-013 RES Bundle](./2026-05-09-RES-bundle-commission.md)
**Target IRF row**: `IRF-RES-008` (P0, GOVERNANCE) — Formalize the IRA panel
protocol as Tarskian escape

## Why this memo exists

The RES Bundle commission identifies `IRF-RES-008` as Wave 4 work that **cannot
deliver from inside ORGANVM alone**. Per the source corpus that grounds the bundle:

> SYN-03 §5.4 limitation note + SYN-02 §3: single-operator IRA cannot escape
> Tarski's diagonal — the panel must include raters outside ORGANVM to function
> as the Tarskian truth-oracle the system requires.

ORGANVM is a single-operator system. Internal raters share priors, vocabulary,
and operator. The Inter-Rater Agreement panel that the SGO Charter establishes
(see `governance/charter.yaml` `tiers.academic[*].defense_protocol = standard`)
is intellectually self-referential when all raters originate inside the system.
The **Tarskian escape** — governance certifying its own completeness from
*outside* the formal language — requires raters whose priors, vocabulary, and
training are not derivative of ORGANVM's own operator.

Without external panel members, RES-008's deliverable is a charter that *claims*
external verification while structurally lacking it. This memo positions the
recruitment work that prevents that failure mode.

## What's being commissioned

**Three or more external IRA-panel raters** (and/or institutional partners
willing to host commissioned defense-protocol runs) for:

1. **Calibration runs** of the existing IRA mechanism (the
   `auto-revision-epistemic-engine` deployed per the SGO Charter's
   `evaluation_machinery: auto-revision-epistemic-engine (IRA)`) on a
   representative sample of governance verdicts emitted from
   `organvm-engine`.
2. **Independent semantic judgment** on properties that automated checks
   declare uncovered (per RES-007's 5-failure-mode schema: reference / collision
   / drift / mismatch / governance failure).
3. **Cross-rater agreement assessment** producing ICC scores per the SGO's
   academic-tier thresholds (Paper > 0.61 / Thesis > 0.70 / Dissertation > 0.75).

The panel exists to *verify ORGANVM's governance from outside ORGANVM's formal
language*. The panel does **not** define ORGANVM's governance; that remains the
Provost's authority. The panel's role is precisely the Tarskian truth-oracle:
they tell us when an internal verdict is true, false, or undecidable from
outside.

## Rater profile (any one suffices for a single panel slot)

The bundle's source corpus drives the rater-profile requirements. A qualified
rater satisfies *at least one* of:

1. **Methodological independence**: trained in measurement theory, psychometrics,
   IRA / ICC analysis, or factor analysis at a level sufficient to evaluate
   construct validity and inter-rater agreement (per RP-07's measurement-theory
   framework). Examples: psychometricians, applied statisticians, audit
   methodologists.

2. **Theoretical independence**: scholarly familiarity with self-reference
   limits, governance impossibility theorems (Tarski / Goodhart / Löb / Arrow /
   Gibbard-Satterthwaite), or boundary-object theory (Star and Griesemer 1989,
   Latour 2005). Examples: STS scholars, philosophers of science working on
   self-reference, organizational sociologists working on auditability.

3. **Domain independence**: practitioner experience in software-engineering
   governance (CI/CD verdicts, code review systems, organizational dependency
   graphs, multi-team naming conventions) at a scale comparable to ORGANVM's 145
   repos × 8 organs. Examples: senior platform engineers, DevEx leads at multi-
   team organizations, engineering-effectiveness researchers.

4. **Faculty independence**: SGO faculty members from any organ *other than the
   one whose verdict is being evaluated* — a rater from ORGAN-V (Logos)
   evaluating an ORGAN-III (Ergon) governance verdict. Internal but cross-organ.
   This satisfies independence weakly but provides a graceful fallback if
   external recruitment fails.

The panel should ideally include at least one rater from category (1) or (2),
since these provide the strongest Tarskian independence. Categories (3) and (4)
are practical fallbacks.

## What the rater commits to (by panel slot)

- **One initial calibration session** — review the IRA charter, become familiar
  with ORGANVM's governance-rules.json + a representative sample of seed.yaml
  contracts, agree to the rating instrument (rubric per the existing SGO defense
  protocol). **Estimated time**: 4–8 hours.
- **Multi-rater calibration runs** — score 5–10 governance verdicts independently
  alongside ≥2 other raters, then a calibration discussion (post-rating, not
  during). **Estimated time per run**: 2–3 hours; **total for first cycle**:
  10–15 hours.
- **Disagreement disposition** — when ICC falls below threshold, contribute to a
  disposition memo (what semantic property caused the divergence, what the rubric
  needs to resolve). **Estimated time**: 1–2 hours per disagreement.

**Total first-cycle commitment**: ~15–25 hours over ~4 weeks. Subsequent cycles
are lighter as the rubric stabilizes.

## What the rater receives

- Co-authorship credit on the formal IRA-panel-protocol artifact submitted to
  the SGO archive (potentially a Paper or Thesis tier publication, depending on
  rubric stability).
- Access to the underlying ORGANVM governance corpus during the engagement
  (selectively — production data files are read-only per workspace constitution).
- A *separate* engagement-completion artifact suitable for portfolio /
  professional-record use.
- Compensation: TBD per rater's request and the system's funding state. Per the
  RES bundle commission, "External rater commissioning" is named as a budget
  line item and a non-negotiable wallclock-floor constraint. Funding source: see
  the parent commission's "needs" array; current state is *unfunded*; pursuit of
  funding is part of this memo's downstream work.

## Recruitment channels (ranked by expected fit)

1. **Academic measurement-theory communities** — direct outreach to authors of
   the cited corpus (Lawrie, Butler, Hofmeister, Arnaoudova for identifier-quality
   work; Star, Bowker, Latour estate or current ANT scholars for boundary-object
   work). Most legitimacy + most independence; longest recruitment cycle.
2. **STS / philosophy-of-self-reference scholars** — particularly those working
   on governance / auditability / measurement-as-political-act per Strathern's
   audit-culture lineage. High independence + active community.
3. **Engineering-effectiveness research** — university research groups studying
   developer productivity, software governance, code-review effectiveness. Practical
   fit + may have institutional access to comparable corpora for cross-validation.
4. **Industry practitioners with strong public records** — senior platform
   engineers / DevEx leads at multi-team organizations who have published or
   spoken on governance topics. Faster recruitment + lower theoretical depth.
5. **Cross-organ ORGANVM faculty** (fallback per category 4 above) — internal
   raters from non-target organs, used only if external recruitment yields fewer
   than 3 raters within ~6 weeks.

## Risk register

| Risk | Likelihood | Mitigation |
|---|---|---|
| Zero-external-recruit failure (no qualified external rater commits within 6 weeks) | Medium | Fall back to cross-organ internal raters (category 4); document the independence weakness explicitly per the SGO's *visible incompleteness* principle (RES-007). The panel still functions; ICC certification carries an asterisk indicating the Tarskian gap was not closed externally. |
| Single-rater-capture (one external dominates the discussion) | Low–Medium | Enforce blind independent rating per defense-protocol stage 4 (`independent_evaluation`). Disagreements are statistical (ICC), not deliberative. |
| Compensation mismatch (rater expects payment beyond what's funded) | Medium | Frame the engagement as research collaboration with co-authorship credit; honest about funding state; offer alternative non-monetary value. Skip raters whose minimum is above ceiling. |
| Confidentiality / IP overlap | Low | ORGANVM's corpus is GRADUATED / public per workspace constitution. The commission corpus and source papers are openly published. No NDA needed; raters are evaluating public artifacts. |
| Rater drift after first cycle (commitment fades) | Medium | Design the first cycle to be self-contained (deliverable artifact in 4 weeks); make subsequent cycles opt-in. |

## Linkage

- **Parent commission**: [INQ-2026-013 RES Bundle](./2026-05-09-RES-bundle-commission.md) — see Wave 4 RES-008.
- **GitHub issue**: `a-organvm/organvm-corpvs-testamentvm#345`.
- **IRF row**: `IRF-RES-008` in `INST-INDEX-RERUM-FACIENDARUM.md`.
- **Plan file**: `~/.claude/plans/open-tasks-vectorized-pretzel.md` § "Wave 4 — Apply".
- **Source corpus**: SYN-02 §4.5, §5.3 (Tarskian escape via IRA); RP-02 §6.3.
- **SGO governance**: `governance/charter.yaml` §`tiers` (ratified 2026-05-09);
  `governance/defense-protocol.yaml` (panel mechanics); `governance/faculty-registry.yaml`
  (faculty rubrics).
- **Existing IRA infrastructure**:
  `~/Workspace/organvm-i-theoria/auto-revision-epistemic-engine/` (machinery);
  `~/Workspace/meta-organvm/stakeholder-portal/` (Hermeneus — second-instantiation
  proof per inquiry-log INQ-2026-002 evidence list).

## Status

**DRAFT** — ready for Provost review before any outbound recruitment. No
external contact has been initiated. Per home `CLAUDE.md` rule about external
outreach (memory rules #26 & #29 — staggered, never make user look stupid,
read upstream house rules first), the recruitment-execution phase has its own
gate before any messages are sent.

## Next actions (post-Provost-review)

1. Approve / revise rater profile and commitments.
2. Decide funding state (unfunded → academic-credit framing; funded → standard
   research-services rates).
3. Draft individual outreach messages per recruitment channel; queue for
   staggered send.
4. Open a tracking doc (or extend this memo) with one row per candidate,
   status (contacted / responded / committed / declined), and commitment date.
5. Once 3 raters committed: schedule first calibration session; finalize the
   rating instrument.
6. After first cycle: update IRF-RES-008 with first-cycle ICC results;
   update commission INQ-2026-013 evidence list.

## Failure-mode disclosure (per RES-007 visible-incompleteness pattern)

This memo does not address:

- **The non-academic compensation model** for raters whose first preference is
  consulting rates rather than co-authorship credit. The system's funding
  state is the rate-limiter; this memo does not propose a solution.
- **Long-arc rater retention**. The first cycle is self-contained; cycle-on-cycle
  retention is *its own design problem* (per RP-05's continuous-re-enrollment
  finding) and is deferred to a future memo.
- **The Tarski-escape robustness of the resulting panel**. Even with external
  raters, the panel cannot fully escape Tarski if they share methodological
  priors with the SGO. The commission accepts this residual gap as inherent;
  visible-incompleteness reporting (RES-007) makes it transparent rather than
  hidden.
