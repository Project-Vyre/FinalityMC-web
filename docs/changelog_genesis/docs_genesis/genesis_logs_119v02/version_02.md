---
layout: minimal
title: 0.2.0 (1.19.2)
parent: Iteration 0.2
grand_parent: Finality Genesis Changelog
nav_order: 9
---

# Genesis 0.2.0
I was debating on if I should release this as Patch F or just go for 0.1.5 just because of the amount of changes and ended up settling on just labelling it as Patch F since it is a follow up to Patch E and the other patches that incrementally changed things. The next day... the update now has breaking changes in terms of recipes and world generation, so the version number has been bumped accordingly. As for why... it's just that a new structure has been added that replaces Minecraft's Jungle Temples.

- I am fully aware of z-fighting on many blocks, but this is currently a limitation of Sodium and is outside of my control. Feel free to disable Embeddium (fork of Sodium) if it bothers you too much.
- Please ignore the "Failed to parse recipe" messages related to Architect's Palette mod. This is an issue from the mod itself and not KubeJS. I have attempted to correct the 9 errored recipes many times over with JSON files AND KubeJS but the mod does simply does not care.

Apologies if the new changelog format is a bit unusual. Changed it again with RC3.

## Release Candidate 3 Patch A Changes
So I forgot about adding a way to get Lemon Seeds...

- Locked required resourcepacks
- [10.10.23] Re-versioned from 0.2.0-rc3.1 to 0.2.0-rc3a
- Added farmer trade to get lemon seeds
- Lemon seeds can now be acquired from breaking grass
- Added JEI and REI information on how to get lemon seeds
- Spawners now drop 3 Experience Nuggets when broken

### Updated mods
- [10.10.23] Updated ModernFix `modernfix-forge-5.8.0+mc1.19.2` to `modernfix-forge-5.8.1+mc1.19.2`
- [10.10.23] Updated ModernFix `modernfix-forge-5.7.4+mc1.19.2` to `modernfix-forge-5.8.0+mc1.19.2`

### Added mods
- Resource Pack Overrides

## Release Candidate 3 Changes
This update has breaking changes for Iron's Spells and Spellbooks users due to the mod author's rework. Don't say I warned you!
- Updated Forge loader version from `43.2.21` to `43.3.2`
- ~~Changed from release candidate to development / beta build.~~
- [10.9.2023] Changed from development build 3 back to release candidate 3.
- As of Embeddium 0.2 you can now disable Compact Vertex Format, which means you can disable the optimization that **causes Z-fighting and flickering**!
- Quark-3.4-414 is being used and has not presented any *immediate* problems so far from playtesting. If issues arise, downgrade to Quark-3.4.409.
- The duplication bug with Eccentric Tome has not yet been fixed, so I guess it will have to wait for either rc4 or just plain 0.2 release.

These changes should have been in Release Candidate 2 which was released a bit *too* early, but at least playtesting showed some things that I forgot to address. I **will** be taking my time on this. Full release will require a re-do of every draft texture and other uses for the shapes.

- [10.9.23] The rest is in GitHub commits...
- [10.8.23] Tempad cooldown reduced from 30 seconds to 10 seconds.
- [10.7.23] Finalized first iteration of retextures for GUI and the Monobank.
- [10.7.23] Added information for Aether's Obsidian armor pieces.
- [10.6.23] You can now craft Nether Wart Jam
- [10.6.23] Added lemons, literally. The texture is *not* final!
- [10.5.23] Increased maximum sandwich height limit from 32 to 256.
- [10.5.23] You can now craft Grimoire of Gaia's Golden Apple Pie
- [10.5.23] Restored the ability to find Buckets in all chest loot tables.
- [10.5.23] Changed pearl processing recipes to use Crushing to allow for more possibilities. Millstones don't visually support more than 4 different results in the JEI / REI interface.
- [10.1-2.23] Updated GUI hotbar and reticle texture, also some UI for Create's toolboxes for consistency.
- [10.1.23] Updated Final Scythe and Final Sword texture.
- [10.1.23] Making Netherite with Shimmer no longer requires superheating.
- [10.1.23] Removed the Laurel Cabinet due to missing recipe on the mod author's end.
- [10.1.23] Added tooltip for Supplementaries's Key in addition to making it fire-proof.
- [9.29.23] Added more Denied Result recipes to let players know that recipes have been changed.
- [9.28.23] Caupona Create integration... will have to be careful about this though.
- [9.28.23] Create-ified Mob Grinding Utils recipes.
- [9.28.23] Removed Incubation Fried egg recipe as it was causing issues in Fried Egg Create bulk smoking.
- [9.28.23] Iron Wands no longer cost C.U.E fluid, you can just use regular Iron Ingots now.

