# Character Sculpting 

## Setup

### Exporting the model for Zbrush

* **DAZ Studio: Do export at Base resolution with the Single UDIM UV set.** It is important to work in Zbrush with the base resolution model, and Zbrush works best with the Single UDIM UV set.

### Character Sub-figures (Eyes/Mouth)

* **DAZ Studio: Export Eyes and Mouth models separately.** Eye and Mouth geometry should be exported individually from the G9 base model, at Base resolution. 
* **DAZ Studio: Eye and Mouth geometry are sub-tools.** Any sub-figure geometry should be loaded into Zbrush as further subtools, and generally only moved or scaled globally.

### Using Morphs As Starting Point

* **DAZ Studio: Do use the Base Feminine and Base Masculine as starting shapes.** They are example characters and their shapes are free to use as exported starting points for character sculpting. They should not be extracted when loading your finished character blendshape. Your final character should be a standalone shape on the G9 base figure.
  * Get masculine base files [here](https://www.dropbox.com/s/zyr8memrtxvletb/G9_masc_plus_anatomy.zip?dl=0)
  * Get feminine base files [here](https://www.dropbox.com/s/vyoova8miratg90/G9_fem_plus_anatomy.zip?dl=0)
* **DAZ Studio: Do use the morphs in the following packages to create starting shapes.** Merchant resource blendshapes can be a good way to jump-start a shape before further character sculpting in an external program. The following packages are allowed for use this way.
  * G9 Starter Essentials.
  * Head or Body morph packages.
  * Note: Blue morphs on the figure are merchant resources.

## Character Sculpting Process

### Feature Landmarks

* **Zbrush: Do use the landmarks texture map.** G9 comes with two landmark texture maps (masculine and feminine) based on the Single UDIM UV set. This map gives a visual indication of where landmarks such as lip borders, brows, elbows, knees, etc, are located on the topology.
  * Sculpting landmarks consistently helps with shape and texture continuity across diverse characters. 
  * Landmarks such as the brow will help you determine where the card-based eyebrows will end up on the final character. Move the mesh accordingly.

### Head Proportions

* **Zbrush: Don’t change the size of the eyes unless…** Standard human eyes do not deviate much in size or shape, and G9 eyes are measured to be within the average.
  * This does not apply to stylized characters, e.g anime, cartoon, other.
  * This does not preclude changing position.

### Body Proportions

* **Zbrush: Don’t change proportions via sculpting unless…** Most characters should be sculpted in a proportion that maintains the limb lengths and heights of the base figure.
  * This ensures a universal height for all characters. Some characters would by their nature not work with this rule, but they are likely to be outliers.
  * This does not preclude the changing of volume, e.g, thinner or heavier characters.

* **DAZ Studio: Do use the Proportion dials at the end of character setup.** Proportion dials should be used at the end of character creation to create a proportion formula preset dial for the character. This decouples height from the character and gives the end user more options.

### Asymmetry

* **Zbrush: Don’t sculpt extreme character asymmetry unless...** Most characters should avoid extreme degrees of asymmetry in their shape as that locks the character into an appearance customers may not appreciate.
  * Asymmetrical fine details are generally fine. These would be small HD folds, lines, etc.
  * Any required character-specific sculpted asymmetry can and should be included as an additive shape meant to work as an optional blendshape. Generally this means it should be done as a separate layer. This would include things such as:
    * Scars, burns, boils, etc
    * Uniquely extreme attributes too specific to be approximated with the base general set.
* **DAZ Studio: Do use the asymmetry blendshape options included in the figure base to create a preset.** Should you require more drastic asymmetrical aesthetics.
  * There are many asymmetry blendshape options included with the G9 base.
  * You can formula these asymmetry options to a secondary character parameter dial. Example: ‘Victoria 9 Asymmetry’, which would host all parameters you chose as an optional control.
* **DAZ Studio: Don’t use the asymmetry blendshapes for non-approved purposes.** Asymmetry morphs should not be used in expressions or other posing functions. These are intended to provide asymmetry to a character shape only.

### Navel and Nipples

* **Zbrush: Don’t sculpt these as part of your character design.** The navel and nipples on G9 are seperate shapes.
* **Zbrush: Do sculpt any custom navel and nipple shapes as a layer.** Sculpting the navel and nipple as a seperate layer in Zbrush allows easy extraction of those shapes at the end up the process. Those elements should be positioned according to the appropriate Landmark texture map.

### Eyes

* **Zbrush: Don’t use brushes to sculpt on the eye topology.** The eye figure is best adjusted as needed globally; translation and scale. Sculpting them in a manner which distorts their overall symmetry will cause issues with their rotation within the socket.

### Sculpting Techniques To Avoid

* **Zbrush: Don’t distort the topology in ways that only locally slide.** An example would be using a Move brush and locally dragging the model. Such distortions will ultimately make their way into clothing via shape projection, distorting things such as straps and buckles.
* **Zbrush: Don’t use brushes that cause topological pinching/compression.** Zbrush brushes such as *Pinch* or *Dam Standard* compress and distort the topology in ways which will ultimately make their way into clothing via shape projection. It is much better to use sharp *Standard* brushes to get similar effects.
* **Zbrush: Do clean up any topological pinching/compression.** If, at the end of the sculpting process, you notice topological compression in areas, a good way to clean that up is to: 
  * Store a Morph Target of your final sculpt shape.
  * Go down to level 1, and then *Subtool Pane>Project>Reproject Higher Subdiv*
  * *Morph Target Pane>Switch* to change back to your original sculpt
  * Using *Morph* brush, you can brush that clean projection only on the areas that need it.

## Character Setup

### Create the Low Resolution Blendshape

* **Zbrush: Do Create a low resolution blendshape.** Characters in DAZ Studio are often split into a low resolution blendshape (SD or cage resolution) and high blendshapes (HD or any higher levels above 1). This is similar to a low poly bake object. There are two potential methods for creating this shape.
  * The ‘Cage’ option in Zbrush. Geometry palette>SDiv set to 1, Cage is next to it. This option moves the cage points into a position they would be if the realtime subdivision state of the model was attempting to approximate the sculpted volume
    * The pros of this method are that it’s easy, and fast.
    * The cons of this method are that it sometimes produces a cage model that is too erratic or ‘crunchy’ to use.
  * Manually sculpting the low-res model to fit around the high-res sculpt (see [this video](https://drive.google.com/file/d/1LFbBnbtPFPA8jfr8TjHfr43cj1AQSL-E/view?usp=sharing) for an example workflow).
    * The method to do this in Zbrush, is to: duplicate sculpt subtool, lower SDiv level to 1, Del Higher, open Dynamic SubDiv, activate Dynamic. This puts the model into dynamic Subdivision Surface sculpting mode, allowing you to sculpt the model to fit around the HD sculpt in the background. Note: try filling the model with a color to create contrast to allow you see the overlap easier.
    * The pro of this method is that it can be as accurate and clean as you make it.
    * The con of this method is that it is slower and manual work.
  * Suggestion is to try Cage first, inspect the model, and if that didn’t produce a good result, move to the manual method.
* Load the Blendshapes
  * DAZ Studio:
* Corrective Blendshapes
  * **DAZ Studio: Do connect character specific correctives so that they are driven by the base correctives.** Avoid connecting correctives directly to the bone rotations when an existing corrective of the same degree already exists.Better to tweak expression recipes instead of correcting for each individual morph in FACS. It is far too complexCustom Morphs For The Character**DAZ Studio: Do group custom morphs the same as the character.**  For example the Victoria 9 character is located in “Actor/People/Feminine”. If a custom nose morph is made to work with her face specifically then it would be grouped under “Actor/Head/Face/Nose/People/Feminine”

## Texturing

### Skin Textures

* **DAZ Studio: Do use the micro detail normal maps with your skin materials.** High quality micro detail normal map textures are included with G9 base package. 
  * They are available to anyone to use in material presets only for standard humanoid characters.
  * These textures are not a merchant resource, and are not free to modify and redistribute.
* **Texturing App: Don’t paint brows into your skin textures unless...** Brows generally shouldn’t be painted into the skin texture maps. If they are, a browless texture option should always be included so the texture set can easily be used with the geometry-based brows.

### Eyes

* **DAZ Studio: Use the Eye Library in your MAT presets.** Characters should by default use the appropriate free eye material preset in their character MATs
* **Texturing App: Don’t make new eye textures unless…** Characters should only come with new eye textures and materials if a truly unique appearance is the goal, and an existing texture in the Character Essentials Library does not already cover that goal.

### Mouth

* **Texturing App: Don’t make new mouth textures unless…** Characters should by default always use the core mouth texture and materials unless the character requires a unique visual effect. 

### Eyelashes

* **Texturing App: Don’t texture eyelash colors as individual hairs.** Eyelash colors can be achieved using shader tints, or textures with:
  * Solid texture color card fills.
  * A root to tip gradients that fills the entire eyelash card.
  * This allows any of the Eyelash library alphas to be used with the color option.

### Nipples

* **Texturing App: Do create two torso textures.** It is better if your texture comes with two sets of torso maps to support both the Feminine and Masculine nipple placements.

### Normal Maps

* **DAZ Studio: Do use the main normal maps channel in the shader for your character specific (medium normals) details**. Fine details such as pores and such are added via the detail normal map.

### MATs (Material Presets)

* **DAZ Studio: Do include all the components in your character “All MAT” files.** Character MAT files should include the following figures:
  * Eyes,Eyelashes, Tear, Mouth, Gens m/f.
  * **DAZ Studio: Don’t include character specific normals in your “Skin” MAT files.** Skin only MATs, or MATs not intended to inject character details onto the figure, should:
    * Include the G9 base figure’s surfaces.
    * Exclude the primary Normal map channel.
    * Include detail Normal map channel.

### Genitals

* **Bake torso textures to the genitals.**  A UV map is provided for the G9 base figure which aligns to the UVs of the genitals. This allows texture baking from G9 Torso textures to a Genital UV map, giving a seam-matched head start for the gential textures.

* Both genitals should be supported in all Tier 1 characters

  ## Posing

* When posing it is necessary to remember that there is often more than one way to reach the same pose. Some combinations will work much better than others. If you see bad distortion with a pose evaluate if you can reach that same pose in a way that causes less problems

  * The thigh is a great example. If you want the thigh rotated out to the side with the toes pointing up that can be accomplished with a combination of Side-Side and Bend but it looks awful at the thigh joint. Side-Side and Twist, however, looks great
    ![img](https://lh3.googleusercontent.com/p44POYqgrG_YCdS4YFQh8GiESMKT00sK-wWjWQvAKFcHwN4BPUlxQEzPzUwHwY_ChRi8G86VzTWs9mVncDjX781XKLB6vMkELW6oCI4hsXrCL3ngwO-vqdHTuvTawY5zsvWOIvU5EUxrw3nhHS1fTY-CVINc8I9MfuVZSQUHaw7CAFKnw1jtqisWvA)

* It is possible to build poses that push rotations beyond the set limits. Keep in mind that many joint rotations require a corrective blendshape to make them look correct when rotated to the limits. Turning off limits will allow you to push the rotation beyond but the corrective blendshapes will remain within their limits. For best results, avoid turning off limits except when absolutely necessary

* Poses should not include the “Heeled Shoe” pose controls (only shoes should use it for their poses)