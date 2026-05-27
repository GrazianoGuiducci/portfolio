# Security and Curation Boundary

This portfolio is meant to be reviewable by technical people without exposing
private runtime state.

## Never Include

- `.env` files;
- API keys, tokens, cookies, auth files;
- raw VPS logs;
- raw JSONL traces from private cycles;
- private handover files;
- node-specific boot instructions;
- private operator conversations;
- hidden GitHub repository links as primary references.

## Include After Curation

- condensed model files;
- selected diagrams;
- selected cycle reports;
- selected failed claims;
- public dashboard screenshots;
- public repository links;
- clear architecture notes.

## Review Rule

Anything copied from an internal repository must be checked for:

- local paths;
- names and notes that only make sense inside the VPS;
- private collaboration details;
- irrelevant operational noise;
- unstated assumptions.

