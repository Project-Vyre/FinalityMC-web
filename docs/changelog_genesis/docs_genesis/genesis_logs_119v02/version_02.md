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

Apologies if the new changelog format is a bit unusual.

## Changes
- [9.21.2023] Added Goblin Trader trades for Raw Zinc to Zinc Ingot conversion.
- [9.21.2023] Reduced enchanting time for Enchanted Gravitite Blocks from 750 ticks to 500 ticks.
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
- [9.17.2023] Changed the Jade tooltip color from gold to yellow and slightly moved it. ~~I'm fully aware that Explorer's and Nature's Compass do conflict with it in UI terms, but Jade isn't always visible so it will remain on the top left corner.~~ Edit: Moved it to the center of the screen.
- [9.16.2023] Increased duration of Create Cafe effects significantly from 10 seconds to 5 minutes. This is not properly displayed on the tooltip of each drink, however. Please note that this is a serverconfig change, so you will need to copy the new config file from the defaultconfigs folder!
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
- [9.5-6.2023] Added Drowned, Hoglin and Husk Gateway pearls for unlimited copper and hogskin.
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

## Mod removals
- [9.16.2023] ~~Removed The Aether mod due to incompatibilities with Controlling, Catalogue and a few others. Will add back at a later date once things are more stable with it.~~ Edit: The Aether has been re-instated because of the newest patch fixing this issue.
- [9.16.2023] Removed BetterF3 due to incompatibility with The Aether.
  - They did release a fix for it for 1.19.4, in however. See the following links:
  - https://github.com/The-Aether-Team/The-Aether/issues/1693#issuecomment-1712915654
  - https://github.com/cominixo/BetterF3/issues/147

## Mod updates
- [9.23.2023] Updated EnderChests `enderchests-forge-1.19.0-1.10.1.03` to `enderchests-forge-1.19-1.10.7`
- [9.23.2023] Updated EnderTanks `endertanks-forge-1.19.0-1.12.1.04` to `endertanks-forge-1.19-1.12.8`
- [9.23.2023] Updated ShetiPhianCore `shetiphiancore-forge-1.19.0-3.11.3.04` to `shetiphiancore-forge-1.19-3.11.10`
- [9.22.2023] Updated Create Mechanical Extruder `create_mechanical_extruder-1.19.2-1.5.6.c-36.jar` to `create_mechanical_extruder-1.19.2-1.5.7.e-44`
- [9.21.2023] Updated YUNG's Better Ocean Monuments `YungsBetterOceanMonuments-1.19.2-Forge-2.1.0` to `YungsBetterOceanMonuments-1.19.2-Forge-2.1.1`
- [9.21.2023] Updated Embeddium `embeddium-0.1.6+mc1.19.2` to `embeddium-0.1.7+mc1.19.2`
- [9.21.2023] Updated Create `0.5.1c` to `0.5.1e`
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
- [9.7.2023] Edit: Do not update these mods to the latest version! ExtendedCrafting will delete all singularities, including its own.
- [9.5-6.2023] Updated KubeJS `kubejs-forge-1902.6.2-build.3` to `kubejs-forge-1902.6.2-build.5`~~
- [9.5-6.2023] Updated Clickable advancements `clickadv-1.19.2-3.1` to `clickadv-1.19.2-3.4`
- [9.5-6.2023] Updated Embeddium `embeddium-0.1.0+mc1.19.2` to `embeddium-0.1.2+mc1.19.2`
- [9.5-6.2023] Updated Create Slice & Dice `sliceanddice-forge-2.3.1` to `sliceanddice-forge-2.3.2`

## Mod additions
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
