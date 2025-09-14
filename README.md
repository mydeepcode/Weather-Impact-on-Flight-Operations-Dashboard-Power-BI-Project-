# ✈️ Weather Impact on Flight Operations Dashboard (Power BI Project)

## 📌 Project Purpose

This project analyzes the effect of **weather conditions** on flight operations — including delays, cancellations, on-time performance, and passenger satisfaction. The dashboard gives airline operations teams a clear, data-driven view of how adverse weather impacts flight reliability and customer experience.

## 🛠️ Tech Stack

* **Power BI Desktop**
* **Power Query (M)** for data transformation
* **DAX (Data Analysis Expressions)** for KPI measures
* **Excel** as the raw data source
* **Custom Visual Formatting** for professional look & feel

## 📊 Data Source

* **Format:** .xlsx
* **Rows:** \~10,000 (Flight Records)
* **Columns:** 10+ (Flight Date, Weather Flag, Delay Minutes, Cancellation Status, Travel Class, Satisfaction Score, etc.)
* **Source:** Simulated airline operations dataset (weather & flight logs combined)

## ✨ Features & Highlights

### 🧩 5.1.1 Business Problem

Airline management wants to measure the operational and customer experience impact of **bad weather**. This includes:

* Flight delays
* Cancellations
* On-time performance
* No-show rates
* Passenger satisfaction drops

### 🎯 5.1.2 Dashboard Goals

* Track flight delays and cancellations over time
* Compare performance with/without weather impact
* Segment insights by travel class and travel purpose
* Support operational decision-making (e.g., rescheduling, crew planning)

### 📊 5.1.3 Key Visuals

**KPI Cards:**

* Total Flights (10K)
* Weather-Impacted Flights (1,507)
* Average Delay (10.26 min)
* On-Time Rate (77%)
* Weather-Related Cancellations (83)
* Weather Impact No-Show Rate (6%)

**Bar & Column Charts:**

* No-Show Count by Weather & Travel Purpose
* Satisfaction by Weather Condition

**Donut Chart:**

* Cancellation % during bad weather

**Line Chart:**

* Flight Delays Over Time (Weather vs No Weather)

**Slicers/Filters:**

* Travel Class (Business, Economy, First, Premium)

## 💼 5.1.4 Business Impact & Insights

* Bad weather leads to **23% higher delays** and a dip in satisfaction (7.0 → 6.8)
* Cancellations during bad weather = **5.3%**, a key cost driver
* No-show rate increases in weather-impacted conditions, especially for **leisure travelers**
* Travel class segmentation helps identify that **business travelers are most affected by delays**
* Insights allow better **proactive communication** to passengers and **crew scheduling**

## 🖼️ Screenshots / Demo

🔍 **Full Dashboard Preview**
Interactive Power BI dashboard with clean aviation-themed layout and monochrome + yellow highlights for weather impact.

🖼️ *Here is the link: View Full Dashboard Image
*

## 📎 Extras

* Dynamic DAX measures for On-Time Rate & Weather Delay Avg
* Clean, minimal white-themed layout with airplane visual centerpiece
* Conditional formatting for weather impact (yellow for clear weather, black for impacted)
* Drill-through filters for travel class segmentation
