# PRODIGY_DS_03
## Decision Tree Classifier on Bank Marketing Dataset  
This repository contains a Python implementation of a decision tree classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data. The project uses the Bank Marketing dataset from the UCI Machine Learning Repository.

## Project Overview
This project applies machine learning techniques to the Bank Marketing Dataset to predict whether a customer will subscribe to a product or service based on their demographic and behavioral data. The dataset contains real-world marketing campaign data, making it ideal for exploring classification algorithms like Decision Trees.

The decision tree classifier is implemented using Python, with a focus on preprocessing data, training the model, and visualizing its decision-making process. This project demonstrates the practical use of machine learning to aid in decision-making for marketing campaigns.

## Objectives
- **Predictive Modeling:** Build a decision tree classifier to predict whether a customer will purchase a product (yes or no) based on the provided features.
- **Data Preprocessing:** Clean and encode the dataset to handle categorical variables, missing values, and ensure compatibility with machine learning algorithms.
- **Model Training and Evaluation:** Train the decision tree classifier using scikit-learn, evaluate its performance using metrics like accuracy and confusion matrix, and fine-tune its parameters.
- **Visualization:** Visualize the structure of the decision tree to interpret how decisions are made based on input features.
- **Actionable Insights:** Derive insights from the model to help businesses identify key customer traits influencing product subscription, improving marketing strategies.

## Features:
- Data preprocessing and encoding of categorical variables.
- Training and evaluation of a decision tree classifier using scikit-learn.
- Model evaluation with accuracy and confusion matrix.
- Visualization of the decision tree structure.

### **Data Overview**  
The dataset contains 17 columns and 4,521 rows, representing customer information. The features are categorized as follows:

- **Demographics:** Age, job, marital status, and education.  
- **Financial Information:** Account balance, housing loan status, and personal loan status.  
- **Contact Details:** Day and month of contact, along with the duration of the term deposit.  
- **Outcome:** Indicates whether the customer subscribed to a term deposit.
- **Dataset:** https://archive.ics.uci.edu/dataset/222/bank+marketing

### **Core Steps**  
1. **Data Preprocessing**  
   - Loaded the dataset and checked for null values and duplicates.  
   - Renamed the target column from "y" to "deposit."  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized age distribution, marital status, and job roles in relation to subscription outcomes.

## Insights
![image](https://github.com/user-attachments/assets/032f9ec3-ea2b-40d6-a678-739141894ad9)

- The majority of customers fall within the 30 to 40 age range.
- There is a sharp decline in the number of customers beyond 50 years of age.
- A smaller proportion of customers are below 30 years or above 60 years.
- The distribution shows a slight right skew, indicating younger customers are more common than older ones.
- The Kernel Density Estimation (KDE) curve suggests a clear peak around 30–35 years.


![image](https://github.com/user-attachments/assets/7c0ecc2a-105c-4752-b7bf-c6189e829081)

- Married customers form the largest group but have a lower proportion of deposits compared to their total count.
- Single customers show a relatively higher percentage of deposits compared to married customers.
- Divorced customers represent the smallest group, with a low proportion of deposits.
- Overall, single customers seem more likely to subscribe to deposits than other marital status groups.
This analysis suggests that marital status plays a role in deposit subscription trends and could guide targeted strategies.


![image](https://github.com/user-attachments/assets/8db4c9c5-5287-4b60-b490-f9eb3ebe772b)

- Management and blue-collar jobs are the most common job categories in the dataset, but they have relatively low deposit subscription rates.
- Technicians and services also have a significant presence but exhibit a low proportion of deposits.
- Students and retired individuals show a higher percentage of deposits despite their smaller group sizes.
- Housemaids, entrepreneurs, and unemployed individuals have the lowest counts, with minimal deposit subscriptions.
- The "unknown" category has negligible representation in both deposits and overall count.
This analysis highlights that job type influences the likelihood of deposit subscriptions, with retired individuals and students showing promising potential for targeting.










