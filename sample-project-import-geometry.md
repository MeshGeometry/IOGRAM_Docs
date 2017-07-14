## Sample Project: _"Import Geometry"_

The "Import Geometry" sample project demonstrates how to import geometry objects stored in standard file formats into your Iogram project or application. Additionally, each object is hooked up to an "ObjectMove" component allowing the user to move objects around manually in the scene with the mouse.

![](/assets/ImportAndMove1.jpg)

By default users can choose from among the following files:

* OBJ: arm.obj, armadillo.obj, and truck.obj
* OFF: beetle.off, camelhead.off
* DXF: assorted\_shapes.dxf

You can add your own too! The provided files listed above are placed at the top level of the Data folder in the sample project, so that is a good place to add any of your own geometry files for this project.

The geometry in this project is imported by the components "ReadDXF", "ReadOBJ", and "ReadOFF".

![](/assets/ImportAndMove2.jpg)

Hello



![](/assets/ImportAndMove3.jpg)

