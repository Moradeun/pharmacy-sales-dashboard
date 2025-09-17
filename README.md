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
2. Derived new columns:
   - **Total Sales** = Quantity Dispensed × Unit Cost  
   - **Stock Value** = Quantity Remaining × Unit Cost  
   - **Days to Expiry** = Expiry Date – Today (0 for expired)  
   - **Expired Flag** = Valid or Expired  
   - **Purchase Price** estimated based on profit margins by category  
3. Created a **Calendar Table** for time-based analysis (Year, Month, Quarter)

---
