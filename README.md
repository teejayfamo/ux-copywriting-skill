# UX Copywriting Skill

A portable **UX copywriting skill**—write and review **in-product UX copy** (microcopy) with a clear, user-first style.

## What it does

- Drafts or rewrites buttons, form labels, help text, errors, empty states, onboarding steps, and confirmations
- Enforces clarity, brevity, consistency, and helpful guidance (especially for errors)
- Produces a compact, reviewable output format (Primary / Short / Alternatives / Rationale)

## Install (Codex)

Copy the `ux-copywriting` folder into your Codex skills directory:

- Destination (default): `~/.codex/skills/ux-copywriting`
- Contents required: `SKILL.md` (and optional `agents/`, `references/`)

Then restart Codex to pick up the new skill.

## Use

In your prompt, reference it explicitly:

- “Use `$ux-copywriting` to rewrite this error message…”
- “Use `$ux-copywriting` to propose button labels for…”
- “Use `$ux-copywriting` to create an empty-state message for…”

## Use in other AI tools (Claude, Gemini, Kiwi)

Most tools won’t auto-load `SKILL.md`. Use the portable prompts in `prompts/`:

- System instructions: `prompts/system.txt`
- Request template: `prompts/user-template.md`
- Examples: `prompts/examples.md`

### Claude (Projects)
- Paste `prompts/system.txt` into Project instructions.
- Optionally attach `references/ux-copywriting-guide.md` as knowledge.

### Gemini
- Use `prompts/system.txt` as the system instruction (or first message), then send requests using `prompts/user-template.md`.

### Kiwi
- If Kiwi supports a “system prompt” or “instructions” field, paste `prompts/system.txt` there.
- If it supports templates/snippets, add `prompts/user-template.md`.

## Publishing to GitHub

This folder is ready to be its own Git repository. Add a license of your choice (MIT/Apache-2.0/etc.) before publishing.
