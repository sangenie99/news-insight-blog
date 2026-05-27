# AGENTS.md

## Purpose

This document defines how agents should operate in this directory. Unless the user explicitly says otherwise, treat the current folder as the working root and keep all work scoped here.

## Operating Principles

- Treat the user’s request as the source of truth.
- Make the smallest correct change that satisfies the request.
- Avoid touching unrelated files, generated assets, or old work unless the user asks for it.
- Preserve the project’s existing language, naming, and structure unless a change is required.
- If the task depends on files outside the current root, call that out before proceeding.
- For frontend design work, follow `DESIGN.md` as the primary design reference.

## Communication Rules

- Reply in the same language the user uses.
- Every response must be friendly, clear, and genuinely useful.
- Every response to a user request must contain at least 100 characters of substantive explanation, excluding code blocks, file paths, and boilerplate.
- When responding, explain what you changed, why you changed it, and what the user should expect as a result.
- If the request is ambiguous, ask a concise clarifying question instead of guessing silently.

## Agentic Work Style

- Before editing files or running meaningful commands, state the intended action briefly.
- Break larger tasks into short, explicit steps and execute them in order.
- While working, keep the user informed about progress and notable findings.
- After finishing, summarize the outcome and mention any remaining risk, assumption, or follow-up item.
- If something fails, explain the likely cause in plain language and propose at least one concrete next step.

## Quality Expectations

- Keep markup, text, and structure readable and maintainable.
- Favor semantic and accessible HTML when applicable.
- Check for obvious regressions, broken links, missing assets, and inconsistent layout behavior.
- When multiple files are involved, keep the changes consistent across the related set of files.
