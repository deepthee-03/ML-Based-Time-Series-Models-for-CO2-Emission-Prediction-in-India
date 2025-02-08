# 🌍 Machine Learning-Based Time Series Models for CO2 Emission Prediction in India

## 🚀 Overview
This project focuses on predicting India's CO2 emissions over the next decade using **machine learning** and **statistical models**. By analyzing past CO2 emission trends, this system helps forecast future emissions, providing valuable insights for policymakers and researchers.

## 🌟 Key Features
1. **Multi-Model Forecasting** 📊:
   - Implementation of multiple models including **ARIMA, SARIMAX, Holt-Winters, Random Forest Regressor, and LSTM** for comprehensive CO2 emission predictions.
2. **Performance Evaluation** 📈:
   - Models are assessed using various metrics such as **RMSE, MSE, MAE, R² Score, and more** to determine the most effective approach.
3. **Accurate Emission Predictions** 🔍:
   - By leveraging **time series analysis**, this project enhances forecasting accuracy, making it a valuable tool for **environmental sustainability efforts**.

## 🔬 Methodology
### Step-by-Step Process:
1. **Data Preprocessing**:
   - The dataset is cleaned by handling missing values and normalizing data for better model accuracy.
2. **Model Training & Evaluation**:
   - Time series models including **ARIMA, SARIMAX, Holt-Winters, Random Forest, and LSTM** are trained and evaluated.
3. **Comparison & Performance Metrics**:
   - Model performance is compared based on **RMSE, MAE, MAPE, and R² Score**.
4. **Forecasting CO2 Emissions**:
   - The best-performing model is used to **predict India's CO2 emissions for the next decade**.

## 🎯 Results
- **Baseline Model**:
  - Initial models without data preprocessing yielded **moderate accuracy**.
- **Enhanced Model**:
  - After applying preprocessing and hyperparameter tuning, **LSTM emerged as the best model** with significantly lower error rates.

These results demonstrate the **effectiveness of deep learning** in CO2 emission forecasting.

## 🔧 Technologies Used
- **Time Series Analysis**: ARIMA, SARIMAX, Holt-Winters
- **Machine Learning**: Random Forest Regressor
- **Deep Learning**: LSTM (Long Short-Term Memory)
- **Programming Languages**: Python
- **Libraries and Frameworks**: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Statsmodels

## ⚙️ Installation
To run this project locally, follow these steps:

1️⃣ Clone the repository:
```sh
git clone https://github.com/your-username/your-repo-name.git
```
cd your-repo-name
2️⃣ Install dependencies:
```sh
pip install -r requirements.txt
```
## 🚀 Usage
1️⃣ Load the dataset and preprocess it.
```sh
python preprocess.py
```
2️⃣ Choose a model and run the forecasting script.
ARIMA Model:
```sh
python arima_model.py
```
SARIMAX Model:
```sh
python sarimax_model.py
```
Holt-Winters Model:
```sh
python holt_winters.py
```
Random Forest Regressor:
```sh
python random_forest.py
```
LSTM Model:
```sh
python lstm_model.py
```
3️⃣ Evaluate the model's performance using the provided metrics.
```sh
python evaluate.py
```
## 📊 Results
🏆 LSTM was identified as the best model due to its high accuracy and low error rates.
📌 A detailed comparison of models based on various metrics is available in the results section.

## 🔮 Future Work
🔹 Incorporate additional external factors such as policy changes and technological advancements.
🔹 Improve model performance with more advanced deep learning techniques.

## 🤝 Contributing
We welcome your contributions! Fork this repository and submit a pull request to share your ideas and improvements.

## 📧 Contact
Have questions or suggestions? Reach out at deepthee16@gmail.com.
