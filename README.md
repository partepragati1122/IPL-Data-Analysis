# IPL-Data-Analysis
🏏 IPL Data Analysis & Match Prediction (2008–2022)

📌 Project Overview

This project performs an advanced exploratory data analysis (EDA) and machine learning modeling on Indian Premier League (IPL) data from 2008 to 2022.
The goal of this project is to analyze player performance, match trends, scoring patterns, and build a machine learning model to predict match winners.


📂 Dataset

The dataset consists of two CSV files:
IPL_Matches_2008_2022
IPL_Ball-by-Ball_2008_2022 


🛠 Tools & Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn


🧹 Data Cleaning

Removed duplicates
Handled missing values
Converted date columns
Merged match-level and ball-level datasets
Encoded categorical variables for ML


📊 Exploratory Data Analysis (EDA)

🔥 Player Performance
Top 10 Batsmen by Total Runs
Top 10 Bowlers by Wickets
Batting Average & Consistency Analysis
Bowling Economy Rate


📈 Match Trends

Year-wise Total Runs Trend
Toss Impact on Match Result
Powerplay vs Death Over Comparison


⚡ Advanced Metrics

Player Consistency (Standard Deviation of runs per match)
Strike Rate Calculation
Phase-wise scoring analysis


🤖 Machine Learning Model
Objective:
Predict match winner based on team features.

Steps:
Label Encoding of teams
Train-Test Split (80-20)
Random Forest Classifier
Model Accuracy Evaluation

Sample Code:
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score

model = RandomForestClassifier()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
print("Model Accuracy:", accuracy_score(y_test, y_pred))


📊 Dashboard Visualization

Created a dashboard-style layout using Matplotlib & Seaborn including:
Top Batsmen Chart
Top Bowlers Chart
Year Trend Line Chart
Toss Impact Pie Chart
Powerplay vs Death Over Bar Chart


📌 Key Insights

Death overs contribute significantly to total match runs.
Scoring trends have increased over seasons.
Toss has influence but does not guarantee victory.
Consistency plays a major role in player performance.


🚀 How to Run This Project

Clone the repository
Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Jupyter Notebook 


📈 Future Improvements

Add more match features (venue, toss decision, etc.)
Improve ML model accuracy
Deploy as Streamlit Web App
Create interactive dashboard


👩‍💻 Author

Pragati Santosh Parte

Aspiring Data Analyst | Python | Power BI | Machine Learning

⭐ If you like this project, consider giving it a star!
