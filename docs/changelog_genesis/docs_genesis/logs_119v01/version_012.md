---
layout: default
title: Finality Genesis Version 0.1.2b (1.19.2)
parent: Iteration 0.1
grand_parent: Finality Genesis Changelog
nav_order: 7
---
# Version 0.1.2 (KubeJS Create 0.5.1)
KubeJS Create has been updated to support Create 0.5.1.

Please delete the `scripts` folder in your instance that contains all of the `.zs` files as they are no longer necessary.

## Mod additions
- Forgot to add Torchmaster, so it's back in.

## Mod updates
- Re-added KubeJS Create for 0.5.1 compatibility, ensure that `kubejs-create-forge-1902.2.4-build.5.jar` or higher is installed.
- Updated KubeJS Create from `kubejs-create-forge-1902.2.4-build.5.jar` to `kubejs-create-forge-1902.2.4-build.9.jar`
- Updated Drippy Loading Screen from `drippyloadingscreen_forge_2.2.1_MC_1.19.1-1.19.2.jar` to `drippyloadingscreen_forge_2.2.2_MC_1.19.1-1.19.2.jar` so you no longer have to worry about the ever growing `.txt` file in the config folder. Good thing I contacted Keksuccino about this XD
  - Fixed: Drippy keeps adding new entries to the `config/fancymenu/customizablemenus.txt` file on every game launch
- Create Enchantment Industry from `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.4.b.jar` to `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.4.c.jar`
- EnderChests from `enderchests-forge-1.19.0-1.10.1.01.jar` to `enderchests-forge-1.19.0-1.10.1.02.jar`
- EnderTanks from `endertanks-forge-1.19.0-1.12.1.02.jar` to `endertanks-forge-1.19.0-1.12.1.03.jar`
- FastWorkbench from `FastWorkbench-1.19.2-7.1.2.jar` to `FastWorkbench-1.19.2-7.1.3.jar`
- Quark from `Quark-3.4-402.jar` to `Quark-3.4-404.jar`
- Updated Quark again from `Quark-3.4-404.jar` to `Quark-3.4-405.jar`
- Updated Tempad from `tempad-forge-1.19.2-1.4.4.jar` to `tempad-forge-1.19.2-1.4.5.jar`
  - Fixed mod incompatibility
- Mog Grinding Utils from `mob_grinding_utils-1.19.2-0.4.49.jar` to `mob_grinding_utils-1.19.2-0.4.50.jar`
  - Fixed interaction with Torchmaster.
- Lootr (Forge) from `lootr-1.19-0.4.23.60.jar` to `lootr-1.19-0.4.24.61.jar`
- Mystical Agriculture from `MysticalAgriculture-1.19.2-6.0.8.jar` to `MysticalAgriculture-1.19.2-6.0.9.jar`
- Mystical Agradditions from `MysticalAgradditions-1.19.2-6.0.2.jar` to `MysticalAgradditions-1.19.2-6.0.3.jar`
- Open Parties and Claims from `open-parties-and-claims-forge-1.19.2-0.17.3.jar` to `open-parties-and-claims-forge-1.19.2-0.17.5.jar`


## Lib updates
- Collective from `collective-1.19.2-6.53.jar` to `collective-1.19.2-6.57.jar`
- Cucumber Library from `Cucumber-1.19.2-6.0.6.jar` to `Cucumber-1.19.2-6.0.7.jar`
- ShetiPhianCore from `shetiphiancore-forge-1.19.0-3.11.3.02.jar` to `shetiphiancore-forge-1.19.0-3.11.3.03.jar`
- Moonlight Lib from `moonlight-1.19.2-2.2.37-forge.jar` to `moonlight-1.19.2-2.2.38-forge.jar`

## Mod removals
Please delete the `scripts` folder in your instance that contains all of the `.zs` files as they are no longer necessary. I never want to see that ZenScript again.
- CraftTweaker
- CreateTweaker

# Version 0.1.2 (CraftTweaker)
This was while CraftTweaker was still present on June 10, 2023. 

This update is currently in development and will be published soon.

CraftTweaker will be staying until KubeJS Create is updated, I am not going to use JSON syntax for Sequenced Assembly.

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

## Mod additions
- Added Backpacked by MrCrayFish
- Added Create Enchantment Industries, it is now compatible with Create 0.5.1.

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
- Updated `Moonlight Lib` for the 3rd time to `moonlight-1.19.2-2.2.37-forge.jar`. Forgot to paste developer changelog, but it was among the lines of "please no more bugs, i dont want to touch this version again"
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



