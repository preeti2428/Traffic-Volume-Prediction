# 🚦 Traffic Volume Prediction

A machine learning project to predict hourly traffic volume on Interstate 94 using weather and temporal features. The project compares the performance of three regression models: *Linear Regression, **Random Forest, and **XGBoost*.

---

## 📌 Project Overview

This project uses the Metro Interstate Traffic Volume dataset to:

- Explore and preprocess real-world traffic data.
- Train and evaluate multiple regression models.
- Identify key features that influence traffic patterns.
- Visualize results and feature importances.

---

## 🔍 Problem Statement

Predict the number of vehicles passing through a highway per hour using environmental and time-based features. This can help city planners and traffic control authorities optimize road usage and planning.

---

## 📁 Dataset

- *Name:* Metro Interstate Traffic Volume
- *Source:* [Kaggle Dataset](https://www.kaggle.com/datasets/utsa/my-encoded-traffic-volume-dataset)
- *Features include:*
  - Weather conditions (temperature, rain, snow, clouds)
  - Time-related features (hour, day, month)
  - Encoded categorical weather descriptions
- *Target:* traffic_volume — number of vehicles on I-94 highway per hour

---

## 📊 Models Used

| Model               | Description |
|--------------------|-------------|
| *Linear Regression* | Baseline model to capture linear trends |
| *Random Forest Regressor* | Ensemble model to capture complex non-linear relationships |
| *XGBoost Regressor* | Gradient boosting model for high accuracy |

---

## 🛠 Libraries and Tools

- pandas, numpy – Data manipulation
- matplotlib, seaborn – Visualization
- scikit-learn – Machine learning tools
- xgboost – Advanced gradient boosting

---

## 🧪 How to Run

1. Clone this repo:

    bash
    git clone https://github.com/your-username/traffic-volume-prediction.git
    cd traffic-volume-prediction
    

2. Install required libraries:

    bash
    pip install -r requirements.txt
    

3. Run the notebook or script:

    - *Google Colab*: Upload the notebook and dataset
    - *Local*: Ensure the CSV file is in the working directory

---

## 📈 Evaluation Metrics

- *MAE* – Mean Absolute Error
- *RMSE* – Root Mean Squared Error
- *R² Score* – Coefficient of determination

---

## 📌 Key Results

- Best performance achieved using *Random Forest* and *XGBoost*.
- Important predictors: weather conditions, hour of day, and temperature.
- Visualizations reveal traffic peaks during rush hours and dips during weekends.

---

## 📊 Visualizations

- Traffic volume distribution by hour and day
- Feature importance bar charts
- Error metrics comparison table

---

## ✅ Conclusion

This project demonstrates how machine learning models can effectively forecast traffic volume based on environmental and temporal data. The results can support traffic management systems and infrastructure planning.

---

## 🤝 Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

