# Customer-Churn-Analysis-Project
Customer Churn Analysis using Python, Machine Learning, and Power BI to predict customer attrition and generate business insights.


<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/f8f2eabd-0ddc-4dd5-8794-dd0556bb1299" />


# PROJECT WORKFLOW: 
<img width="1151" height="1367" alt="image" src="https://github.com/user-attachments/assets/6398e6c7-3005-4cab-a9ff-1d25500978fb" />


**Project Overview**

Customer retention is one of the most important challenges faced by subscription-based businesses. Acquiring new customers is significantly more expensive than retaining existing ones. Therefore, identifying customers who are likely to leave the company is critical for improving customer satisfaction and increasing profitability.

This project focuses on analyzing customer behavior and predicting customer churn using Machine Learning techniques. The project includes data preprocessing, exploratory data analysis, visualization, predictive modeling, model evaluation, and an interactive Power BI dashboard for business decision-making.


**Business Problem**

Customer churn occurs when customers discontinue their relationship with a company. High churn rates negatively impact revenue and customer lifetime value.

The objective of this project is to:

1. Identify factors contributing to customer churn
2. Analyze customer behavior patterns
3. Predict whether a customer is likely to churn
4. Provide actionable business recommendations
5. Visualize churn trends through an interactive Power BI dashboard


**Dataset Information**

Dataset: Customer Churn Retention

**Kaggle Dataset (IBM Telco Customer Churn):**

[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?utm_source=chatgpt.com)

The dataset contains customer demographic information, account details, subscribed services, and churn status.

Key Attributes:- 
Gender
Senior Citizen
Partner
Dependents
Tenure
Phone Service
Internet Service
Online Security
Device Protection
Contract Type
Payment Method
Monthly Charges
Total Charges
Churn Label
Project Workflow
Data Collection
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Data Visualization
Machine Learning Model Development
Model Evaluation
Business Insight Generation
Power BI Dashboard Development
Data Preprocessing


**The following preprocessing steps were performed:**

1. Removal of irrelevant columns
2. Handling missing values
3. Data type corrections
4. Label Encoding
5. One-Hot Encoding
6. Feature Selection
7. Train-Test Split
8. Exploratory Data Analysis


**Several visualizations were created to understand customer behavior and churn patterns:**

1. Customer Churn Distribution

2. Analyzed overall churn percentage among customers.

3. Contract Type Analysis

4. Studied churn behavior across different contract categories.

5. Monthly Charges Analysis

6. Examined the relationship between monthly charges and churn.

7. Tenure Analysis

8. Investigated how customer retention varies with tenure.

9. Correlation Analysis

10. Identified relationships between features using heatmaps.


# DATA RELATIONSHIP MODEL 
It shows relationship among different tables : 

<img width="1256" height="505" alt="image" src="https://github.com/user-attachments/assets/8e96ff91-fe6c-4b96-a066-da94358009d0" />


**Machine Learning Models**

The following models were implemented:

**Logistic Regression**
A baseline classification model used to predict customer churn.

**Random Forest Classifier**
An ensemble learning model used for improved prediction performance and feature importance analysis.

**Support Vector Machine** 
A supervised machine learning algorithm that classifies data by finding the optimal boundary (hyperplane) that best separates different classes.

* **XGBoost Classifier:**
A powerful gradient boosting algorithm that builds decision trees sequentially to improve prediction accuracy and reduce errors.


# Model Evaluation Metrics

The models were evaluated using:

1. Accuracy Score
2. Precision
3. Recall
4. F1 Score 
5. ROC-AUC Score
6. Confusion Matrix

# Insights:

1. Customers on the Two-Year contract, have been with the company for long, while most of the customers on Month-to-Month contract joined the company.
2. The company is at risk of losing recently joined customers. based on the results from analysis.. if they decided to month-to-month contract.
3. 7043 customers are at the risk of churn. and The churn rate is 27%  and yearly charges is $16.06M charges. and Monthly Charges is $456.12K monthly charges.
4. 2955 tech tickets were opened and 3632 admin tickets were opened.
5. Most of the churned customers  did not sign up for Online Security and tech support and  also did not sign up for Phone Services.
6. It a lot of customers had an issue with Fiber Optic . Up to 42% of the customers churned were using Fiber Optic as their Internet Services.
7. Customer churn is higher in certain cities and regions (highest in Los Angeles) , indicating location-specific retention challenges.
8. The machine learning model successfully identified customers with a high risk of churn based on their behavior and service usage patterns.


# Recommendations:

1. The Company could try convincing customers to subscribe to One-Year and Two-Year contract. The contract are not favorable to customers  as they tend to pay more monthly.
2. Giving the discount to customers based on the some specific tasks is also good wat retaining them, specially those month-to-month contract.
3. From analysis majority customers who churned did not sigh up for Online Security and Tech Support. These are the important services that customers should customers signup for. The company should educate customers  on the benefits of signing up for these services.
4. Increase sale of 1 and 2 year contract by 5% each and Yearly increase of automatic payments by 5%.
5. Focus retention campaigns and service improvements in high-churn geographic areas.
6. Use the predictive model to proactively target high-risk customers with personalized retention offers.


# Power BI Dashboard

The Power BI dashboard provides:

Customer Churn Dashboard 
<img width="904" height="509" alt="image" src="https://github.com/user-attachments/assets/e5f4a255-2ed5-46f1-aa29-a8c0f873baf8" />

Customer Risk Dashboard
<img width="912" height="505" alt="image" src="https://github.com/user-attachments/assets/dd47d676-7a1b-4e73-9632-e41906d1b2ca" />

Services Dashboard
<img width="911" height="507" alt="image" src="https://github.com/user-attachments/assets/dc840686-5d53-4353-82da-8d3d25c597bf" />

Geography Dashboard
<img width="892" height="502" alt="image" src="https://github.com/user-attachments/assets/56a80ce4-148a-464c-b91f-e6f75e272ccc" />

ML Algorithm Dashboard
<img width="888" height="497" alt="image" src="https://github.com/user-attachments/assets/f8deb64f-ed02-4252-a7dc-962095143f51" />

Insights & Recommendations 
<img width="909" height="504" alt="image" src="https://github.com/user-attachments/assets/f08b9bda-8a8d-47ee-811f-bf2d2b18f0f7" />


# PROJECT OUTCOME
The project successfully identified the major drivers of customer churn and developed predictive models capable of forecasting churn risk. The insights generated can help businesses improve customer retention strategies and reduce revenue loss.


## Installation & Dependencies

### Clone the Repository

```bash
git clone https://github.com/vrindmangla/Customer-Churn-Analysis-Project.git
cd Customer-Churn-Analysis
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Required Dependencies

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* openpyxl
* jupyter
* xgboost

### Run the Project

1. Open the Jupyter Notebook.
2. Load the dataset from the `Dataset` folder.
3. Execute the notebook cells sequentially.
4. Review visualizations, model results, and evaluation metrics.
5. Open the Power BI dashboard (`.pbix`) file to explore interactive insights.


# Author

**Vrind Mangla**
**Data Analytics | Machine Learning | Power BI**
