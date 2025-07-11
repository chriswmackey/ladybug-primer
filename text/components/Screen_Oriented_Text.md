## Screen Oriented Text

![](../../images/components/Screen_Oriented_Text.png)

![](../../images/icons/Screen_Oriented_Text.png) - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Screen%20Oriented%20Text.py)


Generate screen-oriented text that displays in the Rhino scene as a head-up display (HUD). 

This is useful when there are certain summary results or information that should always be displayed on-screen. 



#### Inputs
* ##### text [Required]
Text string to be displayed in the plane of the screen. 
* ##### leg_par2d 
Optional 2D LegendParameters from the "LB Legend Parameters 2D" component, which will be used to customize a text in the plane of the screen. Note that only the text_height, origin_x and origin_y inputs of this component affect the placement of the text. 
* ##### font 
An optional text string to specify the font to be used for the text. Examples include "Arial", "Times New Roman", "Courier" (all without quotations). Default is "Arial". 
* ##### color 
An optional color to set the color of the text. If unspecified, it will be black. 
* ##### viewport 
Text for the name of the Rhino viewport to which the 2D screen-oriented legend will be rendered. If unspecified, the 2D legend will be rendered in all viewports. Acceptable inputs include: 
Perspective Top Bottom Left Right Front Back any view name that has been saved within the Rhino file 

#### Outputs