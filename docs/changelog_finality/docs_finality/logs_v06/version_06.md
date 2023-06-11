---
layout: default
title: Version 0.6.0b
grand_parent: Finality Changelog
parent: Iteration 0.6
has_children: true
nav_order: 2
---

# Version 0.6.0b

In Development
{: .label .label-yellow }

Game Breaking
{: .label .label-red}

Unfortunately, we're still stuck on Create 0.5.0i as much as I want to update the modpack to support Create 0.5.1b.

## Finality Core changes
- Added tight Create integration for Tinker's Construct.
- Changed Wither Storm related recipes to use Insanium Essence, not just corruption.
  - This should have been the original recipe.
- 

## Mod removals
- Removed FastSuite, Fast WorkBench and FastFurnace
- Removed Rotten Creatures
  - Log spam and the config file does not even work. Explanation for this issue can be found here: https://github.com/teamfusion/rottencreatures/pull/24
- Removed Hypothermic
  - Log spam
- Removed Stack Refill
  - Might be responsible for causing the item stacking issues with torches.

## Mod updates
- Updated Jade to `Jade-1.18.2-forge-5.3.0.jar` from `Jade-1.18.2-forge-5.2.6.jar`
- Updated ShetiPhianCore from `shetiphiancore-forge-1.18.2-3.10.14.jar` to `shetiphiancore-forge-1.18.2-3.10.16.jar`
  - Improved error logging in the texture provider override handler (system that processes 'assets/shetiphian/texture_remap.json')
  - Corrected 'texture_remap' entry 'grass_path' to 'dirt_path'
- Updated EnderChests
  - Texture Updates
  - Adjusted owner display to support formatting codes
- Updated EnderTanks
  - Texture Updates
  - Adjusted owner display to support formatting codes
- Updated Terralith from `Terralith_v2.2.3.jar` to `Terralith_1.18.2_v2.2.4.jar`
  - Now requires Cristel Lib, but now has integration with Terrablender by default.

---