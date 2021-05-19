## ![](../../images/icons/PMV_Polygon.png) PMV Polygon - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20PMV%20Polygon.py)

![](../../images/components/PMV_Polygon.png)

Draw thermal comfort polygons on a Psychrometric Chart using the PMV model for

This component can also plot passive strategy polygons on the psychrometric chart



#### Inputs
* ##### psych_chart [Required]
A hourly, daily, or sub-hourly data collection of temperature values
* ##### mrt 
A number or list of numbers for the mean radiant temperature. These
* ##### air_speed 
A number or list of numbers for the air speed values in m/s. If None, a
* ##### met_rate 
A number or list of numbers for the metabolic rate in met. If None, a met
* ##### clothing 
A number or list of numbers for the clothing level in clo. If None, a clo
* ##### pmv_par 
Optional PMVParameter object to specify parameters under
* ##### merge_poly 
Boolean to note whether all comfort polygons should be merged
* ##### strategies 
An optional text input of passive strategies to be plot on the
* ##### strategy_par 
Optional passive strategy parameters from the "LB Passive Strategy
* ##### solar_data 
An annual hourly continuous data collection of irradiance

#### Outputs
* ##### report
...
* ##### total_comfort
The percent of the data on the psychrometric chart that
* ##### total_comf_data
Data collection or a 0/1 value noting whether each of the data
* ##### polygon_names
A list of names for each of the polygons. This will include both the
* ##### polygon_comfort
The percent of the input data that are in each of the comfort
* ##### polygon_data
A list of data collections or 0/1 values indicating whether each 
* ##### comfort_poly
Brep representing the range of comfort for the input mrt, air speed,
* ##### strategy_poly
Brep representing the area of the chart made comfortable by any