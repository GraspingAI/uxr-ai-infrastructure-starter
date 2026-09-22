# Research Readout Workflow

**State:** Current worked example  
**Owner:** Cyberdyne Research  
**Last updated:** 2026-09-21

## Purpose

Use AI to help draft a stakeholder-facing research readout while preserving the relationship between claims, evidence, scope, contradiction, and human judgment.

## Inputs

Required:

- `context/project-context.md`;
- `sources/source-index.md`;
- the decision or audience for the readout;
- approved in-scope research sources.

For the September Auto-Actions example, begin with C-01, C-02, and C-08. Use C-03 for traceability. Bring in C-04 or C-05 only when their different scope is relevant. C-07 may explain decision context. Do not use C-06 as research evidence.

## Workflow

1. **State the audience and decision.**  
   What is this readout supposed to help someone understand or decide?

2. **Confirm the source set.**  
   Make the in-scope IDs explicit before drafting.

3. **Draft by evidence layer.**  
   Ask AI to keep these distinct:
   - observation / source;
   - reviewed finding;
   - interpretation;
   - implication;
   - recommendation;
   - uncertainty / limitation.

4. **Attach source IDs to consequential claims.**

5. **Check contradiction and scope.**  
   Ask what evidence complicates the claim and whether a different population, feature, or study is being silently generalized.

6. **Researcher claim review.**  
   For every consequential statement, choose:
   - keep;
   - qualify;
   - verify;
   - remove.

7. **Approve stakeholder language.**  
   A named researcher approves the final claims, caveats, and recommendation language before the readout travels.

8. **Record the decision.**  
   If the readout influences an organizational decision, record that separately in the decision log.

## Human review gate

No finding, implication, recommendation, or statement about what “users want” travels solely because the AI produced it.

Human review must have access to:

- the relevant source;
- source status;
- the decision context;
- enough time and authority to challenge the draft.

## Example

A draft such as:

> “Users want a confirmation step before Auto-Actions can be trusted.”

should be checked against C-02 and C-05.

A more defensible version might be:

> “In the September first-use study, 5 of 8 participants hesitated because they were unsure when Auto-Actions would act. Understanding the confirmation step was generally associated with greater comfort during setup, although two participants remained uncomfortable. Separate research with experienced power users suggests confirmation needs may differ in routine, high-frequency workflows.”

The revised version is longer because the evidence is genuinely more conditional.
