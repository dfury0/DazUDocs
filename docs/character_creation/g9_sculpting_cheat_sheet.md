# Genesis 9 Character Sculpting Process

## Load Genesis 9 from the Developers Kit

* People > Genesis 9 > Developer Kit > Genesis 9 Dev Load

### Export eye and mouth geometry followers to help rough in proportions. 

* People > Genesis 9 > Anatomy > Daz Originals > Base Anatomy > Genesis 9 Eyes
* People > Genesis 9 > Anatomy > Daz Originals > Base Anatomy > Genesis 9 Mouth

## Rough-in Character in DAZ Studio

Keep mesh symmetrical. 

* Can start from **Base Feminine** or **Base Masculine** Shapes
* Genesis 9 Head Shapes
* Genesis 9 Body Shapes

The following morphs should NOT be included in the character shape. You must reverse them from the character shape on reimport if you activate them now.

* **Asymmetry**
* **Navel** 
* **Nipple** 
* **Mouth Realism**
* **Teeth**
* **Eyelash**
* **Eye** morphs that affect eyeball geometry (Pupils and Iris )

* **Proportion**

Save a scene file of the character.

## Export OBJs for ZBrush (or the application of your choice)

* Change UVs to Single UDIM UV before export
  * Surface Tab > Editor > UV Set > Base Single UDIM

* Export mesh to ZBrush using one of two methods:
  * Use **GoZ** to send Genesis 9 Dev load to ZBrush. It will automatically put eyes and teeth as separate subtools.
  * Export OBJs manually using default Daz OBJ export settings with resolution set to Base.

### Sculpt in ZBrush with Layers

Keep character symmetrical for everything but skin details and fine wrinkles. Build a new layer for any other asymmetry (crooked nose). 

Do not sculpt height, limb, neck, or torso proportion changes.

Do not sculpt (for now)

* Nipples
* Navel
* Eyes
* Teeth

## Use Landmark Textures for Sculpting Reference

Can be found in **DAZ 3D Library\Runtime\Textures\DAZ\Characters\Genesis9\Base\DevKit**

* **Genesis9_Detail_Atlas_F.jpg** (Female Landmarks)
* **Genesis9_Detail_Atlas_M.jpg** (Male Landmarks)

### Mesh Areas Sensitive to Sculpting

* Eyelids
* Lips
* Fingernails
* Toenails
* Neck area (do not slide mesh around)

## Export OBJs (Question: GoZ back?)

Export base resolution OBJ with Cage active

Export high-resolution OBJ of Genesis 9 sculpt

## Load character OBJs onto Genesis 9 in DAZ Studio

 Use **Morph Loader Pro HD** plugin

Check for mesh issues

* thin eyelids
* lip pinches (open jaw to see)
* Base Resolution Cage should wrap around HD character.
* Adjust rigging to shape and test some poses

#### Decide on the character's presentation name

The name will be used for future steps. It can change later, but it is extra work to rename all the files. 

Create a folder for all character files. Add this folder as a new base directory.

### Split Head and Body base resolution and HD Morphs

Base resolution morph should wrap around HD morph

Use the **Genesis 9 Headsplit DFormer** to split head and body morphs using Morph Loader Pro. 

* Genesis 9 > Developer Kit > **Genesis 9 HeadSplit DFormer**
* Morph Loader Pro > Attenuate By (right click) > Weight Maps > D-Former1 > Influence Weights
* Set Attenuate By Strength to 1 for Body morphs, -1 for Head morphs

### Add proportional morphs to set character height

Create a character control dial

Add proportional morphs and ERC them to the character dial

### Additional sculpting

Sculpt any other proportion morph fixes

Sculpt Custom nipple, navel, and teeth morph if needed

ERC additional morphs to character dial

## Texturing

You can assemble a character using only the existing **Genesis 9 MAT** presets. You may also customize these textures. 

### Skin Textures

Start from provided Genesis 9 MAT textures (01-04 for Feminine and Masculine)

* Genesis 9 > Base Materials > Genesis 9 Base Feminine MAT 01
* Genesis 9 > Base Materials > Genesis 9 Base Masculine MAT 01 

There must always be a skin texture without eyebrows. Texture-painted eyebrows are not required. 

#### Use the micro detail normal maps.

*  Genesis 9 > Base Materials > Genesis 9 Base Feminine Skin Details MAT
*  Genesis 9 > Base Materials > Genesis 9 Base Masculine Skin Details MAT

### Genitals

Fix genital seams on the torso map. Tier 1 characters must support Male and Female genitals. 

#### Bake torso textures to the genitals with Genital Map Bake UVs.  

* Surfaces Tab > Genesis 9 > UV Set > Genital Map Bake

### Eye Material

There are 16 Eye Mats available to choose from. 

* Genesis 9 > Materials > Base Materials > Eyes > Genesis 9 Eyes MAT 01 - 16

Only create a new eye MAT if needed for the character. You may modify the Eye MATs for redistribution (Question: or can they?)

### Mouth

Use the default mouth texture unless the character requires something different. 

### Eyelashes

Do not texture eyelash colors as individual hairs.

Eyelash colors can be modified using shader tints or textures with the following:

* Solid texture color card fills.
* A root-to-tip gradient that fills the eyelash card.

 This allows **all** Eyelash library alphas to be used with custom colors.

## Save a character preset

Save custom morphs 

* Save As > Support Asset > Morph Asset

Save character preset

Run Validator on character content library

Package the character folder as a Zip and submit it to PASS