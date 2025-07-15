 🚗 Car Price Prediction Project

## 📌 Introduction

This project aims to predict the **price of a car** based on various features using machine learning algorithms. Given a car’s specifications like company, model, year, fuel type, kilometers driven, etc., the system can estimate its selling price.

➡️ Try building a web interface using [Streamlit](https://streamlit.io)  
➡️ View full notebook: [MLR Algorithm Notebook](./MLR_algorithm_car_price_prediction.ipynb)

---

## 🎯 Objective

- Build a machine learning model that accurately predicts the price of used cars.
- Compare different regression algorithms to select the best-performing one.
- Preprocess and clean the raw data for model training.
- Perform exploratory data analysis (EDA) to understand feature relationships.

---

## 🗂️ Project Structure

| Notebook/File Name                | Description |
|----------------------------------|-------------|
| [`01data_cleaning.ipynb`](./01data_cleaning.ipynb)           | Data cleaning: handling null values, formatting data |
| [`02eda.ipynb`](./02eda.ipynb)                     | Exploratory Data Analysis: visualizations, feature correlation |
| [`03 model_selection.ipynb`](./03%20model_selection.ipynb)       | Training models and comparing their performance |
| [`MLR_algorithm_car_price_prediction.ipynb`](./MLR_algorithm_car_price_prediction.ipynb) | Multiple Linear Regression prediction and evaluation |
| [`using_Three_diff_algos.ipynb`](./using_Three_diff_algos.ipynb)   | Comparing Linear, Lasso, and Ridge regression |

---

## ⚙️ Features

- Cleaned and preprocessed dataset
- EDA using plots (scatter plot, histogram, heatmap, etc.)
- Implemented regression models:
  - **Linear Regression**
  - **Lasso Regression**
  - **Ridge Regression**
- Model evaluation using **R² Score**
- Prediction and comparison of model accuracy
- (Optional) Can be integrated with Streamlit for a web app

---

## ✅ Benefits

- Helps users estimate car prices based on specifications
- Assists in fair valuation during buying or selling
- Useful for dealerships or marketplaces for pricing analytics
- Highlights which features have the most influence on price

---

## ⚠️ Limitations

- Predictions may not be accurate for rare or vintage models
- Some important factors like **location** or **condition** may be missing
- Limited dataset size might restrict model performance
- May underfit/overfit depending on model and features

---

## 📊 Model Performance Summary

| Algorithm         | R² Score (approx) |
|-------------------|-------------------|
| Linear Regression | ~0.84             |
| Lasso Regression  | ~0.83             |
| Ridge Regression  | ~0.85             |

---

## 🚀 Future Scope

- Use advanced models like **Random Forest**, **XGBoost** for better accuracy
- Feature engineering and selection to improve model robustness
- Create a full-fledged **[Streamlit Web App](https://streamlit.io)** for user input and live prediction
- Continuously update the model with new data

---

## 👤 Author

**Payal Tanaji Chougale**  
