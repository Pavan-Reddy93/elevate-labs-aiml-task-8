# 🧩 Task 8: Clustering with K-Means

## Objective  
Perform **unsupervised learning** using K-Means clustering on the **Mall Customers dataset**.



##  Dataset  
- **Mall_Customers.csv**  
- Features include:
  - CustomerID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  



##  Steps Followed  
1. **Loaded dataset** and explored structure.  
2. **Selected features** (`Annual Income`, `Spending Score`) for clustering.  
3. Applied the **Elbow Method** to find the optimal number of clusters.  
4. Fitted **K-Means clustering** with the chosen K.  
5. **Visualized clusters** with scatter plots and centroids.  
6. Calculated the **Silhouette Score** for cluster quality.  
7. Optionally used **PCA** for dimensionality reduction and visualization with all features.  


##  Results  
- **Optimal clusters (K)** ≈ `5`  
- **Silhouette Score** ≈ `0.55` (indicating moderately well-formed clusters).  
- Clusters observed:  
  - High income, high spenders  
  - High income, low spenders  
  - Average income, average spenders  
  - Low income, high spenders  
  - Low income, low spenders  

## Author
Pavan Reddy Kasara B.Tech – Artificial Intelligence & Machine Learning Presidency University, Bengaluru
