# Sample Project: _"Basic Interaction"_

This documentation highlights the key features of the IOGRAM Sample project "Basic Interaction" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "Basic Interaction" project illustrates how to use screen sliders to create a simple UI to modify geometry.

This project uses the "SuperEllipsoid" component to generate some mesh geometry. As usual, the output from this component must be connected to the "MeshRenderer" component to view the geometry on screen.

The UI is achieved as follows:

* The "ScreenContainer" component provides an automatic layout for keeping the sliders organized. The _Size_ and _Name_ are set by right-clicking on the respective inputs. 
* The "ScreenSlider" components generate the slider UIs. Connecting the "ScreenContainer" output to the _Parent_ input of the "ScreenSlider" will arrange the Slider in the Container. It is also possible to adjust the ordering of the sliders in the container by adjusting the _Priority_ input \(integer\). 
* The _Range_ of the ScreenSliders is controlled by a Vector3, of which only the X and Y entries are relevant. In this case, the Sliders are constrained to the range \(0.20001, 4.0\). We use the "Panel" component to record this. Note that the vector "0.20001 4 0" is recorded in the body of the panel, and we set the input type \("Vector3"\) in the secondary input panel. 
* Both "ScreenSlider" components must be linked to the "SliderListener" components. This harvests the entries from the sliders, and can provide the data to the "SuperEllipsoid" component.

![](/assets/Interaction.PNG)

After building this out to an app \(see "Getting Started" for method\), you should see the UI we created, and be able to modify the ellipsoid geometry accordingly! ![](/assets/app.PNG)