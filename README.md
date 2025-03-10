# 🌟 Hotel Booking Data Analysis Report

## 1. Introduction
This report analyzes hotel booking data based on five provided datasets. The objective is to extract meaningful insights related to hotel performance, customer booking behavior, and revenue trends. The findings will help stakeholders make data-driven decisions to optimize hotel operations.

## 2. Data Overview
The datasets provided contain information about hotels, rooms, booking transactions, and aggregated booking trends:

- **dim_date**: Contains date-related attributes such as month, week number, and day type (Weekend/Weekday).
- **dim_hotels**: Provides details of hotels, including property ID, name, category (Luxury/Business), and city.
- **dim_rooms**: Describes room types (RT1-RT4) and their corresponding classes (Standard, Elite, Premium, Presidential).
- **fact_aggregated_bookings**: Summarizes room bookings at each hotel on a given date, including successful bookings and capacity.
- **fact_bookings**: Contains individual booking records with booking status, revenue details, and customer ratings.

## 3. Key Metrics
The following key performance metrics were used in the analysis:

- **Revenue**: Total revenue realized from bookings.
- **ADR (Average Daily Rate)**: Average revenue generated per room sold.
- **RevPAR (Revenue Per Available Room)**: Average revenue generated per available room, whether or not they are occupied.
- **DBRN (Daily Booked Room Nights)**: Average number of rooms booked per day over the given period.
- **DSRN (Daily Sellable Room Nights)**: Average number of rooms ready for sale per day.
- **DURN (Daily Utilized Room Nights)**: Average number of rooms actually utilized by customers per day.
- **Occupancy %**: Percentage of rooms occupied compared to the total capacity.
- **Cancellation %**: Percentage of bookings that were canceled.
- **Realization %**: Percentage of successful check-outs from total bookings.

## 4. Data Model
![Data Model](https://github.com/Aarush250/Hospitality-Project/raw/main/Data%20Model.png)

## 5. Overall Analysis View
![Overall Analysis View](https://github.com/Aarush250/Hospitality-Project/raw/main/Overall%20Analysis%20View.png)

## 6. Key Insights

### 6.1 Revenue Analysis
- Mumbai generates the highest revenue among all cities at ₹661 million.
- AtliQ Exotica contributes an impressive ₹316 million, while AtliQ Seasons records the lowest revenue at ₹65 million.
- Delhi, despite having the highest average customer rating, recorded the lowest revenue at ₹291 million.
- The Luxury category surpasses the Business category in revenue generation, with a revenue ratio of 62:38, highlighting its superior market performance.
- Weekdays generate the highest revenue, totaling ₹1.16 billion.
- Elite and Premium rooms contribute the most revenue among all room types.
- The Average Daily Rate (ADR) remains stable with minimal fluctuations, indicating consistent pricing strategies by hotels.

### 6.2 Occupancy & Capacity Trends
- AtliQ properties in Delhi exhibit a notably high occupancy rate compared to other locations.
- Delhi leads in both occupancy and customer rating, despite generating lower revenue.

### 6.3 Customer Behavior Analysis
- Other travel platforms are the primary booking source, accounting for 40% of total bookings and generating ₹690 million in revenue.
- Direct offline booking contributes the least, accounting for only 5% of total bookings and revenue.
- MakeYourTrip ranks second among all booking platforms, contributing 20% of total bookings and ₹341 million in revenue.
- The Elite room category generates the most revenue, whereas Standard rooms underperform.
- AtliQ Exotica and AtliQ Palace are the top revenue contributors, making up 18.75% and 17.80% of total revenue, respectively. Both hotels maintain strong average ratings of 3.6 and 3.7, showcasing their excellent performance.

## 7. Recommendations
- **Luxury hotels generate higher revenue but experience higher cancellation rates.** Implementing stricter cancellation policies could improve revenue realization.
- **Peak booking periods occur during weekends and specific months (May & July).** Hotels should implement dynamic pricing strategies to maximize revenue during these high-demand periods.
- **Online booking platforms dominate the market.** Investing in digital marketing and incentivizing direct bookings can reduce dependency on third-party platforms.
- **Customer ratings highlight service gaps.** Analyzing customer feedback can help improve service quality and enhance customer retention.
- **Standard rooms underperform.** Targeted marketing campaigns and special promotions could improve their occupancy and revenue.
- **Bengaluru has strong revenue but the lowest average rating.** Enhancing customer experience through staff training, facility upgrades, and customer feedback collection is recommended.
- **Delhi records the lowest revenue but the highest occupancy and rating.** Given the high customer satisfaction and demand, consider expanding hotel properties in Delhi.
- **Hyderabad shows the second-lowest revenue and the lowest RevPAR.** Selling or leasing underperforming properties in Hyderabad can help raise capital for expansion in higher-demand cities like Delhi.
- **Business hotels generate less revenue than luxury hotels despite similar ratings.** Enhancing guest experiences, upgrading amenities, and implementing better marketing strategies can attract higher-paying guests.
- **Presidential rooms show high occupancy but lower revenue.** Reassess pricing strategies and enhance customer experiences to increase profitability.
- **Cancellation rates are high (25%) for bookings made through MakeYourTrip.** Implementing a simple feedback form for canceled bookings can help identify and address underlying issues.
