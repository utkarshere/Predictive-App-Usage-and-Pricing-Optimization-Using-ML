# **📱 App Usage Analysis Through Machine Learning**

A project involving the analysis of user interaction time with a mobile application and identifying quitting reasons through advanced analytics. The goal is to derive insights and recommend pricing and retention strategies to enhance engagement and revenue.

## Problem Statement and approach

This project analyzes a dataset of  **10,000 customer records** , focusing on user engagement with a mobile application. Key features include:

* Number of days the app was used
* Total minutes spent on the app
* Reasons for user churn (four categories)
* Pricing tiers offered to customers

To extract insights and drive strategy:

* **Classification models** like **Random Forest Classifier** and **Logistic Regression** were trained, achieving an accuracy of approximately **67%.**
* **K-Means Clustering** was used to segment users based on usage traits and behavioral patterns.
* **Visualizations** were created to showcase usage trends, churn factors, and pricing sensitivity.



## 🔄 Update

An additional analysis has been added that builds a classification model to **predict the highest price a customer is likely to accept** at two predefined probability thresholds.

If no acceptable price is identified based on the model’s confidence, the system defaults to recommending either the **original** or the  **minimum offered price** .
