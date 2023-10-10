---
layout: minimal
title: Finality Tau 0.4.0b
nav_order: 1
parent: Tau Iteration 0.4
grand_parent: Finality Tau Changelog
---
# Finality Tau 0.4.0b Changelog

Game Breaking
{: .label .label-red }

In Development
{: .label .label-yellow }

Do not update `Flat Colored Blocks - For Forge` as the newest version still breaks server joining. Edit: The mod has since been removed in versions after 0.3.9.2b.
{: .warning }

{: .highlight }
All files have been scanned for Fractureiser malware before exporting. None of the files have it present as of 6.19.23

Updated to `Forge 43.2.14` from `Forge 43.2.11`.

## 0.4.0 release

8.9.23

### Mod updates
- 

### Mod additions
- 

## 04b5 Update Release
7.29.32

Due to the removal of Weeping Angels, you may find missing blocks from the mod in your world. A world regeneration is not required as it does not add much.
Variant Crafting Tables has also been removed.

- Enigmatic Legacy's Enigmatic Vessel should now only be able to be picked up only by the owner.
- Reconfigured the Ender Dragon fight to respawn end crystals less frequently.
- Added Blue Skies compat for the Handheld Crafting Table.

### Mod updates
- Updated Cave Dweller Evolved `cave_dweller-1.19.2-1.4.0.jar` to `cave_dweller-1.19.2-1.5.1.jar`
- Updated Clickable advancements `clickadv-1.19.2-3.0.jar` to `clickadv-1.19.2-3.1.jar`
- Updated Crafting Tweaks `craftingtweaks-forge-1.19.2-15.1.7.jar` to `craftingtweaks-forge-1.19.2-15.1.8.jar`
- Updated Create Central Kitchen `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.8.b.jar` to `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.8.b.jar`
- Updated FTB Quests `ftb-quests-forge-1902.5.1-build.250.jar` to `ftb-quests-forge-1902.5.3-build.258.jar`
- Updated Fusion (Connected Textures) `fusion-1.0.3-forge-mc1.19.2.jar` to `fusion-1.0.5-forge-mc1.19.2.jar`
- Updated KubeJS `kubejs-forge-1902.6.1-build.327.jar` to `kubejs-forge-1902.6.1-build.337.jar`
- Updated Cataclysm `L_Enders_Cataclysm-1.23-1.19.2.jar` to `L_Enders_Cataclysm-1.26-1.19.2.jar`
- Updated Lootr `lootr-1.19-0.4.24.62.jar` to `lootr-1.19-0.4.24.64.jar`
- Updated ModernFix `modernfix-forge-5.3.2+mc1.19.2.jar` to `modernfix-forge-5.4.1+mc1.19.2.jar`
- Updated Savage Ender Dragon `dragonfight-1.19.2-2.6.jar` to `dragonfight-1.19.2-4.0.jar`
- Updated Sophisticated Core `sophisticatedcore-1.19.2-0.5.81.377.jar` to `sophisticatedcore-1.19.2-0.5.83.394.jar`
- Updated Sophisticated Storage `sophisticatedstorage-1.19.2-0.8.38.555.jar` to `sophisticatedstorage-1.19.2-0.8.39.573.jar`
- Updated Torchmaster `torchmaster-19.2.91.jar` to `torchmaster-19.2.93.jar`
- Updated Xaero's Minimap `Xaeros_Minimap_23.5.0_Forge_1.19.1.jar` to `Xaeros_Minimap_23.6.0_Forge_1.19.1.jar`
- Updated Xaero's World Map `XaerosWorldMap_1.30.6_Forge_1.19.1.jar` to `XaerosWorldMap_1.31.0_Forge_1.19.1.jar`

### Mod additions
- Re-added Create Deco
- Re-added Create Chunkloading
- Added Create Mechanical Extruder
- Added Grimoire of Gaia

### Mod removals
- Removed the Weeping Angels mod due to significant performance impact in both singleplayer and multiplayer sessions. Developer will be backporting the fix soon, hopefully.
- Removed Variant Crafting Tables

## 04a5 Update Release
7.25.23

- Added Cave Dweller Evolved
  - This was the missing piece.
- Actually remembered to fix the quest for sandpaper to accept *any* sandpaper.

## 04a4 Alpha Update Release

### 7.24.23
- Downgraded Forge to 43.2.14 instead of 43.2.17.
- Updated Let's Do Beachparty from `letsdo-beachparty-forge-1.0.9.jar` to `letsdo-beachparty-forge-1.0.11.jar`
- Updated Create Central Kitchen `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.8.jar` to `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.8.b.jar`
- Updated FTB Library `ftb-library-forge-1902.4.0-build.232.jar` to `ftb-library-forge-1902.4.1-build.236.jar`
- Updated Cataclysm `L_Enders_Cataclysm-1.21-1.19.2.jar` to `L_Enders_Cataclysm-1.23-1.19.2.jar`
- Updated Rechiseled `rechiseled-1.1.1-forge-mc1.19.2.jar` to `rechiseled-1.1.2-forge-mc1.19.2.jar`
- Updated SuperMartijn's Core Lib `supermartijn642corelib-1.1.11-forge-mc1.19.2.jar` to `supermartijn642corelib-1.1.12-forge-mc1.19.2.jar`
- Updated Torchmaster `torchmaster-19.2.90.jar` to `torchmaster-19.2.91.jar`
- Added MemoryLeakFix.

### 7.22.23
IRL issues are happening, please bear with me.

