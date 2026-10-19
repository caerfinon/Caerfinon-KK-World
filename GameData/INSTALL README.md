# INSTALL Instructions for **Caerfinon-KK-World**

## Bundled Mods
- **Country Doggo's** - Various mods. Statics only, no bases 
- **FastCorp's Roads mod** - Statics only, no bases
If you have these mods installed already, you can remove them, or delete them from the /Caerfinon-KK-World/FreeStatics folder to avoid duplicates. 

## Required Mods
- **Kerbal Konstructs** - Required for Base construction
- **Custom Pre Launch Checks** - dependency of Kerbal Konstructs
- **Kerbin Side Remastered** - Used for Statics only. **Strongly recommend** deleting the directory /Statics/ExampleBases 
- **KerbinSide Core** - (From CKAN) Collection of original KerbinSide Statics. No bases are provided.
- **Omega's Stockalike Structures: No Textures Required** - Collection of Statics
- **Ordinary Konstuction Co.** - Collection of Statics - The example base makes changes to the Island Airfield. This can be kept or removed.
- **Tundra's Space Center** - Collection of Statics 
- **ModuleManager** - required for patches

## Recommended Mods   
- **NAVUtilities Updated** - Provides Navigation assistance during flight. Supported with a patch to populate all base runways. (See below to remove stock runways)
- **KramaxAutoPilot** - A decent Autopilot mod that can have established Flightplans to various runways. Supported with a patch to populate all base flightplans. (See below to remove stock flightplans)
- **GAPFAS** - A contract pack for providing missions to the various bases provided by Caerfinon-KK-World. Supported with a patch to provide all base locations to GAPFAS 
- **Contract Configurator** - required for GAPFAS
- **Waypoint Manager** - required for GAPFAS

## Conflicting Mods
- **Kerbin Side Remastered Gap Extras** - Statics reused in Caerfinon-KK-World already
- **Panocean Canal** - Statics reused in Caerfinon-KK-World already
- **The Outpost** - Statics reused in Caerfinon-KK-World already. Sound Cube commented out.
- **Kerbin Side Remastered GAP** - Not recommended if you left the Kerbin Side Remastered bases installed. Better yet would be to use the GAPFAS template to add the Kerbin Side Remastered bases to GAPFAS  
    

## Install Main Folder
Copy the **Caerfinon-KK-World** folder into your GameData folder.

## Optional Installs

###  KramaxAutoPilot
The folder **KramaxAutoPilot** contains only modified files for flightplans.
It removes the default flightplans so that only ones from the **Caerfinon-KK-World** patches will be loaded.
If you do not use this, the new patch will still load the flightplans but you will also have all the default flightplans that may or may not be present on your world. 
Use only if you have Kramax Auto Pilot installed. Copy the **KramaxAutoPilot** folder into your GameData folder. It will overwrite the flightplan files.

### NAVUtilities Updated
The folder **NavInstruments** contains only modified files for runways.
It removes the default runways so that only ones from the **Caerfinon-KK-World** patches will be loaded.
If you do not use this, the new patch will still load the runways but you will also have all the default runways that may or may not be present on your world.
Use only if you have NAVUtilities Updated installed. Copy the **NavInstruments** folder into your GameData folder. It will overwrite the runway files.

### KerbinSide Remastered
There is an issue with the static supplied by the mod that affects the windsock that is deployed at all Airstrips.
With no changes, the windsock appears as a completely grey object. In order to allow the windsock to be correctly coloured you will need to delete the file **windsock.dds** from the directory **GameData/KerbinsideRemastered/Statics/** which allows **windsock.tga** to load the correct textures.