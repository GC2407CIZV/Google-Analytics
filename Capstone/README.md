# Bellabeat Smart Device Usage Analysis: Strategic Recommendations for the Leaf Product

This case study analyzes smart device usage data to provide actionable insights for Bellabeat, a wellness technology company. The goal is to understand consumer trends related to activity, sleep, and calorie expenditure to inform Bellabeat’s marketing strategy for the Leaf wellness tracker.

## Table of Contents

1. [Project Overview](#1-project-overview)
2. [Skills](#2-skills)
3. [Ask (Business Task & Questions)](#3-ask)
4. [Prepare (Data & Limitations)](#4-prepare)
5. [Process (Data Analysis)](#5-process)
    * [5.1 Data Cleaning & Transformation](#5.1-data-cleaning-transformation)
    * [5.2 Exploratory Data Analysis](#5.2-exploratory-data-analysis)
6. [Share (Key Findings & Recommendations)](#6-share)
    * [6.1 Key Findings](#6.1-key-findings)
    * [6.2 Recommendations](#6.2-recommendations)
7. [Act (Next Steps)](#7-act)
8. [Conclusion](#8-conclusion)
9. [Repository Contents](#9-repository-contents)

## 1. Project Overview

This case study uses publicly available Fitbit data to analyze user trends in activity, sleep, and calorie expenditure.  The insights gained are used to develop data-driven marketing recommendations for Bellabeat's Leaf product, focusing on product positioning, feature promotion, and target audience identification.

## 2. Skills

* **Programming Language:** R
* **Tools & Technologies:** RStudio (Posit Cloud), tidyverse, lubridate, ggplot2, readr
* **Data Analysis:** Data cleaning, transformation, exploratory data analysis (EDA), data visualization
* **Business Acumen:**  Translating data insights into actionable business recommendations, strategic thinking, marketing strategy development

## 3. Ask (Business Task & Questions)

**Business Task:** Analyze smart device usage data to understand consumer trends related to activity, sleep, and calorie expenditure, and provide data-backed marketing recommendations for Bellabeat’s Leaf product.

**Key Questions:**

1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

## 4. Prepare (Data & Limitations)

**Data Source:** Fitbit Fitness Tracker Data (Kaggle)

**Data Characteristics:** Minute-level data on activity, heart rate, and sleep from 30 Fitbit users. Includes daily and hourly summaries.

**Data Limitations:** Small sample size (30 users), potential bias in self-reported data, data from Fitbit users (not Bellabeat users).  These limitations are acknowledged and considered in the analysis and recommendations.

## 5. Process (Data Analysis)

### 5.1 Data Cleaning & Transformation

* Loaded and inspected data using `readr` and `glimpse()`.
* Checked for missing values and handled them appropriately.
* Converted date/time columns to correct formats using `lubridate`.
* Merged relevant datasets using `dplyr`'s `left_join()`.
* Calculated new variables (e.g., total active minutes, weekday).

### 5.2 Exploratory Data Analysis

* Used `ggplot2` to visualize data and explore trends.
* Analyzed distributions of daily steps, sleep time, and activity levels.
* Investigated relationships between steps, calories, sleep, and sedentary minutes.
* Compared activity levels between weekdays and weekends.
* Identified potential correlations and patterns in the data.

## 6. Share (Key Findings & Recommendations)

### 6.1 Key Findings

* **Sedentary Behavior:** A significant portion of users' time is spent in sedentary activities.
* **Steps & Calories:**  A positive correlation exists between daily steps and calorie expenditure.
* **Sleep Patterns:** Sleep durations vary widely among users.
* **Sleep & Activity:**  A complex relationship exists between sleep duration and activity levels.
* **Weekday/Weekend Activity:** Potential differences in activity levels between weekdays and weekends.

### 6.2 Recommendations

* **Target Sedentary Users:** Position the Leaf as a tool to encourage movement and break up sedentary time.
* **Promote Holistic Wellness:** Emphasize the importance of tracking both sleep and activity for overall well-being.
* **Personalized Insights:** Develop personalized recommendations based on individual user patterns.
* **Targeted Marketing:** Tailor marketing campaigns to specific user segments and activity patterns.
* **Highlight Key Features:** Promote features related to sleep tracking, activity monitoring, and personalized goal setting.

## 7. Act (Next Steps)

* **Further Research:** Explore the influence of other factors (e.g., age, weight, diet) on activity and sleep.
* **Feature Development:** Develop new features based on user trends and needs (e.g., sedentary behavior alerts, gamification).
* **Marketing Campaign Development:** Implement marketing campaigns based on the recommendations.

## 8. Conclusion

This analysis provides valuable insights into user behavior related to activity, sleep, and calorie expenditure.  The recommendations presented can help Bellabeat effectively position the Leaf product, target its marketing efforts, and ultimately drive growth in the competitive wellness technology market.

## 9. Repository Contents

* `README.md`: This file.
* `Bellabeat Data Analysis.R`: R script file containing the data analysis code.
* `Bellabeat Data Analysis.Rmd`: R Markdown file containing the data analysis code and narrative.
* `Bellabeat-Data-Analysis.html`: HTML output generated from the R Markdown file.
* `Bellabeat-Data-Analysis.pdf`: PDF version of the R Markdown report.
