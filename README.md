# Smartphone Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard analyzing smartphone sales across India — comparing brand performance, monthly sales trends, city-wise distribution, payment methods, and customer satisfaction in a single executive view.

![Dashboard Preview](images/dashboard-preview.png)

## 📊 Overview

This project turns raw smartphone transaction data into a decision-ready report. Instead of digging through spreadsheets, a business user can open the dashboard and instantly answer questions like:

- Which smartphone brand is generating the most revenue and units sold?
- How does sales volume trend month over month?
- Which Indian cities are driving the most sales?
- How are customers paying — UPI, cards, or cash?
- How satisfied are customers, based on ratings?

## 🔑 Key Features

- **KPI Cards** — Total Sales (₹769M), Total Quantity (19K units), Total Transactions (4K), Average Price (₹40.11K)
- **Quantity Sold by Month** — line chart tracking unit sales trends across the year
- **Top 3 Brands** — clustered column chart ranking Apple, Samsung, and OnePlus by units sold
- **Transactions by Payment Method** — pie chart showing an even split across UPI, Debit Card, Credit Card, and Cash
- **Customer Ratings** — funnel visual showing the distribution of 1–5 star ratings
- **Geographic Map** — bubble map plotting sales activity across major Indian cities (Delhi, Mumbai, Bangalore, Kolkata, Chennai, and more)
- **Brand Summary Table** — Total Sales, Units Sold, and Transactions broken down by brand (Apple, OnePlus, Samsung, Vivo, Xiaomi)
- **Interactive Slicers** — filter the entire report by month and phone model

## 🗂️ Data Model

A single fact table, `Sales_Data`, powers the report with fields including:

| Field | Description |
|---|---|
| `Date` | Transaction date |
| `Brand` | Smartphone brand (Apple, Samsung, OnePlus, Vivo, Xiaomi) |
| `City` | Location of sale |
| `Units Sold` | Quantity sold per transaction |
| `Price Per Unit` | Unit price |
| `Total_Sales` | Revenue generated |
| `Tot_Transactions` | Transaction count |
| `Payment Method` | UPI, Debit Card, Credit Card, or Cash |
| `Customer Ratings` | Customer satisfaction score (1–5) |

## 📈 Sample Insights

- **Apple** leads in total revenue (₹161.6M) despite Samsung and OnePlus posting similar unit volumes — pointing to a higher average selling price.
- Monthly unit sales fluctuate between ~1,450 and ~1,700 units, with no single month dominating — demand looks fairly stable year-round.
- Payment methods are nearly evenly split (24–26% each across UPI, Debit Card, Credit Card, and Cash), suggesting no single payment channel dominates customer preference.
- Most customers rate their purchase 5 stars, with ratings dropping off steadily from 4 to 1 star — a healthy satisfaction funnel.

## 🛠️ Tools & Skills Demonstrated

- **Power BI Desktop** — data modeling, DAX-driven visuals, and report design
- **Data Visualization** — matching chart type to the story each metric tells (trend, ranking, composition, distribution, geography)
- **Dashboard UX** — single-page layout with slicers for self-serve filtering, designed for a non-technical business audience
- **Business Analysis** — translating raw transactional data into KPIs that support sales and customer-experience decisions

## 🚀 How to Use

1. Download `dashboard.pbix`
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the Month and Model slicers to filter the report
4. Hover over any visual for detailed tooltips

## 💡 Why This Project

This dashboard reflects how I approach data analysis end-to-end: starting from raw transactional data, identifying the metrics that matter to the business, and presenting them in a way that's immediately usable by decision-makers — not just technically correct, but genuinely readable.

---
*Part of my data analytics portfolio — feel free to connect if you'd like to discuss the approach or extend the analysis.*
