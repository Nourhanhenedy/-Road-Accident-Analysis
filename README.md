**🚗 Road Accident Analysis Dashboard**



📌 Project Overview

This interactive Power BI dashboard provides a comprehensive analysis of road accidents in the UK.

The goal is to visualize casualty trends, identify high-risk road types, 

and compare current year (CY) performance against the previous year (PY) to drive data-driven safety improvements.

*****************************************************************************************




**📊 Key Performance Indicators (KPIs)**



The dashboard tracks 5 primary metrics for the Current Year (CY), all showing a positive downward trend:


Total Casualties: 195.7K (⬇️ 11.9% YoY)

Total Accidents: 144.4K (⬇️ 11.7% YoY)

Fatal Casualties: 2.9K (⬇️ 33.3% YoY)

Serious Casualties: 27.0K (⬇️ 16.2% YoY)


Slight Casualties: 165.8K (⬇️ 10.6% YoY)


*****************************************************************************************

**🔍 Data Insights & Findings**



**🚦 Road & Environmental Factors**

Road Type: Single Carriageways are the highest risk areas, accounting for 140K casualties.

Urban vs. Rural: 61.95% of accidents occur in Urban areas, indicating a need for better city traffic management.

Light Conditions: Surprisingly, 73.84% of accidents happen during Daylight, suggesting high traffic volume is a bigger factor than visibility.

**🚲 Vehicle Analysis**

Cars are involved in the vast majority of incidents (156K casualties).

Bikes and Vans follow equally with 16K casualties each.

**📅 Seasonal Trends**

Casualties show a significant peak in November, while the safest months are January and February.

The 2022 trend consistently remains lower than 2021, proving an overall improvement in road safety.

*****************************************************************************************


**🛠️ Technical Implementation (Power BI & DAX)**



To achieve these insights, I implemented several advanced measures and data modeling techniques:

**1. DAX Measures Created**


**Time Intelligence**: Used TOTALYTD and SAMEPERIODLASTYEAR to compare CY vs. PY metrics.

**YoY Growth**: Calculated the percentage difference between years to highlight safety improvements.

**Dynamic Titles**: Created measures to update chart titles based on user filtering.




**2. Data Transformation (Power Query)**


. Cleaned and formatted raw accident data.

. Created a custom Calendar Table for accurate time-series analysis.

. Grouped vehicle types and road conditions for better categorization.

************************************************************************************************

**📁 Repository Structure**

**Road_Accident_Analysis.pbix**: The main Power BI project file.

**Data/:** Folder containing the raw datasets (CSV/Excel).

**Screenshots/**: Images of the dashboard for quick preview.

****************************************************************************************************


**🚀 How to Use**



Clone the repository.

Open the .pbix file using Power BI Desktop.

Use the Road Surface and Weather Conditions slicers at the top to filter the entire report.

Would you like me to help you write the specific DAX code for the "YoY Growth" or "CY/PY" measures to include in the technical section?



************************************************************************************************

**🖥️ Dashboard Preview**



** 📊 Visualizing the Data**


Below is the interactive Road Accident Analysis Dashboard. 

It is divided into three main sections:

**Global KPIs**

**Casualty Trends**

 **Environmental Factors** (Weather, Road Type, and Light Conditions).




<img width="1334" height="740" alt="Power BI Desktop 3_12_2026 8_52_36 PM" src="https://github.com/user-attachments/assets/df8ecc8c-f365-4c99-8a15-cf2fb3fab4ce" />



