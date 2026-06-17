# FUTURE_DS_01 – Business Sales Performance Analytics Dashboard

## Overview

This project focuses on analyzing business sales performance using data analytics and visualization techniques using Power BI.

The objective of this project is to identify important business trends, product performance, regional profitability, and revenue patterns to generate meaningful business insights and recommendations.

This project was completed as part of the **Future Interns Data Science & Analytics Internship – Task 1 (2026)**.

---

## Project Objective

The main objective of this project is to analyze business sales data and answer important business questions such as:

- Which products generate the highest revenue?
- How do sales change over time?
- Which category performs best?
- Which region is most profitable?
- Where can business performance be improved?

---

## Tools & Technologies Used

- **Power BI** – Data visualization and dashboard creation
- **CSV Dataset** – Superstore business sales data (9,994 records)
- **Microsoft Word** – Documentation and reporting

---

## Dataset Used

### Superstore Sales Dataset

**Dataset Size:** 9,994 rows × 21 columns | **Date Range:** January 2014 – December 2017

The dataset includes the following key business fields:

| Column | Description |
|--------|-------------|
| Row ID | Unique record identifier |
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method used |
| Customer ID / Name | Customer identifier and name |
| Segment | Business segment (Consumer, Corporate, Home Office) |
| Country / City / State / Region | Geographic details |
| Product ID / Name | Product identifier and name |
| Category / Sub-Category | Product classification |
| Sales | Revenue generated |
| Quantity | Units sold |
| Discount | Discount applied |
| Profit | Profit earned |

This dataset represents a retail business sales scenario and helps in performing real-world business analysis.

---

## Data Cleaning & Preparation

Before analysis, the dataset was cleaned and prepared for accurate results.

The following preprocessing steps were performed:

- Converted **Order Date** and **Ship Date** into proper date format (`MM/DD/YYYY`)
- Fixed date formatting issues using locale settings
- Verified numeric columns:
  - Sales
  - Profit
  - Quantity
  - Discount
- Checked for missing values across all 21 columns
- Validated categorical fields: Category, Region, Segment, Ship Mode
- Cleaned and prepared the data for accurate business analysis

---

## Key Performance Indicators (KPIs)

| KPI | Value |
|-----|-------|
| Total Sales | **$2.30M** |
| Total Profit | **$286.40K** |
| Total Quantity Sold | **37,873** |
| Total Orders | **5,009** |
| Profit Margin % | **12.47%** |
| Unique Customers | **793** |
| Unique Products | **1,850** |

---

## Dashboard Features

The dashboard includes the following interactive business analytics visualizations:

### 1. Sales Trend Over Time
Analyzes how business sales changed over time from 2014 to 2017. The trend chart reveals seasonal spikes and an overall upward trajectory in revenue.

### 2. Category-wise Sales Analysis
Compares revenue generated across three product categories:
- **Technology** – $836,154
- **Furniture** – $742,000
- **Office Supplies** – $719,047

### 3. Region-wise Profit Analysis
Shows profitability performance across four business regions (West, East, South, Central).

### 4. Top 10 Products by Sales
Identifies the top revenue-generating products, led by:
- Canon imageCLASS 2200 Advanced Copier – $61,599
- Fellowes PB500 Electric Punch Plastic Comb Binding Machine – $27,453
- Cisco TelePresence System EX90 Videoconferencing Unit – $22,638

### 5. Category-wise Profit Analysis
Compares category profitability across Technology, Furniture, and Office Supplies.

### 6. Interactive Region & Category Filters
Allows dashboard interaction using Region-based and Category-based filtering (e.g., filtering by "Office Supplies + East Region" shows $205.52K sales and $41.01K profit at 19.96% margin).

---

## Key Insights

### Regional Performance
| Region | Total Sales | Total Profit |
|--------|------------|-------------|
| **West** | $725,458 | **$108,418** ✅ Highest |
| East | $678,781 | $91,523 |
| South | $391,722 | $46,749 |
| **Central** | $501,240 | **$39,706** ❌ Lowest |

