TO SETUP TELEOPERATION:

Change IP address of server in config.txt

Run program. 


Some parameters can be changed in the program's code. Just open the file AnchoredSpringForce.vcproj. The parameters are:

Spring stiffness
Damping coefficient
Spring force and Sensor force weights (in case sensors are being used)
Freedom/Collision threshold
Weight of the stylus and/or attached shaft (for gravity compensation)

They are constants defined and precisely commented in the first lines of the code file masterslave.cpp. 
Their values can be changed as needed. After making changes, recompile the code and run.

The flow control implementation can also be changed by manipulating the literal on line 394
