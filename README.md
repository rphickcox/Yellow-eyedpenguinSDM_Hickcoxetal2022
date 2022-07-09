# Yellow-eyed Penguin SDM_Hickcoxetal2022

**PI:**	Prof. Philip J. Seddon 

**Code author:** Rachel P. Hickcox

**Co-authors:** Dr. Thomas Mattern, Dr. Mariano Rodríguez Recio, Melanie J. Young, Prof. Yolanda Van Heezik

##
---------------------------------------------------------------
**Description**:
This code accompanies the following paper: 

Hickcox, R.P., van Heezik, Y., Mattern, T., Rodríguez Recio, M., Young, M. J., Seddon, P. J. (In review). Staying close to home: marine habitat selection by foraging yellow-eyed penguins using spatial distribution models.

Files are saved to a working directory and subfolders therein. Some data is not provided but may be made available upon request. See the paper for details about the sources of spatial data and for GPS tracking methods, including device and data descriptions. 

The following R Notebooks included in this repository are:
-	**gps_divedata_prep_github**: reads marine tracking for yellow-eyed penguins and cleans, interpolates, and performes several dive and spatial analysis, using the *diveMove* (v1.5.2; Luque, 2007) and *adehabitatLT* package (v3.25; Calenge, 2006), among others.
-**mapping_marine_github**: reads environmental rasters or shapefiles and extracts data to study extent and reprojects to NZTM2000 CRS. 
-**maxent_modelling_github**: reads marine tracking data from **gps_divedata_prep_github** and environmental data from **mapping_marine_github**. Fits Maxent spatial distribution models using the *ENMeval* (v0.3.1; Muscarella et al., 2014) and *dismo* packages (v1.3-3; Hijmans et al., 2020). 
-**maxent_figures_github**: all paper figures and maps
