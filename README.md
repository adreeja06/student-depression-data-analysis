# 🎓 Student Depression Data Analysis

This project analyzes mental health trends among students, focusing on identifying key factors that correlate with depression. The analysis was conducted using SQL for data processing and Tableau for creating an interactive, insightful dashboard.

## 🎯 Goal

The primary objective is to identify and visualize the key factors contributing to student depression, such as academic pressure, sleep duration, and financial stress. The final output is a user-friendly dashboard that allows for dynamic exploration of the data to derive meaningful insights.

## 🛠️ Tech Stack

* **Database:** SQL Server
* **Data Visualization:** Tableau
* **Dataset:** `updated_student_depression_data.csv`

## 📊 Dashboard Preview

The final dashboard provides a comprehensive overview of several key metrics related to student well-being.

### 🧠 Final Dashboard Overview
![Final Dashboard](final.png)

The dashboard visualizes the following relationships:
- **Sleep Duration ($SD$) vs Student Count ($SC$)**
- **Study Hours ($SH$) vs Student Count ($SC$)**
- **Study Satisfaction ($SS$) vs Student Count ($SC$)**
- **Academic Pressure ($AP$) vs Student Count ($SC$)**
- **Financial Stress ($FC$) vs Student Count ($SC$)**

### 🔄 Interactive Filtering in Action

The dashboard is fully interactive. Clicking on any data point on a chart will filter the entire dashboard, allowing for a granular analysis of how different factors are correlated.

| **Example 1: Filtering by Study Satisfaction** | **Example 2: Filtering by Sleep Duration** |
| :---: | :---: |
| ![Interaction 1](interactive1.png) | ![Interaction 2](interactive2.png) |

## 📁 Repository Files

* `Depression I Student - Dataset.csv`: The initial raw dataset.
* `updated_student_depression_data.csv`: The cleaned and preprocessed dataset used for the analysis.
* `depression_analysis_queries.sql`: Contains all the SQL queries used for data cleaning, transformation, and analysis.
* `SQL+Tableau Project.pdf`: A detailed report document outlining the project's lifecycle and findings.
* `final.png`, `interactive1.png`, `interactive2.png`: Image assets of the dashboard and its interactive features.
