🏎️ F1 Race Prediction - Complete Setup Guide

📌 Overview

This project predicts Formula 1 race positions using machine learning (XGBoost). It analyzes historical F1 race data, including driver performance, team strength, pit stops, and lap times, to forecast race outcomes accurately.

🚀 Running the Project Locally (GitHub)

1️⃣ Clone the Repository

To get started, clone the repository from GitHub:

git clone https://github.com/dhanushkumarms/dpl_hackathon.git
cd dpl_hackathon

2️⃣ Install Dependencies

Ensure all required libraries are installed:

pip install -r requirements.txt

3️⃣ Run the Model

Execute the Python script to train and test the model:

python f1_prediction.py

4️⃣ Understanding the Output

Predictions: Displays predicted driver positions.

Performance Metrics: Outputs MAE, RMSE, and R² scores.

Visualization: Generates graphs showing actual vs. predicted positions.

🌐 Running the Project on Google Colab

1️⃣ Open Google Colab & Mount Drive

Mount your Google Drive to access files:

from google.colab import drive
drive.mount('/content/drive')

2️⃣ Change Directory to Project Folder

import os
os.chdir('/content/drive/My Drive/dpl_hackathon/')

3️⃣ Open and Run the Notebook

Navigate to f1_prediction.ipynb in Colab.

Run all cells to train and evaluate the model.

🛠️ Project Components

🔹 Dataset Files

circuits.csv - Circuit details (location, altitude, country)

constructors.csv - Team details & nationalities

drivers.csv - Driver information (name, nationality, experience)

lap_times.csv - Lap-by-lap performance data

pit_stops.csv - Pit stop timings and frequency

qualifying.csv - Qualifying session results

races.csv - Race schedule and results

results.csv - Final race outcomes and driver standings

🔹 Model & Training Details

Algorithm Used: XGBoost Regressor

Feature Engineering:

Driver experience, team strength, pit stop frequency, grid advantage

Lap time efficiency, constructor performance trends

Train-Test Split: 80% training, 20% testing

Hyperparameter Tuning: Optimized learning rate, estimators, tree depth

Evaluation Metrics: MAE, RMSE, R² Score

🔹 Key Outputs & Insights

Feature Importance: Identifies top race outcome factors

Actual vs Predicted Scatterplot: Evaluates model accuracy

Driver & Constructor Trends: Performance trends over time

Track Difficulty Impact: Influence of circuits on driver rankings

📦 Additional Features

Live Data Integration (Future Scope): Incorporating real-time weather and track conditions.

Web Deployment: Plan to deploy using Flask/Django for interactive predictions.

Hyperparameter Optimization: Future improvements with GridSearchCV for fine-tuning.

🎯 Conclusion

This project provides a data-driven approach to Formula 1 race predictions, helping teams and analysts optimize race strategies. Future enhancements will integrate real-time data, advanced ML models, and web-based prediction tools.



