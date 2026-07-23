# Mimir Protocol

## Goal

Enable a person or AI to resume and update a project without relying on previous conversations.

## Reading Order

When starting work on a project, read in this order:

1. `README.md` to understand the purpose, scope, and general status.
2. `CONTEXT.md` to learn the current goal, state, and next action.
3. The documents linked under "Required Reading" in `CONTEXT.md`.
4. `TASKS.md` or `DECISIONS.md` only when they are relevant to the current work.

Reading every past session is not required to begin.

## Authority Order

When documents conflict, this order prevails:

1. Current `CONTEXT.md` and `DECISIONS.md`.
2. `README.md`, `SPECS.md`, and `ROADMAP.md`.
3. `TASKS.md`.
4. Records in `03 Sessions/`.
5. `IDEAS.md` and `00 Inbox/`.

## Starting a Session

1. Read the Context Snapshot.
2. Confirm the next action and its definition of done.
3. Record an open question before assuming undocumented information.

## Closing a Session

1. Update `TASKS.md` whenever a task status changes.
2. Record every decision that affects scope, architecture, or priorities in `DECISIONS.md`.
3. Update `CONTEXT.md` with the actual state, risks, and next action.
4. Create a concise record in `03 Sessions/` using the corresponding template.

## Model Selection

1. Select the model before starting a bounded session whenever practical.
2. Use capable, low-cost models for routine work when the required documents provide sufficient context.
3. Use higher-capability models for complex reasoning, critical reviews, and high-risk decisions.
4. Avoid switching models mid-session when it would discard useful context caching; prefer a new session with the documents required for the next task.
5. Record the model and environment when they materially affect a validation result or project decision.

## Writing Rules

- Separate facts, decisions, hypotheses, and ideas.
- Do not present an AI inference as a confirmed fact.
- Link related documents instead of duplicating content.
- Keep `CONTEXT.md` concise, current, and actionable.
- Move completed material to `99 Archive/` without removing its history.