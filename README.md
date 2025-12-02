Customer Segmentation with K-Means Clustering
Unsupervised Machine Learning for Marketing Analytics

This project applies K-Means clustering to the Mall Customers dataset to identify distinct customer segments based on Annual Income and Spending Score.
The goal is to support targeted marketing, customer experience optimization, and data-driven business strategy.

Project Objectives

Identify distinct customer groups based on income and spending behavior

Analyze demographic and purchasing patterns

Build an unsupervised machine learning model using K-Means

Provide actionable insights for business and marketing teams

Demonstrate clustering, visualization, and analysis skills in Python

Tools and Technologies
Tool / Library	Purpose
Python	Data analysis and modeling
Pandas / NumPy	Data preparation and cleaning
Matplotlib / Seaborn	Visualizations
Scikit-learn	K-Means clustering and feature scaling
Jupyter Notebook	Interactive analysis workflow
Repository Structure
customer-segmentation-project/
│
├── customer_segmentation.ipynb                 # Main notebook
├── Mall_Customers.csv                          # Dataset
├── README.md                                   # Project documentation
│
├── images/                                     # Visual outputs
│   ├── elbow_method.png
│   ├── segmentation_plot.png
│   └── cluster_summary.png
│
└── report/
    └── Customer_Segmentation_Executive_Summary.docx   # Business insights report

Dataset Description

The dataset includes key customer attributes:

Customer ID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

Clustering was performed using:

Annual Income (k$)

Spending Score (1–100)

Data Preparation Steps

Loaded and reviewed dataset structure

Checked for missing values

Selected features for clustering

Scaled features using StandardScaler

Prepared data matrix for K-Means modeling

Elbow Method — Determining Optimal Clusters

The Elbow Method identified 5 clusters as the optimal balance between compactness and separation.

Elbow Method Plot
(images/elbow_method.png)

Customer Segmentation Results (K = 5)

The model produced five meaningful clusters that differ in income and spending behavior.

Segmentation Visualization
(images/segmentation_plot.png)

Cluster Summary Table
(images/cluster_summary.png)

Interpretation of Clusters
Cluster	Description
Cluster 1	High income, high spending — premium/VIP customers
Cluster 3	High income, low spending — potential upsell opportunity
Cluster 0	Moderate income and moderate spending
Cluster 2	Moderate income, high spending — value-driven customers
Cluster 4	Low income, low spending — price-sensitive segment
Business Insights & Recommendations

Engage high-value customers with loyalty programs and exclusives

Offer targeted promotions to low-spending groups

Upsell high-income but low-spending customers with bundles and personalized suggestions

Allocate marketing budget based on behavior rather than demographics

Use segmentation to improve campaign precision and ROI

Executive Report

A full business report summarizing insights and recommendations is available:

report/Customer_Segmentation_Executive_Summary.docx

Future Enhancements

Incorporate demographic attributes (Age, Gender, etc.)

Experiment with alternative clustering algorithms (DBSCAN, GMM)

Build an interactive Tableau or Power BI dashboard

Develop customer personas for marketing teams

Author

Sahro Haji
Data Analytics Student
GitHub: https://github.com/SHAJI001
