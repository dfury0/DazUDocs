# High Heel Shoe Rigging 
Workflow by [Mada](https://www.daz3d.com/mada)
Rigging high-heeled shoes effectively start from the modeling process. There are a couple of steps in this workflow that are unique to High Heels because the shoes must change the Genesis default pose for them to work correctly. 
## Video
![type:video](https://www.youtube.com/embed/ykMxPJbysjg)

### Pose Genesis for high heels and save pose

* Use High Heel Pose Control or foot bend for custom shoe height
* You can set feet flat legs together for easier modeling
  - You must reverse flat foot pose later
* Save the  heel pose, you will need it later

### Model symmetrical shoes

- Model on Genesis posed for High Heels for reference

* Import shoes OBJ into Daz Studio

* Apply to pose to Genesis and make sure the  shoe still fits

### Transfer saved high-heel pose to the shoes 
This step is critical and unique to making High Heel Shoes. 

- Click high heel posed Genesis
- Select Joint Control Tool
- Right-click in viewport
- Edit | Bake Joint Rotations
  - Changes the default pose for Genesis to wear high heels
  - High Heel creation is the <u>only</u> workflow you will use this tool

### Transfer weights from Genesis to shoes using the Transfer Utility

- No projection template

### Save shoe asset and reload

- File Save As > Figure / Prop Asset
- Create new blank document
- Load Genesis and apply heel pose
- Load shoes

### Paint Weights with toes up

- Create a flat-foot toe-up pose
  - Call it 0_Pose
  - toes up mimic high heel pose
- Paint shoe weights to toe group and foot
  - Not Individual toes

### Create Joint Controlled Morphs for High Heels

- Create left and right foot up/down movement shoe JCMs
  - Flat-foot toes-up morphs
    - **0_Pose_L**
    - **0_Pose_R**
    - Matches shoe pose for toes with heel flat
  - Foot down morphs
    - **Foot_Down_75_L**
    - **Foot_Down_75_R**
    - Increase foot down maximum from 65 to 75 for better performance
  - Foot up morphs
    - **Foot_Up_40_L**
    - **Foot_Up_40_R**

### Set up the originally modeled shoe shape as a morph ERC

- Original Shoe Shape
  - Shape_L
  - Shape_R
  - Original modeled shoe shape
    - ERC to foot bone in default shoe pose
