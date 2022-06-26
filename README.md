# tunnel-conflict-analysis
Software used: Revit, Dynamo, PowerBI

This is a project created in order to define the conflicts between an old existing Tunnel and a new Tunnel that is needed to be built in it's place.
The script created, has an input of a path and a profile, given those it creates a Volume. After entering a new input in Dynamo the Sweep changes so that it has the least conflicts with the Tunnel.

Afterwards the script creates an Excel file with all the intersection and non-intersection points and the measurements of the distances of the top Level of the two tunnels

In the end a PowerBI dashboard is created combining the 3D Model along with the data created with Dynamo

The dashboard, Dynamo script can be found as a separate file on the repository
