## ![](../../images/icons/Analysis_Period.png) Analysis Period - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Analysis%20Period.py)

![](../../images/components/Analysis_Period.png)

Create an Analysis Period to describe a slice of time during the year.



#### Inputs
* ##### start_month 
Start month (1-12). 
* ##### start_day 
Start day (1-31). 
* ##### start_hour 
Start hour (0-23). 
* ##### end_month 
End month (1-12). 
* ##### end_day 
End day (1-31). 
* ##### end_hour 
End hour (0-23). 
* ##### timestep 
An integer number for the number of time steps per hours.

#### Outputs
* ##### period
Analysis period.
* ##### hoys
List of dates in this analysis period.
* ##### dates
List of hours of the year in this analysis period.