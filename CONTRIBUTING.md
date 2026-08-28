# Contributing to Magrathean UK Repositories

This is the default contribution policy for repositories that do not provide their own `CONTRIBUTING.md` or `AGENTS.md`. The closest repository-specific instructions, licence, architecture, runbook, and generated-file rules take precedence.

Some public repositories contain proprietary source or public support material and may not accept external code contributions. Public visibility alone does not imply an open-source licence. Check the affected repository's `LICENSE` before starting work.

## Before changing code

1. Read the repository README, licence, contribution instructions, agent guidance, architecture, and runbook.
2. Search existing issues and pull requests.
3. For a substantial behavioural, architectural, dependency, storage, protocol, or user-interface change, open a proposal before implementation.
4. Confirm which files are generated and which file is the source of truth.
5. Keep credentials, customer data, personal data, production configuration, and licensed third-party assets out of commits and fixtures.

## Change expectations

- Keep the change narrowly scoped and explain why it is needed.
- Preserve security boundaries, data ownership, compatibility, and rollback behaviour unless the proposal explicitly changes them.
- Add or update tests for changed behaviour where the repository has a test lane.
- Run the exact verification commands documented by that repository. Do not invent generic lint or formatting requirements that the project does not configure.
- Update operator, user, API, migration, release, and recovery documentation when behaviour changes.
- Do not hand-edit generated projects, bindings, lockstep artefacts, vendor trees, build outputs, or release evidence unless the repository explicitly says to do so.
- Introduce dependencies only when their purpose, maintenance burden, licence, security impact, and replacement cost are understood.

## Licensing and provenance

Contributions are submitted under the licence of the affected repository unless a separate written agreement says otherwise. You must have the right to contribute every line, asset, fixture, translation, model, font, icon, and dependency included in the change.

Copyleft, source-available, proprietary, or otherwise restrictive dependencies are not automatically prohibited, but they must be compatible with the repository's licence and distribution model and must be documented explicitly.

Unless a repository says otherwise, commits to an open-source Magrathean project should include a Developer Certificate of Origin sign-off:

```text
Signed-off-by: Full Name <email@example.com>
```

Create a signed-off commit with:

```bash
git commit -s
```

## Pull request evidence

A useful pull request states:

- the problem and chosen approach;
- affected components and user-visible behaviour;
- verification commands and results;
- known omissions or untested paths;
- security, privacy, licence, migration, compatibility, and operational impact;
- deployment, rollback, and recovery steps where the change can affect a running system;
- screenshots or recordings only when they add evidence and contain no sensitive data.

Report vulnerabilities privately through [`SECURITY.md`](./SECURITY.md), not through a public issue or pull request.
