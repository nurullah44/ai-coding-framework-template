---
name: verify
description: Drive the running app like a user and capture evidence that a change works. Use before handing off any change, when verifying someone else's change, or when reproducing a bug report.
---

# Verify

> **Fill this in.** How agents prove a change works on the running app instead of claiming it. The `verify` script next to this file is a stub that answers "not configured" (exit 2) until you build the real one.

## Questions to answer

- Which commands does the proof tool have (for example: check health, start and stop an instance, perform one user action, save evidence, run every feature)?
- What counts as proof, and what does not ("it opens", a passing unit test)?
- What is the result when the proof could not run?
- Where is the evidence kept?

## A filled example

[`.agents/skills/verify/SKILL.md` in ai-coding-framework](https://github.com/nurullah44/ai-coding-framework/blob/main/.agents/skills/verify/SKILL.md).
