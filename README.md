# 📊 Amazon Sales Performance & Geographical Insights (2020–2024) | Power BI Portfolio

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-0078D4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## 📌 Project Overview
An interactive, 3-page **Power BI** executive dashboard analyzing **$91.83M** in e-commerce sales across **100,000 orders** from **2020 to 2024**. This project evaluates multi-year revenue trends, product and brand velocity, promotional discount efficiency, order cancellation bottlenecks, and regional customer growth across 5 countries.

The report is designed for executive stakeholders, category managers, and operations teams to monitor KPIs via Year-over-Year (YoY) DAX indicators and drill down into granular category and geographic performance.

---

## 🖼️ Dashboard Preview

### 1. Executive Sales Overview
> *Tracks high-level KPIs with YoY growth sparklines, regional revenue share, monthly seasonality, and category-level order cancellation rates.*
<img width="2075" height="1200" alt="amazon sales_page-0001" src="https://github.com/user-attachments/assets/84258b20-ab49-4917-9f0f-00dd1915003e" />


### 2. Product & Brand Performance
> *Analyzes top revenue-generating brands, SKU order velocity, and the relationship between promotional discount rates and sales quantity.*
<img width="2075" height="1200" alt="amazon sales_page-0002" src="https://github.com/user-attachments/assets/d817f9a0-aa4f-4f80-b07d-8b32d5d214dc" />


### 3. Geographical Insights & Market Health
> *Maps global revenue distribution, cross-country category demand, state-level cancellation rates, and international customer growth velocity.*
<img width="2075" height="1200" alt="amazon sales_page-0003" src="https://github.com/user-attachments/assets/005ee915-db9a-4e68-ae5a-4f39dce5b51f" />


---

## 🎯 Business Problem & Objectives
To support data-driven commercial and operational decisions, this dashboard answers five core business questions:
1. **Executive Trajectory:** How are top-line revenue, order volume, customer acquisition, and Average Order Value (AOV) trending YoY?
2. **Category & Brand Concentration:** Which product categories, brands, and individual SKUs drive the highest revenue and order volume?
3. **Promotional Efficiency:** Do higher average discount rates correlate with significantly higher unit sales across categories?
4. **Operational Bottlenecks:** Which product categories and US states exhibit the highest order cancellation rates?
5. **Geographic Expansion:** How does revenue concentration compare against YoY customer growth across domestic and international markets?

---

## 📈 Key Insights & Findings

### 1. Executive Summary & Growth Dynamics
* **Strong Multi-Year Volume & Top-Line Growth:** Generated **$91.83M** in cumulative total sales across the 2020–2024 period, closing with a **+24.66% YoY** annual sales growth rate. Overall fulfillment reached **100,000 total orders** (**+24.80% YoY**) and **300,140 total units sold** (**+24.77% YoY**).
* **Retention-Driven Order Velocity:** The platform engaged **43,233 unique customers** over the 5-year span, with customer acquisition growing at **+8.16% YoY**. Because order growth (+24.80% YoY) significantly outpaced unique customer growth, revenue momentum is primarily fueled by **repeat customer purchase frequency** and strong user retention.
* **Stable Basket Size Across 5 Years:** Average Order Value (AOV) across all historical transactions held remarkably steady at **$918.26**, showing virtually zero pricing erosion (**-0.11% YoY**) and reflecting strong long-term pricing power.
* **Monthly Seasonality:** Across the 5-year timeline, order volumes experience a recurring seasonal contraction in **February** (~6.8K orders) before rebounding in March and sustaining peak activity in **January, May, and August**.

### 2. Category, Brand & Product Performance
* **Co-Leading Categories:** **Electronics** (**$20.18M** | 65,925 units) and **Toys & Games** (**$20.14M** | 65,781 units) serve as the dual revenue engines, jointly contributing **43.9%** of cumulative 5-year revenue, followed closely by **Books** (**$16.68M**).
* **Brand Concentration:** The top 5 brands—**KiddoFun** ($14.7M), **HomeEase** ($14.6M), **UrbanStyle** ($12.9M), **ReadMore** ($12.9M), and **Apex** ($7.4M)—account for **$62.5M** (~68% of total cumulative sales).
* **Top-Selling SKUs:** High-utility consumer goods lead historical transaction frequency, topped by **LED Desk Lamp**, **Water Bottle**, **Cookware Set**, **Electric Kettle**, and **Router**.
* **Disciplined Discounting Strategy:** Average discount rates across all categories remain tightly controlled between **7.30%** (*Home & Kitchen*) and **7.49%** (*Electronics*), averaging **7.42%** overall. Category performance differences are driven by organic demand rather than aggressive promotional discounting.

