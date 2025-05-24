# SoopyV2

**SoopyV2** is an essential ChatTriggers module providing powerful utilities, APIs, and GUI components used by other SkyBlock-related scripts. It is not a standalone script but a **required dependency** that must be installed manually.

## Installation

> ⚠️ This module **cannot** be installed via `/ct import`. Manual installation is required:

1. Download ChatTriggers:

   https://chattriggers.com/

2. Open your ChatTriggers modules folder (or just do /ct files ingame):  
   - Windows: `%appdata%/.minecraft/config/ChatTriggers/modules`  
   - macOS/Linux: `~/.minecraft/config/ChatTriggers/modules`

3. Extract the archive and move the folder into the modules directory. 

4. Restart Minecraft or run `/ct reload` in-game.

## Features

- 🧠 High-performance internal logic (math, timers, interpolation)  
- 🖼️ Interactive GUI framework (menus, buttons, sliders)  
- 🛰️ Utilities for packet handling and rendering  
- 🔌 Extensible APIs for advanced script development

For developers:  
```js
const gui = new SoopyGuiElement();
// or use other classes/functions provided by SoopyV2
