#  House Price Prediction using Linear Regression

## 📌 Overview

This project predicts house prices based on features such as area, number of bedrooms, bathrooms, and amenities using a **Linear Regression model**.
It demonstrates a complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

---

## 🔗 Project Links

- 📁 Project Folder: [https://github.com/...](https://github.com/nikitagaikwad0111/OIBSIP/tree/main/House-Price-Prediction)
- 📓 Notebook: https://github.com/...
- 📊 Dataset: [https://github.com/...](https://github.com/nikitagaikwad0111/OIBSIP/blob/main/House-Price-Prediction/Housing.csv)

---

🎯 Objective
Predict house prices using regression models
Identify key factors affecting house prices
Evaluate model performance

---

##  Project Structure

```
House-Price-Prediction/
│
├── house_price_prediction.ipynb
├── Housing.csv
└── README.md
```

---

##  Dataset

* The dataset contains **545 observations** and multiple features describing house properties.
* Key features include:

  * Area, Bedrooms, Bathrooms, Stories
  * Parking, Air Conditioning, Furnishing Status
* Target variable: **Price**

📎 Dataset used in this project:  
👉 [Download Dataset](./Housing.csv)

---

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

---

## 🧹 Data Preprocessing

* No missing values found
* Converted categorical variables (`yes/no`) into numerical format
* Applied one-hot encoding for furnishing status
* Prepared data for model training

---

##  Exploratory Data Analysis

* Performed correlation analysis using heatmap

### Key Findings:

* Strong positive correlation: **area, bathrooms, air conditioning**
* Moderate influence: **stories, parking**
* Negative relationship: **unfurnished houses tend to have lower prices**

---

##  Model Building

* Algorithm: **Linear Regression**
* Train-Test Split: **80% training, 20% testing**
* Model trained to learn relationships between features and price

---

##  Model Evaluation

| Metric   | Value         |
| -------- | ------------- |
| R² Score | ~0.65         |
| RMSE     | ~1.32 Million |

### Interpretation:

* Model explains **~65% variance** in house prices
* Prediction error is moderate

---

##  Visualizations

* Correlation Heatmap
* Actual vs Predicted Plot
* Residual Distribution

---

##  Key Insights

* Area and bathrooms significantly impact house prices
* Air conditioning and preferred area increase value
* Unfurnished houses tend to have lower prices

---

##  Sample Prediction

The model was tested on sample data to compare predicted and actual values, demonstrating its real-world applicability.

---

## ⚠️ Limitations

* Assumes linear relationships
* Possible missing features
* Outliers may affect accuracy
* Moderate performance (R² ≈ 0.65)

---

## 🚀 Future Improvements

* Apply Ridge / Lasso Regression
* Use advanced models (Random Forest, XGBoost)
* Feature engineering
* Outlier handling and scaling

---

##  Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🔗 Project Links

- 📓 Notebook: [View Notebook](./house_price_prediction.ipynb)  
- 📊 Dataset: [Download Dataset](./Housing.csv)

---

## 📌 Conclusion

This project demonstrates how Linear Regression can be applied to predict house prices effectively. While the model captures key relationships, further improvements using advanced models and feature engineering can enhance prediction accuracy.

---

## 👩‍💻 Author

**Nikita Gaikwad**

* [GitHub](https://github.com/nikitagaikwad0111)
* [LinkedIn](http://linkedin.com/in/nikita-gaikwad-3b449a221)
