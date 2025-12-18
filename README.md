# Energy Consumption Forecasting

This project focuses on forecasting household energy consumption using historical numerical data. 
Both classical time-series modeling and machine learning approaches are implemented and compared.

---

## 📌 Project Overview

The goal of this project is to predict future energy consumption based on past observations.  
Daily aggregated energy usage data is modeled using:

- **ARIMA** as a statistical baseline for time-series forecasting
- **XGBoost** with lag-based feature engineering to capture non-linear patterns

Model performance is evaluated using **MAE** and **RMSE** metrics.

---

## 🧠 Models Used

### 1. ARIMA (Baseline Model)
- Used to capture overall trend and level in the time series
- Serves as a strong statistical baseline
- Handles non-stationarity through differencing

### 2. XGBoost (Machine Learning Model)
- Converts time series into a supervised learning problem
- Uses lag features (previous time steps) as inputs
- Better captures short-term variations and non-linear relationships

---

## 📊 Workflow

1. Data loading and preprocessing  
2. Daily resampling of energy consumption  
3. Time-based train–test split  
4. Model training (ARIMA & XGBoost)  
5. Model evaluation using MAE and RMSE  
6. Performance comparison and visualization  

---

## 📂 Dataset

This project uses the **Individual Household Electric Power Consumption** dataset from the UCI Machine Learning Repository.

Due to GitHub file size limits, the raw dataset is **not included** in this repository.

🔗 **Download link:**  
https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

After downloading, place the file in the following path:
data/household_power_consumption.txt

---

## 🛠 Tech Stack

- Python
- pandas, numpy
- statsmodels
- scikit-learn
- XGBoost
- matplotlib

---

## 📈 Key Insights

- ARIMA provides a stable baseline forecast but smooths short-term fluctuations.
- XGBoost performs better by learning complex patterns from historical data.
- Feature-based machine learning models can outperform classical time-series models for this task.

---

## 🚀 How to Run

1. Clone the repository  
2. Create a virtual environment and install dependencies  
3. Download the dataset and place it in the `data/` folder  
4. Run the notebook inside the `notebooks/` directory  

---

## 📬 Author

**Venkatesh Badiger**  
AI & Data Science Undergraduate  
