# DAC ITS 2024 – Solar Energy Prediction with CNN-LSTM

## 🌞 Overview
This project was developed for the **Data Analytics Competition (DAC) ITS 2024**, aimed at predicting solar energy output using a hybrid deep learning model combining **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory (LSTM)**. Accurate forecasting helps address the challenges of grid stability and sustainability in renewable energy.

## 🎯 Objectives
- Predict solar power output based on irradiance and weather data
- Utilize a CNN-LSTM hybrid model to capture both spatial and temporal features
- Enhance forecasting reliability for the energy sector

## 🧾 Dataset
- `train.csv`: Solar and weather data (Jan 2014 – Sep 2017)
- `test.csv`: Data for Oct–Dec 2017
- `sample_submission.csv`: Submission format
- `metadata.csv`: Feature descriptions
- `Solar_Irradiance_YYYY.csv`: Historical irradiance data for 2014–2017

## 🔧 Preprocessing Pipeline
- Datetime parsing and alignment across datasets
- Merging weather, irradiance, and power output data
- Outlier handling with IQR method
- Null value imputation and duplicate removal
- Feature scaling and one-hot encoding

## 🧠 Model Architecture
- CNN layers to extract spatial patterns
- LSTM layer to capture sequential dependencies
- Dense layers with dropout for regularization

## 📊 Evaluation
- Metric: **Mean Absolute Error (MAE)** ≈ 0.03 on validation set
- Visual analysis: Time-series plots, loss/MAE curves, prediction comparison
- CNN-LSTM demonstrated high accuracy in short-term forecasting

## 📈 Tools & Libraries
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`, `plotly`, `altair`, `missingno`

## 📎 Related Paper
- Hybrid CNN-LSTM-RF for Time Series Forecasting, Elsevier 2024
- Deep Learning Enhanced Solar Energy Forecasting with AI-Driven IoT, Wiley 2021
