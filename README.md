# 🏎️ F1 Race Prediction

This project predicts Formula 1 race positions using machine learning (XGBoost). It analyzes historical race data—including driver performance, team strength, pit stops, lap times, and more—to forecast race outcomes with high accuracy.

---

## 📌 Overview

An end-to-end predictive analytics pipeline for F1 racing that includes:
- Data preprocessing and feature engineering
- Model training using XGBoost Regressor
- Evaluation via MAE, RMSE, R²
- Visualization of predictions vs actuals

---

## 🚀 Running the Project Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/dhanushkumarms/dpl_hackathon.git
cd dpl_hackathon
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Model
```bash
python f1_prediction.py
```

### 4️⃣ Output Includes
- 📊 **Predicted Positions**
- 📈 **Evaluation Metrics**: MAE, RMSE, R²
- 📉 **Visualization**: Actual vs. Predicted Scatterplots

---

## 🌐 Running on Google Colab

### 1️⃣ Mount Google Drive
```python
from google.colab import drive
drive.mount('/content/drive')
```

### 2️⃣ Change to Project Directory
```python
import os
os.chdir('/content/drive/My Drive/dpl_hackathon/')
```

### 3️⃣ Run the Notebook
Open `f1_prediction.ipynb` and execute all cells to train and evaluate the model.

---

## 🛠️ Project Components

### 📁 Dataset Files

- `circuits.csv`: Track data (location, altitude)
- `constructors.csv`: Team info
- `drivers.csv`: Driver details
- `lap_times.csv`: Lap-by-lap data
- `pit_stops.csv`: Pit stop timings
- `qualifying.csv`: Qualifying results
- `races.csv`: Schedule and race meta
- `results.csv`: Final race standings

### 🧠 Model Architecture

- **Algorithm**: XGBoost Regressor

- **Features**:
  - Driver experience
  - Constructor strength
  - Pit stop frequency
  - Lap time efficiency
  - Grid position

- **Training**:
  - 80/20 Train-Test Split
  - Tuned hyperparameters (learning rate, estimators, depth)

- **Metrics**:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 📊 Key Insights

- 🧩 Feature importance ranking
- 📈 Scatterplot: Actual vs. Predicted positions
- 🔁 Performance trends across drivers and teams
- 🛣️ Track difficulty impact on rankings

---

## 🔮 Future Enhancements

- 🌦️ Live weather and real-time data integration
- 🌍 Web deployment via Flask/Django
- 🧪 Hyperparameter tuning with GridSearchCV
- ⏱️ Time series & real-time predictions

---

## 🎯 Conclusion

A comprehensive, data-driven approach to Formula 1 race predictions—designed to assist analysts, teams, and enthusiasts. With future support for live data and deployment, this project lays the foundation for an intelligent race strategy tool.

---

## 👨‍💻 Author

**Dhanush Kumar M S**  
GitHub: [@dhanushkumarms](https://github.com/dhanushkumarms)

---
