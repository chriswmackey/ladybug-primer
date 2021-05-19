## ![](../../images/icons/PMV_Comfort.png) PMV Comfort - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20PMV%20Comfort.py)

![](../../images/components/PMV_Comfort.png)

Calculate Predicted Mean Vote (PMV).

PMV is a thermal comfort model for use on the interior of buildings



#### Inputs
* ##### air_temp [Required]
Data Collection or individual value of air temperature in C. 
* ##### mrt 
Data Collection or individual value of mean radiant temperature
* ##### rel_humid [Required]
Data Collection or individual value of relative humidity in %. 
* ##### air_speed 
Data Collection or individual of air speed values in m/s.
* ##### met_rate 
Data Collection or individual value of metabolic rate in met.
1 met = Metabolic rate of a resting seated person
* ##### clothing 
Data Collection or individual value of clothing insulation in clo.
1 clo = Three-piece suit
* ##### pmv_par 
Optional comfort parameters from the "LB PMV Comfort Parameters"
* ##### run [Required]
Set to True to run the component. 

#### Outputs
* ##### report
Reports, errors, warnings, etc.
* ##### pmv
Predicted Mean Vote (PMV).
* ##### ppd
Percentage of People Dissatisfied (PPD).
* ##### set
Standard Effective Temperature (SET) in Celcius.
* ##### comfort
Integers noting whether the input conditions are acceptable
* ##### condition
Integers noting the thermal status of a subject according to
* ##### heat_loss
A list of 6 terms for heat loss from the human energy
* ##### comf_obj
A Python object containing all inputs and results of the