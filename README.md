Data
The dataset used for this project is from Kaggle
The data contained 6 files as described below
country_wise_latest.csv: This file contains the latest COVID-19 statistics for each country, including the number of confirmed cases, deaths, and recoveries.
covid_19_clean_complete.csv: This file provides a dataset with detailed information on COVID-19 cases, deaths, and recoveries, cleaned and consolidated from various sources
worldometer_data.csv: This file includes country-level COVID-19 data sourced from worldometer, such as total cases, new cases, total deaths, new deaths, and other relevant statistics.
usa_county_wise.csv: This file contains COVID-19 data at the county level for the United States, including daily case counts, deaths, and recoveries for each county.
full_grouped.csv: This file aggregates COVID-19 data by day and by country, including province/state and county levels where applicable.
day_wise.csv: This file provides daily COVID-19 statistics without country-level data, focusing on the number of cases, deaths, and recoveries over time.
Data Cleaning
Handling Missing Values: Missing values were imputed for any of the dataset with missing values.
Handling Duplicates: We checked for duplicates in the dataset, and discovered they did not contain duplicate values
Standardizing formats: Dates that were in string object formats were standardized to datetime object.
Data Transformation
Feature Engineering: New features such as rolling average of confirmed cases, growth rate and mortality ratio were created after the data for Nigeria was extracted.
Normalization and scaling: Continuous variables were normalized to bring them to a similar scale, which helps in improving model performance
