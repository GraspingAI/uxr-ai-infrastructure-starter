# Synthesis Workflow

**Status:** Current  
**Owner:** Cyberdyne Research  
**Last updated:** 2026-08-24  
**Change rule:** Proposed changes should explain what problem they are solving and should be reviewed before becoming the shared default.

## Purpose

Create a first-pass synthesis from approved research material while keeping source boundaries and researcher judgment visible.

## Inputs

- approved source material listed in `sources/source-index.md`;
- the current project context in `context/project-context.md`;
- the specific synthesis question for the task at hand.

## Workflow

1. Confirm which sources are in scope.
2. Separate direct evidence, researcher inference, and stakeholder assumptions.
3. Ask the AI system to organize patterns and tensions without resolving uncertainty on its own.
4. **Run a contradiction pass before writing the dominant story.** List evidence that weakens, complicates, or conflicts with each candidate pattern.
5. Trace consequential candidate findings back to source IDs.
6. Review the candidate synthesis manually before it is treated as a reviewed output.
7. Record open questions, contradictory evidence, and missing support.

## Contradiction pass

For each candidate finding, ask:

- What evidence points in the other direction?
- Is the apparent pattern driven by only one participant, segment, or source?
- Are we treating absence of evidence as agreement?
- Would the claim need to become narrower if the conflicting evidence were shown next to it?

Do not force contradictions into a single resolved narrative. Preserve disagreement when the evidence warrants it.

## Output standard

A synthesis should make it possible to distinguish:

- what participants actually said or did;
- what pattern the researcher is inferring;
- where evidence disagrees;
- what remains uncertain;
- which sources support consequential claims.

## Stop conditions

Stop and return to the source material when:

- a consequential claim cannot be traced to evidence;
- a source is missing or its status is unclear;
- contradictory evidence has been flattened into a single story;
- the request requires a decision the available evidence cannot support.

## What this workflow does not do

It does not decide which findings should ship, replace researcher review, or turn generated language into evidence.
