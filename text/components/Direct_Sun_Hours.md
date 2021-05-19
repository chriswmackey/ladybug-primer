## ![](../../images/icons/Direct_Sun_Hours.png) Direct Sun Hours - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Direct%20Sun%20Hours.py)

![](../../images/components/Direct_Sun_Hours.png)

Calculate the number of hours of direct sunlight received by geometry using sun

Such direct sun calculations can be used for shadow studies of outdoor enviroments

Note that this component uses the CAD environment's ray intersection methods,



#### Inputs
* ##### vectors [Required]
Sun vectors from the "LB SunPath" component, which will be used
* ##### timestep 
A positive integer for the number of timesteps per hour at
* ##### geometry [Required]
Rhino Breps and/or Rhino Meshes for which direct sun analysis
* ##### context 
Rhino Breps and/or Rhino Meshes representing context geometry
* ##### grid_size [Required]
A positive number in Rhino model units for the size of grid
* ##### offset_dist 
A number for the distance to move points from the surfaces
* ##### legend_par 
Optional legend parameters from the "LB Legend Parameters"
* ##### parallel 
Set to "True" to run the study using multiple CPUs. This can
* ##### run [Required]
Set to "True" to run the component and perform direct sun analysis. 

#### Outputs
* ##### report
...
* ##### points
The grid of points on the test _geometry that are be used to perform
* ##### results
A list of numbers that aligns with the points. Each number indicates
* ##### mesh
A colored mesh of the test _geometry representing the hours of direct
* ##### legend
A legend showing the number of hours that correspond to the colors
* ##### title
A text object for the study title.
* ##### int_mtx
A Matrix object that can be connected to the "LB Deconstruct Matrix"