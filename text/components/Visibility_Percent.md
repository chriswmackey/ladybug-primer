## ![](../../images/icons/Visibility_Percent.png) Visibility Percent - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Visibility%20Percent.py)

![](../../images/components/Visibility_Percent.png)

Evaluate the percent visibility from geometry to a specific set of points.

Such visibility calculations can be used to understand the portions of a building



#### Inputs
* ##### view_points [Required]
A list of points that characterize an area of interest to which
* ##### pt_weights 
An optional list of numbers that align with the _view_points
* ##### geometry [Required]
Rhino Breps and/or Rhino Meshes for which visibility analysis
* ##### context 
Rhino Breps and/or Rhino Meshes representing context geometry
* ##### grid_size [Required]
A positive number in Rhino model units for the size of grid
* ##### offset_dist 
A number for the distance to move points from the surfaces
* ##### max_dist 
An optional number to set the maximum distance beyond which the
* ##### geo_block 
Set to "True" to count the input _geometry as opaque and
* ##### legend_par 
Optional legend parameters from the "LB Legend Parameters"
* ##### parallel 
Set to "True" to run the study using multiple CPUs. This can
* ##### run [Required]
Set to "True" to run the component and perform visibility analysis of

#### Outputs
* ##### report
...
* ##### points
The grid of points on the test _geometry that are be used to perform
* ##### results
A list of numbers that aligns with the points. Each number indicates
* ##### mesh
A colored mesh of the test _geometry representing the percentage of
* ##### legend
A legend showing the number of hours that correspond to the colors
* ##### title
A text object for the study title.
* ##### int_mtx
A Matrix object that can be connected to the "LB Deconstruct Matrix"