## ![](../../images/icons/Legend_Parameters.png) Legend Parameters - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Legend%20Parameters.py)

![](../../images/components/Legend_Parameters.png)

Use this component to change the colors, numerical range, and/or number of divisions

Any Ladybug component that outputs a colored mesh and a legend will have an input



#### Inputs
* ##### min 
A number to set the lower boundary of the legend. If None, the
* ##### max 
A number to set the upper boundary of the legend. If None, the
* ##### seg_count 
An interger representing the number of steps between
* ##### colors 
An list of color objects. Default is Ladybug's original colorset. 
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