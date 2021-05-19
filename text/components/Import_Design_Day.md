## ![](../../images/icons/Import_Design_Day.png) Import Design Day - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Import%20Design%20Day.py)

![](../../images/components/Import_Design_Day.png)

Import hourly climate data from a Ladybug DesignDay object.



#### Inputs
* ##### design_day [Required]
A DesignDay object to import. 

#### Outputs
* ##### location
A Ladybug Location object describing the location of the
* ##### dry_bulb_temperature
The houlry dry bulb temperature over the design
* ##### dew_point_temperature
The hourly dew point temperature over the design
* ##### relative_humidity
The hourly Relative Humidity over the design day
* ##### wind_speed
The hourly wind speed over the design day in m/sec.
* ##### wind_direction
The hourly wind direction over the design day in degrees.
* ##### direct_normal_rad
The hourly Direct Normal Radiation over the design
* ##### diffuse_horizontal_rad
The hourly Diffuse Horizontal Radiation over
* ##### global_horizontal_rad
The hourly Global Horizontal Radiation over the
* ##### horizontal_infrared_rad
The Horizontal Infrared Radiation Intensity
* ##### total_sky_cover
The fraction for total sky cover over the design day
* ##### barometric_pressure
The hourly weather station pressure over the