# Security Policy

## Reporting a Vulnerability

Please do not report security vulnerabilities in a public issue.

- For a vulnerability in this Homebrew formula or its packaging, use [private vulnerability reporting for this tap](https://github.com/nithishduda-ai/homebrew-tap/security/advisories/new).
- For a vulnerability in the `pagerduty-oncall-ack` application, use [private vulnerability reporting for the application](https://github.com/nithishduda-ai/pagerduty-oncall-ack/security/advisories/new).

Include the affected version, installation method, impact, and reproduction steps when possible. Never include PagerDuty API tokens, credentials, or other secrets in a report.

## Supported Versions

Only the latest formula version on the `main` branch is supported. Upgrade before reporting an issue:

```sh
brew update
brew upgrade pagerduty-oncall-ack
```
