## ![](../../images/icons/Apply_Conditional_Statement.png) Apply Conditional Statement - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Apply%20Conditional%20Statement.py)

![](../../images/components/Apply_Conditional_Statement.png)

Convert a hourly Ladybug data collection to a continuous collection at a

This will be done either through linear interpolation or by culling out values



#### Inputs
* ##### data [Required]
A list of aligned Data Collections to be evaluated against
* ##### statement [Required]
A conditional statement as a string (e.g. a > 25).
The variable of the first data collection should always be named 'a'
For example, if three data collections are connected to _data

#### Outputs
* ##### data
A list of Data Collections that have been filtered by the statement_.