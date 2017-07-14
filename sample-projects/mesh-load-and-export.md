# Sample Project: _"Import Geometry"_

This documentation highlights the key features of the IOGRAM Sample project "Import and Move Geometry" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "Import and Move Geometry" sample project demonstrates how to import geometry objects stored in standard file formats into an Iogram project or application. Additionally, each object is hooked up to an "ObjectMove" component allowing the user to move objects around manually in the scene with the mouse.

![](/assets/ImportAndMove1.jpg)

By default this sample lets users choose from among the following files:

* OBJ: arm.obj, armadillo.obj, and truck.obj
* OFF: beetle.off, camelhead.off
* DXF: assorted\_shapes.dxf

You can add your own too! The provided files listed above are placed at the top level of the Data folder in the sample project, so that is a good place to add any of your own geometry files for this project.

The geometry in this project is imported by the components "ReadDXF", "ReadOBJ", and "ReadOFF", each of which is hooked up to receive user input from the scene.

![](/assets/ImportAndMove2.jpg)

The objects read in from these components are rendered by the Mesh, Curve, and Point renderer components as appropriate. In particular, see how the "ReadDXF" component imports meshes, polylines, and points!

![](/assets/ImportAndMove3.jpg)

The scene can become quite cluttered, with the camelhead and armadillo vying for your attention, so be sure to try moving things around with the capability provided by the "ObjectMove" components.