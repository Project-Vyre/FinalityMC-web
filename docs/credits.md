---
title: Credits & Contributors
layout: default
nav_order: 8
---
This was just pasted over from the original GitHub repository wiki, I apologize for the formatting being rough around the edges.

# Music Credits
Please check out Cjbeards, very awesome music! [Cjbeards music is free use as mentioned here](https://docs.google.com/spreadsheets/d/1ZTM7nf4Uia19c-NQheqPnLAk1Bs6NS6XZiLt7Mk4Z1Q/edit#gid=0), but please check his [channel on YouTube.](https://www.youtube.com/channel/UCarvKz1XSCON68oeSZ1mlkg) I do not own any of his work or music. 
* [menu1.ogg and 5.ogg] [Heart of the Wicked - Cjbeards](https://youtu.be/ZsKEZUgKaXg) {You may recognize this from FTB Legend of the Eyes.}
* [menu2.ogg and 11.ogg] [From the Shadows - Cjbeards](https://youtu.be/m2IA-rXEKPk)
* [Formerly menu3.ogg, now replaced.] [Cubeponk - Cjbeards & Fayr](https://youtu.be/Id2LUBrnHh4)
* [menu4.ogg and 13.ogg] [Mirror Mirror (Instrumental) - Cjbeards](https://youtu.be/u91uppHLfS4)
* [end.ogg] [Shattered Glass - Cjbeards](https://youtu.be/rjumdHtHU5U)
* [boss.ogg] [Brave the Storm - Cjbeards](https://youtu.be/dGmLKmxvJ0I)
* [menu3.ogg and chirp.ogg] [Arlecchino Battle Theme Phase 1 & 2 (Fan-Made) | Genshin Impact - Farabi Hasan Music](https://youtu.be/1Jj5aAEYSeo)
  * *Feel free to use my mix as a BGM for your contents, but do please leave credits!*
* [cjbeards_bad_deeds_inst.ogg](https://youtu.be/prrBvmXmMSY)

# Contributors
## Modpack Team
People developing the modpack:
* CelestialAbyss - Lead Dev
  * Currently it is technically just me... It's also unfortunate to say that I might not be able to accomplish everything I wanted to with my modpack but I'll try to the best of my ability. Also, the modpack icon and animated black hole among other assets like the title and retextures are made by me using paint.NET or Blender or a combination of the two. The main menu animation took *forever* to render on my GTX 1660 Ti, even with the newest changes to the Cycles rendering engine so it might be a while before I try and tackle the suggestions that were said in the Create Discord server.
* Ryanite - Dev
  * The multiplayer server administrator, also loves Create. Will take my place in case my living situation gets out of my control entirely.
* patchi
  * Suggested the steeleaf tools to be used for Ars Nouveau's Tier 1 Spell Book. Sorry that the game didn't accept the items correctly.

## 3rd Party Contributors
As for people who *helped* me in the process of developing the modpack there's quite a few:

### Max - KubeJS
  * Thank you for fixing KubeJS Create for all the times I discovered bugs with it ;-;

### squoshi 
  * Check out their modpack Magna here: https://www.curseforge.com/minecraft/modpacks/magna
  * A personal note to squoshi: You'll probably never see this but sorry for annoying you (if I did)

### ChiefArug
  * Thank you for helping me and others extensively, especially providing an example of key map pairings

### Pie 
  * Also helped me with the above

### Reveter
  * Thank you for providing the following script when KubeJS wasn't respecting NBT tags of Patchouli books:

```js
onEvent('item.tooltip', event => {
    event.addAdvanced('patchouli:guide_book', ((item, advanced, text) => {
        if (!item.hasNBT()) return;
        if (item.nbt['patchouli:book'] == 'patchouli:tome_of_finality') {
            text.add(Component.lightPurple("Hi! Please craft this book, it's important. - Overseers of Finality"))
        }
    }))
})
```

### YT Mango (Mango is Me! on the KubeJS Discord)
  * Provided a this fix when I encountered a 1.19.2 KubeJS related issue.
```js
Array(9).fill('minecraft:coal_block').concat([Fluid.of('minecraft:lava', 250)])
```

### Lexxie Raven Black (Lady Lexxie Black on the KubeJS Discord)
  * Provided a script fix for the same problem above.
  * Helped during the KubeJS Create dark ages

### Tazz
  * Thank you for helping me understand how to use a for loop.

### EnigmaQuip
  * Explained why KubeJS and KubeJS Legacy were behaving differently. Future modpack devs, please read (if this is still the case in the future):
  ```
  Celeste, I was snooping your pack and you have a note in your wiki about not being able to use twilight tools for the ars spellbook in 1.18 due to kubejs. It is possible if you want to keep that recipe, the reason it works in 1.19 and not in 1.18 is due to a change in the way recipe ingredients in kubejs are setup. In 1.18 they strictly check nbt by default, so you need to ignore it so as to not worry about enchants or damage. While in 1.19 it ignores all nbt data by default and you need to tell it to check that data. If you wrap each twilight tool in Item.of("mod:id").ignoreNBT() your recipe will work again
  ```
  * Also helped during the KubeJS Create dark ages 

### TheBCWonder
  * Helped with the Flint and Steel durability not being used issue.

More importantly, thank you to the *awesome* mod developers. Will be writing a long list below.

## Create Team 
Literally the only reason I got back into Minecraft *and* got into scripting with KubeJS then later modpack development.
* simibubi
* kryppers
* dani.ase
* Jozufozu
* Pepper
* tterrag

## KubeJS
Thank you for making modpack development so easy. I can't imagine in a decade that this would have been achievable to the same degree. The amount of customization is insane.
* Lat
* Max

