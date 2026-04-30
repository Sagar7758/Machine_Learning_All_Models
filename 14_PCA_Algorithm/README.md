#### **🚑 Patient Health Pattern Analysis using PCA**

**Problem Statement**

Hospitals collect multiple health parameters such as blood pressure, cholesterol, glucose, BMI, heart rate, and oxygen level to monitor patients.

However, many of these features are highly correlated, making analysis complex and difficult to interpret.

- This project aims to reduce these correlated features into fewer meaningful components and uncover hidden patient health patterns using
Principal Component Analysis (PCA).

**Project Objective**

In this project, I aim to:

* Apply PCA to reduce the dimensionality of health data
* Retain maximum important information (variance)
* Simplify complex medical data for better understanding
* Visualize patient data in 2D space for pattern recognition
* Identify hidden patterns in patient health conditions
* Group patients based on similarity in health parameters
* Support early identification of potential high-risk patients

**Approach & Workflow**

* Data Loading and Initial Exploration
* Data Preprocessing (missing values, duplicates check)
* Feature Selection (removing Patient_ID)
* Feature Scaling using StandardScaler
* Applying PCA (dimensionality reduction)
* Evaluating PCA using explained variance
* Visualization of patient patterns (2D PCA plot)
* Creating Risk Score and Risk Groups
* Visualizing patient risk segments

 **Key Results**

* Reduced multiple health parameters into 2 principal components
* Retained a significant portion of data variance
* Identified clear patient health patterns
* Successfully grouped patients into Low, Medium, and High risk categories

 **Business Insights**

* Hospitals can quickly understand complex patient data by reducing multiple health parameters into a few meaningful components
* PCA helps identify hidden patterns that are not easily visible in raw data
* Patients with similar health conditions can be grouped together, improving analysis efficiency
* The risk scoring approach enables early identification of high-risk patients, allowing timely medical intervention
* 2D visualization helps doctors and analysts make faster and more informed decisions
* This approach reduces manual effort and promotes data-driven healthcare decision-making

**Conclusion**

In this project, I applied Principal Component Analysis (PCA) to simplify complex and highly correlated patient health data.

* PCA reduced multiple features into fewer meaningful components
* A significant amount of important information (variance) was retained
* Patient health patterns became easier to visualize and interpret
* Patients were grouped into Low, Medium, and High risk categories
* This approach supports early detection of potential health risks

- Overall, this project demonstrates how unsupervised learning can be used to simplify data, uncover patterns, and improve decision-making in healthcare.

**Tech Stack**

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 👨‍💻 Author

**Sagar Wagh**  
Aspiring Data Scientist   
📍 India 