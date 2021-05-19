## ![](../../images/icons/Generate_Point_Grid.png) Generate Point Grid - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Generate%20Point%20Grid.py)

![](../../images/components/Generate_Point_Grid.png)

Genrate a mesh with corresponding test points from a Rhino Brep (or Mesh).

The resulting mesh will be in a format that the "LB Spatial Heatmap" component



#### Inputs
* ##### geometry [Required]
Brep or Mesh from which to generate the points and grid. 
* ##### grid_size [Required]
Number for the size of the test grid. 
* ##### offset_dist 
Number for the distance to move points from the surfaces
* ##### quad_only 
Boolean to note whether meshing should be done using Rhino's
FOR ADVANCED USERS: This input can also be a vector object that will

#### Outputs
* ##### points
Test points at the center of each mesh face.
* ##### vectors
Vectors for the normal direction at each of the points.
* ##### face_areas
Area of each mesh face.
* ##### mesh
Analysis mesh that can be passed to the "LB Spatial Heatmap" component.