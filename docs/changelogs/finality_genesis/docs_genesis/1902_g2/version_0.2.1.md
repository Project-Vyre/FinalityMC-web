---
layout: default
title: 0.2.1 (1.19.2)
parent: Iteration 0.2 - 1.19.2
grand_parent: Finality Genesis Changelog
nav_order: 8
---

# Finality Genesis 0.2.1 Changelogs

These are the changelogs for all 0.2.1 updates.

## Finality Genesis 0.2.1 Build 72

> [!IMPORTANT]
> This update will break existing automation lines due to the backport of 1.20.1 changes.

### Fixed

- [2024.06.16] Loading screen now automatically scales with the window size.
- [2024.06.04] Fixed duplication issues with silk touch pickaxes and ores. Sorry for those who were already abusing this.

### Added

- [2024.06.04] Added Malum compat with Ore Growth
- [2024.06.04] Added Ad Astra compat with Ore Growth

### Changed

- [2024.06.15] Backported 1.20.1 recipe changes without the removal of the Obsidian recipe that utilizes Mechanical Extruders.
- [2024.06.04] Ancient Debris no longer grows crystals.

#### 0.2.1-build.72 mod updates


##### 2024.06.15

- CraterLib `1.1.1` to `2.0.0`
- Create: Copycats+ `1.2.5` to `1.3.1`
- Elytra Slot `6.1.1` to `6.1.2`
- Essential Mod `1-3-2-5` to `1-3-2-6`
- FTB Quests `1902.5.8-build.345` to `1902.5.9-build.399`
- ImmediatelyFast `1.2.17` to `1.2.18`
- KubeJS `1902.6.2-build.69` to `1902.6.2-build.73`
- Lootr `0.4.27.71` to `0.4.28.72`
- Not Enough Animations `1.7.3` to `1.7.4`
- PolyLib `1900.0.3-build.100` to `1900.0.3-build.144`
- Simple Discord Link Bot `3.0.1` to `3.1.0`
- Simple Discord RPC `3.2.4` to `3.3.0`
- Simple Voice Chat `2.5.15` to `2.5.16`

##### 2024.06.05

- Create: Bitterballen `0.0.80` to `0.0.85`
- Lootr
- ModernFix `5.17.0` to `5.18.0`
- Xaero's Minimap `24.1.1` to `24.2.0`
- Xaero's World Map `1.38.4` to `1.38.8`

### Removed

---

## Finality Genesis 0.2.1 Build 64

> [!WARNING]
> This update has breaking changes for certain automated recipes. Apologies for any inconveniences that may be caused as a result.

- [2024.05.23] Updated FML from `43.3.9` to `43.3.13`

### Fixed

- [2024.05.23] Enabled auto-scaling for the main menu. This should hopefully fix weird edge cases where the menu returns back to a GUI scale of 4 even if it is not specified *anywhere*.
- [2024.05.21] Fixed Stripped Laurel Wood and Log blocks not being able to be turned into Create's casing blocks. This was due to TeamAbnormals not tagging them for some reason...

### Added

- [2024.05.31] You can now make Blaze Cake Bases with rice, potatoes, sugar and Cinder Flour instead of eggs.
- [2024.05.31] You can now make Zombie Heads by surrounding a Skeleton Skull with Rotten Flesh in a crafting table.
- [2024.05.31] You can now haunt Bone Blocks into Skeleton Skulls.
- [2024.05.31] Added recipes to convert Woodworks chests back into the vanilla chest.
- [2024.05.23] Added one trade for both librarians, cartographers and wandering traders.
- [2024.05.21] Added iridium blocks and items.

<details>

<summary>0.2.1-build.64 added mods</summary>

- [2024.05.31] ImmediatelyFast
  - Reinstated.
- [2024.05.31] Passable Foliage
- [2024.05.19] Mowzie's Mobs

</details>

### Changed

- [2024.05.31] Denied Result recipes for vanilla items and blocks have been removed due to instances of players having muscle memory while not looking at the output...
- [2024.05.31] Changed High Entropy Alloy Nugget recipe again. Now requires Null Matter, Iridium Nuggets and the Metallurgy Mechanism.
- [2024.05.31] Raw Zinc blocks can now be smelted in addition to being able to be processed via Bulk Blasting
- [2024.05.31] Buckets can only now be made with iron sheets once again.
- [2024.05.31] Ender Dragon now has a health and mob spawn modifier of 3.0.
- [2024.05.31] Restored Tinkers Construct Seared Bricks recipes.
- [2024.05.31] Set default Mipmap Levels to 0x. This change will not apply if you have changed your keybinds as it is a default option.
- [2024.05.31] Changed Tempad recipes, again.
- [2024.05.30] Removed the `create:wrench_pickup` tag from all Functional Storage blocks due to occasional mishaps players were encountering.
- [2024.05.23] Clarified the wording for the Final Tools regarding Apotheosis.
- [2024.05.23] Cthonic Gold rates have been increased for the Extruder. However, it now requires an actual block of Cthonic Gold to function. Wandering Traders can also now randomly trade Chtonic Gold Blocks.
- [2024.05.23] Certain blocks and items now require iridium to craft.
- [2024.05.23] Changed all command block recipes to utilize iridium and singularities.
- [2024.05.23] Changed High Entropy Alloy armor, tool and weapon recipes.
- [2024.05.22] Reduced Awakened Singularity Core stack size from 8 to 1.
- [2024.05.22] Reduced Dormant Singularity Core stack size from 16 to 1.
- [2024.05.21] EnderChests, EnderTanks & Tesseracts now require iridium.

