# Goblet Resource Pack — Minecraft Java 26.2

This directory is for the custom goblet model for the Minestom project.

## Contents
Download the generated ZIP from the conversation and extract the contents of its `resourcepack/` folder here so that `pack.mcmeta` and `assets/` are directly inside this directory.

The resource pack defines a custom item model (`goblet:goblet`) intended for a server-side `ItemDisplay`. It does **not** replace the vanilla Copper Golem's own entity geometry; vanilla clients without mods cannot load arbitrary resource-pack geometry for mob entities. Minestom can display the goblet model as an `ItemDisplay` and implement movement/behavior server-side.

## Setup
1. Put `pack.mcmeta` and `assets/` in this directory's root.
2. Zip the contents of this directory (not the containing folder).
3. Host the ZIP at a direct HTTPS URL.
4. Send it to clients through Minestom's server resource-pack mechanism.

Note: this commit adds the setup instructions only. The model JSON and PNG binary texture still need to be uploaded from the provided ZIP.