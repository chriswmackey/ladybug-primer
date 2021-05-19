## ![](../../images/icons/Adaptive_Comfort.png) Adaptive Comfort - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Adaptive%20Comfort.py)

![](../../images/components/Adaptive_Comfort.png)

Calculate Adaptive thermal comfort.

The Adaptive thermal comfort model is for use on the interior of buildings where

Note that, for fully conditioned buildings, the PMV thermal comfort model should



#### Inputs
* ##### out_temp [Required]
Outdoor temperatures in one of the following formats:
1 - A Data Collection of prevailing outdoor temperature values in C.
* ##### air_temp [Required]
Data Collection or individual value of air temperature in C. 
* ##### mrt 
Data Collection or individual value of mean radiant temperature
* ##### air_speed 
Data Collection or individual of air speed value in m/s.
* ##### adapt_par 
Optional comfort parameters from the "LB Adaptive Comfort Parameters"
* ##### run [Required]
Set to True to run the component. 

#### Outputs
* ##### report
Reports, errors, warnings, etc.
* ##### prevail_temp
Data Collection of prevailing outdoor temperature in
* ##### neutral_temp
Data Collection of the desired neutral temperature in
* ##### deg_neutral
Data Collection of the degrees from desired neutral
* ##### comfort
Integers noting whether the input conditions are acceptable
* ##### condition
Integers noting the thermal status of a subject according to
* ##### comf_obj
A Python object containing all inputs and results of the