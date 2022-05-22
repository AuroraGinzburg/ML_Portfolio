![Project Schematic](https://github.com/AuroraGinzburg/ML_Portfolio/blob/master/github_splash.tif)

# Predicting California's Energy Demand
Forecasting future energy demand is crucial for the success of renewable energy systems. 
Energy that is generated from wind and solar sources needs to be stored upon capture so that it can be used when the sun isn't shining and the wind isn't blowing.
Therefore, the ability to accurately anticipate future energy demand is of the utmost importance for designing the most economical and reliable energy storage systems.
Since the California Independent System Operator (ISO) maintains one of the world's largest power grids and makes their data available to the public, 
California's energy demand is the focus of this project.

This is a personal project I did to practice and expand my data science skills. 

#### -- Project Status: Active

## Project Intro/Objective
This project aims to understand the relationships between weather and energy demand and use a deep neural network to forecast energy demand. 

## Project Description
- California energy demand data is from [California ISO](https://www.caiso.com/TodaysOutlook/Pages/default.aspx#section-demand-trend)
- Weather data is from [NOAA's National Centers for Environmental Information](https://www.ncdc.noaa.gov/cdo-web/webservices/v2)
- Weather data points were requested from weather stations at the following 7 locations: Fresno, Los Angeles Coastal, Los Angeles Inland, Sacramento, 
  San Diego, San Francisco, San Jose (see Notebook 1 for location ID numbers)
- The weather data used consisted of the daily minimum and maximum temperature for each location
- The dataset used spanned April 2018-May 2022
- The energy demand data used was the total state demand per day
- A deep neueral network was used to predict the energy demand for the most recent year of data with known values.


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is acquired during web scraping in Notebook 1. I used a Chrome web browser during web scraping, the ChromeDriver can be downloaded [here](https://sites.google.com/a/chromium.org/chromedriver/downloads). The only external raw data used was the California shapefiles needed to generate a geoplot in Notebook 3, can be found in the [shapefiles folder](https://github.com/AuroraGinzburg/ML_Portfolio/tree/master/shapefiles). There is a folder of CSV files that served as save points; downloading these is not necessary to run the notebooks.
    
3. Go through the three notebooks sequentially. 

## Featured Notebooks
* [Notebook 1: Web Scraping of Energy and Weather Data](https://github.com/AuroraGinzburg/ML_Portfolio/blob/7249b7754bafc3cfbfbbfcbc9650e7fb8784bdc8/1-Data%20Scraping.ipynb)
* [Notebook 2: Exploratory Data Analysis and Data Cleaning](https://github.com/AuroraGinzburg/ML_Portfolio/blob/7249b7754bafc3cfbfbbfcbc9650e7fb8784bdc8/2-Data%20Cleaning%20and%20EDA.ipynb)
* [Notebook 3: Data Visualization, Model Building and Model Evaluation](https://github.com/AuroraGinzburg/ML_Portfolio/blob/7249b7754bafc3cfbfbbfcbc9650e7fb8784bdc8/3-Data%20Visualization%20and%20Modeling.ipynb)


## Contact
* Feel free to contact me with any questions or if you are interested in collaborating on future work! 
 **auroraginz@gmail.com**
