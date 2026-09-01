# E-Commerce Sales & Customer Analytics

A Python-based business analytics project analyzing e-commerce sales, customers, products, categories, geography, sales channels, discounts, and payment methods.

The objective is to convert transaction-level data into actionable business insights using exploratory data analysis and data visualization.

---

## 📊 Key Metrics

| Metric | Value |
|---|---:|
| Net Sales | ₹3.51 Cr |
| Total Orders | 8,000 |
| Unique Customers | 1,490 |
| Average Order Value | ₹4,388.72 |
| Repeat Customers | 1,459 |
| Repeat Customer Rate | 97.92% |

---

## 🎯 Business Questions

This project answers key business questions such as:

- What is the overall sales and order performance?
- Which categories generate the most revenue?
- Which products are the top revenue contributors?
- Which states contribute the most sales?
- How do Online and Offline channels compare?
- How did business performance change between 2024 and 2025?
- How are discounts associated with Average Order Value?
- Which payment methods are most commonly used?
- What customer purchasing patterns can be identified?

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains transaction-level e-commerce information covering:

- Order details
- Customer information
- Product information
- Category
- City and State
- Quantity
- Unit Price
- Discount Percentage
- Payment Method
- Sales Channel
- Customer Rating
- Gross Sales
- Net Sales

### Dataset Size

- Original Records: **8,020**
- Records after cleaning: **8,000**
- Columns: **18**
- Unique Orders: **8,000**
- Unique Customers: **1,490**

---

## 🧹 Data Cleaning

The following data preparation steps were performed:

1. Identified and removed 20 duplicate records.
2. Identified 20 missing Payment Method values.
3. Replaced missing Payment Method values with `Unknown`.
4. Retained missing Customer Rating values where no reliable replacement was available.
5. Converted `Order_Date` to datetime format.
6. Performed final validation after cleaning.

---

## 📈 Analysis Performed

### Overall Sales Performance

- Total Net Sales
- Total Orders
- Unique Customers
- Average Order Value

### Category Analysis

- Revenue by category
- Quantity sold by category
- Average unit price by category

### Customer Analysis

- Orders per customer
- Repeat customers
- Repeat customer rate
- Order frequency

### Geographical Analysis

- Revenue by state
- Revenue contribution by state
- Top-performing state

### Sales Channel Analysis

- Orders by channel
- Revenue by channel
- Average Order Value by channel

### Time-Based Analysis

- Monthly revenue
- Monthly order volume
- Yearly revenue
- Yearly orders
- Yearly AOV
- Year-over-year growth

### Product Analysis

- Top 10 products by revenue
- Top 10 products by quantity

### Discount Analysis

- Revenue by discount level
- Orders by discount level
- Average Order Value by discount level

### Customer Rating Analysis

- Average customer rating by category

### Payment Analysis

- Orders by payment method
- Revenue by payment method

---

# 🔑 Key Business Insights

### 1. Strong Overall Sales

The business generated approximately **₹3.51 crore in net sales** across **8,000 orders**, with an Average Order Value of approximately **₹4,388.72**.

### 2. High Repeat Customer Rate

The analysis identified **1,459 repeat customers out of 1,490 customers**, resulting in a repeat customer rate of approximately **97.92%**.

### 3. Electronics Leads Revenue

Electronics generated approximately **₹1.16 crore** in net sales, making it the highest-revenue category.

### 4. Maharashtra is the Largest Market

Maharashtra generated approximately **₹89.85 lakh**, contributing approximately **25.59% of total net sales**.

### 5. Online is the Dominant Channel

Online generated **5,415 orders**, compared with **2,585 offline orders**, indicating significantly higher transaction volume through the online channel.

### 6. Smart Watch is the Top Revenue Product

Smart Watch generated approximately **₹42.77 lakh** in net sales, making it the highest-revenue product in the dataset.

### 7. Higher Discounts are Associated with Lower AOV

Average Order Value decreased from approximately **₹4,821 at 0% discount** to **₹3,516.90 at 25% discount**.

This represents an observed association and does not establish causation.

### 8. 2025 Performance Remained Stable

Compared with 2024:

- Revenue declined by **0.64%**
- Orders declined by **0.40%**
- AOV declined by **0.24%**

Overall business performance remained broadly stable year-over-year.

---

# 💡 Business Recommendations

### 1. Strengthen High-Performing Categories

Continue investing in Electronics and Home & Kitchen while identifying opportunities to improve lower-performing categories.

### 2. Optimize the Online Channel

Given the higher online order volume, focus on improving online conversion, customer experience, and retention.

### 3. Expand Geographic Reach

Maharashtra is a major revenue contributor. Opportunities should be explored to increase penetration in lower-performing states while maintaining established markets.

### 4. Optimize Discounting

Discounts should be targeted toward specific products and customer segments rather than applied broadly.

Promotional campaigns should be evaluated based on incremental revenue and profitability.

### 5. Leverage High-Performing Products

Products such as Smart Watches, Air Fryers, and Bluetooth Speakers can be prioritized for cross-selling, bundling, and inventory planning.

### 6. Protect Customer Retention

The high repeat-customer rate provides an opportunity to strengthen loyalty programs and personalized offers.

### 7. Monitor Growth

Although 2025 performance was broadly stable, category, product, channel, and geographic trends should be monitored to identify opportunities for renewed growth.

---

# 📊 Visualizations

### Revenue by Category

![Revenue by Category](visualizations/revenue_by_category.png)

### Revenue by State

![Revenue by State](visualizations/revenue_by_state.png)

### Revenue by Sales Channel

![Revenue by Channel](visualizations/revenue_by_channel.png)

### Monthly Sales Trend

![Monthly Sales Trend](visualizations/monthly_sales_trend.png)

### Top Products by Revenue

![Top Products by Revenue](visualizations/top_products_by_revenue.png)

### Discount vs Sales

![Discount vs Sales](visualizations/discount_vs_sales.png)

---

# 📁 Project Structure

```text
retail-sales-analytics/
│
├── data/
│   └── ecommerce_sales.csv
│
├── notebooks/
│   └── ecommerce_sales_analysis_final.ipynb
│
├── visualizations/
│   ├── discount_vs_sales.png
│   ├── monthly_sales_trend.png
│   ├── revenue_by_category.png
│   ├── revenue_by_channel.png
│   ├── revenue_by_state.png
│   └── top_products_by_revenue.png
│
├── README.md
│
└── requirements.txt