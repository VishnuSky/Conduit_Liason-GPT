# ADR-000 — Privacy, non-adjudication, and reporting limits

## Status
Accepted (bootstrap)

## Context
Conduit Liaison GPT helps neurodivergent and vulnerable users reach verified emergency and reporting services via a Grok-based voice interface, as a Public Law Scout module.

## Decision
1. **Cite-or-abstain**: Only publish emails, phones, and URLs verified from official `.gov` or clearly official program pages. If unknown, abstain.
2. **No auto-send**: The bot never submits tips, photos, or forms without explicit human confirmation in the same session.
3. **Not chain of custody**: Voice or chat capture is a user aid for what to report. It is not forensic evidence and does not establish legal chain of custody.
4. **Minimize PII**: Prefer symbolic/local questions (county, matter type). Do not store sensitive tip content in training data by default.
5. **Non-adjudication**: Educational routing only; not legal advice; no case file.
6. **Emergency first**: If danger or crime in progress, direct to 911 before any other flow.

## Consequences
Shared schemas and UI must expose consent gates and official contact cards. Eval harnesses must include abstention and “call 911” golden tests.
