<div align = "center">

# Bug Fixes

</div>

- **Layers In Tab** - Fixes sometimes players not having a hat layer on tab. *default	
- **Parallax Fix** - Fix the camera being too far back, seemingly making your eyes be in the back of your head.
- **Culling Fix** - Fix false negatives in frustum Culling, creating sometimes invisible Chunks. (Can negatively impact performance)
- **Case Insensitive Commands** - Stop Vanilla commands from forcing case sensitivity. *default
- **Head Rotations** - Resolve an issue where your head would not properly rotate while riding an Entity. *default
- **Keep Shaders on Perspective change** - Keep Vanilla shaders you're currently using while also being able to toggle Perspective. *default
- **Resource Exploit Fix** - Fix an exploit in 1.8 allowing servers to look through directories. *default
- **Arrow Lighting** - Stop Arrows attached to an Entity from messing up Entity lighting.
- **Command Handling** - Fix Forge's command handler not Checking for a '/' at the start of a command. *default
- **Reset Death Timers** - Resolve an issue where changing the fullscreen state on the Game Over screen would lock the buttons. *default
- **Player Void Rendering** - Remove the black box around the player while in the void. *default
- **Fluid Stitching** - Fix missing edges in fluids. "Requires Chunk reload (F3+a)." (May cause Z-Fighting against blocks that aren't full size.) *default
- **Fullscreen Fix** - Resolve an issue where you could not maximize the game once toggling fullscreen. *default
- **Arm Rotations** - Resolve an issue where your arm rotation would be angled upwards when mounting an Entity. *default
- **Mouse Bind Fix** - Fixes an issue where keybinds bound to mouse buttons do not work in inventories. *default
- **Mouse Delay Fix** - Resolve an issue where your crosshair is a tick behind your head position. *default
<div align = "center">

# Performance

</div>

- **Disable Nametags Boxes** - Remove the transparent box around the nametag. 
- **Disable Mapped Item frames** - Stop item frames only with maps as their item from rendering
- **Disable Item Frames** - stop item frames from rendering
- **Disable Semitransparent Players** - Stop semitransparent players from rendering.
- **Disable Skulls** - Stop sakulls from rendering. 
- **Disable Armorstands** - Stop armorstands from rendering (Armorstands are commonly used for npc nametag rendering. enabling this will stop those from rendering as well).
- **Disable Enchantment Books** - Stop enchantment table books from rendering.
- **Disable Enchantment Glint** - Disable the enchantment glint on enchanted items/potions.
- **Disable Gl Error Checking** - Disable unnecessary constant checking for errors in OpenGL. (Requires restart once toggled.) *default
- **Disable End Portals** - Stop end portals from rendering.
- **Batch Model Rendering** - Render models in a single draw call, reducing the amount of OpenGL instructions performed a second. *default
- **Disable Mob Spawning** - Reduce memory usage by disabling the check for mob spawning despite the set game rule. (this will disable mob spawning in singleplayer)
- **Remove Cloud Transparency** - Remove transparency from clouds.
- **Static Fog Color** - Simplify fog color creation with a static fog color. *default
- **Low Animation Tick** - Lowers the amount of animations that happen a second from 1000 to 500. *default
- **Instant World Swapping** - Remove the dirt screen and waiting time when switching a world. *default
- **Chunk Update Limit** - Specify the amount of updates that can happen a second.  
- **Particle Culling** - Stop particles that aren't visible to the player from rendering. *default
- **Static Particle Color** - Disable particle lighting checks each frame. *default
- **Entity Culling** - Stop entities that aren't visible to the player from rendering. *default
- **Entity Culling Interval** - The amount of time in ms between occlusion checks for entities. Shorter periods are more costly toward performance but provide the most accurate information. Lower values recommended in competitive environments.
- **Smart Entity Culling** - Stop entity culling effect when using OptiFine shaders. (Due to the way OptiFine shaders work, we are unable to make Entity Culling compatible at this time). *Default
- **Don't Cull Player Nametags** - Render nametags even when the player and nametag are occluded. 
- **Don't Cull Entity Nametags** - Render nametags even when the entity and nametag are occluded.
- **Don't Cull Armorstand Nametags** - Render nametags even when the armour stand is occluded.
- **Check Armorstand Rules** - Don't cull armorstands that have a marker set in their entity rules. This will result in a lot of unculled armorstands in places like Hypixel Skyblock, but will provide better entity visibility, while losing out on some performance improvements.
- **Optimized Font Renderer** - Use modern rendering techniques to improve font renderer performance. *default
- **Optimized Cloud Renderer** - Use modern rendering techniques to improve cloud renderer performance. *default
- **Optimized Item Renderer** - Cache information about items, avoiding recalculating everything about it every frame. *default
- **Optimized Resource Pack Discovery** - Optimize the time it takes to open the resource packs GUI. (Does not work with Labymod's RP24 addon.) *default
- **Downscale Pack Images** - Change all pack icons to 64x64 to reduce memory usage. *default
- **Disable Attached Arrows** - Stop arrows that are attached to a player from Rendering. 
- **Disable Moving Arrows** - Stop arrows that are airborne from rendering.
- **Disable Grounded Arrows** - Stop arrows that are in the ground from rendering.
- **Disable Shadowed Text** - Remove shadows from text. (can positively improve performance.)
- **Cache Font Data** - Cache font data allowing for it to be reused multiple times before needing recalculation. *default
- **Entity Render Distance Toggle** - Toggle allowing a custom entity render distance
- **Entity Render Distance** - Stop rendering entities outside of the specified radius
- **Disable Breaking Particles** - Remove block breaking particles for visibility.
- **Item Searching** - Stop items from searching for extra items to combine with when the stack is already full. *default
<div align = "center">

# Miscellaneous 

</div>

- **Remove Screen Bobbing** - While using View Bobbing, only remove the view aspect but have the hand still - bounce around.
- **Better Camera** - Stop blocks such as grass and tall plants from affecting your FOV as done in 1.14+. *default
- **Crosshair Perspective** - Remove the crosshair when in third person.
- **Better F1** - Hide nametags when in F1 mode.
- **Remove Ground Foliage** - Stop plants/flower from rendering. (Requires Chunk reload (F3+A)).
- **Smooth Scroll-to-Zoom Animation** - Add a smooth animation when you scroll in and out while zoomed.
- **Smooth Zoom Animation** - Add a smooth animation when you zoom in and out.
- **Zoom Smooth Camera** - Remove the smooth camera effect when using zoom.
- **Zoom Sensitivity** - Use a custom mouse sensitivity when zoomed. this is a percentage of your normal sensitivity 
- **Smooth Zoom Function** - Change the smoothing function used in the smooth zooming animation.
- **Zoom Adjustment** - Scroll when using OptiFine's zoom to adjust the zoom level.
- **Toggle to Zoom** - Make OptiFine's zoom key a toggle instead of requiring you to hold it
- **Simplify FPS Counter** - Remove the additions OptiFine L5 and above makes to the debug screen fps counter. *default
- **Remove Water Overlay** - Remove the water texture overlay when underwater.
- **Show Own Nametag** - See your own nametag in third person.
- **Clean View** - Stop rendering your own potion effect particles.
- **Disable Text shadow** - Remove shadows from text. (Can positively impact performance).
- **Alternate Text Shadow** - Change the text shadow to only move down rather than moving to the side.
- **Add Text Shadow to Nametags** - Render nametag with shadowed text.
- **Numerical Enchantments** - Use readable numbers instead of roman numerals on enchants. *default
<div align = "center">

# Quality of Life

</div>

- **Fire Overlay Height** - Change the height of the fire overlay
- **Damage Glance** - View the damage value of the currently held item above your hotbar. *default
- **Item Count Glance** - View the amount of the currently held item above your hotbar. *default
- **Enchantment Glance** - View the enchantments of the currently held item above your hotbar. *default
- **Protection Percentage** - View how much total armor protection you have inside of your inventory. *default
- **Projectile Protection Percentage** - View how much total projectile protection you have inside of your inventory. *default
- **1.12 Farm Selection Boxes** - Replace the selection box for crops with the 1.12 variant. (Only works on hypixel & Singleplayer.) *default
- **Log Optimizer** - Delete any files in the logs folder. as this usually can take up a lot of space. (These files are not recoverable once deleted.)
- **Log Otimizer Amount** - Choose how many days old a file must be before deleted.
- **Image Preview** - Preview image links when hovering over a supported URL. Press shift to use fullscreen Control to render in native image resolution. (Currently supported: Imgur, Discord, Badlion screenshots.)
- **Image Preview Width** - The % of screen width to be used for image preview.
- **Disable Achievements** - Remove achievement notification.
- **Startup Notification** - Notify how long the game took to startup with a notification *default
- **Smart Disconnect -** Choose between disconnecting or relogging when clicking the disconnect button. (Only works on multiplayer servers.)
- **Nausea Effect** - Remove the nether portal appearing when clearing nausea.
- **Container Backgrounds** - Remove the dark background inside of a container.
- **Inventory Position** - Stop potion effects from shifting your inventory to the right. *default
- **Fov Modifier** - Allow for modifying FOV change states.
- **Sprinting Fov** - Modify your FOV when sprinting.
- **Bow FOV** - Modify your FOV when pulling back a bow.
- **Speed Fov** - Modify your FOV when having the speed effect.
- **Slowness FOV** - Modify Your FOV when having the slowness effect.
- **Remove Water FOV** - Remove the change of FOV when underwater (Does not require FOV Modifier to be enabled)
- **Remove Inverted Colors from Crosshair** - Remove the inverted color effect on the crosshair.
- **Clean Main Menu** - Remove the Realms button on the main menu as you need to be on the latest Mnecraft version to use Realms. *default
- **Skin Refresher** - Add a button to the escape menu to refresh your current skin without needing to leave the server. (Also accessible with the command "/refreshskin".)
- **GUI Crosshair** - Stop rendering the crosshair when in a GUI.
- **Replace Open to Lan** - Remove the Open to Lan button when in multiplayer server with a button to quickly open your server list. (Will be reworked in the future to not kick you from the server.)
- **Replaced Mods Warning** - Display on startup what mods you may have that are replaced by Patcher. *default
- **Better Keybind Handling** - Make keys re-register when closing a GUI, like in 1.12+. *default
- Fullbright - Remove lighting updates, increasing visibility. (Requires Chunk reload (F3+A)). (Can positively impact performance.) *default
- **Smart Fullbright** - Automatically Disable the Fullbright Effect when using OptiFine Shaders. (Requires Fullbright)
- **Sky Height** - Remove the flickering effect from the void when passing between Y level 63. *default
- **Tab Height** - Move the tab overlay down n amount of pixels when there's an active bossbar.
- **Set Tab Height** - Choose how many pixels down the tab will go when there's an active bossbar
- **Tab Opacity** - Allow for customizing tab opacity.
- **Custom Tab Opacity** - Change the tab list opacity.
- **Toggle Tab** - Hold tab open without needing to hold down the tab key.
- **Number Ping** - Show a readable ping number in tab instead of bars.
- **Instant Fullscreen** (windows only) - Instant switching between full screen and non fullscreen modes. (Windowed Fullscreen must also be enabled for this to work.)
- **Windowed Fullscreen** - Implement Windowed Fullscreen in Minecraft allowing you to drag your mouse outside the window
<div align = "center">

# Chat

</div>

- **Chat Keeper** - Keep chat when toggling fullscreen. *default
- **Chat Position** - Move the chat up 12 pixels to stop it from overlapping the health bar, as done in 1.12+.
- **Compact Chat** - Clean up chat by stacking duplicate messages (Does not work with Labymod.) *default
- **Compact Chat time** - Change how long before old messages are no longer compacted. (Measured in seconds.)
- **Cross Chat** - Stop clearing chat when switching servers. *default
- **Safe Chat Clicks** - Show the commmand or link that is ran/opened on click. 
- **Shift Chat** - Holding shift while pressing enter will keep chat open.
- **Transparent Chat** - Remove the background from chat. (Can positively impact performance)
- **Transparent Chat input field** - Remove the background from chat's input field. (Can positively impact performance) 
- **Anti Clear Chat** - Remove blank messages from chat.
- **Chat Timestamps** - Add timestamps before a message.
- **Chat Timestamps Format** - Change the time format of Chat Timestamps, Examples: [3:24 PM] Steve: Hey!, [15:24] Steve: Hey!
<div align = "center">

# Screenshot

</div>

- **No Feedback** - Remove the messages from screenshots entirely.
- **Compact Response** - Compact the message given when screenshotting.
- **Screenshot Manager** - Change the way screenshotting works as a whole, creating a whole new process to screenshotting such as uploading to imgur, copying to clipboard, etc. *default
- **Preview Time** - Adjust how long the preview should stay on screen before sliding out. time is measured in seconds.
- **Preview Scale** - Change the scale of the preview. smaller number is bigger.
- **Screenshot Preview** - Preview the look of your screenshot when taken in the bottom right corner.
- **Preview Animation** - Select an animation style for the screenshot preview. 
- **Auto Copy Screenshot** - Automatically copy screenshots to the clipboard when taken
---
## Patcher has 49 Default options and 136 options in general 16 of those are bug fixes (note that those are the only bug fixes that you can enable and disable there is over 70 bug fixes which are force enabled) 41 QOL features and 41 Performance features (note that again those are the only visible ones)

## Patcher also replaces 17 mods which are CaseCommands, CommandPatcher, CompactChat, CrossChat, frames+, ItemOptimizations, MouseBindFix, ResourceExploitFix, WindowedFullscreen, CleanView, FastChat ,MemoryFix, MouseDelayFix, NoCloseMyChat, VanillaEnhancements, VoidChat, BetterScaledGUI 

## Patcher also had/has options that arent in the config which are 

**Scoreboard Patch** - which fixed log spam but now is force enabled 

**Scoreboard Optimization** - Render the whole scoreboard in one draw call, rather than creating a separate rectangle for every score. which at the time wasnt compatible with Powns & Canelex's scoreboard mod.

**Disable Constant Fog Color Checking** - still a thing but renamed to static fov color which simplifies fog color creation with a static fog color.

**Startup Optimization** - Don't refresh resources twice during startup.

**PathFinding optimization** (Cleanup blockaccess once processed).

**TileEntity optimization** (cleanup removable tile//entities).

**Cleanup resources when leaving a world**, fixing a vanilla OpenGL buffer leak.

**Optimizations made to GameRules$Value and EntityOtherPlayerMP**.

**Fixed crippling performance issues with large amounts of particles caused by an improper obfuscation mapping**.

**Improve faster annotation searching**.

**Rewrote data table search**.

**Note that this is all public information and there is many many stuff that are in the code but are not made public**.

<div align = "center">

# Patcher FunFacts

</div>

- **Fastchat**, **Fast Language Swap**, **Better Keybind Handling** pretty much all **OptiFine zoom stuff** were added by Llamalad7 along with fixing ssmanager by making it take priority over VanillaEnhancements since it completely broke it

- **Fire Overlay Height** option was originally named Fire Height then got renamed with the release of Patcher 1.1 beta 1

- **Downscale Pack Images** option was originally named Pack Images then later on got renamed with the release of Patcher 1.1 beta 7

- With the release of Patcher 1.1 beta 9 they Renamed /blacklist to /pblacklist and Removed /history alias to name history later on in Patcher 3 beta 16 they Renamed /name to /pname due to it potentially messing up normal server/client commands

- In Patcher 3 beta 14 the disable armorstands option's description was extended to note that this setting will also disable most NPC names on most servers due to a ton of idiots complaining 

- In Patcher 1.3.1 beta 1 the Blaze Culling Algorithm was released which performs some extra checks to see if entities are hidden behind others to not render anything to later on get removed in 
Patcher 1.4 beta 1 then integrated in entity culling after it being redone in Unknown Patcher Version

- Speaking of Patcher 1.4 beta 1 this version had 24+ vanilla bugs that were reported there is others that were unreported including the hitbox rendering of Cactus after x/z +/// 1677216, and other related floating precision point issues.

- In Patcher 1.4 beta 6 the file size got reduce by an incredible amount from 3.3mb to ~600kb by asbyth requesting permission from sk1er to bundle coroutines and caffeine then removing them from the Patcher jar

- In Patcher 1.5 beta 3 they Removed Chunk Lighting Fix due to complaints of stuttering 
<div align = "center">

# The End.

</div>
