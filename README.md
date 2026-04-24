# 📊 Power BI Dashboard Analysis of AtliQ Hardware

### ✅ Project Details:

- Client – AtliQ Hardware 
- Segment – Sales Domain

### 🔎Project Brief:

AtliQ Hardware is a global consumer electronics entity operating across five regions (APAC, EU, Latin America, NA). It is expanding globally, but not able to compete with other companies. Faced challenges in maintaining a "single version of truth" for its performance metrics.

### ✅ Problem statement:

-	Fragmented Data Visibility: Disparate data sources (manual Excel/CSV records) hindered real-time tracking of Net Sales, Gross Margin, and Net Profit.
-	Supply Chain Inefficiency: Lack of clear visibility into forecast accuracy led to significant operational risks, specifically Out of Stock (OOS) and Excess Inventory (EI) scenarios.
-	Profitability Leakage: Despite high revenue, the business needed to identify exactly where manufacturing, freight, and operational costs were impacting the bottom line.
  
So, the goal of this project is to implement an advanced analytics solution using Power BI that will enable the company to get insights and make informed decisions.

### Interactive Dashboard Link:
- [Click here to View](https://app.powerbi.com/view?r=eyJrIjoiMTEzMTRjNGEtNmVhOC00NzYyLWFmZTQtNjkwYjBiODAyNGQxIiwidCI6IjFlM2U2YmJlLTVkNzMtNGVhMS1iNDVlLTc0YzgzOThhNTM5OSJ9)

- [Click here to View](https://app.powerbi.com/view?r=eyJrIjoiMTEzMTRjNGEtNmVhOC00NzYyLWFmZTQtNjkwYjBiODAyNGQxIiwidCI6IjFlM2U2YmJlLTVkNzMtNGVhMS1iNDVlLTc0YzgzOThhNTM5OSJ9)

Once done, the report could be used by stakeholders from sales, marketing, finance, and the executive team. The focus is on the following:
- Robust Data Modeling
- User-empathetic Report design
- Drillable Insights

### ✅The Approach:

To address these challenges, as a ‘Data Analyst’ engineered a robust BI solution following an end-to-end analytical workflow:

-	**Data Integration & Modeling**: Extracted large-scale transactional data via MySQL Workbench and integrated it with dimension data Excel/CSV files.
-	**Multi-View Dashboarding**:
  Developed a layered reporting structure
1. **Executive View**: High-level KPIs including Net Sales ($823.85M), Gross Margin (36.49%), and Forecast Accuracy (80.21%).
2. **P&L Statement**: A detailed financial breakdown from Gross Sales to a Net Profit of -6.63%, allowing for granular cost-driver analysis.
4. **Performance Matrix**: Comparative analysis of markets and regions (e.g., India leading with 25.6% revenue contribution) against Gross Margin targets.
5. **Supply Chain Analytics**: Created a dedicated view to monitor Forecast Accuracy % and Net Error trends to mitigate inventory risks.
6. **Automated Monthly Refreshes**: Designed the report architecture to update system data monthly, ensuring stakeholders always have the latest historical and forecast insights.
   
### ⚡Project Execution Steps: 

1. Understanding the business acumen:
- Understanding business requirements and framing the right questions that will lead to better insight generation.
   
2. Discussion of Problem Statement & Solution design:
- Mock-up review discussion with stakeholders, so that the project aligns with their views and needs. Designing a dummy mock-up and further discussion with stakeholders.
   
3. Imported those CSV files to Power BI for further Transformation and analysis using Power Query Editor:
-	Import CSV files to Power BI & transform in Query Editor
-	Perform calculations, remove errors & null values.
-	Establish required relationship using Data Modelling (Snowflake Design method)

<img width="1027" height="732" alt="Relationship Diagram" src="https://github.com/user-attachments/assets/cb2800b6-c58b-4bcf-8567-9a6afbe6ea10" />


4.	Perform DAX Measures: 
-	Created calculated columns: Week no, Weekend Column
-	Created numerous DAX measures

5.	Build a dashboard from scratch using Bar charts, KPI indicators, Ribbon charts, and many more. Generated important KPIs and visualized the key performance indicators.

<img width="1316" height="732" alt="Finanve Vw" src="https://github.com/user-attachments/assets/211a8296-9011-4693-ae62-a60093803292" />

### ✅The Impact:

The implementation of this BI report delivered immediate strategic value:
-	Identified Growth Opportunities: Pinpointed the Accessories and Notebook segments as primary revenue drivers, contributing $244.85M and $266.49M in Net Sales, respectively.
-	Risk Mitigation: Classified customers and products by risk levels (OOS/EI), identifying that major customers like Amazon and AtliQ Exclusive were at "OOS" risk despite high forecast accuracy
-	Financial Optimization: Exposed a 207.43% year-over-year (YoY) change in P/L values, highlighting that while sales grew, operational expenses ($355.28M) required tighter control to flip the -6.63% Net Profit to positive.
-	Regional Strategy: Revealed that while NA (North America) had significant sales ($177.9M), it suffered a deep Net Profit loss of -13.67%, signalling a need for immediate regional cost restructuring.

<img width="1235" height="683" alt="Market Perf Quadrant" src="https://github.com/user-attachments/assets/785f92ee-ee61-41dd-9e51-ef7abb01645a" />

### 💡Key Learnings:

1.	Understanding Business Problems
2.	Data Understanding and Collection
3.	Power Query (Basic and Advanced Operations) 
4.	Data Exploration (EDA) & Data Transformation
5.	Data modelling involving 10+ tables
6.	Dashboard designing principles
7.	Building a dashboard and generating Insights using ‘Power BI.’
8.	Using bookmarks
9.	Deploying in Power BI service
10.	Stakeholder Feedback Implementation
11.	Sales, Marketing, Finance & Supply Chain metrics

### ⚡Some Important Insights from the Dashboard:

<img width="2752" height="1500" alt="Report Snapshot" src="https://github.com/user-attachments/assets/23e39179-9f4d-4f14-9569-3d36912b78c3" />


### ✅The Takeaway:

Through this project, I mastered several critical BI and technical competencies:

- Advanced DAX & Financial Modeling: Building a dynamic P&L statement that accurately reflects complex unit economics like GM/Unit ($5.99) and Total COGS (63.51% of sales)
- Strategic KPI Selection: Learning to balance conflicting KPIs, such as driving Sales Growth while maintaining Forecast Accuracy to protect margins.
- User-Centric Design: Implementing slicers for Region, Customer, and Segment to allow stakeholders to drill down from global trends to specific market performance.
- Supply Chain Logic: Understanding the direct correlation between Net Error in forecasting and its impact on customer satisfaction and inventory costs.

## Author & Contact:
👩‍💻 Author: Pragyan Saikia

📧 Email: [pragyan.saikia04@gmail.com

