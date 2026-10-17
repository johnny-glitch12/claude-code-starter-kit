# Claude Code Starter Kit

A practical starter kit for people who use Claude Code.

Clone this repo, copy the files you need into your project, and Claude will follow better conventions from the first session.

## What's included

### CLAUDE.md Templates
Ready-to-copy project instruction files for common stacks:
- `templates/nextjs-claude.md` — Next.js + TypeScript
- `templates/python-fastapi-claude.md` — Python FastAPI
- `templates/general-claude.md` — Minimal general purpose

### Skills
Drop-in skills under `skills/`:
- code-reviewer
- tdd-helper
- refactor-safely
- write-tests
- explain-code

### How to use
1. Clone this repo
2. Copy a CLAUDE.md template into the root of your project and rename it to `CLAUDE.md`
3. Copy any skills you want into `.claude/skills/` in your project
4. Start Claude Code in that project

## Why this exists
Most people start Claude Code with no context. These files give Claude the non-obvious rules and workflows so it makes fewer mistakes.

MIT License. Fork and improve.
