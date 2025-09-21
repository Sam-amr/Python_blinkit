# Blinkit Data Analysis Using Python 

##  Overview 
This project analyzes sales, outlet performance, and customer behavior using the Blinkit dataset.
The dataset contains 8,523 rows and 12 features, covering product details (item type, fat content, weight), outlet details (size, type, location, establishment year), and performance metrics (sales, ratings).

The analysis focuses on:

1) Data Cleaning (fixing inconsistent values, handling missing data).

2) Business KPI Calculation (total sales, avg. sales, ratings, etc.).

3) Visualization of sales trends across product categories, outlets, and years.

4) Insights & Recommendations for business growth.

## Objectives
1. Clean and preprocess Blinkit dataset for consistency.

2. Calculate Key Performance Indicators (KPIs) like total sales, average sales, no. of items sold, and average ratings.

3. Visualize sales distribution across:

   Item fat content,

   Item types,

   Outlet locations,

   Outlet establishment years,

   Outlet sizes and types.

4. Derive business insights to support decision-making.

5. Provide a foundation for building Power BI dashboards and predictive ML models in the future.

## Tool Used
Jupyter Notebook

## DataSet Source 
Kaggle 

## Libraries Used

1. pandas: Used for data cleaning, transformation, and analysis. It organizes raw data into structured DataFrames like Excel tables.

2. numpy: Provides fast mathematical operations on arrays and matrices, making calculations efficient.

3. matplotlib.pyplot: Used for creating basic visualizations like line, bar, pie, and scatter plots with full customization.

4. seaborn: Built on matplotlib, it creates beautiful, statistical charts (heatmaps, distributions, regression plots) with minimal code.

## Features Of The Project 
1. Data Cleaning – Fixed inconsistent entries (low fat, LF → Low Fat, reg → Regular).
2. Business KPIs – Calculated sales and ratings statistics.
3. Visualizations – Interactive plots (bar, pie, line, grouped charts).
4. Insights Extraction – Identified patterns across outlets and products.
5. Scalable Setup – Can be extended to Power BI dashboards & ML predictions

## All Results Explained 

### Data Cleaning

- The dataset contained different notations for the same category in the column Item Fat Content (e.g., LF, low fat, reg).

- These were replaced with standardized terms (Low Fat and Regular) to ensure consistency in analysis.

### Key Metrics (Sales and Ratings)

- Total Sales: The dataset shows total sales amounting to a large value (calculated sum). This represents the overall revenue generated across all items and outlets.

- Average Sales: The mean sales per transaction was calculated, giving an idea of the typical sales volume.

- Number of Items Sold: The count of all transactions (sales entries) was determined, representing the total number of items sold.

- Average Ratings: The dataset also includes customer ratings, and their average value highlights the overall customer satisfaction level across outlets.

### Sales by Fat Content (Pie Chart)

The pie chart represents the proportion of sales contributed by Regular vs. Low Fat items.

We can see which category dominates customer purchases:

If Regular is higher, it means customers prefer standard-fat products.

If Low Fat is significant, it shows a growing demand for healthier alternatives.

This helps companies decide whether to push healthy marketing campaigns or maintain focus on popular regular items.

### Sales by Item Type (Bar Chart)

This chart displays the total sales across all product categories (Item Types).

Categories are sorted in descending order, so the top bars show the most profitable product categories.

For example, if Fruits & Vegetables or Snack Foods are at the top, these are the highest-selling product lines.

The labels above each bar provide the exact sales figures, making it easy to identify not only trends but also actual revenue contribution.

### Outlet Tier by Item Fat Content (Clustered Bar Chart)

This visualization compares sales of Regular vs. Low Fat items across different Outlet Location Types (Tier 1, Tier 2, Tier 3).

From this, we can analyze:

Whether urban outlets (Tier 1) prefer Low Fat products more than smaller towns.

Whether semi-urban and rural outlets (Tier 2 and 3) still rely heavily on Regular products.

This insight is very useful for targeted marketing strategies, tailoring promotions differently for Tier 1, Tier 2, and Tier 3 markets.

### Sales by Outlet Establishment Year (Line Chart)

This line chart tracks total sales by the year outlets were established.

It shows whether older outlets (established earlier) generate more sales due to trust and loyalty, or whether newer outlets perform better due to modern facilities.

For example:

A steady increase indicates that older outlets keep growing steadily.

A dip in certain years may suggest outlets from that period were less successful.

Adding labels on each point gives clarity on how much revenue each outlet-year contributed.

### Sales by Outlet Size (Pie Chart)

This pie chart shows the proportion of sales by outlet size (Small, Medium, Large).

If Large outlets dominate, it indicates that customers prefer bigger outlets due to variety and availability.

If Small outlets have significant sales, it reflects convenience and accessibility as key factors.

This information can guide companies in choosing the best outlet size for future expansions.

### Sales by Outlet Location Type (Bar Chart)

This chart shows total sales across Tier 1, Tier 2, and Tier 3 outlet locations.

It highlights which geographical markets contribute the most revenue.

For example:

If Tier 1 (urban cities) has the highest sales, demand is stronger in big metropolitan areas.

If Tier 2 (semi-urban) also shows strong performance, it means mid-sized cities are equally important for business growth.

Tier 3 (rural) contribution shows penetration into smaller towns.

This insight can help in regional supply chain planning and ad targeting.

## Business KPIs Results

1. Total Sales: ₹1,201,681.5

2. Average Sales per Item: ₹141.0

3. No. of Items Sold: 8,523

4. Average Ratings:  4.0


## Conclusion

1. Blinkit’s core strength lies in Tier 3 cities and medium-sized outlets.

2. Regular Fat items slightly outperform Low Fat, but both remain profitable.

3. Fruits, Vegetables, and Snack Foods are the company’s top revenue drivers.

4. Expansion into newer outlets (2020–2022) is showing good potential.

5. Underperforming large outlets and grocery stores need re-strategizing.
   
## Author 
Shrawani M. Amrutkar 

https://github.com/Sam-amr
