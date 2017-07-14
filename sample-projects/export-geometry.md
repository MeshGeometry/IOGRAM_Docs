#Sample Project: _"Export Geometry"_#

This documentation highlights the key features of the IOGRAM Sample project "Export Geometry" found[ here](https://github.com/MeshGeometry/IogramSamples).

This sample project showcases Iogram's ability to export geometry in standard file formats. In the application, two sliders control the "Frame factor" and "Window factor" for Frame and Window operations respectively on a sphere. When the user moves both factors away from the default zero value, a framed and windowed sphere appears in the view.

![](/assets/export_geometry_0.jpg)

When ready, the user enters a root file name, and the framed and windowed sphere geometry is saved to disk in OBJ, OFF, PLY, and DXF file formats. Under the hood, the project saves these files to disk using the "WriteOBJ", "WriteOFF", "WritePLY", and "WriteDXF" components.