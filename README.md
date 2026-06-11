# MySQL-Core
# Ola Cab Bookings Data Analysis Project

## Project Overview
This project delivers a comprehensive data analysis of 40,000 Ola cab booking records using MySQL. The primary objective is to evaluate operational performance, understand customer booking patterns, and extract actionable business insights regarding ride success, cancellations, and revenue generation.

## Key Objectives
* Evaluate ride success and cancellation rates across different segments.
* Identify peak booking hours and top revenue-generating customer segments.
* Analyze driver ratings and customer feedback to improve service quality.

## Tech Stack & Tools
* **Database Engine:** MySQL
* **Interface:** MySQL Workbench
* **Language:** SQL (Structured Query Language)

## Dataset Description
The dataset contains 40,000 anonymized booking transactions with the following core attributes:
* **Booking ID / Date / Time:** Unique transaction identifiers and timestamps.
* **Customer ID / Vehicle Type:** Customer tracking and ride category (e.g., Sedan, SUV, Mini).
* **Pickup / Drop Location:** Spatial data for route analysis.
* **Booking Status:** Transaction outcomes (Success, Cancelled by Customer, Cancelled by Driver).
* **Ride Distance / Fare:** Quantitative metrics for operational efficiency and revenue.
* **Ratings:** Performance metrics for drivers and customers.

## Database Operations & SQL Techniques Used
* **Data Aggregation:** `COUNT`, `SUM`, `AVG` to compute totals, revenues, and average distances.
* **Date & Time Functions:** Extracting peak hours and analyzing trends over time.
* **Conditional Logic:** `CASE WHEN` statements to segment data dynamically.
* **Filtering & Sorting:** `WHERE`, `HAVING`, `GROUP BY`, and `ORDER BY` for targeted data extraction.
* **Subqueries:** Implementing nested queries to isolate top-performing categories.

## Business Insights Derived
* **Booking Success Rate:** Quantified the exact percentage of completed rides versus cancellations.
* **Cancellation Analysis:** Isolated the top reasons why customers and drivers cancel rides.
* **Revenue Peak:** Identified the specific hours of the day that yield the highest gross revenue.
* **Fleet Performance:** Ranked vehicle types by total demand and average rating scores.

## Repository Structure
├── README.md               # Project documentation

└── ola_bookings_queries.sql # SQL script containing database setup and analytical queries

|__ schema.png

|__ schema.mwb

