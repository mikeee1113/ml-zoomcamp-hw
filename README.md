# ML Zoomcamp 2026 — Homework

My solutions to the homework of [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp) (2026 cohort).

| Module | Homework | Solution |
|---|---|---|
| 02 — Machine Learning for Regression | [task](https://github.com/DataTalksClub/machine-learning-zoomcamp/blob/main/cohorts/2026/homework/02-regression/homework.md) | [homework_2.ipynb](02-regression/homework_2.ipynb) |

## Homework 2: Machine Learning for Regression

Linear regression implemented from scratch in NumPy to predict `fuel_efficiency_mpg` on the 2026 Car Fuel Efficiency dataset.

| # | Question | Answer |
|---|---|---|
| 1 | Column with missing values | `horsepower` |
| 2 | Median of `horsepower` | 254 |
| 3 | Better way to fill NAs | With mean (RMSE 2.202 vs 2.205) |
| 4 | Best regularization `r` | 0 (RMSE 2.2053) |
| 5 | Std of RMSE across seeds 0–9 | 0.029 |
| 6 | RMSE on test (seed 9, `r=0.001`) | 2.236 |

## Running

```bash
pip install numpy pandas matplotlib jupyter
jupyter notebook 02-regression/homework_2.ipynb
```

The notebook downloads the dataset directly from the course repository.
