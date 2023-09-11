---
layout: minimal
title: 0.2.0 (1.19.2)
parent: Iteration 0.2
grand_parent: Finality Genesis Changelog
nav_order: 9
---

# Genesis 0.2.0
I was debating on if I should release this as Patch F or just go for 0.1.5 just because of the amount of changes and ended up settling on just labelling it as Patch F since it is a follow up to Patch E and the other patches that incrementally changed things. The next day... the update now has breaking changes in terms of recipes and world generation, so the version number has been bumped accordingly. As for why... it's just that a new structure has been added that replaces Minecraft's Jungle Temples.

I am fully aware of z-fighting on many blocks, but this is currently a limitation of Sodium and is outside of my control. Feel free to disable Embeddium (fork of Sodium) if it bothers you too much.

Please ignore the "Failed to parse recipe" messages related to Architect's Palette mod. This is an issue from the mod itself and not KubeJS. I have attempted to correct the 9 errored recipes many times over with JSON files AND KubeJS but the mod does simply does not care.

- [9.10.2023] Increased Zinc Nugget drop rate from Creepers from 5% to 10%.
- [9.9.2023] Implemented Create's tooltip registry to items wherever applicable to avoid Rhino's concurrency error.
- [9.9.2023] Implemented rectangle shape components and colored variations... Definitely not looking forward to making the others.
- [9.8.2023] Witches now drop Lapis Lazuli, starting at 10%
- [9.8.2023] Blacklisted Create Enchantment Industry from being picked up by Carry On so you no longer pick up your blazes when trying to take the Enchanting Guide you gave them.
- [9.8.2023] Blacklisted Create Crafts & Additions from being picked up by Carry On.
- [9.7.2023] Made Echo of the Ship Graveyard renewable with Create's automation methods.
- [9.7.2023] Made Calcite renewable with Create's automation methods.
- [9.7.2023] Made the Abyssal Sacrifice able to be fully automated.
- [9.7.2023] Made the Abyssal Amethyst able to be fully autoted.
- [9.7.2023] Made all primordial mechanisms fire resistant.
- [9.7.2023] Fixed Structure Void not being visible in JEI.
- [9.6-7.2023] Added colors, shapes, numbers and hex code crafting recipes.
- [9.5-6.2023] Re-balanced creation methods of Condensed Universal Entropy.
  - Re-implemented the old method of acquiring Condensed Universal Entropy which involved no heating whatsoever.
  - Now provides an increased yield if superheated.
- [9.5-6.2023] Added quest nodes for Construction Wand related items. 962023
- [9.5-6.2023] Added Drowned, Hoglin and Husk Gateway pearls for unlimited copper and hogskin.
- [9.5-6.2023] Added text for Phantom Membranes being renewable by haunting rotten flesh.
- [9.5-6.2023] Added text for the Enigmatic Amulet and a certain ring for new players to understand their purposes.
- [9.5-6.2023] Corrected multiple Handcrafted recipes. I genuinely do not know why they decided to handicap Create with lower percentages when making wood boards.
  - Handcrafted recipes that ask for a chest now ask for any wooden chest type.
- [9.5-6.2023] Increased Monobank capacity from 8,192 items to 16,384 items.
- [9.5-6.2023] Blacklisted flies from spawning on all Ad Astra dimensions.
- [9.5-6.2023] Blacklisted Ad Astra's rockets from being picked up by Carry On to avoid awkwardly picking up your rocket when you are trying to give it fuel from a bucket.
- [9.5-6.2023] Added a recipe for making Ad Astra's oil infinitely renewable with Create automation.
- [9.5-6.2023] Added Tier 2 and Tier 3 Artifact reward tables.
- [9.5-6.2023] Added recipes for compressing HEA into Blocks of HEA and decompressing them into HEA ingots.

## Mod updates
- [9.9.2023] Updated Embeddium `embeddium-0.1.2+mc1.19.2` to `embeddium-0.1.4+mc1.19.2`
- [9.9.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.10` to `kubejs-forge-1902.6.2-build.15`
- [9.7.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.5` to `kubejs-forge-1902.6.2-build.10`
- [9.7.2023] ~~Updated Cucumber Library `Cucumber-1.19.2-6.0.7` to `Cucumber-1.19.2-6.0.8`~~
- [9.7.2023] ~~Updated Extended Crafting `ExtendedCrafting-1.19.2-5.1.7` to `ExtendedCrafting-1.19.2-5.1.8`~~
- [9.7.2023] ~~Updated Mystical Agriculture `MysticalAgriculture-1.19.2-6.0.11` to `MysticalAgriculture-1.19.2-6.0.12`~~
- [9.7.2023] Edit: Do not update these mods to the latest version! ExtendedCrafting will delete all singularities, including its own.
- [9.5-6.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.3` to `kubejs-forge-1902.6.2-build.5`~~
- [9.5-6.2023] Updated Clickable advancements `clickadv-1.19.2-3.1` to `clickadv-1.19.2-3.4`
- [9.5-6.2023] Updated Embeddium `embeddium-0.1.0+mc1.19.2` to `embeddium-0.1.2+mc1.19.2`
- [9.5-6.2023] Updated Create Slice & Dice `sliceanddice-forge-2.3.1` to `sliceanddice-forge-2.3.2`

## Mod additions
- [9.7.2023] Added YUNG's Better Jungle Temples
- [9.5-6.2023] Added Redirectionor for even more significant performance gains after testing. Launch time is now consistently even shorter than it used to be.
- [9.5-6.2023] Added Architect's Palette
- [9.5-6.2023] Added Easy Anvils which should have been in the modpack from the very beginning.
- [9.5-6.2023] Added Client Crafting to address server latency while hosting worlds via Essential and actual server instances.
- [9.5-6.2023] Added Gadgets Against Grind
