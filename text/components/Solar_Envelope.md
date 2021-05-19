## ![](../../images/icons/Solar_Envelope.png) Solar Envelope - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Solar%20Envelope.py)

![](../../images/components/Solar_Envelope.png)

Generate a solar envelope boundary for a given geometry, set of sun vectors, and

Solar collection envelopes show the height above which one will have solar access

Solar rights envelopes illustrate the volume in which one can build while ensuring



#### Inputs
* ##### geometry [Required]
Rhino Breps and/or Rhino Meshes for which the solar envelope will
* ##### obstacles [Required]
A list of horizontal planar Breps or curves indicating the tops (in the
* ##### vectors [Required]
Sun vectors from the "LB SunPath" component, which determine the
* ##### grid_size [Required]
A positive number in Rhino model units for the size of grid
* ##### height_limit 
A positive number for the minimum distance below (for collections)
* ##### solar_rights 
Set to True to compute a solar rights boundary and False to compute
* ##### run [Required]
Set to "True" to run the component and get a solar envelope. 

#### Outputs
* ##### report
...
* ##### points
The grid of points above the test _geometry representing the height to
* ##### mesh
A mesh representing the solar envelope. For solar collections (the default),