# CodeAlpha - Indian Unemployment Analysis

A data analysis and visualization project focused on understanding unemployment trends in India using Python, Pandas, NumPy, and Matplotlib.

This project was completed as part of the **CodeAlpha Data Analytics Internship – Task 2**.

---

## Project Overview

The objective of this project is to analyze unemployment data across different regions and areas of India and identify important trends, patterns, and variations in unemployment rates.

The analysis covers:

- Data cleaning and preprocessing
- Missing value handling
- Duplicate detection and removal
- Statistical analysis
- Regional unemployment comparison
- Rural vs Urban analysis
- Monthly unemployment trends
- 2019 vs 2020 comparison
- COVID-19 period analysis
- Data visualization
- Key findings and conclusions

---

## Objectives

The major objectives of this project are:

1. Clean and prepare the unemployment dataset.
2. Analyze overall unemployment statistics.
3. Compare unemployment rates across different regions.
4. Compare Rural and Urban unemployment.
5. Analyze monthly unemployment trends.
6. Compare unemployment rates between 2019 and 2020.
7. Study the increase in unemployment during March–June 2020.
8. Create meaningful visualizations to communicate insights.

---

## Dataset

The analysis uses an Indian unemployment dataset containing information related to:

- **Region**
- **Date**
- **Frequency**
- **Estimated Unemployment Rate (%)**
- **Estimated Employed**
- **Estimated Labour Participation Rate (%)**
- **Area**

### Dataset Information

After cleaning:

- **Rows:** 740
- **Columns:** 7
- **Missing Values:** 0
- **Duplicate Rows:** 0

The dataset contains observations covering the available period from **2019 to 2020**.

> Note: The analysis is based only on the observations available in the provided dataset.

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

### 1. Column Name Cleaning
Leading and trailing spaces were removed from column names.

### 2. Missing Value Analysis
Missing values were identified across all columns.

The dataset initially contained **28 incomplete rows**.

### 3. Incomplete Row Removal
Completely blank/incomplete records were removed because they did not contain useful analytical information.

### 4. Duplicate Detection
Duplicate records were identified and removed.

### 5. Date Conversion
The `Date` column was converted from object/string format into a proper datetime format.

### 6. Frequency Validation
Unique values in the `Frequency` column were inspected to ensure data consistency.

### 7. Final Data Quality Check
The cleaned dataset was verified to ensure:

- No missing values
- No duplicate records
- Correct data types
- Consistent structure

---

## Exploratory Data Analysis

Several statistical analyses were performed to understand unemployment patterns.

### Overall Unemployment

The overall average unemployment rate in the analyzed dataset was:

**11.79%**

### Year-wise Comparison

| Year | Average Unemployment |
|------|----------------------|
| 2019 | 9.40% |
| 2020 | 15.10% |

The available 2020 observations show a considerably higher unemployment rate compared with 2019.

---

## Regional Analysis

Average unemployment rates were calculated for each region.

### Highest Average Unemployment

**Tripura — 28.35%**

### Lowest Average Unemployment

**Meghalaya — 4.80%**

This demonstrates substantial variation in unemployment levels across different regions.

---

## Rural vs Urban Analysis

Average unemployment rates were compared between Rural and Urban areas.

| Area | Average Unemployment |
|------|----------------------|
| Urban | 13.17% |
| Rural | 10.32% |

The analyzed dataset shows a higher average unemployment rate in **Urban areas** compared with Rural areas.

---

## Monthly Trend Analysis

Monthly unemployment rates were analyzed to identify changes over time.

The analysis shows a significant increase in unemployment during early 2020, particularly around **April and May 2020**.

### Peak Month

**May 2020 — 24.88%**

The unemployment rate increased sharply during the March–June 2020 period before declining in June.

---

## COVID-19 Period Analysis

The analysis compares unemployment during the early 2020 period with the March–June 2020 period.

| Period | Average Unemployment |
|--------|----------------------|
| Jan–Feb 2020 | 9.96% |
| Mar–Jun 2020 | 17.77% |

### Increase

**7.82 percentage points**

### Relative Increase

**78.50%**

This indicates a substantial increase in unemployment during the March–June 2020 period within the available dataset.

---

##  Visualizations

The following visualizations were created during the analysis to understand unemployment patterns, regional differences, time-based trends, and the impact of the March–June 2020 period.

---

### 1. Unemployment Rate Distribution

This histogram shows the distribution of estimated unemployment rates across the available observations.

![Unemployment Rate Distribution](Visualizations/unemployment_distribution.png)

---

### 2. Average Unemployment Rate by Region

This horizontal bar chart compares the average unemployment rate across different Indian regions.

![Average Unemployment Rate by Region](Visualizations/average_unemployment_by_region.png)

---

### 3. Monthly Unemployment Rate Trend

This line chart shows how the average unemployment rate changed over the analyzed period.

![Monthly Unemployment Rate Trend](Visualizations/monthly_unemployment_trend.png)

---

### 4. Rural vs Urban Unemployment Trend

This visualization compares unemployment trends between Rural and Urban areas.

![Rural vs Urban Unemployment Trend](Visualizations/rural_vs_urban_trend.png)

---

### 5. Average Unemployment Rate by Month

This chart highlights the average unemployment rate for each month and clearly shows the sharp increase during April and May 2020.

![Average Unemployment Rate by Month](Visualizations/average_unemployment_by_month.png)

---

### 6. Early 2020 vs March–June 2020

This comparison shows the significant increase in unemployment between January–February 2020 and March–June 2020.

![Early 2020 vs March-June 2020](Visualizations/early_2020_vs_mar_jun_2020.png)

---

## Key Findings

1. Overall average unemployment rate was **11.79%**.
2. Average unemployment during available 2019 observations was **9.40%**.
3. Average unemployment during available 2020 observations was **15.10%**.
4. Jan–Feb 2020 average unemployment was **9.96%**.
5. Mar–Jun 2020 average unemployment increased to **17.77%**.
6. The increase was **7.82 percentage points**.
7. The relative increase was approximately **78.50%**.
8. **May 2020** recorded the highest monthly unemployment rate at approximately **24.88%**.
9. **Tripura** had the highest average regional unemployment at **28.35%**.
10. **Meghalaya** had the lowest average regional unemployment at **4.80%**.
11. Urban areas recorded an average unemployment rate of **13.17%**.
12. Rural areas recorded an average unemployment rate of **10.32%**.

---

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Collab Notebook**

---

## Project Structure

```text
CodeAlpha_Unemployment_Analysis/
│
├── dataset/
│   └── unemployment.csv
│
├── visualizations/
│   ├── unemployment_distribution.png
│   ├── average_unemployment_by_region.png
│   ├── monthly_unemployment_trend.png
│   ├── rural_vs_urban_trend.png
│   ├── average_unemployment_by_month.png
│   └── early_2020_vs_mar_jun_2020.png
│
├── CodeAlpha_Task2_Unemployment_Analysis.ipynb
│
└── README.md
