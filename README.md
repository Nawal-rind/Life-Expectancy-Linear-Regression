# Life-Expectancy-Linear-Regression
# Linear Regression Project

## Overview

This project implements **Linear Regression** using **Python** and **scikit-learn** to predict a target variable from one or more features. The project includes:

* Training a Linear Regression model
* Evaluating model performance using metrics like **R², MSE, MAE, RMSE**
* Making predictions on new data
* Visualizing results with **matplotlib**

---

## Dataset

The project works with a CSV dataset. The dataset should include:

* Feature columns (inputs)
* A target column (the value to predict)

> Note: You can replace the CSV with your own dataset as long as the format is consistent.

---

## Features

* Automatically splits the dataset into **training and testing sets**
* Trains a **Linear Regression model** using scikit-learn
* Calculates and displays performance metrics:

  * **Slope / Coefficients**
  * **Intercept**
  * **Mean Squared Error (MSE)**
  * **Root Mean Squared Error (RMSE)**
  * **R² Score**
  * **Mean Absolute Error (MAE)**
* Makes predictions on **new unseen data**
* Plots **actual vs predicted values** to visualize model performance

---

## How to Use

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Upload your CSV dataset
3. Update the target column name in the code if needed
4. Run all cells to train the model, see metrics, and view plots
5. Modify `X_new` to predict new data points

---

## Visualization

* **Single feature:** plots a regression line with actual points
* **Multiple features:** plots predicted vs actual scatter with a reference line

---

## Requirements

* Python 3.x
* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`

> Install packages using:

```bash
pip install pandas numpy scikit-learn matplotlib
```

---

## Conclusion

This project demonstrates how to use **Linear Regression** for prediction and evaluation, with a **fully reproducible workflow**. The notebook is ready to use with any tabular dataset for predictive analysis.
