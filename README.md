# 🏥 Health Insurance Premium Prediction

## Project Overview

This project predicts health insurance charges using machine learning techniques. It includes data preprocessing, exploratory data analysis, feature engineering, model training, performance evaluation, and comparison of multiple regression models to identify the most accurate predictor.

---

## Dataset

- **Dataset:** Medical Cost Personal Dataset
- **Target Variable:** `charges`
- **Features:** Age, Sex, BMI, Children, Smoker Status, Region

---

## Project Workflow

- Imported required libraries
- Performed data understanding and exploration
- Checked for missing values and duplicates
- Conducted exploratory data analysis (EDA)
- Encoded categorical variables
- Split the data into training and testing sets
- Built and evaluated multiple machine learning models
- Compared model performance
- Analyzed feature importance
- Saved the best-performing model

---

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## Results

| Model | MAE | RMSE | R² Score |
|-------|------:|------:|------:|
| Linear Regression | 4181.19 | 5796.28 | 0.7836 |
| Decision Tree | 3384.47 | 6861.24 | 0.6968 |
| Random Forest | **2544.64** | **4573.55** | **0.8653** |

**Best Model:** Random Forest Regressor

---

## Visualizations

### Actual vs Predicted Charges

![Actual vs Predicted](images/actual_vs_predicted.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

---

## Project Structure

```
health_insurance_premium_prediction/
│
├── data/
│   └── insurance.csv
│
├── images/
│   ├── actual_vs_predicted.png
│   └── feature_importance.png
│
├── models/
│   └── random_forest_model.pkl
│
├── notebooks/
│   └── insurance_analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## How to Run

1. Clone the repository.
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   notebooks/insurance_analysis.ipynb
   ```
4. Run all cells to reproduce the analysis and results.

---

## Future Improvements

- Perform hyperparameter tuning for improved accuracy.
- Experiment with advanced ensemble models such as XGBoost and LightGBM.
- Deploy the model as a web application using Streamlit or Flask.

---

## Author

**Varnika Attri**