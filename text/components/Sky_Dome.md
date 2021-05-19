## ![](../../images/icons/Sky_Dome.png) Sky Dome - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Sky%20Dome.py)

![](../../images/components/Sky_Dome.png)

Visualize a sky matrix from the "LB Cumulative Sky Matrix" component as a colored



#### Inputs
* ##### sky_mtx [Required]
A Sky Matrix from the "LB Cumulative Sky Matrix" component, which
* ##### center_pt 
A point for the center of the dome. (Default: (0, 0, 0)) 
* ##### scale 
A number to set the scale of the sky dome. The default is 1,
* ##### projection 
Optional text for the name of a projection to use from the sky
    * Stereographic

* ##### show_comp 
Boolean to indicate whether only one dome with total radiation
* ##### legend_par 
An optional LegendParameter object to change the display of the

#### Outputs
* ##### report
...
* ##### mesh
A colored mesh representing the intensity of radiation for each of
* ##### compass
A set of circles, lines and text objects that mark the cardinal
* ##### legend
A legend showing the kWh/m2 values that correspond to the colors
* ##### title
A text object for the title of the sunpath.
* ##### patch_vecs
A list of vectors for each of the patches of the sky dome.
* ##### patch_values
Radiation values for each of the sky patches in kWh/m2. This
* ##### mesh_values
Radiation values for each face of the dome mesh in kWh/m2. This