📦 Parcel Delivery Time Estimation
Linear Regression Assignment – LR/02

This repository contains the complete solution for the Linear Regression Assignment: Parcel Delivery Time Estimation.
The goal of the project is to analyse delivery operations data and build a linear regression model that predicts delivery time based on various order, store, and operational features.

📁 Repository Contents
File	Description
LR_Delivery_Time_Prediction_<your_name>.ipynb	Main Jupyter Notebook with full analysis, EDA, preprocessing, and model building
LR_Delivery_Time_Prediction_<your_name>.pdf	Final report containing visualisations, insights, conclusions, and interpretations
data/	Folder containing the dataset (if required for upload)
README.md	Project overview and instructions
🎯 Project Objective

To build a regression model that can:

Predict delivery time for an order

Identify key drivers affecting delivery duration

Improve operational planning through data-driven insights

Evaluate model performance using regression metrics

🧪 Project Workflow
1. Data Loading

Load dataset into a pandas DataFrame

Inspect columns, missing values, and basic structure

2. Data Preprocessing & Feature Engineering

Includes:

Fixing datatypes

Cleaning timestamps

Computing time_taken_minutes

Handling missing values

Train–validation split (to avoid data leakage)

3. Exploratory Data Analysis (EDA)
Training Data EDA

Distribution of numerical features

Distribution of categorical features

Target variable distribution

Relationship between input features and delivery time

Correlation heatmap

Outlier detection and treatment

Validation Data EDA (Optional)

Performed separately to avoid leakage.

4. Model Building

Feature scaling

Simple Linear Regression

Multiple Linear Regression

Feature selection using RFE (Recursive Feature Elimination)

Comparison of models

5. Results & Interpretation

Residual analysis

Coefficient analysis

Identifying important predictors

Error trends and insights

📊 Key Insights

Distance, number of busy dashers, and order complexity strongly influence delivery time

Skewed variables benefit from transformation

Feature selection improves generalisation

Residuals help validate model assumptions

📝 Final Deliverables

✔ Jupyter Notebook
✔ PDF Report
✔ Visualisations
✔ Business Insights
✔ Conclusions & Recommendations

🔧 Tech Stack

Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Statsmodels

Scikit-Learn

🏁 Conclusion

This project demonstrates how linear regression can be used to predict delivery times and identify operational factors influencing delays.
The findings can help logistics platforms optimise workforce planning, improve delivery accuracy, and enhance customer experience.

👤 Author

<Sagar Fadtare>
Assignment: LR_Delivery_Time_Prediction
