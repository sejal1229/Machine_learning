# PRODIGY_ML_02

📘  Project: Customer Segmentation using K-Means Clustering


🔹 Introduction

Customer segmentation is one of the most widely used applications of unsupervised machine learning in business and marketing.

The objective of this project is to apply K-Means clustering to group customers into distinct segments based on their purchasing behavior and demographic attributes.

These segments help businesses better understand their customer base and design targeted marketing strategies.

🔹 Dataset Description

The dataset contains information about customers, typically including:

- CustomerID – Unique identifier for each customer

- Age – Age of the customer

- Annual Income – Income level of the customer

- Spending Score – Score assigned based on spending habits

  For segmentation, we mainly focus on Annual Income and Spending Score, since these two features provide meaningful insights into customer purchasing patterns.

🔹 Methodology

- Importing Libraries

  Used pandas, numpy for data manipulation, matplotlib and seaborn for visualization, and sklearn for clustering.

- Loading and Exploring the Dataset

  The dataset was loaded and explored using .head(), .info(), and .describe() functions.

  Checked for missing values and basic data distributions.

- Feature Selection
  
  Selected important attributes like Annual Income and Spending Score for clustering.

- Data Visualization

Plotted distributions and scatterplots to understand customer spread across income and spending dimensions.

- Finding Optimal Clusters (Elbow Method)

  The Elbow Method was used to determine the optimal number of clusters by plotting WCSS (Within-Cluster Sum of Squares) against the number of clusters.

  The “elbow point” was identified as the best cluster number.

- Applying K-Means Clustering
  
  Implemented the K-Means algorithm with the chosen number of clusters.
  
  Assigned each customer to a cluster.

- Visualizing Clusters
  Plotted the clusters in 2D space (Income vs Spending Score) with distinct colors to interpret the segmentation results.

🔹 Results and Insights

  The customers were successfully grouped into distinct clusters such as:

- High Income – High Spending (premium customers)
- High Income – Low Spending (savers)
- Low Income – High Spending (potentially impulsive spenders)
- Low Income – Low Spending (budget-conscious customers)

These insights help businesses to:

Identify valuable customer groups

Create targeted marketing campaigns

Improve customer relationship management

🔹 Conclusion

This project demonstrates how K-Means clustering can be applied for customer segmentation. 

By analyzing attributes like income and spending score, businesses can identify meaningful customer groups and tailor their strategies accordingly. 

The approach provides a foundation for data-driven decision-making in marketing and customer relationship management.
