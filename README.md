# DebugMod
This mod adds a multifunctional console menu for convenient modding, debugging, and in-game manipulation.  
  
**⚠️WARNING⚠️ This version of DebugMod is designed to function with VotV 0.9.0n. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or encounter a bug, you can submit it as an issue on my [GitHub repository](https://github.com/Acitulen/DebugMod).

---

# **Configs**:
Configs can be accessed in the game settings under the **Mod configs** category or by pressing **Ctrl+Shift+C**.

- **MainMenuBind** - Sets the keybind to open main debug menu.  
  **Default:** `M`

- **DestroyBind** - Sets the keybind to destroy the object you are looking at.  
  **Default:** `Alt+B`

- **InspectBind** - Sets the keybind to open object inspector for object you are looking at.  
  **Default:** `Alt+N`

- **TimeStopBind** - Sets the keybind to toggle timestop.  
  **Default:** `Alt+T`

- **ToggleSpectatorBind** - Sets the keybind to toggle spectator.  
  **Default:** `Alt+V`

- **SwapSpectatorBind** - Sets the keybind to replace spectator with player.  
  **Default:** `Alt+L`

- **SpectatorHints** - Enables hints in spectator mode.  
  **Default:** `true`

- **TimeStopSounds** - Enables sound effects during time stop activation.  
  **Default:** `true`

- **InspectorMode** - Allows you to choose one of three inspector modes: Object for Actors, Component for Actor mesh components and Zone for scanning multiple actors in radius. 
  **Default:** `Object`  

- **ZoneRadius** - Sets range of the zone inspector. Can also be changed in-game by scrolling the mouse wheel.  
  **Default:** `300`

- **ElementsPerPage** - Sets the maximum number of elements displayed on a single page of a list (may affect performance).  
  **Default:** `200`  

- **ResetLocks** - Resets all locks.  

---

# Preview

<details>
<summary>Demonstration</summary>

* **Teleport across worlds:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/TeleportAcrossWorldsDemonstration.png?raw=true)

* **Event activator:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/EventActivatorDemonstration.png?raw=true)

* **Variable inspector:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/PropertyInspectorDemonstration.png?raw=true)

* **Bytecode inspector:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/6.0.0/Preview/BytecodeInspector.png?raw=true)

* **Spectator:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/SpectatorDemonstration.png?raw=true)

* **Extended spawn menu (with deferred spawn):**  

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/SpawnMenuDemonstration.png?raw=true)

* **ESP:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/ESPDemonstration.png?raw=true)

* **Viewmodes:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/6.0.0/Preview/Viewmodes.png?raw=true)

</details>

<details>

<summary>Main menu</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/MainMenuPreview.png?raw=true)
</details>

<details>
<summary>Object locator</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/ObjectLocatorPreview.png?raw=true)
</details>

<details>
<summary>Console</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/ConsolePreview.png?raw=true)
</details>

<details>
<summary>Servers</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/ServerPreview.png?raw=true)
</details>

<details>
<summary>Signal panel</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/SignalPanelPreview.png?raw=true)
</details>

<details>
<summary>Teleport across worlds</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/TeleportAcrossWorldsPreview.png?raw=true)
</details>

<details>
<summary>Events activator</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/EventPanelPreview.png?raw=true)
</details>

<details>
<summary>Extended spawn menu</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/ExtendedSpawnMenuPreview.png?raw=true)
</details>

<details>
<summary>Waypoints</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/5.0.0/Preview/WaypointsPreview.png?raw=true)
</details>

# Features: 
## Main menu:
- Freeze everything except player.
- *Some entities may move during timestop.
- Set time to `00:00`, `12:00` or `03:30`.
- Change speed of day/night cycle.
- Change global time speed.
- Change player time speed.
- Change ariral reputation.
- Change in-hand drive processing level.
- Force save game, even during events.
- Disable annoying unsolvable labyrinth (backrooms).
- Prevent crashing from some entities and events.
- Prevent force teleport.
- Set player points.
- Make player immortal.
- Prevent player death.
- Make player satiety non-consumable (75%+).
- Make player stamina non-consumable (75%+). 
- Make flashlight charge infinite (100%+).
- Disable max hp loss.
- Disable bleeding.
- Disable ragdoll.
- Enable fullbright for perfect night vision.
- Make player inventory infinite.
- Toggle spectator mode.
- Turn on/off all the lights.
- Clean and fix all base walls and floors from stains and cracks. 
- Remove trash.
- Clean main base window. 
- Fix broken radio tower.
- Fix broken radar towers.
- Reboot transformers.
- Base power control.

## Object locator:
- Find any actor in the world.
- Find any props in the world.
- Get objects locations.
- ESP objects.
- Teleport to objects.
- Teleport objects to player.
- Inspect objects.
- Destroy objects.

## Servers:
- Break servers.
- Fix servers.
- Protect servers.
- Spawn items for today's task.

## Signal panel:
- View signal images from all levels.
- Listen signal sounds from all levels.
- Read signal messages from all levels.
- Spawn drives with signals from all levels.

## Event panel:
- Monitor meta paranoia.
- Run story events.  
*Most events can only be started in story mode.
- Run trigger events.
- Run ticker events.  
*You need to set the number of tries to execute an event.

## Waypoints:
- Create waypoints.
- Delete waypoints.
- Teleport to waypoints.  
*All waypoints are the same for all worlds.

## Other:
- Portable version of base console terminal.
- Teleport across levels.
- Extended spawn menu.
- Property inspector.
- Function inspector and executor.
- Ability to disable execution of functions.
- Bytecode analyzer: view, search and patch the bytecode of Blueprint functions.
- Edited functions menu: review and reset disabled functions and bytecode patches.
- Protection from accidental destruction of important objects.

---

## Manual installation guide.

<details>
<summary>Install unreal shimloader</summary>

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. Its new path should be `GAME/Binaries/Win64/dwmapi.dll`.
2. Copy the contents of the `UE4SS` folder in the package into `GAME/Binaries/Win64`.

`GAME/Binaries/Win64` should now contain the following *new* files and folders:
- `GAME-Win64-Shipping.exe`
- `ue4ss.dll`
- `UE4SS-settings.ini`
- `dwmapi.dll` ← *This is the unreal-shimloader binary. It will load UE4SS for you.*
- `Mods/`
</details>

<details>
<summary>Install ModUtils</summary>

DebugMod does not work without [ModUtils](https://github.com/Acitulen/ModUtils). Install it before DebugMod:
1. Copy `ModUtils.pak` from the `pak` folder of the ModUtils package to `GAME/Content/Paks/LogicMods` directory.
2. Copy the contents of the `mod` folder of the ModUtils package into the `GAME/Binaries/Win64/Mods/Acitulen-ModUtils` directory.  
*You need to create the `Acitulen-ModUtils` folder manually.
</details>

<details>
<summary>Install DebugMod</summary>

1. Copy `DebugMod.pak` from the `pak` folder to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder into the `GAME/Binaries/Win64/Mods/Acitulen-DebugMod` directory.  
*You need to create the `Acitulen-DebugMod` folder manually.
</details>
