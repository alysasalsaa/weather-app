# weather-app

A real-time weather app built with HTML, CSS, and JavaScript — no API key needed.

## About

Enter a city name and press Enter to see the current temperature, weather condition, wind speed, humidity, feels-like temperature, and whether it is day or night. The background theme changes dynamically based on weather conditions.

## Features

- [x] Enter a city name and press Enter to fetch weather
- [x] Displays temperature, weather condition, and condition icon
- [x] Shows day or night badge based on local solar position
- [x] Dynamic background theme (clear day, night, cloudy, rain)
- [x] Details: humidity, wind speed, feels-like temperature
- [x] Last searched city saved to localStorage and auto-loaded on next visit (bonus)
- [x] Loading spinner while fetching data
- [x] Error message for invalid or unfound cities

## APIs Used

| Service | Purpose | Key Required |
|---------|---------|--------------|
| [Open-Meteo](https://open-meteo.com) | Weather data | ❌ None |
| [Nominatim (OpenStreetMap)](https://nominatim.openstreetmap.org) | City geocoding | ❌ None |

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla)

## How to run

Open `index.html` in your browser — no build tools or API keys needed. Requires an internet connection to fetch live weather data.
