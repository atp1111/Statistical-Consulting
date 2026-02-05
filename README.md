# Student Success Factors: A Statistical Consulting Project

This repository contains a comprehensive statistical analysis of student educational performance. [cite_start]The project was conducted as part of a graduate-level consulting engagement for the Translational Data Analytics program at The Ohio State University. [cite: 2]

## 🎯 Research Objective
[cite_start]The primary goal was to answer: **"What behavioral and environmental factors lead to better educational performance?"** [cite: 3, 32, 88]

## 🛠️ Technical Stack
- [cite_start]**Language:** R [cite: 90]
- **Libraries:** `dplyr`, `ggplot2`, `car`
- [cite_start]**Statistical Methods:** - Exploratory Data Analysis (EDA) [cite: 90]
  - [cite_start]Univariate Correlation & ANOVA F-tests [cite: 90]
  - [cite_start]Multiple Linear Regression [cite: 90, 103]
  - [cite_start]Model Diagnostics (Multicollinearity, Skewness, Residual Analysis) [cite: 91, 103]

## 📊 The Dataset
[cite_start]The analysis utilized a 6,400-row Kaggle dataset tracking various student metrics: [cite: 45, 87]
- [cite_start]**Numeric:** Hours studied, Attendance, Previous scores, Sleep hours. [cite: 46, 89]
- [cite_start]**Categorical:** Access to resources, Parental involvement, School type, Peer influence. [cite: 31, 89]

## 🏗️ Analytical Workflow
1. [cite_start]**Data Cleaning:** Handled missing values (empty strings) and removed low-variance features (e.g., Internet Access, Gender). [cite: 62, 90]
2. [cite_start]**Variable Selection:** Ranked predictors by F-statistics and practical mean differences. [cite: 93, 94, 95]
3. [cite_start]**Modeling:** Developed a simplified 7-predictor linear model explaining **~XX%** of the variance in exam scores. [cite: 90]
4. [cite_start]**Diagnostics & Refinement:** Identified and addressed outliers and impossible values (>100) to improve model robustness (RMSE reduction). [cite: 91, 103]

## 📈 Key Insights
- [cite_start]**Primary Drivers:** Attendance and Study Hours showed the strongest positive association with final scores. [cite: 93, 94]
- [cite_start]**Environmental Impact:** Access to resources and parental involvement were significant positive predictors. [cite: 94, 96]
- [cite_start]**Negative Factors:** School distance had a statistically significant negative effect on performance. [cite: 95]
- [cite_start]**Nuanced Findings:** Subjective measures like "Motivation Level" were found to be less significant in the multivariable model compared to bivariate analysis. [cite: 60, 97]

## 📂 Project Structure
- `Data_Analysis.Rmd`: Full R code for EDA, modeling, and diagnostics.
- [cite_start]`Consulting_Reflection.pdf`: Detailed documentation of the consulting process and client interactions. [cite: 1]
