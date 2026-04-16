# **Analysis of Factors Affecting Car Pricing in Poland**
### **INTRODUCTION**
This project focuses on identifying and analyzing the key factors affecting used car prices in Poland. By leveraging data analysis and machine learning, it aims to build a predictive model to accurately estimate car prices. The project implements a data science pipeline, from data cleaning and exploratory data analysis (EDA) to building regression models.
### **MODELS USED FOR TRAINING IN THIS PROJECT**
- `Linear Regression:` Produces relatively biased price predictions based on the year of manufacture.
- `Support Vector Regressor:` Produces significantly biased price predictions based on the year of manufacture, with high error rates.
- `Random Forest:` Achieves very high predictive accuracy.
### **WORKFLOW**
- `Data Preprocessing:` Handling missing and duplicate values, removing outliers.
- `Exploratory Data Analysis (EDA):` Visualized the data to understand the relationships between technical features and price.
- `Model Training:` Split the data into train, test, and validation sets, with a 70/30 split for train/temp, followed by a 50/50 split of the temp set into test and validation for model training.
- `Model Evaluation:` Comparing models using metrics such as R-squared ($R^2$), Mean Absolute Error (MAE), and Root Mean Square Error (RMSE).
### **TECHNOLOGIES**
- Python
- Scikit-learn
- Linear Regression
- SVR
- Random Forest
- Matplotlib
- Seaborn
