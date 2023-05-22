---
layout: default
title: Version 0.5.7b (1.18.2)
parent: Finality Iteration 0.5
grand_parent: Finality 1.18.2 Changelog
nav_order: 3
---
# Version 0.5.7b (1.18.2)
**Version 0.5.7b has now been released.**

Unfortunately I am thinking about removing a few mods from the modpack for performance reasons, but this might be for the better. This update *will* require a world regeneration as structure mods have been added. 

* Updated the modpack icon with a cube instead of a sphere.
* Fixed typo in one of my assets in FancyMenu
* Someone pointed out to me that Quark's chest variations are not showing up and I looked into this issue. It turns out this is actually intended. By default, Quark disables its chest variations when the Woodworks by TeamAbnormals is installed to avoid overlap, but I have Polymorph to handle conflicting recipes. Honestly speaking, I prefer style of the chests from Woodworks over Quark's variations, so I will not be disabling the Anti-overlap feature built into Quark.

## Documentation Changelog (1.18.2)
All patch notes related to FTB Quests and the Tome of Finality.
### FTB Quests changes
* Moved Wither Storm to the top of the FTB Quests lists to make it more visible as I don't want it to be a *late* endgame mod as it destroys the overworld. I will be adding alternative recipes later on for players who want to acquire the Withered Beacon without having to fight the Wither Storm at all.
* Added subtitle line "This is Create." to line 1 of the `Age of Creation` chapter.
* Added the Sustenance chapter group to meet parity with the Tome of Finality.
* Moved Create's Architect Age chapter to a new chapter group `Architecture and Decor`
  * Added Spice it Up! to this new chapter group to start the decor quests.
* Added a dedicated entry for The Graveyard.
* Changed description lines on `Hi! Welcome to Finality` from:

| Line # | Text |
| --- | --- |
| Line 1 | Ensure your difficulty is on Hard for maximum suffering. |
| Line 2 | Patchouli book granting has been fixed! | 
| Line 3 | If you lose it, it's reclaimable from Emergency Items (broken heart icon) on the right. You can also craft the book with two sticks! |
| Line 4 | Also, take the time now to SET YOUR KEYBINDS, only if you want to." |

to

| Line # | Text |
| --- | --- |
| Line 1 | If you wish to play the modpack on its intended difficulty, set the difficulty to Hard. For obvious reasons, this is optional. |
| Line 2 | The rest of the chapters can be accessed after you click the checkmark here and move your cursor to the left edge of your screen. |
| Line 3 | If you lose the Tome of Finality, it is reclaimable from Emergency Items (broken heart icon) on the right. You can also craft the guidebook with two sticks! |
| Line 4 | Also, take the time now to SET YOUR KEYBINDS, only if you want to." |


### Tome of Finality changes
* Added entry `A Serious Warning` to explain the consequences of the Wither Storm.
* Added entry `Recipe Conflicts` to explain to players what Polymorph does.
* Added new tooltip lines to the Tome of Finality.
* Added a title for a spotlight page featuring the Ring of the Seven Curses to better fit. Also edited some text to make it clearer that it is permanent.
* Added entry `Modified MC Recipes` entry in the Genesis category.
* Added more information into certain entries in the Momentum category.
* Added the Create: Central Kitchen entry in the Sustenance category.
* Added the BIG SANDWICH entry in the Sustenance category.
* Added more text to previously existing Sustenance entries.
* Added the Technology category for other tech related entries.
* Added the Decoration category for decoration related entries.

## Core changes (1.18.2)
Changes that actually affect gameplay.

### Config changelog
* Remembered to set the water freezing temp for Hypothermic to 0.5 to match extremely cold environments. The default value of 1.5 simply felt too high of a threshold so any body or stream of water in typical biomes ended up freezing players. Will be synchronizing with the 1.19.2 variant of the modpack soon.

### Recipes changelog
* For some reason I put the Beacon recipe to be exclusive to ExtendedCrafting's crafting tables. The recipe can now be used on regular crafting tables.
* Fixed Create: Stuff & Additions recipes for the following items. Interestingly there were a few typos from the mod's jar file directly. The items `minecraft:copper_nugget` and `create:crushed_brass_ore` were listed as outcomes, but neither **actually exist**. 
  * Steam Engine 
  * Heat Engine
  * Hydraulic Engine
* Added alternative recipes to acquire the Withered Nether Star, Tainted Flesh Blocks and Tainted Glass.

### Item removals
* Waystones related items
  * Removed and hid Warp Plates
  * Removed and hid Warp Dust
  * Removed and hid Attuned Shards

### Mod additions
Several new mod additions, and three carried over from the 1.19.2 modpack variant.
* Added Hypothermic by MuffinsQw
  * Just carrying this over from the 1.19.2 variant of the modpack.
* Added SereneSeasons, a Glitchfiend mod.
  * This was supposed to be added to both variants of the modpack, but now it's here.
* Added Decorative Blocks
  * Just carrying this over from the 1.19.2 variant of the modpack.
* Added Create Enchantment Industries
  * Apparently forgot to add this one over from the 1.19.2 variant as well.
* Added Create Deco
  * Carried over from the 1.19.2 variant of the modpack.
* Added Better Third Person 
  * Another QoL mod that I forgot to add... *sigh*
* Added Boat Break Fix by ElocinDev
* Added [Twigs](https://www.curseforge.com/minecraft/mc-mods/twigs)
  * Re-adding this.
* Added ItemZoom
  * Having a GUI scale of 2 has its own issues.
* Re-added Server Performance - Smooth Chunk by someaddon
* Added Create: Central Kitchen
* Added Some Assembly Required
* Added Molten Vents
* Added Molten Geodes
* Added Aileron
* Added Elytra Bounce
* Added Etched
  * Thank you to Juni Knytt from the Create Discord server for showing me these mods ^-^
* Added Variant Crafting Tables [Forge] by Kitteh6660
  * At the suggestion of Jacqueline Vile
* Added Colossal Chests by kroeser
* Added EnergeticcSheep by kroeser
* Added Atmospheric by TeamAbnormals
* Added Picke Tweaks by BlakeBr0
* Added [Connected Glass by SuperMartijn642](https://www.curseforge.com/minecraft/mc-mods/connected-glass)
* Added [Chunk Loaders by SuperMartijn642](https://www.curseforge.com/minecraft/mc-mods/chunk-loaders)

### Mod updates
* Updated Integrated Dungeons and Structures by CraisinLord to version `idas_forge-1.6.4+1.18.2.jar`. His changelog can be read below. However, this also means that I have to update the config pack soooo yeah... You can regenerate your world in case there are Interated Dungeons / Structures that have been affected by this.
  * Fixed an issue with the structure set to avoid list not working, therefore fixing all issues with structure collision
  * Fixed a typo in the Sunken Ship advancement
  * Added lore books by Mothrin to the Witch's Treestump
  * Added lore books by Hisakid to the Haunted Manor
  * Make sure to update the config pack if you're using!
* Updated Cyclops Core by kroeser to `CyclopsCore-1.18.2-1.17.3`

### Removed mods
These two mods were removed as my FPS dropped considerably after installing these optimization mods on the 1.19.2 variant. Out of curiosity, I also removed the same three mods on the 1.18.2 variant. Surprisingly, FPS went back to tolerable levels.
* Removed Better FPS - Render Distance
* Removed Dynamic View
* Removed Sons of Sins
  * May make a return at some point, but for now it is being removed because of the loud sounds, will make adjustments in the resourcepack to fix this in another update.