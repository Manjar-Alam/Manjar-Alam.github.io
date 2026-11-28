
# Day 28. A City Full of Life: Mapping the Geography of Excitement

## Overview

- **Theme:** Feeling
- **Project title:** A City Full of Life - Mapping the Geography of Excitement
- **Study area:** Amsterdam, Netherlands
- **Project type:** Urban activity mapping and spatial density analysis

This project explores the geography of excitement through the spatial distribution of urban activities across Amsterdam, Netherlands. Using OpenStreetMap points of interest (POIs), the analysis identifies locations associated with entertainment, nightlife, shopping, public spaces, and cultural attractions.

The objective is to examine how activity-related places are distributed across the city and identify urban hotspots where multiple activities are concentrated. A 500 m grid-based spatial analysis was used to quantify activity density and highlight areas with high concentrations of mapped POIs.

The map presents a spatial interpretation of the theme **Feeling**, representing places associated with urban vibrancy, recreation, social interaction, and cultural experiences rather than directly measuring human emotions.


## Interactive map
<iframe
  src="/30_day_map/maps_code/Day28_Feeling_Amsterdam_Clustered.html"
  width="100%"
  height="650"
  style="border:1px solid #ddd; border-radius:8px;"
  loading="lazy">
</iframe>

[View Interactive Map](/30_day_map/maps_code/Day28_Feeling_Amsterdam_Clustered.html){:target="_blank"}

Explore the interactive Amsterdam activity map, where you can:

- Explore the spatial distribution of five urban activity categories.
- Click on individual POIs to view their names, categories, and OpenStreetMap IDs.
- Expand clustered markers to explore nearby locations.
- Visualize activity density using a 500 m grid.
- Identify the top 15 activity hotspots.
- Toggle individual activity categories and map layers.



## Data and Methodology

### Data Sources

- [Geofabrik - OpenStreetMap Data](https://download.geofabrik.de/europe/netherlands.html)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [OpenStreetMap Wiki - Map Features](https://wiki.openstreetmap.org/wiki/Map_features)

### Data Processing

The analysis was carried out using Python and the following workflow:

1. **Data extraction:** Extracted Amsterdam-related POIs from the Netherlands OpenStreetMap PBF dataset using Pyrosm.
2. **POI classification:** Categorized locations into five urban activity groups based on OpenStreetMap tags.
3. **Spatial processing:** Converted geometries into representative point locations, filtered them to the Amsterdam study boundary, and removed duplicate records.
4. **Grid analysis:** Created a 500 m grid and calculated the number of POIs and activity density within each cell.
5. **Hotspot identification:** Ranked grid cells based on total POI counts and highlighted the top 15 activity concentration areas.
6. **Cartographic visualization:** Developed a static map and an interactive Folium map with clustered clickable POIs, density visualization, and layer controls.

## Activity Categories

Five categories were used to represent different dimensions of urban activity.

| Category | POIs | Percentage |
|---|---:|---:|
| Entertainment | 174 | 0.84% |
| Nightlife & Dining | 4,113 | 19.83% |
| Markets & Shopping | 4,782 | 23.06% |
| Public Spaces | 10,143 | 48.90% |
| Culture & Attractions | 1,529 | 7.37% |
| **Total** | **20,741** | **100%** |

## Spatial Analysis Results

- **Total mapped POIs:** 20,741
- **Activity grid resolution:** 500 m
- **Total grid cells:** 989
- **Highest POI count in a grid cell:** 414
- **Maximum activity density:** 1,656 POIs/km²

The analysis shows that public spaces account for the largest share of mapped activity locations, followed by markets and shopping, and nightlife and dining. The grid-based analysis further reveals spatial variations in activity concentration across Amsterdam.


## Tools and Technologies
* QGIS, ArcGIS Pro, Esri World Street Map
* Python (GeoPandas, Pandas, Matplotlib, Folium) [Python Notebook](#Link)

## Cartographic Design

The visualization combines a warm density colour ramp with five distinct category colours to distinguish different types of urban activities.

The interactive map includes:

- 500 m activity-density grid.
- Top 15 activity hotspot outlines.
- Category-wise clustered POI markers.
- Clickable POI information popups.
- Amsterdam administrative boundary.
- Esri World Street Map basemap.
- Interactive layer controls.

## Interpretation and Limitations
- The map provides a spatial perspective on locations associated with urban activity and excitement. Areas with higher POI concentrations may indicate greater availability of recreational, commercial, cultural, and social destinations.
- However, mapped POI density should not be interpreted as a direct measurement of human excitement, happiness, or actual visitor activity. OpenStreetMap coverage, tagging practices, and differences in data completeness may influence the observed spatial patterns.
