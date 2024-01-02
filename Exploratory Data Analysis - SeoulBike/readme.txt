SeoulBike Dataset Analysis
This repository contains an exploratory analysis of the SeoulBike dataset, which includes bike rental data along with weather and date/time information. The analysis covers various aspects of the dataset, including data cleaning, visualization, clustering, feature selection, and regression modeling.

Overview
The SeoulBike dataset aims to predict bike rental demand based on weather conditions and other factors. It comprises 8760 records with 14 features and 1 label. Features include temperature, humidity, windspeed, visibility, dew point temperature, solar radiation, rainfall, snowfall, seasons, holiday, functioning day, hour, and date.

Analysis Highlights
Data Cleaning: Checked for missing values and renamed columns for clarity.
Visualization: Utilized histograms, scatter plots, bar charts, and box plots to visualize relationships between features and bike rentals.

Clustering: Employed K-means clustering and hierarchical clustering to identify patterns and segments in the data.

Classification: Utilized K-nearest neighbors (KNN) and logistic regression for predicting bike rental counts and assessing model accuracy.

Regression: Implemented linear regression and polynomial regression for predicting bike rental counts, considering various features.

Key Findings
Strong positive correlation between bike rentals and temperature/solar radiation.
Negative correlation between bike rentals and rainfall/snowfall.
Higher rentals during rush hours and weekends.
Bike rentals peak during warmer seasons.

Credits
This analysis is based on the SeoulBike dataset from UCI Machine Learning Repository.

License
The dataset used in this analysis may have its own licensing. Please refer to the original dataset source for licensing information.