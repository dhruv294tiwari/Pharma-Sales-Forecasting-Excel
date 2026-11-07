Pharma Sales Forecasting & Analytics Dashboard

An Excel-based pharmaceutical sales forecasting and analytics project focused on identifying historical sales trends, analysing monthly seasonality, predicting future demand, and evaluating forecasting performance across eight pharmaceutical drug categories.

Project Overview

The project analyses historical pharmaceutical sales data to understand demand patterns and develop a trend-based forecasting model using Microsoft Excel.

The objective is to transform historical sales records into actionable insights that can support sales analysis, demand planning, and business decision-making.

The project uses linear trend forecasting combined with monthly seasonal indices and compares its performance against a Seasonal Naive forecasting baseline.

Business Problem

Pharmaceutical companies need to understand how demand for different drug categories changes over time.

This project addresses the following questions:

* How do pharmaceutical sales change over time?
* Which drug categories experience stronger seasonal variations?
* Can historical sales trends help predict future demand?
* How accurately can future sales be forecasted?
* Does a trend-based forecasting model outperform a seasonal naive baseline?
* Which drug categories require different forecasting approaches?

Dataset

* Historical pharmaceutical sales data covering 2014–2019.
* Daily sales observations.
* Eight pharmaceutical drug categories.
* Monthly sales aggregation for trend and seasonality analysis.

Drug Categories Analysed

Category	Description
R03	Drugs for obstructive airway diseases
R06	Antihistamines
N02BE	Other analgesics and antipyretics
N05B	Anxiolytics
N05C	Hypnotics and sedatives
N02BA	Salicylic acid and derivatives
M01AE	Propionic acid derivatives
M01AB	Acetic acid derivatives

Tools & Technologies

* Microsoft Excel
* Pivot Tables
* Excel Formulas
* FORECAST.LINEAR
* Seasonal Index Calculation
* Trend Analysis
* MAPE (Mean Absolute Percentage Error)
* Excel Charts and Interactive Dashboards

Project Methodology

1. Data Preparation

* Imported and organised historical pharmaceutical sales records.
* Prepared monthly sales aggregations using Pivot Tables.
* Structured the dataset for category-wise analysis.

2. Trend Analysis

* Analysed historical monthly sales patterns.
* Calculated underlying sales trends.
* Used Excel’s FORECAST.LINEAR function to estimate future sales based on historical trends.

3. Seasonality Analysis

* Calculated monthly seasonal indices for each drug category.
* Identified months with relatively higher and lower demand.
* Used seasonal indices to adjust trend-based forecasts.

4. Sales Forecasting

Developed a forecasting approach combining linear trend predictions with monthly seasonal adjustments.

Forecasting Logic:

Final Forecast = Trend Forecast × Seasonal Index

The model was developed separately for all eight pharmaceutical categories.

5. Forecast Evaluation

Evaluated forecasting performance using Mean Absolute Percentage Error (MAPE).

Compared the trend-based forecasting model against a Seasonal Naive baseline.

The comparison helped identify categories where the developed model performed better and categories where the baseline performed better.

Forecasting Results

The model was evaluated across eight pharmaceutical categories.

Drug Category	Model MAPE	Naive MAPE	Better Performer
R03	23.43%	35.80%	Trend Model
R06	17.56%	23.34%	Trend Model
N02BE	10.27%	23.56%	Trend Model
N05B	38.24%	34.56%	Seasonal Naive
N05C	42.72%	63.89%	Trend Model
N02BA	18.63%	20.24%	Trend Model
M01AE	13.05%	12.03%	Seasonal Naive
M01AB	21.43%	12.96%	Seasonal Naive

Key Performance Findings

* The trend-based forecasting model outperformed the baseline in 5 out of 8 categories.
* Model success rate: 62.5%.
* Average Model MAPE: 23.17%.
* Average Seasonal Naive MAPE: 28.30%.
* N02BE achieved the lowest Model MAPE at 10.27%.

The average MAPE figures represent an unweighted average across the eight categories.

Excel Dashboard

An interactive Excel dashboard was developed to visualise forecasting performance and seasonal demand patterns.

Dashboard Features

1. Dynamic Drug Category Selection.
2. Model MAPE KPI.
3. Seasonal Naive MAPE KPI.
4. Forecast Improvement.
5. Seasonal Index Range.
6. Forecasting Verdict.
7. Peak Demand Month.
8. Actual vs Forecast Line Chart.
9. Monthly Seasonal Index Chart.
10. Forecast Accuracy Comparison Chart.

Dashboard Screenshots

Add your screenshots in the Screenshots folder and display them here.

Main Dashboard

Forecast Accuracy Comparison

Forecasting Model

Key Business Insights

* Pharmaceutical categories exhibit different monthly demand patterns.
* Seasonal indices help identify recurring variations in monthly sales.
* Forecasting performance differs across drug categories.
* A single forecasting approach may not be equally effective for every category.
* Comparing model performance against a baseline helps identify where alternative forecasting methods may be more suitable.

Limitations

* The forecasting approach uses linear trend estimation and seasonal indices.
* Forecasting performance may vary with changing demand patterns.
* The analysis uses historical sales data rather than actual inventory records.
* Stock-out probability and actual inventory requirements cannot be established without inventory and supply-chain data.
* Forecast accuracy is evaluated on a historical holdout period and may not represent future performance.

Future Improvements

* Explore advanced forecasting models such as ARIMA and Prophet using Python.
* Evaluate forecasting performance using rolling-origin validation.
* Investigate the relationship between seasonal strength and forecasting accuracy.
* Incorporate actual inventory data for stock-out risk analysis.
* Develop automated forecasting and reporting workflows.

Project Files

The repository contains the Excel workbook, dataset (where redistribution is permitted), dashboard screenshots, and project documentation.

Author

Dhruv Tiwari

B.Tech – Electronics & Communication Engineering

Aspiring Data Analyst | Excel | SQL | Python | Power BI

GitHub Profile

LinkedIn Profile
