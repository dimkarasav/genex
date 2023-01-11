

These files are just to present the requested format for the data. All data values are random and are just for visualization purposes.


1) Damage_simulations.csv

This file provides the information of each simulation run. One such file is expected since each row corresponds to one simulation run.

2) Sensor_locations.csv

This file contains the coordinates (locations) of the piezoelectric sensors. In this dummy dataset 12 sensors have been assumed - feel free to change that according to the finalized number of sensors.

3) Time_series folder.

Here the time series outputs of the sensors are saved. For each simulation one .csv is expected. The total number of files expected in this folder is equal to the rows of the Damage_simulations.csv.
The names of the files should be clear enough to understand to which row of the Damage_simulations.csv they correspond.


Note: In this dummy dataset i have assumed that we have 3 coordinates for the location of the sensors, the location and the oriantation of the damage. Feel free to change it according to the final geometry that would be simulated (3D, planar, etc.)