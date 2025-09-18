
# Energy Consumption Big Data Analysis & Forecasting

## 📌 Project Overview
This project explores large-scale **energy consumption data** from London households (Low Carbon London project, Nov 2011 – Feb 2014).  
It combines **data analysis** and **time series forecasting** to uncover consumption patterns, correlations with weather/demographics, and predict future energy usage.  

The pipeline includes:
- Preprocessing and cleaning of smart meter data
- Exploratory data analysis and visualization
- Clustering households by consumption behavior
- **Time series forecasting using deep learning models**

---

## ⚙️ Features
- 📊 **Data Analysis**: Trends, seasonal patterns, anomalies  
- 🌦 **Weather & Demographic Integration**  
- 🏠 **Household Clustering** for energy behavior profiling  
- 🔮 **Forecasting Models Implemented**:
  - Naïve Forecast
  - Multi-Layer Perceptron (MLP)
  - Convolutional Neural Network (CNN)
  - Recurrent Neural Network (RNN)
  - Long Short-Term Memory (LSTM)
  - Gated Recurrent Unit (GRU)

---

## 📈 Forecasting Results
- Among all models, **MLP (Multi-Layer Perceptron)** achieved the **best performance** on forecasting tasks.  
- MLP outperformed CNN, RNN, LSTM, and GRU in terms of accuracy and stability.  
- Forecasting results highlight the potential of simple feedforward networks in energy demand prediction.

---

## 📂 Dataset
- **Source**: Low Carbon London project  
- **Components**:
  - `energy.csv` → Smart meter consumption data (2011–2014)  
  - `weather.csv` → Daily weather data (from Dark Sky API)  
  - `demographics.csv` → Household demographic info  

---

## 🛠️ Tech Stack
- **Languages**: Python (Jupyter Notebook)  
- **Libraries**:
  - `pandas`, `numpy` → Data processing
  - `matplotlib`, `seaborn` → Visualization
  - `scikit-learn` → Clustering & ML
  - `tensorflow`, `keras`, `pytorch` → Deep learning models
  - `statsmodels` → Time series forecasting
  - `pyspark` → Big data handling (optional extension)

---
