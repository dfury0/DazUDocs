# 08 | Floor length dress with control bones

Workflow by [Mada](https://www.daz3d.com/mada)

Skill level : Advanced
I recommend working through basic rigging tutorials first

![type:video](https://www.youtube.com/embed/joIM9_usd1g)

Length : 17:41

## Weightmapping

- Import dress obj and apply SubD
  - Assets | Transfer Utility
  - Source : Genesis 8 Female | Target : Dress | Projection Template : Full-Body
    *(I’m not using the knee-length dress template because it doesn’t have Thigh Twist and Shin bones and I want them included to rig for a long dress)*
- Turn off Base Joint Correctives on Genesis
- Select the Geometry Editor and start cleaning up the face groups
  - Select rFoot and rToe faces, right click on rShin | Assign Selected Faces to Group
  - Select lFoot and lToe faces, right click on lShin | Assign Selected Faces to Group
- Save Dress
  - File | Support Asset | Figure/Prop Assets
- Change to Weight Map Brush and select the toes, metatarsals and feet on the dress, use subtractive painting to remove the weight from the toes and feet
  - If you use subtractive painting but the map stays red, use the smooth brush over it first and then try subtractive painting again – it should work after smoothing
- Pose the left and right thighs to the side and use the smoothing brush to start evening out the map, alternating between the shins, thigh twist and bend. If you have too much weight from the shin bones on the thighs use subtractive painting to remove it and smooth back the edges on the shins
- Weightmap the rest of the dress, I start at the neck and work down to the feet, adjusting shin bends a bit more
- Then I go to collars and work my way down to the hands, paying attention to the areas under the arms when you bend the collar and shoulders up and front



![type:video](https://www.youtube.com/embed/_PEFekuvHAQ)

Length : 23:47

## JCM Top/Sleeves

- Turn on Base Joint Correctives on Genesis
- Start with the neck again and work your way down to the pelvis
- Use the exact same name for the JCM as the one being used on Genesis, that will then overwrite the existing JCM when you import it back into DS
- Fix your morph in a modeler and import with Morph Loader Pro
  - Reverse Deformations : Yes
  - Overwrite Existing : Deltas only
- There are 2 JCMs in the neck that you have to dial up at the same time to create the morph
  - For *pJCMNeckFwd_35* bend both Neck Lower and Neck Upper forward. That will set the dial to 100% – export and fix in modeler, import back into Daz Studio
  - For *pJCMNeckBack_27* bend both Neck Lower and Neck Upper back – that will set the dial to 99% which is usually close enough so I don’t bother to unlock the bend further – export and fix in modeler, import back into Daz Studio
- Collars : bend down is usually fine but bend up needs to be fixed in a modeler with attention to under the arms and around the neck for collars
  - *pJCMCollarUp_55_L*
- Shoulders : bend down and up needs to be fixed
  - *pJCMShldrUp_90_L*
  - *pJCMShldrDown_40_L* – turn smoothing off or collide against nothing if you find the hand goes into the cloth at the hips
- Shoulders : front and back. I will sometimes add a custom morph for shoulders back if there’s poke through that I can’t fix with weightmapping. Forward always need to be fixed
  - *pJCMShldrFwd_110_L*
- Multidimensional Property Morphs are already in Genesis for Shoulders front + bend down and up. You can use the exact same JCM name and then you don’t have to do anything except import into the clothing, it will replace the morph created by Genesis
  - *pJCMShldrFront_n110_Bend_n40_L*
  - *pJCMShldrFront_n110_Bend_p90_L*
- I spend a bit of time in getting the shoulders bending down to look good, since that’s the pose that will be used the most and you want a good silhouette



![type:video](https://www.youtube.com/embed/dhfvr2GbBtk)

Length : 31.43

## JCM Legs

- Bend left thigh to side and export with base resolution and the exact same JCM name as Genesis to fix in a modeler, repeat for the right thigh
  - If you use smoothing set the collision item to None otherwise the hands on Genesis intersects with the mesh and causes distortions
  - *pJCMThighSide_85_L*
  - *pJCMThighSide_85_R*
- Use a texture as a guide to even out the morph on the dress
- Import into Daz Studio with reverse deformation on and deltas only and it will overwrite the existing JCMs
- Bend the left Thigh to -57 and export JCM, fix in modeler. Repeat for right thigh
  - *pJCMThighFwd_57_L*
  - *pJCMThighFwd_57_R*
- I add a custom morph in for thighs left and right bend at -90. Bend the left thigh to -90, export and fix in modeler, import and ERC freeze. Repeat for the right thigh.
  - *pJCMThighFwd_90_L*
  - *pJCMThighFwd_90_R*
- Bend the left thigh to -115, export and fix in modeler. Repeat for right thigh
- Import into Daz Studio with reverse deformation on and deltas only and it will overwrite the existing JCMs
- Bend down the feet and if there’s a JCM distorting the dress open parameter settings
  - *pJCMFootDwn_75_L
    pJCMFotoDwn_75_R*
  - Set Min to 0 and Max to 0
  - Tick Use Limits and untick Auto follow
  - Change Type from Modifier/Shape/Generated to Modfier/Shape
- Repeat for the right foot
- Bend the feet up and follow the same steps as above to remove the JCM
  - *pJCMFootUp_40_L*
  - *pJCMFootUp_40_R*
- Bend the left shin to 90, export and fix in modeler. Repeat for right shin
  - *pJCMShinBend_90_L*
  - *pJCMShinBend_90_R*
- Import into Daz Studio with reverse deformation on and deltas only and it will overwrite the existing JCMs
- Bend left shin to 155, and fix in modeler if needed. For long dresses this is often too extreme a bend between the shins, in that case I ignore it and just turn the JCM off to prevent distortions.
  - *pJCMShinBend_155_L*
  - *pJCMShinBend_155_R*
  - Set Min to 0 and Max to 0
  - Tick Use Limits and untick Auto follow
- Change Type from Modifier/Shape/Generated to Modfier/Shape
- Repeat for the right shin
- I add a custom morph for when both thighs bend together at -90
  - *pJCMThighFwd_90_LR*
- Use the Multidimensional Property Setup script to set up the formula for when both thighs bend at the same time
  - Select the Figure, Left Thigh Bend and Right Thigh Bend in Scene tab
  - Select Bend under Currently Used in the parameters tab (there should be a 2 after it in brackets if everything is set up right)
  - Run the Multidimensional Property Setup script
- Last custom morph is for when both shins are bent together at 90. Because of how the shins bend backwards quite often long dresses will start intersecting in the middle. I click on the dress shins and use the parameter dials to adjust them out to where there’s less intersection
  - *pJCMShinsBend_90_LR*
- Use the Multidimensional Property Setup script to set up the formula for when both thighs bend at the same time
  - Select the Figure, Left Shin Bend and Right Shin Bend in Scene tab
  - Select Bend under Currently Used in the parameters tab (there should be a 2 in brackets if everything is set up right)
  - Run the Multidimensional Property Setup script
- Next I create 2 morphs for when you move the thighs in – I usually set it about 15 (rThigh) and -15 (lThigh) for longer dresses but play around depending on shape. The idea is to minimise the amount of intersection in the skirt
  - *pJCMThigh_In_L*
  - *pJCMThigh_In_R*
- The final morph I create is for when Genesis is in a normal standing pose with both legs closer together instead of the A pose. Because of the A pose often there is a weird kink or compression in the middle of dresses, I remove most of that with a Multidimensional Property Setup Morph
- Adjust the thighs in on Genesis to a standing pose – usually I use around 6 or 7
- Click on the control handles for the thighs in the dress and adjust them out a bit more
- Export a base resolution obj to fix in your modeler
  - *JCMThighsIn_LR*
- Zero the thigh handles before you import the morph with Multiloader Pro
  - Reverse deformations on
- Open the parameter settings and set the morph 0 for Min and dial the morph up
- Use the Multidimensional Property Setup script to set up the formula
  - Select the Figure, Handle_lThighBend and Handle_rThighBedn in the Scene Tab
  - Select Side-Side on the Parameter Tab under Currently Used (there should be a 2 in brackets if everything is set up right)
- Run the Multidimensional Property Setup script

## Creating control bones

- Select the Joint Editor tool and click on the Left Thigh Bend in the scene tab

- Right click in the viewport

  - Create | Create Control Bone(s)
  - I change the prefix from cb_ to Handle_ to make it more clear on usage
  - Mode | Selected and Children

- Duplicate steps for the Right Thigh Bend

- Select the bones you don’t want to be visible in the scene view

  - Handle_lFoot, Handle_lMetatarsals, Handle_lToe

  - Joint Editor Tool | Tool Settings | Hide in Scene View(s) should have a checkmark

- Duplicate steps for right leg

- Click on Handle_Left_Thigh in the scene tab and go to tool settings for the Joint Editor Tool

  - On the Selection Group dropdown find the the different body parts you have selected and tick the box to change the Assigned Bone
  - select Handle_lShin | tick box for lShin
  - select Handle_lThigh | tick box for lThigh
  - select Handle_rShin | tick box for rShin
  - select Handle_rThigh tick box for rThigh

- Now when you click on the figures thigh it will select the dress thigh and you can adjust it as needed, handy to fix poke throughs especially when the thighs bend in too much on the figure