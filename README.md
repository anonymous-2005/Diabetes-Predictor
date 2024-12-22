# Diabetes Prediction Using Machine Learning

## Overview
This project uses a machine learning model to predict whether a person is diabetic based on specific health parameters. The dataset utilized contains features such as glucose levels, blood pressure, BMI, and other metrics.

---

## Features
- Data preprocessing using `StandardScaler` to standardize the feature set.
- Model training and testing using Support Vector Machine (SVM) with a linear kernel.
- Predicting outcomes for new input data.

---

## Requirements

### Libraries
- `numpy`
- `pandas`
- `scikit-learn`

Install the required libraries using:
```bash
pip install numpy pandas scikit-learn
```

### Dataset
The project uses the `diabetes.csv` dataset, which contains the following columns:
- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`
- `Outcome` (Target variable: 0 for non-diabetic, 1 for diabetic)

---

## Usage

1. **Load the Dataset**
   The dataset should be placed in the specified path: `E:\python only\diabetes.csv`.

2. **Preprocess the Data**
   - Standardize the feature set using `StandardScaler`.
   - Separate the features (X) and target variable (Y).

3. **Train-Test Split**
   - Split the data into training and testing sets with an 80:20 ratio.
   - Use stratified sampling to maintain class distribution.

4. **Train the Model**
   - Use the Support Vector Machine (SVM) algorithm with a linear kernel to train the model.

5. **Evaluate the Model**
   - Calculate accuracy scores for training and testing datasets.

6. **Make Predictions**
   - Standardize new input data.
   - Predict the outcome and classify whether the person is diabetic or not.

---

## Example Input
```python
input_data = (5,166,72,19,175,25.8,0.587,51)
```

**Predicted Output**
- The person is diabetic.

---

## Accuracy
- Training Data Accuracy: **78.91%**
- Testing Data Accuracy: **77.92%**

---

## Directory Structure
```
DiabetesPrediction/
├── diabetes.csv            # Dataset
├── diabetes_prediction.py  # Main Python script
```

---

## Contact
For further questions or improvements, feel free to reach out:
- **Email**: developer@example.com

---

## License
This project is licensed under the MIT License.

