---
layout: default
title: 0.2.0 (1.19.2)
parent: Iteration 0.2 - 1.19.2 
grand_parent: Finality Genesis Changelog
nav_order: 9
---

## Finality Genesis 0.2.0 Build 38 (HOTFIX)

{: .important }
> This update resolves the issue with CraterLib causing the inability to join servers!

- [1.3.24] Updated Bocchium `0.0.2-10-13-23` to `0.0.2-1-3-24`
- [1.3.24] Updated CraterLib from `1.1.0` to `1.1.1` due to inability to join servers.
- [1.3.24] Updated Simple Discord Link Bot `3.0.0` to `3.0.1`

---

## Finality Genesis 0.2.0 Build 37

Another minor patch.

### Changed

* [1.3.24] Buffed Malum's Tyrving sword.
* [1.2.24] Decreased amount of loops for making H.E.A nuggets.
* [1.2.24] Slightly changed the block model of the Create Mechanical Extruder to make the recipe filter more obvious.
* [1.1.24] Charcoal production recipe no longer requires _only_ moss blocks. All leaves can also be used.
* [12.31.23] Removed Crystaltine Catalyst as a requirement for making High Entropy Alloy nuggets.
* [12.31.23] Adjusted output quantity of Mystical Agriculture recipes.
* [12.28.23] Changed the Bioethanol Recipe back to something that is similar to the original recipe.

<details>

<summary>0.2.0-build-37 mod updates</summary>

#### 1.2.24

- Collective `7.28` to `7.30`
- CraterLib `1.0.2` to `1.1.0`
- Create Central Kitchen `0.5.1.f-1.3.9.f` to `0.5.1.f-1.3.9.g`
- Essential `1-3-0-1` to `1-3-0-2`
- Gadgets Against Grind `2.0.0-build.8` to `2.0.0-build.16`
- Iron's Spells n' Spellbooks `2.1.2` to `2.2.0`
- ProbeJS `5.3.2` to `5.3.4`

#### 1.1.24

- Archaeology API `12.20.23` to `12.31.23`
- Exposure `1.2.1` to `1.2.2`
- Skin Layers 3D `1.5.2` to `1.6.1`
- Wares `1.2.4` to `1.2.5`

#### 12.29.23

- Cataclysm `1.85` to `1.86`
- Extended Crafting `5.1.9` to `5.1.10`

#### 12.28.23

- Collective `7.26` to `7.28`
- Moonlight Lib `2.3.5` to `2.3.6`
- Sooty Chimneys `1.1.1` to `1.2.0`
- Supplementaries `2.4.14` to `2.4.15`
- The Salt `1.2.1` to `1.2.4`

</details>

### Added

- [1.3.24] Added two recipes to make Supplementaries Blue Bombs, one for single and one for bulk crafting.
- [1.2.24] You can now make Obsidian with a Basin + Mechanical Press and a Mechanical Extruder... Don't question it. ~~Might even regret this~~
- [1.2.24] Added Cloud Storage Balloon Tie to the Carry On entity blacklist.
- [12.31.23] Added gambling trades for singularities in The Shop.
- [12.31.23] Added a recipe to make Prismarine with Water Breathing potions with Create... Put those pufferfish to use!
- [12.31.23] Added a recipe to make Lapis Lazuli with Create... the recipe probably doesn't make sense at all
- [12.31.23] Added a recipe for bulk producing Netherrack in a mixing basin.
- [12.31.23] Added a recipe to make 2x Brass Blocks when combining 1x Copper Block and 1x Zinc Block... also added one for brass nuggets for consistency's sake.
- [12.30.23] Added a recipe to be able to craft Create's Brown Toolbox from barrels.
- [12.28.23] Added the ability for Create's Netherite Backtank to also provide immunity to damage when wearing the High Entropy Alloy armor set.
- [12.28.23] Added Create spout filling and basin mixing support for tipping arrows for your automated potion factories.

#### Added mods

- [12.30.23] Added Functional Storage for massive storage, though it will cost you dearly.
- [12.30.23] Added Storage Labels after much thought...

### Removed

- [1.1.24] Removed WorldEdit due to using almost 1 GB of RAM, thanks embeddedt for your analysis.
- [1.1.24] Removed Yeetus Experimentus, replaced by Kiwi.

---

## Finality Genesis 0.2.0 Build 36

Just a minor patch...

### Fixed

- [12.27.23] Fixed some KubeJS items having an undefined display name, it was actually a mistake in my code.

### Changed

- [12.27.23] Changed default keybind for Voice Chat GUI due to conflict with the Cataclysm Ability keybind.
- [12.27.23] Increased Modern Remnant damage multiplier from 1.0 to 250.0. Also increased Modern Remnant health multiplier from 1.0 to 5.0.
- [12.27.23] Removed H.E.A sheets as an ingredient for EnderChests and EnderTanks related recipes. I _maaaay_ have been too harsh with that change.

<details>

<summary>0.2.0-build.36 mod updates</summary>

#### 12.27.23

- Curios API `5.1.4.3` to `5.1.4.4`

</details>

### Added

- [12.27.23] Added Create tooltips for the new Cataclysm items.

### Removed

- N/A

---

## Finality Genesis 0.2.0 Build 35

{: .important }
This update contains a backport of Cataclysm on 1.20.1, enjoy the new content! May need to generate new chunks, however. 0.2.0-build.33 has been changed to 0.2.0-build.35 as a result. I have also disabled resolution checks and forced GUI scaling, so apologies if the main menu looks a bit different as a result.

Update 0.2.0-build.35 addresses a mistake I made with one compacting recipe, adjust your Create production lines accordingly. With the addition of Embeddium++, dynamic lighting is now present! No, I will not be bundling Oculus by default due to its issues.

Some things that I should point out, however:

- This update will be using an early implementation of coins and trades will not yet be randomized with each world load and is not finished as I am trying to think of how to balance this to the best of my ability.
- The Entropy Mechanism recipe will eventually be randomized on sequenced steps 2-5 to be more in line with shapez.io's last few levels.
- Proper custom Wares delivery agreements implementation will not be implemented with this update.

{: .warning }
You may need to rebuild your factories due to recipe changes, sorry!

