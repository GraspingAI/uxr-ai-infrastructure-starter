# Synthesis Workflow

**State:** Current  
**Owner:** Cyberdyne Research  
**Last updated:** 2026-08-26  
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
4. Trace consequential claims in the AI output back to source IDs.
5. Review the AI output manually before any claim is treated as a reviewed finding.
6. Record open questions, contradictory evidence, and missing support.

## Output standard

A synthesis should make it possible to distinguish:

- what participants actually said or did;
- what pattern the researcher is inferring;
- where evidence disagrees;
- what remains uncertain;
- which sources support consequential claims;
- what remains AI output versus what has become a reviewed finding.

## Stop conditions

Stop and return to the source material when:

- a consequential claim cannot be traced to evidence;
- a source is missing or its state is unclear;
- contradictory evidence has been flattened into a single story;
- the request requires a decision the available evidence cannot support.

## What this workflow does not do

It does not decide which claims are warranted, replace researcher review, or turn AI-generated language into evidence.
