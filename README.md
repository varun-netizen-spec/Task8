# 📊 K-Means Clustering - Mall Customer Segmentation

This project demonstrates **unsupervised learning using K-Means clustering** to group mall customers based on their **age, income, and spending score**. The goal is to identify distinct customer segments for business insights using **Scikit-learn**, **Pandas**, and **Matplotlib**.

---

## 🚀 Objective
Perform **K-Means clustering** on the Mall Customer dataset and evaluate the clustering performance using **Elbow Method**, **PCA visualization**, and **Silhouette Score**.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- PCA (for dimensionality reduction)

---

Features:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 📌 Task Breakdown

### Step 1: Load & Preprocess Data
- Selected features: Age, Income, Spending Score
- Standardized using `StandardScaler`

### Step 2: Elbow Method
- Used to find the optimal number of clusters (K)
- Visualized inertia vs number of clusters

### Step 3: K-Means Clustering
- Applied with K=5 based on Elbow Method
- Cluster labels assigned to each customer

### Step 4: PCA for Visualization
- PCA reduced data to 2D for cluster visualization
- Scatter plot with color-coded clusters

### Step 5: Evaluation
- Evaluated clustering quality using **Silhouette Score**
- Generated **summary statistics** for each cluster

---

## 📷 Visuals

### 📈 Elbow Plot
Helps identify the optimal number of clusters using the point of inflection.

### 🎨 Cluster Visualization (PCA)
Displays clusters in 2D space with color-coded labels using `Seaborn`.

---

## 📏 Evaluation Metric
- **Silhouette Score**: Indicates how well each point fits within its cluster (range: -1 to 1).




