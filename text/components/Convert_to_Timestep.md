## ![](../../images/icons/Convert_to_Timestep.png) Convert to Timestep - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Convert%20to%20Timestep.py)

![](../../images/components/Convert_to_Timestep.png)

Convert a hourly Ladybug data collection to a continuous collection at a

This will be done either through linear interpolation or by culling out values



#### Inputs
* ##### data [Required]
A Ladybug Hourly DataCollection object.  This can be either
* ##### timestep 
The timestep to which the data will be converted. If this

#### Outputs
* ##### data
A Continuous DataCollection at the input _timestep_.