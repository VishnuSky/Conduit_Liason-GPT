# OWNER.md

Layer ownership for Conduit Liaison GPT (Public Law Scout module).

| Path / area | Owner agent | Notes |
|---|---|---|
| `docs/adr/`, privacy, consent, redaction, progressive literacy copy | Claude | Safety/anonymity and policy ADRs |
| Official .gov / Legal-GPT bridge, cite-or-abstain briefs, tip-channel cards | Grok (Domestic Connector / PLS track) | Verified contacts only; no invented emails |
| Data pipeline, CI, API stubs, reporting UI against shared schemas | Anti-Gravity | Implements contracts in `/schemas` |

## Rules
- Do not edit another owner's paths without a PR review from that owner.
- Never auto-submit tips or evidence to agencies; human confirms every outbound report.
- Audio mode assists routing and note-taking only; it does **not** create legal chain of custody.
- Emergencies: 911 path stays outside the model.
