---
yaiml: 0.2
role: maintainer
title: LlamaSaddle Maintainer Guide
purpose: Current commands and maintenance procedure for LlamaSaddle.
belongs-here: verified commands, setup notes, diagnostics, danger zones, YAIML maintenance.
not-here: product direction, durable architecture, complete history.
durability: current-only; remove dead commands quickly.
budget: About 600 words; a working target, not a length to fill.
read-with: SOT; Architecture.
update-when: commands, setup, tests, dependencies, or repository structure change.
last-verified: not established; claims not rechecked in this refresh.
agent-guidance: Record only commands that exist or were actually run.
---

# LlamaSaddle Maintainer Guide

## Verified Commands

Check repository status:

```powershell
git status --short
```

No build, test, package, or runtime commands are currently present.

## YAIML Maintenance

Follow the synthesis, privacy, and retention rules in [AGENTS.md](AGENTS.md). Ordinary material updates replace changed facts and remove superseded or resolved state; keep one detailed home per fact. Measure affected memory before and after, compress safely first, and report necessary growth or retained budget overages in the task response.

For convention refresh requests (including "refresh YAIML"), obtain the human-provided, workspace-local, or team-approved reference at run time; request one if unavailable. Compare its update and init guidance with local instructions and maintenance notes. Keep private reference locations out of versioned files. Preserve project knowledge, local names, discovery layout/version, paths, and meaningful custom fields; layout migration requires explicit human authorization and consumer checks. Do not add prompt/template copies without a concrete local workflow.

For cleanup requests, remove stale or repetitive memory while preserving direction, evidence limits, decisions, uncertainty, unresolved conflicts, and governed records. Do not relocate history or delete necessary knowledge to meet budgets. Verify affected links, discovery paths, stable headers, and instruction scope; rerunning the same refresh should leave healthy files unchanged. Report configured persistence separately from observed fresh-session loading.
