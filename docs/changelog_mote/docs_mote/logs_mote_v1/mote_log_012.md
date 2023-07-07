---
layout: minimal
title: 0.1.2b (1.19.2)
parent: Iteration 0.1
grand_parent: Finality Mote Changelog
nav_order: 8
---

# Version 0.1.2b

This is not a game breaking update, so everything should be working normally.
Make sure Flywheel 0.6.8a is not installed separately and remove it if it is still in your mods folder!

## Config changes
- Reduced cooldown for the VASW from Cataclysm to 30 ticks, the same as the Void Forge hammer cooldown.
- Reduced Environment Evaluation Ray count from 32 to 8 due to lag from Sound Physics Remastered while near a large amount of active Create Steam Engines in open air.
  - Feel free to reduce this further in-game with your config by pressing the ` key which is located under your ESC button, usually.

## Mod updates
- Updated Create from `0.5.1b` to `0.5.1c` https://github.com/Creators-of-Create/Create/wiki/0.5.1c
  - Now using Flywheel 0.6.9
  - New translations from Crowdin
  - Added the entity type tag #create:ignore_seat
  - Added a config option to prevent hostile mobs from getting picked up by seats
  - Potato cannons can no longer plant crops on the side of farmland
  - Fixed Mechanical rollers consuming filter items despite not supporting them
  - Fixed brass tunnels not refunding previous filter items when changed
  - Fixed catalyst ingredients getting consumed in the basin
  - Fixed Smart observers not activated by funnels when facing up or down
  - Fixed custom sequenced assembly recipes conflicting when starting with a filling step
  - Fixed item slots of powered and unpowered redstone link models not matching in size
  - Fixed custom fluids not rendering fog underwater
  - Fixed improved diving helmet vision applied without it being equipped
  - Fixed incompatibility with Supplementaries
  - Fixed wood cutting recipe compatibility for Hexcasting (AndreAugustoAAQ)
  - Updates to the Bogey API (rabbitminers)
  - Separated config options for placing fluid blocks with Create (attackeight)
  - Optimisations to some of Create's vector math shortcuts (Timo van Veen)
  - Addons can now register backtank-esque air sources placed in any armor and curios slots (Michael C)
  - Addressed a number of memory leaks and server crashes
- Updated Polymorph from `polymorph-forge-0.46.3+1.19.2.jar` to `polymorph-forge-0.46.4+1.19.2.jar` https://www.curseforge.com/minecraft/mc-mods/polymorph/files/4629009
  - Fixed configuration sync attempts on empty packets
- Updated Open Parties and Claims from `open-parties-and-claims-forge-1.19.2-0.18.0.jar` to `open-parties-and-claims-forge-1.19.2-0.19.0.jar` https://www.curseforge.com/minecraft/mc-mods/open-parties-and-claims/files/4627631