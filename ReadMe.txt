#### Read Me

This notebook contains code to analyze Sea Surface Temperature Anomalies and Total Column Water Vapor over the Pacific Basin. Through maps users will be able to analyse climate variability in this region.

For this study, ERA 5 data has been fetched through UCAR Thredds Data Server. ERA5 is the fifth generation ECMWF reanalysis for the global climate and weather. It provides hourly estimates for a large number of atmospheric and land-surface variables.

To run this code, the user has rely on several Python libraries such as
xarray for handling multi-dimensional arrays, matplotlib for plotting, cartopy for geographical visualization, and numpy for numerical computations. 

In Part one, the SST and TCWV anomalies were plotted to illustrate the  variability within the Pacific Basin.

In Part two, SST anomalies were calcuated by substracting climatological mean from the observed SST data for each month. Detrending was applied to the SST anomalies to remove any long-term trends by fitting a polynomial function to the data.

In Part three, four and five, EOF analysis was done to  decompose the spatial patterns of SST anomalies into orthogonal modes of variability. 