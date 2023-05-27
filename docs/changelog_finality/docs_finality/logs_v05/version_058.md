---
layout: default
title: Version 0.5.8b (1.18.2)
parent: Finality Iteration 0.5
grand_parent: Finality Changelog
nav_order: 2
---
# Version 0.5.9b Changelog

{: .warning}
`supermartijn642corelib-1.1.8-forge-mc1.18.jar` causes the modpack to crash. DO NOT UPDATE IT! Remain on `supermartijn642corelib-1.1.7-forge-mc1.18.jar`

This update I changed the main menu around a little bit, also going to re-render the black hole in Blender...

Hopefully you guys like it.

## Soundtrack additions
* [end.ogg] [Shattered Glass - Cjbeards](https://youtu.be/rjumdHtHU5U)
* [boss.ogg] [Brave the Storm - Cjbeards](https://youtu.be/dGmLKmxvJ0I)

## Documentation Changes
Documentation changes for the in-game experience.

### FTB Quests
* Added chapter for `Baubley Heart Canisters`
* Added chapter for `Artifacts`
* Moved chapter `Mob Grinding Utils` to chapter group `Useful Utilities`
* Added clock decoration related quest to `Spice it Up!` 

### Tome of Finality
* Work in progress.

## Core Changes
Changes that actually affect gameplay.

Upgraded from `Forge 40.2.1` to `Forge 40.2.4`. The Forge changelog is below.

| 40.2 | Changes |
| ------ | ------- | 
| 40.2.4 | [1.18.2] Fix incorrect SpecialSpawn fire location (#9481) |
|  | - Co-authored-by: Brennan Ward <3682588+Shadows-of-Fire@users.noreply.github.com> |
| | [1.18.x] Make mixins work with JarJar (#9506) |
| | - Backport of #8900 |
| | - Update ASM to 9.5 |
| | - Update JarJar to 0.3.19 |
| | - Update SecureJarHandler to 1.0.8 |
| 40.2.2 | Fix forge grindstone hooks allowing stacks of non-stackable items (#9458) |
| 40.2.1 | Fire TickEvent.WorldTickEvent on ClientLevel tick (#9304) |
| 40.2.0 | Mark 1.18.2 Recommended Build 2 |

## Config changes
Some minor config changes...

### Default configs 
These changes are not retroactive as they are in the `defaultconfigs` folder, so be sure to synchronize them with your world's internal `serverconfig` folder.
* Increased Wither Storm evolution speed, so now it should evolve faster.
* Increased Player Protection time for the Wither Storm to 5 minutes. 
* The nights now last longer, good luck.

## Mod updates
* Updated `UnusualEnd1.18.2_V1.4.1.jar` to `UnusualEnd1.18.2_V1.4.2.jar`
  - Buffed the Nether Orb from 15 to 30s Fire Protection
  - Reduced a bit the Wanderer's House generation rate
  - Added a recipe for Heaviness Potions (Bolok Scale in Awkward Potion)
* Updated `Ars Nouveau` from `ars_nouveau-1.18.2-2.8.0.jar` to `ars_nouveau-1.18.2-2.9.0.jar`
  - Adds tags to blacklist warping entities with blink and portals
  - Fixes linger not having the same color as the casting spell
  - Fixes crash with wilden guardian
  - Catches errors for the scribes tables when other mods do dumb things
* Updated `Architectury` from `architectury-4.11.90-forge.jar` to `architectury-4.11.93-forge.jar`

## Mod removals
* Removed XPTome

## Mod additions
* [Healing Campfire by Serilum](https://www.curseforge.com/minecraft/mc-mods/healing-campfire)
* [Villager Names by Serilum](https://www.curseforge.com/minecraft/mc-mods/villager-names)
* [Stack Refill by Serilum](https://www.curseforge.com/minecraft/mc-mods/stack-refill)
* [Sound Physics Remastered](https://www.curseforge.com/minecraft/mc-mods/sound-physics-remastered)
* [Whisperwoods](https://www.curseforge.com/minecraft/mc-mods/whisperwoods)
* [Hourglass](https://www.curseforge.com/minecraft/mc-mods/hourglass)
* [Create: Alloyed](https://www.curseforge.com/minecraft/mc-mods/create-alloyed)
* [Spice of Life: Carrot Edition](https://www.curseforge.com/minecraft/mc-mods/spice-of-life-carrot-edition)
* [Create: Slice and Dice](https://www.curseforge.com/minecraft/mc-mods/slice-and-dice)

