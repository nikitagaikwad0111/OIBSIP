# Customer Segmentation Analysis
![GitHub](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Overview
This project performs customer segmentation for an e-commerce dataset using K-Means clustering. The goal is to group customers based on their behavior to enable targeted marketing strategies.

---

## 🎯 Objective
To identify distinct customer segments based on:
- Income
- Spending behavior
- Recency (customer activity)
- Purchase frequency

---

## 📊 Dataset
The dataset contains customer-related information such as:
- Income
- Total Spending (MntTotal)
- Recency (days since last purchase)
- Number of Web Purchases
  
The dataset is included in this repository for easy access.

---

## ⚙️ Methodology
The project follows these steps:

1. Data Exploration and Cleaning  
2. Feature Selection  
3. Feature Scaling using StandardScaler  
4. Elbow Method to determine optimal clusters  
5. K-Means Clustering  
6. Visualization and Interpretation  

---

## 📈 Key Visualizations
- Income vs Spending (Customer Value)
- Spending vs Recency (Customer Activity)
- Cluster Distribution
- Boxplots for cluster comparison

---

## 📊 Results

The K-Means clustering algorithm successfully segmented customers into 4 distinct groups based on income, spending, recency, and purchase frequency.

These clusters represent different customer behaviors and provide valuable insights for targeted marketing strategies.

---

## 💡 Key Insights
- High-income and high-spending customers form the most valuable segment.
- Some high-value customers are inactive and require re-engagement.
- Low-spending but active customers can be targeted with promotions.
- Customer segmentation helps in improving marketing efficiency and business strategy.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📂 Project Structure

```
Customer_Segmentation/
│
├── customer_segmentation.ipynb
├── ifood_df.csv
└── README.md
```
---

## ▶️ How to Run

1. Clone or download this repository
2. Ensure the dataset file `ifood_df.csv` is in the same folder as the notebook
3. Open the notebook in Jupyter Notebook or VS Code
4. Install required libraries if not already installed:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
5. Run all cells sequentially
6. View visualizations and insights

---

## 🔮 Future Improvements

- Include more features such as customer demographics
- Apply advanced clustering techniques like Hierarchical Clustering
- Build a dashboard for real-time analysis

---

## 🚀 Conclusion
This project demonstrates how clustering techniques can be used to understand customer behavior and support data-driven decision-making in business.

---

## 🔗 Project Link

[GitHub Repository](https://github.com/nikitagaikwad0111/OIBSIP)

---

## 👩‍💻 Author

Nikita Gaikwad  
Oasis Infobyte Internship (OIBSIP)

---

## 🌐 Connect with Me

[LinkedIn Profile](http://linkedin.com/in/nikita-gaikwad-3b449a221)
