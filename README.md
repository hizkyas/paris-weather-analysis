# Paris Weather Analysis (Past 7 Days)

This project fetches weather data for Paris from the **Open-Meteo API**, processes it using **Pandas**, and visualizes daily temperature trends with **Matplotlib**.

## Features
- Fetches maximum and minimum daily temperatures for the last 7 days
- Converts raw API data into a clean Pandas DataFrame
- Plots temperature trends over time
- Saves the chart as an image file (`weather_chart.png`)

## Technologies Used
- Python
- Requests
- Pandas
- Matplotlib
- Open-Meteo API

## How It Works
1. Calculates the date range (today and the previous 7 days)
2. Requests weather data from the Open-Meteo API
3. Extracts and structures daily temperature data
4. Generates and saves a line chart of max/min temperatures

## Installation
```bash
pip install requests pandas matplotlib
