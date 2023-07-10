> [Checking an Outfit]{.underline}

1.  Check the data folder for supported shapes for each piece of the
    outfit.

    a.  If the Outfit includes "fit" "squish" morphs for Genesis 8, then
        those morphs should go in an "Actor/Clothing/" group.

    b.  Smoothing is fine as long as the piece loads with smoothing on
        and works.

2.  In Daz Studio

    a.  Check that there is a preset to load the whole outfit. This is
        required for all products.

    b.  Clear the log file.

    c.  Now, load a "clean" character that the product is designed for.
        This is a textureless, morphless version of Genesis 3, 8 etc.

    d.  Load each item of clothing separately onto the character and
        check the following, then load the whole outfit and relevant
        combinations and check them working together.

        i.  Make sure that there are no missing files when loading.

        ii. There should be NO poke-through in default pose.

        iii. Make sure NO pieces are floating (such as straps above the
             shoulders.)

        iv. Make sure that there are NO stray polys.

        v.  Make sure that the clothing pieces are loading Parented and
            Fitted To the figure.

    e.  Footwear that requires a specific foot pose should load with
        that pose, as well as include an H.Pose to apply it.

        i.  Platform Shoes with thick sole do NOT need to follow
            Metatarsal and Toe Bones

        ii. Thinner Flat Soled Shoes that can realistically bend in real
            life MUST follow them and the actual feet bones.

        iii. Heels/boots are tested by bending the foot bone only.
             Up/down, side/side. Not the toes etc\...

    f.  If clothing includes simulation settings in the parameter pane,
        or other dForce parts, then it MUST be tested and work with
        dForce.

    g.  Apply Poses/Morphs to base figure.

        i.  Poses

            1.  Apply poses provided in the QA Pose Package and Pose
                controls for the Arms, Legs, and Feet.

                a.  Make sure the outfit moves with the figure.

                b.  There are some extreme and some normal poses.

                c.  Make sure that there is no poke-through

                d.  Make sure that the mesh of the clothing is not
                    > distorted. There should be no "mesh crumpling"

                e.  Check to make sure that any JCM's are kicking in.

                f.  When posing, especially with arms up, make sure low
                    > cut tops, low cut dress as well as low cut bras
                    > cover the nipples and areola. If the clothing
                    > piece does not cover, morphs dials are an
                    > adjustment to the mesh will be needed.

        ii. Apply Morphs to the figure.

            1.  Check the data folder for supported shapes for each
                piece of the outfit.

                a.  Daz Originals should include the required list of
                    > figure morphs and any character it is specifically
                    > for.

                b.  If a morph is included for any piece, then every
                    > piece should work with that morph (does not need
                    > to include the morph for every piece, as long as
                    > auto-projection works fine.)

            2.  Apply Character Body and if applicable Head morphs.

                a.  There should be no poke-through in default pose.

                b.  Apply some testing poses

                    i.  If there is any poke-through, make sure that the
                        > clothing adjustment morphs can fix this.

        iii. Check Clothing morph dials.

             1.  Select each item of clothing in the scene pane.

             2.  Go to the Parameters pane and make sure each morph dial
                 works.

             3.  Check Spelling on all included dials.

             4.  Also check the adjustment morphs to make sure that they
                 work correctly.

    h.  Check Material zones on each piece

    i.  Check material zone naming and that material zones are set up
        realistically and logically.

        i.  Run Random Color all Items from the QA Scripts.

            1.  Check for stray pieces of mesh or see if something was
                mapped to the incorrect MAT zone.

```{=html}
<!-- -->
```
i.  Check that each piece is selectable in the viewport.

    i.  You should be able to click/right+click on any part of the piece
        and have the option to select that part.

    ```{=html}
    <!-- -->
    ```
    a.  Check the UVs

        i.  Change to the UV View in the View Selection Menu of the
            Viewport, Select one surface at a time.

            1.  Look for any of the mapping that falls off on one side
                and continues on the opposite side. Even though the
                colored squares look right and your template looks right
                the View selection will help notice any oddities in
                mapping.

            2.  Look for any smashed/ separate, odd mesh.

        ii. Add a UV checker jpg to the surfaces and check the
            following:

            1.  Make sure there is no stretching - squares and numbers
                should be consistent size.

            2.  Checked for flipped Normals - all numbers should read
                the same direction.

            3.  Also use different tiling sizes to make sure that
                textures will melt together correctly.

            4.  Make sure to do this after any mesh changes as they UV's
                can get messed up on resaving.

    b.  Check the materials.

        i.  Make sure that all of the materials apply to the clothing
            correctly.

            1.  Render the materials in the correct render engine(s) to
                make sure that they render correctly.

        ii. Check the names of the materials.

            1.  **[Make sure they match the name of the
                product]{.underline}**.

        iii. Make sure the Thumbnail images match the material that is
             being applied

        iv. When testing textures, make sure that the grain of the
            material do not look like seams.

        v.  Also make sure any textures such as dirt etc. that are
            painted in, flow with the material after simulation or
            posing.

        vi. During material check look in the materials to see if there
            is embedded simulation settings.

            1.  Use Josh's embedded geometry checker it will show it.
