---
name: slack-reader
description: Use this skill when the user wants to navigate Slack via MCP to fetch channel messages, threaded replies, and cross-referenced messages for meeting note extraction.
---

# Slack Reader
## Instructions
1. Identify the target channels from the user's request; default to channels whose names contain "standup", "daily", "sync", or "meeting" when no channel is specified.
2. Fetch the main channel timeline first, then for each message that has a reply count greater than zero, fetch the full thread — threaded replies often contain the actual task assignments that followed an in-channel prompt.
3. When a message references another message (via Slack's "reply in thread" link or a quoted attachment), fetch the referenced message so context is not lost; do not summarise a message that refers to content you haven't read.
4. Preserve the author name and timestamp for every message you pass to the parser; strip Slack formatting tokens (`:emoji:`, `<@U123>` user mentions → display name, `<#C123>` channel mentions → channel name) before returning text.
5. If the MCP call returns a rate-limit or permission error, report the exact channel name and error code rather than silently skipping — missing channels mean missing tasks.
