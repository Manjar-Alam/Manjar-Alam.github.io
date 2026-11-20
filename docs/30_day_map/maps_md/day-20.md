
# Day 20. Delhi in Hexagons

## Overview

- **Theme:** Hexagons
- **Project type:** Urban GIS and building footprint density analysis
- **Study area:** Delhi, India

This project explores the spatial distribution of urban development across Delhi using a hexagonal grid-based approach. OpenStreetMap building footprints are aggregated into hexagonal cells to quantify the proportion of land occupied by buildings within each cell.

The resulting map illustrates variations in built-up intensity across the city, highlighting areas of concentrated urban development and relatively low building coverage. A graduated colour scheme, ranging from deep purple to yellow, represents six levels of built-up intensity against a dark cartographic background.


## Interactive map

<iframe
  src="/30_day_map/maps_code/Day20_Delhi_In_Hexagons.html"
  width="100%"
  height="650"
  style="border:1px solid #ddd; border-radius:8px;"
  loading="lazy">
</iframe>

[View Interactive Map](/30_day_map/maps_code/Day20_Delhi_In_Hexagons.html){:target="_blank"}

## Data & Tools
**Data Sources**

- [Geofabrik](https://www.geofabrik.de/)
- [DIVA-GIS](https://diva-gis.org/data.html)

**Tools Used**

* QGIS, ArcGIS Pro
* Python (GeoPandas, Pandas, Matplotlib, Folium) [Python Notebook](#Link)

## Key takeaways

- Hexagonal aggregation provides a consistent spatial framework for examining variations in building footprint density across Delhi.
- The analysis highlights spatial differences in built-up intensity beyond conventional administrative boundaries.
- Areas with higher building footprint percentages indicate greater building coverage within individual hexagonal cells.
- The results represent mapped building footprints available in OpenStreetMap and should not be interpreted as a complete inventory of all buildings in Delhi.
