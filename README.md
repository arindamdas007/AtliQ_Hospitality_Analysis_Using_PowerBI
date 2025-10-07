# 🏨 AtliQ Hospitality Analysis using Power BI
An end-to-end Power BI project analyzing revenue performance for AtliQ Grands across Indian cities to uncover insights and optimize decision-making in the hospitality sector.

### 📘 Project Overview
This project is part of the **Codebasics Data Analytics Bootcamp**, created to deliver business insights for **AtliQ Grands**, a luxury hotel chain in India.  
The analysis uncovers trends in **revenue, occupancy, booking patterns, and guest experience**, helping the management team make data-driven decisions.

---

### ❗ Problem Statement
AtliQ Grands, a leading five-star hotel chain in India, is losing market share and revenue in the luxury/business segment due to strong competitor strategies and ineffective management decisions. To address this, the management seeks to adopt Business and Data Intelligence for informed decision-making, but currently lacks an in-house analytics team. In response to this challenge, the management decided to onboard external data analytics expertise to uncover actionable insights from historical booking and revenue data. The goal is to build a centralized dashboard that empowers the revenue team to identify performance gaps, optimize pricing strategies, and improve channel efficiency across properties. The **Revenue Management Team** needed a **centralized Power BI dashboard** to:
- Track KPIs like *Occupancy %, RevPAR, ADR,* and *Guest Ratings*.  
- Identify underperforming properties or booking channels.  
- Provide actionable insights for pricing and operational improvements.

---

### 🎯 Objectives
- Analyze AtliQ Grands' performance across major Indian cities.
- Understand revenue patterns, pricing structures, and booking channel performance.
- Evaluate occupancy, cancellations, and guest satisfaction trends.
- Recommend dynamic pricing strategies and operational improvements to boost profitability.

---

### ⚙️ Tools and Technologies
- **Power BI** – Dashboard design and visualization  
- **Excel / CSV** – Data source and cleaning  
- **DAX** – KPI calculations and dynamic measures  
- **GitHub** – Portfolio hosting and documentation  

---

### 🧱 Data ETL Process
1. **Extraction:** Imported raw `.csv` files containing booking, property, and room data.  
2. **Transformation:** Used Power Query for cleaning, merging, and removing unnecessary columns.  
3. **Modeling:** Established relationships using a **star schema** (Fact and Dimension tables).  
4. **DAX Measures:** Created calculated metrics like `Revenue`, `RevPAR`, `Occupancy %`, and `Cancellation Rate`.  
5. **Loading:** Applied cleaned and modeled data into Power BI for visualization.  

---

### 📊 Dashboard Views

#### 🌆 **City View**
- Compare city-wise performance for revenue, occupancy, and guest rating.  
- **Insight:** Mumbai generated the highest revenue, while Delhi had the best occupancy rate.

#### 💰 **Revenue View**
- Analyze revenue contribution by cities, room types, and booking channels.  
- **Insight:** Luxury and Elite rooms are top contributors; weekday optimization could boost RevPAR.

#### 📦 **Booking View**
- Examine booking channel distribution and cancellations.  
- **Insight:** Other Channels performed best, while OTA (online travel agency)channels faced higher cancellations.

#### 🧑‍💼 **Executive View**
- Consolidated KPIs and insights for management-level decisions.  
- **Insight:** Focus areas include guest satisfaction improvement and dynamic pricing adoption.

---

#### 📊 **Quantitative Insights**

- **Occupancy Rate**: Average occupancy across all hotels stood at 58.4%, with Delhi achieving the highest at 71% and Bangalore the lowest at 44.3%.
- **Average Daily Rate (ADR)**: The ADR remained flat around ₹12,000, indicating a lack of dynamic pricing across seasons and weekends.
- **Revenue Contribution**: Mumbai contributed nearly 35% of total revenue, leading all cities, while Hyderabad contributed the least.
- **Cancellation Rate**: Average cancellation rate was 24%, with OTA (Online Travel Agency) channels showing the highest cancellations.
- **Guest Ratings**: Properties with ratings above 4.0 stars maintained over 70% occupancy, whereas ratings below 3.0 saw drops below 50%, showing a clear positive correlation between ratings and occupancy.

---

#### 💡 **Key Outcomes**

- Identified need for **dynamic and weekend pricing** to boost revenue.
- Highlighted **Delhi** and **Mumbai* as top-performing cities; **Bangalore** underperformed.
- Found strong link between guest ratings and occupancy.
- Revealed **high cancellation** rates on OTA channels.
- Delivered an interactive Power BI dashboard for data-driven decisions.

---

### 📎 Deliverables
- [`Report/AtliQ_Hospitality_Analysis.pbix`](https://app.powerbi.com/view?r=eyJrIjoiYzcwNGNjMzItM2YwNC00ZjgwLTk4YjktMjVkZGIyM2QwZTVhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) – Power BI report file    
- `https://www.linkedin.com/posts/arindamdas007_codebasicsresumechallenge-powerbi-dataanalytics-activity-7379204953283645441-mBc0?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFK67-UBvAHcWbtIHdVOKSuddDxFCZteRoE` – Presentation deck  

---
