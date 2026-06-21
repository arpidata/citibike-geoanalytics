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
│
├── data/
│   ├── citibike/               # Source Citi Bike monthly trip data (CSV files)
│   │   ├── JC-202502-citibike-tripdata.csv
│   │   ├── JC-202503-citibike-tripdata.csv
│   │   └── ... [other monthly files]
│   │
│   ├── processed/              # Cleaned and engineered datasets
│   │   └── citibike_cleaned.csv
│   │
│   └── raw/                    # Placeholder for unmodified raw source files
│       └── .gitkeep
│
├── notebooks/                  # Data pipeline steps executed via Jupyter Notebooks
│   ├── 01_data_collection.ipynb
│   ├── 02_data_enrichment.ipynb
│   ├── 03_weather_data.ipynb
│   ├── 04_data_visualization.ipynb
│   └── 05_neighborhood_analysis.ipynb
│
├── outputs/                    # Exported charts, maps, and reporting assets
│   └── .gitkeep
│
├── .gitignore                  # Specifies intentionally untracked files to ignore
├── README.md                   # Main documentation for the repository
└── requirements.txt            # List of Python dependencies (pandas, numpy, etc.)


## Data Source

[Citi Bike System Data](https://citibikenyc.com/system-data) — 
public trip history files (Jersey City, 2025)

Weather data via [Open-Meteo Archive API](https://open-meteo.com/)

## Status

🚧 In progress

