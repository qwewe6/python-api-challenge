# WeatherPy Analysis (Module 6 Challenge)

## Overview
This project analyzes how weather varies with latitude using data from over 500 cities worldwide. The goal is to visualize trends in temperature, humidity, cloudiness, and wind speed as they relate to geographic location, particularly proximity to the equator.

## Technologies Used
- Python
- OpenWeatherMap API
- Citipy Library
- Pandas, Matplotlib, SciPy
- GeoViews, Geoapify API (VacationPy)

## Part 1: WeatherPy

### Objective
Use the OpenWeatherMap API and Citipy to gather weather data and explore how it changes with latitude.

### Visualizations
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

### Regression Analysis
- Linear regression applied separately to cities in the Northern and Southern Hemispheres to identify directional trends.

## Part 2: VacationPy

### Objective
Plan ideal vacation spots using weather conditions and map-based visualizations.

### Features
- Filter cities based on ideal weather:
  - Temperature: 21–27°C
  - Wind speed < 4.5 m/s
  - 0% cloudiness
- Locate nearby hotels using the Geoapify API.
- Generate interactive maps displaying city names, hotel locations, and humidity levels.

## Setup Instructions
1. Clone this repository.
2. Install required libraries (`requests`, `matplotlib`, `pandas`, `scipy`, `hvplot`, etc.).
3. Run Jupyter Notebooks to view both the WeatherPy and VacationPy reports.

## Credits
- Tools & Guidance: Google, ChatGPT
