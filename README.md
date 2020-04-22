# OGRE Import/Export addons for Rigs of Rods using Blender 2.79

## Original addon authors:
- Importer - Dusho, goatman, CCCenturion
- Exporter - Brett Hartshorn, S.Rombauts, F00bar, Waruck, Mind Calamity, Mr.Magne, Jonne Nauha, vax456

## Installation 

**The first two steps are for existing addon users!**

- Uninstall old version:

File -> User Prefs -> Addons -> Search "rigs" -> Remove 
![BlenderRemove](https://i.imgur.com/pUMWEDV.png)

Restart Blender after removing.

- Delete `blender2ogre.pickle` from `%appdata%\Blender Foundation\Blender\2.79\config\scripts`

(Paste location into Run window [Windows key +R] to get there quickly)

- Download `RoR_ImportExport_0.7.0.zip` from the [Releases page](https://github.com/CuriousMike56/RoROgrePlugins/releases/tag/0.7.0-RoR

- File -> User Prefs -> Addons -> Install from File -> Select `RoR_ImportExport_0.7.0.zip`

- Search "rigs" and enable both addons 

![AddonEnable](https://i.imgur.com/S6ELqrT.png)

- Save user prefs.



## Changes from the original export addon:

- Fixed basic (single texture) material export 

![BlenderExample](https://i.imgur.com/0xVCjsK.png)

![IngameExample](https://i.imgur.com/Ei3QFUu.png)

- Shadows support if "Receive Shadows" is enabled for the material

![BlenderShadow](https://i.imgur.com/jmQPxzl.png)

- Added setting to use object data name or outliner name as the exported mesh name 
(Default: Outliner name) 

![DataOutliner](https://i.imgur.com/i0bPvoV.png)

- Removed most features not used by RoR 


