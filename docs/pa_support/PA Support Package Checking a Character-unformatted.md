# Checking a Character

## Clones
Clones are not to be used in the creation of characters.

## Check included morphs

###  data/Morphs Folder check 

-   Check folder pathing and content.

-   Watch for base Genesis or other stray files.

-   Open each dsf file, OR specifically look at each morph dial in Studio and check to make sure that:

     1.  Image Cards are linked in and show up

     2.  Morph locations are correct and Match Base Figure morph locations

     3.  Dial Label Names make sense and limits are set min 0 and max 1

     4.  Morphs for Genesis 8 should be percents

### Check Image Cards.

Correct size and image placement. CTRL, FBM and FHM should have morph cards. CTRL and FBM card should be 147x185, FHM should be 91x91

*If the character preset (other than Genesis 8) references the Character Addon Loader script, make sure it is included in the data folder. Proper attribution is required, correct text to put in the readme is: Character Addon Loader script from Genesis 8 Starter Essentials used with permission from Daz 3D*

b.  4\. Eyelashes Morphs for Genesis 8 Only-

1.  Make sure there is a matching morph for any eyelash morphs on both the base figure and the lashes.

2.  Eyelashes morph needs to be hidden on the lashes and visible on the Base Figure.

    a.  Morph Dials:

        i.  Characters should have Separate Head and Body Morphs, and a
            Control Dial Unless it makes more sense to have as one morph
            as in an alien for example.

            1.  Character presets should be made from the above
                > mentioned control dial instead of individual head and
                > body morphs.

    b.  People Folder Checks -

        i.  Character preset is in the Characters folder and named
            uniquely not just "Character Name" but "3DU Character Name
            G8 Female" as an example. Character Folder and all files in
            it should match the Character Preset Name!! "Character Name
            8" (or 8.1) is reserved for Daz Figures ONLY They must have
            the PA Name Abbreviation!!

            1.  Examples:

                a.  PAName Character Name G8 Female

                b.  PAName Character Name G8.1 Female

        ii. All other files are included in the Character Name folder
            and/or subfolders.

        iii. Apply and Remove shaping presets are optional

3.  Check for required products or bad reference calls:

    a.  Check PASS for any listed required products.

    b.  Make sure that there is nothing except for the Starter
        Essentials and the character you are testing mapped in the
        Content Library.

        i.  DO NOT have the required products installed.

        ii. Load Character into the Scene.

        iii. Make sure that missing file errors populate in the log. If
             they do not, you know that they have a DSF in the data
             folder that should not be there.

