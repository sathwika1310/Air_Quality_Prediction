
Project Overview

The goal is to predict Air Quality Index (AQI) categories for Indian cities based on pollutant levels using Machine Learning models.
By analyzing the dataset, preprocessing it, and applying ML techniques, the project provides insights into pollution levels and predicts AQI categories (Good, Satisfactory, Moderate, Poor, Very Poor, Severe).

Methodology

* Data Collection & Problem Definition – Identified AQI prediction as the core problem.

* Data Preprocessing – Cleaning dataset, handling missing values, encoding categorical features.

* Exploratory Data Analysis (EDA) – Analyzing pollutant patterns, distributions, and correlations.

* Model Selection – Chose Random Forest Classifier as the predictive model.

* Model Training & Evaluation – Training model on processed data.

Dataset

* Source: [Air Quality Data in India (Kaggle)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
* File Used: `city_day.csv`
Key Features (independent variables):
     * PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene
Target Variable (dependent variable):
     * AQI_Bucket (Categorical: Good, Satisfactory, Moderate, Poor, Very Poor, Severe)


Tech Stack

* Python
* Google Colab
* Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn





