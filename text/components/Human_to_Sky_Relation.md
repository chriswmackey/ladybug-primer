## ![](../../images/icons/Human_to_Sky_Relation.png) Human to Sky Relation - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Human%20to%20Sky%20Relation.py)

![](../../images/components/Human_to_Sky_Relation.png)

Calculate parameters for the relationship between human geometry and the sky given

The outputs of this component can be plugged into either the "LB Outdoor Solar MRT"



#### Inputs
* ##### north 
A number between -360 and 360 for the counterclockwise
* ##### location [Required]
A ladybug Location that has been output from the "LB Import EPW"
* ##### position [Required]
A point for the position of the human subject in the Rhino scene.
* ##### context [Required]
Rhino Breps and/or Rhino Meshes representing context geometry
* ##### pt_count 
A positive integer for the number of points used to represent
* ##### height 
A number for the the height of the human subject in the current Rhino
* ##### parallel 
Set to "True" to run the study using multiple CPUs. This can
* ##### run [Required]
Set to "True" to run the component and compute the human/sky relationship.

#### Outputs
* ##### report
...
* ##### human_points
The points used to represent the human subject in the calculation
* ##### human_line
Line representing the height of the human subject. Note that this
* ##### fract_body_exp
A data collection for the fraction of the body exposed to
* ##### sky_exposure
A single number between 0 and 1 for the fraction of the sky