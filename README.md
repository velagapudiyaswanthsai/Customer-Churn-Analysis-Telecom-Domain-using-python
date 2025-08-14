# Customer-Churn-Analysis-Telecom-Domain-using-python

📊 Customer Churn Analysis – Telecom Domain
📌 Project Overview

This project analyzes customer churn data for a telecom company to identify patterns and factors contributing to customer attrition. Using Python for data manipulation, visualization, and predictive modeling, the project aims to support customer retention strategies through data-driven insights.

The dataset contains 7,043+ customer records with demographic, account, and service-related attributes.

🎯 Objectives

Analyze customer data to identify key churn factors.

Build predictive models to forecast churn probability.

Create visualizations to understand trends and customer behavior.

Recommend strategies to improve retention.

🗂 Dataset

Source: Provided as part of Python for Data Science training.
Key Features:

Demographics: Gender, Senior Citizen, Partner, Dependents

Account Information: Tenure, Contract Type, Payment Method

Services: Internet Service, Online Security, Streaming TV, etc.

Target Variable: Churn (Yes/No)

⚙️ Tech Stack

Programming Language: Python

Libraries & Tools: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Machine Learning Models:

Linear Regression

Logistic Regression (Simple & Multiple)

Decision Tree Classifier

Random Forest Classifier

📈 Workflow
1. Data Manipulation

Filtered subsets of customers based on tenure, payment method, and churn status.

Extracted specific columns for focused analysis.

Random sampling for testing subsets.

2. Data Visualization

Bar Plot: Distribution of Internet Service categories.

Histogram: Tenure distribution.

Scatter Plot: Monthly Charges vs Tenure.

Box Plot: Tenure vs Contract type.

3. Model Development & Evaluation
Model	Metric	Result
Linear Regression	RMSE	29.39
Logistic Regression	Accuracy	76.36%
Decision Tree	Accuracy	75.08%
Random Forest	Accuracy	73.60%
📌 Key Insights

Senior citizens with electronic check payments have a higher churn rate.

Customers with month-to-month contracts are more likely to churn.

High monthly charges correlate with higher churn probability.

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/customer-churn-analysis.git
cd customer-churn-analysis


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook "Solution -Python Capstone Project.ipynb"

📜 Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter

📊 Results & Impact

The models developed can help telecom companies predict potential churners with up to 76% accuracy, enabling targeted retention campaigns and revenue protection strategies.

📄 License

This project is licensed under the MIT License – see the LICENSE file for details.


Visualizations:

![Sales Trend](images/sales_trend.png)  
![Revenue by Product](images/revenue_product.png)  
![Confusion Matrix](images/confusion_matrix.png)
