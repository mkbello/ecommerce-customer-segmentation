# E-Commerce Customer Segmentation Report

## Introduction
This project analyzes transactional data from an e-commerce retail business to uncover key revenue drivers, customer behavior patterns, and opportunities for growth. Using Python for data cleaning and RFM (Recency, Frequency, Monetary) segmentation, customers were classified into strategic groups: **Champions, Loyal Customers, Frequent Buyers, and At Risk customers** to better understand their value and purchasing habits.

The goal of this project is to provide actionable insights through an interactive **Power BI dashboard** that visualizes sales performance, customer segmentation, product trends, and geographic distribution.

---

## Dataset
- **Transactions:** 397884 records  
- **Unique Customers:** 4338  
- **Countries:** 37  
- **Date Range:** 2010-12-01 – 2011-12-09 
- **Total Revenue:** [Currency]8,911,407.90
- **Source:** Online Retail Dataset  
---

## Methodology
1. **Data Cleaning & Preprocessing**
   - Removed duplicates, null CustomerIDs, and canceled transactions  
   - Calculated total transaction value per row (`TotalPrice = Quantity × UnitPrice`)

2. **Exploratory Data Analysis (EDA)**
   - Total revenue 
   - Top countries by revenue  
   - Monthly sales trend

3. **Customer Segmentation using RFM**
   - **Recency:** Days since last purchase  
   - **Frequency:** Total number of purchases  
   - **Monetary:** Total spend  
   - Customers scored and grouped into segments:
     - **Champions:** High frequency, high spend, recent purchase  
     - **Loyal Customers:** Frequent buyers, moderate spend  
     - **Frequent Buyers:** Active customers, moderate purchase behavior  
     - **At Risk:** Previously high-value customers with declining activity  
     - **Others:** Remaining customers

4. **Dashboard Creation**
   - Developed in **Power BI** with interactive visuals: KPI cards, line charts, bar charts, pie charts, maps, and tables  
   - Slicers for filtering by **Country, Month, Product, and Segment**  
   - Designed for clear storytelling and actionable insights

---

## Dashboard Highlights
- **Page 1:** Executive Overview – Key metrics and high-level business overview 
- **Page 2:** Sales Insights – Revenue trends, and top countries 
- **Page 3:** Customer Insights (RFM) – RFM segments, top customers, and revenue by segment  
- **Page 4:** Product Insights – Top products and quantity sold trends  
- **Page 5:** Geographic Insights – Revenue and customer distribution by country  
- **Page 6:** Key Insights & Recommendations – Actionable strategies based on data

---

## Key Findings
- A small portion of high-value customers (Champions) contributes a **significant share of total revenue**.  
- Certain countries (United Kindom, Netherland) drive the majority of sales, highlighting **geographic opportunities**.  
- Top products (Paper craft, Regency cakestand 3 tier etc) generate the highest revenue, suggesting **priority items for marketing campaigns**.  
- At Risk customers (33.03%) represent an opportunity for **targeted retention campaigns**.

---

## Recommendations
- **Reward Champions:** Implement VIP programs, exclusive discounts, and early access promotions to retain top customers.  
- **Re-engage At Risk Customers:** Send personalized promotions or win-back campaigns to reduce churn.  
- **Promote Top Products in High-Revenue Markets:** Focus marketing and bundling strategies on top-performing items in key regions.  
- **Optimize Marketing by Segment:** Use RFM segments to design personalized campaigns and improve ROI.

---

## Limitations

- **Historical Dataset:** The analysis is based on transactional data from **2010–2011**, which may not fully represent current customer behavior or market conditions.

- **Limited Customer Information:** The dataset does not include demographic or behavioral attributes (e.g., age, gender, marketing channels), limiting deeper customer profiling and personalization insights.

- **RFM Model Constraints:** While RFM segmentation effectively categorizes customers based on purchasing behavior, it does not account for other factors such as customer satisfaction, product preferences, or engagement across marketing channels.

- **Transaction-Level Data Only:** The analysis relies solely on transaction records and does not incorporate external factors such as marketing campaigns, seasonality effects beyond the dataset period, or economic conditions that could influence sales trends.

---

## Conclusion

The analysis shows that revenue is heavily driven by a small group of high-value customers, emphasizing the need for strong retention strategies. Sales are concentrated in key markets like the United Kingdom and the Netherlands, while a few top-performing products generate a significant share of total revenue. 

The high proportion of At Risk customers presents both a challenge and an opportunity for targeted re-engagement. Overall, RFM segmentation provides actionable insights to improve customer retention, optimize marketing efforts, and support sustainable revenue growth.

---

*Prepared by: Muktar Bello*  
*Date: 2026-02-22*

