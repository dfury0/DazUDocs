# High Heel Shoe Rigging
Rigging high heeled shoes effectively starts from the modeling process.
## Video
![type:video](https://www.youtube.com/embed/ykMxPJbysjg)

Pose Genesis for high heels

* Use High Heel Pose Control or foot bend for custom shoe height
* You can set feet flat legs together for easier modeling
  - You must reverse this pose later

Save heel pose

- You will need it later

Create symmetrical high-heel-shoes in modeler 

- Model on high-heel posed Genesis

Import shoes OBJ to Daz

Apply to pose to Genesis and make sure shoe still fits

- Transfer saved high-heel pose to the shoes (critical unique step)
  - Click high heel posed Genesis
  - Select Joint Control Tool
  - Right click in view port
  - Edit | Bake Joint Rotations
    - This is the only workflow you will do this
- Transfer weights from Genesis to shoes using transfer utility
  - No projection template
- Save shoe asset
  - File Save As > Figure / Prop Asset
- Create new blank document
- Load Genesis and apply heel pose
- Load shoes
- Create 0_Pose (flat-foot toe-up pose)
  - toes up mimics high heel pose
- Paint shoe weights to toe group and foot
  - Not Individual toes
- Create left and right foot up/down movement shoe JCMs
  - 0_Pose - Flat-foot toes-up
    - 0_Pose_L
    - 0_Pose_R
    - Matches shoe pose for toes with heel flat
  - Foot Down 75
    - Foot_Down_75_L
    - Foot_Down_75_R
    - Increase foot down maximum from 65 to 75
  - Foot Up 40
    - Foot_Up_40_L
    - Foot_Up_40_R
- Set-up original shoe-shape morph ERC
  - Original Shoe Shape
    - Shape_L
    - Shape_R
    - Original modeled shoe shape
      - ERC to foot bone in default shoe pose
