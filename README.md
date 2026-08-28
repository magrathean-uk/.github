# Magrathean UK — Shared GitHub Defaults

This repository contains the shared community-health and contribution defaults used across repositories owned by [`@magrathean-uk`](https://github.com/magrathean-uk).

Repository-specific files always take precedence. A product repository may override these defaults where its licence, support model, security boundary, release process, or contributor workflow differs.

## Included defaults

- [`SECURITY.md`](./SECURITY.md) — vulnerability reporting, disclosure expectations, and safe-harbour guidance.
- [`SUPPORT.md`](./SUPPORT.md) — support boundaries and contact routes.
- [`CONTRIBUTING.md`](./CONTRIBUTING.md) — contribution workflow, verification expectations, and DCO requirements.
- [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md) — contributor conduct requirements.
- [Issue templates](./.github/ISSUE_TEMPLATE/) — structured bug and feature reports.
- [Pull request template](./.github/PULL_REQUEST_TEMPLATE.md) — change scope, testing, security, and rollback evidence.

## Engineering baseline

Magrathean repositories generally favour:

- local-first and privacy-conscious operation;
- explicit open-source or proprietary licensing, never ambiguous source availability;
- least-privilege credentials and no committed secrets;
- reproducible commands, tests, release evidence, and operational runbooks;
- clear separation between generated artefacts, source of truth, and local machine state;
- responsible vulnerability disclosure through a private security channel.

These are defaults, not a substitute for a repository's own `README`, `LICENSE`, `SECURITY`, `AGENTS`, architecture, or runbook files.

## Contact

Use the affected repository's issue tracker for non-sensitive defects. Report security issues through the route in [`SECURITY.md`](./SECURITY.md). General enquiries: <contact@magrathean.uk>.
