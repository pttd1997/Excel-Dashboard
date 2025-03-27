# 📊 Monthly Call Center Dashboard – Personal Project 

## Project Objective 

Based on my hands-on experience working in a call center, I came up with the idea to create a dashboard for monthly reporting. This dashboard is designed for team leaders, supervisors, and higher-level managers to get a clear overview of monthly key performance metrics, such as total calls by channel (Call-Center, Chatbot, Email, Web), average customer satisfaction score (CSAT), and average call duration. 

The goal is to present the performance and identify underperforming areas in agent performance to provide insights into which KPIs are being met successfully and which ones require more focus and improvement. 

This tool also contributes to building a smarter, more efficient analysis process — optimizing reporting and enhancing operational performance moving forward. 

## Dataset
- <a href= "https://github.com/pttd1997/Excel-Dashboard/blob/main/Call%20Center%20Dashboard.xlsx">Dataset</a>

## Questions (KPIs) 

🔹 1. Call Volume & Channel Distribution 

How many calls were handled this month in total? 

How is the total call volume distributed across channels (Call Center, Chatbot, Email, Web)? 


Which channel had the highest usage? 

🔹 2. Customer Satisfaction (CSAT) & Sentiment 

What is the average customer satisfaction score this month? 

How does customer sentiment (Very Positive → Very Negative) distribute across different call centers? 

Which call centers or channels receive more negative feedback? 

🔹 3. Call Duration 

What is the average call duration this month? 

Are certain call centers or channels experiencing longer calls? 

🔹 4. Service Level Agreement (SLA) & Response Time 

How many calls were handled within SLA timeframes? 

Which call centers are struggling to meet SLA? 

🔹 5. Call Reason Analysis 

What are the top reasons customers are calling? 

Are there recurring issues (e.g., billing, service outage)? 

Which reasons are associated with lower CSAT or longer call durations? 

🔹 6. Daily Trends 

How does call volume change over the days of the month? 

Are there any peak periods or unusual spikes? 

🔹 7. Geographic Insights 

From which states or cities are most calls coming? 

Are certain regions more likely to use specific channels? 

- Dashboard Interaction <a href="https://github.com/pttd1997/Excel-Dashboard/blob/main/Dashboard.png">View Dashboard</a>

## Process 

- Verified the dataset for missing values and anomalies and resolved any inconsistencies to ensure data reliability. 

- Cleaned and standardized the data, ensuring consistency in: Data types, Date/time formats, Value categories 

- Reformatted the Call Timestamp column into proper Date format for easier analysis and filtering. 

- Created PivotTables based on predefined key performance questions, focusing on: Call volume, Channel distribution, Sentiment and CSAT analysis, SLA response time, Call reasons and trends 

- Visualization: Visual charts (bars, donuts, line chart, and map); Key KPI cards; Slicers for date, call center, channel, and reason — enabling dynamic exploration.

## Dashboard 

<img width="969" alt="Untitled 7" src="https://github.com/user-attachments/assets/2b2c3228-2a00-4949-92bc-33883917b9b9" />

<img width="969" alt="Untitled 8" src="https://github.com/user-attachments/assets/7c1f150a-b01a-4070-b442-190c42b546a5" />

## Dashboard Insights 

- Call-Center remains the most used channel, handling 32% of total calls, followed by Chatbot (25%), Email (23%), and Web (20%). 
- The total number of calls handled in October was 32,941, with an average CSAT score of 5.55 and an average call duration of 25.02 minutes. 
- Most calls were resolved within SLA, accounting for over 60% of total interactions. 
- Negative and Neutral sentiments dominate customer feedback, with Negative sentiment (11,063 calls) being the highest, followed by Neutral (8,754). 
- The top 3 reasons customers reached out were: Billing Questions (~23,462 calls); Payments; Service Outages;
- Los Angeles/CA and Baltimore/MD are among the highest-volume call centers.
- Daily trends show relatively stable call volume throughout the month, with a small drop toward the end.
- Geographic distribution shows high call volumes from states like California, Texas, and New York.
  
## 📈 Final Conclusion 

To improve overall customer service performance, attention should be given to reducing the volume of negatively rated interactions, especially related to billing issues. Training agents to handle these topics more effectively and streamlining billing-related processes could help improve satisfaction. 

Additionally, deeper investigation into why sentiment is skewing negative or neutral is needed, especially in high-volume locations like Los Angeles and Baltimore. Targeted efforts such as quality monitoring, sentiment-based agent coaching, and workflow optimization may help improve resolution quality and customer experience. 
