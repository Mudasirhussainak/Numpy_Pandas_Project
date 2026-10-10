# Online Retail Revenue and Retention Analysis

An approachable exploratory data analysis project using real transaction data from the UCI Online Retail dataset. The notebook examines monthly completed sales, cancellation signals, international markets, and repeat-customer behavior using NumPy and pandas.

## Business question

What can historical transaction data reveal about revenue patterns, cancelled orders, and customer retention?

## Run the project

1. Create and activate a Python environment.
2. Install the dependencies with `python -m pip install -r requirements.txt`.
3. Open `online_retail_insights.ipynb` in VS Code or Jupyter and run the cells from top to bottom.

The compressed CSV dataset is included in `data/`, so the notebook runs without downloading data or installing an Excel reader.

## Data source

Chen, D. (2015). **Online Retail**. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33

The dataset contains invoice-line transactions for a UK-based online retailer. The notebook keeps cancellation lines separate from completed sales, retains sales rows with missing customer IDs for revenue totals, and limits customer-retention metrics to identified customers.

## Analysis highlights

- Summarizes monthly completed revenue and typical line-item revenue with NumPy percentiles.
- Estimates cancellation invoice rate and cancelled value from cancellation lines.
- Ranks international markets by completed revenue.
- Compares revenue from one-time and repeat customers, with repeat defined as at least two distinct completed invoices.

## Resume summary

> Analyzed real-world online retail transactions with Python, pandas, and NumPy to quantify monthly revenue trends, cancellation signals, international sales, and repeat-customer contribution.

This is descriptive analysis: the observed patterns do not establish causes, and the cancellation metrics are transaction-level estimates.