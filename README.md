# 📊 Automated Inventory Management System

A Python-based automated system for campus inventory management, designed to streamline data processing, stock monitoring, and reporting. This project demonstrates the integration of **Python**, **SQL logic**, and **Automated Reporting**.

## 🚀 Overview
Managing hundreds of inventory items manually in spreadsheets is time-consuming and prone to human error. This system automates the workflow by:
1. **Processing Data**: Reading raw CSV files with Python (Pandas).
2. **Stock Analysis**: Automatically categorizing items into "Critical Stock" (< 50 units) and "Ample Stock" (> 100 units).
3. **Automated Reporting**: Generating timestamped folders containing formatted Excel reports and data visualizations.

## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Libraries**: Pandas, Matplotlib, XlsxWriter
- **Database Logic**: SQL for structured data storage
- **Version Control**: GitHub

## 📈 Key Features
- **Dynamic Folder Creation**: Automatically creates folders named based on the current date (`Laporan_YYYY-MM-DD`).
- **Data Cleaning**: Filters out zero-stock items to ensure clear and actionable visualizations.
- **Visual Insights**: Generates bar charts with automated data annotations.
- **Conditional Formatting**: Excel reports are automatically formatted (e.g., highlighting critical stock in red) using Python logic.

## 📂 Project Structure
- `itemsppni.csv`: Raw inventory data.
- `inventory_automation.py`: The main Python script.
- `Laporan_YYYY-MM-DD/`: Output folder containing generated reports and charts.

## 💡 How It Works
The script reads the inventory file, applies filter logic to remove empty entries, calculates stock levels, and exports the results into a multi-sheet Excel file with built-in conditional formatting.

---
*Created by [Ryan Sofiyulloh](https://github.com/ryansof22) as part of a Data Analytics learning journey.*
