---
layout: minimal
title: Version 0.6.0b
grand_parent: Finality Changelog
parent: Iteration 0.6
has_children: true
nav_order: 2
---
# Version 0.6.0b (Create 0.5.1b)

In Development
{: .label .label-yellow }

{: .highlight }
All files have been scanned for Fractureiser malware before exporting. None of the files have it present as of 6.28.23

- Updated Forge from 40.2.8 to 40.2.9.
- KubeJS Create has been updated to have compatibility with Create 0.5.1b.

This changelog has been written after I wrote the changelog for Finality Tau, so this is going to be a lot of repeated lines.

## 7.3.2023 Changes

### Mod additions
- Re-added Default Options because KubeJS `defaultoptions.txt` keybind boogaloo.

### Mod updates
- Updated Chunk Loaders from `chunkloaders-1.2.3-forge-mc1.18.jar` to `chunkloaders-1.2.4-forge-mc1.18.jar` https://www.curseforge.com/minecraft/mc-mods/chunk-loaders/files/4616512
- Updated Dimensional Dungeons from `dimdungeons-177-forge-1.18.2.jar` to `dimdungeons-178-forge-1.18.2.jar` https://www.curseforge.com/minecraft/mc-mods/dimensional-dungeons/files/4619978
- Updated Ender's Delight from `endersdelight-1.18.2-1.0.1.jar` to `endersdelight-1.18.2-1.2.jar` https://www.curseforge.com/minecraft/mc-mods/enders-delight/files/4620613
- Updated Fusion (Connected Textures) from `fusion-1.0.1-forge-mc1.18.jar` to `fusion-1.0.2-forge-mc1.18.jar` https://www.curseforge.com/minecraft/mc-mods/fusion-connected-textures/files/4621066
- Updated Macaw's Lights and Lamps from `mcw-lights-1.0.5-mc1.18.2forge.jar` to `mcw-lights-1.0.6-mc1.18.2forge.jar` https://www.curseforge.com/minecraft/mc-mods/macaws-lights-and-lamps/files/4618176
- Updated Open Parties and Claims from `open-parties-and-claims-forge-1.18.2-0.17.6.jar` to `open-parties-and-claims-forge-1.18.2-0.18.0.jar` https://www.curseforge.com/minecraft/mc-mods/open-parties-and-claims/files/4617202
- Updated Polymorph from `polymorph-forge-1.18.2-0.46.jar` to `polymorph-forge-1.18.2-0.48.jar` https://www.curseforge.com/minecraft/mc-mods/polymorph/files/4617431
- Updated Sophisticated Backpacks from `sophisticatedbackpacks-1.18.2-3.18.53.859.jar` to `sophisticatedbackpacks-1.18.2-3.18.55.869.jar` https://www.curseforge.com/minecraft/mc-mods/sophisticated-backpacks/files/4618523
- Updated Sophisticated Core from `sophisticatedcore-1.18.2-0.5.72.331.jar` to `sophisticatedcore-1.18.2-0.5.76.345.jar` https://www.curseforge.com/minecraft/mc-mods/sophisticated-core/files/4620053
- Updated Sophisticated Storage from `sophisticatedstorage-1.18.2-0.8.28.481.jar` to `sophisticatedstorage-1.18.2-0.8.31.508.jar` https://www.curseforge.com/minecraft/mc-mods/sophisticated-storage/files/4620059

## 6.28.2023 Mod updates
- Updated Ice and Fire from `iceandfire-2.1.12-1.18.2-beta2.jar` to `iceandfire-2.1.12-1.18.2.jar` https://www.curseforge.com/minecraft/mc-mods/ice-and-fire-dragons/files/4614465
  - new riding system, courtesy of quinnfrost
  - added Terralith and Biomes You'll Go biome support
  - removed dimension config entries since they don't really serve a purpose anymore
  - split configs for dragon related feature generation into cave and non cave configs
  - faster swim for ice and fire dragons
  - ice dragons are now unaffected by the bubble columns
  - fire dragons are now unaffected by the soul sands
  - fixed dragons in water no longer float forwards
  - fixed shallow water blocking dragon movement
  - fixed larger dragons not stepping up more blocks
  - fixed debug pathfind node rendering failed to update properly in dedicated server mode
  - fixed move wrongly error
  - fixed camera not adjust accordingly when auto 3rd person is disabled
  - fixed null error for riding swimming mounts
  - fixed flight on servers might get kicked
  - fixed rider dismount position
  - fixed mob AI not working whilst riding
  - fixed some pathfinding crashes
  - fixed durability of tools and swords
  - fixed dragons and the likes not being able to pathfind below y 0
  - fixed hippocampus riding issues
  - fixed cockatrice not moving
  - fixed incorrect biome entry type for custom biomes
