# Day 25. The Moon
## Overview

- **Theme:** Is this a map?
- **Project type:** Planetary cartography and digital elevation model (DEM) visualisation
- **Study area:** The Moon

This project explores the unconventional side of cartography by mapping the lunar surface using NASA's Lunar Orbiter Laser Altimeter (LOLA) global elevation data. The digital elevation model (DEM) was processed in Python to visualise the Moon's topographic variations, including elevated highlands, impact basins and cratered terrain. A custom colour palette and simulated hillshade were applied to enhance surface relief and highlight variations in lunar elevation. The resulting global topographic visualisation was further developed into an interactive 3D lunar surface using Plotly, allowing users to explore elevation patterns through rotation, zooming and interactive inspection. The project demonstrates how cartographic principles can extend beyond Earth to represent and interpret the surface of another celestial body.

## Interactive map

<iframe
  src="/30_day_map/maps_code/Day25_Moon_Interactive_3D.html"
  width="100%"
  height="650"
  style="border:1px solid #ddd; border-radius:8px;"
  loading="lazy">
</iframe>

[View Interactive Map](/30_day_map/maps_code/Day25_Moon_Interactive_3D.html){:target="_blank"}

## Data & Tools

**Data Sources**

- [NASA Lunar Orbiter Laser Altimeter (LOLA)](https://pgda.gsfc.nasa.gov/products/95)
- NASA LOLA Global Lunar Digital Elevation Model (`LDEM64_PA_pixel_202405.tif`)

**Tools Used**

* QGIS, ArcGIS Pro
* Python (GeoPandas, Pandas, Matplotlib, Folium, Branca) [Python Notebook](#Link)
* Digital Elevation Model (DEM) Processing
* Hillshade and Topographic Relief Visualisation
* Interactive 3D Surface Mapping

## Key takeaways

- The project demonstrates an unconventional approach to cartography through planetary surface mapping using NASA LOLA elevation data.
- Lunar elevation measurements are transformed into a global topographic relief visualisation using custom colour mapping and simulated illumination.
- Shaded relief highlights the spatial variations of lunar highlands, impact basins and cratered landscapes.
- Interactive 3D visualisation provides an additional perspective for exploring lunar surface elevation and terrain morphology.
- The experiment challenges conventional ideas of mapping by demonstrating that cartography is not limited to terrestrial landscapes and can extend to planetary surfaces beyond Earth.