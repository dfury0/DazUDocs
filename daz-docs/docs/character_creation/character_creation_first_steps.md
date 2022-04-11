# Character Creation First Steps
## Important Concepts

### What is Genesis?

* Genesis is an avatar system. 
* Genesis “characters” are blendshapes, stacked onto a unified base topology and rig. 
* Genesis has a fixed topology. It cannot be changed. There are ways to temporarily replace areas of the model with new geometry called **geografting** used for tails, wings, etc. discussed elsewhere, but it still relies on matching topology. 
* Genesis figures have one set of skinning weights and they cannot be altered. Likewise, the figure’s bone list also cannot be altered. Joint center points, however, *must* be edited to be in the proper location for characters that need different limb lengths, etc. *note: our **Adjust Rigging to Shape** tool automates this process.* 
* Genesis Bone orientations can be altered, but generally should not be. It causes problems with posing and animation. 

***You can change proportions and shape quite drastically while character sculpting but the overall pose of the character needs to match the original genesis mesh.***

## What makes up a Genesis “Character”?

### A Genesis character will generally consist of the following components.

* **A low-resolution character blendshape** 
  * Fits around the volume of a high-resolution shape. 
  * Split into head and body shapes inside Daz Studio.

* **A high-resolution character blendshape** 
  * contains HD details not captured by the low-resolution model.  

* **Separate navel and nipple blendshapes** - that will be loaded additively to the core figure navel and nipples in our software. They should not be a part of either the high or low-resolution character shape.
* **Pose space corrective blendshapes for the body** - once the joint centers have been moved into proper position for the low resolution character shape, the figure joints are then posed to positions where a sculpted corrective already exists in the base and:If the posed shape is found aesthetically insufficient, a custom one for that character is created. These are then hooked up with set driven logic.The common corrective amounts range from 20 - 40 correctives, depending on how far the character deviates from the base.

* **FACS based expression correctives for the head** - the core figure has a set of FACS based expression blendshapes. Often these will not perform optimally for a new character face shape and correctives for some of the targets will have to be made.

* **Tear geometry fit shape** - Genesis comes with a separate “tear” geometry add-on that fits around the edge of the eye socket and over the eyeball. Often with new character shapes this will not fit properly, and a custom character fit will have to be made.

* **Eyelash geometry fit shape** - Genesis comes with a separate “eyelash” geometry add-on that follows the edge loop of the eye rim. It too sometimes performs poorly with new character shapes and requires a custom fit be made.

* **Body shape set corrections** - Genesis has a set of core body and head shapes that are sold. We do try to at minimum correct the worst-performing shapes in the sets.

* **Normal map exports** - Because the low and high-resolution character shapes are sold separately, we bake a set of normal maps from the final character files, high to low, to ship with the low-resolution character product. Safest to do this at the end of the process.

  ## Character Sculpting

* **Scaling** - Keep character blendshapes the same scale as the base, so all characters have a uniform volume. Otherwise, blendshapes on the figure will be too strong, or weak. 

  * When you want a character to be bigger or smaller (ie a child or a monster) you still sculpt it at the same scale as genesis. Then we will scale it in Daz Studio. It might be strange to have giant babies and tiny monsters, but our avatar system works better with normalized scales. 

