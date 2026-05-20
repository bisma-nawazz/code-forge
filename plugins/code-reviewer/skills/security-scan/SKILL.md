---
name: security-scan
description: Use this skill when the user wants to scan code for security vulnerabilities including SQL injection, XSS, and exposed secrets.
---

# Security Scan
## Instructions
1. Scan for SQL injection: check all database queries for string concatenation or interpolation with user input.
2. Scan for XSS: check all places where user-supplied data is rendered in HTML without sanitization.
3. Search for hardcoded secrets: API keys, passwords, tokens, and private keys embedded in source code.
4. Check authentication and authorization paths for missing guards, insecure token handling, and privilege escalation risks.
5. Report each finding with severity (critical/high/medium/low), the exact location, and a concrete remediation step.
