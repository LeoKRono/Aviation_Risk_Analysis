# Aviation Risk Analysis Project

## Project Overview

This project aims to analyze aviation accident data to identify aircraft with the lowest risk profiles. The analysis focuses on factors such as accident frequency, severity, and related variables to provide insights into which aircraft present the least safety, financial, and operational risks. The findings will guide decision-making in selecting suitable airplanes for acquisition and operation.

### Objectives

1. Identify airplane models with minimal risk profiles.
2. Analyze the severity and frequency of aviation accidents.
3. Examine factors contributing to these accidents.
4. Provide data-driven recommendations for selecting the safest airplane models.

## Data Source

The aviation accident dataset is sourced from Kaggle and originally obtained from the National Transportation Safety Board (NTSB). It contains comprehensive records of airplane accidents, including details such as:

- Accident Number
- Date and Location of the Accident
- Aircraft Make and Model
- Injury Severity
- Weather Conditions
- Flight Phase

### Dataset Structure

The dataset consists of **90,348 entries** and **31 columns**. Below are some key columns in the dataset:

- `event_id`: Unique identifier for the event
- `investigation_type`: Type of investigation (e.g., accident)
- `accident_number`: Unique identifier for the accident
- `event_date`: Date of the accident
- `location`: Location of the accident
- `country`: Country where the accident occurred
- `make`: Aircraft manufacturer
- `model`: Aircraft model
- `injury_severity`: Severity of injuries (e.g., fatal, serious, minor)
- `total_fatal_injuries`: Total number of fatal injuries
- `total_serious_injuries`: Total number of serious injuries
- `total_minor_injuries`: Total number of minor injuries
- `total_uninjured`: Total number of uninjured passengers
- `weather_condition`: Weather conditions at the time of the accident
- `broad_phase_of_flight`: Phase of flight during the accident

### Data Cleaning and Preparation

The following data cleaning steps were performed:

1. Removed duplicate entries based on the `accident_number` column.
2. Dropped columns with more than 35% missing values.
3. Dropped irrelevant columns for analysis.
4. Handled missing values by dropping rows or filling with 'Unknown' where appropriate.
5. Standardized representations of missing data.
6. Created a new column for the year of the accident for future analysis.

## Data Analysis

The analysis includes:

- Trend analysis of injuries and uninjured passengers over time.
- Grouping data by aircraft model and make to evaluate total injuries.
- Visualization of trends and injury statistics using bar charts and line plots.

## Results

- Trends indicate a general decrease in the severity and frequency of injuries over the years, suggesting improvements in aviation safety standards.
- Specific aircraft models and makes are identified for their injury statistics, providing insights into which aircraft may be safer for operation.

## Usage

The cleaned dataset is saved as `cleaned_aviation_data.csv` and can be used for further analysis or modeling.

## Conclusion

This project provides a comprehensive analysis of aviation accident data, offering valuable insights into aircraft safety. The findings can assist stakeholders in making informed decisions regarding aircraft acquisitions and operations.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Kaggle for providing the aviation accident dataset.
- National Transportation Safety Board for the original data source.
