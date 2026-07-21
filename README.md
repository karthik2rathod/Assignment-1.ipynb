# AI-ML Assignment 1

## Medical Insurance Cost Prediction using Multiple Linear Regression

---

## Objective

The objective of this project is to build a Multiple Linear Regression model that predicts medical insurance charges using customer demographic and health-related information.

---

## Dataset

Medical Cost Personal Insurance Dataset

Kaggle Link:

https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Methodology

1. Load the dataset using Pandas.
2. Explore the dataset and identify numerical and categorical features.
3. Check for missing values.
4. Encode categorical variables using LabelEncoder.
5. Split the dataset into 80% training and 20% testing sets.
6. Train a Multiple Linear Regression model.
7. Predict insurance charges for the test dataset.
8. Evaluate the model using MAE, MSE, and R² Score.
9. Visualize Actual vs Predicted values using a scatter plot.

---

## Results

The model achieved the following performance:

- Mean Absolute Error (MAE): **4186.51**
- Mean Squared Error (MSE): **33635210.43**
- R² Score: **0.7833**

The model predicts insurance charges with good accuracy. Smoking status, BMI, and age were found to be the most influential features.

---

## Conclusion

The Multiple Linear Regression model successfully predicts medical insurance charges using demographic and health-related features. The model explains approximately 78% of the variation in insurance charges. Although the model performs well, Linear Regression assumes a linear relationship between the features and target variable, which may not capture complex real-world patterns.

---

## Repository Structure

```
AI-ML-Assignment-1/
│── Assignment-1.ipynb
│── README.md
```
