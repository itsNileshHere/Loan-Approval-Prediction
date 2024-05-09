# Loan Approval Prediction Project

This project aims to predict whether a loan will be approved or not based on various applicant features using machine learning techniques. The dataset used in this project contains information about applicants' gender, marital status, education, income, loan amount, credit history, and more.

## Exploratory Data Analysis

First, exploratory data analysis (EDA) was performed to gain insights into the dataset. Descriptive statistics were calculated for numerical features, and visualizations such as boxplots and histograms were created to understand the distribution and characteristics of the data.

## Data Preprocessing

Missing values were handled by imputing them with appropriate statistical measures such as mean, median, or mode. Categorical features were encoded into numerical format using label encoding. Outliers in numerical features were identified and removed using the interquartile range (IQR) method.

## Feature Transformation

To address skewness in certain numerical features, a square root transformation was applied. This helped in achieving a more normal distribution of the data, which is beneficial for certain machine learning algorithms.

## Model Building

Four machine learning models were trained and evaluated for this project:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Naive Bayes Classifier

The models were trained on the preprocessed dataset and evaluated using accuracy and precision scores. Confusion matrices were also plotted to visualize the performance of each model in predicting loan approval.

## Conclusion

Based on the evaluation metrics, the logistic regression and naive Bayes classifiers achieved the highest accuracy and precision scores for this dataset. However, further optimization and fine-tuning of the models may be required to improve their performance. Overall, this project demonstrates the application of machine learning techniques in predicting loan approval outcomes.
