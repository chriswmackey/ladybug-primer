## ![](../../images/icons/Create_Legend.png) Create Legend - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Create%20Legend.py)

![](../../images/components/Create_Legend.png)

Create a custom legend for any set of data or range. Creating a legend with this



#### Inputs
* ##### values [Required]
A list of numerical values or data collections that the legend refers
* ##### base_plane 
An optional plane or point to set the location of the
* ##### title 
A text string representing a legend title. Legends are usually
* ##### legend_par 
Optional legend parameters from the  Legend Parameters component. 

#### Outputs
* ##### mesh
A colored mesh for the legend colors.
* ##### title_obj
A text object for the  legend title.
* ##### label_objs
An array of text objects for the label text.
* ##### label_text
An array of text strings for the label text.
* ##### colors
An array of colors that align with the input _values. This can