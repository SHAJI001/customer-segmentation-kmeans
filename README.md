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
Scikit-learn	K-Means clustering + feature scaling
Jupyter Notebook	Interactive analysis workflow
Repository Structure
customer-segmentation-kmeans/
│
├── customer_segmentation.ipynb                # Main Jupyter Notebook (analysis + clustering)
├── Mall_Customers.csv                         # Dataset
├── README.md                                  # Project documentation
│
├── images/                                    # Visual outputs
│   ├── elbow_method.png
│   ├── segmentation_plot.png
│   └── cluster_summary.png
│
└── report/
    └── Customer_Segmentation_Executive_Summary.docx    # Business insights report

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

Loaded dataset and inspected structure

Checked for null values (none found)

Selected features for clustering

Scaled values using StandardScaler

Prepared feature matrix for K-Means modeling

Elbow Method – Choosing Optimal Clusters

The Elbow Method indicated that 5 clusters offer the best balance of compactness and separation.

Elbow Method Plot

Customer Segmentation Results (K = 5)

K-Means produced five meaningful customer clusters based on income and spending patterns.

Segmentation Visualization

Cluster Summary Table

Cluster Interpretations
Cluster	Description
1	High income, high spending — Premium / VIP customers
3	High income, low spending — Upsell opportunity segment
0	Moderate income, moderate spending
2	Moderate income, high spending — Value-driven shoppers
4	Low income, low spending — Budget-sensitive segment
Business Insights & Recommendations

High-value customers (Cluster 1) respond well to exclusive offers and loyalty programs

Low-income segments (Cluster 4) may require budget-friendly promotions

High-income but low-spending customers (Cluster 3) are strong upsell candidates

Marketing campaigns should target behavior-based segments, not just demographics

Segmentation supports optimized marketing spend and personalized experiences

Executive Report

A full business-ready summary is available:

📄 report/Customer_Segmentation_Executive_Summary.docx

Future Enhancements

Add demographic variables (Age, Gender) for deeper segmentation

Test alternative clustering algorithms (DBSCAN, Gaussian Mixture Models)

Deploy dashboard in Power BI or Tableau

Build customer personas based on behavior

Author

Sahro Haji
Data Analytics Student
GitHub: https://github.com/SHAJI001
