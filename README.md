# 📱 App Usage Analysis Through Machine Learning

This project analyzes user interaction time with a mobile application and identifies quitting reasons through advanced analytics. The goal is to derive insights and recommend **pricing** and **retention strategies** to enhance user engagement and revenue.

---

## 🧠 Problem Statement and Approach

We analyzed a dataset of **10,000 customer records** with the following key features:
- Number of days the app was used
- Total minutes spent on the app
- Churn reasons (categorized into four types)
- Pricing tiers offered to customers

To derive actionable insights:
- **Classification models** (Random Forest Classifier, Logistic Regression) were trained, achieving approximately **67% accuracy**.
- **K-Means Clustering** segmented users based on usage and behavioral patterns.
- **Visualizations** highlighted usage trends, churn drivers, and pricing sensitivity.

---

## 🔄 Update: Dynamic Pricing Prediction

An additional module predicts the **highest price** a customer is likely to accept at two predefined probability thresholds.

- If the model doesn’t meet the confidence level for any price tier, it defaults to recommending either the **original** or the **minimum offered price**.

---

## 📊 Key Visualizations

A folder named `Images` contains all essential visualizations related to user behavior, churn analysis, and pricing impact.

---

## ▶️ How to Run the Project

## Step 1: Clone the repository
git clone https://github.com/utkarshere/ML-Driven-App-Usage-and-Churn-Analytics.git
cd App-Usage-analysis--prediction-and-strategic-recommendations

## Step 2: Install the dependencies
pip install -r requirements.txt

## Step 3: Run the project
### Option 1: If you're using a Jupyter Notebook
jupyter notebook app_usage_analysis.ipynb

### Option 2: If you're running a Python script
python main.py

