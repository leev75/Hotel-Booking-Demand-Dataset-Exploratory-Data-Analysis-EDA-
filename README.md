# Hotel Booking Demand Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3-red)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11-green)
[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-orange)](https://www.kaggle.com/datasets/example-hotel-bookings)

## 📖 Overview
This project analyzes hotel booking data to identify key trends, cancellation drivers, and revenue optimization opportunities. The dataset includes **119,390 records** with features like booking dates, customer demographics, stay details, and cancellation status.

## 🔍 Business Questions Explored
1. What percentage of bookings are canceled, and what factors drive cancellations?
2. How do booking patterns vary between **city hotels** and **resort hotels**?
3. Which months have the highest demand and average daily rates (ADR)?
4. Do lead times or deposit types correlate with cancellations?

## 🛠️ Features
- **Data Cleaning**: Handled missing values, outliers, and inconsistent formatting.
- **Feature Engineering**: Created new metrics (e.g., `total_guests`, `stay_duration`).
- **Visualizations**: Heatmaps, seasonal trend charts, cancellation correlation matrices.
- **Statistical Analysis**: Hypothesis testing for cancellation drivers (e.g., t-tests, chi-square).

## 📂 Dataset
- **Source**: [Kaggle Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/example-hotel-bookings)
- **Features**:
  - `hotel` (City/Resort)
  - `is_canceled` (1/0)
  - `lead_time`, `arrival_date_month`, `adr`, `market_segment`, etc.

## 🚀 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hotel-booking-eda.git
