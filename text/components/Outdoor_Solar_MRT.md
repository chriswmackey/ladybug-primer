## ![](../../images/icons/Outdoor_Solar_MRT.png) Outdoor Solar MRT - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Outdoor%20Solar%20MRT.py)

![](../../images/components/Outdoor_Solar_MRT.png)

Calculate Mean Radiant Temperature (MRT) as a result of outdoor shortwave

This component uses the SolarCal model of ASHRAE-55 to estimate the effects



#### Inputs
* ##### location [Required]
A Ladybug Location object, used to determine the altitude and
* ##### surface_temp [Required]
A single number or an hourly data collection with the temperature
* ##### dir_norm_rad [Required]
Hourly Data Collection with the direct normal solar
* ##### diff_horiz_rad [Required]
Hourly Data Collection with diffuse horizontal solar
* ##### horiz_infrared [Required]
Hourly Data Collection with the horizontal infrared
* ##### fract_body_exp 
A single number between 0 and 1 or a data collection for
* ##### sky_exposure 
A single number between 0 and 1 or a data collection representing
* ##### ground_ref 
A single number between 0 and 1 or a data collection
* ##### solar_body_par 
Optional solar body parameters from the "LB Solar Body Parameters"
* ##### run [Required]
Set to True to run the component. 

#### Outputs
* ##### report
Reports, errors, warnings, etc.
* ##### short_erf
Data collection of shortwave effective radiant field (ERF) in W/m2.
* ##### long_erf
Data collection of longwave effective radiant field (ERF) in W/m2.
* ##### short_dmrt
Data collection of shortwave mean radiant temperature delta in C.
* ##### long_dmrt
Data collection of longwave mean radiant temperature delta in C.
* ##### mrt
Data collection of mean radiant temperature in C.  This accounts for