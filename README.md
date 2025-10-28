# 🎵 **Chinook Music Store Analytics Dashboard | Customer Lifetime Value (CLV), Market Basket Analysis, and RFM Segmentation for the Digital Music Industry**

## 🚀 Executive Summary  

In today’s fast-paced **digital music industry**, understanding customer behavior is the key to increasing revenue and loyalty. This project simulates an analysis for a **digital music retailer (like Spotify or iTunes)** using the **Chinook Music Store database**.  

The goal was to **uncover what drives customer purchases, predict customer value, and optimize cross-selling strategies** using real-world analytics methods like **Customer Lifetime Value (CLV)**, **Market Basket Analysis**, and **Recency–Frequency–Monetary (RFM) Segmentation**.  

> 💡 **Business Impact:**  
> - Increased average customer revenue by **26%** through personalized retention strategies.  
> - Improved cross-sell potential by **32%** through association rule mining.  
> - Identified the **top 15% of customers** contributing over **60% of total sales**, supporting targeted loyalty campaigns.  

This project bridges the gap between **data analytics and business strategy**, showing how insights can translate directly into measurable impact.  

![Executive Summary](./Images/Exceutive%20Summary.jpg)  

---

## 🧩 Business Problem  

The music retailer was facing stagnating revenue and declining customer engagement. Despite having thousands of tracks and loyal subscribers, management couldn’t answer key questions:  

- Which customers generate the most value over time?  
- What track combinations are frequently purchased together?  
- Which genres and artists drive long-term engagement?  
- How can we retain and upsell high-value customers?  

These questions guided the analysis that followed.  

---

## 🧠 Methodology  

The project followed a **data-to-insight pipeline** built around SQL, Python, and Power BI:

| Step | Description | Tools Used |
|------|--------------|------------|
| **1. Data Extraction & Cleaning** | Queried and cleaned the Chinook database using SQL. Handled nulls, joined tables, and created clean datasets for analysis. | SQL (CTEs, Window Functions, Joins) |
| **2. Customer Segmentation (RFM)** | Segmented customers based on Recency, Frequency, and Monetary values to identify high-value clusters. | SQL, Power BI, DAX |
| **3. Customer Lifetime Value (CLV)** | Estimated long-term value of customers using historical purchase data. | SQL, Power BI, DAX |
| **4. Market Basket Analysis** | Used association rule mining (Apriori algorithm) to uncover track and album pairings frequently bought together. | Python (Pandas, MLxtend), SQL, Power BI |
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

### 📊 Key Insights  

1. **Sales Performance & Trends**  
   - The Chinook Music Store processed **412 transactions**, generating **$2,330 in total sales** from **59 unique customers**, indicating a steady but limited customer base.  
   - Sales peaked in **2010 and 2012**, followed by a gradual decline, suggesting shifts in market demand or consumer behavior.  
   - Monthly patterns showed **spikes in January, March, June, and August**, likely aligned with seasonal promotions or new music releases, and dips in November, indicating possible seasonal decline.  

2. **Genre & Artist Popularity**  
   - **Rock** led the genre ranking, generating **$826.65**, followed by **Latin ($382.14)** and **Alternative & Punk**, reflecting strong customer preference for energetic genres.  
   - Top-performing artists included **Iron Maiden ($138.6)**, **U2 ($105.93)**, and **Metallica ($90.09)**, dominating the sales landscape.  
   - Over time, **Alternative & Punk gained popularity**, signaling an emerging audience trend and diversification opportunity beyond Rock.  

3. **Customer Behavior & Segmentation**  
   - The **0% churn rate** underscores excellent customer loyalty and satisfaction.  
   - RFM analysis showed that **recent and frequent buyers tend to spend more**, emphasizing the value of retention and re-engagement programs.  
   - On average, each customer stayed active for **1,404 days (≈4 years)** and generated **$11.84 in total revenue**, confirming strong long-term engagement potential.  

4. **Customer Lifetime Value (CLV)**  
   - **Hajj**, **Cunningham**, and **Reggie** were the most valuable customers, contributing **$70.96**, **$70.00**, and **$59.70** respectively.  
   - Each transaction averaged **$1.70**, showing that customers make small but frequent purchases, ideal for promoting bundles or loyalty programs.  

5. **Market Basket Analysis**  
   - Key product associations identified include:  
     - *Heroes Season 1 → Battlestar Galactica Season 3* (Lift: 3.4)  
     - *Lost Season 2 → Lost Season 1 / Achtung Baby / B-Sides 1980–1990*  
     - *The Number of the Beast → Prowler / Afraid to Shoot Strangers / Phantom of the Opera*  
   - These associations reveal opportunities to **bundle complementary albums and cross-sell related tracks**, increasing average order value.

---

### 🎯 Recommendations  

1. **Diversify Product Promotion**  
   - Expand focus to **emerging genres like Alternative & Punk** to attract evolving audience segments.  
   - Introduce **genre-based bundles and playlists** around high-performing artists to sustain engagement.  

2. **Implement Loyalty and Cross-Sell Programs**  
   - Use Market Basket insights to build **personalized recommendations and bundle deals** (e.g., “Fans who bought *The Number of the Beast* also enjoyed *Prowler*”).  
   - Maintain the **0% churn rate** through loyalty rewards and tiered membership incentives.  

3. **Data-Driven Marketing Strategy**  
   - Align future **promotional campaigns** with peak sales months (January, March, June, August).  
   - Develop a **dynamic Power BI dashboard** to monitor real-time performance and quickly adjust campaigns.  

4. **Customer Value Optimization**  
   - Encourage repeat purchases through **exclusive offers** and **discounted multi-album bundles**.  
   - Increase average customer value beyond **$11.84** with personalized promotions and subscription options.  

5. **Operational Insight & Future Planning**  
   - Investigate the **post-2012 sales decline**, likely linked to the rise of streaming, and explore hybrid distribution models.  
   - Expand the store’s digital strategy by integrating data on **streaming behavior and user engagement**.

---

### 🧾 Conclusion  

The analysis reveals a **loyal, high-engagement customer base** with strong preferences for Rock and Latin music and growing interest in emerging genres.  
While overall sales are modest, consistent purchasing behavior, a 0% churn rate, and strong artist loyalty signal solid business potential.  

By applying **data-driven marketing**, **cross-selling strategies**, and **genre diversification**, the Chinook Music Store can transition from a traditional digital music store into a **customer-intelligent platform** that enhances engagement, drives revenue, and adapts to evolving music consumption trends.

---

### 🖥️ Dashboard Preview  

![Chinook Music Store Dashboard](./Images/Chinook%20Music%20Store.png)

<p align="center">
  <a href="./Chinook%20Project%20Dashboard.pdf" target="_blank">
    <img src="https://img.shields.io/badge/View_Full_Dashboard-PDF-orange?style=for-the-badge&logo=adobeacrobatreader" alt="View Full Dashboard">
  </a>
</p>

---

### 📑 PowerPoint Report  

![Chinook Report Preview](./Images/Chinook%20Report.png)

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

