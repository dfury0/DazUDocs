# Tips | Fixing geometry after rigging

Workflow by [Mada](https://www.daz3d.com/mada)

![type:video](https://www.youtube.com/embed/YcdJ_aObq4g)

Length : 3:02

In this video I’ll show how to update geometry after a clothing item is already finished and rigged and how to prevent losing the face groups when you update. I noticed on the top that when I turn smoothing on and off that a part of the edge on the top is moving more than I like.

- Set the mesh resolution (SubD) to base and turn smoothing off.
- Import your file into your modeller of choice.
  *(I’m using Modo but it will be the same process in most modelers. I can turn on SubD in Modo on the fly with my tab key to see what its going to look like in Daz Studio when SubD is turned on.)*
- Select Genesis, flip the polygons so you can see where the problem areas are on the inside. Select the top and use the move and push tools to adjust the mesh so it doesn’t poke through Genesis.
- Export the mesh out and save as an obj.
  *(I like to keep a copy of the original object as a backup in case something goes wrong – Control+C and Control+V to copy and paste the original, and then save your edited mesh with the original name.)*
- In Daz Studio select
  - Edit | Geometry | Update Base Geometry
- and then for this instance I’m selecting “Update Vertex Positions” since the UVs didn’t change, only the vertex points.
- If you changed the UVs select “Update Full Geometry” which will update faces and UVs. This is where you want to make sure that you use an exported mesh from Daz Studio because it will include the face groups that was set up during the rigging process. If you make your changes on the original object before it was rigged and then import the full obj it will lose the face groups. Weight mapping will still be as before.
- Worst case scenario – you lost your faces, the good news is it can be fixed. Use the transfer utility and uncheck everything under general options except for face groups. That will recreate the face groups and keep your edited weightmapping and rigging intact.
- Once the top is updated, save and reload so that you can test the smoothing.