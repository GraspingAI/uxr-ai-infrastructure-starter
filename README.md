# UXR AI Infrastructure Starter

> **Module 7 worked example branch:** `example/module-7-working-kit`

This branch shows one possible answer to the final course question in **Beyond Prompting: Building AI Infrastructure for UX Research**:

> What is our AI strategy for research, and how do we build it sustainably?

It is intentionally small. It is **not** a canonical “complete” kit and not a prescription for how every research team should work.

## The scenario

A small fictional Cyberdyne research team wants to use AI to help turn approved research material into stakeholder-facing readouts without allowing generated language to outrun the evidence.

The research evidence itself lives in a separate repository:

**Cyberdyne Research Corpus**  
https://github.com/GraspingAI/uxri-cyberdyne-research-corpus

That separation is deliberate. The kit should know **where its sources are and what status they have** without copying every source into the infrastructure repository.

## What is in this worked kit?

```text
uxr-ai-infrastructure-starter/
├── context/
│   └── project-context.md
├── sources/
│   └── source-index.md
├── workflows/
│   ├── synthesis-workflow.md
│   ├── planning-workflow.md
│   └── research-readout-workflow.md
├── docs/
│   ├── ai-operating-principles.md
│   ├── evidence-and-synthetic-boundaries.md
│   ├── delegation-and-ownership.md
│   ├── ai-strategy.md
│   └── github-lite.md
├── decisions/
│   ├── decision-log.md
│   └── first-implementation-move.md
├── templates/
│   ├── research-memory-blueprint.md
│   └── research-readout.md
└── archive/
    └── README.md
```

## How the course pieces show up

| Course piece | Worked example |
|---|---|
| AI Operating Principle | `docs/ai-operating-principles.md` |
| Reusable Context | `context/project-context.md` |
| Research Memory + Workflow Library | `sources/` + `workflows/` + the external corpus |
| Decision / Planning Workflow | `workflows/planning-workflow.md` |
| Research Reuse + Evidence Boundaries | `workflows/research-readout-workflow.md` + `docs/evidence-and-synthetic-boundaries.md` |
| Synthetic Research Use Spec | `docs/evidence-and-synthetic-boundaries.md` |
| Delegation + Ownership | `docs/delegation-and-ownership.md` |
| First Implementation Move | `decisions/first-implementation-move.md` |

## One workflow through the system

```text
approved research sources
        ↓
AI candidate draft
        ↓
claim ↔ evidence check
        ↓
researcher approval
        ↓
stakeholder readout
        ↓
decision log
```

The model is only one component. The useful infrastructure is the maintained relationship among context, sources, workflow rules, review, boundaries, and ownership.

## Worked strategy statement

See `docs/ai-strategy.md` for the full example. In short:

> We use AI to help plan and draft stakeholder-facing research communication when the decision, source set, and evidence boundary are explicit, using approved indexed research material and reusable project context, with researcher review before any finding, implication, or recommendation travels. We do not use AI output or synthetic material as evidence about users, and we do not delegate final claim strength or product decisions.

## Why this is a branch

The `main` branch remains the smaller research-memory starter used earlier in the course. This branch shows what happens when that starter is extended into a more connected working kit.

That is also the versioning lesson: **main can stay stable while a branch makes a proposed change visible and reviewable.**

## You do not need GitHub

The same structure could live in Google Drive, Docs, Sheets, Notion, a research repository, or another approved system. The folder names are not the point.

The point is whether someone can tell:

- what context applies;
- which sources are allowed and current;
- what AI may do;
- what a person must review;
- what may not be claimed;
- who owns maintenance;
- what the team is trying first.

## Public-repository safety boundary

Everything in this example is fictional and synthetic.

Do not put confidential or identifying research material into a public copy of this repository. Real research should use only organization-approved systems, access controls, retention practices, and AI environments.

---

Built by [GraspingAI](https://www.graspingai.com/) for the UXR Institute course **Beyond Prompting: Building AI Infrastructure for UX Research**.
