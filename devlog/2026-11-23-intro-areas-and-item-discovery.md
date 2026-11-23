# November 23, 2026 — Three opening areas and clearer interactions

**Language:** **English** · [Русский](2026-11-23-intro-areas-and-item-discovery.ru.md)

*Development milestone confirmed by the creator and merged through the private game's PR #3 on November 23, 2026.*

## A stronger opening for Saltshore

The creator has accepted a revised set of three opening locations: the **shipwreck beach**, the **cave and spring**, and a **forest clearing**. This work includes the environments, movement routes, collisions, lighting, transitions, and introductory objects.

It is an important step toward a more cohesive beginning, though it does **not** mean that the full first chapter is complete.

## Interactions that are easier to read

Nearby interactive objects now receive a subtle outline and a relevant action label. Farther away, eligible objects use a restrained blue-green marker. In the cave, these cues respect the lighting system, so information is not revealed through darkness.

The changes are about helping players understand what can be inspected or collected without burying the scene under intrusive UI.

## New resources and the beginnings of discovery

**Forest berries, mushrooms, and plantain leaves** now have dedicated inventory icons and reusable descriptions.

Their properties initially appear **unknown**. The game can save learned information, but the broader teaching, reading, and consumption mechanics are not fully implemented. In particular, a character with Intelligence 2 does **not** automatically uncover the resources' properties by consuming them.

## Verification and limitations

The R03 review included targeted interaction and lighting checks, the introductory route, inventory rendering, and save compatibility. Some pre-existing validation discrepancies and a narrow-width UI test issue remain documented internally.

No new world screenshots are included in this public journal entry. The environments will be shown when the creator selects suitable, approved images.

## What's next

Polish the opening experience and its presentation, then continue building the story and the systems that make choices matter.

[Development log](../README.md#development-log) · [Roadmap](../docs/ROADMAP.md)