4.  Test the Character shape

    a.  Map any required products to the Content Library

        i.  Clear the log file.

        ii. Load the character into the Scene.

            1.  Make sure that no errors appear in the log file.

        iii. Go to the Scene pane and make sure the character's name is
             listed here.

             1.  It should not read Genesis 8 Female. It should be the
                 > character\'s name. 1

        iv. Select the character in the Scene pane.

        v.  Go to the Parameters pane.

    b.  Genesis 9 Characters and proportions:

        i.  Genesis 9 Characters should be in same proportions as base
            figure.

        ii. if you need to change the proportions of anything like leg
            length, height etc then utilize proportion dials.

        iii. Best practice is to have the proportion dials dialed up by
             your character preset, unless the character looks unusual
             without them, then including them in the Character dial
             would be ok.

    c.  Check the Currently Used morphs

        i.  Any Head/Body/Ctrl dials should be applied

        ii. Other morphs included with the character may or may not be
            applied.

        iii. Navel morph should be applied.

        iv. Mouth Realism HD should be applied

        v.  Characters for a Core Character i.e. Sally for Victoria 8
            should have Victoria 8 applied.

        vi. dial spun characters will have the relevant Head/Body morphs
            applied

        vii. Make sure that the Character preset is dialing up the
             Control dial, as well as any other dials included.

        viii. The Character morph should be named the same name as the
              character you are testing.

        ix. Dial up each morph individually.

        x.  Scale should be driven by the main character control
            property (CTRL), not the body morph

        xi. Morphs that move the mesh significantly, should also move
            the relevant bones.

        xii. Pose controls move bones.

        xiii. Make sure morph limits are set.

        xiv. For multiple morphs for a character after testing each
             morph, make sure that it is at 0% before moving on to the
             next morph.

        xv. Make sure to be consistent between points and percentages.

        xvi. Morphs should show up in both the Parameter and Shaping
             Panes.

        xvii. Hidden morphs-morphs in the HIdden group-should be hidden,
              not visible.

        xviii. For HD Characters/morphs, Viewport subDivision Level
               should not exceed 2 (1 is fine). Render subDivision level
               should not exceed the morph's level.

        xix. Make sure that the head and body morph images go to the
             Dark Gray borders. Ideally, it should not go beyond or
             cover the morph name.

        xx. The dials for the character Morphs need to be placed in the
            correct groups.

        xxi. PA's should look at base characters if they have a question
             on how their morphs should be set up.

             1.  There are also tutorials on how to do this.

    d.  Remove the figure from the scene.

        i.  Load in a blank base figure

            1.  Ex. Genesis 3 Female, Genesis 8 Male, etc.

            2.  Make sure that none of the morphs from the figure you
                > are testing are auto-dialing onto the base figure

                a.  Check under Currently Used in the parameter pane

        ii. Check affected verts for each morph

            1.  Go to the Tool Settings pane

                a.  Change Active Tool to the Geometry Editor.

                b.  Select the Vertex Selection in the top left corner
                    > of the Tool Settings pane.

                    i.  Currently, this is the only way to check morphs
                        > for stray vertices

            2.  Go back to the Parameters pane

                a.  Right click in the empty space in the Parameters
                    > pane and choose Edit Mode.

                b.  Right-click on the \[M\] next to the head morph dial
                    > and choose Select Morph Vertices.

                    i.  It should zero in on the head.

                c.  Right-click on the \[M\] next to the body morph
                    > dials and choose Select Morph 2

> Vertices.

i.  It should not have the whole body selected.

ii. Head should only be included in the head morph.

```{=html}
<!-- -->
```
d.  These vertices tests should also be done with the head hidden in the
    > scene pane. If the teeth are being unintentionally affected, check
    > if they are warping. If so, they need to be fixed.

```{=html}
<!-- -->
```
iii. If there are brows/lashes, load them onto the base figure into the
     scene.

     1.  Dial up the head morph

     2.  Make sure the lashes are still working correctly.

     3.  Look at these from ALL angles. Make sure that they are not
         > sitting away from the head.

     4.  Also Dial the eyeball rotation morphs to make sure the
         > brows/lashes are not breaking.

     5.  Apply and check any included morphs for the lashes.

     6.  Test the Eyes Closed morphs.

     7.  Load any MATs onto the brows/lashes.

         a.  Make sure they load correctly.

         b.  Make sure that the color that loads matches the color in
             > the thumbnail?.

iv. Check the morphs posing

    1.  Apply several of the testing poses with the body morph applied
        > and look for distorted joints.

    2.  Apply several expressions with the head morph applied and look
        > for distortion.

        a.  Select the Eyeballs.

            i.  Use the translate options to Twist the eyes, and make
                > sure that they stay in place.

            ii. Move them side-side and make sure it works correctly

        b.  Test the Eyes Closed morphs.

v.  Test shaping presets

    1.  Apply each of these onto the base figure and make sure that they
        > apply the intended morphs.

    2.  REM presets should remove any and everything applied by the
        > Apply preset.

vi. Test the body MATs for the character.

    1.  Make sure they load correctly.

    2.  The base material skin \"all\" mat should load everything that
        > comes with this character.

> i.e. Eyelashes, genitalia, eyebrows, antennae, etc.

3.  For Genesis 8, make sure the base material skin and any eyelash
    > material presets are loading the character eyelash materials, Not
    > leaving them blank.

    a.  You can check this in the surfaces pane for the eyelashes.

        i.  You can also check the transparency maps.

