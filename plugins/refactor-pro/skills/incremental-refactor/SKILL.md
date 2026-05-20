---
name: incremental-refactor
description: Use this skill when the user wants to refactor code step by step with explanations, without rewriting everything at once.
---

# Incremental Refactoring
## Instructions
1. Never rewrite the entire file — work in small, safe steps where each step leaves the code in a working state.
2. Start with the change that delivers the most clarity or reduces the most risk, not the most dramatic transformation.
3. After each step, explain what improved and why — the developer should understand the refactor, not just accept it.
4. Run or check tests after each step to confirm no behavior was changed.
5. Stop when the code is good enough — do not chase perfection. Note further improvements if they exist but are out of scope.
