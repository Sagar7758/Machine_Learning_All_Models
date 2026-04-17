# 📊 Customer Churn Prediction using Machine Learning

##  Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Losing existing customers directly impacts revenue and growth.

In this project, I built a **Machine Learning model** to predict whether a customer is likely to churn (leave the service) or not, using historical customer data.

The goal is simple —
 **Identify at-risk customers early and help businesses take proactive action.**

---

##  Problem Statement

A telecom company wants to reduce customer churn by identifying customers who are likely to leave.

Using historical customer behavior data, the objective is to:

* predict customer churn
* understand key factors behind churn
* support business decision-making

---

##  Dataset Information

The dataset contains customer-related information such as:

* `tenure` → how long the customer has stayed
* `MonthlyCharges` → monthly billing amount
* `TotalCharges` → total billing
* `Contract` → contract type
* `InternetService` → type of internet service
* `TechSupport` → availability of support
* `PaymentMethod` → payment type
* `Churn` → target variable (0 = No, 1 = Yes)

---

##  Project Workflow

This project follows a complete end-to-end machine learning pipeline:

### 1️⃣ Data Understanding

* Checked dataset shape, structure, and data types
* Identified missing values and duplicates
* Reviewed statistical summary

---

### 2️⃣ Exploratory Data Analysis (EDA)

* Visualized churn distribution
* Identified class balance
* Used correlation heatmap to understand feature relationships

---

### 3️⃣ Data Preprocessing

* Cleaned column names to avoid hidden errors
* Converted categorical features into numerical format using **Label Encoding**
* Prepared clean dataset for modeling

---

### 4️⃣ Feature Scaling

* Applied **StandardScaler** to normalize feature values
* Important step for SVM performance

---

### 5️⃣ Train-Test Split

* Split dataset into training (80%) and testing (20%)
* Used stratified sampling to maintain class balance

---

### 6️⃣ Model Training

* Used **Support Vector Machine (SVM)** with RBF kernel
* Captures complex, non-linear patterns in data

---

### 7️⃣ Model Evaluation

The model was evaluated using multiple performance metrics:

* **Accuracy Score** → Overall correctness
* **Classification Report** → Precision, Recall, F1-score
* **Confusion Matrix** → Detailed prediction breakdown
* **ROC-AUC Score** → Model’s ability to distinguish classes

---

##  Key Insights

* The model is able to distinguish between churn and non-churn customers effectively
* Certain features like contract type and service usage show strong influence on churn
* Scaling significantly improves SVM performance

---

## 💼 Business Impact

This model can help businesses:

* Identify high-risk customers early
* Reduce churn through targeted retention strategies
* Improve customer satisfaction and loyalty
* Optimize marketing and support efforts

 Instead of reacting after customers leave, the company can now **act before churn happens**

---

##  Future Improvements

* Try advanced models like Random Forest or XGBoost
* Perform hyperparameter tuning for better accuracy
* Use feature selection techniques
* Deploy model using Streamlit for real-time predictions
* Integrate with business dashboards (Power BI / Tableau)

---

##  Author

**Sagar Wagh**
Aspiring Data Scientist

---

##  Final Thought

This project is not just about building a model —
it’s about solving a real business problem using data.

 Turning raw data into meaningful decisions is the true power of Data Science.
