# Sleep Health and Lifestyle Dataset - Assignment 1

## Dataset Name
Sleep Health and Lifestyle Dataset

## Source
Kaggle

## File Included
- `Sleep_health_and_lifestyle_dataset.csv`

## Description
This dataset contains information related to sleep habits, lifestyle, and health indicators for different individuals. It includes demographic data, occupation, sleep duration, sleep quality, physical activity, stress level, BMI category, blood pressure, heart rate, daily steps, and sleep disorder status.

## Number of Rows and Columns
- Rows: 374
- Columns: 13

## Main Columns
- Person ID
- Gender
- Age
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Blood Pressure
- Heart Rate
- Daily Steps
- Sleep Disorder

## Cleaning Performed
- Filled missing values in `Sleep Disorder` with `None`
- Standardized `BMI Category` by replacing `Normal Weight` with `Normal`
- Split `Blood Pressure` into:
  - `Systolic BP`
  - `Diastolic BP`

## Purpose of Analysis
The purpose of this analysis is to explore how sleep duration, sleep quality, stress, physical activity, and health measurements relate to one another. The dataset is suitable for EDA because it contains both categorical and numerical variables that allow for univariate, bivariate, and correlation analysis.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