### Fixed

- [12.25.23] Apparently Create's Chocolate Bar recipe was missing from the last update, so that's being fixed with this release. It was being overridden by Neapolitan from the looks of it...
- [12.20.23] Fixed the Create tooltip on Backpacked backpacks from not loading. This was caused by a typo for a mod check...
- [12.15.23] Fixed a recipe compacting recipe that involved 1x Dried Kelp Block being compacted into 1x Coal Block which was incorrect. Thanks to TurnLeft25 for pointing this out.
- [12.15.23] Fixed conflict with Create Deco netherite nugget recipe result from decompressing Netherite Ingots
- [12.15.23] Some quest nodes were not hidden by default, my mistake.

### Changed

- [12.26.23] Changed Quantum Processor recipe to utilize actual qubits.
- [12.26.23] Crystallus Hasta now uses netherite ingots and echo shards to craft.
- [12.25.23] Changed Shimmer recipe to use Create's Refined Radiance.
- [12.25.23] Changed recipes for EnderChests and EnderTanks related items.
- [12.25.23] Changed the Netherrack recipe from Mystical Agriculture.
- [12.25.23] Changed the Glowstone Dust recipe from Mystical Agriculture.
- [12.25.23] Changed both the Creative World Shaper, Entropy Mechansim and High Entropy Alloy related recipes.
- [12.24.23] Increased EnderChests capacity from 27 to 54 slots.
- [12.24.23] Enabled an additional FerriteCore override.
- [12.24.23] Enabled additional ModernFix overrides.
- [12.22.23] Charcoal can now be compressed into coal.
- [12.22.23] The keybind for opening the mod list has been removed due to the presence of FTB Ultimine.
- [12.21.23] Increased Experience Nugget chance for kelp to coal to diamond conversion.
- [12.20.23] Adjusted scheduled message timing for Lootr and Extended Crafting singularity messages.
- [12.19.23] Changed a few villager trades and integrated custom coin currency. Wares implementation will be implemented at a later update.
- [12.18.23] Making Brass Ingots from Brass Essence now requires Infusion Energy.
- [12.18.23] Clarified the wording on the Iron's Spells n' Spellbooks introductory quest to make it clearer that using scrolls by themselves are consumed, but can be used infinitely when inscribed within a spell book.
- [12.18.23] Disabled resolution check and forced GUI scaling.
- [12.15.23] C.U.E (aka Condensed Universal Entropy) is now required for making Cthonic Gold to be more in line with the other extruder recipes.

<details>

<summary>0.2.0-build.35 mod updates</summary>

#### 12.26.23

- Embeddium `0.2.15` to `0.2.16`

#### 12.25.23

- Embeddium `0.2.14` to `0.2.15`
- Open Parties and Claims `0.20.3` to `0.20.4`

#### 12.24.23

- Cataclysm `1.83` to `1.85`
- Coloured Tooltips `18.1.3` to `18.1.4`
- Create: Power Loader `1.2.3` to `1.2.4`
- Embeddium `0.2.13` to `0.2.14`
- Friendly Fire `14.0.4` to `14.0.6`
- ModernFix `5.11.0` to `5.11.1`
- Open Parties & Claims `0.20.1` to `0.20.3`
- Villager Names `7.2` to `7.3`

#### 12.23.23

- Comforts `6.0.6` to `6.0.7`
- Exposure `1.2.0` to `1.2.1`
- Exposure `1.1.1` to `1.2.0`
- Wares `1.2.3` to `1.2.4`

#### 12.22.23

- Enchantment Descriptions `13.0.14` to `13.0.18`
- ModernFix `5.10.1` to `5.11.0`
- The Aether `1.0.0-beta.2.2` to `1.0.0`

#### 12.21.23

- Cloth Config API `8.3.103` to `8.3.115`
- Collective `7.23` to `7.26`

#### 12.20.23

- Archaeology API `1.0.0` to `1.0.0` (I have no idea why the version number has remained the same)
- Essential `1-3-0` to `1-3-0-1`
- Collective `7.22` to `7.23`
- Create Central Kitchen `0.5.1.f-1.3.9.e` to `0.5.1.f-1.3.9.f`

#### 12.19.23

- Essential `1-2-3` to `1-3-0`

#### 12.18.23

- Cataclysm `1.80` to `1.83`
- Collective `7.21` to `7.22`
- Create Enchantment Industry `0.5.1.f-1.2.7.e` to `0.5.1.f-1.2.7.f`
- Cycle Paintings `3.3` to `3.5`
- Supplementaries `2.4.13` to `2.4.14`

#### 12.17.23

- Collective `7.16` to `7.21`
- Create Enchantment Industry `0.5.1.f-1.2.7.d` to `0.5.1.f-1.2.7.e`
- Healing Campfire `5.2` to `5.3`
- Cataclysm `1.38` to `1.80`
- Villager Names `7.1` to `7.2`

#### 12.16.23

- Simple Voice Chat `2.4.31` to `2.4.32`

#### 12.15.23

- The Aether `1.0.0-beta.2.1` to `1.0.0-beta.2.2`

</details>

### Removed

- Removed Client Crafting

### Added

- [12.25.23] Added usage information for the Ender Bag and Ender Bucket through the REI / JEI information tab.
- [12.25.23] Added High Entropy Alloy (H.E.A) sheet, nugget and rod.
- [12.25.23] Added Potion Base Singularity
- [12.24.23] Added Salt Singularity
- [12.24.23] Added a tooltip for EnderChests and EnderTanks on how to use them.
- [12.24.23] Replaced Minecraft's Music Disc tooltips with Create tooltips since something seems to be interfering with lang overrides.
- [12.22.23] Added a recipe to convert Zombie Heads into Skeleton Heads.
- [12.22.23] Added two recipes to make Potion X from Create Mixing since the JEI recipe is not visible for whatever reason.
- [12.19.23] Added the Mutant Boss and Bosses of Mass Destruction large gate pearls.
- [12.18.23] Added a login message and information for FindMe usage in FTB Quests introductory node.
- [12.18.23] Added coins for more advanced trades from both Wandering Traders and Villagers.

#### Added mods

