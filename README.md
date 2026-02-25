🧩 Customer Segmentation using Machine Learning
📌 Project Overview

This project focuses on customer segmentation using unsupervised machine learning techniques. The goal is to group customers based on their demographics, purchasing behavior, and engagement patterns to support targeted marketing strategies.

By applying clustering algorithms, the project identifies meaningful customer segments that help businesses improve marketing efficiency, customer retention, and revenue.

🎯 Objectives

Segment customers based on behavior and demographics

Apply clustering algorithms (K-Means, Hierarchical, DBSCAN)

Evaluate models using Elbow Method and Silhouette Score

Generate actionable business insights from clusters

Build an interactive Streamlit dashboard

📊 Dataset

File: marketing_campaign.xlsx

Records: 2240 customers

Features: 29 attributes

Key Feature Types:

Demographic: Age, Income, Education, Marital Status

Behavioral: Spending, Purchases, Recency

Campaign: Response, Complaints

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn, Plotly

Scikit-learn

Streamlit

🔍 Exploratory Data Analysis (EDA)

Income and spending distributions are right-skewed

Strong correlation between Income and TotalSpend

Outliers were removed for better clustering

Key features selected for segmentation

🤖 Models Used
Model	Purpose
K-Means	Primary segmentation
Hierarchical Clustering	Comparison
DBSCAN	Density-based clustering
PCA + K-Means	Improved separation
📈 Model Evaluation
Model	Silhouette Score
K-Means	0.184
Hierarchical	0.14
DBSCAN	0.016
PCA + K-Means	0.447

K-Means (k=4) selected for business interpretation

PCA + K-Means used for improved mathematical performance

👥 Customer Segments

⭐ Stars (VIPs): High income, high spending

🚀 High Potential: Good income, moderate spending

⚠️ Needs Attention: Low engagement customers

💰 Low Value: Low income, minimal spending

💡 Business Recommendations

Stars: Loyalty programs, premium offers

High Potential: Upselling, personalized marketing

Needs Attention: Discounts, re-engagement campaigns

Low Value: Cost-effective awareness strategies

📊 Business Impact

Improves marketing efficiency

Increases ROI

Enables personalized communication

Supports data-driven decision making

⚠️ Limitations

Based on static historical data

No real-time behavior tracking

Limited digital interaction features

K-Means requires predefined clusters

🔮 Future Scope

Real-time data integration

Advanced clustering models

Predictive analytics (churn, LTV)

CRM and dashboard integration

🖥️ Streamlit Dashboard

The project includes an interactive dashboard with:

EDA visualizations

Cluster analysis

Customer profiling

Business insights
