# Sprint 2 – SQL Analysis: Zuber Taxi Ride Data (Chicago)

**Author:** Jaymeson Metz  
**Program:** TripleTen Business Intelligence Analytics  
**Sprint:** 2 – Data Collection and Storage (SQL)  
**Tools Used:** SQL (TripleTen embedded environment)

---

## 🧠 Project Overview

In this project, I worked as a data analyst for **Zuber**, a fictional ride-sharing company entering the Chicago market. The goal was to explore patterns in public taxi data and determine how weather, company operations, and geography influenced ride frequency and duration.

The project was divided into two parts:
- **Part 1:** Analyze taxi companies’ performance and compare volume across various timeframes
- **Part 2:** Test a hypothesis about the effect of **weather** (specifically rain and storms) on **ride durations from the Loop to O’Hare Airport** on **Saturdays**

---

## 🧩 Data Tables Used

- `neighborhoods`: name, neighborhood_id  
- `cabs`: cab_id, company_name  
- `trips`: trip_id, cab_id, pickup/dropoff location, timestamps, duration  
- `weather_records`: timestamp, description of weather

---

## 🔍 Key Queries and Insights

### 🚕 Part 1: Taxi Company Performance
- Identified the **top-performing taxi companies** by trip count between Nov 15–16, 2017  
- Compared the performance of companies containing **“Yellow”** or **“Blue”** in their name during Nov 1–7, 2017  
- Grouped companies into **Flash Cab**, **Taxi Affiliation Services**, and **Other** to simplify analysis

### 🌧️ Part 2: Weather Impact on Ride Duration
- Mapped **weather conditions** to a “Good” vs “Bad” classification using `CASE` logic:
  - **Bad:** Descriptions with `"rain"` or `"storm"`
  - **Good:** All others
- Joined `weather_records` to `trips` using timestamps to estimate weather at ride time
- Filtered trips on **Saturdays** from **Loop (ID: 50)** to **O’Hare (ID: 63)**
- Retrieved only trips with **matching weather data** to measure duration impact

---

## 📸 Screenshots of SQL Queries (Passed Tasks)

Each of these queries was successfully submitted and passed:

1. Top companies by trip volume  
2. Companies with “Yellow” or “Blue”  
3. Grouping top companies vs others  
4. Identifying Loop & O’Hare neighborhood IDs  
5. Creating weather categories using `CASE`  
6. Merging trip data with weather conditions and filtering for analysis

*(See `/screenshots/` folder for SQL queries)*

---

## ✅ Review Outcome

> _All 6 tasks were passed successfully, and queries were approved by the system._  
> _This project demonstrated the ability to filter, join, group, and use `CASE` statements to manipulate and analyze real-world datasets._

---

## 🚀 Skills Demonstrated

- SQL joins across multiple tables  
- Grouping, filtering, and aggregation  
- Data classification using `CASE`  
- Real-world hypothesis testing with time-based JOINs  
- Writing reproducible queries to answer business questions

---

## 📂 Files (for GitHub Repo)
