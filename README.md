# Web Traffic Modelling

A data analytics and machine learning project aimed at predicting website page views based on key traffic metrics such as Visitors, Bounce Rate, and Average Time Spent.

## 📊 Project Overview

This project explores real-world web traffic data collected over multiple months. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation using several regression algorithms.

## 🔍 Objective

To build and compare predictive models that estimate the number of `Page Views` using:
- `Visitors`
- `Bounce Rate`
- `Average Time Spent`

## 🛠️ Tools & Libraries

- **Python**
- `pandas` — data manipulation
- `numpy` — numerical operations
- `matplotlib`, `seaborn` — data visualization
- `scikit-learn` — machine learning models and evaluation

## 📁 Dataset

Multiple `.xlsx` files representing monthly web traffic statistics were loaded and merged. Preprocessing included:
- Filling and dropping missing values
- Encoding and converting time/percentage fields
- Feature scaling using `StandardScaler`

## ⚙️ Models Used

- **Linear Regression**
- **Support Vector Regression (SVR)**
- **K-Nearest Neighbors Regression (KNN)** with GridSearchCV

## 📈 Model Evaluation

Each model was evaluated on:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score (Coefficient of Determination)

Additionally, the results were visualized using:
- Scatter plots (Actual vs Predicted)
- Residual plots
- Feature correlation heatmaps
- Monthly Page View bar charts

## 🧠 Key Insights

- Proper data preprocessing significantly improves model performance.
- Linear and KNN models performed best in terms of interpretability and accuracy.
- Data visualization helped validate assumptions and spot outliers.

## 💡 Future Improvements

- Incorporate more features such as device types, referral links, or bounce sessions.
- Deploy the best model as a web service (e.g., Flask + Heroku).
- Explore time-series models for trend-based forecasting.

## 👨‍💻 Contributors

Kelvin Sim Huan Siang (and team members)