### RC3 Mod Updates
- [10.8.2023] Updated SuperMartin's Core Lib `1.1.14-forge-mc1.19.2` to `1.1.15-forge-mc1.19.2`
- [10.8.2023] Updated Open Parties and Claims `1.19.2-0.20.0` to `1.19.2-0.20.1`
- [10.8.2023] Updated Embeddium `0.1.15` to `0.2.0`
- [10.7.2023] Updated Create Enchantment Industry `0.5.1.e-1.2.7` to `0.5.1.e-1.2.7.b`
- [10.6.2023] Updated Quark `Quark-3.4-409` to `Quark-3.4-413` Roll back to `Quark-3.4-409` if you experience a crash on startup or other issues.
- [10.6.2023] Updated Neapolitan `neapolitan-1.19.2-4.0.2` to `neapolitan-1.19.2-4.1.0`
- [10.6.2023] Updated Create Enchantment Industry `create_enchantment_industry-1.19.2-for-create-0.5.1.e-1.2.6.c` to `create_enchantment_industry-1.19.2-for-create-0.5.1.e-1.2.7`
- [10.5.2023] Updated Simple Voice Chat `voicechat-forge-1.19.2-2.4.25` to `voicechat-forge-1.19.2-2.4.26`
- [10.5.2023] Updated Open Parties and Claims `open-parties-and-claims-forge-1.19.2-0.19.3` to `open-parties-and-claims-forge-1.19.2-0.20.0`
- [10.5.2023] Updated ImmediatelyFast `ImmediatelyFast-1.2.5+1.19.2` to `ImmediatelyFast-1.2.6+1.19.2`
- [10.5.2023] Updated Grimoire of Gaia `GrimoireOfGaia4-1.19.2-3.0.0-alpha.7` to `GrimoireOfGaia4-1.19.2-3.0.0-alpha.8`
- [10.5.2023] Updated FTB Ranks `ftb-ranks-forge-1902.1.15-build.77` to `ftb-ranks-forge-1902.1.16-build.98`
- [10.3.2023] Updated Iron's Spells and Spellbooks `irons_spellbooks-1.19.2-1.2.1` to `irons_spellbooks-1.19.2-2.0.1`
- [10.2.2023] Updated Embeddium `embeddium-0.1.14+mc1.19.2` to `embeddium-0.1.15+mc1.19.2` to resolve crash with Snow Real Magic
- [10.2.2023] Updated Snow! Real Magic! `SnowRealMagic-1.19.2-forge-6.5.3` to `SnowRealMagic-1.19.2-forge-6.5.4`
- [10.2.2023] Updated FTB Quests `ftb-quests-forge-1902.5.5-build.297` to `ftb-quests-forge-1902.5.6-build.304`
- [10.2.2023] Updated Embeddium `embeddium-0.1.12+mc1.19.2` to `embeddium-0.1.14+mc1.19.2`
- [10.1.2023] Updated SuperMartin642's Core Lib `supermartijn642corelib-1.1.13-forge-mc1.19.2` to `supermartijn642corelib-1.1.14-forge-mc1.19.2`
- [10.1.2023] Updated Cataclysm `L_Enders_Cataclysm-1.35 -1.19.2` to `L_Enders_Cataclysm-1.38 -1.19.2`
- [9.30.2023] Updated Embeddium `embeddium-0.1.11+mc1.19.2` to `embeddium-0.1.12+mc1.19.2`
- [9.30.2023] Updated Simple Discord RPC `simple-rpc-forge-1.19.x-3.2.3` to `SimpleRPC-forge-1.19-3.2.4`
- [9.30.2023] Updated Woodworks `woodworks-1.19.2-2.2.1` to `woodworks-1.19.2-2.2.2`
- [9.30.2023] Updated Savage & Ravage `savage_and_ravage-1.19.2-5.0.4` to `savage_and_ravage-1.19.2-5.0.5`
- [9.30.2023] Updated Personality `personality-1.19-3.0.1` to `personality-1.19.2-3.0.2`
- [9.30.2023] Updated Incubation `incubation-1.19-3.0.0` to `incubation-1.19.2-3.0.1`
- [9.30.2023] Updated Clayworks `clayworks-1.19.2-2.0.1` to `clayworks-1.19.2-2.1.0`
- [9.30.2023] Updated Buzzier Bees `buzzier_bees-1.19-5.0.1` to `buzzier_bees-1.19.2-5.0.1`
- [9.30.2023] Updated Boatload `boatload-1.19.2-4.2.1` to `boatload-1.19.2-4.2.2`
- [9.30.2023] Updated Autumnity `autumnity-1.19.2-4.0.0` to `autumnity-1.19.2-4.0.1`
- [9.30.2023] Updated Allurement `allurement-1.19.2-3.1.0` to `allurement-1.19.2-3.2.0`
- [9.30.2023] Updated Abnormals Delight `abnormals_delight-1.19.2-4.0.2` to `abnormals_delight-1.19.2-4.1.0`
- [9.29.2023] Updated SuperMartin's Core Lib `supermartijn642corelib-1.1.12-forge-mc1.19.2` to `supermartijn642corelib-1.1.13-forge-mc1.19.2`
- [9.29.2023] Updated Grimoire of Gaia `GrimoireOfGaia4-1.19.2-3.0.0-alpha.6` to `GrimoireOfGaia4-1.19.2-3.0.0-alpha.7`
- [9.29.2023] Updated Embeddium `embeddium-0.1.10+mc1.19.2` to `embeddium-0.1.11+mc1.19.2`
- [9.29.2023] Updated Chunk Loaders `chunkloaders-1.2.7-forge-mc1.19` to `chunkloaders-1.2.8-forge-mc1.19`
- [9.28.2023] Updated FTB Backups `ftbbackups2-forge-1.19.2-1.0.19` to `ftbbackups2-forge-1.19.2-1.0.22`
- [9.28.2023] Updated The Aether `aether-1.19.2-1.0.0-beta.1.1-forge` to `aether-1.19.2-1.0.0-beta.1.2-forge`

