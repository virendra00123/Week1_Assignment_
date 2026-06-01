# 📘 Week 1 — ML Foundations Assignment

Complete solutions for Week 1 of the ML Foundations course.

## Topics Covered

| Part | Topic | Key Concepts |
|------|-------|-------------|
| 1 | Python Fundamentals | Control flow, data structures, exceptions, lambdas |
| 2 | NumPy | Array creation, indexing/slicing, dot products, broadcasting |
| 3 | Pandas | Series vs DataFrame, iloc/loc, groupby, missing data |
| 4 | Linear Algebra | Vectors, matrix ops, eigenvalues/eigenvectors, SVD/PCA |
| 5 | Statistics | Descriptive stats, hypothesis testing, error metrics, PSI |
| 6 | Probability Theory | Bayes' theorem, distributions, CLT |

## Setup

```bash
pip install numpy pandas matplotlib scipy statsmodels
```

Then open the notebook:
```bash
jupyter notebook week1_solutions.ipynb
```

## Running

Use **Kernel → Restart & Run All** to execute all cells from top to bottom.  
All `assert` blocks should pass ✓ and all plots should render.

## Key Takeaways

- **NumPy** vectorized ops replace Python loops for numerical computation
- **Pandas** `groupby` + `agg` is the go-to pattern for grouped summaries
- **SVD** decomposes a matrix into directions of maximum variance — same as PCA
- **Bayes' theorem** updates beliefs with evidence: posterior ∝ likelihood × prior
- **CLT** guarantees sample means are ~normal regardless of population shape
- **PSI > 0.2** signals major distribution shift and model retraining is needed
