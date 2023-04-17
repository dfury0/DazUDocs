# Transfer Utility
Transfer Utility is one of the main rigging tools for Daz Studio. Transfer Utility is often the first step for rigging if you are making characters, clothing, hair, jewelry or accessories. Unlike other rigging workflows where you add bones and create weights from scratch, Transfer Utility binds objects to a parent figure's skeleton and transfers the parent figures weights automatically.

This means you can add a clothing OBJ to Genesis, run transfer Utility, and the clothing will follow. The difficulty comes in cleaning up the transfer so that you get good behavior however users play with the content. 

If you are setting up a character or prop from scratch you will often want to use the Figure Setup Tool. 

## Fixing Broken Vertex Orders
If your vertex order breaks there might be an issue with your modeling pipeline. Blender, for instance, will change vertex order on import and export unless explicitly told not to. But once you have a broken vertex order is there anything you can do to fix it? If you have the base model with the same broken vertex order you can use transfer utility to project the morph.  