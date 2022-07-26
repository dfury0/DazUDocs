# 07 | Glasses and rigidity maps

Workflow by [Mada](https://www.daz3d.com/mada)

![type:video](https://www.youtube.com/embed/SsQ94I03n4E)

Length : 22:10

## Weightmapping

- Import the obj and use the transfer utility to fit to Genesis
  - Source Item : Genesis 8 Female
  - Target Item : Glasses
  - Projection Template : Short Hair
- Select all the polygons in the glasses, select the glasses head body part in the scene tab
- Change to the weightmap brush, right click in the viewport and choose Weight Editing | Fill Selected
- Fill Selected Faces with 100% – that will take the weight away from any of the facial bones that can distort the glasses during expressions

## Morphs and rigidity

- Change to vertex selection and select all the vertices in the glasses in the Geometry Editor Tool
- Change to the vertex selection tab and right click on Rigidity Groups
  - Rigidity Groups | Create Rigidity Group from Selected
- Next step is to select the reference vertices that Daz Studio will use to keep the shape of the glasses when you apply morphs
- I started out with 3 vertices – one on each side of the glasses and one in the middle and right click on References
  - References | Assign Selected Vertices to Group
- Select the weight brush tool, select the faces you want to keep rigid and go to the weightmap tools, click Add Map to add Rigid Weights if its not already there
- Fill it with a percentage, I started with 100%. With faces still selected right click in the viewport and select
  - Weight Editing | Smooth Selected
- Now you need to clear Generated Morphs to see the result
  - Edit | Figure | Clear Generated Morphs
- If nothing happens it means that there’s a morph in the data folder that’s overwriting the rigidity. To fix that you save the glasses and delete them. Find the morphs in the following folder
  - data | (Vendor name) | Product Name | Item Name | Morphs | (Vendor Name) | Base
- Delete any FBM and FHM morphs in the folder
- Load the glasses again and it should now load with less distortion
- Keep on refining the reference vertices and rigid weightmap until you find something that works best for most of the morphs
- Some of the more extreme morphs you will have to export, fix the size in a modeler and import with reverse deformation on

## Turning the glasses into a bone

- Change to the joint editor tool and in the scene editor select the head bodypart on the glasses.
- Right click on the selected bone in the viewport
  - Create | Create Child Bone
  - Bone Name and Label : Glasses
  - Rotation Order : YZX
- Adjust the start and endpoints – I move the start point to where I want the glasses to rotate around the ear
- Right click on the bone
  - Align | Align Node
- Select all the polygon faces on the glasses with the geometry editor tool
- Right click on Face Groups and create a new group called Glasses
  - Face Groups | Create Face Group from Selected
- Change to the weightmap brush, right click in the viewport and choose Weight Editing | Fill Selected
- Fill Selected Faces with 100%
- Joint Editor Tool | Tool Settings – click on Selection Group and tick the box next to glasses, now users can click on the glasses to select them in the viewport
- Right click in the viewport and memorize the rigging
  - Memorize | Memorize Selected Node(s) Rigging
- Rotate the glasses with the X Rotate dial to check where the frame starts cutting into her ear, open the Parameter Settings and set Min to and Max (in this case I set it to -30 and 5)
- Hide ZRotate and YRotate since they won’t be used
- Check all expressions to make sure none of them are distorting the glasses when used