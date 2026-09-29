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

## Shared epistemic practice

Root Sequence treats inquiry as error-correcting infrastructure. The canonical methods live in the conceptual commons:

- [Epistemic Contrast](https://github.com/Root-Sequence/root-sequence/blob/main/research/methods/epistemic-contrast.md)
- [Deliberative Inquiry](https://github.com/Root-Sequence/root-sequence/blob/main/research/methods/deliberative-inquiry.md)
- [Collective Judgment and Manufactured Consensus](https://github.com/Root-Sequence/root-sequence/blob/main/analysis/collective-judgment-and-manufactured-consensus.md)

Repository-specific work should **translate rather than duplicate** these methods. As applicable:

- seek contrasting roles, assumptions, incentives, and affected perspectives before treating a model as complete;
- distinguish factual, causal, definitional, probabilistic, and normative disagreement;
- weight claims by evidence and method rather than by the number or status of people asserting them;
- record uncertainty, counterexamples, and what would change the current model;
- for consequential collective decisions, build sufficient shared understanding before authorization;
- preserve dissent and process-integrity concerns instead of manufacturing consensus;
- observe outcomes and revise when reality contradicts the model.

A useful shorthand is **“reality gets veto power.”** It means no Root Sequence conclusion is protected from revision merely because it is elegant, familiar, politically congenial, or already embedded in a project.

## Make decisions legible

For consequential work, distinguish clearly between:

- established behavior or evidence;
- proposals and hypotheses;
- experiments or prototypes;
- accepted decisions;
- unresolved questions.

Prefer links to canonical material over copied text that will drift.

For a thought or connection that may span repositories, use the Root Sequence [`RS?` routing convention](https://github.com/Root-Sequence/root-sequence/blob/main/THOUGHT_ROUTING.md). Capture it once, search existing homes, and record deliberate project-specific transformations rather than pasting the same note into several repositories.

## Pull requests

A pull request should make it possible for another contributor to understand:

1. what changed;
2. why it changed;
3. what was tested or verified;
4. what documentation was checked or updated;
5. what remains unresolved, if anything.

Use the organization pull-request template when a repository does not define its own.
