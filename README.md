[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aminatahir-0/Student-Engagement-Analytics/blob/main/Student%20Engagement%20analysis.ipynb)

# Student Engagement Analytics

## 📌 Project Overview
This project investigates the key factors influencing student course completion and dropout rates using an online learning engagement dataset. Through data cleaning, feature engineering, and exploratory data analysis in Python, this study evaluates program retention, departmental variations, and behavioral engagement metrics.

## 📊 Key Findings
* **High Attrition Rate:** The overall program dropout rate stands at **57.8%**, highlighting a significant retention challenge.
* **Behavioral Variability:** **Assignments Completed** and **Mentor Interactions** showed the highest coefficient of variation (~60%), indicating inconsistent engagement among participants.
* **Independent Metrics:** Pearson correlation analysis revealed near-zero linear relationships (0.0 to ±0.05) among individual engagement habits, suggesting dropouts are driven by broader factors rather than isolated actions.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Seaborn, NumPy

## 📈 Methodology
1. **Data Preprocessing & Feature Engineering:** Cleaned the dataset, created binary success/dropout status based on course progress, and binned mentor interactions.
2. **Exploratory Data Analysis (EDA):** Visualized distributions using pie charts, horizontal bar charts, and trend plots.
3. **Statistical & Correlation Modeling:** Computed Coefficient of Variation (CV) to measure behavioral unpredictability and generated a Pearson correlation matrix.

## 💡 Recommendations
* Focus academic support and tutoring resources on high-risk departments.
* Implement automated early-warning alerts for students lagging behind on assignments.
* Restructure mentor sessions to focus proactively on struggling participants.
