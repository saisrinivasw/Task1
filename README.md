# Task1

🎓 Student Performance Data Analysis (Task 1)
A data analysis project focused on exploring and visualizing student exam performance using core Python libraries like pandas, NumPy, matplotlib, and seaborn.

🔍 Goal: To analyze student grades (G1, G2, G3), study time, and gender performance to uncover key academic trends.

📁 Dataset
File: student-mat.csv

Source: UCI Machine Learning Repository

Key Features:

G1, G2, G3: Grades for three terms

studytime: Weekly hours spent studying

sex: Gender (M or F)


✅ Project Workflow

📥 Data Loading

Loaded CSV data using pandas

Displayed the first few rows for preview


🔎 Data Exploration

Checked for missing values

Examined data types and shape

Reviewed unique value distributions


🧹 Data Cleaning

Removed duplicates

Handled any missing or inconsistent data (none found)


📊 Data Analysis

Calculated average final grade (G3)

Counted students scoring above 15 in G3

Measured correlation between studytime and G3

Compared average G3 scores by gender


📈 Data Visualization

Histogram of final grades (G3)

Scatter plot: Study time vs Final grade

Bar chart: Gender-wise average final grade


📌 Key Insights
Average Final Grade (G3): 10.42

Students Scoring Above 15: 38

Correlation (Study Time vs G3): 0.24 (moderate positive)

Higher Average G3: Female students performed slightly better on average

Visuals confirm that more study time often leads to better grades

🧰 Technologies Used
Python 3.x

Jupyter Notebook

Libraries:

pandas

numpy

matplotlib

seaborn
