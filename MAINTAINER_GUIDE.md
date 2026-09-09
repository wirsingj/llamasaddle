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

Provide the YAIML reference from the human prompt, workspace context, or a team-approved source at run time. Do not commit machine-specific reference paths, local drive names, user profile paths, `file://` URIs, localhost URLs, private workspace URLs, secrets, private transcripts, or raw sensitive logs into versioned project memory.

Phrases such as "update YAIML", "updated YAIML", "check new YAIML", "refresh YAIML", or "run a YAIML update" mean convention refresh, not an ordinary project-memory rewrite. For this repository, compare local YAIML scaffolding against the provided reference and update only compatible prompts, templates, discovery hints, agent-instruction pointers, or YAIML-maintenance guidance. Preserve project memory and the existing discovery layout unless a human explicitly authorizes a layout migration.

Phrases such as "clean up YAIML", "compress YAIML", "compact project memory", "prune project memory", or "prune SoT" mean to remove stale or repetitive memory while preserving current truth, evidence, human direction, decisions, unresolved conflicts, and uncertainty. Do not pad documents to meet budgets or delete necessary governed knowledge just to reduce word count.

This repository does not need local YAIML prompt or template copies unless it already keeps them for a concrete workflow. Do not add `prompts/` or `templates/` just because the reference has them. Preserve project-specific SoT, Architecture, Maintainer Guide, risks, commands, naming, and supporting documents unless the reference changes how future agents should maintain YAIML here.
