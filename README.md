# Crypto-Data-Science-Project

# Crypto Trading Behavior & Market Sentiment Analysis

## Overview

This project analyzes the relationship between **Bitcoin market sentiment** and **trader behavior** using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The objective is to uncover behavioral patterns, profitability trends, risk-taking dynamics, and market psychology insights that can help design smarter trading strategies and sentiment-aware analytics systems.

The project combines:

* Exploratory Data Analysis (EDA)
* Behavioral Finance Analytics
* Time-Series Analysis


---

# Project Objectives

The project aims to answer the following key questions:

* How does market sentiment influence trader profitability?
* Do traders become more aggressive during Greed periods?
* Does Fear improve trading discipline?
* Which trader behaviors lead to higher profitability?
* Can machine learning identify profitable trading patterns?
* Can unusual trading behavior be automatically detected?

---

# Datasets Used

## 1. Hyperliquid Historical Trader Dataset

Contains:

* Account IDs
* Trading pairs
* Execution prices
* Trade sizes
* Fees
* Trade timestamps
* Closed PnL
* Direction (BUY/SELL)

### Key Columns

| Column          | Description            |
| --------------- | ---------------------- |
| Account         | Trader wallet/account  |
| Coin            | Trading pair           |
| Execution Price | Trade execution price  |
| Size USD        | Trade size in USD      |
| Side            | BUY / SELL             |
| Closed PnL      | Profit/Loss from trade |
| Fee             | Trading fee            |
| Timestamp IST   | Trade execution time   |

---

## 2. Bitcoin Fear & Greed Index Dataset

Contains:

* Daily market sentiment
* Sentiment classification
* Fear-Greed numerical score

### Key Columns

| Column         | Description            |
| -------------- | ---------------------- |
| classification | Fear / Greed category  |
| value          | Fear-Greed index score |
| date           | Daily timestamp        |

---

# Tech Stack

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
plotly

```

---

# Project Workflow

## Phase 1 — Data Understanding

* Dataset inspection
* Data type analysis
* Missing value analysis
* Statistical summaries
* Initial visualization

---

## Phase 2 — Data Cleaning & Preprocessing

* Timestamp conversion
* Duplicate removal
* Feature engineering
* Sentiment data merging
* Data validation

### Engineered Features

* Profit flag
* Trade hour
* Trade day
* Fee percentage
* Risk score
* Trading sessions

---

## Phase 3 — Exploratory Data Analysis (EDA)

Performed:

* Sentiment analysis
* Profitability analysis
* Trading activity analysis
* Coin-level analysis
* Time-based analysis
* Whale trade analysis

### Visualizations Included

* Sentiment distribution
* PnL distribution
* Trade size analysis
* Correlation heatmaps
* Trading activity timelines
* Profitability by sentiment

---


# Project Structure

```text
Crypto Project Report.pdf
notebook.ipynb
```

---

# How to Run

## Clone Repository

```bash
git clone <repository-link>
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Launch Notebook

```bash
jupyter notebook
```

Open:

```text
notebook.ipynb
```

---

# Future Improvements

Possible future enhancements:

* Deep Learning models for profitability prediction
* Real-time sentiment integration
* Live trading dashboard using Streamlit
* Reinforcement learning for trading strategy optimization
* Portfolio optimization engine
* NLP-based crypto news sentiment analysis

---

# Business Value

This project demonstrates how:

* market psychology
* trader behavior
* sentiment analysis
* machine learning

can be combined to build:

* trading intelligence systems
* behavioral analytics platforms
* quantitative research pipelines

---

# Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Behavioral Analytics
* Financial Data Science
* Time-Series Analysis


---

# Final Conclusion

The analysis demonstrates a strong relationship between market sentiment and trader behavior in crypto markets. Traders become more aggressive during Greed periods and more cautious during Fear periods. High-performing traders appear to maintain better discipline, lower emotional exposure, and stronger risk management practices.


# Future Additions (Due to limited limit I can not add it)
1)Predictive Modeling

Built a Random Forest classifier to predict:

profitable vs non-profitable trades


2)Anomaly Detection

Applied Isolation Forest to detect:

abnormal trades
unusual losses
extreme profit events


3)Time-Series Trend Analysis

Analyzed:

rolling profitability
daily activity
sentiment-driven market regimes


4)Strategy Recommendation Engine

Created sentiment-aware rule-based trading recommendations.

This project highlights how behavioral finance and machine learning techniques can be used together to generate actionable trading intelligence and improve decision-making in volatile crypto markets.
