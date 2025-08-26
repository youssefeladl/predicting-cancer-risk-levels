🧬 Cancer Severity Prediction using Machine Learning

This project focuses on predicting the severity level of cancer in patients based on demographic, lifestyle, and genetic risk factors.
It applies data science & machine learning workflows end-to-end: from cleaning and exploratory analysis to building predictive models with advanced evaluation metrics.

📌 Table of Contents

Introduction

Dataset

Exploratory Data Analysis (EDA)

Data Preprocessing

Modeling

Evaluation & Results

Visualizations

Tech Stack

How to Run

💡 Introduction

Early prediction of cancer severity is a crucial step in improving treatment plans and survival rates.
This project leverages machine learning classification models to estimate patient risk levels (low, medium, high) by analyzing multiple health and environmental factors.

🧾 Dataset

Source: Global Cancer Patients Dataset (2015–2024).

Features include:

Age

Genetic Risk

Air Pollution Exposure

Alcohol Use

Smoking

Obesity Level

Country/Region

Target Variable: Risk_level (cancer severity score).

🔍 Exploratory Data Analysis (EDA)

Distribution plots (age, lifestyle habits, genetic factors).

Correlation heatmaps between numerical features.

Boxplots for outlier detection.

Pivot tables & aggregations (e.g., top countries by cases, most common cancer types).

🧹 Data Preprocessing

Removed duplicates & irrelevant columns (e.g., Patient_ID).

Handled missing values.

Renamed variables for clarity (Target_Severity_Score → Risk_level).

Outlier analysis using boxplots.

Encoded categorical variables for modeling.

🤖 Modeling

We applied and compared multiple ML classifiers:

Logistic Regression

Random Forest Classifier

Gradient Boosting

Support Vector Machine (SVM)

Techniques used:

Train-Test Split for evaluation

Scaling & Normalization

Hyperparameter Tuning (GridSearchCV)

📊 Evaluation & Results

Metrics: Accuracy, Precision, Recall, F1-score

Visualization: Confusion Matrix, ROC-AUC curves

Example results:

Random Forest achieved the highest accuracy (~94%)

Balanced recall across classes, reducing bias in predictions

📈 Visualizations

Some key insights:

Age vs Risk Level: older patients tend to fall in higher severity categories.

Lifestyle factors (smoking, obesity, alcohol use) show strong correlation with severity.

Top cancer types & affected countries were identified via pivot tables.

🛠️ Tech Stack

Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

ML Techniques: Data Wrangling, Classification, Model Evaluation, Hyperparameter Tuning

Environment: Jupyter Notebook