- [12.24.23] Added Modern World Creation
- [12.23.23] Added Block Limit Fix
- [12.21.23] Added WorldEdit for those who want it
- [12.21.23] Added FTB Ultimine
- [12.21.23] Added Bocchium
- [12.20.23] Added Naturally Charged Creepers
- [12.17.23] Added Embeddium++ and TexTrue's Embeddium Options
- [12.17.23] Added Simple Discord Link Bot
- [12.16.23] Added Mixin in Heaven
- [12.16.23] Added Neruina

---

## Finality Genesis 0.2.0 Build 32

> [!WARNING]
> DO NOT update The Aether mod to `1.0.0-beta.2-forge` or you will be unable to join servers that are running the modpack. `1.0.0-beta.2.1-forge` addresses this issue.

> [!IMPORTANT]
> Please check the crash-report folder to see if Malum is still causing a NullPointerException crash from Totem Bases after this update! The mod author has released a fix to address this issue.

### Fixed

- [12.14.23] Fixed Malum Signs causing client side crash with a KubeJS script to fix their rendering code. Thank you ChiefArug!
- [12.13.23] A Nether Star now drops as a reward after killing the Wither spawned during the Large Boss Gate Pearl.
- [12.10.23] Finally fixed client crash on both custom boss gate pearls after figuring out what was wrong with them.

### Changed

- [12.10.23] Gave the Wrench even _more_ pick up power, not going to specify what additional blocks were added to the list.

<details>

<summary>0.2.0-build.32 mod updates</summary>

### 12.14.23

- Architect's Palette `1.3.3` to `1.3.4`
- Bosses of Mass Destruction `1.0.5` to `1.0.6`
- Collective `7.15` to `7.16`
- Create: Power Loader `1.2.2` to `1.2.3`

#### 12.13.23

- FTB Essentials `1902.1.10-build.47` to `1902.3.4-build.109`
- Iron's Spells and Spellbooks `2.1.1` to `2.1.2`
- Jade `8.9.1` to `8.9.2`
- Rhino `1902.2.2-build.280` to `1902.2.3-build.284`

#### 12.12.23

- Bosses of Mass Destruction `1.0.4` to `1.0.5`
- Create: Bitterballen `0.0.6` to `0.0.61`
- Malum `1.5.0.3` to `1.5.0.4`
- Simple Voice Chat `2.4.30` to `2.4.31`

##### 12.12.23 pt.1

Technically updates from 12.11.23 but 4 AM mod updates... yay.

- Embeddium `0.2.12` to `0.2.13`
- ModernFix `5.10.0` to `5.10.1`
- The Aether `1.0.0-beta.1.3` to `1.0.0-beta.2.1`
- Wares `1.2.2` to `1.2.3`

#### 12.10.23

- Collective `7.13` to `7.15`
- Waystones `11.4.1` to `11.4.2`

</details>

### Added

- [12.14.23] Added additional preventive measures.
- [12.9.23] Added Woodworks's sawmill block to Create's wrench pickup tag for easy pickup.

<details>

<summary>0.2.0-build.32 mod additions</summary>

- [12.12.23] Added PaxelJS
- [12.12.23] Added Bosses of Mass Destruction
- [12.12.23] Added Mutant Monsters
- [12.10.23] Added Just More Cakes!
  - Also added Cake Chomps
- [12.10.23] Added Advanced Mining Dimension
- [12.10.23] Added FindMe
- [12.10.23] Re-added ImmediatelyFast
- [12.10.23] Added Create: Bitterballen
- [12.9.23] Added Wares by mortuusars

</details>

### Removed

- [12.14.23] All of Malum's sign recipes.

---

## Finality Genesis 0.2.0 Build 31

The Aether mod team broke something again, yay.

- Reverted Aether from `1.0.0-beta.2` to `1.0.0-beta.1.3` due to to causing a server crash whenever a player attempts to join.

---

## Finality Genesis 0.2.0 Build 30

> [!WARNING]
> This update is broken due to the Aether mod, please update to 0.2.0-build.31!

### Fixed

- [12.7.23] Fixed incorrect tooltip on Cataclysm's Monstrous eye.
- [12.6.23] Blacklisted Supplementaries and Graveyard blocks from Carry On.
- [12.6.23] Fixed Fishing Bobber Model flipping texture when in a lit state.
- [12.4.23] Server side update checker script fixed.

### Changed

- [12.8.23] Changed Create's placement assistant indicator from texture to triangle.
- [12.7.23] Changed required number and chance of bonks for some Mechanical Extruder recipes.
- [12.7.23] Fixed loophole with Dripstone. Don't worry! It's still infinitely renewable using Create methods.
- [12.7.23] Unhid Denied Result and Removed Item from the hide list on both JEI and REI
- [12.6.23] Players will now spawn with a backpack on first world load. Please note that any players who have already joined will have to craft their own backpacks from leather and 1 iron ingot!
- [12.6.23] Bucket recipe has been reverted back to the vanilla of 3x Iron Ingots instead of 3x Iron Sheets from Create. You will still be able to make Buckets with Iron Sheets, however.
- [12.6.23] Big tooltip registry re-write... expect more tooltips.
- [12.6.23] Increased inventory column size of Backpacked's backpack to 13 columns.
  - Was previously 9 columns and 7 rows.
- [12.5.23] Internal scripts...
- [12.5.23] Removed Denied Result from removed recipes.

<details>

<summary>0.2.0-build.30 mod updates</summary>

#### 12.8.23

- Better chunk loading `2.2` to `2.5`
- Crafting Tweaks `15.1.8` to `15.1.9`
- Exposure `1.1.0` to `1.1.1`
- Kiwi `8.3.4` to `8.3.5`
- Simple Voice Chat `2.4.29` to `2.4.30`

#### 12.7.23

- Updated Collective `7.12` to `7.13`
- Updated Xaero's Minimap `23.9.2` to `23.9.3`
- Updated Exposure `1.0.2` to `1.1.0`

#### 12.6.23

- Updated Collective `7.11` to `7.12`
- Updated Xaero's Minimap `23.9.1` to `23.9.2`
- Updated Xaero's World Map `1.37.1` to `1.37.2`

#### 12.5.23

