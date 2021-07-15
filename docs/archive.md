# Archive

Mods that were removed because they became obsolete, were abandoned, or no longer fit the pack. This file preserves the reason for each decision so the same projects do not need to be researched repeatedly.

## Abandoned

| Project | Last noted version | What it does | Reason archived |
| --- | --- | --- | --- |
| [Adaptive Brightness](https://www.curseforge.com/minecraft/mc-mods/adaptive-brightness) | 1.18 | Adjusts brightness dynamically. | No longer maintained. |
| [AFKTape](https://www.curseforge.com/minecraft/mc-mods/afktape) | 1.16.5 | Automates input while the player is AFK. | No longer maintained. |
| [AntiGhost](https://modrinth.com/mod/antighost) | 1.20.4 | Resynchronizes ghost blocks with the server. | No longer maintained. |
| [Audio Output](https://www.curseforge.com/minecraft/mc-mods/audio-output) | 1.17 | Allows the audio output device to be changed in-game. | No longer maintained. |
| [Auto Torch](https://www.modrinth.com/mod/auto-torch/versions) | 1.19.2 | Places torches automatically. | No longer maintained. |
| [Beenfo](https://modrinth.com/mod/beenfo) | 1.20.4 | Displays information about beehives. | No longer maintained. |
| [Better Foliage](https://www.curseforge.com/minecraft/mc-mods/better-foliage) | 1.16.5 | Enhances foliage rendering. | No longer maintained. |
| [Better World List](https://www.curseforge.com/minecraft/mc-mods/better-world-list) | 1.16.5 | Improves the world-selection screen. | No longer maintained. |
| [ClickThrough](https://modrinth.com/mod/clickthrough) | 1.20.4 | Allows interaction through item frames or signs. | No longer maintained. |
| [Don't Clear Chat History](https://modrinth.com/mod/dcch) | 1.20.1 | Preserves chat across reconnects or screen changes. | No longer maintained. |
| [Don't Drop It!](https://modrinth.com/mod/HcVOCzMh) | 1.16.4 | Prevents accidental item drops. | No longer maintained. |
| [EasierCrafting](https://modrinth.com/mod/easiercrafting) | 1.20.4 | Simplifies crafting interactions. | No longer maintained. |
| [EasierVillageTrading](https://modrinth.com/mod/easiervillagertrading) | 1.20.1 | Simplifies repeated villager trades. | No longer maintained. |
| [Fabripresence](https://modrinth.com/mod/fabripresence) | 1.16.5 | Adds Discord Rich Presence. | No longer maintained. |
| [FlightHelper](https://modrinth.com/mod/flighthelper) | 1.20.4 | Assists with elytra flight. | No longer maintained. |
| [Head-down Display](https://modrinth.com/mod/hdd) | 1.16.4 | Adds HUD information. | No longer maintained. |
| [HUDTweaks](https://www.curseforge.com/minecraft/mc-mods/hudtweaks) | 1.18.1 | Customizes HUD elements. | No longer maintained. |
| [Hydrogen](https://modrinth.com/mod/hydrogen/) | 1.17.1 | Reduces memory usage. | No longer maintained. |
| [Loading Timer](https://modrinth.com/mod/loading-timer) | 1.17.1 | Displays the game's loading time. | No longer maintained. |
| [MinimalMenu](https://modrinth.com/mod/minimalmenu) | 1.16.5 | Simplifies menus. | No longer maintained. |
| [Nicephore](https://www.curseforge.com/minecraft/mc-mods/nicephore-fabric) | 1.19.3 | Adds screenshot utilities. | No longer maintained. |
| [QuickCalc](https://modrinth.com/mod/quickcalc) | 1.17.1 | Adds an in-game calculator. | No longer maintained. |
| [QuickReplant](https://modrinth.com/mod/quickreplant) | 1.16.5 | Replants harvested crops. | No longer maintained. |
| [RandomPatches](https://modrinth.com/mod/randompatches) | 1.16.5 | Provides a collection of miscellaneous fixes. | No longer maintained. |
| [Recently Used](https://www.curseforge.com/minecraft/mc-mods/recently-used) | 1.16.5 | Tracks recently used items. | No longer maintained. |
| [Servers Plus](https://modrinth.com/mod/serversplus) | 1.16.5 | Expands the multiplayer server list. | No longer maintained. |
| [Sign Copy](https://www.curseforge.com/minecraft/mc-mods/signcopy) | 1.17 | Copies text between signs. | No longer maintained. |
| [Smarter HUD](https://www.curseforge.com/minecraft/mc-mods/smarter-hud) | 1.16.5 | Improves HUD behavior. | No longer maintained. |
| [WorldTime](https://modrinth.com/mod/worldtime) | 1.20.4 | Displays world time on the HUD. | No longer maintained. |

## Retired during the NeoForge 1.21.1 QC pass

These projects were removed from the migration queue after review because they were redundant, too small to justify a compatibility bridge, or covered by the active baseline.

| Project | What it does | Reason archived |
| --- | --- | --- |
| [Better Mount HUD](https://modrinth.com/mod/better-mount-hud) | Improves the HUD while riding a mount. | No compelling native 1.21.1 successor was found; the vanilla mount HUD is sufficient for the current pack. |
| [Accurate Block Placement Reborn](https://modrinth.com/mod/accurate-block-placement-reborn) | Removes the delay between placing blocks. | [Tweakerge](https://modrinth.com/mod/tweakerge) covers the intended accurate-placement workflow, so a separate placement mod is redundant. |
| [AutoSwitch](https://modrinth.com/mod/autoswitch) | Automatically selects the most suitable tool for a block. | [Inventory Profiles Next](https://modrinth.com/mod/inventory-profiles-next) remains the inventory owner; no compatible target file or demonstrated missing workflow justified adding another automation layer. |
| [ClearDespawn](https://modrinth.com/mod/cleardespawn) | Makes dropped items blink shortly before despawning. | No trustworthy native 1.21.1 continuation was found, and the feature is too small to justify a bridge. |
| [Cull Leaves](https://modrinth.com/mod/cull-leaves) | Improves leaf rendering in a style similar to OptiFine's Smart Leaves. | [More Culling](https://modrinth.com/mod/moreculling) already owns the relevant culling functionality in the active pack. |
| [Debugify](https://modrinth.com/mod/debugify) | Fixes numerous bugs from the Minecraft bug tracker. | Fabric-oriented and not worth adding through [Sinytra Connector](https://modrinth.com/mod/connector) alongside [ModernFix](https://modrinth.com/mod/modernfix) without a reproducible missing fix. |
| [Enhanced Block Entities](https://modrinth.com/mod/ebe) | Optimizes block-entity rendering. | No stable native 1.21.1 path was found; reconsider only if a benchmark demonstrates a real gap. |
| [Entity View Distance](https://modrinth.com/mod/entity-view-distance) | Adds configurable entity render distances. | Minecraft's built-in Entity Distance setting and Sodium controls cover the normal use case. |
| [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix) | Fixes known memory leaks. | [ModernFix](https://modrinth.com/mod/modernfix) already covers memory reduction and bug fixes; a separate legacy fix adds maintenance risk. |
| [More Chat History](https://modrinth.com/mod/morechathistory) | Increases retained local chat history. | Current NeoForge options are low-confidence relative to the small feature gain. |
| [Name Pain](https://modrinth.com/mod/namepain) | Tints entity name tags red when their health is low. | No compatible 1.21.x NeoForge file was available, and the extra combat nameplate information is not part of the baseline. |
| [Mouse Wheelie](https://modrinth.com/mod/mouse-wheelie) | Adds mouse-wheel inventory shortcuts. | [Inventory Profiles Next](https://modrinth.com/mod/inventory-profiles-next) remains the inventory owner; adding another broad inventory mod would create shortcut collisions. |
| [Slyde](https://modrinth.com/mod/slyde) | Allows sliders to exceed their normal limits. | Niche and potentially unsupported behavior is not worth carrying an uncertain port. |
| [Animatica](https://modrinth.com/mod/animatica) | Supports the OptiFine/MCPatcher animated-texture format. | No enabled resource pack currently requires it, so a compatibility bridge is not justified. |
| [Astrocraft](https://modrinth.com/mod/astrocraft) | Adds real-world stars and planets to the night sky. | Archived at the request of the current pack review; revisit only if a native sky-enhancement workflow is wanted. |
| [Particular](https://modrinth.com/mod/particular) | Adds ambient visual effects such as fireflies, falling leaves, and waterfall cascades. | Dropped from the current visual-effects plan; no separate particle suite is needed for the baseline. |
| [Charmonium](https://modrinth.com/mod/charmonium) | Adds ambient environmental sounds. | [AmbientSounds](https://modrinth.com/mod/ambientsounds) is the selected ambient bed, so a second broad ambience mod would be redundant. |
| [CIT Resewn](https://modrinth.com/mod/cit-resewn) | Supports OptiFine/MCPatcher custom item textures. | No enabled resource pack currently requires CIT, so the compatibility stack is not baseline material. |
| [Continue Button](https://modrinth.com/mod/continue) | Adds a button that resumes the most recently played world. | Small convenience feature; not worth retaining as an uncertain cross-loader candidate. |
| [DeathLog](https://modrinth.com/mod/deathlog) | Records the player's deaths and their details. | The active [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap)/[Xaero's World Map](https://modrinth.com/mod/xaeros-world-map) stack covers location recovery, while inventory snapshots are not a current requirement. |
| [Held Item Info](https://modrinth.com/mod/held-item-info) | Displays additional information about the held item. | Overlaps the active tooltip and information stack without a demonstrated missing workflow. |
| [Horse Stats Vanilla](https://modrinth.com/mod/horsestatsvanilla) | Displays horse statistics in the inventory. | Dropped from this migration pass; the current pack has no stated need for a dedicated horse-statistics overlay. |
| [Krypton](https://modrinth.com/mod/krypton) | Optimizes Minecraft networking. | No reproducible client-side benefit was established for this pack, and no native target file was available. |
| [Language Reload](https://modrinth.com/mod/language-reload) | Speeds up language reloads and adds language fallbacks. | No multilingual or frequent language-switching requirement is currently documented. |
| [Litematica](https://modrinth.com/mod/litematica) | Provides schematic viewing and building assistance. | Dropped from the current technical-building plan; no active schematic workflow requires it. |
| [No Nether Portal Overlay](https://modrinth.com/mod/no-nether-portal-overlay) | Removes the animated Nether portal overlay. | Minor visual preference without a native NeoForge 1.21.1 file; not worth a compatibility bridge. |
| [OptiGUI](https://modrinth.com/mod/optigui) | Supports OptiFine custom GUI resource packs. | No enabled resource pack currently requires OptiGUI rules, so it is not baseline material. |
| [Roughly Searchable](https://modrinth.com/mod/roughly-searchable) | Searches nearby storage contents through REI's search bar. | Dropped from the current workflow; the exact integration is not needed and no native target file was found. |
| [Amecs](https://modrinth.com/mod/amecs) | Adds modifier-key support and keybind search. | [Controlling](https://modrinth.com/mod/controlling) supplies the searchable keybind workflow; the pack does not retain Amecs's modifier semantics. |
| [MiniHUD](https://modrinth.com/mod/minihud) | Adds technical overlays and information displays. | [BoccHUD](https://modrinth.com/mod/bocchud) supplies the selected technical overlays with less overlap in the current HUD. |
| [Tweakeroo](https://modrinth.com/mod/tweakeroo) | Provides a broad set of configurable client-side tweaks. | [Tweakerge](https://modrinth.com/mod/tweakerge) is the selected replacement and covers the workflow intended by [Accurate Block Placement Reborn](https://modrinth.com/mod/accurate-block-placement-reborn). |
| [Fabrishot](https://modrinth.com/mod/fabrishot) | Captures screenshots at resolutions larger than the game window. | [Forgeshot](https://modrinth.com/mod/forgeshot) is the selected screenshot tool for this pack. |
| [Mixin Conflict Helper](https://modrinth.com/mod/mixin-conflict-helper) | Presents clearer errors when mods have Mixin conflicts. | [Crash Assistant](https://modrinth.com/mod/crash-assistant) and [Not Enough Crashes](https://modrinth.com/mod/notenoughcrashes) cover the current crash-diagnosis workflow. |

## Obsolete

| Project | Last noted version | What it does | Reason archived |
| --- | --- | --- | --- |
| [Damage Tilt](https://www.curseforge.com/minecraft/mc-mods/damage-tilt) | 1.19 | Restores the camera tilt shown when the player takes damage. | Superseded by the fix for MC-26678 in Minecraft 1.19.4 and newer. |
| [LazyDFU](https://modrinth.com/mod/lazydfu) | 1.20.6 | Defers unnecessary DataFixerUpper initialization to reduce startup time. | Its loading improvements are already present in newer Minecraft versions. |
| [Pling](https://modrinth.com/mod/pling) | 1.20.1 | Plays a sound when the game or a world finishes loading. | No target-loader continuation was found; [Seamless Loading Screen](https://modrinth.com/mod/seamless-loading-screen)'s startup sound option provides the same function. |
| [Smooth Boot](https://modrinth.com/mod/smoothboot-fabric) | 1.16.5 | Improves startup responsiveness and CPU scheduling. | Its relevant behavior was fixed in Minecraft 1.19.4 and newer. |
| [Starlight](https://github.com/Tuinity/Starlight) | 1.19 | Replaces Minecraft's lighting engine with a faster implementation. | Superseded by Minecraft's newer lighting engine. |
