# Sprint 3 – Business Analytics: Conversion Funnel & Retention Analysis

**Author:** Jaymeson Metz  
**Program:** TripleTen Business Intelligence Analytics  
**Sprint:** 3 – Business Analytics  
**Tools Used:** Google Sheets / Excel  

---

## 🧠 Project Overview

In this sprint, I was hired as a junior analyst for an e-commerce company to transform raw transactional logs into meaningful business insights. The dataset included user-level event activity such as product views, cart openings, and purchases.

My objective was to:
- Build a **conversion funnel** to assess user flow from product view to purchase
- Prepare **cohort analysis data** to measure customer retention by acquisition month
- Calculate **retention rates** across monthly cohorts
- Organize and document the spreadsheet for executive-level review

---

## 📊 Funnel Analysis

### Goal: Understand how effectively users convert through the website

**Stages of the funnel:**
1. Product Page Views  
2. Cart Opens  
3. Purchases  

- Built a pivot table (`conversion_funnel` tab) using unique user counts
- Calculated total and step-by-step conversion rates
- Found opportunities to improve the conversion from cart to purchase

---

## 📈 Cohort Analysis & Retention

### Goal: Track customer retention by acquisition month

- Filtered **only purchase events** into a `purchase_activity` sheet  
- Calculated each user’s **first purchase date** via pivot table (`first_purchase`)
- Created 3 helper columns in `purchase_activity`:
  - `event_month` (when purchase occurred)
  - `first_purchase_month` (acquisition cohort)
  - `cohort_age` (months since acquisition)

- Aggregated user count per cohort and age group in `cohort_analysis`
- Used fixed formulas in `retention_rates` tab to calculate retention % over months 1–4

---

## 🧾 Executive Summary & Structure

- Used a clearly structured **Table of Contents**
- Wrote summaries for:
  - Results of the funnel and retention analysis
  - Key assumptions (event logic, cohort definitions, user count usage)
- Reordered tabs and added formatting for executive readability

---

## ✅ Review Outcome

> _"Hello, Jaymeson!  
> Your project is beautifully designed, you answered the questions of the terms of reference in a great way.  
> You once again did a very good job and I see your skills in analytics!  
> I note that Excel is one of the most basic analytics tools, and it is very important to be able to use it.  
> Thank you for your work and I wish you success in your next projects! 😊"_  
> — **Dmitry Mikhalenko, Reviewer**

---

## 🎓 Suggested Resources (from reviewer)

- Advanced Excel Formulas  
- Hints & Tips for formatting  
- YouTube: [Excel Lessons](https://www.youtube.com/results?search_query=advanced+excel+formulas)

---

## 📎 Project File

📄 [View Final Spreadsheet (Google Sheets)](https://docs.google.com/spreadsheets/d/1vIcHrRRT171h68s4nufXufT53Dg1lMcy9Tice6E_oos/edit?usp=sharing)

---

## 🚀 Skills Demonstrated

- Spreadsheet logic: `VLOOKUP()`, `TEXT()`, `DATEDIF()`, relative/fixed references  
- Funnel construction and conversion metric calculation  
- Retention cohort modeling  
- Executive-level data storytelling and spreadsheet design  
- Project documentation and sheet organization
