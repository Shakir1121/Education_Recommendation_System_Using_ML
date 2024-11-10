# Education_Recommendation_System_Using_RandomForestClassifier
#Introduction:
The Education Recommendation System is a machine learning-based project designed to assist students in identifying potential career paths based on their academic performance, extracurricular involvement, and other relevant factors. This system leverages a diverse dataset containing student attributes such as academic scores, gender, extracurricular activities, part-time job status, self-study hours, and more to predict career aspirations with associated probabilities.
# Objective:
The main objective of this project is to provide personalized career recommendations to students. By analyzing each student's unique data, the model predicts the most suitable career choices, which include options like Software Engineer, Doctor, Artist, Teacher, Scientist, Business Owner, and more. This system aims to aid students in making informed career decisions that align with their skills and interests, ultimately fostering better academic and professional outcomes.
# Dataset:
This dataset contains information about students enrolled in an academy, including their personal details, academic scores, extracurricular activities, and career aspirations.
Download Dataset from https://www.kaggle.com/datasets/noorsaeed/student-studeis-recommendation
# Data Preprocessing:
- Drop Irrrevalent Columns that no Need
- Create 2 new columns / features sum and avg of all subjects
- Convert Categorical Columns into Numerical(Gender,extracurricular_activities.part_time_jobs.
- Balancing the Dataset Using SMOTE
- Feature Scaling
# Train Test Split:
- Training:80%
- Testing :20%
  # Model Development:
  This Project is a Classification Project so Training multiple ML Algorithm but not good accuracy.when using RandomForestClassifier that's accuracy is best as compared to another.so i can used this Algorithm.Achieved 82% Accuracy.
# Result:
Classification Report and Confusion Matrix are given in below table:

