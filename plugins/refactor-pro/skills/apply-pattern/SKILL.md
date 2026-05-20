---
name: apply-pattern
description: Use this skill when the user wants to apply a design pattern to resolve a specific code smell.
---

# Design Pattern Application
## Instructions
1. Confirm the smell being addressed before choosing a pattern — the pattern must solve a real problem, not be applied for its own sake.
2. Select the most fitting pattern: Extract Method for long methods, Strategy for conditional behavior, Repository for data access coupling, Factory for construction complexity.
3. Apply the pattern to the actual code — show the real before and after, not a textbook example.
4. Explain what the pattern achieves and what tradeoffs it introduces.
5. Stop at the pattern that solves the smell — do not chain multiple patterns or introduce abstractions that aren't yet needed.
