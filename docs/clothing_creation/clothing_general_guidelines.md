# Clothing Tips 

Build Clothing and Hair for the Genesis Base. NOT on custom characters. 

The clothing will project from the base shape to the custom character, then you can adjust the morph for the custom character. This is how clothing can be compatible with multiple characters. 

A benefit of the Genesis Avatar system is sharing clothing between multiple characters. But this comes with challenges. 

## Plan Clothing for Rigging

Rigging a Daz clothing item can be difficult and time-consuming. Expert clothing creators take every shortcut they can. It starts from the planning and design stage. Some articles of clothing, like plate armor, may never deform correctly unless you follow some of these tricks. 

#### Keep clothing geometry close to the base mesh

Tight-fitting clothing is easier to rig. 

Loose clothing requires lots of corrections later in the process. 

#### Keep details away from joint areas

Concentrate details on stable areas with less pose distortion

* middle of shoulder bones
* long thigh bones
* upper chest area

If clothing can be worn separately, it should be a separate model.

Chains, ropes, or ribbons attached at both ends are hard to rig. 

Lose hanging chains, ropes, and ribbons are easier to work with

Use OBJ vertex group import. 

#### Avoid too many rigid parts.

They are a lot of work. Plate armor is hard!

Place rigid objects on single bones. Thinking about bones while modeling will help when rigging. 

Move a belt buckle higher or lower to be on a single bone group. It will perform better. 

#### Mesh Density

Lower density meshes are easier to work with and perform better. Most people add too much resolution, life will be easier if you go lower. 

Fine details should be done in textures, not through modeling. 

Mesh density should generally be about the same as the character base mesh. 

Model for SubD. Daz Studio works well with subdivisions. 

Hold edges with extra loops if necessary

Retopologize simulated cloth to match Genesis mesh density. 

Rigging high-density meshes is a nightmare and rarely works. Low resolution is usually better. 

#### Modeling

Model clothing shape to match how the clothing hangs in the reference. 

Model some wrinkles into the base. Simulating dForce will smooth the mesh overall. 

Add cloth thickness to mesh, but do not include backside. This is fairly unique

DO NOT cap ends. Our smoothing modifier explodes if you do. 

## Make UVs for Texture Artists

Make your UVs so others can easily modify and create new textures

flat UVs with vertical alignment for textures

Group UVs by similar type so they are easy to find. 

Make sure the texture is easy to modify in 2d image editors. 

Cut UV seams where real-world clothing seams would be.

UVs can be updated after rigging, but we avoid it if we can. 

#### Test UVs for distortion

Test with a vertical stripe and horizontal stripe pattern. 

## General Clothing Rigging Guidelines

Rigging clothing in Daz Studio can be quite different from traditional rigging pipelines. Because Genesis is an avatar system, you are making sure the clothing works with multiple Genesis characters.

#### Clothing is rigged to the base character using Transfer Utility

Transfer Utility projects bone weights from one figure to another

Weighting a low res proxy object is easier. 

#### Selecting Donor Clothing

You can transfer rigging from donor clothing and preserve JCM formulas. MAGIC!

Mada's Daz Original Clothing is a great starting place for donor rigging. 

Select a donor outfit with the closest shape and latest date. 

Transfer Utility with Presets Script transfers weights and Morphs. 

## Weight Painting Cleanup

Weights will already exist from Transfer Utility but may need cleaning. 

Weight paint with Genesis Base Joint Correctives Turned OFF. 

Matching Genesis' shape as it deforms is the goal. It will not look perfect yet. That will require Joint Corrective Morphs, which will come later. 

Use the Add brush to paint weights. The Subtract Brush is unpredictable; it has to put weights somewhere and is hard to guess where they will go. 

Test your weights in multiple joint positions. 

If a rigid object is shared by two bones, weight rigid objects to one bone. Then, create a JCM for the second bone.

Turn Genesis Correctives Back on before building Joint Corrective Morphs. 

## Corrective Morphs

Export OBJs to your modeler to make corrective morphs. 

Check mesh distortion using checker UV patterns. 

For reference, you can export a posed character OBJ. 

OBJs brought back into Daz Studio using Morph Loader Pro with Reverse Deformations active. 

Heavier shapes require more correctives. 

Correctives activate with Bones (Joint Corrective Morphs: **JCMs**) or Morphs (Morphs Corrective Morphs: **MCMs**). If your clothing morph has the same name as a morph on Genesis, it will activate automatically with that genesis morph. Other morphs you need to set up manually. 

#### Adjustment Morphs Required for Characters *(to be updated)*

## Common Corrective Morph Fixes

Under arms when the shoulders bend:

* down
* forward
* down + forward

Thigh bend

* forward
* sitting pose
* abdomen twist

Do not fight auto projection morphs. Just fix the broken mesh. In other words, don't try to fix mesh placement from a different character morph. As a clothing modeler, you cannot control how the character meshes deform. Just make it less broken. 

If the pose crunches geometry, start from the base mesh to get clean deformations. This is useful for collars and belts. 

The neck area is difficult to get right because there are a lot of bones in the area. 

Use the smoothing modifier export/reimport trick!

## Ways to save clothing

#### Figure Prop Asset 

* Geometry data
* Shaders
* Materials

#### Wearable Presets 

* do not affect Geometry. 

* Can be used for 







