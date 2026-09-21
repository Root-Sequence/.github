# Root Sequence Documentation System

Root Sequence uses a layered documentation system so depth can grow without forcing every reader—or every assistant—to reconstruct the whole organization from scattered files.

## The four layers

| Layer | Question it answers | Canonical location |
| --- | --- | --- |
| Cognitive on-ramp | “What is this, and where do I begin?” | each repository's `START-HERE.md` |
| Project context | “What do I need to understand before working here?” | each repository's `PROJECT-CONTEXT.md` |
| Project truth | “Where is the authoritative detail?” | the repository's named status, roadmap, decision, evidence, canon, or architecture files |
| Ecosystem graph | “How does this connect across projects?” | `root-sequence/ECOSYSTEM.md`, the Root Sequence Wiki, and the public-safe project registry |

The first two layers route to canonical detail; they do not replace it.

## Why one context document serves humans and AI

Markdown with stable headings and small YAML front matter is legible to people, language models, scripts, and future interfaces. Maintaining a separate prose briefing for humans and another for AI would create two summaries that can disagree.

`PROJECT-CONTEXT.md` therefore uses one shared contract:

1. purpose and canonical scope;
2. a source-of-truth map;
3. present reality, including what does **not** exist;
4. boundaries and non-goals;
5. repository structure;
6. typed ecosystem relationships;
7. working and verification rules;
8. an update contract.

Assistants should read `START-HERE.md` first, then `PROJECT-CONTEXT.md`, then only the canonical sources relevant to the task. This reduces context load without treating a summary as authority.

## Connections are typed edges

The goal is not an all-to-all web of links. The goal is a traversable graph in which every meaningful relationship has a type and a source.

Useful relationship types include:

- `broader-context`
- `focused-inquiry`
- `grounds`
- `tests`
- `informs`
- `adapts`
- `indexes`
- `discussion-hub`
- `private-overlay`
- `world-design`
- `narrative-expression`
- `autonomous-counterpart`

Two projects sharing a word or source does not establish a relationship automatically. The canonical ecosystem map or a reviewed Wiki record should explain consequential edges.

## Machine-readable registry

[`PROJECT_REGISTRY.yml`](PROJECT_REGISTRY.yml) provides a public-safe routing index for repositories, context documents, status sources, and high-level relationships. It is navigation metadata, not a replacement for project documents or private overlays.

The public Wiki may use this registry to generate links and review signals. It must not infer semantic equivalence, canon, publication approval, or private content from the registry.

## Update flow

```text
material project change
        ↓
canonical project source changes
        ↓
relevance check
        ├─ no orientation/context impact → no summary churn
        └─ material impact → draft START-HERE / PROJECT-CONTEXT update
                                      ↓
                              human review and merge
                                      ↓
                         Wiki/registry projection if needed
```

Automation may detect changes, validate structure and links, and propose draft pull requests. It must not silently decide project meaning, evidence, canon, ownership, or publication.

## Privacy rule

Public documentation and automation are complete without access to private repositories. The registry may include already-disclosed public-safe names and roles, but not private content. Private Wiki overlays may extend the graph; publication always moves through an explicit review decision.

## Change rule

Update this system when the documentation layers, relationship vocabulary, canonical organization map, registry schema, Wiki projection, or automation boundary changes. Project-specific facts belong in the project context and its canonical sources.
