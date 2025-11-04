# Urban-Soil-Sustainability
## The role of community gardens in mitigating soil erosion risk and developing food security in Calgary

**Author:** Kate Murch 

**Course**: GEOG587 - Geospatial Project Management  

**Institution**: University of Calgary 

**License**: CC0 1.0 Universal

**Contact Information**: kate.murch@ucalgary.ca

---
## Project Overview
This project explores how community gardens support the health and sustainability of urban soils as well as food security in the City of Calgary. The main map combines slope/erosion risk, vegetation cover, and permeability.

---
## Structure  
| Folder | Contents |  
| ------ | -------- |  
| 'data/' | CSV datasets |  
| 'maps/' | Final map exports |  
| 'LICENSE' | CC0 License |  
| 'README.md' | Project information (this file) |  

---
## Coordinate Reference System   
All data uses **NAD84 / UTM Zone 11 N**  

---
## Data Sources and Processing  
| Layer | Source | Processing |  
| ----- | ------ | ---------- |  
| **Community Garden Locations** | [Calgary Horticulture Society] (https://www.calhort.org/get-involved/find-a-community-garden/#/action/Alpha/value/ALL/cid/771/id/8501/listingType/O) | Geocoded into ArcGIS Pro | 
| **NDVI** | [City of Calgary - Vegetation Cover] (https://data.calgary.ca/Environment/Citywide-Land-Cover-Classification-Map/g53d-yj3y) |  Derived from land cover |   
| **DEM / Slope** | [City of Calgary - DEM] (https://www.calgary.ca/maps/digital-elevation-model.html) | Converted to slope degrees for analysis |  
| **USSI** | Created in ArcGIS Pro | Raster calculations |   
| **Impervious Surfaces** | [City of Calgary] (https://data.calgary.ca/Environment/Impervious-Surface-Map-2021/rs9i-za7y) | 

---

