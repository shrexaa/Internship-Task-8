# Internship-Task-8
# 🧠 Task 8: Clustering with K-Means (AI & ML Internship)
## 📌 Objective

The goal of this task is to perform **unsupervised learning** using the **K-Means Clustering** algorithm to group customers based on features such as Annual Income and Spending Score. This allows us to understand customer segments and target them accordingly.

---

## 📁 Dataset Used

**Mall Customer Segmentation Dataset**

- Source: [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Format: CSV
- Features used:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Steps Performed

1. **Imported the Dataset**
   - Loaded the customer data using Pandas.

2. **Preprocessed the Data**
   - Selected relevant numerical features.
   - Removed unnecessary columns like CustomerID and Gender.

3. **Visualized the Data**
   - Optional: Applied **PCA** for 2D visualization.
   - Plotted scatter plots to observe feature distribution.

4. **Used the Elbow Method**
   - Ran KMeans with clusters `k = 1 to 10`.
   - Plotted the Within-Cluster Sum of Squares (WCSS).
   - Chose the optimal `k` using the "elbow point".

5. **Applied K-Means Clustering**
   - Initialized and fit the model with the chosen `k` (e.g., 5).
   - Assigned cluster labels to the dataset.

6. **Visualized the Clusters**
   - Used Seaborn to plot clusters with different colors.

7. **Evaluated the Model**
   - Calculated **Silhouette Score** to evaluate cluster quality.

---

## ⚠️ Warning Fix

If you see the following warning on Windows:UserWarning: KMeans is known to have a memory leak on Windows with MKL...


