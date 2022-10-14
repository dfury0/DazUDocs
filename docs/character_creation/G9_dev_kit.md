# The Genesis 9 Developer Kit

The Genesis 9 Developer Kit contains tools for creating characters, morph fixes, and textures. 

## Genesis 9 Dev Load 

The base Genesis 9 character without any followers (mouth, teeth, eyelashes, etc.) or morphs active. The Dev Load character should be used to start any custom character. Exporting the Genesis 9 base shape as an OBJ instead of the Dev Load will embed the mouth, eyes, eyelashes, and eye moisture, breaking vertex compatibility for morphs. The Dev Load should be your go-to for all character work. 

If you frequently work with characters, you want to add this preset as a custom action. 

* Right Click on the preset > Create Custom Action... 

## Genesis 9 Hand Prop Sample

Genesis 9 includes anchor bones in the left and right palms for parenting gripped objects. The anchor bones do not affect the character geometry. This hand prop sample shows how anchor bones should be set up. 

## Genesis 9 Head Split DFormer

The head split DFormer is used to separate head and body morphs. Characters all should separate at the exact location in the neck so heads and bodies can mix and match. The Head split DFormer is used with Morph Loader Pro. 

- Load Head Split DFormer onto the Dev Load Character
- Select Character OBJ
- Morph Loader Pro > Attenuate By (right click None) > Weight Maps > D-Former1 > Influence Weights
  - Set Attenuate By > Strength to 1 for body morph
  - Set Attenuate By > Strength to -1 for head morph

Video tutorial using Genesis 8, but the process is similar: 
![type:video](https://www.youtube.com/watch?v=L4N2qC9uHac)

## Landmark Material Presets

Landmark materials change the UV preset to **Base Single UDIM** and load a custom texture that shows anatomical landmarks for Genesis 9 Character sculpting and texturing. Most anatomical reference points are the same between masculine and feminine shapes, except for the nipple and eyebrow placement. 

You must load one of these Materials before exporting it to ZBrush. The Base Single UDIM works much better with most sculpting applications. If the landmark textures look distorted, check if the UV Set has changed. 

### Genesis 9 Landmarks Feminine

Used for placing nipples and eyebrows for Feminine characters.

### Genesis 9 Landmarks Masculine

Used for placing nipples and eyebrows for Masculine characters.

## Genesis 9 UV Prep Pose

A utility Character pose to simplify texturing and painting UV seams. This pose opens the jaw, closes the eyelids, and spreads the fingers and toes.  Usually, the character is not brought back into DAZ Studio with this pose, just the textures created on it. The pose can also be used to check for texture seams. 

Our Quality Assurance team usually finds seams on ancillary maps like roughness, not on the base albedo map. 

## UVs

### Genesis 9 UVs Default

The default Genesis 9 UVs. It should be the default for all characters. Other UV layouts are utility UVs to help assemble textures on this UV Map set. 

### Genesis 9 Force UVs To Unique UDIMS

Separates the Genesis 9 UVs onto different UDIM tiles. The default UVs overlap in the 0-1 UV space but use different material groups, so they do not mix. Unique UDIMS is for artists that want to work with UDIMs for sculpting and texturing. 

### Base Single UDIM

The Landmark Materials will load this UDIM. Helpful in sculpting in ZBrush and baking maps in xNormal. To manually enable this UV set:

* Surfaces Tab > Genesis 9 > UV Set > Genital Map Bake

### Genital Map Bake UVs

Used for fixing seams on genitals for texture artists. Includes the border polygons connecting the torso UV to the genital UVs. 

There is no preset for the genital bake UVs, so you need to activate them manually. 

* Surfaces Tab > Genesis 9 > UV Set > Genital Map Bake

