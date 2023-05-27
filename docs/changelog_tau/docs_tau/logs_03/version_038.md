---
layout: default
title: Finality Tau 0.3.8b
nav_order: 1
parent: Finality Tau Changelog
permalink: /docs/version_038
---
# v0.3.8b Changelog
Now (in the process of being approved by CF) released, but I may have forgotten some recipes. Just trying to get this out as soon as possible. Also, FTB Quests now requires `Forge 43.2.8` or higher now, so hopefully there aren't any broken interactions between mods. I read the changelogs and I will first release the 1.19.2 variant of the modpack on `Forge 43.2.11`. If there are any issues I will revert it back to `Forge 43.29`.

I'm aware the 1.19.2 variant is missing its modpack logo, this will be released later.

I also just realized I deleted my `en_us` corrections for the Cataclysm mod, sooo there's that.

Also just imported the FancyMenu layout from the 1.18.2 variant, though maintaining both menus to look *exactly* the same the whole time is probably not doable over the long term.

## Config changes
* Thanks to CF's rejection, I was given the chance to set the water freezing temp for Hypothermic to 0.5 to match extremely cold environments. The default value of 1.5 simply felt too high of a threshold so any body or stream of water in typical biomes ended up freezing players. 

## Recipe changes
I will be using CraftTweaker to handle recipes in the 1.19.2 variant, so this might take some time to rewrite the new recipes. It won't take as much time as the KubeJS rewrite for the 1.18.2 variant due to many of the recipes already existing and CraftTweaker being unable to remove all of Avaritia1.1x's recipes. 

**Soooo new update... I might be forced to use KubeJS again as Patchouli's Guide Book refuses to be given to players on first join with other global data pack loaders like OpenLoader by DarkhaxDev and Paxi by YUNG**

* Using the old recipe for Ars Noveau's spell book for Tier 1 as I have verified in-game that the spell book is made. This does mean you will have to get a full set of Steeleaf tools, however. KubeJS for some reason can't use Steeleaf tools as ingredients.
* Synchronized the recipe change for the Tier 3 Ars Nouveau spell book to utilize the 3 Precision Mechanisms and 2 Dark Matter orbs over the old recipe which utilized 2 Crystaltine Ingots.
* Partially synchronized the recipes for the Creativerite Ingot failure outputs, just to keep it different from the 1.18.2 variant.

## Mod changes
Below are lists for updated, removed or added mods, if applicable.
### Added mods
* Re-added OpenLoader
  * It did not seem like the datapacks for CraisinLord's structure mods were being applied by KubeJS, so OpenLoader is being reinstated.
* Re-added Golden Hoppers
  * I forgot to re-add this, oops
* Added Villager Names by Serilum
* Added Healing Campfire by Serilum
* Added KubeJS as the global datapack loader because Paxi and OpenLoader were not granting the modpack's Patchouli guidebook.

### Removed mods
* ~~Removed OpenLoader by DarkhaxDev~~ 
  * Also tried Paxi by YOUNGNICKYUNG to see if it would solve the issue with the modpack's Patchouli guidebook which unfortunately that didn't work as well.
* Removed Better FPS - Render Distance
* Removed Server Performance - Smooth Chunk Save
* Removed Dynamic View
* Removed XP Tome

### Updated mods
* Quark has been updated to `Quark-3.4-399.jar`. Vazkii's changelog is below.
  - Added a config option to the general config that allows for disabled items to stay visible
  - Added Pathfinder's Quill, a new item that generates a Pathfinder Map over time, to help lower server stress - any previous ways to acquire Pathfinder Maps now provide the same Pathfinder's Quill
  - Added Slimes splitting into Magma Cubes if they die from Magma damage
  - Added some more celebration days to the q button (mostly VM team member birthdays)
  - Fixed Forgotten Hat not having the forge:helmets tag
  - Fixed incorrect face culling logic for Bamboo Carpets when Rubidium is used
  - Fixed Leaf Carpets not having map colors
  - Fixed Tetra hoes not breaking in an area
  - Improved the config for the Pathfinder Maps module with more modularity
  - Lowered the drop rate of saplings from Blossom trees by a lot to be more in line with other trees
  - Monster box mob spawns are now controlled by the quark:monster_box_spawns loot table (all entries must be mob eggs)
  - Usage Ticker should now correctly pick up ammo from Guns Without Roses and other projectile weapon mods
  - Wandering Traders will now always carry a random Pathfinder's Quill (configurable)
* Moonlight Lib
  * Removed some early Items class classloading so we don't erroneously get the blame for other mods failed mixins
* Integrated Dungeons and Structures has been updated to `idas_forge-1.7.1+1.19.2.jar`
  * Fixed an issue with the structure set to avoid list not working, therefore fixing all issues with structure collision
  * Fixed a typo in the Sunken Ship advancement
  * Added lore books by AncientWiserOne to the Ancient Mines
  * Added lore books by Mothrin to the Witch's Treestump
  * Added lore books by Hisakid to the Haunted Manor
  * Make sure to update the config pack if you're using!
* Hypothermic has been updated to `v2.1.0.1`
  * Fixed freezing being too slow
  * Cold Resistance potions now work
  * Removed Freeze Protection
* Upgraded Netherite has been updated to `upgradednetherite-1.18.2-5.1.0.9-release` developer's notes below...
  * Fix Crossbow
* Upgraded Netherite: Ultimerite has been updated to `upgradednetherite_ultimate-1.19.2-4.1.0.4-release` developer's notes below...
  * Fix Crossbow