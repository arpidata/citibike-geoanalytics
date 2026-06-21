# 🚲 Citi Bike Geospatial Analytics

End-to-end geospatial analysis of Citi Bike trip data
for Jersey City (2025) using Python.

## Project Overview

This project explores **where**, **when**, and **how** people
use Citi Bike in Jersey City by combining trip data with
weather data and geospatial visualization tools.

## Key Questions

- Which stations are the most active departure and arrival points?
- How does ride volume change across seasons and weather conditions?
- Which routes (station pairs) are most frequently used?
- How do casual riders and members differ in behavior?

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python / Pandas | Data processing |
| GeoPandas | Spatial calculations |
| Plotly | Interactive charts |
| Folium | Interactive maps |
| Kepler.gl | Advanced geospatial visualization |

## Project Structure

```text
citibike-geoanalytics/
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_cleaning_and_features.ipynb
│   ├── 03_weather_analysis.ipynb
│   ├── 04_station_route_analysis.ipynb
│   └── 05_geospatial_visualization.ipynb
├── outputs/
├── data/ ← not tracked (large files)
├── requirements.txt
└── README.md

## Data Source

[Citi Bike System Data](https://citibikenyc.com/system-data) — 
public trip history files (Jersey City, 2025)

Weather data via [Open-Meteo Archive API](https://open-meteo.com/)

## Status

🚧 In progress
