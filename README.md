# Data-Cleaning-&-Exploratory-Data-Analysis on Layoffs Dataset by using SQL


## Overview

This project demonstrates the complete data preparation and analysis process using SQL on a real-world layoffs dataset. The goal was to clean raw data, improve data quality, and perform exploratory data analysis to uncover trends and patterns related to workforce reductions across companies, industries, countries, and time periods.

The project is divided into two stages:

* Data Cleaning
* Exploratory Data Analysis (EDA)

---

## Tools & Technologies

* MySQL
* SQL
* Window Functions
* Common Table Expressions (CTEs)
* Joins
* Aggregate Functions

---

## Dataset Information

The dataset contains information about layoffs reported by companies worldwide, including:

* Company Name
* Industry
* Location
* Country
* Total Employees Laid Off
* Percentage of Workforce Laid Off
* Funding Raised
* Company Stage
* Layoff Date

---

## Data Cleaning

The first phase focused on preparing the dataset for analysis by improving its quality and consistency.

### Tasks Performed

* Created staging tables to preserve the original data.
* Identified and removed duplicate records using window functions.
* Standardized company, industry, and country values.
* Converted date fields into a proper date format.
* Handled missing and incomplete values.
* Removed records that contained insufficient information.
* Eliminated temporary columns used during the cleaning process.

### SQL Concepts Used

* ROW_NUMBER()
* CTEs
* Self Joins
* UPDATE Statements
* DELETE Statements
* String Functions
* Date Functions

---

## Exploratory Data Analysis (EDA)

After cleaning the data, exploratory analysis was performed to identify meaningful trends and insights.

### Analysis Conducted

#### Company Analysis

* Identified companies with the highest number of layoffs.
* Compared workforce reductions across organizations.

#### Industry Analysis

* Determined which industries experienced the largest layoffs.
* Examined industry-level workforce trends.

#### Country Analysis

* Analyzed layoffs across different countries.
* Compared the impact of layoffs by region.

#### Time-Based Analysis

* Evaluated yearly and monthly layoff trends.
* Identified periods with significant workforce reductions.

#### Company Stage Analysis

* Compared layoffs across different stages of company growth.
* Examined trends among startups, private companies, and public organizations.

#### Ranking Analysis

* Ranked top companies by layoffs for each year using window functions.
* Generated cumulative layoff trends through rolling calculations.

---

## Key Insights

* Identified companies responsible for the largest workforce reductions.
* Highlighted industries most affected by layoffs.
* Revealed countries with the highest layoff counts.
* Tracked layoff trends across multiple years.
* Analyzed workforce reductions based on company growth stages.

---

## Skills Demonstrated

* SQL Query Writing
* Data Cleaning
* Data Transformation
* Data Validation
* Exploratory Data Analysis
* Window Functions
* Joins
* CTEs
* Aggregation Techniques
* Business Insight Generation

---

## Project Outcome

This project showcases how SQL can be used to transform raw data into a reliable and analysis-ready dataset. By combining data cleaning techniques with exploratory analysis, meaningful insights were generated to better understand layoff patterns across industries, companies, and regions.

The project strengthened practical SQL skills and provided hands-on experience with real-world data preparation and analysis workflows.

---

## Repository Structure

```text
Data-Cleaning-and-Exploratory-Data-Analysis-on-Layoffs-Dataset/
│
├── Data Cleaning.sql
├── Exploratory Data Analysis.sql
├── README.md
└── layoffs.csv
```

