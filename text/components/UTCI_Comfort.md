## ![](../../images/icons/UTCI_Comfort.png) UTCI Comfort - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20UTCI%20Comfort.py)

![](../../images/components/UTCI_Comfort.png)

Calculate Universal Thermal Climate Index (UTCI).

UTCI is a thermal comfort model strictly for the outdoors.

While UTCI is valid in all climates, seasons, and scales, it assumes



#### Inputs
* ##### air_temp [Required]
Data Collection or individual value of air temperature in C. 
* ##### mrt 
Data Collection or individual value of mean radiant temperature
* ##### rel_humid [Required]
Data Collection or individual value of relative humidity in %. 
* ##### wind_vel 
Data Collection or individual of air speed values in m/s.
* ##### run [Required]
Set to True to run the component. 

#### Outputs
* ##### report
Reports, errors, warnings, etc.
* ##### utci
Universal Thermal Climate Index (UTCI) in Celcius.
* ##### comfort
Integers noting whether the input conditions result in no
* ##### condition
Integers noting the thermal status of a subject.
* ##### category
Integers noting the category that the UTCI conditions fall
* ##### comf_obj
A Python object containing all inputs and results of the