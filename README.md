# Dataset

As part of a research project on the optimal configuration of heterogeneous Multistatic Sonar Networks (MSNs), we provide here a dataset of 100 instances that were derived from 4 DEMs with different topology (see *Visualisations* section). 

A Digital Elevation Model (DEM) is a representation of the topography of a given Area of Interest (AoI) using bathymetrics and/or altimetrics data. More precisely, these DEMs are based on elevation data made available by GEBCO [1] and which were subsequently preprocessed (see *Pre-processing* section) in order to down-sample the grids. This down-sampling was done so that they could be handled by exact resolution methods detailed in the related paper.

For each DEM, we thus have proposed 25 instances with a different distribution for the 3 types of acoustic buoys (sonobuoys): transmitter-only (Tx), receiver-only (Rx) and transmitter-receiver (TxRx). These instances are detailed in the corresponding section. For completeness, the inter-sensor performance table is also rewritten here.

## Format

The various DEMs are delivered in **Esri ASCII** format with a certain amount of metadata in the header and the elevations in raster form. A didactic example displaying the structure of this specific format on a 10x10 grid is shown below:

```
ncols        10  
nrows        10  
xllcorner    -9.012500000000  
yllcorner    36.995833333333  
cellsize     0.004166666667  
NODATA_value -32767  
 -44 -41 -43 23 69 26 45 59 61 54  
 -41 -41 -40 42 69 7 51 60 59 52  
 -45 -41 4 47 68 51 47 -269 34 39  
 -47 -41 8 25 39 40 39 -188 -207 -151  
 -48 1 4 2 -36 -47 -67 -74 -15 -13  
 3 5 -37 -31 -25 -20 -19 -35 -18 -17  
 2 1 -37 -32 -28 -24 -22 -21 -21 33  
 -53 -47 -40 -35 -32 -29 -26 -24 36 78  
 -52 -45 -41 -37 -34 -31 -29 -27 17 71  
 -48 -46 -43 -39 -35 -33 -31 -29 -27 37  
```

Where *xllcorner* and *yllcorner* correspond respectively to the longitude and latitude of the lower left corner of the considered grid and *cellsize* corresponds to 15 arc-seconds in degrees.

## Pre-processing

## Visualisations of the DEMs (grids)

## Instances