- Updated Embeddium `0.2.11` to `0.2.12`
- Updated KubeJS `1902.6.2-build.42` to `1902.6.2-build.45`
- Updated Serilum `7.9` to `7.11`
- Updated Crafts & Additions `1.2.0` to `1.2.1`

#### 12.4.23

- Updated The Aether from `1.0.0-beta.1.3` to `1.0.0-beta.2`

</details>

### Added

- [12.7.23] Added a recipe to create Dripstone blocks.
- [12.7.23] Added a reversal recipe for converting Ad Astra Steel Ingots back into Iron Ingots using Shimmer.
- [12.5.23] Added the Netherite Nugget, textured by yours truly.

---

## Finality Genesis 0.2.0 Build 28

### Changed

- [12.3.23] Blacklisted the Minecraft Jukebox from being picked up with Carry On.

<details>

<summary>0.2.0-build.28 mod updates</summary>

- [12.4.23] Updated ModernFix from `5.9.3` to `5.10.0`
- [12.3.23] Updated Real Camera from `0.5.3-beta` to `0.5.4-beta`

</details>

---

## Finality Genesis 0.2.0 Build 27

So a mod deleted the vanilla chest recipe without me noticing as I assumed it was going to **stay** and be safe after previous playthroughs.
There's also an issue with Malum's totem base and Carry On.

### Changed

- [12.2.23] Blacklisted the entirety of Little Logistics and Little Contraptions due to duplication exploit.
- [12.2.23] Blacklisted the entirety of Malum from Carry On due to NPE. Servers that are still crashing due to this issue will have to either roll back prior to the soft locked crash or worst case scenario delete Malum temporarily and firstload the server without it present and start it again with the mod present.
- [12.1.23] Re-implement vanilla chest recipe for wooden planks from Biomes o' Plenty

<details>

<summary>0.2.0-build.27 mod updates</summary>

- [12.2.23] Updated Exposure `1.0.1` to `1.0.2`
- [12.2.23] Updated Supplementaries `2.4.12` to `2.4.13`

</details>

### Added

- [12.2.23] Added item application recipe for Chest Minecarts.

---

## Finality Genesis 0.2.0 Build 26

Another minor update with bug fixes from Xaero's mods regarding `null pointer exception` and Create: Power Loader if JEI is missing.

### Changed

- [12.1.23] Fixed `quark:shiba_inu` to `'quark:shiba'`
- [12.1.23] Added a log in message to remind players not to break Lootr chests out of courtesy.
- [12.1.23] Added more Malum quest nodes, still not complete though.
- [12.1.23] FTB Quests emergency item cooldown has been reduced to 5 seconds.
  - Admittedly this should have been done at the very beginning with all of my modpacks... It was not immediately clear to me what the countdown was for until it clicked.
- [12.1.23] Clock now has the ability to skip more time, at the cost of something.

<details>

<summary>0.2.0-build.26 mod updates</summary>

#### 12.1.23

- [12.1.23] Updated Create: Power Loader `1.2.0` to `1.2.2`
- [12.1.23] Updated FTB Quests `1902.5.6-build.304` to `1902.5.7-build.326`
- [12.1.23] Updated Supplementaries `2.4.11` to `2.4.12`
- [12.1.23] Updated Xaero's Minimap from `23.9.0` to `23.9.1`
- [12.1.23] Updated Xaero's World Map from `1.37.0` to `1.37.1`
  - The developer of Xaero's Minimap and World Map has released an update that addresses **null pointer exception** crashes before or during client world changes.

</details>

### Added

- [12.1.23] Added Exposure by mortuusars
  - Thank you for developing this mod! I was wondering what the repository was for.

---

## Finality Genesis 0.2.0 Build 24

This is technically a very minor update, but the build number has been increased a bit more due to a mod receiving a major rework update:

- Unfortunately, it seems that Iron's Spells n' Spellbooks has had _another_ major update, so you will have to update your world's serverconfigs to reflect those changes.

> [!WARNING]
> Please remember to back up your world and its world seed prior to updating! I am not responsible for negligence.

### Changed

- [11.29.23] Changed ExtendedCrafting's Basic Table recipe.
- [11.29.23] Due to recipe conflicts that I started running into while adding new ones, molten metal recipes have been changed to use sheets instead of ingots. I do not want Zinc Ingots accidentally turning into Molten Zinc as you are trying to make Brass Ingots.
- [11.29.23] Changed the recipes for Shetiphian's EnderChests and EnderTanks utilize Enhanced Ender Catalysts.
- [11.28.23] It seems that my fix for Create Cafe no longer works... You shouldn't see Cryo Fuel and Fertilizer being eligible ingredients for your drinks anymore.
- [11.28.23] This is another balancing pass that will affect Mystical Agriculture's augments and Creative Flight Augment.
  - The Unattuned Augment now needs 8 Prosperity Shards and 1 ExtendedCrafting basic catalyst.
  - The Flight Augment now needs 4 Flux Stars and 4 Command Blocks.

<details>

<summary>0.2.0-build.24 mod updates</summary>

### 11.28.23

- Updated Collective `7.8` to `7.9`
- Updated Iron's Spells n' Spellbooks `2.1.0` to `2.1.1`
- Updated Simple Voice Chat `2.4.28` to `2.4.29`
- Updated Villager Names `7.0` to `7.1`
- Updated Xaero's Minimap `23.8.4` to `23.9.0`
- Updated Xaero's World Map `1.36.0` to `1.37.0`

### 11.27.23

- Updated Chunk Sending `2.7` to `2.8`
- Updated Clickable advancements `3.5` to `3.6`
- Updated Create Crafts & Additions `1.1.1` to `1.2.0`
- Updated Curios API `5.1.4.2` to `5.1.4.3`
- Updated Embeddium `0.2.10` to `0.2.11`
- Updated Iron's Spells n' Spellbooks `2.0.3` to `2.1.0`
- Updated Mystical Agriculture `6.0.12` to `6.0.13`
- Updated PolyLib `1900.0.2-build.73` to `1900.0.3-build.100`

</details>

### Added

