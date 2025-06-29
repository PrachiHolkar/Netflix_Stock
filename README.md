# 📊 Netflix Stock Price Analysis Using Python

## 🧠 Project Objective

The goal of this project was to analyze Netflix's historical stock data from **May 2002 to June 2025**, uncovering patterns in price movement, volatility, and performance over time. 

---

## 📁 Dataset

The dataset includes historical daily stock prices for Netflix:
- `date`, `open`, `high`, `low`, `close`, `adj_close`, `volume`

---

## 🧹 Step 1: Data Cleaning & Preparation

- Removed redundant header row
- Converted `date` column type to `datetime` and set it as index for time series operations
- Ensured numeric columns were properly typed
- Checked for missing/null values
- Calculated new features like `daily_return`, `30-day` and `90-day` moving averages

---

## 📈 Step 2: Visual Analysis & Insights

### 1. **Closing Price Over Time**
- Early stage (2002–2012): Flat or slow growth
- Growth phase (2013–2021): Rapid price increase, especially around 2020
- Volatile movement (2022–2023): Rise of competing streaming services
- Sharp rise again (2024–2025): Reflects possible market optimism

### 2. Daily Return Over Time
💡 daily_return = (today's close - yesterday's close) / yesterday's close
- Some days have returns as high as +40% or -40%, although rare.
- Most values hover between -5% and +5%, which is typical for daily returns.

### 3. Moving Averages
- The green wavy line (daily close) fluctuates a lot — shows volatility.
- Red line (30-day avg): Reacts faster to recent changes.
- Blue line (90-day avg): Shows the macro trend — smooth and delayed.

### 4. Yearly Average Return
- Green bars showed positive years, while red bars indicated negative years.
- Some years (like 2002, 2004, 2011, 2022) showed noticeable declines.
  
### 5. Key Statistical Summary
- Highest Close Price:	$1250.52
- Date of High:	June 5, 2025
- Lowest Close Price:	$0.37
- Date of Low:	October 9, 2002

- Netflix’s stock price grew by approximately 335,243% from its lowest point ($0.37 on 2002-10-09) to its highest ($1250.52 on 2025-06-05) — that's massive growth! 

---

## 🛠️ Tools Used
- Python 
- Pandas for data wrangling
- Matplotlib & Seaborn for data visualization
- PercentFormatter for axis formatting
- Jupyter Notebook for step-by-step execution

---

## 📫 Contact

If you found this project insightful or want to collaborate, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/prachi-holkar/) or reach out via email (holkarprachi@hotmail.com)
