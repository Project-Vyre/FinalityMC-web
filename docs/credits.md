---
title: Credits & Contributors
layout: default
nav_order: 4
---
This was just pasted over from the original GitHub repository wiki, I apologize for the formatting being rough around the edges.

# Music Credits
Please check out Cjbeards, very awesome music! [Cjbeards music is free use as mentioned here](https://docs.google.com/spreadsheets/d/1ZTM7nf4Uia19c-NQheqPnLAk1Bs6NS6XZiLt7Mk4Z1Q/edit#gid=0), but please check his [channel on YouTube.](https://www.youtube.com/channel/UCarvKz1XSCON68oeSZ1mlkg) I do not own any of his work or music. 
* [menu1.ogg] [Heart of the Wicked - Cjbeards](https://youtu.be/ZsKEZUgKaXg) {You may recognize this from FTB Legend of the Eyes.}
* [menu2.ogg] [From the Shadows - Cjbeards](https://youtu.be/m2IA-rXEKPk)
* [menu3.ogg] [Cubeponk - Cjbeards & Fayr](https://youtu.be/Id2LUBrnHh4)
* [menu4.ogg] [Mirror Mirror (Instrumental) - Cjbeards](https://youtu.be/u91uppHLfS4)
* [end.ogg] [Shattered Glass - Cjbeards](https://youtu.be/rjumdHtHU5U)
* [boss.ogg] [Brave the Storm - Cjbeards](https://youtu.be/dGmLKmxvJ0I)

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
* squoshi 
  * Check out their modpack Magna here: https://www.curseforge.com/minecraft/modpacks/magna
  * A personal note to squoshi: You'll probably never see this but sorry for annoying you (if I did)
* Reveter
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

More importantly, thank you to the *awesome* mod developers. Will be writing a long list below
