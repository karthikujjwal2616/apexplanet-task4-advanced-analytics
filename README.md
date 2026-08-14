# ApexPlanet Internship – Task 4: Advanced Analytics

## Overview

This project was completed as part of the ApexPlanet Software Pvt. Ltd. internship program.

Task 4 focuses on applying advanced analytics and machine learning techniques to analyze data, identify patterns, perform forecasting, create segments, and build predictive models.

## Objectives

The main objectives of this task are:

- Perform statistical analysis and hypothesis testing.
- Analyze and forecast time-series data.
- Segment data using K-Means clustering.
- Visualize clusters using PCA.
- Build and evaluate predictive machine learning models.
- Interpret results and document model limitations.

## Technologies Used

- Python
- Jupyter Notebook / VS Code
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn
- Statsmodels

## Project Sections

### 1. Statistical Analysis

The statistical analysis includes:

- Mean, median and mode
- Variance and standard deviation
- Skewness and kurtosis
- Confidence intervals
- T-test
- Chi-square test
- ANOVA
- Correlation analysis
- P-values and statistical significance

### 2. Time-Series Analysis

The time-series analysis includes:

- Date/time preparation
- Resampling
- Time-series visualization
- Moving averages
- Exponential smoothing
- Augmented Dickey-Fuller (ADF) stationarity test
- Time-series decomposition
- Trend analysis
- Seasonality analysis
- Residual analysis
- ARIMA forecasting
- Forecast evaluation using MAE, RMSE and MAPE

### 3. Customer Segmentation

K-Means clustering was applied to create five segments.

The process includes:

- Feature preparation
- Feature scaling using StandardScaler
- K-Means clustering
- Selection of five clusters
- Cluster evaluation
- PCA visualization
- Cluster profiling
- Segment interpretation
- Recommendations

### 4. Predictive Modeling

The following machine learning models were implemented:

#### Linear Regression

Used for numeric prediction and evaluated using:

- R²
- MAE
- RMSE

#### Logistic Regression

Used for binary classification and evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

#### Decision Tree

Used for classification and evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Feature importance was also analyzed using the Decision Tree model.

## Key Results

### Statistical Analysis

ANOVA was performed to compare fares across passenger classes.

The analysis produced a very small p-value, indicating a statistically significant difference in average fares between passenger classes.

### Time-Series Forecasting

The time-series model was evaluated using:

- MAE: approximately 2343.50
- RMSE: approximately 2352.60
- MAPE: approximately 10.05%

Time-series decomposition was also used to identify trend, seasonal and residual components.

### Predictive Modeling

Two classification models were compared:

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.692 | 0.659 | 0.500 | 0.569 | 0.733 |
| Decision Tree | 0.692 | 0.635 | 0.569 | 0.600 | 0.652 |

Logistic Regression achieved the higher ROC-AUC and Precision, while the Decision Tree achieved higher Recall and F1-Score.

## Limitations

- The analysis uses a limited set of features.
- The dataset is historical and may not represent other populations or datasets.
- Model performance depends on the quality and quantity of available data.
- Additional feature engineering and hyperparameter tuning could improve the models.
- The results show relationships within the dataset and should not automatically be interpreted as causal relationships.

## Project Structure

```text
Task_4/
│
├── Task_4_Advanced_Analytics.ipynb
├── dataset/
│   └── dataset.csv
│
├── reports/
│   ├── statistical_analysis/
│   ├── time_series/
│   ├── clustering/
│   └── predictive_modeling/
│
├── requirements.txt
└── README.md