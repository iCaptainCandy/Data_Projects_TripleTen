# Sprint 5 – Storytelling with Data: Analyzing Superstore Returns

**Author:** Jaymeson Metz  
**Program:** TripleTen Business Intelligence Analytics  
**Sprint:** 5 – Storytelling with Data  
**Tools Used:** Tableau, Excel  
**Project Focus:** Identifying root causes of product returns and building a return-monitoring dashboard  

🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/jaymeson.metz/viz/metz_sprint5_project/Returnratebyproductcategory)

---

## 🧠 Project Overview

In this sprint, I worked as a data analyst for Superstore to uncover the root causes of customer returns. The CEO requested an actionable dashboard and story-based analysis to reduce return volume and improve business outcomes. The project included data cleaning, visualization design, dashboard creation, and presenting insights through a Tableau Story.

---

## 🔍 Part 1: What’s Causing Returns?

After LEFT JOINing the Returns table to the Orders table, I created a calculated `Returned` field (1 for "Yes", 0 for null). Using this field, I created the following visualizations:

1. **Scatterplot: Total Sales vs Total Returns by Subcategory**  
   - Not all high sales lead to high returns  
   - Phones and Chairs have high sales but low returns compared to Binders and Paper  
   - 📊 *"Correlation between total sales and total returns"*

2. **Return Rate by Product Category**  
   - 📊 *"Return rate by product category"*

3. **Return Rate by Customer**  
   - Filtered to customers with more than one order  
   - 📊 *"Return rate by customer"*

4. **Geographic Return Rate**  
   - Used state as dimension  
   - 📊 *"Return rate by state"*

5. **Seasonal Patterns in Returns**  
   - Analyzed by week  
   - 📊 *"Return rate by week"*

6. **Composite Return Rate Charts**  
   - Mixed multiple dimensions to find layered insights  
   - 📊 *"Return rate by customer and product category"*  
   - 📊 *"Return rate by state and week"*

---

## 🧰 Part 2: Dashboard Design & Mockups

- Sketched 3 dashboard layout mock-ups by hand
- Created a wireframe/template in Tableau using empty containers
- Built and finalized the dashboard using previously created worksheets
- Added titles, filters, and styling for executive readability

🖼️ Dashboard components include:
- Return trends over time
- Geographic return hotspots
- High-risk customers and products
- KPI metrics and filters for interactive deep-dives

---

## 🎯 Part 3: Storytelling & Presentation

- Constructed a clear Story arc across Story Points:
  - Summary of return metrics
  - Key causes of returns by category, region, customer
  - Dashboard walkthrough with filters and takeaways
  - Conclusion with recommended actions

- Delivered a **3–5 minute screencast presentation** summarizing findings
- Submitted a PDF export of the Story as well

---

## ✅ Review Outcome

> _“Jaymeson, hello!  
> The dashboard is brilliantly made and fully complies with the technical task.  
> The screencast is done perfectly—you make consistent conclusions from graph to graph and explain your logic.  
> The mockups are also well done.  
> You achieved outstanding results. All requirements are met. No critical comments.  
> You're really improving your skills from project to project, keep it up!”_  
> — **Dmitry Mikhalenko, Reviewer**

---

## 📚 Suggested Resources (from reviewer)

- **[Tableau Tips and Tricks](https://www.tableaufit.com/)**
- **[How to Select the Right Chart Type](https://www.tableau.com/learn/articles/chart-type)**

---

## 🚀 Skills Demonstrated

- Data storytelling via Tableau Story Points  
- Dashboard layout planning and execution  
- Exploratory analysis with JOINs and calculated fields  
- Visual correlation analysis  
- Filtering logic to identify root causes  
- Presenting insights in a professional, persuasive manner

---

## 📎 Files for GitHub Repo
