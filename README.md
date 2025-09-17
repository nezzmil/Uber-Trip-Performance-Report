# 🚖 Uber Trip Performance Report 

![Overview Analysis](/Images/Overview%20Analysis.png)

## 📌 Project Overview  
This project analyzes **Uber trip data** to uncover insights into customer booking behavior, vehicle preferences, payment trends, and ride performance.  
Using **Power BI**, I created an interactive dashboard that visualizes key metrics across time, location, and vehicle types.  

The dashboard provides a **data-driven perspective on mobility patterns**, enabling stakeholders to identify revenue drivers, optimize resource allocation, and improve operational efficiency.  

---

## 🎯 Objectives  
- Analyze **total bookings, trip distance, and booking value**.  
- Compare **day vs night trip distributions**.  
- Evaluate **vehicle type performance** based on revenue, distance, and bookings.  
- Identify **frequent pickup & drop-off points**.  
- Study **payment method preferences**.  
- Visualize **time-based demand trends** by hour and weekday.  

---

## 📊 Key Insights  
- **Total Bookings**: 103.7K rides worth **$1.6M revenue**.  
- **Average Trip**: 3 miles, 16 minutes, $15 value.  
- **Vehicle Popularity**: UberX leads with 38K+ bookings, followed by Uber Comfort and Uber Black.  
- **Payment Trends**: Uber Pay is the most used, while Cash and Amazon Pay are less preferred.  
- **Day vs Night Trips**: 65% of bookings happen in the **daytime** vs 35% at **night**.  
- **Hotspot Locations**:  
  - Pickup → **Penn Station / Madison Sq West**  
  - Dropoff → **Upper East Side North**  
- **Peak Demand Hours**: 7 AM – 10 AM and 5 PM – 8 PM.  

---

## ⏰ Time Analysis  

![Time Analysis](/Images/Time%20Analysis.png)
- **Total Bookings**: 103.7K | **Total Value**: $1.6M | **Avg Trip**: 3 miles / 16 min / $15  
- **Hourly Trends**:  
  - Demand peaks at **7–10 AM** (office commute) & **5–8 PM** (evening return).  
  - Lowest rides occur at **1–5 AM**.  
- **Day of Week Trends**:  
  - **Fridays & Saturdays** → highest demand.  
  - **Tuesdays & Wednesdays** → lowest demand.  
- **Combined Patterns**:  
  - Weekday mornings show strong peaks.  
  - Evenings are busy across both weekdays & weekends.  
  - Saturdays have the largest evening spikes (leisure/social trips).  

---

## 📑 Details Page  

![Details](/Images/Details.png)

The **Details Page** provides a **transaction-level drill-down** of the Uber trip dataset.  
Unlike the summary dashboards, this page shows each ride with all related attributes, allowing deeper exploration and validation.  

### 🔹 Columns Displayed  
- **Trip ID** → Unique ride identifier  
- **Pickup Date & Time** → Exact start time of the trip  
- **Vehicle Type** → UberX, Uber Comfort, UberXL, Uber Green, Uber Black  
- **Payment Type** → Uber Pay, Cash, Amazon Pay, Google Pay  
- **Number of Passengers** → Passenger count per ride  
- **Trip Distance** → Distance covered (in miles)  
- **Booking Value** → Fare earned per trip (USD)  
- **Pickup & Drop-off Location** → Starting and ending points  
- **Total Booking** → Aggregated ride count  

### 🔹 Purpose  
- Ensures **data granularity and traceability**  
- Allows filtering and slicing by **date, vehicle, payment method, or location**  
- Validates summary KPIs against raw data  
- Detects **outliers** such as longest trips, high-value rides, or unusual patterns  

### 🔹 Business Use Cases  
- **Operations** → Investigate complaints or anomalies at the ride level  
- **Finance** → Validate revenue and payment method reconciliation  
- **Customer Insights** → Study booking preferences at a granular level  
- **Strategy** → Identify location clusters and demand for long-distance rides  

✅ The **Details Page** acts as the **raw trip ledger** supporting all higher-level insights, enabling **in-depth analysis and decision-making**.  

---

## 🛠️ Tools & Technologies  
- **Data Visualization**: Power BI  
- **Data Source**: Uber trip details and Location Table  
- **Techniques Used**:  
  - DAX calculations  
  - Data modeling & transformation  
  - Time intelligence functions  
  - Interactive slicers & filters  

---

## 📂 Dashboard Features  
1. **Overview Analysis** – KPIs (bookings, revenue, avg trip metrics).  
2. **Vehicle Type Analysis** – Bookings, distance, and revenue split.  
3. **Location Analysis** – Pickup/drop-off hotspots.  
4. **Time Analysis** – Hourly, daily, and weekday trends.  
5. **Payment Method Analysis** – Uber Pay, Cash, Amazon Pay, Google Pay.  
6. **Detailed Trip Records** – Passenger count, distance, and fare details.  

---

## 🚀 Business Impact  
- Identifies **high-demand areas & peak times**.  
- Provides insights into **preferred vehicle types & payment methods**.  
- Assists in **strategic planning for driver allocation**.  
- Enables **data-driven decision-making** for growth and efficiency.  

---

## 📌 Conclusion  
This project demonstrates how **Power BI dashboards can transform raw ride data into actionable insights**.  
It highlights passenger trends, revenue opportunities, and operational challenges, helping businesses like Uber to **enhance service quality and profitability**.  

---
