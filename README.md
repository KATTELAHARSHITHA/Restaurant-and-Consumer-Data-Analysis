# 🍽️ Restaurant & Consumer Analytics Database (SQL Project)

## 📌 Overview

This project focuses on designing a **relational database system** to analyze restaurant performance and consumer behavior using **MySQL**.
It covers the full workflow — from **database design and normalization** to **advanced SQL analytics** with queries, views, CTEs, and stored procedures.

---

## 🛠️ Features & Implementation

### 🔹 Database Design

* Created normalized schemas with the following tables:

  * **Restaurant** – Details like location, alcohol service, pricing, franchise status, and parking.
  * **Consumers** – Demographics, lifestyle, budget, and occupation.
  * **Ratings** – Consumer reviews with overall, food, and service ratings.
  * **Restaurant\_Cuisines** – Cuisine mapping for each restaurant.
  * **Consumer\_Preferences** – Captures preferred cuisines.
* Implemented **Primary & Foreign Keys** to enforce referential integrity.

### 🔹 SQL Queries & Analysis

* Filtering with **WHERE**, **GROUP BY**, **HAVING**, and **JOINS**.
* Insights delivered:

  * Top-rated restaurants by cuisine and location.
  * Consumer segmentation based on budget, lifestyle, and engagement.
  * Performance benchmarking of restaurants (above/below average).
  * Identification of loyal consumers and popular cuisines.

### 🔹 Advanced SQL Concepts

* **CTEs & Derived Tables** – for layered analysis (e.g., engagement score, cuisine ranking).
* **Window Functions** – RANK, ROW\_NUMBER, LEAD/LAG for ranking and comparisons.
* **Views** – *HighlyRatedMexicanRestaurants*, *ConsumerAverageRatings* for reusable insights.
* **Stored Procedures**:

  * `GetRestaurantRatingsAboveThreshold` – fetch restaurant ratings above a given threshold.
  * `GetConsumerSegmentAndRestaurantPerformance` – classify consumers into budget segments & evaluate restaurant ratings vs. averages.

---

## 📊 Business Insights Delivered

* Segmented consumers into **Budget Conscious, Moderate Spenders, and Premium Spenders**.
* Identified top cuisines and restaurants driving customer satisfaction.
* Highlighted underperforming restaurants compared to overall averages.
* Helped in **franchise performance tracking** and **consumer loyalty analysis**.

---

## 🛠️ Tech Stack

* **MySQL** – Database design, SQL queries, views, stored procedures, window functions
* **RDBMS Concepts** – Normalization, constraints, relationships

---

## 🚀 How to Run

1. Clone the repo
2. Import the SQL file into MySQL
3. Run queries in the script to generate insights


