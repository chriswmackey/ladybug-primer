## ![](../../images/icons/View_From_Sun.png) View From Sun - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20View%20From%20Sun.py)

![](../../images/components/View_From_Sun.png)

Open a new viewport in Rhino that shows the parallel-projected view from the sun.

This is useful for understanding what parts of Rhino geometry are shaded at a



#### Inputs
* ##### vector [Required]
A sun vector from which the the Rhino view will be generated.
* ##### center_pt 
The target point of the camera for the Rhino view that will be
* ##### width 
An optional interger for the width (in pixels) of the Rhino
* ##### height 
An optional interger for the height (in pixels) of the Rhino
* ##### mode 
An optional text input for the display mode of the Rhino viewport

#### Outputs
* ##### report
...