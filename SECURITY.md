# Security policy

## Reporting a vulnerability

Please do not open a public issue for a security problem.

1. **Preferred:** use GitHub's private vulnerability reporting. In the affected repository, open the **Security** tab and choose **Report a vulnerability**. Only the maintainers can see the report.
2. **Fallback:** email **security@conventionalcontext.org**.

Include what you found, where (repository, file, release), and how to reproduce it. We acknowledge reports within 7 days. This is a volunteer project, so fixes are best effort; we keep you informed until the report is closed, and credit you in the release notes unless you prefer not to be named.

## What counts

Conventional Context is mostly text: an OpenSpec schema whose instructions AI agents follow, and Markdown templates. Besides the usual problems (for example a leaked secret, or a compromised workflow), a security problem includes **instructions that could lead an agent to act unsafely**: for example, to copy secrets into `docs/context/`, to skip a person's review, or to run commands the user did not ask for.

## Supported versions

| Version | Supported |
|---|---|
| Latest `0.x` release | Yes |
| Older releases | No; upgrade to the latest release |
