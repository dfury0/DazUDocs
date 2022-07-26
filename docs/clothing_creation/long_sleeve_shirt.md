# 05 | Long Sleeve Shirt
Workflow by [Mada](https://www.daz3d.com/mada)
![type:video](https://www.youtube.com/embed/R2tB1nChdhw)
Length : 3:59

## Weightmapping: A loose shirt created with a donor item to speed up rigging and morphs

- Load your donor item (should be as close in design as possible for best results)
- Import your clothing obj, and use the Transfer Utility with Presets script by Josh Darling
  *(available for download on the [scripts page](mada_basics.md))*
- Select the donor item as source and your obj as the Target, and under Choose Transfer Preset select Replace Source with Target
- Clean up and delete morphs that you don’t want in the shirt
- Open up Scene Identification and change the Node Name and label to your obj name
  *(otherwise it will save using the source item name)*
- Save your item : File | Save As | Support Asset | Figure/Prop Assets
- Delete and reload the shirt, click on Genesis and turn Base Joint Correctives off *(this makes it easier to weightmap without JCMs interfering with the shape)*
- Turn on your weightmap tool and use the smoothing brush to smooth out problem areas you find by posing genesis, starting from the neck and working down to pelvis, then collars down to hands

![type:video](https://www.youtube.com/embed/SvCxVtlgTPI)
Length : 17:18

## JCMs : Neck area
- For shirts with a collar you need to spend a bit more time on getting it to look right around the neck with JCMs
- Turn on Base Joint Correctives on Genesis
- Use the exact same name for the JCM as the one being used on Genesis, that will then overwrite the existing JCM when you import it back into DS
- Fix your morph in a modeler and import with Morph Loader Pro
  - Reverse Deformations : Yes
  - Overwrite Existing : Deltas only
- There are 2 JCMs in the neck that you have to dial up at the same time. For *pJCMNeckFwd_35* bend both Neck Lower and Neck Upper forward. That will set the dial to 100% – export and fix in modeler, import back into Daz Studio
- For *pJCMNeckBack_27* bend both Neck Lower and Neck Upper back – that will set the dial to 99% which is usually close enough so I don’t bother to unlock the bend further – export and fix in modeler, import back into Daz Studio

![type:video](https://www.youtube.com/embed/4EjuGlO7PSY)
Length : 9:47

## Weightmapping and JCMs : Shoulders
Get the weightmapping in the shoulders and collars as smooth as you can with the least amount of texture distortion. To keep it simple I’m only showing the left side but the right side is exactly the same with the corresponding JCM names

- Collars : bend down is usually fine but bend up needs to be fixed in a modeler with attention to under the arms and around the neck for collars
  - *pJCMCollarUp_55_L*
  - *pJCMCollarUp_55_R*
- Shoulders : bend down and up needs to be fixed
  - *pJCMShldrUp_90_L*
  - *pJCMShldrUp_90_R*
  - *pJCMShldrDown_40_L* – turn smoothing off or collide against nothing if you find the hand goes into the cloth at the hips
  - *pJCMShldrDown_40_R*
- Shoulders : front and back. I will sometimes add a custom morph for shoulders back if there’s poke through that I can’t fix with weightmapping. Forward <u>always</u> need to be fixed
  - *pJCMShldrFwd_110_L*
  - *pJCMShldrFwd_110_R*
- Multidimensional Property Morphs are already in Genesis for Shoulders front + bend down and up. You can use the exact same JCM name and then you don’t have to do anything except import into the clothing, it will replace the morph created by Genesis
  - *pJCMShldrFront_n110_Bend_n40_L*
  - *pJCMShldrFront_n110_Bend_p90_L*
