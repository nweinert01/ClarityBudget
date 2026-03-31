# ClarityBudget

**Automated Personal Finance Year End Summaries**

Version: v1.0
Built by: Nichole Weinert
Tools: Google Sheets (Advanced Formulas, Power Query) + Python (optional extension)

**Project Summary**

This project is a fully automated personal finance system built using clean data modeling principles. This workbook transforms raw bank transactions into categorized, analytics‑ready data and produces year‑end insights through dynamic dashboards. Designed to mirror real analytics pipelines, it demonstrates skills in data transformation, modeling, automation, and user‑centered reporting. This public version uses mock data to protect privacy while showcasing the full workflow

---

**Purpose of This Workbook**
This workbook is designed to help everyday people understand, track, and improve their financial health through automation, clarity, and data-driven insights.

Most people were never taught how to manage money in a practical, empowering way. This system removes friction by:

- Automating calculations and trends
- Reducing manual work
- Presenting clear, human-friendly insights
- Encouraging sustainable financial habits

---

**Key Features**

- Fully automated data pipeline (no manual formulas in downstream tabs)

- Clean separation of raw, transformed, and analytical layers

- Dynamic category logic using dimension tables

- Yearly and monthly rollups powered by structured metrics

- Dashboard with trend analysis and category comparisons

- Mock data included for demonstration

- Built with analytics best practices (ETL, fact/dim modeling, metric layers)

--

**Skills Demonstrated**

- Data modeling (fact/dimension schema)

- ETL logic and transformation workflows

- Advanced spreadsheet automation

- Metric design and KPI development

- Dashboard design and data storytelling

- Data integrity and governance principles

- Mock data generation for safe public sharing

--

**How This Workbook Thinks About Data**

This workbook is structured like a mini data analytics system, not a traditional spreadsheet.


**High-level flow:**

RAW_TRANSACTIONS
        
CLEAN_TRANSACTIONS
        
DIM TABLES  -> FACT_TRANSACTIONS

METRICS

DASHBOARD

    
Each tab has one clear responsibility, and data flows in one direction only to ensure accuracy and scalability.

