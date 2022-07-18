# LCP-Analysis-on-Snake-River-Plain
Least-cost path (LCP) analysis is a common technique for archaeologists to model ancient trade or travel routes. The materials in this repository are from an archaeological study aimed at using geochemically sourced obsidian artifacts as a proxy to model prehistoric mobility on the Snake River Plain (SRP) in southern Idaho. Idaho is an ideal location to perform this type of analysis considering that approximately 105 lithic quarries with 20 geochemically-distinct variations lie on the peripheries of the SRP. 
LCPs are mathematically-generated movement models designed to better simulate travel than Euclidean (straight-line) paths. This study uses Tobler's offpath hiking function to caluclate transport distance (km) for obsidian and approximate time (hours) for obsidian procurement. 
Tobler's offpath hiking function produces reduced time approximations compared to the footpath variation, with base estimations at 3 km and 5 km, respectively. LCPs were generated for both directions of travel (TO and FROM) obsidian sources. 
Altogether, 27 obsidian source were used in this analysis. In addition to the 23 known geochemically distinct obsidian quarries, three obsidian types that were not listed on the initial source sheet were added as well as three subsources ((Coal Bank Springs (Brown's Bench), Reas Pass (Packsaddle), Deadhorse Ridge (Packsaddle)). Additionally, maps were created to visualize the frequency and distribution of geochemically distinct obsidian sources. 
The GIS software used for this analysis was ArcGIS Pro 2.9.3. To create the accumulated cost surface (ACS), a 10-m surface elevation raster and a vertical factor table, revised from Tripcevich's 2009 footpath table, were input into the Distance Accumulation tool in the Distance Toolset introduced in 2020 and the ArcGIS User Conference.
The vertical factor table takes the degree of slope into account for each cell and outputs a time estimation for travel through that cell (at a base rate of 3 km/hr at a 0 degree slope). 
Scripts created in ArcPy for the Distance Accumulation tool are located in this repository for both directions of travel as well as Euclidean (straight-line) distance.
After source and back direction rasters are generated in the Distance Accumulation geoprocessing tool, the Optimal Path as Line geoprocessing tool were used to generate the least-cost paths.
To add additional information to the travel routes, the Add Surface Information geoprocessing tool was used.
The materials in this repository represent the scripts, data compiled, data generated, and maps related to this study. 
For specific information about the materials available in this repository, please refer to the "Directory.xlxs" file. 

Citation: Cota, Talissa D (2022) Title [file name]. https://github.com/Cotatal2/LCP-Analysis-on-Snake-River-Plain/filename.  
Contact email: talissacota@isu.edu 
