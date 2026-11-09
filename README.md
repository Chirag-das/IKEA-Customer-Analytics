 # IKEA Customer Analytics | Customer Segmentation & RFM Analysis

## Project Overview

This project focuses on analyzing retail customer purchasing behavior using the Online Retail II dataset. The objective is to identify customer segments, understand purchasing patterns, evaluate customer value, and generate actionable business recommendations.

The project follows an end-to-end data analytics workflow using Excel, SQL Server, Python, and Power BI.

## Business Objectives

- Analyze customer purchasing behavior and revenue patterns.
- Identify high-value and inactive customers.
- Perform RFM (Recency, Frequency, Monetary) analysis.
- Segment customers into meaningful business categories.
- Identify customers at risk of churn.
- Develop actionable recommendations for customer retention and revenue growth.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and initial analysis |
| SQL Server | Data querying and analysis |
| Python (Pandas) | Data preparation and RFM segmentation |
| Power BI | Interactive dashboard development |

## Project Workflow

1. **Data Collection:** Obtained the Online Retail II dataset.
2. **Data Cleaning:** Cleaned and prepared the retail transaction data using Excel and SQL Server.
3. **Data Analysis:** Used SQL to analyze customer transactions and purchasing patterns.
4. **Python Analysis:** Implemented RFM methodology using Python and Pandas.
5. **Customer Segmentation:** Classified customers into six segments.
6. **Dashboard Development:** Built an interactive Power BI dashboard to communicate business insights.

## RFM Customer Segmentation

RFM analysis evaluates customers using three dimensions:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How frequently a customer purchased.
- **Monetary:** How much a customer spent.

A 90-day inactivity threshold was applied to identify potential churn risk.

### Customer Segmentation Results

| Customer Segment | Customers |
|---|---:|
| Lost | 1,524 |
| Loyal | 1,416 |
| Champions | 1,291 |
| At Risk | 821 |
| New | 442 |
| Needs Attention | 387 |
| **Total** | **5,881** |

## Power BI Dashboard

The dashboard contains the following analytical views:

### 1. Home Page
Project overview and high-level business KPIs.

### 2. Customer Overview
Customer purchasing behavior and customer-level performance.

### 3. Revenue Overview
Revenue trends and sales performance.

### 4. RFM Country Analysis
Customer segmentation across different countries.

### 5. RFM Segment Analysis
Customer distribution across the six RFM segments.

## Dashboard Screenshots

### Home Page
![Home Page](./IKEA-Customer-Analytics/05_Screenshots/Home%20Page.png)

### Customer Overview
![Customer Overview](./IKEA-Customer-Analytics/05_Screenshots/Customer%20Overview.png)

### Revenue Overview
![Revenue Overview](./IKEA-Customer-Analytics/05_Screenshots/Revenue%20Overview.png)

### RFM Country
![RFM Country](./IKEA-Customer-Analytics/05_Screenshots/RFM%20Country.png)

### RFM Segment
![RFM Segment](./IKEA-Customer-Analytics/05_Screenshots/RFM%20Segment.png)

## Key Business Recommendations

- **Champions:** Introduce loyalty rewards and exclusive benefits to retain high-value customers.
- **Loyal:** Encourage repeat purchases through personalized offers.
- **At Risk:** Launch targeted re-engagement campaigns.
- **Lost:** Evaluate win-back campaigns to reactivate inactive customers.
- **New:** Improve customer onboarding and encourage second purchases.
- **Needs Attention:** Use personalized promotions to improve engagement.

## Repository Structure

```text
IKEA-Customer-Analytics/
│
├── README.md
│
├── 02_PowerBI/
│   └── IKEA_Customer_Analytics_Dashboard.pbix
│
├── 03_SQL/
│   └── IKEA_Analysis.sql
│
├── 04_Python/
│   └── IKEA RFM Segmentation.ipynb
│
├── 05_Screenshots/
│   ├── Home Page.png
│   ├── Customer Overview.png
│   ├── Revenue Overview.png
│   ├── RFM Country.png
│   └── RFM Segment.png
│
└── 06_Documentation/
    ├── Business_Insights.md
    └── IKEA BRD.docx
```

## Dataset Information

The project uses the Online Retail II dataset.

The original and cleaned datasets are stored separately because of their large file sizes.

## Dataset Information & Downloads

This project uses the Online Retail II dataset for customer analytics and RFM segmentation.

The original and processed datasets are available through the following Google Drive links:

| Dataset | Download Link |
|---|---|
| Ecommerce Dashboard Dataset | [View / Download](https://drive.google.com/file/d/1Cu0BrxvlLfTNj7hMUr2S-TtIRSoPQOlh/view?usp=sharing) |
| Online Retail II Dataset - Page 1 | [View / Download](https://docs.google.com/spreadsheets/d/1FU5kieYjaYPOG_9BlRvXq4u67RrbDCrl/edit?usp=sharing) |
| Online Retail II Dataset - Page 2 | [View / Download](https://drive.google.com/file/d/1a3ut_rlOt9g_TtBhh6ai1-EC_SzwTuC0/view?usp=sharing) |
| Cleaned Retail Dataset | [View / Download](https://drive.google.com/file/d/1aQ-wy0oJwSpHrgwnLUsHzOSHFgd1T2q0/view?usp=sharing) |

**Note:** These datasets are hosted on Google Drive due to their large file sizes and are not stored directly in this GitHub repository.

## Project Deliverables

- Interactive Power BI dashboard.
- SQL analysis queries.
- Python notebook for RFM customer segmentation.
- Dashboard screenshots.
- Business insights documentation.
- Business Requirements Document (BRD).

## Conclusion

This project demonstrates an end-to-end retail customer analytics workflow, combining data cleaning, SQL querying, Python-based RFM analysis, customer segmentation, and interactive Power BI visualization.

The analysis helps identify valuable customers, recognize potential churn risks, and develop data-driven customer retention strategies.

---

**Project Category:** Retail Analytics | Customer Analytics | RFM Segmentation

**Technologies:** Excel | SQL Server | Python | Power BI
