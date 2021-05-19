## ![](../../images/icons/Import_STAT.png) Import STAT - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Import%20STAT.py)

![](../../images/components/Import_STAT.png)

Import data from a standard .stat file.



#### Inputs
* ##### stat_file [Required]
A .stat file path on your system as a string. 

#### Outputs
* ##### location
A Ladybug Location object describing the location data in the STAT file.
* ##### ashrae_zone
The ASHRAE climate zone of the STAT file. Numbers in the zone
* ##### koppen_zone
The Koppen climate zone of the STAT file. The Koppen climate
* ##### clear_dir_norm_rad
The hourly "Clear Sky" Direct Normal Radiation in Wh/m2.
* ##### clear_diff_horiz_rad
The hourly "Clear Sky" Diffuse Horizontal Radiation
* ##### ann_heat_dday_996
A DesignDay object representing the annual 99.6%
* ##### ann_heat_dday_990
A DesignDay object representing the annual 99.0%
* ##### ann_cool_dday_004
A DesignDay object representing the annual 0.4%
* ##### ann_cool_dday_010
A DesignDay object representing the annual 1.0%
* ##### monthly_ddays_050
A list of 12 DesignDay objects representing monthly
* ##### monthly_ddays_100
A list of 12 DesignDay objects representing monthly
* ##### extreme_cold_week
A Ladybug AnalysisPeriod object representing the
* ##### extreme_hot_week
A Ladybug AnalysisPeriod object representing the
* ##### typical_weeks
A list of Ladybug AnalysisPeriod objects representing