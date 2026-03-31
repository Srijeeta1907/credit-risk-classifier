# 🏦 Loan Approval Prediction Pipeline

## 📌 Project Overview
Loan Approval Prediction poses a critical challenge in the fintech sector. This project applies Machine Learning to analyze credit history data and applicant demographics to construct an intelligent system capable of making informed decisions about loan approvals. 

By analyzing factors such as financial history, income, credit rating, and employment status, this model helps automate and optimize the lending decision process.

## 🚀 Key Features
* **Robust Data Preprocessing:** Handles missing values (median imputation for numerical, mode for categorical) and encodes categorical text data into machine-readable formats.
* **Optimized Machine Learning Model:** Utilizes a `RandomForestClassifier` with hyperparameters tuned via `GridSearchCV` to maximize predictive accuracy.
* **Production-Ready Export:** The trained model and data encoders are exported as `.pkl` files, allowing the model to make predictions on new data without needing to be retrained.
* **Custom Applicant Testing:** Includes a script to feed hypothetical applicant data into the model to simulate real-world API requests.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest, Grid Search, Label Encoding)
* **Model Serialization:** Joblib
* **Data Visualization:** Matplotlib, Seaborn

## 📊 Model Performance
The model was evaluated on a testing split of the dataset and achieved the following results:
* **Overall Accuracy:** 78.86%
* **Precision (Approved Loans):** High confidence in identifying safe loans.
* **Recall:** Successfully captures the vast majority of qualified applicants.

*(Note: Credit History was identified as the most heavily weighted feature in determining approval status).*

## 💻 How to Run Locally

**1. Clone the repository**
```bash
git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
cd your-repo-name
