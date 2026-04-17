# Customer Review Sentiment Analysis using Naive Bayes

## Project Overview
Understanding customer feedback is crucial for any business, but manually reading thousands of reviews is time-consuming.

In this project, I built a **Sentiment Analysis Model** that automatically classifies customer reviews as **positive** or **negative** using **Natural Language Processing (NLP)** and the **Multinomial Naive Bayes algorithm**.

The goal is simple:  
Convert raw text into insights that businesses can act on.

---

## Problem Statement
Companies receive large volumes of customer reviews daily but struggle to analyze them efficiently.

This project aims to:
- automatically classify reviews into positive or negative sentiments  
- reduce manual effort  
- help businesses understand customer satisfaction quickly  

---

## Dataset Information
The dataset used:

**customer_reviews.csv**

### Features:
- `review` → textual feedback from customers  

### Target:
- `sentiment` → positive / negative  

---

## How the Model Works (Simple Flow)

### 1️⃣ Data Understanding
- Checked dataset shape, missing values, duplicates  
- Analyzed sentiment distribution  

👉 Insight: Understanding data quality is the first step  

---

### 2️⃣ Text Cleaning
- Converted text to lowercase  
- Removed punctuation  

👉 Cleaning removes noise and improves learning  

---

### 3️⃣ Text Vectorization
Used **CountVectorizer**  

👉 Example:  
"good product" → word frequency vector  

---

### 4️⃣ Train-Test Split
- 80% training  
- 20% testing  
- Stratified split  

---

### 5️⃣ Model Training
Used **Multinomial Naive Bayes**

👉 Why?
- fast  
- efficient  
- great for text data  

---

### 6️⃣ Prediction & Evaluation
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

### 7️⃣ Real-World Testing

```python
custom_review = ["this product is very good and useful"]

** Author ** 
  sagar wagh
Aspiring Data Scientist