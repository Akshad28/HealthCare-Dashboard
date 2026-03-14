Hospital Statistics Dashboard (2019 - 2024)
#Project Overview
This interactive Power BI dashboard provides a comprehensive analysis of hospital operations, patient demographics, and financial performance over a six-year period. By processing over 40,000 patient records, this project aims to uncover patterns in medical conditions, billing trends, and insurance utilization to support data-driven healthcare management.

#Key Features & Insights
Executive Summary (KPIs): Real-time tracking of Total Billing Amount ($1.42bn), Patient Count (40K), Average Age (51.54), and most frequently prescribed medication (Lipitor).

#Financial Trends: A dual-axis line chart comparing the Sum of Billing against Patient Count by year, identifying a significant revenue peak between 2020 and 2023.

#Patient Demographics: * Medical Condition Analysis: Breakdown of patients by condition (Arthritis, Diabetes, etc.) cross-referenced with Blood Type.

#Sankey-style Flow: Visualization of patient volume categorized by Age Group (Old Age, Middle Age, Senior, Young) and Admission Type.

#Operational Metrics: Top 5 most visited hospitals (led by LLC Smith) and a market share analysis of the top 5 insurance providers.

Tech Stack
#Tool: Power BI Desktop

#Data Source: Hospital Management System (Synthetic Dataset)

#Data Transformation: Power Query (Cleaning, Handling Nulls, Data Typing)

#Modeling: Star Schema with a dedicated Date Table.

#DAX Measures: Custom calculations for Average Duration of Stay, Rolling Billing Totals, and Dynamic Year Filtering.

How to Use
Year Slicer: Use the top-right button grid to filter the entire dashboard by a specific year (2019–2024).

Cross-Filtering: Click on any "Medical Condition" bar to see how insurance and age demographics shift for that specific ailment.

Tooltip Insights: Hover over the "Sum of Billing" line chart to see exact month-over-month growth figures.
