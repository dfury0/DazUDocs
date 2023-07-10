---
title: "[]{#Guide to Using the Scripts in the PA Sup .anchor}Guide to
  Using the Scripts in the PA Support Package"
---

There are several scripts contained in the pa support package, these are
designed to help you complete certain tasks. Please see below on how to
use each one, In many cases they are mentioned in the appropriate
testing documents. Some items in the scripts folder are not actual
Script but placed here to keep all the utility tools together.

1.  PA Support Package Script:

    A.  This makes a Box that has several of the scripts in it.

        1.  Clear Troubleshooting Log

        2.  List Geometry Source

        3.  List Morphs

        4.  Random All Colors

        5.  Embedded Geometry Check - In File

    B.  Simply Activate the script and move the box wherever you want

2.  Clear Troubleshooting Log

    A.  Will Clear the Troubleshooting log

    B.  Troubleshooting log can be found at Help\>Troubleshooting\>View
        > Log File

        1.  You can set a hot key to this

        2.  Press F3

        3.  Find Help then Pres the + to expand menu

        4.  Find &View log File

        5.  Right Click and Change Keyboard Shortcut

    C.  This instrumental in ensuring your product is error free.

    D.  You will need to view the log first then clear it.

3.  Embedded Geometry Check - In File

    A.  This checks for embedded geometry and embedded settings/UV

    B.  In content library select the file or files in the folder you
        > wish to check

    C.  Activate the script

    D.  It will generate a box giving results

    E.  If there is nothing it's good to go

    F.  If there are issues, then

        1.  Simulation settings, and smoothing modifier will always show
            > up and that is as expected

        2.  There should not be Simulation settings on materials unless
            > it is meant to change how the cloth behaves.

        3.  Should not have embedded geometry or UV's

4.  Morph Lister

    A.  This simply lists the morphs for the selected item

        1.  Select item in Scene tab

        2.  Execute Script

        3.  Box will pop up with morphs for that item listed in there
            > you can copy this list to clipboard if needed

5.  Check JCM Scripts

    A.  This is three scripts that work together.

    B.  Best used on clothing and Hair to check whether the JCM behaved
        > correctly or not.

    C.  The min and max scripts can be used in checking JCM on
        > characters see Checking a Character on how it's done.

    D.  Select the piece of clothing (it should be parented).

    E.  Use Script JCM Min Limits ALL.

    F.  Use Script JCM Currently Used.

    G.  Use Script JCM Max Limits ALL.

    H.  Use Script JCM Currently Used again it will pop up a box

    I.  In the box brows to to the data/ Morphs folder for the item you
        > are checking.

    J.  Hit accept.

    K.  This will pop up a box that shows you what morphs were not used.

    L.  You can ignore any of the morphs that are not JCM.

    M.  If any JCM are listed there, then you will need to manually
        > check the referenced bones/rotations to see if the listed JCM
        > work or do not

6.  Random Color All Items

    A.  Select the item/items you wish to change colors in the scene.

    B.  Execute script.

    C.  Will assign random colors to all material zones for selected
        > objects

    D.  Used with Clothing to make sure all material zones are good
        without stray colors from other material zones.

    E.  Use with hair to see the different material zones in hair

7.  Scene Geometry Source Lister

    A.  Select the item/items you wish to check in the scene.

    B.  Execute script.

    C.  This will show where the geometry is being pulled from.

    D.  It will note items in red that are pulling geometry from the
        .duf or other areas .

    E.  The data path if correct will be data/then what ever.

    F.  If the item is pulling geometry from elsewhere it will be #/then
        > whatever.

8.  Shader-UV Checks

    A.  This will apply

    B.  a colored UV grid

    C.  Select item in the scene

    D.  Go to surfaces tab

    E.  Select the surfaces you want to apply the UV grid to

    F.  Apply the preset.

    G.  This will let you check to make sure you have no reverse
        mapping, stretched uv or flipped normal/faces or unmapped areas.

9.  Strip Textures

    A.  This will strip all textures from selected surfaces

    B.  Good for looking at mesh to evaluate any issues

    C.  Use when checking characters for need of JCM

    D.  Use on clothing to strip off textures before applying random
        colors or uv grid+
