# Data Science – Assignment 3 

---

## File Structure

```
ds-assignment-3/
├── A-03_Problem1.ipynb                # Problem 1 – Inferential Statistics (PakWheels)
├── A-03_Problem2.ipynb                # Problem 2 – Spurious Correlations
├── Global Economy Indicators.csv      # Dataset for Problem 2
└── README.md
```

---

## Assignment Overview

### Problem 1 – PakWheels Used Car Dataset
Inferential statistics analysis on a real-world automobile dataset from Kaggle.

| Part | Topic |
|------|-------|
| a | Data cleaning, descriptive statistics & EDA |
| b | One-sample inference (z-test / t-test) |
| c | Two-sample comparison |
| d | Multiple-group comparison (ANOVA / Kruskal-Wallis) |
| e | Effect of significance level |
| f | Correlations & heatmap |
| g | Bootstrapping |

### Problem 2 – Spurious Correlations
Exploration of misleading correlations using real and reference datasets.

| Part | Topic |
|------|-------|
| a | Identifying a spurious correlation from tylervigen.com |
| b | Learnings on spurious correlations in real datasets |
| c | Creating a new spurious correlation (r ≥ 0.8) from Kaggle |
| d | 95% confidence interval & p-value |
| e | Bootstrapping for correlation coefficient CI |

---

## Datasets

- **Problem 1:** PakWheels Used Car Dataset — download from [Kaggle](https://www.kaggle.com/datasets/muhammadwaqargul/pakwheels-used-car-dataset-october2022) and place as `pakwheels.csv` in the root folder.
- **Problem 2:** Global Economy Indicators — included in the repository.

---

## Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` / `seaborn` – Visualization
- `scipy` – Hypothesis testing, correlation, bootstrapping

---

## How to Run

1. Clone the repository:
```bash
   git clone https://github.com/KainatZahraa/ds-assignment-3.git
   cd ds-assignment-3
```

2. Install dependencies:
```bash
   pip install pandas numpy matplotlib seaborn scipy
```

3. Download the PakWheels dataset from Kaggle and place it in the repo folder as `pakwheels.csv`.

4. Launch Jupyter Notebook:
```bash
   jupyter notebook A-03_Problem1.ipynb
   jupyter notebook A-03_Problem2.ipynb
```
