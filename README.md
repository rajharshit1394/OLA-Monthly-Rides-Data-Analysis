# OLA-Monthly-Rides-Data-Analys

## 📌 Project Overview
This is an end-to-end **Data Analyst Project** based on OLA ride bookings in **Bengaluru city**.
The project covers **Data Generation → MySQL Analysis → Power BI Dashboard**
---
## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| 🗄️ MySQL | Data storage and SQL analysis |
| 📊 Power BI | Interactive dashboard and visualization |
| 📁 Excel/CSV | Raw dataset |

---
## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `mysql_OLA_Monthly_Analysis.sql` | Full MySQL database dump |
| `Bookings_updated.csv` | Raw dataset with 1,00,000 rows including Payment Method |
| `queries.sql` | All SQL queries and views used for analysis |
| `OLA_Dashboard.pbix` | Power BI Dashboard with 5 pages |
| `README.md` | Project documentation |

---

## 📊 Dataset Details

| Detail | Info |
|--------|------|
| 🏙️ City | Bengaluru |
| 📅 Period | July 2024 |
| 📦 Total Records | 1,00,000 |
| 🚗 Vehicle Types | Auto, Mini, Bike, eBike, Prime Sedan, Prime Plus, Prime SUV |
| 📍 Locations | 50 areas across Bengaluru |
| 💳 Payment Methods | UPI, Cash, Credit Card, Debit Card, Wallet |

---

## 📈 Key Metrics

| Metric | Value |
|--------|-------|
| ✅ Successful Rides | 62% |
| ❌ Cancelled by Customer | 7% |
| ❌ Cancelled by Driver | 18% |
| ⚠️ Incomplete Rides | 6% |
| 🚫 No Driver Found | 7% |

---

## 🔍 SQL Analysis — Questions Solved

1. Retrieve all successful bookings
2. Find the average ride distance for each vehicle type
3. Get the total number of cancelled rides by customers
4. List the top 5 customers who booked the highest number of rides
5. Get the number of rides cancelled by drivers due to personal and car related issues
6. Find the maximum and minimum driver ratings for Prime Sedan bookings
7. Find the average customer rating per vehicle type
8. Calculate the total booking value of rides completed successfully
9. List all incomplete rides along with the reason
10. Top 5 customers by total booking value

> All queries are saved as **Views** in MySQL for easy reuse

---

## 📊 Power BI Dashboard — 5 Pages

### 📄 Page 1 — Overall
- Ride Volume Over Time
- Booking Status Breakdown

### 📄 Page 2 — Vehicle Type
- Top 5 Vehicle Types by Ride Distance
- Average Customer Ratings by Vehicle Type

### 📄 Page 3 — Revenue
- Revenue by Payment Method
- Top 5 Customers by Total Booking Value
- Ride Distance Distribution Per Day

### 📄 Page 4 — Cancellation
- Cancelled Rides Reasons by Customer
- Cancelled Rides Reasons by Driver

### 📄 Page 5 — Ratings
- Driver Ratings Distribution
- Customer vs Driver Ratings

---

## 🚀 How to Use This Project

### Import Database in MySQL
1. Open **MySQL Workbench**
2. Go to **Server → Data Import**
3. Select **mysql_OLA_Monthly_Analysis.sql**
4. Click **Start Import**

### Run SQL Queries
1. Open `queries.sql` in MySQL Workbench
2. Select the **ola** database
3. Run queries to see all analysis

### View Power BI Dashboard
1. Download `OLA_Dashboard.pbix`
2. Open in **Power BI Desktop**
3. Explore all 5 pages of the dashboard

### View Raw Data
- Open `Bookings_updated.csv` in **Excel** to explore the dataset

---

## 💡 Key Insights
- 📅 Ride demand is significantly higher on **weekends**
- 🚗 **Mini and Auto** are the most popular vehicle types
- 💰 Booking values are higher on **weekends**
- 💳 **UPI is the most preferred** payment method (35%)
- ⚠️ Most driver cancellations are due to **personal and car related issues**
- ❌ Most customer cancellations happen because **change of plans**

---

## 👤 Author
**Harshit Raj**
GitHub: [@rajharshit1394](https://github.com/rajharshit1394)
