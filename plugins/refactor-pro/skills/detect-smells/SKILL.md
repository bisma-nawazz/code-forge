---
name: detect-smells
description: Use this skill when the user wants to identify code smells such as god classes, long methods, duplicated logic, or tight coupling.
---

# Code Smell Detection
## Instructions
1. Scan for god classes: classes with too many responsibilities or methods (200+ lines is a signal).
2. Flag long methods that do more than one thing — a good method fits on a screen and has a single purpose.
3. Identify duplicated logic across files or modules — look for copy-pasted blocks and near-identical functions.
4. Check for tight coupling: code that directly instantiates dependencies, accesses internals of other classes, or has excessive imports.
5. Report each smell with its location, why it's a problem, and which design pattern or technique addresses it.
