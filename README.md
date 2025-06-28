# saas-revenue-analysis

# 💼 Revenue & Product Analysis for a Digital SaaS

This project explores how a fictional SaaS platform (inspired by tools like [Stan Store](https://www.stan.store/) and [The Leap](https://www.theleap.co/)) performs in terms of revenue and product efficiency. The platform allows creators to sell digital products such as courses, templates, memberships, and more.

The goal is to answer key business questions using real-world data practices: cleaning, exploration, and deriving actionable insights for marketing and product decisions.

> 📌 Note: This is a portfolio project for learning purposes. The dataset is artificially generated.

---

### 📊 Technologies Used
- Python (Pandas, NumPy)
- Data Cleaning & EDA
- Seaborn, Matplotlib
- Business + Product Analytics Thinking

---

### 📁 Project Structure
├── data/
│ └── saas_revenue_data.csv
├── notebook/
│ └── saas_analysis.ipynb
├── images/
│ └── revenue_per_product.png
└── README.md


---

### 📌 Questions We Explore

- **Q1:** What product types drive the most revenue efficiency (revenue per order)? ✅
- **Q2–Q5:** Coming soon...

---

### ✅ Completed So Far

#### 1. Data Wrangling
- Replaced missing `product` values with `"Unknown"`
- Detected and removed rows with invalid `order_value` (e.g. negative or `'unknown'`)
- Converted `order_date` and `order_value` to proper types
- Removed 2 duplicated rows

#### 2. Q1 Analysis: Revenue Efficiency by Product
We calculated total revenue, total orders, and revenue per order for each product type.

📊 Here’s a quick summary:

| Product          | Revenue/Order |
|------------------|----------------|
| Membership       | $40.05         |
| Template Pack    | $38.51         |
| E-book           | $38.13         |
| 1-on-1 Coaching  | $37.06         |
| Online Course    | $37.03         |
| Unknown          | $41.50         |

> ⚠️ "Unknown" may include edge cases or data entry errors, so we focus our insight on defined products.

You can view the full notebook [here](notebook/saas_analysis.ipynb) or see visualizations in the `images/` folder.

---

### 📌 Next Steps
- Q2: Analyze performance across creator niches
- Q3: Identify monthly/seasonal revenue trends
- Q4: Explore pricing sweet spots by product type
- Q5: Profile top creators and their best-selling products
