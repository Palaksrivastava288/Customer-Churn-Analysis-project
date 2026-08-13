# Customer-Churn-Analysis-project
# Customer Churn Analysis & Prediction

## 📌 Project Overview
This project analyzes customer churn using Python and basic machine learning techniques. The goal is to understand customer churn patterns, identify important customer characteristics, and build a basic predictive model to identify customers who may be at risk of churn.

## 🎯 Objectives
- Clean and prepare customer data
- Perform exploratory data analysis (EDA)
- Apply statistical analysis
- Identify patterns associated with customer churn
- Build basic machine learning classification models
- Compare model performance
- Generate business insights and recommendations

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow
### 1. Data Understanding
- Examined dataset structure
- Checked data types and dimensions
- Reviewed numerical and categorical variables

### 2. Data Cleaning
- Handled missing values
- Converted appropriate columns to numeric format
- Removed unnecessary columns
- Prepared categorical variables for analysis

### 3. Exploratory Data Analysis
Analyzed relationships between churn and factors such as:
- Contract type
- Internet service
- Tenure
- Monthly charges
- Total charges
- Customer services

Visualizations were created using Matplotlib and Seaborn.

### 4. Statistical Analysis
Performed basic statistical analysis including:
- Mean
- Median
- Quartiles
- Percentiles
- Interquartile Range (IQR)
- Outlier detection
- Skewness

### 5. Machine Learning
Basic classification models were implemented using Scikit-learn:

#### Logistic Regression
Used to predict whether a customer is likely to churn or stay.

#### Random Forest
Used as a second classification model for comparison.

### 6. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

### 📊 Model Results
| Model | Accuracy | ROC-AUC |
|---|---:|---:|
| Logistic Regression | 80.1% | 0.849 |
| Random Forest | 79.5% | 0.837 |
Logistic Regression performed better on this dataset based on the overall evaluation results.

## 💡 Key Insights
- Tenure Months was one of the most important predictive features.
- Monthly Charges and Total Charges were also important predictive features.
- CLTV was another important feature for the Random Forest model.
- Internet Service – Fiber optic appeared among the important categorical predictors.
- The analysis provides useful information for identifying customers who may require targeted retention efforts.

## 💼 Business Recommendations
- Focus retention efforts on customers with shorter tenure.
- Monitor customers with higher monthly charges.
- Identify high-risk customer segments using customer and service information.
- Use churn prediction as a supporting tool for targeted retention strategies.

