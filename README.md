# PowerBI Visualization and Dashboard Mini_Project_1 

 Business Objective: Incorporate real time diagnostics of plant operational process to better manage available production lines and increase profit margin
 Analytics Objective: Build an analytics dashboard to track plant's operational process i.e., downtime minutes, total machine utilization time, etc.
 
Create a visualization dashboard to track important KPIs of the plant's operational process 
1. Calculate the below listed KPIs(measures) using DAX 
Machine Utilization - (ProductionFBE – Scrap FBE) / ProductionFBE Theoretical
Right first time - (ProductionFBE – ScrapFBE – ReworkFBE) / ProductionFBE
Scrap rate - Scrap rate_ScrapFBE / ProductionFBE 
Rework rate - REwork rate_ReworkFBE / ProductionFBE 
Downtime minutes Production pieces_(ProductionFBE – Scrap FBE) / ProductionFBE Theoretical
Downtime minutes - Sum of downtime value (in secs)
Production pieces - Count of total items produced

2. Create charts to track the overall trend of the above calculated metrics over the given time period. Also, create a KPI card highlighting the overall values for each KPIs across the given time period in the data
 
3. Create list of filters at top of the dashboard to filter for the above designed metrics tracker
I. Line ID
II. Team ID
III. Date

4. Bonus Question: Is there a correlation between (i) total production and scrap pieces produced, (ii) total production and rework pieces? What is the magnitude of correlation?
  

• Use Power Query and DAX to merge various data sets together
• Create new columns/ calculated field in Power BI using pre-existing columns and formulae
• Create charts to analyze data i.e., scatter plot, line chart, KPIs, etc.
• Adding images, filters, scroll bars in the dashboard to make dynamic visualizations
