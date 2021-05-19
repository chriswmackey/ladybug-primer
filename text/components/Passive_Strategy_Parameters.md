## ![](../../images/icons/Passive_Strategy_Parameters.png) Passive Strategy Parameters - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Passive%20Strategy%20Parameters.py)

![](../../images/components/Passive_Strategy_Parameters.png)

Adjust the assumptions of the passive strategies that can be overalid on the

Thermal Mass + Night Vent - The polygon represents the conditions under which

Occupant Use of Fans - This polygon is made by assuming that an air speed of 1.0 m/s

Capture Internal Heat - The polygon is made by assuming a minimum building balance

Passive Solar Heating - The polygon represents the conditions under which



#### Inputs
* ##### day_above_comf 
A number in degrees Celsius representing the maximum daily
* ##### night_below_comf 
A number in degrees Celsius representing the minimum temperature
* ##### fan_air_speed 
The air speed around the occupants that the fans create in m/s.
* ##### balance_temp 
The balance temperature of the building in Celsius when accounting
* ##### solar_heat_cap 
A number representing the amount of outdoor solar flux (W/m2)
* ##### time_constant 
A number that represents the amount of time in hours that a

#### Outputs
* ##### strategy_par
Passive strategy parameters that can be plugged into the "LB