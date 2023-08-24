---
layout: minimal
title: 0.1.4 (1.19.2)
parent: Iteration 0.1
grand_parent: Finality Genesis Changelog
nav_order: 5
---

# Genesis 0.1.4

This update replaces JEI with REI and its addon counterparts where applicable. This means:
- Just Enough Resources has been replaced with Roughly Enough Resources
- Just Enough Professions has been replaced with Roughly Enough Professions

However, you will *always* have the choice of reverting back to using JEI.

Updated Forge mod loader `43.2.14` to `43.2.21` 8.20.23

**This update adds mods that affect world generation and add new ores and structures! However, YOU DO NOT have to re-generate your world!**

The main menu does look slightly different due to Essential adding compatibility with FancyMenu. Will change the menu to something more suitable in future updates!

## 8.23.23 Changes
- Updated ESSENTIAL `Essential-forge_1-18-2` to `essential_1-2-2_forge_1-19-2`
- Disabled BetterF3 animations to remove lag caused by it.
- Added Caupona to Carry On blacklist
- Added Some Assembly Required to Carry On blacklist

## 8.22.23 Changes
- Essential has released an update that fixes incompatiblity with FancyMenu. However, the update is a bit limited in how I can customize the menu so it's been reworked a bit.
- Disabled Quark's improved tooltips in config (thanks Squoshi for pointing that out)
- Some content in the Caupona and Iron's Spell Books quest trees, but more thorough questing will be implemented over the next few follow-up updates.

### Mod updates
- Updated Supplementaries `supplementaries-1.19.2-2.3.23` to `supplementaries-1.19.2-2.3.24`
  - This fixes a crash with the present screen and the *overencumbered* effect.
- Updated Xaero's Minimap `Xaeros_Minimap_23.6.2_Forge_1.19.1` to `Xaeros_Minimap_23.6.3_Forge_1.19.1`
- Updated Xaero's World Map `XaerosWorldMap_1.33.0_Forge_1.19.1` to `XaerosWorldMap_1.33.1_Forge_1.19.1`

### Mod additions
- Added Elytra Slot because I forgot to implement it.

## 8.21.23 Changes
Re-implemented Starlight due to chunks loading too slowly, hopefully no chunk lighting issues may result from this.
- Blacklisted Caupona from being picked up with Carry On.

### Mod updates
- Updated Rhino `rhino-forge-1902.2.2-build.268` to `rhino-forge-1902.2.2-build.272`
- Updated Cupboard `cupboard-1.19.2-1.7` to `cupboard-1.19.2-1.8`
- Updated ModernFix by embeddedt, destroyer of launch times `modernfix-forge-5.7.0+mc1.19.2` to `modernfix-forge-5.7.1+mc1.19.2`
- Enabled ModernFix's optimization: mixin.perf.dynamic_resources=true
- Updated SuperMartijn642's Config Lib `supermartijn642configlib-1.1.7-forge-mc1.19` to `supermartijn642configlib-1.1.8-forge-mc1.19`

### Mod additions
- Re-implemented Starlight
- Added Better Chunk Loading
- Added Caupona
- Added Easy Shulker Boxes
- Added Echo Chest
- Added Lil' Wings
- Added Monobank
- Added Neko's Enchanted Books
- Added Not Enough Animations by tr7zw
- Added Overflowing Bars
- Added Sooty Chimneys
- Added The Salt
- Added Universal Bonemeal

## 8.20.23 Changes
- Added Iron's Spells n Spellbooks
- You can now smelt Nether Gold Ore again as it is more profitable than mining.
- REI grouping scripts... can I please stop typing grups?
- Reimplemented JEI config files for those who still want to use JEI.
- Implemented a check if JEI is loaded.

## 8.18.23 Changes
- Added Roughly Enough Items
- Added Roughly Enough Professions
- Added Roughly Enough Resources
- Added Roughly Enough Trades
- Removed Just Enough Items
- Removed Just Enough Resources
- Increased time delay for update checker.
- Updated FTB Quests `ftb-quests-forge-1902.5.3-build.258.jar` to `ftb-quests-forge-1902.5.4-build.275.jar`
- Updated Chunk Loaders `chunkloaders-1.2.6-forge-mc1.19` to `chunkloaders-1.2.7-forge-mc1.19`
- Updated Cupboard `1.19.2-1.6` to `1.19.2-1.7`
- Updated FTB XMod Compat `ftb-xmod-compat-forge-1.2.1` to `ftb-xmod-compat-forge-1.2.2` to fix JEI / REI crashing with FTB Quests
- Updated ModernFix by embeddedt, destroyer of launch times `modernfix-forge-5.6.1+mc1.19.2` to `modernfix-forge-5.7.0+mc1.19.2`

### Mod updates
- KubeJS `kubejs-forge-1902.6.1-build.362.jar` to `kubejs-forge-1902.6.1-build.364.jar`
- KubeJS Create `kubejs-create-forge-1902.2.4-build.27.jar` to `kubejs-create-forge-1902.2.4-build.29.jar`
- NetJS `1.1.0` to `1.1.1`
- LootJS `1.19.2-2.9.0` to `1.19.2-2.9.1`
- Create Enchantment Industry `0.5.1c-1.2.6` to `0.5.1c-1.2.6b`
- ModernFix `modernfix-forge-5.6.0+mc1.19.2.jar` to `modernfix-forge-5.6.1+mc1.19.2.jar`
- Supplementaries `supplementaries-1.19.2-2.3.20.jar` to `supplementaries-1.19.2-2.3.22.jar`
- Supplementaries updated again `1.19.2-2.3.22` to `1.19.2-2.3.23`
- Xaeros Minimap `23.6.1_Forge_1.19.1` to `23.6.2_Forge_1.19.1`