# campfire-landsat-mapper

## Description
A simple map interface that utilises Landsat imagery from the Google Earth Engine API to visualise before and after damage caused by the 2018 "Camp Fire" fires of Northern California. Uses NDVI (Normalized Difference Vegetation Index) metric to highlight areas of destroyed vegatation, effectively visualising fire damage.

**[Map Interface](https://grey-otoc.github.io/campfire-landsat-mapper/)**

## Tech Stack
### Frontend
- **Folium** - Library used to create the interactive map with Earth Engine image overlays

### Backend
- **Python** - Core application logic and orchestration
- **earthengine-api** – Accesses and processes Landsat imagery from Google Earth Engine
- **pandas** - Processes Earth Engine data and derives usable images for visualisation
- **IPython** - Provides ability to view images returned from Earth Engine API in Jupyter notebook

## Dependencies
- **earthengine-api**
- **folium**
- **geopandas**
- **jupyterlab** 
- **pandas**

## Links
- **Repository:** [campfire-landsat-mapper](https://github.com/grey-otoc/campfire-landsat-mapper)
- **[Map Interface](https://grey-otoc.github.io/campfire-landsat-mapper/)**
