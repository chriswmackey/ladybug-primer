## ![](../../images/icons/Adaptive_Comfort_Parameters.png) Adaptive Comfort Parameters - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Adaptive%20Comfort%20Parameters.py)

![](../../images/components/Adaptive_Comfort_Parameters.png)

Create a set of parameters that define the acceptable conditions of the

These parameters can be plugged into any of the components that compute



#### Inputs
* ##### ashrae_or_en15251 
A boolean to note whether to use the ASHRAE-55 neutral
* ##### neutral_offset 
The number of degrees Celcius from the neutral temperature
* ##### avgm_or_runmean 
A boolean to note whether the prevailing outdoor
* ##### discr_or_cont_vel 
A boolean to note whether discrete
* ##### cold_prevail_limit 
A number indicating the prevailing outdoor
* ##### conditioning 
A number between 0 and 1 that represents how "conditioned"

#### Outputs
* ##### adapt_par
An Adaptive comfort parameter object that can be plugged into