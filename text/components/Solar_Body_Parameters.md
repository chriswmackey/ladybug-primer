## ![](../../images/icons/Solar_Body_Parameters.png) Solar Body Parameters - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Solar%20Body%20Parameters.py)

![](../../images/components/Solar_Body_Parameters.png)

Create a set of parameters that define the characteristics of a human

These parameters can be plugged into any of the components that estimate



#### Inputs
* ##### posture 
A text string indicating the posture of the body. Letters must
    - seated
    - supine
Default is "standing". 
* ##### sharp 
A number between 0 and 180 representing the solar horizontal
* ##### body_az 
A number between 0 and 360 representing the direction that
* ##### absorptivity 
A number between 0 and 1 representing the average
* ##### emissivity 
A number between 0 and 1 representing the average

#### Outputs
* ##### sol_body_par
A solar body parameter object that can be plugged into