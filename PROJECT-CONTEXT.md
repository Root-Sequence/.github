---
context_format: root-sequence-project-context/v1
project_id: organization-infrastructure
repository: Root-Sequence/.github
visibility: public
status: active-shared-infrastructure
---

# Project Context — Root Sequence Organization Infrastructure

## Purpose and scope

This repository owns public shared contribution guidance, pull-request defaults, workflow templates, stewardship policy, and documentation contracts for Root Sequence repositories.

It provides thin adapters and conventions. Individual repositories remain authoritative for their own meaning, status, implementation, evidence, privacy, and canon.

## Source-of-truth map

| Question | Canonical source |
| --- | --- |
| Repository orientation | [`README.md`](README.md) |
| Maintenance philosophy and event model | [`PROJECT_STEWARDSHIP.md`](PROJECT_STEWARDSHIP.md) |
| Cognitive on-ramp standard | [`COGNITIVE_ONRAMPS.md`](COGNITIVE_ONRAMPS.md) |
| Documentation layers and graph contract | [`DOCUMENTATION_SYSTEM.md`](DOCUMENTATION_SYSTEM.md) |
| Public-safe machine routing | [`PROJECT_REGISTRY.yml`](PROJECT_REGISTRY.yml) |
| Reusable workflow starters | `workflow-templates/` |

## Current reality

The repository supplies policy and templates adopted incrementally. It is not yet a complete cross-project stewardship engine. Passing a structural check does not prove project documentation is semantically current. Shared standards do not silently modify repositories that have not adopted them.

## Repository structure

Root Markdown files hold organization policy and documentation contracts. `workflow-templates/` contains optional workflow starters. `profile/` controls GitHub organization profile content.

## Ecosystem connections

This is the organization-infrastructure layer. Root Sequence owns the semantic ecosystem map; the Wiki owns public findability and graph projections; `wiki-private` owns private graph extensions; each project owns its substantive truth.

## Working rules

- Automate memory, not judgment.
- Deterministic checks and generated projections may update automatically.
- Semantic rewriting, ownership, equivalence, canon, visibility, and publication require review.
- Never treat old age or low connectivity as sufficient reason to delete material.
- Keep public automation independent of private repository contents.

## Update contract

Review when stewardship policy, shared templates, documentation layers, registry schema, automation boundaries, or organization-wide contribution rules change.
