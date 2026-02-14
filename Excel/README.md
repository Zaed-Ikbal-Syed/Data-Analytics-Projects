# 📊 Superstore Sales Dashboard Project

## 📌 Project Overview

This project demonstrates a complete **data cleaning, transformation, and dashboard creation process in Microsoft Excel** using raw Superstore sales data.

The objective was to transform uncleaned transactional data into an interactive dashboard that provides clear insights into:

* Sales distribution by category
* Performance by product manager
* Sales trends over time
* Regional and segment-based filtering

---

## 📁 Repository Contents

* **Raw Superstore data uncleaned.xlsx** → Original dataset (uncleaned)
* **My Solution to the uncleaned data.xlsx** → Cleaned dataset + Pivot Tables + Dashboard

---

## 🔄 Step-by-Step Process

### 1️⃣ Data Cleaning

The raw dataset was first examined and cleaned to ensure accuracy and consistency.

Cleaning steps included:

* Removing duplicates (if any)
* Handling missing or inconsistent values
* Standardizing text fields (e.g., category names, regions)
* Ensuring correct data types (dates, numeric sales values)
* Formatting columns for analysis readiness

This prepared the dataset for reliable analysis and reporting.

---

### 2️⃣ Product Manager Mapping (VLOOKUP)

To associate each product with its respective Product Manager:

* A reference table was created containing:

  * Product Name / Category
  * Corresponding Product Manager
* The **VLOOKUP** function was used to:

  * Match products from the main dataset
  * Automatically populate the Product Manager column

This enabled performance analysis by manager.

---

### 3️⃣ Data Summarization Using Pivot Tables

Multiple Pivot Tables were created to analyze sales from different perspectives:

#### 📌 A. Sales by Category Distribution

* Total sales grouped by product category
* Used to understand revenue contribution by category

#### 📌 B. Sales by Product Manager

* Total sales grouped by assigned manager
* Used to evaluate managerial performance

#### 📌 C. Sales Trend Analysis

* Sales aggregated by time (monthly/yearly)
* Used to identify growth patterns and seasonal trends

Pivot Tables allowed dynamic, scalable analysis without altering the base dataset.

---

### 4️⃣ Data Visualization

Based on Pivot Table summaries, visualizations were created:

* 📊 **Bar Charts** → Category & Manager comparisons
* 📈 **Trend Line / Column Chart** → Sales over time
* 🥧 **Pie Chart** → Category distribution breakdown

Charts were formatted for:

* Clear labeling
* Consistent color theme
* Readability and professional presentation

---

### 5️⃣ Dashboard Creation

A final interactive dashboard sheet was created by:

* Placing all relevant charts in a structured layout
* Aligning visuals for clarity and storytelling
* Adding slicers for dynamic filtering

#### 🎛 Interactive Slicers Added:

* Region
* Segment

This allows users to filter the entire dashboard dynamically and explore insights based on specific business dimensions.

---

## 🎯 Key Insights Enabled

The dashboard allows users to:

* Identify top-performing categories
* Compare product manager performance
* Monitor sales trends over time
* Filter performance by region and customer segment
* Quickly derive executive-level insights

---

## 🛠 Tools & Techniques Used

* Microsoft Excel
* Data Cleaning Techniques
* VLOOKUP
* Pivot Tables
* Pivot Charts
* Slicers
* Dashboard Design Principles

---

## 💡 Skills Demonstrated

* Data Cleaning & Preparation
* Excel Formula Application (VLOOKUP)
* Data Modeling & Summarization
* Business-Oriented Data Visualization
* Dashboard Development
* Analytical Thinking

## 🚀 Business Value

This project simulates a real-world business scenario where raw transactional data is converted into:

> Actionable insights for decision-makers through structured analysis and interactive visualization.
