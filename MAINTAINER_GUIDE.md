---
yaiml: 0.2
role: maintainer
title: LlamaSaddle Maintainer Guide
purpose: Current commands and maintenance procedure for LlamaSaddle.
belongs-here: verified commands, setup notes, diagnostics, danger zones, YAIML maintenance.
not-here: product direction, durable architecture, complete history.
durability: current-only; remove dead commands quickly.
read-with: SOT; Architecture.
update-when: commands, setup, tests, dependencies, or repository structure change.
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

Phrases such as "update YAIML", "updated YAIML", "check new YAIML", or "run a YAIML update" mean: compare this repository's local YAIML setup against a human-provided, workspace-provided, or team-approved YAIML reference, refresh compatible convention scaffolding, and preserve LlamaSaddle-specific project memory.

Do not commit machine-specific YAIML reference paths, local drive names, user profile paths, `file://` URIs, localhost URLs, secrets, private chat transcripts, or raw sensitive logs.
