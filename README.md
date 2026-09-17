# Linear Regression on the Diabetes Dataset

A beginner-friendly Jupyter notebook that fits a simple linear regression model on scikit-learn’s diabetes dataset. Body mass index (BMI) is used as the single predictor of quantitative disease progression one year after baseline.

This project was built by following the tutorial playlist:

[Machine Learning Tutorials For Beginners Using Python In Hindi](https://youtube.com/playlist?list=PLu0W_9lII9ai6fAMHp-acBmJONT7Y4BSG&si=SQzEqJZDvTm3yp-q)

## What the notebook covers

- Loading the built-in diabetes dataset from scikit-learn
- Inspecting keys, feature matrix, and dataset description
- Selecting BMI (`feature index 2`) as the sole input feature
- Creating a train/test split
- Fitting `sklearn.linear_model.LinearRegression`
- Generating predictions on the test set
- Computing mean squared error
- Printing model weights (coefficients) and intercept
- Plotting actual vs. predicted values with a regression line

## Dataset

The [diabetes dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html) contains 442 samples and 10 numeric baseline features (age, sex, BMI, blood pressure, and six blood serum measurements). The target is a quantitative measure of disease progression one year later. Features are already mean-centered and scaled.

This notebook uses only BMI for a single-variable demonstration.

## Requirements

- Python 3
- numpy
- matplotlib
- scikit-learn

Install with:

```bash
pip install numpy matplotlib scikit-learn
```

## How to run

1. Open `Linear_Regression_Model.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or Google Colab.
2. Run all cells in order.

## Notes

The training set uses all samples except the last 30 (`[:-30]`), while the test set uses the last 20 samples (`[-20:]`). This follows the tutorial structure and is intended as a learning example rather than a production-grade split.

## License

Use and adapt freely for learning purposes.
