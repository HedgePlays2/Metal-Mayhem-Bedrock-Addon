# Sonic Robots — Minecraft Bedrock Add-On

A fan-made Sonic robot add-on project targeting Minecraft Bedrock **26.32**.

## Current source files
- `behavior_pack/` — behavior pack manifest, entity definition, Golden Ring item and recipe
- `resource_pack/` — resource pack manifest, entity client definition, model geometry, render controller and animation

## Planned gameplay

All four robots are tamable companions that follow their owner and fight hostile mobs. **Taming items differ by robot:**
- **Metal Sonic:** custom Golden Rings, with a random chance per ring (25% planned)
- **Mecha Sonic Mark II:** custom Golden Rings, with a random chance per ring
- **Tails Doll:** custom Golden Rings, with a random chance per ring
- **Metal Knuckles:** **emeralds only** — Golden Rings cannot tame him

### Metal Sonic
- Classic-inspired blue Metal Sonic with red eyes, long quills, red chest panel and hover shoes
- When hit, enters mini-boss mode and retaliates
- Aim for a blue, vanilla-style boss health bar
- Drops a rare Metal Sonic Core used to craft **Metal Sonic Armor**, intended to be exceptionally difficult to obtain and the strongest armor set in the add-on

### Additional robot bosses
- **Mecha Sonic Mark II** — heavy-hitting boss with powerful charge/spin attacks and its own rare drop
- **Tails Doll** — eerie floating boss with hovering and surprise attacks, plus a unique drop
- **Metal Knuckles** — close-range bruiser with powerful punches and a charging attack, plus a unique drop

Each boss, taming behavior, drop, armor recipe, boss bar and special attack still needs implementation and testing. The blue Metal Sonic boss bar is a design goal; it is not implemented yet.

## Status
The JSON/source scaffolding is in progress. **This repository does not yet contain the finished PNG textures or an import-ready `.mcaddon` file.** The model geometry is an initial block-style approximation and still needs a polished texture/model pass and in-game validation for Bedrock 26.32.
