# Road-Accident-Analysis-Using-Machine-Learning
# 🔍 Objective:
The goal of this project is to analyze a road accident dataset to uncover hidden patterns, understand factors contributing to accident severity, and explore how time, driver characteristics, and vehicle types influence road safety. The analysis uses **feature engineering, exploratory data analysis (EDA), clustering,** and **time series modeling** to gain actionable insights.

# 📁 Dataset Overview:
The dataset contains information about road accidents, including the following features:

1. Time: Timestamp of the accident
2. Day_of_week: Day the accident occurred
3. Age_band_of_driver: Age category of the driver
4. Driving_experience: Driver's years of experience
5. Type_of_vehicle: Vehicle involved
6. Area_accident_occured: Urban, rural, office, etc.
7. Lanes_or_Medians: Road layout
8. Types_of_Junction: T-junctions, crossings, etc.
9. Cause_of_accident: Main reason for the accident
10. Accident_severity: Target variable – Slight Injury, Serious Injury, or Fatal Injury

# ⚙️ Feature Engineering:
- Extracted the hour of accident from the Time field to capture temporal patterns.
- Converted all categorical columns using Label Encoding to make them suitable for machine learning.
- Mapped accident severity to numeric classes for modeling.


📊 Exploratory Data Analysis (EDA):
1. Severity by Day & Hour
- Identified how accident severity varies across the week and hour of the day.
- Peak accident times and days were identified, showing higher frequencies during weekday rush hours and weekends.

2. Category-wise Breakdown

- Visualized severity distributions across:
  -Driver experience levels
  -Vehicle types
  -Areas (urban, rural, etc.)
  -Age bands















