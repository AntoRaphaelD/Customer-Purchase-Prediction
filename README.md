# Customer Behavior Analysis Dashboard

This project analyzes customer shopping behavior and provides an interactive dashboard (Power BI) along with supporting analysis in a notebook.

## Contents

- `customer_shopping_behavior.csv` – Raw dataset used for the analysis.
- `Customer analytics.ipynb` – Jupyter notebook containing data exploration/cleaning and insights.
- `customer_behavior_basic business questions.sql` – SQL queries used to answer key business questions.
- `Customer_behavior_dashboard.pbix` – Power BI dashboard file.
- `dashboard_snapshot.png` – Screenshot of the dashboard.

## Project Overview

The workflow is:

1. Load and clean `customer_shopping_behavior.csv`.
2. Explore customer behavior patterns and compute metrics (see `Customer analytics.ipynb`).
3. Use SQL queries to answer targeted business questions (see `customer_behavior_basic business questions.sql`).
4. Visualize results in the Power BI report (`Customer_behavior_dashboard.pbix`).

## How to Run/Use

### Power BI

1. Open `Customer_behavior_dashboard.pbix` in Power BI Desktop.
2. Ensure the dataset path/data source settings match your environment.
3. Refresh data (if prompted) to update visuals.

### Jupyter Notebook

1. Open `Customer analytics.ipynb` in Jupyter/VSCode.
2. Ensure the notebook can access `customer_shopping_behavior.csv` (same directory by default).
3. Run the cells to reproduce the analysis.

## Notes

- If you add or rename the CSV file, update references inside the notebook and/or Power BI data model.
- The provided SQL file is intended as a supporting layer for the business-question outputs.

## License

Add your preferred license here (e.g., MIT) if applicable.

