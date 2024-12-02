# Aircraft Risk Analysis

## Overview
This project analyzes aviation accident data to identify airplanes with the lowest risk for a company planning to enter the aviation industry. The analysis is conducted using a dataset sourced from Kaggle, which contains detailed records of airplane accidents, including accident frequency, severity, and contributing factors.

## Table of Contents
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Data Analysis](#data-analysis)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

## Business Understanding
The company intends to diversify its assets by purchasing and operating airplanes for commercial and private enterprises. The objective is to minimize safety and financial liabilities by identifying the safest and most reliable airplane models. 

### Goals
1. Identify low-risk airplane models.
2. Evaluate the severity and frequency of accidents.
3. Assess factors contributing to accidents.
4. Provide recommendations for selecting the best airplanes based on data analysis.

## Data Understanding
The dataset used for this analysis is the [Aviation Accident Database](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) obtained from Kaggle, which includes:
- Accident Number
- Event Date
- Location
- Make and Model of the Aircraft
- Severity of Injuries
- Weather Conditions
- Phase of Flight
- Other relevant factors

## Data Preparation
The data preparation process includes:
- Cleaning column names for easier access.
- Checking for and removing duplicate entries.
- Handling missing values by dropping or filling with appropriate substitutes.
- Standardizing data representations.

## Data Analysis
The analysis includes:
- Trend analysis of injuries and uninjured passengers over time.
- Evaluating injuries by plane model, make, amateur-built status, engine type, and number of engines.
- Correlation analysis to understand the relationship between the number of engines and injuries.

## Conclusion
Accidents are inevitable in aviation, but certain factors such as make, model, and engine type can influence the likelihood of injuries. The analysis indicates that the number of engines does not correlate with the number of injuries.

## Recommendations
Based on the findings, the following recommendations are made for the company:
- **Model of Aircraft**: Consider model 737 due to its high number of uninjured passengers.
- **Make of Aircraft**: Focus on Boeing for its safety record.
- **Type of Aircraft**: Prefer professionally built planes over amateur-built ones.
- **Engine Type**: Turbo tan engines show favorable outcomes in terms of uninjured passengers.

## Installation
To run this notebook, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required libraries: pandas, numpy, matplotlib, seaborn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn
