# Adaptive Comfort Parameters

![](../../.gitbook/assets/Adaptive_Comfort_Parameters.png)

![](../../.gitbook/assets/Adaptive_Comfort_Parameters%20%281%29.png) - [\[source code\]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Adaptive%20Comfort%20Parameters.py)

Create a set of parameters that define the acceptable conditions of the Adaptive thermal comfort model.

These parameters can be plugged into any of the components that compute Adaptive thermal comfort.

## Inputs

* **ashrae\_or\_en15251**

  A boolean to note whether to use the ASHRAE-55 neutral temperature function \(True\) or the EN-15251 function \(False\). Note that this input will also determine default values for many of the other properties of this object. 

* **neutral\_offset**

  The number of degrees Celcius from the neutral temperature where the input operative temperature is considered acceptable. The default is 2.5C when the neutral temperature function is ASHRAE-55 and 3C when the neutral temperature function is EN-15251. You may want to use the set\_neutral\_offset\_from\_ppd\(\) or the set\_neutral\_offset\_from\_comfort\_class\(\) methods on this object to set this value using ppd from the ASHRAE-55 standard or comfort classes from the EN-15251 standard respectively. 

* **avgm\_or\_runmean**

  A boolean to note whether the prevailing outdoor temperature is computed from the average monthly temperature \(True\) or a weighted running mean of the last week \(False\).  The default is True when the neutral temperature function is ASHRAE-55 and False when the neutral temperature function is EN-15251. 

* **discr\_or\_cont\_vel**

  A boolean to note whether discrete categories should be used to assess the effect of elevated air speed \(True\) or whether a continuous function should be used \(False\). The default is True when the neutral temperature function is ASHRAE-55 and False when the neutral temperature function is EN-15251. 

* **cold\_prevail\_limit**

  A number indicating the prevailing outdoor temperature below which acceptable indoor operative temperatures flatline. The default is 10C when the neutral temperature function is ASHRAE-55 and 15C when the neutral temperature function is EN-15251. This number cannot be greater than 22C and cannot be less than 10C. 

* **conditioning**

  A number between 0 and 1 that represents how "conditioned" vs. "free-running" the building is. 0 = free-running \(completely passive with no air conditioning\) 1 = conditioned \(no operable windows and fully air conditioned\) The default is 0 since both the ASHRAE-55 and EN-15251 standards prohibit the use of adaptive comfort methods when a heating/cooling system is active. When set to a non-zero number, a neutral temperature function for heated/cooled operation derived from the SCATs database will be used. For more information on how adaptive comfort methods can be applied to conditioned buildings, see the neutral\_temperature\_conditioned function in the ladybug\_comfort documentation. 

## Outputs

* **adapt\_par**

  An Adaptive comfort parameter object that can be plugged into any of the components that compute Adaptive thermal comfort. 
