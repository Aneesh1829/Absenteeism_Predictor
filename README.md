# Absenteeism_Predictor
🧾 Absenteeism Analysis Project
📌 Project Overview
The Absenteeism Analysis Project is a data-driven study that explores the patterns, causes, and predictors of employee absenteeism. By analyzing various factors such as transportation expenses, BMI, age, and reasons for absence, the project aims to provide actionable insights to Human Resources (HR) departments to manage and reduce employee absenteeism. This project includes both machine learning modeling and interactive data visualization using Tableau.

🎯 Objectives
Identify the main causes of absenteeism.

Clean and preprocess real-world absenteeism data.

Perform exploratory data analysis (EDA) to uncover key trends.

Build a predictive model to classify and estimate absenteeism risk.

Create interactive dashboards using Tableau for intuitive understanding and storytelling.

📁 Dataset
The dataset contains anonymized employee absenteeism records with the following features:

Reason for Absence (categorical codes)

Date of Absence

Transportation Expense

Age

Body Mass Index (BMI)

Education Level

Children

Pets

Month Value

Absenteeism Time in Hours

⚙️ Technologies Used
Python – Data preprocessing, modeling, analysis

Pandas, NumPy – Data manipulation

Scikit-learn – Model building (e.g., Logistic Regression, Decision Tree)

Matplotlib, Seaborn – Visualization for EDA

Tableau – Interactive dashboards and visual storytelling

Jupyter Notebook – Code development and documentation

📊 Key Steps
Data Cleaning & Preprocessing

Removed missing values and inconsistent entries

Encoded categorical variables and created dummy variables

Extracted new features like day of the week

Exploratory Data Analysis (EDA)

Visualized absentee trends based on age, BMI, transportation cost

Grouped absence reasons into meaningful categories

Identified patterns using heatmaps and pair plots

Model Building

Built a classification model to predict absenteeism probability

Evaluated model using metrics like accuracy, ROC-AUC, confusion matrix

Interactive Visualization using Tableau

Designed dashboards to show:

Absenteeism by reason category

Trends by month, day of the week, and department

Demographic influence (age, education, BMI, etc.)

Enabled filtering by date range and individual employee ID

🔍 Results & Insights
High BMI, long transportation times, and certain reasons (e.g., medical or personal issues) strongly correlate with frequent absenteeism.

Older employees showed slightly higher absentee rates.

Tableau dashboards helped clearly communicate patterns and allowed for interactive exploration by HR teams.

📌 Conclusion
This project combines machine learning and interactive visual analytics to help organizations:

Understand the root causes of absenteeism

Take preventive actions for high-risk employees

Design informed HR policies and wellness programs

🧠 Future Work
Incorporate more employee-specific features (e.g., job role, department)

Use time series forecasting to predict absenteeism trends

Deploy the model with a Flask/Streamlit interface

Embed Tableau dashboards into a web application or HR tool
