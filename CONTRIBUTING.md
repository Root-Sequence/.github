# Contributing across Root Sequence

This is the default contribution baseline for Root Sequence repositories that do not provide a repository-specific `CONTRIBUTING.md`.

Repository-specific instructions take precedence when present.

## Start from the repository

Treat the current repository as the authoritative source for that project's implementation, architecture, status, and documentation.

Before making a consequential change, read the repository's relevant entry points, such as its root `README.md`, local contribution guide, status/roadmap documents, architecture documents, and decision records where they exist.

## Documentation coherence

When a canonical idea, capability, architecture, workflow, or project relationship changes, check whether the change should propagate to the documents that help people discover and correctly understand it.

Use this checklist as applicable:

- **Nearest README/index** — update the closest directory README, index, or navigation document when its contents or scope changed.
- **Root README** — update when the change affects what the project is, contains, supports, or prioritizes.
- **Status** — update when the change alters the project's current reality, maturity, capabilities, or known limitations.
- **Roadmap** — update when the change alters planned work, sequencing, milestones, or priorities.
- **Architecture / decision records** — update when the change modifies a consequential boundary, invariant, implementation decision, or architectural assumption.
- **Cross-project / ecosystem references** — update when the relationship between this repository and another project changes.

Do not update documents mechanically or duplicate the same explanation everywhere. The goal is **coherence without duplication**: important changes should be discoverable from the right entry points, while detailed material should remain canonical in the most appropriate place.

## Make decisions legible

For consequential work, distinguish clearly between:

- established behavior or evidence;
- proposals and hypotheses;
- experiments or prototypes;
- accepted decisions;
- unresolved questions.

Prefer links to canonical material over copied text that will drift.

## Pull requests

A pull request should make it possible for another contributor to understand:

1. what changed;
2. why it changed;
3. what was tested or verified;
4. what documentation was checked or updated;
5. what remains unresolved, if anything.

Use the organization pull-request template when a repository does not define its own.