### RC3 Mod Removals
- [9.30.2023] Removed Allurement
- [9.30.2023] Removed Sound Physics Remastered due to lag spikes when around Create machinery, the worst example being a boiler with 18 Steam Engines on it. I know the Nether won't sound as hellish with the distorted moos echoing across the Nether, but the FPS lag was not worth it.

### RC3 Mod Additions
- [10.8.2023] Added Chunky
- [10.7.2023] Added Achievements Optimizer
- [10.7.2023] Added FTB Quests Optimizer
- [10.2.2023] Added Not Enough Recipe Book [NERB] to address TPS lag with recipes, thanks embeddedt and thanks to chasr for discovering this in a cursed scenario.
- [10.2.2023] Added ProbeJS even though it will be a while before I add my own ponder scenes.

---

## Release Candidate 2 Changes
Hello.
PLEASE
READ
THE
CHANGELOG, thank you.

Since **someone** was so eager to play the new update... Please report any issues you experience on the GitHub repository, thank you. There may be issues that I have not accounted for.
- [9.26.2023] Entropy Mechanism will now require 3 loops to craft, with weights adjusted.
- [9.26.2023] Fixed Eccentric Tome's tooltip. 758ada8
- [9.26.2023] Forcibly apply modpack resources to resolve seeing missing textures in some areas. adb6734
- [9.26.2023] Changed default keybind for disabling voice chat to `Not bound` to remove conflict with the keybind for sitting. https://github.com/Project-Vyre/Finality-Genesis/commit/7da3262141e77bb6c2dab3799acc8f81ddcf08d2#diff-c43fc778bde2aa1368f744a3fbdca45d8ea7a75f794f40fceab72dae0b439dffL93-R93
- [9.25.2023] Re-implemented Create Crafts and Additions bioethanol. https://github.com/Project-Vyre/Finality-Genesis/commit/7da3262141e77bb6c2dab3799acc8f81ddcf08d2#diff-56b6088c8858d7947b9bb27f4ee3bcdc07ced278b4e0be381fc983565554e3c5
- [9.25.2023] Liquid fuels in buckets from Create Crafts & Additions are now compatible with Blaze Burners. For example, Seed Oil and Bioethanol buckets. https://github.com/Project-Vyre/Finality-Genesis/commit/7da3262141e77bb6c2dab3799acc8f81ddcf08d2#diff-32d2795f04017334ba7d4b5c0e9f9b45fbb2ff60a796d84f7b8335dcfef9d0f1R524-R526
- [9.25.2023] Increased limit for the Boon of the Earth enchantment. 414ec90
- [9.24.2023] Added recipe for Lil' Wings Swallowtail paper wings to be able to converted into 3x string.
- [9.24.2023] Added Quartz block reversal recipe in case you have friends who compressed your Quartz into Quartz blocks. Thank me later.
- [9.24.2023] Added the Pixelated Enhanced Visuals resourcepack to remove the HD textures of Enhanced Visuals. Please note that you will need to update selected resourcepacks on your end.
- [9.24.2023] Added more blocks to the Blockrunner tag list.
- [9.24.2023] Added conversion recipe for BOP Rose Quartz and recipes for flesh blocks.
- [9.23.2023] Added forge:wither_bones to Architect's Palette Withered Bones
- [9.23.2023] Create Crafts and Additions now has uses for gold rods so it has been removed from the REI / JEI hide list.
- [9.23.2023] Changed maximum trade limit on Andesite Alloy from the Goblin Trader from 128 to 32.
- [9.21.2023] Added Goblin Trader trades for Raw Zinc to Zinc Ingot conversion.
- [9.21.2023] Reduced enchanting time for Enchanted Gravitite Blocks from 750 ticks to 500 ticks.

