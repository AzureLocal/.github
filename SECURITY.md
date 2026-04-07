# Security Policy

## Supported Versions

Security fixes are applied to the latest release on the `main` branch. Older versions are not actively patched.

## Reporting a Vulnerability

**Do not file a public GitHub issue for security vulnerabilities.**

To report a vulnerability, email the maintainers at the address listed in the repository's README, or use [GitHub's private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) if enabled for the repository.

Please include:
- A description of the vulnerability and its impact
- Steps to reproduce or a proof-of-concept (if safe to share)
- The affected repository and version

We will acknowledge receipt within 5 business days and aim to provide a resolution timeline within 14 business days.

## Scope

These repositories contain infrastructure automation, documentation, and tooling for Azure Local deployments. Key concerns include:

- Hardcoded credentials or secrets committed to code
- Insecure default configurations in example scripts or templates
- Dependency vulnerabilities in tooling components

## Out of Scope

- Vulnerabilities in upstream Microsoft Azure Local or Azure Arc products (report those to [Microsoft Security Response Center](https://msrc.microsoft.com/))
- Issues that require physical access to infrastructure
