# rulespec-us-az

This repository is archived. Its canonical content now lives in
[`TheAxiomFoundation/rulespec-us`](https://github.com/TheAxiomFoundation/rulespec-us)
under `us-az/`; keep all future RuleSpec work there.

Arizona RuleSpec encodings.

## Contents

- `statutes/`, `regulations/`, or `policies/`: RuleSpec YAML when encoded rules are added.
- `.github/workflows/`: wrapper around the shared RuleSpec validation workflow.

## Conventions

Use RuleSpec YAML under `statutes/`, `regulations/`, or `policies/` for encoded rules. Do not add source text, source registry sidecars, generated source payloads, extracted document snapshots, or wave manifests to Git; source material belongs in the corpus database/object storage.

In the canonical monorepo, Arizona-administered materials live under `us-az/`; shared federal materials live at the country root.
