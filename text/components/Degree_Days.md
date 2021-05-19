## ![](../../images/icons/Degree_Days.png) Degree Days - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Degree%20Days.py)

![](../../images/components/Degree_Days.png)

Calculate humidity metrics from relative humidity, dry bulb temperature and



#### Inputs
* ##### dry_bulb [Required]
A data collection representing outdoor dry bulb temperature [C] 
* ##### heat_base 
A number for the base temperature below which a given hour
* ##### cool_base 
A number for the base temperature above which a given hour

#### Outputs
* ##### hourly_heat
A data collection of heating degree-days.
* ##### hourly_cool
A data collection of cooling degree-days.
* ##### heat_deg_days
A value indicating the total number of heating degree-days
* ##### cool_deg_days
A value indicating the total number of cooling degree-days