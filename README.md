# 🧠 Hierarchical Clustering – Mall Customers Segmentation

## 📖 Project Overview
This project demonstrates the implementation of the **Hierarchical Clustering** algorithm using Python and Scikit-Learn.

The goal is to segment customers of a mall into different groups based on their purchasing behavior:

- Annual Income (k$)  
- Spending Score (1-100)  

The dataset used is **Mall_Customers.csv**.

---

## ⚙️ Machine Learning Workflow
The project follows a standard ML pipeline:

1. Importing the libraries  
2. Importing the dataset  
3. Selecting features for clustering (Annual Income and Spending Score)  
4. Using the **Dendrogram** to find the optimal number of clusters  
5. Training the **Hierarchical Clustering** model on the dataset  
6. Predicting clusters for each customer  
7. Visualizing the clusters

---

## 🤖 Algorithm Used
**Hierarchical Clustering (Agglomerative)**

**Why Hierarchical Clustering?**

- Shows a **hierarchical structure** of clusters  
- No need to pre-specify number of clusters (can use dendrogram)  
- Good for **small to medium datasets**  
- Easy to interpret visually  
- Widely used for customer segmentation  

---

## 📊 Model Evaluation
Since Hierarchical Clustering is **unsupervised**, the evaluation focuses on:

- **Dendrogram** to choose the optimal number of clusters  
- **Visualization of clusters** to interpret customer groups  

---

## 📁 Dataset Features

| Feature       | Description |
|---------------|-------------|
| CustomerID    | Unique ID for each customer |
| Genre         | Gender of the customer (Male/Female) |
| Age           | Age of the customer |
| Annual Income | Income in thousands of dollars |
| Spending Score| Score assigned by mall based on spending habits (1-100) |

---

## 🚀 Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib
- Scipy
- Scikit-Learn