* **Proportion Changes** - When it comes to changing the proportions of your character we have found it is best to rough in the proportions of the character in Daz Studio in the beginning. We have morphs and scaling properties available for head scale, hand scale, feet scale, limb lengths, limb thickness, etc. and this tends to be cleaner than doing the adjustments in another tool. Make sure the 1chin area is aligned with the Genesis base chin, letting the feet go through the floor or float above the floor (see video [starting around 1:00](https://youtu.be/SM9jlyiiMqs?t=60) for an explanation)

* **Landmarks** - When sculpting, landmarks are important: lip lines, eyelid edges, navel, need to be maintained between all shapes on Genesis for blend stacking, texture alignment, and accessory elements (eyebrows, eyelashes) to work successfully. Every blendshape has to use the topology in the same basic way.

* **Landmark Drift** - It is best to avoid landmark drift, topology dragging, or pinching etc. This is the cleanest method for having fewer issues later that would require a custom corrective for other shapes, expressions. or bends, etc. You can get around being this strict while sculpting if you plan later to manually fit a cleaned version of our base topology around, re-project the details and clean up any errors at the end.

* **Mesh Resolution** - We usually sculpt a character at either 5 or 6 divisions of our base mesh in Zbrush for right now. (4.2m – 16.7m polygons). We ship both a low cage topology blendshape, and an extracted higher detail difference blendshape of each character. The two are then stack-able to achieve the final character. It is important that high poly sculpt be animation clean as well.

* **Alignment** - Before exporting, make sure the head is aligned properly. This is important because we split the character sculpt into a head and body shape. 

  * See the video [starting around 2:50](https://youtu.be/SM9jlyiiMqs?t=169) for an explanation

  ## Basic Workflow

  We highly recommend a quick test of the first 3 steps and send us your high resolution mesh. We will verify it is still compatible with our mesh before you put any substantial time into a sculpt. 

* [**Video**](https://youtu.be/SM9jlyiiMqs) **showing steps 1 and 2**

  * Load the target figure mesh (Genesis 8.1 Male or Female) and rough in the body proportions. This needs to be done with the Dev Load version of the mesh that loads without any morphs applied and doesn’t have the eyelashes or tears.
    * **Make sure to pay attention to the notes in the “Character Sculpting” section above before proceeding**

* Export the cage resolution mesh to OBJ 

  * Easiest to use the script that we include in "/People/Genesis 8 Male/Developer Kit/" for exporting OBJs

* Import into ZBrush (or the tool of your choice), subdivide in ZBrush to the desired resolution and sculpt the character shape (making sure to avoid workflows and tools that break vert and facet compatibility with the original mesh, such as breaking it up into subtools)

* Export the shape (at the desired resolution) to OBJ

* Use Morph Loader Pro in Daz Studio to import the shape as a morph target at HD resolution. 

  * **IMPORTANT:** *The shape you are working with throughout this entire process should <u>not</u> have navel or nipples included. Those will be created/loaded later*

* Apply a [tiling texture](https://drive.google.com/file/d/1G9yzpOaK0mhYPD8UpGME6rYn7bTO2fPC/view?usp=sharing) to the surfaces of the figure and set your morph to 100%. You are looking for areas that distort badly in order to identify areas the shape needs to be fixed. If there are problems then go back into ZBrush and slide geometry around to remove the bad distortions and bring it back in as a morph. The original morph can be deleted or replaced.

* Once you are satisfied there isn’t too much distortion in the sculpt you will need to build the base resolution morph. The most basic method is by doing the following:

  * Set your morph (from the previous step) to 100%
  * Set to base resolution, export cage version of the mesh
  * Set to high res at SubD level 2 and export to OBJ. This will be used as a reference for fixing the volume of the base resolution morph
  * Load the two meshes into a modeler, subdivide the base resolution version and place the subD level 2 (reference) mesh in the background. You should see all sorts of areas of the mesh where the high-resolution morph is poking through the base resolution mesh
  * Pull the geometry of the base resolution mesh out to match the volume of the reference mesh. Pay special attention to areas around the face such as ears and lips

* With the optimized base-resolution and high-resolution versions of the character done you are ready to load these into Daz Studio as morph targets. You will end up with 4 morph targets: body, head, HD body, HD head. The naming convention is consistent so it is easy to follow. Substitute your character name for Victoria in the following example:

  * Body - FBMVictoria8_1
  * Head - FHMVictoria8_1
  * HD Body - FBMVictoria8_1_HDLv4
    *  The final number indicates subdivision level
  * HD Head - FHMVictoria8_1_HDLv4 
    * The final number indicates subdivision level

* To load the morphs:

  * Apply Head Split DFormer
  * Launch MLP and add base resolution morph twice
  * First one will be the head morph, name per instructions above
  * Set “Attenuate By” to the weight map and use default setting of 1 for the Strength
  * Second will be the body morph, name per instructions above
  * Set “Attenuate By” to the weight map and set Strength to -1
  * Click Accept
  * Dial head and body morph, making sure to also verify the head split is good
  * With both head and body morph set at 100%, launch MLP and add the HD morph twice. On both:
    * Set Morph Subdivision to Yes, Built Resolution to 4, SubD Mapping to ZBrush (if subdivided in ZBrush, otherwise leave default)
    * Set Delta Tolerance to 0.0001
    * Set Reverse Deformations to Yes
  * First one will be the head morph, name per instructions above
  * Set “Attenuate By” to the weightmap and use default setting
  * Second will be the body morph, name per instructions above
  * Set “Attenuate By” to the weightmap and set Strength to -1
  * Click Accept

* Fix issues that inevitably come up at this point, such as teeth and eye problems Generally the eyes and inner mouth should not be affected by the head morph other than to be moved into place, possibly some scaling if necessary

  * Load base resolution OBJ as reference for where teeth and eyes should be
  * With Geometry Editor tool select Teeth and Mouth surfaces
  * Select both head morphs (base and HD)
  * Run “Clear HD Morph Deltas (Faces)” script
  * Compare position of mouth and eyes to reference OBJ
  * If position now needs to be fixed it could be done in DS or in an external modeler
  * To do it in DS, create a dFormer, create weightmap that only affects the part you want to move, move it into place and export to OBJ. Delete dFormer
  * Reload fixed head morph, making sure name matches so it will replace the current oneSave morph assets by running 

* Save Morph Assets script

  * Set Asset Directory to the project directory
  * Set Vendor Name to “Daz 3D”
  * Set Product Name to the name of the character, making sure to use “_” instead of a “.” (ie Victoria 8_1)

* Once the sculpt is loaded in and fixed up properly you will move on to the rigging portion of the process

## Rigging A Character

"Rigging" a Genesis-based character involves the following:

* Moving the bone positions relative to the mesh changes of the character shape

* Joint Correction

* Morph Correction

**KEEP IN MIND:**

Sometimes a problem is caused by reckless sculpting (such as not maintaining landmarks properly or by sliding geometry around). Often it is best to go back into a modeler and fix the problem (while maintaining the original sculpted shape). As an example, if you find an area that is problematic with multiple morphs and/or joint bends you may want to save yourself time and fix the sculpt once instead of fixing each problem

Other times you will find that building custom corrective morphs for a problem will be necessary. The number of correctives you will need to create is going to be different with every character and obviously will be highly influenced by how much you are changing the shape from the base mesh and how carefully it was built. Some characters end up with **0 corrective morphs** for joints, some end up with **30 or 40**. In addition, it is pretty common to end up with another **20 to 60** corrective morphs to fix morph issues with various morphs on the genesis figure. Again, this number fluctuates based on how much change is introduced in the character shape and by how carefully the sculpt was done

## Moving The Bones

Moving the bone positions relative to the character shape is a critical first step in rigging a character. This needs to be done on the base resolution version of the body and head morph and should be done one morph at a time. Below I will outline the basic steps when doing this manually. To get faster, more optimized results you can also consider purchasing and using [this product](https://www.daz3d.com/shape-rigger-plus) instead.

* Dial the base resolution body morph to 100%
* Activate the Joint Editor Tool, right-click in the viewport and go to Edit > Adjust Rigging to Shape
* Right-click on Neck Upper and Uncheck Selected and Children
* Uncheck face groups related to the head (Head, lEye, rEye, LowerJaw, Tongue, UpperJaw)
* Click Accept
* Put Parameters Pane into Edit Mode, right-click on the body morph you dialed up and adjusted the bones to, click on ERC Freeze 
* Make sure the list is only populated by body bone movements and click Accept. You should now be able to dial the morph up and down, watching the bones move with the shape
* Dial off the body morph and repeat steps 1-7 above but with the head morph, making sure to invert what you have selected in the dialog (this time you want all bones unchecked except starting from Neck Upper, and you only want the head related face groups)

## Joint Correction

Correcting joint bend issues refers to moving the bone positions relative to the mesh changes and then evaluating every bone rotation to find issues. When an issue is found you evaluate what the best course of action is for fixing it.

**IMPORTANT:** *The rigging should only need to be done on the base resolution morphs. The HD morph is just the details so won’t need much work done specifically for it. If details are sculpted in on the knees and elbows then a common corrective we make is one to smooth the knees and elbows when they bend. All HD work will get done after all the base resolution work is done.*

Common workflow would be:

* Dial body morph to 100%
* Start at toes, check each joint for bend issues, working your way up to the lower neck bone. 
* To check for issues, rotate the bone on each axis, one at a time, from minimum value to maximum value
* To fix an issue:
  * Export to OBJ the problem pose (ie lFoot Bend Up). Naming is very important and should follow the same naming formula every time. 

## Morph Correction

The rigging process doesn't stop there, however…

Next, we evaluate how the character interacts with morphs on the face and any of the body ones that make sense to support (ie. breast morphs for the female). The morphs you need to check your character against are all either included with the Genesis mesh you are building for (look for purple or red properties) or are in the following products that you need to install:

* [Genesis 8 Female Body Morphs](https://www.daz3d.com/genesis-8-female-body-morphs)
* [Genesis 8 Female Head Morphs](https://www.daz3d.com/genesis-8-female-head-morphs)

* [Genesis 8 Female Expressions](https://www.daz3d.com/genesis-8-female-expressions)
* [Genesis 8 Male Body Morphs](https://www.daz3d.com/genesis-8-male-body-morphs)
* [Genesis 8 Male Head Morphs](https://www.daz3d.com/genesis-8-male-head-morphs)
* [Genesis 8 Male Expressions](https://www.daz3d.com/genesis-8-male-expressions)

Morphs are split into two main types: Posing and Shaping. They can be found under the Panes by those names or by navigating in the Parameters Pane to the “Pose Controls” group for Posing and the “Actor” group for Shaping.

## Posing Morphs
## Shaping Morphs
## Final Setup

* Y Traslation
* Scale