# 📊 Student Exam Score Prediction (Machine Learning)

## 📌 Project Overview

This project builds a machine learning regression model to predict a student’s exam score based on academic and lifestyle factors such as study hours, attendance, sleep, and previous performance.

The goal is to understand how different features affect predictions and to practice the end-to-end ML workflow as a beginner.

---

## 🧠 Problem Statement

Given a student’s characteristics:

- Study Hours
- Attendance Rate
- Sleep Hours
- Previous Exam Scores

Predict the final exam score using regression techniques.

---

## 📂 Dataset

- Size: 500 Students
- Type: Synthetic but realistic data
- Target Variable: exam_score

### 📌 Features

| Feature       | Description                     |
| ------------- | ------------------------------- |
| `study_hours` | Hours studied per day           |
| `attendance`  | Attendance percentage           |
| `sleep_hours` | Average daily sleep (hours)     |
| `prev_score`  | Previous exam score             |
| `exam_score`  | Final exam score (target)       |

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn

---

## 🔄 Machine Learning Workflow

1. Load and explore the dataset
2. Split data into **features and target**
3. Split into training and testing sets
4. Train **Linear Regression** model
5. Evaluate model performance using **MAE**.
6. Make predictions on new data

---

## How to Run the Project
1. Clone the repository using 

    ```bash
    git clone https://github.com/CrazyRockgg/Student-Exam-Score-Predictor.git
    cd Student-Exam-Score-Predictor
    ```
   
2. Install required packages:

    ```bash
    pip install pandas scikit-learn numpy matplotlib
    ```
   
3. Run the cells in the jupyter notebook `student_exam_score_prediction.ipynb` step-by-step to see the workflow in action.

---