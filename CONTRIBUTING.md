# Contributing to Magrathean UK repositories

This is the default contribution policy for repositories without their own `CONTRIBUTING.md`. Follow the affected repository's specific instructions, licence, and generated-file rules. Agent guidance may add working instructions; it does not change the licence or replace GitHub's contribution-file selection.

External contributions are accepted only for public repositories, subject to the target repository's published licence and contribution terms. Private repositories are maintainer-only. Public visibility does not create an open-source licence or grant additional reuse rights. Check the target repository's terms before starting.

## Before making a change

1. Read the README and the instructions relevant to the files you will change.
2. Search existing issues and pull requests.
3. Open a proposal before substantial changes to behaviour, architecture, dependencies, storage, protocols, or the user interface.
4. Identify the source of truth and any generated files.

Keep credentials, personal or customer data, production configuration, and private licensed assets out of contributions and examples.

## Prepare and verify

Keep changes focused and explain the problem they solve. Preserve security boundaries, data ownership, compatibility, and recovery behaviour unless the agreed change explicitly addresses them.

Use the repository's documented verification commands. Add or update meaningful tests when behaviour changes and a test suite exists. Do not introduce generic lint or formatting requirements that the project does not configure. Update the documentation affected by the change.

Do not hand-edit generated projects, bindings, vendor trees, build outputs, or release evidence unless repository guidance calls for it. Explain the purpose, maintenance cost, licence, and security implications of new dependencies.

For changes to this shared-defaults repository, check links, Markdown rendering, issue-form syntax, and agreement between policies and templates. There is no build or test suite here. Changes can affect repositories using these defaults, so describe that impact in the pull request.

For repositories with package installs or build output, consider [Clean Development](https://github.com/magrathean-uk/clean-development) as an optional way to manage development storage. This documentation repository needs no setup.

## Licensing and provenance

Contributions are submitted under the licence of the affected repository unless a separate written agreement says otherwise. You must have the right to contribute every line, asset, fixture, translation, model, font, icon, and dependency included in the change.

Copyleft, source-available, proprietary, or otherwise restrictive dependencies are not automatically prohibited, but they must be compatible with the repository's licence and distribution model and must be documented explicitly.

Unless a repository says otherwise, commits to an open-source Magrathean project should include a Developer Certificate of Origin sign-off:

```text
Signed-off-by: Full Name <email@example.com>
```

When making an authorised commit, Git can add the sign-off with `git commit -s`. A sign-off is a provenance declaration, not a transfer of copyright. This repository's own [licence notice](LICENSE) is explained in [LICENSING.md](LICENSING.md).

## Pull request evidence

Describe the problem, approach, and affected behaviour. Include verification commands and results, skipped checks, and untested paths. Explain relevant security, privacy, licensing, dependency, migration, compatibility, and operational effects. Include deployment, rollback, or recovery steps when the change affects a running system or persisted data.

Add sanitised screenshots or logs only when they help demonstrate the result. Follow the [code of conduct](CODE_OF_CONDUCT.md). Report vulnerabilities privately through [SECURITY.md](SECURITY.md), not in a public issue or pull request.
