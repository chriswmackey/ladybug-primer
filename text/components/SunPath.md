## ![](../../images/icons/SunPath.png) SunPath - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20SunPath.py)

![](../../images/components/SunPath.png)

Output a Sunpath (aka. sun plot) graphic into the Rhino scene.

The component also outputs sun vectors that can be used for solar access



#### Inputs
* ##### north 
A number between -360 and 360 for the counterclockwise
* ##### location [Required]
A ladybug Location that has been output from the "LB Import EPW"
* ##### hoys 
A number or list of numbers between 0 and 8760 that respresent the
* ##### dl_saving 
An optional analysis period for daylight saving time.
* ##### solar_time 
A boolean to indicate if the input hours should be treated
* ##### center_pt 
A point for the center of the sun path. (Default: (0, 0, 0)) 
* ##### scale 
A number to set the scale of the sun path. The default is 1,
* ##### projection 
Optional text for the name of a projection to use from the sky
    * Stereographic

* ##### daily 
Boolean to note whether the sunpath should display only one daily
* ##### data 
Optional HourlyContinuousCollection objects, which will be used
* ##### statement 
A conditional statement as a string (e.g. a > 25).
* ##### legend_par 
An optional LegendParameter object to change the display

#### Outputs
* ##### report
...
* ##### vectors
Vector(s) indicating the direction of sunlight for each sun
* ##### altitudes
Number(s) indicating the sun altitude(s) in degrees for
* ##### azimuths
Number(s) indicating the sun azimuths in degrees for each
* ##### hoys
The hour of the year for each sun positions on the sun path.
* ##### sun_pts
Point(s) representing the location of the sun on the sunpath.
* ##### analemma
A set of curves that mark the hourly positions of the sun
* ##### daily
A set of arcs that mark the path of the sun across the sky
* ##### compass
A set of circles, lines and text objects that mark the cardinal
* ##### legend
Geometry representing the legend for the input data_. Will be None
* ##### title
A text object for the title of the sunpath.
* ##### color_pts
A list of points colored with the input data_, which will display