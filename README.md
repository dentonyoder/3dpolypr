# 3dpolypr

3dpolypr is a lisp routine to produce a profile text file consisting of stations and elevations directly from Civil-3d survey points.
1. Draw a pline from the beginning point to the end point of your alignment.  Use the node snap to select the points.
2. Draw a 3dpoly from the starting point, through all datapoints, to the endpoint.
3. (load "3dpolypr") or drag the program into your drawing to load it.
4. Executing 3dpolypr, select the 3dpoly to get the elevations, select the 2d polyline to get the stationing.  Enter 0 for the starting station or whatever station you want.  Also, in the process you need to identify the output filename...

You can import the generated file in civil-3d through the profile import from file tool.

This tool allows profile creation without requiring a surface model.  I originally wrote it to do a road resurfacing project where we only surveyed the centerline of the road and tape measured the road width.
