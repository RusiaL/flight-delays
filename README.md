# Flight Delays and Cancellations

This repository contains an analysis of flight delays and cancellations in the United States using data from 2015. The goal of this project is to explore patterns in flight performance, understand factors contributing to delays, and build predictive models.

## Dataset

The dataset is provided by the **U.S. Department of Transportation (DOT) Bureau of Transportation Statistics** and tracks the on-time performance of domestic flights operated by large air carriers. It includes summary information on the number of:

- On-time flights  
- Delayed flights  
- Canceled flights  
- Diverted flights  

The data is publicly available and was downloaded from [Kaggle: US DOT Flight Delays](https://www.kaggle.com/datasets/usdot/flight-delays).

### Key Features

Some of the features in the dataset include:

- `FlightDate` – Date of the flight  
- `Carrier` – Airline carrier code  
- `FlightNum` – Flight number  
- `Origin` / `Dest` – Origin and destination airports  
- `DepDelay` / `ArrDelay` – Departure and arrival delays (in minutes)  
- `Cancelled` – Indicator for canceled flights  
- `Diverted` – Indicator for diverted flights  

## Project Overview

The project focuses on:

1. **Exploratory Data Analysis (EDA)** – Understanding delay patterns by airline, airport, day of the week, and month.  
2. **Data Cleaning and Feature Engineering** – Handling missing values, creating relevant features for analysis and prediction.  
3. **Predictive Modeling** – Building models to predict flight delays and cancellations using machine learning techniques.  
4. **Visualization** – Presenting insights using charts, plots, and dashboards.  

## Notebooks

The repository contains the following notebooks:

- **01_data.ipynb** – Short overview of the dataset, basic structure, and feature descriptions.  
- **02_eda.ipynb** – Exploratory data analysis with basic statistics and visualizations of flight delays and cancellations.  
- **03_modeling.ipynb** – Predictive modeling using logistic regression to classify flights as delayed or on-time.  

## License

This repository is provided for educational and personal use.
