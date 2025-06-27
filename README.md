# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict house prices using machine learning models based on features like area, number of bedrooms, and location. It demonstrates a complete data science workflow including data preprocessing, exploratory data analysis (EDA), model building, and performance evaluation.

---

## ❓ What business problem does this solve?
Real estate professionals and potential buyers often need a way to estimate house prices based on various factors. Accurate predictions help:
- Buyers know if a house is fairly priced
- Sellers set competitive prices
- Investors evaluate property value in different areas

---

## 📊 What data is used?
- Format: CSV file
- Key Features:
  - `area`: Size of the property (in sq ft)
  - `bedrooms`: Number of bedrooms
  - `bathrooms`: Number of bathrooms
  - `location`: City or neighborhood (categorical)
  - `price`: Target variable (house price in USD)

📁 *[Dataset source]*: Kaggle

---

## 🔍 What questions does this project answer?
### 1. What are the most important factors affecting house prices?
- **Answer**: `area` and `location` were found to be the most influential features based on model feature importance scores.

### 2. Are larger houses always more expensive?
- **Answer**: Generally yes, but price also depends heavily on location. Some small homes in high-demand neighborhoods are more expensive than larger ones in low-demand areas.

### 3. Which model predicts house prices most accurately?
- **Answer**: **Random Forest Regressor** performed best, achieving an R² score of approximately **0.91**.

### 4. How well do traditional models like Linear Regression perform?
- **Answer**: Linear Regression underfit the data with lower accuracy (R² ≈ 0.74), suggesting that the relationship between features and price is non-linear.

---

## 🧪 Techniques Used
- **EDA**: Correlation heatmaps, distribution plots, scatter plots
- **Preprocessing**: Handling categorical variables (e.g., one-hot encoding), scaling
- **Models**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- **Evaluation Metrics**:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## 📈 Key Findings
- Houses with more area and located in premium areas tend to be priced significantly higher.
- Random Forest captured non-linear patterns better than other models.
- Model performance can still improve with more advanced preprocessing and feature engineering.

---

## 🛠 Tools & Libraries
- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for EDA)
- Scikit-learn (for ML models and evaluation)

---

## 🔄 Next Steps
- Use **cross-validation** for more robust model evaluation
- Perform **hyperparameter tuning** using GridSearchCV
- Add more location-based features (e.g., distance to city center, amenities)
- Build a simple web app using **Streamlit** or **Flask** to make predictions

---

## 📂 Folder Structure
