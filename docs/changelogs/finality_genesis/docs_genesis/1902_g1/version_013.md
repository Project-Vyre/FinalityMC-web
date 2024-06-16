---
layout: minimal
title: 0.1.3 (1.19.2)
parent: Iteration 0.1
grand_parent: Finality Genesis Changelog
nav_order: 6
---

# Important Things

- Fixed solappliepie-server.toml not using the correct attribute for speed. (Patch B)
  - VERY IMPORTANT! Copy and paste the new solappliepie-server.toml config file from the defaultconfigs folder into `saves\<your world name>\serverconfig`

# Genesis 0.1.3e
A follow up to Patch D with fixes for certain Mystical Agriculture recipes and more quest hints. One such example was honey essence combined with a glass bottle in a shaped recipe requiring the full 3x3 grid for some odd reason.

- Default keybind for Personality's crawling has been set to X and toggled sprinting back to Ctrl (MC default)
- Changed recipe method sorting so that Create's Item Draining method is not the first type shown to players.
- Fixed quest branches displaying prematurely in the Age of Combat chapter without player interaction.
- Enigmatic Legacy's darkness branch has been made entirely optional, a change that should have been applied earlier...
- Added additional explanations for Apotheosis.
- Added additional explanations for Mystical Agriculture.
- Xaero's Minimap now displays IRL time.
- Fixed shapeless version of the BHC Relic Apple recipe.
- Fixed Honey Bottle recipe from Mystical Agriculture. Also added a vertical recipe for ease.
- Removed extra diamond compacting recipe that I wrote, oops...
- Fixed Honeycomb recipe from Mystical Agriculture.
- Dragon Breath can now be crafted with a bottle and a dragon egg.

### Mod updates
- Cupboard `cupboard-1.19.2-1.5.jar` to `cupboard-1.19.2-1.6.jar`

# Genesis 0.1.3d
This is another follow up update to the initial release of 0.1.3c with very minor updates with no recipe changes. KubeJS's tag event visibility was "fixed", so you shouldn't have those illegal errors when loading a world as often. If you do still see the errors, follow the instructions provided by the error message.

### Mod updates
- KubeJS `kubejs-forge-1902.6.1-build.352.jar` to `kubejs-forge-1902.6.1-build.362.jar`
- Quark `3.4-405` to `3.4-409`
- Xaero's World Map `XaerosWorldMap_1.32.0_Forge_1.19.1.jar` to `XaerosWorldMap_1.33.0_Forge_1.19.1.jar`

# Genesis 0.1.3c
This is another follow up update to the initial release of 0.1.3 but has a hefty amount of mod additions mostly for decoration purposes. However, with the addition of Savage & Ravage, new pillager outposts will be different from existing ones in your world.

## 8.14.23
- Blacklisted Red Power blocks from being carried with Carry On.
- Changed the retexture of the "Command Blocks" slightly.
- Added additional information and rewards to Age of Creation quest nodes.
- Returned orestone generation with the Mechanical Extruder. Command Block method produces a stack with every bonk.
- Added additional food rewards and increased reward size, so you should be able to get more than 1 item.
- GoG4 Soundpack is no longer selected by default.
- Changed keybinds for Sitting, Crawling, Chat Peek. Only first time installations will have keybinds changed.
- Added the primordial mechanisms.
- Entropy Mechanism is now made with the ascendant mechanism which is made with each descending order of the primordial mechanism line. All I can say is good luck!
- Entropy Mechanism percentage has been increased to 65% success rate.
- Fixed Apotheosis gem recipes for Overworld, Nether and End gems!
- You can now obtain Ancient rarity gems from Apotheosis!
- Mystical Agriculture's Harvester block is no longer craftable.

### Mod additions
- Added NetJS for update notifications.
- Added Abnormals Delight for Farmer's Delight compatibility
  - This should have been here from the start...
- Added Boatload
- Added Clayworks
- Added Personality
- Added Savage & Ravage
- Added Allurement
- Added Chipped 
- Added Handcrafted
- Added Decorative Blocks
- Added Dark Paintings
- Added Cycle Paintings
- Added Vertical Slabs Compat
- Added Just Enough Painting Previews
- Added Just Enough Effect Descriptions
- Added Supplementaries Squared
- Added Dimensional Paintings
- Added BetterF3

