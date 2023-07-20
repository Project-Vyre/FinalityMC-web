---
layout: minimal
title: 0.1.4b (1.19.2)
parent: Iteration 0.1
grand_parent: Finality Mote Changelog
nav_order: 7
---

Currently in development!

# Version 0.1.4b

Not a world or game breaking update, so it is safe to update.

# 7.18.23-7.20.23 Changelog

Apparently I wrote duplicate scripts and never caught my own mistake, that's been fixed now and will be patched to all versions of Finality.

- Custom fluids can now be used with the bucket.
- Updated texture used for the Trident Prong.
- Fixed the quest for Sandpaper to now detect any kind of sandpaper, this is a mistake on my part.

## Singularity Recipe Changes
These changes will be applied to all versions of Finality.
- Changed the Mechanical Crafting singularities to utilize Dormant Singularity Cores at the center.
- Brass Singularity now uses the new singularity creation method.
- Changed the Rose Quartz Singularity recipe to use regular Rose Quartz.

## Mod updates
- KubeJS has been updated to 6.1.
  - `kubejs-forge-1902.6.0-build.142.jar` to `kubejs-forge-1902.6.1-build.300.jar`
  - `kubejs-forge-1902.6.1-build.300.jar` to `kubejs-forge-1902.6.1-build.307.jar`
  - `kubejs-forge-1902.6.1-build.311.jar`
- KubeJS Create has been updated to support KJS 6.1. Updated a second time after item quantities for both Mixing and Compacting have been fixed by Max yaaay
  - `kubejs-create-forge-1902.2.4-build.9.jar` to `kubejs-create-forge-1902.2.4-build.16.jar`
  - `kubejs-create-forge-1902.2.4-build.16.jar` to `kubejs-create-forge-1902.2.4-build.18.jar`
  - `kubejs-create-forge-1902.2.4-build.18.jar` to `kubejs-create-forge-1902.2.4-build.20.jar`
- As a result, I have cleaned up some scripts.
- Cataclysm updated from `L_Enders_Cataclysm-1.18-1.19.2.jar` to `L_Enders_Cataclysm-1.19-1.19.2.jar`
- FTB Quests updated from `ftb-quests-forge-1902.4.18-build.244.jar` to `ftb-quests-forge-1902.5.0-build.248.jar`
  - `ftb-quests-forge-1902.5.0-build.248.jar` to `ftb-quests-forge-1902.5.1-build.250.jar`
- Cataclysm updated from `L_Enders_Cataclysm-1.19-1.19.2.jar` to `L_Enders_Cataclysm-1.20-1.19.2.jar`
- Updated ModernFix from `modernfix-forge-5.2.5+mc1.19.2.jar` to `modernfix-forge-5.3.1+mc1.19.2.jar`

--- 
7.15.23 - 7.17.23

## Config and core updates
- Apparently the Alex's Mobs compat datapack for IDAS was implemented, this has now been removed.
- Added additional descriptions to Create related quests.
- Fixed structure detection to detect YUNG's Better Nether Fortress instead of the vanilla Nether Fortress.

These changes will be applied to all versions of Finality.
- Moved Jade to the top left corner to provide unobstructed viewing of Cataclysm's boss health bars.
- Enigmatic Legacy's Amulet Vessel now can only be claimed by the original owner.
- Reduced Tempad's cooldown to 30 seconds.
- Added Nicer Rain by Lat
- Tridents are now craftable.
- Increased inventory space for Backpacked's backpacks please update your server's config files if it does not synchronize over!
  - Added a recipe that uses Leather to make the item more accessible. Bunnies don't seem to spawn all that often.

These changes will be applied to all versions of Finality on Forge MC 1.19.2 and higher.
- Fixed JEI information script.

## Mod additions
- Added Carry On
  - Blacklisted EnderChests and EnderTanks to prevent the visual bug (private EnderChests and EnderTanks with their diamond trims being removed after being carried)from ocurring.
- Added Clumps
  - This should have been here from the start, but this was my Just Create (Forge) instance so I just never added it after converting it to a modpack.
- Re-added Healing Campfire
  - I was very hesitant in adding this ONLY out of the concern of adding more mods, but it has been re-added.
- Added Toast Control 
  - Just to silence certain annoying Toasts along with making them translucent as to not obstruct certain UI elements.

## Mod updates
- Updated Cataclysm from `L_Enders_Cataclysm-1.16-1.19.2.jar` to `L_Enders_Cataclysm-1.17-1.19.2.jar`.
- Updated Cataclysm from `L_Enders_Cataclysm-1.17-1.19.2.jar` to `L_Enders_Cataclysm-1.18-1.19.2.jar`
- Updated FTB Library from `ftb-library-forge-1902.3.19-build.214.jar` to `ftb-library-forge-1902.4.0-build.232.jar`.
- Updated ModernFix from `modernfix-forge-5.2.3+mc1.19.2.jar` to `modernfix-forge-5.2.5+mc1.19.2.jar`.
- Updated Raised from `raised-forge-1.19.2-1.2.3.jar` to `raised-forge-1.19.2-2.0.0.jar`.