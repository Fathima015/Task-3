# Task 3: Linear Regression – Housing Price Prediction
## Dataset

- Source: [Kaggle - Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Format: CSV
- Target Variable: `price`

---

## Preprocessing Steps

1. Load and inspect the dataset
2. Handle missing values (if any)
3. Label Encode binary categorical columns:
   - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`
4. One-Hot Encode the `furnishingstatus` column
5. Split the dataset into training and testing sets (80-20 split)

---

## Model Used

- Linear Regression from `sklearn.linear_model`

---

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R² Score)

---

## Visualizations

- Scatter plot with regression line (for simple regression using 'area')

---
