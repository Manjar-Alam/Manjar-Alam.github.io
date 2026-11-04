
# Day 4.  Clusters

## Overview

- **Theme:** Clusters
- **Project type:** Satellite-based active fire mapping and spatial clustering
- **Study area:** India

This map explores the spatial concentration of satellite-detected active fires and thermal anomalies across India during 2025. The NASA FIRMS dataset provides geographic coordinates and observation attributes for each detection. Spatial clustering helps reveal areas with relatively high concentrations of detections and highlights regional patterns in fire activity.

The map is intended as a spatial overview of satellite detections. A detection does not necessarily represent a unique fire incident: one fire may be detected on multiple satellite overpasses, and a flagged pixel may contain one or more fires or other thermal anomalies.




## Interactive map

<iframe
  src="/30_day_map/maps_code/Day4_India_Fire_2025_Interactive.html"
  width="100%"
  height="650"
  style="border:1px solid #ddd; border-radius:8px;"
  loading="lazy">
</iframe>

[View Interactive Map](/30_day_map/maps_code/Day4_India_Fire_2025_Interactive.html){:target="_blank"}



## Data & Tools
**Data Sources**

- [NASA FIRMS Archive](https://firms.modaps.eosdis.nasa.gov/download/create.php)
- [DIVA-GIS](https://diva-gis.org/data.html)

**Tools Used**

* QGIS, ArcGIS Pro
* Spatial fields: Latitude and longitude
* Analysis: Data cleaning, point generation and density-based spatial clustering
* Python (GeoPandas, Pandas, Matplotlib, Folium) [Python Notebook](#Link)

## Key takeaways

- Satellite fire detections are not the same as unique fire incidents.
- Spatial clustering highlights areas with high concentrations of detections.
- FRP adds information about the radiative intensity of individual detections.
- Detection patterns are influenced by satellite overpasses, observation conditions and the characteristics of the fire product.
- The resulting map provides a spatial overview of active fire detections during 2025, rather than a complete inventory of all fires or burned areas.
