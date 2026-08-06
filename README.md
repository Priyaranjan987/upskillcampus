# ⛏️ Quality Prediction in a Mining Process using Machine Learning

## 📌 Project Overview

This project focuses on predicting the **% Silica Concentrate** in an iron ore flotation process using Machine Learning techniques. Predicting silica concentration in advance helps mining engineers optimize the flotation process, improve iron ore quality, reduce impurities, and minimize material loss.

The project was developed as part of an **Industrial Internship** conducted through **upskill Campus**, in collaboration with **The IoT Academy** and **UniConverge Technologies Pvt. Ltd.**

---

## 🎯 Objectives

- Predict **% Silica Concentrate** using real industrial process data.
- Compare multiple Machine Learning regression models.
- Identify the best-performing prediction model.
- Perform feature engineering and hyperparameter tuning.
- Enable future prediction for proactive decision-making.
- Build a deployable machine learning model.

---

## 📂 Dataset

- **Dataset Name:** Mining Process Flotation Plant Database
- **Records:** ~736,000
- **Features:** 24
- **Target Variable:** `% Silica Concentrate`

The dataset contains real operational parameters collected from an industrial mining flotation plant.

### Input Features

- % Iron Feed
- % Silica Feed
- Starch Flow
- Amina Flow
- Ore Pulp Flow
- Ore Pulp pH
- Ore Pulp Density
- Flotation Column Air Flow
- Flotation Column Levels
- Date & Time

### Target

- **% Silica Concentrate**

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Project Workflow

```
Load Dataset
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Hyperparameter Tuning
      ↓
Model Evaluation
      ↓
Future Prediction
      ↓
Model Deployment
```

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

The best-performing model was selected based on evaluation metrics.

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R² Score

---

## 📁 Project Structure

```
Quality-Prediction-in-a-Mining-Process/
│
├── Dataset/
│   └── MiningProcess_Flotation_Plant_Database.csv
│
├── Notebook/
│   └── Quality_Prediction.ipynb
│
├── Models/
│   └── random_forest_model.pkl
│
├── Images/
│   ├── High_Level_Diagram.png
│   ├── Low_Level_Diagram.png
│   └── Graphs/
│
├── Report/
│   └── Internship_Report.pdf
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Features

- Industrial dataset analysis
- Complete EDA
- Feature Engineering
- Multiple ML models
- Hyperparameter Tuning
- Feature Importance Analysis
- Future Prediction
- Model Serialization (.pkl)
- Deployment Ready

---

## 🔮 Future Scope

- Real-time prediction using live sensor data
- Integration with Industrial IoT (IIoT)
- Web dashboard deployment
- Cloud deployment
- Advanced models such as XGBoost and LSTM
- Predictive maintenance and anomaly detection

---

## 📷 Project Output

- Data Analysis
- Correlation Heatmap
- Model Comparison
- Feature Importance
- Prediction Results
- Future Prediction
- Saved Machine Learning Model

---

## 📚 References

- Kaggle Mining Process Dataset
- Scikit-learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation

---

## 👨‍💻 Author

**Priya Ranjan Dash**

B.Tech Student  
Institute of Technical Education and Research (ITER)  
Siksha 'O' Anusandhan (SOA) University

---

## ⭐ Acknowledgement

This project was completed as part of an Industrial Internship organized by:

- upskill Campus
- The IoT Academy
- UniConverge Technologies Pvt. Ltd.

---

## 📜 License

This project is intended for educational and learning purposes.

