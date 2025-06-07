📘 Student Habits vs Academic Performance: A Simulated Study
This project explores the relationship between students' daily habits and their academic performance using machine learning techniques. The dataset contains simulated yet realistic data of 1,000 students, including lifestyle habits such as study hours, sleep, social media use, diet quality, mental health, and more—mapped against their final exam scores.

🧠 Problem Statement
Educational outcomes are influenced not only by intelligence and curriculum but also by lifestyle choices. However, quantifying this influence can be challenging. This project aims to leverage machine learning to predict final exam scores based on behavioral and lifestyle data, providing insights into which habits most affect academic success.

🎯 Objective
Predict students’ final exam scores using regression models.

Analyze and visualize the impact of various lifestyle factors on academic performance.

Identify key features influencing performance using feature importance metrics.

Build a scalable and interpretable pipeline suitable for educational insights.

📁 Dataset Overview
The dataset includes the following features:

Numerical: Study hours, sleep hours, screen time, mental health rating, etc.

Categorical:

Label Encoded: diet_quality, parental_education_level, internet_quality

One-Hot Encoded: gender, part_time_job, extracurricular_participation

Target Variable: Final_Exam_Score

🔧 Project Workflow
Data Preprocessing

Null checks

Manual Label Encoding and One-Hot Encoding

Feature Scaling with StandardScaler

Model Building

Train-test split (80-20)

Model used: RandomForestRegressor

Evaluation

Metrics: Mean Squared Error (MSE), R² Score

Visualization: Feature importance and Actual vs Predicted plots

📈 Results
Mean Squared Error: 38.88

R² Score: 0.848

The model accurately predicts student scores and explains ~85% of score variability.

📊 Key Insights
Habits like study hours, mental health, and internet quality have a significant impact on exam performance.

Feature importance graphs provide actionable insight for educational improvement.

📂 Files
student-habit-vs-academic-performance.ipynb: Main notebook with full pipeline

student_habits.csv: Input dataset

README.md: Project documentation (this file)

🚀 Future Enhancements
Try model tuning with GridSearchCV

Implement additional models like XGBoost, Gradient Boosting

Extend the dataset to include attendance, assignment scores, etc.

Deploy as a Flask app for real-time prediction

📌 Requirements
pandas
scikit-learn
matplotlib
seaborn
Install all with:

pip install -r requirements.txt
🙌 Author
Bhanu Goel
Data Analyst & ML Enthusiast
Delhi, India
