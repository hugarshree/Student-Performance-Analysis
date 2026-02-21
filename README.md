🎓 Student Performance Analysis & Prediction
📌 Project Overview

This project analyzes student academic performance using Exploratory Data Analysis (EDA) and builds a Machine Learning model to predict final grades.

The dataset is synthetically generated using Python and includes student scores, attendance, and study hours.

🛠 Technologies Used

🐍 Python
📊 Pandas
🔢 NumPy
📈 Matplotlib
🎨 Seaborn
🤖 Scikit-learn
📂 Dataset Information

The dataset contains 200 students with the following features:

Column Name	Description
student_id	Unique student ID
gender	M / F
math_score	Math marks (40–100)
reading_score	Reading marks (45–100)
writing_score	Writing marks (42–100)
attendance	Attendance percentage (60–100)
study_hours	Daily study hours (1–6)
final_grade	Weighted final grade
📊 Final Grade Calculation
Final Grade =
0.3 × Math Score +
0.3 × Reading Score +
0.3 × Writing Score +
0.1 × Attendance
🔍 Exploratory Data Analysis (EDA)

The following analysis was performed:

✔ Data inspection (head(), info(), describe())
✔ Missing value check
✔ Correlation analysis
✔ Study hours vs final grade visualization
✔ Gender-based performance comparison

📈 Visualizations
Study Hours vs Final Grade (Scatter Plot)
Attendance Distribution (Histogram)
Performance by Gender (Boxplot)
Correlation Matrix (Heatmap)

🤖 Machine Learning Model
Model Used:
Linear Regression
Feature Selection:

study_hours
attendance
math_score
reading_score
writing_score
Target:
final_grade
Train-Test Split:

80% Training

20% Testing

📊 Model Performance
Mean Squared Error (MSE): 0.090
R² Score: 0.999

✅ The model performs extremely well because the final grade was generated using a linear formula.

🔮 Prediction Example
Example student:
Study Hours: 4
Attendance: 90
Math: 85
Reading: 88
Writing: 87

Predicted Final Grade: 86.98
