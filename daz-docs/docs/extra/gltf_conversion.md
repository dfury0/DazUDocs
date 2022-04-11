# Converting a Daz Prop to glTF using Blender
glTF is a fast and highly compressed 3D format used in games, 
native web applications, AR, VR, and 3D ads. 
You can also embed glTF files in Microsoft Word documents or PowerPoint files.

## Save prop as FBX with Embed Textures
* Load Prop in Daz Studio
* Export as FBX
* Embed Textures checked
<figure markdown>
  ![Load the Prop](img/GLTF_Conversion/01_loadprop.gif){ width="720" }
</figure>

## Import FBX into Blender
* File > Import > *.fbx
* Standard Settings
<figure markdown>
  ![Image title](img/GLTF_Conversion/02_Blender Import FBX.gif){ width="720" }
</figure>

## Reset the Bone Pose
* Change to pose mode 
* Alt + R to reset bones
* Alt + A to Apply as rest pose 
<figure markdown>
  ![Image title](img/GLTF_Conversion/03_Fix Bone Pose.gif){ width="720" }
</figure>

## Check Material is loaded
* Materials should be embedded from the Daz FBX export. 
* Viewport shading to rendered
<figure markdown>
  ![Image title](img/GLTF_Conversion/04_Material Check.gif){ width="720" }
</figure>

##Export GLTF (file extension .GLB)
* File > Export > glTF 2.0 (.glb/.gltf)
<figure markdown>
  ![Image title](img/GLTF_Conversion/05_Export GLB.gif){ width="720" }
  <figcaption>Export Complete!</figcaption>
</figure>
