# CreditWise Loan Approval System

A Machine Learning classification project that predicts whether a loan application is likely to be approved based on an applicant's financial, personal, and credit-related information.

---

## Project Overview

The objective of this project is to build a classification model that can predict loan approval status using historical applicant data. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature encoding, model training, and performance evaluation.

Three different machine learning algorithms were implemented and compared to identify the best-performing model.

---

## Features Used

The dataset contains the following features:

* Applicant Income
* Coapplicant Income
* Employment Status
* Age
* Marital Status
* Dependents
* Credit Score
* Existing Loans
* Debt-to-Income (DTI) Ratio
* Savings
* Collateral Value
* Loan Amount
* Loan Term
* Loan Purpose
* Property Area
* Education Level
* Gender
* Employer Category

**Target Variable**

* Loan Approved (Yes / No)

---

## Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Data Exploration (EDA)
4. Handle Missing Values
5. Encode Categorical Features
6. Split Dataset into Training and Testing Sets
7. Train Multiple Machine Learning Models
8. Evaluate Model Performance
9. Compare Algorithms
10. Predict Loan Approval

---

## Machine Learning Algorithms Used

* K-Nearest Neighbors (KNN)
* Logistic Regression
* Gaussian Naive Bayes

---

## Model Performance

| Model                     |  Accuracy | Precision |    Recall |  F1-Score |
| ------------------------- | --------: | --------: | --------: | --------: |
| K-Nearest Neighbors (KNN) |     75.5% |     62.0% |     50.8% |     55.9% |
| Logistic Regression       | **87.5%** | **79.0%** | **80.3%** | **79.7%** |
| Gaussian Naive Bayes      |     86.5% |     78.3% |     77.0% |     77.7% |

---

## Best Model

Among all three models, **Logistic Regression** achieved the highest overall performance with:

* Accuracy: **87.5%**
* Precision: **79.0%**
* Recall: **80.3%**
* F1-Score: **79.7%**

Based on these evaluation metrics, Logistic Regression was selected as the best-performing model for this dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text
CreditWise-Loan-Approval-System/
│
├── CreditWise_Loan_System.ipynb
├── loan_approval_data.csv
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Imtkhere/CreditWise-Loan-Approval-System.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
CreditWise_Loan_System.ipynb
```

---

## Future Improvements

* Hyperparameter tuning
* Feature selection
* Cross-validation
* Random Forest and XGBoost implementation
* Streamlit web application for real-time prediction

---

## Author

**Tarun Kumar**

BCA (Hons.) – Artificial Intelligence & Machine Learning

GitHub: https://github.com/Imtkhere

---

## License

This project is created for educational and portfolio purposes.
