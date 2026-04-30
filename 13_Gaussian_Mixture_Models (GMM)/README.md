#### **Network Traffic Anomaly Detection using GMM**

### **Project Overview**

In this project, I built an Anomaly Detection System using
Gaussian Mixture Model (GMM)
to identify abnormal network traffic behavior.

The focus of this project is to detect unusual patterns in network data without using labeled data.

### **Objective**

* Detect abnormal network activity
* Identify suspicious behavior
* Segment traffic into risk categories
* Reduce manual monitoring

### **Dataset Features**

* Packet_Size
* Request_Frequency
* Connection_Duration
* Failed_Logins
* Data_Transfer


### **Steps Performed**

**Step 1:** Import required libraries
**Step 2:** Load dataset
**Step 3:** Basic data understanding
**Step 4:** Data cleaning (if required)

**Step 5:** Exploratory Data Analysis

            - Univariate Analysis
            - Bivariate Analysis

 (Multivariate analysis was not used in this project)

**Step 6:** Feature Scaling (StandardScaler)

**Step 7:** Model Training using GMM

**Step 8:** Cluster Prediction

**Step 9:** Anomaly Detection using probability

**Step 10:** Traffic Segmentation

    - High Risk
    - Medium Risk
    - Normal

**Step 11:** Visualization

**Step 12:** Final Output Dataset

### **Model Output**
    - Cluster label
    - Probability score
    - Risk category

 Lower probability = Higher anomaly 

### **Important Note**

This is an **Unsupervised Learning Model**, so no Accuracy, Precision, or Recall is used.

### **Business Impact**

-  Detects suspicious network activity early
-  Improves overall network security
-  Reduces manual monitoring effort
-  Helps prevent financial loss from cyber attacks
-  Segments traffic into actionable risk categories
-  Enables data-driven security decisions

### **Conclusion**

I built an anomaly detection system using
Gaussian Mixture Model
to identify abnormal network behavior.

- I detected hidden patterns without labeled data
- I classified traffic into High, Medium, and Low risk
- Demonstrates the power of unsupervised learning in cybersecurity
- Can be extended into real-time intrusion detection

**Author**\n
Sagar Wagh\n
(Aspiring Data Scientist )