# Seattle-Tract-Index-Tool
An interactive web-based dashboard that visualizes livability scores across Seattle census tracts.

## Overview
This project calculates a composite accessibility index based on three metrics:

- Transit Availability – bus stops and transportation infrastructure
- Park Availability – access to green space and recreational areas
- Food Availability – proximity to grocery stores

Users can adjust the weight of each metric using sliders to dynamically recalculate the composite score and explore spatial differences across the city.

## Features

  - Interactive Mapbox choropleth map
  - Adjustable index weights
  - Real-time composite score updates
  - Census tract popup metrics
  - Score distribution bar chart
  - UI components styled based on Figma design

## Technologies Used
   - Mapbox GL JS
   - C3.js (D3-based charting)
   - HTML / CSS / JavaScript

## Data Sources
   - [Parks and Recreation Dataset](https://data.seattle.gov/Community-and-Culture/Seattle-Parks-And-Recreation-Park-Addresses/v5tj-kqhc/about_data)
   - [Transit Stop Datapoints](https://www5.kingcounty.gov/sdc/?Layer=transitstop)
   - [Seattle Census Tracts](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::2020-census-tracts-seattle/explore?location=47.612038%2C-122.333403%2C11)
   - The parks point dataset and the transit stop dataset were gathered, loaded, and aggregated by census tract. Instead of displaying individual points on the map, the map calculates the index based on the counts of each measure in that tract.

[Live Demo](https://jaedencca.github.io/Seattle-Tract-Index-Tool/)

