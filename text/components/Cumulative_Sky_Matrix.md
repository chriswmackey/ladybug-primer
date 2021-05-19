## ![](../../images/icons/Cumulative_Sky_Matrix.png) Cumulative Sky Matrix - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Cumulative%20Sky%20Matrix.py)

![](../../images/components/Cumulative_Sky_Matrix.png)

Get a matrix containing radiation values from each patch of a sky dome.

Creating this matrix is a necessary pre-step before doing incident radiation

This component uses Radiance's gendaymtx function to calculate the radiation



#### Inputs
* ##### north 
A number between -360 and 360 for the counterclockwise
* ##### location [Required]
A ladybug Location that has been output from the "LB Import EPW"
* ##### direct_rad [Required]
An annual hourly DataCollection of Direct Normal Radiation such
* ##### diffuse_rad [Required]
An annual hourly DataCollection of Diffuse Horizontal Radiation
* ##### hoys 
A number or list of numbers between 0 and 8760 that respresent
* ##### high_density 
A Boolean to indicate whether the higher-density Reinhart
* ##### folder 
The folder in which the Radiance commands are executed to

#### Outputs
* ##### report
...
* ##### sky_mtx
A sky matrix object containing the radiation coming from each patch