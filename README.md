# Retail Sales, Profitability & Inventory Analytics

## Project Overview

This project presents an end-to-end retail analytics workflow using Python, Pandas, NumPy, and Jupyter Notebook.

The objective of the project is to transform raw retail transaction, product, store, returns, and inventory data into meaningful business insights that can support management reporting and data-driven decision-making.

The analysis focuses on sales performance, profitability, store and product performance, returns, inventory efficiency, and target achievement.

---

## Business Objectives

The key objectives of this project are:

- Analyze overall retail sales performance
- Measure gross profit and gross margin
- Track key retail KPIs
- Analyze monthly and year-over-year sales trends
- Compare store-level performance
- Evaluate product and category profitability
- Identify loss-making transactions and products
- Analyze customer/product returns
- Measure inventory sell-through
- Identify slow-moving inventory
- Monitor stock availability
- Compare sales targets against actual performance
- Identify areas that may require management attention

---

## Dataset

The project uses multiple retail datasets:

- `sales_raw.csv` – Transaction-level sales data
- `products.csv` – Product master data
- `stores.csv` – Store master data
- `returns.csv` – Product return transactions
- `inventory_monthly.csv` – Monthly inventory data

These datasets are combined and analyzed to create a consolidated view of retail performance.

---

## Data Preparation

The project includes several data preparation and validation steps:

- Missing value analysis
- Duplicate transaction detection
- Duplicate record removal
- Data type validation
- Date conversion
- Data standardization
- Category cleanup
- Channel and payment method validation
- Business-rule checks
- Feature engineering
- Dataset merging
- KPI calculations
- Aggregation and summarization

---

## Key KPIs

| KPI | Result |
|---|---:|
| Total Net Sales | ₹22,137,921.10 |
| Total Gross Profit | ₹7,466,848.30 |
| Gross Margin | 33.73% |
| Total Transactions | 15,000 |
| Total Units Sold | 28,244 |
| Average Transaction Value (ATV) | ₹1,475.86 |
| Units Per Transaction (UPT) | 1.88 |

---

## Analysis Performed

### 1. Sales Performance Analysis

The sales analysis focuses on understanding overall business performance.

Key areas analyzed:

- Total Net Sales
- Gross Profit
- Gross Margin
- Total Transactions
- Units Sold
- Average Transaction Value
- Units Per Transaction
- Monthly Sales Trend
- Month-over-Month Growth
- Year-over-Year Growth

This analysis helps identify growth patterns and periods of stronger or weaker sales performance.

---

### 2. Monthly and Year-over-Year Trend Analysis

Sales trends were analyzed over time to understand performance movement.

The analysis includes:

- Monthly sales comparison
- Month-over-Month growth
- Year-over-Year comparison
- Identification of growth and decline periods

Trend analysis helps management understand whether performance is improving, declining, or remaining stable.

---

### 3. Store Performance Analysis

Store-level performance was evaluated using multiple business measures.

The analysis includes:

- Net Sales by Store
- Gross Profit by Store
- Transaction Volume
- Units Sold
- Store Ranking
- Store-Level Target Achievement
- Performance comparison across locations

This helps identify high-performing and underperforming stores.

---

### 4. Product and Category Analysis

Product and category-level analysis was performed to evaluate revenue and profitability.

The analysis includes:

- Product Sales Performance
- Category Performance
- Subcategory Performance
- Product-Level Gross Profit
- Gross Margin Analysis
- High Revenue Products
- Low Profitability Products
- Loss-Making Transactions

This analysis provides visibility into which products and categories contribute most to overall performance.

---

### 5. Profitability Analysis

Profitability analysis was performed using sales, cost, and gross profit information.

Key areas include:

- Gross Profit Analysis
- Gross Margin %
- Product-Level Profitability
- Category-Level Profitability
- Store-Level Profitability
- Identification of low-margin transactions
- Identification of loss-making transactions

This can help management review pricing, discounting, and product mix.

---

### 6. Returns Analysis

Return transactions were analyzed to understand their impact on business performance.

The analysis includes:

- Total Returned Transactions
- Return Amount
- Return Rate
- Return Reasons
- Product-Level Returns
- Category-Level Returns
- Return Hotspots

This analysis can help identify products or categories that may require further investigation.

---

### 7. Inventory Analysis

Inventory performance was analyzed using monthly inventory data.

The analysis includes:

- Opening Stock
- Closing Stock
- Units Sold
- Inventory Value
- Sell-Through %
- Product-Level Inventory
- Category-Level Inventory
- Stock Availability
- Stockout Identification

Sell-through analysis helps evaluate how efficiently inventory is converted into sales.

---

### 8. Slow-Moving Inventory Analysis

Slow-moving products were identified by comparing inventory levels with sales movement.

This analysis helps highlight products that may have:

- High stock levels
- Low sales movement
- Low sell-through percentage
- Potential excess inventory

These insights can support inventory planning and stock optimization decisions.

---

### 9. Target vs Actual Analysis

Store performance was also evaluated against sales targets.

The analysis includes:

- Sales Target
- Actual Sales
- Sales Variance
- Target Achievement %
- Months Achieved
- Months Missed
- Store-Level Target Performance

This provides a clear view of how stores are performing against planned business targets.

---

## Key Business Insights

- The business generated approximately **₹22.14 million in Net Sales**.

- Gross Profit was approximately **₹7.47 million**, with an overall **Gross Margin of 33.73%**.

- A total of **15,000 transactions** generated **28,244 units sold**.

- The overall **Average Transaction Value was ₹1,475.86**.

- The **Units Per Transaction was 1.88**, providing visibility into average basket size.

- Monthly sales analysis showed fluctuations in performance, helping identify growth and decline periods.

- Store-level analysis highlighted differences in revenue, profitability, transaction volume, and target achievement.

- Product and category analysis identified strong contributors as well as lower-margin and loss-making transactions.

- Returns analysis provided visibility into product return patterns and return reasons.

- Inventory analysis identified differences in sell-through performance across products.

- Slow-moving inventory analysis highlighted products with relatively high stock levels compared with sales movement.

- Target vs Actual analysis provided visibility into store achievement percentage and months in which sales targets were achieved or missed.

---

## Business Recommendations

Based on the analysis, management can consider the following areas for further review:

- Investigate stores that consistently miss sales targets
- Review slow-moving inventory and excess stock
- Monitor products with high return rates
- Review low-margin and loss-making transactions
- Improve availability of high-performing products
- Track ATV and UPT to understand basket performance
- Benchmark underperforming stores against stronger-performing locations
- Review product mix based on profitability and sell-through
- Monitor monthly sales trends for early identification of performance changes

---

## Data Analysis Techniques

The project demonstrates the use of:

- Data Cleaning
- Data Validation
- Data Transformation
- Data Aggregation
- Feature Engineering
- Dataset Merging
- Exploratory Data Analysis
- KPI Development
- Trend Analysis
- Profitability Analysis
- Inventory Analysis
- Business Rule Validation
- Performance Benchmarking

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Project Structure

```text
Retail-Sales-Profitability-Inventory-Analytics/
│
├── Retail_Sales_Profitability_Inventory_Analytics.ipynb
├── README.md
├── requirements.txt
│
└── data/
    ├── sales_raw.csv
    ├── products.csv
    ├── stores.csv
    ├── returns.csv
    └── inventory_monthly.csv
```

---

## Author

**Aftab Alam**

Senior Data Analyst | Power BI | SQL | Python

---

## Disclaimer

This project is created for portfolio and learning purposes.

The dataset used in this project is intended for analytical demonstration and does not represent confidential company information.
