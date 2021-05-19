## ![](../../images/icons/EPW_to_DDY.png) EPW to DDY - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20EPW%20to%20DDY.py)

![](../../images/components/EPW_to_DDY.png)

Produce a DDY file with a heating and a cooling design day from an EPW.

This method will first check if there is any heating or cooling design day information

Information on the uncertainty introduced by using only one year of data to create



#### Inputs
* ##### epw_file [Required]
An .epw file path on your system, from which a .ddy will
* ##### percentile 
A number between 0 and 50 for the percentile difference
* ##### folder 
An optional file path to a directory into which the DDY file
* ##### write [Required]
Set to "True" to write the .ddy file. 

#### Outputs
* ##### ddy_file
A .ddy file path that has been written to your system.