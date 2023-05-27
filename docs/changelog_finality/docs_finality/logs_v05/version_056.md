---
layout: default
title: Version 0.5.6b (1.18.2)
parent: Finality Iteration 0.5
grand_parent: Finality Changelog
nav_order: 4
---
# Version 0.5.6b (1.18.2) 
**This update has been released, but there may still be issues that we haven't caught yet. Please let us know.**

After play testing on the multiplayer server, the Ars Nouveau Tier 1 spell book recipe did not function with Twilight Forest's Steeleaf shovel, pickaxe, axe and sword for unknown reasons despite working previously. I did not write the recipe script to respect any NBT tags or detect enchantments, so the recipe *should* have been valid. Also replaced `Simple Discord Rich Presence` by Sunekaer with `Simple Discord RPC` by hyperionsa 

This update is NOT game breaking, so there is no need to create a new world.

## Recipe Changes
### Ars Nouveau recipe changes
  * Spell Book Tier 1 has been reverted back to iron tools, but still requires entry to the Twilight Forest. However, players will now also have to get into Blue Skies to obtain an iron equivalent ore called Charoite.
  * Spell Book Tier 2 remains mostly unchanged, but the precision mechanism at the end has been removed and replaced with a blaze cake.
  * Spell Book Tier 3 still requires ProjectE's dark matter (which is *much* easier to obtain in my modpack if you dedicate a Create coal manufacturing factory) but Crystaltine Ingots have been removed. Now requires 2 Dark Matter orbs and 3 of Create's precision mechanisms. The requirement for the Enhanced Ender Catalyst, Wilden Tribute and Minecraft's Undying Totem remains the same.

## FTB Quests changes
* Added the Architect Age
* Added some quests (they are currently placeholders) into the Botania chapter.
* Added some names to some quests.
## Other changes
* Carry On block blacklist additions:
  * Blacklisted Shetiphian's ender chests and ender tanks from being picked up with Carry On to prevent their appearance from changing as they reverted back to their pre-upgrade texture but still kept their functionality.
  * Blacklisted Refined Storage blocks from being picked up by Carry On due to previously causing a crash in a previous playthrough.
* Corrected FTB Quests progression on the Ring of the Seven Curses. 
  * Now relies on the Advancement built into the Enigmatic Legacy mod instead.
* Updated the following mods:
  * Create Crafts & Additions `createaddition-forge-1.18.2-20230507a`
    * Fixed crash when using some non-English system languages.
    * Fixed Energy Condition crash.
    * General Improvements
  * Spark
    * This is a backported version of spark v1.10.x for Minecraft 1.18.2.
  * Unusual End `UnusualEnd1.18.2_V1.4.1.jar`
    * Added 2 Advancements
    * Tweaked a bit the advancements progression
    * Added 2 new vanilla wandering traders trades (Void Totem + Firefly Bucket)
    * Changed the mod icon and author name (Sweetygamer2 -> Sweetygamer)
* Removed the following mods:
  * Inventory Sorter by cpw
    * This actually doesn't add much to the game as the majority of players are aware of how to use the functions provided by the mod. Quark is better at presenting its sorting function visually.