#### Recipe changes
The following will apply to all versions of Finality.
- Mechanical Crafter singularities will now use the correct Awakened Singularity core at the center.
- Reworked Create renewal recipes for coal and diamonds.
  - What does this mean? It means 1 coal block will give you 1 diamond instead of 9 coal blocks giving you only 1 block. So it's now a 1:1 ratio.
  - Also, 9 coal blocks will now give you 1 diamond block.

#### Mod updates 
- Updated KubeJS from `kubejs-forge-1902.6.1-build.311.jar` to `kubejs-forge-1902.6.1-build.324.jar`
  - Updated to `kubejs-forge-1902.6.1-build.327.jar`
- Updated KubeJS Create from `kubejs-create-forge-1902.2.4-build.20.jar` to `kubejs-create-forge-1902.2.4-build.23.jar`
- Updated KubeJS Thermal from `kubejs-thermal-1902.1.9-build.9.jar` to `kubejs-thermal-1902.1.9-build.11.jar`
- Updated Apotheosis from `Apotheosis-1.19.2-6.3.0.jar` to `Apotheosis-1.19.2-6.3.1.jar`
- Updated Cataclysm from `L_Enders_Cataclysm-1.20-1.19.2.jar` to `L_Enders_Cataclysm-1.21-1.19.2.jar`
- Updated Create Enchantment Industry from `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.5.jar` to `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.5.b.jar`
- Updated FancyMenu from `fancymenu_forge_2.14.7_MC_1.19-1.19.2.jar` to `fancymenu_forge_2.14.9_MC_1.19-1.19.2.jar`
- Updated ModernFix from `modernfix-forge-5.3.1+mc1.19.2.jar` to `modernfix-forge-5.3.2+mc1.19.2.jar`
- Updated Open Parties & Claims from `open-parties-and-claims-forge-1.19.2-0.19.0.jar` to `open-parties-and-claims-forge-1.19.2-0.19.1.jar`
- Updated Terralith from `Terralith_1.19.3_v2.3.8.jar` to `Terralith_1.19.3_v2.3.9.jar`
- Updated YUNG's Better Nether Fortresses from `YungsBetterNetherFortresses-1.19.2-Forge-1.0.5.jar` to `YungsBetterNetherFortresses-1.19.2-Forge-1.0.6.jar`

#### Mod additions
- Added NetherPortalFix

#### Mod removals
- Removed Darker Depths

### 7.20.23 Changelog
- Updated KubeJS from `kubejs-forge-1902.6.1-build.300.jar` to `kubejs-forge-1902.6.1-build.311.jar`
- Updated KubeJS Create from `kubejs-create-forge-1902.2.4-build.16.jar` to `kubejs-create-forge-1902.2.4-build.20.jar`
- Updated FTB Quests from `ftb-quests-forge-1902.4.18-build.244.jar` to `ftb-quests-forge-1902.5.1-build.250.jar`
- Updated Cataclysm from `L_Enders_Cataclysm-1.19-1.19.2.jar` to `L_Enders_Cataclysm-1.20-1.19.2.jar`
- Updated Lucky's Spelunker's Charm from `SpelunkersCharm-3.2.0-1.19.2.jar` to `SpelunkersCharm-3.2.1-1.19.2.jar`
- Updated ModernFix from `modernfix-forge-5.2.5+mc1.19.2.jar` to `modernfix-forge-5.3.1+mc1.19.2.jar`
- Updated SuperMartijn642's Core Lib from `supermartijn642corelib-1.1.10-forge-mc1.19.2.jar` to `supermartijn642corelib-1.1.11-forge-mc1.19.2.jar`

### 7.18.23 Changelog

- KubeJS has been updated to 6.1.
  - `kubejs-forge-1902.6.0-build.142.jar` to `kubejs-forge-1902.6.1-build.300.jar`
- KubeJS Create has been updated to support KJS 6.1. Updated a second time after item quantities for both Mixing and Compacting have been fixed by Max yaaay
  - `kubejs-create-forge-1902.2.4-build.9.jar` to `kubejs-create-forge-1902.2.4-build.16.jar`
  - `kubejs-create-forge-1902.2.4-build.16.jar` to `kubejs-create-forge-1902.2.4-build.18.jar`
- KubeJS Thermal has been updated to support KJS 6.1.
  - `kubejs-thermal-1902.1.6-build.22.jar` to `kubejs-thermal-1902.1.9-build.9.jar`
- Cataclysm updated from `L_Enders_Cataclysm-1.18-1.19.2.jar` to `L_Enders_Cataclysm-1.19-1.19.2.jar`

### 7.17.23 Changelog

- Added additional descriptions to Create related quests.
- Fixed structure detection to detect YUNG's Better Nether Fortress instead of the vanilla Nether Fortress.
- Moved Jade to the top left corner to provide unobstructed viewing of Cataclysm's boss health bars.
- Enigmatic Legacy's Amulet Vessel now can only be claimed by the original owner.
- Reduced Tempad's cooldown to 30 seconds.
- Added Nicer Rain by Lat
- Tridents are now craftable.

Exclusive to Tau
- Added Herobrine.

Added the following mods:
- Added Realistic Torches
- Added Lucky's Spelunker's Charm II
  - Unfortunately Lucent appears to be a required dependency, so Flywheel's optimizations may be disabled.
  - This mod has returned and I was looking forward to including it in this modpack.
- Re-added Eyes in the Darkness as sounds have been changed.
  - You will need to update your server configs manually, however.

