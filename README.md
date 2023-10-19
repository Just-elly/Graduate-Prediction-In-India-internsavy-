# Graduate Admission Prediction in India

This project aims to predict the chances of admission for graduate students in India using a dataset containing various factors such as GRE scores, TOEFL scores, university ratings, and more. The project involves data analysis, exploratory data visualization, and the application of different machine learning models for prediction.


## Introduction

Graduate admission can be a highly competitive process, and this project aims to provide insights into the factors that influence admission decisions. We will use data analysis and machine learning techniques to predict the chances of admission based on various criteria.

## Dataset
The dataset used was acquired from kaggle:
/kaggle/input/graduates-admission-prediction/admission_data.csv

The dataset used in this project contains the following columns:
- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP)
- Letter of Recommendation (LOR)
- CGPA (Cumulative Grade Point Average)
- Research Experience
- Chance of Admission (Target Variable)

## Exploratory Data Analysis

In the exploratory data analysis (EDA) phase, we explored the dataset, visualized the relationships between different variables, and calculated correlation coefficients. Key findings from the EDA include:
- Strong positive correlations between GRE scores and the chance of admission.
- Positive correlations between TOEFL scores and the chance of admission.
- The influence of university ratings, SOP, LOR, and CGPA on admission.

## Data Preprocessing

The data preprocessing step included handling missing values (if any) and standardizing the features. Fortunately, there were no missing values in the dataset, and we used Min-Max scaling to standardize the feature values.

## Machine Learning Models

We applied several machine learning models to predict the chance of admission. These models include:
- Linear Regression
- Lasso Regression
- Polynomial Regression
- Ridge Regression
- K-Nearest Neighbors (KNN)

We evaluated the performance of these models using metrics such as R-squared and visualized the results to determine the best model.

## Results

- The best-performing model was K-Nearest Neighbors (KNN) with an R-squared score of approximately 0.92.
- Polynomial regression showed improved performance with a degree of 2 or 3.
- Other models, such as linear regression and ridge regression, also provided reasonable results.

## Conclusion

This project demonstrated the predictive power of machine learning models in determining the chances of graduate admission. The choice of the most suitable model can vary depending on the dataset and data preprocessing steps. In this context, K-Nearest Neighbors (KNN) proved to be a strong model for this admission prediction task.

Feel free to explore the Jupyter Notebook or Python script for a more detailed analysis of the project. Your feedback and contributions are welcome.