- [11.29.23] Added Netherite and Zinc sheets. Thank you to DMJaxun for making the Netherite Sheet texture.
- [11.28.23] Players will now receive a Sack from Supplementaries on world first load. This is to try and address inventory management in the beginning for players who don't manage their inventory that well.
- [11.28.23] Tooltips on some Supplementaries items and blocks.

---

## Finality Genesis 0.2.0 Build 16

Minor corrections to correct the mistakes I made while 4 AM developing as well as more modular changes to make porting to 1.20.1 easier.

- [11.24.23] After checking on the Ultimate Singularity recipe, it seems to be missing until an in-world reload with the `/reload` command is initiated which is a bit unusual...

### Fixed

- [11.24.23] Fixed incorrect tooltip on the Final Scythe.
- [11.24.23] Fixed Ultimate Singularity recipe not showing up without typing `/reload` after the world is loaded. The auto-generated recipe on the mod's end seems to no longer work...
- [11.21.23] REI event attempting to hide an item in the group entries listener.

### Changed

- [11.24.23] Everything Etched related can no longer be picked up with Carry On due to the ability to permanently play sounds when the source is moved away from its original position and placed back down elsewhere.
- [11.21.23] Changed watcher ID back to what it was as I was unaware at the time that the URL ID does not change when a pastebin is renamed.
- [11.21.23] Lodestone related scripts have been moved to their own scripts instead.

<details>

<summary>0.2.0-build.16 mod updates</summary>

#### 11.25.23

- Updated Collective `7.7` to `7.8`

#### 11.24.23

- Updated Embeddium `0.2.9` to `0.2.10`

</details>

---

## Finality Genesis 0.2.0 Build 15

This is a follow up update to the previous build. This update is slightly disruptive as it **does** remove both existing chunk loader mods in favor of another one.

Small note for 11.18.23: I am sorry if development feels like it has suddenly slowed. IRL situation is complicating things and I don't want to go into detail about it.

### Fixed

- [11.16.23] Fixed Crystaltine Ingot recipes.
- [11.14.23] Fixed Awakened Supremium Gemstone recipe.
- [11.14.23] Fixed Awakened Supremium Ingot recipe using the incorrect materials.
- [11.13.23] Fixed music discs not displaying the correct text. This is due to me _forgetting_ to put the important parts of the en_us.json inside the script that was supposed to handle lang.

### Changed

- [11.20.23] Particles from wearing the Finality armor set will no longer show.
- [11.16.23] Changed Crystaltine Ingot recipe.
- [11.12.23] Reworked Mystical Agriculture recipes, again.
- [11.11.23] Mystical Agriculture redstone recipe has been modified to require less Strength Potion fluid.
- [11.11.23] Enabled the ability for the clock to change time.

<details>

<summary>Mod updates</summary>

#### 11.19.23 Mod Updates

- Carry On `1.19.2-2.1.1.21` to `1.19.2-2.1.1.22`
- KubeJS `1902.6.2-build.39` to `1902.6.2-build.42`
- Sructure Essentials `1.19.2-3.1` to `1.19.2-3.2`

#### 11.18.23 Mod Updates

- Apotheosis `1.19.2-6.4.0` to `1.19.2-6.4.1`
- Placebo `1.19.2-7.3.3` to `1.19.2-7.3.4`
- Server Performance - Smooth Chunk Save `1.19.2-3.4` to `1.19.2-3.5`
- Supplementaries `1.19.2-2.4.10` to `1.19.2-2.4.11`
- YUNG's API `1.19.2-Forge-3.8.9` to `1.19.2-Forge-3.8.10`
- YUNG's Better Mineshafts `1.19.2-Forge-3.2.0` to `1.19.2-Forge-3.2.1`

#### 11.15.23 Mod Updates

- Create: Power Loader `1.1.1-mc1.19.2` to `1.2.0-mc1.19.2`

#### 11.13.23 Mod Updates

- Collective `1.19.2-7.3` to `1.19.2-7.7`
- Embeddium `0.2.7+mc1.19.2` to `0.2.9+mc1.19.2`
- EnderChests `1.19-1.10.7` to `1.19-1.10.8`
- EnderTanks `1.19-1.12.8` to `1.19-1.12.9`
- Just Enough Resources `1.19.2-1.2.2.236` to `1.19.2-1.2.3.243`
- ModernFix `5.9.2+mc1.19.2` to `5.9.3+mc1.19.2`
- ShetiPhianCore `1.19-3.11.10` to `1.19-3.11.11`
- Villager Names `1.19.2-6.2` to `1.19.2-7.0`

#### 11.11.23 Mod Updates

- Cycle Paintings `1.19.2-3.2` to `1.19.2-3.3`
- Eccentric Tome `1.19.2-1.10.1` to `1.19.2-1.10.2`
- FTB XMod Compat `1.2.2` to `1.2.3`
- Healing Campfire `1.19.2-5.1` to `1.19.2-5.2`
- KubeJS Create `1902.2.4-build.29` to `1902.2.4-build.36`
- Supplementaries `1.19.2-2.4.8` to `1.19.2-2.4.10`
- Villager Names `1.19.2-6.1` to `1.19.2-6.2`

</details>

### Added

- [11.19.23] Added two new trades to the Vein Goblin Trader to help with acquiring Ghasts for the new chunk loaders. Be sure to have some trading materials ready!
- [11.19.23] Quark's Gold Bars can now be wrenched by Create's wrench.
- [11.18.23] Added trades to the Wandering Trader to make Fruit Trees' saplings available to players on older worlds.
- [11.18.23] Added a new mod: Fruit Trees by Snownee
- [11.18.23] Goblin Traders and Vein Goblin Traders are now protected, so you can no longer accidentally commit friendly fire.
- [11.16.23] Added more Grimoire of Gaia related trades to the Goblin Trader.
- [11.14.23] Re-added the shaped recipe for Redstone Dust as it now requires a Strength Potion, which is the same cost as the current mixing recipe.
- [11.14.23] Added REI/JEI information for Awakened Supremium Essence acquisition methods.
- [11.14.23] Added a new mod: **Create: Power Loader**
- [11.13.23] Added Glow Shroom to Wandering Trader trades pool.
- [11.13.23] Added Tuff to CobbleGenRandomizer pool
- [11.13.23] Added block loot modifier for Malum's Brilliant Stone and Brilliant Deepslate
- [11.13.23] Mystical Agriculture's Agglomeratios can now be crafted shapelessly or with Create's Mixing recipe method.

