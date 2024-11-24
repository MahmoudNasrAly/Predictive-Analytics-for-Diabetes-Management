# Predictive-Analytics-for-Diabetes-Management
Predictive-Analytics-for-Diabetes-Management
# Diabetes Prediction Model 🎯

A machine learning project to predict diabetes based on diagnostic features using the Pima Indians Diabetes Dataset.

## Dataset 📊
The dataset contains diagnostic measurements to predict diabetes:
- **Source**: Pima Indians Diabetes Dataset.
- **Target Variable**: `Outcome` (0 = No Diabetes, 1 = Diabetes).
- Features include:
  - `Pregnancies`: Number of pregnancies.
  - `Glucose`: Plasma glucose concentration.
  - `BloodPressure`: Diastolic blood pressure (mm Hg).
  - `SkinThickness`: Triceps skinfold thickness (mm).
  - `Insulin`: 2-Hour serum insulin (mu U/ml).
  - `BMI`: Body mass index (weight in kg/(height in m)^2).
  - `DiabetesPedigreeFunction`: Diabetes pedigree function.
  - `Age`: Age (years).

## Project Structure 🗂️

## Features ⚙️
- Handles class imbalance using **SMOTE**.
- Implements Logistic Regression with `class_weight='balanced'`.
- Evaluates model performance using confusion matrix, classification report, and AUC-ROC curve.

## Requirements 🛠️
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
```

Key Results 📈
Achieves balanced performance across metrics like Precision, Recall, and F1-score.
Classifies individuals into diabetic or non-diabetic categories.
Contributing 🤝
Feel free to contribute by opening issues or submitting pull requests. Suggestions for improvements are always welcome!

License 📜
This project is licensed under the MIT License.

