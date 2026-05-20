---
name: fill-coverage-gaps
description: Use this skill when the user wants to analyze existing tests and write additional cases to cover untested code paths.
---

# Coverage Gap Filling
## Instructions
1. Read the existing test file and source file together to map what is and isn't covered.
2. Identify uncovered branches: else clauses, error throws, null/undefined inputs, and boundary values.
3. Prioritize gaps by risk — untested error handling and edge cases before trivial paths.
4. Write targeted tests for each gap without duplicating existing coverage.
5. Verify each new test would actually fail if the corresponding code were deleted or broken.
