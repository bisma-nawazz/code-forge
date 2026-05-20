---
name: generate-tests
description: Use this skill when the user wants to generate a full test suite for a file, module, or feature from scratch.
---

# Test Suite Generation
## Instructions
1. Identify the right test level: unit (pure functions, isolated logic), integration (component interactions), or e2e (full user flows).
2. Select the appropriate testing framework for the language and stack (Jest, Pytest, Go testing, RSpec, etc.).
3. Cover the happy path, all documented edge cases, and known error conditions.
4. Structure tests with clear Arrange-Act-Assert or Given-When-Then patterns.
5. Avoid mocking internals — test behavior through public interfaces and use real dependencies where feasible.
