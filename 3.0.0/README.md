# DebugMod
This mod adds the multifunctional console menu for comfortable modding, debugging and manipulation.  
  
**⚠️WARNING⚠️ This version of DebugMod is designed to function with VotV-pa0082b_0006. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or found a bug you can send it as "issue" in my [gitHub repository](https://github.com/Acitulen/DebugMod).

# Binds (default):

**M** - open main debug menu.
 
**Alt+N** - open variable inspector for object you are looking at. 

**Alt+B** - destroy object you are looking at. 

**Alt+P** - Toggle timestop. 

**Alt+L** - Toggle spectator. 


All these binds can be changed in config.

# Preview



<details>
<summary>Demonstration</summary>

 * **Teleport across worlds:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModDemonstration2.png?raw=true)

* **Event activator:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModDemonstration3.png?raw=true)

* **Variable inspector:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModDemonstration1.png?raw=true)

![Preview](https://github.com/Acitulen/DebugMod/blob/main/VariableInspectorPreview.png?raw=true)

* **Spectator:**  

![Preview](https://github.com/Acitulen/DebugMod/blob/main/SpectatorPreview.png?raw=true)

</details>

<details>

<summary>Main menu</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/MainMenuMenu.png?raw=true)
</details>

<details>
<summary>Actor locator</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/ActorLocatorMenu.png?raw=true)
</details>

<details>
<summary>Console</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/ConsoleMenu.png?raw=true)
</details>

<details>
<summary>Servers</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/ServersMenu.png?raw=true)
</details>

<details>
<summary>Debug mod config</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/DebugModConfigMenu.png?raw=true)
</details>

<details>
<summary>Teleport across worlds</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/TeleportAcrossWorldsMenu.png?raw=true)
</details>

<details>
<summary>Events activator</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/EventsActivatorMenu.png?raw=true)
</details>

<details>
<summary>Waypoints</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/3.0.0/Preview/WaypointsMenu.png?raw=true)
</details>

# Features: 
## Main menu:
- Disable annoying unsolvable labyrinth (backrooms).
- Freeze everything except player.  
*Some entities may move during timestop.
- Change speed of day/night cycle.
- Change ariral reputation.
- Make player immortal.
- Make player satiety non-consumable (75%+).
- Make player stamina non-consumable (75%+). 
- Make flashlight charge infinite (100%+).
- Make player inventory infinite.
- Toggle spectator mode.
- Turn on/off all the lights.
- Clean all base walls and floors from stains. 
- Remove all useless (non-recyclable) trash.
- Fix broken radio tower.
- Reboot transformers.

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

## Debug mod config:
- Set bind for main debug menu.
- Set bind for variable inspector.
- Set bind for destroy object function.
- Set bind for timestop.
- Set bind for spectator.
- Set searches per tick.  
*higher values may increase lags.
- Set elements per page.  
*higher values may increase lags.
- Toggle timestop sounds.

## Event activator:
- Run story events.  
*Most of events can only start in story mode.
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

## Manual instalation guide.

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
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/Acitulen-DebugMod` directory.  
*you have to create `Acitulen-DebugMod` folder manually.
</details>
