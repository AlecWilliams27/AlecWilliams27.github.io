---
layout: single
title: "Saving SuperStore Visualization"
date: 2025-10-08 12:20:00 +0000
categories: [dashboards]
tags: [tripleten, education, dashboard]
highlight_home: true
header:
  caption: "Photo by Oscar Ramirez on Unsplash"
  teaser: "https://plus.unsplash.com/premium_photo-1742516057603-cf93e8d4b6c6?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
  overlay_image: "https://plus.unsplash.com/premium_photo-1742516057603-cf93e8d4b6c6?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
excerpt: "Tableau analysis that pinpoints SuperStore’s profit centers, loss drivers, ad ROI, and return risks, with clear recommendations to restore profitability."
---

# 📌 Project Overview
Welcome to my Data Visualization project! In this case study, I acted as a consultant for a struggling SuperStore that was on the brink of bankruptcy. My task was to analyze operations, uncover profit and loss drivers, and make recommendations that could help the store return to profitability.
I used a structured rubric to guide my work and ensure that I demonstrated mastery of visualization techniques and business storytelling.

Check out the dashboard here: [https://public.tableau.com/app/profile/alec.williams2101/viz/DataVisualizationProjectComplete/SuperStoreDashboard]

## 🎯 Objectives
The project was divided into three key parts:

### Part 1: Profits & Losses
* Identified the two biggest profit centers and two biggest loss-makers using visualizations.
* Determined which products the superstore should stop selling based on profitability analysis.
* Highlighted three product subcategories to focus on and three subcategories to discontinue.

### Part 2: Advertising
* Evaluated if advertising investments would be worthwhile.
* Identified the 3 best combinations of states and months for advertising by visualizing average monthly profits.
* Calculated how much the store should be willing to pay for advertising based on a return on ad spend ratio (spending up to 1/5 of profits).

### Part 3: Returned Items
* Used the Returns table, LEFT JOINED onto the Orders table, to analyze product returns.
* Created a calculated field for returns (Yes = 1, Null = 0).
* Built visualizations to answer:
Which products have the highest return rate?
Which customers have the highest return rate?
* Compared average profit vs. average return rate across dimensions (state, shipping mode, product type) to identify whether the superstore should continue or stop doing business under certain conditions.

## 🛠️ Tools & Techniques
* Data Sources: Orders and Returns tables
* Joins: LEFT JOIN (Orders + Returns)
* Data Cleaning: Created calculated fields for return indicators
* Visualizations: Profit/loss analysis, product performance charts, advertising ROI visuals, retention/return rate dashboards
* Key Formulas:
Conversion of returns → IFNULL([Returned],0)
ROI on advertising → Profit × 20%

## 📂 Deliverables
* Visualizations highlighting profit centers and loss-makers
* Product- and subcategory-level recommendations
* Advertising ROI analysis by state + month
* Return rate dashboards for products and customers
* Profit vs. Return Rate analysis with clear recommendations

## 💡 Business Insights
* Identified products and subcategories that drain profitability and should be discontinued.
* Highlighted top-performing categories that the store should double down on.
* Provided a data-backed advertising strategy targeting specific states and months for maximum ROI.
* Flagged customers and products with abnormal return rates that could hurt long-term profitability.

### ✨ This project demonstrates my ability to use data visualization to uncover actionable insights, tell a compelling business story, and provide clear recommendations for executives.
What did you build and why does it matter?

## Tech & Tools
- Tableau


## Links
<p class="btn-group">
  <a class="btn btn--primary" href="https://public.tableau.com/app/profile/alec.williams2101/viz/DataVisualizationProjectComplete/SuperStoreDashboard" target="_blank" rel="noopener">
    <i class="fas fa-chart-line" aria-hidden="true"></i> View Live Dashboard
  </a>
</p>