### RC2 Mod Updates
- [9.26.2023] Updated ESSENTIAL `essential_1-2-2-1_forge_1-19-2` to `essential_1-2-2-2_forge_1-19-2`
- [9.25.2023] Updated Embeddium `embeddium-0.1.8+mc1.19.2` to `embeddium-0.1.10+mc1.19.2`
- [9.25.2023] Updated Xaero's Minimap `Xaeros_Minimap_23.8.0_Forge_1.19.1` to `Xaeros_Minimap_23.8.2_Forge_1.19.1`
- [9.25.2023] Updated Simple Voice Chat `voicechat-forge-1.19.2-2.4.24` to `voicechat-forge-1.19.2-2.4.25`
- [9.25.2023] Updated ModernFix `modernfix-forge-5.7.2+mc1.19.2` to `modernfix-forge-5.7.4+mc1.19.2`
- [9.25.2023] Updated Create Crafts & Additions `createaddition-1.19.2-1.1.0` to `createaddition-1.19.2-1.1.1`
- [9.23.2023] Updated Create Central Kitchen `create_central_kitchen-1.19.2-for-create-0.5.1.c-1.3.9.c` to `create_central_kitchen-1.19.2-for-create-0.5.1.e-1.3.9.d`
- [9.23.2023] Updated Chalk `chalk-1.19.2-1.6.0` to `chalk-1.19.2-1.6.2`
- [9.23.2023] Updated Better Chunk Loading `betterchunkloading-1.19.2-2.1` to `betterchunkloading-1.19.2-2.2`
- [9.23.2023] Updated Chunk Sending `chunksending-1.19.2-2.6` to `chunksending-1.19.2-2.7`
- [9.23.2023] Updated Clickable Advancements `clickadv-1.19.2-3.4` to `clickadv-1.19.2-3.5`
- [9.23.2023] Updated Collective `collective-1.19.2-6.65` to `collective-1.19.2-6.66`
- [9.23.2023] Updated Connectivity `connectivity-1.19.2-4.5` to `connectivity-1.19.2-4.6`
- [9.23.2023] Updated Create Enchantment Industry `create_enchantment_industry-1.19.2-for-create-0.5.1.c-1.2.6.b` to `create_enchantment_industry-1.19.2-for-create-0.5.1.e-1.2.6.c`
- [9.23.2023] Updated Embeddium `embeddium-0.1.7+mc1.19.2` to `embeddium-0.1.8+mc1.19.2`
- [9.23.2023] Updated Cataclysm `L_Enders_Cataclysm-1.34 -1.19.2` to `L_Enders_Cataclysm-1.35 -1.19.2`
- [9.23.2023] Updated Server Performance - Smooth Chunk Save `smoothchunk-1.19.2-3.2` to `smoothchunk-1.19.2-3.4`
- [9.23.2023] Updated Structure Gel API `structure_gel-1.19.2-2.7.2` to `structure_gel-1.19.2-2.7.3`
- [9.23.2023] Updated EnderChests `enderchests-forge-1.19.0-1.10.1.03` to `enderchests-forge-1.19-1.10.7`
- [9.23.2023] Updated EnderTanks `endertanks-forge-1.19.0-1.12.1.04` to `endertanks-forge-1.19-1.12.8`
- [9.23.2023] Updated ShetiPhianCore `shetiphiancore-forge-1.19.0-3.11.3.04` to `shetiphiancore-forge-1.19-3.11.10`
- [9.22.2023] Updated Create Mechanical Extruder `create_mechanical_extruder-1.19.2-1.5.6.c-36.jar` to `create_mechanical_extruder-1.19.2-1.5.7.e-44`
- [9.21.2023] Updated YUNG's Better Ocean Monuments `YungsBetterOceanMonuments-1.19.2-Forge-2.1.0` to `YungsBetterOceanMonuments-1.19.2-Forge-2.1.1`
- [9.21.2023] Updated Embeddium `embeddium-0.1.6+mc1.19.2` to `embeddium-0.1.7+mc1.19.2`
- [9.21.2023] Updated Create `0.5.1c` to `0.5.1e`

