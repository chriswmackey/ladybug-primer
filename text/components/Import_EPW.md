## ![](../../images/icons/Import_EPW.png) Import EPW - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Import%20EPW.py)

![](../../images/components/Import_EPW.png)

Import climate data from a standard .epw file.



#### Inputs
* ##### epw_file [Required]
An .epw file path on your system as a string. 

#### Outputs
* ##### location
A Ladybug Location object describing the location data in the
* ##### dry_bulb_temperature
The houlry dry bulb temperature, in C.
* ##### dew_point_temperature
The hourly dew point temperature, in C.
* ##### relative_humidity
The hourly Relative Humidity in percent.
* ##### wind_speed
The hourly wind speed in m/sec.
* ##### wind_direction
The hourly wind direction in degrees.
* ##### direct_normal_rad
The hourly Direct Normal Radiation in Wh/m2.
* ##### diffuse_horizontal_rad
The hourly Diffuse Horizontal Radiation in Wh/m2.
* ##### global_horizontal_rad
The hourly Global Horizontal Radiation in Wh/m2.
* ##### horizontal_infrared_rad
The Horizontal Infrared Radiation Intensity in Wh/m2.
* ##### direct_normal_ill
The hourly Direct Normal Illuminance in lux.
* ##### diffuse_horizontal_ill
The hourly Diffuse Horizontal Illuminance in lux.
* ##### global_horizontal_ill
The hourly Global Horizontal Illuminance in lux.
* ##### total_sky_cover
The fraction for Total Sky Cover  in tenths of coverage.
* ##### barometric_pressure
The hourly weather station pressure in Pa.
* ##### model_year
The year from which the hourly data has been extracted.
* ##### ground_temperature
Monthly ground temperature data if it exists within