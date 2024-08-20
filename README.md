# Sales Data Analysis with PySpark

This project analyzes sales data using PySpark, providing insights into customer behavior, product performance, and sales trends. The dataset includes information about orders, products, locations, and order sources.

## Project Structure

- **sales.csv**: Contains sales data with fields such as `Product_id`, `Customer_id`, `Order_date`, `Location`, and `Source_Order`.
- **menu.csv**: Contains product information with fields such as `Product_id`, `Product_Name`, and `Price`.

## Requirements

- Python 3.x
- PySpark
- Jupyter Notebook

## Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/SwatiMane92/Sales-Analysis.git
    cd Sales-Analysis
    ```

2. **Install dependencies:**
    Ensure you have PySpark installed:
    ```bash
    pip install pyspark
    ```

3. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Open the `sales_data_analysis.ipynb` file.

## Analysis Overview

1. **Data Loading:**
   - Sales and menu data are loaded into PySpark DataFrames with appropriate schemas.
   - Additional columns like `Year`, `Month`, and `Quarter` are derived from the `Order_date`.

2. **Merging Data:**
   - The sales and menu data are merged on `Product_id`.

3. **Analysis Conducted:**
   - **Total Amount Spent by Customer:** Shows the total spending of each customer.
   - **Total Amount Spent by Each Food Category:** Displays the total sales by product category.
   - **Sales Trends Over Time:**
     - Monthly, yearly, and quarterly sales are analyzed.
     - Daily sales trends are visualized.
   - **Product Popularity:** Analysis of the frequency of product purchases.
   - **Customer Behavior:**
     - Frequency of customer visits to restaurants.
     - Customer retention analysis over different years.
   - **Sales by Location and Order Source:**
     - Total and average sales by location.
     - Sales contribution by order source (e.g., online, restaurant).
   - **Product Pricing:**
     - Identification of the top 5 most expensive products.
   - **Growth Analysis:**
     - Month-wise sales growth rate.

4. **Additional Insights:**
   - **Average Spend per Order by Customer:**
     - Calculated for each customer with formatting up to two decimal places.
   - **Percentage Contribution:**
     - Contribution of each product and location to total sales.

## Usage

1. **Running the Analysis:**
   - Each cell in the notebook can be executed sequentially to perform the analysis.
   - Outputs are displayed in tabular format for easy interpretation.

2. **Customizing the Analysis:**
   - Modify the groupings, aggregations, and filters to suit specific business needs.
   - Additional visualizations or analyses can be added as needed.

## Conclusion

This project provides a comprehensive analysis of sales data, offering valuable insights into customer behavior, product performance, and sales trends. It is designed to be extensible and can be adapted to different datasets or business scenarios.

## Author

- **Swati Mane** - [GitHub](https://github.com/SwatiMane92/)
