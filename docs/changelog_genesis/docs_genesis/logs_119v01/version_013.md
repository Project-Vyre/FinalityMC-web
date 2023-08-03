---
layout: minimal
title: 0.1.2b (1.19.2)
parent: Iteration 0.1
grand_parent: Finality Genesis Changelog
nav_order: 7
---

# Genesis 0.1.3

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

### Mod additions
- Replaced Spice of Life: Carrot Edition with Spice of Life: Apple Edition

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
- Implemented a compat recipe for Autumnity and Atmospheric's stripped logs to be compatible with Create. I'm not going to bother with tags for this for now.
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
