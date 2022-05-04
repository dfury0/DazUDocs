# 01 | Flat Sandals
Workflow by [Mada](https://www.daz3d.com/mada)
![type:video](https://www.youtube.com/embed/5_D6OZ-d1ko)

Length : 5:01

## Weightmapping

- Import your obj into Daz Studio. Use the transfer utility and choose Genesis as Source and your outfit as the Target
  *(For flat shoes I’ll select the Full-Body template since that will group all the individual toe weightmaps into a main left and right toe group.)*
- Select Genesis and find the Base Joint Correctives button under Parameters and turn it off. This will turn off all the JCMs so that you can concentrate on just the weightmapping. You want to get the best possible weightmapping at this point
- Select the left foot and bend it down. Turn on your weightmap tool and use the smoothing brush
- Bend the left toes and adjust the weightmap using the smoothing brush and the paint brush
- Select the left foot on the shoes and activate the weightmap brush. Right click and go down to Weight Editing and then Weight Map Symmetry. Select Entire Figure, Axis X, +to- (Left to Right) and tick Create maps if they do not exist and then accept. This will mirror the weightmapping from one shoe to the other side. It will only work if your shoes are symmetrical, mirrored left to right
- Turn on Base Joint Correctives on Genesis

![type:video](https://www.youtube.com/embed/8n2UWTRr8qM)

Length : 8:31

## JCMs

- Select the left foot on Genesis and on the bend dial open up the parameter settings. Change the max from 65.0 to 75.0
- Set your shoes to base mesh and turn smoothing on and off to see which will be better for the JCM. Click on the shoes, select currently used in parameters, open parameter settings and copy the name of the JCM – in this case
  - pJCMFootDown_75_L (the 75 is why you changed the setting on Genesis, so that you can set the foot to 75 and get a 100% dialed JCM to work on)
- Export the obj and name it exactly the same by using the copied name. Fix the morph in your modeler keeping and eye on the texture distortions and mesh collisions. Export the fixed morph and use Morph Loader Pro to import the morph into Daz Studio. Use reverse deformation to get the best results
- Zero the left foot and bend the right foot down to 75. Use Morph Loader Pro to import pJCMFootDown_75_L again, but in the dropdown rename it from pJCMFootDown_75_L to pJCMFootDown_75_R. Under Morph Mirroring select X:Swap and click accept. This will mirror the left foot morph to the right foot – and again this will only work if the mesh is symmetrical left and right
- Follow the same process for the toes – export left toe morph, fix, import with Morph Loader Pro. Then import and use Morph Mirroring to get the toe morph for the right foot

![type:video](https://www.youtube.com/embed/UBSa9e_Vzm0)

Length : 5:21

## Adjustment and full body morphs

- Now test the full body morphs and fix as needed.
- For more extreme morphs like Edie turn on smoothing and set collision item to none. That gives a smoothed mesh that’s not distorted by Edie’s mesh pushing through the shoes. Take smoothing iterations up to between 5 and 10 as needed. Export obj and fix in modeler with symmetry on so you only need to fix one side
- *NOTE: Always use the bodymorph dial only and not the full character morph since that will often include scaling*
