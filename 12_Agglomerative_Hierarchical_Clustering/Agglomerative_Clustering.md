#### ***Customer Lifestyle Hierarchy Analysis using Agglomerative Clustering***

#### **Project Overview**

In this project, I performed Customer Segmentation using Agglomerative Hierarchical Clustering to identify meaningful customer groups based on lifestyle and spending behavior.

Unlike traditional segmentation, this project focuses on understanding hierarchical relationships between customers, helping businesses move towards personalized and data-driven strategies.

#### **Problem Statement**

Businesses often rely on basic segmentation techniques, which fail to capture deeper behavioral patterns.

This project aims to:

- Analyze customer data using Age, Income, Spending Score, Purchase Frequency, and Order Value
- Identify distinct customer groups based on lifestyle patterns
- Understand how smaller clusters combine into larger groups
- Enable targeted and personalized marketing strategies

#### **Dataset Information**
 The dataset contains the following features:

- Customer_ID
- Age
- Annual_Income
- Spending_Score
- Purchase_Frequency
- Average_Order_Value

#### **Project Workflow (Step-by-Step)**
#### *Step 1: Data Loading & Understanding*
- Loaded dataset using Pandas
- Checked data types, missing values, and summary statistics
#### *Step 2: Data Preprocessing*
- Checked missing values and duplicates
- Selected relevant features for clustering

#### ***Step 3: Exploratory Data Analysis (EDA)***

#### **Univariate Analysis**
    - Distribution plots for all features

#### **Bivariate Analysis**
    - Income vs Spending Score
    - Age vs Spending Score

#### **Correlation Analysis**
    - Heatmap showed very weak correlation (~0) between features

#### **Key Insights from EDA**
    - No strong linear relationship between features
    - Customer behavior is complex and independent
    - Justifies the use of clustering techniques

#### **Feature Scaling**
    - Applied StandardScaler
    - Converted features to same scale (mean = 0, std = 1)
    - Essential for distance-based clustering


#### **Hierarchical Clustering**

#### Dendrogram Analysis
    - Used Ward method
    - Identified possible cluster range (~4–5 clusters)

#### **Cluster Comparison**

Tested multiple cluster values (K = 2 to 7) using:

    - Silhouette Score (higher is better)
    - Davies-Bouldin Score (lower is better)
    - Calinski-Harabasz Score (higher is better)

     Best K (mathematically) = 7

#### **Final Model**
    - Applied Agglomerative Clustering
    - Linkage Method: Ward
    - Final Clusters: 7

#### **Cluster Visualization**

 Clusters show clear variation in income and spending behavior

#### **Cluster Profiling (Key Findings)**

Each cluster represents different customer behavior:

    -  Premium Customers → High income + High spending
    - Careful Spenders → High income + Low spending
    - Risky Customers → Low income + High spending
    - Low Engagement → Low income + Low spending


#### **Model Evaluation**
        Metric	            Value	Interpretation
        Silhouette Score	~0.13	Weak separation
        Davies-Bouldin	    ~1.57	Moderate overlap
        Calinski-Harabasz	~28	    Low separation

##### **Conclusion:** Clusters are meaningful but slightly overlapping

#### Customer Segments

Final business segments created:

    - Premium High-Spending Customers
    - High Income Careful Spenders
    - Frequent Budget Customers
    - Low Engagement Customers


#### Business Impact

This project helps businesses understand customer behavior beyond traditional segmentation by identifying lifestyle-based customer groups.

Using hierarchical clustering, customers are segmented into meaningful groups such as premium customers, budget buyers, and careful spenders.

* These insights enable businesses to:

    - Retain high-value customers through loyalty programs
    - Increase revenue by targeting high-income but low-spending customers
    - Identify risky customers and optimize financial strategies
    - Reduce marketing costs by avoiding low-engagement segments

 Helps shift from mass marketing → personalized marketing

#### Conclusion

- Customer behavior is multi-dimensional and not dependent on a single feature
- Clustering helps uncover hidden patterns
- Hierarchical clustering provides deeper insights into customer grouping
- Although cluster separation is moderate, segmentation is business-useful
- Further tuning can improve model performance

#### Technologies Used

Python 
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn


👤 Author
Sagar Wagh
Aspiring Data Scientist

#### Final Note

This project demonstrates how machine learning can transform raw customer data into actionable insights for real-world business applications.