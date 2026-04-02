# 📊 Customer Segmentation using RFM Analysis & K-Means Clustering

## 🎯 Objective

The objective of this project is to segment customers based on their purchasing behavior in order to help businesses design targeted marketing strategies and improve customer retention.

---

## 📂 Dataset

* Dataset: Online Retail Dataset
* Contains transaction-level data including customer purchases, dates, quantity, and price.

---

## 🧠 Approach & Methodology

### 1. Data Cleaning

* Removed missing values
* Filtered out negative or invalid quantities
* Converted date columns into proper datetime format

### 2. Feature Engineering

* Created a new column: **TotalPrice = Quantity × UnitPrice**

### 3. RFM Analysis

* **Recency (R):** Days since last purchase
* **Frequency (F):** Number of purchases
* **Monetary (M):** Total spending

👉 This helps understand customer value and engagement.

### 4. Data Scaling

* Used StandardScaler to normalize RFM values
* Ensures all features contribute equally

### 5. Clustering (K-Means)

* Applied K-Means clustering to group customers
* Used Elbow Method to find optimal number of clusters

### 6. Segment Labeling

Customers were categorized into:

* High Value
* Loyal
* At Risk
* Low Value

---

## 📊 Key Insights

* High-value customers contribute the majority of revenue
* At-risk customers have not purchased recently and may churn
* Loyal customers purchase frequently but may not spend the most
* Low-value customers show low engagement

---

## 💡 Business Recommendations

* Provide rewards and exclusive offers to high-value customers
* Run re-engagement campaigns for at-risk customers
* Maintain loyalty programs for frequent buyers
* Convert low-value customers through targeted marketing

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn (K-Means, StandardScaler)
* Matplotlib / Seaborn

---

## 🚀 Conclusion

Customer segmentation enables businesses to treat customers differently based on behavior, leading to better marketing efficiency, improved customer retention, and increased revenue.

---

## 🎯 Key Learning

* Understanding customer behavior using data
* Applying unsupervised learning (clustering)
* Translating data insights into business strategies
