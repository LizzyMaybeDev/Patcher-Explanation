# Patcher Features

<details>
  <summary>Bug Fixes</summary>

# Bug Fixes
- **Command Handling** - Fix Forge's command handler not checking for a '/' at the start of a command. *default
- **Case Insensitive Commands** - Stop vanilla commands from forcing case sensitivity. *default
- **Arrow Lighting** - Stop arrows attached to an entity from messing up entity lighting.
- **Mouse Bind Fix** - Fixes an issue where keybinds bound to mouse buttons do not work in inventories. *default
- **Keep Shaders on Perspective change** - Keep vanilla shaders you're currently using while also being able to toggle perspective. *default
- **Better Keybind Handling** - Make keys re-register when closing a GUI, like in 1.12+. *default
- **Parallax Fix** - Fix the camera being too far back, seemingly making your eyes be in the back of your head.
- **Culling Fix** - Fix false negatives in frustum culling, creating invisible chunks in some cases. (Can negatively impact performance)
- **Layers In Tab** - Fixes sometimes players not having a hat layer on tab. *default
- **Mouse Delay Fix** - Resolve an issue where your crosshair is a tick behind your head position. *default
- **Arm Rotations** - Resolve an issue where your arm rotation would be angled upwards when mounting an entity. *default
- **Head Rotations** - Resolve an issue where your head would not properly rotate while riding an entity. *default
- **Player Void Rendering** - Remove the black box around the player while in the void. *default
- **Fluid Stitching** - Fix missing edges in fluids. “Requires Chunk reload (F3+a)”. (May cause Z—Fighting against blocks that aren't full size). *default
- **Reset Death Timers** - Resolve an issue where changing the fullscreen state on the Game Over screen would lock the buttons. *default
- **Resource Exploit Fix** - Fix an exploit in 1.8 allowing servers to look through directories. *default
- **Fullscreen Fix** - Resolve an issue where you could not maximize the game once toggling fullscreen. *default
- **Sky Height** - Remove the flickering effect from the void when passing between Y level 63. *default
</details>
<details>
  <summary>Miscellaneous</summary>

# Miscellaneous
- **Remove Ground Foliage** - Stop plants/flower from rendering. (Requires chunk reload (F3+A)).
- **1.12 Farm Selection Boxes** - Replace the selection box for crops with the 1.12 variant. (Only works on hypixel & Singleplayer). *default
- **FOV Modifier** - Allow for modifying FOV change states.
- **Sprinting FOV** - Modify your FOV when sprinting.
- **Bow FOV** - Modify your FOV when pulling back a bow.
- **Speed FOV** - Modify your FOV when having the speed effect.
- **Slowness FOV** - Modify Your FOV when having the slowness effect.
- **Remove Water FOV** - Remove the change of FOV when underwater (Does not require FOV Modifier to be enabled)
- **Crosshair Perspective** - Remove the crosshair when in third person.
- **Log Optimizer** - Delete all files in the logs folder, as these can usually take up a lot of space. (These files are not recoverable once deleted).
- **Log Optimizer Amount** - Choose how many days old a file must be before being deleted.
- **Better Camera** - Stop blocks such as grass and tall plants from affecting your FOV as done in 1.14+. *default
- **Better F1** - Hide nametags when in F1 mode.
- **Remove Screen Bobbing** - While using View Bobbing, only remove the view aspect but have the hand still bounce around. - **Suggested by [Akinsoft](https://www.youtube.com/channel/UCNMigEMQWTYEsRThvKYfoMQ)**
- **Zoom Adjustment** - Scroll when using OptiFine's zoom to adjust the zoom level.
- **Zoom Smooth Camera** - Remove the smooth camera effect when using zoom.
- **Zoom Sensitivity** - Use a custom mouse sensitivity value when zoomed in. This is a percentage of your normal sensitivity.
- **Smooth Zoom Animation** - Add a smooth animation when you zoom in and out. - **Suggested by Pug#5853**
- **Smooth Scroll-to-Zoom Animation** - Add a smooth animation when you scroll in and out while zoomed.
- **Smooth Zoom Function** - Change the smoothing function used in the smooth zooming animation.
- **Toggle to Zoom** - Make OptiFine's zoom key a toggle instead of requiring you to hold it. - **Suggested by [Microcontrollers#6733](https://canary.discord.com/channels/411619823445999637/411620521382510592/727392685563838475) / [Twens#9340](https://canary.discord.com/channels/411619823445999637/411620521382510592/768100485210177556) / [me](https://inv.wtf/firedotexe)**
- **Simplify FPS Counter** - Remove the additions OptiFine L5 and above makes to the debug screen fps counter. *default
- **Nausea Effect** - Remove the nether portal effect appearing when clearing nausea.
- **Disable Achievements** - Remove achievement notification.
- **Fire Overlay Height** - Change the height of the fire overlay.
- **Remove Water Overlay** - Remove the water texture overlay when underwater.
- **Remove Inverted Colors from Crosshair** - Remove the inverted color effect on the crosshair.
- **Fullbright** - Remove lighting updates, increasing visibility. “Requires chunk reload (F3+A)”. (Can positively impact performance). *default
- **Smart Fullbright** - Automatically Disable the Fullbright Effect when using OptiFine Shaders. (Requires Fullbright). - Suggested by [jacob#9999](https://canary.discord.com/channels/411619823445999637/411620521382510592/761567628388335626)
- **Show Own Nametag** - See your own nametag in third person.
- **Numerical Enchantments** - Use readable numbers instead of Roman numerals on enchants. *default
- **Clean View** - Stop rendering your own potion effect particles.
- **Disable Breaking Particles** - Remove block breaking particles for visibility.
- **Alternate Text Shadow** - Change the text shadow to only move down rather than moving to the side. - **Suggested by [Aktimoose#3001](https://canary.discord.com/channels/411619823445999637/411620521382510592/762279014303662090) with a [visual example](https://media.discordapp.net/attachments/411620521382510592/762279100915908629/unknown.png)**
- **Add Text Shadow to Nametags** - Render nametag with shadowed text. - **Suggested by [Twens#9340](https://canary.discord.com/channels/411619823445999637/411620521382510592/705408054920871966) / [4Fluffin#2181](https://canary.discord.com/channels/411619823445999637/411620521382510592/712753614497644634) / [LRX#6974](https://canary.discord.com/channels/411619823445999637/411620521382510592/743866604088983563)**
- **Disable Text shadow** - Remove shadows from text. (Can positively impact performance).
- **Toggle Tab** - Hold tab open without needing to hold down the tab key.
- **Number Ping** - Show a readable ping number in tab instead of bars.
- **Windowed Fullscreen** - Implement Windowed Fullscreen in Minecraft allowing you to drag your mouse outside the window
- **Instant Fullscreen** (Windows Only) - Instant switching between full screen and non fullscreen modes. (Windowed Fullscreen must also be enabled for this to work).
  
</details>
<details>
  <summary>Performance</summary>

# Performance
- **Entity Culling** - Stop entities that aren't visible to the player from rendering. *default
- **Entity Culling Interval** - The amount of time in ms between occlusion checks for entities. Shorter periods are more costly toward performance but provide the most accurate information. Lower values recommended in competitive environments.
- **Smart Entity Culling** - Stop entity culling effect when using OptiFine shaders. (Due to the way OptiFine shaders work, we are unable to make Entity Culling compatible at this time). *Default - **Suggested by [Twens#9340](https://canary.discord.com/channels/411619823445999637/411620521382510592/761634374361546763) / Already planned when [Microcontrollers#6733](https://canary.discord.com/channels/411619823445999637/411620521382510592/762373914167869440) Suggested it**
- **Don't Cull Player Nametags** - Render nametags even when the player and nametag are occluded.
- **Don't Cull Entity Nametags** - Render nametags even when the entity and nametag are occluded.
- **Don't Cull Armorstand Nametags** - Render nametags even when the armour stand is occluded.
- **Check Armorstand Rules** - Don't cull armorstands that have a marker set in their entity rules. This will result in a lot of unculled armorstands in places like Hypixel Skyblock, but will provide better entity visibility while losing out on some performance improvements.
- **Particle Culling** - Stop particles that aren't visible to the player from rendering. *default
- **Disable Armorstands** - Stop armorstands from rendering (armorstands are commonly used for NPC nametag rendering. Enabling this will stop those from rendering as well).
- **Disable Semitransparent Players** - Stop semitransparent players from rendering.
- **Disable Enchantment Books** - Stop enchantment table books from rendering.
- **Disable Item Frames** - Stop item frames from rendering.
- **Disable Mapped Item frames** - Stop item frames only with maps as their item from rendering. - **Suggested by [Duel#0969](https://canary.discord.com/channels/411619823445999637/411620457754787841/765679834118357034) / [DJtheRedstoner#6408](https://canary.discord.com/channels/411619823445999637/411620521382510592/766016290938683415)**
- **Disable Grounded Arrows** - Stop arrows that are in the ground from rendering.
- **Disable Attached Arrows** - Stop arrows that are attached to a player from Rendering. 
- **Disable Skulls** - Stop skulls from rendering. 
- **Disable Nametags Boxes** - Remove the transparent box around the nametag. 
- **Entity Render Distance Toggle** - Toggle allowing a custom entity render distance.
- **Entity Render Distance** - Stop rendering entities outside a specified radius.
- **Disable End Portals** - Stop end portals from rendering.
- **Disable Enchantment Glint** - Disable the enchantment glint on enchanted items/potions.
- **Disable Gl Error Checking** - Disable unnecessary constant checking for errors in OpenGL. (Requires restart once toggled). *default
- **Optimized Resource Pack Discovery** - Optimize the time it takes to open the resource packs GUI. (Does not work with Labymod's RP24 addon). *default - **I'd like to feel like I inspired this**
- **Item Searching** - Stop items from searching for extra items to combine with when the stack is already full. *default
- **Optimized Item Renderer** - Cache information about items, avoiding recalculating everything about it every frame. *default
- **Static Particle Color** - Disable particle lighting checks each frame. *default
- **Downscale Pack Images** - Change all pack icons to 64x64 to reduce memory usage. *default
- **Optimized Font Renderer** - Use modern rendering techniques to improve font renderer performance. *default
- **Cache Font Data** - Cache font data allowing for it to be reused multiple times before needing recalculation. *default
- **Instant World Swapping** - Remove the dirt screen and waiting time when switching a world. *default
- **Limit Chunk Updates** - Limit the amount of chunk updates that happen a second. - **Was planned, wasn't able to implement until [Moulberry](https://github.com/moulberry/) presented a way, public suggester is [Darkr#4233](https://canary.discord.com/channels/411619823445999637/411620521382510592/776726232162893844) [and](https://canary.discord.com/channels/411619823445999637/411620457754787841/776865329086464040) [and](https://canary.discord.com/channels/411619823445999637/411620521382510592/783764217869369376) / Geek#8405 (?)**
- **Chunk Update Limit** - Specify the amount of updates that can happen a second.  
- **Static Fog Color** - Simplify fog color creation with a static fog color. *default
- **Low Animation Tick** - Lowers the amount of animations that happen a second from 1000 to 500. *default
- **Batch Model Rendering** - Render models in a single draw call, reducing the amount of OpenGL instructions performed a second. *default
- **Optimized Cloud Renderer** - Use modern rendering techniques to improve cloud renderer performance. *default - Alternative explanation: **[Upload cloud geometry to the GPU, resulting in much faster cloud rendering](https://twitter.com/asbythh/status/1249024695846023168).**
- **Remove Cloud Transparency** - Remove transparency from clouds.
- **Disable Mob Spawning** - Reduce memory usage by disabling the check for mob spawning despite the set game rule. (this will disable mob spawning in single player).
  
</details>
<details>
  <summary>Screens</summary>

# Screens
- **Transparent Chat** - Remove the background from chat. (Can positively impact performance).
- **Transparent Chat input field** - Remove the background from chat's input field. (Can positively impact performance).
- **Compact Chat** - Clean up chat by stacking duplicate messages (Does not work with Labymod). *default
- **Compact Chat time** - Change the amount of time old messages take to stop being compacted. (Measured in seconds.)
- **Anti Clear Chat** - Remove blank messages from chat.
- **Shift Chat** - Holding shift while pressing enter will keep chat open.
- **Chat Position** - Move the chat up 12 pixels to stop it from overlapping the health bar, as done in 1.12+.
- **Chat Timestamps** - Add timestamps before a message.
- **Chat Timestamps Format** - Change the time format of Chat Timestamps, Examples: [3:24 PM] Steve: Hey!, [15:24] Steve: Hey!
- **Cross Chat** - Stop clearing chat when switching servers. *default
- **Chat Keeper** - Keep chat when toggling fullscreen. *default
- **Safe Chat Clicks** - Show the command or link that is ran/opened on click. 
- **Damage Glance** - View the damage value of the currently held item above your hotbar. *default
- **Item Count Glance** - View the amount of the currently held item above your hotbar. *default
- **Enchantment Glance** - View the enchantments of the currently held item above your hotbar. *default
- **Protection Percentage** - View how much total armor protection you have inside of your inventory. *default
- **Projectile Protection Percentage** - View how much total projectile protection you have inside of your inventory. *default
- **Container Backgrounds** - Remove the dark background inside of a container.
- **GUI Crosshair** - Stop rendering the crosshair when in a GUI.
- **Startup Notification** - Notify how long the game took to startup with a notification *default
- **Clean Main Menu** - Remove the Realms button on the main menu as you need to be on the latest Mnecraft version to use Realms. *default
- **Skin Refresher** - Add a button to the escape menu to refresh your current skin without needing to leave the server. (Also accessible with the command “/refreshskin”).
- **Replace Open to Lan** - Remove the Open to Lan button when in multiplayer server with a button to quickly open your server list. (Will be reworked in the future to not kick you from the server).
- **Replaced Mods Warning** - Display on startup what mods you may have that are replaced by Patcher. *default
- **Smart Disconnect -** Choose between disconnecting or relogging when clicking the disconnect button. (Only works on multiplayer servers). - **Suggested by [Pug#5853](https://canary.discord.com/channels/411619823445999637/411620521382510592/705222390338158682)**
- **Image Preview** - Preview image links when hovering over a supported URL. Press shift to use fullscreen and Control to render in native image resolution. (Currently supported: Imgur, Discord, Badlion screenshots).
- **Image Preview Width** - The % of screen width to be used for image preview.
- **Inventory Position** - Stop potion effects from shifting your inventory to the right. *default
- **Custom Tab Opacity** - Change the tab list opacity.
- **Tab Opacity** - Allow for customizing tab opacity.
- **Tab Height** - Move the tab overlay down n amount of pixels when there's an active bossbar.
- **Set Tab Height** - Choose how many pixels down the tab will go when there's an active bossbar
  
</details>
<details>
  <summary>Screenshots</summary>

# Screenshots
- **Compact Response** - Compact the message given when screenshotting.
- **No Feedback** - Remove the messages from screenshots entirely.
- **Screenshot Manager** - Change the way screenshotting works as a whole, creating a whole new process to screenshotting such as uploading to imgur, copying to clipboard, etc. *default
- **Auto Copy Screenshot** - Automatically copy screenshots to the clipboard when taken - **Suggested by [mdash#0001](https://canary.discord.com/channels/411619823445999637/411620521382510592/772087167488622603) / DJtheRedstoner#6408 had a [similar suggestion](https://canary.discord.com/channels/411619823445999637/411620521382510592/770318489012928552) so dont get confused with both**
- **Screenshot Preview** - Preview the look of your screenshot when taken in the bottom right corner.
- **Preview Time** - Adjust how long the preview should stay on screen before sliding out. time is measured in seconds.
- **Preview Animation** - Select an animation style for the screenshot preview.
- **Preview Scale** - Change the scale of the preview. smaller number is bigger.

</details>

# Other

<details>
  <summary>Nonconfigurable Patcher Settings</summary>
 
# Nonconfigurable Patcher Settings
- **1.9 Skin Support** - Allow for transparency on secondary skin layers, as done in 1.9+.
- **Async Block & Item Loading** - **Register blocks & items at the same time instead of one after another.**
- **Async Mod Loading** - Unknown.
- **Cleanup resources when leaving a world**, fixing a vanilla OpenGL buffer leak.
- **Clear out stored errors after model loading finishes** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/pull/4938).
- **Disable Constant Fog Color Checking** - still a thing but renamed to static fov color which simplifies fog color creation with a static fog color.
- **Faster fluid checking** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/commit/5a48ca99b6787c7f811045d1f98b26db6ce073b7#diff-a27ff85fc320f1d8269b133701c1c5b2).
- **Fix bleeding text color, causing several rendering issues with transparent HUD elements.**
- **Fix keybinds being loaded too early, resolving issues with mods that use Mixins on KeyBinding.**
- **Fix Minecraft sometimes never saving options**.
- **Fix the player not hearing when their own armor breaks**.
- **Fix the possible crash on opening the server menu**.
- **Fix the possible crash when connecting a server quickly**.
- **Fix typo in Forge's mod list** by changing “Search:\\” to “Search:”.
- **Fix typo in sky rendering causing tons of BlockPos allocations** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/pull/3267).
- **Fix Unclosed Server Stream** - Release server icons buffer, fixing a memory leak.
- **Fix unclosed stream in AnvilChunkLoader** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/pull/5766).
- **Fix unclosed stream in GuiModList** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/pull/5766).
- **Force Chat History Length to always be 32767**.
- **Force tooltips to render above potion effects**.
- **Head Optimization** - Cache custom head layers, improving performance.
- **Implement new fast-graphics leaf culling** - [Before](https://cdn.discordapp.com/attachments/530585040120315924/747852737856798800/2020-08-25_12.14.06.png), [After](https://cdn.discordapp.com/attachments/530585040120315924/747852760241799168/2020-08-25_12.18.34.png).
- **Improve faster annotation searching**.
- **OptiFine I7-M5:** Resolve OptiFine causing resourcepacks that edit the XP bar color to be the Vanilla color. (Credits: DJtheRedstoner)
- **OptiFine L5-L6:** Resolve horses sometimes never rendering, and hitting said horse would cause the screen to have a red tint. (Credits: rbrick & DJtheRedstoner)
- **OptiFine L5-L6:** Resolve signs flickering while editing them, such as the Hypixel Skyblock Banker's signs. (Credits: DJtheRedstoner)
- **OptiFine L5-L6:** Resolve wither particles following your crosshair when using L5 or above. (Credits: DJtheRedstoner)
- **OptiFine L5-M5:** Resolve a duplicate & useless "Alternate Blocks" button in the Details menu. (Credits: DJtheRedstoner)
- **Optimizations made to GameRules$Value and EntityOtherPlayerMP**.
- **Optimizations regarding PathFinding memory leak, BlockEntities removal, Resource loading, Entity capability checks, GameRules, and other players**.
- **Optimizations related to armorstands & player states**
- **Optimized character stripping** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/pull/3907).
- **Optimized Lightmap Updates**.
- **Optimized Model Rendering**.
- **Optimized Particle Collision**.
- **Optimized Skin Loading** - Reduce the amount of stutter when loading into a world with a lot of players, caused by fetching the skin file and applying it. (Credits: [Moulberry](https://github.com/moulberry/))
- **PathFinding optimization** - Cleanup blockaccess once processed.
- **Persistent Chunk Check Performance** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/pull/5706).
- **ReflectionOptimizations** - Unknown.
- **Remove the "Unable to locate sign at (coords)" message from chat**.
- **Resolve Minecraft sometimes never saving options**.
- **Resource Optimization** - Cache resources to reduce loading startup & pack loading times.
- **Rewrote data table search**.
- **Save Chat when toggling fullscreen**.
- **Scoreboard Optimization** - Render the whole scoreboard in one draw call, rather than creating a separate rectangle for every score, which at the time wasnt compatible with Powns & Canelex's scoreboard mod.
- **Scoreboard Patch** - which fixed log spam but now is force enabled
- **Settings Enhancement** - Don't change mipmap levels until user leaves GUI, stopping accidental mipmap level changes & freezing the game as a result.
- **Show Patcher version in the F3 menu**.
- **Skip searching for mods in the JAVA_HOME directory** - [Forge optimization](https://github.com/MinecraftForge/MinecraftForge/commit/3a48a9cd731238c2a5f664362fb073732b426ef5#diff-9687ac6b081c5d4b560e95a42620a355)
- **Startup Optimization** - Don't refresh resources twice during startup.
- **Skylight performance being recalculated is very slow.**
- **Tab Overlay Ping draws with a shadow**.
- **TileEntity optimization** (Cleanup removable tile entities).
- **[MC-185](https://bugs.mojang.com/browse/MC-185)**: Creating or loading a singleplayer world shows the main menu for a brief second.
- **[MC-234](https://bugs.mojang.com/browse/MC-234)**: z-fighting when digging straight down.
- **[MC-417](https://bugs.mojang.com/browse/MC-417)**: arrows bounce back then appear at correct location.
- **[MC-1846](https://bugs.mojang.com/browse/MC-1846)**: player camera is too far back, making things appear the way they shouldnt. (Fixes -> Parallax Fix)
- **[MC-2781](https://bugs.mojang.com/browse/MC-2781)**: languages using Windows IME to type (chinese, korean, japanese, etc.) cannot speak in chat.
- **[MC-4647](https://bugs.mojang.com/browse/MC-4647)**: Having both underwater/Night vision and Blindness turns the world black.
- **[MC-5404](https://bugs.mojang.com/browse/MC-5404)**: Name Tags/XP Orbs/Splash Potions are angled in third-person mode.
- **[MC-10480](https://bugs.mojang.com/browse/MC-10480)**: Blindness + Night-vision Effects Create Complete Blindness.
- **[MC-11519](https://bugs.mojang.com/browse/MC-11519)** & **[MC-50304](https://bugs.mojang.com/browse/MC-50304)**: collecting too much xp could act as an epilepsy trigger & experience orbs are too low to the ground.
- **[MC-31222](https://bugs.mojang.com/browse/MC-31222)**: Crash when pressing a Hotbar slot key & leaving the GUI at the same time.
- **[MC-35714](https://bugs.mojang.com/browse/MC-35714)**: Sounds duplicate when entering/leaving a GUI.
- **[MC-49628](https://bugs.mojang.com/browse/MC-49628)**: When in spectator mode the head overlay shows even if it is set not to show in the skin customisation options.
- **[MC-51150](https://bugs.mojang.com/browse/MC-51150)**: Swimming in water, riding a minecart or standing on soul sand and snow layers 8 darkens the sky at day time.
- **[MC-58177](https://bugs.mojang.com/browse/MC-58177)**: Night vision rendered darker and orange when nearing light sources with brightness on moody.
- **[MC-58614](https://bugs.mojang.com/browse/MC-58614)**: xp bar isnt transparent when crosshair isnt visible.
- **[MC-63020](https://bugs.mojang.com/browse/MC-63020)** & **[MC-70850](https://bugs.mojang.com/browse/MC-70850)**: False-negatives in frustum culling, leaving empty spots in chunks.
- **[MC-67017](https://bugs.mojang.com/browse/MC-67017)**: The small cube in slime blocks isn't displayed in inventory and when dropped.
- **[MC-67406](https://bugs.mojang.com/browse/MC-67406)**: Small armor stands display items differently than normal ones.
- **[MC-68381](https://bugs.mojang.com/browse/MC-68381)**: NullPointerException: group when connecting to MP server.
- **[MC-71990](https://bugs.mojang.com/browse/MC-71990)**: In tab list, spectators and distant players are always hatless.
- **[MC-72397](https://bugs.mojang.com/browse/MC-72397)**: Alex Model Displays Items Incorrectly.
- **[MC-72494](https://bugs.mojang.com/browse/MC-72494)**: In Statistics screen 'm' is the same unit for both minutes and meters.
- **[MC-74764](https://bugs.mojang.com/browse/MC-74764)**: Particle "largeexplode", "hugeexplosion" and “sweepattack” not showing when using the front view. (twice F5)
- **[MC-76899](https://bugs.mojang.com/browse/MC-76899)**: Dragging items with the middle mouse button causes block count to go negative.
- **[MC-77759](https://bugs.mojang.com/browse/MC-77759)**: The game takes a screenshot when pressing the "<|>" key on foreign keyboards.
- **[MC-80966](https://bugs.mojang.com/browse/MC-80966)**: Lightcalculation of ChunkSelection faulty implemented resulting in client bugs. (empty chunks don’t show light/render dark)
- **[MC-81738](https://bugs.mojang.com/browse/MC-81738)**: Crash: IndexOutOfBoundsException on Tesselating block in world.
- **[MC-81876](https://bugs.mojang.com/browse/MC-81876)**: Number of characters before line cutoff in chat is not same when unicode mode is enabled and when it is off.
- **[MC-84774](https://bugs.mojang.com/browse/MC-84774)**: Cobblestone wall fence gate facing south has different texture mapping. (uvlock tag issue)
- **[MC-85132](https://bugs.mojang.com/browse/MC-85132)**: Leaves are not culled in fast mode.
- **[MC-86385](https://bugs.mojang.com/browse/MC-86385)**: Leading zeroes omitted on dyed leather armor colour.
- **[MC-90560](https://bugs.mojang.com/browse/MC-90560)**: Custom Payload Packet Memory Leak.
- **[MC-92057](https://bugs.mojang.com/browse/MC-92057)**: particles/entities at y>=256 are dark.
- **[MC-94535](https://bugs.mojang.com/browse/MC-94535)**: Flying and holding CTRL really close to the ground, emits walking particles.
- **[MC-98093](https://bugs.mojang.com/browse/MC-98093)**: Distorted Pistons.
- **[MC-101233](https://bugs.mojang.com/browse/MC-101233)**: burned out Redstone torch map causes a memory leak..
- **[MC-117412](https://bugs.mojang.com/browse/MC-117412)**: Heightmap min value not set when loading chunk from NBT.
- **[MC-121884](https://bugs.mojang.com/browse/MC-121884)**: Server->Client custom payload packets can leak resources.
- **Note that this is all public information and there is many many stuff that are in the code but are not made public.**
</details>
<details>
  <summary>Patcher FunFacts</summary>

# Patcher FunFacts
- Patcher has 49 Default options and 136 options in general, 16 of those are bug fixes, (note that those are the only bug fixes that you can enable and disable there is over 70 bug fixes which are force enabled) 41 QOL features and 41 Performance features (note that again those are the only visible ones) and Patcher also [replaces](https://github.com/LunaNotdev/Patcher-Explanation#mods-patcher-replaces) 17 mods.
- **Fastchat**, **Better Keybind Handling**, pretty much all **OptiFine zoom stuff** were added by Llamalad7 along with fixing ssmanager by making it take priority over VanillaEnhancements since it completely broke it.
- **Patcher fixes not only vanilla bugs but even other mod's bugs** suprisingly enough patcher fixes forge bugs and vanilla bugs and even optifine bugs.
- **Patcher** was originally called tweaker as a project [Asbyth](https://github.com/asbyth/) the now main patcher developer was working on and then introduced tweaker 2.0 and Patcher which was then superseded by the now known patcher which has been worked on in the span of an entire year and more to come in the future.
- **Save Chat when toggling fullscreen** was added by UserTeemu.
- **Downscale Pack Images** - Used to upscale packs to 64x if they were less than 64x. - reported by [me](https://inv.wtf/firedotexe)
- **Resource Exploit Fix** - Had a problem where servers were actually able to workaround which was later on fixed in an unknown patcher version. - Reported by Unknown
- **Old /FOV** - Many people believe the /fov command had unlimited posibilities which isnt true, the command actually has a limit which is /fov 340282356779733661637539395458142568447. - Discovery by [me](https://inv.wtf/firedotexe "i need serious help")
- Patcher fixes an issue with the sun sometimes being black when using a Powns mod.
- **Optimized Resource Packs Menu** - Is force disabled with the presence of labymod as the developers of the RP24 addon have no intentions of fixing their addon because it does things very poorly.
- **Fire Overlay Height** - option was originally named Fire Height then got renamed with the release of Patcher 1.1 beta 1.
- **Downscale Pack Images** - option was originally named Pack Images then later on got renamed with the release of Patcher 1.1 beta 7.
- With the release of Patcher 1.1 beta 9 they renamed /blacklist to /pblacklist and removed /history alias to name history later on in Patcher 1.3 beta 16 they renamed /name to /pname due to it potentially messing up normal server/client commands.
- In Patcher 1.1 they added optimizations regarding TileEntities, PathFinding memory leak, BlockEntities removal, Resource loading, Entity capability checks, GameRules, and other players.
- In Patcher 1.3 beta 14 the disable armorstands option's description was extended to note that this setting will also disable most NPC names on most servers due to a ton of idiots complaining.
- In Patcher 1.3 they fixed the annoying Vanilla bug that would crash the game when closing a GUI and pressing a hotbar key slot at the same time.
- In Patcher 1.3 they moved commands such as /patchersounds to /patcher sounds, /name to /patcher name, /pblacklist to /patcher blacklist.
- In Patcher 1.3.1 beta 1 the Blaze Culling Algorithm was released which performs some extra checks to see if entities are hidden behind others to not render them to later on get removed in Patcher 1.4 beta 1 then integrated in entity culling after it being redone in Unknown Patcher Version.
- In Patcher 1.4 they fixed over 40 vanilla bugs.
- In Patcher 1.4 they rewrote Entity Culling to use Depth Buffer Sampling, resulting in much better culling performance.
- Speaking of Patcher 1.4 beta 1 this version had 24+ vanilla bugs that were reported there is others that were unreported including the hitbox rendering of Cactus after x/z + 1677216, and other related floating precision point issues here's [some](https://github.com/LunaNotdev/Patcher-Explanation/#nonconfigurable-patcher-settings).
- In Patcher 1.4 beta 6 the file size got reduce by an incredible amount from 3.3mb to ~600kb by asbyth requesting permission from sk1er to bundle coroutines and caffeine then removing them from the Patcher jar.
- In Patcher 1.5 beta 3 they Removed Chunk Lighting Fix due to complaints of stuttering.
- /coords was changed to /sendcoords in a Patcher 1.5 beta after the user Microcontrollers complained about it being first in tab complete ahead of /coordshud.
- The Compact Chat rewrite and Limit Chunk Updates were pretty much done by [Moulberry](https://github.com/moulberry/).
- In Patcher 1.5 they forced max FOV through /fov to be 110 to stop things from being broken when too high.
- In Patcher 1.5 the Name History menu was completely redesigned.
</details>
<details>
  <summary>Known Planned Features for Patcher</summary>
 
# Known Planned Features for Patcher
- **Entity backface culling** -  Hides parts of the entity model that you cant see.
- **Chat timestamps on hover** - Show timestamp for messages when you hover over them like [this](https://i.imgur.com/pR3aDv4.png) **(this isnt a concrete example its just to show the idea of what the final feature might look like)**.
- **Fixed Entity Culling trying to cull particles causing some performance issues**.
- **The ability to change entity render distance separately per category, globally, players, hostile mobs, passive mobs**.
- **Fix Scoreboard fix not fixing Scoreboard log spam bug**.
- **1.12.2 Farm Selection Boxes now supports the hypixel.io IP**.
- **Fix z-fighting issues with fluid stitching** - As seen [here](https://i.imgur.com/EOxQKKD.png).
- **Fix some [formatting issues](https://media.discordapp.net/attachments/485175582854873132/799656306599919636/unknown.png)**.
- **Fixed some [smooth lighting issues](https://media.discordapp.net/attachments/728064513605369866/820918408643870720/unknown.png)**.
- **Port chat send delay** - Port the new [chat send delay feature](https://imgur.com/a/ewt6Gq1) from newer Minecraft versions.
- **Improvements related to resource pack discovery menu** - Unknown.
- **Improvements related to resource pack loading** - Uses vanilla's resource pack loading instead of forge's.
- **Horse transparency when riding it** - Like [this](https://media.discordapp.net/attachments/411620521382510592/803366568658337812/unknown.png) and [this](https://media.discordapp.net/attachments/411620521382510592/803369980405219388/unknown.png).
- **Added unfocused fps & sound volume slider** - Lower FPS and sound when the game is unfocused.
- **Fixed DebugFPS feature killing performance** - The feature to debug fps significantly [drops fps](https://media.discordapp.net/attachments/728064513605369866/820912978500386866/unknown.png) by a ton and it's now fixed: [Line responsible](https://media.discordapp.net/attachments/411620521382510592/801545071568748584/unknown.png), [Before](https://media.discordapp.net/attachments/411620521382510592/801550165474541630/unknown.png), [After](https://media.discordapp.net/attachments/411620521382510592/801550190536294470/unknown.png).
- **Renamed anti clear chat to remove blank messages** - Self explanatory.
- **Renamed container backgrounds to remove container backgrounds** - Self explanatory.
- **Reworked a lot of option descriptions** - Unknown
- **Force enabled some options** - For example Disable GL Error Checking, Head Rotations, Sky Height, MouseBindFix, Arrow Lighting, Fluid Stitching, Fullscreen Fix, Reset Death Timers, Command Handling, MouseDelayFix, Arm Rotation, Item Searching, Cross Chat, Chat Keeper, Particle Culling, Static Fog Color, Optimized Resourcepack Discovery.
- **Removed disable mob spawning** - It was useless.
- **Fixed parallax fix from removing crosshair on F3** - Self explanatory.
- **Clicking out of containers** - The ability to click out of guis instead of having to press esc etc...
- **Remove optifine's custom ALT+F3** - Self explanatory.
- **Fix crashing issue with hychat** - Self explanatory.
- **Opacity silder for chat transparency instead of the current option**. - Current option is just transparency with no configurable slider, that will change in the next version(s).
- **Cache current CPU information** - Unknown.
- **Save a bit of rendering time** - Unknown.
- **Save chatbox content when closed** - For when you're randomly warped the text you were typing in the chatbox gets saved.
- **Resolve issues with commands that have casing in them** - any command with a case in its name broke because of the case insensitive commands feature, that will change in the next version(s).
- **Disable view bobbing effect when holding map** - Self explanatory.
- **Linux LWJGL key registration fix** - Fixes a LWJGL bug causing incorrect registration of Shift+2 and Shift+6 on Linux systems.
- **Fix shadows on sized withers** - Properly scale shadows on withers that are not the default size.
- **Hide projectiles for a few frames after thrown** - Hides snowballs, eggs, ender pearls, ender eyes, splash potions, exp bottles, and firework rockets for a few frames after being thrown to prevent them from taking up a majority of the screen.
</details>
<details>
  <summary>Mods Patcher Replaces</summary>

# Mods Patcher Replaces
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

- **[BetterScaledGUI](https://www.youtube.com/watch?v=E1VsQ3-xkF8)** - [Moulberry](https://github.com/moulberry/)

- **[Fullbright](https://www.curseforge.com/minecraft/mc-mods/fullbright)** - Unknown

</details>

# Credits to

- [asbyth](https://github.com/asbyth/) and [Sk1erLLC](https://github.com/sk1erllc) for making this awesome mod and the “[mods it replaces](https://gist.github.com/asbyth/bcdb67d8f0ed18878c3916f15f4ddf9b "Mods Patcher Replaces")” part and a TON of other things that i took which i forgot.
- [SirNapkin1334](https://github.com/sirnapkin1334) for having a cool readme that I can steal from.
- [Chachy](https://github.com/ChachyDev), [Microcontrollers](https://www.youtube.com/watch?v=dQw4w9WgXcQ), [Proudmuslim](https://github.com/proudmuslim-dev) for contributing.
<div align = "center">

# The End.

</div>

![big monkey](https://user-images.githubusercontent.com/37629791/115776153-195e8e00-a3b4-11eb-8ff5-bb5569de8848.png)

