# Cognitive On-Ramps

Root Sequence repositories use a root-level `START-HERE.md` as a deliberately small cognitive on-ramp: a **TC;DP (“too complex; didn’t process”) mitigation layer** for new contributors, returning maintainers, and anyone meeting the work while overloaded.

The on-ramp is not a replacement README. It answers only enough to help a person form a usable mental model and choose one next route.

## Required shape

Each `START-HERE.md` should contain:

1. **In one sentence** — the smallest honest description.
2. **If you remember only three things** — the load-bearing distinctions.
3. **Current reality** — what exists now, separated from aspiration.
4. **The smallest useful map** — no more structure than a newcomer needs.
5. **Where it fits** — its relationship to the ecosystem without collapsing project autonomy.
6. **What to do next** — routes based on reader intent.
7. **Go deeper** — links to canonical detail.

Prefer plain language, short sections, and specific links. Preserve ambiguity when the project itself is unresolved. State private/public boundaries and evidence status where relevant.

## What it must not become

A cognitive on-ramp is not:

- a second canonical specification;
- a compressed copy of every README heading;
- marketing that turns goals into accomplishments;
- an automatically generated summary published without review;
- a reason to make every repository use identical language or structure beyond the small shared interface.

## Maintenance contract

Every on-ramp contains a `START-HERE-META` comment naming the files or areas that most often change its truth. Review the on-ramp in the same pull request when a change materially affects:

- project purpose or scope;
- current implementation or publication status;
- active frontier, recommended next action, or roadmap stage;
- top-level structure or navigation;
- ecosystem ownership or routing;
- privacy, canon, evidence, or authority boundaries.

Do **not** churn it for every small edit. “Relevant” means the reader’s smallest useful mental model or next route would become misleading.

## Automation boundary

Automation may:

- notice that a trigger source changed;
- verify that `START-HERE.md` exists and is linked from the README;
- check required headings and local links;
- open a draft pull request proposing an update;
- explain which source change made review necessary.

Automation must not:

- publish semantic rewrites directly to the default branch;
- move information from private to public repositories;
- invent project status, canon, evidence, or decisions;
- force an update when the on-ramp remains accurate;
- merge proposals without human review.

The preferred future loop is: **material project change → relevance check → draft proposal if needed → project-owner review → merge**.

## README link

Place a short link near the top of each root README:

```markdown
> **New, returning, or overloaded? Read [START-HERE.md](START-HERE.md) for the smallest useful map.**
```

Project-specific wording is welcome when it improves clarity.
