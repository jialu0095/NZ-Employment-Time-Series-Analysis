# NZ-Employment-Time-Series-Analysis
The main goal of the study is to develop a reliable forecasting model capable of predicting future employee numbers in the finance and insurance industry of New Zealand. 

# **Data description**

The Household Labour Force Survey (HLFS) is a quarterly survey conducted by Statistics New Zealand. It measures the numbers of employed and unemployed people, those not in the labour force, and the official unemployment rate for New Zealand.

The `employed.csv` file contains information about the number of people employed (in thousands) by ANZSIC06 industry group in New Zealand. The data set contains measurements from 2003 Q1 until 2021 Q1.

# Collaborative Workflow

At the start of this group project, discuss the optimal workflow with group members. Options include drafting the report in Google Docs or using Overleaf. To share and edit R code or an RMarkdown file among group members, consider setting up a Github repository.
The allocated time series in employed.csv serves as the training set. A test set with the remaining h=8 quarters of data (from 2021 Q2 until 2023 Q1) will be available on Canvas 48-hours before the deadline.

The group is required to draft a report, detailing the analytical steps taken for the allocated time series (i.e., actions taken and their rationale). The report should encompass the following elements:

- Analyze the statistical features of the original time series (e.g., trend-cycle, seasonality, variability, structural breaks, etc).
- Detail any transformations and differencing applied.
- Investigate various time series models for the data. Describe the methodology employed to curate a list of suitable candidate ARIMA models and ETS models. Both manual and automatic fitting are expected. Other relevant benchmark forecasting methods discussed in the course can also be included.
- Compare the curated models using AICc and discuss the superior models. Exercise caution during these comparisons as some models might not be directly comparable.
- Select one ARIMA model and one ETS model based on the analysis and document the fitted models.
- Generate residual diagnostics (plots and Ljung-Box test) for the selected models and discuss the adherence to model assumptions.
- Forecast (point-forecasts and prediction intervals) for the h=8 quarters up to and including 2023 Q1 using the selected models.
- Upon the release of the test set on Canvas 48-hours before the deadline, match the forecasts with the test set to evaluate model precision.
- Discuss the forecasting performance of the models.
- Delve into the advantages and drawbacks of the models chosen for the allocated time series.
- Clearly state the contribution of each group member to the project.
- Ensure graphs are labeled correctly and are referenced within the text during interpretation.
