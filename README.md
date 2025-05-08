# 🌫️ Air Quality Prediction using Machine Learning

This project predicts the Air Quality Index (AQI) based on pollutant concentration data using a Random Forest Regression model. It uses the `city_day.csv` dataset containing air pollution measurements across various Indian cities.

---

## 📂 Dataset

- File: `city_day.csv`
- Source: Central Pollution Control Board (CPCB) via Kaggle (or local)
- Features:
  - PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene
  - Target: AQI

---

## 📊 Project Workflow

1. Upload `city_day.csv` file
2. Load and clean the dataset (handle missing values)
3. Select relevant pollutant columns as features
4. Split data into training and testing sets
5. Train a Random Forest Regressor
6. Evaluate performance using:
   - Mean Absolute Error (MAE)
   - R² Score
7. Visualize feature importance

---

## 🚀 How to Run in Google Colab

1. Go to [Google Colab](https://colab.research.google.com/)
2. Create a new notebook
3. Install required libraries (if not already installed)

    ```python
    !pip install pandas scikit-learn matplotlib seaborn
    ```

4. Upload your dataset:

    ```python
    from google.colab import files
    uploaded = files.upload()
    ```

5. Copy and run the main Python code (from `air_quality_prediction.ipynb` or provided code block)

---

## 📊 Sample Output

- Mean Absolute Error: Displayed in console
- R² Score: Displayed in console
- Feature Importance Chart: Visual bar plot of pollutant contribution to AQI

---

## 📦 Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## 📌 Future Improvements

- Predict AQI category (`AQI_Bucket`) using Classification models
- Use advanced models like XGBoost or LightGBM
- Handle missing data with advanced imputation techniques
- Deploy model as a web app using Streamlit or Flask

---

## 📜 License

This project is for educational and research purposes only.

---

## ✨ Author

Dharunya V  
[GitHub Profile](https://github.com/dharunya-1111)

