😴 Sleep Health Data Analysis

This project explores sleep patterns and disorders using a dataset of individuals' sleep metrics and health attributes. The analysis focuses on how occupation and BMI categories relate to sleep duration, quality, and the prevalence of insomnia.

📂 Dataset

File: data/sleep_health_data.csv

Each row includes a person's health and lifestyle data:

Demographics: Age, Gender, Occupation
Sleep Metrics: Sleep Duration, Quality of Sleep, Sleep Disorder
Health Indicators: Stress Level, BMI Category, Blood Pressure, Heart Rate
Lifestyle Metrics: Physical Activity Level, Daily Steps
📊 Key Analysis Steps

1. Occupation and Sleep
Calculate average sleep duration per occupation.
Calculate average sleep quality per occupation.
Identify the occupation with the lowest sleep duration and lowest sleep quality.
Determine if both issues affect the same occupation.
✅ Both metrics were lowest for Sales Representatives.
2. BMI and Insomnia Analysis
Focus on individuals with Insomnia.
Analyze how insomnia prevalence varies across:
Normal
Overweight
Obese BMI categories
Ratios of people with insomnia in each BMI category:
Normal: ~X.XX (updated based on actual output)
Overweight: ~X.XX
Obese: ~X.XX
3. Handling Inconsistent BMI Labels
Accounted for possible alternate labels (e.g., "Normal" vs "Normal Weight").
