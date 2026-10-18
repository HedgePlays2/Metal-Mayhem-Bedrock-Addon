# Metal Mayhem — Sonic Robots Minecraft Bedrock Add-On

A fan-made Sonic robot add-on project targeting Minecraft Bedrock **26.32**.

## Robot roster
- **Metal Sonic** — custom Golden Rings for taming; 25% planned chance per ring; mini-boss mode and Metal Sonic Core/armor are planned.
- **Mecha Sonic Mark II** — heavy hitter; Golden Rings for taming.
- **Tails Doll** — eerie plush-like robot; Golden Rings for taming.
- **Metal Knuckles** — bruiser; **emeralds only** for taming. Golden Rings must not tame him.

The three additional robots now have initial behavior entity JSON, client entity definitions, geometry, render-controller and idle-animation files, plus starter loot tables. These are source scaffolds and need in-game validation; the models are block-based approximations, not finished game-accurate models.

## Important status notes
- Taming/follow/combat behavior is scaffolded but not yet tested in Minecraft Bedrock 26.32.
- Loot tables currently use a temporary iron-ingot drop and must be replaced with each robot's intended unique rare drop.
- The client definitions refer to PNG textures that still need to be created. Until those textures exist, the robots will not have their intended appearances.
- The blue vanilla-style Metal Sonic boss bar, Metal Sonic Core, crafting recipe for the strongest Metal Sonic Armor set, and special attacks are still planned and not implemented.
- No import-ready `.mcaddon` has been built yet.
