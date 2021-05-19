## ![](../../images/icons/Solar_MRT_from_Solar_Components.png) Solar MRT from Solar Components - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Solar%20MRT%20from%20Solar%20Components.py)

![](../../images/components/Solar_MRT_from_Solar_Components.png)

Calculate Mean Radiant Temperature (MRT) as a result of shortwave solar using

This component uses the SolarCal model of ASHRAE-55 to estimate the effects



#### Inputs
* ##### location [Required]
A Ladybug Location object. 
* ##### longwave_mrt [Required]
A single number or an hourly data collection with the long-wave
* ##### dir_horiz_rad [Required]
Hourly Data Collection with the direct horizontal solar
* ##### diff_horiz_rad [Required]
Hourly Data Collection with diffuse horizontal solar
* ##### fract_body_exp 
A single number between 0 and 1 or a data collection
* ##### ground_ref 
A single number between 0 and 1 or a data collection
* ##### solar_body_par 
Optional solar body parameters from the "LB Solar Body Parameters"
* ##### run [Required]
Set to True to run the component. 

#### Outputs
* ##### report
Reports, errors, warnings, etc.
* ##### erf
Data collection of effective radiant field (ERF) in W/m2.
* ##### dmrt
Data collection of mean radiant temperature delta in C.
* ##### mrt
Data collection of mean radiant temperature in C.