# indoor_light_conditions
Provides measurements of light conditions at different locations and times during 24-hour periods. Measurements include light intensity, limited spectral aspects (IR, R, G, B), ambient temperature, and short circuit current of two indoor PV panels.

Data is provided in two formats:
- csv files for each 24-hour period (in /csv folder)
- collection of all light conditions in MATLAB .mat file (one table per light condition)

Each row in the data files represents one sample. Samples are timestamped (first column). Header description for each column is provided.

The data is collected with the customized sensor node described in:
>S. Bader et al., "Distributed Measurement of Light Conditions for Indoor Photovoltaic Applications", in Proc. of IEEE Sensors, 2020.

More information on the different light conditions can be found in:
>X. Ma et al., "Estimating Harvestable Energy in Time-Varying Indoor Light Conditions", in 8th International Workshop on Energy Harvesting & Energy-Neutral Sensing Systems (ENSsys'20), 2020.
