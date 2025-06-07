
# 🛠️ Turbofan Engine RUL Predictor

This project uses machine learning to predict the **Remaining Useful Life (RUL)** of aircraft engines using the NASA C-MAPSS dataset. It's a part of a predictive maintenance initiative to estimate how many cycles an engine can run before failure, helping reduce unplanned downtime and improve maintenance planning.

## 📂 Dataset

- **Source:** NASA C-MAPSS (Prognostics Center of Excellence)
- **Data:** Time-series sensor readings from turbofan engines over multiple operational cycles
- **Target:** Predict RUL for each engine unit
- [Dataset Link](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository)

## 🧠 Techniques Used

- Data preprocessing (normalization, sequence generation)
- Feature engineering
- Machine Learning Models:
  - Linear Regression
  - Random Forest
  - Gradient Boosting
- Evaluation metrics: RMSE, MAE

## 📈 Results

Achieved promising results using tree-based models, with lower RMSE and better generalization on test data compared to linear methods. The model can predict RUL from real-time sensor input sequences.

## 🛠️ Requirements

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  

## 📌 TODO / Future Work

- Try LSTM models for sequence-based prediction  
- Add hyperparameter tuning  
- Develop a web-based UI for prediction

## 👨‍💻 Author

Akshit Sachdeva  
B.Tech Data Science, Manipal Institute of Technology