Updated the following mods: 
- Updated Let's Do Candlelight from `letsdo-candlelight-forge-1.1.5.jar` to `letsdo-candlelight-forge-1.1.6.jar`
- Updated Let's Do Vinery from `letsdo-vinery-forge-1.3.6.jar` to `letsdo-vinery-forge-1.3.7.jar`
- Updated Apotheosis from `Apotheosis-1.19.2-6.2.1.jar` to `Apotheosis-1.19.2-6.3.0.jar`
- Updated Ars Nouveau from `ars_nouveau-1.19.2-3.17.8.jar` to `ars_nouveau-1.19.2-3.17.9.jar`
- Updated Chat Heads from `chat_heads-0.10.16-forge-1.19.2.jar` to `chat_heads-0.10.18-forge-1.19.2.jar`
- Updated FTB Library from `ftb-library-forge-1902.3.19-build.214.jar` to `ftb-library-forge-1902.4.0-build.232.jar`
- Updated L_Ender's Cataclysm from `L_Enders_Cataclysm-1.16-1.19.2.jar` to `L_Enders_Cataclysm-1.18-1.19.2.jar`
- Updated ModernFix from `modernfix-forge-5.2.3+mc1.19.2.jar` to `modernfix-forge-5.2.5+mc1.19.2.jar`
- Updated Placebo from `Placebo-1.19.2-7.3.0.jar` to `Placebo-1.19.2-7.3.1.jar`
- Updated Raised from `raised-forge-1.19.2-1.2.3.jar` to `raised-forge-1.19.2-2.0.0.jar`
- Updated Some Assembly Required from `some-assembly-required-1.19.2-3.0.2.jar` to `some-assembly-required-1.19.2-3.0.3.jar`
- Updated Sophisticated Core from `sophisticatedcore-1.19.2-0.5.78.363.jar` to `sophisticatedcore-1.19.2-0.5.81.377.jar`

I have isolated the cause for the flooding of errors in the server console log to a certain mod.
- Removed Deeper and Darker.
  - They have stated that they will fix patch this, but the fix is not yet available.

- Removed Rotten Creatures
  - Waiting on fix from developers regarding config files.
- Removed Dynamic Asset Generator
- Removed BetterF3
- Removed Inventory HUD+
- Removed BotanyPots
- Removed Botany Trees
- Removed Create Slice & Dice
- Removed Kotlin for Forge

# 7.13.2023 Changelog

## 04a3 Alpha Update Release
- ~~Changed config for Eyes in the Darkness to limit spawn rate~~
  - Ended up just removing the mod entirely.
- Added the logs that burn tag to Palm Logs from Beach Party to be able to be converted into charcoal.
- Removed EMC values from singularities.

## 04a2 Alpha Update Release
- Fixed recipes for Extended Crafting using invalid transitional items.
- Removed Item Pickup because it's been replaced by Obscuria's Loot Journal
- Restored recipe for Handheld Crafting Table

## 04a1 Alpha Update Release
Changed version to 04a1 for an in progress update.

Updated to Forge `43.2.17` from `Forge 43.2.14`.

Changed the cooldown for Cataclysm's weapons:
- BulwarkOfTheFlameCooldown = 45
- GauntletOfBulwarkCooldown = 45
- InfernalForgeCooldown = 30
- VoidForgeCooldown = 30
- TheIncineratorCooldown = 60
- WASWMissileCooldown = 40
- WASWHowitzerCooldown = 100
- VASWCooldown = 30
- VoidCoreCooldown = 45

- Added DefaultOptions to fix KubeJS keybind boogaloo.
- Added Yeetus Experimentus to actually remove Experimental Settings warning on world generation to replace Shut Up Experimental Settings.

- Removed Create Stuff & Additions (NOT Create Crafts & Additions)
- Removed Create Confectionery
- Removed Ender's Delight, replaced with End's Delight
- Removed Enlightend
- Removed Phantasmic

- Updated the Let's Do mods.
  - Candlelight from `letsdo-candlelight-forge-1.1.4.jar` to `letsdo-candlelight-forge-1.1.5.jar`
  - Vinery from `letsdo-vinery-forge-1.3.4.jar` to `letsdo-vinery-forge-1.3.6.jar`
