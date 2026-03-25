# Swiggy Web Traffic & Conversion Analysis

## Project Background

Swiggy, one of India’s largest online food delivery platforms, operates in a highly competitive digital environment where user experience and conversion rates are critical to revenue growth. Despite strong web and app traffic, the platform faces relatively low conversion rates, indicating inefficiencies in user engagement and marketing effectiveness.

This project analyzes Swiggy’s web traffic data to understand user behavior, identify drop-off points, and evaluate marketing campaign performance. The objective is to uncover actionable insights to improve conversion rates and optimize digital strategy.

---

## Goal as a Data Analyst

The goal of this project is to build an interactive **Tableau dashboard** that enables stakeholders to:

- Monitor key web performance metrics (traffic, engagement, conversions)  
- Analyze user behavior across segments and channels  
- Identify underperforming areas in the conversion funnel  
- Support data-driven decision-making to improve conversion rates  

---

## Insights and recommendations are provided on the following key areas:

- **Campaign Performance Analysis:** Evaluation of marketing campaigns and their impact on conversion rates.  

- **Regional Performance (Maharashtra Focus):** Analysis of traffic contribution and conversion performance across key regions.  

- **User & Device Segmentation:** Assessment of conversion behavior across user types and device categories.  

- **Temporal & Channel Trends:** Analysis of conversion patterns across days and traffic channels.  

---

## Data Structure

The dataset contains detailed web traffic data, where each row represents a user session.

| Column Name              | Data Type   | Description                                                                 |
|--------------------------|------------|-----------------------------------------------------------------------------|
| Date                     | DATE       | Date of the session, used for trend analysis                                |
| Traffic_Source           | VARCHAR    | Source of traffic (Direct, Paid, Organic, etc.)                             |
| Visitor_Type             | VARCHAR    | New or Returning visitor                                                    |
| Device_Type              | VARCHAR    | Device used (Mobile, Desktop)                                               |
| Browser_Type             | VARCHAR    | Browser used to access the platform                                         |
| Operating_System         | VARCHAR    | OS of the user device                                                       |
| Page_Views               | FLOAT      | Average number of pages viewed per session                                  |
| Sessions                 | INT        | Total number of sessions                                                    |
| Bounce                   | INT        | Indicator of whether the user dropped off without interaction               |
| Avg_Session_Duration     | FLOAT      | Average time spent per session                                              |
| Conversion               | VARCHAR    | Indicates if a session resulted in a transaction (Yes/No)                   |

---

## Project Resources

- **Tableau Dashboard:** [View Dashboard](https://public.tableau.com/app/profile/shashwat.sungh/viz/Swiggy_DB/Dashboard1?publish=yes)  
- **Tableau Workbook:** [Download Tableau Workbook](dashboard/Swiggy_DB.twbx)  
- **Project Dataset (CSV):** [Download CSV](data/tableau-milestone-data.csv)  
---

