 Project Workflow
1. Data Preprocessing
Read CSV files into DataFrames.

Transform wide-format data into long-format using pd.melt().

Rename columns and convert data types.

Check for and handle missing values and duplicates.

2. Data Integration
Merge imports, retail prices, and production into a single DataFrame final_file.

Fill missing values with 0.

Summary statistics and country/year coverage check.

3. Exploratory Data Analysis
Total imports, retail prices, and production by country.

Identify top contributors and countries with missing or zero values.

Summary statistics for each column.

📈 Visualizations
📉 Global Trends Over Time
Dual-axis line plot showing global imports, production, and retail prices over the years.

 Top 10 Importing Countries
Bar chart of top 10 countries by total imports.

 Heatmap
Heatmap of retail prices per country over time.

⚖ Imports vs Production
Scatter plot visualizing the relationship between imports and production globally.

 Brazil vs World
Line chart comparing Brazil’s coffee production to the rest of the world over time.

 Country Comparisons
Scatter plot comparing:

Brazil vs Venezuela

(Optional) Brazil vs Vietnam (can be added similarly)

 Key Insights
Top Importer: Identifies the country with the highest total imports.

Top Producer: Highlights the leading country in coffee production.

Top Retail Price: Shows which country has the highest average retail price.

Zero Contribution: Lists countries with zero values in each metric.

 Future Enhancements
Add interactive visualizations (e.g., using Plotly or Dash).

Time-series forecasting (e.g., ARIMA) for production trends.

Add country-level clustering based on coffee metrics.

 How to Use
Open the notebook in Google Colab.

Upload the three required CSV files using the file upload cell.

Run the notebook cells in order to clean, analyze, and visualize the data.

