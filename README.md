# 🚖 Uber Ride Analytics Dashboard

**End-to-end analysis of 150,000+ Uber ride bookings — from raw data to an interactive Power BI dashboard.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

---
## 📌 Overview

This project analyzes a full year (2025) of Uber ride-booking data — **150,000 trips** — to uncover patterns in ride demand, cancellations, revenue, vehicle-type performance, and customer/driver ratings. The raw data was cleaned and modeled in Excel, then visualized in a 3-page interactive **Power BI dashboard** (Home, Overview, Vehicle) with KPI cards, trend charts, and slicers for dynamic filtering.

**Goal:** Turn raw ride-level data into an executive-ready dashboard that answers questions like:
- Where is revenue coming from, and which vehicle types perform best?
- What's driving cancellations — customers or drivers?
- How do ratings and ride distance vary across vehicle types and payment methods?
- How does demand trend month over month?

---

## 📊 Dashboard Preview
## Home
<img width="1373" height="833" alt="Ride-Booking-Business-Dashboard" src="https://github.com/user-attachments/assets/9e2d5fa1-dd78-4e10-9f35-88d4eb8d957b" />

## Overview
<img width="1305" height="830" alt="Ride-Booking-Business-Overview" src="https://github.com/user-attachments/assets/33d0755a-40e0-43b0-ad03-cf739ebf6bdd" />

## Vehicle
<img width="1303" height="826" alt="Ride-Booking-Business-Vehicle" src="https://github.com/user-attachments/assets/b9069b5f-a73a-4453-b088-429f08ccacb5" />


---

## Video Walkthrough
<!-- Drag-and-drop a short screen recording (Home → Overview → Vehicle, using the slicers)
     into a GitHub comment/issue to get a user-attachments video URL, then paste it below. -->
     

https://github.com/user-attachments/assets/e7e5e5f4-692b-4aff-aed9-62c08ca19c19

## 📊 Key Insights

| Metric | Value |
|---|---|
| Total bookings | 150,000 |
| Completed rides | 93,000 (**62%**) |
| Cancelled by driver | 27,000 (18%) |
| Cancelled by customer | 10,500 (7%) |
| No driver found | 10,500 (7%) |
| Incomplete rides | 9,000 (6%) |
| Total revenue (completed rides) | ₹4.73 Cr |
| Avg. booking value | ₹508 |
| Avg. ride distance | 24.6 km |
| Avg. driver rating | 4.23 ★ |
| Avg. customer rating | 4.40 ★ |
| Top vehicle by revenue | Auto (₹1.29 Cr) |
| Most-used payment method | UPI (45%) |

**Highlights:**
- 🚗 **Auto and Go Mini** together drive over **45% of total revenue**, making them the highest-priority vehicle segments.
- ⚠️ **Driver-side cancellations (18%)** outweigh customer cancellations (7%) by a wide margin — the single biggest lever for improving completion rate.
- 💳 **UPI dominates payments** (45%), followed by Cash (25%) — a strong signal for where to focus payment-experience investment.
- ⭐ Customer ratings (4.40) run consistently higher than driver ratings (4.23) across the dataset.

---

## 🗂️ Dataset

| Field | Description |
|---|---|
| `Date`, `Time` | Booking timestamp |
| `Booking ID`, `Customer ID` | Unique identifiers |
| `Booking Status` | Completed / Cancelled by Driver / Cancelled by Customer / No Driver Found / Incomplete |
| `Vehicle Type` | Auto, Bike, eBike, Go Mini, Go Sedan, Premier Sedan, Uber XL |
| `Pickup Location`, `Drop Location` | Trip endpoints |
| `Cancellation Reason` (Customer/Driver) | Free-text reason fields |
| `Booking Value` | Fare amount |
| `Ride Distance` | Trip distance (km) |
| `Driver Ratings`, `Customer Rating` | 1–5 star ratings |
| `Payment Method` | UPI, Cash, Uber Wallet, Credit Card, Debit Card |

**Source file:** `uber.xlsx` (150,000 rows, cleaned and structured for direct Power BI import)

---

## 🧰 Tech Stack

- **Microsoft Excel** — data cleaning, structuring, and pre-modeling
- **Power BI Desktop** — data modeling, DAX measures, and interactive report design
- **DAX** — calculated KPIs (completion rate, revenue, average ratings, etc.)

---

## 📁 Repository Structure

```
uber-ride-analytics/
├── uber.xlsx          # Cleaned dataset
├── Uber.pbix           # Power BI report (Home, Overview, Vehicle pages)
├── assets/             # Screenshots + video thumbnail for README
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/uber-ride-analytics.git
   ```
2. Open `Uber.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Explore the three report pages — **Home**, **Overview**, and **Vehicle** — and use the slicers to filter by date, vehicle type, or payment method.

---

## 🔗 Dashboard Pages

- **Home** — landing/navigation page
- **Overview** — company-wide KPIs, revenue trend, booking status breakdown, payment method split
- **Vehicle** — performance breakdown by vehicle type (revenue, ratings, distance)

---

## Author

**Kapala Surya Charan**
Aspiring Data Analyst | B.Tech CSE (AI), Parul University

[LinkedIn](https://linkedin.com/in/surya-charann) | [Email](mailto:kapalasuryacharan@gmail.com) | [GitHub](https://github.com/Surya410C)

