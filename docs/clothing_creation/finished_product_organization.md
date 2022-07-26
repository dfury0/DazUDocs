# 06 | Finished product organization

Workflow by [Mada](https://www.daz3d.com/mada)

![type:video](https://www.youtube.com/embed/y9V5tZg0X2c)

Length : 5:40

## Product Thumbnails

- PNG thumbnails = 91 x 91
- Tips thumbnails = 256 x 256

## Cleaning up Morphs

- Adjustment morphs : Actor | Adjustments
- Presets : Actor | Adjustments | Presets (conditional grafts etc)
- Body morphs : Item name | Hidden
- JCMs : *Right click on dial* : Set | Presentation | Content Type | Modifier/Corrective
- JCMs : *Right click on dial :* Hidden | Hide selected properties
- JCMs : select and drag into Item Name | Hidden on the left

## Setting up a push modifier with an empty weightmap to paint out poke throughs

- Select your item in the scene and go to Create | New Push Modifier Weight Node
- I rename it to Adjustable Weightmap Layer (clothing item name)
- Select in the scene tab and go to the weightmap tool settings
- Click on the new map you just created in Unused Maps and then Add Map
- Select the map and it will show up as red – as a default it comes in 100% filled
- Select all the faces and right-click in the viewport
  - Weight Editing | Fill Selected | Weight Value 0%
- Select Genesis to save a wearable preset
  - File | Save As | Wearable Preset
- On the Wearable Preset Save Options tab select everything that goes with that specific item (rigid follow node buttons, surface add-ons, push modifier layers) and save

## Zipping up files

- Inside the main content folder, you need to zip up the following files
  - data
    - Vendor Name
      - Product Name
        - Outfit Name
          - Morphs
            - Vendor Name
              - Base
                - Morphs and JCMS
          - UV Sets
          - .dsf
  - People
    - Genesis 8 Female or Male
      - Clothing
        - Product name
          - Files
  - Runtime
    - Textures
      - Vendor Name
        - Product Name
          - Texture files