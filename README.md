# Titanic Dataset Exploratory Analysis (EDA)

This project is an exploratory data analysis (EDA) of the Titanic dataset. The goal is to gain initial insights into passenger information and understand factors that might have influenced survival chances. Data Science and Data Analyst mini bootcamp (Dibimbing: Digital Skill Fair 38)

## Project Description

This analysis focuses on the Titanic dataset to explore passenger information, specifically the `Survived`, `Name`, `Sex`, and `Age` columns[cite: 2]. The primary objective is to understand the distribution of data and identify potential relationships between variables[cite: 3].

## Goals

* Understand the distribution of Titanic data (age, gender, etc.)[cite: 3].
* Analyze patterns and relationships between variables[cite: 3].
* Handle missing and duplicate data[cite: 4].
* Discover initial insights for further analysis[cite: 4].

## Workflow

1.  **Data Understanding:** Examine data structure, distribution, and statistics[cite: 5].
2.  **Data Cleaning:** Remove duplicates and handle missing values[cite: 5].
3.  **Exploratory Data Analysis:** Visualize distributions and analyze variable relationships[cite: 6].
4.  **Insight & Interpretation:** Summarize data and identify influential factors[cite: 6].

## Dataset Overview

The Titanic dataset contains 500 rows and 4 columns: `survived`, `name`, `sex`, and `age`[cite: 7].

The dataset includes passenger information such as:

* `survived`: Survival status (0 = No, 1 = Yes)
* `name`: Passenger name
* `sex`: Passenger gender
* `age`: Passenger age [cite: 7, 8]

## Data Sample

* Top 5 rows of the dataset are displayed[cite: 9, 10].
* Bottom 5 rows of the dataset are displayed[cite: 11, 12].
* 5 random rows of the dataset are displayed[cite: 13, 14].

## Dataset Information

* The dataset has dimensions of 500 rows and 4 columns[cite: 15].
* Columns and their data types:
    * `survived`: int64
    * `name`: object
    * `sex`: object
    * `age`: float64 [cite: 15]
* The `age` column has missing values[cite: 15].

## Data Cleaning

* **Duplicate Removal:**
    * One duplicate row was identified and removed[cite: 16, 17, 18, 19].
* **Missing Value Handling:**
    * Missing values in the `age` column were filled with the median age (35.0)[cite: 19].

## Exploratory Data Analysis

* **Sex Distribution:**
    * The dataset is dominated by male passengers (288 males and 211 females)[cite: 20, 21].
* **Age Distribution:**
    * The majority of passengers are adults (20-59 years old)[cite: 22].
* **Survival Rate:**
    * The distribution of survivors and non-survivors is relatively balanced[cite: 23].

## Conclusions

* The dataset consists of 500 rows and 4 columns (`survived`, `name`, `sex`, `age`)[cite: 24].
* The `age` column had 49 missing values (9.8%), which were imputed using the median[cite: 25].
* One duplicate row was removed[cite: 26].
* The average passenger age is approximately 29 years (ranging from 0.75 to 80 years)[cite: 27].
* The dataset includes 288 male and 212 female passengers[cite: 28].
* 270 passengers survived, and 230 did not survive[cite: 28].

## Contact

Meina Lisa:

* Email: meinalisa02@gmail.com
* Phone: +(62) 852 6049 8159 [cite: 29]
