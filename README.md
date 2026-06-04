# Bellabeat Fitbit User Behaviour Analysis

## Project Overview

This project analyzes Fitbit smart-device data to identify user activity, sleep, and wellness behaviour patterns. The objective is to generate actionable business recommendations that can help Bellabeat improve customer engagement, product adoption, and personalized wellness experiences.

---

## Business Task

Analyze Fitbit fitness tracker data to uncover behavioural trends and provide data-driven recommendations that can support Bellabeat's marketing and growth strategy.

---

## Dataset Overview

The analysis utilizes the Fitbit Fitness Tracker Dataset, which contains anonymized smart-device usage records collected from Fitbit users.

The project incorporates six datasets:

| Dataset | Description | Granularity |
|----------|------------|------------|
| Daily Activity | Daily activity and calorie metrics | User-Day |
| Sleep | Sleep duration and time in bed | User-Day |
| Hourly Steps | Hourly step counts | User-Hour |
| Hourly Calories | Hourly calorie expenditure | User-Hour |
| Heart Rate | Heart rate measurements | User-Second |
| Weight Log | Weight and BMI tracking events | Event-Based |

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

---

## Methodology

1. Data Importation
2. Structural Profiling
3. Data Cleaning & Validation
4. Datetime Normalization
5. Feature Engineering
6. Granularity Assessment
7. Data Integration
8. Exploratory Data Analysis
9. Insight Generation
10. Business Recommendations

---

## Key Findings

- Daily step count demonstrates a strong positive relationship with calorie expenditure.
- User activity levels vary significantly across the population.
- Sleep behaviour shows considerable variability among users.
- Activity and sleep patterns differ between weekdays and weekends.
- A large proportion of users remain within low-to-moderate activity categories.

---

## Business Recommendations

- Develop personalized activity coaching features.
- Implement behavioural segmentation for targeted engagement.
- Introduce sleep-improvement and wellness campaigns.
- Encourage user participation through goal-based challenges and rewards.
- Leverage wearable insights to improve user retention and engagement.

---

## Project Structure

```text
Bellabeat_Project
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│
├── outputs
│   ├── charts
│   └── reports
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Outputs

- Analytical Notebook (`.ipynb`)
- HTML Notebook Export
- PDF Business Report
- Data Visualizations
- Processed Datasets

---

## Author

Alfred Iheanacho

GitHub: https://github.com/alfred-iheanacho