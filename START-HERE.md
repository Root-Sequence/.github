# Start Here — Root Sequence Organization Infrastructure

> **TC;DP:** This repository holds shared defaults and maintenance patterns so every project does not have to remember the same organizational chores independently.

<!-- START-HERE-META
format: 1
review_sources: README.md, PROJECT_STEWARDSHIP.md, COGNITIVE_ONRAMPS.md, workflow-templates
review_when: stewardship policy, shared workflow, onboarding standard, or automation-boundary changes
END-START-HERE-META -->

For a comprehensive working briefing, continue to [PROJECT-CONTEXT.md](PROJECT-CONTEXT.md).

## In one sentence

The `.github` repository defines shared contribution guidance, workflow templates, and conservative stewardship conventions for the Root Sequence organization.

## If you remember only three things

1. Automate deterministic checks; surface semantic judgment for review.
2. Documentation is part of the dependency graph, not cleanup to postpone indefinitely.
3. Cross-project automation must preserve canonical ownership, privacy, provenance, and human approval.

## Current reality

The repository currently provides stewardship policy and workflow templates that projects may adopt incrementally. It is not yet a complete cross-project stewardship engine, an authority that can rewrite every project, or a guarantee that documentation is current merely because checks pass.

## The smallest useful map

- [`PROJECT_STEWARDSHIP.md`](PROJECT_STEWARDSHIP.md) — maintenance philosophy and boundaries.
- [`COGNITIVE_ONRAMPS.md`](COGNITIVE_ONRAMPS.md) — the organization-wide `START-HERE.md` standard and update policy.
- `workflow-templates/` — optional organization workflow starters.
- `profile/` — organization-profile content shown on GitHub.

## Where it fits

Individual repositories remain responsible for their own truth, scope, tests, and decisions. This repository carries small shared conventions that reduce drift and memory load without flattening project differences.

## What to do next

- **Maintaining a repo:** use the stewardship checklist and keep its `START-HERE.md` aligned with material changes.
- **Automating a task:** first ask whether the result is deterministic or requires semantic review.
- **Changing a shared rule:** propose it here, then adopt it incrementally rather than assuming every repository changed automatically.

## Go deeper

Read [`PROJECT_STEWARDSHIP.md`](PROJECT_STEWARDSHIP.md) and [`COGNITIVE_ONRAMPS.md`](COGNITIVE_ONRAMPS.md). The goal is less human memory burden, not more ceremony.
