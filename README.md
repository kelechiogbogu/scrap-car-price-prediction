# Scrap Car Price Prediction

Predicting scrap car prices using **Linear Regression**. This project demonstrates data cleaning, exploration, processing, and model evaluation to build a regression model that estimates car scrap values accurately.

---

## Project Overview

The goal of this project is to predict scrap car prices based on various car attributes. I used **machine learning techniques**, focusing on **Linear Regression**, to train a model that can provide accurate price predictions for scrap cars. The project includes:  

- Data exploration  
- Data cleaning  
- Feature engineering  
- Model building and evaluation  

---

## Understanding the Data

Before building the model, I explored the dataset to understand its structure and quality. This involved:  

- Checking the dataset for missing or duplicate values  
- Understanding the types of features (numerical and categorical)  
- Visualizing data trends and patterns using charts to see relationships between features and car prices  

This step ensures we know the data well before cleaning or modeling.

---

## Data Cleaning

Data cleaning was essential to make the dataset usable for modeling:  

- Removed unnecessary columns that won’t help in prediction  
- Grouped similar values in categorical features to reduce noise  
- Fixed spelling mistakes and inconsistencies in car names  
- Created new simplified features from complex columns  

These steps improve data quality and help the model learn better.

---

## Data Processing

To prepare the data for modeling, I performed the following:  

- **Outlier removal** using the Interquartile Range (IQR) method  
- **Encoding categorical variables** with One-Hot Encoding  
- **Separating independent variables (features) and the dependent variable (price)**  
- **Multicollinearity testing** to identify highly correlated features  
- **Train-test split** to evaluate the model on unseen data  
- **Feature scaling** to make sure all features contribute equally to the model  

---

## Model Training & Evaluation

I trained a **Linear Regression** model on the processed dataset and tested it on unseen data:  

- The model achieved an **R² score of 0.81**, meaning it explains about **81% of the variation in car prices**  
- **Cross-validation** confirmed the model’s reliability, with an average score of **0.80**  
- These results show the model is **stable** and **generalizes well** to new data  

---

## Summary

This Linear Regression model predicts scrap car prices reasonably well. It serves as a strong baseline for this problem. Future improvements could include:  

- Trying more advanced regression models (e.g., Random Forest, Gradient Boosting)  
- Adding new features to better capture car characteristics  
- Hyperparameter tuning to improve model performance  

---

## Technologies Used

- Python  
- Pandas & NumPy for data manipulation  
- Matplotlib & Plotly for visualization  
- Scikit-learn for model building and evaluation  

---

## Author

**Kelechi Ogbogu** 

---

