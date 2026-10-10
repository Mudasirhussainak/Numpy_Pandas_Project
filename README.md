# Online Retail Performance Review

This project is a realistic, business-style analysis of UK online retail transactions using the UCI Online Retail dataset. The notebook focuses on the kinds of questions a commercial or operations team would review in a monthly performance meeting:

- revenue quality and monthly trend
- cancellation and return risk
- top international markets
- repeat-customer contribution

The analysis uses only NumPy and pandas and reads the bundled gzip CSV directly from the `data/` folder, so it runs without extra setup beyond installing the project requirements.

## Run the project

1. Create and activate a Python environment.
2. Install dependencies: `python -m pip install -r requirements.txt`
3. Open `online_retail_insights.ipynb` and run the cells from top to bottom.

## Data source

Chen, D. (2015). Online Retail. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33

## Notes

This project is intentionally simple and readable. It is designed to behave like a real-world internal business review rather than a heavy notebook demo.
