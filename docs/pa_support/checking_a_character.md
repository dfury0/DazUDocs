# Checking a Character

## Check included morphs

### data//Morphs Folder check

* Check folder pathing and content.
* Watch for base Genesis or other stray files.
* Open each DSF file, OR specifically look at each morph dial in Studio and check to make sure that:
  * Image Cards are linked in and show up
  * Morph locations are correct and Match Base Figure morph locations
  * Dial Label Names make sense and limits are set min 0 and max 1
  * Morphs for Genesis 8 should be percents
* Check Image Cards for correct size and image placement. CTRL, FBM and FHM should have
  morph cards. CTRL and FBM card should be 147x185, FHM should be 91x91
*  If the character preset (other than Genesis 8) references the Character Addon Loader
  script, make sure it is included in the data folder. Proper attribution is required, correct
  text to put in the readme is: Character Addon Loader script from Genesis 8 Starter
  Essentials used with permission from Daz 3D

### Eyelashes Morphs for Genesis 8 Only

Make sure there is a matching morph for any eyelash morphs on both the base figure
and the lashes.

Eyelashes morph needs to be hidden on the lashes and visible on the Base Figure.

### Morph Dials

Characters should have Separate Head and Body Morphs, and a Control Dial Unless it makes
more sense to have as one morph as in an alien for example.

Character presets should be made from the above mentioned control dial instead of
individual head and body morphs.

### People Folder Checks

Character preset is in the Characters folder and named uniquely not just “Character Name” but
“3DU Character Name G8 Female” as an example. Character Folder and all files in it should
match the Character Preset Name!! “Character Name 8” (or 8.1) is reserved for Daz Figures
ONLY They must have the PA Name Abbreviation!!

Examples:

* PAName Character Name G8 Female
* PAName Character Name G8.1 Female

All other files are included in the Character Name folder

Apply and Remove shaping presets are optional

## Check for required products or bad reference calls

Check PASS for any listed required products.

Make sure that there is nothing except for the Starter Essentials and the character you are testing
mapped in the Content Library.

* DO NOT have the required products installed.
* Load Character into the Scene.
* Make sure that missing file errors populate in the log. If they do not, you know that they have a
  DSF in the data folder that should not be there.

## Test the Character shape

#### Map any required products to the Content Library

* Clear the log file.
* Load the character into the Scene.
  * Make sure that no errors appear in the log file.
* Go to the Scene pane and make sure the character’s name is listed here.
  * It should not read Genesis 8 Female. It should be the character's name.
* Select the character in the Scene pane.
* Go to the Parameters pane.

#### Check the Currently Used morphs

1. Any Head/Body/Ctrl dials should be applied
2. Other morphs included with the character may or may not be applied.
3. Navel morph should be applied.
4. Mouth Realism HD should be applied
5. Characters for a Core Character i.e. Sally for Victoria 8 should have Victoria 8 applied.
6. Dial spun characters will have the relevant Head/Body morphs applied
7. Make sure that the Character preset is dialing up the Control dial, and any other dials
   included.
8. The Character morph should be named the same name as the character you are testing.
9. Dial up each morph individually.
10. Scale should be driven by the main character control property (CTRL), not the body morph
11. Morphs that move the mesh significantly, should also move the relevant bones.
12. Pose controls move bones.
13. Make sure morph limits are set.
14. For multiple morphs for a character after testing each morph, make sure that it is at 0% before
    moving on to the next morph.
15. Make sure to be consistent between points and percentages.
16. Morphs should show up in both the Parameter and Shaping Panes.
17. Hidden morphs-morphs in the hidden group should be hidden, not visible.
18. For HD Characters/morphs, Viewport subDivision Level should not exceed 2 (1 is fine). Render
    subDivision level should not exceed the morph’s level.
19. Ensure the head and body morph images go to the Dark Gray borders. Ideally, it should
    not go beyond or cover the morph name.
20. The dials for the character Morphs need to be placed in the correct groups.
21. PA’s should look at base characters if they have questions about how their morphs should be set
    up. 

> There are also tutorials on how to do this.

#### Remove the figure from the scene.

##### Load in a blank base figure

* Ex. Genesis 3 Female, Genesis 8 Male, etc.
* Make sure that none of the morphs from the figure you are testing are auto-dialing onto
  the base figure 
  * Check under Currently Used in the parameter pane

##### Check affected verts for each morph

Go to the Tool Settings pane

* Change Active Tool to the Geometry Editor.
* Select the Vertex Selection in the top left corner of the Tool Settings pane.
* Currently, this is the only way to check morphs for stray vertices

Go back to the Parameters pane

* Right-click in an empty space in the Parameters pane and choose Edit Mode.
* Right-click on the [M] next to the head morph dial and choose Select Morph
  Vertices.
  * It should zero in on the head.
* Right-click on the [M] next to the body morph dials and choose Select Morph
  Vertices.
  * It should not have the whole body selected.
  * Head should only be included in the head morph.
* These vertices tests should also be done with the head hidden in the scene
  pane. If the teeth are being unintentionally affected, check if they are warping. If
  so, they need to be fixed.

###### If there are brows/lashes, load them onto the base figure into the scene.

