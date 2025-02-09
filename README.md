# Goldman Sachs & JPMorgan Chase Stock Price Analysis

# Goldman Sachs Stock Price Analysis

![Dashboard Demo](screen.gif)

## Author: Dawit Asmerawork  
**Year:** 2025  
**GitHub:** [Dawit0101](https://github.com/Dawit0101/)  

---

## Project Overview
This project focuses on analyzing the stock price data of two of the largest investment banks in the USA: **Goldman Sachs** and **JPMorgan Chase**. The dataset includes historical stock prices from **2000 to May 2024**, with columns such as `Date`, `Price`, `Open`, `High`, `Low`, `Vol.`, and `Change %`.

The goal of this project is to:
1. Perform exploratory data analysis (EDA) on the stock price data.
2. Visualize trends, patterns, and key metrics using interactive charts.
3. Build a dashboard to provide an intuitive and interactive view of the data.

---

## Dataset Details
The dataset contains the following columns:
- **Date**: The date of the stock price record.
- **Price**: The closing price of the stock on the given date.
- **Open**: The opening price of the stock on the given date.
- **High**: The highest price of the stock on the given date.
- **Low**: The lowest price of the stock on the given date.
- **Vol.**: The volume of shares traded on the given date (in thousands or millions).
- **Change %**: The percentage change in the stock price compared to the previous day.

File Name: `Goldman Sachs Stock Price History (02.05.2024-29.11.2024).csv`

---

## Tools and Technologies Used
- **Python**: Primary programming language for data analysis and visualization.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.
- **Plotly**: For creating interactive visualizations.
- **Dash**: For building the interactive web dashboard.
- **Jupyter Notebook**: For writing and executing the code.

---

## Key Features of the Project
1. **Data Cleaning**:
   - Handle missing values and convert columns to appropriate data types.
   - Convert `Vol.` column to numeric format by handling `K` (thousands) and `M` (millions) suffixes.
   - Clean the `Change %` column by removing the `%` sign and converting it to a percentage.

2. **Visualizations**:
   - **Line Chart**: Shows the stock price trend over time.
   - **Candlestick Chart**: Displays the open, high, low, and close prices for each day.
   - **Volume Chart**: Visualizes the volume of shares traded over time.
   - **Histogram**: Shows the distribution of daily price changes.

3. **Interactive Dashboard**:
   - Built using **Dash**, the dashboard allows users to:
     - Filter data by date range.
     - View updated charts based on the selected date range.

---

## How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Dawit0101/Goldman-Sachs-Stock-Analysis.git
   cd Goldman-Sachs-Stock-Analysis
