# 🏨 Restaurant Sales Analysis & Predictive Modeling (99.9% Accuracy)

This project demonstrates a complete Data Science pipeline using a restaurant orders dataset. It includes data cleaning, advanced visualization, customer segmentation, and a high-accuracy sales prediction model.

## 📊 Key Highlights
- **Exploratory Data Analysis (EDA):** Uncovered peak business hours (Dinner/Lunch) and weekly revenue trends.
- **Outlier Removal:** Used the IQR method to ensure data quality and model stability.
- **Customer Segmentation:** Implemented K-Means Clustering to identify High-Value (VIP) customers.
- **Predictive Modeling:** Achieved an **R2 Score of 0.9998** using Random Forest Regressor.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Seaborn, Matplotlib, Joblib
- **Model:** Random Forest Regressor

## 📂 Project Structure
1. **Cleaning:** Handled nulls in special requests and removed outliers.
2. **Encoding:** Converted categorical data (Time, Day) into numeric format.
3. **Scaling:** Normalized numerical features to a 0-1 range.
4. **Modeling:** Trained and saved the model as a `.pkl` file for deployment.

## 🚀 How to Use the Predictor
The project includes a saved model and scaler. You can load these files and use the `predict_sales_vip()` function to forecast revenue for any order quantity and price.
