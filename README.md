
# Credit Scoring and Risk Prediction System using Machine Learning

##  Project Overview

This project was developed as part of the CodeAlpha Machine Learning Internship Program. The objective is to build a Credit Scoring Model that predicts customer credit risk based on demographic, financial, and credit history data.

The model helps financial institutions evaluate customer creditworthiness and support data-driven lending decisions.

---

##  Objectives

* Predict customer credit risk using Machine Learning.
* Perform data preprocessing and feature engineering.
* Train a classification model for credit scoring.
* Evaluate model performance using standard metrics.
* Identify important features influencing credit decisions.

---

##  Dataset

The project uses two datasets:

### application_record.csv

Contains customer demographic and financial information.

### credit_record.csv

Contains customer credit history and payment records.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

##  Machine Learning Workflow

### 1. Data Collection

Loaded customer application and credit history datasets.

### 2. Data Preprocessing

* Handled missing values
* Merged datasets
* Encoded categorical variables

### 3. Feature Engineering

Created additional features:

* Age in Years
* Employment Years

### 4. Model Training

Implemented Random Forest Classifier for credit risk prediction.

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## Results

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 88.66% |
| Precision | 91.14% |
| Recall    | 96.45% |
| F1 Score  | 93.72% |
| ROC-AUC   | 76.82% |

---

##  Key Features

The most important features influencing predictions include:

* Age
* Annual Income
* Employment Duration
* Occupation Type
* Family Status
* Education Level

---

## Model Output

The trained model is saved as:

```text
credit_scoring_model.pkl
```

---

##  Project Structure

```text
CodeAlpha_CreditScoringModel/
│
├── application_record.csv
├── credit_record.csv
├── CodeAlpha_Credit_Scoring_Model.ipynb
├── credit_scoring_model.pkl
├── README.md
```

---

##  Internship Information

**Internship Program:** CodeAlpha Machine Learning Internship

**Task:** Credit Scoring Model

---

##  Conclusion

This project successfully developed a Machine Learning-based Credit Scoring System capable of predicting customer credit risk using financial and demographic information. The Random Forest model achieved strong performance and demonstrated the practical application of Machine Learning in credit risk assessment and financial decision-making systems.

---

###  If you found this project useful, consider giving it a star.
