# 🏠 Task 1 — House Price Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Task-1%20of%204-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Domain-Artificial%20Intelligence-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>
</p>

---

## 🏢 Internship Details

| Field | Details |
|-------|---------|
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Intern Name** | Khushi Kumari |
| **Intern ID** | CITS2079 |
| **Domain** | Artificial Intelligence |
| **Mentor** | Neela Santhosh Kumar |
| **Duration** | 4 Weeks |

---

## 📌 Objective

Build a **Machine Learning regression model** to predict house prices in Indian cities based on features like area, bedrooms, location, age, and garage availability.

---

## 📁 Files in This Task

| File | Description |
|------|-------------|
| `house_price_prediction.ipynb` | Main Jupyter Notebook with complete code |
| `house_prices.csv` | Dataset — 100 house records across Indian cities |
| `README.md` | This documentation file |

---

## 📊 Dataset Overview

- **Rows:** 100 houses  
- **Cities:** Mumbai, Delhi, Bangalore, Chennai, Hyderabad, Pune, Kolkata  
- **Features:**

| Column | Description |
|--------|-------------|
| `Area_sqft` | Area of the house in square feet |
| `Bedrooms` | Number of bedrooms |
| `Bathrooms` | Number of bathrooms |
| `Floors` | Number of floors |
| `City` | City (Indian metro) |
| `Age_years` | Age of the house in years |
| `Garage` | Garage availability (0/1) |
| `Price_INR` | 🎯 Target — House price in ₹ |

---

## 🤖 Models Used

| Model | Description |
|-------|-------------|
| **Linear Regression** | Baseline regression model |
| **Random Forest Regressor** | Ensemble-based model for higher accuracy |

---

## 📈 Results

| Metric | Linear Regression | Random Forest |
|--------|:-----------------:|:-------------:|
| R² Score | ~0.94 | ~0.98 |
| MAE | Lower | Lowest |
| RMSE | Moderate | Low |

✅ **Random Forest** gives better predictions due to its ability to capture non-linear patterns.

---

## 📷 Output Visualizations

> Screenshots of plots are included below (run the notebook to regenerate):

- **Price Distribution** — Histogram of house prices
- **Average Price by City** — Bar chart comparing cities
- **Correlation Heatmap** — Feature correlation matrix
- **Area vs Price Scatter** — Relationship between area and price
- **Actual vs Predicted** — Model evaluation scatter plots
- **Feature Importance** — Which features matter most

---

## ▶️ How to Run

```bash
# 1. Clone the repo
git clone https://github.com/khushis1n/<repo-name>.git

# 2. Navigate to Task 1 folder
cd Task-1-House-Price-Prediction

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 4. Launch Jupyter
jupyter notebook house_price_prediction.ipynb
```

---

## 🛠️ Libraries & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

---

<p align="center">Made with ❤️ during CODTECH AI Internship</p>
