---
name: task-formatter
description: Use this skill when the user wants to format extracted action items into a structured, scannable task list grouped by assignee and sorted by urgency.
---

# Task Formatter
## Instructions
1. Group all tasks by assignee, with one section per person; sort sections alphabetically by name so the list is predictable across runs.
2. Within each assignee's section, sort tasks by urgency: explicit deadlines first (earliest date at top), then "ASAP"/"urgent" items, then undated tasks.
3. For each task, emit a single bullet with the format: `- [ ] <task description> — <deadline or "no deadline"> — <priority: high/medium/low>`.
4. Collect tasks with no identified owner under a clearly labelled "Unassigned" section at the end — never drop them or silently merge them into another section.
5. Keep task descriptions to one concise sentence; strip filler words ("just", "maybe", "probably") and preserve the concrete action and object.
