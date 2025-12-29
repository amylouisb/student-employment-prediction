# Student Employment Prediction

**Machine learning project to predict student employment opportunities using Python and Scikit-learn**

## Project Overview
This repository contains a machine learning project focused on predicting college student placement outcomes. The study identifies key factors that influence employability and compares multiple classification models to find the most effective predictive tool.

The primary goal is to determine whether a student will secure a job based on their academic and non-academic profiles. This project provides data-driven insights for students to understand which areas—beyond just GPA—significantly impact their career opportunities.

## Key Insights & Conclusions
- **Grades Aren't Everything**: The analysis confirms that while GPA is important, students with average grades can significantly boost their employment chances by focusing on **Projects Completed** and **Extra-Curricular Scores**.  
- **Best Model**: The Random Forest model emerged as the top performer, providing high precision and recall, making it a reliable tool for placement screening.  
- **Feature Interaction**: Creating complex feature interactions (e.g., GPA x Internship Experience) did not necessarily improve performance and, in some cases (like KNN), introduced noise that reduced accuracy.

## Dataset Features
The model analyzes **10,000 student records** with the following attributes:

- **Academic**: CGPA, Previous Semester Results, Academic Performance  
- **Experience**: Internship Experience (Yes/No), Projects Completed  
- **Personal Skills**: IQ, Communication Skills, Extra-Curricular Score  
- **Target**: Placement (Yes/No)  
- **Dataset Source**: Kaggle - College Student Placement Factors

## Tech Stack
- **Language**: Python  
- **Data Handling**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Scikit-Learn (Logistic Regression, KNN, Random Forest, Naive Bayes)  
- **Imbalance Handling**: SMOTE (Imbalanced-Learn)

## Experiments Conducted
1. **Baseline Training**: Evaluated standard models on raw data  
2. **Feature Importance**: Identified "Projects" and "Extra-Curriculars" as critical differentiators  
3. **Model Optimization**: Used RandomizedSearchCV for hyperparameter tuning
