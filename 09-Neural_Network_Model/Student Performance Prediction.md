# Student Performance Prediction using Neural Network

## Project Overview

In this project, I built a **Neural Network model** to predict whether a student will **Pass or Fail** an exam based on key academic factors such as:

- Hours Studied
- Previous Exam Score

The model uses **Artificial Neural Network (ANN)** to capture relationships between study behavior and exam performance.

---

## Problem Statement

The objective of this project is to:

- Analyze student study patterns and performance
- Identify key factors affecting exam results
- Build a predictive model for pass/fail classification
- Enable early identification of at-risk students

---

## Dataset Information

The dataset includes:

- Hours_Studied  
- Previous_Score  

### Target Variable:
- Result  
  - 0 → Fail  
  - 1 → Pass  

---

## Exploratory Data Analysis (EDA)

- Most students study between **5–7 hours** (balanced distribution)
- Previous scores are concentrated around **60–70 range**
- Both features show **strong relationship with result**
- Strong correlation between features indicates **multicollinearity**
- Students with higher study hours and previous scores are more likely to pass

---

## Model Building

Steps followed:

- Data loading and understanding  
- Feature and target separation  
- Train-test split  
- Feature scaling using StandardScaler  
- Neural Network model creation  
- Model training using TensorFlow/Keras  

---

## Model Performance

- Model successfully predicts pass/fail outcomes  
- High accuracy achieved on test data  
- Confusion matrix shows good classification performance  
- Model generalizes well on unseen data  

---

## Feature Importance (Conceptual)

- Hours_Studied → Strong influence on result  
- Previous_Score → Strong predictor of performance  

Conclusion:  
 **Both study effort and past performance are key drivers of success**

---

## Conclusion

- Built a Neural Network model for student performance prediction  
- Identified key drivers: Study Hours & Previous Score  
- Achieved strong classification performance  
- Validated model using test data  

This project demonstrates both **Deep Learning modeling** and **real-world educational application**

---

## Real-world Application

- Identify students at risk of failing  
- Help teachers provide early support  
- Improve academic performance strategies  
- Enable data-driven decision making in education  

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras  

---

## Author

**Sagar Wagh**  
Aspiring Data Scientist