<details>

<summary>0.2.1-build.64 updated mods</summary>

#### 2024.06.01

- Grimoire of Gaia `3.0.0-alpha.11` to `3.0.0-alpha.12`
- ImmediatelyFast `1.2.15` to `1.2.17`

#### 2024.05.30

- Artifacts `5.0.5` to `5.0.6`
- Collective `7.60` to `7.61`
- Essential `1-3-2-3` to `1-3-2-5`
- Iron's Spells 'n Spellbooks `3.1.6` to `3.1.7`
- ~~Lootr `0.4.27.71` to `0.4.28.72`~~
  - Rolled back to `0.4.27.71` due to Aether Mimic mishaps.

#### 2024.05.22

- Collective `7.57` to `7.60`
- Create: Power Loader `1.4.0` to `1.5.0`
- Iron's Spells 'n Spellbooks `3.1.5` to `3.1.6`
- L_Ender's Cataclysm `1.99.2-1.19.2-5-6-2024` to `1.99.2-1.19.2-5-16-2024`
- Neruina `1.3.0` to `2.0.0-beta.10`
- Simple Voice Chat `2.5.13` to `2.5.15`
- Tinkers Construct `3.8.2.32` to `3.8.3.39`
- Titanium `3.7.4-30` to `3.7.4-31`

</details>

### Removed

<details>

<summary>0.2.1-build.64 removed mods</summary>

#### 2024.05.23

- 3D Skin Layers
- Paper Doll

</details>

---

## Finality Genesis 0.2.1 Build 53

### Fixed

- [2024.05.14] Blacklisted all entities from the Iron's Spellbooks mod to preemptively prevent weird crashes in server environments.
- [2024.05.14] Fixed player names being censored on the server tab list. This is due to a conflict between ImmediatelyFast and Essential.
- [2024.05.10] Disabled `allowAsyncStreams` in an attempt to fix occasional recipe concurrency issues.

### Added

- [2024.05.16] Added quest nodes in The Shop page to utilize Gold Coins.
- [2024.05.15] Added completely custom music discs.
- [2024.05.14] Added new tooltips for some Grimoire of Gaia weapons.
- [2024.05.14] Added additional offerings for The Shop.
- [2024.05.14] Added new recipes for the End Crystal that don't utilize Ender Stars.
  - Also increased quantity of Ender Crystals made with Ender Stars from ExtendedCrafting.
- [2024.05.10] Added more Create tooltips for the following items / blocks.
  - Tuff
  - Diorite
  - Granite
  - Red Sand
  - Coal
  - Diamond

### Changed

- [2024.05.16] Changed background menu animation resolution to 720p and switched format from `.apng` to `.fma` for faster loading and less memory usage.
- [2024.05.16] The Beacon recipe now requires an End Crystal to craft instead of an Ender Star.
- [2024.05.14] Substantially increased durability of Grimoire of Gaia's weapons across the board.
  - Some Grimoire of Gaia weapons are also now unbreakable.
  - Some Grimoire of Gaia weapons have also had their damage increased substantially.
- [2024.05.14] Etherium Armor was not unbreakable for some reason, so that's now the case. In truth it was because I made a typo that went unnoticed for a very long time.
- [2024.05.14] Most, if not all, netherite armor and tools are now unbreakable. This is something I have been thinking about for a very long time.
- [2024.05.10] Modified some existing Create tooltips. The following items / blocks have been affected.
  - Andesite
  - Block of Coal
  - Block of Diamond

<details>

<summary>0.2.1-build.53 mod updates</summary>

#### 2024.05.14

- Create Enchantment Industry `0.5.1.f-1.2.9.d` to `0.5.1.f-1.2.9.e`
- Essential `1-3-2-2` to `1-3-2-3`
- Exposure `1.5.1` to `1.6.0`
- FancyMenu `3.2.2` to `3.2.3`
- Iron's Spells 'n Spellbooks `3.1.4` to `3.1.5`
- Mantle `1.10.24` to `1.10.36`
- Tinkers Construct `3.8.1.16` to `3.8.2.32`

#### 2024.05.10

- Create: Steam n' Rails `1.6.2` to `1.6.4`
- FTB XMod Compat `1.2.3` to `1.2.4`

</details>

### Removed

- [2024.05.14] Removed Tinker's Construct's vanilla Ender Crystal recipe, sorry about that.

<details>

<summary>0.2.1-build.53 mod removals</summary>

#### 2024.05.16

- Removed ImmediatelyFast

</details>

---

## Finality Genesis 0.2.1 Build 52

### Fixed

N/A

### Added

- [2024.05.08] Added a recipe for the Cryptic Eye. Utilizes Condensed Universal Entropy, 1x Block of Experience and one Ender Eye.

<details>

<summary>0.2.1-build.52 mod additions</summary>

#### 2024.05.08

- Lionfish API

</details>

### Changed

N/A

<details>

<summary>0.2.1-build.52 mod updates</summary>

#### 2024.05.08

- Apotheosis `6.5.0` to `6.5.1`
- Better chunk loading `2.5` to `4.2`
- Collective `7.56` to `7.57`
- Embeddium `0.3.14` to `0.3.18`
- EnderTanks `1.12.9` to `1.12.10`
- ESSENTIAL `1-3-1-3` to `1-3-2-2`
- FancyMenu `3.1.7` to `3.2.2`
- Grimoire of Gaia `3.0.0-alpha.10` to `3.0.0-alpha.11`
- ImmediatelyFast `1.2.12` to `1.2.14`
- Cataclysm `1.90 tongue fixed` to `1.99.2-5-6-2024`
- Loot Journal `2.1` to `3.0`