- **West region generated the highest profit** ($108,418)
- **Central region generated the lowest profit** ($39,706) despite being the 2nd highest in sales volume

### Category Performance
| Category | Total Sales | Total Profit |
|----------|------------|-------------|
| **Technology** | $836,154 | **$145,455** ✅ Highest |
| Office Supplies | $719,047 | $122,491 |
| **Furniture** | $741,999 | **$18,451** ❌ Lowest |

- **Technology category generated the highest profit** ($145,455)
- **Furniture category generated the lowest profit** ($18,451) despite high sales volume

### Sub-Category Performance
**Top Profitable Sub-Categories:**
- Copiers – $55,618
- Phones – $44,516
- Accessories – $41,937

**Loss-Making Sub-Categories:**
- Supplies – **-$1,189** (loss)
- Bookcases – **-$3,473** (loss)
- Tables – **-$17,725** (loss)

### Customer Segment Performance
| Segment | Total Sales |
|---------|------------|
| Consumer | $1,161,401 |
| Corporate | $706,146 |
| Home Office | $429,653 |

### Product Performance
- A small number of high-value products (especially copiers and binding machines) contributed significantly to overall Technology sales.
- Canon imageCLASS 2200 Advanced Copier alone generated $61,600 — the single highest-revenue product.

### Sales Trend
- Sales showed consistent seasonal peaks, especially towards the end of each year (Q4 spikes visible in 2015, 2016, and 2017).
- Overall sales demonstrated a year-over-year increasing trend from 2014 to 2017.

### Geographic Insights
**Top 5 States by Sales:**
1. California – $457,688
2. New York – $310,876
3. Texas – $170,188
4. Washington – $138,641
5. Pennsylvania – $116,512

---

## Business Recommendations

Based on the analysis, the following recommendations are suggested:

1. **Invest more in Technology products** – Highest profit margin category; expanding product range or promotions here will directly boost profitability.
2. **Improve performance in the Central region** – Despite moderate sales, profit is the lowest across all regions; review operational costs and discount policies.
3. **Review the Furniture category strategy** – Particularly Tables (-$17,725 loss) and Bookcases (-$3,473 loss) need urgent pricing and cost review.
4. **Eliminate or reprice loss-making sub-categories** – Supplies, Bookcases, and Tables are actively hurting profitability.
5. **Prioritize marketing and inventory for Top-selling products** – Focus inventory planning around Copiers, Phones, and Accessories (top 3 profitable sub-categories).
6. **Plan for Q4 demand surges** – Sales spike significantly at year-end; better inventory and logistics planning during Q3-Q4 can maximize revenue.
7. **Leverage the Consumer segment** – Largest segment by sales ($1.16M); targeted campaigns can drive even greater revenue.
8. **Focus geographic expansion in California and New York** – Already top-performing states; deepening market penetration here will yield the best return.

---

## Project Files Included

```text
Business-Sales-Performance-Analytics/
│── Sample - Superstore.csv
│── Business_Sales_Performance_Analytics.pbix
│── Dashboard Screenshot.png
│── README.md
```

## Dashboard Preview

*The dashboard supports interactive filtering by Category and Region.
<img width="991" height="566" alt="image" src="https://github.com/user-attachments/assets/b0c19315-a76e-4e2d-aca1-e7f4cbfb53ee" />

---

## Conclusion

This project demonstrates how data analytics and Power BI can be used to transform raw business sales data into meaningful insights and actionable recommendations.

Through KPI analysis, trend analysis, category comparison, regional profitability analysis, and product performance evaluation, this project provides a data-driven approach to business decision-making.

The Superstore dataset — spanning 4 years (2014–2017), 9,994 transactions, 793 customers, and 1,850 unique products — provided a rich foundation for uncovering patterns that directly inform strategic business decisions.

---

## Author

**Krish Patil**
B.Tech CSE(AIML) Student
