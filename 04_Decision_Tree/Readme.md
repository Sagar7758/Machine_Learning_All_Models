# 🌳 Customer Purchase Prediction using Decision Tree

## 📌 Project Overview

This project predicts whether a customer will purchase a product based on their **Age** and **Estimated Salary** using a **Decision Tree Classifier**.

The model analyzes customer behavior and classifies them as:

* ✅ Target Customer (Will Purchase)
* ❌ Not Target Customer (Will Not Purchase)

---

## 🎯 Problem Statement

To build a machine learning model that predicts customer purchase behavior based on:

* Age
* Income (Estimated Salary)

---

## 🧠 Algorithm Used

* **Decision Tree Classifier**

  * Easy to interpret
  * Rule-based model
  * No need for feature scaling

---

## 📂 Dataset

* **File Name:** `Social_Network_Ads.csv`
* Features used:

  * Age
  * EstimatedSalary
* Target:

  * Purchased (0 or 1)

---

## ⚙️ Project Workflow

1. Import required libraries
2. Load dataset using Pandas
3. Perform data exploration (`head()`, `info()`, `describe()`)
4. Check missing and duplicate values
5. Split features and target
6. Visualize data using scatter plot
7. Perform train-test split (80-20)
8. Train Decision Tree model
9. Make predictions
10. Evaluate using accuracy & confusion matrix
11. Visualize Decision Tree
12. Take user input and predict result

---

## 📊 Visualizations

### 🔹 Scatter Plot (Customer Distribution)

* Shows relationship between Age and Salary
* Helps understand customer behavior

### 🌳 Decision Tree Visualization

* Shows how model makes decisions
* Displays rules used for prediction

---

## 📈 Model Performance

* **Accuracy:** 91.25%
* **Confusion Matrix:**

```
[[47  5]
 [ 2 26]]
```

---

## 🖥️ How to Run

1. Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

2. Run the script:

```bash
python decision_tree_customer_prediction.py
```

3. Enter user input:

```
Enter Age: 30
Enter Salary: 50000
```

4. Output:

```
Target Customer (Will Purchase)
```

---

## 📁 Project Structure

```
project/
│
├── decision_tree_customer_prediction.py
├── Social_Network_Ads.csv
├── images/
│    ├── scatter_plot.png
│    └── decision_tree.png
└── README.md
```

---

## ⚠️ Note

* Warning related to feature names may appear during prediction.
* It does not affect model performance.

---

## 🚀 Future Improvements

* Add **Education feature**
* Compare with Logistic Regression & KNN
* Build Streamlit Web App
* Hyperparameter tuning

---

## 💡 Conclusion

The Decision Tree model successfully predicts customer purchase behavior with high accuracy.
It is simple, interpretable, and effective for classification tasks.

---

## 🙌 Author

* Sagar Wagh
