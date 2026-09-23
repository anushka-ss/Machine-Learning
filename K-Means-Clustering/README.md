# 🎯 DAY 23 — K-MEANS CLUSTERING

## Unsupervised Machine Learning — Customer Segmentation

Day 23 focuses on **K-Means Clustering**, an important **Unsupervised Machine Learning** algorithm.

K-Means Clustering groups similar data points into different clusters based on their features.

---

# 📌 Topics Covered

- K-Means Clustering
- Unsupervised Learning
- Cluster Formation
- `KMeans`
- `n_clusters`
- `random_state`
- Cluster Prediction
- Inertia
- Elbow Method
- PCA
- Data Visualization
- K-Means Pipeline

---

# 🤖 1. K-Means Clustering

K-Means is an **unsupervised Machine Learning algorithm** used to divide data into a predefined number of clusters.

The algorithm assigns each data point to the cluster whose centroid is closest to it.

### Basic Implementation

```python
from sklearn.cluster import KMeans

model = KMeans(
    n_clusters=3,
    random_state=42
)

model.fit(df)