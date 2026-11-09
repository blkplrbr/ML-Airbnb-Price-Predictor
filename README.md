# Airbnb Multi-City Price Predictor

## Project Overview
This project utilizes a Machine Learning regression model to forecast Airbnb nightly prices across 10 of the world's most visited cities (including New York, London, Paris, Tokyo, and Sydney). The model analyzes property features, location, and host metrics to predict optimal pricing strategies for real estate investors and property managers.

## The Business Problem
Property managers and real estate investors struggle to price their Airbnb listings competitively without leaving money on the table. The goal was to build a predictive model that could estimate a fair nightly price based on the specific attributes of a listing, allowing hosts to optimize their revenue.

## Dataset Overview
*   **Source:** Inside Airbnb (compiled across 10 global cities).
*   **Volume:** Over 290,000 listings with 20 columns.
*   **Key Features:** 
    *   *Property Details:* Room type (Entire home, Private room, etc.), minimum nights requirement, availability (days per year).
    *   *Location:* Neighbourhood, latitude, and longitude coordinates.
    *   *Host Metrics:* Number of listings per host, host info.
    *   *Target Variable:* Price per night.

## Technical Stack
*   **Language:** Python
*   **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn

## Methodology
1.  **Data Cleaning:** Handled missing values (especially in pricing and bedroom columns) and removed extreme outliers that would skew the regression model (e.g., listings priced at $10,000/night).
2.  **Feature Engineering:** Created new features from the existing data, such as extracting neighborhood data and analyzing the impact of minimum night requirements on price.
3.  **Geospatial Analysis:** Visualized the impact of latitude and longitude on pricing to identify premium neighborhoods across different cities.
4.  **Model Building:** Implemented Regression models (Linear Regression, Random Forest Regressor, and Gradient Boosting) to predict `price`.
5.  **Evaluation:** Evaluated model performance using RMSE (Root Mean Squared Error) and R-squared to ensure the predictions were within an acceptable margin of error.

## Business Impact
*   Provides a data-driven pricing baseline for new Airbnb listings.
*   Helps hosts identify underpriced amenities and optimize their availability calendar.
*   Allows for cross-city market comparison to identify the most profitable global locations for real estate investment.

## Status
🚧 **Work in Progress:** The Jupyter Notebook containing the regression pipeline and geospatial visualizations will be uploaded shortly.
