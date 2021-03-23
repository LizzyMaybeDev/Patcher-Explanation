<div align = "center">

# Bug Fixes

</div>

- **Command Handling** - Fix Forge's command handler not Checking for a '/' at the start of a command. *default
- **Case Insensitive Commands** - Stop vanilla commands from forcing case sensitivity. *default
- **Arrow Lighting** - Stop arrows attached to an entity from messing up entity lighting.
- **Mouse Bind Fix** - Fixes an issue where keybinds bound to mouse buttons do not work in inventories. *default
- **Keep Shaders on Perspective change** - Keep vanilla shaders you're currently using while also being able to toggle perspective. *default
- **Better Keybind Handling** - Make keys re-register when closing a GUI, like in 1.12+. *default
- **Parallax Fix** - Fix the camera being too far back, seemingly making your eyes be in the back of your head.
- **Culling Fix** - Fix false negatives in frustum culling, creating sometimes invisible Chunks. (Can negatively impact performance)
- **Layers In Tab** - Fixes sometimes players not having a hat layer on tab. *default	
- **Mouse Delay Fix** - Resolve an issue where your crosshair is a tick behind your head position. *default
- **Arm Rotations** - Resolve an issue where your arm rotation would be angled upwards when mounting an entity. *default
- **Head Rotations** - Resolve an issue where your head would not properly rotate while riding an entity. *default
- **Player Void Rendering** - Remove the black box around the player while in the void. *default
- **Fluid Stitching** - Fix missing edges in fluids. "Requires Chunk reload (F3+a)". (May cause Z-Fighting against blocks that aren't full size). *default
- **Reset Death Timers** - Resolve an issue where changing the fullscreen state on the Game Over screen would lock the buttons. *default
- **Resource Exploit Fix** - Fix an exploit in 1.8 allowing servers to look through directories. *default
- **Fullscreen Fix** - Resolve an issue where you could not maximize the game once toggling fullscreen. *default
- **Sky Height** - Remove the flickering effect from the void when passing between Y level 63. *default

<div align = "center">

# Miscellaneous 

</div>

- **Remove Ground Foliage** - Stop plants/flower from rendering. (Requires chunk reload (F3+A)).
- **1.12 Farm Selection Boxes** - Replace the selection box for crops with the 1.12 variant. (Only works on hypixel & Singleplayer). *default
- **Fov Modifier** - Allow for modifying FOV change states.
- **Sprinting Fov** - Modify your FOV when sprinting.
- **Bow FOV** - Modify your FOV when pulling back a bow.
- **Speed Fov** - Modify your FOV when having the speed effect.
- **Slowness FOV** - Modify Your FOV when having the slowness effect.
- **Remove Water FOV** - Remove the change of FOV when underwater (Does not require FOV Modifier to be enabled)
- **Crosshair Perspective** - Remove the crosshair when in third person.
- **Log Optimizer** - Delete any files in the logs folder, as this usually can take up a lot of space. (These files are not recoverable once deleted).
- **Log Otimizer Amount** - Choose how many days old a file must be before deleted.
- **Better Camera** - Stop blocks such as grass and tall plants from affecting your FOV as done in 1.14+. *default
- **Better F1** - Hide nametags when in F1 mode.
- **Zoom Adjustment** - Scroll when using OptiFine's zoom to adjust the zoom level.
- **Zoom Smooth Camera** - Remove the smooth camera effect when using zoom.
- **Zoom Sensitivity** - Use a custom mouse sensitivity when zoomed. This is a percentage of your normal sensitivity.
- **Smooth Zoom Animation** - Add a smooth animation when you zoom in and out. - **Suggested by Pug#5853**
- **Smooth Scroll-to-Zoom Animation** - Add a smooth animation when you scroll in and out while zoomed.
- **Smooth Zoom Function** - Change the smoothing function used in the smooth zooming animation.
- **Toggle to Zoom** - Make OptiFine's zoom key a toggle instead of requiring you to hold it.
- **Simplify FPS Counter** - Remove the additions OptiFine L5 and above makes to the debug screen fps counter. *default
- **Nausea Effect** - Remove the nether portal appearing when clearing nausea.
- **Disable Achievements** - Remove achievement notification.
- **Fire Overlay Height** - Change the height of the fire overlay.
- **Remove Water Overlay** - Remove the water texture overlay when underwater.
- **Remove Inverted Colors from Crosshair** - Remove the inverted color effect on the crosshair.
- **Fullbright** - Remove lighting updates, increasing visibility. "Requires chunk reload (F3+A)". (Can positively impact performance). *default
- **Smart Fullbright** - Automatically Disable the Fullbright Effect when using OptiFine Shaders. (Requires Fullbright)
- **Show Own Nametag** - See your own nametag in third person.
- **Numerical Enchantments** - Use readable numbers instead of roman numerals on enchants. *default
- **Clean View** - Stop rendering your own potion effect particles.
- **Disable Breaking Particles** - Remove block breaking particles for visibility.
- **Alternate Text Shadow** - Change the text shadow to only move down rather than moving to the side.
- **Add Text Shadow to Nametags** - Render nametag with shadowed text.
- **Disable Text shadow** - Remove shadows from text. (Can positively impact performance).
- **Toggle Tab** - Hold tab open without needing to hold down the tab key.
- **Number Ping** - Show a readable ping number in tab instead of bars.
- **Windowed Fullscreen** - Implement Windowed Fullscreen in Minecraft allowing you to drag your mouse outside the window
- **Instant Fullscreen** (Windows Only) - Instant switching between full screen and non fullscreen modes. (Windowed Fullscreen must also be enabled for this to work).
- **Remove Screen Bobbing** - While using View Bobbing, only remove the view aspect but have the hand still - bounce around.

<div align = "center">

# Performance

</div>

- **Entity Culling** - Stop entities that aren't visible to the player from rendering. *default
- **Entity Culling Interval** - The amount of time in ms between occlusion checks for entities. Shorter periods are more costly toward performance but provide the most accurate information. Lower values recommended in competitive environments.
- **Smart Entity Culling** - Stop entity culling effect when using OptiFine shaders. (Due to the way OptiFine shaders work, we are unable to make Entity Culling compatible at this time). *Default
- **Don't Cull Player Nametags** - Render nametags even when the player and nametag are occluded.
- **Don't Cull Entity Nametags** - Render nametags even when the entity and nametag are occluded.
- **Don't Cull Armorstand Nametags** - Render nametags even when the armour stand is occluded.
- **Check Armorstand Rules** - Don't cull armorstands that have a marker set in their entity rules. This will result in a lot of unculled armorstands in places like Hypixel Skyblock, but will provide better entity visibility, while losing out on some performance improvements.
- **Particle Culling** - Stop particles that aren't visible to the player from rendering. *default
- **Disable Armorstands** - Stop armorstands from rendering (Armorstands are commonly used for npc nametag rendering. Enabling this will stop those from rendering as well).
- **Disable Semitransparent Players** - Stop semitransparent players from rendering.
- **Disable Enchantment Books** - Stop enchantment table books from rendering.
- **Disable Item Frames** - Stop item frames from rendering.
- **Disable Mapped Item frames** - Stop item frames only with maps as their item from rendering.
- **Disable Grounded Arrows** - Stop arrows that are in the ground from rendering.
- **Disable Attached Arrows** - Stop arrows that are attached to a player from Rendering. 
- **Disable Attached Arrows** - Stop arrows that are attached to a player from Rendering. 
- **Disable Skulls** - Stop skulls from rendering. 
- **Disable Nametags Boxes** - Remove the transparent box around the nametag. 
- **Entity Render Distance Toggle** - Toggle allowing a custom entity render distance.
- **Entity Render Distance** - Stop rendering entities outside of the specified radius.
- **Disable End Portals** - Stop end portals from rendering.
- **Disable Enchantment Glint** - Disable the enchantment glint on enchanted items/potions.
- **Disable Gl Error Checking** - Disable unnecessary constant checking for errors in OpenGL. (Requires restart once toggled). *default
- **Optimized Resource Pack Discovery** - Optimize the time it takes to open the resource packs GUI. (Does not work with Labymod's RP24 addon). *default
- **Item Searching** - Stop items from searching for extra items to combine with when the stack is already full. *default
- **Optimized Item Renderer** - Cache information about items, avoiding recalculating everything about it every frame. *default
- **Static Particle Color** - Disable particle lighting checks each frame. *default
- **Downscale Pack Images** - Change all pack icons to 64x64 to reduce memory usage. *default
- **Optimized Font Renderer** - Use modern rendering techniques to improve font renderer performance. *default
- **Cache Font Data** - Cache font data allowing for it to be reused multiple times before needing recalculation. *default
- **Instant World Swapping** - Remove the dirt screen and waiting time when switching a world. *default
- **Limit Chunk Updates** - Limit the amount of chunk updates that happen a second.
- **Chunk Update Limit** - Specify the amount of updates that can happen a second.  
- **Static Fog Color** - Simplify fog color creation with a static fog color. *default
- **Low Animation Tick** - Lowers the amount of animations that happen a second from 1000 to 500. *default
- **Batch Model Rendering** - Render models in a single draw call, reducing the amount of OpenGL instructions performed a second. *default
- **Optimized Cloud Renderer** - Use modern rendering techniques to improve cloud renderer performance. *default
- **Remove Cloud Transparency** - Remove transparency from clouds.
- **Disable Mob Spawning** - Reduce memory usage by disabling the check for mob spawning despite the set game rule. (this will disable mob spawning in singleplayer).

<div align = "center">

# Screens

</div>

- **Transparent Chat** - Remove the background from chat. (Can positively impact performance).
- **Transparent Chat input field** - Remove the background from chat's input field. (Can positively impact performance).
- **Compact Chat** - Clean up chat by stacking duplicate messages (Does not work with Labymod). *default
- **Compact Chat time** - Change how long before old messages are no longer compacted. (Measured in seconds.)
- **Anti Clear Chat** - Remove blank messages from chat.
- **Shift Chat** - Holding shift while pressing enter will keep chat open.
- **Chat Position** - Move the chat up 12 pixels to stop it from overlapping the health bar, as done in 1.12+.
- **Chat Timestamps** - Add timestamps before a message.
- **Chat Timestamps Format** - Change the time format of Chat Timestamps, Examples: [3:24 PM] Steve: Hey!, [15:24] Steve: Hey!
- **Cross Chat** - Stop clearing chat when switching servers. *default
- **Chat Keeper** - Keep chat when toggling fullscreen. *default
- **Safe Chat Clicks** - Show the commmand or link that is ran/opened on click. 
- **Damage Glance** - View the damage value of the currently held item above your hotbar. *default
- **Item Count Glance** - View the amount of the currently held item above your hotbar. *default
- **Enchantment Glance** - View the enchantments of the currently held item above your hotbar. *default
- **Protection Percentage** - View how much total armor protection you have inside of your inventory. *default
- **Projectile Protection Percentage** - View how much total projectile protection you have inside of your inventory. *default
- **Container Backgrounds** - Remove the dark background inside of a container.
- **GUI Crosshair** - Stop rendering the crosshair when in a GUI.
- **Startup Notification** - Notify how long the game took to startup with a notification *default
- **Clean Main Menu** - Remove the Realms button on the main menu as you need to be on the latest Mnecraft version to use Realms. *default
- **Skin Refresher** - Add a button to the escape menu to refresh your current skin without needing to leave the server. (Also accessible with the command "/refreshskin").
- **Replace Open to Lan** - Remove the Open to Lan button when in multiplayer server with a button to quickly open your server list. (Will be reworked in the future to not kick you from the server).
- **Replaced Mods Warning** - Display on startup what mods you may have that are replaced by Patcher. *default
- **Smart Disconnect -** Choose between disconnecting or relogging when clicking the disconnect button. (Only works on multiplayer servers).
- **Image Preview** - Preview image links when hovering over a supported URL. Press shift to use fullscreen Control to render in native image resolution. (Currently supported: Imgur, Discord, Badlion screenshots).
- **Image Preview Width** - The % of screen width to be used for image preview.
- **Inventory Position** - Stop potion effects from shifting your inventory to the right. *default
- **Custom Tab Opacity** - Change the tab list opacity.
- **Tab Opacity** - Allow for customizing tab opacity.
- **Tab Height** - Move the tab overlay down n amount of pixels when there's an active bossbar.
- **Set Tab Height** - Choose how many pixels down the tab will go when there's an active bossbar

<div align = "center">

# Screenshot

</div>

- **Compact Response** - Compact the message given when screenshotting.
- **No Feedback** - Remove the messages from screenshots entirely.
- **Screenshot Manager** - Change the way screenshotting works as a whole, creating a whole new process to screenshotting such as uploading to imgur, copying to clipboard, etc. *default
- **Auto Copy Screenshot** - Automatically copy screenshots to the clipboard when taken
- **Screenshot Preview** - Preview the look of your screenshot when taken in the bottom right corner.
- **Preview Time** - Adjust how long the preview should stay on screen before sliding out. time is measured in seconds.
- **Preview Animation** - Select an animation style for the screenshot preview. 
- **Preview Scale** - Change the scale of the preview. smaller number is bigger.

<div align = "center">

# Patcher FunFacts

</div>

- **Fastchat**, **Fast Language Swap**, **Better Keybind Handling** pretty much all **OptiFine zoom stuff** were added by Llamalad7 along with fixing ssmanager by making it take priority over VanillaEnhancements since it completely broke it

- [**Patcher**] was originally called tweaker as a project [Asbyth](https://github.com/asbyth/) the now main patcher developer was working on and then introduced tweaker 2.0 and Patcher which was then superseded by the now known patcher which has been worked on in the span of an entire year and more to come in the future.

- **Fire Overlay Height** - option was originally named Fire Height then got renamed with the release of Patcher 1.1 beta 1

- **Downscale Pack Images** - option was originally named Pack Images then later on got renamed with the release of Patcher 1.1 beta 7

- With the release of Patcher 1.1 beta 9 they Renamed /blacklist to /pblacklist and Removed /history alias to name history later on in Patcher 3 beta 16 they Renamed /name to /pname due to it potentially messing up normal server/client commands

- In Patcher 3 beta 14 the disable armorstands option's description was extended to note that this setting will also disable most NPC names on most servers due to a ton of idiots complaining 

- In Patcher 1.3.1 beta 1 the Blaze Culling Algorithm was released which performs some extra checks to see if entities are hidden behind others to not render anything to later on get removed in 
Patcher 1.4 beta 1 then integrated in entity culling after it being redone in Unknown Patcher Version

- Speaking of Patcher 1.4 beta 1 this version had 24+ vanilla bugs that were reported there is others that were unreported including the hitbox rendering of Cactus after x/z +/// 1677216, and other related floating precision point issues.

- In Patcher 1.4 beta 6 the file size got reduce by an incredible amount from 3.3mb to ~600kb by asbyth requesting permission from sk1er to bundle coroutines and caffeine then removing them from the Patcher jar

- In Patcher 1.5 beta 3 they Removed Chunk Lighting Fix due to complaints of stuttering

- /coords was changed to /sendcoords in a Patcher 1.5 beta after the user Microcontrollers complained about it being first in tab complete ahead of /coordshud

- The Compact Chat rewrite and Limit Chunk Updates were pretty much done by [Moulberry](moulberry.codes/)
---
## Patcher has 49 Default options and 136 options in general, 16 of those are bug fixes, (note that those are the only bug fixes that you can enable and disable there is over 70 bug fixes which are force enabled) 41 QOL features and 41 Performance features (note that again those are the only visible ones) and Patcher also [replaces](https://github.com/LunaNotdev/Patcher-Explanation#mods-patcher-replaces) 17 mods

## Nonconfigurable Patcher Options

- **Scoreboard Patch** - which fixed log spam but now is force enabled 
- **Scoreboard Optimization** - Render the whole scoreboard in one draw call, rather than creating a separate rectangle for every score, which at the time wasnt compatible with Powns & Canelex's scoreboard mod.
- **Disable Constant Fog Color Checking** - still a thing but renamed to static fov color which simplifies fog color creation with a static fog color.
- **Startup Optimization** - Don't refresh resources twice during startup.
- **PathFinding optimization** (Cleanup blockaccess once processed).
- **TileEntity optimization** (Cleanup removable tile//entities).
- **Cleanup resources when leaving a world**, fixing a vanilla OpenGL buffer leak.
- **Optimizations made to GameRules$Value and EntityOtherPlayerMP**.
- **Improve faster annotation searching**.
- **Rewrote data table search**.
- **Fix typo in Forge's mod list** by changing "Search:\\" to "Search:".
- **Note that this is all public information and there is many many stuff that are in the code but are not made public**.

## Known Planned Features for Patcher

- **Entity backface culling** -  Hides parts of the entity model that you cant see.
- **Chat timestamps on hover** - Show timestamp for messages when you hover over them like [this](https://i.imgur.com/pR3aDv4.png) **(this isnt a concrete example its just to show the idea of what the final feature might look like)**
- **Fixed Entity Culling trying to cull particles causing some performance issues**
- **The ability to change entity render distance separately per category, globally, players, hostile mobs, passive mods**
- **Fix Scoreboard fix not fixing Scoreboard log spam bug**
- **1.12.2 Farm Selection Boxes now supports the hypixel.io IP**
- **Fix z-fighting issues with fluid stitching**
- **Fix some [formatting issues](https://media.discordapp.net/attachments/485175582854873132/799656306599919636/unknown.png)**
- **Fixed some [smooth lighting issues](https://media.discordapp.net/attachments/728064513605369866/820918408643870720/unknown.png)**
- **Port chat send delay** - Port the new [chat send delay feature](https://imgur.com/a/ewt6Gq1) from newer Minecraft versions.
- **Improvements related to resource pack discovery menu** - Unknown.
- **Improvements related to resource pack loading** - Uses vanilla's resource pack loading instead of forge's.
- **Horse transparency when riding it** - Like [this](https://media.discordapp.net/attachments/411620521382510592/803366568658337812/unknown.png) and [this](https://media.discordapp.net/attachments/411620521382510592/803369980405219388/unknown.png) .
-  **Added unfocused fps & sound volume** - Lower FPS and sound when the game is unfocused.
- **Fixed DebugFPS feature killing performance** - The feature to debug fps significantly [drops fps](https://media.discordapp.net/attachments/728064513605369866/820912978500386866/unknown.png) by a ton and it's now fixed: [Line responsible](https://media.discordapp.net/attachments/411620521382510592/801545071568748584/unknown.png), [Before](https://media.discordapp.net/attachments/411620521382510592/801550165474541630/unknown.png), [After](https://media.discordapp.net/attachments/411620521382510592/801550190536294470/unknown.png).
- **Renamed anti clear chat to remove blank messages** - Self explanatory.
- **Renamed container backgrounds to remove container backgrounds** - Self explanatory.
- **Reworked a lot of option descriptions** - Unknown
- **Force enabled some options** - For example Disable GL Error Checking, head rotations, sky height, mouse bind fix, arrow lighting, fluid stitching, fullscreen fix, reset death timers, command handling, mouse delay fix, arm rotation, item searching, cross chat, chat keeper, particle culling, static fog color, optimized resourcepack discovery.
- **Removed disable mob spawning** - It was useless.
- **Fixed parallax fix from removing crosshair on F3** - Self explanatory.
- **Clicking out of containers** - The ability to click out of guis instead of having to press esc etc...

## Mods Patcher Replaces

- **[CaseCommands](https://sk1er.club/mods/case_commands)** - Sk1er LLC

- **[CommandPatcher](https://sk1er.club/mods/command_patcher)** - Sk1er LLC

- **[CompactChat](https://sk1er.club/mods/compactchat)** - Sk1er LLC

- **[CrossChat](https://sk1er.club/mods/cross_chat)** - Sk1er LLC

- **[Frames+](https://frames.sk1er.club/)** - Sk1er LLC

- **[ItemOptimizations](https://sk1er.club/mods/item_optimization)** - Sk1er LLC

- **[MouseBindFix](https://sk1er.club/mods/mousebindfix)** - Sk1er LLC

- **[ResourceExploitFix](https://sk1er.club/mods/resourceexploitfix)** - Sk1er LLC

- **[WindowedFullscreen](https://sk1er.club/mods/sk1er_fullscreen)** - Sk1er LLC

- **[CleanView](https://www.curseforge.com/minecraft/mc-mods/cleanview)** - LainMI

- **[FastChat](https://2pi.pw/mods/fastchat)** - 2Pi

- **[MemoryFix](https://prplz.io/memoryfix/)** - prplz

- **[MouseDelayFix](https://prplz.io/mousedelayfix/)** - prplz

- **[NoCloseMyChat](https://hypixel.net/threads/forge-modification-noclosemychat-for-mc-1-8.1260752/)** - Cecer

- **[VanillaEnhancements](https://www.curseforge.com/minecraft/mc-mods/vanilla-enhancements)** - OrangeMarshall

- **[VoidChat](https://skyerzz.com/minecraft/mods/voidchat/)** - skyerzz

- **[BetterScaledGUI](https://www.youtube.com/watch?v=E1VsQ3-xkF8)** - Moulberry

- **[Fullbright](https://www.curseforge.com/minecraft/mc-mods/fullbright)** - Unknown

# Credits to [Asbyth](https://gist.github.com/asbyth/bcdb67d8f0ed18878c3916f15f4ddf9b)
<div align = "center">

# The End.

</div>
