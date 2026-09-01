# Security policy

Security reports are welcome and should be disclosed privately.

## Reporting a vulnerability

For a public Adu Labs repository, use GitHub's **Security** tab and select
**Report a vulnerability**. Do not open a public issue containing exploit
details, credentials, personal data, or a working proof of concept.

Please include:

- affected repository, release, or commit;
- impact and required attacker capabilities;
- minimal reproduction steps;
- whether secrets or personal data may have been exposed;
- any suggested mitigation.

If private vulnerability reporting is not available for a repository, open a
public issue containing no vulnerability details and ask the maintainer to
enable a private reporting channel.

## Response expectations

Adu Labs is an independent, best-effort open-source project. Receipt will be
acknowledged when possible, followed by validation, remediation planning, and
coordinated disclosure. No fixed response-time or support SLA is currently
offered.

## Supported versions

Before a project reaches `v1.0`, security fixes target the latest published
release and the default branch. Individual repositories may publish a stricter
support matrix.

## Secrets

Never submit real API keys, tokens, certificates, cookies, production URLs, or
credentials in an issue, pull request, test fixture, trace, screenshot, or
benchmark artifact. If a secret is exposed, revoke and rotate it immediately;
deleting it from the latest commit is not sufficient.
