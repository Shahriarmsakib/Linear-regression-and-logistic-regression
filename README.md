# Linear and Logistic Regression from Scratch

![NumPy](https://img.shields.io/badge/NumPy%20%7C%20pandas-from%20scratch-013243)
![Type](https://img.shields.io/badge/graduate%20coursework-UC%20Riverside-lightgrey)

This project implements linear regression (closed-form and gradient descent) and binary logistic regression (gradient descent) without library model fitting. Each implementation is checked against scikit-learn on real datasets.

## Parts

**Linear regression: Boston housing ([UCI](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/))**

- Exploratory analysis with pandas and Matplotlib, e.g. price vs. average number of rooms.
- Single-feature model derived and fit by hand, then extended to multiple features.
- Closed-form least squares compared with gradient descent.

**Logistic regression: Breast Cancer Wisconsin ([UCI](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/))**

- Data visualization by class.
- Logistic loss and its gradient implemented directly; trained with gradient descent.
- Test accuracy compared with `sklearn.linear_model.LogisticRegression`.

## Files

| File | Content |
|---|---|
| `linear regression and logistic regression.ipynb` | Implementation and experiments (data are downloaded from UCI) |
| `linear regression and logistic regression_report.pdf` | Write-up |

## Run

```bash
pip install numpy pandas matplotlib scikit-learn
jupyter notebook "linear regression and logistic regression.ipynb"
```
