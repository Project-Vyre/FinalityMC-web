---
layout: default
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

Do not update `Flat Colored Blocks - For Forge` as the newest version still breaks server joining.
{: .warning }

Updated to `Forge 43.2.14` from `Forge 43.2.11`.

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