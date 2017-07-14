# Sample Project: "_Node Cloning"_

This documentation highlights the key features of the IOGRAM Sample project "Node Cloning" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "Node Cloning" project illustrates how to use the node cloning component to efficiently create copies of a static model with different transformations.![](/assets/Overview_small.PNG)

There are three main ideas in the project:

1. Constructing a transform.  
   Since we will be creating many copies of the same model, we choose to give each copy a unique transform, through a combination of position and rotation.  
   For the position, we use the "HexGrid" component. For the rotation, we use the "Series" component to generate a number of angles between 0 and 360 degrees. The exact number depends on how many grid points are being output by the "HexGrid" component, and we get that number using the "ListLength" component.  
   Connecting the positions and rotations up to the "ConstructTransform" component gives us the transformation input to "CloneNode".  
   ![](/assets/Transform.PNG)

2. Cloning a model.  
   The original geometry comes from the "SuperTorus" component. Connecting the\_ TriMesh \_output of this component to the "MeshRenderer" component creates a static model, and the \(integer\) ID of the model's node. Connecting the \_NodeID \_output of the renderer component to the "CloneNode" component will generate copies of the model.  
   ![](/assets/EditAndClone.PNG)

3. Editing the geometry.  
   We take one further step, which is to connect the output of the "SuperTorus" component to the "GeometryEdit" component \(note that this always needs to be connected to the "EditGeometryListener" component!\). This creates a wire cage around the original mesh, which can be edited. Because this is the input to the "CloneNode" component, the changes from the geometry edit are mirrored across all of the models. This is a fun one to make into an app!

## 



