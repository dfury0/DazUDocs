# Checking a Pose in Daz Studio
If a pose requires multiple figures, make sure that it is clear *which figure* each pose is for.

If poses are included for multiple characters, make sure either the file name or thumbnail indicates which character the pose is for. *The thumbnail should be for that character.*

## Poses should not change scale, translation, or expression when applied

Generally, a pose should not alter the figure's location, scale, or expressions. But there are exceptions; see below.

### Set up the testing scene

*  Add a ground plane

  * Create-\>New Primitive-\>Plane
  
  * Make the plane large enough so the figure is on it
*  Load the base figure(s) that the poses are made for into the Scene.
*  Select the figure in the Scene pane.

### Apply Scaling

* Select the Posing Tab and apply the Scale modifier

### Apply Translation

* Move a figure in the x and z axis so it's not centered in the scene

### Apply an expression to the figure

Pick any expression to apply. A significant expression will make it easier to spot if anything changes.  

### Apply all poses

* In the content library, select **all the poses** and right+click\>Merge to Scene

* As the poses apply, the figure should **stay in place**, and the **expression should not change**.

## Apply each pose and check:

If prompted to **turn limits off**, do so.

The pose **matches** the thumbnail.

Make sure there are **no odd twists and turns**.

### No Poke through

Make sure that none of the figure's limbs poke through the body while testing the listed figure.

* *Exception: If you have a **larger** body morph.*

* If there is poke-through and limits were **turned off**, check with the **limits on** to see if that is causing the issue.

    1. It will be necessary to load a new figure and re-apply the pose, respecting limits at the prompt

    2. Poses should work with limits *on* or *off*.

    3. If limits need to stay on, a note that says so **must** be added to the ReadMe.

### Poses with Props

If there is a prop, ensure the figure interacts with the prop correctly.

1.  Minimal Poke through

2.  If a hand is on part of the prop, ensure it rests **on** it, not away from it.

### No Floor Penetration 

Make sure that the body doesn't poke through the floor unless necessary.
1.  *Exception: A figure in water (swimming) is okay.*

2.  The easiest way to check this is to create a primitive plane and color it to be visible, then apply the pose and see if body parts poke through it.

### Zero Pose resets correctly

It is always suggested to have a **Zero Pose**. Apply a pose before applying the zero pose to ensure it resets the pose.

### Poses with Expressions

Poses can include expressions if it's intentional.

 1.  Poses should not contain the default expressive information. No default blank stare. 

 2.  It should be noted on the Store Page and ReadMe.

### Pose with Translations
Poses can include translations if intentional, especially for populating an environment. These poses *should not* contain the default blank stare.

Check that the poses do not zero the figure or expressions (unless the poses contain expressions)

* "Goto" poses SHOULD move the figure in the scene.