### 3. Geographical & Operational Health
| Country | Total Sales | Revenue Share | Total Orders | AOV | Total Customers | YoY Customer Growth % |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **United States** | $64,310,048.50 | 70.03% | 70,058 | $917.95 | 37,731 | +11.86% |
| **India** | $13,875,839.12 | 15.11% | 15,051 | $921.92 | 12,976 | +21.19% |
| **Canada** | $5,323,757.00 | 5.80% | 5,818 | $915.05 | 5,486 | +22.51% |
| **United Kingdom** | $4,526,896.86 | 4.93% | 4,943 | $915.82 | 4,742 | +24.49% |
| **Australia** | $3,789,106.44 | 4.13% | 4,130 | $917.46 | 3,969 | +22.80% |
| **Total / Overall** | **$91,825,647.92** | **100.00%** | **100,000** | **$918.26** | **43,233** | **+8.16%** |

* **International Expansion Opportunity:** While the **United States** generates **70.03%** of revenue (led by **Texas** and **California**), international markets are expanding their customer bases at **2x the pace** of the US, led by the **UK (+24.49% YoY)** and **Australia (+22.80% YoY)**.
* **Fulfillment & Cancellation Risks:** Overall order cancellation sits at **3.03%**. However, **Sports & Outdoors** exhibits the highest category cancellation rate at **3.40%** despite generating the lowest revenue ($9.28M). At the state level, **Indiana**, **Ohio**, and **New York** experience elevated cancellation spikes (>3.3%), whereas **North Carolina** and **Books** (2.84%) show the lowest cancellation friction.

---

## 💡 Strategic Recommendations
1. **Investigate Sports & Outdoors Fulfillment:** Audit supplier lead times, product descriptions, and sizing accuracy in *Sports & Outdoors* to bring its **3.40%** cancellation rate down toward the **3.03%** company benchmark.
2. **Reallocate Marketing Spend to High-Growth International Markets:** Capitalize on the **>21% YoY customer growth** in the **UK, Australia, Canada, and India** (where India also yields the highest AOV at **$921.92**) through localized campaigns and inventory expansion.
3. **Optimize February Promotional Calendar:** Counteract the recurring February sales trough by introducing targeted post-holiday bundles or loyalty promotions in late January/early February.
4. **Target State-Level Logistics Bottlenecks:** Review regional warehouse routing and carrier performance in **Indiana, Ohio, and New York** to reduce >3.3% state-level order cancellations.

---

## 🛠️ Technical Implementation & Power BI Features
* **Data Modeling:** Structured a clean data model with a dedicated `Dim_Date` calendar table to support time-intelligence analysis across 2020–2024.
* **DAX Measures:** Created explicit DAX measures for:
  * *Base KPIs:* `Total Sales`, `Total Orders`, `Total Quantity`, `Total Customers`, `Average Order Value (AOV)`
  * *Time Intelligence:* `YoY Sales Growth %`, `YoY Orders Growth %`, `YoY Customer Growth %`, `YoY AOV Growth %`
  * *Operational Metrics:* `Cancellation Rate %`, `Avg Discount %`
* **UI/UX Design:**
  * Executive KPI cards with integrated trend sparklines and dynamic YoY conditional indicators.
  * Custom tile slicers with category icons for intuitive cross-filtering on the Product Performance page.
  * Conditional heatmap formatting on matrix tables to immediately surface regional performance outliers.

---

## 📂 Repository Structure
```text
├── assets/                          # High-resolution dashboard screenshots
├── data/                            # Source dataset (Kaggle Amazon Sales Dataset)
├── Amazon_Sales_Dashboard.pbix      # Power BI Desktop report file
├── amazon_sales_dashboard.pdf       # Static PDF export of the 3-page report
├── LICENSE                          # MIT License
└── README.md                        # Project documentation and findings
