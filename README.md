# Airport-Analytics-Dashboard
# ✈️ Airport Delay & Passenger Analytics Dashboard

An interactive Business Intelligence dashboard developed using Power BI to analyze airport operations, airline performance, flight delays, and passenger traffic across international airports.

---

# 📌 Project Overview

This project provides a complete analytical solution for monitoring aviation operations using interactive dashboards and advanced data visualizations.

The dashboard combines Flights, Airports, and Airlines datasets to generate meaningful operational insights and support data-driven decision-making.

The analysis focuses on:
- Flight delay monitoring
- Passenger traffic analysis
- Airport performance evaluation
- Airline operational efficiency
- Domestic vs International flight comparison

---

# 📂 Datasets Used

## 1️⃣ Flights Dataset
Contains detailed flight operation records including:
- Flight ID
- Airline ID
- Airport ID
- Flight Type
- Delay Duration
- Passenger Count
- Flight Date
- Delay Category

---

## 2️⃣ Airports Dataset
Contains airport-related information such as:
- Airport Name
- Country
- Airport Code
- Airport Traffic Statistics

---

## 3️⃣ Airlines Dataset
Contains airline operational data including:
- Airline Name
- Airline Code
- Country
- Airline Type

### Sample Airlines Data

| Airline_ID | Airline_Name | Country | Airline_Type |
|---|---|---|---|
| AL001 | EgyptAir | Egypt | Full Service |
| AL002 | Emirates | UAE | Full Service |
| AL003 | British Airways | UK | Full Service |
| AL004 | American Airlines | USA | Full Service |
| AL005 | Air France | France | Full Service |
| AL006 | Turkish Airlines | Turkey | Full Service |
| AL007 | Lufthansa | Germany | Full Service |
| AL008 | Qatar Airways | Qatar | Premium |
| AL009 | Singapore Airlines | Singapore | Premium |
| AL010 | Delta Airlines | USA | Full Service |

---

# 🔗 Data Modeling

The project uses relational data modeling inside Power BI to connect:
- Flights table
- Airports table
- Airlines table

### Relationships
- Flights[Airline_ID] → Airlines[Airline_ID]
- Flights[Airport_ID] → Airports[Airport_ID]

These relationships enable:
- Cross filtering
- Interactive analysis
- Dynamic KPI calculations
- Drill-down reporting

---

# 📊 Dashboard Features

## ✈️ Flight Delay Analysis
- Analyze delays by category:
  - Long Delay
  - Medium Delay
  - Short Delay
  - No Delay
- Measure average delay duration.
- Identify airlines and airports with the highest delays.
- Track operational bottlenecks.

---

## 🛫 Airport Performance Analysis
- Compare airport traffic and operational activity.
- Rank airports based on flight volume.
- Monitor airport efficiency and passenger handling.

---

## 👥 Passenger Trend Analysis
- Visualize monthly passenger movement trends.
- Detect peak travel seasons.
- Analyze yearly passenger distribution.

---

## 🌍 Domestic vs International Flights
- Compare international and domestic flight operations.
- Analyze traffic percentages by flight type.
- Evaluate operational distribution.

---

# 📈 Key Performance Indicators (KPIs)

The dashboard includes important KPIs such as:
- Total Flights
- Total Passengers
- Delay Percentage
- Average Delay Duration
- Airport Rankings
- Airline Performance Metrics

---

# 🔍 Interactive Filters

Users can dynamically filter dashboard insights using:
- Country
- Airport Name
- Airline
- Month
- Flight Type

---

# 📷 Dashboard Pages

## 1️⃣ Airport Overview Dashboard
Provides:
- Total flights overview
- Passenger statistics
- Delay summaries
- Airport rankings

---

## 2️⃣ Delay Analysis Dashboard
Focuses on:
- Delay categories
- Delay trends
- Airline delay comparison
- Airport delay distribution

---

## 3️⃣ Passenger & Traffic Dashboard
Displays:
- Passenger trends
- Airport traffic analysis
- Flight type comparison
- Monthly travel patterns

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Business Intelligence Analytics

---

# 🎯 Project Objectives

- Improve visibility into airport operations.
- Identify delay patterns and inefficiencies.
- Support operational optimization.
- Deliver interactive business intelligence reporting.
- Generate actionable insights from aviation datasets.

---

# 🚀 Skills Demonstrated

This project demonstrates practical skills in:
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Dashboard Design
- KPI Development
- Business Intelligence
- Data Storytelling
- Interactive Reporting

---

# 📌 Insights Generated

- Identification of airports with the highest delays.
- Passenger movement trends across months.
- Airline operational performance comparison.
- Delay distribution across airports and airlines.
- Domestic vs International traffic analysis.

---

# 📈 Conclusion

This dashboard transforms raw aviation datasets into actionable insights through interactive visualizations and analytical reporting.

The project demonstrates how Power BI can be used to monitor airport performance, analyze airline operations, and support data-driven decision-making in the aviation industry.
