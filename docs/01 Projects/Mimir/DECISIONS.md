# Decisions

## 2026-07-22 - Validate the Protocol Before Creating an Application

Decision:

Prioritize the document protocol and its manual use with AI before developing an interface or automation.

Rationale:

The application must solve needs demonstrated by real use of the system, not assumptions.

Consequences:

Early releases focus on Markdown, structure, templates, and context-transfer tests.

## 2026-07-22 - Use Context Snapshot as the Entry Point

Decision:

Every active project will have a concise, current `CONTEXT.md`.

Rationale:

An AI needs to quickly identify the state and next action without reading the complete history.

Consequences:

Closing each session must update the snapshot whenever the project state changes.