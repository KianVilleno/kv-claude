# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Status

This is a newly initialized repository. Update this file as the project develops with build, test, and lint commands.

## Agent Skills

This repository uses the [Skills CLI](https://skills.sh/) ecosystem for extending agent capabilities. Skills are installed in `.agents/skills/` and symlinked to `.claude/skills/`.

**Installed skills:**
- `brainstorming` - Ideation and creative problem-solving
- `writing-plans` - Structured planning approaches
- `professional-communication` - Email templates, meeting structures, async communication
- `difficult-workplace-conversations` - Conversation frameworks and delivery scripts
- `feedback-mastery` - SBI feedback model and expectation alignment
- `find-skills` - Discover and install additional skills

**Skills CLI commands:**
```bash
npx skills find [query]     # Search for skills
npx skills add <repo>       # Install a skill
npx skills check            # Check for updates
npx skills update           # Update all skills
```
