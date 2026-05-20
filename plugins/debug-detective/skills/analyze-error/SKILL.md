---
name: analyze-error
description: Use this skill when the user wants to parse an error message or stack trace and identify the most likely root causes.
---

# Error Analysis
## Instructions
1. Read the full error message and stack trace — do not skip frames. The root cause is often not the top frame.
2. Identify the error type (null reference, type mismatch, network failure, permission denied, etc.) and its origin.
3. Propose hypotheses ranked by likelihood, each grounded in specific evidence from the stack trace or code.
4. Cross-reference the error location with the surrounding code to confirm or rule out each hypothesis.
5. Present findings as: most likely cause → supporting evidence → what to check next.
