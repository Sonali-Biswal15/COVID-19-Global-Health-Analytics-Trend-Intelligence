# COVID-19-Global-Health-Analytics-Trend-Intelligence
An interactive Business Intelligence platform engineered in Power BI to analyze pandemic severity and mortality trends across 100,000+ rows of global health data.

**🚀 Project Overview**
This project transforms raw global health data into actionable insights. The core objective was to correlate infection volumes with mortality rates using a 2% Case Fatality Rate (CFR) Risk Threshold to identify periods of critical healthcare strain.

**🛠️ Technical Stack**
--BI Tool: Power BI Desktop
--ETL Engine: Power Query (Data Cleaning & Transformation)
--Language: DAX (Data Analysis Expressions) for complex measures
--Data Modeling: Star Schema (Relational Modeling)

**🧠 Key Features & Analytical Logic**
--Relational Data Modeling: Established 1-to-many relationships between a Fact table and a custom Calendar Dimension to enable seamless Time-Intelligence reporting.
--Advanced DAX Measures: Developed custom calculations for:
--Case Fatality Rate (CFR): Dynamic percentage calculation reflecting pandemic severity.
--Trend Correlation: Dual-axis analysis comparing infection spikes against death counts.
--Exception Reporting: Utilized Top-N Filtering to isolate the 5 highest-risk geographical regions by mortality rate.
--Risk Benchmarking: Integrated an analytical Risk Threshold at 2%, providing a visual "Danger Zone" for health officials to monitor.

**📈 Business/Health Insights**
--Identified an inverse correlation between infection peaks and fatality rates as healthcare protocols matured.
--Visualized geographical "hotspots" using Geospatial Mapping, allowing for regional-specific data drills.
--Automated historical trend forecasting using Year-over-Year (YoY) and Month-over-Month (MoM) comparisons.

