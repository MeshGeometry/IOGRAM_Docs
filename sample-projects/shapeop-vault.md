# Sample Project: _"ShapeOp Vault"_

This documentation highlights the key features of the IOGRAM Sample project "ShapeOp Vault" found[ here](https://github.com/MeshGeometry/IogramSamples).

The "ShapeOp Vault" project illustrates how to use the set of ShapeOp components to perform some basic physics based form-finding. \***IMPORTANT**\* This an intermediate level sample.

![](/assets/shape_vault_1.png)

Notes:

* This project uses three different graph views: Scene \(for general appearance\), Vault \(for ShapeOp logic\), and Color \(for custom coloring of the deformed mesh\). To get to these different views, double click on the Graph View label, and type the name of the view you would like to seem. Remember that you can use the Editor Split View features to view multiple Graph Views at the same time!
* If we were to put all the logic for this project on one Graph View, it would be very difficult to navigate the view and generally cluttered. We there for use the three different views \(mentioned above\). However, this introduces a problem: How do we get data from one view to another? 
* \***IMPORTANT**\* Use the ImportViewData and ExportViewData components to move data between views!

![](/assets/import_shape.png)

