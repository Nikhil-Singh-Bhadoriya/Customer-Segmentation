# 🧩 Customer Segmentation Using Clustering Techniques

A machine learning project focused on segmenting customers using unsupervised clustering techniques to uncover meaningful groups based on behavior and demographics.

---

## 📌 Project Overview

This project implements a full unsupervised learning workflow: collecting customer transaction and demographic data; exploratory analysis to understand patterns; feature engineering; applying clustering algorithms to segment customers; and interpreting cluster profiles for actionable business insights.

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔄 Workflow Summary

### 1. Data Collection

Dataset comprises customer attributes such as age, gender, spending score, annual income, number of purchases, preferred product categories, and other behavioural metrics.

### 2. Exploratory Data Analysis (EDA)

* Visualisations of customer demographics and spending distributions
* Scatter plots & pair-plots of income vs spending score, purchase frequency vs income
* Correlation and descriptive statistics for behavioural features
* Identification of outliers, skewness, and segmentation potential

### 3. Feature Engineering

* Encoding categorical variables (gender, preferred category)
* Creating derived features like average purchase value, frequency per month, recency score
* Scaling/normalising numerical features for clustering compatibility
* Dimensionality reduction (e.g., PCA) if needed for high-dimensional data

### 4. Clustering Modeling

Techniques applied:

* **K-Means Clustering** (primary)
* **Hierarchical Clustering** or **DBSCAN** (optional exploration)
* Choosing optimal number of clusters via Elbow method, Silhouette score

### 5. Evaluation & Interpretation

* Silhouette score and Davies–Bouldin index to assess clustering quality
* Cluster profiling: reviewing cluster centers, size, and behaviour
* Visualising clusters (e.g., 2D PCA plot) and interpreting segments for business use

**Result:** Identified distinct customer segments such as “high income/high spend”, “low income/low spend”, “frequent but low-value purchases”, enabling targeted marketing strategies.

### 6. Insights & Business Application

* Mapped segments to business action: e.g., premium customers targeted with loyalty offers, low-activity segment engaged with retention campaigns
* Provided actionable recommendations: personalised marketing, tiered loyalty programs, upsell/cross-sell opportunities

---

## 📁 Project Structure

```
Customer-Segmentation-Clustering/
│── data/
│── notebooks/
│── src/
│── README.md
│── requirements.txt
```

---

## 📈 Key Findings

* Income and spending score emerged as the most discriminative features for segmentation
* Clusters captured clear behavioural differences enabling marketing strategy alignment
* Feature scaling and selection crucial for meaningful cluster separation
* Segmentation based on clustering offers low-cost strategic insight for business outreach

---

## 🚀 Future Improvements

* Incorporate temporal customer behaviour (recency/frequency/monetary) for advanced segmentation (RFM modelling)
* Use deeper unsupervised techniques such as Gaussian Mixture Models or Self-Organising Maps for non-linear segment discovery
* Deploy interactive dashboards to explore segments and KPIs dynamically
* Integrate external data (social media sentiment, churn history) to refine segment profiles
* Continuously update segment assignments with incoming real-time customer data

---

