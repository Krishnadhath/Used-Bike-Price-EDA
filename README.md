# 🏍️ Used Bike Price Prediction

This project focuses on analyzing a dataset of used bikes and predicting their selling prices using machine learning techniques. It involves data cleaning, exploratory data analysis (EDA), feature engineering, and model building.

---

## 🎯 Objective

To analyze used bike listings to understand key factors influencing the price and to predict the selling price using a machine learning regression model.

---

## 📊 Dataset

The dataset includes details about used bikes such as:
- **Name** of the bike
- **Price**
- **Kms Driven**
- **Owner** type
- **Year** of purchase
- **Power**
- **MileagE**

> Source: Provided as part of a learning project. *(You can update this if there's a public source.)*

---

## 🔧 Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-Learn (Random Forest, etc.)
- Jupyter Notebook / VS Code

---

## 📈 Key Steps

1. **Data Cleaning**
   - Removed duplicates, nulls, and unnecessary columns.
   - Converted year to bike age (feature engineering).

2. **Exploratory Data Analysis**
   - Visualized data using bar plots, scatter plots, and correlation heatmaps.
   - Identified how features like brand, bike age, and kms driven affect price.

3. **Model Building**
   - Used **Random Forest Regressor** to predict prices.
   - Evaluated performance using R² score and Mean Absolute Error.

4. **Price Prediction**
   - Built a simple interface to input bike details and predict price.

---


## 📊 Sample Prediction

```python
Input:
  Bike Age: 5 years
  Brand: Royal Enfield
  Owner Type: First
  Kms Driven: 30,000
  Fuel Type: Petrol
  Transmission: Manual

Predicted Price: ₹52,000
