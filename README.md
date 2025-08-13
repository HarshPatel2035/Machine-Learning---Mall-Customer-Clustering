# 🛍 Mall Customer Segmentation (Clustering) – Machine Learning Project

## 📌 Overview
This project performs **customer segmentation** for a mall using clustering techniques.  
The goal is to divide customers into distinct groups based on their purchasing behavior, enabling businesses to design targeted marketing strategies.

## 🎯 Objective
- Analyze customer demographic and spending data.
- Apply clustering algorithms to segment customers.
- Visualize and interpret the clusters for actionable business insights.

## 📊 Dataset
The dataset contains the following features:
- **CustomerID** – Unique ID assigned to each customer.
- **Gender** – Male/Female.
- **Age** – Age of the customer.
- **Annual Income (k$)** – Customer’s yearly income in thousands of dollars.
- **Spending Score (1–100)** – Score assigned by the mall based on customer spending patterns.

> Dataset was cleaned and prepared for clustering by removing unnecessary columns and scaling features where needed.

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - pandas, numpy – Data manipulation
  - matplotlib, seaborn – Data visualization
  - scikit-learn – Preprocessing, clustering (K-Means)
  - scipy – Hierarchical clustering
  - Jupyter Notebook – Development environment

## 📈 Workflow
1. **Data Collection** – Loaded dataset of mall customers.
2. **Exploratory Data Analysis (EDA)** – Checked distributions, correlations, and outliers.
3. **Feature Selection** – Selected relevant features for clustering.
4. **Clustering Techniques**:
   - **K-Means Clustering** – Determined optimal clusters using Elbow Method.
   - **Hierarchical Clustering** – Compared results.
5. **Visualization** – Used scatter plots to represent clusters.
6. **Insights** – Interpreted customer groups for business strategies.

## 📂 Project Structure

├── Mall Customer Segmentation Analysis - Clustering.ipynb # Main notebook
├── README.md # Project documentation
├── Mall_customers.csv/ # Dataset 
