# 📈 Salary Prediction using Linear Regression

This project demonstrates a simple **Linear Regression** model built with Python and scikit-learn to predict salaries based on years of experience. It's a foundational machine learning project perfect for beginners.

---

## 📁 Dataset

The dataset used contains two columns:
- `YearsExperience`: Total years of work experience
- `Salary`: Corresponding salary in INR/USD

> Example rows:
> ```
> YearsExperience,Salary
> 1.1,39343.00
> 1.3,46205.00
> ```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## 🚀 Project Workflow

1. Loaded dataset using `pandas`
2. Checked dataset shape and null values
3. Visualized data using a **scatter plot**
4. Split the dataset into **training and testing sets**
5. Trained a **Linear Regression** model using `LinearRegression()`
6. Predicted salaries using the trained model
7. Plotted the prediction line on top of original data
8. Predicted salary for new experience input

---

## 📉 Visualization

The scatter plot below shows actual data points and the regression line (best fit line) learned by the model:

![Prediction Line](salary_prediction_plot.png)

---

## 🔮 Sample Prediction

```python
# Predicting salary for 5.5 years of experience
lr.predict([[5.5]])
