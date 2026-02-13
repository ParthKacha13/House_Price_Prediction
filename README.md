# 🏠 House Price Prediction

A machine learning project that predicts house prices using structured housing data and regression techniques.

---

## 📌 Problem Statement

The objective of this project is to build a predictive model that estimates house prices based on various property features such as:

- Area type  
- Availability  
- Location  
- Size (BHK configuration)  
- Total square footage  
- Number of bathrooms  
- Number of balconies  

The target variable is **price**, and the goal is to generate accurate predictions for unseen test data.

---

## 📂 Dataset Description

The dataset is provided by Kaggle and includes:

### Files

- **train.csv** – Contains features along with the target variable (price)
- **test.csv** – Contains features where the target variable is hidden
- **sample_submission.csv** – Sample format for final submission

---

## 🧾 Column Details

- **id** – Unique identifier  
- **area_type** – Type of area classification  
- **availability** – Availability status of the house  
- **location** – Location of the property  
- **size** – Number of bedrooms, halls, and kitchens  
- **total_sqft** – Total area in square feet  
- **bath** – Number of bathrooms  
- **balcony** – Number of balconies  
- **price** – Target variable (house price)

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 Project Workflow

1. Data Cleaning & Preprocessing  
   - Handling missing values  
   - Converting categorical variables  
   - Feature formatting  

2. Feature Engineering  
   - Extracting BHK from size  
   - Processing total_sqft values  
   - Encoding categorical variables  

3. Model Building  
   - Linear Regression  
   - Random Forest Regressor  

4. Model Evaluation  
   - Performance metrics  
   - Cross-validation  

5. Submission Generation  
   - Predicting test data  
   - Creating Kaggle submission file  

---

## 🎯 Conclusion

This project demonstrates the application of regression techniques and feature engineering in solving real-world pricing problems. It highlights the importance of data preprocessing and model tuning in improving predictive accuracy.

---

⭐ Feel free to explore the notebook and experiment with different regression models to improve performance.
