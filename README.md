# transfer-performance-project
This is the code repository for "Transfer Performance Evaluation Using Bayesian Methods."

The code can be run as follows.

All univariate results are entirely contained within `univariate_normal/univariate_normal_linear.ipynb`.

Similarly, all multivariate results are contained within running `multivariate_normal/multivariate_normal_linear.ipynb`.

The code is all in Python, and requires the following packages to run:
- `numpy`
- `matplotlib` (specifically, the `pyplot` module)
- `random`
- `math`
- `pandas`
- `sklearn`
- `itertools`
- `scipy` (specifically, the `stats` module)
- `time`
- `statsmodels` (specifically, the `api` module)
- `cvxopt`
- `datetime` (specifically the `datetime` module)

Since the random seed is fixed, so long as everything is ran once, results should be replicated. The end of `univariate_normal/univariate_normal_linear.ipynb` also contains the "easter egg" of an unfinished Poisson example that proved uninsightful.