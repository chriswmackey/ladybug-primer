## ![](../../images/icons/Time_Interval_Operation.png) Time Interval Operation - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Time%20Interval%20Operation.py)

![](../../images/components/Time_Interval_Operation.png)

Perform time interval operations on an hourly data collection.

This includes operations like:

These actions can be performed over the following time intervals:



#### Inputs
* ##### data [Required]
A Ladybug data collection object. 
* ##### operation 
Text indicating the operation that should be performed on
Such text must be one of the following:
    - total
    - [a number between 0 and 100]

In the case of the last option, the number will be interpreted as
Default is 'average' if the input data type is not cumulative and

#### Outputs
* ##### daily
Daily data collection derived from the input _data and _operation_.
* ##### monthly
Monthly data collection derived from the input _data and _operation_.
* ##### mon_per_hr
Monthly Per Hour data collection derived from the input