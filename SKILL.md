---
name: "ux-copywriting"
description: "Write and review in-product UX microcopy (buttons, labels, help text, errors, empty states, onboarding) using clear, user-first, consistent language. Use when asked to draft UI text, rewrite product copy for clarity, standardize terminology/tone, or build a reusable message library."
---

# UX Copywriting

Use this skill when producing or reviewing **in-product** copy (not marketing): UI labels, CTAs, helper text, validation, errors, empty states, confirmations, onboarding steps, and navigation labels.

If you need the full guide text, read `references/ux-copywriting-guide.md`.

## Operating principles (non-negotiable)

- **Clarity over cleverness**: plain words, no jargon.
- **User-first**: optimize for the user’s immediate goal.
- **Brevity with meaning**: every word earns its place.
- **Consistency**: same term for same action everywhere.
- **Guidance, not decoration**: copy exists to unblock tasks.

## Default output format

Return copy in this structure unless the user asks otherwise:

1) **Primary** (recommended)
2) **Short** (more compact)
3) **Alternatives** (1–3 options)
4) **Rationale** (one sentence; tie to the user goal)

## Component heuristics

### Buttons / CTAs

- Start with a verb + object ("Create account", "Download report").
- Avoid vague labels ("Submit", "Continue") unless the context makes it unambiguous.

### Form labels + help text

- Use familiar nouns (what the user would call it).
- Add examples when it reduces errors (e.g., email format).

### Errors (required structure)

Every error message must:
1) Say what happened (in user language)
2) Say how to fix it (next step)
3) Stay calm and respectful

Template:
- "{Problem}. {Fix}."

### Empty states

- Explain why it’s empty.
- Suggest a next action.

Template:
- "No {items} yet." + "{Action} to {benefit}."

### Tone selection

- Error: calm, supportive
- Success: positive, reassuring
- Empty: encouraging
- Warning: direct, serious

## QA checklist (before shipping)

- Clear on first read?
- Helps the user complete a task?
- As short as possible?
- Tone matches the moment?
- Terms consistent across the product?

## Collaboration prompts (ask when missing)

If context is missing, ask only what you need:

- What is the user’s goal right now?
- Where does this appear (button/error/empty state/etc.)?
- Any required terminology (product nouns, role names)?
- Any hard constraints (character limit, legal wording)?

