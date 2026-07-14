# Sensitive Data Handling Standard

## Overview

This document defines mandatory requirements for handling sensitive and confidential information in Emerson DeltaV GitHub repositories.

All contributors are responsible for ensuring that no sensitive information is committed, uploaded, documented, or disclosed in any repository artifact, including code, configuration, documentation, logs, examples, and visual content.

---

## Prohibited Data

Contributors must not commit, upload, document, or disclose sensitive or confidential information.

Sensitive information includes, but is not limited to:

- Credentials and secrets (passwords, API keys, tokens, private keys, certificates)
- Personal information (email addresses, phone numbers, identifiers)
- Internal system details (IP addresses, hostnames, internal URLs)
- Connection details (connection strings, database credentials)
- Customer or project data
- Emerson confidential information

Sensitive information must not be included for testing, demonstration, or documentation purposes.

---

## Required Practices

Contributors must:

- Use placeholders for environment-specific values
- Use synthetic or non-production data
- Sanitize logs, outputs, examples, and documentation
- Externalize credentials using approved mechanisms
- Exclude sensitive files using .gitignore

---

## Examples (Illustrative Only)

All values below are placeholders and not real data.

Prohibited:

DB_PASSWORD=MyActualPassword123
api_key="sk-live-abc123XYZ"
email="john.doe@gmail.com"
http://10.10.25.14/internal-api

Acceptable:

DB_PASSWORD=<your_secure_password>
api_key="<REDACTED>"
email="user@example.com"
INTERNAL_API_URL=<configured_externally>

---

## Screenshots and Visual Content

Screenshots and visual artifacts must be treated as sensitive by default.

They must not expose IPs, hostnames, credentials, usernames, or internal system details.

All screenshots must be redacted, blurred, masked, or replaced with placeholders before inclusion.

---

## Default and Initial Credentials

Initial credentials must:

- Be temporary
- Be changed on first use
- Be supplied via environment variables or runtime configuration
- Not be hardcoded in code, Dockerfiles, or documentation

---

## Credential Handling

Credentials must be supplied or injected at runtime using:

- Environment variables
- Deployment configuration
- Secret management systems

Hardcoding credentials is not allowed.

---

## Incident Handling

If sensitive data is exposed:

- Notify opensource.deltav@emerson.com immediately
- Do not attempt independent remediation

---

## Guiding Principle

Sensitive data must never be embedded in repositories.
