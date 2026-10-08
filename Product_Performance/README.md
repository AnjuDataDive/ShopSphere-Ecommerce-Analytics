# 🛍️ ShopSphere — Product Performance Dashboard

> **Understanding product sales, revenue, ratings, and brand performance through interactive Power BI analytics.**

---

## 📌 Overview

The **ShopSphere Product Performance Dashboard** is an interactive Power BI dashboard designed to evaluate how products and brands are performing across key business metrics.

The dashboard provides a consolidated view of:

- Product portfolio size
- Units sold
- Product revenue
- Average product rating
- Top-performing products
- Products with the highest sales volume
- Brand-wise ratings
- Brand-wise revenue performance

It enables business teams to quickly identify **high-performing products, leading brands, sales leaders, and opportunities for product-level improvement.**

---

## 🎯 Business Objective

The primary objective of this dashboard is to answer:

> **Which products and brands are driving ShopSphere's sales and revenue, and how does customer rating relate to product performance?**

The dashboard helps decision-makers:

- Identify products generating the highest revenue
- Identify products with the highest sales volume
- Compare revenue performance across brands
- Monitor customer ratings by brand
- Understand the overall product portfolio
- Filter product performance based on different business dimensions

---

## 📊 Key Performance Indicators

| KPI | Description |
|---|---|
| 🛍️ **Total Products** | Total number of products available in the analysis |
| 📦 **Total Units Sold** | Total quantity of products sold |
| 💰 **Product Revenue** | Revenue generated from product sales |
| ⭐ **Average Rating** | Average customer rating across products |

### Current Dashboard Snapshot

- **Total Products:** 1K
- **Total Units Sold:** 15K
- **Product Revenue:** 2.80M
- **Average Rating:** 4.17 / 5

> KPI values shown above represent the current dashboard view and can change when filters are applied.

---

## 📈 Dashboard Visualizations

### 1. Top 10 Products by Revenue

A bar chart ranks the **top 10 products based on revenue generated**.

This helps identify the products contributing most significantly to ShopSphere's product revenue.

The current dashboard highlights products such as:

- iPhone 15
- Puzzle Set
- Wireless Mouse
- IdeaPad Slim 3
- Galaxy S24
- Non-Stick Cookware Set
- Cricket Bat
- Denim Jeans
- Moisturizer
- Air Fryer

---

### 2. Products with Most Units Sold

A donut chart displays the products contributing the highest number of units sold.

This helps distinguish between:

> **Products that sell frequently** vs. **products that generate high revenue.**

This distinction is useful because a product can have high sales volume without necessarily being the highest-revenue product.

---

### 3. Total Ratings by Brand

The dashboard compares the **number of ratings received by different brands**.

The current view includes brands such as:

- Philips
- Puma
- Nike
- Hasbro
- Lakme

This visualization provides an indication of customer engagement with products from different brands.

---

### 4. Top 5 Brands by Revenue

A bar chart ranks the **top five brands by revenue**.

The dashboard currently highlights:

- Apple
- Nike
- Philips
- Lakme
- Funskool

This allows the business to quickly identify the brands contributing the most revenue.

---

## 🎛️ Interactive Filters

The dashboard includes interactive filters that allow users to explore product performance from different perspectives.

### Available Filters

- ⭐ **Rating**
- 📦 **Units Sold**
- 📅 **Month**
- 🏷️ **Brand**

These filters allow users to move from an overall product view to a more specific analysis.

For example:

> Select a particular brand → analyze its products → compare sales volume and revenue → evaluate customer ratings.

---

## 💡 Business Questions Answered

The dashboard helps answer important product-related questions:

### Product Performance

- Which products generate the highest revenue?
- Which products sell the most units?
- Which products are the strongest performers overall?

### Brand Performance

- Which brands generate the highest revenue?
- Which brands receive the most customer ratings?
- How does brand performance differ across revenue and customer engagement?

### Customer Feedback

- What is the overall average product rating?
- Which brands receive the highest number of ratings?

### Decision Making

- Which products should receive more inventory attention?
- Which brands are important revenue contributors?
- Which products may require further investigation based on their sales or rating performance?

---

## 🔍 Key Analytical Insights

The dashboard enables several useful business observations.

### 🏆 Revenue Leaders

The **Top 10 Products by Revenue** visualization makes it possible to identify the products responsible for a significant share of product revenue.

### 📦 Sales Volume

The **Products with Most Units Sold** visualization highlights products with strong customer demand.

### 🏷️ Brand Contribution

The **Top 5 Brands by Revenue** chart provides a clear view of which brands are major contributors to ShopSphere's revenue.

### ⭐ Customer Engagement

The **Total Ratings by Brand** visualization provides another dimension of product performance by showing how much customer interaction different brands receive.

### 📊 Multi-dimensional Analysis

Combining:

**Revenue + Units Sold + Ratings**

provides a more complete view of product performance than looking at sales alone.

---

## 🧮 Power BI & DAX

The dashboard was developed using **Microsoft Power BI**, with DAX measures used to calculate key performance indicators and analytical metrics.

Examples of metrics include:

- Total Products
- Total Units Sold
- Product Revenue
- Average Rating
- Revenue by Product
- Revenue by Brand
- Units Sold by Product
- Ratings by Brand

The dashboard uses Power BI's filtering and interactive visualization capabilities to allow users to explore these metrics dynamically.

---

## 🗂️ Data Used

The dashboard primarily uses product and transaction-related information, including:

- Product details
- Product categories
- Brands
- Selling prices
- Units sold
- Revenue
- Customer ratings
- Dates / months

These fields are transformed into analytical measures and visualizations within Power BI.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| 🐍 **Python** | Data generation and preparation |
| 🗄️ **MySQL** | Data storage and validation |
| 📊 **Excel** | Data inspection and analysis |
| 📈 **Power BI** | Dashboard development and visualization |
| 🧮 **DAX** | KPI calculations and analytical measures |

---

## 🔄 Analytical Workflow

```text
Raw E-Commerce Data
        ↓
Data Cleaning & Validation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Power BI Visualizations
        ↓
Product Performance Analysis
        ↓
Business Insights
