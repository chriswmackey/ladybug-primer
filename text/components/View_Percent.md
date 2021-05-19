## ![](../../images/icons/View_Percent.png) View Percent - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20View%20Percent.py)

![](../../images/components/View_Percent.png)

Evaluate the percent view to the outdoors or sky from input geometry through context.

Such view calculations can be used to estimate the quality of a view to the

Note that this component uses the CAD environment's ray intersection methods,



#### Inputs
* ##### view_type [Required]
Text or an integer representing the type of view analysis
0 - HorizontalRadial - The percentage of the 360 horizontal view
1 - Horizonta30DegreeOffset - The percentage of the 360 horizontal
2 - Spherical - The percentage of the sphere surrounding each of
3 - SkyExposure - The percentage of the sky that is visible from
4 - SkyView - The percentage of the sky that is visible from the
* ##### resolution 
A positive integer for the number of times that the original
* ##### geometry [Required]
Rhino Breps and/or Rhino Meshes for which view analysis
* ##### context 
Rhino Breps and/or Rhino Meshes representing context geometry
* ##### grid_size [Required]
A positive number in Rhino model units for the size of grid
* ##### offset_dist 
A number for the distance to move points from the surfaces
* ##### geo_block 
Set to "True" to count the input _geometry as opaque and
It is "True" for:
    * SkyView

It is "False" for:
    * Horizonta30DegreeOffset
    * Spherical

* ##### legend_par 
Optional legend parameters from the "LB Legend Parameters"
* ##### parallel 
Set to "True" to run the study using multiple CPUs. This can
* ##### run [Required]
Set to "True" to run the component and perform view analysis of

#### Outputs
* ##### report
...
* ##### points
The grid of points on the test _geometry that are be used to perform
* ##### view_vecs
A list of vectors which are projected from each of the points
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