</details>

---

## Finality Genesis 0.2.1 Build 51

> [!IMPORTANT]
> This is an emergency hotfix.

### Fixed

- [2024.05.02] Fixed C.U.E recipe going missing from pressing Crying Obsidian in a Basin.
- [2024.05.01] Fixed Malum and Caupona's Walnut planks not being able to be utilized for chests. Additional compatibility for other mods may need to be manually written if I can't come up with a better solution.
- [2024.05.01] Fixed Tinker's Construct Beacon recipe still being present.
- [2024.05.01] Fixed blasting and smelting recipes going missing with the previous update.
- [2024.05.01] Fixed KubeJS bossDeathToast not defined error. This was due to script priority.

### Added

- [2024.05.01] Added a recipe for the Portable Hole utilizing Create's Mechanical Crafters.

### Changed

N/A

<details>

<summary>0.2.1-build.51 mod updates</summary>

#### 2024.05.02

- Collective `7.54` to `7.56`
- Simple Voice Chat `2.5.12` to `2.5.13`

</details>

---

## Finality Genesis 0.2.1 Build 50

The date format has now changed to ISO 8601 format which is YYYY-MM-DD. Sorry for this update taking forever to be released, but I was beginning to get discouraged.

> [!HIGHLIGHT]
> Tinker's Construct is now officially on 1.19.2! Have fun!

> [!IMPORTANT]
> Breaking update! Iron's Spells n' Spellbooks along with IDAS and Integrated Stronghold and Apotheosis have had some breaking changes. PLEASE BACK UP YOUR WORLDS!! I AM NOT RESPONSIBLE FOR ANY DATA LOSS THAT MAY INCUR FROM FAILING TO FOLLOW THESE INSTRUCTIONS!

> [!WARNING]
> If your game can't start up, delete the Zeta mod from the mods folder! It may be installed automatically due to CurseForge mixing up dependencies.

### Fixed

N/A

### Added

- [2024.05.01] Added a tooltip to Dirt for how to renew it.
- [2024.05.01] You can now make H.E.A Nuggets using **Chromatic Concrete Singularities** with 4 Chromatic Compound and 4 Stable Entropy Particles. Superheating is not required.
  - Will be moving away from using Extended Crafting in 1.20.1 and above.

<details>

<summary>0.2.1-build.50 mod additions</summary>

#### 2024.04.11

- Roadrunner
- Tinker's Construct

</details>

### Changed

- [2024.04.23] Tagging for FinalityJS related molten metals has been added for Tinker's Construct compatibility.
- [2024.04.18] All Tinker's Construct related fluids can no longer be bottomless.
- [2024.04.18] Certain Finality related fluids can now be bottomless. *May* retract this later.
- [2024.04.11] Tinker's Construct Grout can only be made with Create's Mixer.
- [2024.04.11] Updated Forge from `43.3.7` to `43.3.9`
- [2024.04.11] Updated IDAS and Integrated Stronghold datapacks due to breaking changes.

<details>

<summary>0.2.1-build.50 mod updates</summary>

#### 2024.05.01

- Collective `7.49` to `7.54`
- Create Enchantment Industry `0.5.1.f-1.2.9.c` to `0.5.1.f-1.2.9.d`
- Curios API `5.1.6.1` to `5.1.6.2`
- FancyMenu `3.1.5` to `3.1.7`
- ImmediatelyFast `1.2.11` to `1.2.12`
- Iron's Spells 'n Spellbooks `3.1.3` to `3.1.4`
- ModernFix `5.16.1` to `5.17.0`
- Mystical Agradditions `6.0.3` to `6.0.4`
- Not Enough Animations `1.7.1` to `1.7.3`
- Ore Growth `1.0.11` to `1.0.11a`
- Rechiseled `1.1.5c` to `1.1.6`
- Skin Layers 3D `1.6.2` to `1.6.4`
- The Aether `1.4.0` to `1.4.2`

#### 2024.04.23

- Collective `7.40` to `7.49`
- Create Enchantment Industry `0.5.1.f-1.2.9.b` to `0.5.1.f-1.2.9.c`
- Create: Bitterballen `0.0.70B` to `0.0.80`
- Create: Steam 'n Rails `1.6.1` to `1.6.2`
- Wares `1.2.7` to `1.2.8`

#### 2024.04.18

- Embeddium `0.3.12` to `0.3.14`
- FancyMenu `3.1.4` to `3.1.5`
- KubeJS `1902.6.2-build.63` to `1902.6.2-build.69`
- ModernFix `5.15.0` to `5.16.1`
- The Aether `1.3.1` to `1.4.0`
- Xaero's Minimap `24.0.3` to `24.1.1`
- Xaero's World Map `1.38.1` to `1.38.4`

#### 2024.04.11

