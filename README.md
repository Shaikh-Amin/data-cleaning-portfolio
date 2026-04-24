# data-cleaning-portfolio
A collection of real-world data cleaning projects using MySql, MS Excel including missing value handling, outlier treatment, and data processing.


# 🛍️ E-Commerce Sales Dashboard (Excel)

An interactive Excel dashboard built to analyze e-commerce sales performance across products, channels, geography, and customer demographics.

---

## 📊 Dashboard Overview

This project transforms raw transactional sales data into a fully interactive Excel dashboard. It tracks key business metrics and answers critical business questions through pivot tables, charts, and KPI cards.

![Dashboard Preview](dashboard_preview.png)
> *Screenshot of the dashboard (add your own image here)*

---

## 🗂️ File Structure

The workbook is organized across 6 sheets:

| Sheet | Description |
|-------|-------------|
| `Dashboard` | Main interactive dashboard with charts and KPI cards |
| `Data` | Raw transactional data (2,400+ orders) |
| `Questions & KPIs` | Business questions and KPI definitions |
| `Pivots` | Pivot tables powering the main dashboard |
| `Pivots_2` | Additional pivot tables for secondary visuals |
| `Logo & Colors` | Brand assets and color palette used in the dashboard |

---

## 📈 KPIs Tracked

| KPI | Value |
|-----|-------|
| Total Orders | 2,400 |
| Total Quantity Sold | 11,997 units |
| Total Revenue | $649,019.80 |
| Average Customer Rating | 4.0 / 5.0 |
| Average Days to Deliver | 2.3 days |

---

## ❓ Business Questions Answered

The dashboard is designed to answer the following business questions:

1. **Trend in the last 13 weeks** — How is revenue and quantity trending over time?
2. **How our customers like to buy** — Which order channels (App, Website, Instagram, Target.com, Partner App) are most popular?
3. **How many they buy?** — What is the typical order quantity per transaction?
4. **Which products are popular?** — Which product categories drive the most sales?
5. **Overall gender split** — What is the breakdown of Male, Female, and Other customers?
6. **Where do our customers live?** — Which states and counties generate the most orders?
7. **How long does shipping take?** — What is the distribution of delivery days?
8. **How happy are our customers?** — What is the distribution of customer ratings?

---

## 🗃️ Data Schema

The `Data` sheet contains individual transaction records with the following fields:

| Column | Description |
|--------|-------------|
| `TX ID` | Unique transaction identifier |
| `Product` | Product category (e.g., Jeans, Sneakers, T-Shirts) |
| `Quantity` | Units purchased per order |
| `Unit Price` | Price per unit ($) |
| `Amount` | Total order value ($) |
| `Order Date` | Date the order was placed |
| `Ship Date` | Date the order was shipped |
| `Customer Gender` | M / F / O (Other) |
| `Order Mode` | Sales channel (App, Website, Instagram, Target.com, Partner App) |
| `Rating C` | Customer satisfaction rating (1–5) |
| `State` | Customer's state |
| `County` | Customer's county |
| `Days to Deliver` | Number of days between order and shipment |
| `Weeknum` | Week number of the order date |
| `Gender Value` | Expanded gender label (Male / Female / Other / Unknown) |

---

## 🛒 Products Covered

The dataset includes the following product categories:

Tops & Tees · Jeans · Shorts · Dresses (Casual, Maxi, Sundresses) · Sneakers · Sandals · Hoodies & Sweatshirts · Leggings · Crop Tops · Bikinis · Pajama Sets · Tote Bags · Sunglasses · Baseball Caps · Jewelry · Workout Tops · Tank Tops · Graphic Tees

---

## 🌍 Geography

Data covers customers across **California**, broken down by county (Los Angeles, San Diego, Sacramento, San Francisco, and many more).

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Charts, Slicers, Conditional Formatting, KPI Cards

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Ecommerce_dashboard_project.xlsx` in Microsoft Excel (2016 or later recommended).
3. Navigate to the **Dashboard** sheet.
4. Use slicers/filters (if available) to explore data by date, product, gender, or channel.
5. The pivot tables in the `Pivots` and `Pivots_2` sheets update automatically if you refresh the data.

---

## 📁 Repository Contents

```
📦 ecommerce-dashboard
 ┣ 📊 Ecommerce_dashboard_project.xlsx
 ┗ 📄 README.md
```

---

## 📬 Contact

Feel free to open an issue or reach out if you have questions or suggestions!
