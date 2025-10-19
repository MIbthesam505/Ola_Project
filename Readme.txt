# 🚗 Ola Data Analysis Dashboard

## 📊 Overview

This project analyzes **Ola ride booking data** using **Power BI** and **SQL** to uncover trends in bookings, cancellations, revenue, and customer ratings. The goal is to help identify performance patterns and operational improvements.

---

## 🧠 Key Insights

* ~28% of total bookings were cancelled.
* Most cancellations were due to driver-related or customer change-of-plan reasons.
* Sedan rides generated the highest revenue.
* Evening hours had the most bookings.

---

## ⚙️ Tools & Technologies

* **SQL** – Data extraction, cleaning, and transformation.
* **Power BI** – Dashboard creation and visualization.
* **DAX** – For KPI and ratio calculations.
* **Excel/CSV** – Data source and preprocessing.

---

## 🧩 Main Measures

```DAX
TotalBookings = COUNTROWS(Bookings)
CanceledBookings = CALCULATE(COUNTROWS(Bookings), Bookings[Booking_Status] = "Canceled")
Cancelled Percentage = DIVIDE([CanceledBookings], [TotalBookings], 0)
```

---

## 📈 Dashboard Sections

* **Overall Summary**
* **Vehicle Type Analysis**
* **Revenue Insights**
* **Cancellations Breakdown**
* **Ratings Overview**

---

## 🚀 How to Use

1. Open `Ola_Proj.pbix` in Power BI Desktop.
2. Refresh data connections.
3. Use slicers to explore by month, vehicle type, or city.

---

## 👨‍💻 Author

**Muhammad Ibthesam**
Data Analyst | Power BI & SQL Developer

---

