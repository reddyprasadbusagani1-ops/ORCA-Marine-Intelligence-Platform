# Contributing to ORCA

Thank you for your interest in CodeNova's ORCA project.

## Current status

ORCA is currently a planning and documentation starter repository. Application code and live integrations are not yet implemented. Contributions should not describe planned functionality as completed.

## Contribution workflow

1. Discuss a proposed change with the team before substantial work.
2. Keep changes focused and document the reason for the change.
3. For data integrations, record provider, product, access method, licence, units, coordinate reference system, temporal semantics and known limitations.
4. For safety-related logic, provide authoritative references, test cases and explicit limitations. Do not invent thresholds.
5. Add or update tests with implementation changes.
6. Update the relevant README or documentation when architecture, setup or status changes.

## Code quality expectations

- Prefer clear, modular Python code when implementation begins.
- Keep secrets, API keys, credentials and private user data out of Git.
- Handle missing, stale, conflicting and malformed data explicitly.
- Attribute external data and respect its licence and terms.
- Never represent an experimental result as an official marine advisory.

## Pull requests

A pull request should explain the purpose, affected modules, test evidence, data sources (if applicable), and any known limitations. Mark unfinished work clearly as planned or in progress.
