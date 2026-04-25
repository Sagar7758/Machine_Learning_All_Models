#  E-commerce Customer Segmentation using DBSCAN

##  Project Overview

In this project, I built an **unsupervised machine learning model** to segment e-commerce customers based on their purchasing behavior.

Unlike traditional clustering methods, this project uses **DBSCAN**, which can automatically detect clusters and identify outliers.

 The goal is to help businesses understand customers better and improve marketing strategies.

---

##  Problem Statement

An e-commerce company wants to improve its marketing strategy by identifying different types of customers.

Traditional segmentation methods are not effective.

 So, we use **DBSCAN clustering** to group customers based on:

- Annual Income  
- Spending Score  
- Purchase Frequency  
- Average Order Value  

---

##  Dataset Information

The dataset includes:

- `Annual_Income`
- `Spending_Score`
- `Purchase_Frequency`
- `Average_Order_Value`

These features represent **customer value and behavior**

---

## Algorithm Used

### 🔹 DBSCAN (Density-Based Clustering)

- Groups customers based on density  
- Detects outliers automatically  
- No need to define number of clusters  
- Works well for real-world data  

---

##  Project Workflow

1. Import Libraries  
2. Load Dataset  
3. Data Understanding  
4. Data Cleaning  
5. Feature Selection  
6. Feature Scaling  
7. EPS Selection using KNN Distance Plot  
8. Train DBSCAN Model  
9. Assign Clusters  
10. Cluster Analysis  
11. PCA Visualization  
12. Model Evaluation  
13. Business Insights  
14. Final Conclusion  

---

##  Visualizations

-  KNN Distance Plot (EPS Selection)  
-  Cluster Count Plot  
-  PCA Cluster Visualization  
-  Income vs Spending Scatter Plot  
-  Purchase Frequency vs Order Value  
-  Pairplot  

---

##  Model Evaluation

- **Silhouette Score** → Cluster separation  
- **Davies-Bouldin Score** → Cluster overlap  
- **Calinski-Harabasz Score** → Cluster strength  

---

##  Customer Segments

-  Premium Customers  
-  Loyal Customers  
-  Low Engagement Customers  
-  Moderate Customers  
-  Outliers (Noise)  

---

##  Business Insights

###  Premium Customers
High income + high spending  
 Target: VIP offers, premium products  

###  Loyal Customers
High frequency + high order value  
 Target: Loyalty programs  

###  Low Engagement
Low spending behavior  
 Target: Discounts & reactivation  

###  Outliers
Unusual behavior  
 Target: Fraud detection / niche strategy  

---

##  Business Impact

- Improves marketing targeting  
- Increases conversion rate  
- Identifies high-value customers  
- Reduces marketing cost 
- Detects unusual behavior 

---

##  Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- DBSCAN  
- PCA  

---

##  Project Structure


DBSCAN_Customer_Segmentation/
│
├── ecommerce_customers.csv
├── dbscan_model.ipynb
├── images/
│ ├── KNN Distance Plot.png
│ ├── Cluster Count.png
│ ├── PCA Visualization.png
│ ├── Income vs Spending.png
│ ├── Frequency vs Order Value.png
│ ├── Pairplot.png
│
└── README.md


---

##  Future Improvements

- Deploy using Streamlit  
- Create Power BI Dashboard  
- Use real-world large dataset  
- Try advanced clustering (HDBSCAN)  

---

##  Final Conclusion

DBSCAN successfully segmented customers based on purchasing behavior and identified outliers.

 This project demonstrates how machine learning can be used to generate actionable business insights and improve decision-making.

---

##  Author

**Sagar Wagh**  
Aspiring Data Scientist 