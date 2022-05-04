# 04 | Long Pants
Workflow by [Mada](https://www.daz3d.com/mada)
![type:video](https://www.youtube.com/embed/_p_GyCZurys)

Length : 5:36

## Using a donor item for the pants and cleaning up

I’m using the Marvelous Bodysuit as a donor item for pants and I had a lot of cleaning up to do, I only realised near the end of rigging that it was using Generic smoothing instead of base shape smoothing which I prefer. It still works well after switching to Base Shape Smoothing but it pays to check your donor item for suitability before you use it.

- Load the bodysuit and import your obj and use the Transfer Utility with Presets script by Josh Darling
  *(available for download on the scripts page)*
- Select the donor item as source and your obj as the Target, and under Choose Transfer Preset select Replace Source with Target
- Clean up and delete morphs that you don’t want in your pants
- Open up Scene Identification and change the Node Name and label to your obj name
- Save your item : File | Save As | Support Asset | Figure/Prop Assets
- Since there’s a lot of cleaning up to do I’m going to save and delete the pants and go to the data folder and find the folder for the pants. That way I can delete the morphs all in one go
- Never delete morphs with the clothing item open and loaded on Genesis, it causes all kinds of issues including 1kb morphs
- You should also never delete any morph folders when the clothing item is loaded and then try to save it. When Daz Studio loads an item it doesn’t load the morph deltas, just the property info and any formulas used. The morph deltas only load when its dialed – so if you load an item, delete the morphs folder and then try saving the item it will write empty morphs because no deltas exist in memory



![type:video](https://www.youtube.com/embed/RzMiHMIQ66A)

Length : 3:30

## Weightmapping

- Load the pants, click on Genesis and turn Base Joint Correctives off
  *(this makes it easier to weightmap without JCMs interfering with the shape)*
- Turn on your weightmap tool and use the smoothing brush to smooth out problem areas you find by posing genesis
- I start at the top and work my way down, other riggers prefer to start at the toes and work their way up – both ways work fine



![type:video](https://www.youtube.com/embed/H3R5Pv9vogs)

Length : 19:58

## JCMs

For JCMs and morphs on pants you need to set the collision item to None if you’re going to use smoothing. In the case of pants the hands for Genesis intersects with the mesh and causes distortions if you collide against it.

- Turn on the Base Joint Correctives on Genesis
- Fix JCMs in your modeler, export with base resolution and the exact same JCM name as Genesis
- Import into Daz Studio with reverse deformation on and deltas only and it will overwrite the existing JCMs
- I add 2 custom morphs for the thighs using the multi dimensional property morph script
  - one for when both thighs are bend out to the side
    - *pJCMThighSide_85_LR*
  - one for when thighs are bend forward to -90
    - *pJCMThighFwd_90_LR*

## Morphs

- Body morphs can be found on the Shaping tab. Only use morphs included under Full Body, you just want the body dial with no scaling or translations – never the full control dial (the dials included under People)
- Apply the morph, export with Resolution level set to base. If I use smoothing I set the collision item to None
- Fix your morph in a modeler and import with Morph Loader Pro
  - Reverse Deformations : Yes
  - Overwrite Existing : Deltas only