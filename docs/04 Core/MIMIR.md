# Mimir

## Knowledge System for AI-Assisted Projects

Version: `0.2.1`

Status: Experimental

## Purpose

Mimir is an open standard for managing project knowledge with AI assistance. Information lives in Markdown files: chats are temporary, while documents are permanent.

## Principles

- Knowledge belongs to the project, not to a specific AI.
- Documents are the source of truth.
- The format must be human-readable and compatible with any AI.
- The system must be maintainable from a phone.
- Every project must be able to recover its state without reading the complete conversation history.
- English is the canonical language for Mimir's public documentation.

## Vault Structure

```text
docs/
├── 00 Inbox/       # Unsorted captures
├── 01 Projects/    # Active projects
├── 02 Knowledge/   # Reusable knowledge
├── 03 Sessions/    # Chronological work record
├── 04 Core/        # Mimir standard, protocol, and templates
└── 99 Archive/     # Completed material
```

## Standard Documents

- `PROTOCOL.md`: how a person or AI must read and update the vault.
- `TEMPLATES.md`: templates for project documents and sessions.
- `CHANGELOG.md`: notable changes to the Mimir standard.

## Minimum Project Documents

- `README.md`: purpose, scope, and general status.
- `CONTEXT.md`: operational snapshot for resuming work.
- `TASKS.md`: actionable, prioritized work.
- `DECISIONS.md`: current decisions and their rationale.

Optional documents include `IDEAS.md`, `SPECS.md`, and `ROADMAP.md`.

## Current Status

Mimir v0.2 defines the minimum protocol and templates for validating context transfer across sessions.

Last updated: 2026-07-22
