## ![](../../images/icons/Spatial_Heatmap.png) Spatial Heatmap - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Spatial%20Heatmap.py)

![](../../images/components/Spatial_Heatmap.png)

Color a mesh as a heatmap using values that align with the mesh faces or vertices.

Note that any brep can be converted to a gridded mesh that can be consumed by 



#### Inputs
* ##### values [Required]
A list of numerical values with which to color the mesh.
* ##### mesh [Required]
A Mesh object, with a number of faces or vertices that match
* ##### offset_dom 
Optional domain (or number for distance), which will
* ##### legend_par 
Optional legend parameters from the Ladybug
* ##### legend_title 
A text string for Legend title. Typically, the units
* ##### global_title 
A text string to label the entire mesh.  It will be

#### Outputs
* ##### mesh
The input _mesh that has been colored with results.
* ##### legend
Geometry representing the legend for the mesh.
* ##### title
A text object for the global_title.
* ##### colors
The colors associated with each input value.
* ##### legend_par
The input legend parameters with defaults filled for