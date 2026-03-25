Statistical Consulting: Student Success Factors
This repository documents a formal statistical consulting engagement with graduate students from the Translational Data Analytics (TDA) program at The Ohio State University. The project involved transforming a broad research question into a rigorous analytical framework to identify the primary drivers of student academic performance.

🎯 Project Overview
The "clients" provided a 6,400-row dataset and sought to understand which behavioral and environmental factors lead to better educational outcomes, measured by final exam scores. My role involved guiding the clients through the ASCCR framework (Opening, Ask, Seek, Check, Revisit, and Closing) to ensure a shared understanding of the data's provenance and analytical goals.

🛠️ Technical Workflow & Analysis
The analysis utilized R to perform a systematic evaluation of over 20 potential predictors.


Data Cleaning & Provenance: Identified "red flags" regarding the original data source and addressed missing values/empty strings in the dataset.


Quantitative & Quality Assessment (QQQ): Evaluated data quality, sample sizes, and checked for outliers or impossible values (scores >100) that could skew results.


Variable Selection: Used ANOVA F-tests and Spearman correlation to rank variables by practical impact, ultimately narrowing the scope to the 7 most significant predictors.


Statistical Modeling: Built a Multiple Linear Regression model to quantify effect sizes while checking for multicollinearity and model assumptions.

📈 Key Findings

Behavioral Drivers: Attendance and study hours were identified as the strongest positive predictors of exam performance.


Environmental Factors: Access to resources and parental involvement showed meaningful positive effects on student outcomes.


Social & Geographic Impacts: Distance from home had a small but significant negative correlation, while peer influence played a measurable role.


Interpretation: Subjective factors like "motivation" showed weaker effects in the multivariable model, highlighting the importance of looking at factors in combination rather than isolation
