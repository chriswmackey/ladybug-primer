## ![](../../images/icons/Area_Normalize.png) Area Normalize - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Area%20Normalize.py)

![](../../images/components/Area_Normalize.png)

Get a Data Collection that is normalized by an area value.

Note that this component will raise a ValueError if the data type in the header



#### Inputs
* ##### data [Required]
A Data Collection to be normalized by the input _area. 
* ##### area [Required]
Script variable Python 
* ##### unit 
Text for the units that the area value is in. Acceptable inputs include

#### Outputs
* ##### data
A Ladybug data collection object derived from the operation between