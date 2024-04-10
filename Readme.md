# Time Series Analyses for Environmental Sciences

This repository contains a collection of time series analyses I've conducted as part of the course "71606 Time Series Analysis for Environmental Sciences" (link to the course website: [https://yairmau.com/time-series/](https://yairmau.com/time-series/)).

## Project Summary
This study investigates the environmental dynamics of the Hula Lake ecosystem in Israel, focusing on the relationship between water and vegetation factors and their impact on the energy balance and carbon emissions. The project aims to elucidate the differences in annual and daily ranges of various parameters between a water station and a vegetation station within the lake.

The analysis is divided into two parts:

### Near-Term Analysis

This part focuses on high-frequency meteorological data collected from October 2023 to February 2024. The analysis includes data preprocessing, comparison of daily trends between the water and vegetation stations, and cross-correlation analysis to quantify time differences.

### Long-Term Analysis
This part utilizes remotely sensed data from the Sentinel-2 satellite to generate time series of average NDVI (Normalized Difference Vegetation Index) values for the lake water and the vegetated island. The analysis involves smoothing, resampling, decomposition, and observation of annual trends in vegetation dynamics.

Throughout the project, rigorous scientific standards are maintained, employing appropriate statistical techniques and data visualization methods to effectively communicate the findings.

The overall goal is to provide an initial understanding of the differences in the annual and daily ranges of various parameters between the water and vegetation stations, paving the way for future forecasting and linking remote sensing data to physical parameters within the Hula Lake ecosystem.


### Tools and Functions Used

**Data Preprocessing:**
- Handling missing data
- Outlier detection and removal
- Date/time formatting

**Data Analysis:**
- Time series generation
- Trend and seasonality decomposition
- Cross-correlation analysis
- Smoothing and resampling techniques
- Stationarity
- Auto-Correlation
- Arima
