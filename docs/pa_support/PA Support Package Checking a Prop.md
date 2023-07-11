# Checking a Prop

## Check the **Scene ID**. 

Load the prop into the scene and ensure the geometry comes from the data folder, not the DUF.

Run **List Geometry Source Script** in **QA scripts**. If errors (Red):

* Select the Item in the Scene. *Edit-\>Object-\>Scene Identification*
    * If it is pulling from the **DUF**  it will have \***#whatever*** after it
    * If it is pulling from the **data folder**, it will show **/data/whatever**

Run Embedded **Check in Geometry File Script**, then Clear the Daz Studio log file.

## Check the Geometry and Center of Rotation

Load the prop into a New Scene and ensure no error messages appear in the **log file**.

Check the prop's center of rotation (the Universal Tool will show the axis)

* For handheld props, the center should be where the item would be gripped
* The center should be a logical point for other props to rotate.

## Figure Props

1.  Load the figure first and then load the prop into the scene.
2.  Ensure there is minimal poke through where the figure's body connects with the prop.
3.  Ensure the prop is not *"hovering*" away from the character.

ALL props should load at 0,0 unless loaded within a Scene Preset. 

## Test all materials.

Make sure that the materials load correctly with **no Missing file errors**. The material thumbnail should match the applied material.

## Thoroughly examine every inch of the prop.

### Moveable parts (doors, windows, etc.)

* Make sure that limits are set correctly.
    * The object should not become distorted when moving the dial up or down.
    * Moveable parts should load in Default Position.

### Grouped Props
Separate props that make up something like a vehicle or a structure should Be under a **Group** to allow the movement of all the props as one.

### Weapons
* Any hand-held prop should be saved out as a "wearable preset" that loads with the grip.
* There needs to be a separate H-pose preset that includes the 'grip' poses of the hands ONLY when the weapon is applied.

### Check that each item is selectable in the viewport.

You should be able to click/right+click on any item and have the option to select that item.

##  Render

Make sure that the prop renders correctly.
 -  Be sure to test in the correct render engine(s).
 -  Render each material.
 -  DO NOT use the **Iray Drawstyle** to test the render. They do need to be rendered out.
