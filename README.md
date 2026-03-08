# Patient Survival Analysis using Exploratory Data Analysis

## Project Overview

This project analyzes a clinical healthcare dataset containing records of **over 9,000 critically ill patients** to investigate factors affecting patient survival and medical outcomes. 

The analysis focuses on **2-month and 6-month survival rates**, identifying relationships between demographic factors, medical conditions, laboratory results, and healthcare indicators.

Using Python and exploratory data analysis techniques, the project extracts insights from complex clinical data to better understand patterns related to survival outcomes and disease trends.

## Dataset

The dataset includes information on **9105 critically ill patients** and consists of **48 variables**, including both numerical and categorical medical attributes. 

Key variables include:

* Patient demographics (age, gender, race)
* Medical conditions and disease categories
* Laboratory test results
* Coma scores and clinical indicators
* Hospital costs and healthcare metrics
* Survival predictions and doctor survival estimates

## Data Preprocessing

Before analysis, several data cleaning steps were performed:

* Handling **missing values in medical test results**
* Correcting **formatting inconsistencies**
* Converting categorical variables stored as numeric
* Removing duplicates
* Transforming discrete numeric values into appropriate formats
* Grouping variables for meaningful visualizations

These preprocessing steps ensured reliable and accurate analysis.

## Exploratory Data Analysis

The project applies multiple EDA techniques to uncover patterns in patient data:

* Descriptive statistical analysis
* Outlier detection
* Correlation analysis
* Chi-square statistical testing
* Data visualisation using histograms, density plots, scatter plots, and heatmaps

These techniques help identify relationships between medical variables and survival outcomes.

## Key Insights

The analysis revealed several important healthcare insights:

* Strong correlations exist between **model survival predictions and doctor survival estimates**.
* **Longer hospital stays tend to result in higher hospital charges.**
* Patients aged **60–80 show the highest concentration of critical conditions.**
* Higher **TISS scores are associated with increased ICU costs.**
* Diabetes and glucose levels show significant variation across age groups.
* Female patients showed higher diabetes prevalence in older age groups.

These findings demonstrate how data analysis can help identify trends in healthcare data and support medical decision-making.

## Tools and Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

## Key Visualizations

The project includes several visualizations to explore patient data:

* Distribution plots for clinical variables
* Correlation heatmaps
* Boxplots for outlier detection
* Scatter plots for variable relationships
* Age group and disease pattern analysis

## Future Improvements

Potential extensions of this project include:

* Building **machine learning models for survival prediction**
* Applying **feature importance analysis**
* Creating **interactive healthcare dashboards**
* Integrating additional clinical datasets for deeper analysis

