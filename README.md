# Elevate-Labs-Task-8

# 🛍️ Mall Customer Segmentation with K-Means Clustering

## 🎯 Objective
Perform unsupervised learning using **K-Means Clustering** to group mall customers based on their income and spending behavior.

## 📊 Dataset
- **Source**: [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Columns Used**:
  - Annual Income (k$)
  - Spending Score (1-100)

## ✅ Steps Performed

1. **Data Loading & Preprocessing**
   - Loaded `Mall_Customers.csv`
   - Selected relevant features
   - Scaled features using `StandardScaler`

2. **Elbow Method**
   - Calculated Within-Cluster Sum of Squares (WCSS)
   - Identified optimal number of clusters (K ≈ 5)

3. **Model Training**
   - Fitted KMeans with the optimal K
   - Assigned cluster labels to customers

4. **Visualization**
   - Plotted clusters based on Annual Income and Spending Score
   - Used PCA to visualize high-dimensional data in 2D

5. **Evaluation**
   - Used **Silhouette Score** to evaluate clustering performance

## 🧠 Results
- **Optimal K**: 5
- **Silhouette Score**: ~0.55 (good separation between clusters)
- Clusters revealed distinct groups of customers with different spending/income behavior

## 📦 Tools Used
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
