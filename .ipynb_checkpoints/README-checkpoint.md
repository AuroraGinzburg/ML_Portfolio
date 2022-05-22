![Project Schematic](https://github.com/AuroraGinzburg/ML_Portfolio/blob/master/Github_splash.png)

# Predicting California's Energy Demand
Forecasting future energy demand is crucial for the success of renewable energy systems. 
Energy that is generated from wind and solar sources needs to be stored upon capture so that it can be used during periods of intermittency.
Therefore, the ability to accurately anticipate future energy demand is of the utmost importance for designing the most economical and reliable energy storage systems.
Since the California Independent System Operator (ISO) maintains one of the world's largest power grids and makes their data available to the public, 
California's energy demand is the focus of this project.

This is a personal project I undertook to practice, expand, and showcase my data science skills. 

#### -- Project Status: Active

## Project Intro/Objective
This project aims to understand the relationships between weather and energy demand. Statistics, visualizations and supervised learning (i.e. a deep neural network) are used to better understand the relationship between weather, date and energy demand. 

## Project Description
- California energy demand data are from [California ISO](https://www.caiso.com/TodaysOutlook/Pages/default.aspx#section-demand-trend)
- Weather data are from [NOAA's National Centers for Environmental Information](https://www.ncdc.noaa.gov/cdo-web/webservices/v2)
- Weather data points were requested from weather stations at the following 7 locations: Fresno, Los Angeles Coastal, Los Angeles Inland, Sacramento, 
  San Diego, San Francisco, San Jose (see Notebook 1 for location ID numbers)
- The weather data used consisted of the daily minimum and maximum temperature for each location
- The dataset used spanned April 2018-May 2022 and each day's date was used as a feature
- The energy demand values were the total state demand per day
- A deep neural network was used to predict the energy demand for the most recent year of data, while using the previous years for training


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is acquired during web scraping in Notebook 1. A Chrome web browser was employed for web scraping and the ChromeDriver can be downloaded [here](https://sites.google.com/a/chromium.org/chromedriver/downloads). The only external raw data used was the California shapefiles needed to generate a geoplot in Notebook 3, they can be found in the [shapefiles folder](https://github.com/AuroraGinzburg/ML_Portfolio/tree/master/shapefiles). There is a folder of CSV files that served as save points; downloading these is not necessary to run the notebooks.    
3. Go through the three notebooks sequentially. 

## Featured Notebooks
* [Notebook 1: Web Scraping of Energy and Weather Data](https://github.com/AuroraGinzburg/ML_Portfolio/blob/7249b7754bafc3cfbfbbfcbc9650e7fb8784bdc8/1-Data%20Scraping.ipynb)
* [Notebook 2: Exploratory Data Analysis and Data Cleaning](https://github.com/AuroraGinzburg/ML_Portfolio/blob/7249b7754bafc3cfbfbbfcbc9650e7fb8784bdc8/2-Data%20Cleaning%20and%20EDA.ipynb)
* [Notebook 3: Data Visualization, Model Building and Model Evaluation](https://github.com/AuroraGinzburg/ML_Portfolio/blob/7249b7754bafc3cfbfbbfcbc9650e7fb8784bdc8/3-Data%20Visualization%20and%20Modeling.ipynb)


## Contact
* Feel free to contact me with any questions or if you are interested in collaborating on future work! 
 **auroraginz@gmail.com**
 
## Resources
The following community resources were helpful when developing this project:
* [Web-Scraping Electricity Data with Selenium] (https://medium.com/@k246fri/web-scraping-electricity-data-with-selenium-f2504a124fc4)
* [Getting Weather Data in 3 Easy Steps] (https://towardsdatascience.com/getting-weather-data-in-3-easy-steps-8dc10cc5c859)
* [Encoding Time Information as Features for ML Models] (https://developer.nvidia.com/blog/three-approaches-to-encoding-time-information-as-features-for-ml-models/)
* [A Gentle Introduction to Batch Normalization for Deep Neural Networks] (https://machinelearningmastery.com/batch-normalization-for-training-of-deep-neural-networks/)
* [Hyperparameter Tuning with KerasTuner] (https://towardsdatascience.com/hyperparameter-tuning-with-kerastuner-and-tensorflow-c4a4d690b31a)