- Abnormals Delight `4.1.1` to `4.1.2`
- Apotheosis `6.4.1` to `6.5.0`
- Atmospheric `5.1.0` to `5.1.2`
- Collective `7.36` to `7.40`
- Crabber's Delight `1.1.2` to `1.1.4`
- Create Central Kitchen `1.3.10` to `1.3.11.c`
- Create Enchantment Industry `1.2.8` to `1.2.9.b`
- Create: Bitterballen `0.0.65` to `0.0.70B`
- Create: Copycats+ `1.1.0-mc1.19.2-all` to `1.2.5`
- Create: Steam n' Rails `1.5.3` to `1.6.1`
- Cupboard `2.3` to `2.6`
- Embeddium `0.3.5` to `0.3.12`
- Essential `1-3-1` to `1-3-1-3`
- Exposure `1.4.0` to `1.5.1`
- FancyMenu `3.1.1` to `3.1.4`
- Gadgets Against Grind `2.1.0-build.18` to `2.1.0-build.22`
- Gateways to Eternity `3.2.2` to `3.2.3`
- ImmediatelyFast `1.2.10` to `1.2.11`
- Integrated API `1.2.7` to `1.2.8`
- Integrated Dungeons & Structures `1.7.6` to `1.7.7`
- Iron's Spells 'n Spellbooks `2.2.2` to `3.1.3`
- Lootr `0.4.25.67` to `0.4.27.71`
- ModernFix `5.13.0` to `5.15.0`
- Mystical Agriculture `6.0.13` to `6.0.14`
- Open Parties and Claims `0.20.4` to `0.22.0`
- Placebo `7.3.5` to `7.4.0`
- Polymorph `0.46.5` to `0.46.6`
- Savage Ender Dragon `4.1` to `4.4`
- Simple Voice Chat `2.5.6` to `2.5.12`
- The Aether `1.2.0` to `1.3.1`
- Wares `1.2.5` to `1.2.7`
- Xaero's Minimap `23.9.7` to `24.0.3`
- Xaero's World Map `1.37.8` to `1.38.1`

</details>

### Removed

Not applicable.

---

## Finality Genesis 0.2.1 Build 41

Changes for 0.2.1-build.41.

> [!IMPORTANT]
> I am aware that Iron's Spells n' Spellbooks has released a major update. Unfortunately, it's a bit too major and I might just leave it for the 1.20.1 port of Finality Genesis. It's time to move on.

### Fixed

- [2.22.24] Fixed Lapis Ore recipe requiring too many fluids. 
- [2.22.24] Fixed Snow Real Magic blocks being able to be picked up with Carry On. I discovered this bug myself by right clicking on one of Create's snowed on stairs.

### Added

- [3.3.24] Added a new tip that says something along the lines of "Automation is everything! Just DO IT!". You are welcome.
- [3.3.24] Added a recipe to deconstruct Architect's Palette Spool block back into its original components.
- [3.3.24] Added a recipe for Atmospheric's Grimwood and Yucca saplings.
- [2.29.24] Added uncrafting recipes for Architect's Palette Flint blocks.
- [2.26.24] Added a new recipe to get High Entropy Alloy nuggets from Ultimate Nuggets to make it a 1:1 ratio.
- [2.23.24] Added a Mechanical Crafting recipe for the Ultimate Singularity due to the Ultimate Extended Crafting table exhibiting unusual behavior...

<details>

<summary>0.2.1-build.41 mod additions</summary>

- Tesseract

</details>

### Changed

- [3.3.24] Singularity gambling now has the percentages visible.
- [2.26.24] The sequenced assembly recipe that doesn't use Awakened Singularity Cores for concrete singularities now has a chance to fail and refund 9x concrete powder.
- [2.26.24] Changed Better Beacons amplifier values for H.E.A blocks to 128 and H.E.A connecting blocks to 254.
- [2.26.24] Changed the current H.E.A nugget recipe that uses Ultimate Catalysts to output H.E.A blocks instead.
- [2.26.24] Increased result quantity from 1x to 9x for singularities made with mechanical crafters.
- [2.22.24] C.U.E is no longer required to make Lapis Lazuli ore.
- [2.22.24] Changed connection behaviour on the connecting variant of blocks of H.E.A to create a border when the block face is covered by the same block. Shout out to SuperMartijn642! See commit: https://github.com/SuperMartijn642/Fusion/commit/3d31859a93818ace2fec01307fc8f06281cdff79

<details>

<summary>0.2.1-build.41 mod updates</summary>

#### 3.3.24

- Abnormals Delight `4.1.0` to `4.1.1`
- Almost Unified `0.8.0` to `0.8.1`
- Atmospheric `5.0.0` to `5.1.0`
- Create Central Kitchen `0.5.1.f-1.3.9.g` to `0.5.1.f-1.3.10`
- Exposure `1.3.1` to `1.4.0`
- Supplementaries `2.4.20-2-17-2024` to `2.4.20-3.2.24` 
- Titanium `3.7.4-28` to `3.7.4-30` 

####  2.28.24

- Archaelogy API `1.0.0-12-31-2023` to `1.0.0-2-27-24`
- Carry On `2.1.1.22` to `2.1.2.23`
- Essential `1-3-0-6` to `1-3-1`
- FancyMenu `3.1.0` to `3.1.1`

#### 2.26.24

- Architectury API `6.5.90` to `6.6.92`
- Collective `7.32` to `7.36`
- Create Enchantment Industry `0.5.1.f-1.2.7.f` to `0.5.1.f-1.2.8`
- Embeddium `0.3.3` to `0.3.5`
- Grimoire of Gaia `3.0.0-alpha.9` to `3.0.0-alpha.10`
- Mob Grinding Utils `0.4.50` to `0.4.52`
- Simple Voice Chat `2.5.5` to `2.5.6`
- Zume `0.14.0` to `0.15.0`

