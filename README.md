# ai-coding-framework-template

**For people who want to design their own way of building software with coding agents.** This is an empty skeleton: every file is in place, and each one says what it is for and which questions to answer. If you want a framework that is complete and ready to use, start from [ai-coding-framework](https://github.com/nurullah44/ai-coding-framework) instead.

## How to use it

1. Click **Use this template** on GitHub to create your repo.
2. Open each file below. It tells you what the file is for and lists the questions to answer. Replace the questions with your answers.
3. Each file links to its filled version in ai-coding-framework, in case you want to see one way of answering.

A good order: principles first, then the process and the roles, then the templates, and the guide last, once the rest is settled.

Claude Code reads `AGENTS.md` by itself only when there is no `CLAUDE.md`. If you add one (`/init` creates it), make its first line `@AGENTS.md`.

## The parts

| Path | What it is for |
|---|---|
| `AGENTS.md` | Loaded by every agent in every session: commands, hard rules, pointers to the rest |
| `docs/guide.md` | How a project goes from start to finish, for newcomers |
| `docs/agents/principles.md` | The few ideas every other rule serves |
| `docs/agents/process.md` | Roles, models, work size, and the rules of the loop |
| `docs/agents/roles/` | One job description per role: Planner, Builder, Reviewer, Coordinator |
| `docs/agents/templates/` | The shape of a piece of work, and of a review result |
| `docs/agents/invariants.md` | Rules the code must never break, each with what enforces it |
| `docs/agents/trust-ladder.md` | Where to fix a mistake so it can't come back |
| `docs/agents/garden.md` | The log of mistakes and corrections |
| `.agents/skills/verify/` | How agents prove a change works: the skill, a stub CLI, and a feature map |
| `tools/` | Scripts for mechanical jobs, such as starting a role |

The four roles are a starting point, not a rule. Rename, merge or add roles to fit how you work, and keep `process.md` in step.
