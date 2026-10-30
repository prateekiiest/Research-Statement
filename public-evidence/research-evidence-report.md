# Research Process & AI-Use Evidence Report

> **Evidence assessment:** INCONCLUSIVE — no Cursor hook log is available; absence of a log cannot establish non-use

- Generated (UTC): 2026-10-30T06:22:34.778245+00:00
- Observed events: 34
- Observed period: 2026-10-30T05:33:25.225+00:00 to 2026-10-30T06:21:34.766+00:00
- Snapshot hashes checked: 33
- Snapshot failures: 0

## 1. Executive assessment

This report summarizes machine-observed research-workspace metadata. It helps reviewers understand the evidence without reading raw JSONL logs. It is not a certification of authorship or proof that AI was never used.

## 2. Integrity checks

| Log source | Present | Hash chain | Events |
|---|---:|---:|---:|
| macOS filesystem collector | Yes | Pass | 34 |
| Cursor hooks | No | Not available | 0 |
| VS Code extension | No | Not available | 0 |

## 3. Research activity observed

- Event categories: {"file_baseline": 14, "git_head_observed": 1, "saved_file_version": 19}
- Evidence classes: {"filesystem_observed": 33, "git_observed": 1}
- File types observed: {".bib": 1, ".json": 1, ".log": 8, ".pdf": 6, ".py": 6, ".tex": 11}

Counts describe recorded events, not intellectual contribution, quality, or authorship.

## 4. AI-tool activity assessment

- Cursor-related event count: **0**
- Cursor event types: {}
- Model labels observed: {}

A Cursor hook event shows that Cursor emitted that event. It does not quantify AI-generated text. No matching event means only that none appears in the available Cursor log.

## 5. Coverage limitations

- Offline ideation and thoughts are not observable.
- Browser literature searches, external chat tools, terminal commands, and other devices are not comprehensively monitored.
- Cursor events are visible only when hooks are installed, enabled, and functioning.
- Editor hashes and file snapshots do not identify the person or tool that produced text.
- Polling can miss edits that occur and revert between scans; Overleaf changes appear only after local synchronization.
- A local user can stop or rewrite logs. Hash chains detect inconsistency, not a determined administrator.
- AI-text detectors and writing-style scores are not treated as authorship proof.

## 6. Verdict and interpretation

**INCONCLUSIVE — no Cursor hook log is available; absence of a log cannot establish non-use**

The conclusion is limited to the instrumented logs available at audit time. A valid hash chain supports internal consistency; it does not prove completeness, immutability, or authorship.

## 7. Reproducibility

Run python3 scripts/analyze_research_evidence.py. The machine-readable summary is public-evidence/research-evidence-audit.json. Keep raw logs and snapshots private; inspect generated files before publishing.
