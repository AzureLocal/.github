# Contributing to AzureLocal

Thank you for your interest in contributing! These guidelines apply to all AzureLocal repositories.

## Before You Start

- Search existing issues before filing a new one.
- For significant changes, open a [Feature Request](https://github.com/AzureLocal/.github/blob/main/ISSUE_TEMPLATE/feature_request.md) issue first to align on scope.

## Workflow

1. Fork the repository and create a branch from `main`.
2. Make your changes following the standards below.
3. Test in a non-production environment.
4. Submit a pull request using the PR template.

## Standards

All contributions must comply with the [AzureLocal Standards](https://azurelocal.cloud/standards/):

- **Naming** — follow the [Naming Standard](https://azurelocal.cloud/standards/naming/).
- **Repository structure** — follow the [Repository Management Standard](https://azurelocal.cloud/standards/repository-management/).
- **Variables** — no hardcoded IPs, credentials, tenant IDs, or environment-specific values in committed code.
- **Examples** — always use the fictional company **IIC** (International Infrastructure Corp.) in example data. Never Contoso.
- **Commits** — follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `chore:`, etc.).
- **Changelog** — add an entry to `CHANGELOG.md` under `[Unreleased]` for every user-facing change.

## Code Review

All PRs require at least one approving review before merge. Automated structure validation and (where present) unit tests must pass.

## Questions?

Open a discussion or visit [azurelocal.cloud](https://azurelocal.cloud).
