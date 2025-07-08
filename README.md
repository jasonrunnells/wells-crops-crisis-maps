# Tulare County – Wells, Crops, and Water Crisis

This project visualizes groundwater decline, crop types, and agricultural pressure in Tulare County, California, one of the most water-stressed regions in the U.S. It uses interactive web maps to explore well-level data, spatial analysis outputs, and the surrounding crop patterns over time.

The project draws attention to the intersecting environmental and agricultural challenges of the Central Valley, with the goal of making complex groundwater data more accessible to the public and decision-makers.

## Features

- 💧 **Well Decline Analysis**  
  Displays total water surface elevation (WSE) change and slope from 2012 to 2024.

- 🔥 **Hot Spot Mapping**  
  Highlights statistically significant clusters of declining wells using Getis-Ord Gi* analysis.

- 🎯 **Multivariate Clustering**  
  Categorizes wells into three classes:  
  - **Severe Decline (Red)**  
  - **Moderate Decline (Orange)**  
  - **Stable (Green)**  

- 🌽 **Crop Type Context**  
  Shows the top 5 crop types found within 500m of each well using CDL raster summaries.

- 📍 **Interactive Popups**  
  Click on any well point to view its full attributes, classification, and surrounding crop breakdown.

## Technologies Used

- [Leaflet](https://leafletjs.com/) for interactive mapping  
- Custom GeoJSON layers exported from ArcGIS Pro  
- Tabulate Area analysis of USDA Cropland Data Layer (CDL)  
- HTML / CSS / JavaScript (no framework)

## Folder Structure

