# E-Commerce Sales & Customer Analysis

## Project Overview

This project performs an end-to-end exploratory data analysis of the Olist Brazilian E-Commerce dataset to understand sales performance, customer behavior, product categories, seller performance, geographic trends, customer satisfaction, and delivery performance.

The analysis focuses on identifying actionable business insights that can help improve customer retention, sales growth, seller performance, and delivery operations.

## Dataset

The project uses the Olist Brazilian E-Commerce Public Dataset, containing information about:

- Orders
- Customers
- Order items
- Products
- Payments
- Reviews
- Sellers
- Geolocation
- Product category translations

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code
- Exploratory Data Analysis
- Data Cleaning
- Data Visualization

## Key KPIs

| KPI | Value |
|---|---:|
| Delivered Orders | 96,478 |
| Total Revenue | ₹132.21L |
| Items Sold | 110,197 |
| Average Order Value | ₹137.04 |
| Unique Customers | 93,358 |
| Repeat Customers | 2,801 |
| Repeat Customer Rate | 3.00% |
| Average Delivery Time | 12.56 days |
| Median Delivery Time | 10.22 days |
| Late Orders | 7,826 |
| Late Delivery Rate | 8.11% |
| Average Review Score | 4.09 / 5 |
| Negative Reviews | 14,575 |
| Negative Review Rate | 14.69% |

## Key Business Insights

### Customer Insights

- The customer base is highly concentrated in one-time buyers.
- Repeat customers represent only 3% of customers.
- Repeat customers generate higher average revenue per customer than one-time buyers.
- Improving customer retention and encouraging repeat purchases represents a major growth opportunity.

### Product & Category Insights

- Health & Beauty is the highest-revenue product category.
- Watches & Gifts and Bed Bath Table are also major revenue contributors.
- Furniture Decor, Bed Bath Table, and Computers Accessories have relatively high negative-review rates.
- High revenue does not always correspond to high customer satisfaction.

### Geographic Insights

- São Paulo (SP) is the dominant revenue-generating state.
- Rio de Janeiro (RJ) and Minas Gerais (MG) are the next-largest markets.
- Revenue is concentrated in a relatively small number of major states.

### Seller Insights

- A relatively small group of sellers contributes significantly to marketplace revenue.
- High seller revenue does not always correspond to high customer ratings.
- Some high-revenue sellers have relatively low review scores and may require operational improvements.

### Delivery Insights

- Average delivery time is 12.56 days.
- Median delivery time is 10.22 days.
- 8.11% of delivered orders were late.
- The largest delivery-time group is 8–14 days, representing approximately 41.7% of delivered orders.
- Orders taking more than 30 days represent a smaller share of deliveries but have a much higher concentration of late orders.

## Business Recommendations

### 1. Improve Customer Retention

Develop loyalty programs, personalized offers, and post-purchase campaigns to convert one-time customers into repeat buyers.

### 2. Focus on High-Revenue Categories

Prioritize inventory, promotions, and seller partnerships in categories such as Health & Beauty, Watches & Gifts, and Bed Bath Table.

### 3. Address High Negative-Review Categories

Investigate product quality, packaging, seller service, and delivery issues in categories with high negative-review rates.

### 4. Improve Delivery Performance

Focus on reducing delays in orders with longer delivery times and identify sellers or regions associated with frequent late deliveries.

### 5. Monitor Seller Quality

Evaluate sellers using both revenue and customer satisfaction metrics. High-revenue sellers with lower review scores should receive additional operational monitoring.

### 6. Expand in High-Value States

Use the strong performance of São Paulo, Rio de Janeiro, and Minas Gerais as a benchmark while identifying opportunities in other states.

## Project Structure

```text
ecommerce-sales-customer-analysis/
│
├── data/
│   └── raw/
│       ├── olist_customers_dataset.csv
│       ├── olist_geolocation_dataset.csv
│       ├── olist_orders_dataset.csv
│       ├── olist_order_items_dataset.csv
│       ├── olist_order_payments_dataset.csv
│       ├── olist_order_reviews_dataset.csv
│       ├── olist_products_dataset.csv
│       ├── olist_sellers_dataset.csv
│       └── product_category_name_translation.csv
│
├── notebooks/
│   └── 01_eda.ipynb
│
└── README.md