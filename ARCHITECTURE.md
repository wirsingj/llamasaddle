---
yaiml: 0.2
role: architecture
title: LlamaSaddle Architecture
purpose: Durable system shape and boundaries for LlamaSaddle.
belongs-here: implemented components, boundaries, data flow, invariants, retired approaches.
not-here: current priorities, command reference, speculative product design.
durability: stable; update when implementation structure exists or changes.
budget: About 600 words; a working target, not a length to fill.
read-with: SOT; Maintainer Guide.
update-when: source files, runtime surfaces, data model, or external integrations are added.
last-verified: not established; claims not rechecked in this refresh.
agent-guidance: Do not invent architecture before implementation evidence exists.
---

# LlamaSaddle Architecture

No implementation architecture is present yet.

## Current Boundary

The repository currently contains only project-memory files and Git metadata. Any future architecture should be derived from committed source, tests, docs, or explicit human direction.

## Known Invariants

- Preserve YAIML as portable repository memory.
- Do not add dependencies, runtime tooling, or product structure without explicit project direction.
