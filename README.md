# Rocket-GNC-simulation

MATLAB code on model2.m

Simulink code on simulink_model_n.slxc

Change initial and targeted position at:
```
%target location
LAT_TARGET = 34.6588;
LON_TARGET = -118.769745;
ELEV_TARGET = 10000; %m - MSL

%INITIAL LOCATION
LAT_INIT = 34.2329;
LON_INIT = -119.4573;
ELEV_INIT = 0; %m p- MSL

%OBSTACLE MIDPOINT LOCATION
LAT_OBS = 0;
LON_OBS = 0;
```

Make sure the MATLAB code runs first before the Simulink

Code reference: https://github.com/Vinayak-D/GNCAirstrike/tree/master

Essay reference: https://www.researchgate.net/publication/303256153_Missile_Longitudinal_Autopilots_Connections_Between_Optimal_Control_and_Classical_Topologies

