# NO2
Repository of processed data used in manuscript entitled
"Population size and centrality effects on NO2 air pollution across and within European cities"
submitted for publication
by Yufei Wei, Rémi Lemoy and Geoffrey Caruso.

The processed data from which regressions and graphics were made is available in the form of two csv files:
WeiCarusoLemoy_G_NO2.csv for ground based NO2 concentrations
WeiCarusoLemoy_C_NO2.csv for TROPOMI based NO2 concentrations

Variables in WeiCarusoLemoy_G_NO2.csv:

"FUAId" and "FUAName" id of urban areas (based on GHSL FUA eFUA_ID and eFUA_name);
"StationX" and "StationY" coordinates of monitoring station;                  
"NO2AveGround" NO2 concentration (year daily average, in micro g per cubic m);
"Dist" distance to main centre (town hall (in house dataset assembled by Lemoy Caruso and Kilgarriff));
"Pop2015" population size (based on GHSL FUA);
"CBDX" and "CBDY" coordinates of main centre;
"StationBackgrd" type of station background NO2 (categories: Background" (mixed reference), Traffic or Industrial)

Variables in WeiCarusoLemoy_C_NO2.csv:

"FUAId" and "FUAName" id of urban areas (based on GHSL FUA eFUA_ID and eFUA_name);
"CellX" and "CellY" coordinates of cells;                  
"NO2AveSatellite" NO2 concentration (year daily average, in micro moles per sq m);
"Dist" distance to main centre (town hall (in house dataset assembled by Lemoy Caruso and Kilgarriff));
"Pop2015" population size (based on GHSL FUA);
"CBDX" and "CBDY" coordinates of main centre;
"Cmin" background NO2 (min of NO2AveSatellite for each city)
