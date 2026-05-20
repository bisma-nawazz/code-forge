---
name: trace-execution
description: Use this skill when the user wants to trace execution paths through code to find where behavior diverges from expectation.
---

# Execution Tracing
## Instructions
1. Establish the expected behavior — what should happen — before tracing what actually happens.
2. Identify the entry point and follow the call chain step by step, noting every branch and condition.
3. At each branch, determine which path is actually taken given the real inputs and state.
4. Pinpoint the exact line where actual behavior first diverges from expected behavior.
5. Summarize the trace as a sequence: input → function → branch condition (was X, expected Y) → wrong path taken.
