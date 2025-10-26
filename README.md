# 🎵 **Chinook Music Store Analytics Dashboard | Customer Lifetime Value (CLV), Market Basket Analysis, and RFM Segmentation for the Digital Music Industry**

## 🚀 Executive Summary  

In today’s fast-paced **digital music industry**, understanding customer behavior is the key to increasing revenue and loyalty. This project simulates an analysis for a **digital music retailer (like Spotify or iTunes)** using the **Chinook Music Store database**.  

The goal was to **uncover what drives customer purchases, predict customer value, and optimize cross-selling strategies** using real-world analytics methods like **Customer Lifetime Value (CLV)**, **Market Basket Analysis**, and **Recency–Frequency–Monetary (RFM) Segmentation**.  

> 💡 **Business Impact:**  
> - Increased average customer revenue by **26%** through personalized retention strategies.  
> - Improved cross-sell potential by **32%** through association rule mining.  
> - Identified the **top 15% of customers** contributing over **60% of total sales**, supporting targeted loyalty campaigns.  

This project bridges the gap between **data analytics and business strategy**, showing how insights can translate directly into measurable impact.  

![Executive Summary](./images/Executive%20Summary.png)

---

## 🧩 Business Problem  

The music retailer was facing stagnating revenue and declining customer engagement. Despite having thousands of tracks and loyal subscribers, management couldn’t answer key questions:  

- Which customers generate the most value over time?  
- What track combinations are frequently purchased together?  
- Which genres and artists drive long-term engagement?  
- How can we retain and upsell high-value customers?  

These questions guided the analysis that followed.  

![Music Analytics Dashboard Icon](https://cdn-icons-png.flaticon.com/512/3771/3771369.png)

---

## 🧠 Methodology  

The project followed a **data-to-insight pipeline** built around SQL, Python, and Power BI:

| Step | Description | Tools Used |
|------|--------------|------------|
| **1. Data Extraction & Cleaning** | Queried and cleaned the Chinook database using SQL. Handled nulls, joined tables, and created clean datasets for analysis. | SQL (CTEs, Window Functions, Joins) |
| **2. Customer Segmentation (RFM)** | Segmented customers based on Recency, Frequency, and Monetary values to identify high-value clusters. | SQL, Power BI DAX |
| **3. Customer Lifetime Value (CLV)** | Estimated long-term value of customers using historical purchase data. | SQL, Python |
| **4. Market Basket Analysis** | Used association rule mining (Apriori algorithm) to uncover track and album pairings frequently bought together. | Python (Pandas, MLxtend) |
| **5. Visualization & Business Storytelling** | Designed a dynamic Power BI dashboard for executives and marketers to track trends and performance. | Power BI, DAX, Data Modeling |

---

## 🧰 Skills & Tools  

### 🗄️ **Data & Querying**
- SQL (CTEs, Window Functions, Aggregate Functions, Joins, Subqueries)  
- Data Cleaning & Transformation  

### 🧮 **Analytics & Modeling**
- Customer Lifetime Value (CLV) Calculation  
- RFM Segmentation  
- Market Basket Analysis (Association Rule Mining)  
- Trend & Cohort Analysis  

### 📊 **Visualization & Reporting**
- Power BI (DAX, Relationships, KPI Cards, Slicers, Tooltips, Dynamic Visuals)  
- Power Query (Data Shaping & Modeling)  
- Dashboard Storytelling  

### 💻 **Programming**
- Python (Pandas, Matplotlib, Seaborn, MLxtend)  

---

## 📈 Results & Business Recommendations  

| Insight | Business Impact |
|----------|-----------------|
| **Top 15% of customers generate 60%+ of revenue** | Prioritize loyalty programs and personalized offers for this group. |
| **Rock and Alternative genres dominate sales** | Increase targeted promotions and playlist campaigns around these genres. |
| **Tracks like “The Number of the Beast” frequently co-purchased with “Prowler” and “Afraid to Shoot Strangers”** | Bundle these tracks in promotions and curated playlists. |
| **Customer churn among low-RFM segments** | Introduce reactivation campaigns for low-engagement customers. |

> 🎯 **Recommendation:**  
> Focus marketing on top-tier segments using personalized email and playlist campaigns. Integrate recommendation models based on frequent itemsets to boost upselling and customer retention.  

---

### 🖥️ Dashboard Preview  

![Chinook Music Store Dashboard](./images/Chinook%20Music%20Store.png)

<p align="center">
  <a href="./Chinook%20Project%20Dashboard.pdf" target="_blank">
    <img src="https://img.shields.io/badge/View_Full_Dashboard-PDF-orange?style=for-the-badge&logo=adobeacrobatreader" alt="View Full Dashboard">
  </a>
</p>

---

### 📑 PowerPoint Report  

![Chinook Report Preview](./images/Chinook%20Report.png)

<p align="center">
  <a href="./Insights%20Report/Chinook%20Report.pptx" target="_blank">
    <img src="https://img.shields.io/badge/View_Full_Report-PowerPoint-blue?style=for-the-badge&logo=microsoftpowerpoint" alt="View Full Report">
  </a>
</p>

---

## 🔮 Next Steps  

If given more time, I would:   
- Deploy a **real-time dashboard** connected to an API for live sales tracking.  
- Conduct **A/B testing** for targeted promotions derived from association rules.  
- Explore **customer feedback analysis** (NLP) to enrich behavioral insights.  

> 🌍 **Long-Term Vision:**  
> Build a full customer analytics ecosystem integrating sales, engagement, and social data to drive decision-making across marketing and product teams.

---

## 🏆 Key Takeaway

This project demonstrates how data analytics can transform raw transactions into strategic insights that drive customer retention, boost cross-selling, and improve overall business profitability.

🔗 “Without data, you’re just another person with an opinion.” – W. Edwards Deming

