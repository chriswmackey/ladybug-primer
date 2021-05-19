## ![](../../images/icons/Wind_Rose.png) Wind Rose - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Wind%20Rose.py)

![](../../images/components/Wind_Rose.png)

Create a plot of any hourly data by wind directions.



#### Inputs
* ##### north 
An optional number between -360 and 360 for the counterclockwise
* ##### data [Required]
A HourlyContinuousCollection or HourlyDiscontinuousCollection of
* ##### wind_direction [Required]
A HourlyContinuousCollection or HourlyDiscontinuousCollection
* ##### dir_count 
Number that determines the number of directions to the wind rose
* ##### center_pt 
Point3D to be used as a starting point to generate the geometry of
* ##### show_calmrose 
A boolean to indicate if the wind rose displays a calm rose. The
* ##### show_freq 
A boolean to show the frequency of _data data values in the
* ##### freq_dist 
The distance for the frequency interval in model units. If 
* ##### freq_hours 
The number of hours in each frequency interval (Default: 50). 
* ##### max_freq_lines 
A number representing the maximum frequency intervals in
* ##### legend_par 
An optional LegendParameter object to change the display of the
* ##### statement 
A conditional statement as a string (e.g. a > 25) for
* ##### period 
An optional Ladybug analysis period to be applied to all of

#### Outputs
* ##### report
...
* ##### mesh
A colored mesh representing the wind rose derived from the input data.
* ##### compass
A set of circles, lines and text objects that mark the cardinal
* ##### orient_line
Line geometries representing the edges (or "spokes") of the wind
* ##### freq_line
Polygon geometries representing the frequency intervals of the wind
* ##### windrose_line
Polygon geometries representing the windrose outlines. This
* ##### legend
Geometry representing the legend for the wind rose.
* ##### title
A text object for the global_title.
* ##### prevailing
The predominant direction of the outpt wind rose in clockwise
* ##### angles
A list of angles corresponding to each windrose directions.
* ##### calm_hours
The number of hours with calm wind speeds. Only returns a value if the input 
* ##### histogram
The input _data in a histogram structure after it has gone through any of 