#  **Logistic Regression Projects Collection**

This repository contains multiple Machine Learning projects implemented using **Logistic Regression**.  
The goal is to understand and apply different types of logistic regression:

- **Binary Logistic Regression**
- **Multinomial Logistic Regression**
- **Ordinal Logistic Regression**

Each project focuses on a different real-world business problem and demonstrates data preprocessing, EDA, model training, evaluation, and business impact.

---

#  **Projects Included**

# **1️⃣ E-Commerce Purchase Prediction (Binary Logistic Regression)**

## **Problem Statement**
An e-commerce company wants to predict whether a customer will make a purchase based on customer activity and demographic details.

## **Objective**
Predict:
- **0 → No Purchase**
- **1 → Purchase**

## **Features Used**
- Age
- Time_Spent
- Added_to_Cart
- Previous_Purchases

## **Steps Performed**
- Data Loading
- Data Cleaning
- Exploratory Data Analysis
- Feature Selection
- Train-Test Split
- Logistic Regression Model
- Prediction
- Evaluation

## **Evaluation Metrics**
- Accuracy Score
- Confusion Matrix
- Classification Report

## **Business Impact**
- Identify customers likely to buy
- Improve marketing strategy
- Increase conversion rate
- Better customer targeting

---

# **2️⃣ Email Spam Detection (Binary Logistic Regression)**

## **Problem Statement**
Classify emails as spam or not spam.

## **Objective**
Predict:
- **0 → Not Spam**
- **1 → Spam**

## **Dataset Features**
- Email Text
- Label

## **Steps Performed**
- Text preprocessing
- Data cleaning
- TF-IDF vectorization
- Train-Test Split
- Logistic Regression
- Prediction
- Evaluation

## **Metrics**
- Accuracy
- Confusion Matrix
- Classification Report

## **Business Impact**
- Reduce spam emails
- Improve inbox filtering
- Better user experience

---

# **3️⃣ News Article Category Classification (Multinomial Logistic Regression)**

## **Problem Statement**
Predict the category of a news article based on text.

## **Objective**
Classify articles into:
- Business
- Entertainment
- Politics
- Sport
- Tech

## **Dataset Features**
- News Text
- Category

## **Steps Performed**
- Text preprocessing
- TF-IDF vectorization
- Multinomial Logistic Regression
- Prediction
- Evaluation

## **Metrics**
- Accuracy
- Confusion Matrix
- Classification Report

## **Business Impact**
- Faster article categorization
- Content recommendation
- News automation systems

---

# **4️⃣ Customer Satisfaction Level Prediction (Ordinal Logistic Regression)**

## **Problem Statement**
Predict customer satisfaction level based on service and demographic data.

## **Objective**
Predict:
- Low
- Medium
- High

## **Features Used**
- Age
- Monthly Income
- Product Quality Rating
- Support Rating

## **Steps Performed**
- Data Cleaning
- EDA
- Feature Selection
- Train-Test Split
- Ordinal Logistic Regression
- Prediction
- Evaluation

## **Metrics**
- Accuracy
- Confusion Matrix
- Classification Report

## **Business Impact**
- Understand customer experience
- Improve service quality
- Increase retention

---

##  **Technologies Used**

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

##  **Machine Learning Concepts Covered**

- Binary Classification
- Multiclass Classification
- Ordinal Classification
- Feature Engineering
- Text Vectorization
- Model Training
- Prediction
- Accuracy Evaluation
- Confusion Matrix
- Classification Report

---

##  **Repository Structure**

```bash
02_Logestic_Regression/
│
├── E-Commerce Purchase Prediction.ipynb
├── Email Spam Detection.ipynb
├── News Article Category Classification.ipynb
├── Customer Satisfaction Level Prediction.ipynb
├── datasets/
├── images/
└── README.md