# Air Quality Analysis

This project analyzes the "city_day.csv" dataset to understand air quality trends and patterns across various cities. The analysis involves data cleaning, preprocessing, and exploratory data analysis to uncover insights into air pollution.

## Dataset

The dataset used in this project is "city_day.csv", which contains daily air quality measurements for different cities. The key features of the dataset include:

* City: The name of the city.
* Date: The date of the measurement.
* PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene: Concentrations of various air pollutants.
* AQI: The Air Quality Index.
* AQI_Bucket: The category of the AQI (e.g., 'Good', 'Satisfactory', 'Moderate', 'Poor', 'Very Poor', 'Severe').

## Data Cleaning and Preprocessing

The following steps were taken to clean and preprocess the data:

1.  **Date Conversion:** The 'Date' column was converted to a datetime format to enable time-series analysis.
2.  **Handling Missing Values:** Missing values in the dataset were filled with 0.
3.  **Feature Engineering:** 'Month' and 'Year' columns were extracted from the 'Date' column to facilitate time-based analysis.

## Exploratory Data Analysis (EDA)

The EDA involved the following visualizations to understand the data:

* **Histograms:** To visualize the distribution of different air pollutants.
* **Scatter Plots:** To explore the relationship between PM2.5 and AQI, as well as NO2 and AQI.
* **Bar Charts:** To show the average AQI for each AQI bucket and the average levels of each pollutant for every city.
* **Line Plot:** To visualize the trend of the average Air Quality Index (AQI) over the years.

## Key Findings

The analysis reveals the following insights:

* The distribution of various pollutants and their relationship with the AQI.
* The trend of air quality over time.
* A comparative analysis of air quality across different cities.

This project provides a comprehensive overview of the air quality data, and the findings can be used to inform further research and policy decisions.
