
# Day 16. Places We Dream of Visiting

## Overview

- **Theme:** Collaborative Map
- **Project type:** Interactive Web GIS and collaborative mapping
- **Study area:** Global

This project explores the collective travel aspirations of people through an interactive collaborative world map. Participants can select a country they dream of visiting, submit their name, and contribute to a shared global visualization.

Each contribution is stored in Google Sheets and reflected on the interactive map. Countries are symbolized according to the number of dream destination selections, allowing users to explore travel interests and discover which destinations attract the most attention.

The application also includes an interactive country selection feature that automatically zooms the map towards the selected destination


## Interactive map

<iframe
  src="https://places-we-dream-of-visiting.streamlit.app/?embed=true"
  width="100%"
  height="750"
  style="border:1px solid #ddd; border-radius:8px;">
</iframe>

[Open Collaborative Map Application](https://places-we-dream-of-visiting.streamlit.app/){:target="_blank"}

## Data & Tools
**Data Sources**

- [Natural Earth-Global country boundaries](https://www.naturalearthdata.com/)
- [Google Sheets-Collaborative contribution storage.]
- [User-submitted country selections – Community travel preferences.]

**Tools Used**

* Streamlit-Interactive web application development
* GeoPandas – Geospatial data processing
* Pandas – Contribution management and statistical summaries
* lotly – Interactive choropleth world map
* Google Sheets API / gspread – Collaborative data storage

## Key Features
- Interactive global choropleth visualization.
- Country selection and automatic map zoom.
- User name and destination submission.
- Live preview of selected destinations.
- Persistent community contributions through Google Sheets.
- Dynamic statistics showing total contributions, selected countries and dream destinations.

## Key takeaways
- Collaborative mapping can transform individual travel aspirations into a shared geographical visualization.
- Interactive choropleth mapping helps identify popular destinations through spatial patterns.
- Cloud-based data storage enables contributions to be collected and updated dynamically.
- Web GIS applications can make spatial participation accessible to a wider audience.
