# November 22, 2026 — Combat milestone R7 joins the main branch

**Language:** **English** · [Русский](2026-11-22-combat-r7-checkpoint.ru.md)

*Progress report based on the verified Saltshore T14 R7 checkpoint and merged development PR #2. This is not a public game release.*

## What changed

The T14 combat prototype was consolidated into the game's main development branch after an owner-reviewed playtest. Its technical foundations include turn-based combat rules, character actions, equipment durability, combat presentation, enemy behavior, and a dedicated set of test scenarios.

The team worked on attack poses, weapon handling, character movement, and the visual transitions involved in grapples and equipment changes. The test harness covers six combat scenarios in an isolated environment.

## What is actually ready?

**A functional work-in-progress, not finished combat.** The battle components remain opt-in rather than wired into the ordinary story route. The art and animation coverage is incomplete, and the creator has not given final visual approval.

The R7 checkpoint recorded 66 unresolved art-coverage checks, alongside known transition and pose issues. Automated checks show that substantial parts of the underlying system work, but passing tests is not the same as a polished, playable encounter.

## Next steps

Resolve the missing artwork and transition states, repeat hands-on testing, and obtain explicit acceptance before combat becomes part of the main game flow.

[Development log](../README.md#development-log) · [Current status](../docs/STATUS.md)
