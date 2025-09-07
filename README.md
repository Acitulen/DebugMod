# DebugMod
This mod adds a multifunctional console menu for convenient modding, debugging, and in-game manipulation.  
  
**⚠️WARNING⚠️ This version of DebugMod is designed to function with VotV 0.8.2c_0011. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or encounter a bug, you can submit it as an issue on my [GitHub repository](https://github.com/Acitulen/DebugMod).

---

# **Configs**:
Configs can be accessed in the game settings under the **Mod configs** category or by pressing **Ctrl+Shift+C**.

- **MainMenu** - Sets the keybind to open main debug menu.  
  **Default:** `M`
 
- **Inspect** - Sets the keybind to open object inspector for object you are looking at.  
  **Default:** `Alt+N`

- **Delete** - Sets the keybind to destroy object you are looking at.  
  **Default:** `Alt+B`

- **TimeStop** - Sets the keybind to toggle timestop.  
  **Default:** `Alt+P`

- **Spectator** - Sets the keybind to toggle spectator.  
  **Default:** `Alt+L`

- **TimestopSounds** - Enables time stop sounds.  
  **Default:** `true`

- **ZoneScanner** - Enables zone scanner mode of object inspector.  
  **Default:** `false`  

- **ScannerRange** - Sets range of the zone scanner.  
  **Default:** `300`


---

# Preview

<details>
<summary>Demonstration</summary>

* **Teleport across worlds:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/3.0.0/Preview/TeleportAcrossWorldsDemonstration.png?raw=true)

* **Event activator:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/3.0.0/Preview/EventActivatorDemonstration.png?raw=true)

* **Variable inspector:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/3.0.0/Preview/PropertyInspectorDemonstration.png?raw=true)

* **Spectator:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/SpectatorDemonstration.png?raw=true)

* **Extended spawn menu (with deferred spawn):**  

![Preview](https://github.com/Acitulen/DebugMod/blob/4.1.0/Preview/SpawnMenuDemonstration.png?raw=true)

</details>

<details>

<summary>Main menu</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.1.0/Preview/MainMenuPreview.png?raw=true)
</details>

<details>
<summary>Object locator</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.1.0/Preview/ObjectLocatorPreview.png?raw=true)
</details>

<details>
<summary>Console</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/ConsolePreview.png?raw=true)
</details>

<details>
<summary>Servers</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/ServerPreview.png?raw=true)
</details>

<details>
<summary>Signal panel</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/SignalPanelPreview.png?raw=true)
</details>

<details>
<summary>Teleport across worlds</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/TeleportAcrossWorldsPreview.png?raw=true)
</details>

<details>
<summary>Events activator</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/EventActivatorPreview.png?raw=true)
</details>

<details>
<summary>Extended spawn menu</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.1.0/Preview/ExtendedSpawnMenuPreview.png?raw=true)
</details>

<details>
<summary>Waypoints</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/4.0.0/Preview/WaypointPreview.png?raw=true)
</details>

# Features: 
## Main menu:
- Disable annoying unsolvable labyrinth (backrooms).
- Freeze everything except player.  
*Some entities may move during timestop.
- Change speed of day/night cycle.
- Set time to `00:00`, `12:00` or `03:30`.
- Change ariral reputation.
- Change in hand drive processing level.
- Force save game, even during events.
- Set player points.
- Make player immortal.
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
- Clean all base walls and floors from stains. 
- Remove all useless (non-recyclable) trash.
- Fix broken radio tower.
- Reboot transformers.
- Base power control.

## Actor locator:
- Find any actor in the world.
- Get actor locations.
- Teleport to actors.
- Teleport actors to player.
- Inspect actors.
- Destroy actors.

## Servers:
- Break servers.
- Fix servers.
- Protect servers.
- Copy today's task.

## Signal panel:
- View signal images from all levels.
- Listen signal sounds from all levels.
- Read signal messages from all levels.

## Event activator:
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
- Teleport across worlds.
- Extended spawn menu.
- Property inspector.
- Function inspector and executor.

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
<summary>Install DebugMod</summary>

1. Copy `DebugMod.pak` from the `pak` folder to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder into the `GAME/Binaries/Win64/Mods/Acitulen-DebugMod` directory.  
*You need to create the Acitulen-DebugMod folder manually.
</details>
