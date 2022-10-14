# Genesis Character Creation Pipeline

### Character Planning

* A good face is most important.

* Use Reference images.

* Check Example characters.

### Test your pipeline before you begin

* Export Genesis 9 Dev load OBJ from Daz.

* Quick Sculpt in app testing your brushes and tools (Zbrush, Mudbox, Blender, etc.).

* Load OBJ as a morph onto Genesis 9 using **Morph Loader Pro**.

* If the morph does **not** load, your pipeline is broken. Make sure the vertex order of the OBJ remains the same for Morph Loader Pro to load new character morphs. Do not remove geometry from the base mesh. 

### Base Mesh Export

* Start from the G9 Devload figure.

* Rough in proportions using HD Body morphs and HD Head Morphs. These morphs are carefully crafted and will minimize distortion in your character.

* Export for Zbrush .
  * GoZ
  * OBJ Export


### Sculpting Process

* Keep the mesh symmetrical. Add asymmetry as another morph. 
* Go as far as you can on the base resolution.

* The base resolution does most shape work; HD morphs look pretty.

* Proportion changes for the character can be dramatic (elves, trolls, infants, gorillas, etc.) But the mesh should not be stretched. 
* Move the mesh proportionally.
  *  Along the normal axis is best (ALT + Move Brush in Zbrush)

* Be careful of bumping sensitive areas like eyelids, lips, and nails while sculpting.

* Keep asymmetry, nipples, navel, scars, and skin damage as layers so they can be toggled and added as new morphs.

### Zbrush Tips

* Use the standard brush with a sharp fall-off over the Dam Standard brush.

* Use subdivision levels 3 or 4 for detail on Genesis 9.

* Zbrush smoothing algorithm will shrink the base mesh.

### Sculpt for Rigging

* The Genesis Weight maps are locked and cannot be changed.

* When you move the Genesis mesh, the bones will move as well.
* If you stretch the mesh to make a new shape, it will stretch every item of clothing the character wears. 
* To check for stretching, load a tile texture to see if you have distorted the mesh. The shape can look good, but stretching breaks compatibility with props. 

### HD Morphs

* They are only allowed for content sold on the Daz Web Store.