# Legend Parameters

![](../../.gitbook/assets/Legend_Parameters.png)

![](../../.gitbook/assets/Legend_Parameters%20%281%29.png) - [\[source code\]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Legend%20Parameters.py)

Use this component to change the colors, numerical range, and/or number of divisions of any Ladybug legend along with the corresponding colored mesh that the legend refers to.

Any Ladybug component that outputs a colored mesh and a legend will have an input that can accept Legend Parameters from this component.

## Inputs

* **min**

  A number to set the lower boundary of the legend. If None, the minimum of the values associated with the legend will be used. 

* **max**

  A number to set the upper boundary of the legend. If None, the maximum of the values associated with the legend will be used. 

* **seg\_count**

  An interger representing the number of steps between the high and low boundary of the legend. The default is set to 11 and any custom values input in here should always be greater than or equal to 2. 

* **colors**

  An list of color objects. Default is Ladybug's original colorset. 

* **continuous\_leg**

  Boolean. If True, the colors along the legend will be in a continuous gradient. If False, they will be categorized in incremental groups according to the number\_of\_segments. Default is False for depicting discrete categories. 

* **num\_decimals**

  An optional integer to set the number of decimal places for the numbers in the legend text. Default is 2. 

* **larger\_smaller**

  Boolean noting whether to include larger than and smaller than \(&gt; and &lt;\) values after the upper and lower legend segment text. Default is False. 

* **vert\_or\_horiz**

  Boolean. If True, the legend mesh and text points will be generated vertically.  If False, they will genrate a horizontal legend. Default is True for a vertically-oriented legend. 

* **base\_plane**

  A Plane to note the starting point and orientation from where the legend will be genrated. The default is the world XY plane at origin \(0, 0, 0\). 

* **seg\_height**

  An optional number to set the height of each of the legend segments. Default is 1. 

* **seg\_width**

  An optional number to set the width of each of the legend segments. Default is 1 when legend is vertical. When horizontal, the default is \(text\_height \* \(number\_decimal\_places + 2\)\). 

* **text\_height**

  An optional number to set the size of the text in model units. Default is half of the segment\_height. 

* **font**

  An optional text string to specify the font to be used for the text. Examples include "Arial", "Times New Roman", "Courier" \(all without quotations\). Default is "Arial". 

## Outputs

* **leg\_par**

  A legend parameter object that can be plugged into any of the Ladybug components with a legend. 