### Mod updates
DO NOT UPDATE APOTHEOSIS to 6.3.4 as it causes a crash with Tempad!
- Apotheosis `6.3.3` to `6.3.5`
- Biomes o' Plenty `BiomesOPlenty-1.19.2-17.1.1.162.jar` to `1.19.2-17.1.2.544`

## 8.13.23
- Removed the retexture for diorite.
- Introduction chapter now uses Flexible progression.
- The original gravel crushing recipe has been restored. Dirt is now renewable via mixing or with Mystical Agriculture.
- Corrected Red Power typo. Should be *Amplifies the power of the input signal up to 10.* and not *Amplifier the power of the input signal up to 10.*
- Reduced processing time for the Ultimate Singularity. Also now grants a guaranteed 3 ultimate nuggets, and 25% chance of giving 1-3 nuggets with a 75% chance of returning the singularity for re-processing.
- Command Blocks are no longer consumed when making Structure Void.
- The "Command Blocks" can now be mined.
- Added chapter for Red Power (1.19.2+ exclusive)
- Increased Cloud Storage chest limit to 262144 slots.
- Endgame Aquamirae gear is now unbreakable and can no longer burn in lava.
- BHC Vitality Blade is now unbreakable and can no longer burn in lava.
- Phantom Membranes can now be made from haunting rotten flesh.
- Implemented Red Power recipe changes, specifically for the basic Node, Wires and Safety Glasses.
- Implemented BHC Canister recipe change. Now uses iron sheets for the frame and soul sand as the core.
- BHC relic apple now uses Golden Apples.
- BHC wither bones can now be acquired from haunting bones but is not guaranteed.
- Echo Shards can now be made by haunting Deepslate Shards, but with a low success rate.

### Mod updates
- Apotheosis `Apotheosis-1.19.2-6.3.2.jar` to `Apotheosis-1.19.2-6.3.3.jar`
- Moonlight Lib `moonlight-1.19.2-2.2.43-forge.jar` to `moonlight-1.19.2-2.2.44-forge.jar`
- Server Performance - Smooth Chunk Save `smoothchunk-1.19.1-2.0.jar` to `smoothchunk-1.19.2-3.1.jar`

### Mod additions
- Added Lodestone

## 8.10.23-8.12.23
- Fixed non-functional red sand mixing recipe from the Mystical Agriculture Create compat script. This was never mentioned as invalid by KubeJS for some reason. As for what the typo was that resulted in this error not working: `['16x minecraft:red_sand', 16]` but it should have been `'16x minecraft:red_sand'`
- Removed glowstone from the Create Neterrack crushing recipe. I actually forgot that glowstone is renewable via Create's automated brewing methods sooo yeah.
- Removed more cursed vanilla recipes. Please don't be one of those people who SMELT or Blast quartz ore. This also applies to normal / deepslate diamond ore, emerald ore, old iron ore, etc.
- Updated hiding script.
- Iron ore blocks can now drop 1-2 by default without looting on your pickaxe.
- Changed ItemID for High Entropy Alloy to match.
- Changed recipe for Creativerite Ingots.
- Changed recipe for Ultimerite Ingots.
- Changed armor set strength effect bonus to 3.
- Waystones actually now use inverse XP, so the further you are from a waystone the cheaper it is eventually going free after a certain distance.
- Milk acquisition via Mystical Agriculture + Create has been added.
- Supplementaries Quiver is now craftable.

### Mod updates
- Create Cafe `createcafe-1.2.2-1.19.2.jar` to `createcafe-1.2.3-1.19.2.jar`
- Xaero's Minimap `Xaeros_Minimap_23.6.0_Forge_1.19.1.jar` to `Xaeros_Minimap_23.6.1_Forge_1.19.1.jar`

### Mod additions
- Added LootJS
- Added Visual Workbench

# Genesis 0.1.3b

## 8.9.23 - 8.10.23
This is another follow up update to the initial release of 0.1.3.
- Fixed `solappliepie-server.toml` not using the correct attribute for speed.
  - VERY IMPORTANT! Copy and paste the new .toml config from the defaultconfigs folder into `saves\<your world name>\serverconfig`
