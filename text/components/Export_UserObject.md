## ![](../../images/icons/Export_UserObject.png) Export UserObject - [[source code]](https://github.com/ladybug-tools/ladybug-grasshopper/blob/master/ladybug_grasshopper/src//LB%20Export%20UserObject.py)

![](../../images/components/Export_UserObject.png)

Export a Ladybug Tools Grasshopper GHPython component as a UserObject that can



#### Inputs
* ##### components [Required]
A Ladybug Tools GHPython component to be exported. This
* ##### folder [Required]
Full path to folder to copy the updated UserObject and the
* ##### change_type 
One of the values listed below based on the type of
    * release: You are changing the versions for a new release.
Bump the major with 1 and set minor and patch to 0.
    * feat: You have added a new feature. Adding a new feature usually
results in a change in inputs or outputs of the component.
    * perf: You have improved the component for better performance.
Similar to adding a feature you should bump the minor by 1 and
    * fix: You have fixed the code inside the component. It results in
a single bump in patch.
    * docs: You have improved the documentation. No change in version.

    * ignore: This is an exception to the rule and you want the change
type to be ignored. You should use this option only in rare
* ##### export [Required]
Set to True to export the component. 

#### Outputs
* ##### report
Errors, warnings, etc.