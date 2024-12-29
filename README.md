# 🏨 AtliQ Grands Hotel Business Intelligence Dashboard

## 📊 Power BI Project: Data-Driven Insights for AtliQ Grands  
**Project Overview:**  
AtliQ Grands, a luxury five-star hotel chain across India, is facing declining market share and revenue. This project leverages **Power BI** to provide actionable insights into their operational and financial performance. By analyzing historical booking data, we identify critical metrics (RevPar, OCC%, ADR) to optimize revenue strategies and improve occupancy rates.  

---

## 🚀 Project Workflow:  
1. **Data Acquisition:**  
   - Load booking and hotel data directly from source folders using Power BI’s "Get Data" feature.  

2. **Data Transformation (Power Query):**  
   - Clean and transform raw data (renaming columns, correcting weekend classifications, handling null values).  
   - Establish a **Star Schema** for optimized performance and clear relationships.  

3. **Data Modeling & DAX (Data Analysis Expressions):**  
   - Develop calculated columns and key performance measures (RevPar, OCC%, ADR, DSRN).  
   - Use DAX for custom metrics, weekday/weekend classifications, and cumulative calculations.  

4. **Dashboard Design:**  
   - Visualize key hotel performance metrics through an interactive dashboard based on stakeholder mock-ups.  
   - Incorporate filters for weekday/weekend insights, city-level comparisons, and dynamic date ranges.  

5. **Insight Generation:**  
   - Perform **Root Cause Analysis (RCA)** through level analysis.  
   - Address key business questions such as:   
     1. Why is revenue declining?  
     2. Which cities/hotels contribute most to the revenue dip?  
     3. What pricing and occupancy patterns emerge across weekdays and weekends?  

---

## 📈 Key Metrics:  
- **RevPar (Revenue Per Available Room):** `total_revenue / total_rooms_available_to_sell`  
- **OCC% (Occupancy Rate):** `total_rooms_occupied / total_rooms_available`  
- **ADR (Average Daily Rate):** `total_rooms_revenue / number_of_rooms_sold`  
- **DSRN (Daily Sellable Room Night):** Available rooms per night basis  

---

## 🔍 Findings & Recommendations:  
- **Pricing Strategy:** Lack of dynamic pricing reduces potential weekend revenue. Introduce promotions on direct channels to drive bookings.  
- **Channel Optimization:** Direct offline bookings outperform direct online bookings, indicating underutilized online channels.  
- **Revenue Gaps:** Key cities (e.g., Bangalore) underperform due to suboptimal room pricing and occupancy fluctuations.  

---

## 📂 Files and Documentation:  
- 📄 **Power BI Dashboard (.pbix)** – Interactive dashboard reflecting AtliQ Grands’ performance.  
- 📊 **DAX Scripts** – Collection of custom DAX queries for metric calculation.  
- 📘 **Project Report** – Detailed analysis and stakeholder recommendations.  

---

## 🛠️ Tools & Technologies:  
- **Power BI**  
- **Power Query**  
- **DAX (Data Analysis Expressions)**  
- **SQL (Optional for data extraction/preprocessing)**  

---

## 🔗 How to Run:  
1. Download the `.pbix` file and open it in Power BI Desktop.  
2. Connect to the provided dataset or replace it with your hotel booking data.  
3. Refresh data, ensuring folder paths are correctly mapped.  
4. Interact with filters to explore performance by city, date, and booking channels.  

---

## 💡 Next Steps:  
- Automate data refresh for real-time insights.  
- Integrate more granular datasets (e.g., customer feedback, regional trends).  
- Build predictive models to forecast occupancy and revenue.  

---  
**Feel free to contribute, report issues, or suggest improvements!**  
✨ *Let’s help AtliQ Grands regain their market position through data intelligence.*