* Dial up the head morph
* Make sure the lashes are still working correctly.
* Look at these from ALL angles. Make sure that they are not sitting away from the head.
* Also Dial the eyeball rotation morphs to make sure the brows/lashes are not breaking.
* Apply and check any included morphs for the lashes.
* Test the Eyes Closed morphs.
* Load any MATs onto the brows/lashes.
  * Make sure they load correctly.
  * Make sure that the color that loads matches the color in the thumbnail.

###### Check the morphs posing

* Apply several of the testing poses with the body morph applied and look for distorted
  joints.
* Apply several expressions with the head morph applied and look for distortion.
  * Select the Eyeballs.
    * Use the translate options to Twist the eyes, and make sure that they stay
      in place.
    * Move them side-side and make sure it works correctly
  * Test the Eyes Closed morphs.

###### Test shaping preset.

* Apply each of these onto the base figure and make sure that they apply the intended
  morphs.
* REM presets should remove any and everything applied by the Apply preset.

###### Test the body MATs for the character.

* Make sure they load correctly.
* The base material skin "all" mat should load everything that comes with this character.
  * Eyelashes, genitalia, eyebrows, antennae, etc.
* For Genesis 8, make sure the base material skin and any eyelash material presets are
  loading the character eyelash materials, Not leaving them blank.
  * You can check this in the surfaces pane for the eyelashes.
  * You can also check the transparency maps.
* Check the seams:
  * Do a full-body render.
  * Go to the toes and check the seams.
  * Make sure to check between the toes.
    * Use the spread toes pose controls.
  * Spot render to check for seams.
* Go up the leg where the seam shows on the UV’s.
  * If there is anything out of the ordinary, do a spot render.
* Render a profile image of the figure.
  * Make sure that the specularity from the top and bottom of the head seam
    are not off.
* Use the Mouth Open morph.
  * Zoom in and select the back of the tongue.
  * Look inside the mouth.
  * Check for seams.
  * Raise the tongue and look under for seams.
  * Also check to make sure that the teeth are in the gums.
* Check for Seams underneath the chin.
* Check for Seams on the back of the ears.
* To check the arm seams, put the figure into a T Pose.

###### Test the Navel morph.

* Does it load on the Navel detail?
* If they are using custom Nipple or Navel morphs (you can tell by looking in the data
  folder) then those need to be done as MCM with reverse deformation and should only
  apply when that specific body is applied

###### Check if there is a genital morph that applies to the base mesh.

* If there is one tell the PA that it needs to be removed, no gens morph dials at all on Base
  Figures.
* Genital morphs can only be applied to the geo-graft genitalia so that it can’t be applied to
  young teen/children.

###### Check the Nipple morphs.

* Does it load in the center of the nipple where it should?

###### Check Ear details. 

* Do they line up with the morphs?

###### Check the Eyeball.

* Select the eyeball and use the rotation options to Twist the eyes.
  * Make sure that they stay in place.
* Move them side-side.
  * Make sure it works correctly

###### Check hands

* Make sure that the wrinkles are correct.
  * Sometimes PA’s put the wrinkles going out instead of into the skin.
* Check between the fingers for seams and that long nail morphs do NOT have skin on the
  underside of them.

###### Check MAT presets.

	1. See if product has Iray/3Delight MATs
	2. Make sure that MAT is applying what the thumbnail shows.
	3. Make sure that all MATs load correctly
    	1. Eyes
    	2. Eyelashes
    	3. Lips
    	4. Makeup
    	5. Nails
    	6. Needs a reset to natural nails.
    	7. Brows
	4. Sometimes the difference in the hair colors are very subtle so you will have to look in the
    Surfaces pane while loading the materials to see if there is a difference between the
    MATs
	5. Hierarchical Materials:
    	1. Eyebrows, Eyelashes, Genitals, and any other material additive to the figure like
        Zalera spine should be Hierarchical so they apply the item materials and not the
        base character material.
    	2. Strip materials from Character and Select the figure root then apply the H. Mat to
        check this.

###### If the character has JCM’s, you will need to test them.

1. JCMs are Joint Control Morphs. They are morphs triggered by the joint.
2. Clear your log
3. Activate the joint editor tool.
4. Apply poses to the figure. Check for anything that doesn’t look normal and make sure the bones
   are moving properly for both head and body.
5. Applying the poses will generate notes in the log on which JCMs have fired off.
6. Open the Log and compare the list in the log file to the data folder JCMs and note any that didn't
   fire off.
7. Use that list and manually move the bone(s) listed in the JCMs to see if it was just missed by the
   poses.
8. Dial in Base expressions to ensure that nothing is going wrong with the posing.

Checking for Erc Bone information in Property Hierarchy

1. In parameters Tab go into edit mode
2. Select the morph you wish to check
3. Right Click on the morph
4. At the Bottom of the list select Show in Property Hierarchy
5. Open the all of the little triangle to fully expand so you can see all of the bones
   1. This may require you to drag the little separators at the top to make the names visible
6. The head should only have head bones and body should only have body bones in here just like
   the vertices
   1. Just scroll through the list to see if there are any bones not for that morph
   2. If there are body bones in the head or head bones in the body, fix it.