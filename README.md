# 🛒 SmartCart Clustering System

## 📌 Overview

SmartCart Clustering System is an **unsupervised machine learning project** developed to segment e-commerce customers based on their purchasing behaviour, engagement, and loyalty-related characteristics.

The project uses customer data to identify groups of customers with similar behavioural patterns. These customer segments can help businesses understand their customers and support more targeted marketing and customer-retention strategies.

---

## 🎯 Problem Statement

SmartCart is a growing e-commerce platform serving customers across multiple countries. The platform contains **2,240 customer records** with information related to demographics, purchasing behaviour, website activity, and customer response.

The use of generic marketing and engagement strategies can result in:

* Inefficient marketing campaigns
* Difficulty identifying high-value customers
* Missed customer-retention opportunities
* Delayed identification of customers with low engagement

To address this problem, an intelligent customer segmentation system is developed using **unsupervised machine learning and clustering techniques**.

---

## 🎯 Objectives

* Analyse customer purchasing behaviour.
* Analyse customer engagement and activity.
* Preprocess and transform the customer dataset.
* Create meaningful features for clustering.
* Apply dimensionality reduction where required.
* Group customers based on similar characteristics.
* Visualize and analyse the resulting customer segments.
* Provide insights that can support personalized marketing and customer-retention strategies.

---

## 📊 Dataset

The dataset contains **2,240 customer records and 22 attributes**.

### Main categories of features

**Demographic Information**

* ID
* Year_Birth
* Education
* Marital_Status
* Income
* Kidhome
* Teenhome
* Dt_Customer

**Purchase Information**

* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds

**Purchase Frequency**

* NumDealsPurchases
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases

**Customer Engagement**

* NumWebVisitsMonth
* Recency
* Complain

---

## ⚙️ Project Workflow

```text
Customer Dataset
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Feature Engineering
       ↓
Categorical Encoding
       ↓
Feature Scaling
       ↓
Dimensionality Reduction
       ↓
Clustering
       ↓
Cluster Visualization
       ↓
Customer Segment Analysis
```

---

## 🧹 Data Preprocessing

The dataset is prepared before applying clustering algorithms.

The preprocessing workflow includes:

* Checking dataset structure
* Checking data types
* Handling missing values
* Checking duplicate records
* Identifying unnecessary features
* Handling categorical variables
* Preparing numerical features
* Scaling features before clustering

---

## 🔧 Feature Engineering

Relevant customer-level features are created to better represent customer behaviour.

Examples include:

* Total purchase amount
* Purchase frequency
* Customer household information
* Customer engagement indicators

Feature engineering helps convert the raw customer information into features that are more useful for segmentation.

---

## 📏 Feature Scaling

Feature scaling is applied before clustering because different features can have significantly different numerical ranges.

Scaling helps ensure that features with larger numerical values do not dominate the clustering process.

---

## 📉 Dimensionality Reduction

**Principal Component Analysis (PCA)** is used to reduce the dimensionality of the dataset when required.

PCA helps:

* Reduce the number of dimensions
* Preserve important patterns in the data
* Make customer data easier to visualize
* Visualize customer clusters in lower-dimensional space

---

## 🤖 Machine Learning

This project focuses on **Unsupervised Machine Learning**.

### Clustering

Clustering algorithms are used to group customers according to similarities in their behaviour.

The project explores clustering techniques such as:

* K-Means Clustering
* DBSCAN

The clustering results are analysed to understand the characteristics of different customer groups.

---

## 📊 Cluster Analysis

After clustering, the resulting customer groups are analysed using their behavioural characteristics.

The analysis can help identify patterns such as:

* Customers with higher purchase activity
* Customers with regular engagement
* Customers with lower purchase activity
* Customers showing lower recent engagement

The exact characteristics of each cluster depend on the final clustering results obtained from the model.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📁 Project Structure

```text
SmartCart-Clustering-System/
│
├── README.md
├── SmartCart_Clustering.ipynb
│
├── dataset/
│   └── customer_data.csv
│
└── images/
    └── cluster_visualization.png
```

> Update the filenames above according to the actual files you upload to GitHub.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd SmartCart-Clustering-System
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

---

## 📈 Results

The project generates customer clusters based on similarities in customer behaviour.

The results can be visualized using:

* Cluster plots
* PCA visualizations
* Customer feature distributions
* Cluster-wise comparisons

Add your **actual graphs and model results** here after completing the final analysis.

Example:

```text
Number of clusters: [ADD YOUR VALUE]

Clustering evaluation:
- Silhouette Score: [ADD YOUR VALUE]

PCA visualization:
- [Add PCA/cluster plot here]
```

---

## 💡 Business Use

Customer segmentation can help an e-commerce business:

* Understand different types of customers
* Create more targeted marketing campaigns
* Identify valuable customer segments
* Improve customer engagement
* Support customer-retention strategies
* Make data-driven marketing decisions

---

## 🚀 Future Scope

Possible improvements include:

* Real-time customer segmentation
* Customer churn prediction
* Personalized product recommendations
* Automated marketing campaigns
* Interactive customer-segmentation dashboard
* Integration with live e-commerce data

---

## 👨‍💻 Author

**Ritik Ranjan Mohanta**

B.Tech CSE (AI/ML)
Batch: 2024–28

### Areas of Interest

* Artificial Intelligence
* Machine Learning
* Data Science
* Python
* Customer Analytics

---

## 📌 Project Type

**Internship Project | Unsupervised Machine Learning | Customer Segmentation**
