# 📈 Telco Customer Churn Prediction
This project tackles the critical issue of customer churn in the telecom sector using real-world data and machine learning. By identifying patterns in customer behavior, we aim to build predictive models that help telecom companies proactively retain customers and minimize revenue loss.

#🔍 Problem Statement
Telecom providers face high costs in acquiring new customers. Retaining existing ones is far more cost-effective. Predicting which customers are likely to churn can lead to targeted retention strategies and improved business outcomes.

# 📊 Dataset
- Source: IBM Sample Dataset (via Kaggle)
- Records: 7,043 customers
- Features: Demographics, service usage, billing preferences, and churn labels

# 🧪 Techniques Used
- Data Cleaning & Transformation
- Feature Encoding & Scaling
- Handling Class Imbalance with SMOTE
- EDA using visualizations and correlation analysis
- Model Building using:
- Logistic Regression
- Random Forest
- Gradient Boosting

# Key Findings
- Customers with month-to-month contracts, high monthly charges, and low tenure are most likely to churn.
- Lack of value-added services like Tech Support or Online Security correlates with churn
- Class imbalance significantly impacts performance; SMOTE improved churn recall across all models.

 # ⚙️ Results
Model	           ||             Accuracy        ||     Recall (Churn)    ||   	Precision (Churn)   ||    	AUC
Logistic Regression	              76%	                      72%	                      53%	                 0.83
Random Forest	                    78%	                      60%	                      58%	                 0.83
Gradient Boosting	                77.5%	                    61%	                      57%	                 0.83

- Best for Business: Logistic Regression (high recall, easy to interpret)
- Best Technical Model: Gradient Boosting (robust, high accuracy, strong generalization)

# Conclusion
Predictive modeling offers a powerful tool for customer retention. The choice between Logistic Regression and Gradient Boosting depends on whether the goal is interpretable, actionable insights or high predictive performance. Both deliver strategic value in combating churn.

# Use Case
Whether you're a data analyst, a business strategist, or a machine learning practitioner, this project provides a practical blueprint for applying classification models to real-world customer retention challenges. It demonstrates how to transform raw telecom data into actionable insights using machine learning.

This churn prediction framework can be adapted across various industries where customer retention, subscription models, or user engagement are critical — such as banking, SaaS, insurance, and e-commerce. By identifying at-risk users before they leave, organizations can proactively implement targeted strategies, optimize customer experience, and minimize revenue loss.

