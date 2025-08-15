# 🌍 Global Food Prices Trending & Forecasting

## 📌 About the Project

This project analyzes global food price trends over time and forecasts future prices using statistical and machine learning models. It involves **data cleaning, exploratory data analysis (EDA), visualizations, and forecasting** to identify patterns and provide insights for stakeholders such as policymakers, researchers, and economists.

The goal is to **understand historical trends in food prices** and **predict future movements**, helping in informed decision-making for agriculture, trade, and food security planning.

---

## 📊 Dataset Details

The dataset used in this project contains **global food price indices** over monthly and annual periods. Key features include:

* **Date / Year** – Time of data recording
* **Food Price Index** – Overall food price measure
* **Commodity-specific Indices** – Prices for categories like cereals, dairy, meat, sugar, and oils
* **Source** – [FAO (Food and Agriculture Organization) Statistics Database](https://www.fao.org/faostat/)

---

## 🛠 Data Preprocessing & Analysis

1. **Data Import & Cleaning**

   * Removed missing and duplicate values
   * Converted date columns to proper datetime format
   * Normalized index values for better comparison

2. **Exploratory Data Analysis (EDA)**

   * Identified long-term trends in food prices
   * Observed seasonal patterns
   * Compared commodity-specific trends

---

## 📈 Visualizations Created

* **Line Charts** – Trends in overall and commodity-wise food prices
* **Heatmaps** – Correlation between different commodity price indices
* **Bar Charts** – Yearly comparison of food price indices
* **Time Series Plots** – Highlighting seasonal and trend components
* **Forecast Plots** – ARIMA and Prophet-based future predictions

---

## 🔮 Forecasting Models Used

* **ARIMA (AutoRegressive Integrated Moving Average)** – For short-term trend forecasting
* **Prophet (Facebook)** – For seasonality-aware forecasting

Both models were evaluated and compared for accuracy, with forecast visualizations generated for the coming months/years.

---

## 📚 Learning Outcomes

Through this project, I learned:

* How to **clean and preprocess time-series datasets**
* Applying **EDA techniques** for identifying trends and patterns
* Creating **meaningful visualizations** using Matplotlib and Seaborn
* Building and tuning **time-series forecasting models**
* Comparing model performance for predictive analytics
* Structuring a **data science project for real-world use cases**

---

## 📦 Technologies Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Statsmodels** (ARIMA)
* **Facebook Prophet** (Forecasting)
* **Jupyter Notebook** (Development)

---

## 📜 Project Structure

```
Global-Food-Prices-Forecasting/
│
├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks with code
├── visuals/              # Generated graphs and plots
├── README.md              # Project documentation
└── requirements.txt       # Dependencies
```
