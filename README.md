# Sales Performance Insights

A small exploratory sales analysis notebook that summarizes performance by region, tracks annual net sales, and compares sales across product categories.

## Project files

- `sales_performance_insights.ipynb` — analysis notebook with three visualizations and printed takeaways.
- `sales.csv` — input dataset (3,200 records).
- `requirements.txt` — Python dependencies for running the notebook.

## Run the notebook

1. Create and activate a Python environment.
2. Install the dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Launch Jupyter from this directory and open `sales_performance_insights.ipynb`:

   ```bash
   jupyter notebook
   ```

The notebook reads `sales.csv` from the same directory. Run its cell to generate:

- Total net sales by region
- Annual net sales trend
- Share of net sales by category

## Dataset fields

The CSV includes date and calendar fields, geography, product and category, sales channel and customer segment, units, pricing and discount, gross and net sales, cost, returns, marketing spend, profit, campaign, and promotion status.

## Notes

The notebook expects `date` and `net_sales` in the dataset, with `region` and `category` for its groupings. It uses pandas for data preparation and Matplotlib for charts.
