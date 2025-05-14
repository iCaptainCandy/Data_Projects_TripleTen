# Sprint 6 – Shopify App Review Analysis (Power BI)

**Author:** Jaymeson Metz  
**Program:** TripleTen Business Intelligence Analytics  
**Sprint:** 6 – Power BI  
**Tools Used:** Power BI Desktop, DAX  

---

## 🧠 Project Overview

In this project, I analyzed data scraped from the Shopify App Store to understand what contributes to an app’s success, based on public ratings, developer responsiveness, and user engagement. The goal was to create an organized, insight-rich Power BI report that explores relationships between reviews, developers, responsiveness, and helpfulness scores.

The project is structured into **three main sections**, each reflected in its own Power BI report tab.

---

## 🔹 Part 1: App Landscape

### 1.1 Unique Apps KPI  
- ✅ Counted 7,341 unique apps in the dataset  
📸 *Screenshot:* `1.1 - UNIQUE APPS KPI CARD.jpeg`

### 1.2 Review Count Over Time  
- ✅ Line chart shows review volume decline and periodic spikes  
📸 *Screenshot:* `1.2 - REVIEWS OVER TIME.jpeg`

### 1.3 Reviews Count vs. Rating  
- ✅ Scatterplot identifies app clusters and outliers with strong product-market fit  
📸 *Screenshot:* `1.3 - REVIEWS COUNT VS. RATING.jpeg`

---

## 🔹 Part 2: Reviews (Weighted Metrics & Developer Responses)

### 2.1 Helpful Review Score  
- ✅ Calculated `helpful_reviews = rating * (1 + helpful_count)`  
- 📈 Average Helpful Review Score: 5.48  
📸 *Screenshot:* `2.1 – HELPFUL REVIEWS KPI CARD.jpeg`

### 2.2 Developer Answered vs. Rating  
- ✅ Created a binary field `developer_answered`  
- ✅ Scatterplot of average ratings shows little variation by response  
📸 *Screenshot:* `2.2 - DEV ANSWERED VS. AVG RATING.jpeg`

---

## 🔹 Part 3: App Reviews & Developer Impact

### 3.1 Sum of Ratings by Developer  
- ✅ Created relationship between `reviews.app_id` and `apps.id`  
- ✅ Bar chart shows top developers by cumulative review score  
📸 *Screenshot:* `3.1 - RATINGS BY DEVELOPER.jpeg`

### 3.2 Avg. Helpful Review Score by Developer  
- ✅ Used new metric to identify most appreciated developers  
📸 *Screenshot:* `3.2 - AVG HELPFUL REVIEW SCORE BY DEVELOPER.jpeg`

### 3.3 Developer Responsiveness  
- ✅ Filtered for developers with >500 reviews  
- ✅ Visualized average response rates  
📸 *Screenshot:* `3.3 - DEVELOPER RESPONSIVENESS.jpeg`

---

## ✅ Review Outcome

> _“Hi, Jaymeson!  
> I am happy to review your project today—there are many things that I like.  
> **Part 1:** Indicator card, line chart, and scatter plot—well done.  
> **Part 2:** Great visualizations.  
> **Part 3:** Very informative bar plots.  
> In general: super project. All visualizations are informative and easy to read.  
> There are no critical comments, and I am happy to say your project is accepted!”_  
> — **Ekaterina Terentyeva, Reviewer**

---

## 🚀 Skills Demonstrated

- Power BI dashboard creation  
- DAX expressions for calculated columns  
- KPI card configuration  
- Data model relationships  
- Custom visual annotations  
- Multi-page report structuring for storytelling  

---

## 📁 GitHub Folder Structure

/Sprint_6_PowerBI_Shopify/
├── README.md
├── 1.1 - UNIQUE APPS KPI CARD.jpeg
├── 1.2 - REVIEWS OVER TIME.jpeg
├── 1.3 - REVIEWS COUNT VS. RATING.jpeg
├── 2.1 – HELPFUL REVIEWS KPI CARD.jpeg
├── 2.2 - DEV ANSWERED VS. AVG RATING.jpeg
├── 3.1 - RATINGS BY DEVELOPER.jpeg
├── 3.2 - AVG HELPFUL REVIEW SCORE BY DEVELOPER.jpeg
└── 3.3 - DEVELOPER RESPONSIVENESS.jpeg
