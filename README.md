# Voice-Based-Health-Classification

📖 Project Overview
This project explores how acoustic features extracted from human voice recordings can be used to predict vocal health.
By combining Exploratory Data Analysis (EDA), data visualization in Power BI and  machine learning models, the project identifies measurable differences between healthy and unhealthy voices.

🎯 Objectives
Analyze the acoustic feature dataset (VowelA_High_latest.csv) to uncover key patterns.
Build and evaluate machine learning models to classify vocal health.
Visualize results and insights through an interactive Power BI dashboard.

🧠 Key Insights
Unhealthy voices show higher spectral variability and entropy, indicating instability.
Ensemble models like Random Forest and XGBoost achieved the highest performance:

⚙️ Methodology
1. Data Preparation
Cleaned missing values, normalized numeric features.
Encoded categorical data (Gender, Label).
Split dataset 80/20 for training/testing.
2. Exploratory Data Analysis
Identified correlations between MFCCs, RMSE, and spectral features.
Visualized feature distributions by health status.
Observed clear separation between healthy and unhealthy voice clusters.
3. Modeling
Trained and evaluated multiple classifiers:

Logistic Regression
Random Forest
XGBoost

💻 Tools & Technologies
Libraries	Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost
Visualization	Power BI
