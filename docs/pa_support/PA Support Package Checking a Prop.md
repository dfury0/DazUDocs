> [Checking a Prop]{.underline}

1.  In Daz Studio

    a.  Check the Scene ID to ensure that the geometry is coming from
        the data folder and not the duf.

    b.  Run List Geometry Source Script in QA scripts, if errors(Red):

        i.  Select Item in the Scene

        ii. Edit-\>Object-\>Scene Identification

        iii. If it is pulling from the duf it will have #what ever after
             it

        iv. If it is pulling from the data folder it will show
            /data/then whatever

    c.  Run Embedded Check in Geometry File Script.

    d.  Clear the Daz Studio log file.

    e.  Load prop into the Scene.

        i.  Make sure that no error messages appear in the log file.

        ii. Check the prop's center of rotation (the Universal Tool will
            show the axis)

            1.  For hand held props, the center should be where the item
                would be gripped

            2.  For other props, the center should be a logical point to
                rotate on.

        iii. If the prop goes to a figure:

```{=html}
<!-- -->
```
a.  Load the figure first and then load the prop into the scene.

b.  Make sure there is minimal through where the figure's body connects
    > with the prop.

c.  Make sure that the prop is not "hovering" away from the character.

    i.  ALL props should load at 0,0 unless they are loaded within a
        Scene Preset. Test all materials.

```{=html}
<!-- -->
```
a.  Make sure that the materials load correctly

    i.  No Missing file errors.

    ii. Material in thumbnail should match material that is applied.

    iii. Make sure you thoroughly examine every inch of the prop.

         i.  Any moveable parts (doors, windows, etc.)

             1.  Make sure that limits are set correctly.

                 a.  When moving dial up or down all of the way, the
                     > object should not become distorted.

                 b.  Moveable parts should load in Default Position.

         ii. Grouped Props:

             1.  Separate props that make up something like a vehicle or
                 a Structure should Be under a Group to allow movement
                 of all the props as one.

         iii. Weapons:

              1.  Any hand-held prop should be saved out as a "wearable
                  preset" that loads with the grip.

              2.  There needs to be a separate H-pose preset that
                  includes the 'grip' poses of the hands ONLY when the
                  weapon is applied.

         iv. Check that each item is selectable in the viewport.

             1.  You should be able to click/right+click on any item and
                 have the option to select that item.

         v.  Render

             1.  Make sure that the prop renders correctly.

                 a.  Be sure to test in the correct render engine(s).

                 b.  Render each material.

                 c.  DO NOT use the Iray Drawstyle to test the render.
                     > They do need to be rendered out.

1
