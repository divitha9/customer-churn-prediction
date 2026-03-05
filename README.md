# 📊 Customer Churn Prediction

# 📌 Project Overview

Customer churn is a major challenge for telecom companies. Losing customers reduces company revenue and increases the cost of acquiring new customers.

This project analyzes telecom customer data and builds a machine learning model to predict whether a customer will churn or not. The model helps companies identify customers who are likely to leave so they can implement retention strategies.

# 🎯 Project Objectives

>Analyze telecom customer data

>Identify factors influencing customer churn

>Build a machine learning model to predict churn

>Visualize patterns and trends in customer behavior

# 🛠 Tools & Technologies Used

>Python – Programming language used for analysis and modeling

>Pandas – Data manipulation and analysis

>Scikit-learn – Machine learning model development

>Google Colab – Cloud environment for running Python notebooks

>Kaggle – Source of the dataset

# 📚 Libraries Used

>Pandas

>NumPy

>Scikit-learn

# 📂 Dataset Information

The dataset was obtained from Kaggle and contains telecom customer information such as:

* Customer ID

* Gender

* Senior Citizen

* Tenure

* Internet Service

* Contract Type

* Payment Method

* Monthly Charges

* Total Charges

* Churn Status

Target Variable:

* Churn

Values:

Yes → Customer left the company

No → Customer stayed

# 🔎 Project Workflow

1️⃣ Data Collection

The telecom customer churn dataset was imported and explored to understand its structure and variables.

2️⃣ Data Cleaning

→ Checked for missing values

→ Converted incorrect data types

→ Removed unnecessary records

3️⃣ Exploratory Data Analysis (EDA)

→ Performed data visualization to understand patterns in churn behavior.

→ Key analysis included:

→ Churn distribution

→ Contract type vs churn

→ Monthly charges vs churn

4️⃣ Feature Engineering

Categorical variables were converted into numerical format for machine learning algorithms.

5️⃣ Model Building

A Logistic Regression model was built using Scikit-learn to predict customer churn.

6️⃣ Model Evaluation

→ Model performance was evaluated using:

* Accuracy Score

* Confusion Matrix

# 📊 Model Performance

→ Model Accuracy:

78%

→ Confusion Matrix: 

| Actual / Predicted | No Churn | Churn |
| ------------------ | -------- | ----- |
| No Churn           | 915      | 118   |
| Churn              | 181      | 193   |

# 📈 Data Visualizations

The project includes several visualizations such as:

* Churn distribution chart

* Contract type vs churn

* Monthly charges vs churn

* Confusion matrix visualization

These visualizations help identify important patterns affecting customer churn.

# 🔍 Key Insights

From the analysis, the following insights were identified:

* Customers with month-to-month contracts have the highest churn rate.

* Customers with higher monthly charges are more likely to churn.

* Customers with shorter tenure tend to leave earlier.

* Customers without technical support services churn more frequently.

# 💡 Business Recommendations

Based on the insights obtained:

* Encourage customers to move to long-term contracts.

* Offer loyalty discounts to high-risk customers.

* Improve customer support services.

* Implement customer retention programs.

# 🚀 Future Improvements

The project can be further improved by:

* Testing advanced machine learning models such as Random Forest,Gradient Boosting,XGBoost.

* Performing feature selection.

* Building an interactive dashboard using Power BI or Tableau.

# 👩‍💻 Author

Sai Divitha Prathapani

Aspiring Data Analyst skilled in:

* Data Analysis

* Python

* SQL

* Machine Learning

* Data Visualization
