# Security Policy — Magrathean UK

This is the default security policy for Magrathean UK repositories that do not publish a repository-specific `SECURITY.md`. A repository-specific policy takes precedence.

## Report vulnerabilities privately

Do not open a public issue, discussion, or pull request for a suspected vulnerability.

Use one of these routes:

- Email <contact@magrathean.uk> with the subject `SECURITY: <repository or product>`.
- Use GitHub's **Report a vulnerability** option on the affected public repository when private vulnerability reporting is enabled.

Do not send live credentials, private keys, access tokens, personal data, or production database extracts. Redact evidence and provide the minimum material needed to reproduce the issue safely.

## Include

- affected repository, product, component, version, and commit where known;
- deployment context and required permissions;
- clear reproduction steps or a minimal proof of concept;
- observed and potential impact;
- whether exploitation is known to be active;
- proposed remediation or a patch, when available;
- a safe contact route for coordinated follow-up.

## Scope

Good-faith research is in scope only where it targets software or infrastructure operated by Magrathean UK, a researcher-owned deployment, or an environment for which the researcher has explicit authorisation.

Third-party platforms, vehicle services, cloud tenants, app stores, payment systems, identity providers, and customer-operated deployments are outside Magrathean UK's authority unless the affected owner has expressly authorised the testing.

## Safe-harbour position

Magrathean UK Ltd. will not pursue legal action against a researcher for accidental, good-faith activity that follows this policy and:

- uses the least intrusive method reasonably available;
- avoids persistence, destructive changes, denial of service, social engineering, and lateral movement;
- does not access, retain, alter, or disclose other people's data beyond the minimum unavoidable evidence;
- stops immediately when sensitive data, credentials, safety systems, or an unexpected production boundary is encountered;
- reports promptly and allows a reasonable period for investigation and remediation before disclosure;
- does not demand payment, ransom, or commercial advantage as a condition of disclosure.

This policy does not authorise activity prohibited by law or by the lawful owner of a third-party system. It does not create a bounty or promise payment.

## Excluded activity

Safe harbour does not cover credential stuffing, phishing, physical intrusion, malware, data exfiltration, automated denial of service, high-volume scanning that degrades service, persistence, extortion, or unauthorised testing of third-party connected services.

## Handling and disclosure

Reports are handled on a best-effort basis. Magrathean UK will validate scope, assess impact, coordinate remediation where appropriate, and agree disclosure timing with the reporter where practicable. No fixed response or remediation SLA is promised unless a separate written agreement applies.
