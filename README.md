# Campaign Performance Analytics Dashboard

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17sYyNRvUyj_FlaQpkbim0z67v4CjuJxE?usp=sharing)

This project builds an **interactive analytics dashboard** for exploring marketing campaign performance.

The goal of the dashboard is to help marketing teams analyze campaign effectiveness and generate **data-driven insights** for improving marketing strategy.

The dashboard allows users to explore campaign performance across:

- Marketing channels
- Campaign objectives
- Customer segments
- Time periods
- Campaign uplift metrics

---

# Project Overview

Marketing campaigns generate large volumes of data, but extracting meaningful insights from this data can be challenging.

This dashboard provides a **comprehensive analytical environment** that allows users to explore campaign performance using interactive filters, visualizations, and KPI metrics.

Using this tool, analysts can:

- identify high performing campaigns
- detect weak marketing channels
- analyze customer segments
- understand campaign timing patterns
- generate strategic recommendations

---

# Dashboard Components

## 1. Channel Filter

This dropdown allows users to analyze campaigns from a specific marketing channel.

Examples:

- Email  
- Social  
- Display  

**Purpose**

Helps identify which channels produce the strongest marketing impact and where marketing investment should increase.

---

## 2. Objective Filter

Campaigns can be filtered by their marketing objective.

Objectives include:

- Acquisition
- Retention
- Cross-sell
- Reactivation

**Purpose**

Allows comparison of different marketing strategies and determines which objective generates the best results.

---

## 3. Segment Filter

Campaigns can be analyzed based on the target customer segment.

Segments include:

- New Customers
- Deal Seekers
- Churn Risk

**Purpose**

Helps identify which customer groups respond most strongly to marketing campaigns.

---

## 4. Minimum Uplift Slider

Allows users to filter campaigns based on minimum uplift value.

**Purpose**

Helps isolate high-performing campaigns and remove lower-impact campaigns from analysis.

---

## 5. Date Range Selector

Users can restrict analysis to campaigns within a specific time period.

**Purpose**

Helps identify:

- seasonal marketing trends
- campaign timing patterns
- periods of high marketing activity

---

# Dashboard Visualizations

## Campaigns by Objective (Bar Chart)

Shows the number of campaigns for each objective.

**Insight**

Helps understand the marketing strategy focus.

Example interpretation:

If **Retention campaigns dominate**, the company is prioritizing engagement with existing customers.

---

## Expected Uplift Distribution (Histogram)

Shows how campaign uplift values are distributed.

**Insight**

Reveals whether campaign performance is consistent or widely spread.

Example interpretation:

Most campaigns show **moderate uplift**, while a few campaigns produce very high performance.

---

## KPI Summary

The dashboard calculates key campaign metrics:

- Total campaigns
- Average uplift
- Average campaign duration
- Maximum uplift
- Minimum uplift

Example interpretation:

Campaigns lasted about **31 days on average** and generated roughly **9.4% uplift**, indicating moderate but stable performance.

---

## Campaign Timeline (Gantt Chart)

Visualizes campaign activity across time.

Axes:

- X-axis → timeline
- Y-axis → marketing channel
- Color → campaign objective

**Insights**

- overlapping campaigns
- seasonal campaign activity
- marketing intensity periods

Example interpretation:

Social campaigns appear more frequently during **Q3**, while Display campaigns appear earlier in the year.

---

## Correlation Heatmap

Displays relationships between campaign variables.

**Example Insight**

Expected uplift shows **weak correlation with campaign duration**, suggesting longer campaigns do not necessarily produce better results.

---

# Customer Segment Insights

### New Customers

Campaigns focused on acquiring first-time users.

Typical strategies:

- welcome discounts
- signup bonuses
- introductory promotions

Example campaign:

“20% off for new subscribers”

---

### Deal Seekers

Customers who respond strongly to discounts and promotions.

Typical behavior:

- wait for sales
- use coupons
- compare prices

Example campaign:

“Exclusive limited-time 50% sale”

---

### Churn Risk Customers

Customers who previously engaged but are becoming inactive.

Indicators:

- declining purchase frequency
- inactivity periods
- low engagement

Example campaign:

“We miss you — come back and get 30% off”

---

# Key Insights from the Data

Analysis of the campaign dataset reveals several important observations:

- Retention campaigns appear frequently, indicating a strong focus on customer engagement.
- Campaign uplift values are mostly moderate with some high-performing campaigns.
- Campaign duration does not strongly influence uplift.
- Customer segmentation plays an important role in campaign effectiveness.

---

# Strategic Recommendations

Based on the analysis, the following recommendations can improve campaign performance:

- Increase investment in campaigns with high uplift.
- Focus marketing resources on the most effective channels.
- Extend campaign duration when short campaigns show weak performance.
- Leverage email marketing where engagement is strong.
- Use targeted marketing strategies for high-value customer segments.

---

# Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Jupyter Notebook  
- ipywidgets  

---

# Project Structure
campaign-performance-analytics-dashboard
│
├── notebooks
│ ├── campaign_analytics_dashboard.ipynb
│ └── campaign_dashboard_results.ipynb
│
├── data
│
├── images
│
├── results
│
├── presentation
│
└── README.md

---

# Author

**Sreekar Regulavalasa**

Data Analytics | Campaign Analytics | Python
