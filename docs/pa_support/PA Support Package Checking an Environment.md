# Checking an Environment

## Load the Environment

**Clear** the Daz Studio <u>log file</u> and **load** the environment into the scene.

* Make sure that **no error** messages appear in the log file.
* Ensure there is a **preset** to load the complete environment (with props).
* Props with scene presets should load in the correct positions (not at 0,0).

### HDRI

If it is an HDRI, ensure the environment appears when rendered. 

* If there is a background under environment, it must be set to **None** so that the HDRI shows up in the render.

### Check each item is selectable in the viewport.

 You should be able to **click/right+click** on *any* item and have the option to select that item.

* Check that items which should be moveable are. In most cases, this includes **doors opening**.

### Load a figure into the scene.

Make sure that the environment is scaled in reference to the figure. The scaling should be proportioned correctly.

## Check unique features of the environment. If there are:

### Cameras
Make sure that each camera moves to the correct position in the scene. 

* Camera should match the environment thumbnail.
* If Camera is Pointed at a wall check to see if the wall is Hide-able
### Materials
Make sure they **apply** and **render** correctly.
### Render Settings
Make sure they **apply** correctly.
### Lights
Make sure that they **load** and **render** correctly. Render the environment. Make sure that the environment renders correct in the correct render engine(s).