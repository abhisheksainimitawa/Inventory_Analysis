# Inventory Analysis Project

## Overview
This project focuses on analyzing and optimizing inventory, purchase, and sales data. The main analysis is conducted in the `solution.ipynb` notebook, which includes various sections such as data preprocessing, demand forecasting, ABC analysis, EOQ calculation, reorder point analysis, lead time analysis, stock aging analysis, and inventory optimization.

## Files
- `solution.ipynb`: Contains the main analysis and optimization code for inventory, purchase, and sales data.

## How to Run the Notebook Locally

1. **Install Python**  
   Ensure you have Python 3.8+ installed. You can download it from [python.org](https://www.python.org/downloads/).

2. **Install Required Libraries**  
   Open a terminal and run the following command:
   ```
   pip install pandas numpy matplotlib seaborn prophet jupyter
   ```

3. **Download the Data Files**  
   Place the necessary CSV files in the same folder as the notebook:
   - 2017PurchasePricesDec.csv
   - BegInvFINAL12312016.csv
   - EndInvFINAL12312016.csv
   - InvoicePurchases12312016.csv
   - PurchasesFINAL12312016.csv
   - SalesFINAL12312016.csv

4. **Open the Notebook**  
   In the terminal, navigate to the project folder and run:
   ```
   jupyter notebook
   ```
   Then open `solution.ipynb` in your browser.

5. **Run All Cells**  
   In Jupyter, click "Cell" > "Run All" to execute the notebook.

6. **View Results**  
   The plots and analysis will appear below each code cell.

## Key Insights
- The analysis identifies top-selling products and forecasts future demand.
- ABC analysis categorizes products based on sales revenue, helping prioritize inventory management.
- EOQ and ROP calculations optimize order quantities and timing.
- Lead time analysis highlights vendors and products with long lead times, indicating areas for improvement.
- Stock aging analysis reveals slow-moving inventory, guiding decisions on markdowns or liquidation.

This project aims to enhance inventory management practices through data-driven insights and optimizations.