#### 2.22.24

- Almost Unified `0.7.2` to `0.8.0`
- AttributeFix `17.2.7` to `17.2.8`
- Collective `7.30` to `7.32`
- Fusion (Connected Textures) `1.1.0c` to `1.1.1`
- Simple Voice Chat `2.5.4` to `2.5.5`

</details>

---

## Finality Genesis 0.2.1 Build 40

### Fixed

- [2.16.24] Fixed Quartz singularity salvage results. I am questioning myself why I had `minecraft:quartz_ore` and `minecraft:deepslate_quartz_ore`

### Added

- [2.20.24] Added a deconstruction recipe for Iron's Spellbooks Arcane Anvil.
- [2.19.24] Added an undo recipe for converting Smooth Stone back into Stone.
- [2.19.24] Added undo recipes for converting cobbled deepslate and cobblestone into their natural alternatives.
- [2.16.24] Added a recipe for making Budding Amethyst.
- [2.16.24] Added new deploying recipes to make Refined Radiance and Shadow Steel easier without having to throw Chromatic Compound items into the world.
- [2.16.24] Added a connected texture for blocks of H.E.A.
- [2.16.24] Added Deploying recipes for making Refined Radiance and Shadow Steel.
- [2.16.24] Added an emptying recipe to extract C.U.E from Crying Obsidian. Not even ashes will remain, however.
- [2.16.24] Added a filling recipe to use C.U.O to make Budding Amethyst.
- [2.16.24] Added a compacting recipe for Tuff to get useful Create materials when used with Shimmer.
- [2.16.24] Added a new recipe for making Create: Enchantment Industry's Experience Rotor with a Create Propeller and Experience Nugget.
- [2.16.24] Added a new recipe for all Concrete Singularities so that they are able to use Awakened Singularity Cores instead.
- [2.16.24] Added Quark's sorting button to Backpacked's GUI. No longer will you have to sort the inventory manually.

<details>

<summary>0.2.1-build.40 mod additions</summary>

#### 2.19.24

- Create: CopyCats+

#### 2.16.24

- Fusion
- SuperMartijn642's Core Lib
  - ...and Config Lib
- Ore Growth
- Rechiseled
- Rechiseled: Create

</details>

### Changed

- [2.19.24] Experience Nuggets can now be used to make Create Enchantment Industry's Experience Rotor for easier conversion.
- [2.19.24] EnderTanks and EnderChests can also now be made with Ender Pearl Singularities.
- [2.19.24] Cobbled Deepslate now requires at least a Stone Pickaxe to mine for consistency.
- [2.16.24] Superheated compacting with Crying Obsidian now provides 1000 mB of C.U.E
- [2.16.24] Entropy Coins are now worth 256 Netherite Coins.
- [2.16.24] Reduced Sequenced Assembly number of loops for singularities across the board and in other recipes where applicable.
- [2.16.24] Changed certain upgrade recipes from Functional Storage to utilize more of Create's materials.
- [2.9.24] Eversor gems no longer drop from all entities and now only drop by chance from bosses. For now the Warden and the Lich boss from the Graveyard mod are the only entities that can drop the gem naturally. Other bosses will be added at a later date.
- [2.7.24] ~~Added damage scaling overrides to specific weapons.~~ Edit: This is currently a work in progress and will not be implemented until it has been fully fleshed out.
- [2.6.24] Adjusted scaling and attributes of both the Eversor and Acuti Ora gems, they were unfortunately **too** powerful and I was overconfident in their rarity.

<details>

<summary>0.2.1-build.40 mod updates</summary>

#### 2.20.24

- KubeJS `1902.6.2-build.61` to `1902.6.2-build.63`

#### 2.19.24

- Botarium `1.9.1` to `1.9.2`
- Drippy Loading Screen `3.0.0` to `3.0.1`
- FancyMenu `3.0.6` to `3.1.0`
- FTB Essentials `1902.3.4-build.109` to `102.3.5-build.120`
- KubeJS `1902.6.2-build.59` to `1902.6.2-build.61`
- Supplementaries `2.4.19` to `2.4.20`

#### 2.16.24

- Embeddium `0.3.0` to `0.3.3`
- Simple Voice Chat `2.5.3` to `2.5.4`

#### 2.15.24

- JEI `11.6.0.1018` to `11.6.0.1019`

#### 2.13.24

- Artifacts `5.0.4` to `5.0.5`
- Simple Voice Chat `2.5.2` to `2.5.3`
- Zume `0.13.2` to `0.14.0`

#### 2.11.24

- Create Crafts & Additions `1.2.2` to `1.2.3`
- Essential `1-3-0-4` to `1-3-0-6`

#### 2.10.24

- Not Enough Animations `1.7.0` to `1.7.1`

#### 2.9.24

- Essential `1-3-0-3` to `1-3-0-4`
- Exposure `1.3.0` t0 `1.3.1`
- Simple Voice Chat `2.5.1` to `2.5.2`

#### 2.7.24

- KubeJS `1902.6.2-build.54` to `1902.6.2-build.59`

#### 2.6.24

- Placebo `7.3.4` to `7.3.5`

</details>

---

## Finality Genesis 0.2.1 Build 39

> [!IMPORTANT]
> This is technically not a large update, though minor breaking changes have been made.

> [!NOTE]
> The changelog below may be missing some changes due to me forgetting to write into the changelog after pushing commits to the repository. Apologies for the inconvenience!

