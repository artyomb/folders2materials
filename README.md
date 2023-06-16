Blender Add-on
# folders2materials
The addon Loads textures from the list of folders and creates **PBR materials**.

For example, the **Quixel bridge** fails to create proper material in **Blender**. But it downloads the materials in local 
folder which can be used with the addon.

- Batch processing of multiple folders.
- Setup **Princepled BSDF** shader with following parameters:
  - Defuse texture: Base Color
  - Ambient Occlusion: Mix color with deffuse texture
  - Roughness texture: Roughness 
  - Opacity texture: Alpha
  - Normal map: Normal
  - Height map: Displacement (midlevel, slace)
  - Metal map: Metalic
  - Emission texture: Emission
  - Preview: Asset preview
- Setup mapping scale with respect to image size proportions. 
- Mark material as Asset

# Install
Download the addon archive and install it as usual.
![image](https://github.com/artyomb/folders2materials/assets/2667887/6404281a-079e-44e4-bc94-138601ce6a11)

# Setup
Setup global parameters for created materials. As displacement scale and midlevel, AO mix factor.
![image](https://github.com/artyomb/folders2materials/assets/2667887/aa91b53c-9fe6-4d93-a270-04d1f155e61f)


# Location
The addon panel is located at the Asset browser side panel.
![image](https://github.com/artyomb/folders2materials/assets/2667887/79933114-5fba-44ab-86a8-6877ea24b2fa)

# Import
Select the parent folder where the list of subfolders contains of textures. Select the required import options.
Manage the file names and extensions for the texture's lookup.

![image](https://github.com/artyomb/folders2materials/assets/2667887/9edabdef-bc02-4745-801e-d6a063f164b2)



