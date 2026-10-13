# Boston Housing — Statistical Analysis

An educational Jupyter Notebook exploring the Boston Housing dataset through visualization, hypothesis testing and linear regression. Completed as a peer-graded statistics assignment.

## What the notebook covers

- Exploratory plots with Matplotlib and Seaborn.
- A two-sample t-test comparing home values by proximity to the Charles River.
- One-way ANOVA across housing age groups.
- Pearson correlation between industrial land use and nitric oxide concentration.
- Ordinary least squares regression relating home values to distance from employment centres.

## Run locally

```bash
python -m venv .venv
# Activate the environment for your operating system.
python -m pip install jupyter pandas matplotlib seaborn scipy statsmodels
jupyter notebook
```

Open `Optional--Peer-Graded-Assignment-jupyterlite-v2.ipynb` and run the cells in order. The notebook downloads its CSV from the IBM Skills Network course dataset URL, so an internet connection is required.

## Scope

This is a learning exercise using a historical dataset, not a current housing valuation tool. Results should be read in that context.
