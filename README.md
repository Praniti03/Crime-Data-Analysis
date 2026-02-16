**Crime Data Analysis & Time Series Forecasting**

**Tableau Dashboard**

https://public.tableau.com/views/LACrimeAnalysisDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**📖 Project Overview**

This project analyzes large-scale historical crime data to uncover temporal patterns, geographic hotspots, dominant crime types, and to forecast future crime volumes using time-series and regression-based models. The objective is to support data-driven decision-making for resource allocation, intervention planning, and proactive crime prevention.

The workflow integrates data preprocessing, exploratory data analysis (EDA), predictive modeling, and an interactive Tableau dashboard to convert raw crime records into actionable insights for both technical and non-technical stakeholders.

**🎯 Business Problem**

Crime datasets are often large, noisy, and difficult to interpret without structured analysis. Public agencies and planners need clear answers to:

When crimes are most likely to occur

Which crime types dominate overall volume

Where persistent hotspots exist

How crime levels may evolve in the future

This project addresses these challenges by combining historical trend analysis with forecasting and visual analytics.

**🧠 Objectives**

Clean and prepare raw crime data for reliable analysis

Identify monthly, weekly, and seasonal crime patterns

Detect high-frequency crime categories and hotspot regions

Forecast future crime volumes to distinguish high- and low-risk periods

**📊 Dataset Overview**

Historical crime records spanning multiple years

Key attributes include crime type, date/time, and geographic area

Significant preprocessing required due to missing values, duplicates, and mixed data types

**🛠️ Data Preprocessing**

Key steps performed:

Removed duplicate records to prevent bias

Imputed missing values to maintain data consistency

Encoded 13 categorical features for analysis

Scaled 11 numeric features to support modeling

Produced a clean, structured dataset for EDA and forecasting

**🔍 Exploratory Data Analysis (EDA)**

Using Python (Pandas, Seaborn, Matplotlib), the analysis uncovered:

Monthly and seasonal crime trends

Day-of-week crime patterns

High-frequency crime categories

Consistent geographic crime hotspots

**Key Observations**

Clear seasonal peaks in crime occurrence

Higher crime frequency toward weekends, with Friday as the peak day

A small subset of crime types accounts for a disproportionately large share of incidents

Certain regions remain persistent hotspots across multiple years

**📈 Predictive Modeling & Forecasting**

To estimate future crime trends, multiple models were developed and compared:

Polynomial Linear Regression

SARIMAX (Seasonal ARIMA with exogenous components)

Prophet

These models were used to forecast monthly crime volumes from 2020 onward, enabling:

Identification of high- vs. low-crime periods

Support for proactive planning and staffing decisions

Long-term trend analysis for crime prevention strategies

**📊 Interactive Tableau Dashboard**

<p align="center">
  <img src="C:\Users\Praniti\Downloads\Dashboard 1 (1).png" width="900">
</p>


An interactive Tableau dashboard was built to translate analytical results into an intuitive, decision-ready format.

**KPI Summary:**

Total Crimes Analyzed: 1,004,991

Peak Crime Year: 2022

Most Frequent Crime Type: Vehicle – Stolen

Highest Crime Area: Central Los Angeles

Top 10 Crime Hotspots: Visual ranking of high-risk regions

Seasonal Crime Patterns: Monthly trends vs. yearly average

Day-of-Week Analysis: Highlights Friday as the peak activity day

Trend View (2020–2025): Interactive exploration of long-term crime changes

**💡 Insights & Business Impact**

Forecasts highlight periods of elevated crime risk, enabling earlier intervention

Temporal patterns support optimized resource deployment and staffing

Hotspot analysis enables targeted policing and prevention strategies

Dashboard allows stakeholders to explore when, where, and what crimes dominate without technical expertise

**🧰 Tools & Technologies**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (Regression, Scaling)

Statsmodels (SARIMAX)

Prophet

Tableau

