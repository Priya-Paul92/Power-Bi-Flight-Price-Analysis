✈️ Airline Price Analysis Dashboard (Power BI)
📌 Project Overview

This project analyzes airline ticket pricing patterns using multiple factors such as airlines, booking window, travel class (Economy vs Business), routes, time of travel, number of stops, and flight duration.
The objective of this dashboard is to help stakeholders understand price behavior, demand concentration, and operational patterns, enabling better pricing and marketing decisions.

🎯 Business Questions Addressed

The dashboard answers the following key questions:
1.Does ticket price vary across different airlines?
2.How does ticket price change when flights are booked closer to the departure date?
3.How do departure time and arrival time together impact ticket prices?
4.How does ticket price vary across different source and destination routes?
5.How does pricing differ between Economy and Business class?
6.How does the number of stops affect average ticket price?
7.How does pricing vary across duration of flights ?


📊 Dashboards Created

The project consists of three interactive Power BI dashboards:

🔹 Dashboard 1: Overview & Pricing Summary

Key KPIs:

Average Ticket Price
Average Economy Price
Average Business Price
Average Flight Duration
Average Price per Hour
Total Flights
Airline-wise price comparison
Economy vs Business price comparison

Donut chart showing Avg Price by Number of Stops

🔹 Dashboard 2: Time & Booking Behavior Analysis

Line chart showing price trends based on Days Left before departure

Heat map showing ticket price variation by Departure Time vs Arrival Time

Price volatility analysis across booking windows

🔹 Dashboard 3: Route & Demand Analysis

Decomposition Tree for:

Source → Destination → Class → Airline


⚙️ Features & Functionality

Global Top-N Parameter to dynamically control visuals across all dashboards

Interactive slicers for:

Airline
Class (Economy / Business)
Source City
Destination City
Departure Time
Arrival Time
Reusable DAX measures for consistent calculations
Clean, professional layout with optimized visual formatting

🧮 Key DAX Measures Used

1.Average Ticket Price
2.Average Economy Price
3.Average Business Price
4.Average Flight Duration
5.Average Price per Hour
6.Total Flights


📈 Key Insights

1.Business class tickets are consistently priced higher, even for similar flight durations.
2.Ticket prices increase significantly when booking closer to the departure date.
3.Certain departure–arrival time combinations show consistently higher prices.

Non-stop flights generally have higher average prices compared to multi-stop flights.
