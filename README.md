## Contributors
- Sharon Njeri - Project Lead & Developer
  
## Livestock Price Modeling with R

This repository contains code and data for a basic livestock price modeling project using R. The objective is to showcase proficiency in R programming, data analysis, and basic time series modeling techniques.

## Overview

Livestock prices are influenced by various factors, including seasonal patterns and external factors such as drought. This project aims to analyze historical livestock prices and develop models to predict future prices based on these factors. Therefore, getting an insight on the best time to sell the livestock.

## Data

The dataset used in this project (`Makert Prices 2022.xlsx`) contains historical market prices for different types of livestock, including Bull, Cow, Heifer, and Steer. Each entry includes the date, season, and corresponding prices.

## Analysis

### Exploratory Analysis

- The dataset was initially explored to understand its structure and characteristics.
- Summary statistics were calculated for each livestock type to gain insights into price distributions and trends.

### Modeling

- ARIMA (AutoRegressive Integrated Moving Average) models were fitted for each type of livestock, incorporating seasonal variables (Drought, Wet, Dry) as external regressors.
- The models were trained using historical data and evaluated based on their performance metrics and coefficient estimates.

### Forecasting

- Future price forecasts were generated for the next 12 months using the trained ARIMA models and seasonality data.
- Visualization techniques, such as line plots, were employed to display historical prices alongside forecasted trends for each livestock type.

## Results

- The ARIMA models indicated potential relationships between livestock prices and seasonal factors, such as drought.
- However, the models exhibited varying degrees of uncertainty, as indicated by the large standard errors associated with coefficient estimates.
- Future price forecasts provided insights into potential price trends, allowing stakeholders to make informed decisions regarding selling strategies.

## Code Organization

- `livestock_price_modeling.Rmd`: R Markdown document containing annotated code for data loading, exploratory analysis, modeling, and forecasting.
- `Makert Prices 2022.xlsx`: Excel file containing the market price data for livestock.
- `README.md`: This README file providing an overview of the project.

## Dependencies

- dplyr
- ggplot2
- forecast
- readxl

## Instructions

To replicate the analysis:

1. Ensure R and required packages are installed on your system.
2. Clone or download the repository to your local machine.
3. Open `livestock_price_modeling.Rmd` in RStudio or any compatible IDE.
4. Run the code chunks sequentially to reproduce the analysis.
5. Explore the results and modify the code as needed for further analysis or customization.


