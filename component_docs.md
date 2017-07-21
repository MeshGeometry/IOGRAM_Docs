### Maths_Addition
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|X + Y|Addition|Mathematical addition|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|First number to add|Float|Item||
|Y|Y|Y|Second number to add|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Sum|Sum of the numbers|Variant|Item|
### Maths_Subtraction
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|X - Y|Subtraction|Mathematical subtraction|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|Number to subtract from|Float|Item||
|Y|Y|Y|Number to subtract|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Result|Result of the subtraction|Variant|Item|
### Maths_Multiplication
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|X * Y|Multiplication|Mathematical multiplication|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|First number to multiply|Float|Item||
|Y|Y|Y|Second number to multiply|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Product|Product of the numbers|Variant|Item|
### Maths_Division
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|X/Y|Division|Mathematical division|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|Number to divide|Float|Item||
|Y|Y|Y|Number to divide by|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Result|Result of the division|Variant|Item|
### Maths_GreaterThan
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GreaterThan|Greater Than|Tests if input B is greater than input A|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|firstNumber|First number|Float|Item||
|B|B|secondNumber|Second number|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|>|>|Greater than (>)|True if A > B|Variant|Item|
|>=|>=|Greater than or equal to (>=)|True if A >= B|Variant|Item|
### Maths_LessThan
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LessThan|Less Than|Tests if input B is less than input A|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|firstNumber|First number|Float|Item||
|B|B|secondNumber|Second number|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|<|<|Less than (<)|True if A < B|Variant|Item|
|<=|<=|Less than or equal to (<=)|True if A <= B|Variant|Item|
### Maths_RandomValue
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RandomValue|Random Value|Generates a random float between min and max|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|min|min|Min|Start of range (default = 0)|Float|Item||
|max|max|Max|end of range (default = 1)|Float|Item||
|S|S|Seed|Seed for random number generator (int)|Int|Item||
|N|N|Number|Number of random numbers to generate (int)|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|RnadomValue|Random float between min and max|Variant|List|
### Maths_DotProduct
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DotProduct|Dot Product|Computes the dot product of two vectors|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|firstVector|First vector|Vector3|Item||
|Y|Y|secondVector|Second vector|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|D|D|Dot Product|Float representing X dot Y|Variant|Item|
### Maths_CrossProduct
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CrossProduct|Cross Product|Computes the cross product of two vectors|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|firstVector|First vector|Vector3|Item||
|Y|Y|secondVector|Second vector|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Cross Product|Float representing X cross Y|Variant|Item|
### Maths_VectorLength
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|VectorLength|Vector Length|Computes the length of a vector|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|Vector|Vector|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|Length|Float representing length of X|Variant|Item|
### Maths_UnitizeVector
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|UnitizeVector|UnitizeVector|Computes a unit vector from a vector|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|Vector|Vector|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|U|U|UnitVector|Unit Vector in direction of X|Variant|Item|
### Maths_Lerp
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LinInterp|Linear Interpolation|Linear interpolation between two values|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|From|Value to lerp from|Float|Item||
|B|B|To|Value to lerp to|Float|Item||
|t|t|T|Parameter t|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Lerped Value|Value at param t|Variant|Item|
### Maths_RectangularGrid
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RectangularGrid|Rectangular Grid|Generates a planar rectangular grid from transform, number of cells and cell size|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|transform|Transform: sets plane for rectangular grid|Matrix3x4|Item||
|NX|NX|numberX|Number of cells in X direction|Int|Item||
|NZ|NZ|numberZ|Number of cells in Z direction|Int|Item||
|x|x|sizeX|Size of cells in X direction|Float|Item||
|z|z|sizeZ|size of cells in Z direction|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|G|G|Rectangular Grid Vertices|Vertices|Variant|List|
|P|P|Rectangular Grid Polylines|Cell Polylines|Variant|List|
### Maths_RectangularArray
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RectangularArray|Rectangular Array|Generates a 3D rectangular array of cells from transform, number of cells and cell size|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|transform|Transform for coordinate system|Matrix3x4|Item||
|NX|NX|numberX|Number of cells in X direction|Int|Item||
|NY|NY|numberY|Number of cells in Y direction|Int|Item||
|NZ|NZ|numberZ|Number of cells in Z direction|Int|Item||
|x|x|sizeX|Size of cells in X direction|Float|Item||
|y|y|sizeY|size of cells in Y direction|Float|Item||
|z|z|sizeZ|size of cells in Z direction|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|G|G|Rectangular Grid Vertices|Vertices|Variant|List|
### Maths_HexGrid
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|HexagonalGrid|Hexagonal Grid|Generates a planar hexagonal grid|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|transform|Transform: sets plane for hex grid|Matrix3x4|Item||
|NX|NX|numberX|Number of cells in X direction|Int|Item||
|NY|NY|numberY|Number of cells in Y direction|Int|Item||
|NZ|NZ|numberZ|Number of cells in Z direction|Int|Item||
|s|s|size|Size of cells|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|G|G|Hexagonal Grid Vertices|Vertices|Variant|List|
|P|P|Hexagonal Grid Polylines|Cell Polylines|Variant|List|
### Maths_RhodoLattice
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RhodoLattice|Rhodo Lattice|Generates 3D lattice from rhombic dodecahedral tiling|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|transform|Transform for coordinate system|Matrix3x4|Item||
|NX|NX|numberX|Approx. width in rhodo diameters along x-axis of box|Int|Item||
|NY|NY|numberY|Approx. width in rhodo diameters along y-axis of box|Int|Item||
|NZ|NZ|numberZ|Approx. width in rhodo diameters along z-axis of box|Int|Item||
|D|D|Diameter|Diameter of one rhombic dodecahedron|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|G|G|Rectangular Grid Vertices|Vertices|Variant|List|
|P|P|Rhodo Lattice Polylines|...|Variant|List|
### Geometry_Rotation
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConstructRotation|Construct Rotation Quaternion|Construct a rotation quaternion from axis and angle|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|Axis|Axis (unit vector)|Vector3|Item||
|R|R|Angle|Angle of rotation (in degrees)|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Q|Q|Rotation Quaternion|Rotation quaternion out|Variant|Item|
|T|T|Rotation Transform|Rotation transformation out|Variant|Item|
### Geometry_LookAt
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConstructRotation|Construct Rotation Quaternion|Construct a rotation quaternion from axis and angle|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|TargetPoint|Target Point|Vector3|Item||
|UP|UP|Up|Optional Up direction.|Vector3|Item||
|T|T|Transform|Option transform to modify|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Rotation Transform|Rotation transformation out|Variant|Item|
### Geometry_ReadDXF
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ReadDXF|Read DXF|Reads a DXF file. Supports Meshes, Polylines, and Points.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Path|Path to DXF|None|Item||
|Y|Y|Y Up|Force Y Up.|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Meshes|Meshes|Variant|List|
|PL|PL|Polylines|Polylines|Variant|List|
|PT|PT|Points|Points|Variant|List|
### Geometry_WriteDXF
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|WriteDXF|Write DXF|Writes a DXF file. Supports Meshes, Polylines, and Points.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Path|Path to DXF|None|Item||
|Z|Z|Z Up|Force Z Up.|Bool|Item||
|L|L|Layer|Layer|String|Item||
|M|M|Meshes|Meshes|None|List||
|PL|PL|Polylines|Polylines|None|List||
|PT|PT|Points|Points|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Res|Res|Result|Result|Variant|Item|
### Geometry_Reflection
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConstructReflection|Construct Reflection Transformation|Construct a reflection transformation from plane|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Point|Point on plane|Vector3|Item||
|N|N|Normal|Plane Normal|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Rotation Transform|Reflection transformation out|Variant|Item|
### Geometry_ReflectionFromTransform
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConstructReflection|Construct Reflection Transformation|Construct a reflection transformation from plane|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Transform|Transformation representing plane|Matrix3x4|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Rotation Transform|Reflection transformation out|Variant|Item|
### Geometry_PlaneTransform
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PlaneTransform|ConstructPlaneTransform|Construct Transform from Point and Normal|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Point|Point on plane|Vector3|Item||
|N|N|Normal|Plane Normal|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Transform|Plane transform out|Variant|Item|
### Geometry_AffineTransformation
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Affine Transformation|Apply Affine Transformation|Apply spatial transformation to geometric object|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|G|G|Geometry|Mesh to transform|None|Item||
|T|T|Transformation|Transformation to apply to geometry|Matrix3x4|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|H|H|NewGeometry|Transformed Geometry|Variant|Item|
### Sets_Series
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Series||Create a series of numbers|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|Start|First number in the series|Float|Item||
|N|N|Step|Step size for each successive number|Float|Item||
|C|C|Count|Number of values in the series|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Series|Series of numbers|Variant|List|
### Sets_LogisticGrowthSeries
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LogisticGrowth||Create a series of numbers following logistic growth curve|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|MaxVal|Maximum Value in the series|Float|Item||
|S|S|Steepness|rate of increase|Float|Item||
|C|C|Count|Number of values in the series|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Series|Series of numbers|Variant|List|
### Sets_ListItem
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ListItem|List Item|Select items by index|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|List|List of items|None|List||
|I|I|Indices|Indices of desired list items|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|O|O|List items|Selected list items|Variant|Item|
### Sets_IfThen
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|IfThen|If then|Separates list items according to pattern|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|List|List of items|None|List||
|P|P|Pattern|Pattern of separation|VariantVector|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|List A|'true' list items|Variant|List|
|F|F|List B|'false list items|Variant|List|
### Sets_Merge
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Merge|Merge|Merges two lists according to pattern|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|List_A|First List|None|List||
|B|B|List_B|Second List|None|List||
|P|P|Pattern|Pattern of separation|VariantVector|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|MergedList|New compsed list|Variant|List|
### Sets_ListConstruct
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ListConstruct|List Construct|Construct a list from items|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|I1|I1|Item1|First item|None|List||
|I2|I2|Item2|Second item|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|List|List of items|Variant|List|
### Sets_ShiftList
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ListItem|List Item|Select items by index|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|List|List of items|None|List||
|S|S|Shift Length|Number of indices to shift|Int|Item||
|W|W|Wrap|Wrap the indices to branch count|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|O|O|Shifted List|Selected list items|Variant|List|
### Sets_LoopBegin
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ForLoopBegin|For Loop Begin|Entry point for a For Loop|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|Name|Optional label for this loop.|String|Item||
|N|N|Steps|Number of steps to compute. -1 for indefinite loop|Int|Item||
|D|D|Data|Initial Data|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|I|I|Index|Current index|Variant|Item|
|D|D|Data|Optional temporary data|Variant|Item|
### Sets_LoopEnd
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LoopEnd|Loop End|Ends a loop or transmits data back to start.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|LS|LS|LoopStart|Loop start component to operate on. Connect to any Loop Start output.|None|Item||
|S|S|Stop|Optional bool to stop loop|Bool|Item||
|D|D|Data|Generic data to transmit back to start|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|D|D|Last Data|Last computed data|Variant|Item|
### Sets_Heap
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DataRecorder|Data Recorder|Records generic data and outputs to list.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|D|D|DataItem|Data to record|None|Tree||
|N|N|RecordLimit|Number of items to record|Int|Item||
|R|R|Reset|Reset the recording|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|D|D|Data|Optional temporary data|Variant|List|
### Sets_Freeze
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Freeze|Data Freeze|Writes all incoming data to a file. Then, if enabled, reads that data back. Good for saving states.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|D|D|Data|Data to record|None|Tree||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|O|O|Output|Output Data|Variant|List|
### Sets_Pop
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DataRecorder|Data Recorder|Records generic data and outputs to list.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|List|List to pop.|None|List||
|R|R|Rate|Rate to pop items|Float|Item||
|S|S|Stride|Number of items to pop|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Pop|Popped items|Variant|List|
### Sets_NamedPair
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AddKeyValue|Add Key Valye|Adds a key value pair to a variant map|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|N|N|Name|Name of to bind to variant|None|Item||
|V|V|Value|Value of the variant|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Pair|Variant map out.|Variant|Item|
### Sets_AddKeyValue
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AddKeyValue|Add Key Valye|Adds a key value pair to a variant map|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Map|Variant map to operate on. Can be empty.|None|Item||
|K|K|Key|Key of value to add|None|Item||
|V|V|Value|Value add. This input is list access.|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|VM|VM|Map out|Variant map out.|Variant|Item|
### Sets_GetValueByKey
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GetValueByKey|Get Value by Key|Gets a value by key name.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Map|Variant map to operate on. Can be empty.|None|Item||
|K|K|Key|Key of value to add|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Value out|Value out|Variant|List|
### Sets_ExportViewData
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ExportViewData|Export View Data|Exports data from a view to be used in another view.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Out|Out|Data|Data tree to export|None|Tree||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Out|Out|ExportedData|Exported Data|Variant|Tree|
### Sets_ImportViewData
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ImportViewData|Import View Data|Imports data from a view to be used in this view.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|In|In|DataIn|Data in|None|Tree||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|In|In|ImportedData|Exported Data|Variant|Tree|
### Maths_MassAverage
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MassAvg|Mass Average|Average of list of numbers|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|List|List of floating point values|Float|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|A|A|Average|Average of values|Variant|Item|
### Maths_MassAddition
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MassAdd|Mass Addition|Sums a list of numbers|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|List|List of floating point values|Float|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Sum|Sum of values|Variant|Item|
### Input_Slider
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Slider|Slider|An interactive numerical slider.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|||I||Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|||Value||Variant|Item|
### Input_Panel
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY||||
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|||||None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|||||Variant|Item|
### Input_Float
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Float|Float|Creates or casts a float|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|Number|Number to cast to a float|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|F|F|Float|Float|Variant|Item|
### Input_Int
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Integer|Integer|Creates or casts an integer|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|Number|Number to cast to an int|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|I|I|Integer|Integer|Variant|Item|
### Input_Toggle
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Toggle|Boolean Toggle|Boolean Toggle input|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|||||Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|||||Variant|Item|
### Input_ScreenToggle
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenToggle|Screen Toggle|Adds a boolean toggle to the user interface|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|P|Position of the button in screen coordinates.|None|Item||
|L|L|Label|Label of the button|String|Item||
|T|T|Toggle|Toggle mode|Bool|Item||
|I|I|Priority|Priority Index|Int|Item||
|PE|PE|Parent|Optional parent|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ptr|Ptr|Button Pointer|Pointer to the UI Element|Variant|Item|
### Input_ScreenContainer
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenContainer|Screen Container|A container for UI objects.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|N|N|Name|Name of this container|String|Item||
|P|P|Position|Optional position. If left blank, the element is automatically positioned.|Vector3|Item||
|S|S|Size|Optional size. If left blank, the element is automatically size.|Vector3|Item|	|
|O|O|Options|Container options|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|ContainerElement|Container Element|Variant|Item|
### Input_CustomElement
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenText|Screen Text|Adds some text to the screen UI|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|CustomType|Custom type name to create. Name must be contained the style file|None|Item||
|F|F|Style File|Optional file to look up. If blank, the default style file will be used.|String|Item||
|P|P|Position|Optional position. If left blank, the element is automatically positioned.|None|Item||
|S|S|Size|Size of root element|None|Item||
|I|I|Priority|Priority|Int|Item||
|PE|PE|Parent|Optional Parent element|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|CE|CE|CustomElement|Custom Element|Variant|Item|
|C|C|Children|Children elements.|Variant|List|
### Input_ButtonListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ButtonListener|Button Listener|Listens to button in scene|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|BP|BP|Button Pointers|Pointers to screen buttons|None|Item||
|M|M|Mute|Mute this listener|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Values|Values Out|Variant|Item|
### Input_LineEditListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LineEditListener|Line Edit Listener|Listens for line edit input|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|LE|LE|LineEdit Pointers|Pointers to screen line edit|None|Item||
|M|M|Mute|Mute this listener|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Values|Values Out|Variant|Item|
### Input_KeyboardListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|KeyboardListener|Keyboard Listener|Listens for Key strokes|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|On|On|On|Listen for mouse clicks|Bool|Item||
|K|K|Key Filter|Keys to listen to. If blank, return all.|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Key Press|Returns once on the frame that the key has pressed.|Variant|Item|
|D|D|Key Down|Returns on every frame that the key is held down.|Variant|Item|
|U|U|Key Up|Returns once on the frame that the key is released.|Variant|Item|
### Input_MouseDownListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MouseDownListener|Mouse Down Listener|Listens for mouse down in scene|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|On|On|On|Listen for mouse clicks|Bool|Item||
|MB|MB|Mouse button|Mouse Button|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|MP|MP|Mouse Position|Mouse Position|Variant|Item|
|MD|MD|Mouse Delta|Mouse Delta|Variant|Item|
### Input_GamepadListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GamepadListener|Gamepad Listener|Listens for gamepad input|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|On|On|On|Listen for mouse clicks|Bool|Item||
|GI|GI|Gamepad index|Gamepad Index|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|BI|BI|Button ID|Button ID|Variant|Item|
|BV|BV|Button Value|Button Value|Variant|Item|
|AI|AI|Axis ID|Axis ID|Variant|Item|
|AV|AV|Axis Value|Axis Value|Variant|Item|
### Input_ScreenLineEdit
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenLineEdit|Screen Line Edit|Adds a line edit to the user interface|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Screen Coords|Point Coordinate in Screen Space|None|Item||
|L|L|Label|Label|String|Item||
|I|I|Priority|Optional priority index|Int|Item||
|PE|PE|Parent|Optional parent|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|LE|LE|Line Edit out|Ptr to line edit|Variant|Item|
### Input_ScreenText
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenText|Screen Text|Adds some text to the screen UI|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Position|Optional position. If left blank, the element is automatically positioned.|None|Item||
|T|T|Text|Text to display|String|Item||
|F|F|Font|Path to Font to use|String|Item||
|S|S|Size|Font Size|Int|Item||
|I|I|Priority|Priority|Int|Item||
|PE|PE|Parent|Optional Parent element|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|TE|TE|TextElement|Text Element|Variant|Item|
### Input_StringReplace
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|StringFormat|StringFormat|Appends or Creates a string with Formatting.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|String|String to work on|None|Item||
|A|A|ReplaceThis|String to replace|None|Item||
|B|B|ReplaceWith|Replacement string|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|String|Resulting string|Variant|Item|
### Input_StringAppend
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|StringAppend|StringAppend|Appends a string.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|InputString|Input String|None|Item||
|B|B|AppendString|String to append|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|String|Resulting string|Variant|Item|
### Input_ScanDir
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScanDir|ScanDir|Scans a directory for files.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Path|Directory path|None|Item||
|F|F|Filter|Optional filter|None|Item||
|R|R|Recursive|Search directory recursively|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Results|Scanned files|Variant|List|
|F|F|FullPaths|Full paths to scanned files|Variant|List|
### Input_Trigger
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Trigger|Trigger|Transmit IoDataTree at first input upon trigger at second input|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|In|In|IoDataTree|IoDataTree input to transmit on trigger|None|Item||
|Tr|Tr|Trigger|Trigger -- listen for change in trigger input|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|In|In|IoDataTree|IoDataTree transmitted on trigger|Variant|Item|
### Input_ObjectMove
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ObjectMove|ObjectMove|Moves an object based on user interaction|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Constraints|Movement constraints. One bit for each of the 6 degrees of freedom|Int|Item||
|LC|LC|Local Coords|Using local Coords for translation|Bool|Item||
|F|F|Node Filter|Only allow movement on these nodes. If 0, all nodes are allowed to move.|Int|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|ID|ID of affected node|Variant|Item|
|T|T|Transform|Transform defining movement|Variant|Item|
### Input_Vector3
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Vector3|Vector3 Selector|Slider for selecting a Vector3|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|N|N|Default|Vector3|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Vector3|Vector output|Variant|Item|
### Input_ColorSlider
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Color|Color Selector|Slider for selecting a Color|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Color|Color|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Color_out|Color output|Variant|Item|
### Input_GeometryEdit
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GeometryEdit|GeometryEdit|Allows the user to manipulate geometry vertices.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|G|G|Geometry|Geometry to operate on.|None|Item||
|C|C|Constraints|Movement constraints. One bit for each of the 6 degrees of freedom|Int|Item||
|T|T|DisplayThickness|Thickness of display curves|Float|Item||
|CL|CL|Color|Color of diplay curves|Color|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|Edit Geometry|Reference to Edit Geometry. Connect to Edit Geometry Listener.|Variant|Item|
### Input_SketchPlane
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SketchPlane|Sketch Plane|Create a sketch and position it in 3D.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|CP|CP|Curves|Storage and/or optional input curves|None|List||
|R|R|Reset|Resets the sketch area|Bool|Item||
|M|M|Mode|Freeform or Line Mode|Int|Item||
|T|T|Transform|Transform to map curve points|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Curves|Resulting Curves|Variant|List|
|T|T|Texture|Sketch Texture|Variant|Item|
### Input_EditGeometryListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|EditGeometryListener|EditGeometryListener|Listens for updates to editable geometry|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|NodeID|Id of edit geometry to listen to.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|G|G|Geometry|Edited geometry|Variant|Item|
### Interop_SystemCommand
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SystemCommand|Calls a program from the OS|Calls a program from the OS|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Executable|The executable to call|None|Item||
|A|A|Arguments|Arguments|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|ExitCode|Result of the call|Variant|Item|
### Interop_AsyncSystemCommand
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AsyncSystemCommand|Calls a program from the OS|Calls several programs from the OS|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Executable|The executable to call asynchronously|None|Item||
|A|A|Arguments|Arguments|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|ExitCode|Result of the call|Variant|Item|
### Interop_JsonSchema
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|JsonSchema|Create JSON Schema|Creats a JSON Document from geometry data.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|G|G|Geometry|Geometry to parse|None|Item||
|D|D|Directory|Directory|None|Item||
|N|N|Name|Name|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|J|J|Json|Json Document|Variant|Item|
|F|F|File|File|Variant|Item|
### Interop_SendData
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ExportViewData|Export View Data|Exports data from a view to be used in another view.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|In|In|Data|Data tree to export|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Out|Out|ExportedData|Exported Data|Variant|List|
|IP Address|IP Address|IP|IP Address|Variant|Item|
### Interop_ReceiveData
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ExportViewData|Export View Data|Exports data from a view to be used in another view.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Out|Out|Data|Data tree to export|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Out|Out|ExportedData|Exported Data|Variant|List|
### Graphics_LoadResource
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LoadResource|Load Resource|Loads a resource from a path|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Path|Path to Resource file (e.g. "Models/TeaPot.mdl")|None|Item||
|T|T|Type|Type Name. Must be a registered class type. (e.g. "model")|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|ResourcePointer|Void Pointer to Resource|Variant|Item|
### Graphics_SaveResource
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SaveResource|Save Resource|Saves a resource to a path|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|R|R|Resource|Resource to save.|None|Item||
|D|D|Directory|Directory Path save resource.|None|Item||
|N|N|Name|Name to save resource.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|RF|RF|Reference|Reference|Variant|Item|
### Graphics_CreateMaterial
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CreateMaterial|Create Material|Create a material from parameters|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Tec|Tec|Technique|Rendering technique specification.|String|Item||
|P|P|Parameters|Named pairs of shader parameters.|None|List||
|T|T|Textures|Named pairs of texture units.|None|List||
|VS|VS|Vertex Defines|Vertex shader defines|None|List||
|PS|PS|Pixel Defines|Pixel shader defines|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Material|Material|Variant|Item|
|R|R|Resource|Resource Path|Variant|Item|
### Graphics_StandardMaterial
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CreateMaterial|Create Material|Create a material from parameters|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|D|D|Diffuse|Diffuse Color|Color|Item||
|S|S|Specular|Specular Color|Color|Item||
|E|E|Emissive|Emissive Color|Color|Item||
|R|R|Roughness|Roughness|Float|Item||
|M|M|Metallic|Metallic|Float|Item||
|BF|BF|Backface|Backface|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Resource|Resource Path|Variant|Item|
### Graphics_ModifyMaterial
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CreateMaterial|Create Material|Create a material from parameters|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Material|Material to modify|None|Item||
|P|P|Parameters|Named pairs of shader parameters.|None|List||
|T|T|Textures|Named pairs of texture units.|None|List||
|VS|VS|Vertex Defines|Vertex shader defines|None|List||
|PS|PS|Pixel Defines|Pixel shader defines|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Material|Material|Variant|Item|
|MatName|MatName|MatName|MatName|Variant|Item|
### Graphics_Zone
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderSettings|Base Render Settings|Sets a few of the most important render settings.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ZS|ZS|Zone Size|Vector defined size of the render zone|Vector3|Item||
|AL|AL|AmbientLight|Ambient Light. Alpha channel determines brightness.|Color|Item||
|FC|FC|Fog Color|Color of Fog.|Color|Item||
|FE|FE|Fog extents|Fog extents. Vector 3 where x,y are start and end distances. Z is density.|Vector3|Item|	|
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Z|Z|Zone|Pointer to zone|Variant|Item|
### Graphics_Viewport
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Viewport|Create Viewport|Creates a viewport for viewing geometry|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Camera|Camera with which to render viewport.|None|Item||
|R|R|Rect|Screen space rectangle in which to render. If null, full extents are used.|Vector4|Item||
|RP|RP|RenderPath|Base RenderPath for viewport. If blank, this will default to the main viewport path.|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|VP|VP|Viewport|Point to resulting viewport|Variant|Item|
### Graphics_MeshRenderer
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshRenderer|MeshRenderer|Converts a mesh to a viewable object in the scene.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh Structure|None|Item||
|MT|MT|Material|Path to material.|None|Item||
|S|S|SplitVertices|Split the vertices for flat shading|Bool|Item||
|C|C|Color|MainColor|Color|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|ID of rendered node|Variant|Item|
|SM|SM|StaticModelPointer|Void Pointer to Static Model|Variant|Item|
|ModelName|ModelName|ModelName|ModelName|Variant|Item|
### Graphics_PointRenderer
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Display|Geometry Display|Displays geometry in the scene|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Points|Points to render|None|List||
|C|C|Color|Color to Display|Color|Item||
|S|S|Sprite|Sprite to use for points|String|Item||
|D|D|Size|Dimensions of point sprite|Vector3|Item||
|F|F|FixedSize|Use a fixed screen size|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|Node|Node ID of display|Variant|Item|
|B|B|BillboardSet|Pointer to billboard set|Variant|Item|
### Graphics_MeshEdges
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshRenderer|MeshRenderer|Converts a mesh to a viewable object in the scene.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh structure|None|Item||
|C|C|Color|Color|Color|Item||
|W|W|Width|Line width|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|Ptr|Ptr|Model|Static Model Pointer|Variant|Item|
|ModelName|ModelName|ModelName|ModelName|Variant|Item|
### Graphics_CurveToModel
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CurveToModel|Curve To Model|Converts a curve to a model on disk with a pointer to the model|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline structure|None|Item||
|F|F|File|Optional path to save Model|String|Item||
|T|T|Thickness|Line thickness|Float|Item||
|C|C|VertexColors|VertexColors|VariantVector|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|ModelPointer|Void Pointer to Model|Variant|Item|
|ModelName|ModelName|ModelName|ModelName|Variant|Item|
### Graphics_CurveRenderer
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Curve Renderer|Curve Renderer|Curve Renderer|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Curve|Curve to render|None|Item||
|W|W|Width|Width of curve|Float|Item||
|C_A|C_A|Color_A|Color|Color|Item||
|C_B|C_B|Color_B|Color|Color|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|Node ID|Node ID|Variant|Item|
### Graphics_RenderTexture
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderTexture|Render Camera to Texture|Creates a texture that is filled by the given camera.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Camera|Camera with which to render viewport.|None|Item||
|VP|VP|Viewport|Optional viewport to use for render texture|None|Item||
|RP|RP|RenderPath|Base RenderPath for viewport. If blank, this will default to the main viewport path.|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Texture|Render Texture|Variant|Item|
|M|M|Material|Basic Material with the RenderTexture assigned.|Variant|Item|
|TextureName|TextureName|TextureName|TextureName|Variant|Item|
|MatName|MatName|MatName|MatName|Variant|Item|
### Graphics_Texture2D
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderTexture|Render Camera to Texture|Creates a texture that is filled by the given camera.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|DimX|Pixel dimensions in X direction|Int|Item||
|Y|Y|DimY|Pixel dimensions in Y direction|Int|Item||
|C|C|Colors|Color array to fill texture|Color|List||
|N|N|Name|Optional name for texture resource.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Texture|Texture|Variant|Item|
|I|I|Image|Image path|Variant|Item|
### Graphics_Texture3D
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderTexture|Render Camera to Texture|Creates a texture that is filled by the given camera.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|DimX|Pixel dimensions in X direction|Int|Item||
|Y|Y|DimY|Pixel dimensions in Y direction|Int|Item||
|Z|Z|DimZ|Pixel dimensions in Z direction|Int|Item||
|C|C|Colors|Color array to fill texture|Color|List||
|N|N|Name|Optional name for texture resource.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Texture|Texture|Variant|Item|
|I|I|Image|Image path|Variant|Item|
### Graphics_LayersToImage
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderTexture|Render Camera to Texture|Creates a texture that is filled by the given camera.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|Layers|Layers to create image from|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Texture|Texture|Variant|Item|
|I|I|Image|Image path|Variant|Item|
### Graphics_SampleTexture
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderTexture|Render Camera to Texture|Creates a texture that is filled by the given camera.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|I|I|Image|Image or texture to sample|None|Item||
|X|X|X|Pixel location in X direction|Int|Item||
|Y|Y|Y|Pixel location in Y direction|Int|Item||
|Z|Z|Z|Pixel location in Z direction|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Color|Color|Variant|Item|
|BW|BW|Greyscale|Greyscale value|Variant|Item|
|L|L|Luminance|Luminance value|Variant|Item|
### Graphics_Light
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Sun|Sun|Create a directional Sun light|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Transform|Transform|Matrix3x4|Item||
|L|L|LightType|LightType|Int|Item||
|C|C|Color|Color|Color|Item||
|R|R|Range|Range|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|LT|LT|Light|LightPtr|Variant|Item|
### Graphics_VertexColors
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CreateMaterial|Create Material|Create a material from parameters|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|D|D|Drawable|Pointer to drawable to edit vertex colors.|None|Item||
|C|C|Colors|Vertex colors.|Color|List||
|FV|FV|Force|Force vertex coloring.|Bool|Item||
|C|C|Copy counts|A list of numbers to copy the color. Useful for per face coloring.|Int|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ref|Ref|Reference|Reference to drawable|Variant|Item|
### Graphics_Skybox
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderTexture|Render Camera to Texture|Creates a texture that is filled by the given camera.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|ColorA|First color for gradient|Color|Item||
|B|B|ColorB|Second color for gradient|Color|Item||
|BR|BR|BlurRadius|Radius for blur.|Float|Item||
|BL|BL|Blend|Blend factor between texture and gradient.|Float|Item||
|T|T|Texture|Optional texture.|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Skybox|Skybox reference.|Variant|Item|
### Graphics_Grid
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Sun|Sun|Create a directional Sun light|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Transform|Transform|Matrix3x4|Item||
|S|S|Scale|Scale|Vector3|Item|	|
|D|D|Density|Density|Float|Item||
|C|C|Color|Color|Color|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|R|R|Reference|Reference|Variant|Item|
|ModelName|ModelName|ModelName|ModelName|Variant|Item|
### Graphics_ReflectionProbe
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ReflectionProbe|Reflection Probe|Create a refleciton probe for environment maps.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Transform|Transform|Matrix3x4|Item||
|R|R|Resolution|Resolution|Int|Item||
|C|C|Color|Color|Color|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|RP|RP|Probe|ProbePtr|Variant|Item|
### Physics_ApplyForce
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ApplyForce|Apply Force|Apply a force (vector with magnitude) to a rigid body|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|R|R|RigidBody|RigidyBody|None|Item||
|F|F|Force|Vector defining the force|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|RigidBody|Rigid Body|Variant|Item|
### Physics_CollisionShape
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CollisionShape|Collision Shape|Construct a collision shape form a mesh or model|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|Node ID|Node to construct collision shape on|None|Item||
|M|M|Base Mesh|Mesh to construct collision shape from|None|Item||
|T|T|Shape type|Type of collision shape to create|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|RigidBody|Rigid Body|Variant|Item|
### Physics_Constraint
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PhysicsConstraint|Physics Constraint|Construct a constraint between a rigidbody and an optional second one.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|Body A|First rigidbody.|None|Item||
|X|X|Local Anchor A|Position in local coordinates for start of constraint|Vector3|Item||
|B|B|Body B|Second rigidbody.|None|Item||
|Y|Y|Local Anchor B|Position in local coordinates for end of constraint|Vector3|Item||
|T|T|Constraint Type|Type of constraint|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Constraint|Constraint|Variant|Item|
### Scene_DeconstructModel
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DeconstructModel|Deconstruct Model|Deconstructs a static model into vertices, faces and normals|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Model|Path to Model|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh Out|Variant|Item|
### Scene_AddNode
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Add Node|Add Node To Scene|Adds a node with optional name and parent|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Transform|Transform of node|Matrix3x4|Item||
|N|N|Name|Optional node name|String|Item||
|P|P|Parent|Optional node parent|Int|Item||
|O|O|Options|Options to control node editing|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|Node ID|ID of node|Variant|Item|
|T|T|Transform|Transform|Variant|Item|
### Scene_CloneNode
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Clone Node|Clones a node and all of its components.|Clones a node|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|NodeID|ID of node to clone|None|Item||
|T|T|Transform|Transform of cloned node|None|Item||
|P|P|ParentID|Optional parent of cloned node|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|ID of new node|Variant|Item|
### Scene_AddStaticModel
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Add Static Model|Add Static Model To Scene|Adds a static model|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|NodeID|ID of node|None|Item||
|Resource|Resource|Resource|Resource|String|Item||
|MT|MT|Material|Pointer to Material|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|SM|SM|Static Model|Pointer to static Model|Variant|Item|
### Scene_AnimatedModel
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Add Static Model|Add Static Model To Scene|Adds a static model|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|NodeID|ID of node|None|Item||
|AM|AM|AnimatedModel|Pointer or path to Model|String|Item||
|MT|MT|Material|Pointer to Material|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|AM|AM|Animated Model|Pointer to animated Model|Variant|Item|
### Scene_PlayAnimation
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PlayAnimation|Play animation|Play an animation|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|NodeID|ID of node|None|Item||
|AC|AC|AnimationController|Pointer to animation contorller|None|Item||
|A|A|Animation|Path to animation|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|AM|AM|Animated Model|Pointer to animated Model|Variant|Item|
### Scene_ScreenPointToRay
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PointToRay|Screen Point To Ray|Given a screen point, returns a ray in world coordinates|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|SP|SP|ScreenPoint|Point in normalized screen coordinates|None|Item||
|CM|CM|CameraPtr|Optional pointer to a camera. If none provided, a camera will be found.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|SP|SP|Start Point|Start point of ray in world coords|Variant|Item|
|DR|DR|Direction|Direction of ray in world coords|Variant|Item|
### Scene_Raycast
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Raycast|Screen Raycast|Listens for screen raycasts, returns hit information|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|SP|SP|StartPoint|Point in world coords|None|Item||
|DR|DR|Direction|Direction in which to cast ray|None|Item||
|MD|MD|Max Distance|Max distance to raycast|Float|Item||
|M|M|Mask|Mask elements from raycast|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|HP|HP|Hit Points|Hit Points of ray|Variant|Item|
|D|D|Distance|Distance|Variant|Item|
|N|N|Normal|Normal|Variant|Item|
|MD|MD|ModelPtr|Model pointer.|Variant|Item|
### Scene_ScreenBloom
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenBloom|Screen Bloom|Adds intensity-controlled screen bloom effect|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|I|I|Intensity|Intensity of Bloom|Float|Item||
|S|S|Source|Source Mix|Float|Item||
|B|B|Bloom Mix|Bloom Mix|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Vertices|Vertices Out|Variant|List|
### Physics_PhysicsWorld
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PhysicsWorld|PHysics World|Initializes physics world|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Go|Go|Step|Run physics|Bool|Item||
|G|G|Gravity|Gravity Vector|Vector3|Item|	|
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|PW|PW|Physics World|Pointer to static physics world|Variant|Item|
### Physics_RigidBody
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RigidBody|Rigid Body|Adds rigid body behaviour to a node|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|Node ID|Node ID to add Rigid body to.|None|Item||
|PW|PW|Physics World|Physics World|None|Item||
|M|M|Mass|Mass. Set to zero if you want a fixed object|Float|Item||
|S|S|Shape type|Collision shape type.|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|RB|RB|Rigid Body|Pointer to Rigid Body|Variant|Item|
|CS|CS|Collision Shape|Pointer to Collision Shape|Variant|Item|
### Scene_Text3D
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Text3D|Text3D|Creates a 3D text node at given position and scale|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Text|Text to display|String|Item||
|P|P|Positon|Position of text node.|Vector3|Item||
|F|F|Font|Font to display|String|Item||
|S|S|Scale|Scale of text|Float|Item||
|O|O|Options|3D Text options as bitmask. 1 - face camera, 2 - keep vertical, 4 - constant pixel size.|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Node ID|Node ID|ID|ID of node|Variant|Item|
|T|T|TextPointer|Pointer to text component|Variant|Item|
### Scene_ScriptInstance
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScriptInstance|Script Instance|Executes a script from file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|SC|SC|ScriptFile|Path to script file|None|Item||
|X|X|X|Input variable called X|None|Item||
|Y|Y|Y|Input variable called Y|None|Item||
|Z|Z|Z|Input variable called Z|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|A|A|A|Output variable called A|Variant|Item|
|B|B|B|Output variable called B|Variant|Item|
|C|C|C|Output variable called C|Variant|Item|
### Scene_MouseClickListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MouseClickListener|Mouse Click Listener|Listens for mouse clickkinput|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|On|On|On|Listen for mouse clicks (bool)|Bool|Item||
|MB|MB|Mouse button|Mouse Button|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|MP|MP|Mouse Position|Mouse Position|Variant|Item|
### Scene_SelectGeometry
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SelectGeometry|Select Geometry|Returns selected geometry|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|On|On|On|Activate selection|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|MeshesOut|Meshes out|Variant|List|
|P|P|PolylinesOut|Polylines out|Variant|List|
|Pt|Pt|PointsOut|Points out|Variant|List|
|MP|MP|Mouse Position|Mouse Position|Variant|Item|
### Scene_ModifyNode
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ModifyNode|Modify Node|Modifies basic properties of a Node|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|ID|Node ID|None|Item||
|T|T|Transform|New transfrom|None|Item||
|N|N|Name|Name|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|ID|ID of node|Variant|Item|
|||||Variant|Item|
### Scene_GetNode
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GetNode|Get Node|Finds a Node|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|NodeID|ID of node to inspect.|None|Item||
|||||None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|N|N|Name|Name|Variant|Item|
|T|T|Transform|Transform|Variant|Item|
### Scene_GetComponent
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GetComponent|Get Component|Gets a reference to a component from Node ID|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|Node ID|Node ID|None|Item||
|T|T|Type|Type of component to return|None|Item||
|R|R|Recursive|Search node recursively|Bool|Item||
|||||None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ptr|Ptr|Reference|Reference to component|Variant|Item|
### Scene_AddComponent
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AddComponent|Add Component|Adds a native component to a scene node.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|Node ID|Node ID to add component|None|Item||
|T|T|Type|Type of component to add.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ptr|Ptr|Reference|Reference to added component|Variant|Item|
### Scene_ModifyComponent
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ModifyComponent|Modify Component|Modifies the properties of a native component.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Component Reference|Pointer reference to native component.|None|Item||
|P|P|Property|Name of Property to modify.|None|List||
|V|V|Value|Value with which to modify property.|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ptr|Ptr|Reference|Reference to modified component|Variant|Item|
### Scene_SendEvent
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SendEvent|Send Event|Define and send an event|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|E|E|EventName|Unique event name to send|None|Item||
|T|T|DataTree|DataTree to send|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
### Scene_HandleEvent
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|HandleEvent|Handle Event|Receive an Event|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|E|E|EventName|Unique event name to send|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|DataTree|DataTree to send|Variant|Item|
### Scene_SetGlobalVar
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SetGlobalVar|Set Global Variant|Sets a global variant by name (key)|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|K|K|Key|Key of variant to set.|None|Item||
|V|V|Variant|Variant to set|None|Item||
|R|R|Reset|Reset to null value|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Variant|Set variant|Variant|Item|
### Scene_GetGlobalVar
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GetGlobalVar|Get Global Variant|Gets a global variant by name (key)|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|K|K|VarName|Key of variant to get.|None|Item||
|D|D|DefaultValue|Default value if get fails.|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Variant|Returned variant|Variant|Item|
### Scene_TriMeshVisualizeScalarField
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|TriMeshVisualizeScalarField|TriMesh Visualize Scalar Field|Visualize scalar field on a TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|TriMesh|TriMesh input|None|Item||
|SF|SF|ScalarField|Scalar field on the input TriMesh|Float|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|Node|Node ID of displayed TriMesh|Variant|Item|
|M|M|Model|Pointer to model|Variant|Item|
### Scene_LoadScene
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LoadScene|Load Scene|Loads a Scene resource file from XML or JSON|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|ScenePath|Resource Path to scene file|None|Item||
|A|A|Additive|If true, loads scene additively|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|SceneReference|Pointer to loaded scene|Variant|Item|
### Scene_SaveScene
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SaveScene|Save Scene|Saves current Scene resource file from XML or JSON|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|ScenePath|Resource Path to scene file|None|Item||
|J|J|UseJson|If true, will write to JSON format. Otherwise XML.|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Success|Returns true if file was written|Variant|Item|
### Scene_AppendRenderPath
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RenderPath|Render Path|Appends a render path item to a viewport.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|RP|RP|RenderPath|Path to render path definition|None|Item||
|VP|VP|ViewportID|Viewport ID to add render path to.|Int|Item||
|P|P|Parameters|Set additional render path parameters|None|List||
|V|V|Values|Addtional render path values|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|A|A|Tags|Append Render path tags|Variant|Item|
### Mesh_DecimateMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DecimateMesh|Decimate Mesh|Perform decimation on triangle mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh before decimation|None|Item||
|C|C|Target Face Count|Target number of faces|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after decimation|Variant|Item|
### Maths_ConstructTransform
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConTransform|Construct Transform|Construct transform from position, scale, and rotation|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Position|Vector3 position|Vector3|Item||
|S|S|Scale|Vector3 or float scale|Vector3|Item||
|R|R|Rotation|Quaternion for rotation|Quaternion|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|T|T|Transform|Matrix3x4 representing a Transform|Variant|Item|
### Scene_DeconstructTransform
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DeconstructTransform|Deconstruct Transform|Deconstruct a transform into position, rotation, and scale|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|Transform|Transform to deconstruct|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Position|Position|Variant|Item|
|S|S|Scale|Scale|Variant|Item|
|R|R|Rotation|Rotation|Variant|Item|
### Vector_ConstructVector
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConstructVector|Construct Vector|Construct a vector from xyz-coordinates|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|X coordinate|Float|Item||
|Y|Y|Y|Y coordinate|Float|Item||
|Z|Z|Z|Z coordinate|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Vector3|Vector3 out|Variant|Item|
### Input_Inspect
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Inspect|Inspect|Convert tree to string for inspection|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|||TreeIn|Input Tree|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|||TreeOut|Output Tree|Variant|Item|
### Mesh_SmoothMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SmoothMesh|Smooth Mesh|Perform smoothing on triangle mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh before smoothing|None|Item||
|I|I|Iterations|Number of smoothing iterations|Int|Item||
|F|F|Target Factor|Move towards smoothed target by factor|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after smoothing|Variant|Item|
### Input_ScreenSlider
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ScreenSlider|Screen Slider|Adds a slider to the user interface|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Position|Optional position. If left blank, the element is automatically positioned.|None|Item||
|R|R|Range|Range of slider|Vector3|Item||
|L|L|Label|Label|String|Item||
|I|I|Priority|Priority|Int|Item||
|PE|PE|Parent|Optional Parent element|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Screen Slider Out|Ptrs of Slider on Screen|Variant|Item|
### Tree_Flatten
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Flatten|Flatten Tree|Perform flattening on a tree|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|IoDataTree|IoDataTree to flatten|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|F|F|IoDataTree|Flattened IoDataTree|Variant|Item|
### Tree_Graft
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Graft|Graft Tree|Perform grafting on a tree|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|IoDataTree|IoDataTree to graft|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|G|G|IoDataTree|Grafted IoDataTree|Variant|Item|
### Tree_Reverse
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Reverse|Reverse Tree|Perform reversal on a tree|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|IoDataTree|IoDataTree to reverse|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|IoDataTree|Reversed IoDataTree|Variant|Item|
### Tree_Simplify
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Simplify|Simplify Tree|Perform simplification on a tree|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|IoDataTree|IoDataTree to simplify|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|IoDataTree|Simplified IoDataTree|Variant|Item|
### Tree_GetItem
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GetTreeItem|Get Tree Item|Get Tree Item by path and index|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|IoDataTree|IoDataTree storing lookup item|None|Tree||
|B|B|Branch (int)|Path in branch in tree|Int|Item||
|I|I|Optional Index|Index of item in list|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|I|I|Item|Item from tree|Variant|Tree|
### Tree_FlipMatrix
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Flatten|Flatten Tree|Perform flattening on a tree|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|T|T|IoDataTree|IoDataTree to flatten|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|F|F|IoDataTree|Flattened IoDataTree|Variant|Item|
### Sets_ListLength
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ListLength|List Length|Compute list lengths for tree nodes|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|D|D|DataTree|IoDataTree storing lists at nodes|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|LengthTree|IoDataTree storing lengths at nodes|Variant|Item|
### Sets_DivideRange
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Divide||Divides a range into N equal size chunks|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|Min|Range minimum (float)|Float|Item||
|B|B|Max|Range maximum (float > minimum)|Float|Item||
|N|N|Number|Number of partitions|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Series|Divided Range|Variant|List|
### Sets_DivideDomain3D
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DivideDomain||Divides a 3D domain into subdomains|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|MinVec|Range minimum (Vector3)|Vector3|Item||
|B|B|MaxVec|Range maximum (Vector3)|Vector3|Item||
|N|N|DivisionPattern|Number of partitions (Vector3)|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|S|S|Subdomains|Divided Domain|Variant|List|
### Sets_VariantMap
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|VariantMap|Variant Map|Construct a variant map from keys and values|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|K|K|Key|Key|None|List||
|V|V|Value|Value|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|VM|VM|Map|Variant Map|Variant|Item|
### Mesh_DeconstructTriangleMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DeconstructMesh|Deconstruct Mesh|Deconstructs a triangle mesh into vertices, faces, and normals|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Path to Model|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Vertices|Vertices Out|Variant|List|
|F|F|Faces|Faces Out|Variant|List|
|N|N|Normals|Normals Out|Variant|List|
|FC|FC|FaceCounts|Faces counts|Variant|List|
|FN|FN|FaceNormals|Faces normals|Variant|List|
### Mesh_ConstructTriangleMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ConTriMesh|Construct Triangle Mesh|Construct a mesh from vertex and face lists|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|V|V|Vertices|List of coordinates of vertices|None|List||
|F|F|Faces|List of face indices|None|List||
|N|N|Normals|List of vertex normals. If ommitted, they will be computed.|Vector3|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Constructed mesh|Variant|Item|
### Mesh_ClosestPoint
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshClosestPoint|Closest Point to Mesh|Find point on Mesh closest to query point|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to search|None|Item||
|Q|Q|Query Point|Point to search from|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Point|Point on mesh closest to query point|Variant|Item|
|I|I|Index|Index of closest face|Variant|Item|
|D|D|Distance|Distance from query point to mesh|Variant|Item|
### Mesh_HexayurtMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Hexayurt|ConstructHexayurtMesh|Construct a hexayurt mesh from scale|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|W|W|Width|Width to thicken by|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Hexayurt Mesh|Variant|Item|
### Mesh_CubeMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Cube|ConstructCubeMesh|Construct a cube mesh from scale|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Side|Side|Side|Side length|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Cube Mesh|Variant|Item|
### Mesh_Icosahedron
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Icosahedron|ConstructIcosahedron|Construct an icosahedron mesh from scale|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|Scale|Scale of Icosahedron|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Icosahedron Mesh|Variant|Item|
### Mesh_Sphere
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Sphere|ConstructSphere|Construct a sphere mesh from scale|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|R|R|Radius|Sphere radius|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Sphere Mesh|Variant|Item|
### Mesh_Plane
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Plane|ConstructPlaneMesh|Construct a plane mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Height|Height|Height|Offset from origin|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|XZ|XZ|XZplane|XZ Plane Mesh|Variant|Item|
|XY|XY|XYplane|XY Plane Mesh|Variant|Item|
|YZ|YZ|YZplane|YZ Plane Mesh|Variant|Item|
### Mesh_Cylinder
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Cylinder|ConstructCylinderMesh|Construct a Cylinder mesh from radii|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|LowerRadius|Lower radius|Float|Item||
|U|U|UpperRadius|Upper radius (0 for cone)|Float|Item||
|h|h|Height|Height|Float|Item||
|S|S|Sides|Integer (>3) describing number of sides|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|TriMesh|Cylinder TriMesh|Variant|Item|
### Mesh_Pipe
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Polygon|Construct Polygon|Construct a polygon with n sides|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Curve|Curve to pipe.|None|Item||
|S|S|Sides|Number of sides in section.|Int|Item||
|X|X|DeltaX|Stretch in local X direction|Float|Item||
|Y|Y|DeltaY|Stretch in local Y direction|Float|Item||
|E|E|Extension|Extends the segment by this amount.|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Meshed curved with given section.|Variant|Item|
|D|D|Debug|Meshed curved with given section.|Variant|Item|
### Mesh_SaveMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SaveMesh|Save Mesh|Saves a mesh in a variety of formats|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to save|None|Item||
|P|P|Path|Path|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Result|Result|Variant|Item|
### Mesh_CleanMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CleanMeshVertices|Cull Unused Vertices|Cull unused vertices from trimesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh with unused vertices|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after removing unused vertices|Variant|Item|
|N|N|NumRemoved|Number of vertices removed|Variant|Item|
### Mesh_BoundingBox
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|BoundingBox|Bounding Box|Construct TriMesh bounding box for another TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|B|B|BoxMesh|Meshed bounding box of input mesh|Variant|Item|
|min|min|BoxMin|Minimum corner|Variant|Item|
|max|max|BoxMax|maximum corner|Variant|Item|
|C|C|BoxCenter|Centre of box|Variant|Item|
|D|D|Diagonal|Length of box diagonal|Variant|Item|
### Mesh_HausdorffDistance
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|HausdorffDistance|Hausdorff Distance|Compute Hausdorff distance between TriMeshes|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M1|M1|Mesh1|First mesh|None|Item||
|M2|M2|Mesh2|Second mesh|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|HD|HD|HausdorffDistance|Hausdorff distance between input meshes|Variant|Item|
### Mesh_HarmonicDeformation
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|HarmonicDeformation|Harmonic Deformation|Given some displacement vectors, the harmonic deformation field is calculated|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to deform|None|Item||
|V|V|Displacement vectors.|Displacement vectors. Must be parallel to index list.|Vector3|List||
|I|I|Displacement indices|Index of mesh vertices to move. Must be parallel to vector list.|Int|List||
|K|K|Harmonic exponent.|Exponent that controls the deformation field solve|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|HD|HD|Harmonic Displacements|Harmonic displacemnt vectors|Variant|List|
|DM|DM|Mesh|Transformed Mesh|Variant|Item|
### Mesh_TriangulateNMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|TriangulateNMesh|Triangulate NMesh|Triangulates a quad or N-mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to triangulate|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|TM|TM|MeshOut|TriMesh out|Variant|Item|
### Mesh_MeshModeler
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshModeler|Mesh Modeler|Mesh modeling through harmonic deformation|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to edit|None|Item||
|R|R|Radius|Radius of influence|Float|Item||
|D|D|DisplayOn|Toggle render on/off|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|EM|EM|EditedMesh|Edited mesh geometry|Variant|Item|
|ID|ID|NodeID|Editor id|Variant|Item|
### Curve_ZigZagPolyline
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ZigZag|ConstructZigZagPolyline|Construct a zig zag polyline|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|XS|XS|XScale|X-direction scale for zig zag|Float|Item||
|ZS|ZS|ZScale|Z-direction scale for zig zag|Float|Item||
|T|T|Transformation|Transformation to apply to hexayurt|Matrix3x4|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Polyline|Zig zag polyline|Variant|Item|
### Curve_HelixSpiral
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Helix/Spiral|ConstructHelixPolyline|Construct a helix or spiral polyline|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|r_L|r_L|lower_r|Lower radius for helix|Float|Item||
|r_U|r_U|upper_r|Upper radius for helix|Float|Item||
|h|h|height|Height of helix|Float|Item||
|T|T|turns|Number of turns|Float|Item||
|res|res|resolution|Polyline resolution|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Polyline|Zig zag polyline|Variant|Item|
### Curve_PolylineSweep
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PolylineSweep|Polyline Sweep|Sweeps a section curve along one or two rail curves|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|Section|Section polyline|None|Item||
|R1|R1|Rail_1|Rail polyline|None|Item||
|R2|R2|Rail_2|Optional Second Rail polyline|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Sweep mesh|Variant|Item|
### Curve_Polyline
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Polyline|Construct Polyline|Construct a polyline from a vertex list|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|V|V|Vertices|List of coordinates of vertices|None|List||
|C|C|Close|Close the curve|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Polyline|Constructed polyline|Variant|Item|
### Curve_OffsetPolyline
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|OffsetPolyline|Offset Polyline (inexact)|Offsets a polyline by offsetting its vertices|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline to offset|None|Item||
|D|D|Distance|Distance to offset by|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|OP|OP|Offset Polyline|Offset polyline|Variant|Item|
### Curve_SmoothPolyline
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SmoothPolyline|Smooth Polyline|Smooth polyline via subdivision|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline to smooth|None|Item||
|I|I|Iterations|Number of smoothing iterations to perform|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Smoothed Polyline|Smoothed and subdivided polyline|Variant|Item|
### Curve_LineSegment
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LineSegment|Construct Line Segment|Construct a line segment from start and end vertices|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|StartVertex|Start of segment|Vector3|Item||
|B|B|EndVertex|End of segment|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|LineSegment|Constructed line segment|Variant|Item|
### Curve_PolylineBlend
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LoftPolylines|Loft Polylines|Lofts a collection of polylines into a mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P1|P1|Polyline|First polyline|None|Item||
|P2|P2|Polyline|Second polyline|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Lofted mesh|Variant|Item|
### Curve_PolylineDivide
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DividePolyline|Divide Polyline|Divide polyline into equal parts|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline to divide|None|Item||
|N|N|NumParts|Number of parts|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|D|D|DividedPolyline|Polyline divided into parts|Variant|Item|
### Curve_PolylineLoft
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LoftPolylines|Loft Polylines|Perform loft operation on a list of polylines|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|L|L|PolylineList|List of polylines to loft|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Lofted mesh|Variant|Item|
### Curve_PolylineEvaluate
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|EvaluatePolyline|Evaluate Polyline|Evaluate point on polyline from parameter|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline|None|Item||
|T|T|Parameter|Parameter to evaluate|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Point|Point on polyline corresponding to parameter|Variant|Item|
|T|T|Transform|Transform on polyline corresponding to parameter|Variant|Item|
### Curve_PolylineRevolve
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PolylineRevolve|Polyline Revolve|Creates a surface of revolution from a polyline and an axis|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|Section|Section polyline|None|Item||
|A|A|Axis|Axis Vector|Vector3|Item||
|R|R|Resolution|Mesh resolution|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh of revolution|Variant|Item|
### Curve_Polygon
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Polygon|Construct Polygon|Construct a polygon with n sides|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|N|N|Number of sides|Number of sides for the polygon|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Polygon|Constructed polygon|Variant|Item|
|V|V|Vertices|Constructed vertices|Variant|List|
### Curve_SketchPlane
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SketchPlane|Sketch Plane|Create a sketch and position it in 3D.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|CP|CP|Curves|Storage and/or optional input curves|None|List||
|R|R|Reset|Resets the sketch area|Bool|Item||
|M|M|Mode|Freeform or Line Mode|Int|Item||
|T|T|Transform|Transform to map curve points|Matrix3x4|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Curves|Resulting Curves|Variant|List|
|T|T|Texture|Sketch Texture|Variant|Item|
### Curve_MeshSketch
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshSketch|Mesh Sketch|Sketch on a Mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|Surface|Surface to sketch on|None|Item||
|R|R|Reset|Clears the curves|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Curves|The curves.|Variant|List|
|L|L|Last|Last modified curve|Variant|Item|
### Curve_Rebuild
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|RefinePolyline|Refine Polyline|Refine polyline based on list of parameters|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|Curve|Rebuilds the curve with the given number of segments|None|Item||
|N|N|NumPoints|Number of target points|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Curve|The rebuilt curve.|Variant|Item|
### Curve_Length
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CurveLength|Curve Length|Calculates the length of a curve.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|Length|Curve Length|Variant|Item|
### Mesh_SubdivideMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SubdivideMesh|Subdivide Triangle Mesh|Perform subdivision on triangle mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh before subdivision|None|Item||
|S|S|Steps|Number of subdivision steps|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after subdivision|Variant|Item|
### Input_SliderListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SliderListener|Slider Listener|Listens for slider input|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|SP|SP|Sliders|Pointers to sliders|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|SV|SV|Slider Values|Values of Sliders out|Variant|Item|
### Vector_DeconstructVector
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DecVec|Deconstruct Vector|Deconstruct a vector into its components|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|V|V|Vector|Vector to deconstruct|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|X|X|X-Coordinate|X-Coordinate of vector|Variant|Item|
|Y|Y|Y-Coordinate|Y-Coordinate of vector|Variant|Item|
|Z|Z|Z-Coordinate|Z-Coordinate of vector|Variant|Item|
### Maths_EvalFunction
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|EvalFunction|Evaluate Function|Evaluates a basic math function.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|First Arg|First input|Float|Item||
|Y|Y|Second Arg|Second input|Float|Item||
|Z|Z|Third Arg|Third input|Float|Item||
|FN|FN|Function|Function definition in Script|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|Result|Evaluated result|Variant|Item|
### Maths_Expression
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Expression|Evaluate Expression|Evaluates a basic Expression.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|Generic input|Float|Item||
|Y|Y|Y|Generic input|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|A|A|A|Generic output|Variant|Item|
### Vector_ClosestPoint
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ClosePoint|Closest Point|Which point in list is closest|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Point|Query point|Vector3|Item||
|L|L|Point List|List of points|Vector3|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Closest Point|Closest point in list to P|Variant|Item|
|I|I|Index|Index into L of closest point|Variant|Item|
|D|D|Distance|Distance to closest point|Variant|Item|
### Vector_Distance
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Distance|Vector Distance|Compute distance between vectors|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|V|V|Vector|First vector|Vector3|Item||
|W|W|Vector|Second vector|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|D|D|Distance|Distance between vectors|Variant|Item|
### Vector_ColorRGBA
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Color|Construct Color|Construct a color from RGBA values|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|R|R|R|Red|Float|Item||
|G|G|G|Green|Float|Item||
|B|B|B|Blue|Float|Item||
|A|A|A|Alpha|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Color|Color|Variant|Item|
### Vector_ColorPalette
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ClosePoint|Closest Point|Which point in list is closest|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|C|C|StartColor|Start Color|Color|Item||
|N|N|Length|Number of colors to generate|Int|Item||
|V|V|Variance|Variance of colors|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|R|R|ResultingColors|Resulting Colors|Variant|List|
### Vector_BestFitPlane
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|BestFitPlane|Best-Fit Plane|Compute the least-squares plane of best fit|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|G|G|Geometry|Geometry determining the point cloud|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Point|Reference point on best-fit plane|Variant|Item|
|N|N|Normal|Normal to best-fit plane|Variant|Item|
### Scene_UpdateListener
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|UpdateListener|Update Listener|Listens for scene updates|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mute|Mute the listener|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ET|ET|ElapsedTime|Elapsed Time since last start|Variant|Item|
|DT|DT|DeltaTime|Frame update time|Variant|Item|
### Mesh_Offset
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|OffsetMesh|Offset Triangle Mesh|Perform offset operation on a triangle mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to offset|None|Item||
|W|W|Width|Width to offset by|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after offsetting|Variant|Item|
### Mesh_Window
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Window|Mesh Window|Creates a set of windows from a mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to ...|None|Item||
|I|I|Inset Factor|Factor controlling amount of inset|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Windowed mesh|Variant|Item|
### Mesh_Frame
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Frame|Mesh Frame|Creates an inset frame mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to ...|None|Item||
|I|I|Inset Factor|Factor controlling amount of inset|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Framed mesh|Variant|Item|
### Mesh_Thicken
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ThickenMesh|Thicken Triangle Mesh|Perform thickening operation on a triangle mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to thicken|None|Item||
|W|W|Width|Width to thicken by|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after thickening|Variant|Item|
### Mesh_LoopSubdivide
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LoopSubdivide|Loop Subdivide Triangle Mesh|Perform loop subdivision on triangle mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh before subdivision|None|Item||
|I|I|Iterations|Number of iterations to perform|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh after subdivision|Variant|Item|
### Mesh_ExtrudePolyline
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ExtrudePolyline|Extrude Polyline|Extrudes a polyline along a vector|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polyline|Polyline to extrude|None|Item||
|V|V|Extrude Direction|Vector along which to extrude|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Framed mesh|Variant|Item|
### Mesh_FillPolygon
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|FillPolygon|Fill polygon|Triangulates a polygon|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Polygon|Tries to mesh a polygon|None|Item||
|H|H|Holes|Holes of the polygon|None|List||
|T|T|Transform|Optional transform for triangulation|Matrix3x4|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Triangulated polygon|Variant|Item|
### Mesh_FacePolylines
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|FacePolylines|Face Polylines|Returns the face polylines from a mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|P|P|Polylines|Polylines|Variant|List|
### Mesh_Boundary
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshBoundary|Mesh Boundary|Compute boundary of a mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh with boundary|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|B|B|Boundary|Boundary of mesh as polyline|Variant|List|
### Mesh_MeshPlaneIntersection
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeshPlaneIntersection|Mesh Plane Intersection|Intersect triangle mesh with plane|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to intersect with plane|None|Item||
|P|P|Point|Point on plane|Vector3|Item||
|N|N|Normal|Normal to plane|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M1|M1|Mesh1|Mesh on normal side of plane|Variant|Item|
|M2|M2|Mesh2|Mesh on non-normal side of plane|Variant|Item|
### Mesh_JoinMeshes
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|JoinMeshes|Join Meshes|Join meshes in a list into a single mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ML|ML|MeshList|List of meshes|None|List||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|JM|JM|JoinMesh|Joined mesh|Variant|Item|
### Mesh_TriMeshVolume
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|TriMeshVolume|TriMesh Volume|Compute volume of TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh input to volume computation|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V|V|Volume|Volume of mesh|Variant|Item|
### Mesh_Tetrahedralize
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Tetrahedralize|Tetrahedralize Mesh|Create a tetrahedralization of a mesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to tetrahedralize|None|Item||
|V|V|Volume|Optional volume condition|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|TM|TM|MeshOut|Tetrahedralized mesh out|Variant|Item|
### Mesh_UnifyNormals
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|UnifyNormals|Unify Normals|Unify TriMesh normals to consistent orientation|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|MeshIn|Mesh in|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|N|N|MeshOut|Mesh with unified normals|Variant|Item|
### Mesh_AverageEdgeLength
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AvgEdge|Average Edge Length|Compute average edge length for TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|MeshIn|Mesh to compute average edge length on|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|L|L|Length|Average edge length|Variant|Item|
### Mesh_CollapseShortEdges
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CollapseShortEdges|Collapse Short Edges|Collapse edges shorter than (1 - tol) * avg|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|TriMesh|TriMesh before edge collapses|None|Item||
|T|T|Tol|Collapse edges shorter than (1 - tol) * avg|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|N|N|TriMesh|TriMesh after edge collapses|Variant|Item|
### Mesh_MeanCurvatureFlow
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|MeanCurvatureFlow|Mean Curvature Flow|Mean Curvature Flow on TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh input|None|Item||
|Num|Num|NumSteps|Number of steps to flow|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|N|N|Mesh|Mesh output|Variant|Item|
### Mesh_PerVertexEval
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|PerVertexEval|Per-Vertex Evaluate Function|Evaluates function on vertices of TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|TriMesh input|None|Item||
|FN|FN|Function|Function definition in Script|String|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|RL|RL|ResultList|List of results evaluated on each vertex|Variant|List|
### Mesh_ToYUp
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ToYUp|ToYUp|Convert mesh from Z-Up to Y-Up coordinates|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|MeshIn|MeshIn|MeshIn|MeshIn|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|MeshOut|MeshOut|MeshOut|MeshOut|Variant|Item|
### Mesh_ToZUp
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ToZUp|ToZUp|Convert mesh from Y-Up to Z-Up coordinates|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|MeshIn|MeshIn|MeshIn|MeshIn|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|MeshOut|MeshOut|MeshOut|MeshOut|Variant|Item|
### Spatial_ReadOSM
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ReadOSM|Read OSM File|Reads an OSM file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|OSMFile|Path to OSM File (XML)|String|Item||
|S|S|Scale|Scale|Float|Item||
|O|O|Options|OSM Options|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|W|W|Ways|Ways|Variant|List|
|B|B|Buildings|Buildings|Variant|List|
|BH|BH|BuildingHeight|Building Height|Variant|List|
### Spatial_Terrain
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Terrain|Terrain Object|Terrain Object|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|I|I|ImageFile|Image File|String|Item||
|M|M|Material|Material Path|String|Item||
|T|T|Transform|Transform|Matrix3x4|Item||
|S|S|Spacing|Grid Spacing|Vector3|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|T|T|Terrain|Terrain|Variant|Item|
### Spatial_Sun
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Sun|Sun|Create a directional Sun light|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|LA|LA|Latitude|Latitude|Float|Item||
|LO|LO|Longitude|Longitude|Float|Item||
|M|M|Month|Month|Int|Item||
|D|D|Day|Day|Int|Item||
|H|H|Hour|Hour|Float|Item||
|C|C|Color|Color|Color|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|S|S|Sun|SunPtr|Variant|Item|
### Spatial_NavigationMesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AddComponent|Add Component|Adds a native component to a scene node.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|ID|ID|Node ID|Node ID to add component|None|List||
|P|P|Padding|Padding|Vector3|Item||
|C|C|CellSize|Cell Size|Float|Item||
|S|S|MaxSlope|Max Slope|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ptr|Ptr|Reference|Reference to added component|Variant|Item|
|Geometry|Geometry|Geometry|Polylines of nav mesh|Variant|List|
### Spatial_CrowdManager
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CrowdManager|Crowd Manager|Adds a crowd manager to scene root.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|N|N|NavMesh|Nav Mesh|None|Item||
|Q|Q|Quality|Quality level of the crowd|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Ptr|Ptr|Reference|Reference to added component|Variant|Item|
### Spatial_CrowdAgent
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|CrowdManager|Crowd Manager|Adds a crowd manager to scene root.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|N|N|NavMesh|Nav Mesh|None|Item||
|CM|CM|CrowdManager|Crowd Manager|None|Item||
|S|S|Start|Start Point|Vector3|Item||
|T|T|Target|Target Point|Vector3|Item|	|
|V|V|Velocity|Velocity|Float|Item||
|D|D|Agent Dimensions|Radius and height of agent.|Vector3|Item||
|VZ|VZ|Visualize|Visualize|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
|Ptr|Ptr|Reference|Reference to added component|Variant|Item|
### Spatial_AlignedDimension
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|AddComponent|Add Component|Adds a native component to a scene node.|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|A|A|Start|First dimension point.|None|Item||
|B|B|End|Second dimension point.|None|Item||
|O|O|Offset|Offset|Float|Item||
|S|S|Scale|Scale|Float|Item||
|U|U|Up|Up direction hint.|Vector3|Item||
|C|C|Color|Color.|Color|Item|	|
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|Node ID|Variant|Item|
### Mesh_SplitLongEdges
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SplitLongEdges|Split Long Edges|Split edges longer than (1 + tol) * avg|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|TriMesh|TriMesh before edge splits|None|Item||
|T|T|Tol|Split edges longer than (1 + tol) * avg|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|N|N|TriMesh|TriMesh after edge splits|Variant|Item|
### Mesh_ComputeAdjacencyData
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ComputeAdjacencyData|Compute Mesh Topology Data|Computes Mesh Topology Data (manifold trimeshes only!)|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|TriMesh|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh with topology data computed|Variant|Item|
### Mesh_FaceTopology
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|FaceTopology|Compute Mesh Face Topology|Computes Mesh Topology Data for face|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|TriMeshWithAdjacencyData|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V_ID|V_ID|IncidentVertIDs|Indices of vertices incident to F|Variant|List|
|V|V|IncidentVertices|Vertices incident to F|Variant|List|
|F|F|AdjFaces|Indices of faces adjacent to F|Variant|List|
### Mesh_VertexTopology
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|VertexTopology|Compute Mesh Vertex Topology|Computes Mesh Topology Data for vertices|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|TriMeshWithAdjacencyData|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V_ID|V_ID|VertexStarIDs|Indices of vertices adjacent to V|Variant|List|
|V|V|VertexStar|Vertices adjacent to V|Variant|List|
|F|F|AdjFaces|Indices of faces incident to V|Variant|List|
### Mesh_BoundaryVertices
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|VertexTopology|Compute Mesh Vertex Topology|Computes Mesh Topology Data for a given vertex|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|TriMesh|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|B_ID|B_ID|BoundaryVertexIDs|Indices of vertices on mesh boundary|Variant|List|
|B|B|BoundaryVertices|Vertices on boundary|Variant|List|
|I_ID|I_ID|InteriorVertexIDs|Indices of interior vertices of mesh|Variant|List|
|I|I|InteriorVertices|Vertices in mesh interior|Variant|List|
### Mesh_DeconstructFace
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|DeconstructFace|Compute Mesh Face Data|Returns normal, centroid and vertices of face|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|TriMesh|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|V_ID|V_ID|FaceVertexIDs|Indices of vertices on mesh face|Variant|List|
|V|V|FaceVertices|Vertices on face|Variant|List|
|N|N|FaceNormal|Normal to face|Variant|Item|
|C|C|FaceCentroid|Centroid of face|Variant|Item|
### Mesh_Torus
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Torus|ConstructTorusMesh|Construct a torus mesh from radii|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|O|O|OuterRadius|Outer radius|Float|Item||
|I|I|InnerRadius|Inner radius|Float|Item||
|P1|P1|FirstPower|FirstPower|Float|Item||
|P2|P2|SecondPower|SecondPower|Float|Item||
|R|R|MeshResolution|Integer (>3) describing mesh resolution|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|QuadMesh|Torus QuadMesh|Variant|Item|
|T|T|TriMesh|Torus TriMesh|Variant|Item|
### Mesh_SuperEllipsoid
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SuperEllipsoid|ConstructSuperEllipsoidMesh|Construct an ellipsoid mesh from params|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|X|X|X|X scale (> 0)|Float|Item||
|Y|Y|Y|Y scale (> 0)|Float|Item||
|Z|Z|Z|Z scale (> 0)|Float|Item||
|r|r|FirstPower|FirstPower (0.2 < r < 4)|Float|Item||
|t|t|SecondPower|SecondPower (0.2 < t < 4)|Float|Item||
|R|R|MeshResolution|Integer (>3) describing mesh resolution|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|TriMesh|SuperEllipsoid TriMesh|Variant|Item|
|Q|Q|QuadMesh|SuperEllipsoid QuadMesh|Variant|Item|
### Mesh_FlipNormals
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|FlipNormals|Unify Normals|Unify TriMesh normals to consistent orientation|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|MeshIn|Mesh in|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|N|N|MeshOut|Mesh with flipped normals|Variant|Item|
### Mesh_OrientOutward
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|OrientOutward|OrientOutward|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|MeshIn|Mesh in|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|N|N|MeshOut|Mesh out|Variant|Item|
### Mesh_ReadOBJ
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ReadOBJ|ReadOBJ|Read TriMesh from OBJ file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|File|File|File|File|None|Item||
|ToYUp|ToYUp|ToYUp|Transform coords to Y Up|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh|Variant|Item|
### Mesh_ReadOFF
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ReadOFF|ReadOFF|Read TriMesh from OFF file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|File|File|File|File|None|Item||
|ToYUp|ToYUp|ToYUp|Transform coords to Y Up|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh|Variant|Item|
### Mesh_ReadPLY
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ReadPLY|ReadPLY|Read TriMesh from PLY file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|File|File|File|File|None|Item||
|ToYUp|ToYUp|ToYUp|Transform coords to Y Up|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|M|M|Mesh|Mesh|Variant|Item|
### Mesh_WriteOFF
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|WriteOFF|WriteOFF|Write TriMesh to OFF file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|FileName|FileName|FileName|FileName|None|Item||
|M|M|Mesh|Mesh|None|Item||
|ToZUp|ToZUp|ToZUp|Transform coords to Z Up|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|SavedName|SavedName|SavedName|SavedName|Variant|Item|
### Mesh_WriteOBJ
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|WriteOBJ|WriteOBJ|Write TriMesh to OBJ file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|FileName|FileName|FileName|FileName|None|Item||
|M|M|Mesh|Mesh|None|Item||
|ToZUp|ToZUp|ToZUp|Transform coords to Z Up|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|SavedName|SavedName|SavedName|SavedName|Variant|Item|
### Mesh_WritePLY
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|WritePLY|WritePLY|Write TriMesh to PLY file|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|FileName|FileName|FileName|FileName|None|Item||
|M|M|Mesh|Mesh|None|Item||
|ToZUp|ToZUp|ToZUp|Transform coords to Z Up|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|SavedName|SavedName|SavedName|SavedName|Variant|Item|
### Mesh_Remesh
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|Remesh|Remesh|Perform basic remeshing on a TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|TriMesh|TriMesh|TriMesh|TriMesh|None|Item||
|Target|Target|TargetEdgeLength|Target average edge length (optional)|None|Item||
|Tolerance|Tolerance|Tolerance|Tolerance from average length to split/collapse|Float|Item||
|NumSteps|NumSteps|NumSteps|Number of split/collapse steps to perform|Int|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|TriMesh|TriMesh|TriMesh|TriMesh after remeshing|Variant|Item|
### Mesh_SlideTowards
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|SlideTowards|SlideTowards|Slide mesh towards another|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|SlidingMesh|SlidingMesh|SlidingMesh|SlidingMesh|None|Item||
|FixedMesh|FixedMesh|FixedMesh|FixedMesh|None|Item||
|TargetFactor|TargetFactor|TargetFactor|0 - do not move; 1 - move all the way|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|NewMesh|NewMesh|NewMesh|Mesh after sliding|Variant|Item|
### Mesh_LinearDeformation
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|LinearDeformation|Mesh Modeler|Mesh modeling through Linear deformation|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to edit|None|Item||
|R|R|Radius|Radius of influence|Float|Item||
|D|D|DisplayOn|Toggle render on/off|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|EM|EM|EditedMesh|Edited mesh geometry|Variant|Item|
|ID|ID|NodeID|Editor id|Variant|Item|
### Mesh_BoxMorph
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|BoxMorph|Mesh Modeler|Mesh modeling through bounding box morph|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|M|M|Mesh|Mesh to edit|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ID|ID|NodeID|NodeID|Variant|Item|
|||||Variant|Item|
### Tmp_TreeAccess
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|BoundingBox|Bounding Box|Construct TriMesh bounding box for another TriMesh|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|Tree|Tree|Tree|Tree|None|Tree||
|DummyIn|DummyIn|DummyIn|DummyIn|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|DummyOut|DummyOut|DummyOut|DummyOut|Variant|Item|
### ShapeOp_Solve
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ShapeOpSolve|ShapeOp Solve|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|CL|CL|Constraint List|Constraint List|None|List||
|WD|WD|WeldDist|Weld points within distance|Float|Item||
|G|G|Gravity|Gravity|None|Item||
|M|M|Mass|Mass (assigned to all points; 1.0f default)|Float|Item||
|D|D|Damping|Damping (default 1.0f)|Float|Item||
|T|T|Timestep|Timestep (default 1.0f)|Float|Item||
|I|I|Iterations|Iterations for solver (default 10)|Int|Item||
|ML|ML|MeshList|List of tracked meshes|None|List||
|ResetPts|ResetPts|ResetPts|Reset points|Bool|Item||
|Restart|Restart|Restart|Restart|Bool|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|Pts|Pts|Points|Point list output|Variant|List|
|ML|ML|MeshList|Mesh list output|Variant|List|
### ShapeOp_EdgeStrain
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ShapeOpEdgeStrain|ShapeOp Edge Strain|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|S|S|Start|Start point of edge|None|Item||
|E|E|End|End point of edge|None|Item||
|W|W|Weight|Weight of edge constraint|Float|Item||
|rMin|rMin|rangeMin|rangeMin for ShapeOp EdgeConstraint|None|Item||
|rMax|rMax|rangeMax|rangeMax for ShapeOp EdgeConstraint|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ES|ES|EdgeStrain|EdgeStrain ShapeOp constraint|Variant|Item|
### ShapeOp_TriangleStrain
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ShapeOpTriangleStrain|ShapeOp Triangle Strain|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|vA|vA|vertexA|Triangle vertex A|None|Item||
|vB|vB|vertexB|Triangle vertex B|None|Item||
|vC|vC|vertexC|Triangle vertex C|None|Item||
|W|W|Weight|Weight of edge constraint|Float|Item||
|rMin|rMin|rangeMin|rangeMin for ShapeOp EdgeConstraint|None|Item||
|rMax|rMax|rangeMax|rangeMax for ShapeOp EdgeConstraint|None|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ES|ES|TriangleStrain|TriangleStrain ShapeOp constraint|Variant|Item|
### ShapeOp_Closeness
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|ShapeOpCloseness|ShapeOp Closeness|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|P|P|Position|Target position|None|Item||
|W|W|Weight|Weight of edge constraint|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|CS|CS|Closeness|Closeness ShapeOp constraint|Variant|Item|
### ShapeOp_GeometryStrain
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GeometryStrain|Geometry Strain|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|G|G|Geometry|Mesh or polyline geometry|None|Item||
|W|W|Weight|Weight of strain|Float|Item||
|MX|MX|Max|Max of strain|Float|Item||
|MN|MN|Min|Min strain.|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ES|ES|EdgeStrain|Edge Strain|Variant|List|
### ShapeOp_MeshTriangleStrain
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GeometryStrain|Geometry Strain|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|G|G|Geometry|Mesh or polyline geometry|None|Item||
|W|W|Weight|Weight of strain|Float|Item||
|MX|MX|Max|Max of strain|Float|Item||
|MN|MN|Min|Min strain.|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|ES|ES|EdgeStrain|Edge Strain|Variant|List|
### ShapeOp_GenericConstraint
Overview: 

| Icon | Category | Name | Full Name | Description |
| :--- |:--- |:--- |:--- |:--- |
|Textures/Icons/DefaultIcon.png|GRAPH_CATEGORY|GeometryStrain|Geometry Strain|...|
Inputs: 

| Variable | Name | Full Name | Description | Type | List Access | Default Value |
| :--- |:--- |:--- |:--- |:--- | :--- | :--- |
|CT|CT|Type|Constraint type.|None|Item||
|V|V|Vertices|Vertices that define the constraint|None|List||
|W|W|Weight|Weight of strain|Float|Item||
|MX|MX|Max|Max of strain|Float|Item||
|MN|MN|Min|Min strain.|Float|Item||
Outputs: 

| Variable | Name | Full Name | Description | Type | List Access |
| :--- |:--- |:--- |:--- |:--- | :--- |
|C|C|Constraint|Generic Constraint|Variant|Item|
