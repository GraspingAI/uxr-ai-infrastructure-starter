# UXR AI Infrastructure Starter

A small, public example of what maintainable AI-enabled UX research infrastructure can look like.

Created by **GraspingAI** for the UXR Institute course **Beyond Prompting: Building AI Infrastructure for UX Research**.

This is **not a prompt library** and not a prescription for how every research team should organize its work. It is a fictional, deliberately lightweight example for exploring four practical questions:

- **Find** — Can the next researcher locate the right thing?
- **Trust** — Can they tell what it is, where it came from, and whether it is current?
- **Reuse** — Can useful context, workflows, and templates survive beyond one chat or project?
- **Maintain** — Is ownership, change, review, and retirement visible?

## What is in this repository?

```text
uxr-ai-infrastructure-starter/
├── context/
│   └── project-context.md
├── sources/
│   └── source-index.md
├── workflows/
│   └── synthesis-workflow.md
├── templates/
│   ├── research-memory-blueprint.md
│   └── research-readout.md
├── decisions/
│   └── decision-log.md
├── archive/
│   └── README.md
└── docs/
    └── github-lite.md
```

The example organization is **Cyberdyne Systems**, a fictional course case. The files are synthetic and exist only to demonstrate infrastructure patterns.

## Start here

You do not need Git or GitHub to use the underlying ideas in this repository. The same principles can be implemented in Google Drive, Docs, Sheets, Notion, a research repository, or another system your organization already uses.

If you *do* use GitHub, this repository is also a small example of versioned research infrastructure. You can inspect the commit history, compare changes, create a branch, or use the repository as a starting point for your own fictional practice environment.

### The basic versioning model

- **Main** — the version people should currently rely on.
- **Branch** — a safe line of change that does not disturb the current version.
- **Commit** — a meaningful checkpoint with a short explanation of what changed and why.
- **Diff** — the exact change between versions.
- **Review / merge** — the decision to incorporate a proposed change into the shared version.

The point is not Git itself. The point is to make consequential changes visible, reviewable, and reversible.

If you want the non-scary version first, read [`docs/github-lite.md`](docs/github-lite.md). Pull request [#1](../../pull/1) is an intentionally small live example of **branch → commit → diff → review → merge**.

## How to use this starter

1. Browse the repository before changing anything.
2. Choose the smallest scope you actually need: a recurring workflow, a research project, a team library, or another bounded system.
3. Keep only the structure that helps people find, trust, reuse, and maintain the work.
4. Use the lightest versioning system that preserves the history and accountability your workflow needs.

If you want to design your own structure first, start with [`templates/research-memory-blueprint.md`](templates/research-memory-blueprint.md).

## Public-repository safety boundary

**Do not put confidential or identifying research material into a public copy of this repository.**

That includes participant data, raw notes or transcripts, client information, employer-confidential material, internal product plans, proprietary prompts or workflows, credentials, or other protected information.

If you want to experiment publicly, use the supplied fictional material or your own synthetic examples. If you translate the structure into real work, use only systems and access controls approved by your organization.

## What this is trying to model

A useful research-memory system should make it possible for someone to answer questions such as:

- What is this artifact?
- Why was it created?
- What source material does it depend on?
- Is it source material, AI-generated working material, reviewed output, or a decision record?
- Who owns it?
- What changed?
- Which version should be used?
- What has been superseded?
- What can safely be reused?

The exact folder names matter less than whether the system preserves those relationships.

## License

Except where otherwise noted, the original educational material in this repository is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. You may share and adapt it, including commercially, with appropriate attribution and an indication of changes.

Suggested attribution: **“UXR AI Infrastructure Starter by GraspingAI, licensed CC BY 4.0.”**

See `LICENSE` for details.

The GraspingAI name, logos, and other trademarks are not licensed for reuse by the Creative Commons license.

---

Built by [GraspingAI](https://www.graspingai.com/) as a public learning resource. The repository will evolve as the course develops.
