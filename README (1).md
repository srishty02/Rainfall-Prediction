
# Rainfall Prediction Using Machine Learning

This project aims to predict monthly rainfall using machine learning techniques based on historical rainfall data across various Indian states. The objective is to build a model that can assist in agricultural planning, water resource management, and climate-related decision-making.

## 🌧️ Problem Statement

Rainfall prediction is crucial for sectors such as agriculture, irrigation, and disaster preparedness. This project explores data-driven machine learning models to forecast rainfall levels based on historical meteorological data.

---

## 📁 Dataset

- **File**: `Rainfall.csv`
- **Source**: Indian Meteorological Department (assumed)
- **Attributes**:
  - `SUBDIVISION`: Indian state/subdivision name
  - Monthly rainfall columns: `JAN` through `DEC`
  - `ANNUAL`: Annual rainfall in mm

---

## 🧠 Machine Learning Workflow

### 1. **Data Preprocessing**
- Loaded the dataset using `pandas`
- Handled missing values using mean imputation
- Selected relevant features: Monthly rainfall columns as input, `ANNUAL` as target

### 2. **Exploratory Data Analysis (EDA)**
- Visualized rainfall patterns with heatmaps and box plots
- Checked correlation between monthly rainfall and annual rainfall

### 3. **Model Building**
- Models used:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
- Evaluated using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

### 4. **Model Comparison**
- Random Forest Regressor showed the best performance in terms of R² and error metrics.

---

## 📊 Results

| Model                 | MAE       | MSE       | R² Score |
|----------------------|-----------|-----------|----------|
| Linear Regression     | ~X.XX mm  | ~XX.XX mm²| ~0.85    |
| Decision Tree         | ~X.XX mm  | ~XX.XX mm²| ~0.88    |
| Random Forest         | ~X.XX mm  | ~XX.XX mm²| ~0.92 ✅ |

*(Exact values can be updated based on final outputs)*

---

## 💻 Tech Stack

- **Programming Language**: Python
- **Libraries**: 
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for ML models and evaluation

---

## 📂 How to Run

1. Clone the repository or download the notebook.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook Rainfall_Prediction_using_Machine_Learning.ipynb
   ```

---

## 🚀 Future Enhancements

- Integrate other features such as temperature, humidity, and wind speed
- Use deep learning models like LSTM for time-series forecasting
- Deploy as a web application for user interaction

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## ✍️ Author

- **Shivam Jaiswal**
