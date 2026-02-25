# Customer-Segmentation-Using-Clustering

**Customer Segmentation using K-Means Clustering**

**Project Overview:**
This project focuses on segmenting mall customers into distinct groups based on purchasing behavior using unsupervised machine learning techniques. The goal is to identify meaningful customer segments that can help businesses optimize marketing strategies and improve revenue targeting.

The segmentation is performed using K-Means clustering with proper preprocessing and cluster validation techniques.

**Dataset**
Dataset: Mall_Customers.csv
Features Used:
Age
Annual Income (k$)
Spending Score (1–100)
These features help analyze customer purchasing power and behavior patterns.

**Technologies Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Project Workflow
1️.Data Preprocessing
Loaded dataset using Pandas
Selected relevant numerical features
Applied feature scaling using StandardScaler
Ensured clustering was not biased due to feature magnitude differences

2️.Optimal Cluster Selection
To determine the optimal number of clusters:
Applied Elbow Method
Calculated Within-Cluster Sum of Squares (WCSS)
Selected optimal K based on curve inflection point

3️.Model Implementation
Implemented K-Means Clustering
Used random initialization with fixed random_state for reproducibility
Assigned cluster labels to each customer
Computed cluster centroids for interpretation

4️.Cluster Visualization
Plotted 2D scatter visualization of:
Annual Income vs Spending Score
Color-coded clusters for easy interpretation
Highlighted cluster centroids

Key Insights

The clustering revealed distinct customer groups such as:

High Income – High Spending (Premium Customers)

High Income – Low Spending (Upselling Opportunity)

Low Income – High Spending (Value-Driven Buyers)

Average Income – Moderate Spending (Regular Customers)

These segments can help businesses:

Design targeted marketing campaigns

Improve loyalty programs

Optimize pricing strategies


How to Run the Project

Clone the repository:

git clone https://github.com/your-username/customer-segmentation.git

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the notebook:

jupyter notebook Customer_Segmentation.ipynb

**Author**

Vinit Khanvilkar
Computer Engineering Student
AI / Machine Learning Enthusiast
