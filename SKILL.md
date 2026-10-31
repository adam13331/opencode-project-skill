---
name: project-initializer
description: Interactive project initializer. Use when typing @start or asking to bootstrap a project structure by generating AGENT.md, MAP.md, CONTEXT.md, and CAVEMAN.md.
---

# Project Initializer & Dynamic Router

This skill guides the user through an interactive workflow to automatically generate core project tracking files (`AGENT.md`, `MAP.md`, `CONTEXT.md`, and `CAVEMAN.md`) and enables dynamic skill routing.

## Workflow Steps

1. **Interactive Diagnostic:** When triggered via `@start`, ask the user:
   - What is the project mission and tech stack?
   - What are the core folders/entry points?
   - What task are we starting on today?
   - Should Caveman Mode be enabled?
2. **Template Generation:** Output the tailored versions of the 4 core files based on their answers.
3. **Dynamic Routing:** Reference specialized micro-skills (e.g., database, testing, UI) on demand rather than loading everything at once.
