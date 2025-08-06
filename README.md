🧠 SQL Portfolio: Data Analysis Projects

This repository showcases SQL-based data analysis projects using datasets from retail, banking, and research domains.

## 🔍 Projects Included

### 1. 🛒 Supermarket Sales Analysis
- Basket size analysis
- Customer segmentation by price sensitivity
- Year-over-Year performance

### 2. 🏦 Thai Bank KPI Comparison
- KPI benchmarking across banks
- Growth rate of financial indicators

### 3. 📊 Research Dataset EDA
- Summary statistics
- Segmentation and pattern discovery

Each project contains schema setup, SQL queries, and business insights.

---
> ✅ Tools: SQLite, BigQuery  
> ✨ Skills: CTEs, Window Functions, Aggregates, Joins, Business Thinking
📁 ภายในแต่ละโฟลเดอร์: README เฉพาะโปรเจกต์
ตัวอย่าง supermarket_analysis/README.md
markdown
Copy
Edit
# 🛒 Supermarket Sales SQL Analysis

Analyze customer purchasing behavior from supermarket transaction data.

## Key Queries
- `basket_summary.sql`: Total spend & units per basket
- `segment_analysis.sql`: Spending by price sensitivity
- `performance_yoy.sql`: YoY change in overall sales & customers

## SQL Concepts
- Window Functions (LAG)
- Aggregation (SUM, COUNT)
- CTEs (WITH clause)
- Filtering & Grouping

## Business Questions Answered
- Which customers spend the most per visit?
- How do sensitive vs insensitive customers behave?
- Is performance improving YoY?
