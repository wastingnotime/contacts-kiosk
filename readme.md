# Contacts Kiosk

## What This Repository Is

This repository is the working home for the Contacts Kiosk project: an application and supporting artifacts for a kiosk-style contact lookup experience.

The repository keeps the product work, the semantic model, the slice definitions, and the implementation evidence in one place so the project can evolve in small, explicit steps.

## Role Of MRL

MRL is the method used here, not the product itself.

It provides the artifact-driven loop for shaping this repository:

```text
extract -> refine -> build -> egd -> release -> expose -> living -> extract
```

In this repository, MRL is used to:

- capture project meaning explicitly in semantic docs
- turn that meaning into bounded slice definitions
- implement and test one slice at a time
- record expectation gaps and release decisions as repository artifacts

That means the MRL docs and skills define how work is organized, while the repository content defines what the Contacts Kiosk project is trying to build.

This repository uses a split-license arrangement:

- MRL core and process artifacts remain under MIT
- all other source code, documentation, and project artifacts are under MPL-2.0

## Working With The Repository

Read these files first:

- `docs/operating/mrl_reference.md`
- `docs/operating/skills_workflow.md`
- `docs/operating/packs.md`
- `docs/operating/best_practices.md`
- `architecture.md`
- `groundrules.md`
- `docs/building/project_structure.md`

Then use the MRL loop to refine the Contacts Kiosk model in small, documented increments.

## Notes

- Keep the project purpose in the semantic and slice artifacts, not in conversational memory.
- Treat `work/` as repository memory, not scratch space.
- Prefer one small slice over broad scaffolding.
