## ![](../../images/icons/Directional_Solar_Irradiance.png) Directional Solar Irradiance - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Directional%20Solar%20Irradiance.py)

![](../../images/components/Directional_Solar_Irradiance.png)

Compute the hourly solar irradiance or illuminance falling on an unobstructed surface

The calculation method of this component is faster than running "LB Incident



#### Inputs
* ##### location [Required]
A Ladybug Location object, used to determine the altitude and
* ##### direct_norm [Required]
Hourly Data Collection with the direct normal solar
* ##### diffuse_horiz [Required]
Hourly Data Collection with diffuse horizontal solar
* ##### srf_azimuth 
A number between 0 and 360 that represents the azimuth at which
* ##### srf_altitude 
A number between -90 and 90 that represents the altitude at which
* ##### ground_ref 
A number between 0 and 1 that represents the reflectance of the
    *   grass: 0.20
    *   fresh grass: 0.26
    *   soil: 0.17
    *   sand: 0.40
    *   snow: 0.65
    *   fresh_snow: 0.75
    *   asphalt: 0.12
    *   concrete: 0.30
    *   sea: 0.06

* ##### anisotrophic 
A boolean value that sets whether an anisotropic sky is used

#### Outputs
* ##### report
...
* ##### total
A data collection of total solar irradiance or illuminance in the
* ##### direct
A data collection of direct solar irradiance or illuminance in the
* ##### diff
A data collection of diffuse sky solar irradiance or illuminance in
* ##### reflect
A data collection of ground reflected solar irradiance or