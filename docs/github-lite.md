# GitHub Lite for Researchers

You do not need GitHub to build useful research memory. Google Drive, Docs, Sheets, a research repository, or another shared system may be the right choice.

This page is for people who are curious about what Git adds when exact changes, parallel experimentation, review, and rollback start to matter.

## Five ideas

### Main

The version people should currently rely on.

### Branch

A safe line of change. It starts from the current version but lets you experiment without changing what everyone else is using.

### Commit

A checkpoint with a short explanation of what changed. A good commit message names the change rather than merely saying “update.”

### Diff

The exact difference between two versions. A diff makes review concrete: you can inspect what was added, removed, or rewritten.

### Review + merge

A decision about whether a proposed change should become part of the shared version.

## The research analogy

Imagine your team has a synthesis workflow everyone relies on. You want to add a stronger contradiction check, but you do not want to overwrite the current workflow while you test the idea.

You can:

1. start a **branch** from the current workflow;
2. make the change;
3. save a meaningful **commit**;
4. inspect the **diff**;
5. open a review;
6. **merge** it if the change should become the new shared version.

If the experiment fails, the current version never had to be disturbed.

## See it in this repository

Pull request **#1, “Strengthen contradiction check in synthesis workflow,”** is an intentionally small example. It changes one shared workflow so you can inspect the branch, commit, diff, and review context without needing to create anything yourself.

## Optional practice

If you already use GitHub, try this with fictional or synthetic material:

1. Create a branch from `main`.
2. Make one small improvement to a workflow or template.
3. Commit it with a message that explains the change.
4. Open a pull request explaining why it should become part of the shared version.
5. Read the diff as if you were the reviewer.

The goal is not to learn Git commands. The goal is to practice making changes visible, reviewable, and reversible.

## When Git may earn its keep

Git becomes more useful when:

- several people maintain the same text-based workflows or infrastructure;
- exact changes matter;
- people need safe parallel experiments;
- changes should be reviewed before becoming canonical;
- rollback and durable history matter.

For a single researcher's context file or an ordinary project folder, a simpler system may be entirely adequate.
