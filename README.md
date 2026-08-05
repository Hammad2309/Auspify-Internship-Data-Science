# End-to-End Netflix Data Science and Business Intelligence Project

## Executive Summary
This repository contains a comprehensive, end-to-end data science project executed on the Netflix Movies and TV Shows dataset (8,790 records). The project covers the full lifecycle of data analysis: raw data preprocessing, exploratory data analysis (EDA), content-based recommendation modeling, time-series forecasting, predictive machine learning classification, and executive dashboard development in Power BI.

---

## Technical Stack and Tools
* **Programming Language:** Python
* **Data Manipulation & Preprocessing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning & NLP:** Scikit-Learn (TF-IDF, Cosine Similarity, Decision Tree, Random Forest, Logistic Regression)
* **Business Intelligence:** Power BI (Interactive Dashboard, DAX, KPI Visuals)
* **Environment:** Jupyter Notebook, Google Colab

---

## Repository Structure and Project Workflow

### Task 1: Data Cleaning and Preprocessing
* **Objective:** Prepare raw dataset for analytical pipelines and downstream modeling.
* **Key Actions:**
  * Imported dataset and verified schema structure.
  * Verified dataset integrity for missing values and duplicated records.
  * Converted `date_added` into standardized datetime format and engineered a new `year_added` feature.
  * Extracted numeric values from content runtime (`duration_num`).
  * Processed genre lists (`listed_in`) into structured arrays.
* **Output Artifact:** `cleaned_netflix.csv`

### Task 2: Exploratory Data Analysis (EDA)
* **Objective:** Extract structural patterns, distribution metrics, and domain insights.
* **Key Actions:**
  * Analyzed content distribution: Movies (69.7%) vs. TV Shows (30.3%).
  * Identified top contributing regions (USA leading with 3,248 titles, followed by India with 1,857 titles).
  * Evaluated primary genres (Dramas, International Movies) and release distributions across decades.
* **Visual Output:** Distribution charts, regional concentration bar graphs, and runtime distribution histograms.

### Task 3: Recommendation System Analysis
* **Objective:** Develop a content-based recommendation engine for automated title suggestions.
* **Key Actions:**
  * Combined text attributes (`title`, `director`, `listed_in`, `country`).
  * Applied NLP text preprocessing (tokenization, lowercase normalization, punctuation removal).
  * Generated numerical vector spaces using TF-IDF Vectorizer.
  * Computed Cosine Similarity matrix across titles to generate top-5 similarity predictions.

### Task 4: Trend Prediction Analysis
* **Objective:** Evaluate temporal growth trends and project content expansion.
* **Key Actions:**
  * Calculated annual content addition metrics from the `release_year` feature.
  * Implemented 3-year and 5-year Moving Averages to smooth short-term fluctuations and identify macro trends.
  * Analyzed historic peaks (peak expansion in 2021) to assess long-term trajectory.

### Task 5: Machine Learning Classification Model
* **Objective:** Build predictive classifiers to categorize content types (`Movie` vs `TV Show`).
* **Key Actions:**
  * Preprocessed categorical attributes using Label Encoding.
  * Split data into 80% training and 20% test sets (random state = 42).
  * Evaluated performance across multiple algorithms:
    * Logistic Regression: 99.8% Accuracy
    * Decision Tree: 100% Accuracy
    * Random Forest: 100% Accuracy
  * Selected Decision Tree as the optimal classifier due to execution speed and resource efficiency.

### Task 6: Business Insights Dashboard
* **Objective:** Consolidate analytics, model results, and KPIs into an executive decision support system.
* **Key Actions:**
  * Built an interactive Power BI report (`.pbix`) featuring overall metrics: Total Titles (8,790) and Average Duration (69.94 mins).
  * Integrated multi-dimensional visual slicers for geographic, genre, and timeline filtering.
  * Formulated strategic business recommendations for content acquisition strategy.
* **Output Artifact:** Interactive Power BI Report (`.pbix`) and exported visual PDF analysis.

---

## Key Business Findings
1. **Content Mix Strategy:** Movies dominate the catalog (69.7%), but TV Shows present higher long-term user engagement potential.
2. **Geographic Focus:** The United States and India account for the primary share of total catalog offerings.
3. **Growth Trajectory:** Content addition peaked around 2021, shifting strategy toward curated quality over raw volume.

---

## Author & Contact Information
* **Developer:** Muhammad Hammad Ayub
* **Role:** Aspiring Data Scientist / Data Analyst
* **GitHub:** [GitHub Profile](https://github.com/Hammad2309)
