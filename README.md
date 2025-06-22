# Weather_Data_Analysis

This project performs exploratory data analysis (EDA) on historical weather data to understand relationships between key weather parameters, detect outliers, and visualize trends.

📌 Project Highlights
 Loaded and cleaned the dataset (handled missing values, removed outliers).
 Computed correlation matrices to study relationships between weather features.
 Visualized:

Correlation heatmap

Scatter plots (e.g., Temperature vs Apparent Temperature, Humidity vs Wind Speed)

Pairwise relationships between features

Monthly average trends for key weather parameters
 Analyzed how Temperature differs from Apparent Temperature (FeelsLike_Delta) and its correlation with other features.

 Dataset
The dataset (weatherHistory.csv) includes weather records with features like:

Temperature (C)

Apparent Temperature (C)

Humidity

Wind Speed (km/h)

Pressure (millibars)

Formatted Date (used for monthly trend analysis)

Key Analyses & Visualizations
Correlation Heatmap — visualizes relationships between temperature, humidity, wind speed, and pressure.

Scatter Plots — shows pairwise relationships between selected features (e.g., temperature vs apparent temperature).

Outlier Removal — filtered temperature data beyond 3 standard deviations to improve correlation accuracy.

Pairwise Feature Matrix — explored relationships between all variables using scatter matrix.

Monthly Trends — line plot showing how average weather features change over time.

Tools & Libraries
Python

Pandas

NumPy

Matplotlib


Example Insights
Temperature and Apparent Temperature show very high correlation.

Humidity and Wind Speed are weakly correlated.

Outlier removal improved correlation precision for temperature-related analyses.
