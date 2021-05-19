## ![](../../images/icons/PMV_Comfort_Parameters.png) PMV Comfort Parameters - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20PMV%20Comfort%20Parameters.py)

![](../../images/components/PMV_Comfort_Parameters.png)

Create a set of parameters that define the acceptable conditions of the

These parameters can be plugged into any of the components that compute



#### Inputs
* ##### ppd_thresh 
A number between 5 and 100 that represents the upper
* ##### hr_upper 
A number between 0 and 1 indicating the upper limit of
* ##### hr_lower 
A number between 0 and 1 indicating the lower limit of
* ##### still_air_thresh 
The air speed threshold in m/s at which the standard

#### Outputs
* ##### pmv_par
A PMV comfort parameter object that can be plugged into