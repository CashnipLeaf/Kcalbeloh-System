# Kcalbeloh System
Kcalbeloh System adds a new black hole star system to Kerbal Space Program. 

# Installation Guide
### Install Automatically from CKAN
Not available for beta release.

### Install Manually
1. **Install Kcalbeloh System**
   * [**Download**](https://github.com/jcyuan06/Kcalbeloh-System/releases) the newest version of Kcalbeloh System, extract and put all the contents in /GameData to your KSP /GameData folder.
   * If you are updating this mod, make sure you delete the previous version completely before installing the new version.  
2. **Install Dependencies**
   * [**Kopernicus**](https://forum.kerbalspaceprogram.com/index.php?/topic/200143-181-1122-kopernicus-stable-branch-last-updated-november-25th-2021/): for creating custom celestial bodies.
   * [**Singularity**](https://forum.kerbalspaceprogram.com/index.php?/topic/193709-wip18x-112x-singularity-black-hole-shaders/#comment-3782330): for blackhole and wormhole shaders.   
3. **Install Visuals**  
The planet pack works fine without visual mods, but it will lose a large part of its aesthetic.
   * [**EVE Redux**](https://forum.kerbalspaceprogram.com/index.php?/topic/196411-19-112-eve-redux-performance-enhanced-eve-maintenance-v11151-07112021/): for clouds, dust storms, and auroras.
   * [**Scatterer**](): for realistic atmosphere, oceans, and sun flares.  
### For KSP 1.12.x
In KSP 1.12.x, the stock maneuver tool can cause severe lag/stutter in planet mods, so KSPCommunityFixes is STRONGLY recommended. To fix this issue, you need to:
   1. Install [KSPCommunityFixes](https://forum.kerbalspaceprogram.com/index.php?/topic/204002-18-112-kspcommunityfixes-bugfixes-and-qol-tweaks/).
   2. Disable the stock maneuver tool in the in-game settings menu.
### Installation Checklist
   After a complete installation, the GameData folder should at least have the following contents:
   * EnvironmentalVisualEnhancements
   * KcalbelohSystem
   * Kopernicus
   * KopernicusExpansion
   * ModularFlightIntegrator
   * Scatterer
   * Singularity
   * ModuleManager.4.2.1.dll
# Mod Setting Guide
Go to `KSP folder/GameData/KcalbelohSystem/` and open `Kcalbeloh System Settings.cfg`.

### Wormholes Setting
`Wormholes = `: whether to have wormholes connecting stock solar system and Kcalbeloh system.  
   - `True`: (default) enable the wormholes.
   - `False`: disable the wormholes.

### Home Switch Setting
`HomeSwitch = `: whether to move KSC to Kcalbeloh system. 
   - `False`: (default) keep KSC on Kerbin.
   - `Suluco`: move KSC and other launch sites and airfields to Suluco.
   - `Efil`: move KSC and other launch sites and airfields to Efil.
   - Home switch is NOT compatible with system-replacement planet mods (Beyond Home, GPP, RSS, etc).
   - Do **NOT** load any saved game after changing home switch setting.

### Distance Setting
`DistanceFactor =`: moving Kcalbeoh System closer or further to stock system.  
   - `1`: (default) keep the default distance (271.8 Tm).
   - `0.1`: 0.1x default distance.
   - `10`: 10x default distance.
   - `100`: 100x default distance.

### Rescale Setting
`Rescale = `: rescale the system to 2.5x or 10x size.  
   - `1`: (default) No rescales applied. It has the same scale with stock system.
   - `2.5`: 2.5x scale. If JNSQ is installed, this value will be forced.
   - `10`: - 10x scale (realistic scale). If RealSolarSystem is installed, this option will be forced.
   - This setting needs Sigma Dimensions installed: https://github.com/Sigma88/Sigma-Dimensions
   - Rescale only applies to celectial bodies from this mod.

# FAQs
1. **Does it replace the Kerbol system or add a new system?**  
It adds a new system without any change to the Kerbol system. But it also offers home switch options which allow you to move KSC to habitable planets in Kcalbeloh system.

2. **Is it based on the movie Interstellar?**  
Yes, but no. Although some ideas of the mod are inspired by Interstellar, the goal of the mod is not to facsimile the Gargantua system from Interstellar, but to create a unique star system.

3. **Is it compatible with other planet packs?**  
Yes, it is compatible with most planet packs but it still needs further testing. Let me know if you have any issues.

4. **Is it compatible with other visual mods?**
Yes, it is compatible with most visual mods for stock system, such as Astronomer's Visual Pack, Spectra, and Stock Visual Enhancement.

# Contact
[KSP Forum](https://forum.kerbalspaceprogram.com/index.php?/topic/203753-wip-112x-kcalbeloh-system-planet-pack-beta-12-a-journey-to-a-black-hole-may-02-2022/)  
[Discord Server](https://discord.gg/Crmy8KgqK2) 
