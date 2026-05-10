# Session: SpecStory v2 Rollup Crack — 2026-04-30

User invocation: *"massive weight contextually insurmount & impenetrable"* + path to `~/Workspace/SpecStory, Markdown v2.md` (39 MB, 718,588 lines).

This bundle is the durable persistence of that session — scripts, derived artifacts, recovered substrate, and the ingested JSONL. Per Universal Rule #2 (`local:remote = 1:1`), this directory makes the session reproducible from git alone.

## What was built

Six phases ran end-to-end:

1. **Manifest** — single streaming pass over the rollup → `artifacts/rollup-manifest.tsv` (109 sessions, line ranges, agents, UUIDs).
2. **Reconcile** — UUID-based join against `~/Workspace/.specstory/history/` (200 files post-recovery) → `artifacts/rollup-vs-substrate.md`. Found: 107 BOTH, 2 EXPORT-ONLY (recovered), 9 SUBSTRATE-ONLY UUIDs (pre-rollup-window), 2 same-second twin clusters.
3. **Index** — chronological human-navigable session table → `artifacts/SpecStory-v2.INDEX.md`. After this, the rollup is line-jump-tractable.
4. **Ingest** — wrapped `ingest-supplementary.py:ingest_specstory()` against the Workspace-anchored substrate → 957 prompts in canonical schema → `artifacts/supplementary-prompts-specstory-workspace.jsonl`.
5. **Distill** — `organvm prompts distill` over the 957 prompts → 73.3% pattern coverage; 2 uncovered → `artifacts/distill-coverage-report.json`.
6. **Verify** — rollup mtime preserved; substrate doubling confirmed at 1.69× post-recovery; atom corpus untouched (4,247 signal in `data/atoms/annotated-prompts.jsonl`).

The narrative summary is `artifacts/SpecStory-v2.DISTILLATE.md` — read that first if you want the operational fingerprint.

## Bundle layout

```
2026-04-30--specstory-rollup-crack/
├── README.md                      ← this file
├── scripts/                       ← /tmp originals; reproducible
│   ├── build-manifest.py          ← Phase 1
│   ├── reconcile.py               ← Phase 2 v1 (timestamp-keyed; SUPERSEDED)
│   ├── reconcile-v2.py            ← Phase 2 v2 (UUID-keyed; canonical)
│   ├── build-index.py             ← Phase 3
│   ├── run-specstory-ingest.py    ← Phase 4 (wraps upstream ingest_specstory)
│   └── convert-for-distill.py     ← Phase 5 prep (JSONL → flat JSON for distill)
├── artifacts/                     ← derived outputs (mirrored from .specstory/)
│   ├── rollup-manifest.tsv        ← 109 rows
│   ├── rollup-vs-substrate.md     ← reconciliation buckets
│   ├── SpecStory-v2.INDEX.md      ← navigable session index
│   ├── SpecStory-v2.DISTILLATE.md ← narrative summary, IRF cross-refs
│   ├── specstory-prompts-distill-input.json   ← distill-shaped JSON (957)
│   ├── distill-coverage-report.json           ← coverage + uncovered patterns
│   └── supplementary-prompts-specstory-workspace.jsonl ← canonical JSONL
└── recovered-from-rollup/         ← lost-twin substrate sessions
    ├── 2026-03-31_19-32-39-0400-recovered-from-rollup-300ecbd9.md  (11,238 lines)
    └── 2026-04-29_17-32-21-0400-recovered-from-rollup-a20be727.md  (6,056 lines)
```

The originals at `~/.specstory/` (artifacts) and `~/.specstory/history/` (recovered substrate) are STILL there for live operation. This bundle is the git-tracked mirror.

## Cross-references

| Where | What |
|---|---|
| `~/.claude/plans/massive-weight-contextually-humming-walrus.md` | Plan, committed `c0b7150` on `4444J99/domus-semper-palingenesis` |
| `~/Workspace/organvm/organvm-corpvs-testamentvm/INST-INDEX-RERUM-FACIENDARUM.md` § `S-2026-04-30-specstory-rollup-distillation` | IRF rows DST-001..003, committed `c629b08` on `a-organvm/organvm-corpvs-testamentvm` |

## Reproducing

From a fresh clone:

```bash
# 1. Manifest (re-derives the 109-row TSV from the 39MB rollup)
python3 scripts/build-manifest.py

# 2. Reconcile (UUID-keyed join — assumes substrate at ~/Workspace/.specstory/history/)
python3 scripts/reconcile-v2.py

# 3. Index
python3 scripts/build-index.py

# 4. Ingest (uses ingest-supplementary.py:ingest_specstory upstream)
python3 scripts/run-specstory-ingest.py

# 5. Convert + distill
python3 scripts/convert-for-distill.py
organvm prompts distill --input ~/Workspace/.specstory/specstory-prompts-distill-input.json --dry-run --json
```

Each script writes to `~/Workspace/.specstory/`; copy back into `artifacts/` if you want to refresh this bundle.

## Three vacuums opened (per vacuum-radiation rule)

- **IRF-DST-001 [P1]** — `session-state-management` has no T1 SOP despite 98 prompts in 2-month window.
- **IRF-DST-002 [P3]** — `feature-expansion` T3 pattern uncovered (3 prompts).
- **IRF-DST-003 [P1]** — SpecStory CLI captures Gemini session HEADERS but DROPS BODIES (10 substrate files at exactly 5 lines).

All three entered into the IRF ledger of record at commit `c629b08`.