- Quest progression in the Age of Creation chapter is now set to Flexible. Hopefully this eliminates the awkward ***"Oh, I already did this already... Why wasn't this tracked?"*** moments.
  - Quest progression for Apotheosis is now set to Flexible.
  - Quest progression for Storage Management is now set to Flexible.
  - Quest progression for Epilogue is now set to Flexible. 
  - Passangers seat quest now accepts all seat colors.
- Damage cancellation script no longer produces errors but this is a temporary solution.
- Blacklisted Backpacked from Carry On interaction to remove conflicting functionality.
  - During further playtesting users were not able to pick up their backpacks by Shift + Right click because of Carry On overriding this feature. This has been fixed with the blacklist.
- Enigmatic Legacy seems to be resetting the .omniconf file and we have been able to pick up enigmatic vessels of other players... I could have forgotten again, however.
- Added more hints to the Apotheosis quest tree.
- Added tooltips and hints related to Cloudstorage.
- The Travel Staff recipe from Travel Anchors seems to have reversed materials and may have been broken for longer. This has now been fixed to what it was originally which was 2 iron ingots and 1 ender pearl.
- Adjusted recipe for High Entropy alloy.
- Adjusted Mechanical Extruder recipes for Create's orestones.
- Buffed Baby Leviathan significantly.
- Added even more Apotheosis compat recipes, this time for the arrows.
- Added the Toggle Latch to the Create quest tree, I wasn't aware of it's existence actually...
- Changed Mechanical Extruder recipe for orestones again. Crying Obsidian is no longer used.
- Added actual recipes for the command blocks.
- Added a recipe for vanilla spawners.
- Increased Cloud Storage slots for both the cloud chest and static cloud chest from 4096 slots to 131072 slots

### Mod updates
- Connectivity `connectivity-1.19.2-4.4.jar` to `connectivity-1.19.2-4.5.jar`
- Create Cafe `createcafe-1.2.1-1.19.2.jar` to `createcafe-1.2.2-1.19.2.jar`
- Create Slice & Dice `sliceanddice-forge-2.3.0.jar` to `2.3.1`
- Just Enough Resources `JustEnoughResources-1.19.2-1.2.2.200.jar` to `JustEnoughResources-1.19.2-1.2.2.236.jar`
- Cataclysm `L_Enders_Cataclysm-1.28-1.19.2.jar` to `L_Enders_Cataclysm-1.29-1.19.2.jar`
- Max Health Fix `MaxHealthFix-Forge-1.19.2-8.0.1.jar` to `MaxHealthFix-Forge-1.19.2-8.0.2.jar`
- ModernFix `modernfix-forge-5.5.1+mc1.19.2.jar` to `modernfix-forge-5.6.0+mc1.19.2.jar`
- Open Parties and Claims `open-parties-and-claims-forge-1.19.2-0.19.1.jar` to `open-parties-and-claims-forge-1.19.2-0.19.3.jar`
- Pollen `pollen-forge-2.0.3.jar` to `pollen-forge-2.1.0.jar`
- Xaero's World Map `XaerosWorldMap_1.31.0_Forge_1.19.1.jar` to `XaerosWorldMap_1.32.0_Forge_1.19.1.jar`

# Genesis 0.1.3a
This update is a follow up update to the initial release of 0.1.3.
Highlights include: 
- Implementing that Backpacked recipe that I forgot to include in 0.1.2.
- A few tweaks with FTB Quests and adding more rewards.
- Cataclysm boss health adjustments.
- Added a new soundtrack from Cjbeards.
- WASW primary fire was somehow kept at a 40 tick cooldown. This has been reduced to 30 ticks.
- WASW alt fire cooldown has been reduced as well from 100 to 60

## 8.5.23
Just a few mod updates.

### Mod updates
- Create Crafts & Additions `createaddition-1.19.2-20230623a.jar` to `createaddition-1.19.2-1.0.0.jar`
- Grimoire of Gaia `GrimoireOfGaia4-1.19.2-3.0.0-alpha.5.jar` to `GrimoireOfGaia4-1.19.2-3.0.0-alpha.6.jar`

## 8.4.23
- Implemented the leather recipe for the backpack, this should have shipped with the initial 0.1.2-0.1.3 release and I'm sorry for it.
- Updated Apotheosis `Apotheosis-1.19.2-6.3.1.jar` to `Apotheosis-1.19.2-6.3.2.jar`
- Fixed some quest chapters showing up prematurely.
- Fixed a reward on a certain chocolate related quest.
- Removed the recipe override for the ender star mixing recipe.
  - This gives you the option to still use Ender Crafting.
