# Minecraft Client-Side Modlist

A client-side Minecraft modlist managed with [Pakku](https://juraj-hrivnak.github.io/Pakku/) for Minecraft 1.21.1 and 1.21.

NeoForge is the primary loader and Fabric is a secondary resolver target for projects that run through [Sinytra Connector](https://modrinth.com/mod/connector). Exports remain NeoForge-primary.

This README describes the current pack, its debug profile, and projects intentionally kept outside the baseline. The [Candidates](docs/candidates.md) file records future possibilities; the [Archive](docs/archive.md) file records retired or rejected projects.

## Current pack

### Performance baseline

The current performance baseline.

| Mod | What it does | Notes |
| --- | --- | --- |
| [BadOptimizations](https://modrinth.com/mod/badoptimizations) | Applies small optimizations outside the rendering pipeline. | |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Reduces resource use while Minecraft is unfocused or idle. | |
| [Sodium](https://modrinth.com/mod/sodium) | Replaces the rendering engine to improve client performance. | Its rendering/API support makes [Indium](https://modrinth.com/mod/indium) unnecessary. |
| [Entity Culling](https://modrinth.com/mod/entityculling) | Skips rendering entities and block entities hidden from view. | |
| [FerriteCore](https://modrinth.com/mod/ferrite-core) | Reduces memory usage. | |
| [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) | Optimizes immediate-mode rendering. | |
| [Iris Shaders](https://modrinth.com/mod/iris) | Loads OptiFine-compatible shader packs. | Requires Sodium. |
| [Lithium](https://modrinth.com/mod/lithium) | Optimizes game logic, ticking, and other internal systems. | |
| [ModernFix](https://modrinth.com/mod/modernfix) | Combines performance improvements, memory reductions, and bug fixes. | Covers the broad memory and bug-fix role that made [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix) unnecessary. |
| [More Culling](https://modrinth.com/mod/moreculling) | Adds additional rendering culling to improve performance. | Covers the leaf-culling use case; [Cull Leaves](https://modrinth.com/mod/cull-leaves) is not used separately. |
| [Not Enough Crashes](https://modrinth.com/mod/notenoughcrashes) | Makes crashes less disruptive and provides more useful recovery options. | |
| [Remove Reloading Screen](https://modrinth.com/mod/rrls) | Reloads resource packs in the background. | |

### Privacy

| Mod | What it does | Notes |
| --- | --- | --- |
| [No Telemetry](https://modrinth.com/mod/no-telemetry) | Suppresses Minecraft telemetry collection. | |
| [No Chat Reports](https://modrinth.com/mod/no-chat-reports) | Disables chat reporting where the server permits it. | |

### Interface and utility

Current interface and utility mods.

| Mod | What it does | Notes |
| --- | --- | --- |
| [AppleSkin](https://modrinth.com/mod/appleskin) | Displays hunger and saturation information. | |
| [Auto Fishing](https://modrinth.com/mod/x+-autofish) | Automatically fishes for the player. | |
| [Accessible Step](https://modrinth.com/mod/accessible-step) | Lets the player step up full blocks without jumping. | |
| [Better Advancements](https://modrinth.com/mod/better-advancements) | Enlarges the advancements screen and displays completion progress. | |
| [Better Ping Display](https://modrinth.com/mod/better-ping-display) | Shows numerical player ping values in the player list. | |
| [Chat Animation](https://modrinth.com/mod/chatanimation) | Animates incoming chat messages. | |
| [Chat Heads](https://modrinth.com/mod/chat-heads) | Displays player heads beside chat messages. | |
| [Cherished Worlds](https://modrinth.com/mod/cherished-worlds) | Allows worlds to be marked as favourites. | |
| [Controlling](https://modrinth.com/mod/controlling) | Adds a searchable, manageable keybind screen. | Provides the searchable keybind role of [Amecs](https://modrinth.com/mod/amecs); modifier semantics are intentionally omitted. |
| [Cubes Without Borders](https://modrinth.com/mod/cubes-without-borders) | Provides a configurable borderless fullscreen window. | Test with the Sodium video-settings screen. |
| [Crafting Tweaks](https://modrinth.com/mod/crafting-tweaks) | Adds convenience buttons to crafting interfaces. | |
| [Enchantment Descriptions](https://modrinth.com/mod/enchantment-descriptions) | Adds descriptions to enchanted books and enchantments. | |
| [Inventory Profiles Next](https://modrinth.com/mod/inventory-profiles-next) | Adds inventory sorting and automatic item and tool management. | |
| [InvMove](https://modrinth.com/mod/invmove) | Allows player movement while an interface is open. | |
| [Mod Menu (NeoForge Edition)](https://modrinth.com/mod/mod-menu-%28neoforge-edition%29) | Adds searchable mod management and config entry points. | |
| [Monsters in the Closet](https://modrinth.com/mod/monsters-in-the-closet) | Highlights nearby monsters when they prevent sleeping. | |
| [Roughly Enough Items](https://modrinth.com/mod/rei) | Provides item and recipe browsing. | |
| [Seamless Loading Screen](https://modrinth.com/mod/seamless-loading-screen) | Uses a screenshot of the world as its loading background. | Its startup sound option replaces [Pling](https://modrinth.com/mod/pling)'s loading chime. |
| [Shulker Box Tooltip](https://modrinth.com/mod/shulkerboxtooltip) | Shows shulker box contents in a tooltip. | |
| [Smooth Scroll](https://modrinth.com/mod/smooth-scroll) | Adds smooth scrolling to supported interface elements. | Runs through [Sinytra Connector](https://modrinth.com/mod/connector) as the pack's secondary Fabric project; NeoForge remains the primary export loader. |
| [Sound Physics Remastered](https://modrinth.com/mod/sound-physics-remastered) | Adds echo, occlusion, and environmental sound propagation. | |
| [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap) | Adds a minimap and waypoints. | |
| [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map) | Adds a full-screen map integrated with Xaero's Minimap. | |

### Technical tools

Current technical-building and troubleshooting tools.

| Mod | What it does | Notes |
| --- | --- | --- |
| [BoccHUD](https://modrinth.com/mod/bocchud) | Adds configurable technical information overlays. | Chosen in place of [MiniHUD](https://modrinth.com/mod/minihud); disable duplicate lines already supplied by [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap). |
| [Tweakerge](https://modrinth.com/mod/tweakerge) | Provides configurable technical-client tweaks. | Chosen in place of [Tweakeroo](https://modrinth.com/mod/tweakeroo); it also covers the workflow intended by [Accurate Block Placement Reborn](https://modrinth.com/mod/accurate-block-placement-reborn). |

### Sodium companions

These projects extend Sodium's settings and rendering options.

| Mod | What it does | Notes |
| --- | --- | --- |
| [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options) | Reorganizes Sodium's video settings. | |
| [Sodium Extra](https://modrinth.com/mod/sodium-extra) | Adds extra video and rendering settings to Sodium. | |
| [Sodium Shadowy Path Blocks](https://modrinth.com/mod/sodium-shadowy-path-blocks) | Restores darker rendering for path blocks when using Sodium. | |

### Visuals and camera

Current visual and camera tools.

| Mod | What it does | Notes |
| --- | --- | --- |
| [3D Skin Layers](https://modrinth.com/mod/3dskinlayers) | Renders player skin layers in 3D. | |
| [Better Beds](https://modrinth.com/mod/better-beds) | Improves bed models with minor visual tweaks. | |
| [Better Third Person](https://modrinth.com/mod/better-third-person) | Allows the third-person camera to rotate independently of player movement. | |
| [Boat Item View](https://modrinth.com/mod/boat-item-view) | Makes held items, including maps, visible while riding a boat. | |
| [Distant Horizons](https://modrinth.com/mod/distanthorizons) | Extends view distance using level-of-detail terrain. | |
| [Forgeshot](https://modrinth.com/mod/forgeshot) | Captures screenshots at resolutions larger than the game window. | Chosen in place of [Fabrishot](https://modrinth.com/mod/fabrishot) for high-resolution screenshots. |
| [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights) | Makes held and dropped light-emitting items illuminate their surroundings. | |
| [Model Gap Fix](https://modrinth.com/mod/modelfix) | Fixes gaps in block and item models. | |
| [Not Enough Animations](https://modrinth.com/mod/not-enough-animations) | Shows additional first-person actions in third person. | |
| [Ok Zoomer](https://modrinth.com/mod/ok-zoomer) | Adds a configurable OptiFine-style zoom. | Currently a beta build. |
| [Smooth Skies](https://modrinth.com/mod/smooth-skies) | Smooths skybox color transitions at long render distances. | |

### Audio and atmosphere

Additional atmosphere and audio layers alongside Sound Physics Remastered.

| Mod | What it does | Notes |
| --- | --- | --- |
| [AmbientSounds](https://modrinth.com/mod/ambientsounds) | Adds an ambient environmental sound bed. | Chosen as the ambient bed in place of [Charmonium](https://modrinth.com/mod/charmonium). |
| [Presence Footsteps](https://modrinth.com/mod/presence-footsteps-forge) | Adds varied footstep sounds based on the surface and environment. | |
| [Sounds](https://modrinth.com/mod/sound) | Adds and enhances game and interface sound effects. | |

### OptiFine compatibility

Current OptiFine/MCPatcher compatibility support.

| Mod | What it does | Notes |
| --- | --- | --- |
| [Continuity](https://modrinth.com/mod/continuity) | Adds connected-texture support for resource packs. | |
| [Entity Model Features](https://modrinth.com/mod/entity-model-features) | Supports OptiFine-style custom entity models. | |
| [Entity Texture Features](https://modrinth.com/mod/entitytexturefeatures) | Supports OptiFine-style emissive, random, and custom entity textures. | |
| [Polytone](https://modrinth.com/mod/polytone) | Adds resource-pack-controlled colors and other OptiFine-style visual features. | |
| [Puzzle](https://modrinth.com/mod/puzzle) | Provides configuration for several OptiFine-format compatibility features. | |

### Debug profile

Development and diagnostics profile; enable these when needed.

| Mod | What it does | Notes |
| --- | --- | --- |
| [Crash Assistant](https://modrinth.com/mod/crash-assistant) | Shows and analyzes affected logs after a crash. | Alongside [Not Enough Crashes](https://modrinth.com/mod/notenoughcrashes), covers the crash-diagnosis role of [Mixin Conflict Helper](https://modrinth.com/mod/mixin-conflict-helper). |
| [MixinTrace Reforged](https://modrinth.com/mod/mixintrace-reforged) | Adds Mixin information to crash stack traces. | |

### Resource packs

Resource packs included in the current setup and managed through Pakku.

| Resource pack | What it does | Notes |
| --- | --- | --- |
| [Reimagined](https://modrinth.com/resourcepack/reimagined) | Reworks vanilla textures, models, and interface elements while retaining a familiar style. | |
| [Simple Grass Flowers](https://modrinth.com/resourcepack/simple-grass-flowers) | Adds vanilla-friendly flowers, clovers, and rocks to grass-like blocks. | |
| [Motschen's Better Leaves](https://modrinth.com/resourcepack/better-leaves) | Makes leaf blocks appear bushier. | |
| [Slightly Improved Font](https://modrinth.com/resourcepack/slightly-improved-font) | Replaces the default font with a refined version. | |

### Shader packs

Photon is the current shader pack. Iris loads it, and the shader-pack menu controls activation.

| Shader pack | What it looks like | Notes |
| --- | --- | --- |
| [Photon Shaders](https://modrinth.com/shader/photon-shader) | Gameplay-focused semi-realistic lighting and atmosphere. | |

## Currently unused

### Mods

These projects are documented as optional and are not part of the current documented setup.

| Mod | What it does | Notes |
| --- | --- | --- |
| [BetterF3](https://modrinth.com/mod/betterf3) | Replaces the built-in F3 debug screen with a configurable display. | [BoccHUD](https://modrinth.com/mod/bocchud) and the vanilla debug screen cover the current workflow. |
| [Camera Overhaul](https://modrinth.com/mod/cameraoverhaul) | Adds dynamic camera movement and tilting. | |
| [FlightAssistant](https://modrinth.com/mod/flightassistant) | Adds an elytra flight HUD, autopilot, and flight protections. | |
| [Spark](https://modrinth.com/mod/spark) | Provides an in-game performance profiler. | |

### Resource packs

Optional resource-pack alternatives; none are part of the current setup.

| Resource pack | What it does | Notes |
| --- | --- | --- |
| [Bray's World](https://modrinth.com/resourcepack/braysworld) | Overhauls vanilla blocks, items, and entities with varied textures and custom models. | Optional alternative. |
| [Nature X](https://modrinth.com/resourcepack/nature-x) | Makes natural environments feel livelier with additional texture and model detail. | Optional alternative. |
| [Vanilla Evolved](https://modrinth.com/resourcepack/vanilla-evolved) | Enhances the default look with custom textures and models. | Optional OptiFine-style features may need compatibility testing. |
| [New Default+](https://modrinth.com/resourcepack/new-default-plus) | Adds extensive vanilla-style textures, models, variants, and OptiFine-style features. | Optional alternative. |
| [Ashen 16x](https://modrinth.com/resourcepack/ashen) | Reimagines Minecraft as a detailed 16x medieval-fantasy world. | Optional alternative. |
| [Stay True](https://www.curseforge.com/minecraft/texture-packs/stay-true) | Refines vanilla textures while retaining their original style. | Not in the current Pakku lockfile; Pakku still needs a CurseForge API key to manage it. [Unity](https://github.com/Unity-Resource-Pack) remains an alternative. |

### Held back from the baseline

These projects are intentionally excluded from the current baseline.

| Mod | What it does | Reason held back |
| --- | --- | --- |
| [Indium](https://modrinth.com/mod/indium) | Adds Fabric Rendering API support to Sodium. | Sodium provides the required rendering support and is incompatible with Indium. |
| [Noisium](https://modrinth.com/mod/noisium) | Optimizes world generation. | The available project is server-side and singleplayer rather than client-side. Revisit if the pack later includes server or integrated-server performance mods. |

## Pack status

No unresolved pack entries remain. The current pack, optional projects, and archive represent the complete disposition of the modlist.
