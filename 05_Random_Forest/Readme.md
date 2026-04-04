# Customer Purchase Prediction using Random Forest

## Project Overview
This project predicts whether a customer is likely to purchase a product based on features such as **Age** and **Estimated Salary**.  
The model is built using the **Random Forest Classifier**, a powerful ensemble machine learning algorithm that improves prediction accuracy by combining multiple decision trees.

This project is designed as a beginner-to-intermediate level classification project and follows a structured machine learning workflow.

---

## Problem Statement
Use a **Random Forest Classifier** to predict whether a person is likely to purchase a product based on certain customer features.

The target variable is:

- **Purchased = 1** → Customer is likely to purchase  
- **Purchased = 0** → Customer is not likely to purchase  

---

## Dataset Information
The dataset used in this project is:

**Social_Network_Ads.csv**

### Features used:
- **Age**
- **EstimatedSalary**

### Target:
- **Purchased**

### Optional columns:
- **User ID** → removed because it does not help prediction  
- **Gender** → converted into numeric format if present  

---

## Project Workflow

### Step 1: Import Required Libraries
Imported important Python libraries for:
- numerical operations  
- data handling  
- data visualization  
- model training and evaluation  

### Step 2: Data Loading
Loaded the dataset using Pandas.

### Step 3: Data Understanding
Performed basic data exploration using:
- `df.head()`  
- `df.describe()`  
- `df.info()`  

This helped in understanding:
- data structure  
- feature types  
- basic statistics  

### Step 4: Data Cleaning and Preprocessing
Performed preprocessing steps such as:
- checking missing values  
- checking duplicate rows  
- removing duplicate rows  
- dropping unnecessary columns like `User ID`  
- converting categorical column `Gender` into numerical form  

### Step 5: Feature and Target Splitting
Selected:
- **X = Age, EstimatedSalary**  
- **y = Purchased**  

### Step 6: Visualization
Used visualization to understand customer behavior:
- Scatter Plot of **Age vs EstimatedSalary**  
- Color encoding based on **Purchased**  

This helped in identifying customer purchase patterns visually.

### Step 7: Train-Test Split
Split the data into:
- **80% Training Data**  
- **20% Testing Data**  

### Step 8: Feature Scaling
Applied `StandardScaler` for pipeline consistency.

> Note: Random Forest does not strictly require feature scaling, but it was included to maintain a consistent workflow.

### Step 9: Model Initialization
Initialized the **Random Forest Classifier** with:
- `n_estimators = 100`  
- `random_state = 42`  

### Step 10: Model Training
Trained the model using the training dataset.

### Step 11: Prediction
Predicted customer purchase outcomes on the test dataset.

### Step 12: Model Evaluation
Evaluated the model using:
- **Confusion Matrix**  
- **Accuracy Score**  

### Step 13: User Input
Accepted user input for:
- Age  
- Estimated Salary  

### Step 14: Prediction on User Input
Used the trained model to predict whether the entered customer is likely to purchase.

### Step 15: Final Output
Displayed the final result in a user-friendly format:
- **Customer will purchase**  
- **Customer will not purchase**  

---

## Visualization Used

### Customer Purchasing Behavior
A scatter plot was used to visualize:
- **Age**  
- **Estimated Salary**  
- **Purchase decision**  

This graph helps to understand how customer demographics influence buying behavior.

---

## Model Used

### Random Forest Classifier
Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their outputs to improve accuracy and reduce overfitting.

### Why Random Forest?
- handles classification problems effectively  
- reduces overfitting compared to a single decision tree  
- works well on structured datasets  
- provides stable performance  

---

## Evaluation Metrics
The model was evaluated using:

- **Confusion Matrix**  
- **Accuracy Score**  

These metrics help measure how well the model classifies customers into purchase and non-purchase categories.

---

## Key Insights
- **Age** and **Estimated Salary** are strong indicators of purchase behavior.  
- Customers with certain age and salary ranges are more likely to purchase the product.  
- Random Forest provides a strong baseline model for this classification task.  

---

## Project Structure

```bash
Customer-Purchase-Prediction-Random-Forest/
│
├── customer_purchase_prediction_random_forest.ipynb
├── Social_Network_Ads.csv
├── images/
│   └── random_forest_visualization.png
└── README.md

---

## Author

**Sagar Wagh**  
Aspiring Data Scientist