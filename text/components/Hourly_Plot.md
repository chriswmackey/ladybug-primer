## ![](../../images/icons/Hourly_Plot.png) Hourly Plot - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Hourly%20Plot.py)

![](../../images/components/Hourly_Plot.png)

Create a colored plot of any hourly data collection.



#### Inputs
* ##### data [Required]
A HourlyContinuousCollection or HourlyDiscontinuousCollection
* ##### base_pt 
An optional Point3D to be used as a starting point to generate
* ##### x_dim 
A number to set the X dimension of the mesh cells (Default: 1 meters). 
* ##### y_dim 
A number to set the Y dimension of the mesh cells (Default: 4 meters). 
* ##### z_dim 
A number to set the Z dimension of the entire chart. This will
* ##### reverse_y 
Boolean to note whether the Y-axis of the chart is reversed
* ##### legend_par 
An optional LegendParameter object to change the display of the
* ##### statement 
A conditional statement as a string (e.g. a > 25).
* ##### period 
A Ladybug analysis period to be applied to all of the input _data. 

#### Outputs
* ##### report
...
* ##### mesh
A colored mesh derived from the input _data. Multiple meshes will
* ##### legend
Geometry representing the legend for each mesh.
* ##### borders
A list of lines and polylines representing different time
* ##### labels
A list of text objects that label the borders with the time
* ##### title
A text object for the global_title.