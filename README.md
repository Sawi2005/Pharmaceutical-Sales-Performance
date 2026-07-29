# 💊 Pharmaceutical Sales & Commercial Performance Dashboard

## 📖 Overview

This project is an interactive **Microsoft Excel dashboard** and **commercial analytics workbook** built to analyze pharmaceutical sales performance across the **Germany** and **Poland** markets. It combines traditional business intelligence reporting with formula-driven commercial analytics to simulate real-world pharmaceutical sales analysis.

The dashboard demonstrates how raw transactional data can be transformed into actionable business insights through segmentation, prioritization, performance evaluation, and incentive compensation modeling.

---

## 🎯 Objectives

The dashboard helps answer key business questions such as:

- How have sales changed across markets and years?
- Which distributors and customers contribute the most revenue?
- How should distributors and customers be segmented for prioritization?
- Which sales representatives are exceeding or missing expectations?
- How can incentive compensation be modeled using sales attainment?
- Which markets are growing, declining, or exiting?

---

## 🗂 Dataset

The project uses a pharmaceutical wholesale–retail sales dataset containing transactional data across **Germany** and **Poland**.

### Data Includes

- Distributor
- Customer (Hospital / Pharmacy)
- Country & City
- Channel & Sub-channel
- Product Name & Product Class
- Sales Representative, Manager & Team
- Quantity Sold
- Sales Revenue
- Returns
- Month & Year

---

# 📊 Dashboard Features

### Executive KPI Cards

- Total Sales
- Total Returns
- Return Rate

### Sales Performance

- Monthly Sales Trend
- Year-wise Sales Comparison (2018–2020)

### Distributor Analysis

- Top Performing Distributors
- Distributor Returns Analysis

### Product Analysis

- Sales by Product Class

### Channel Analysis

- Sales by Hospital & Pharmacy
- Government, Private, Institution & Retail Comparison

### Team Performance

- Sales Contribution by Team
- Sales by Manager
- Returns by Team

### Interactive Dashboard

- Market Filter
- Year Filter
- Dynamic Pivot Charts
- Interactive Slicers

---

# 🧮 Commercial Analytics Layer

Beyond dashboard reporting, a dedicated commercial analysis sheet was developed using advanced Excel formulas to simulate real pharmaceutical commercial analytics workflows.

## 1️⃣ Distributor Segmentation (Pareto Analysis)

Distributors are categorized into:

- **A – Strategic**
- **B – Core**
- **C – Long Tail**

based on cumulative sales contribution using:

- `RANK.EQ`
- `SUMIF`
- `IF`

---

## 2️⃣ Customer Segmentation

Customers are classified into:

- Key Account
- Growth Account
- Standard Account

using sales rankings generated with:

- `UNIQUE`
- `XLOOKUP`
- `RANK.EQ`

---

## 3️⃣ Distributor Prioritization Score

A weighted prioritization model ranks distributors using:

- **70% Sales Contribution**
- **30% Return Rate Risk**

to simulate distributor call-planning and engagement prioritization.

---

## 4️⃣ Sales Rep Performance & Incentive Compensation

Each sales representative is evaluated using:

- Sales Target Achievement
- Attainment Percentage
- Performance Tier
- Incentive Payout

Performance tiers include:

- Top Performer
- Core Performer
- Developing

Targets were assumed at **90% of actual sales** to simulate a real incentive compensation framework.

---

## 5️⃣ Market Growth Analysis

Year-over-year growth is calculated using:

- `SUMIFS`

Results are validated against PivotTables to ensure consistency.

---

# 🧠 Excel Functions Used

- XLOOKUP
- INDEX / MATCH
- SUMIFS
- COUNTIFS
- SUMPRODUCT
- RANK.EQ
- PERCENTILE
- UNIQUE
- LARGE
- IF / IFS
- IFERROR
- TEXT
- TRIM
- EXACT
- ISNUMBER

---

# 📈 Key Business Insights

- A small number of distributors generate the majority of total sales, indicating strong market concentration.
- **Poland generated sales only in 2018**, with no sales recorded in 2019 or 2020, suggesting a complete market exit or discontinued distribution partnership.
- **Germany experienced approximately 4% growth in 2019** followed by **around 9% decline in 2020**, highlighting the need for deeper product and channel-level analysis.
- Customer segmentation identified a limited number of **Key Accounts** contributing a significant share of total revenue.
- Sales representative performance is relatively balanced across teams, supporting a fair and data-driven incentive compensation model.

---

# 🛠 Tools & Technologies

- Microsoft Excel
- PivotTables
- PivotCharts
- Power Query
- Slicers
- Conditional Formatting
- Advanced Excel Formulas

---

# 🚀 Skills Demonstrated

- Microsoft Excel
- Dashboard Development
- KPI Reporting
- Commercial Analytics
- Pharmaceutical Sales Analytics
- Customer & Distributor Segmentation
- Incentive Compensation Modeling
- Business Intelligence Reporting
- Data Validation & Quality Assurance
- Business Problem Solving

---

# 📌 Future Enhancements

- Automated data refresh using Power Query
- SQL integration for large-scale data processing
- Python-based forecasting and predictive analytics
- Region and sub-channel level drill-down analysis
- Interactive what-if scenario modeling

---

# 📷 Dashboard Preview

> Add screenshots of the dashboard here.

Example:

```
Dashboard Images/
├── Dashboard Overview.png
├── Commercial Analysis.png
└── Filters & KPIs.png
```

---

# 📂 Project Structure

```
Pharmaceutical-Sales-Dashboard/
│
├── Pharmaceutical Sales Dashboard.xlsx
├── Dashboard Preview.pdf
├── Dashboard Images/
├── README.md
```

---

# 📄 Conclusion

This project demonstrates how **Microsoft Excel** can serve as a powerful commercial analytics platform by combining traditional BI reporting with formula-driven business analysis. Through distributor and customer segmentation, prioritization models, market growth analysis, and sales incentive modeling, the project showcases decision-oriented analytics commonly used in pharmaceutical commercial organizations.
