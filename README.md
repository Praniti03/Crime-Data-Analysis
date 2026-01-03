**Crime Data Analysis & Time Series Forecasting**

**📖 Overview**

This project focuses on analyzing historical crime data to uncover temporal patterns, geographic hotspots, and crime trends, and to forecast future crime volumes using time series and regression-based models. The goal is to support data-driven decision-making for resource allocation, intervention planning, and proactive crime prevention.

The analysis combines data preprocessing, exploratory data analysis (EDA), and predictive forecasting to translate raw crime records into actionable insights.

**🎯 Business Problem**

Crime data is often large, noisy, and difficult to interpret without systematic analysis. Public agencies and planners need clear insights into:

•	When crimes are most likely to occur

•	Which crime types dominate

•	Where hotspots emerge over time

•	How crime levels may evolve in the future

This project addresses these challenges by identifying patterns in historical crime data and forecasting future trends.

**🧠 Objectives**

•	Clean and prepare raw crime data for reliable analysis

•	Identify temporal patterns such as monthly, weekly, and seasonal trends

•	Detect high-frequency crime types and geographic hotspots

•	Forecast future crime volumes to distinguish high- and low-crime periods

**📊 Dataset Overview**

•	Historical crime records covering multiple years

•	Key attributes include crime type, date/time, and location

•	Data required extensive preprocessing due to missing values, duplicates, and mixed data types

**🛠️ Data Preprocessing**

**Key steps performed:**

•	Removed duplicate records to avoid bias

•	Imputed missing values for consistency

•	Encoded 13 categorical features for analysis

•	Scaled 11 numeric features to support modeling

•	Prepared a clean and structured dataset for EDA and forecasting

**🔍 Exploratory Data Analysis (EDA)**

Using Python (Pandas, Seaborn, Matplotlib), the analysis explored:

•	Monthly and weekly crime trends

•	Seasonal patterns and year-over-year variations

•	High-frequency crime categories

•	Geographic crime hotspots

**Key Observations**

•	Clear seasonal peaks in crime occurrence

•	Higher crime frequency during weekends

•	A small subset of crime types accounts for a large share of incidents

•	Consistent hotspot regions across multiple time periods

**📈 Predictive Modeling & Forecasting**

To estimate future crime trends, multiple models were developed and compared:

•	Polynomial Linear Regression

•	SARIMAX (Seasonal ARIMA with exogenous components)

•	Prophet

These models were used to forecast monthly crime volumes from 2020 onward, enabling:

•	Identification of high- vs. low-crime periods

•	Support for proactive planning and resource allocation

**💡 Insights & Impact**

•	Forecasts highlight periods of elevated crime risk, allowing earlier intervention

•	Temporal patterns help align staffing and resource deployment

•	Trend analysis supports long-term crime prevention strategies

**🧰 Tools & Technologies**

•	Python

•	Pandas, NumPy

•	Matplotlib, Seaborn

•	Statsmodels (SARIMAX)

•	Prophet

•	Scikit-learn (Regression, Scaling)

