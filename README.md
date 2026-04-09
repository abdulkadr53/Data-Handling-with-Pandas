# Titanic Survival Analysis — Data Handling with Pandas

This Task explores the famous Titanic dataset using only **pandas** for data analysis . This Task demonstrates practical data handling skills with Pandas, extracting meaningful insights from raw data.
--

## Project Summary

This Task analyzes passenger data from the Titanic disaster to uncover patterns that influenced survival rates. It highlights key data science steps:

* Data cleaning and preprocessing
* Handling missing values and outliers
* Feature engineering
* Exploratory Data Analysis 
* Insight generation using Pandas
---
## Objectives

* Understand the structure and quality of real-world datasets
* Clean and prepare messy data for analysis
* Explore relationships between features and survival
* Derive actionable insights using Pandas
----
## Dataset

* Name: Titanic Dataset
* Records: 891 passengers
* Features: 12 columns (Age, Sex, Pclass, Fare, etc.)
* Target Variable: Survived
---

## Key Skills Demonstrated

* Data Cleaning (handling missing values, dropping irrelevant features)
* Exploratory Data Analysis
* Feature Engineering (AgeGroup creation)
* Groupby Aggregations
* Data Filtering & Querying
* Statistical reasoning (mean vs median, IQR method)
---

## Data Cleaning Process

* Filled missing Age values using median (robust to outliers)
* Filled missing Embarked values using mode
* Dropped Cabin column due to excessive missing data
* Verified dataset integrity (no duplicates found)
---

##  Exploratory Data Analysis

* Survival Rate by Gender
    * Female: ~74% survival
    * Male: ~19% survival
* This indicates strong gender-based survival bias
---
* Survival Rate by Passenger Class
    * 1st Class: ~63%
    * 2nd Class: ~47%
    * 3rd Class: ~24%
*Higher socio-economic class increased survival chances
---
* Survival by Age Group

* Custom age categories created using `pd.cut()`:
    * Children had the highest survival rate
    * Seniors had the lowest survival rate
-----
Created a new feature:

* AgeGroup
    * Child
    * Teen
    * Adult
    * Middle-aged
    * Senior
* This improved interpretability of age-based patterns.
----
## Key Insights

* Gender is the strongest predictor of survival
* Passenger class significantly affects outcomes
* Younger passengers had higher survival rates
* Data cleaning decisions (e.g., median vs mean) impact results
---
## Tech Stack

* Python
* Pandas
* Jupyter Notebook
---
## Folder Structure
```
 Data-Handling-with-pandas/
 |
 ├── Titanic-dataset.ipynb
 └── README.md
```
---
## How to Run
```
git clone https://github.com/abdulkadr53/Data-Handling-with-Pandas.git
cd Data-Handling-with-Pandas.git
jupyter notebook
```
----
Abdulkadr Heyredin

Submitted: CSE-Data Science Task 3 submission

