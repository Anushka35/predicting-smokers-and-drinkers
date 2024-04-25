# DM_Project_2
Team : T04    Dataset : Smoking and Drinking Dataset with Body Signal


**Overview:**

This repository contains an analysis of the Smoking and Drinking Dataset with body signal. The dataset contains attributes like sex, age, physical attributes, various medical measurements, such as cholesterol levels, blood pressure, and smoking and drinking habits. The primary goal of this analysis is to explore the dataset, perform data analysis and get insights, and develop predictive models for different objectives related to smoking and drinking. The overview of steps we followed is:

1. **Initial Analysis:**
   - First we performed basic data analysis , which  included checking the shape, examining data types, looking for missing values, checking the number of unique values in each column, identifying duplicate rows and knowing the mathematical description of data.

2. **Exploratory Data Analysis (EDA) and Preprocessing:**
   - Then we conducted EDA is to gain insights into the dataset. This includes visualizations and analyses of variables like blood pressure, body measurements, haemoglobin levels, cholesterol levels, etc.
   - Gender-wise analysis was done. We also compared different factors for the smoking and drinking groups through boxplots and histplots.
   - We encoded categorical variables (e.g., 'sex' and 'DRK_YN') using label encoding. Also, removed duplicate rows from the dataset.

3. **Classification Problems:**
   - We identified two classification tasks:
     - Task 1: Predicting Smoking Status (SMK_stat_type_cd)
     - Task 2: Predicting Drinking Status (DRK_YN)

4. **Model Building and Evaluation:**
   - For each classification task:
     - Initially, we used all the features except the target variable and trained different models (Decision Tree, Logistic Regression and Support Vector Classifier)
     - Then, selected some features based on correlation with the target variable and trained different models (Decision Tree, Random Forest, Logistic Regression, and Support Vector Classifier) 
     - Performed hyperparameter tuning for random forest and logistic regression models. 
     - Used classification reports to assess model performance and compare different models.

**Conclusion:**
Accuracy of 70 % is achieved to predict smoker/drinker.
