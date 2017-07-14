# Sample Project: _"Hex Twist"_

This documentation highlights the key features of the IOGRAM Sample project "Hex Twist" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "Hex Twist" project builds an application that lets you stretch and rotate a tower built out of hexagonal cells.

![](/assets/hex_twist_app.jpg)

A view from above the hex tower shows the application in development at an earlier stage. The "HexGrid" component makes a small planar patch of hexagonal cells. The tower is created by replicating this patch under the different transformations coming in to the "HexGrid" component at the "Transform" input.

![](/assets/hex_twist_2.png)

The one-to-many output of the "Series" component helps create a list of `Vector3` objects at "ConstructVector". Each `Vector3` object is used to construct a position-rotation pair in turn used to construct a Transform. The result is a list of Transform objects, each of which acts upon the hexagonal lattice created by "HexGrid".

![](/assets/hex_twist_2b.png)

The group of components shown below illustrates a data tree bookkeeping method.

![](/assets/hex_twist_3b.png)

The unprocessed tree output of the "HexGrid" component stores one hexagon in the form of a closed polyline for each hexagonal cell in each grid patch. The data is arranged as follows:

* Branch 0: first polyline of first patch, second polyline of first patch, ...
* Branch 1: first polyline of second patch, second polyline of second patch, ...

The "PolylineLoft" component can interpolate a mesh between edges of matching polylines. However, if we plug the polylines directly into "PolylineLoft", all the hexagons in the first patch will be lofted together, then all the hexagons in the second patch will be lofted together, and so on. This is not what we want!

We need to arrange the tree as follows:

* Branch 0: first polyline of first patch, first polyline of second patch, ...
* Branch 1: second polyline of first patch, second polyline of second patch, ...

This is accomplished with "FlipMatrix".