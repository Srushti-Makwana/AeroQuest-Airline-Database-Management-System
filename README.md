# ✈️ AeroQuest Airlines Database Management System

## 🚀 Overview
AeroQuest Airlines DBMS is a comprehensive **Database Management System** built using **PostgreSQL**. It manages **end-to-end airline operations** — including flight scheduling, passenger management, employee records, bookings, refunds, and more.

All tables are normalized up to **BCNF**, ensuring data consistency and minimizing redundancy. The project also features **complex analytical SQL queries** that generate actionable business insights.

---

## 🏗️ Tech Stack
- **PostgreSQL** – Schema design, data population, and analytical querying  
- **Dia** – ER diagram creation and visualization  
- **SQL scripts** – All code in `.sql` format for easy execution and replication

---

## 📊 Features & Highlights
- **Passengers**: Personal info, disability support, and frequent flyer points  
- **Aircraft Fleet**: Aircraft specifications and seating capacities  
- **Trips**: Scheduled flights with aircraft type, distance, and duration  
- **Bookings & Transactions**: Ticketing system with integrated payments  
- **Surfing Data**: Tracks user browsing behavior to analyze demand  
- **Refunds & Events**: Manages full/partial refunds for disrupted trips  
- **Employees**: Tracks pilots, airhosts, managers, flying hours, and salaries  
- **Feedback**: Passenger reviews and crew member ratings

---

## 🔍 Key Analytical Queries
- ✅ Identify trips that are frequently browsed but never booked (untapped demand)  
- ✅ Compute total revenue, refunds, and net earnings per trip  
- ✅ Find trips with the most vacant seats to aid in dynamic pricing strategies  
- ✅ List passengers who require special assistance  
- ✅ Analyze pilot salaries by rank and total flying hours  
- ✅ Generate monthly summaries of passenger travel – like a "Spotify Wrapped" for flyers

---

## 📝 Normalization
All relations are:
- Analyzed for **Functional Dependencies (FDs)**  
- Reduced to **minimal FD sets**  
- Verified to be in **Boyce-Codd Normal Form (BCNF)**  

Full documentation is available in [`docs/Normalization.pdf`](docs/Normalization.pdf).

---

## 📂 File Structure
