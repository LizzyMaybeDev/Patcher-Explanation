# Bug Fixes
- **Layers In Tab** - Fixes sometimes players not having a hat layer on tab. *default	Parallax Fix // Fix the camera being too far back, seemingly making your eyes be in the back of your head.
- **Culling Fix** - Fix false negatives in frustum Culling, creating sometimes invisible Chunks. (Can negatively impact performance)
- **Case Insensitive Commands** - Stop Vanilla commands from forcing case sensitivity. *default
Head Rotations // Resolve an issue where your head would not properly rotate while riding an Entity. *default
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
