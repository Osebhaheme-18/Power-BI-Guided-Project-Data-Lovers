# Power-BI-Guided-Project-Data-Lovers
![gettyimages-2177686437-612x612](https://github.com/user-attachments/assets/3afcdc94-6e42-4b01-a3ea-7ee486dea302)

Check out the final dashboard here:
-

# Business Problem 
The hotel management team lacked a centralized, data-driven view of business performance across regions and customer segments. Key metrics such as total bookings, revenue, cancellations, and customer behavior were scattered across multiple sources, making it difficult to identify trends or optimize decision-making.
This project aims to build an interactive Power BI dashboard that consolidates hotel data from 2018–2020, enabling stakeholders to monitor performance, analyze booking behavior, and uncover insights to reduce revenue loss and improve operational efficiency.
# Dataset Information
🧩 Dataset Details
Dataset: Hotel Management (2018–2020)
Source:  Provided sample dataset
Column                 Name	Description
- Booking_ID	         Unique booking identifier
- Hotel	               Hotel name or type (Resort, City Hotel, etc.)
- Country	             Guest’s country of origin
- Arrival_Date	       Guest arrival date
- Nights	             Number of nights stayed
- Revenue	             Revenue generated per booking
- Deposit_Type	       Booking deposit category (No Deposit, Non-refundable, Refundable)
- Customer_Type	       Transient, Group, Contract, or Transient-Party
- Booking_Status	     Whether the booking was canceled or completed
- Market_Segment	     Booking source (Online TA, Direct, Corporate, etc.)
# Project Objectives
To create a Power BI dashboard that visualizes hotel performance between 2018 and 2020, providing insights into bookings, revenue, cancellations, and customer behavior for better strategic decision-making.

This project enabled us to accomplish the following significant outcomes:
## Understand Business Objectives and User Requirements
We undertook a thorough analysis of the business problem to understand its objectives and requirements, pinpointing the main focus areas and formulating the key questions to be answered.
## Define Business Questions and Metrics
Following the analysis conducted in Step 1, we established a set of targeted business questions that the dashboard aims to resolve. Example questions include:
- Average Lead Time for Hotel Bookings
- Average Daily Rate (ADR) by Month (2018)
- What is the overall hotel performance in terms of total bookings, revenue, and revenue loss?
- How do weekday and weekend performances compare in terms of bookings and revenue?
- What are the patterns in booking behavior, such as lead time and deposit type and how they impact revenue?
## Identify the metrics and Key Performance Indicators (KPIs) that will provide insights to answer the defined business questions.
Examples of metrics
- Total Revenue
- Average Lead Time
- Total Bookings
- Revenue Loss
- Average Daily Stay
## Dataset preparation:
We cleaned the dataset by removing duplicates, fixing inconsistencies, and formatting it appropriately for analysis and visualization.
# Dataset before cleaning
<img width="983" height="593" alt="Screenshot 2025-11-13 at 1 13 54 PM" src="https://github.com/user-attachments/assets/96831e11-709e-4c70-93b4-6620881f2fea" />

# Dataset after cleaning


# Data Modeling
The key dimensions for breaking down the analysis were identified, and corresponding tables were created for each. These included:
- Locatiom Dim
- Hotel Dim
- Date Dim
- To improve analytical accuracy and insight, additional features were generated.
A Star Schema design was adopted, with all dimension tables connected to the fact table in a one-to-many configuration.

<img width="1086" height="591" alt="Screenshot 2025-11-13 at 1 51 39 PM" src="https://github.com/user-attachments/assets/04d5636f-ef6d-4741-b9a4-6d471cab6e78" />

## Design visualizations and charts: 
Relevant chart formats including bar, line, and pie charts were utilized to illustrate the metrics and insights. Interactive features, such as filters, drill-down options, and tooltips, were implemented to enhance data exploration.

<img width="1107" height="612" alt="Screenshot 2025-11-13 at 12 53 00 PM" src="https://github.com/user-attachments/assets/34a05dd9-872f-4722-a0b9-15ebd495cc31" />

## Dashboard Testing and Refinement
Students had the opportunity to schedule one-on-one sessions with an instructor throughout the project to receive feedback on their work and ensure alignment with the project requirements. Based on the feedback gathered during these sessions, students made necessary adjustments to their dashboard layout, visualizations, and insights to improve overall quality and effectiveness.
## Highlight Key Insights and Patterns:
Each student showcased the most significant insights and trends within their dashboard.
## Insights
- Europe contributes most bookings and revenue.
- High cancellation loss ($10.46M) signals a need for stricter policies or dynamic pricing.
- Summer months (especially August) are the strongest season for revenue.
- Transient travelers dominate — focus on loyalty programs for individuals.
- Online channels bring in most revenue — digital marketing remains critical.
## Recommendations
- Target off season promotions to balance revenue.
- Reduce refund flexibility or adjust deposit rules.
- Strengthen online partnerships and optimize OTA listings.
- Encourage direct bookings through incentives or loyalty benefits.
- Use lead-time data for forecasting and yield management.






