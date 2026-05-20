---
name: propose-fix
description: Use this skill when the user wants a targeted fix that addresses the root cause of a bug and prevents recurrence.
---

# Fix Proposal
## Instructions
1. Confirm the root cause before proposing a fix — do not patch the symptom.
2. Write the minimal code change that resolves the issue without altering unrelated behavior.
3. Explain why the fix works in terms of the root cause, not just what line changed.
4. Identify whether the same pattern exists elsewhere in the codebase and flag those locations.
5. Suggest a guard or test that would catch this class of bug automatically in the future.
