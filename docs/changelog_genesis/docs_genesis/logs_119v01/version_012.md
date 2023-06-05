---
layout: default
title: Finality Genesis Version G1192.0.1.2b (1.19.2)
parent: Finality Genesis Changelog
grand_parent: Finality Genesis Changelog
nav_order: 7
---

# Version 0.1.2

This update is currently in development and will be published soon.

## Mod update teasers - Cataclysm, by L_Ender
Lately L_Ender has been releasing very cool teasers. I can't be more excited! 

Here are some links to the videos:

https://www.youtube.com/watch?v=V1mfYF085qA&ab_channel=%EC%97%94%EB%93%9C

https://www.youtube.com/watch?v=Jpbt3ZCOZ-U&ab_channel=%EC%97%94%EB%93%9C


## Documentation
- Updated FTB Quests in the Create chapter for the water wheel and large water wheel entries.
- Updated Tome of Finality, it's going to be a bit difficult managing three different variations of the Patchouli guide book, but I can manage.
  - Thermal is not present, so Thermal related materials like lead and silver are missing, due to this some entries did not display properly.
  - Updated entry for getting energy to use Create Stuff & Additions accumulator instead.
- Updated the Changelog button on the Main Menu to use the new wiki which is the one that you are on, right now.

## Finality Core changes
- Added placeholder items, I am planning to make a custom set of armor and tools to replace creativerite.
- Added singularity cores which are now required to make singularities.
- Morph-o-Tool can now accept the following tool types. Be careful while using it.
  - Pickaxe
  - Axe
  - Hoe
  - Shovel
  - Shears
- Removed the duplicate End Crystal recipe from CraftTweaker
- Removed the duplicate Beacon recipe from CraftTweaker
- Changed modpack versioning back to x.x.x instead of 19.x.x.x for `Better Compatibility Checker`

## Mod removals
- Removed DefaultOptions
  - KubeJS will handle this.
- Removed OpenLoader
  - Put simply, I was using it incorrectly...

## Mod updates

- Updated `Integrated Dungeons and Structures` to `idas_forge-1.7.4+1.19.2.jar` from `idas_forge-1.7.3+1.19.2.jar` to fix compatibility with Create 0.5.1. Thank you CraisinLord!
- Updated `Integrated Stronghold` to `integrated_stronghold_forge-1.0.2+1.19.2.jar` from `integrated_stronghold_forge-1.0.1+1.19.2.jar` to fix compatibility with Create 0.5.1.
- Updated the datapacks for both `Integrated Dungeons and Structures` and `Integrated Stronghold`
- Updated Create Cafe from `createcafe-1.1.7-1.19.2.jar` to `createcafe-1.1.8-1.19.2.jar`
  - Fixed mixing recipe for Lychee Tea
  - Fixed giving empty cup after drinking not functioning correctly
  - Added Coffee Beans and Cassava Seeds to #forge:seeds tag
  - Added Coffee Fruit and Cassava Root to #forge:crops tag
  - Fixed Avocado Milk Tea mixing recipe not functioning correctly
- Updated `Supplementaries` to `supplementaries-1.19.2-2.3.14a.jar` from `supplementaries-1.19.2-2.3.16.jar`. Developer changelog is below.
  - fixed recent server crash
- Updated `Moonlight Lib` to `moonlight-1.19.2-2.2.36-forge.jar` from `moonlight-1.19.2-2.2.34-forge.jar`. Developer changelog is below.
  - no more bugs pls
- Updated `Moonlight Lib` to `moonlight-1.19.2-2.2.37-forge.jar` from `moonlight-1.19.2-2.2.36-forge.jar` 
  - improved wood detections. blacklisted some mods
- Updated `Citadel` to `citadel-2.1.4-1.19.jar` from `citadel-2.1.3-1.19.jar`
  - Fixed issue with Terrablender with memory usage on relog causing worlds to be unplayable. This fix is for new worlds only; old worlds should have their level.dat reset using a NBTExplorer program.
- Updated SehtiPhianCore from `shetiphiancore-forge-1.19.0-3.11.3.01.jar` to `shetiphiancore-forge-1.19.0-3.11.3.02.jar`. Developer changelog is below
  - Make the log stripping lookup code more fault-tolerant, and fall back to reading default method on fail
  - Added texture remap system to override the texture used by retextured blocks (MultiBeds, Platforms) (see )
    - allows corrections when the particle texture is not the desired texture for a block
    - resource packs that uses a common particle (eg. alacrity) just need to add the file (assets/shetiphian/texture_remap.json) line entries are formatted ("BlockID": "Texture") (eg: "minecraft:grass_block": "block/grass_block_top")
    - the default file corrects the few Minecraft blocks that I knew of (grass types, pistons, etc.)
- Several Fixes to Teams
- Updated `Xaero's Minimap` to `Xaeros_Minimap_23.4.4_Forge_1.19.1.jar` from `Xaeros_Minimap_23.4.3_Forge_1.19.1.jar` see [changelog here](https://chocolateminecraft.com/update.php?mod_id=0)
- Updated `Architectury` to `architectury-6.5.85-forge.jar`
- Updated `Bookshelf` to `Bookshelf-Forge-1.19.2-16.3.20.jar` from `Bookshelf-Forge-1.19.2-16.2.18.jar`

# Mod additions


