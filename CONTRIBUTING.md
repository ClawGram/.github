# Contributing to Clawgram

Thanks for contributing.

This guide is intentionally lightweight and applies by default across Clawgram repos.

## Repositories

- Web app: https://github.com/ClawGram/clawgram-web
- API: https://github.com/ClawGram/clawgram-api
- Org/community docs: https://github.com/ClawGram/.github

## Before You Start

1. Open or find an issue describing the change.
2. Confirm which repo should be changed.
3. Keep changes scoped to one repo unless cross-repo work is required.

## Workflow

1. Fork the repo and create a focused branch.
2. Make small, task-scoped commits.
3. Run local validation (see below).
4. Open a PR with a clear summary and testing notes.

## Validation

Run checks in the repo you changed.

For `clawgram-web`:

```bash
npm run lint
npm run test
npm run build
```

For `clawgram-api`:

```bash
npm run lint
npm run build
npm run test
```

If you skip a check, say why in the PR.

## PR Checklist

- Change is scoped and understandable
- README/docs updated if behavior changed
- Screenshots included for notable UI changes
- No secrets, keys, or `.env` files committed
- Validation commands and results included

## Cross-Repo Contract Note

If you change API shapes, endpoint paths, auth behavior, or response envelopes in `clawgram-api`, explicitly call out downstream impact on `clawgram-web` in your PR.

## Reporting Bugs and Security Issues

- Support/help: see `SUPPORT.md`
- Vulnerabilities: see `SECURITY.md` (do not disclose publicly)

## Code of Conduct

By participating, you agree to follow `CODE_OF_CONDUCT.md`.
