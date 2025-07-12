# SmartChurn — Customer Churn Prediction 🎧📉

> Predicting music platform customer churn using Machine Learning and Deep Learning models.

---

## 📌 Project Description

This project aims to predict whether a user of a music streaming platform will **churn** (i.e., cancel their subscription) based on their behavior, subscription type, location, and interaction with the platform.

We applied **classification models** to a labeled dataset to identify users likely to leave, helping businesses take action to retain them.

---

## 🧠 Models Used

- 🎯 **Random Forest**
- ⚡ **LightGBM**
- 📈 **XGBoost**
- 🤖 **TensorFlow Neural Network (DNN)**

After preprocessing and hyperparameter tuning (with GridSearchCV), the best-performing model achieved:

- **Accuracy**: `~83%`
- **AUC Score**: `~0.92`

---

## 📊 Features Used

- Demographics (e.g., age, location)
- Subscription type and payment plan
- Engagement metrics (session length, songs played, skip rate)
- Customer service interactions
- Notifications and playlist activity

---