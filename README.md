# 🛒 SmartCart – Customer Segmentation System

An Unsupervised Machine Learning project that segments e-commerce customers based on their demographics, purchasing behaviour, and engagement patterns.

## 📌 Problem Statement

SmartCart is an e-commerce platform serving customers across multiple countries. It has a dataset containing **2,240 customer records and 22 attributes**.

Using the same marketing strategy for every customer can lead to inefficient campaigns, missed opportunities to retain high-value customers, and delayed identification of customers who may disengage.

This project applies customer segmentation techniques to identify distinct customer groups and support more targeted marketing strategies.

## 🎯 Project Objectives

- Identify customer behaviour patterns.
- Segment customers based on purchasing habits and engagement.
- Understand differences between customer groups.
- Support personalised marketing and customer retention strategies.

## 📂 Dataset Overview

The dataset contains 2,240 customer records and 22 attributes, covering:

- **Demographics:** Age, education, marital status, income, and family information.
- **Purchase Behaviour:** Spending across different product categories.
- **Purchase Frequency:** Web, catalog, and store purchases.
- **Customer Engagement:** Website visits, recency, and complaints.

Dataset file: `smartcart_customers.csv`

## 🛠️ Technologies & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Machine Learning Workflow

The project follows these steps:

1. Data Loading and Exploration
2. Missing Value Treatment using Median Imputation
3. Feature Engineering
   - Age
   - Customer Tenure
   - Total Spending
   - Total Children
4. Outlier Treatment
5. Categorical Encoding using One-Hot Encoding
6. Feature Scaling using StandardScaler
7. Dimensionality Reduction using PCA
8. Optimal Cluster Analysis using Elbow Method and Silhouette Score
9. Customer Segmentation using:
   - K-Means Clustering
   - Agglomerative Clustering
10. Cluster Visualization and Analysis

## 📊 Results

The project explores customer segmentation using K-Means and Agglomerative Clustering.

The final customer segmentation analysis uses **Agglomerative Clustering with 4 clusters**, helping identify different customer behaviour patterns.

## 📁 Repository Structure

```text
SmartCart-Customer-Segmentation/
│
├── smartcart.ipynb
├── smartcart_customers.csv
└── README.md
```

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/Aryan-sharma-10/SmartCart-Customer-Segmentation.git
```

2. Navigate to the project directory:

```bash
cd SmartCart-Customer-Segmentation
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `smartcart.ipynb` and run the notebook cells.

## 🎓 Learning Experience

This project provided practical experience in Unsupervised Machine Learning, customer segmentation, feature engineering, dimensionality reduction, and clustering techniques.

---

**Project:** SmartCart – Customer Segmentation System  
**Domain:** Machine Learning | Unsupervised Learning
