> **dForce Hair Notes**

1.  In Daz Studio:

    a.  Load the hair onto the figure it is intended for.

        i.  It should load parented to the base figure and show as a
            figure in the scene pane, not as a strand-based hair node
            (squiggly lines)

        ii. In most cases, PA\'s should not be distributing the strand
            based hair node.

    b.  You may see either all the hair, or only the guide hairs in the
        viewport.

        i.  PA\'s may or may not have \"Generate PS Hairs\" or \"Preview
            PR Hairs\" on or off.

        ii. As long as some hair is in the viewport, and it renders
            fine, it\'s ok.

        iii. If you don\'t see any hair, make sure you do not have the
             geometry editor or the node weight brush selected - the
             hair will not display with those tools.

    c.  In the Simulation Settings pane, simulate the hair with in
        default pose.

        i.  While simulating, watch for any hairs that fly off on their
            own (explode).

        ii. After running the simulations, check the log for errors.

    d.  Pose the relevant areas (the head ect for a head of hair) and
        simulate again.

    e.  Apply any included morphs and simulate the hair.

    f.  Apply any material presets one at a time.

        i.  Material Presets that only change the hair material, should
            not include the simulation settings.

        ii. Material Presets that only change the simulation settings,
            should not include the hair material.

        iii. Material Presets that change both, can include both. And
             products containing such a preset, is an exception to the
             above rule.

    g.  If the hair is not simulating properly check the settings in
        surfaces:

        i.  The default settings changed at one point.

        ii. Velocity Shock Propagation should be 0

        iii. Dampening should be 0.080

1
