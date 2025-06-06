# Predicting Customer Purchase Behavior Using Decision Trees in Python with the Bank Marketing Dataset for Smarter Marketing Decisions

![image](https://github.com/user-attachments/assets/abcf4a73-0273-4f8d-8f38-cd08c1d81b5e)

## All datasets and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All info are dummy and design to demonstrate my capabilities of using Python to build Decision Trees

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


![image](https://github.com/user-attachments/assets/e1df1897-801f-47d7-9912-4a62951c64c3)

- Customers with secondary education form the largest group but have a low proportion of deposits.
- Tertiary-educated customers have a higher deposit subscription rate compared to primary and secondary groups.
- Primary education group is the smallest among known education levels, with fewer deposits.
- Unknown education category has very few data points, making it difficult to derive meaningful insights.
- Higher education levels (tertiary) seem to correlate with a greater likelihood of deposit subscriptions.
This suggests that education level may influence financial decisions, with higher-educated individuals more likely to invest in deposits.


![image](https://github.com/user-attachments/assets/37a42409-a697-4b7f-add2-76598db837fe)


- More customers have housing loans compared to those without.
- Deposit subscription is lower across both groups, but slightly higher among those without housing loans.
- Customers without housing loans seem more likely to subscribe to a deposit than those with housing loans.
- Financial commitments like housing loans may influence a customer’s ability or willingness to invest in deposits.
This suggests that customers with existing financial obligations may be less inclined to commit to additional financial products.

## Model
- Split the dataset into training and testing set (80:20 split)
- Built a decision tree classifier using sklearn

## Model Evaluation
- The accuracy of 90% on the test set.
- Generated a classification report with precision, recall and F1-score
- Visualized the decision tree structure for better interpretability

## Confusion Matrix
- Predicted	   No	  Yes
- No	         785  22
- Yes	         63	  35

## Metrics
- Precision: 77%
- Recall: 66%
- Weighted Average F1-score: 89%

## Results
The model provides a strong foundation for customer prediction analysis, aiding in better targeting and decision-making processes. Let's continue refining and exploring

## Conclusion:
This model provides a strong baseline for predicting customer behavior, offering insights that can enhance marketing strategies. However, improvements in handling class imbalance and refining model complexity can further optimize predictions.

# Contact
- Linkedln: http://www.linkedin.com/in/festus-ijabani-159585293
- Email: ijabanifestus01@gmail.com