- Updated Ars Nouveau from `ars_nouveau-1.19.2-3.17.6.jar` to `ars_nouveau-1.19.2-3.17.8.jar`
- Updated Artifacts from `artifacts-1.19.2-5.0.2.jar` to `artifacts-1.19.2-5.0.3.jar`
- Updated AttributeFix from `AttributeFix-Forge-1.19.2-17.2.6.jar` to `AttributeFix-Forge-1.19.2-17.2.7.jar`
- Updated Cloth Config from `cloth-config-8.2.88-forge.jar` to `cloth-config-8.3.103-forge.jar`
- Updated Collective from `collective-1.19.2-6.62.jar` to `collective-1.19.2-6.65.jar`
- Updated Extended Crafting from `ExtendedCrafting-1.19.2-5.1.6.jar` to `ExtendedCrafting-1.19.2-5.1.7.jar`
- Updated Farmer's Delight from `FarmersDelight-1.19-1.2.1.jar` to `FarmersDelight-1.19.2-1.2.2.jar`
- Updated Integrated Dungeons and Structures from `idas_forge-1.7.4+1.19.2.jar` to `idas_forge-1.7.6+1.19.2.jar`
- Updated L_Ender's Cataclysm from `L_Enders_Cataclysm-0.84-1.19.2.jar` to `L_Enders_Cataclysm-1.16-1.19.2.jar`
- Updated Mahou Tsukai from `mahoutsukai-1.19.2-v1.34.51.jar` to `mahoutsukai-1.19.2-v1.34.52.jar`
- Updated ModernFix from `modernfix-forge-5.1.0+mc1.19.2.jar` to `modernfix-forge-5.2.3+mc1.19.2.jar`
- Updated Mystical Agriculture from `MysticalAgriculture-1.19.2-6.0.10.jar` to `MysticalAgriculture-1.19.2-6.0.11.jar`
- Updated Raised from `raised-forge-1.19.2-1.2.2.jar` to `raised-forge-1.19.2-1.2.3.jar`
- Updated Sophisticated Backpacks from `sophisticatedbackpacks-1.19.2-3.18.53.868.jar` to `sophisticatedbackpacks-1.19.2-3.18.55.889.jar`
- Updated Sophisticated Core from `sophisticatedcore-1.19.2-0.5.77.346.jar` to `sophisticatedcore-1.19.2-0.5.78.363.jar`
- Updated Sophisticated Storage from `sophisticatedstorage-1.19.2-0.8.32.510.jar` to `sophisticatedstorage-1.19.2-0.8.38.555.jar`
- Updated Waystones from `waystones-forge-1.19.2-11.4.0.jar` to `waystones-forge-1.19.2-11.4.1.jar`


# 7.12.2023 Changelog

- Added ModernFix. Thank you for deleting the load time.
- Added LazyDFU
  - This should have been in the modpack from the start but looks like I forgot...
- Added Loot Journal

# 7.7.2023 Changelog
It's been a while. Let's see the amount of mods that need updating... Fortunately I have spoken to the developer of Let's Do Beach Party and the "This block has functions that are not fully implemented. Stay Tuned!" message no longer appears on /reload.

- Create has been updated to `0.5.1c`. Make sure to remove Flywheel 0.6.8a locally in your mods folder if CurseForge fails to automatically remove it for some reason.
- Just Enough Items (JEI) has been updated from `jei-1.19.2-forge-11.6.0.1015.jar` to `jei-1.19.2-forge-11.6.0.1016.jar`
- Ported fixed Mystical Agriculture recipes and quests from Finality Mote.

## Mod additions
- Added EnhancedVisuals

## Mod updates
I am shuddering at the amount of mod updates... There's a total of 41 mod updates. 
Some important things to mention: 
**Flat Colored Blocks has been removed.**
**Ad Astra has been removed and will remain on Finality Genesis.**
**Added ModernFix**

For all of the Let's Do mods...
- Added Let's Do API `letsdo-api-forge-1.1.0.jar`
- Updated Let's Do Beachparty from `beachparty-1.0.7.jar` to `letsdo-beachparty-forge-1.0.9.jar`
- Updated Let's Do Candlelight from `candlelight-forge-1.1.0.jar` to `letsdo-candlelight-forge-1.1.4.jar`
- Updated Let's Do Vinery from `vinery-forge-1.3.1.jar` to `letsdo-vinery-forge-1.3.4.jar`

Create addons:
- Updated Create Cafe from `createcafe-1.1.8-1.19.2.jar` to `createcafe-1.2.1-1.19.2.jar`
- Updated Create Central Kitchen from `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.7.c.jar` to `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.8.jar`
- Updated Create Crafts & Additions from `createaddition-1.19.2-20230527a.jar` to `createaddition-1.19.2-20230623a.jar`
- Updated Create Enchantment Industry from `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.4.c.jar` to `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.5.jar`

