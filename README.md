
Air Quality Prediction

Project Overview

It focuses on analyzing and preprocessing air quality data from Indian cities (2015–2020) and then building machine learning models to predict Air Quality Index (AQI) levels and AQI categories.
The project includes data cleaning, handling missing values, feature engineering, exploratory data analysis (EDA), and preprocessing (encoding & scaling). In later stages, regression and classification models will be implemented to forecast air quality and support environmental monitoring efforts.

Objectives

* Clean and preprocess real-world air quality data
* Handle missing values and inconsistent entries
* Convert date columns and extract useful time-based features
* Perform exploratory data analysis (EDA) to identify trends and patterns
* Apply encoding and scaling to prepare the dataset for machine learning models

Dataset

* Source: [Air Quality Data in India (Kaggle)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
* File Used: `city_day.csv`
* Features: Pollutants (PM2.5, PM10, NO2, CO, SO2, O3, etc.), AQI, City, Date

Preprocessing Steps 

1. Data Loading
2. Handling Missing Values
3. Converting Date column to datetime format
4. Extracting new features (Year, Month, Day)
5. Exploratory Data Analysis (EDA) – AQI trends, city comparison, correlations
6. Final preprocessing:

   * Encoding `AQI_Bucket` (categorical → numeric)
   * Scaling pollutant features for ML readiness

Insights from EDA

* AQI shows seasonal patterns, with higher values in winter.
* Some cities (like Delhi, Lucknow, Kanpur) consistently record poor air quality.
* Strong correlation observed between **PM2.5, PM10, NO2** and AQI.





