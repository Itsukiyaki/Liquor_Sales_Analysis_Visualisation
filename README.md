# Iowa Liquor Sales Analysis

This project analyzes liquor sales data in Iowa for January 2022. The analysis includes data cleaning, visualization, and statistical testing to derive insights for retailers.

## Project Structure

- **`notebook.ipynb`**: Contains the data analysis and visualization code.
- **`iowa_sales_jan_2022.csv`**: Raw dataset for January 2022.
- **`iowa_sales_jan_2022_filtered.csv`**: Dataset after dropping unnecessary columns.
- **`iowa_sales_jan_2022_cleaned.csv`**: Cleaned dataset with missing values handled.
- **`average_price_per_volume.csv`**: Summary of average price per bottle volume for American Vodkas.

## Key Insights

1. **Peak Sales Day**: 
   - Date: January 19, 2022
   - Bottles Sold: 113,926
   - Retailers can consider promotions or discounts around Wednesdays to leverage high sales volumes.

2. **Top and Bottom Stores**:
   - Highest Sales: Hy-Vee #3 / BDI / Des Moines (55,847 bottles sold)
   - Lowest Sales: Big 10 Mart #12 / Dubuque (1 bottle sold)

3. **Category Impact**:
   - Kruskal-Wallis H-test indicates that beverage categories significantly affect sales (p-value < 0.05).

4. **Daily Sales Trend**:
   - Retailers can implement premium pricing during high-demand days, such as weekends.

## How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scipy
2. Open notebook.ipynb in Jupyter Notebook or JupyterLab.

3. Run the cells sequentially to reproduce the analysis.

## Data Cleaning Steps
- Dropped unnecessary columns such as **`invoice_and_item_number`**, **`store_number`**, etc.
- Replaced missing values with 0.
- Saved the cleaned dataset as **`iowa_sales_jan_2022_cleaned.csv`**.

## Visualizations
- Daily sales trends plotted using seaborn.
- Average price per bottle volume for American Vodkas.

## Statistical Tests
- Kruskal-Wallis H-test to evaluate the impact of beverage categories on sales.

## License
This project is for educational purposes only.
