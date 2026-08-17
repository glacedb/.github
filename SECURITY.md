# Security Policy

This policy applies to every public repository in the `glacedb` organization
unless a repository carries its own `SECURITY.md`.

## Reporting a vulnerability

Please do **not** open a public issue for security vulnerabilities.

1. Preferred: open a **private vulnerability report** on the affected
   repository (GitHub → Security → Report a vulnerability).
2. Or email **security@glacedb.com**.

Include a description, steps to reproduce, the affected version/commit, the
potential impact, and a suggested fix if you have one.

## What to expect

- **Acknowledgment** within 48 hours.
- **Assessment and severity triage**, with progress updates as we work.
- **Coordinated disclosure**: we follow a **90-day disclosure deadline** from
  report to public disclosure. If a fix ships earlier, we disclose with the
  release; we may ask for a short extension for exceptional cases and will
  agree on timing with you.
- **Credit** in the security advisory unless you prefer to remain anonymous.

Fixes for embargoed issues are developed in private forks via GitHub Security
Advisories and disclosed with a published advisory and patched release.

## Scope

In scope across the organization's repositories: memory-safety issues,
authentication/authorization bypasses, query-injection vulnerabilities,
denial of service, information disclosure, and unsafe deserialization.
Out of scope: vulnerabilities in third-party dependencies (report upstream —
but do tell us so we can pin or patch), and issues requiring physical access
to a machine.
