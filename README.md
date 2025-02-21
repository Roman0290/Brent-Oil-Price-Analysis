# Brent Oil Price Change Analysis

## Overview
Analyzing Brent oil price fluctuations due to global events using change point analysis and time series modeling. Insights aid investors, analysts, and policymakers in decision-making.

## Business Objective
Investigate how political decisions, conflicts, sanctions, and OPEC policies impact Brent oil prices. Provide data-driven insights for strategic decision-making.

## Dataset
- **Period:** May 20, 1987 - September 30, 2022
- **Fields:**
  - **Date:** Recorded in `day-month-year` format
  - **Price:** Brent oil price in USD per barrel

## Project Tasks
###  Data Analysis Workflow
- Define workflow and analysis steps
- Understand data sources and time series models (ARIMA, GARCH)
- Identify effective result communication strategies

### Statistical Analysis
- Perform Exploratory Data Analysis (EDA)
- Apply time series models (VAR, Markov-Switching ARIMA, LSTM)
- Investigate economic, technological, and political influences
- Validate model predictions with backtesting and cross-validation

### Interactive Dashboard
Build a Flask-React dashboard for data visualization.
- **Backend (Flask):** API for model results
- **Frontend (React):** Interactive charts and filters
- **Features:** Event highlights, historical trends, volatility metrics

## Technologies Used
- **Data Analysis:** Python (pandas, NumPy, statsmodels, scikit-learn)
- **Modeling:** ARIMA, GARCH, VAR, LSTM
- **Dashboard:** Flask (backend), React (frontend)
- **Visualization:** Recharts, Chart.js, D3.js

## Setup
### Prerequisites
- Python 3.x, Flask
- Node.js, npm

### Installation
```sh
# Clone the repository
git clone https://github.com/Roman0290/Brent-Oil-Price-Analysis.git
cd Brent-Oil-Price-Analysis

# Backend setup
cd backend
pip install -r requirements.txt
python app.py

# Frontend setup
cd frontend
npm install
npm start
```



