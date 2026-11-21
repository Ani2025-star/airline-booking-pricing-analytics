# airline-booking-pricing-analytics
Project Overview
This project analyzes airline ticket pricing and booking patterns using Power BI. The objective is to identify the factors influencing airfare, customer booking behavior, and flight operations performance.

The dashboard was developed using a Snowflake Schema data model and includes interactive visualizations for pricing analysis, booking intelligence, and operational insights.

Tools Used
Excel
Power BI
DAX
Data Modeling (Snowflake Schema)
Dataset Features
The dataset contains over 30,000 airline booking records with the following attributes:

Airline
Flight
Source City
Destination City
Departure Time
Arrival Time
Stops
Travel Class
Duration
Days Left Before Departure
Ticket Price
Data Model
A Snowflake Schema was implemented consisting of:

Fact Table
Flight Fact Table
Dimension Tables
Airline Dimension
Route Dimension
Departure Time Dimension
Arrival Time Dimension
Stops Dimension
Class Dimension


Dashboard Pages

1. Project Overview
Dataset summary
KPI metrics
Project objectives

2. Executive Overview
Average Price by Airline
Average Price by Class
Average Price by Stops
Average Price by Departure Time

4. Booking Intelligence
Booking Window vs Average Price
Days Left vs Average Price
Booking Window vs Total Flights
Class vs Booking Window

5. Flight Operations Analysis
Airline vs Average Duration
Departure Time vs Average Price
Stops vs Average Duration
Departure Time vs Total Flights

6. Insights & Recommendations
Key findings
Business recommendations


Key Findings

- Vistara has the highest average airfare.
- Air Asia offers the lowest average fares.
- Business Class tickets are approximately 8x more expensive than Economy Class tickets.
- Early Booking provides the lowest average ticket prices.
- Last-Minute bookings have the highest average ticket prices.
- Night departures have the highest average fares.
- Flights with two or more stops have the longest travel durations.

Business Recommendations
- Book flights at least 30 days before departure.
- Consider budget airlines for price-sensitive travel.
- Choose late-night departures for lower average fares.
- Compare one-stop flights to reduce travel costs.

Dashboard Screenshots
Executive Overview
<img width="1281" height="712" alt="DashBoard_1" src="https://github.com/user-attachments/assets/7a854885-b488-47cb-af30-12248013615d" />

Booking Intelligence
<img width="1307" height="711" alt="DashBoard_2" src="https://github.com/user-attachments/assets/73096d8a-2b0f-45d3-9c9e-0d1bd585fa09" />

Flight Operations Analysis
<img width="1295" height="712" alt="DashBoard_3" src="https://github.com/user-attachments/assets/981c91e9-70cc-4ad3-918f-50999edb591a" />

Insights & Recommendations
<img width="1297" height="727" alt="KEY INSIGHTS AND RECOMMADATIONS" src="https://github.com/user-attachments/assets/0e569e13-ddfd-401a-92ff-b09c232e4365" />

Author
Aniket