- Updated Artifacts from `artifacts-1.18.2-4.2.1.jar` to `artifacts-1.18.2-4.2.2.jar` https://www.curseforge.com/minecraft/mc-mods/artifacts/files/4614546
  - Fix Charm of Sinking not working after switching dimensions
- Updated Max Health Fix from `MaxHealthFix-Forge-1.18.2-5.0.1.jar` to `MaxHealthFix-Forge-1.18.2-5.0.4.jar`
  - Fix mobs being unintentionally revived in some circumstances. ([8eb3736](https://github.com/Darkhax-Minecraft/Max-Health-Fix/commit/8eb3736b74264118bf874301a7250bdfae1ab0df))
  - https://www.curseforge.com/minecraft/mc-mods/max-health-fix/files/4609586
- Updated Dungeon Crawl from `DungeonCrawl-1.18.2-2.3.12.jar` to `DungeonCrawl-1.18.2-2.3.14.jar`
  - `[2.3.14]` Fixed an issue causing the biome used for the dungeon type/theme selection to be probed not at the dungeon entrance's location but at an offset from it
  - https://www.curseforge.com/minecraft/mc-mods/dungeon-crawl/files/4612221

Here are some important things to note:
- Dimensional Dungeons has been updated with new rooms, so you may have to re-generate your dungeons.
- ~~JEI has been replaced with REI.~~ Edit: Apotheosis requires JEI 9.999999999999999999 so I can't replace JEI with REI. These changes have been reversed.
  - ~~Just a change of pace as I got tired of JEI's rigidity even though it is faster than REI. Don't worry, everything still works as intended and you may make use of REI's features. You might even like how nice it is as well. Did I mention REI has dark mode built in?~~
    - ~~Just Enough Resources removed.~~
    - ~~Just Enough Professions removed.~~

## Recipe changes
- Ars Nouveau spell Book Tier 1 recipe has been reverted back to using Steeleaf with charorite removed.
  - 4 Steeleaf tools
  - 1 Andesite Alloy
  - 1 Golden Carrot
  - 1 Book
  - 1 Amethyst
- Ars Nouveau Spell Book Tier 3 recipe has been adjusted to use:
  - 1 Ender Star (instead of enhanced ender catalyst)
  - 1 Wilden Tribute
  - 2x Tertium Essence (instead of ProjectE dark matter)
  - 3x Precision Mechanism
  - 1 Totem of Undying
- Re-enabled Mystical Agriculture's furnaces
  - Yes, all 5 tiers.
- Re-enabled ProjectE's furnaces

## Finality Core changes
- Added tight Create integration for Tinker's Construct.
- Changed Wither Storm related recipes to use Insanium Essence, not just corruption.
  - This should have been the original recipe.
- Revised singularity crafting, the first test is the Andesite Alloy singularity. The other singularities will follow.
  - Now requires dormant singularity cores to start the process.
  - Now requires Condensed Universal Entropy, which can be extracted from compressing 9 Crying Obsidian blocks.

Basically you have to extract Condensed Universal Entropy from the Crying Obsidian, then use a spout to pour it into a sequenced assembly recipe.

## Mod updates pt. 2
6/25/2023
Just going to separate updates for mods now into multiple parts in case it gets overwhelming to keep track of if a mod has been updated multiple times and has been documented here. I can't keep pasting changelogs for each update, so you will have to find the mod author changelogs yourself.

| Mod name | Updated from | Updated to | Changelog (if applicable) |
| -------- | ------------ | ---------- | ------------------------- |
| CodeChicken Lin 1.8.+ | CodeChickenLib-1.18.2-4.1.3.480-universal.jar | CodeChickenLib-1.18.2-4.1.4.488-universal.jar | https://www.curseforge.com/minecraft/mc-mods/codechicken-lib-1-8/files/4607274 |
| Collective | collective-1.18.2-6.57.jar | collective-1.18.2-6.62.jar | https://www.curseforge.com/minecraft/mc-mods/collective/files/4601901 |
| Create Central Kitchen | create_central_kitchen-1.18.2-for-create-0.5.1.b-1.3.7.c.jar | create_central_kitchen-1.18.2-for-create-0.5.1.b-1.3.7.d.jar | https://www.curseforge.com/minecraft/mc-mods/create-central-kitchen/files/4599771 |
| Create Crafts & Additions | createaddition-1.18.2-20230527a.jar | createaddition-1.18.2-20230623a.jar | https://www.curseforge.com/minecraft/mc-mods/createaddition/files/4605624 |
| Create Enchantment Industry | create_enchantment_industry-1.18.2-for-create-0.5.1.b-1.2.4.c.jar | create_enchantment_industry-1.18.2-for-create-0.5.1.b-1.2.5.jar | https://www.curseforge.com/minecraft/mc-mods/create-enchantment-industry/files/4604040 |
| Lightspeed - Launch optimizations | lightspeed-1.18.2-1.0.4.jar | lightspeed-1.18.2-1.0.5.jar | https://www.curseforge.com/minecraft/mc-mods/lightspeedmod/files/4594803 |
| Lootr (Forge) | lootr-1.18.2-0.3.25.62.jar | lootr-1.18.2-0.3.25.63.jar | https://www.curseforge.com/minecraft/mc-mods/lootr/files/4596362 |
| Mahou Tsukai | mahoutsukai-1.18.2-v1.34.46.jar | mahoutsukai-1.18.2-v1.34.50.jar | https://www.curseforge.com/minecraft/mc-mods/mahou-tsukai/files/4606624 |
| Occultism | occultism-1.18.2-1.80.4.jar | occultism-1.18.2-1.80.12.jar | https://www.curseforge.com/minecraft/mc-mods/occultism/files/4607182 |
| Open Parties and Claims | open-parties-and-claims-forge-1.18.2-0.17.5.jar | open-parties-and-claims-forge-1.18.2-0.17.6.jar | https://www.curseforge.com/minecraft/mc-mods/open-parties-and-claims/files/4603053 |
| Puzzles Lib [Forge & Fabric] | PuzzlesLib-v3.4.5-1.18.2-Forge.jar | PuzzlesLib-v3.4.6-1.18.2-Forge.jar | https://www.curseforge.com/minecraft/mc-mods/puzzles-lib/files/4597628 |
| Re-chiseled | rechiseled-1.0.13-forge-mc1.18.jar | rechiseled-1.1.0a-forge-mc1.18.jar | https://www.curseforge.com/minecraft/mc-mods/rechiseled/files/4598514 |
| Sophisticated Backpacks | sophisticatedbackpacks-1.18.2-3.18.52.846.jar | sophisticatedbackpacks-1.18.2-3.18.53.859.jar | https://www.curseforge.com/minecraft/mc-mods/sophisticated-backpacks/files/4608437 |
| Sophisticated Core | sophisticatedcore-1.18.2-0.5.70.320.jar | sophisticatedcore-1.18.2-0.5.72.331.jar | https://www.curseforge.com/minecraft/mc-mods/sophisticated-core/files/4608423 |
| Sophisticated Storage | sophisticatedstorage-1.18.2-0.8.26.454.jar | sophisticatedstorage-1.18.2-0.8.28.481.jar | https://www.curseforge.com/minecraft/mc-mods/sophisticated-storage/files/4608435 |
| SuperMartijn642's Core Lib | supermartijn642corelib-1.1.9a-forge-mc1.18.jar | supermartijn642corelib-1.1.10-forge-mc1.18.jar | https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-core-lib/files/4601824 |
| Xaero's Minimap | Xaeros_Minimap_23.4.4_Forge_1.18.2.jar | Xaeros_Minimap_23.5.0_Forge_1.18.2.jar | https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap/files/4593177 |
| Xaero's World Map | XaerosWorldMap_1.30.3_Forge_1.18.2.jar | XaerosWorldMap_1.30.6_Forge_1.18.2.jar | https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map/files/4594980 |

## Mod updates
Mod updates in addition to the pre-existing changelog.

- Updated Just Enough Items from `jei-1.18.2-forge-10.2.1.1004.jar` to `jei-1.18.2-forge-10.2.1.1005.jar`
- Updated Drippy Loading Screen from `drippyloadingscreen_forge_2.2.1_MC_1.18.2.jar` to `drippyloadingscreen_forge_2.2.2_MC_1.18.2.jar` so you no longer have to worry about the ever growing `.txt` file in the config folder. Good thing I contacted Keksuccino about this XD
  - Fixed: Drippy keeps adding new entries to the `config/fancymenu/customizablemenus.txt` file on every game launch
- Updated Curios API (Forge) from `curios-forge-1.18.2-5.0.9.0.jar` to `curios-forge-1.18.2-5.0.9.1.jar`
  - Fixed possible NullPointerException crash from SlotResult
- Updated Every Compat (Wood Good) to `everycomp-1.18.2-1.5.18.jar` from `everycomp-1.18.2-1.5.17.jar`
  - REQUIRED for compatibility with Create 0.5.1b.
- Updated Create to `0.5.1b` `create-1.18.2-0.5.1.b.jar` from `0.5.0i` `create-1.18.2-0.5.0.i.jar`
  - This means certain add ons are going to have to go if they do not have support for it yet.
- Updated Create Cafe to `createcafe-1.10.2-1.18.2.jar` from `createcafe-1.10.0-1.18.2.jar`
  - Required for compatibility with `0.5.1b`
- Updated Create Slice & Dice to `sliceanddice-forge-1.2.1.jar` from `sliceanddice-1.1.3.jar`
  - Required for compatibility with `0.5.1b`.
- Updated Create Central Kitchen to `create_central_kitchen-1.18.2-for-create-0.5.1.b-1.3.7.c.jar` from `create_central_kitchen-1.18.2-for-create-0.5.0.i-1.3.2.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Create Enchantment Industry to `create_enchantment_industry-1.18.2-for-create-0.5.1.b-1.2.4.c.jar` from `create_enchantment_industry-1.18.2-for-create-0.5.0.i-1.2.0.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Some Assembly Required to `some-assembly-required-1.18.2-2.0.9.jar` from `some-assembly-required-1.18.2-2.0.8.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Create Crafts & Additions to `createaddition-1.18.2-20230527a.jar` from `createaddition-1.18.2-20230507a.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Create Deco to `createdeco-1.3.3-1.18.2.jar` from `createdeco-1.3.2-1.18.2.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Create Confectionery to `create-confectionery1.18.2_v1.0.9.jar` from `create-confectionery1.18.2_v1.0.8.jar`
- Updated Create Stuff & Additions to `create-stuff-additions1.18.2_v2.0.3b.jar` from `create-stuff-additions1.18.2_v2.0.2c.jar`
- Updated Create Chunkloading to `createchunkloading-1.4.0-forge.jar` from `createchunkloading-1.2.1-forge.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Create: Alloyed to `alloyed-1.18.2-v1.5a.jar` from `alloyed-1.18.2-v1.4e.jar`
  - Required for compatibility with Create `0.5.1b`.
- Updated Supplementaries to `supplementaries-1.18.2-1.5.18.jar` from `supplementaries-1.18.2-1.5.17.jar`
- Updated Sophisticated Backpacks, Sophisticated Storage and Sophisticated Core
  - Sophisticated Backpacks from `sophisticatedbackpacks-1.18.2-3.18.48.835.jar` to `sophisticatedbackpacks-1.18.2-3.18.52.846.jar` 
  - Sophisticated Storage from `sophisticatedstorage-1.18.2-0.8.5.401.jar` to `sophisticatedstorage-1.18.2-0.8.26.454.jar`
  - Sophisticated Core from `sophisticatedcore-1.18.2-0.5.56.273.jar` to `sophisticatedcore-1.18.2-0.5.69.315.jar`
  - Updated Sophisticated Core again from `sophisticatedcore-1.18.2-0.5.69.315.jar` to `sophisticatedcore-1.18.2-0.5.70.320.jar` - 6.16.23
- Updated Dimensional Dungeons to `dimdungeons-177-forge-1.18.2.jar` from `dimdungeons-174-forge-1.18.2.jar`.
  - Ultimate Feature Parity Version - 1.18.2, 1.19.2, 1.19.4, and 1.20!
    - Added two new tower rooms.
    - Theme keys now appear in advanced dungeons.
    - New data blocks for custom room builders. ("SummonKeyholder" and "LockWithCode")
- Updated Integrated Dungeons and Structures to `idas_forge-1.6.6+1.18.2.jar` from `idas_forge-1.6.4+1.18.2.jar`
  - Required for Create 0.5.1b compatibility.
- Updated Integrated Stronghold to `integrated_stronghold_forge-1.0.1+1.18.2.jar` from `integrated_stronghold_forge-1.0.2+1.18.2.jar`
  - Required for Create 0.5.1b compatibility. 
- Updated Lootr from `lootr-1.18.2-0.3.24.61.jar` to `lootr-1.18.2-0.3.25.62.jar`
- Updated The Graveyard
  - Fixed /kill not killing nameless hanged

Very sorry that I switched it around over here
- Updated Dark Utilities from `DarkUtilities-Forge-1.18.2-10.1.7.jar` to `DarkUtilities-Forge-1.18.2-10.1.6.jar`
- Updated Grimoire of Gaia from `GrimoireOfGaia4-1.18.2-2.0.0-alpha.37.jar` to `GrimoireOfGaia4-1.18.2-2.0.0-alpha.38.jar`
- Updated Gateways to Eternity from `GatewaysToEternity-1.18.2-2.2.1.jar` to `GatewaysToEternity-1.18.2-2.3.0.jar`
- Updated Mahou Tsukai from `mahoutsukai-1.18.2-v1.34.44.jar` to `mahoutsukai-1.18.2-v1.34.45.jar` to `mahoutsukai-1.18.2-v1.34.46.jar` as of 6/15/2023
- Updated Mob Grinding Utils from `mob_grinding_utils-1.18.2-0.4.49.jar` to `mob_grinding_utils-1.18.2-0.4.50.jar`
- Updated Torchmaster from `torchmaster-18.1.0.jar` to `torchmaster-18.2.0.jar`
- Updated Mystical Agriculture from `MysticalAgriculture-1.18.2-5.1.4.jar` to `MysticalAgriculture-1.18.2-5.1.5.jar`
- Updated Mystical Agradditions from `MysticalAgradditions-1.18.2-5.1.3.jar` to `MysticalAgradditions-1.18.2-5.1.4.jar`
- Updated Occultism from `occultism-1.18.2-1.78.0.jar` to `occultism-1.18.2-1.80.4.jar`
  - Also updated Modomon from `modonomicon-1.18.2-1.30.2.jar` to `modonomicon-1.18.2-1.33.0.jar`

### Library, utility mods and datapack updates
- Updated KubeJS Create to `kubejs-create-forge-1802.2.4-build.5.jar` from `kubejs-create-forge-1802.2.2-build.28.jar`
  - MANDATORY for Create 0.5.1b compatibility.
- Updated Collective to `collective-1.18.2-6.57.jar` from `collective-1.18.2-6.53.jar`
- Updated Cucumber Library to `Cucumber-1.18.2-5.1.4.jar` from `Cucumber-1.18.2-5.1.3.jar`
- Updated Cyclops Core to `CyclopsCore-1.18.2-1.17.5.jar` from `CyclopsCore-1.18.2-1.17.3.jar`
- Updated Puzzles Lib to `PuzzlesLib-v3.4.5-1.18.2-Forge.jar` from `PuzzlesLib-v3.3.6-1.18.2-Forge.jar`
- Updated FTB Teams to `ftb-teams-forge-1802.2.11-build.107.jar` from `ftb-teams-forge-1802.2.10-build.96.jar`
- Updated Open Parties and Claims to `open-parties-and-claims-forge-1.18.2-0.17.5.jar` from `open-parties-and-claims-forge-1.18.2-0.17.3.jar`

---

# Version 0.6.0b (Create 0.5.0i)
Last edited on June 11, 2023.

Unfortunately, we're still stuck on Create 0.5.0i as much as I want to update the modpack to support Create 0.5.1b.

## Finality Core changes
- Added tight Create integration for Tinker's Construct.
- Changed Wither Storm related recipes to use Insanium Essence, not just corruption.
  - This should have been the original recipe.
- 

## Mod removals
- Removed FastSuite, Fast WorkBench and FastFurnace
- Removed Rotten Creatures
  - Log spam and the config file does not even work. Explanation for this issue can be found here: https://github.com/teamfusion/rottencreatures/pull/24
- Removed Hypothermic
  - Log spam
- Removed Stack Refill
  - Might be responsible for causing the item stacking issues with torches.
- Removed OpenLoader
  - KubeJS replaces this mod.
- Removed Lightspeed

## Mod updates
- Updated Jade to `Jade-1.18.2-forge-5.3.0.jar` from `Jade-1.18.2-forge-5.2.6.jar`
- Updated ShetiPhianCore from `shetiphiancore-forge-1.18.2-3.10.14.jar` to `shetiphiancore-forge-1.18.2-3.10.16.jar`
  - Improved error logging in the texture provider override handler (system that processes 'assets/shetiphian/texture_remap.json')
  - Corrected 'texture_remap' entry 'grass_path' to 'dirt_path'
- Updated EnderChests
  - Texture Updates
  - Adjusted owner display to support formatting codes
- Updated EnderTanks
  - Texture Updates
  - Adjusted owner display to support formatting codes
- Updated Terralith from `Terralith_v2.2.3.jar` to `Terralith_1.18.2_v2.2.4.jar`
  - Now requires Cristel Lib, but now has integration with Terrablender by default.

---