# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment customers of a retail store based on their **purchase history**.  
By analyzing **Annual Income** and **Spending Score**, we identify distinct customer groups to help businesses with **targeted marketing strategies**.

---

## 📂 Dataset
- **Source:** Mall Customer Dataset  
- **Features:**
  - `CustomerID` → Unique ID for each customer (dropped during preprocessing)  
  - `Gender` → Male/Female (encoded numerically)  
  - `Age` → Age of customer  
  - `Annual Income (k$)` → Annual income in thousand dollars  
  - `Spending Score (1-100)` → Score assigned by the store  

---

## ⚙️ Steps Involved
1. **Data Preprocessing**
   - Dropped `CustomerID` (not useful for clustering)  
   - Encoded `Gender` using `LabelEncoder`  
   - Scaled features using `StandardScaler`  

2. **Finding Optimal Clusters**
   - Used **Elbow Method** (Inertia)  
   - Used **Silhouette Score** for cluster validation  

3. **Model Training**
   - Applied **K-Means** with the best `k`  
   - Assigned cluster labels to each customer  

4. **Visualization**
   - Plotted customer groups based on **Annual Income vs Spending Score**  
   - Clear distinction between customer segments  

---

## 📊 Results
- Optimal number of clusters (**best_k**) selected using **Silhouette Score**  
- Segmented customers into meaningful groups (e.g., high-income high-spending, low-income low-spending, etc.)  
- Visual representation of customer segments helps in **business decision making**  

---

