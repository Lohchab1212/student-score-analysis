# Student Exam Score Analysis

## Overview
This project analyses the exam performance of 1,000 students across 
math, reading and writing subjects using Python. The goal was to 
identify key factors that influence student performance.

## Dataset
Students Performance in Exams — Kaggle  
1,000 rows, 8 columns including gender, parental education, 
lunch type, test preparation and exam scores.

## Key Findings
- Females outperform males in reading and writing, while males 
  score higher in math.
- Students who completed the test preparation course scored 
  significantly higher across all subjects (math: 69 vs 64).
- Higher parental education level is linked to better student 
  performance (master's degree: ~70 vs high school: ~62).
- Math scores are left skewed — most students performed well.
- Reading and writing are highly correlated (0.95), while math 
  is more independent.
## Visualisatons
<img width="1200" height="500" alt="Average_scores_by_level of education" src="https://github.com/user-attachments/assets/a29f028c-4d2d-4a2d-8987-d3363a4eb133" />

<img width="800" height="500" alt="Average_scores_by_gender" src="https://github.com/user-attachments/assets/ffdd3846-ed55-45a5-b36e-d9b6b175d2b4" />

<img width="800" height="500" alt="maths_score_dist" src="https://github.com/user-attachments/assets/14faac68-6dba-44c5-bf40-51cc2c91e875" />

<img width="800" height="500" alt="correlation-heatmap" src="https://github.com/user-attachments/assets/5c5d87ef-b353-454f-9d26-dadb7cd01fc4" />

<img width="800" height="500" alt="actual_vs_predicted_math_score" src="https://github.com/user-attachments/assets/5939a2cc-b367-45bf-9822-1d6a35f13177" />

## Machine Learning
Built a Linear Regression model to predict math scores using 
reading and writing scores.
- R² Score: 0.68
- RMSE: 8.79

## Tools Used
- Python, Pandas, Matplotlib, Seaborn, Scikit-learn
