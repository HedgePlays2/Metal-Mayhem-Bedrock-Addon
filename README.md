# Metal Mayhem — Minecraft Bedrock Add-On

A fan-made Sonic robot add-on project targeting Minecraft Bedrock **26.32**.

## Robot roster
- **Metal Sonic** — custom Golden Rings for taming; 25% planned chance per ring; mini-boss mode and Metal Sonic Core/armor are planned.
- **Mecha Sonic Mark II** — heavy hitter; **lapis lazuli** for taming, 25% chance per item.
- **Tails Doll** — eerie plush-like robot; **redstone dust** for taming, 25% chance per item.
- **Metal Knuckles** — bruiser; **emeralds only** for taming. Golden Rings must not tame him.

The three additional robots have behavior entity JSON, client entity definitions, geometry, render-controller and idle-animation files, plus starter loot tables. Initial 64×64 pixel-art texture PNGs have now been added for all four robots. These are first-pass visuals; the models remain block-based approximations and need refinement and in-game validation.

## Important status notes
- Taming/follow/combat behavior is scaffolded but not yet tested in Minecraft Bedrock 26.32.
- Loot tables currently use a temporary iron-ingot drop and must be replaced with each robot's intended unique rare drop.
- Initial PNG textures are present at `resource_pack/textures/entity/`; they are a first pass, not final game-accurate artwork.
- The blue vanilla-style Metal Sonic boss bar, Metal Sonic Core, crafting recipe for the strongest Metal Sonic Armor set, and special attacks are still planned and not implemented.
- No import-ready `.mcaddon` has been built yet.
