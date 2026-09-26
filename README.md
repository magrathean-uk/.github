# Magrathean UK shared GitHub defaults

Community policies and issue and pull request templates for repositories owned by [Magrathean UK](https://github.com/magrathean-uk). This repository contains documentation and GitHub forms. There is no application to install or build.

## Find the right guidance

| File | Purpose |
| --- | --- |
| [Contributing](CONTRIBUTING.md) | Propose changes, verify them, and document provenance |
| [Security](SECURITY.md) | Report vulnerabilities privately and understand research boundaries |
| [Support](SUPPORT.md) | Get help with a repository or find product support |
| [Code of conduct](CODE_OF_CONDUCT.md) | Participation, reporting, and enforcement |
| [Issue forms](.github/ISSUE_TEMPLATE/) | Report defects or propose improvements |
| [Pull request template](.github/PULL_REQUEST_TEMPLATE.md) | Explain changes, verification, and relevant risks |

## How defaults apply

GitHub uses these supported community files when an owned repository has no corresponding file of its own. A repository's valid issue templates or issue-template configuration replace the entire default issue-template set. Inherited files are displayed by GitHub; they are not copied into the receiving repository's clone or downloads. See [GitHub's default-file rules](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

The issue forms use `bug` and `enhancement` labels; repositories using the forms need those labels.

Each project sets its own licence, supported releases, commands, and operational boundaries. This repository's licence is not a default licence for other projects. Its agent instructions describe maintenance of this repository and are not shared community-health defaults.

## Contributions

External contributions are accepted only for public repositories, subject to the target repository's published licence and contribution terms. Private repositories are maintainer-only. See [CONTRIBUTING.md](CONTRIBUTING.md) for the shared workflow.

## Maintain this repository

Edit the Markdown policies or the forms under `.github/ISSUE_TEMPLATE/`. Keep advice useful across projects without assuming a language, runtime, product, or release process.

Before submitting a change:

- Check Markdown links, headings, and rendered text.
- Check issue-form YAML, unique field IDs, required fields, and the private security-reporting route.
- Review the policies and templates together for conflicting requirements.
- Explain any change to contribution, conduct, licensing, or security terms.

There are no configured build, test, or lint commands. Preview the affected Markdown and GitHub form before adopting changes. See [contributing](CONTRIBUTING.md) for the shared workflow.

## Licence and reuse

[LICENSE](LICENSE) is the existing Magrathean UK Ltd. all-rights-reserved notice. It describes publication for the operation of Magrathean UK projects on GitHub and contains no standard open-source licence grant. See [licensing and attribution](LICENSING.md) for the distinction between these documents and the projects that use them.

## Contact

Use the affected repository's issue tracker for non-sensitive defects. For a problem with these shared defaults, use [this repository's issues](https://github.com/magrathean-uk/.github/issues). Report vulnerabilities through [SECURITY.md](SECURITY.md). General enquiries: <contact@magrathean.uk>.
