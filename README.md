# pharmacy-sales-dashboard

## 📌 Project Overview
Managing sales and inventory in a **community pharmacy** involves daily challenges:  
- Preventing **drug expiry losses**  
- Maintaining the right **stock levels**  
- Monitoring **sales and profitability**  
- Understanding **patient purchasing patterns**  

As a pharmacist, I often faced these issues firsthand. To address them, I built this Power BI dashboard to convert pharmacy data into actionable insights. The dashboard enables better decision-making, optimized stock management, and improved financial performance.


## 🎯 Problem Statement
Community pharmacies often rely on manual record-keeping or basic reporting, which makes it difficult to:
- Track **which drugs sell the most**  
- Identify **near-expiry products** that may cause financial loss  
- Monitor **profit margins across drug categories**  
- Understand **patient behavior and visit frequency**  

This project solves these challenges by creating a **centralized analytical dashboard** for pharmacy operations.

## 🔄 Data Preparation (Power Query)
Data was cleaned and enriched in **Power Query**:
1. Removed duplicates and null values
2. Key DAX measures built:
- **Total Sales** = SUM(Pharmacy[Total Sales])  
- **Total Profit** = SUM(Pharmacy[Profit])  
- **Quantity Dispensed** = SUM(Pharmacy[Quantity Dispensed])  
- **Unique Patients** = DISTINCTCOUNT(Pharmacy[Patient ID])  
- **Average Sales per Patient** = [Total Sales] ÷ [Unique Patients]  
4. Created a **Calendar Table** for time-based analysis (Year, Month, Quarter)


## 📸 Dashboard Preview
![Dashboard Screenshot](./Dashboard/pharmacy_dashboard.png)


## 📈 Insights & Findings
- **Antibiotics & Antihypertensives** drive the highest sales and profit margins  
- **Analgesics** contribute high sales volume but lower profitability due to low margins  
- **Stock nearing expiry** poses significant financial risks if not addressed in time  
- **Sales peaks** were observed in specific months, reflecting seasonal demand patterns  
- **Patient trends** show repeat purchases, indicating opportunities for loyalty programs  

---

## 📝 Recommendations
1. **Expiry Management** – Run promotions for near-expiry drugs to minimize waste  
2. **Stock Reordering** – Use stock value trends to avoid stock-outs or overstocking  
3. **Profit Maximization** – Focus on high-margin categories like antibiotics  
4. **Patient Retention** – Create loyalty programs based on unique patient tracking  
5. **Operational Reporting** – Adopt dashboards in day-to-day pharmacy operations  



## 🎯 Real-Life Application
This dashboard directly applies to **pharmacy operations management**:
- **Sales Monitoring** → Track daily, monthly, and yearly sales and profit
- **Inventory Control** → Monitor stock levels, stock value, and prevent stock-outs
- **Expiry Management** → Identify drugs nearing expiry to reduce waste and losses
- **Profitability Analysis** → Focus on high-margin categories such as antibiotics and antihypertensives
- **Patient Insights** → Understand patient purchasing trends to improve service delivery
---


## 📈 Business Impact
- 📉 **Reduced Expiry Losses** – by tracking drugs close to expiry and enabling timely clearance  
- 📦 **Optimized Inventory** – ensured stock availability while reducing overstocking  
- 💰 **Improved Profit Margins** – highlighted high-performing categories for focus  
- 👩‍⚕️ **Better Patient Care** – tracked unique patients and their purchase patterns for service improvement  
- 📊 **Data-Driven Decisions** – simplified reporting for faster managerial decisions  

## ✅ Conclusion
This project demonstrates how **data analytics can transform pharmacy management**.  
By using **Power BI**, I created a tool that:  
- Improves **inventory tracking**  
- Reduces **financial losses from expiries**  
- Optimizes **profitability by category**  
- Enhances **patient service delivery**  
- Supports **evidence-based decision-making** 
