# Student-Performance-Prediction-
This project analyzes the **Students Performance in Exams dataset** to explore factors affecting student scores and predicts their average performance.  We perform **EDA, visualization, preprocessing, and build a predictive model** using Linear Regression

# Predict Student Performance


Visualizing and predicting student academic performance.

**1.Project Overview**

This project predicts the final grades of students based on demographic, academic, and behavioral data. By analyzing study habits, previous grades, and other factors, we identify key influences on student performance.

**2.Objective**

Predict student final grades using machine learning models.

Understand which factors (study time, absences, previous scores) influence performance the most.

**3.Dataset**

Source: Kaggle / UCI Student Performance Dataset

Features include:

gender – Student gender

age – Student age

study_time – Weekly study hours

absences – Number of school absences

previous_grades – Past exam scores

family_support, activities – Extra-curricular info

final_grade – Target variable

**4.Preprocessing**

Handled missing values (median for numerical, mode for categorical).

Encoded categorical variables using LabelEncoder.

Scaled numerical features with StandardScaler.

**5.Exploratory Data Analysis (EDA)**
1. Distribution of Final Grades

2. Gender vs Performance

3. Study Time vs Final Grade

4. Correlation Heatmap

**6.Modeling**

Model Architecture:

Baseline: Linear Regression

Optional Neural Network: Dense(64)-ReLU → Dropout(0.3) → Dense(32)-ReLU → Dense(1)-Linear

Training Details:

80:20 train-test split

Adam optimizer

20–50 epochs

Evaluation

Metrics:

RMSE (Root Mean Squared Error)

R² Score

Actual vs Predicted Grades Plot:


**7.Extensions**

Feature importance analysis to identify key performance drivers.

Interactive dashboards for exploring study habits and performance.

Advanced models like Random Forest or XGBoost can improve predictions.

**8.Tools & Libraries**

Data Handling: pandas, numpy

Visualization: plotly, plotly.figure_factory

Modeling: scikit-learn, Keras (optional)

**9.How to Run**

Clone the repository:

git clone <repo_link>


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook Predict_Student_Performance.ipynb

**10.Project Insights**

Most influential factors: study time, previous grades, absences.

Visualizations help identify trends and areas to focus for improvement.

Can be extended to a predictive tool for teachers and students.
