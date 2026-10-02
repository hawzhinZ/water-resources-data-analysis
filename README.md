# Water Resources Data Analysis

## Project Overview

This project demonstrates a complete data analysis workflow using annual rainfall and mean temperature data.

The analysis includes data cleaning, exploratory data analysis, visualization, correlation analysis, linear regression, prediction, and model evaluation.

## Dataset

The dataset contains annual observations from 2019 to 2025 with the following variables:

* **Year**
* **Annual Rainfall (mm)**
* **Mean Temperature (°C)**

A missing rainfall value was identified and handled during the data-cleaning process.

## Analysis Workflow

1. Data inspection and cleaning
2. Handling missing values
3. Descriptive statistics
4. Data visualization
5. Correlation analysis
6. Scatter plot analysis
7. Linear regression
8. Rainfall prediction
9. Error analysis
10. Train/Test evaluation
11. Model performance evaluation using MAE and R²

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Model Evaluation

A linear regression model was trained using data from **2019–2023** and evaluated on the later observations from **2024–2025**.

Test results:

* **MAE:** 35.21 mm
* **R²:** 0.117

Because the dataset contains only seven observations, these evaluation results should be interpreted cautiously. The project is primarily intended to demonstrate the data-analysis and machine-learning workflow.

## Repository Structure

```text
water-resources-data-analysis/
│
├── data/
├── images/
├── notebooks/
│   └── water_data_analysis.ipynb
└── README.md
```

## Key Skills Demonstrated

* Data cleaning and preprocessing
* Missing-value handling
* Exploratory Data Analysis (EDA)
* Data visualization
* Correlation analysis
* Linear regression
* Model prediction
* Model evaluation
* Python data analysis
* Working with environmental and water-resources data

