# Alpha 1.0.16.05_20 (Cypress) Deobfuscated

## Alpha 1.0.16.05_20 Client

### New version of decompilation is available as files marked with the "NEW_" tag.

ext1605_20_**client**_**de**obfuscated.jar - deobfuscated, compiled source code. (**Can not** run in launcher, **can not** be decompiled by RetroMCP)

ext1605_20_**client**_**re**obfuscated.jar - source code compiled and reobfuscated with [RetroMCP](https://github.com/MCPHackers/RetroMCP-Java). (No sounddata, freerun and ZM worlds) (**Runable** in launcher, **can be** decompiled by RetroMCP)
**Full reobfuscated jar (With sounddata, freerun and ZM worlds) can be found in the "Releases".**

For deobfuscation I used modified version of [RetroGuard](https://github.com/FMG793/RetroGuard-Modded) and [Enigma](https://github.com/FabricMC/Enigma).

For decompilation I used [Fernflower](https://github.com/fesh0r/fernflower)

### [Deobfuscation And Decompilation Tutorial.](Decompilation_Tutorial.md)

## Alpha 1.0.16.05_20 Server

ext1605_20_**server**_**de**obfuscated.jar - deobfuscated, compiled source code. (**Can not** be run, **can not** be decompiled by RetroMCP)

ext1605_20_**server**_**re**obfuscated.jar - source code compiled and reobfuscated with [RetroMCP](https://github.com/MCPHackers/RetroMCP-Java). (**Runable**, **can be** decompiled by RetroMCP)

# Mods
## Alpha 1.0.16.05_20 Client
### Build-in ModLoader is broken. Fix available in the "mods" folder.
### ModLoader fix for new version of decompilation available in the "mods_NEW" folder.
Cypress uses modified version of ModLoader for Alpha 1.2.6.

You can port mods from Alpha 1.1.2_01 up to Beta 1.2_01 or create your own. (You can port mods from Beta 1.2_02 and above, but significant modification is needed)

## Alpha 1.0.16.05_20 Server
### Server TileEntities is broken. (Freezer doesn't freeze, furnace doesn't smelt) Fix available in the "server_mods" folder.
### ModLoader for server available in the "server_mods" folder.

Server uses modified version of ModLoader for Beta 1.2_02.

# Mod List
## All of the mods for server available in the "server_mods" folder.
## All of the mods in the "mods" folder are incompatible with new version of decompilation. Compatible mods available in the "mods_NEW" folder.
## All of the mods I've ported or created available in the "mods" folder.

- Iron Chest

![Iron Chest](/images/ironchest.png)
![Iron Chest Recipes](/images/ironchest_recipes.png)

Adds 5 new chests with extended capacity.

(Requires "Scots Tools API")

- Scots Tools API

API that allows you to create custom tools more easily and add harvesting level to your blocks

(More detailed instructions can be found in the Scots Tools API archive)

- Starving

![Starving](/images/Starving.png)

Adds a hunger bar that can be replenished by food.
(It's recommended to use this mod with "Splinter", because you can't replenish your health)

- Splinter

![Splinter](/images/Splinter.png)
![Splinter Recipes](/images/Splinter_recipes.png)

Adds items that can heal you.

- 303 Arrows

![Arrows](/images/arrows.png)
![Arrows Recipes](/images/arrows_recipes.png)

Adds arrows with various properties.

- Machetes

![Machetes](/images/machetes.png)
![Machetes Recipes](/images/machetes_recipes.png)

Adds machetes that can break leaves and cloth fast.

(Requires "Scots Tools API")

# Mod installation guide

1) Open ext1605_20_client with WinRAR or 7z
2) Open mod archive with WinRAR or 7z
3) Drag and drop mod contents into the ext1605_20_client
4) Close ext1605_20_client
5) Done, you can run Minecraft
