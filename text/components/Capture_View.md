## ![](../../images/icons/Capture_View.png) Capture View - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Capture%20View.py)

![](../../images/components/Capture_View.png)

Capture views of the Rhino scene and save them to your hard drive as as a .png files.

This is particularly useful when creating animations and one needs to automate



#### Inputs
* ##### file_name [Required]
The file name, which the image will be saved as. Note that, for
* ##### folder 
The folder into which the image file will be written. This should
Windows - C:/Users/[USERNAME]/ladybug_tools/resources/captured_views/
* ##### viewport 
Text for the Rhino viewport name which will be captured. This can
Perspective
* ##### width 
Integer for the width of the image to be captured in pixels. If None,
* ##### height 
Integer for the height of the image to be captured in pixels. If None,
* ##### mode 
Text for the display mode of the viewport to be captured.If None, the default
Wireframe
* ##### transparent 
Boolean to note whether the captured .png file should have a
* ##### capture [Required]
Set to "True" to capture the image of the Rhino viewport. 

#### Outputs
* ##### file
The file path of the image taken with this component.