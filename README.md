# Anomaly-Detection-using-Clustering-Algorithms
🚨 Anomaly Detection using Clustering Algorithms This project implements unsupervised anomaly detection techniques using clustering algorithms: K-Means, Hierarchical Clustering, and DBSCAN. These methods identify data points that deviate significantly from cluster patterns
Here’s a GitHub project description tailored specifically for **Anomaly Detection using K-Means, Hierarchical Clustering, and DBSCAN**:

---
### 🧠 Algorithms Used

* **K-Means Clustering**
  Detects anomalies based on distance from cluster centroids. Points far from any centroid are marked as anomalies.

* **Hierarchical Clustering (Agglomerative)**
  Builds a hierarchy of clusters and spots anomalies as distant leaf nodes or small sub-clusters.

* **DBSCAN (Density-Based Spatial Clustering)**
  Detects anomalies as points in low-density regions (noise), without requiring the number of clusters as a parameter.

### 📊 Features

* Preprocessing pipeline for scaling and cleaning
* Visual comparison of clustering results with anomaly labels
* Evaluation using silhouette score, cluster distribution, and anomaly count
* Visualization of clusters and outliers in 2D (PCA / t-SNE)

### 📂 Datasets Used

* healthcare

### 📦 Tech Stack

* Python, NumPy, Pandas
* Scikit-learn for clustering
* Matplotlib, Seaborn for plots
* Plotly for interactive visualization

### ✅ Applications

* Fraud detection in transactions
* Network intrusion identification
* Anomalous behavior in user sessions
* Quality control in manufacturing

---