Everything else:
- Updated Ars Nouveau from `ars_nouveau-1.19.2-3.16.1.jar` to `ars_nouveau-1.19.2-3.17.6.jar`
- Updated Carry On from `carryon-forge-1.19.2-2.0.5.16.jar` to `carryon-forge-1.19.2-2.0.5.17.jar`
- Updated Chat Heads from `chat_heads-0.10.14-forge-1.19.2.jar` to `chat_heads-0.10.16-forge-1.19.2.jar`
- Updated Chunk Loaders from `chunkloaders-1.2.3-forge-mc1.19.jar` to `chunkloaders-1.2.5-forge-mc1.19.jar`
- Updated Collective from `collective-1.19.2-6.57.jar` to `collective-1.19.2-6.62.jar`
- Updated Connected Glass from `connectedglass-1.1.6-forge-mc1.19.jar` to `connectedglass-1.1.7-forge-mc1.19.jar`
- Updated Connectivity from `connectivity-1.19.2-4.2.jar` to `connectivity-1.19.2-4.4.jar`
- Updated Dimensional Dungeons from `dimdungeons-177-forge-1.19.0.jar` to `dimdungeons-178-forge-1.19.0.jar`
- Updated EnderChests from `enderchests-forge-1.19.0-1.10.1.02.jar` to `enderchests-forge-1.19.0-1.10.1.03.jar`
- Updated EnderTanks from `endertanks-forge-1.19.0-1.12.1.03.jar` to `endertanks-forge-1.19.0-1.12.1.04.jar`
- Updated Enhanced Celestials from `Enhanced_Celestials-forge-1.19.2-2.1.0.5.jar` to `Enhanced_Celestials-forge-1.19.2-2.1.0.6.jar`
- Updated Extended Crafting from `ExtendedCrafting-1.19.2-5.1.5.jar` to `ExtendedCrafting-1.19.2-5.1.6.jar`
- Updated FTB Quests from `ftb-quests-forge-1902.4.16-build.235.jar` to `ftb-quests-forge-1902.4.18-build.244.jar`
- Updated FTB Teams from `ftb-teams-forge-1902.2.13-build.100.jar` to `ftb-teams-forge-1902.2.14-build.123.jar`
- Updated Lootr from `lootr-1.19-0.4.24.61.jar` to `lootr-1.19-0.4.24.62.jar`
- Updated Mahou Tsukai from `mahoutsukai-1.19.2-v1.34.46.jar` to `mahoutsukai-1.19.2-v1.34.51.jar`
- Updated Moonlight Lib from `moonlight-1.19.2-2.2.38-forge.jar` to `moonlight-1.19.2-2.2.43-forge.jar`
- Updated Open Parties and Claims from `open-parties-and-claims-forge-1.19.2-0.17.5.jar` to `open-parties-and-claims-forge-1.19.2-0.19.0.jar`
- Updated Placebo from `Placebo-1.19.2-7.2.0.jar` to `Placebo-1.19.2-7.3.0.jar`
- Updated Polymorph from `polymorph-forge-0.46.1+1.19.2.jar` to `polymorph-forge-0.46.4+1.19.2.jar`
- Updated Puzzles Lib from `PuzzlesLib-v4.4.2-1.19.2-Forge.jar` to `PuzzlesLib-v4.4.3-1.19.2-Forge.jar`
- Updated Re-chiseled from `rechiseled-1.0.13-forge-mc1.19.jar` to `rechiseled-1.1.1-forge-mc1.19.2.jar`
- Updated ShetiPhianCore from `shetiphiancore-forge-1.19.0-3.11.3.03.jar` to `shetiphiancore-forge-1.19.0-3.11.3.04.jar`
- Updated Sophisticated Backpacks from `sophisticatedbackpacks-1.19.2-3.18.50.849.jar` to `sophisticatedbackpacks-1.19.2-3.18.53.868.jar`
- Updated Sophisticated Core from `sophisticatedcore-1.19.2-0.5.71.319.jar` to `sophisticatedcore-1.19.2-0.5.77.346.jar`
- Updated Sophisticated Sophisticated Storage from `sophisticatedstorage-1.19.2-0.8.28.453.jar` to `sophisticatedstorage-1.19.2-0.8.32.510.jar`
- Updated SuperMartijn642's Config Lib from `supermartijn642configlib-1.1.6b-forge-mc1.19.jar` to `supermartijn642configlib-1.1.7-forge-mc1.19.jar`
- Updated SuperMartijn642's Core Lib from `supermartijn642corelib-1.1.9a-forge-mc1.19.2.jar` to `supermartijn642corelib-1.1.10-forge-mc1.19.2.jar`
- Updated Supplementaries from `supplementaries-1.19.2-2.3.17.jar` to `supplementaries-1.19.2-2.3.20.jar`
- Updated Xaero's Minimap from `Xaeros_Minimap_23.4.4_Forge_1.19.1.jar` to `Xaeros_Minimap_23.5.0_Forge_1.19.1.jar`
- Updated Xaero's World Map from `XaerosWorldMap_1.30.3_Forge_1.19.1.jar` to `XaerosWorldMap_1.30.6_Forge_1.19.1.jar`

Removed mods: 
- Removed Ad Astra and Botarium.
- Removed Flat Colored Blocks until it is fixed by the developer.
---

# 6.14.2023 Changelog

Currently there is a mod that keeps saying "This block has functions that are not fully implemented. Stay Tuned!" and I don't know which mod it is. The good thing is that this message only appears on reload or world join then disappears shortly afterward.

- Essential should now zoom in smoothly by default.
- Fixed ProjectE's Philosopher's Stone being uncraftable with NULL singularities.
- Fixed Quark configs which nerfs were all enabled by default for whatever reason.
  - Iron Golem's should still drop iron ingots.
  - Mending has been restored to full functionality.
- Some other Quark tweaks:
  - Disabled Quark's Backpack
  - Disabed Totem of Holding as it is now overriding Enigmatic Legacy's Enigmatic Charm
  - Disabled Matrix Enchanting
  - Disabled Pipes
- Fixed Cataclysm config. The times below are in seconds.
  - Bulwark of the Flame Cooldown: 60
  - Gauntlet of Bulwark: 60
  - Infernal Forge: 30
  - The Incinerator: 60
  - VASW Cooldown: 60
  - Void Core Cooldown: 60
  - Void Forge Cooldown: 60
  - WASW Howitzer Cooldown: 60
  - WASW Missile Cooldown: 30
- Added changes to Savage Ender Dragon fight
  - You'll need some protection, maybe.

## Updated mods
- Updated Create from `0.5.0i` to `0.5.1b`.
  - If you have been heavily using water wheels, you may need to make some large water wheels :3
- Updated Drippy Loading Screen from `drippyloadingscreen_forge_2.2.1_MC_1.19.1-1.19.2.jar` to `drippyloadingscreen_forge_2.2.2_MC_1.19.1-1.19.2.jar` so you no longer have to worry about the ever growing `.txt` file in the config folder. Good thing I contacted Keksuccino about this XD
  - Fixed: Drippy keeps adding new entries to the `config/fancymenu/customizablemenus.txt` file on every game launch
