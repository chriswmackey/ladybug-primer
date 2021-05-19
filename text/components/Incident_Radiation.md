## ![](../../images/icons/Incident_Radiation.png) Incident Radiation - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Incident%20Radiation.py)

![](../../images/components/Incident_Radiation.png)

Calculate the incident radiation on geometry using a sky matrix from the "Cumulative

Such studies of incident radiation can be used to apprxomiate the energy that can

Note that NO REFLECTIONS OF SOLAR ENERGY ARE INCLUDED IN THE ANALYSIS



#### Inputs
* ##### sky_mtx [Required]
A Sky Matrix from the "LB Cumulative Sky Matrix" component, which
* ##### geometry [Required]
Rhino Breps and/or Rhino Meshes for which incident radiation analysis
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
Set to "True" to run the component and perform incident radiation

#### Outputs
* ##### report
...
* ##### points
The grid of points on the test _geometry that are be used to perform
* ##### results
A list of numbers that aligns with the points. Each number indicates
* ##### total
A number for the total incident solar energy falling on all input geometry
* ##### mesh
A colored mesh of the test _geometry representing the cumulative
* ##### legend
A legend showing the kWh/m2 that correspond to the colors of the mesh.
* ##### title
A text object for the study title.
* ##### int_mtx
A Matrix object that can be connected to the "LB Deconstruct Matrix"