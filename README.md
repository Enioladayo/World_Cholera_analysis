# World_Cholera_analysis_project

## Overview

This project delves into the global challenge of cholera by analyzing a comprehensive dataset. The goal is to uncover key trends, identify influencing factors, and provide actionable insights to better understand and combat cholera outbreaks worldwide.

[View the Full Cholera Analysis Report](https://github.com/Enioladayo/World_Cholera_analysis/blob/main/Cholera%20analysis%20project.pdf)

[View python script](Cholera project.ipynb)

[View raw data](Cholera_project_dataset.csv)

## Project Structure & Methodology
This project followed a structured data analysis workflow to transform raw cholera data into actionable insights. The methodology comprised the following phases:

## Data Cleaning & Preparation:

Initial assessment for missing values across various columns ( Water Treatment Method).

Investigation and replacement of missing values (Water Treatment Method blanks replaced with "No treatment").

Changing data types for consistency and analysis (e.g., converting percentage and rate columns to appropriate numerical types like int64 or float64).

Checking for inconsistencies in categorical data (e.g., unique values for Country and Year).

## Exploratory Data Analysis (EDA) & Initial Aggregations:

Brief summary of object-type columns (Country, Region, Water Source Type, Water Treatment Method).

Reviewing factors responsible for cholera outbreaks by country, including:

- Average cases per 100,000 people.

- Bacteria count.

- Turbidity.

- Sanitation coverage percentage.

- Contamination level.

Descriptive statistics of numerical columns (Year, Contaminant Level (ppm), pH Level, Turbidity (NTU), Dissolved Oxygen (mg/L), Nitrate Level (mg/L), Lead Concentration (µg/L), Bacteria Count (CFU/mL)).

## Data Visualization:

Visual representation of key findings, including:

- World Cholera Cases (2019-2024 trends).

- Average Cases per 100K People by Country.

- Average Infant Mortality Rate per 1K Live Births by Year.

- Comparison of Treatment vs. No Treatment in Cholera Cases.

- Country-specific cholera causes (e.g., Turbidity, Bacteria Count, Contamination Level, Sanitation Coverage).

## Insights & Reporting:

1. Identification of **key determinants** of cholera outbreaks (e.g., high bacteria level and turbidity in certain regions despite high sanitation coverage).

2. Observation of a **decrease** in average cases in 2024 for **USA** and **Mexico**, directly proportional to treated factors (key determinants).

3.Highlighting that **treated water** can still pose a **risk** of cholera outbreak.

4.Noting the **significant role** of cholera outbreaks in infant mortality rates.

## Key Insights

A. Despite **high sanitation coverage** and **low contamination levels** in some countries (e.g., USA), **high bacteria levels** and **turbidity** were significant determinants of high cholera cases.

B. A **notable decrease** in average cholera cases was observed in 2024 for both USA and Mexico, correlating with improved treatment of causative factors.

The project emphasizes that even treated water can still carry a **risk of cholera outbreaks**.

Cholera outbreaks are **directly linked** to infant mortality rates; a reduction in cholera cases corresponds to a decrease in infant mortality.

## Recommendations
Based on the analysis, the following recommendations are proposed:

Implement **effective systems** to reduce bacteria count and turbidity in water sources.

Prioritize tackling cholera outbreaks as a direct means to decrease infant mortality rates.

**Review and improve** existing treatment methods for cholera.

**Analyze and enhance** strategies used to combat cholera outbreaks in 2024 for potential application and improvement in subsequent years.
