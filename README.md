# Root Sequence organization defaults

> **New, returning, or overloaded? Read [START-HERE.md](START-HERE.md) for the smallest useful map.**

Shared contribution guidance, workflow templates, and repository-stewardship policy for Root Sequence projects.

- [`DOCUMENTATION_SYSTEM.md`](DOCUMENTATION_SYSTEM.md) defines the shared human/AI context layers and typed relationship graph.
- [`PROJECT_REGISTRY.yml`](PROJECT_REGISTRY.yml) is the public-safe machine-readable project routing index.
- [`COGNITIVE_ONRAMPS.md`](COGNITIVE_ONRAMPS.md) defines the short `START-HERE.md` layer.

## Project Stewardship

[`PROJECT_STEWARDSHIP.md`](PROJECT_STEWARDSHIP.md) defines the maintenance model for reducing repository drift and human memory load through conservative automation.

It also defines the maintenance boundary around the Root Sequence [`RS?` thought-routing convention](https://github.com/Root-Sequence/root-sequence/blob/main/THOUGHT_ROUTING.md): deterministic validation and index repair are automatable; canonical-home, equivalence, canon, visibility, and publication decisions remain review work.

The intended pattern is:

- automate deterministic maintenance
- surface semantic review work
- treat documentation as part of the dependency graph
- review stale/orphaned material before deletion
- reconcile repositories periodically so small omissions do not accumulate

## Workflow template

[`workflow-templates/repository-coherence.yml`](workflow-templates/repository-coherence.yml) is an organization workflow template for repositories that expose maintenance scripts such as:

```bash
npm run docs:sync
npm run docs:check
npm run docs:audit
```

Repositories can adopt the template incrementally. A repository without those scripts simply skips the corresponding maintenance steps.

The longer-term plan is to move reusable maintenance logic into a dedicated cross-project stewardship engine while organization `.github` repositories remain thin adapters/templates.
