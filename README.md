# Cowboy-Cigarettes-Time-Series-Sales-Analysis
Brief
You're working in the US federal government as a data scientist in the Health and Environment department. You've been tasked with determining whether sales for the oldest and most powerful producers of cigarettes in the country are increasing or declining.

Cowboy Cigarettes (TM, est. 1890) is the US's longest-running cigarette manufacturer. Like many cigarette companies, however, they haven't always been that public about their sales and marketing data. The available post-war historical data runs for only 11 years after they resumed production in 1949; stopping in 1960 before resuming again in 1970. Your job is to use the 1949-1960 data to predict whether the manufacturer's cigarette sales actually increased, decreased, or stayed the same. You need to make a probable reconstruction of the sales record of the manufacturer - predicting the future, from the perspective of the past - to contribute to a full report on US public health in relation to major cigarette companies.

The results of your analysis will be used as part of a major report relating public health and local economics, and will be combined with other studies executed by your colleagues to provide important government advice.

As ever, this notebook is tiered, meaning you can elect that tier that is right for your confidence and skill level. There are 3 tiers, with tier 1 being the easiest and tier 3 being the hardest.

## 1. Sourcing and loading

Load relevant libraries
Load the data
Explore the data
## 2. Cleaning, transforming and visualizing

Dropping unwanted columns
Nomenclature
Type conversions
Making a predictor variable y
Getting summary statistics for y
Plotting y
## 3. Modelling

Decomposition
Trend
Seasonality
Noise
Testing for stationarity with KPSS
Making the data stationary
The ARIMA Model
Make a function to find the MSE of a single ARIMA model
Make a function to evaluate the different ARIMA models with different p, d, and q values
Visualize the results
Application: Forecasting
## 4. Evaluating and concluding

What is our conclusion?
Next steps
