### **Music Pattern Visualization using t-SNE**

#### **Problem Statement**

Music streaming platforms collect multiple audio features such as tempo, loudness, energy, danceability, and acousticness for each song.

However, these features are high-dimensional, making it difficult to visualize and understand similarities between songs or genres.

 This project aims to reduce high-dimensional audio features into a 2D space and visualize hidden patterns and clusters of songs using
**t-Distributed Stochastic Neighbor Embedding.**

### **Project Objective**

In this project, I aim to:

* Apply t-SNE to reduce high-dimensional audio features into 2D space
* Preserve similarity between songs (similar songs closer, different songs apart)
* Visualize hidden clusters of songs based on audio characteristics
* Identify patterns between different music genres
* Understand how songs group naturally without labels
* Explore relationships between audio features like energy, tempo, and loudness
* Improve interpretability of complex music data through visualization

#### **Approach & Workflow**

* Data Loading and Initial Exploration
* Data Preprocessing (missing values, duplicate check)
* Feature Selection (removing Song_ID, Song_Name, Genre)
* Feature Relationship Analysis (correlation heatmap)
* Feature Scaling using StandardScaler
* Applying t-SNE (dimensionality reduction)
* Visualization with Genre labels
* Visualization without labels (natural clustering)
* Result Interpretation

#### **Key Results**

* Reduced high-dimensional audio features into 2D representation
* Similar songs appeared closer, preserving relationships
* Clear clusters were observed across different genres
* Natural grouping was visible even without labels
* Feature relationships were identified using correlation analysis

#### **Business Insights**

* Helps music platforms understand **song similarity based on audio features**
* Enables **automatic grouping of similar songs** for playlist generation
* Supports **better music recommendation systems**
* Reveals hidden patterns across different genres
* Simplifies complex audio data into **clear visual insights**
* Assists in **data-driven decision-making** for music analytics and personalization

 Can be extended for **real-time music recommendation and clustering systems**

#### **Conclusion**

In this project, I applied
t-Distributed Stochastic Neighbor Embedding
to visualize high-dimensional music data.

* Successfully reduced complex audio features into 2D space
* Similar songs were placed closer, preserving relationships
* Clear clustering patterns were observed across genres
* Natural grouping validated the strength of unsupervised learning

 Overall, this project demonstrates how t-SNE helps in understanding complex data, discovering hidden patterns, and improving interpretability.

#### **Tech Stack**
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