### RC2 Removals
- [9.26.2023] Removed Seals
- [9.26.2023] Removed Raised

### RC2 Mod Additions
- [9.26.2023] Added Structure Essentials
- [9.26.2023] Added MmmMmmMmmMmm (Target Dummy)
- [9.23.2023] Added ImmediatelyFast

---

## Release Candidate 1 Changes
- [9.20.2023] Forgot to document moving Jade to the center of the screen directly under the reticle, oops.
- [9.20.2023] Removed BHC's Enchanted Golden Apple recipe.
- [9.20.2023] Deepslate now requires a Stone Pickaxe to mine.
- [9.20.2023] Significantly increased the level of certain enchantments and spells from Iron's Spells and Spellbooks. Please note that the changes made for Iron's Spells and Spellbooks will require updating the serverconfig file of your world / server world!
- [9.20.2023] Spells imbued into weapons no longer require mana. Please note that this is a serverconfig change, so you will need to copy the new config file from the defaultconfigs folder!
- [9.20.2023] With the addition of Tiny Skeletons, you can now expect more tiny horrors!
- [9.19.2023] Implemented modifications to durability of Aether's items.
- [9.17.2023] Implemented new trades for Goblin Traders...
  - Goblin Traders in the Overworld will convert 1x Andesite + 1x Iron Nugget with a 1:1 ratio like the Mechanical Mixer recipe.
  - Goblin Traders in the Nether can make brass for you if you still haven't found a Nether Fortress, but the trade is not guaranteed to show.
