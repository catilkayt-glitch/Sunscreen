# Goblet Resource Pack — Minecraft Java 26.2

A client-mod-free item model pack for the Minestom project.

## Files in this directory

- `pack.mcmeta` — resource-pack format metadata for Java 26.2 (resource pack format 88).
- `assets/goblet/items/goblet.json` — item definition with model ID `goblet:goblet`.
- `assets/goblet/models/item/goblet.json` — blockbench-style cuboid item geometry for a chalice/goblet.
- `assets/goblet/textures/item/goblet.png` — copper-gold pixel texture.

## Minestom usage

Use an `ItemDisplay` and set its item stack's item-model component to `goblet:goblet`. Deliver this resource pack to clients through Minestom using a direct HTTPS URL and the ZIP's SHA-1 hash.

## Important limitation

This pack does not replace the vanilla Copper Golem's built-in entity geometry. Vanilla clients without mods cannot replace an arbitrary mob's 3D geometry through a resource pack alone. For a mod-free server, use the goblet model on an `ItemDisplay` and implement mob-like movement/behavior server-side in Minestom.
