# campfire-landsat-mapper

## Description
A simple map interface that utilises Landsat imagery from the Google Earth Engine API to visualise before and after damage caused by the 2018 "Camp Fire" fires of Northern California. Uses NDVI (Normalized Difference Vegetation Index) metric to highlight areas of destroyed vegetation, effectively visualising fire damage.

## Lookbook
### Vegetation Condition Prior to Fire (October 7th, 2018)
<p align="left">
    <img src="screenshots/2018_10_07_overlay.png" width=800 />
</p>

### Vegetation Condition in First Smoke/Cloud Free Image Since the Fire (December 26th, 2018)
<p align="left">
    <img src="screenshots/2018_12_26_overlay.png" width=800 />
</p>

### Vegetation Condition 2 Months After the Fire (January 27th, 2019)
<p align="left">
    <img src="screenshots/2019_01_27_overlay.png" width=800 />
</p>

## Tech Stack
### Frontend
- **Folium** - Library used to create the interactive map with Earth Engine image overlays

### Backend
- **Python** - Core application logic and orchestration
- **earthengine-api** – Accesses and processes Landsat imagery from Google Earth Engine
- **pandas** - Handles Earth Engine image metadata manipulation and storage

## Setup and Use
### Dependencies
- **earthengine-api**
- **folium**
- **jupyterlab** 
- **pandas**

### 1. Clone the Repository
```bash
git clone https://github.com/Grey-otoc/campfire-landsat-mapper.git
cd YOUR_FILE_PATH/campfire-landsat-mapper
```

### 2. Install Poetry (Python Package and Dependency Manager)
```bash
pip install poetry
```

### 3. Install Dependencies Into Poetry Managed Virtual Environment
```bash
poetry install
```

### 4. Run Jupyter Notebook Scripts
For example, launch Jupyter Lab and run the scripts there:
```bash
poetry run jupyter lab
```

### 5. Run All Scripts and Retrieve Your HTML File With the Map
```python
my_map.save("campfire_map.html")
```

## Contributing
This project was created for personal learning and exploration. While I'm not actively maintaining it, feel free to fork the repository and adapt it for your own use!

## Acknowledgements
- Utilises publicly available landsat imagery retrieved via the Google Earth Engine Python library: https://github.com/google/earthengine-community

## Links
- **Repository:** [campfire-landsat-mapper](https://github.com/grey-otoc/campfire-landsat-mapper)
