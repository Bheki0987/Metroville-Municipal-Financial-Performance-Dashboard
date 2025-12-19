# 🏛️ Metroville-Municipal-Financial-Performance-Dashboard

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

## 📸 Dashboard Preview

![Dashboard Screenshot](PLACEHOLDER_FOR_YOUR_IMAGE_LINK_HERE)
*(A comprehensive executive view of Metroville Municipality's financial health, tracking budget variance, revenue collection, and outstanding debt.)*

---

## 📖 Project Overview

**Sector:** Public Sector / Municipal Finance  
**Role:** Data Analyst  
**Tools:** Microsoft Excel (Advanced)

This project simulates a real-world financial analytics scenario for a South African Municipality. The goal was to transform raw monthly transactional data into an interactive Executive Dashboard that allows the CFO and Ward Councilors to monitor fiscal performance, identify overspending, and track revenue collection efficiency.

### 🎯 The Business Problem
Municipalities often struggle with:
1.  **Budget Variance:** Departments overspending without early warning signals.
2.  **Revenue Leaks:** Inability to track which Service Types (Water, Rates, Electricity) are failing to collect revenue.
3.  **Debt Management:** A lack of visibility into "Critical Wards" where payment rates are dangerously low.

### 💡 The Solution
I built a dynamic dashboard that provides:
-   **Real-time Variance Analysis:** Instantly flags over-budget departments with visual indicators (Red/Green).
-   **Revenue vs. Debt Tracking:** A stacked analysis showing the "Collection Gap" per service.
-   **Ward Heatmaps:** Identifies underperforming wards (Payment Rate < 60%) to target interventions.

---

## 🛠️ Technical Implementation

This project demonstrates an end-to-end data analytics workflow within Excel:

### 1. Data Cleaning & Transformation (ETL)
-   Converted raw CSV extracts into structured **Excel Tables** for dynamic range handling.
-   Performed data type conversion (Text-to-Date) to enable Timeline filtering.
-   Standardized "Service Type" and "Department" naming conventions.

### 2. Data Modeling & Metric Engineering
-   **Relational Logic:** Used `XLOOKUP` to map Department Heads from a reference table to the main transaction dataset.
-   **KPI Creation:** calculated custom metrics including:
    -   `Budget Variance (R)` = Budget - Actuals
    -   `Collection Rate %` = Revenue / (Revenue + Debt)
    -   `Status Flags` = Nested `IF` logic to classify "Over Budget" vs "Under Budget".

### 3. Advanced Analysis (The "Pivot Engine")
-   Built a dedicated **Pivot Engine** sheet to drive the dashboard visuals.
-   Used **Pivot Tables** to aggregate millions of Rands in transactional data by Department, Month, and Service.
-   Applied **Weighted Averages** for Ward Payment Rates (avoiding the common error of averaging percentages).

### 4. Dashboard UI/UX Design
-   **Interactive Elements:** Connected **Slicers** (Department, Service) and **Timelines** (Month) to control all charts simultaneously.
-   **Conditional Formatting:** Implemented logic-based **Icon Sets** (Red/Green Arrows) to show variance direction instantly.
-   **Custom Number Formatting:** Applied dynamic formatting (e.g., `#,##0.0,,"M"`) to display figures in Millions/Billions automatically.
-   **Visual Hierarchy:** Designed a clean, "App-like" layout with white cards, drop shadows, and a "Metroville" brand theme.

---

## 📂 Files in this Repository

-   `Municipality_Finance_Analytics.xlsx` - The fully functional dashboard file.
-   `Raw_Data.csv` - The original dataset used for analysis.
-   `Dashboard_Screenshot.png` - High-resolution image of the final output.

---

## 🚀 How to Use

1.  Download the **.xlsx** file.
2.  Open in **Microsoft Excel** (2016 or later recommended).
3.  Use the **Slicers** on the right panel to filter by *Department* or *Service Type*.
4.  Adjust the **Timeline** to view specific quarters or months.
5.  Watch the **Scorecards** and **Variance Icons** update dynamically!

---

## 👤 Author

**[YOUR NAME]** *Data Analyst | Excel Specialist*

[LinkedIn Profile](LINK_TO_YOUR_LINKEDIN) | [Portfolio](LINK_TO_YOUR_PORTFOLIO)

---
*Note: This dataset is a simulation created for educational purposes.*
