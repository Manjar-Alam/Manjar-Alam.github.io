
# Day 13. Interactions: India by Air

## Overview

- **Theme:** Interactions – Transport
- **Project type:** Aviation network and transport connectivity mapping
- **Study area:** India

This project explores India's domestic aviation network through the spatial relationships between airports and direct flight connections. The map highlights airport connectivity using graduated symbols and represents the number of airlines operating between airport pairs through varying route widths. It provides a historical perspective on domestic air transport connectivity, identifying major aviation hubs and regional connections across the country.


## Interactive map

<iframe
  src="/30_day_map/maps_code/Day13_India_By_Air_Interactive.html"
  width="100%"
  height="650"
  style="border:1px solid #ddd; border-radius:8px;"
  loading="lazy">
</iframe>

[View Interactive Map](/30_day_map/maps_code/Day13_India_By_Air_Interactive.html){:target="_blank"}



## Data & Tools
**Data Sources**

- [OpenFlights – Airports Dataset](#https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat)
- [OpenFlights – Routes Dataset](#https://raw.githubusercontent.com/jpatokal/openflights/master/data/routes.dat)
- Both datasets were downloaded from GitHub and saved as .dat files for analysis.

**Tools Used**

* QGIS, ArcGIS Pro
* Python (GeoPandas, Pandas, Matplotlib, Folium) [Python Notebook](#Link)

## Key takeaways

- The map illustrates historical domestic aviation connectivity through direct airport-to-airport routes.
- Airport symbol sizes represent the number of unique direct domestic connections, highlighting the relative connectivity of individual airports.
- Route widths indicate the number of airlines recorded for each airport pair, rather than flight frequency or passenger traffic.
- The mapped network provides a historical snapshot of India's domestic aviation system and should not be interpreted as the current flight network.
