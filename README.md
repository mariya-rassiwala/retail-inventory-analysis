# Retail Inventory Analysis

## Project Overview
This project analyzes retail inventory data to understand revenue trends, product performance, stockouts, and lost sales. The goal is to identify useful business insights that can support better inventory management and replenishment decisions.

## Objectives
- Analyze monthly revenue trends.
- Compare revenue across product categories.
- Identify top-performing products by revenue.
- Examine stockout rates across categories.
- Identify categories and products associated with lost sales.
- Inspect data quality, including missing values and duplicates.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Jupyter Notebook

## Dataset
The dataset contains **3,600 records and 23 columns**, covering 150 distinct products across 24 monthly periods.

It includes product details, categories, suppliers, warehouses, costs, selling prices, inventory quantities, revenue, lead times, and stockout-related information.

Files:
- `items_and_stock.csv` — inventory dataset
- `Retail_Inventory_Analysis.ipynb` — analysis notebook

## Key Findings

- **Highest-revenue category:** Fluid power, generating approximately 6.14 million in revenue across the observed periods.
- **Highest lost-sales category:** Fasteners, with 4,939 lost-sales units.
- **Revenue trend:** Monthly revenue fluctuated during the 24-month period. May 2025 recorded the highest monthly revenue, while June 2025 recorded the lowest.
- **Data quality:** No exact duplicate rows were found. Missing values were identified in actual lead time and weeks of cover.
- **Inventory planning:** Stockout patterns and lost-sales volumes highlight areas that could benefit from further investigation into demand forecasting and replenishment.

## Visualizations
The notebook includes interactive and static visualizations for:
- Monthly revenue trends
- Revenue by product category
- Top 10 products by revenue
- Stockout rate by category
- Lost-sales units by category

## How to Run the Project

1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib plotly jupyter
   ```

3. Open `Retail_Inventory_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook cells in order.

Keep `items_and_stock.csv` in the same directory as the notebook.

## Limitations
The dataset is used for a learning and portfolio project. The findings describe the supplied data and should not be treated as verified results from a real company's operations.

## Conclusion
This project demonstrates practical data analysis skills, including data quality checks, exploratory analysis, business-focused aggregation, and visualization. It shows how inventory data can be used to investigate revenue performance and potential stockout-related losses.