4.  Check the seams:

    a.  Do a full body render.

    b.  Go to the toes and check the seams.

        i.  Make sure to check between the toes.

            1.  Use the spread toes pose controls.

        ii. Spot render to check for seams.

    c.  Go up the leg where the seam shows on the UV's.

        i.  If there is anything out of the ordinary, do a spot render.

    d.  Render a profile image of the figure.

        i.  Make sure that the specularity from the top and bottom of
            > the head seam are not off.

    e.  Use the Mouth Open morph.

        i.  Zoom in and select the back of the tongue.

        ii. Look inside the mouth.

        iii. Check for seams.

        iv. Raise the tongue and look under for seams.

        v.  Also check to make sure that the teeth are in the gums.

    f.  Check for Seams underneath the chin.

    g.  Check for Seams on the back of the ears.

    h.  To check the arm seams, put figure into a T Pose.

vii. 

viii. Test the Navel morph.

      1.  Does it load on the Navel detail?

      2.  If they are using custom Nipple or Navel morphs (you can tell
          > by looking in the data folder) then those need to be done as
          > MCM with reverse deformation. and should only apply when
          > that specific body is applied

ix. Check if there is a genital morph that applies to the base mesh.

    1.  If there is one tell the PA that it needs to be removed, no gens
        > morph dials at all on Base Figures.

    2.  Genital morphs can only be applied to the geo-graft genitalia so
        > that it can't be applied to young teen/children.

x.  Check the Nipple morphs.

    1.  Does it load in the center of the nipple where it should?

xi. Check ear details.

    1.  Do they line up with the morphs?

xii. Select the Eyeball.

     1.  Use the rotation options to Twist the eyes.

         a.  Make sure that they stay in place.

     2.  Move them side-side.

         a.  Make sure it works correctly

xiii. Check hands

      1.  Make sure that the wrinkles are correct.

          a.  Sometimes PA's put the wrinkles going out instead of into
              > the skin.

      2.  Check between the fingers for seams and that long nail morphs
          > do NOT have skin on the underside of them.

xiv. Check MAT presets.

     1.  See if product has Iray/3Delight MATs

     2.  Make sure that MAT is applying what the thumbnail shows.

     3.  Make sure that all MATs load correctly

         a.  Eyes

         b.  Eyelashes

         c.  Lips

         d.  Makeup

         e.  Nails

         f.  Needs a reset to natural nails.

         g.  Brows

     4.  Sometimes the difference in the hair colors are very subtle so
         > you will have to look in the Surfaces pane while loading the
         > materials to see if there is a difference between the MATs

     5.  Hierarchical Materials:

         a.  Eyebrows, Eyelashes, Genitals, and any other material
             > additive to the figure like Zalera spine should be
             > Hierarchical so they apply the item materials and not the
             > base character material.

         b.  Strip materials from Character and Select the figure root
             > then apply the H. Mat to check this.

```{=html}
<!-- -->
```
d.  If character has JCM's, you will need to test them.

    i.  JCMs are Joint Control Morphs. They are morphs triggered by the
        joint.

    ii. Clear your log

    iii. Activate the joint editor tool.

    iv. Apply poses to the figure. Check for anything that doesn't look
        normal and make sure the bones are moving properly for both head
        and body.

    v.  Applying the poses will generate notes in the log on which JCMs
        have fired off.

    vi. Open the Log and compare the list in the log file to the data
        folder JCMs and note any that didn\'t fire off.

    vii. Use that list and manually move the bone(s) listed in the JCMs
         to see if it was just missed by the poses.

    viii. Dial in Base expressions to make sure that nothing is going
          wrong with the posing.

di\. Checking for Erc Bone information in Property Hierarchy

i.  In parameters Tab go into edit mode

ii. Select the morph you wish to check

iii. Right Click on the morph

iv. At the Bottom of the list select Show in Property Hierarchy

v.  Open the all of the little triangle to fully expand so you can see
    all of the bones

    1.  This may require you to drag the little separators at the top to
        > make the names visible

vi. The head should only have head bones and body should only have body
    bones in here just like the vertices

    1.  Just scroll through the list to see if there are any bones not
        > for that morph

    2.  If there are body bones in the head or head bones in the body,
        > fix it.
