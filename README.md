✈️ AeroQuest Airlines Database Management System
🚀 Overview
This project is a Database Management System (DBMS) designed for AeroQuest Airlines, built using PostgreSQL.
It manages end-to-end airline operations from flights and passengers to employees, bookings, and refunds.

All tables are normalized up to BCNF, ensuring data consistency and minimal redundancy.
The project also features complex analytical queries to generate business insights.

🏗️ Tech Stack
PostgreSQL schema design, data population, analytics.
Dia — for ER diagram design and visualization.
SQL — all scripts in .sql format for easy execution.
📊 Features & Highlights
Passengers: Details, disabilities, frequent flyer points.
Aircraft Fleet: Specs & seating capacities.
Trips: Schedules flights with aircraft, distance, duration.
Bookings & Transactions: Ticket purchases linked with payments.
Surfing: Tracks browsing data to analyze demand.
Refunds & Events: Handles partial refunds for disruptions.
Employees: Pilots, airhosts, managers, flying hours & salaries.
Feedback: Passenger ratings of crew members.
🔍 Key Analytical Queries
This project includes a rich set of insights, such as: ✅ Trips most browsed but not booked (to identify untapped demand).
✅ Total revenue, refunds, and net earnings by trip.
✅ Find trips with most vacant seats (for pricing strategy).
✅ Identify passengers requiring special assistance.
✅ Pilot salary analysis by rank & flying hours.
✅ Monthly passenger summaries — like a "Spotify Wrapped" for travelers.

📝 Normalization
All tables analyzed for Functional Dependencies, minimal FD sets, and proven to be in BCNF.
Full documentation in docs/Normalization.pdf.
