# E-Commerce Python Analytics

## Python Data Analytics Portfolio Project

An end-to-end Python data analytics project analyzing 20,000 cleaned e-commerce transactions to understand sales performance, profitability, customers, products, regional performance, shipping operations, and payment behavior.

---

## Business Objective

The objective of this project is to analyze e-commerce transaction data and identify:

- Sales and profit trends
- Category and product performance
- Customer value and profitability
- Regional performance
- Shipping and operational issues
- Payment-method performance
- Business risks and growth opportunities

The analysis converts raw transaction data into business insights and actionable recommendations.

---

## Dataset

- Original records: 20,050
- Final records after cleaning: 20,000
- Columns: 16
- Data type: Transaction-level e-commerce data

### Main Data Areas

- Orders
- Customers
- Products
- Categories
- Regions
- Sales
- Profit
- Quantity
- Discounts
- Shipping
- Payment Methods

---

## Tools & Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning

The dataset was validated and cleaned before analysis.

Key cleaning activities included:

- Duplicate removal
- Missing-value handling
- Date conversion
- Category and region standardization
- Payment-method cleaning
- Invalid discount handling
- Zero-quantity handling
- Negative-sales validation
- Shipping-date validation

Final validation resulted in 20,000 records with no duplicate rows, negative sales, zero quantities, or invalid discounts.

---

## Analysis Performed

### 1. Overall Business Performance

Analyzed:

- Total Sales
- Total Profit
- Profit Margin
- Orders
- Customers
- Quantity
- Average Order Value

### 2. Monthly Sales & Profit Trends

Analyzed monthly:

- Sales
- Profit
- Orders
- Profit Margin
- AOV
- Month-over-month sales growth

### 3. Category & Sub-Category Analysis

Compared categories and sub-categories based on:

- Sales
- Profit
- Profit Margin
- Orders
- Sales contribution
- Profit contribution

### 4. Regional Analysis

Evaluated regional:

- Sales
- Profit
- Profit Margin
- Orders
- Customers
- AOV

### 5. Customer Analytics

Analyzed:

- Top customers by sales
- Top customers by profit
- One-time vs repeat customers
- Customer sales concentration
- High-sales low-margin customers
- Customer profitability segments
- Order frequency vs customer value

### 6. Product Analytics

Analyzed:

- Top products by sales
- Top products by profit
- High-sales low-margin products
- Low-sales high-margin products
- Product portfolio segmentation

### 7. Operations & Shipping

Analyzed:

- Average shipping time
- Late-order rate
- Shipping-mode performance
- Regional late-order rates
- Region × shipping-mode performance

### 8. Payment Analysis

Compared payment methods based on:

- Sales
- Profit
- Profit Margin
- Orders
- Customers
- AOV
- Sales contribution

---

## Key Business Findings

### Overall Performance

The business generated approximately **₹1.52 crore in sales** and **₹12.97 lakh in profit**, with an overall profit margin of **8.55%**.

### Product Profitability

The High Sales–Low Margin segment contributes **39.38% of product sales** but generates only a **5.49% profit margin**.

### Customer Profitability

334 customers generate above-average sales while maintaining an average profit margin of only **1.97%**.

### Customer Retention

Approximately **96.26% of customers made more than one purchase**, indicating a strongly repeat-oriented customer base.

### Shipping

Average shipping time is **4.06 days**, while **19.18% of valid shipping orders were classified as late**.

### High-Margin Opportunity

The Low Sales–High Margin product segment contains 18 products with an average margin of **13.06%**.

### Payment Methods

Credit Card, UPI, and Debit Card together account for **76.30% of total sales**.

---

## Business Recommendations

1. Improve margins on high-sales, low-margin products.
2. Review profitability of high-sales customers with weak margins.
3. Investigate the operational causes of delayed orders.
4. Evaluate opportunities to expand selected high-margin products.
5. Investigate the factors behind regional sales differences.
6. Monitor payment costs, failures, refunds, and conversion rates.

---

## Project Structure

```text
Ecommerce-Business-Analytics/
│
├── Ecommerce_Business_Analytics_Portfolio.ipynb
├── README.md
└── data/
    └── ecommerce_python.csv