- [9.17.2023] Implemented Create integration for Grimoire of Gaia items.
- [9.17.2023] Added a tooltip for the Balloon Stand.
- [9.17.2023] Added a recipe for making Static Cloud Blocks. The power of science!
- [9.17.2023] Changed the Jade tooltip color from gold to yellow and slightly moved it. ~~I'm fully aware that Explorer's and Nature's Compass do conflict with it in UI terms, but Jade isn't always visible so it will remain on the top left corner.~~ Edit: Moved it to the center of the screen. f22b6bc
- [9.16.2023] Increased duration of Create Cafe effects significantly from 10 seconds to 5 minutes. This is not properly displayed on the tooltip of each drink, however. Please note that this is a serverconfig change, so you will need to copy the new config file from the defaultconfigs folder! 0dcbe21
- [9.16.2023] Supplementaries Quivers now hold 9 stacks of arrows instead of 6.
- [9.15.2023] Cosmic Cod spawning has been disabled entirely. They have been determined as the source of lag during the End Dragon boss fight as linked here: https://github.com/someaddons/SavageEnderDragon/issues/37 
- [9.15.2023] You now get struck by lightning if you *miss the point* of sandpaper.
- [9.15.2023] Flax and Flax Seeds are now given as a reward and no longer required to unlock the Age of Creation quest tree.
- [9.15.2023] Added the Capturing Enchanted Book to both Reforging Table quest nodes as rewards.
- [9.15.2023] Spawners now drop 8x Structure Void which can be used to recraft them. Originally, Structure Void was only obtainable from using a certain pickaxe on all 3 command blocks. Added a Tip to reflect this change.
- [9.15.2023] More keybind changes... Removed default keybind for Essential's screenshot manager so that it does not conflict with the Ring of Ender's ender chest keybind.
- [9.15.2023] Implemented shimmer and usages. Might rename it later to quantum entropy.
- [9.14.2023] Adjusted fluid requirements for recipes to use 1:1 ratio based on the new Tinker's Construct mB conversion.
- [9.14.2023] Changed Entropy Mechanism recipe to only 3 loops. Edit: Now 1 loop as of 9.15.2023 and salvage weight has been adjusted accordingly to make the result more unstable.
- [9.14.2023] Changed Ascendant Mechanism recipe to only 5 loops.
- [9.13.2023] Added the forward `/` as an item which will be needed for certain recipes.
- [9.13.2023] Implemented Shimmer fluid which will re-implement this but is intended for late end-game use.
- [9.12.2023] After further testing, the output rate of Netherite Scrap from Netherrack did not match expected probability.
  - This was because I was *still* reading the chance wrong. 0.002% when multiplied by 100 is `0.2%` which is **significantly** higher than it should have been the entire time. Percentage is now actually on par with Minecraft world generation and will no longer be changed from here.
- [9.12.2023] You can now compact Snow Blocks into Ice blocks.
- [9.12.2023] Lil Wings changes...
  - Grayling Wings can now actually ferment into Golden Carrots.
  - Cloudy Puff Wings can now be converted into Ghast Tears and not as a substitute that didn't show up in REI/JEI recipes.
  - White Fox Wings can now be converted into Ice blocks.
- [9.12.2023] Default keybind changes...
  - Changed default keybind for Supplementaries quiver from `v` to `,` to accomodate for Simple Voice Chat.
  - Also unbound Open/Close Curios Inventory from `g` to `Not bound`
  - Voice Chat Group keybind has been set from `g` to `Left Arrow` to accomodate for Wildfire's Gender Mod.
- [9.12.2023] Witches can now drop all ink types from Iron's Spells and Spellbooks.
- [9.11.2023] Finished the majority of shape textures... Last few checks and double checking.
- [9.11.2023] Made Lil' Wings Enderfly Net unbreakable.
- [9.10.2023] Increased Zinc Nugget drop rate from Creepers from 5% to 10%.
- [9.9.2023] Implemented Create's tooltip registry to items wherever applicable to avoid Rhino's concurrency error.
- [9.9.2023] Implemented rectangle shape components and colored variations... Definitely not looking forward to making the others.
- [9.8.2023] Witches now drop Lapis Lazuli, starting at 10%
- [9.8.2023] Blacklisted Create Enchantment Industry from being picked up by Carry On so you no longer pick up your blazes when trying to take the Enchanting Guide you gave them.
- [9.8.2023] Blacklisted Create Crafts & Additions from being picked up by Carry On.
- [9.7.2023] Made Echo of the Ship Graveyard renewable with Create's automation methods.
- [9.7.2023] Made Calcite renewable with Create's automation methods.
- [9.7.2023] Made the Abyssal Sacrifice able to be fully automated.
- [9.7.2023] Made the Abyssal Amethyst able to be fully autoted.
- [9.7.2023] Made all primordial mechanisms fire resistant.
- [9.7.2023] Fixed Structure Void not being visible in JEI.
- [9.6-7.2023] Added colors, shapes, numbers and hex code crafting recipes.
- [9.5-6.2023] Re-balanced creation methods of Condensed Universal Entropy.
  - Re-implemented the old method of acquiring Condensed Universal Entropy which involved no heating whatsoever.
  - Now provides an increased yield if superheated.
