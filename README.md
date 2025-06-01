# 🌦️ Weather Trend Forecasting

> **Tech Assessment Project**

A comprehensive Data Science project focused on analyzing and forecasting global weather patterns using advanced machine learning and deep learning models.

---

## 📌 Objective

To analyze the **"Global Weather Repository.csv"** dataset and forecast future weather trends using multiple modeling techniques. This project demonstrates both basic and advanced data science capabilities, including preprocessing, exploratory analysis, and multi-model forecasting.

---

## 📂 Dataset

- **Name:** Global Weather Repository  
- **Source:** [Kaggle - Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code)  
- **Description:** Contains daily weather information from cities around the globe with over **40+ features**, including temperature, humidity, precipitation, wind speed, and more.

---

## 🔍 Project Overview

### ✅ Basic Assessment

- **Data Cleaning & Preprocessing:**
  - Handled missing values and outliers.
  - Normalized relevant features for modeling.
  - Converted time-related columns to datetime format.

- **Exploratory Data Analysis (EDA):**
  - Identified seasonal patterns in temperature and precipitation.
  - Correlation analysis between temperature, humidity, and air quality.
  - Visualized trends using line charts, heatmaps, and bar plots.

- **Model Building:**
  - Used `lastupdated` as the time-series anchor.
  - Developed a baseline forecasting model.
  - Evaluated model performance using MAE, RMSE, and R² scores.

### 🚀 Advanced Assessment

- **Advanced EDA:**
  - Detected and analyzed anomalies in climate patterns.
  - Clustered similar weather profiles using K-Means.

- **Forecasting Models Implemented:**
  1. **ARIMA (AutoRegressive Integrated Moving Average)**  
     - Time-series model suitable for stationary data.
  2. **LSTM (Long Short-Term Memory Networks)**  
     - Deep learning model to capture sequential patterns.
  3. **Random Forest Regressor**  
     - Ensemble learning model to understand feature interactions.

- **Model Comparison & Ensemble:**
  - Compared the models based on forecasting accuracy.
  - Created an ensemble to combine model predictions for enhanced performance.

- **Unique Analyses:**
  - **Climate Analysis:** Studied regional climate variation over time.
  - **Air Quality Impact:** Correlated AQI with temperature, wind, and humidity.
  - **Feature Importance:** Used SHAP & permutation importance to rank features.
  - **Spatial Analysis:** Visualized geographic distribution of weather trends using maps and GeoPandas.

---

## 🧠 Technologies Used

| Category            | Tools / Libraries                      |
|---------------------|-----------------------------------------|
| Language            | Python 3.x                              |
| Data Handling       | Pandas, NumPy                           |
| Visualization       | Matplotlib, Seaborn, Plotly, GeoPandas |
| Modeling            | scikit-learn, statsmodels, Keras, TensorFlow |
| Forecasting Models  | ARIMA, LSTM, Random Forest              |
| Others              | Jupyter Notebook, VS Code               |

---

## 📈 Sample Visuals

![Trend Example](https://via.placeholder.com/600x250.png?text=Temperature+Trends+Over+Years)
*Line plot showing average temperature trends across continents*

![Model Comparison](https://via.placeholder.com/600x250.png?text=Model+Performance+Comparison)
*Bar chart comparing ARIMA, LSTM, and Random Forest model accuracy*

---

## 📋 Results & Insights

- LSTM performed best for temperature prediction due to temporal dependencies.
- Random Forest provided strong performance on short-term forecasts with high feature importance interpretability.
- ARIMA was effective but limited to univariate prediction.
- Air Quality showed strong inverse correlation with humidity and wind speed.
- Notable regional climate anomalies identified in tropical vs. temperate zones.

---

## 🧾 Project Structure
![image](https://github.com/user-attachments/assets/bebef9d0-5da2-4e45-805e-fce312b9156a)


---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-trend-forecasting.git
   cd weather-trend-forecasting
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
