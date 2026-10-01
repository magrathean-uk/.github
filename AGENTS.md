# Repository guidance

This is the `magrathean-uk/.github` community-policy repository. It contains Markdown policies and GitHub issue forms, with no application, package manifest, build, test suite, or CI workflow. These instructions govern this repository; they are not automatically inherited by other repositories.

## Make the right change

- Complete the authorised task through editing and relevant verification. Make routine safe local changes and take necessary implied steps without asking for permission again. Respect explicit exclusions and ask only for a missing decision that materially changes scope or authority.
- Inspect the current diff and preserve unrelated work. Read the policy or template being changed and its linked documents.
- Use bounded delegation for independent work when it is useful, with distinct file ownership. Handle simple changes directly.
- Keep shared defaults independent of any one product or technology. Explain repository-specific overrides in README.md and CONTRIBUTING.md.
- Preserve LICENSE and LEGAL.md verbatim unless the owner explicitly authorises a legal change; do not copy another project's licence or contributor-assignment rules here.
- Legal files (`LICENSE`, `NOTICE`, `docs/legal/`, contributor terms, copyright and
  attribution strings) are owner-controlled: change them only on the owner's explicit
  instruction.
- Preserve existing security, safe-harbour, and conduct commitments unless a change to those terms is part of the authorised task. Keep private reporting separate from public issue forms.
- Use only verified public contacts and links. Never add credentials, private infrastructure details, personal data, or internal review evidence to public documentation.
- Keep agent instructions here. CLAUDE.md imports this file; do not duplicate the rules or add model-specific prompting advice.
- Keep tooling proportional to the task. Prefer existing tools for documentation checks; add dependencies, workflows, or automation only when the requested work justifies them.
- Carry out Git work, installs, publishing, and service or setting changes within the authority provided by the current task. Existing authorisation persists; do not ask again for an already authorised action. A documentation request alone does not authorise unrelated publication or legal-policy changes.

## Verify the change

From the repository root, these read-only checks inspect scope and whitespace:

```sh
GIT_OPTIONAL_LOCKS=0 git status --short
GIT_OPTIONAL_LOCKS=0 git diff --check
```

Check each changed relative link against the repository tree and each changed external link against its destination. Check headings and Markdown fences. For issue forms, check valid YAML, unique field IDs, supported field types, and required-field syntax. Preserve the private security route in config.yml and the forms.

Review Markdown and forms in their intended GitHub context before adoption. State whether this preview was actually completed. There is no configured build or test command; use checks appropriate to the actual files rather than inventing an application test suite. Report what changed, which checks ran, and any remaining uncertainty.

## Pending URL migration

The next release must apply [NEXT-RELEASE-URLS.md](NEXT-RELEASE-URLS.md): product sites moved to `https://magrathean.uk/solutions/<slug>/` and support addresses to `contact+<slug>@magrathean.uk`. Remove this section with that file once released.
