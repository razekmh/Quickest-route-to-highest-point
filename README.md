# Quickest route to highest point
Python code to find the quickest route to the highest point within a radius of 5 km circle around the entry point. The Code was built as part of the assessment for the geospatial programming module. 

The code is presented in two Jupyter notebooks as required by the assessment rules. One of the notebooks hold the code [main.ipynb](https://github.com/razekmh/Quickest-route-to-highest-point/blob/master/main.ipynb) while the other serve as interface [interface.ipynb](https://github.com/razekmh/Quickest-route-to-highest-point/blob/master/interface.ipynb). The code was developed and submitted by [@Ibrahim2311 Ibrahim Alhadidi](https://github.com/Ibrahim2311) and myself. 
***

## Initial prompt
The program is deigned to help in a emergency situation where an extreme flood is taking place on the Isle of Wight. To help residents escape the danger the authorities advise that they proceed on foot to the highest point on land within a radius of 5 km. 

The authorities provided the developers with a Digital Elevation Model (DEM) of the island, road network,  Integrated Transport Network (ITN) file and a raster map of the island. 

*** 
## Installation
1. Download the repo.
2. Unzip the [elevation.7z](Quickest-route-to-highest-point/material/elevation/) file inside the [/material/elevation/](https://github.com/razekmh/Quickest-route-to-highest-point/tree/master/material/elevation)
3. Make sure you have the correct dependencies installed
4. Run the [interface.ipynb](https://github.com/razekmh/Quickest-route-to-highest-point/blob/master/interface.ipynb) notebook. 

## Dependencies

The program is using a list of geospatial libraries - listed below -. Some of the libraries are known to have installation issues and conflicts. Please do use a package management system like [anaconda](https://www.anaconda.com/) or use the recommended versions. 

The program was tested using the following versions: 

| Item          | Version       |
| ------------- |:-------------:|
| OS            |Windows 10 64x|
| python        |3.7 64x|
| GDAL          |3.0.2|
| Fiona         |1.8.13|
| pyproj         |2.4.2|
| Shapely       |1.6.4|
| cartopy       |0.17.0|
| geopandas     |0.6.2|
| networkx      |2.4|
| rasterio      |1.1.2|
| rtree         |0.9.3|
| numpy         |1.17.4+mkl|
| scipy         |1.4.1|