### Removed

- [11.14.23] Removed Chunk Loaders as it has been replaced with **Create: Power Loader**
  - The following dependencies have also been removed:
    - SuperMartijn642's Config Lib
    - SuperMartijn642's Core Lib
- [11.14.23] Removed Create: Chunkloading as it has been replaced with **Create: Power Loader**
- Removed penalty for the clock to age players when used too early. This will return as a beneficial mechanic for players, such as using the clock as a weapon.

---

## Finality Genesis 0.2.0 Build 8-12

Testing build. This is also the first changelog to follow a format similar to the **Keep a Changelog** format.

### Fixed

- [11.4.23] Fixed certain levels of enchantments being unobtainable by giving additional properties to the Command Blocks.
- [11.2.23] Fixed `// requires: 100` typo in Architect's Palette.
- [10.29.23] Corrected typo in update checker script.

### Changed

- [11.8.23] Changed vanilla hopper recipe again to only require a Create Chute and any wooden chest.
- [11.7.23] Modified some keybinds. `H` now opens the Skill Slots wheel. Also gave the clock to ability to modify time.
- [11.6.23] Moved tips to generate virtually. (A technical change that most people won't care about)
- [11.5.23] The Rebound enchantment from Malum can now be put on any weapon in the game. Enjoy your flying scythes and swords of death!
- [11.4.23] Disabled all recipe unlock in Quark config.
- [11.4.23] Due to the Malum integration with Grimoire of Gaia, the NPCs no longer drop their spawn eggs when killed.
  - Something else to note... the integration with Quark has also caused stonelings to not drop their Heart of Diamond when killed.
- [11.2.23] Some recipes now have a chance to make Experience Nuggets.
- Reworked essence to item / block conversion.

<details>

<summary>Mod updates</summary>

Keeping track of mod updates...

#### 11.8.23 Mod Updates

- Chunk Loaders `1.2.8-forge-mc1.19` to `1.2.8a-forge-mc1.19`
- Collective `1.19.2-6.82` to `1.19.2-7.3`
- Jade Addons (Forge) `1.19.2-forge-3.5.0` to `1.19.2-forge-3.6.0`
- ModernFix `5.9.1+mc1.19.2` to `5.9.2+mc1.19.2`
- Supplementaries `1.19.2-2.4.7` to `1.19.2-2.4.8`

#### 11.6.23 Mod Updates

- Updated Collective `1.19.2-6.80` to `1.19.2-6.82`
- Updated Embeddium `0.2.5` to `0.2.7`
- Updated ModernFix `5.9.0` to `5.9.1`
- Updated Supplementaries `1.19.2-2.4.6` to `1.19.2-2.4.7`

#### 11.5.23 Mod Updates

- Updated Moonlight Lib `1.19.2-2.3.4` to `1.19.2-2.3.5`
- Updated Supplementaries `1.19.2-2.4.5` to `1.19.2-2.4.6`
- Updated ProbeJS `5.3.1` to `5.3.2`
- Updated Create Cafe `1.2.3-1.19.2` to `1.2.4-1.19.2`
- Updated Villager Names `1.19.2-5.2` to `1.19.2-6.1`

#### 11.4.23 Mod Updates

- Updated Collective `1.19.2-6.75` to `1.19.2.-6.80`
- Updated Create Central Kitchen `0.5.1.e-1.3.9.d` to `0.5.1.f-1.3.9.e`
- Updated Create Enchantment Industry `0.5.1.e-1.2.7.c` to `0.5.1.f-1.2.7.d`
- Updated Moonlight Lib `1.19.2-2.3.3` to `1.19.2-2.3.4`
- Updated Supplementaries `1.19.2-2.4.4` to `1.19.2-2.4.5`

#### 11.2.23 Mod Updates

- Updated Collective `1.19.2-6.72` to `1.19.2-6.75`
- Updated Create `1.19.2-0.5.1.e` to `1.19.2-0.5.1.f`
- Updated Curious API `1.19.2-5.1.4.1` to `1.19.2-5.1.4.2`
- Updated FTB Backups 2 `1.19.2-1.0.22` to `1.19.2-1.0.23`
- Updated Simple Voice Chat `1.19.2-2.4.27` to `1.19.2-2.4.28`

#### 11.1.23 Mod Updates

- Updated KubeJS `1902.6.2-build.37` to `1902.6.2-build.39`
- Updated Essential `1-2-2-4_forge_1-19-2` to `1-2-3_forge_1-19-2`

#### 10.31.23 Mod Updates

- Updated Chalk `chalk-1.19.2-1.6.2` to `chalk-1.19.2-1.6.3`
- Updated Collective `collective-1.19.2-6.66` to `collective-1.19.2-6.72`
- Updated Essential `essential_1-2-2-3_forge_1-19-2` to `essential_1-2-2-4_forge_1-19-2`
- Updated Iron's Spells n' Spellbooks `irons_spellbooks-1.19.2-2.0.2` to `irons_spellbooks-1.19.2-2.0.3`

#### 10.29.23 Mod Updates

- Uodated Supplementaries `supplementaries-1.19.2-2.3.24` to `supplementaries-1.19.2-2.4.4`
- Updated Moonlight Lib `moonlight-1.19.2-2.2.46-forge` to `moonlight-1.19.2-2.3.3-forge`
- Updated ModernFix `modernfix-forge-5.8.1+mc1.19.2` to `modernfix-forge-5.9.0+mc1.19.2`
- Updated Iron's Spells n' Spellbooks `irons_spellbooks-1.19.2-2.0.1` to `irons_spellbooks-1.19.2-2.0.2`
- Updated Essential `essential_1-2-2-2_forge_1-19-2` to `essential_1-2-2-3_forge_1-19-2`
- Updated Embeddium `embeddium-0.2.3+mc1.19.2` to `embeddium-0.2.5+mc1.19.2`

#### 10.26.23 Mod Updates

- Updated Windswept! `windswept-1.19.2-2.2.2` to `windswept-1.19.2-2.2.3`
- Updated The Aether `aether-1.19.2-1.0.0-beta.1.2-forge` to `aether-1.19.2-1.0.0-beta.1.3-forge`
- Updated KubeJS `kubejs-forge-1902.6.2-build.33` to `kubejs-forge-1902.6.2-build.37`

#### Untracked mod update date

- Updated Cupboard `cupboard-1.19.2-2.0` to `cupboard-1.19.2-2.1`
- Updated Polymorph `polymorph-forge-0.46.4+1.19.2` to `polymorph-forge-0.46.5+1.19.2`

</details>

### Added

- [11.7.23] Clocks now have the ability to add time.
- [11.6.23] Added a tooltip for the Final Katana.
- [11.6.23] Added a way to generate Cthonic Gold.
- [11.6.23] Added even more trades for Caupona and Malum to the Wandering Trader for backwards compatibility for those who are unable to find new saplings when updating the modpack.
- [11.4.23] Added combat protection for Quark's Shiba Inu and Grimoire of Gaia NPCs.
- [11.3.23-11.4.23] Added Malum integration with Grimoire of Gaia.

#### Added mods

- Added Skill Slots
- Added CobbleGenRandomizer
- Added Malum

### Removed

- [11.5.23] Disabled Quark's Automatic Recipe Unlock.
- [11.5.23] Disabled Quark's Feeding Troughs
- [11.2.23] Create has patched the incorrect texture on Smart Observers, so my model JSON correction is no longer needed.

---

# 0.2.0 Release Candidate Updates

All release candidate changelogs are below.

## Release Candidate 3 Patch D Changes

This will be the last patch before full release.

- Fixed a recipe from the Aether module returning `minecraft:air` due to being invalid.
  - Apologies for making a mistake at 4 AM.
- Updated Quark `Quark-3.4-417` to `Quark-3.4-418`
- Updated Xaero's Minimap `Xaeros_Minimap_23.8.3_Forge_1.19.1` to `Xaeros_Minimap_23.8.4_Forge_1.19.1`
- Updated Xaero's World Map `XaerosWorldMap_1.35.0_Forge_1.19.1` to `XaerosWorldMap_1.36.0_Forge_1.19.1`

---

## Release Candidate 3 Patch C Changes

I think I will call Patch C the Stardew Valley patch. Enjoy!

Notice: If you happen to be missing _any_ assets and textures from the previous updates, I suggest updating via the CurseForge launcher then importing the updated instance to Prism Launcher or Prism Launcher _with_ your Xaero's, Essential, Create schematics, world saves, options data, etc. attached.

**.minecraft is your instance's folder**

| Location                                 | Description                                                                                                                         |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| `.minecraft/resourcepacks`               | Contains your resourcepacks.                                                                                                        |
| `.minecraft/essential`                   | Contains your Essential related data and screenshot metadata.                                                                       |
| `.minecraft/saves`                       | Contains your world saves.                                                                                                          |
| `.minecraft/screenshots`                 | Contains your screenshots if you took any memorable ones.                                                                           |
| `.minecraft/schematics`                  | Contains all of your schematics saved with Create's Schematic and Quill Item.                                                       |
| `.minecraft/XaeroWaypoints`              | Contains all of your Xaero's Minimap / World Map related waypoints.                                                                 |
| `.minecraft/XaeroWaypoints_BACKUP032021` | or whichever name it has at the time of backup generation. Contains a backup of your Xaero's Minimap / World Map related waypoints. |
| `.minecraft/XaeroWorldMap`               | Contains all of your Xaero's World Map related data.                                                                                |
| `.minecraft/options.txt`                 | Your Minecraft settings and keybinds.                                                                                               |

### The changes

- Fixed Create's Smart Observer texture having the incorrect texture on the bottom due to being unable to find the correct texture.
- Made a lot of blocks able to be picked up by the power of Create's Wrench.
- Removed Netherite Monstrosity from all boss gateway pearls.
- Added the Scythe of Eternal Oblivion for combat purposes to replace the Agricula Manus.
- The Final Katana now uses a GUI and handheld model for sanity purposes.
- Added Ancient Knights to the Boss Gate Pearl in place of it and moved the Ignited Revenants to the end.
- Made a recipe for renewing Soulium Ore.
- Blacklisted the Alchemist's Cauldron from Iron's Spells and Spellbooks due to permanent duplication of cauldrons and being unable to let go of said cauldron.
- Blacklisted the entirety of Handcrafted from being used with Carry On due to duplication.
- Blacklisted the entierty of Chipped from being used with Carry On as a precaution.
- Actually fixed Discord rich presence message... this isn't Finality Tau edition.
- Added the ability to create Wither Bones from Baubley Heart Canisters and Withered bones from Architect's Palette.
- Added even more Wandering Trader trades to account for the addition of Farmer's Delight add-ons.
- Added dried matcha leaves.
- Added recipes to repair Upgraded Netherite related tools.
- [10.18.23] Fixed Chalk tooltips... this has been _broken_ for a while now due to a typo in the itemID.
- [10.18.23] Added tooltip to the Enchanter's Pearl to clarify that it is currently useless due to a lack of compatibility with Apotheosis.
- [10.19.23] Made the Axe of the Executioner repairable with Netherite Ingots
- [10.20.23] Quark's gold bars are now transparent to Create's Encased Fans.
- [10.22.23] Added repair recipes for Blue Skies
- [10.22.23] Valkyrie Gloves are now unbreakable.
- [10.21-22.23] Updated GUI textures, they are a work in progress.
- Changes that are undocumented can be found in the GitHub commit history.

### Mod updates

- Updated Create Enchantment Industry `create_enchantment_industry-1.19.2-for-create-0.5.1.e-1.2.7.b` to `create_enchantment_industry-1.19.2-for-create-0.5.1.e-1.2.7.c`
- Updated KubeJS `kubejs-forge-1902.6.2-build.27` to `kubejs-forge-1902.6.2-build.33`
- Updated Quark `Quark-3.4-416` to `Quark-3.4-417`
- Updated Vertical Slabd Compat `v_slab_compat-1.19.2-1.6` to `v_slab_compat-1.19.2-1.9`
- Updated Vertical Slabs Compat `v_slab_compat-1.19.2-1.4` to `v_slab_compat-1.19.2-1.6`
- Updated Rhino `rhino-forge-1902.2.2-build.272` to `rhino-forge-1902.2.2-build.280`
- Updated KubeJS `kubejs-forge-1902.6.2-build.23` to `kubejs-forge-1902.6.2-build.27`
- Updated KubeJS `kubejs-forge-1902.6.2-build.19` to `kubejs-forge-1902.6.2-build.23`
- Updated KubeJS `kubejs-forge-1902.6.2-build.15` to `kubejs-forge-1902.6.2-build.19`
- Updated Comforts `comforts-forge-6.0.5+1.19.2` to `comforts-forge-6.0.6+1.19.2`
- Updated Jade `Jade-1.19.1-forge-8.9.0` to `Jade-1.19.1-forge-8.9.1`
- Updated Embeddium `embeddium-0.2.0+mc1.19.2` to `embeddium-0.2.3+mc1.19.2` for some more performance. ALL HAIL EMBEDDEDT
- Updated Quark `Quark-3.4-414` to `Quark-3.4-416` as the crash seems to have been fixed.
- Updated Simple Voice Chat `voicechat-forge-1.19.2-2.4.26` to `voicechat-forge-1.19.2-2.4.27`
- Updated Xaero's Minimap `Xaeros_Minimap_23.8.2_Forge_1.19.1` to `Xaeros_Minimap_23.8.3_Forge_1.19.1`
- Updated Xaero's World Map `XaerosWorldMap_1.34.1_Forge_1.19.1` to `XaerosWorldMap_1.35.0_Forge_1.19.1`

### Mod additions

- Added Collector's Reap
- Added Cultural Delights
- Added Crabber's Delight
- Added Delightful
- Added End's Delight
- Added Miner's Delight
- Added Nether's Delight
- Added Windswept!
- Added Crafting Automat, a backport of Mojang's Crafter.

### Removed mods

- ImmediatelyFast (UI issues.)
- Achievements Optimizer (Actually does nothing at the moment.)
- FTB Quests Optimizer (Actually does nothing at the moment.)

---

## Release Candidate 3 Patch B Changes

- Added Inferium Essence to Millstone seed reprocessing
- Added Boss Gateway Pearl and Large Boss Gateway Pearl
- Added check for Ad Astra and steel essence related recipes
- Added additional warnings for using the Eccentric Tome
- Added Apotheosis override for Create's Potato Cannon to make it able to be reforged. Please note that **not all** bow reforges will affect it!
- Increased limit for Power from 20(+1) to 50(+1) as I'm trying to figure out a solution to make Create's Potato Cannon more effective against armored targets.
- Lowered maximum level for Quick Draw from XX back to V due to being too fast to _actually_ fire or do anything.
- Added tooltips for Lil' Wings Butterfly Net and Enderfly Net
- Fixed the frEEeeeE? Raw Iron message not working in Multiplayer environments.
- Enabled shouldGlow to make it easier to see players that are bleeding out
- Added more deathMessages
- Disabled rendering player model by default when RealCamera is enabled.
- Increased durability of Super Glue from 99 to 128
- Set default keybind to mute microphone to `-`
- Added tooltips for solapplepie food container items
- Added recipe for Gilded Blackstone for decoration purposes
- Added recipes for Icestone, Holystone and Holy Dirt
- Blacklisted Cosmic Cod from spawning in all Blue Skies dimensions due to lag... hopefully they don't spawn ever again due to the mod being ARR which resulted in me being unable to easily find the registry names of the biomes.
- Decreased spawn weight of cosmic cod entirely to 0... was not aware that this was even an option in the config.
- Implemented textures for the Create Bobber block based on the updated Smart Observer's textures.

### Mod updates

- Updated Quark `Quark-3.4-414` to `Quark-3.4-415` Edit: Remain on `Quark-3.4-414` until the issue with crash due to Wandering Traders is fixed.
- Updated Better Advancements `BetterAdvancements-1.19.2-0.2.2.142` to `BetterAdvancements-1.19.2-0.3.0.148`
- Updated Terrablender `TerraBlender-forge-1.19.2-2.0.1.136` to `TerraBlender-forge-1.19.2-2.0.1.166`
- Updated Achievements Optimizer `AchievementOptimizer-1.19.2-1.0.2` on 9.14.23 to `AchievementOptimizer-1.19.2-1.0.2` 10.11.23 which adds config

### Mod additions

- Added Create: Fishing Bobber Detector | Automatic Fishing with Create
- Added Cosmetic Armor Reworked

### Mod removals

- Removed Toast Control due to causing occasional crashes on join.

---

## Release Candidate 3 Patch A Changes

So I forgot about adding a way to get Lemon Seeds...

- _Actually_ fixed server watcher script.
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

---

## Release Candidate 3 Changes

This update has breaking changes for Iron's Spells and Spellbooks users due to the mod author's rework. Don't say I warned you!

- Updated Forge loader version from `43.2.21` to `43.3.2`
- ~~Changed from release candidate to development / beta build.~~
- [10.9.2023] Changed from development build 3 back to release candidate 3.
- As of Embeddium 0.2 you can now disable Compact Vertex Format, which means you can disable the optimization that **causes Z-fighting and flickering**!
- Quark-3.4-414 is being used and has not presented any _immediate_ problems so far from playtesting. If issues arise, downgrade to Quark-3.4.409.
- The duplication bug with Eccentric Tome has not yet been fixed, so I guess it will have to wait for either rc4 or just plain 0.2 release.

These changes should have been in Release Candidate 2 which was released a bit _too_ early, but at least playtesting showed some things that I forgot to address. I **will** be taking my time on this. Full release will require a re-do of every draft texture and other uses for the shapes.

- [10.9.23] The rest is in GitHub commits...
- [10.8.23] Tempad cooldown reduced from 30 seconds to 10 seconds.
- [10.7.23] Finalized first iteration of retextures for GUI and the Monobank.
- [10.7.23] Added information for Aether's Obsidian armor pieces.
- [10.6.23] You can now craft Nether Wart Jam
- [10.6.23] Added lemons, literally. The texture is _not_ final!
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