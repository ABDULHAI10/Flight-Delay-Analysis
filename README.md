✈️ Airline Flight Delay Analysis Power BI Dashboard

📘 Overview
This Power BI project visualizes flight delay patterns across major U.S. airlines. It provides insights into average delays, cancellation rates, delay reasons, and passenger impact using DAX-driven KPIs and interactive visuals.

📊 Key Features
📈 Average Delay by Airline: Compare delay performance across different airlines.
🧭 Delay Trends Over Time: Identify months or days with frequent flight delays.
🧩 Delay Reasons Breakdown: Analyze how weather, crew, and technical issues affect operations.
📍 Flights by Airport: Map visual showing flight activity across major U.S. airports.
📋 Detailed Flight Table: Interactive table summarizing delay details, destinations, and ticket prices.

🧮 DAX Measures Used
Avg Delay (min) = AVERAGE(Airline_Flight_Delay_Analysis[Delay_Minutes])
Total Flights = COUNTROWS(Airline_Flight_Delay_Analysis)
Cancelled Flights = CALCULATE(COUNTROWS(Airline_Flight_Delay_Analysis), Airline_Flight_Delay_Analysis[Cancelled] = "Yes")
Delay Percentage = DIVIDE(Delayed, Total, 0)
Avg Ticket Price ($) = AVERAGE(Airline_Flight_Delay_Analysis[Ticket_Price_USD])

🖼️ Dashboard Preview
The dashboard highlights overall flight performance metrics using an interactive design:
KPI cards (Total Flights, Cancellations, Avg Delay, etc.)
Bar chart comparing airlines
Pie chart showing delay reasons
Time-series chart tracking delay trends
Table view for in-depth analysis

🧠 Insights
Some airlines experience higher average delays due to technical and crew-related reasons.
Weather and air traffic significantly influence delays during specific months.
Airports with higher flight volumes often show a proportional increase in delays.

🧰 Tools & Technologies
Power BI Desktop
Microsoft DAX (Data Analysis Expressions)
CSV Dataset (Synthetic / Sample Data)

💡 Future Enhancements
Predictive modeling for delay forecasting using Power BI
Enhanced storytelling visuals

👨‍💻 Author
Muhammad Abdul Hai
Power BI Developer | Data Enthusiast | Analytics | Sceintists
