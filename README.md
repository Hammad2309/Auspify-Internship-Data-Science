# Auspify Technologies - Data Science Internship

## Overview
This repository contains all 6 tasks completed during my Data Science Internship at Auspify Technologies (July-August 2026). The projects cover data cleaning, exploratory analysis, machine learning, and business intelligence using real-world Netflix data.

## Dataset
- **Source:** Netflix Movies and TV Shows Dataset
- **Size:** 8790 rows, 10 columns
- **Type:** Movies and TV Shows with details like title, director, country, release year, rating, duration, and genre

## Tasks Completed

### Task 1: Data Cleaning & Preprocessing
- Imported dataset using Pandas
- Identified and handled missing values and duplicates
- Transformed date and categorical columns
- Created new features: `year_added`, `duration_num`, `genre_list`
- Exported cleaned dataset: `cleaned_netflix.csv`

### Task 2: Exploratory Data Analysis (EDA)
- Analyzed dataset structure and statistics
- Studied content distribution by type (Movies vs TV Shows)
- Identified top countries and genres
- Created visualizations using Matplotlib & Seaborn
- Summarized key findings and trends

### Task 3: Recommendation System Analysis
- Extracted relevant content features
- Performed text preprocessing (lowercase, punctuation removal)
- Used TF-IDF Vectorizer and Cosine Similarity
- Built a function to generate top 5 similar title recommendations
- Evaluated recommendations for multiple titles

### Task 4: Trend Prediction Analysis
- Prepared release-year data for time series analysis
- Analyzed yearly content trends
- Built forecasting models using moving averages (3-year & 5-year)
- Visualized actual vs predicted trends
- Interpreted results and predicted future content growth

### Task 5: Machine Learning Classification Model
- Selected features and target (`type` column)
- Split data into training (80%) and testing (20%) sets
- Trained 3 models: Logistic Regression, Decision Tree, Random Forest
- Evaluated using accuracy, precision, recall, and F1-score
- Compared models and selected Decision Tree (100% accuracy)

### Task 6: Data Science Business Insights Dashboard
- Performed complete data analysis in Power BI
- Referenced predictive models from Task 5
- Created interactive visualizations (cards, pie chart, bar charts, line chart)
- Generated 5 business recommendations
- Compiled findings in a professional report

## Technologies Used
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Power BI:** Interactive dashboard and data visualization
- **Google Colab:** Notebook environment
- **Git & GitHub:** Version control and project hosting

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Hammad2309/Auspify-Internship-Data-Science.git
2.Open any task folder to view notebooks, reports, and screenshots

3.Power BI dashboard file is in Task 6_Data Science Business Insights Dashboard/

Author:

Muhammad Hammad Ayub

Email: ayubhammad56@gmail.com

LinkedIn: www.linkedin.com/in/muhammad-hammad-ayub-a98292325

Certificate:

Internship Completion Certificate will be added after final submission.

Acknowledgments:

Special thanks to Auspify Technologies for providing this learning opportunity and real-world project experience.

This repository is part of the Data Science Internship program at Auspify Technologies (July-August 2026).
