## ![](../../images/icons/Legend_Parameters_Categorized.png) Legend Parameters Categorized - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Legend%20Parameters%20Categorized.py)

![](../../images/components/Legend_Parameters_Categorized.png)

Use this component to change the colors, range, and display of any Ladybug legend

The legend parameters from this component have more limitations than the normal



#### Inputs
* ##### domain [Required]
A list of one or more numbers noting the bondaries of the data
* ##### colors [Required]
An list of color objects with a length equal to the number of items
* ##### categories 
An optional list of text strings with a length equal to the
* ##### continuous_cols 
Boolean noting whether colors generated are continuous
* ##### continuous_leg 
Boolean. If True, the colors along the legend will be in
* ##### num_decimals 
An optional integer to set the number of decimal
* ##### larger_smaller 
Boolean noting whether to include larger than and
* ##### vert_or_horiz 
Boolean. If True, the legend mesh and text points
* ##### base_plane 
A Plane to note the starting point and orientation from
* ##### seg_height 
An optional number to set the height of each of the legend
* ##### seg_width 
An optional number to set the width of each of the legend
* ##### text_height 
An optional number to set the size of the text in model units.
* ##### font 
An optional text string to specify the font to be used for the text.

#### Outputs
* ##### leg_par
A legend parameter object that can be plugged into any of the