🏠 Housing Price Prediction using Gradient Boosting
📌 Project Overview

In this project, I built a machine learning model to predict housing prices based on various features such as square footage, number of bedrooms, bathrooms, and location.

The model uses Gradient Boosting Regressor, which is effective for capturing complex relationships in data.

🎯 Problem Statement

The objective of this project is to:

Analyze housing data
Identify key factors affecting price
Build an accurate prediction model
Enable real-world house price prediction
📊 Dataset Information

The dataset includes:

Square_Feet
Bedrooms
Bathrooms
Age_of_House
Floor_Number
Near_School
Parking_Available
Location

Target Variable:

Price
🔍 Exploratory Data Analysis (EDA)
Most houses fall in the mid-price range (2M–3M) with a slight right-skew
Square_Feet has the strongest correlation with price
Bedrooms and Bathrooms show multicollinearity
Location significantly affects price (Mumbai highest, others lower)
Larger houses generally have higher prices
⚙️ Model Building

Steps followed:

Data loading and understanding
Feature and target separation
Handling categorical variables (OneHotEncoding)
Data preprocessing using ColumnTransformer
Train-test split
Model training using Gradient Boosting
📈 Model Performance
Predictions are close to actual values
Errors are mostly small and centered around zero
Model shows good accuracy and reliability
📊 Feature Importance
Square_Feet → Most important feature
Location → Strong influence
Other features → Low impact

👉 Conclusion: Price is mainly driven by size and location

🔮 Real-world Prediction

The model was tested on new unseen data and successfully predicted house price, demonstrating practical usability.

🧠 Final Conclusion
Built a Gradient Boosting model for house price prediction
Identified key drivers: Size & Location
Achieved strong model performance
Validated using real-world input

👉 This project demonstrates both machine learning modeling and practical application

🚀 Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
💼 Author

Sagar Wagh
Aspiring Data Scientist
