# LCP-Analysis-on-Snake-River-Plain
These materials were created for an archaeological study aimed at using geochemically sourced obsidian artifacts as a proxy to model prehistoric mobility on the Snake River Plain. The GIS software used was ArcGIS Pro 2.9.2. 
A vertical factor table representative of Tobler's offpath hiking function was created. The hiking function outputs estimations for travel time (on foot) at a base rate of 3 km/hr and reaching a maximum of 3.6 km/hr between a -5 and -7 degree slope. 
Scripts compatible in ArcGIS Pro software were used to create the straight-line distance and cost surfaces for all obsidian sources in Idaho. 
The scripts were used to create Euclidean distance rasters and accumulated cost surface rasters to generate least-cost paths and for the shortest distance.
The Distance Accumulation geoprocessing tool was used to create all rasters. For straight-line distance, the input source and surface raster were the only variables used. To generate the least-cost paths, the vertical factor parameter table was applied in addition to a specification of the travel direction. 
After the distance and back direction rasters are generated in the Distance Accumulation geoprocessing tool, the Optimal Path as Line geoprocessing tool were used to generate the least-cost paths.
To add additional information to the travel routes, the Add Surface Information geoprocessing tool was used.
This project contains resources and results of the study.
For information about the materials available from this study, please refer to the "Directory.xlxs" file. 
