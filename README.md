# Customer Segmentation Using K-Means Clustering

## 📌 Problem Statement
Businesses need to target different customers based on their behavior and preferences. This project aims to use unsupervised learning to cluster customers into distinct groups for better marketing strategies.

## 🎯 Objective
Cluster customers into groups using K-Means Clustering based on the following features:
- Age
- Income
- Spending Score
- Shopping Frequency

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- mpl_toolkits (for 3D visualization)

## 📊 Data Preprocessing
- Dropped non-essential columns such as `CustomerID`, `Gender`, etc.
- Added a synthetic `Frequency` column to simulate shopping frequency.
- Renamed and converted income to dollar units.
- Scaled features using `StandardScaler`.

## 🔍 Clustering Approach
- Used K-Means clustering.
- Determined the optimal number of clusters using the **Elbow Method**.
- Final model used `k=4`.

## 📈 Visualization
- 2D Scatter Plot: Income vs. Spending colored by cluster.
![image](https://github.com/LAXMAN7795/Customer-Segmentation-Using-K-Means/blob/b791cc9af662f8c24ae4a53558ddeaa76c2774a1/output/customer_segmentation.png)
- 3D Scatter Plot: Age, Income, and Spending with cluster coloring.
![image](https://github.com/LAXMAN7795/Customer-Segmentation-Using-K-Means/blob/c27764ca7f5b3493795644b7ba042d3639675449/output/3d_customer_segmentation.png)

## 📌 Key Findings / Conclusion
Four distinct customer segments were identified:
1. **High income, high spenders** – Ideal for premium promotions.
2. **Low income, high spenders** – Possibly value-seeking or brand-loyal.
3. **Young moderate spenders** – Can be targeted for upselling.
4. **Low income, low spenders** – Less responsive, but might convert with discounts.

These insights can help businesses craft tailored marketing campaigns.

## ✅ How to Run
1. Upload `Mall Customers.csv` in the same directory.
2. Run the Jupyter notebook.
3. Visualizations and cluster outputs will be generated.
