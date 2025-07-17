
# ✈️ Flight Delay Prediction

This project focuses on predicting flight delays using various machine learning algorithms, with an emphasis on regression techniques. The goal is to assist airlines in proactively managing schedules, resources, and customer satisfaction.

## 📊 Problem Statement

**Objective:**  
Predict the arrival delay of domestic flights based on historical and operational data.

**Why it Matters:**  
Flight delays are a major concern in the aviation industry, resulting in operational disruptions, financial losses, and customer dissatisfaction.

---

## 📁 Dataset

- **Source:** [Kaggle - US Domestic Flights (2015)]  
- **File:** `flights.csv`  
- **Features Include:**
  - `LATE_AIRCRAFT_DELAY`
  - `AIRLINE_DELAY`
  - `AIR_SYSTEM_DELAY`
  - `WEATHER_DELAY`
  - `DEPARTURE_TIME`
  - `DEPARTURE_DELAY`
  - `DISTANCE`
  - `ARRIVAL_DELAY` *(Target Variable)*

---

## 🛠️ Methods Used

- **Linear Regression**
- **Random Forest Regressor**
- **Ordinary Least Squares (OLS) Regression**

---

## 🧪 Model Evaluation

| Model                   | MSE        | R² Score   |
|------------------------|------------|------------|
| Linear Regression       | 0.167      | 0.99995    |
| Random Forest Regressor| 115.78     | 0.96678    |
| OLS Regression          | 0.101      | 0.99997    |

✅ **Best Model:** OLS Regression

---

## 📈 Performance Metrics

- **MSE (Mean Squared Error)**: Measures the average squared difference between predicted and actual values.
- **R² Score**: Proportion of variance explained by the model.

---

## 🔍 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Conclusion

Predictive modeling enables airlines to optimize operations, improve customer satisfaction, and reduce financial losses due to delays. OLS regression emerged as the most effective model in our tests.

---

## 📽️ Presentation

The PowerPoint presentation summarizing this project is included under the `presentation/` folder.

---

## 📌 Applications

- Delay prediction for airline yield management
- Extension to other transport systems
