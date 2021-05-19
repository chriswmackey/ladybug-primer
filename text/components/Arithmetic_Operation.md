## ![](../../images/icons/Arithmetic_Operation.png) Arithmetic Operation - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Arithmetic%20Operation.py)

![](../../images/components/Arithmetic_Operation.png)

Perform simple arithmetic operations between Data Collections. For example,

Note that Data Collections must be aligned in order for this component to run

Using this component will often be much faster and more elegant compared to



#### Inputs
* ##### data_1 [Required]
The first Data Collection in the operation. If the operator is
* ##### data_2 [Required]
The second Data Collection in the operation. If the operator is
* ##### operator 
Text for the operator to use between the two Data Collections.
* ##### type 
Optional text for a new "type" key in the Data Collection's metadata.

#### Outputs
* ##### data
A Ladybug data collection object derived from the operation between