# VAmPI API Security Assessment

Black-box API security assessment of the VAmPI vulnerable REST API application.

## Finding

- **Severity:** Critical
- **Vulnerability:** Broken Object Level Authorization (BOLA)
- **CVSS v3.1:** 9.1
- **OWASP API Top 10:** API1:2023 – Broken Object Level Authorization
- **Affected endpoints:** `GET /users/v1/{username}` and `GET /users/v1`

## Contents

- `vampi-api-report.md` — full security assessment report
- `screenshots/` — proof-of-concept evidence screenshots

> This assessment is intended for authorized security testing and educational use against the intentionally vulnerable VAmPI application.
