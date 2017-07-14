# Sample Project: _"Hex Twist"_

This documentation highlights the key features of the IOGRAM Sample project "Hex Twist" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "Hex Twist" project builds an application that lets you stretch and rotate a tower built out of hexagonal cells.

![](/assets/hex_twist_app.jpg)

A view from above the hex tower shows the application in development at an earlier stage.

![](/assets/hex_twist_2.png)

The one-to-many output of the "Series" component helps create a list of Vector3 objects at "ConstructVector". Each Vector3 is used to construct a position / rotation pair in turn used to construct a Transform. The result is a list of Transform objects, each of which acts upon the hexagonal lattice created by "HexGrid".

![](/assets/hex_twist_2b.png)

The group of components shown below illustrates a data tree bookkeeping method. &lt;More to come&gt;

![](/assets/hex_twist_3b.png)

