# AGENTS.md

> **Fill this in.** Every agent loads this file in every session, so keep it short: the commands, the hard rules, and pointers to the rest. Detail lives in `docs/agents/`.

## Commands

| Purpose | Command | Notes |
|---|---|---|
| Install | `TODO` | |
| Check (every fast gate: format, lint, typecheck, unit tests) | `TODO` | |
| Verify (drive the real app) | `.agents/skills/verify/verify <cmd>` | See the `verify` skill |

## Hard rules

<!-- The handful of rules every agent must follow in every session. Each should serve one of your principles (docs/agents/principles.md). -->

1. `TODO`

## One-way doors

<!-- Changes that are hard to undo and always need a human. Globs, for example migrations/**, auth/**, anything that deletes user data. -->
- `TODO`

## Read when

- New to this project → `docs/guide.md`
- Taking part in the work loop → `docs/agents/process.md` and your role file in `docs/agents/roles/`
- Fixing a recurring mistake → `docs/agents/trust-ladder.md`
- Adding a rule the code must never break → `docs/agents/invariants.md`
- Proving a change works → the `verify` skill (`.agents/skills/verify/SKILL.md`)

A filled example: [`AGENTS.md` in ai-coding-framework](https://github.com/nurullah44/ai-coding-framework/blob/main/AGENTS.md).
