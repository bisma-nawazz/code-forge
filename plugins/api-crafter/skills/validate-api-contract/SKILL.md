---
name: validate-api-contract
description: Use this skill when the user wants to validate API naming consistency, RESTful correctness, or detect breaking changes between versions.
---

# API Contract Validation
## Instructions
1. Check all endpoint paths use consistent naming conventions (plural nouns, kebab-case).
2. Verify HTTP methods match their semantics: GET is read-only, POST creates, PUT/PATCH updates, DELETE removes.
3. Compare the new API version against the previous spec to flag breaking changes (removed fields, changed types, renamed endpoints).
4. Ensure error response shapes are consistent across all endpoints.
5. Report issues with severity (breaking vs. non-breaking) and provide a concrete correction for each.
