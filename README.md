Red Wine Quality Analysis

Internship Task 1: Data Cleaning & Visualization

Project Overview
This project focuses on the exploratory data analysis (EDA) of the Red Wine Quality dataset. By analyzing the physicochemical properties of Portuguese "Vinho Verde" wine, I identified which chemical factors most significantly impact the sensory quality ratings provided by humans.

Key Findings:
-The Alcohol Factor: There is a strong positive correlation (0.47) between alcohol content and wine quality.  
-Acidity Influence: Volatile acidity has a negative correlation (-0.39) with quality, meaning higher acidity levels (which can lead to a vinegar taste) generally result in lower ratings.  
-Data Imbalance: The dataset is not balanced; most wines are rated as "normal" (5 or 6), with very few excellent (8) or poor (3) samples.

Data Cleaning Process:
To ensure the analysis was accurate, I performed the following "Data Cleaning" steps:
-Duplicate Removal: Identified and removed duplicate rows to prevent bias in statistical outcomes.  
-Handling Outliers: Managed extreme values in variables like total sulfur dioxide to prevent skewed visualizations.  
-Missing Values: Verified that the dataset contains no null values across the 11 physicochemical inputs.
<img width="1101" height="362" alt="Screenshot 2026-05-04 095220" src="https://github.com/user-attachments/assets/39ad1982-acb9-4001-9b6d-c058f2ae7b44" />


Visualizations:
1. Correlation Heatmap
The heatmap was used to identify the relationship between inputs (like pH, sulphates, and alcohol) and the output (quality).
(Pro Tip: You can drag your heatmap.png file here to show it!)
<img width="1038" height="763" alt="Screenshot 2026-05-04 093510" src="https://github.com/user-attachments/assets/c906fccb-b53d-4657-ad57-a53062755974" />


2. Quality Distribution
A count plot confirmed the lack of balance between high, medium, and low-quality wine samples.
<img width="1100" height="413" alt="Screenshot 2026-05-04 095203" src="https://github.com/user-attachments/assets/6eab783c-5764-4b49-94ee-d4242240a826" />




Conclusion:
Chemical properties are a strong indicator of wine quality. For this specific dataset, high-quality red wines tend to have higher alcohol content and lower volatile acidity.
