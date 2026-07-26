# User Login Behavior – OTT Streaming Analytics Case Study

This project analyzes user login and engagement behavior on an OTT (Over-the-Top) streaming platform using realistic synthetic data. It uncovers insights into churn, retention, technical performance, and promotional effectiveness through SQL and data visualization.

## Overview

- **Timeframe**: Jan 2025 – Mar 2026 (15 months)
- **Tools Used**:  
  - SQL (BigQuery)  
  - Google Looker Studio  
  - Google Sheets & Excel
  - Figma
  
- **Skills Applied**:  
  - Root Cause Analysis  
  - Window Functions & CTEs  
  - Cohort & Segmentation Analysis  
  - DAU/MAU, Churn & Retention Metrics  
  - Dashboarding & Storytelling

## Dataset

This is a synthetic dataset generated using generative AI for learning and portfolio purposes.

### Tables

- **Viewers**: signup date, country, age group  
- **Logins**: date, device type, login channel, session score  
- **Sessions**: timestamps, success/failure, duration  
- **Promotions**: promo types, dates, discounts

Dataset links:
- [viewers.csv](https://github.com/sachchidananddubey/OTT-ANALYSIS/blob/main/viewers.csv)
- [logins.csv](https://github.com/sachchidananddubey/OTT-ANALYSIS/blob/main/logins.csv)
- [sessions.csv](https://github.com/sachchidananddubey/OTT-ANALYSIS/blob/main/sessions.csv)
- [promotions.csv](https://github.com/sachchidananddubey/OTT-ANALYSIS/blob/main/promotions.csv)

## Key Use Cases

| Use Case |
|----------|
| Daily & Monthly Active Users (DAU/MAU Trends) 
| Detect Inactive Users |
| Weekly Engaged Users (3+ days/week) | 
| Avg. Session Duration by Region & Age | 
| Time from Signup to Last Login | 
| First Login Drop-off | 
| Login Channel vs. Retention | 
| Trial Users: Retention & Activity | 
| Promotion vs. Organic Viewer Sessions | 
| Signup Cohort Retention | 
| Viewer Churn by Country | 

Explore all queries [here](https://github.com/sachchidananddubey/OTT-ANALYSIS/tree/main/Queries)

## Dashboard & Visualizations

Built using Looker Studio:

- [Live Dashboard](https://lookerstudio.google.com/u/0/reporting/b142085d-ce40-470e-82ea-d555ca43d3f4/page/p_rc75fgeutd)
- [PDF Summary Report](https://github.com/sachchidananddubey/OTT-ANALYSIS/blob/main/OTT_User_Activity_-_Visualization.pdf)

Included:
- DAU & MAU Trends
- Viewer Distribution by Age, Country, Acquisition Type
- Promo Strategy vs Retention & Session Success
- Region-wise Engagement Patterns

