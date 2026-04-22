** Problem Statement **

A mall wants to understand its customer base better in order to improve its marketing strategy. The goal is to segment customers into different groups based on their Annual Income and Spending Score, so that the marketing team can design targeted campaigns according to each group’s preferences and behavior.

* Objective
Analyze customer behavior using income and spending data
Segment customers into meaningful groups
Identify purchasing patterns
Help marketing team create targeted campaigns

* Dataset Information

The dataset includes:

AnnualIncome → Customer’s yearly income
SpendingScore → Customer’s spending behavior score
* Exploratory Data Analysis (EDA)
Scatter plot used to visualize income vs spending
Histograms used to understand distribution of income and spending
Data shows different customer patterns based on spending behavior


* Model Used
- KMeans Clustering (Unsupervised Learning)
Groups similar customers together
Helps discover hidden patterns in data
Does not require labeled data


* Model Evaluation
Inertia (WCSS) → Measures cluster compactness
Silhouette Score → Measures cluster separation
Davies-Bouldin Score → Measures cluster overlap


* Customer Segments

After clustering, customers are grouped into:

 Premium Customers
 Careful Rich Customers
 Impulsive Buyers
 Budget Customers
 Marketing Strategy
Premium Customers → Luxury products, VIP offers
Careful Rich Customers → Value-based premium deals
Impulsive Buyers → Flash sales, trending products
Budget Customers → Discounts, combo offers


* Visualizations

The project includes:

Income vs Spending Scatter Plot
Income Distribution Histogram
Spending Score Histogram
Elbow Method Graph
Cluster Visualization
Cluster Count Chart
Segment Count Chart
Segmented Customer Plot


🧾 Conclusion

In this project, we applied KMeans Clustering to segment customers based on their income and spending behavior. The clusters were converted into meaningful business segments, making the analysis useful for real-world marketing strategies.

The model successfully identifies different customer types and helps businesses understand customer behavior more effectively.

💼 Business Impact
 Enables targeted marketing campaigns
 Improves customer engagement
 Helps increase revenue through focused strategies
 Supports data-driven decision making
 Can be scaled to real-world applications


 Project Workflow
Import Libraries
Load Dataset
Perform EDA
Select Features
Apply Elbow Method
Train KMeans Model
Assign Clusters
Evaluate Model
Analyze Clusters
Assign Business Labels
Visualize Segments
Suggest Marketing Strategy
Predict New Customer
Save Output

📁 Project Structure
10_KMeans_Clustering/
│
├── mall_customers_kmeans_dataset.csv
├── kmeans_clustering.py
├── images/
│   ├── Income Vs Spending.png
│   ├── AnnualIncome.png
│   ├── SpendingScore.png
│   ├── Elbow Method.png
│   ├── Clusters.png
│   ├── Cluster Count.png
│   ├── Segment Count.png
│   ├── Segmented Customers.png
│
└── README.md
  
  Future Improvements

Use real-world dataset (Kaggle)
Add more features (Age, Gender, Location)
Try advanced clustering (DBSCAN, Hierarchical)
Build dashboard (Power BI / Tableau)
Deploy using Streamlit

 
 Author
Sagar Wagh
Aspiring Data Scientist