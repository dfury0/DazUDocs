# 02 | Tight Top
Workflow by [Mada](https://www.daz3d.com/mada)
![type:video](https://www.youtube.com/embed/Z22WaVS68NU)

Length : 7:19

## Weightmapping : Tight top created with a donor item to speed up rigging and morphs

- Load your donor item (should be as close in design as possible for best results)
- Import your clothing obj, and use the Transfer Utility with Presets script by Josh Darling
  *(available for download on the scripts page)*
- Select the donor item as source and your obj as the Target, and under Choose Transfer Preset select Replace Source with Target
- Clean up and delete morphs that you don’t want in your new top
- Open up Scene Identification and change the Node Name and label to your obj name
  *(otherwise it will save using the source item name)*
- Save your item
  - *File | Save As | Support Asset | Figure/Prop Assets*
- Delete and reload the top, click on Genesis and turn Base Joint Correctives off
  *(this makes it easier to weightmap without JCMs interfering with the shape)*
- Turn on your weightmap tool and use the smoothing brush to smooth out problem areas you find by posing genesis, starting from the neck and working down to pelvis



![type:video](https://www.youtube.com/embed/bglmHi3sWGM)

Length : 15:52

## JCMs

- Turn on Base Joint Correctives on Genesis
- Pose Genesis and export JCM’s that need fixing with Resolution level set to base. For smoothing set the collision item to None. *(that prevents double sided mesh like the straps pushing through itself when it gets pushed out by Genesis. I would rather fix it in a modeler for better results)*
- Use the exact same name for the JCM as the one being used on Genesis, that will then overwrite the existing JCM when you import it back into DS
- Fix your morph in a modeler and import with Morph Loader Pro
  - Reverse Deformations : Yes
  - Overwrite Existing : Deltas only



![type:video](https://www.youtube.com/embed/HLt0jpxQA20)

Length : 3:24

## Morphs

- Body morphs can be found on the Shaping tab. Only use morphs included under Full Body, you just want the body dial with no scaling or translations – never the full control dial (the dials included under People)
- Apply the morph, export with Resolution level set to base. If I use smoothing I set the collision item to None
- Fix your morph in a modeler and import with Morph Loader Pro
  - Reverse Deformations : Yes
  - Overwrite Existing : Deltas only