- Updated Quark from `Quark-3.4-400.jar` to `Quark-3.4-404.jar`
  - Fixes quirkiness with Create's new Netherite Backtank not functioning as intended. Please check the developer's changelog notes.
- Updated Quark from `Quark-3.4-404.jar` to `Quark-3.4-405.jar`
  - Added config options to change which tool types pickarangs can have
  - Echorangs can now break sculk blocks (normal pickarangs still can't)
  - Fixed broken simple harvesting
  - Pickarangs now also have the hoe tool type
- Updated Create Crafts & Additions from `createaddition-1.19.2-20230507a.jar` to `createaddition-1.19.2-20230527a.jar`
- Updated Create Cafe from `createcafe-1.1.6-1.19.2.jar` to `createcafe-1.1.8-1.19.2.jar`
- Updated Create Central Kitchen from `create_central_kitchen-1.19.2-for-create-0.5.0.i-1.3.5.jar` to `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.7.c.jar`
- Updated Create Enchantment Industry from `create_enchantment_industry-1.19.2-for-create-0.5.0.i-1.2.0.jar` to `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.4.c.jar`
- ~~Updated Create: Alloyed from `alloyed-1.19.2-v1.5.jar` to `alloyed-1.19.2-v1.5a.jar`~~
  - Removed as it still causes Create to crash, even with the update.
- Updated Create Slice & Dice from `sliceanddice-forge-2.1.1-forge.jar` to `sliceanddice-forge-2.2.0.jar`
- Updated Create Stuff & Additions from `create-stuff-additions1.19.2_v2.0.2c.jar` to `create-stuff-additions1.19.2_v2.0.3b.jar`
- Updated Create Confectionery from `create-confectionery1.19.2_v1.0.8.jar` to `create-confectionery1.19.2_v1.0.9.jar`
- Updated Some Assembly Required from `some-assembly-required-1.19.2-3.0.1.jar` to `some-assembly-required-1.19.2-3.0.2.jar`
- Updated Integrated Dungeons and Structures `idas_forge-1.7.3+1.19.2.jar` to `idas_forge-1.7.4+1.19.2.jar`
  - Compatibility with Create 0.5.1.
- Updated Integrated Stronghold from `integrated_stronghold_forge-1.0.1+1.19.2.jar` to `integrated_stronghold_forge-1.0.2+1.19.2.jar`
  - Compatibility with Create 0.5.1.
- `vinery-forge-1.2.10.jar` to `vinery-forge-1.3.0.jar`
  - I have pasted the developer's entire changelog below. please read as certain items have been removed and will result in the loss of certain items.
- Updated Vinery, again. `vinery-forge-1.3.0.jar` to `vinery-forge-1.3.1.jar`
  - Increased the size of the straw hat so it doesn’t interfere with the 2. Skinlayer
  - Fixed a faulty tag for glass panes 
  - Fixed the an Issue caused Wine Bottles not displaying correctly inside Wine Racks
  - Added tooltips for WoodFiredOven and Stove
- Updated Supplementaries from `supplementaries-1.19.2-2.3.10.jar` to `supplementaries-1.19.2-2.3.17.jar`
- Updated Ars Nouveau from `ars_nouveau-1.19.2-3.13.4.jar` to  `ars_nouveau-1.19.2-3.15.1.jar`
  - Fixed log spam
- Updated Ars Nouveau again. `ars_nouveau-1.19.2-3.15.1.jar` to `ars_nouveau-1.19.2-3.16.0.jar`
  - Patrons can now adopt starbuncles and have access to Lily, the wizard dog!
  - Unique adopted starbuncles now have a chance of appearing in worlds
  - Starbuncles can now be dyed any color
  - Starbuncles now spawn as a random color
  - Decoys in jars will attract nearby mobs (Jarva)
  - Fixes burst not targeting entiites (Alex)
  - Adds recipe to duplicate and copy warp scrolls (Alex)
- Updated Ars Nouveau, again. `ars_nouveau-1.19.2-3.16.0.jar` to `ars_nouveau-1.19.2-3.16.1.jar`
  - Fix crash with familiar starbuncles (Alex)
  - Fix crash with Interact on non-living entities
- Updated Dark Utilities from `DarkUtilities-Forge-1.19.2-13.1.7.jar` to `DarkUtilities-Forge-1.19.2-13.1.9.jar`
- Updated Dimensional Dungeons from `dimdungeons-168-forge-1.19.0.jar` to `dimdungeons-177-forge-1.19.0.jar`
  - Ultimate Feature Parity Version - 1.18.2, 1.19.2, 1.19.4, and 1.20!
    - Added two new tower rooms.
    - Theme keys now appear in advanced dungeons.
    - New data blocks for custom room builders. ("SummonKeyholder" and "LockWithCode")
- Updated Tempad from `tempad-forge-1.19.2-1.4.4.jar` to `tempad-forge-1.19.2-1.4.5.jar`
- Updated EnderChests, EnderTanks and ShetiPhianCore
  - `enderchests-forge-1.19.0-1.10.1.01.jar` to `enderchests-forge-1.19.0-1.10.1.02.jar`
  - `endertanks-forge-1.19.0-1.12.1.02.jar` to `endertanks-forge-1.19.0-1.12.1.03.jar`
  - `shetiphiancore-forge-1.19.0-3.11.3.01.jar` to `shetiphiancore-forge-1.19.0-3.11.3.03.jar`
- Updated Galosphere, this one is quite the update... jumping from `Galosphere-1.19.2-1.2.3-Forge.jar` to `Galosphere-1.19.2-1.3.0-Forge.jar`
  - Miscellaneous Changes
    + Renamed Aura Ringer to Monstrometer
    + Added lichen moss' lit texture
    + Changed lichen moss' light emission
    + Tweaked Monstrometer's texture
    + Tweaked Combustion Table's texture
    + Tweaked Silver block's texture
    + Tweaked Silver ore's texture
    + Tweaked lichen cordyceps' texture
    + Tweaked golden lichen cordyceps' texture
    + Tweaked raw silver's texture
    + Tweaked silver nugget's texture
    + Tweaked Monstrometer (Changed fuel from allurite to lumiere and emits particles in larger dark area (8->16radius))
    + Tweaked indicator particle
    + Tweaked Warped Anchor (TEleportation range increases depending on the charge level, chorus fruit works with warped anchor)
    + Lichen moss can lit up if there's a redstone signal nearby
    + Inventory order change
    + Changed Glow Flare Recipe
    + Increased glow ink clumps' light level
    + Spectre spawning change (Spawns on top of a blocktag named "spectres_spawn_on")
    + Bottling spectre will now save all the data (User that previously controls the spectre, pregnancy, breeding cooldown... etc)
    + Added new spectre texture (Only renders when spectre is being spectated)
    + Monstrometer emits a level of redstone signal in respect of the number of highlighted monsters
    + Monstrometer can now be activated with redstone
    + Added Sound Waves Obfuscation (If an allurite block is placed adjacent to a block that produces sound, it will reduce the sound by 90%)
    + Tweaked Chandelier Model and Texture
    + Tweaked Lumiere Cluster Texture
    + Tweaked Lumiere Shard Texture
    + Tweaked Lumiere Block Texture
    + Tweaked Charged Lumiere Block Texture
    + Tweaked Allurite Shard Texture
    + Tweaked Bottle of Spectre Texture
    + Tweaked Spectre Model and Texture
    + Tweaked Silver Bomb Recipe
    + Tweaked Chandelier Recipe
    + Tweaked Spectre size
    + Tweaked Lichen Caves Biome Placement (Spawns in a low humidity and low continentalness area)
    + Tweaked Spectres' spawn egg color
    + Fixed sparkle and spectre spawning issue
    + Replaced sterling armor's explosion resistance with illager resistance which reduces damage dealt by illagers/vexes/evoker fangs
    + Added Silver Bomb Modifiers Tags
    + Changed Sparkle's regrowth time (It only takes 5-10 minutes now)
  - Blocks
    + Added silver tiles
    + Added silver panel
    + Added silver lattice
    + Added glow berry silver lattice
    + Added glinted amethyst cluster
    + Added glinted allurite cluster
    + Added glinted lumiere cluster
  - Items
    + Added barometer
    + Added spectre flare
  - Sounds
    + Added "Spectral" soundtrack (plays in Lichen Caves)
    + Added Monstrometer sounds
    + Added lichen moss sounds
    + Added bowl lichen sounds
    + Added lichen roots sounds
    + Added lichen shelf sounds
    + Added Combustion Table sounds
  - Mobs
    + Ported Sparkle & Spectre to use the brain AI
    + Added specterpillar
    + Spectre now likes lichen shelf, so you can now breed them.
    + Once they have successfully breed it, they will find the nearest lichen moss and lay a specterpillar on top of the block
    + Specterpillar will always stay in their own form, unless if you feed it with lichen shelf. After they stop producing bonemeal particle, they will move to the nearest lichen moss and burrow into it. Once they've succesffuly burrowed into the block, they will place a lichen cordyceps with a little animation.
    + After that process, you have to wait for 5 minutes. During this period, they'll have a chance to start grow longer, and they will change the top texture to a lit texture after 4 mintues. Once 5 minutes have passed, the block will break and it will spawn a spectre.
  - Worldgen
    + Added gravel patch to lichen caves
    + Added large silver ores to crystal canyons
    + Made silver ores spawn in a smaller size
- Updated Mystical Agriculture from `MysticalAgriculture-1.19.2-6.0.8.jar` to `MysticalAgriculture-1.19.2-6.0.9.jar`
- Updated Mystical Agriculture again from `MysticalAgriculture-1.19.2-6.0.9.jar` to `MysticalAgriculture-1.19.2-6.0.10.jar`
  - Fix Awakened Supremium Leggings recipe not transferring NBT
- Updated Mystical Agradditions from `MysticalAgradditions-1.19.2-6.0.2.jar` to `MysticalAgradditions-1.19.2-6.0.3.jar`
- Updated Mob Grinding Utils from `mob_grinding_utils-1.19.2-0.4.49.jar` to `mob_grinding_utils-1.19.2-0.4.50.jar`
- Updated Torchmaster from `torchmaster-19.2.0.jar` to `torchmaster-19.2.90.jar`
- Updated Mahou Tsukai from `mahoutsukai-1.19.2-v1.34.44.jar` to `mahoutsukai-1.19.2-v1.34.45.jar`
- Updated Mahou Tsukai again, from `mahoutsukai-1.19.2-v1.34.45.jar` to `mahoutsukai-1.19.2-v1.34.46.jar`
  - fix bug with mystic staff mana scaling config
  - update russian and BR portuguese translations
- Updated Sophisticated Backpacks, Sophisticated Storage and Sophisticated Core
  - `sophisticatedstorage-1.19.2-0.8.5.402.jar` to `sophisticatedstorage-1.19.2-0.8.28.453.jar`
  - `sophisticatedbackpacks-1.19.2-3.18.47.836.jar` to `sophisticatedbackpacks-1.19.2-3.18.50.849.jar`
  - `sophisticatedcore-1.19.2-0.5.57.275.jar` to `sophisticatedcore-1.19.2-0.5.70.316.jar`
    - Updated Sophisticated Core again from `sophisticatedcore-1.19.2-0.5.70.316.jar` to `sophisticatedcore-1.19.2-0.5.71.319.jar`
- Updated The Graveyard from `The_Graveyard_2.5.2_(FORGE)_for_1.19.2.jar` to `The_Graveyard_2.5.3_(FORGE)_for_1.19.2..jar`
  - Fixed /kill not killing nameless hanged
- Updated Baubley Heart Canisters from `baubley-heart-canisters-1.19.2-2.0.0.jar` to `baubley-heart-canisters-1.19.2-2.1.0.jar`

## Updated libraries and utilities
- Updated Architectury from `architectury-6.5.82-forge.jar` to `architectury-6.5.85-forge.jar`
- Cucumber Library from `Cucumber-1.19.2-6.0.6.jar` to `Cucumber-1.19.2-6.0.7.jar`
- CreativeCore from `CreativeCore_FORGE_v2.9.3_mc1.19.2.jar` to `CreativeCore_FORGE_v2.9.4_mc1.19.2.jar`
- Updated Collective from `collective-1.19.2-6.53.jar` to `collective-1.19.2-6.57.jar`
- Updated KubeJS Create from `kubejs-create-forge-1902.2.4-build.5.jar` to `kubejs-create-forge-1902.2.4-build.9.jar`
- FTB Backups from `ftbbackups2-forge-1.19.2-1.0.18.jar` to `ftbbackups2-forge-1.19.2-1.0.19.jar`
- Updated Lootr (Forge) from `lootr-1.19-0.4.23.60.jar` to `lootr-1.19-0.4.24.61.jar`
- Updated Moonlight Lib from `moonlight-1.19.2-2.2.34-forge.jar` to `moonlight-1.19.2-2.2.38-forge.jar`
- Updated Puzzles Lib from `PuzzlesLib-v4.4.0-1.19.2-Forge.jar` to `PuzzlesLib-v4.4.2-1.19.2-Forge.jar`
- Updated Open Parties and Claims from `open-parties-and-claims-forge-1.19.2-0.17.3.jar` to `open-parties-and-claims-forge-1.19.2-0.17.5.jar`
- Updated datapacks for IDAS and Integrated Stronghold to support compatibility with Create 0.5.1

## Added mods
- Added Candlelight - Let's do a Candlelight Dinner! by satisfy
- ~~Added Beachparty - Let's Do Beachparty~~
  - Currently has an issue where the message "This block has functions that are not yet fully implemented. Stay Tuned!" keeps showing on /reload and world join.
- Added Catalogue 

## Removed mods
- OpenLoader
- DefaultOptions
- FastSuite
- FastWorkbench
- FastFurnace
- Occultism
- Create Deco
- Create Compat
- Create Chunkloading
  - Not compatible with Create 0.5.1
- Hypothermic
  - Log spam.

### Vinery - Let's do Wine!
Vinery has been updated to 1.3.0

*** Please read before updating! ***

To ensure that all our mods follow a specific key theme, all food items have been removed from Vinery. Vinery should focus entirely on creating  different wines and not on cooking and baking as well. Additionally, the functionality of the wood oven has been limited and the cooking pot has  been removed.

The following items have been removed:

All varieties of jam
- Milchbrot
- Crusty Bread 
- Donut
- Chocolate Bread 
- Apple Pie
- Apple Pie Slice 
- Dough
- Breadslice
- Toast
- Jar
- Apple Cupcake
- Cooking Pot

We are sorry for possibly lost Items. :(

Other changes & fixes:

- Fixed an Issue causing the Straw Hat to render incorrectly 
- Fixed a faulty tag for glass panes 
- Fixed the kitchen sink loottable - you’ll now also get your faucet back 
- Fixed the kitchen sink voxelshape
- Updated following Textures 
- Faucet 
- Table 
- Chair 
- Big Table 
- Shelf 
- Drawer 
- Cabinet 
- Big Wine Bottle Storage 
- Small Wine Bottle Storage 
- Apple Juice 
- Bag with Cherries 
- Bag with red Grapes 
- Bag with white Grapes 
- Renamed following Items & Blocks
- Table -> Cherry Table 
- Chair -> Cherry Chair
- Big Table -> Big Cherry Table
- Shelf -> Cherry Shelf
- Drawer -> Cherry Drawer
- Wine Barrel -> Crested Barrel
- Cabinet -> Cherry Cabinet
- Big Wine Bottle Storage -> Big Cherry Wine Bottle Storage
- Small Wine Bottle Storage -> Small Cherry Wine Bottle Storage
- Old Cherry Tree -> Apple Tree
- Changed following Recipes
- Flower Box, podzol -> dirt
- Grapevine Pot, spruce planks -> tag:planks 
- Grapevine Pot, spruce slabs -> tag:wooden_slabs
- Wine Barrel, tag:planks -> cherry_slabs
- Added following Blocks
- Oak Bottle Storage 
- Mangrove Bottle Storage 
- Spruce Bottle Storage 
- Birch Bottle Storage 
- Acacia Bottle Storage 
- Jungle Bottle Storage 
- Dark Oak Bottle Storage 