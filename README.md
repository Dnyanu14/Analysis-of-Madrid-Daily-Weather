# Analysis-of-Madrid-Daily-Weather
Analysis of Madrid Daily Weather Data
Overview
This project involves analyzing daily weather data for Madrid from 1997 to 2015. The dataset includes metrics such as maximum, minimum, and mean temperature, dew point, humidity, visibility, wind speed, precipitation events, cloud cover, and wind direction. The goal is to uncover insights and trends in Madrid’s weather patterns over the specified period.

Table of Contents
Project Structure
Data Description
Analysis
Setup
Usage
Results
Contributing
License
Project Structure
data/: Contains the raw weather data files.
scripts/: Contains Python scripts used for data cleaning, analysis, and visualization.
notebooks/: Jupyter notebooks for exploratory data analysis and visualization.
results/: Contains output files, charts, and graphs generated from the analysis.
README.md: This file.
Data Description
The dataset includes the following columns:

Date: Date of the observation.
Max Temperature (°C): Maximum temperature recorded on that day.
Min Temperature (°C): Minimum temperature recorded on that day.
Mean Temperature (°C): Average temperature recorded on that day.
Dew Point (°C): Dew point temperature.
Humidity (%): Relative humidity percentage.
Visibility (km): Visibility distance in kilometers.
Wind Speed (km/h): Wind speed in kilometers per hour.
Precipitation (mm): Amount of precipitation recorded in millimeters.
Cloud Cover (%): Percentage of sky covered by clouds.
Wind Direction (°): Wind direction in degrees.
Analysis
The analysis focuses on:

Identifying trends and seasonality in temperature, precipitation, and other weather metrics.
Examining correlations between different weather variables.
Visualizing historical weather patterns and anomalies.
Investigating the impact of weather conditions on visibility and wind speed.

Setup
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/madrid-weather-analysis.git
Navigate to the Project Directory

bash
Copy code
cd madrid-weather-analysis
Install Required Packages

Create a virtual environment (optional) and install the dependencies listed in requirements.txt:

bash
Copy code
pip install -r requirements.txt
Usage
Data Cleaning and Preprocessing

Run the data cleaning script to preprocess the raw data:

bash
Copy code
python scripts/data_cleaning.py
Exploratory Data Analysis

Open the Jupyter notebooks in the notebooks/ directory to perform exploratory data analysis:

bash
Copy code
jupyter notebook notebooks/eda_notebook.ipynb
Run Analysis

Execute the analysis scripts to generate results and visualizations:

bash
Copy code
python scripts/analysis.py
View Results

Check the results/ directory for output files, charts, and graphs.

Results
The results of the analysis, including charts and graphs, are available in the results/ directory. Key findings include:

Seasonal variations in temperature and precipitation.
Trends in wind speed and visibility over the years.
Correlations between weather variables.
