## ![](../../images/icons/Sky_Mask.png) Sky Mask - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Sky%20Mask.py)

![](../../images/components/Sky_Mask.png)

Visualize the portion of the sky dome that is masked by context geometry or shading

Separate meshs will be generated for the portions of the sky dome that are masked



#### Inputs
* ##### context 
Rhino Breps and/or Rhino Meshes representing context geometry that
* ##### orientation 
A number between 0 and 360 that sets the direction of a vertically-
* ##### overhang_proj 
A number between 0 and 90 that sets the angle between the _center_
* ##### left_fin_proj 
A number between 0 and 180 that sets the angle between the _center_
* ##### right_fin_proj 
A number between 0 and 180 that sets the angle between the _center_
* ##### density 
An integer that is greater than or equal to 1, which to sets the
* ##### center 
A point or plane for which the visible portion of the sky will
* ##### scale 
A number to set the scale of the sky mask. The default is 1,
* ##### projection 
Optional text for the name of a projection to use from the sky
    * Stereographic


#### Outputs
* ##### report
...
* ##### context_mask
A mesh for the portion of the sky dome masked by the context_
* ##### orient_mask
A mesh for the portion of the sky dome that is not visible from
* ##### strategy_mask
A mesh of the portion of the sky dome masked by the overhang,
* ##### sky_mask
A mesh of the portion of the sky dome visible by the _center_
* ##### context_view
The percentage of the sky dome masked by the context_ geometry.
* ##### orient_view
The percentage of the sky dome that is not visible from a
* ##### strategy_view
The percentage of the sky dome viewed by the overhang, left
* ##### sky_view
The percentage of the sky dome visible by the _center_ through