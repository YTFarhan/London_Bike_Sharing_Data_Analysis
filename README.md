# London_Bike_Sharing_Data_Analysis

## 📌 Overview

This end-to-end data analytics project analyzes **London bike-sharing usage patterns** to uncover how weather conditions and seasonal trends impact ride demand.

The project demonstrates the complete analytics workflow:

> **Data Acquisition → Data Cleaning & Transformation (Python) → Exploratory Analysis → Business Insights → Interactive Dashboard (Tableau)**

The final output is an interactive Tableau dashboard featuring dynamic moving averages, heatmaps, and drill-down tooltips designed for decision-makers.

---

## 🎯 Business Problem

Urban mobility services rely heavily on weather and seasonality.

The objective of this project was to:

* Identify trends in bike demand over time
* Understand how **temperature and wind speed** impact ridership
* Visualize ride patterns interactively for stakeholders
* Enable dynamic time-based analysis using moving averages

---

## 📂 Dataset

* Source: Kaggle – [London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data)
* Granularity: Daily ride counts with weather metrics
* Key Features:

  * Total bike rides
  * Temperature (°C)
  * Wind speed (kph)
  * Humidity
  * Weather conditions
  * Seasons

---

## 🛠 Tools & Technologies

| Tool                       | Purpose                             |
| -------------------------- | ----------------------------------- |
| **Python (Pandas, Kagglehub)** | Data cleaning & preprocessing       |
| **Google Colab**           | Development environment             |
| **Excel**                  | Data export for BI tool integration |
| **Tableau**                | Interactive dashboard development   |
| **Kaggle API**             | Dataset acquisition                 |

---

## 🔎 Data Processing (Python)

The data preparation phase focused on transforming raw CSV data into analysis-ready format.

### Key Steps:

* Downloaded dataset from Kaggle
* Extracted compressed files
* Loaded CSV into Pandas DataFrame
* Performed exploratory data analysis:

  * Inspected shape and structure
  * Summarized statistics
  * Checked categorical distributions (weather codes, seasons)
* Renamed columns for clarity and readability
* Normalized humidity values
* Mapped:

  * Numeric season codes → Actual season names
  * Weather codes → Descriptive weather conditions
* Exported cleaned dataset to Excel for Tableau integration

This stage ensured clean, structured, and business-friendly data for visualization.

---

## 📊 Tableau Dashboard Features

### 1️⃣ Interactive Moving Average Line Chart

* Displays total bike rides over time
* Dynamic **moving average window** (user-controlled)
* Adjustable aggregation period:

  * Day
  * Week
  * Month
* Interactive date range selection
* Highlights selected periods
* Automatically recalculates trends based on user input

📌 Business Value:
Helps stakeholders identify seasonality trends and demand fluctuations.

---

### 2️⃣ Temperature vs Wind Speed Heatmap

* Visualizes ride density across temperature and wind speed combinations
* Dynamically updates based on selected time period
* Clearly identifies optimal riding conditions

📌 Key Insight:
Bike usage peaks at moderate temperatures with low-to-moderate wind speeds.

---

### 3️⃣ Advanced Tooltip Visualizations

Hover-based drill-down analytics:

* Hourly ride distribution
* Ride count by weather condition

This enables layered analysis without cluttering the main dashboard.

---

## 📈 Key Insights

* Bike demand increases significantly during warmer months.
* Moderate temperatures (10–20°C) correlate with peak usage.
* Higher wind speeds negatively impact ridership.
* Moving averages smooth volatility and clearly show seasonal demand patterns.

---

## 📸 Dashboard Preview

*(Insert dashboard screenshot here)*

<img width="1360" height="751" alt="Screenshot 2026-03-04 170915" src="https://github.com/user-attachments/assets/b1e38d43-6e73-4bb0-9e61-922db1daf913" />