- Adjusted Cataclysm boss health for the following bosses... The Harbinger will remain at 390 as he is extremely fast and can be challenging for new players.
  - Netherite Monstrosity 1.2x, now has 600 HP. Default amount is 500.
  - Ignis 1.2x, now has 540 HP. Default amount is 450.
  - Leviathan 2x, now has 800 HP. Default amount is 400.
    - Disabled block breaking for the Leviathan.

---

# Genesis 0.1.3

This might seem rushed in some areas, because it is. Just IRL issues is all. As a result, I may have to release follow-up updates for this so stay tuned...

This might not be considered a "minor" update, but I can assure you there are no world breaking changes. However, I can guarantee that you will have to change some sequenced assembly setups for the end goal if you got that far yet.

Quest trees have also been reworked, so there's that...

If your health is not correctly set after the addition of Spice of Life: Apply Pie Edition, you will need to respawn to reset your health. I deeply apologize if you are actually playing on Hardcore difficulty.

Also got rid of the pesky GUI Scale warning, but please do not tell me why certain interface elements are intersecting with each other when you change your GUI scale to be something else other than 2.

## 8.4.23

- Nights and Days have now been extended on this variant of Finality.
  - You can also now sleep during the day.
- Replaced Spice of Life: Carrot Edition with Spice of Life: Apple Pie Edition
  - This might break your health a little bit.
- Re-added the fancy animated singularity background.
- Certain befriended entities will no longer despawn.
- Changed Worldshaper recipe again, it now requires command blocks.
- Switched Menu Music audio channel to use the Jukebox Record channel.

### Mod updates
- KubeJS `kubejs-forge-1902.6.1-build.348.jar` to `kubejs-forge-1902.6.1-build.352.jar`

### Mod additions
- Added MemoryLeakFix by fxmorin
- Added fix GPU memory leak by someaddon

## 8.3.23

- Added "Command Blocks" which are now required for the end goal.
- Added a recipe to crush Apotheosis gemstones into dust without the use of an anvil by using Create's Millstones and Crushing Wheels.
- Removed the stonecutting for pressure plates recipes due to recipe conflicts. You will still be able to make pressure plates for cheap though!
- Going to be giving atmospheric and autumnity's logs the forge:stripped_logs tag so I don't need to make extra recipes.

### Mod updates

- KubeJS Create `kubejs-create-forge-1902.2.4-build.25.jar` to `kubejs-create-forge-1902.2.4-build.27.jar`
  - If my netherrack creation recipe was not working previously, it was because of the NBT tag not being read properly. This was fixed yesterday in build 25 but build 27 adds processingTime by default to millstones.
- Create Slice & Dice `sliceanddice-forge-2.2.1.jar` to `sliceanddice-forge-2.3.0.jar`
- Farmer's Delight `FarmersDelight-1.19.2-1.2.2.jar` to `FarmersDelight-1.19.2-1.2.3.jar`
- ModernFix `modernfix-forge-5.4.1+mc1.19.2.jar` to `modernfix-forge-5.5.1+mc1.19.2.jar`
  - Bow before embeddedt, destroyer of load times

## 8.2.23

- Ender Stars can now be made via a mixing recipe.
- Converted End Crystal creation to a shapeless recipe.
- Corrected Construction Wand recipes...
  - Their materials were actually swapped and I didn't catch this during my 3 AM modpack development moment.
- Added background for Create's quest page.
- ~~Gave the Wrench the ability to be used as a weapon.~~
  - Unfortunately, this is actually impossible. I could try making a custom Create Wrench using JavaClasses directly from Create with KubeJS's system but that will be for another time or just outright impossible.
- Added Singularity to the Display Names of natural and create material singularities. This somehow never got noticed by me for some reason.

Added new singularities...
- Red Sand (Sequenced Assembly)
  - Follows the same sequence as the sand singularity
- Soul Sand (Sequenced Assembly)
  - No comment, just look at it in-game.
- Soul Soil (Sequenced Assembly)
  - No comment, just look at it in-game.
- Tinted Glass (Sequenced Assembly)
  - Step 1: Deployer application
  - Step 2-4: Press
- Chocolate (Sequenced Assembly)
  - Step 1-4: Deployer application chocolate bar spam
  - Step 5: Filling with molten chocolate
  - Step 6: Press
