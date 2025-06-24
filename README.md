# Sampath Food City Sales Data Analysis System

A Python-based command-line system for analyzing supermarket sales data, featuring user authentication, data cleaning, EDA, KPI calculation, predictive analytics, and detailed sales reports. Designed for both admin and regular users.

---

## Author
**Dison Methvin**

---

## Introduction
Data Labs is a leading software development company in Sri Lanka, focusing on helping businesses build their operations through creative and effective solutions. As an apprentice software developer at Data Labs, you have been tasked with developing a command-line interface-based software system using Python for the following scenario.

## Project Description
Sampath Food City (PVT) Ltd is one of the main supermarket networks in Sri Lanka with several branches island-wide. Currently, each branch records transactions through a point of sale (POS) system, and at the end of each month, the recorded data is transferred to a centralized database. The top-level management uses this centralized data to perform monthly sales data analysis to make managerial decisions.

The existing paper-based manual system for monthly sales data analysis has several drawbacks, including human errors, time consumption, data redundancy, inconsistency, and difficulty in finding insights, which negatively affect business performance. Therefore, the management has decided to implement a customized software system for sales data analysis to eliminate these weaknesses.

## Features
- User authentication (admin and regular users)
- Data loading and cleaning (Excel/CSV)
- Feature engineering (date, profit, etc.)
- Exploratory Data Analysis (EDA)
- Key Performance Indicators (KPIs) calculation
- Predictive sales analytics (regression-based)
- Monthly, weekly, and branch-specific sales analysis
- Product price and preference analysis
- Sales distribution analysis
- Console-based interactive UI
- Admins can upload new datasets

## Installation
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Sales_Analysis_System
   ```
2. **Install dependencies:**
   Ensure you have Python 3.8+ installed. Then run:
   ```bash
   pip install pandas scikit-learn tabulate openpyxl
   ```
   (Other dependencies may be required based on your environment.)

## Usage
1. **Navigate to the main script directory:**
   ```bash
   cd Src/util
   ```
2. **Run the system:**
   ```bash
   python main.py
   ```
3. **Follow the on-screen menu:**
   - Register or log in as admin/regular user.
   - Choose analysis options from the menu.
   - Admins can upload new datasets.

## Output
- All results and analyses are displayed in the console as formatted tables and summaries.
- No graphical interface is provided; all interaction is via the command line.

## Conclusion
This system streamlines the sales data analysis process for Sampath Food City, reducing errors and improving efficiency. Management can make more informed decisions based on accurate and timely data insights.

For any questions or suggestions, please contact **disonmethvin.education@gmail.com**
