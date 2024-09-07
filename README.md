# Brain Weight Prediction on Head-Brain Data
This project demonstrates a machine learning model that predicts brain weight based on head measurements, using the Head-Brain dataset. The dataset consists of observations that include attributes such as head size and brain weight, and the goal is to establish a linear relationship between them.

Project Overview
The project involves the following steps:

Data Analysis: Exploratory Data Analysis (EDA) is performed to understand the structure of the data, identify trends, and handle any missing or erroneous values.
Data Preprocessing: The dataset is preprocessed to ensure that it is clean and ready for modeling. This includes handling missing data, normalization, and splitting into training and test sets.
Model Building: A simple linear regression model is used to predict brain weight based on head size.
Evaluation: The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R² score to determine its accuracy.
Dataset
The Head-Brain dataset contains the following features:

Gender: The gender of the individual.
Age Range: The age range of the subject (in years).
Head Size (cm³): The size of the subject's head.
Brain Weight (grams): The brain weight of the subject, which is the target variable.
The dataset is sourced from Kaggle and provides a good starting point for regression modeling.

Tools and Technologies
Python: Main programming language.
Pandas, NumPy: For data manipulation and analysis.
Matplotlib, Seaborn: For visualizing relationships in the data.
Scikit-learn: For building and evaluating the linear regression model.
Key Results
The model successfully demonstrates that head size can serve as a predictor for brain weight. The linear regression model shows a strong correlation between the two variables, providing a meaningful insight into the relationship between head measurements and brain weight.