A few highlights of this update:

- Steam n' Rails has been added.
- Contacted snownee to fix a bug with Skill Slots
- Added Zume
  - Thank you to [@nolij, (the creator of the most over-engineered zoom mod)](https://github.com/Nolij) for having multiple aneurysms trying to fix the config issue :dogkek:
- All custom ExtendedCrafting singularities have been replaced with KubeJS singularities.

> [!WARNING]
> Some recipes have been removed to avoid recipe conflicts and you may have to adjust your Create factories accordingly. In addition, certain mods have also been removed so existing worlds may be affected by the loss of Advanced Mining Dimension. Server configs have also been updated due to mod updates, so you will have to change them accordingly. All custom ExtendedCrafting singularities have been replaced with KubeJS singularities though the Precision Mechanism Singularity recipe has changed. The recipe for Umbral Mechanisms has also changed to no longer require items from Aquamirae and Cataclysm.

### Added

- [2.4.24] Added sequenced assembly recipes for all singularities that are currently only crafted with Create's Mechanical Crafters.
- [2.2.24] Added a recipe for using Walnut Oil and extracting it from Caupona's walnuts because I apparently forgot to do so months ago.
- [2.1.24] Added a recipe for the Ender Drawer Linking Guide in case you need it as a physical item
- [1.31.24] Stable Entropy Particles can now be used to make a spawner ignore conditions if you don't want to keep summoning the Ender Dragon
- [1.31.24] Added an item to help explain how to use Ender Drawers due to the drawers themselves not taking Create tooltips that well when a frequency is present. It looks cursed.
- [1.31.24] Added a texture for the Manifestation of Infinity item from Apotheosis.
- [1.31.24] Added the Acuti Ora gem to pair with the Eversor gem. The Acuti Ora gem is intended to obliterate armor and protection while the Eversor gem will now be for dealing damage.
- [1.31.24] Added new Create tooltips for Aether's items.
- [1.29.24] Added a recipe for making the Overseer's Tempad due to great difficulty finding it in The End.
- [1.26.24] Added Wandering Trader trade for obtaining Chorus Fruit.
- [1.26.24] Added a recipe for making End Stone without having to go to the End.
- [1.23.24] Added summoning recipes for Lil Wings butterflies for those encountering great difficulty finding them naturally.
- [1.21.24] Added a new item called the Deconstructor.
- [1.21.24] Added recipes for making arcane inks for Iron's Spells n' Spellbooks via Create methods instead of relying on vanilla Minecraft Witches with a modified loot pool.
- [1.20.24] Added a time acceleration recipe for Farmer's Delight Organic Compost to Rich Soil conversion with Item Application.
- [1.20.24] Soul Soil can now be Bulk Washed for Glowstone Dust to eliminate the need for Witch Farms.
  - Fun fact: In an older update you were previously able to acquire Glowstone Dust from washing Soul Sand.
- [1.18.24] Added Compressed Netherrack, Double Compressed Netherrack and Triple Compressed Netherrack.
  - Also added recipes that process these compressed variations of Netherrack.
- [1.17.24] Added an Enchanted Golden Apple recipe...
- [1.14.24] Added Create tooltips for both redstone and glowstone.
- [1.14.24] Added effect description and Create tooltips for Mutant More due to JEI being unable to display the brewing recipe. REI users are unaffected as it always works.
- [1.14.24] Added the `forge:stone` item tag to more stone blocks. For example, you can now use Smooth Basalt in creating Create's Crushing Wheels. Previously you were not able to and would be forced to use alternative blocks.
- [1.14.24] Added a recipe for upgrading Mystical Agriculture's growth accelerator blocks.
- [1.7.24] Porkchops can now be haunted into hoglin loins from Nether's Delight.
- [1.7.24] The Create Wrench now has additional power. The rest of the tagging can be seen in the commit history.
  - Minecraft's Oak Ladder can now be picked up
  - Wooden plank slabs and stairs can now be picked up if the mod tagged them correctly.
  - ExtendedCrafting's manual and auto crafting tables can now be picked up. Other related blocks can also be picked up.
  - The Crafter can now be picked up
  - Mystical Agriculture altars and pedestals can now be picked up
  - etc.
- [1.7.24] Added a new recipe for Tree Fertilizer that makes use of Enigmatic Legacy's Essence of Raging Life.
- [1.6.24] Apparently Minecraft's Oak Ladders were never tagged with Create's Wrench Pickup block tag, so now they are tagged.
- [1.4.24] Added tooltips for the Crafting Automat Crafter and Skill Slots Slot Unlock item.

<details>

<summary>0.2.1-build.39 mod additions</summary>

- [1.30.24] Added Almost Unified
- [1.22.24] Added Zume
  - Thank you to [@nolij, (the creator of the most over-engineered zoom mod)](https://github.com/Nolij) for having multiple aneurysms trying to fix the config issue :dogkek:
- ~~[1.14.24] Added Lychee~~
  - Edit: Mod has been removed.
- [1.14.24] Added Summoning Rituals
- [1.14.24] Added What Are They Up To? (Watut)
- ~~[1.12.24] Added Create: Interiors~~
  - Edit: Mod has been removed.
- ~~[1.12.24] Added Create Jetpack~~
  - Edit: Mod has been removed.
- ~~[1.10.24] Added Create: Bells & Whistles~~
  - Edit: Mod has been removed.
- [1.10.24] Added Steam n' Rails
- [1.7.24] Added Just Enough Beacons Reforged
- [1.7.24] Added CERBON's Better Beacons
- [1.7.24] Added Finality Core, the modpack's core mod.
- [1.4.24] Added The HeadHunter
  - As an added bonus, he drops Unstable Entropy Particles.

</details>

### Changed

- [2.5.24] Changed the recipe for the Mechanical Extruder.
- [2.5.24] Adjusted chances and bonk requirement for Malum's Cthonic gold.
- [2.2.24] Changed recipe for the Umbral Mechanism to no longer require items from Cataclysm and Aquamirae.
- [2.1.24] Eversor and Acuti Ora gems now multiply _both_ the base and total.
- [1.31.24] Command Blocks now generate 1 Block of H.E.A instead of Netherite Blocks. Please note that you still can't extract items automatically from them via Hoppers or Chutes.
- [1.31.24] Adjusted attributes for the Eversor and Acuti Ora gem.
- [1.30.24] Alex's Mobs seagulls can no longer steal the Lunch Bag, Lunch Box and the Golden Lunch Box from your hotbar.
- [1.28.24] Changed Precision Mechanism Singularity recipe to no longer require Redstone Nuggets from ExtendedCrafting.
- [1.25.24] Shimmer recipe no longer requires super-heating.
- [1.24.24] You can now salt your Eternal Steak and Everlasting Beef for additional saturation. You're welcome!
- [1.21.24] Changed some recipes related to Iron's Spells n' Spellbooks recipes.
  - Cinder Essence is now renewable without having to kill Ancient Knights
  - Arcane Essence is now renewable without having to kill Iron's Spells n' Spellbooks bosses.
- [1.20.24] Echo Shards can now convert Warped Roots into Sculk Sensors as an Item Application recipe.
- [1.20.24] Updated Slightly Improved Font from `1.0.0` to `1.1.3`
- [1.20.24] Changed Gold Essence to Gold Ingot recipe to be in-line with the other essence to ingot recipes.
- [1.18.24] Updated Forge `43.3.2` to `43.3.7`
- ~~[1.14.24] Gave Create's Wrench the ability to damage entities by percentage of their max remaining HP. Totally not a questionable decision on my part. 🤣~~
  - This was a funny joke, but was never going to be actually implemented.
- [1.7.24] `/rtp` is now disabled by default for new server packs.
- [1.7.24] Added the correct step for making Create Cafe's pressed oreo so it doesn't require a basin. WHY does it require a basin in the first place? Do you need a bowl to flatten out dough? USE YOUR HANDS, ROLLING PIN OR SOMETHING!
- [1.6.24] It appears that Cataclysm's Ignitium Armor now provides fire resistance as intended, so the tooltip has been adjusted accordingly.
- [1.4.24] Separated charcoal recipe into two different ones. One for moss blocks and one for charcoal + leaves.
- [1.4.24] Blue Ice Singularity now empties into 500 mB of C.U.O and leaves behind an Awakened Singularity Core instead of 250 mB with a 25% chance of being re-usable. This is due to Create not showing that it is a chanced output.

<details>

<summary>0.2.1-build.39 mod updates</summary>

#### 2.6.24

- Architectury API `6.5.85` to `6.5.90`
- Finality Core `1.3.1` to `1.3.2`

#### 2.5.24

- FancyMenu `3.0.5` to `3.0.6`
- Lootr `0.4.25.65` to `0.4.25.67`
- Zume `0.13.0` to `0.13.2`

#### 2.4.24

- Exposure `1.2.2` to `1.3.0`
- FancyMenu `3.0.4` to `3.0.5`
- MoreJS `0.2.1` to `0.3.0`

#### 2.2.24

- ImmediatelyFast `1.2.8` to `1.2.10`
- ModernFix `0.12.0` to `0.13.0`

#### 2.1.30

- Essential `1-3-0-2` to `1-3-0-3`
- Finality Core `1.3.0` to `1.3.1`
- Supplementaries `2.4.18` to `2.4.19`
- Xaero's World Map `1.37.7` to `1.37.8`

#### 1.30.24

- Cataclysm `1.90` to `1.90-tongue-fix` don't question it, that's just the jar file name.
- Create Crafts & Additions `1.2.1` to `1.2.2`
- Etched `2.3.1` to `2.3.2`
- FancyMenu `3.0.2` to `3.0.4`
- Simple Voice Chat `2.4.32` to `2.5.1`
- Supplementaries `2.4.16` to `2.4.18`

#### 1.29.24

- Curios API `5.1.5.0` to `5.1.6.1`
- Embeddium `0.2.18` to `0.3.0`
- The Aether `1.1.0` to `1.2.0`

#### 1.28.24

- Cataclysm `1.89` to `1.90`
- Create: Power Loader `1.3.3` to `1.4.0`
- Cupboard `2.1` to `2.3`
- FancyMenu `3.0.0` to `3.0.2`
- Gadgets Against Grind `2.0.0-build.16` to `2.1.0-build.18`
- Iron's Spells 'n Spellbooks `2.2.1` to `2.2.2`
- Kiwi `8.3.5` to `8.3.6`
- KubeJS `1902.6.2-build.50` to `1902.6.2-build.54`
- Xaero's Minimap `23.9.3` to `23.9.7`
- Xaero's World Map `1.37.2` to `1.37.7`
- Zume `0.12.0` to `0.12.1`

#### 1.26.24

- Sooty Chimneys `1.2.0` to `1.2.1`
- FTB Quests `1902.5.7-build.326` to `1902.5.8-build.345`

#### 1.25.24

- Drippy Loading Screen `2.14.13` to `3.0.0`
- FancyMenu `2.2.2` to `3.0.0`
- Lootr `0.4.24.64` to `0.4.25.65`

#### 1.22.24

- Botarium `1.9.0` to `1.9.1`
- Embeddium++ `1.2.2` to `1.2.3`
- Farmer's Delight `1.2.3` to `1.2.4`

#### 1.21.24

- Curios API `5.1.4.4` to `5.1.5.0`

#### 1.20.24

- Botarium `1.8.2` to `1.9.0`
- Just Enough Beacons Reforged `1.1.1` to `1.1.2`

#### 1.17.24

- Cataclysm `1.88` to `1.89`
- Create: Bitterballen `0.0.61` to `0.0.65`

#### 1.16.24

- Architect's Palette `1.3.4` to `1.3.5`
- Cataclysm `1.87` to `1.88`
- Embeddium `0.2.16` to `0.2.18`
- KubeJS `1902.6.2-build.45` to `1902.6.2-build.50`

#### 1.14.24

- Cataclysm `1.86` to `1.87`
- Cultural Delights `0.15.4` to `0.15.5`
- FancyMenu `2.14.9` to `2.14.13`
- Konkrete `1.6.1` to `1.8.0`

#### 1.13.24

- The Aether `1.0.0` to `1.1.0`

#### 1.12.24

- Create: Power Loader `1.3.2` to `1.3.3`

#### 1.11.24

- Embeddium++ `1.2.0` to `1.2.2`
  - Embeddium++ `1.2.1` has an issue with rendering text behind the chat background. **DO NOT USE**
- ModernFix `5.11.1` to `5.12.0`

#### 1.10.24

- Grimoire of Gaia `3.0.0-alpha.8` to `3.0.0-alpha.9`
- Skill Slots `1.0.5` to `1.0.6`

#### 1.9.24

- Embeddium++ ` 1.1.0` to `1.2.0`
- Iron's Spells n' Spellbooks `2.2.0` to `2.2.1`
- Skin Layers 3D ` 1.6.1` to `1.6.2`
- Supplementaries ` 2.4.15` to `2.4.16`

#### 1.7.24

- Enchantment Descriptions `13.0.8` to `13.0.20`

#### 1.6.24

- Create: Power Loader `1.3.1` to `1.3.2`
- NetJS `1.1.1` to `1.2.0`

#### 1.5.24

- Create: Power Loader `1.3.0` to `1.3.1`

#### 1.4.24

- Create: Power Loader `1.2.4` to `1.3.0`
- Not Enough Animations `1.6.2` to `1.7.0`

</details>

### Fixed

- [2.5.24] Create's Mechanical Saw compat with Quark's logs and wood blocks was missing, that should be fixed now.
- [2.1.24] Poison Gems were removed from Iron's Spellbooks in a mod update sooo references to them in scripts have also been removed
- [1.26.24] You now get burned when touching molten metals like you are supposed to.
- [1.14.24] Fixed my own Chemical X recipes not loading... they were set to be ignored for some reason. I must have forgotten 🥹
  - Also took the time to re-implement the recipes so that they are visible via JEI. You are welcome.
- [1.14.24] Fixed Aether's swet balls not being usable as a slime ball ingredient in crafting recipes by adding the tag to it.
- [1.14.24] Fixed all potions being missing in both REI and JEI. This was a mistake on my part as they were _all_ being hidden.
- [1.10.24] Skill Slots bug has been resolved. See: https://github.com/Snownee/SkillSlots/issues/3
- [1.9.24] Fixed Unstable Entropy Particle recipe having issues with the Netherite Block and Brass Block melting.
- [1.8.24] Fixed freezing with JEI by disabling low memory search. See commit 990891e
- [1.8.24] Fixed Create Cafe's use of carcinogenic substances in making syrups for drinks.
- [1.7.24] Attempted fix for NBT matching for the Epilogue and Gateways to Eternity FTB Quest trees so one pearl / singularity won't auto-complete the entire tree.

### Removed

- [1.28.24] Removed all custom ExtendedCrafting singularities and replaced them. Apologies for those who wanted to show their massive singularity count.
- [1.12.24] ~~Removed many duplicate Aether recipes and replaced them with tagged recipes. You are welcome!~~ https://github.com/The-Aether-Team/The-Aether/issues/1816
  - Edit: This has been revoked due to a conflict in recipes when it comes to making Aether's skyroot tools. For context if this change remained, two recipes would show up when making a skyroot tool. One for skyroot and one for Minecraft's vanilla wooden tool.
- [1.9.24] Removed block melting recipes due to conflicts with the Unstable Entropy Particle mixing recipe.
- [1.7.24] Removed Mob Grinding Util's blocks from Create's Wrench Pickup tag due to unintended behaviour of deleting the tanks.

<details>

<summary>0.2.1-build.39 removed mods</summary>

- [2.1.24] Embeddium++
- [1.26.24] Advanced Mining Dimension
- [1.26.24] Macaw's Bridges
- [1.25.24] Auudio and Load My Resources
  - Replaced by Melody and is now integrated into FancyMenu v3.
- [1.18.24] MemoryLeakFix
  - This is now handled by ModernFix.
- [1.8.24] Bocchium
- [1.8.24] Redirector

</details>