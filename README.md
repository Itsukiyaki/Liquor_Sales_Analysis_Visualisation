# Iowa Liquor Sales Analysis

This project analyzes liquor sales data in Iowa for January 2022. The analysis includes data cleaning, visualization, and statistical testing to derive insights for retailers.

## Project Structure

- **`notebook.ipynb`**: Contains the data analysis and visualization code.
- **`iowa_sales_jan_2022.csv`**: Raw dataset for January 2022.
- **`iowa_sales_jan_2022_filtered.csv`**: Dataset after dropping unnecessary columns.
- **`iowa_sales_jan_2022_cleaned.csv`**: Cleaned dataset with missing values handled.
- **`average_price_per_volume.csv`**: Summary of average price per bottle volume for American Vodkas.

## Latar Belakang
Retailer di Iowa berupaya meningkatkan kinerja penjualan mereka. Namun, keterbatasan data yang tersedia khususnya, catatan penjualan dari Januari 2022 menimbulkan tantangan dalam memahami perilaku konsumen dan tren secara menyeluruh. Kendala ini menghambat pengembangan manajemen inventaris, strategi pemasaran, dan prediksi penjualan yang efektif. Untuk mengatasi masalah ini, analisis terperinci terhadap data penjualan Januari 2022 diperlukan untuk mendapatkan wawasan yang dapat ditindaklanjuti yang dapat menginformasikan keputusan strategis yang bertujuan untuk meningkatkan penjualan dan profitabilitas.

## SMART
- Specific: Meningkatkan penjualan produk minuman dengan kinerja terbaik.
- Measurable: Melacak penjualan produk yang ditargetkan.
- Achievable: Memanfaatkan data penjualan untuk mengidentifikasi tren dan preferensi konsumen.
- Relevant: Fokus pada peningkatan penjualan di area yang kinerjanya baik untuk memaksimalkan profitabilitas.
- Time-Bound: Menetapkan periode review untuk bulan berikutnya setelah penerapan metode untuk mengevaluasi efektivitas strategi.

## Identifikasi Masalah

- Brand minuman apa yang menempati penjualan teratas pada bulan Januari 2022?
- Apa saja produk minuman terlaris pada bulan Januari 2022?
- Kapan penjualan minuman mencapai puncaknya selama bulan Januari 2022, dan bagaimana retailer dapat menyesuaikan promosi yang sesuai?
- Di mana lokasi penjualan tertinggi dan terendah?
- Mengapa kategori minuman tertentu lebih laku daripada yang lain?
- Bagaimana retailer dapat menggunakan data penjualan untuk mengoptimalkan strategi penetapan harga dan memaksimalkan pendapatan?

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
