# Security Policy

Deslop is a prompt-only skill (`SKILL.md` plus sample text). It ships no executable code, but a malicious edit to the skill's instructions could still change how an agent behaves, so we treat that as a security issue.

## What to report

* Instructions in `SKILL.md` or the samples that could make an agent run commands, exfiltrate data, or ignore its user's intent.
* Tampered or misleading install instructions in the README.

Rule disputes (for example, a legal term of art that was simplified incorrectly) are not security issues. Open a **Rule Suggestion** issue instead.

## How to report

Use GitHub's private reporting: go to the repository's **Security** tab and choose **Report a vulnerability**. Please don't open a public issue for a security problem.

You can expect an acknowledgment within 7 days.

## Supported versions

Only the latest commit on `main` is supported.
