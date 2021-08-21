# Agri-Tech-USGS-LIDAR
# Introduction
AgriTech desire to know the water flow in the maize farm which influence their health and harvest. Therefore, the topography of the farm is cricial to tell the wetness of different parts of the farm.
# Data
Data for data science and machine learning come in different formats depending on its nature, area of focus and where to be applied. In the case of our project, the data is complex because it is a geographical data because the main focus is to find the flow of water in the farm that influences healthy maize plants and ultimately the harvest. Therefore, with the availability of a high resolution elevation data released by USGS as a lidar point cloud, the data is available in a public dataset on Amazon. The data therefore was fetched using the API interfaced with USGS 3DEP. Point Data Abstraction Library (PDAL) is used for manipulating point cloud data, which is inline with other pipeline processing operations. The PDAL processing pipeline is represented in JSON. The data to be collected is the raster data of the region required as specified with the bounds. The resulting files are in the form of .laz and .tif files. .tif file gives the image of the region of interest while .laz stores the LiDAR data as points.
# Elevation
Elevation for different parts of the farm gave the idea on how water can flow through the farm
# TWI
Topographic wetness index gives the specific points with different level of wetness
