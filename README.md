# Root Sequence organization defaults

Shared contribution guidance, workflow templates, and repository-stewardship policy for Root Sequence projects.

## Project Stewardship

[`PROJECT_STEWARDSHIP.md`](PROJECT_STEWARDSHIP.md) defines the maintenance model for reducing repository drift and human memory load through conservative automation.

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
