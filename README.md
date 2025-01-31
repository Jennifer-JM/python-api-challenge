# python-api-challenge

---

## Overview

This project analyzes weather patterns using OpenWeatherMap API and identifies ideal vacation spots with Geoapify API.

## Setup

1. Clone the repo and create a `WeatherPy` folder
2. Add starter files:
   * `WeatherPy.ipynb`
   * `VacationPy.ipynb`
   * `api_keys.py` (add to `.gitignore`)
3. Commit and push updates

## Part 1: WeatherPy

* Fetch weather data for 500+ cities
* Create scatter plots for:
  * Latitude vs. Temperature
  * Latitude vs. Humidity
  * Latitude vs. Cloudiness
  * Latitude vs. Wind Speed
* Perform linear regression for Northern & Southern Hemispheres

## Part 2: VacationPy

* Map all cities with humidity levels
* Filter for ideal weather conditions
* Use Geoapify API to find hotels
* Display final vacation map

## Technologies Used

* Python, Jupyter Notebook
* Pandas, Matplotlib, SciPy
* OpenWeatherMap API, Geoapify API
* citipy, geoViews
