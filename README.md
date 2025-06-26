# AI-ML-Task-3

## By Abhishek Mitra

# 📊 Linear Regression with Scikit-learn

## 🎯 Objective

Implement and understand **Simple** and **Multiple Linear Regression** using Scikit-learn.  
This project demonstrates:

- Importing and preprocessing data
- Splitting data into training and testing sets
- Fitting a linear regression model
- Evaluating the model using MAE, MSE, and R² metrics
- Plotting the regression line
- Interpreting model coefficients

---

## 🛠️ Tools Used

- Python 🐍
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

---

## 🧩 Project Steps

### 1. Import and Preprocess the Dataset

- Load the dataset using Pandas
- Drop missing values or handle them appropriately
- Select features and target variable

  ![image](https://github.com/user-attachments/assets/11f0770e-1f35-45a7-804e-9b09d1ed948d)


### 2. Split Data into Train-Test Sets

- Use `train_test_split()` from `sklearn.model_selection`
- Typical test size: 20% (can vary)

  ![image](https://github.com/user-attachments/assets/3cf68dab-106c-44ba-a311-faeb90c31244)


### 3. Fit a Linear Regression Model

- Use `LinearRegression()` from `sklearn.linear_model`
- Fit the model on the training data using `.fit()`

  ![image](https://github.com/user-attachments/assets/62180044-da1b-4c3d-acdf-3fb9428c0aee)


### 4. Evaluate the Model

- Predict using `.predict()`
- Evaluate using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared Score (R²)
 
    ![image](https://github.com/user-attachments/assets/fd826c61-b1c8-4189-8104-c77652532e09)


### 5. Plot Regression Line & Interpret Coefficients

- For simple linear regression (1 feature), plot:
  - Feature vs Target (scatter)
  - Regression Line

    ![image](https://github.com/user-attachments/assets/7b9f4497-6392-460e-a9c2-d19f628edfee)

- Print model intercept and coefficients

  ![image](https://github.com/user-attachments/assets/5726a990-812f-473a-adb6-07012e25ad3d)


---
