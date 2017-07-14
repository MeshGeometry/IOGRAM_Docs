# Sample Project: _"Curve Offset"_

This documentation highlights the key features of the IOGRAM Sample project "Curve Offset" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "Curve Offset" project illustrates how to use the Polygon and Offset components to create a series of curves. These curves are then rendered using the Curve Renderer and further processed in to a Mesh using the Loft component.

![](/assets/curve_edit_sample_2.png)

Notes:

* In order to make the resulting geometry easily editable, we introduce the Geometry Edit component. This component operates on any Mesh or Curve geometry and creates a editable visual representation in the viewport. You can then click and drag on the handles.
* \***IMPORTANT**\* To use the result of the Geometry Edit you must use the Edit Geometry Listener component. This component can only be used with the Geometry Edit component. It is responsible for returning the changed \(or edited\) geometry back to the Graph. See below for a typical set up.

![](/assets/curve_edit_sample_3.png)