- [9.5-6.2023] Added quest nodes for Construction Wand related items. 962023
- [9.5-6.2023] Added Drowned, Hoglin and Husk Gateway pearls for unlimited copper and hogskin. cf5ea19
- [9.5-6.2023] Added text for Phantom Membranes being renewable by haunting rotten flesh.
- [9.5-6.2023] Added text for the Enigmatic Amulet and a certain ring for new players to understand their purposes.
- [9.5-6.2023] Corrected multiple Handcrafted recipes. I genuinely do not know why they decided to handicap Create with lower percentages when making wood boards.
  - Handcrafted recipes that ask for a chest now ask for any wooden chest type.
- [9.5-6.2023] Increased Monobank capacity from 8,192 items to 16,384 items.
- [9.5-6.2023] Blacklisted flies from spawning on all Ad Astra dimensions.
- [9.5-6.2023] Blacklisted Ad Astra's rockets from being picked up by Carry On to avoid awkwardly picking up your rocket when you are trying to give it fuel from a bucket.
- [9.5-6.2023] Added a recipe for making Ad Astra's oil infinitely renewable with Create automation.
- [9.5-6.2023] Added Tier 2 and Tier 3 Artifact reward tables.
- [9.5-6.2023] Added recipes for compressing HEA into Blocks of HEA and decompressing them into HEA ingots.

### RC1 Removals
- [9.16.2023] ~~Removed The Aether mod due to incompatibilities with Controlling, Catalogue and a few others. Will add back at a later date once things are more stable with it.~~ Edit: The Aether has been re-instated because of the newest patch fixing this issue.
- [9.16.2023] Removed BetterF3 due to incompatibility with The Aether.
  - They did release a fix for it for 1.19.4, in however. See the following links:
  - https://github.com/The-Aether-Team/The-Aether/issues/1693#issuecomment-1712915654
  - https://github.com/cominixo/BetterF3/issues/147

