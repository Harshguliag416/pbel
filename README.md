# AutoAI Model: House Price Prediction

This project demonstrates the use of IBM Watson Studio's AutoAI to predict house prices based on various features.

---


---

## 🧠 Project Description

The goal of this project is to use IBM Watson Studio AutoAI to build a regression model that predicts housing prices using various categorical and numerical input features. The dataset was preprocessed and fed into AutoAI, which automatically generated multiple pipelines and selected the best one based on RMSE.

---

## ⚙️ Implementation Details

- Platform: IBM Watson Studio (AutoAI)
- Dataset: Housing.csv
- Model Type: Ridge Regression (Pipeline 8)
- API deployed using IBM Watson Machine Learning
- Best RMSE: ~1117271.79 (Cross Validation)

---

## 🧩 Challenges & Solutions

- **Challenge:** AutoAI model deployment was not clearly visible initially.
- **Solution:** Promoted model to deployment space, created REST endpoint, and tested predictions using payload.

---

## 📁 Files Included

- `AutoAI_Model.ipynb`: Code to load model, send prediction request
- `Housing.csv`: Dataset used
- `README.md`: Documentation
