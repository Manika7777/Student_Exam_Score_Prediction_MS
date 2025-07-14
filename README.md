# Student_Exam_Score_Prediction_MS
📊 Student Exam Score Predictor – Streamlit Web App
This project is a simple yet interactive Machine Learning web app built using Streamlit. It predicts a student’s exam score based on lifestyle and academic inputs such as study hours, sleep, attendance, mental health, and part-time work.

📁 Files Included
File Name	Description
app.py	Main Streamlit app for user interaction
best_model.pkl	Trained Linear Regression model
notebook.ipynb	EDA + model training notebook (Jupyter)
student_habits_performance.csv	Cleaned dataset used for model training
requirements.txt	All Python libraries needed to run the app
README.md	Project documentation (this file)

🌐 Run on Streamlit Cloud
Click below to access the live deployed app:

🔗 Open App on Streamlit Cloud

📌 Dataset Description
Source: Self-constructed dataset simulating student habits

Total Records: ~200+ rows

Fields Analyzed:

study_hours_per_day

attendance_percentage

mental_health_rating (scale: 1–10)

sleep_hours

part_time_job (Yes/No)

exam_score (target variable)

🔍 Key Model + App Highlights
✅ Clean Streamlit-based UI
✅ User inputs via sliders and dropdowns
✅ Predicts exam score using a trained Linear Regression model
✅ Prediction value clamped between 0 and 100
✅ Real-time prediction with visual feedback
✅ Optionally includes bar chart of feature coefficients (interpretability)

📊 Sample Visualizations (Optional in Notebook)
Correlation matrix of features

Distribution of exam scores

Boxplot for outlier detection in study hours

Bar chart of regression model coefficients (interpretability)

🧰 Tools Used
Python

Pandas – for data manipulation

Matplotlib & Seaborn – for EDA visualization

scikit-learn – model training (LinearRegression)

Streamlit – for web app creation

Joblib – model saving/loading

📄 Summary
Built a regression-based prediction model for exam scores

Found study hours and attendance as strongest predictors

Deployed successfully using Streamlit Cloud

App allows users to test how lifestyle changes might affect scores

🙋‍♀️ Author
👩 Manika Sarkar
B.Tech CSE | Machine Learning & Data Projects
🔗 GitHub Profile

📎 License
This project is for academic and learning purposes only.
Dataset is either simulated or cleaned, and no private data is used.
