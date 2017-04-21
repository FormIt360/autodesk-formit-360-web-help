# Work Planes
 

When you change the world axes in the main sketch, or local axes inside a group, a work plane is associated with the X and Y axes. 

A work plane is a virtual 2-dimensional surface used as a base plane for sketching elements. This work plane stretches out to infinity and provides a surface to sketch on without snapping to elements behind/below it.

## Modifying Work Planes

The world axes and and Group axes have default work plane orientations along the default XY plane.

You may change the work plane orientation in the Main Sketch or in a Group by right-clicking on the canvas, and selecting Set Axes: ![](Images/GUID-D035D02F-480D-44A2-AE80-4B4FBF3A6117-low.png)

![](Images/GUID-35918BD8-0867-423B-A6E6-A4960F6D6DD8-low.png)


Grab the dot at the end of the red axis, and align it to a surface of another object in the sketch. 

![](Images/rotate-workplane-1.png)

This will align the active work plane (whether in a Group or in the Main Sketch) to correspond to this face. You can now sketch, place elements, and modify elements relative to the new XY plane, rather than the default ground plane. 

![](Images/rotate-workplane-2.png)

You can orbit behind or under the grid and work planes to snap and inference to elements behind it.

If you do not see the grid lines, you'll need to turn on the Grid in [Visual Styles](../Visualizing Your Design/Visual Styles.md) > Environment > Grid (or keyboard shortcut: DG)
