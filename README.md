# Flight Delay and Cancellation Prediction

## **Overview**
This project aims to predict whether a flight will be delayed, cancelled, or diverted based on historical flight data. By utilizing machine learning models, the solution helps airlines and passengers better anticipate potential disruptions.

---


## **Dataset Description**
Database used :https://www.kaggle.com/datasets/umeradnaan/flight-delays-dataset

## Methodology

1. **Data Preprocessing:** The dataset is cleaned and preprocessed by removing irrelevant characters, converting text to lowercase, removing stop words, and applying stemming.
2. **Feature Extraction:** TF-IDF (Term Frequency-Inverse Document Frequency) is used to extract features from the text data.
3. **Model Training:** A Logistic Regression model is trained on the preprocessed data.
4. **Model Evaluation:** The model's performance is evaluated using accuracy score on both training and testing data.

## **Future Improvements**
1. Experiment with advanced models such as XGBoost, LightGBM, or CatBoost.
2. Address class imbalance using techniques like SMOTE or class weights.
3. Add more features (e.g., weather conditions, air traffic congestion).
4. Implement time-series models for sequential analysis of delays.

---

## **Dependencies**
- Python 3.8+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`

Install dependencies using:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib joblib
```

---

## **Usage**
1. Clone the repository and navigate to the project directory.
2. Place the dataset file (`flight_data.csv`) in the root directory.
3. Run the notebook or script:

```bash
python flight_prediction.py
```
4. View the predictions and model performance metrics.

--

## **Results and Performance**
- **Accuracy**: ~71%
- Confusion Matrix and Classification Report are used to evaluate detailed performance.
- Feature importance indicates which factors most influence flight delays and disruptions.

---
