# Validation Plan

## Purpose

Verify that Mimir provides enough structured context for a capable, low-cost model to complete a routine project-design session without relying on chat history.

## Scope

- Test project: WorldMind.
- Workflow: start from project documents, define the core gameplay loop, and close the session.
- Allowed inputs: only the documents listed under "Required Reading" in WorldMind's `CONTEXT.md`.
- Excluded inputs: prior chat history, undocumented assumptions, technical architecture decisions, and external research.

## Model Under Test

- Model name and version:
- Provider or environment:
- Date:
- Reason it qualifies as a capable, low-cost model:

## Procedure

1. Start a new conversation with no previous WorldMind context.
2. Provide only WorldMind's required-reading documents.
3. Ask the model to define a five-minute core gameplay loop and a bounded first-prototype scenario.
4. Ask the model to identify uncertainties rather than invent missing facts.
5. Close the session by proposing updates to `TASKS.md`, `DECISIONS.md`, and `CONTEXT.md`.
6. Record the outcome in a dated file in `03 Sessions/`.

## Pass Criteria

- The proposed gameplay loop is consistent with WorldMind's documented goal and current decisions.
- The first-prototype scenario has explicit entities, player actions, world responses, boundaries, and a progression condition.
- New decisions distinguish confirmed facts from hypotheses or ideas.
- The proposed document updates preserve valid links and the required document structure.
- The model identifies material gaps instead of claiming undocumented information as fact.

## Review Questions

- Did the required-reading set provide enough context?
- Which context fields were missing, unnecessary, or ambiguous?
- Did the model require clarification that should instead be represented in a document?
- Is the failure, if any, attributable to the model, the prompt, or the Mimir standard?

## Result

Status: Not run

Evidence:

Recommended changes: