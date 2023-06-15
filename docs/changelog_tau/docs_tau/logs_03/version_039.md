---
layout: default
title: Finality Tau 0.3.9b
nav_order: 1
parent: Tau Iteration 0.3
grand_parent: Finality Tau Changelog
---
# v0.3.9.2b Changelog

Again, I am very sorry if you have not been able to progress through the introductory quests due to the Handheld Crafting Table not being craftable. It has been fixed accordingly.

- Added "You can also now repair your tools in the crafting grid with their respective materials, so you won't have to throw away your items." to the `Useful Utilities` quests.
- Fixed the missing reward for `I don't remember Sugar Cane growing that tall...` 
- Added the Aquamirae Tips entry in the Tome of Finality
- Added more text to The Graveyard entry to serve as a hint on where to find the boss.
- Lowered teleportation chance significantly to 1%.
- Fixed Handheld Crafting Table recipe script.
- Fixed (hopefully) statues teleporting players to other dimensions that can't be escaped by normal means. If this still occurs I will have to disable this mechanic entirely.

## Mod updates for 0.3.9.2b

- Updated Vinery Let's Do Wine! to `vinery-forge-1.2.10.jar` from `vinery-forge-1.2.9.jar`
  - Fixed an Issue where you have been able to drink GrapeJuice limitless
  - Fixed an Issue where you haven’t been able to place Wine Bottles on a Big Table 
  - Fixed an Issue causing the Cooking Pot to crash the game
  - Fixed an Issue causing the Fermentation Barrel to crash the game
  - Fixed an Issue causing the Wood Fired Oven to crash the game
  - Fixed an Issue causing Apple Leaves to decay instantly
  - Fixed multiple recipe errors
  - Fixed Cooking Pot particle effects
  - Removed the ‚Empty‘-Effect

- Updated Ars Nouveau to `ars_nouveau-1.19.2-3.15.1.jar` from `ars_nouveau-1.19.2-3.15.0.jar`
  - Fix log spam

- Updated Botania to `Botania-1.19.2-440-FORGE.jar` from `Botania-1.19.2-439-FORGE.jar`, patch notes located below.
  1.19.2-440
  - Add: The Worldshaper’s Sextant can now generate spheres as well (Wormbo)
  - Add: Grass Seeds can now be placed by dispensers.
  - Add: Manufactory Halo’s auto-crafting can be toggled by shift+right-clicking the crafting table segment or right-clicking the item in an inventory screen
  - Add: Mana lenses can now be merged using either honey bottles or slime balls
  - Add: Conversion chances for Orechid, Orechid Ignem, and Marimorphosis (including biome-specific chances for player’s location) are now displayed in the recipe listings of JEI,  REI, and EMI (Wormbo)
  - Add: Reintroduce the useShaders config option to disable Botania’s special shaders
  - Add: zh_cn updates (Dawnwalker666)
  - Change: The Worldshaper’s Sextant provides more control over the exact shape of circles by having the radius selection snap to the block grind instead of only allowing integers  (Wormbo)
  - Change: The Rosa Arcana’s XP orb mana yield now matches the player-based mana yield
  - Change: The Worldshaper’s Sextant provides more control over the exact shape of circles by having the radius selection snap to the block grind instead of only allowing integers  (Wormbo)
  - Change: Worldshaper’s Astrolabe now places blocks more like a player would, e.g. waterlogging blocks where appropriate, adding more candles to existing ones, or rotating  directional blocks according to the player’s view direction, targeted block side, or available attachment options
  - Fix: Made Teru Teru Bozu truely happy during clear weather again (Wormbo)
  - Fix: Leaves placed by Worldshaper’s Astrolabe no longer decay
  - Fix: Some items being missing from Forge equipment tags and Fabric bow tag
  - Fix: Using an empty bottle in the end will not attempt to pick up Ender Air if the player is aiming at a liquid (Wormbo)
  - Fix: Horn of the Canopy breaking persistent leaves
  - Fix: Thermalily not updating comparators properly
  - Fix: Kindle Lens not creating Soul Fire when it should
  - Fix: Fake bursts triggering game events
  - Fix: Biomes not populating properly in Garden of Glass
  - Fix: Some structures showing up in Garden of Glass
  **Note: These two fixes do not require a GoG jar update, but will only cover newly-generated terrain.**

- Updated Chipped to `chipped-forge-1.19.2-2.1.5.jar` from `chipped-forge-1.19.2-2.1.4.jar`
  - fixed big lanterns being uncrafteable
  - fixed the stiped bug
  - made the mechanist table recipe use any wood type instead of specifically requiring oak and spruce

- Updated Xaero's Minimap to `Xaeros_Minimap_23.4.4_Forge_1.19.1.jar` from `Xaeros_Minimap_23.4.3_Forge_1.19.1.jar`
Update 23.4.4/23.3.6 (2023/05/24):
Minecraft versions: 1.19.4 - 1.19.1, 1.18.2, 1.17.x, 1.16.5 - 1.16.2, 1.15.2, 1.12.2

  - (1.19.4 - 1.16.2, 1.12.2) Compatible with Xaero's World Map 1.11.0 or newer. Version 1.30.3 is HIGHLY recommended.
  - (1.15.2) Compatible with Xaero's World Map 1.11.0 or newer. Version 1.29.9 is HIGHLY recommended.
  - (1.19.4 - 1.16.2) Added a new option to disable biome blending on the map, which can help with performance a lot in some cases of modded biome color calculation.
  - (1.19.4 - 1.19.2) Fixed image widgets not working.
  - (1.19.4 - 1.17) Improved matrix restoration in case of errors during entity icon prerender.
  - (1.19.4 - 1.15.2) Fixed entity icons not supporting entity models that use texture sprite atlases.
  - (1.19.4 - 1.16.2, 1.12.2) Reworked how "solid" blocks are detected when determining automatic cave mode so that it is partially based on what the map would display as transparent.

- Updated Xaero's World Map to `XaerosWorldMap_1.30.3_Forge_1.19.1.jar` from `XaerosWorldMap_1.30.2_Forge_1.19.1.jar` 
Update 1.30.3/1.29.9/1.14.1.24 (2023/05/24):
Minecraft versions: 1.19.4 - 1.19.1, 1.18.2, 1.17.x, 1.16.5 - 1.16.2, 1.15.2, 1.14.4, 1.12.2, 1.8.9, 1.7.10

  - (1.19.4 - 1.16.2, 1.12.2) Compatible with Xaero's Minimap / Better PVP 20.23.0 or newer. Version 23.4.4 is HIGHLY recommended.
  - (1.15.2, 1.14.4) Compatible with Xaero's Minimap / Better PVP 20.23.0 or newer. Version 23.3.6 is HIGHLY recommended.
  - (1.8.9 - 1.7.10) Compatible with Xaero's Minimap / Better PVP 20.23.0 or newer. Version 21.10.33 is HIGHLY recommended.
  - (1.19.4 - 1.16.2, 1.12.2) Added a new option to disable biome blending on the map, which can help with performance a lot in some cases of modded biome colors.
  - (1.12.2) Fixed occasional freeze on dimension change or world leave.
  - (1.19.4 - 1.16.2, 1.12.2) Reworked how "solid" blocks are detected when determining automatic cave mode or the top Y for the full cave mode type so that it is partially based on what the map would display as transparent.
  - (1.19.4 - 1.16.2) Significantly optimized loading biomes from world save in singleplayer. Especially noticeable improvement when going between cave mode layers.
  - (Fabric) Fixed compatibility with older minimap versions.
  - Fixed corrupt heights in saved map data causing full crashes.

- Updated Citadel to `citadel-2.1.4-1.19.jar` from `citadel-2.1.3-1.19.jar`
  - Fixed issue with Terrablender with memory usage on relog causing worlds to be unplayable. This fix is for new worlds only; old worlds should have their level.dat reset using a NBTExplorer program.
- Updated Bookshelf to `Bookshelf-Forge-1.19.2-16.3.20.jar` from `Bookshelf-Forge-1.19.2-16.2.18.jar`
- Updated CorgiLib to `CorgiLib-forge-1.19.2-1.0.0.34.jar` from `CorgiLib-forge-1.19.2-1.0.0.33.jar`

--- 

# v0.3.9.1b Changelog

**Downgraded Flat Colored Blocks to fix the invalid recipe serializer error on multiplayer servers. A server pack can now be released.**

---

# v0.3.9b Changelog
**Major changes. It is recommended to re-generate your world seed.**

{: .warning}
FTB Chunks is being replaced by xaero96's suite of mods due to its inability to share waypoints or make waypoints visible to the players in the same FTB Teams. This should have been a *basic* functionality from the mod. Please back up all your waypoints and note their exact X, Y and Z coordinates. It is not my fault if you update to this version without reading the changelog. This was made obvious while doing multiplayer playthroughs. JourneyMap will never be added due to being resource intensive.

{: .warning}
Do NOT update Some Assembly Required. It will require Create 0.5.1a and all modpack development tools are currently still behind. Please wait for the developers of KubeJS and KubeJS Create to add support for Create 0.5.1a! Quark currently also has issues with Create 0.5.1a.

# Cataclysm
~~Fixed L_Ender's broken English with lang files in the modpack resourcepack, you're welcome.~~
Edit: I quickly found out that you can't add more lines to the existing tooltip. Back to KubeJS tooltip modification.

# FTB Quests
Fixed the Cataclysm and Enigmatic Legacy related chapters and their quests.

# Tome of Finality (patchouli guidebook)
Updated entries to be on par with the 1.18.2 variant where FTB Chunks was removed.

## Updated mods
* Updated Flat Colored Blocks - Forge from `flat-colored-blocks-forge-1.0.9.jar` to `flat-colored-blocks-forge-1.0.11.jar`
* Updated Aquamirae from `aquamirae-5.6.API14.jar` to `aquamirae-6.API15.jar`
* Updated Placebo from `Placebo-1.19.2-7.1.8.jar` to `Placebo-1.19.2-7.2.0.jar`
* Updated Apotheosis from `Apotheosis-1.19.2-6.1.5.jar` to `Apotheosis-1.19.2-6.2.1.jar`
* Updated Gateways to Eternity from `GatewaysToEternity-1.19.2-3.1.1.jar` to `GatewaysToEternity-1.19.2-3.2.0.jar`
* Updated Moonlight Lib `moonlight-1.19.2-2.2.33-forge.jar` to `moonlight-1.19.2-2.2.34-forge.jar`
* Updated Supplementaries from `supplementaries-1.19.2-2.3.10.jar` to `supplementaries-1.19.2-2.3.12.jar`


## Mod additions
* Added [Vinery - Let's Do Wine! by satisfyL](https://www.curseforge.com/minecraft/mc-mods/lets-do-wine)
  * Re-adding this.
* Added [Gardens of the Dead by ochotonida](https://www.curseforge.com/minecraft/mc-mods/gardens-of-the-dead)
  * Re-adding this.
* [Chunk Loaders](https://www.curseforge.com/minecraft/mc-mods/chunk-loaders)
* [Cloud Storage](https://www.curseforge.com/minecraft/mc-mods/alexs-cloud-storage)
* [Whisperwoods](https://www.curseforge.com/minecraft/mc-mods/whisperwoods)
* [Eyes in the Darkness](https://www.curseforge.com/minecraft/mc-mods/eyes-in-the-darkness)
* [True Darkness](https://www.curseforge.com/minecraft/mc-mods/true-darkness)
* [Pickle Tweaks](https://www.curseforge.com/minecraft/mc-mods/pickle-tweaks)
* [The Undergarden](https://www.curseforge.com/minecraft/mc-mods/the-undergarden)
* [Doctor Who - Weeping Angels](https://www.curseforge.com/minecraft/mc-mods/weeping-angels-mod)
* [Mahou Tsukai](https://www.curseforge.com/minecraft/mc-mods/mahou-tsukai)
* [Savage and Ravage](https://www.curseforge.com/minecraft/mc-mods/savage-and-ravage)

## Mod removals
* Removed FTB Chunks
* Removed Ender Crop
* Removed Twilight Forest
* Removed Iron Chests in favor for Sophisticated Storage

## Resourcepack additions
Absolutely nothing to see there.