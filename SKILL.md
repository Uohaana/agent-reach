---
name: agent-reach
description: Research and look up anything on the internet across search, social, GitHub, web, video, finance, and other online platforms.
---

# Agent Reach

Use this skill when the user wants to research, search, investigate, or gather information from the internet.

## What to do
- identify the platform or type of internet research needed
- route to the correct backend or platform workflow
- use search, social, dev, web, video, or finance research patterns as needed
- keep the task focused on fetching and organizing information from the web
- do not perform posting, commenting, liking, or other write actions unless explicitly requested

## Important rules
- do not invent tools or platforms; use the proper routing logic for the task
- if the task is a general internet lookup, use search and web research methods first
- if the user mentions social platforms or product URLs, route to the matching platform-specific flow
- if the platform requires login or cookies, follow the safe, read-only guidance and do not expose secrets
- do not create files in the workspace for normal research tasks; use temporary output when necessary

## Typical use cases
- general web research
- product or brand research across the internet
- Reddit, X/Twitter, Bilibili, Xiaohongshu, LinkedIn, GitHub, YouTube, RSS, and other web sources
- stock or finance research
- technical or code search
