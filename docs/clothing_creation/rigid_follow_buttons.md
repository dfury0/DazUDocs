# 03 | Rigid Follow Node Buttons
Workflow by [Mada](https://www.daz3d.com/mada)
![type:video](https://www.youtube.com/embed/R0jFHrqtO-o)

Length : 9:54

Rigid follow nodes are useful in that items attached to the node will follow the face its parented to when you pose or add morphs. This is an excellent way to prevent distortions by morphs and to keep the shape of the button intact. Its also a good way to stop buttons from floating away when you use dForce.

## Removing buttons from an obj without losing rigging

- To remove buttons from an already rigged outfit select all the button faces in the geometry editor
- Right click in the viewport and select Geometry Visibility | Hide Selected Polygon(s)
  *(I prefer to hide the polygons first so I can see if faces that I didn’t want to delete got selected by accident)*
- Right click in the viewport again and select Geometry Editing | Delete Hidden Polygon(s)
- Don’t save over the same file you loaded from, give it a new name under Item Name that’s different from the previous item ie Threads Top should be Threads Top2
  (*If you call it the same name you might have leftover morphs from the previous outfit and you’ll get errors. You can also give it a new Product Name, that will have the same result as new item name*)

## Creating Rigid Follow Nodes

- Import the buttons you deleted before as individual props
  *(I usually export them from my original obj as single buttons, it makes it easier to drop them into place and my buttons are small in file size so doesn’t affect the file size by much)*
- Use the joint editor tool to set the start and end points on the buttons, align the node and save : File | Save As | Support Asset | Figure/Prop Assets. Its important to save them out as props before you reload them, otherwise you’ll have embedded geometry when you save a wearable file
- Change to Geometry Editor and select the face underneath the button that you want to attach to
- Right click in the viewport and select Geometry Assignment | Create Rigid Follow Node from Selected
- Drag and drop each button onto the corresponding node you created for it
- Change the parent for each node by looking at which body part of Genesis is closest to it – ie Chest Lower, and drag and drop the node onto the Chest Lower on the clothing item
- If you find the button is moving around when posing you can try to attach it to another face or select less faces, or change the parent body part
- To clean up the viewport click the eye icons next to the nodes in the scene file to hide the crosshairs
- Select Genesis in the scene tab and then File | Save As | Wearable(s) Preset
- Check the boxes for the top and all the buttons to include them in the wearable file