# **DebugMod**
This mod adds the multifunctional console menu for comfortable modding, debugging and manipulation.

# Binds (default):
**M** - open main debug menu.
 
**K** - open debug console. 

**N** - open variable inspector for object you are looking at. 

**B** - destroy object you are looking at. 


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

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModMainMenuPreview.png?raw=true)
</details>


<details>
<summary>Servers menu</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModServersPreview.png?raw=true)
</details>


<details>
<summary>Console</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModConsolePreview.png?raw=true)
</details>

<details>
<summary>Teleport across worlds</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModWorldTeleporterPreview.png?raw=true)
</details>

<details>
<summary>Events activator (WIP)</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModEventsActivatorPreview.png?raw=true)
</details>

<details>
<summary>Waypoints</summary>

![Preview](https://github.com/Acitulen/DebugMod/blob/main/DebugModWaypointsPreview.png?raw=true)
</details>

# Features: 
## Objects:
This interface section allows to manipulate with all objects in a world.
- Get location of all objects of the class.  
*You can open variable inspector for located objects by pressing 'data' button.
- Teleport player to found objects (Tp to).
- Teleport objects to a player (Tp here).
- Teleport all objects to a player.
- Delete all objects of the class.


## Stats:
This interface section gives information about different important statistics in VotV and allows to manipulate some of them.
- Get information about ariral reputation.
- Set ariral reputation.
- Show the information about the amount of power left in transformers.
- Restore power in transformers.
- Get information about the status of servers.
- Break/fix/protect all servers.

## Base settings:
This interface section gives the ability to control states of the base.
- Turn on/off all the lights.
- Clean all base walls and floors from stains. 
- Get rid of all useless (non-recyclable) rubbish.
- Fix broken radio tower.

## World settings:
This interface section gives the ability to control some world settings.
- Disable annoying unsolvable labyrinth (backrooms).
- Open portable version of base console terminal. 
- Open menu that gives ability to travel across different levels (not saves).  
*Some levels may crash game.
- Open menu that allows you to run some events.  
*Most of events can only start in story mode.
- Open menu that allows you to create waypoints and teleport to them.
- Change speed of day/night cycle.

## Player settings:
This interface section gives the ability to control some player stats.
- Make player immortal.
- Make player satiety non-consumable (75%+).
- Make player sleepiness non-consumable (75%+). 
- Make flashlight charge endless (100%).
- Toggle spectator mode.


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
<summary>Install VoidMod-2.0.1</summary>

1. Copy `VoidMod2.pak` from the pak floader to `GAME/Content/Paks/LogicMods` directory. 
</details>

<details>
<summary>Install DebugMod</summary>

1. Copy `DebugMod.pak` from the `pak` floader to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/Acitulen-DebugMod` directory.  
*you have to create `Acitulen-DebugMod` floader manually.
</details>
