# 🏠 Housing Price Prediction

This project focuses on building a machine learning model to predict housing prices based on various property features. It covers the full pipeline from data exploration to model evaluation.

---

## 📚 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Scikit-learn**

---

## 📂 Project Overview
- **Dataset**: Housing dataset containing **545 entries** and **13 features**.
- **Target Variable**: `price`
- **Features**:
  - **Numerical**: Area, Bedrooms, Bathrooms, Stories, Parking
  - **Categorical**: Mainroad Access, Guestroom, Basement, Hot Water Heating, Air Conditioning, Preferred Area, Furnishing Status

---

## 🔍 Exploratory Data Analysis
- Analyzed feature distributions and identified key relationships.
- Used **correlation heatmaps** to explore how features interact.
- Visualized data using **histograms**, **boxplots**, and **pie charts**.
- Found that **Area**, **Number of Bathrooms**, and **Stories** strongly impact the **Price**.

---

## 🛠️ Data Preprocessing
- Encoded **categorical variables** into numeric format.
- Applied **Min-Max Scaling** to normalize feature ranges.
- Ensured the dataset was clean, consistent, and suitable for modeling.

---

## 🤖 Model Building
- Selected **Linear Regression** as the baseline model.
- Split the dataset into **training** and **testing** sets.
- Trained the model to predict housing prices based on available features.

---

## 📈 Model Evaluation
- Assessed model performance using appropriate metrics.
- Visualized **Actual vs Predicted** prices to evaluate model fit.
- Identified strong initial performance, noting potential overfitting to be addressed.

---

## 🚀 Future Improvements
- Address potential overfitting by applying **regularization techniques** (e.g., Ridge, Lasso).
- Explore more advanced models like **Random Forest** or **Gradient Boosting**.
- Perform **feature engineering** to create new, more informative variables.
- Apply **hyperparameter tuning** for improved performance.

---

## 📌 Conclusion
This project successfully demonstrates how to approach a real-world regression problem, covering all essential stages from **data analysis** to **model evaluation**, and lays the foundation for further improvements and more advanced modeling techniques.

---
