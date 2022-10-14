# What is ‘Rigging’ for Daz Studio Characters?

The term rigging is generic and is used too broadly to describe various different aspects of animatability.

#### FK Rigging 

The core mechanical stuff that bends a limb. 

Weights, bones, things which are set by the figure base at its creation, and are unchangeable for the lifetime of that figure base. No character edits the weight mapping or bone count/layout of the Genesis base. If they did, compatibility would be broken with add-on items.

#### IK Rigging

The constraints and links allow automatic animation to happen. E.g. linking a character's hands to the handles or pedals of a bike, and letting the motions of the bike drive the limbs of the person.

#### FK Correction Rigging

these are sculpting fixes created to address aesthetically poor character limb posing FK performance. This is primarily a sculpting discipline, with corrective blendshapes made against the posed result of the character + the genesis FK rigging. This is what we are referring to when we say “character rigging”.