- Builder's Tea
  - Step 1-4: Filling with Builder's Tea
  - Step 5-6: Pressing
- End Crystal
  - Step 1: Deployer Application
  - Step 2 and 3: Press

### Mod updates
- KubeJS Create `kubejs-create-forge-1902.2.4-build.23.jar` to `kubejs-create-forge-1902.2.4-build.25.jar`
  - Thank you Max for fixing the Create Potion fluid NBT issue <3
- Create Central Kitchen `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.9.b.jar` to `create_central_kitchen-1.19.2-for-create-0.5.1.c-1.3.9.c.jar`
- Gateways to Eternity `GatewaysToEternity-1.19.2-3.2.0.jar` to `GatewaysToEternity-1.19.2-3.2.2.jar`
- Grimoire of Gaia  `GrimoireOfGaia4-1.19.2-3.0.0-alpha.4.jar` to `GrimoireOfGaia4-1.19.2-3.0.0-alpha.5.jar`
- Placebo `Placebo-1.19.2-7.3.1.jar` to `Placebo-1.19.2-7.3.2.jar`

## 8.1.23

- Adding molten gold as a liquid.
- Adding molten netherite as a liquid.
- Continued quest reworking and additional hints.
- Added Epilogue quest chapter with a background.

### Mod updates

- Updated Text Animator from 1.1.1 to 1.1.2 
  - This fixes the issue with Create's Steam Boiler stat bars not having any color. Thanks Snownee!
- `chunkloaders-1.2.5-forge-mc1.19.jar` to `chunkloaders-1.2.6-forge-mc1.19.jar`
- `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.9.jar` to `create_central_kitchen-1.19.2-for-create-0.5.1.b-1.3.9.b.jar`
- `defaultoptions-forge-1.19-15.0.1.jar` to `defaultoptions-forge-1.19-15.0.2.jar`
- `L_Enders_Cataclysm-1.26-1.19.2.jar` to `L_Enders_Cataclysm-1.28-1.19.2.jar`
- `simple-rpc-forge-1.19.x-3.2.2.jar` to `simple-rpc-forge-1.19.x-3.2.3.jar`
- `upgradednetherite_items-1.19.2-4.1.0.1-release.jar` to `upgradednetherite_items-1.19.2-4.1.0.2-release.jar`

## 7.31.23

- Continued quest tree and progression reworks and beginning to implement proper quest reward loot tables.
- ~~Implemented a compat recipe for Autumnity and Atmospheric's stripped logs to be compatible with Create. I'm not going to bother with tags for this for now.~~
- Implemented a script to give players the quest book. Thanks squoshi <3
  - Also implemented a script to tell players about world lag on first load.
- Retextured End Portal frame, again, modified with my personal touches. Will adjust later.
- Consolidated the chapter pages for Graveyard, Cataclysm and Aquamirae.
- Text Animator bug report filed for removing the color Create's steam boiler stat bars.
  - https://github.com/Snownee/TextAnimator/issues/4

## 7.30.23

- Fixed Ender Dragon fight configs so that Ender Crystals spawn more slowly.
- Added tooltip to campfires to make it clear that they can regenerate player health.
- Added tooltips to the wooden and stone pickaxe to tell players that tools are now repairable.
- Reworked quest tree structure.
- Fixed the Enigmatic Legacy reward table not giving the Dormant Eye as a potential reward.

### Mod updates
- Updated Crafting Tweaks `craftingtweaks-forge-1.19.2-15.1.7.jar` to `craftingtweaks-forge-1.19.2-15.1.8.jar`
- Updated Create Enchantment Industry `create_enchantment_industry-1.19.2-for-create-0.5.1.b-1.2.5.b.jar` to `create_enchantment_industry-1.19.2-for-create-0.5.1.c-1.2.6.jar`
- Updated Cupboard `cupboard-1.19.2-1.4.jar` to `cupboard-1.19.2-1.5.jar`

### Mod additions
- Re-added Torchmaster
- Added Snow! Real Magic!
- Added Text Animator
- Added Chalk
- Added FTB XMod Compat
  - This fixes the lack of JEI compatibility.

### Mod removals
- Replaced Akashic Tome and Morph-o-Tool with Eccentric Tome. Enjoy unlimited power!
