# Security Policy

## Scope

Report security defects affecting the integrity, validation, packaging, parsing, canonicalization, hashing, authority boundaries, or executable behavior of SYS-STSF-001.

Do not publish working exploits, credentials, secrets, or sensitive third-party information in a public issue.

## Reporting

Use GitHub's private vulnerability reporting feature when available.

If private reporting is unavailable, open a minimal public issue stating that a security report is available, without including exploit details.

## Integrity

Security fixes must preserve STSF authority boundaries and must not silently rewrite canonical STD, PRG, SPL, manifest, binding, or evidence content.

A security change does not become authoritative merely because it is merged into the repository.
