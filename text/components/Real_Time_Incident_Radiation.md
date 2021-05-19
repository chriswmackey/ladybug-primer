## ![](../../images/icons/Real_Time_Incident_Radiation.png) Real Time Incident Radiation - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Real%20Time%20Incident%20Radiation.py)

![](../../images/components/Real_Time_Incident_Radiation.png)

Compute Incident Radiation values for any sky matrix in real time using the Geometry/Sky

Using this component enables one to scroll through radiation on an hour-by-hour

The speed of this component is thanks to the fact that the Geometry/Sky intersection



#### Inputs
* ##### int_mtx [Required]
A Geometry/Sky Intersection Matrix from the "LB Incident Radiation" 
* ##### sky_mtx [Required]
A Sky Matrix from the "LB Cumulative Sky Matrix" component, which

#### Outputs
* ##### results
A list of numbers that aligns with the points of the original analysis