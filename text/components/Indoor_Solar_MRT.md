## ![](../../images/icons/Indoor_Solar_MRT.png) Indoor Solar MRT - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Indoor%20Solar%20MRT.py)

![](../../images/components/Indoor_Solar_MRT.png)

Calculate Mean Radiant Temperature (MRT) as a result of outdoor shortwave

This component uses the SolarCal model of ASHRAE-55 to estimate the effects



#### Inputs
* ##### location [Required]
A Ladybug Location object, used to determine the altitude and
* ##### longwave_mrt [Required]
A single number or an hourly data collection with the long-wave
* ##### dir_norm_rad [Required]
Hourly Data Collection with the direct normal solar
* ##### diff_horiz_rad [Required]
Hourly Data Collection with diffuse horizontal solar
* ##### fract_body_exp 
A single number between 0 and 1 or a data collection for
* ##### sky_exposure 
A single number between 0 and 1 or a data collection representing
* ##### ground_ref 
A single number between 0 and 1 or a data collection
* ##### window_trans 
A Data Collection or number between 0 and 1 that represents the
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