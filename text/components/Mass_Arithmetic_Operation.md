## ![](../../images/icons/Mass_Arithmetic_Operation.png) Mass Arithmetic Operation - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Mass%20Arithmetic%20Operation.py)

![](../../images/components/Mass_Arithmetic_Operation.png)

Perform a "mass" arithmetic operation between Data Collections. For example,

Note that Data Collections must be aligned in order for this component to run

Using this component will often be much faster and more elegant compared to



#### Inputs
* ##### data [Required]
A list of Data Collections to be used in the arithmetic operation. 
* ##### operator 
Text for the operator to use between the Data Collections.
* ##### type 
Optional text for a new "type" key in the Data Collection's metadata.

#### Outputs
* ##### data
A Ladybug data collection object derived from the operation between