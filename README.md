🌍 Google Earth Engine Recipes
A curated collection of Google Earth Engine (GEE) scripts and Jupyter notebooks for geospatial analysis, remote sensing, and Earth observation. This repository demonstrates practical workflows for processing satellite imagery, deriving spectral indices, monitoring environmental change, and performing spatial analysis using the Google Earth Engine JavaScript and Python APIs.
Objectives
This repository aims to:
•	Demonstrate reproducible remote sensing workflows using Google Earth Engine.
•	Provide well-documented scripts for common Earth observation tasks.
•	Serve as a learning resource for students, researchers, and practitioners.
•	Build a reusable library of geospatial analysis scripts for research and decision-making.
Topics Covered
Data Access
•	Accessing Earth Engine datasets
•	Loading FeatureCollections and ImageCollections
•	Filtering by date, location, and cloud cover
Image Processing
•	Cloud masking
•	Image mosaicking
•	Median and composite images
•	Image clipping
•	Band selection
Spectral Indices
•	NDVI (Normalized Difference Vegetation Index)
•	NDWI (Normalized Difference Water Index)
•	NDBI (Normalized Difference Built-up Index)
•	SAVI (Soil Adjusted Vegetation Index)
•	EVI (Enhanced Vegetation Index)
•	NBR (Normalized Burn Ratio)
Remote Sensing Applications
•	Land use/land cover mapping
•	Burn scar analysis
•	Forest monitoring
•	Vegetation health assessment
•	Water body extraction
•	Urban expansion analysis
•	Time-series analysis
Raster Analysis
•	Terrain analysis
•	Elevation
•	Slope
•	Aspect
•	Hillshade
•	Zonal statistics
Exporting Results
•	Export images to Google Drive
•	Export FeatureCollections
•	Export GeoTIFFs
•	Export CSV tables
________________________________________
Datasets
Example datasets used throughout the repository include:
•	Sentinel-2 MSI
•	Sentinel-1 SAR
•	Landsat 8 & 9
•	MODIS
•	SRTM Digital Elevation Model
•	ESA WorldCover
•	Dynamic World
•	JRC Global Surface Water
•	FIRMS Active Fire
•	CHIRPS Precipitation
________________________________________
Requirements
Google Earth Engine
•	Google Earth Engine account
•	Earth Engine Code Editor or Python API
Python Packages
earthengine-api
geemap
geopandas
rasterio
matplotlib
numpy
pandas
Install with:
pip install earthengine-api geemap geopandas rasterio matplotlib numpy pandas
Authenticate Earth Engine:
earthengine authenticate
________________________________________
Example Workflow
1.	Load satellite imagery.
2.	Filter by region and date.
3.	Apply cloud masking.
4.	Calculate spectral indices.
5.	Visualize results.
6.	Export processed outputs.
________________________________________
Repository Goals
This repository is being developed as a personal portfolio to demonstrate skills in:
•	Google Earth Engine
•	Remote Sensing
•	GIS
•	Earth Observation
•	Geospatial Analysis
•	Python
•	JavaScript
•	Environmental Modelling
•	Spatial Data Science
New examples and workflows will be added regularly.
________________________________________
Contributing
Suggestions, improvements, and contributions are welcome. If you find an issue or have an idea for a new workflow, feel free to open an issue or submit a pull request.
________________________________________
License
This project is licensed under the MIT License.
________________________________________
Author
Ritika Verma
Research interests:
•	Geospatial AI
•	Remote Sensing
•	Earth Observation
•	Climate Change
•	Environmental Modelling
•	Machine Learning for Spatial Data
If you find this repository useful, consider giving it a ⭐ to support the project.

