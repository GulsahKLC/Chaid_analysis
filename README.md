# Air Quality and Pollution Assessment

This repository contains a comprehensive analysis of environmental metrics and demographic insights for predicting air quality. The primary objective is to assess various factors contributing to air pollution and identify key variables that influence air quality predictions.

## Key Insights from CHAID Analysis

### 1. **CO (Carbon Monoxide)** – Most Important Variable:
   - **CO** is identified as the most important variable for predicting air quality. It appears at the root of the CHAID decision tree, which signifies its strong influence on air quality outcomes.
   - The CHAID analysis uses the chi-squared test to split the data based on this variable, highlighting its significant relationship with air quality.

### 2. **NO2 (Nitrogen Dioxide)** – Second Most Important Variable:
   - **NO2** follows CO in importance, continuing to split data into further subgroups, especially in branches where CO levels vary.
   - The presence of **NO2** in these splits demonstrates its secondary importance in determining air quality.

### 3. **Population Density** – Third Most Important Variable:
   - **Population Density** is another significant factor, influencing air quality predictions in combination with both CO and NO2.
   - The density of population contributes to the variance in air quality, indicating its importance in the model.

### 4. **SO2 (Sulfur Dioxide)** – Fourth Most Important Variable:
   - **SO2** is also a notable variable, contributing to the data splits particularly in branches where CO levels are involved.
   - This shows that sulfur dioxide plays an important role in assessing air quality in specific conditions.

### 5. **PM10 (Particulate Matter 10)** – Fifth Most Important Variable:
   - **PM10** is identified as an important variable in certain branches, helping further refine air quality predictions in areas with specific pollution levels.


## Overview of the Analysis

The CHAID analysis demonstrates the relationships between different pollutants and air quality, providing insights into how various environmental and demographic factors impact air quality. The key variables identified include:

1. **CO (Carbon Monoxide)**
2. **NO2 (Nitrogen Dioxide)**
3. **Population Density**
4. **SO2 (Sulfur Dioxide)**
5. **PM10 (Particulate Matter 10)**

These variables are prioritized based on their influence on air quality, with CO being the most critical factor for predicting air pollution.



### Repository Structure
- **Data**: Contains raw and processed datasets related to air quality and pollution metrics.
- **Analysis**: Includes scripts and Jupyter notebooks used to perform CHAID and other analyses.
- **Models**: Contains machine learning models built for predicting air quality based on the identified key variables.
- **Results**: Contains visualizations and reports from the analysis.


This structure provides a clear understanding of the repository's purpose and the CHAID analysis results, making it easy for users to navigate and understand the findings.
![image](https://github.com/user-attachments/assets/8c32e274-daf5-4be6-8e53-0ca83af161e9)
