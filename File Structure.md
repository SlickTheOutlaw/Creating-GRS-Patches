# File Structure
Create the exact folder structure that GRS Patches has. Should be something like this.
- Assets
  - Circle_Patches
    - Data
  - Flag_Patches
    - Data
  - Rectangle_Patches
    - Data
  - SF_Patches
    - Data
  - Vest_Patches
    - Data
- Resources (Optional)
- Configs
- Prefabs
  - Circle_Patches
  - Flag_Patches
  - Rectangle_Patches
  - Vest_Patches


## Assets
The Assets folder contains the textures and heightmaps (NMO) of each patch.
In this folder the Data folder is required. You can group patches together inside of Data for more organization. The game doesn’t care what you name it. I recommend that your folders don’t have spaces, use underscores or dashes. Normally there are 2 types of files in these folders: “.edds” and “.emat”. You can create NMO files but they aren’t required. 

NMO’s only give patches the ability to have “perceived” raised areas. With current game status, consoles have a hard time rendering graphics. These files also increase your mod size, because you are doubling the texture file size within the emats. More on NMO files later.

## Configs
With the current way GRS handles configs there should be 3 files:
1. GRS_Patches_Flags
2. GRS_Patches_Other
3. GRS_Vest_Patches

## Prefabs
In this folder you can either duplicate one model from the GRS dependency that you want to use for your patches (Doesn’t matter which one), or create your own in Blender (thats a beast of its own)
