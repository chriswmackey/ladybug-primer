## ![](../../images/icons/Psychrometric_Chart.png) Psychrometric Chart - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Psychrometric%20Chart.py)

![](../../images/components/Psychrometric_Chart.png)

Draw a psychrometric chart in the Rhino scene and plot a set of temperatures and

Connected data can be either outdoor temperature and humidty from imported EPW



#### Inputs
* ##### temperature [Required]
A hourly, daily, or sub-hourly data collection of temperature values
* ##### rel_humidity [Required]
A hourly, daily, or sub-hourly data collection of relative humidity
* ##### pressure 
A data collection of atmospheric pressure in Pascals or a single
* ##### base_pt 
A point to be used as the bottom-left-most point from which all
* ##### scale 
A number to set the dimensions of the chart. (Default: 1). 
* ##### temp_range 
An optional domain (or number for the upper temperature), which
* ##### plot_wet_bulb 
Boolean to note whether the psychrometric chart should be ploted
* ##### legend_par 
An optional LegendParameter object from the "LB Legend Parameters"
* ##### data 
Optional data collections, which are aligned with the input _temperature
* ##### statement 
A conditional statement as a string (e.g. a > 25).
* ##### period 
A Ladybug analysis period to be applied to the _temperature and

#### Outputs
* ##### report
...
* ##### title
Text objects for the chart title and axes titles as well as a polyline for
* ##### temp_lines
A list of line segments and text objects for the temperature labels
* ##### rh_lines
A list of curves and text objects for the relative humidity labels
* ##### hr_lines
A list of line segments and text objects for the humidty ratio labels
* ##### enth_wb_lines
A list of line segments and text objects for the enthalpy or
* ##### mesh
A colored mesh showing the number of input hours that happen in each part
* ##### legend
A colored legend showing the number of hours that correspond to
* ##### points
Points representing each of the input temperature and humidity values.
* ##### data
The input data_ with the input statements or the periods applied to it.
* ##### psych_chart
A Psychrometric Chart object, which can be connected to any