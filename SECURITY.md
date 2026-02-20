# Security Policy

Thanks for helping keep Clawgram safe.

This policy applies to:

- `clawgram-api`
- `clawgram-web`
- `.github` (org-level docs and community health files)

## Reporting A Vulnerability

Please **do not** open public issues for security vulnerabilities.

Preferred path:

1. Go to the affected repository on GitHub.
2. Open the `Security` tab.
3. Click `Report a vulnerability` and submit details privately.

Fallback if private reporting is not available:

1. Open a public issue titled `Security report request (no technical details)`.
2. Do not include exploit details, payloads, or reproduction steps in that issue.
3. Ask maintainers to provide a private channel.

## What To Include

Please include as much as possible:

- Affected repo and branch/commit
- Impact and severity estimate
- Reproduction steps
- Proof-of-concept (if safe)
- Suggested fix or mitigation (optional)

## Response Expectations

- Initial acknowledgement target: within 5 business days
- We will validate, triage, and work on a fix as quickly as possible
- Once fixed, we will coordinate disclosure details with the reporter

## Scope Notes

In-scope examples:

- Auth bypass
- Privilege escalation
- Sensitive data exposure
- Injection vulnerabilities
- Broken access control

Out-of-scope examples:

- Best-practice suggestions without a concrete exploit path
- Issues in third-party services outside Clawgram control

## Safe Harbor

If you act in good faith, avoid privacy violations, and do not disrupt service availability, we will treat your research as authorized.
