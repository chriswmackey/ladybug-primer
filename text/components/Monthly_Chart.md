## ![](../../images/icons/Monthly_Chart.png) Monthly Chart - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Monthly%20Chart.py)

![](../../images/components/Monthly_Chart.png)

Create a chart in the Rhino scene with data organized by month.

Data will display as a bar chart if the input data is monthly or daily. If the



#### Inputs
* ##### data [Required]
Data collections (eg. HourlyCollection, MonthlyCollection, or
* ##### base_pt 
An optional Point3D to be used as a starting point to generate
* ##### x_dim 
An optional number to set the X dimension of each month of the
* ##### y_dim 
An optional number to set the Y dimension of the entire
* ##### stack 
Boolean to note whether multiple connected monthly or daily input
* ##### percentile 
An optional number between 0 and 50 to be used for the percentile
* ##### global_title 
A text string to label the entire entire chart.  It will be
* ##### y_axis_title 
A text string to label the Y-axis of the chart.  This can
* ##### legend_par 
An optional LegendParameter object to change the display

#### Outputs
* ##### report
...
* ##### data_mesh
A list of colored meshes that represent the different input data.
* ##### data_lines
A list of polylines that represent the input data. These will
* ##### col_lines
A list of colored polylines that represent the input data. These
* ##### legend
Geometry representing the legend for the chart, noting which
* ##### borders
A list of lines and polylines representing the axes and intervals
* ##### labels
A list of text objects that label the borders with month name
* ##### y_title
A text oject for the Y-axis title.
* ##### title
A text object for the global_title.