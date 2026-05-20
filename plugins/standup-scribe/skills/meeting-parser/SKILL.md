---
name: meeting-parser
description: Use this skill when the user wants to extract actionable tasks from raw meeting notes or Slack thread transcripts.
---

# Meeting Parser
## Instructions
1. Scan the input for action-item signals: phrases like "you'll handle", "can you", "let's make sure", "by Friday", "owner:", and any sentence where someone commits to doing something.
2. Distinguish discussion noise (questions, reactions, context-setting) from genuine commitments — only flag text where a specific outcome is expected from a specific person or team.
3. Extract the owner, the task, and any deadline or urgency signal mentioned in the same sentence or adjacent context; note when any of these three are absent.
4. Resolve pronoun references ("she'll do it", "he can take that") by scanning back through the thread for the most recently named person.
5. Flag ambiguous items — tasks without a clear owner or deadline — in a separate "needs clarification" bucket rather than guessing or dropping them.
