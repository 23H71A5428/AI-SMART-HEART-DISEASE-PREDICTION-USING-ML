# AI-SMART-HEART-DISEASE-PREDICTION-USING-ML
# ❤️ Heart Failure Prediction Using Machine Learning

## 📌 Project Overview

This project predicts the risk of **heart failure** using Machine Learning techniques. The model is trained on clinical patient data and compares the performance of two powerful classification algorithms:

- 🌳 Random Forest Classifier
- 🚀 XGBoost Classifier

The objective is to build an accurate prediction model that can assist in the early detection of heart failure based on patient health records.

---

## 📂 Dataset

**Dataset Name:** `heart_failure_clinical_records_dataset.csv`

The dataset contains clinical records of patients with various health parameters.

### Features

| Feature | Description |
|---------|-------------|
| age | Age of the patient |
| anaemia | Decrease of red blood cells or hemoglobin |
| creatinine_phosphokinase | CPK enzyme level in blood |
| diabetes | Whether the patient has diabetes |
| ejection_fraction | Percentage of blood leaving the heart at each contraction |
| high_blood_pressure | Whether the patient has hypertension |
| platelets | Platelet count in blood |
| serum_creatinine | Level of serum creatinine |
| serum_sodium | Level of serum sodium |
| sex | Gender of the patient |
| smoking | Smoking status |
| time | Follow-up period |
| DEATH_EVENT | Target variable (0 = Survived, 1 = Death) |

---

## 🎯 Project Objectives

- Perform data preprocessing and cleaning.
- Train Machine Learning models for heart failure prediction.
- Compare Random Forest and XGBoost performance.
- Evaluate models using various performance metrics.
- Visualize model performance with Confusion Matrix and ROC Curve.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib

---

## 📁 Project Structure

```
Heart-Failure-Prediction/
│
├── heart_failure_clinical_records_dataset.csv
├── Heart_Failure_Prediction.ipynb
├── model.pkl
├── README.md
└── requirements.txt
```

---

## ⚙️ Workflow

### 1. Data Collection

- Load the clinical records dataset.

### 2. Data Preprocessing

- Check for missing values
- Data exploration
- Feature selection
- Train-Test Split
- Feature Scaling (if required)

### 3. Model Training

Two Machine Learning models were implemented:

- Random Forest Classifier
- XGBoost Classifier

### 4. Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

---

## 📊 Evaluation Metrics

The following metrics were used to compare the models:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

Visualization:

- Confusion Matrix
- ROC Curve

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/Heart-Failure-Prediction.git
```

### Navigate to Project

```bash
cd Heart-Failure-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```
Heart_Failure_Prediction.ipynb
```

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
scikit-learn
xgboost
joblib
```

Install manually:

```bash
pip install numpy pandas matplotlib scikit-learn xgboost joblib
```

---

## 📈 Machine Learning Models

### Random Forest

- Ensemble learning algorithm
- Handles non-linear relationships
- Reduces overfitting
- High prediction accuracy

### XGBoost

- Gradient Boosting algorithm
- Faster training
- Better optimization
- High predictive performance

---

## 📌 Results

The project compares Random Forest and XGBoost based on:

- Prediction Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

The best-performing model can be saved and reused for future predictions.

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Web application using Flask or Streamlit
- Explainable AI using SHAP values
- Deployment on cloud platforms

---

## 🤝 Contribution

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📄 License

This project is developed for educational and research purposes.

---

## 👩‍💻 Author

**Kandela Navya**

Final Year Engineering Student

Machine Learning | Data Science | Python