### RC1 Mod Updates
- [9.20.2023] Updated Placebo `Placebo-1.19.2-7.3.2` to `Placebo-1.19.2-7.3.3`
- [9.20.2023] Updated FTB Quests `ftb-quests-forge-1902.5.4-build.275` to `ftb-quests-forge-1902.5.5-build.297`
- [9.20.2023] Updated Embeddium `embeddium-0.1.5+mc1.19.2` to `embeddium-0.1.6+mc1.19.2`
- [9.20.2023] Updated Create Crafts & Additions `createaddition-1.19.2-1.0.0` to `createaddition-1.19.2-1.1.0`
- [9.19.2023] Updated MoreJS `morejs-forge-1.19.2-0.2.0` to `morejs-forge-1.19.2-0.2.1`
- [9.19.2023] Updated Essential `essential_1-2-2_forge_1-19-2` to `essential_1-2-2-1_forge_1-19-2`
- [9.19.2023] Updated Moonlight Lib `moonlight-1.19.2-2.2.44-forge` to `moonlight-1.19.2-2.2.46-forge`
- [9.18.2023] Updated Cataclysm `L_Enders_Cataclysm-1.29-1.19.2` to `L_Enders_Cataclysm-1.34 -1.19.2`
- [9.17.2023] Updated Embeddium `embeddium-0.1.4+mc1.19.2` to `embeddium-0.1.5+mc1.19.2`
- [9.15.2023] Updated Create Mechanical Extruder `create_mechanical_extruder-1.19.2-1.5.4.c-36` to `create_mechanical_extruder-1.19.2-1.5.5.c-36`
- [9.15.2023] Updated Redirectionor `redirectionor-1.19.2-3.3.2-forge-fix1` to Redirector `redirector-1.19.2-3.4.0-forge`
- [9.14.2023] Updated Balm `balm-forge-1.19.2-4.5.7` to `balm-forge-1.19.2-4.6.0`
- [9.14.2023] Updated Create Mechanical Extruder `create_mechanical_extruder-1.19.2-1.5.3.c36` to `create_mechanical_extruder-1.19.2-1.5.4.c-36`
- [9.13.2023] Updated `dragonfight-1.19.2-4.0` to `dragonfight-1.19.2-4.1`
- [9.13.2023] Updated `cupboard-1.19.2-1.9` to `cupboard-1.19.2-2.0`
- [9.13.2023] Updated Create Mechanical Extruder `create_mechanical_extruder-1.19.2-1.5.2.c-36` to `create_mechanical_extruder-1.19.2-1.5.3.c-36`
- [9.13.2023] Updated Xaero's World Map `XaerosWorldMap_1.34.0_Forge_1.19.1` to `XaerosWorldMap_1.34.1_Forge_1.19.1`
- [9.13.2023] Updated Xaero's Minimap `Xaeros_Minimap_23.7.0_Forge_1.19.1` to `Xaeros_Minimap_23.7.0_Forge_1.19.1`
- [9.12.2023] Updated Blueprint `blueprint-1.19.2-6.1.2` to `blueprint-1.19.2-6.2.0`
- [9.12.2023] Updated Server Performance - Smooth Chunk Save `smoothchunk-1.19.2-3.1` to `smoothchunk-1.19.2-3.2`
- [9.11.2023] Updated Artifacts `artifacts-1.19.2-5.0.3` to `artifacts-1.19.2-5.0.4`
- [9.9.2023] Updated Embeddium `embeddium-0.1.2+mc1.19.2` to `embeddium-0.1.4+mc1.19.2`
- [9.9.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.10` to `kubejs-forge-1902.6.2-build.15`
- [9.7.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.5` to `kubejs-forge-1902.6.2-build.10`
- [9.7.2023] ~~Updated Cucumber Library `Cucumber-1.19.2-6.0.7` to `Cucumber-1.19.2-6.0.8`~~
- [9.7.2023] ~~Updated Extended Crafting `ExtendedCrafting-1.19.2-5.1.7` to `ExtendedCrafting-1.19.2-5.1.8`~~
- [9.7.2023] ~~Updated Mystical Agriculture `MysticalAgriculture-1.19.2-6.0.11` to `MysticalAgriculture-1.19.2-6.0.12`~~
- [9.7.2023] Edit: Do not update `Cucumber Library`, `Extended Crafting`, and `Mystical Agriculture` to the latest version on 1.19.2! Extended Crafting will delete all singularities, including its own.
- [9.5-6.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.3` to `kubejs-forge-1902.6.2-build.5`~~
- [9.5-6.2023] Updated Clickable advancements `clickadv-1.19.2-3.1` to `clickadv-1.19.2-3.4`
- [9.5-6.2023] Updated Embeddium `embeddium-0.1.0+mc1.19.2` to `embeddium-0.1.2+mc1.19.2`
- [9.5-6.2023] Updated Create Slice & Dice `sliceanddice-forge-2.3.1` to `sliceanddice-forge-2.3.2`

### RC1 Mod Additions
- [9.20.2023] Added Paper Doll
- [9.20.2023] Added Loot Beams
- [9.20.2023] Added Armor Stand Shift Swap
- [9.20.2023] Also made up my mind and added Block Runner
- [9.20.2023] Finally made up my mind and added Portable Hole
- [9.20.2023] Added Tiny Skeletons
- [9.17.2023] Added MoreJS
- [9.16.2023] Added Skin Layers 3D
- [9.16.2023] Added The Aether Mod. Edit: Removed due to incompatibility and general stability issues. Edit 2: Re-instated after patch update.
- [9.15.2023] Added YUNG'S Better End
- [9.14.2023] Added Better Climbing
- [9.14.2023] Added Goblin Traders
- [9.14.2023] Added PlayerRevive
- [9.13.2023] Added LazyDFU. I was wondering why I never put it in the start...
- [9.13.2023] Added Chunk Sending
- [9.13.2023] Added Seals
  - Re-adding Better Advancements, but it does not register click locations properly when it is configured to use a smaller scale.
- [9.12.2023] Added Wildfire's Female Gender Mod
- [9.12.2023] Re-added AmbientSounds 5
- [9.12.2023] Re-added EnhancedVisuals
- [9.12.2023] Re-added Sound Physics Remastered which means...
- [9.12.2023] Re-added Simple Voice Chat with the re-introduction of Sound Physics Remastered.
- [9.12.2023] Added Macaw's Bridges
- [9.7.2023] Added YUNG's Better Jungle Temples
- [9.5-6.2023] Added Redirectionor for even more significant performance gains after testing. Launch time is now consistently even shorter than it used to be.
- [9.5-6.2023] Added Architect's Palette
- [9.5-6.2023] Added Easy Anvils which should have been in the modpack from the very beginning.
- [9.5-6.2023] Added Client Crafting to address server latency while hosting worlds via Essential and actual server instances.
- [9.5-6.2023] Added Gadgets Against Grind
