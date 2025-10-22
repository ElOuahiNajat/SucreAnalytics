# SucreAnalytics

# Sugarcane Production Analysis

## Overview

This repository presents an in-depth **Exploratory Data Analysis (EDA)** of global sugarcane production data using Python.  
The analysis aims to uncover key insights about production trends, yield efficiency, and agricultural distribution across continents and countries.

By leveraging popular data science libraries such as **Pandas**, **Seaborn**, and **Matplotlib**, this project provides both descriptive statistics and insightful visualizations to better understand the factors affecting sugarcane production worldwide.

---

## Objectives

The main objectives of this analysis are:

1. To clean and preprocess raw data for consistent analysis.
2. To explore the global distribution of sugarcane production by country and continent.
3. To analyze relationships between acreage, yield, and production levels.
4. To visualize correlations between key agricultural indicators.
5. To derive insights that could support **agricultural optimization**, **policy decision-making**, and **sustainable production practices**.

---

## Table of Contents

1. [Project Description](#project-description)  
2. [Dataset](#dataset)  
3. [Setup and Installation](#setup-and-installation)  
4. [Data Cleaning](#data-cleaning)  
5. [Exploratory Data Analysis](#exploratory-data-analysis)  
   - [Univariate Analysis](#univariate-analysis)  
   - [Bivariate Analysis](#bivariate-analysis)  
   - [Correlation Analysis](#correlation-analysis)  
   - [Analysis by Continent](#analysis-by-continent)
6. [Results and Insights](#results-and-insights)  
7. [Future Work](#future-work)  
8. [Conclusion](#conclusion)  
9. [License](#license)

---

## Project Description

This project performs a statistical and visual exploration of sugarcane production data obtained from public agricultural sources.  
The analysis helps answer questions such as:

- Which countries are the top sugarcane producers?
- How does sugarcane production vary by continent?
- What is the relationship between yield, acreage, and total production?
- Which regions demonstrate the highest production efficiency?

All analyses are implemented in the Jupyter Notebook file:


---

## Dataset

The dataset used is:

**File Name:** `List of Countries by Sugarcane Production.csv`

**Columns:**
| Column | Description |
|---------|-------------|
| `Country` | The name of the country. |
| `Continent` | The continent where the country is located. |
| `Production(Tons)` | Total sugarcane production in tons. |
| `Production_per_person(Kg)` | Sugarcane production per person in kilograms. |
| `Acreage(Hectare)` | Total land area used for sugarcane cultivation (in hectares). |
| `Yield(Kg/Hectare)` | Sugarcane yield per hectare in kilograms. |

---

## Setup and Installation

To run the notebook locally, clone the repository and install the required dependencies.


###
Data Cleaning

Before analysis, the dataset undergoes the following cleaning steps:

Removal of non-numeric characters (commas, dots, etc.) from numeric fields.

Conversion of columns to appropriate data types.

Handling of missing or inconsistent values.

Dropping of irrelevant or redundant columns.

Note: Some minor warnings (FutureWarnings) may appear but do not affect the validity of the analysis.

Exploratory Data Analysis

The EDA section is divided into several analytical dimensions:

1. Univariate Analysis

Examination of each variable individually.

Use of histograms, boxplots, and bar plots to understand distributions.

Detection of outliers in production and yield.

2. Bivariate Analysis

Exploration of relationships between pairs of variables.

Use of scatterplots and grouped bar charts to visualize correlations such as:

Production vs. Acreage

Yield vs. Production

3. Correlation Analysis

Computation of correlation matrix using df.corr().

Visualization with a Seaborn heatmap to highlight strong relationships between metrics.

4. Analysis by Continent

Aggregation of data by continent to analyze regional patterns.

Comparative visualizations (bar plots, line charts) for production and yield across continents.

Results and Insights

Key insights derived from the analysis include:

Top Producers: Countries such as Brazil, India, and China dominate global sugarcane production.

Yield Variability: Some smaller countries achieve high yields due to optimized agricultural techniques.

Continent-Level Trends: Asia and South America contribute the majority of global sugarcane output.

Correlation Findings: Strong correlation exists between acreage and total production, while yield is moderately correlated with both.

Future Work

Potential extensions to this project include:

Incorporating time-series data to analyze production trends over multiple years.

Integrating external datasets such as rainfall, soil type, or fertilizer usage.

Applying machine learning models to predict future sugarcane yields.

Building an interactive dashboard (using Dash, Streamlit, or Power BI) for real-time visualization.

Conclusion

This exploratory analysis provides a data-driven understanding of global sugarcane production.
It highlights the disparities and efficiencies across regions, offering a foundation for more advanced modeling and predictive analytics in agricultural production.

The insights generated can support researchers, policymakers, and agribusiness stakeholders in developing strategies to optimize sugarcane cultivation and improve sustainability.
