**State-level Agriculture Census — Crop Analysis**

**Dataset: State-level agriculture census (India) — crop area, irrigated/unirrigated area, holdings (2011 & 2016).**

**Project Overview**


This project analyzes state-level agricultural census data to:


  Understand factors affecting crop yields and cultivated area.
  
  Identify high-performing and underperforming states and crops.
  
  Produce descriptive, diagnostic, predictive, and prescriptive insights to inform agricultural planning and policy. 

**Data Source**

  Source: Indian Data Portal / Ministry of Agriculture & Farmers Welfare (dataset provided in project files).
  
  Time Period: 2011 and 2016 (two census snapshots). 

**Tools & Technologies**

  Excel (Power Query) — data cleaning & transformations.
  
  Power BI — interactive dashboard and visualizations.
  
  (Optional) Python / Jupyter — EDA, forecasting & reproducible scripts.

**Data Preprocessing**

**Performed using Excel / Power Query:**

  Removed duplicates and invalid rows.
  
  Handled missing values and standardized formats.
  
  Created calculated fields (e.g., irrigated % = Irrigation Area / Total Area).
  
  Built pivot tables for initial summaries. 


**Analysis Performed**

**Descriptive — **
total areas by state and crop; top states by cultivated area (Uttar Pradesh, Rajasthan, etc.). 



**Diagnostic **

identify crops/states with increasing/decreasing area; analyze irrigated vs. unirrigated area. 



**Predictive**

simple forecasts on cultivated area trends (observed decline in some regions). 



**Prescriptive**

maps and KPIs highlighting regions needing intervention (irrigation, diversification)

**Dashboard (Power BI)**

  Visual types: bar charts, line charts (time series), pie charts, cards, tables, and geo-map bubbles.
  
  Key KPIs: Total cultivated area, top crops by area, irrigated vs. unirrigated share, state comparison

**Main Findings / Insights (summary)**

  Total cultivated area across states: ~447.51M (as reported in the project).
  
  Uttar Pradesh and Rajasthan are among the largest agricultural states by area.
  
  Regions with better irrigation infrastructure show higher productivity and larger cropped areas.
  
  Some states show declining cultivated area trends; forecasts predict further decrease in certain regions, indicating need for better land and water management.

**Conclusion**

The agricultural census dataset provides comprehensive insights into India’s crop production patterns across states and farm size categories. Analysis of irrigated and unirrigated areas reveals significant disparities between regions—states with better irrigation infrastructure consistently report higher productivity and larger cropped areas. Major crops such as paddy, wheat, maize, and pulses dominate total cultivated area, reflecting India’s staple food preferences.

State-level comparisons indicate that regions like Uttar Pradesh, Maharashtra, Madhya Pradesh, and Punjab contribute a substantial portion of the country’s total cultivated land. Coastal and northeastern states show smaller agricultural footprints but exhibit diverse crop types.

In summary, the dataset underscores the importance of irrigation infrastructure, landholding size, and crop diversification in shaping agricultural outcomes across India. These insights can guide policymakers in designing more targeted agricultural and irrigation development programs to improve productivity and sustainability.
